---
TOCTitle: Microsoft ISA Server を使用した POP および IMAP サービスの公開
Title: Microsoft ISA Server を使用した POP および IMAP サービスの公開
ms:assetid: 'ca60edf3-41dc-44e6-b877-a90800c59618'
ms:contentKeyID: 19869633
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc768081(v=TechNet.10)'
---

Microsoft ISA Server を使用した POP および IMAP サービスの公開
==============================================================

最終更新日: 2003年7月7日

**Microsoft ISA 2000 Server Feature Pack 1 バージョン 1**

ファイアウォールを使用した Microsoft Exchange Server サービス (POP3、IMAP4、SMTP) の公開は、ISA Server の \[ISA メールサーバーを安全に公開するためのウィザード\] で簡単に構成できます。このマニュアルでは、次の構成を行うための手順を説明します。

-   ISA Server コンピュータ上の Exchange 2000 Server の公開

-   
-   ISA Server コンピュータの背後の Exchange 2000 Server の公開

-   

##### トピック

[](#egaa)[作業を始める前に](#egaa)

[](#efaa)[シナリオ 1 : ISA Server コンピュータ上の Exchange Server の公開](#efaa)

[](#eeaa)[手順](#eeaa)

[](#edaa)[シナリオ 2 : ISA Server コンピュータの背後の Exchange Server の公開](#edaa)

[](#ecaa)[手順](#ecaa)

[](#ebaa)[要約](#ebaa)

[](#eaaa)[その他のリソース](#eaaa)

### 作業を始める前に

作業を始める前に、次の情報を収集します。

-   ISA Server コンピュータの内部および外部 IP アドレス

-   
-   Exchange Server の内部 IP アドレス

-   
-   公開されたメールサーバーの外部 DNS メール交換 (MX) およびホスト (A) レコード

-   
-   ISA Server により公開される必要があるプロトコル

-   

[](#mainsection)[ページのトップへ](#mainsection)

### シナリオ 1 : ISA Server コンピュータ上の Exchange Server の公開

Exchange Server が ISA Server と同じコンピュータにインストールされている場合、\[ISA メールサーバーを安全に公開するためのウィザード\] により、選択したすべてのメールサービスに対する IP パケットフィルタが作成されます。このプロセスは、Exchange Server が別のサーバーにインストールされている場合は異なります。

![](images/Cc768081.ppopi01(ja-jp,TechNet.10).gif)

[](#mainsection)[ページのトップへ](#mainsection)

### 手順

このシナリオを構成するには、次の手順を実行します。各手順については、この後に詳しく説明します。

1.  DNS 名の解決を構成する

2.  3.  クライアントを構成する

4.  5.  \[ISA メールサーバーを安全に公開するためのウィザード\] を実行する

6.  7.  ウィザードの設定を確認する

8.  9.  クライアントアドレスセットを作成する

10. 11. プロトコルルールを作成する

12. 

**手順 1. DNS 名の解決を構成する**

実際に \[ISA メールサーバーを安全に公開するためのウィザード\] を実行する前に、名前の解決を構成する必要があります。次の条件を満たしていることを確認します。

-   Network Solutions に登録された nwtraders.com など、登録済みのドメインがあることを確認します。

-   
-   ISP または適切なベンダから割り当てられたパブリック IP アドレスが ISA Server コンピュータの外部ネットワークアダプタに割り当てられていることを確認します。

-   
-   メール交換 (MX) およびホスト (A) レコードが定義されており、ISA Server コンピュータで割り当てられているパブリック外部 IP に適切にマップされていることを確認します (外部 DNS をホストしていない場合は、ISP に問い合わせてください)。

-   
-   たとえば、mail.nwtraders.com に対する ping が適切な外部 IP アドレスに解決されるなど、外部ドメインが正しい IP アドレスに解決されることを確認します。

-   
-   メールクライアントにより使用される DNS 名が、ISA Server コンピュータの外部 IP アドレスにマップされることを確認します。この手順は、Exchange サービスを公開するときに、POP3、IMAP4、および HTTP クライアントにより FQDN が適切に解決されるようにするために必要です。

-   

**手順 2. クライアントを構成する**

Exchange Server を SecureNAT クライアントとして構成することをお勧めします。

**手順 3. \[ISA メールサーバーを安全に公開するためのウィザード\] を実行する**

1.  \[ISA の管理\] を開きます。

2.  3.  エンタープライズインストールの場合は、\[エンタープライズ\] ツリーを展開し、目的のエンタープライズポリシーを選択します。

    スタンドアロンインストールの場合は、\[サーバーとアレイ\]ツリーを展開し、目的のサーバーまたはアレイを展開します。

4.  5.  \[公開\] を展開し、\[サーバー公開ルール\] を右クリックして、\[メールサーバーの保護\] をクリックします。

6.  7.  \[メールサーバーのセキュリティウィザードの開始\] ページで \[次へ\] をクリックします。

8.  9.  \[メールサービスの選択\] ページで次のチェックボックスをオンにします。

    -   \[受信 SMTP\]

    -   
    -   \[送信 SMTP\]

    -   
    -   \[受信 POP3\]

    -   
    -   \[受信 IMAP4\]

        **注意** SMTP アプリケーションフィルタがインストールされ有効になっている場合は、\[コンテンツフィルタを適用する\] チェックボックスをオンにできます。

        目的のチェックボックスをオンにし、特定のプロトコルに対して SSL 認証を構成することもできます。

    -   

10. 11. ISA Server コンピュータの \[外部 IP アドレス\] ページで、ISA Server コンピュータの外部 IP アドレスを入力して、\[次へ\] をクリックします。

12. 13. \[内部メールサーバー\] ページで、\[ローカルホスト\]、\[次へ\] の順にクリックします。

14. 15. \[Firewall サービスを再起動する\] チェックボックスがオンになっていることを確認し、\[完了\] をクリックしてウィザードを終了します。

16. 17. パケットフィルタが正しく作成されていることを確認するために、\[アクセスポリシー\] を展開し、\[IP パケットフィルタ\] をクリックして、詳細ペインにカスタムフィルタが表示されていることを確認します。

18. 

**手順 4. ウィザードの設定を確認する**

\[ISA メールサーバーを安全に公開するためのウィザード\] を使用しなくても、Exchange Server を簡単に公開できます。ISA Server コンピュータに Exchange をインストールするときに必要なパケットフィルタを作成するには、次の表の情報を参照してください。

次の表に示すように、\[ISA メールサーバーを安全に公開するためのウィザード\] で作成される既定のパケットフィルタでは、ユーザーがメールを外部ドメインに送ろうとしたときにメール交換の参照を可能にするための追加の送信パケットフィルタが含まれる SMTP 以外では、メールサーバーへの受信トラフィックのみが許可されます。

<table style="width:100%;">
<colgroup>
<col width="11%" />
<col width="11%" />
<col width="11%" />
<col width="11%" />
<col width="11%" />
<col width="11%" />
<col width="11%" />
<col width="11%" />
<col width="11%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >プロトコル</th>
<th style="border:1px solid black;" >定義済みカスタム</th>
<th style="border:1px solid black;" >IP プロトコル</th>
<th style="border:1px solid black;" >プロトコル番号</th>
<th style="border:1px solid black;" >方向</th>
<th style="border:1px solid black;" >ローカルポート</th>
<th style="border:1px solid black;" >ローカルポート番号</th>
<th style="border:1px solid black;" >リモートポート</th>
<th style="border:1px solid black;" >リモートポート番号</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">IMAP (受信)</td>
<td style="border:1px solid black;">カスタム</td>
<td style="border:1px solid black;">TCP</td>
<td style="border:1px solid black;">6</td>
<td style="border:1px solid black;">着信</td>
<td style="border:1px solid black;">固定</td>
<td style="border:1px solid black;">143</td>
<td style="border:1px solid black;">すべてのポート</td>
<td style="border:1px solid black;">N/A</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">POP3 (受信)</td>
<td style="border:1px solid black;">カスタム</td>
<td style="border:1px solid black;">TCP</td>
<td style="border:1px solid black;">6</td>
<td style="border:1px solid black;">着信</td>
<td style="border:1px solid black;">固定</td>
<td style="border:1px solid black;">110</td>
<td style="border:1px solid black;">すべてのポート</td>
<td style="border:1px solid black;">N/A</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SMTP (受信)</td>
<td style="border:1px solid black;">カスタム</td>
<td style="border:1px solid black;">TCP</td>
<td style="border:1px solid black;">6</td>
<td style="border:1px solid black;">着信</td>
<td style="border:1px solid black;">固定</td>
<td style="border:1px solid black;">25</td>
<td style="border:1px solid black;">すべてのポート</td>
<td style="border:1px solid black;">N/A</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SMTP (送信)</td>
<td style="border:1px solid black;">カスタム</td>
<td style="border:1px solid black;">TCP</td>
<td style="border:1px solid black;">6</td>
<td style="border:1px solid black;">着信</td>
<td style="border:1px solid black;">すべてのポート</td>
<td style="border:1px solid black;">N/A</td>
<td style="border:1px solid black;">固定ポート</td>
<td style="border:1px solid black;">25</td>
</tr>
</tbody>
</table>
  
**手順 5. クライアントアドレスセットを構成する**
  
クライアントアドレスセットは、社内ネットワークの SMTP および内部DNSサーバーへの送信 SMTP および DNS トラフィックを制限するために必要です。クライアントアドレスセットを構成するには、SMTP サーバーと DNS サーバーの IP アドレスが必要です。
  
**SMTP サーバーのクライアントアドレスセットを作成するには**
  
1.  \[ISA の管理\] を開きます。
  
2.  3.  エンタープライズインストールの場合は、\[エンタープライズ\] ツリーを展開し、目的のエンタープライズポリシーを選択します。
  
    スタンドアロンインストールの場合は、\[サーバーとアレイ\] ツリーを展開し、目的のサーバーまたはアレイを展開します。
  
4.  5.  \[ポリシーの要素\] を展開し、\[クライアントアドレスセット\] を右クリックして、\[新規作成\]、\[セット\] の順にクリックします。
  
6.  7.  SMTP サーバーの名前と IP アドレスを入力して、\[OK\] をクリックします。
  
8.  
  
**DNS サーバーのクライアントアドレスセットを作成するには**
  
1.  \[ISA の管理\] を開きます。
  
2.  3.  エンタープライズインストールの場合は、\[エンタープライズ\] ツリーを展開し、目的のエンタープライズポリシーを選択します。
  
    スタンドアロンインストールの場合は、\[サーバーとアレイ\] ツリーを展開し、目的のサーバーまたはアレイを展開します。
  
4.  5.  \[ポリシーの要素\] を展開し、\[クライアントアドレスセット\] を右クリックして、\[新規作成\]、\[セット\] の順にクリックします。
  
6.  7.  DNS サーバーの名前と IP アドレスを入力して、\[OK\] をクリックします。
  
8.  
  
**手順 6. プロトコルルールを作成する**
  
プロトコルルールは、メールが効率的にルーティングされるように、SMTP および DNS トラフィックの両方に対して発信方向のアクセスをサポートするために必要です。次のプロトコルルールを作成しないと、メールドメイン名を含む完全修飾ドメイン名を解決できないので、内部の、公開されている Exchange Server からメールを送信できません。
  
**SMTP サーバーのプロトコルルールを作成するには**
  
1.  \[ISA の管理\] を開きます。
  
2.  3.  エンタープライズインストールの場合は、\[エンタープライズ\] ツリーを展開し、目的のエンタープライズポリシーを選択します。
  
    スタンドアロンインストールの場合は、\[サーバーとアレイ\] ツリーを展開し、目的のサーバーまたはアレイを展開します。
  
4.  5.  \[アクセスポリシー\] を展開し、\[プロトコルルール\] を右クリックして、\[新規作成\]、\[ルール\] の順にクリックします。
  
6.  7.  ルールに名前を付けて、\[次へ\] をクリックします。
  
8.  9.  \[ルールの動作\] で、\[許可する\]、\[次へ\] の順にクリックします。
  
10. 11. \[プロトコル\] ページで、下方向キーを押して \[選択されたプロトコル\] をクリックします。一覧を下にスクロールし、\[SMTP\] チェックボックスをオンにして、\[次へ\] をクリックします。
  
12. 13. \[スケジュール\] を \[常時\] に設定し、\[次へ\] をクリックします。
  
14. 15. クライアントの種類で \[特定のコンピュータ (クライアントアドレスセット)\] を選択し、SMTP サーバーのクライアントアドレスセットを使用します。
  
16. 17. 設定を確認して \[完了\] をクリックします。
  
18. 
  
**DNS サーバーのプロトコルルールを作成するには**
  
1.  \[ISA の管理\] を開きます。
  
2.  3.  エンタープライズインストールの場合は、\[エンタープライズ\] ツリーを展開し、目的のエンタープライズポリシーを選択します。
  
    スタンドアロンインストールの場合は、\[サーバーとアレイ\] ツリーを展開し、目的のサーバーまたはアレイを展開します。
  
4.  5.  \[アクセスポリシー\] を展開し、\[プロトコルルール\] を右クリックして、\[新規作成\]、\[ルール\] の順にクリックします。
  
6.  7.  ルールに名前を付けて、\[次へ\] をクリックします。
  
8.  9.  \[ルールの動作\] で \[許可する\] を選択し、\[次へ\] をクリックします。
  
10. 11. \[プロトコル\] ページで、下方向キーを押して \[選択されたプロトコル\] を選択します。一覧を下にスクロールして、\[DNS Query\] および \[DNS Zone Transfer\] のチェックボックスをオンにして、\[次へ\] をクリックします。
  
12. 13. \[スケジュール\] を \[常時\] に設定し、\[次へ\] をクリックします。
  
14. 15. クライアントの種類で \[特定のコンピュータ (クライアントアドレスセット)\] を選択し、DNS サーバーのクライアントアドレスセットを使用します。
  
16. 17. 設定を確認して \[完了\] をクリックします。
  
18. 
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### シナリオ 2 : ISA Server コンピュータの背後の Exchange Server の公開
  
この手順では、図に示すように、Microsoft Exchange Server コンピュータがローカルネットワークに配置され、ISA Server コンピュータにより保護されています。
  
内部 Exchange Server を公開する場合も、同様の手順に従います。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 手順
  
ISA Server コンピュータの背後の内部 Exchange Server を公開するには、\[ISA メールサーバーを安全に公開するためのウィザード\] を実行する前に以下が作成されていることを確認します。以下は、「シナリオ 1 : ISA Server コンピュータ上の Exchange Server の公開」で定義済みです。
  
1.  DNS の構成と解決
  
2.  3.  Exchange Server の ISA Server クライアントの種類の構成
  
4.  5.  クライアントアドレスセット
  
6.  7.  DNS および SMTP プロトコルルール
  
8.  
  
さらに、ここでの説明に従って \[ISA メールサーバーを安全に公開するためのウィザード\] を実行することをお勧めします。
  
**\[ISA メールサーバーを安全に公開するためのウィザード\] を実行する**
  
1.  \[ISA の管理\] を開きます。
  
2.  3.  エンタープライズインストールの場合は、\[エンタープライズ\] ツリーを展開し、目的のエンタープライズポリシーを選択します。
  
    スタンドアロンインストールの場合は、\[サーバーとアレイ\] ツリーを展開し、目的のサーバーまたはアレイを展開します。
  
4.  5.  \[公開\] を展開し、\[サーバー公開ルール\] を右クリックして、\[メールサーバーの保護\] をクリックします。
  
6.  7.  \[メールサーバーのセキュリティウィザードの開始\] ページで \[次へ\] をクリックします。
  
8.  9.  \[メールサービスの選択\] ページで次のチェックボックスをオンにします。
  
    -   \[受信 SMTP\]
  
    -     
    -   \[送信 SMTP\]
  
    -     
    -   \[受信 POP3\]
  
    -     
    -   \[受信 IMAP4\]
  
    -   
  
10. 11. ISA Server の \[外部 IP アドレス\] ページで、ISA Server コンピュータの外部 IP アドレスを入力して、\[次へ\] をクリックします。
  
12. 13. \[内部メールサーバー\] ページで、\[指定した IP アドレス\] をクリックし、Exchange Server の内部 IP アドレスを入力して、\[次へ\] をクリックします。
  
14. 15. 情報が正しいことを確認し、\[完了\] をクリックしてウィザードを終了します。
  
    **注意** サーバー公開ルールが正しく作成されていることを確認するために、\[公開\] を展開し、\[サーバー公開ルール\] をクリックして、詳細ペインに適切なプロトコルが表示されていることを確認します。さらに、\[アクセスポリシー\] を展開し、\[プロトコルルール\] をクリックして、発信方向のメールトラフィックを許可するために作成した新しい SMTP プロトコルルールが表示されていることを確認します。
  
16. 
  
ウィザードにより作成される新しいルールの名前にはすべて、メールウィザードルールというプレフィックスが付きます。
  
要約すると、\[ISA メールサーバーを安全に公開するためのウィザード\] では、次のアイテムが自動的に作成されます。
  
-   選択したプロトコル (POP3、IMAP4、SMTP 受信) に必要なサーバー公開ルール
  
-     
-   SMTP クライアントプロトコル (SMTP 送信) の単一のプロトコルルール
  
-     
-   内部 Exchange Server の IP アドレスを含むクライアントアドレスセット
  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 要約
  
ここでは、\[ISA メールサーバーを安全に公開するためのウィザード\] を使用してメールサーバーを公開するための重要事項を確認します。
  
-   DNS は、ネットワーク上に存在しなければなりません。
  
-     
-   DNS でフォワーダを使用してインターネットドメインを解決できなければなりません。
  
-     
-   DNS 構成、プロトコルルール、および SMTP 公開ルールを手動で確認します。
  
-     
-   名前解決に内部 DNS サーバーを使用するように SMTP サーバーを構成します。
  
-     
-   SMTP サーバーは、スマートホストをポイントするように構成することもできます。
  
-     
-   SMTP ポート 25 への送信アクセスのためのプロトコルルール
  
-     
-   送信 DNS クエリのためのプロトコルルール
  
-     
-   通常は UDP ポート 53 を使用し、クエリ全体が単一の UDP データグラムに適合しない場合は TCP ポート 53 を使用する DNS クエリ
  
-     
-   SMTP を ISA Server コンピュータで実行している場合、内部 SMTP サーバーと ISA Server コンピュータで SMTP サービスを無効にします。
  
-     
-   スマートホストを使用するように IIS SMTP が構成されている場合は、TCP および UDP ポート 53 の DNS クエリのプロトコルルールは不要です。
  
-     
-   ISA Server で SMTP、IIS、NNTP、およびその他のサービスを実行しないようにします。
  
-     
-   Wspcfg.ini ファイルを変更して、Exchange をファイアウォールクライアントとして構成することはできますが、この方法はお勧めしません。
  
-     
-   ファイアウォールクライアントは ISA Server コンピュータにインストールしないでください。
  
-     
-   サーバー公開ルールを使用して複数の内部 Exchange Server を公開するには、外部インターフェイスに複数の IP を追加するか、それぞれに IP がバインドされた複数の外部インターフェイスを追加する必要があります。サーバー公開ルールを使用する場合、外部 IP を特定のポート (たとえば、SMTP ポート 25) にバインドした後、同じポートを使用する他のサーバー公開ルールを構成できません。
  
-     
-   ISA Server はポートのリダイレクトを実行できないため、サーバー公開では、ISA Server コンピュータの外部ポートおよび内部サーバーのポート番号が同じである必要があります。
  
-     
-   \[ISA メールサーバーを安全に公開するためのウィザード\] により、必要なサーバー公開ルールとクライアントアドレスセットが作成されます。
  
-     
-   ISA Server では、公開されているサービスに一致しないすべてのパケットが破棄されます。
  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### その他のリソース
  
ここで説明した内容の他に、次のリソースの詳細情報も参照してください。
  
-   [303426](http://support.microsoft.com/kb/303426) ISA Server のサーバー公開ルールで \[送信 SMTP\] チェックボックスが使用できない
  
-     
-   [304948](http://support.microsoft.com/kb/304948) ISA Server 2000 のセキュリティで保護されたメール公開によって公開される RPC インターフェイス
  
-     
-   [280437](http://support.microsoft.com/kb/280437) Exchange 2000 Server の Exchange システムマネージャでパブリックフォルダを開けない
  
-     
-   [313139](http://support.microsoft.com/kb/313139) 最新の Internet Security and Acceleration Server 2000 Service Pack の入手方法
  
-     
-   [296614](http://support.microsoft.com/kb/296614) Exchange 2000 の Standard Edition と Enterprise Edition の相違点
  
-     
-   [263237](http://support.microsoft.com/kb/263237) Windows 2000 と Exchange 2000 の SMTP の DNS 問い合わせ
  
-     
-   [224196](http://support.microsoft.com/kb/224196) Restricting Active Directory Replication Traffic to a Specific Port (英語)
  
-     
-   246739 Exchange 2000 Server のフロントエンド/バックエンドの用語と実装
  
-     
-   [291662](http://support.microsoft.com/kb/291662) How to Publish Domain Name System Servers with Internet Security and Acceleration Server (英語)
  
-     
-   [269556](http://support.microsoft.com/kb/269556) DNS Queries Generated When Static Packet Filter Is Removed (英語)
  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
