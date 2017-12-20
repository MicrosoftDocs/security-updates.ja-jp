---
TOCTitle: ISA Server クライアントの種類
Title: ISA Server クライアントの種類
ms:assetid: 'daaa0e95-338b-466c-8118-9d0fdb3ecbfb'
ms:contentKeyID: 19869285
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc750616(v=TechNet.10)'
---

ISA Server クライアントの種類
=============================

最終更新日: 2003年7月4日

**Microsoft ISA Server 2000 Feature Pack 1 バージョン 1**

Microsoft Internet Security and Acceleration (ISA) Server では、以下の 3 つの種類のクライアントをサポートしています。

-   ファイアウォールクライアントは、ファイアウォールクライアントソフトウェアをインストールして有効にしたクライアントコンピュータです。

-   
-   セキュアネットワークアドレス変換 (SecureNAT) クライアントは、ファイアウォールクライアントがインストールされていないクライアントコンピュータです。

-   
-   Web Proxy クライアントは、ISA Server を使用するために構成されたあらゆるクライアント Web アプリケーションを指します。

-   

詳細については、後の「ファイアウォールクライアント」、「SecureNAT クライアント」、および「Web Proxy クライアント」を参照してください。

##### トピック

[](#ecaa)[ISA Server クライアントとドメインネームシステム](#ecaa)

[](#ebaa)[SecureNAT クライアント](#ebaa)

[](#eaaa)[Web Proxy クライアント](#eaaa)

次の表は、ISA Server クライアントの比較の一覧です。

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >機能</th>
<th style="border:1px solid black;" >SecureNAT クライアント</th>
<th style="border:1px solid black;" >ファイアウォール クライアント</th>
<th style="border:1px solid black;" >Web Proxy クライアント</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">インストールの必要性</td>
<td style="border:1px solid black;">いくつかのネットワーク構成の変更が必要です。</td>
<td style="border:1px solid black;">あり。</td>
<td style="border:1px solid black;">なし。Web ブラウザの構成が必要です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">オペレーティングシステムのサポート</td>
<td style="border:1px solid black;">Transmission Control Protocol/Internet Protocol (TCP/IP) をサポートするオペレーティングシステム。</td>
<td style="border:1px solid black;">Windows プラットフォームのみ。</td>
<td style="border:1px solid black;">すべてのプラットフォーム。ただし、Web アプリケーションを使用。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">プロトコルサポート</td>
<td style="border:1px solid black;">複数の接続プロトコル用アプリケーションフィルタが必要です。</td>
<td style="border:1px solid black;">すべての Winsock アプリケーション。</td>
<td style="border:1px solid black;">Hypertext Transfer Protocol (HTTP)、Secure HTTP (HTTPS)、File Transfer Protocol (FTP)、および Gopher。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ユーザーレベルの認証</td>
<td style="border:1px solid black;">いくつかのネットワーク構成の変更が必要です。</td>
<td style="border:1px solid black;">あり。</td>
<td style="border:1px solid black;">あり。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">サーバーアプリケーション</td>
<td style="border:1px solid black;">構成やインストールは必要ありません。</td>
<td style="border:1px solid black;">構成ファイルが必要です。</td>
<td style="border:1px solid black;">適用できません。</td>
</tr>
</tbody>
</table>
  
ファイアウォールクライアントコンピュータおよび SecureNAT クライアントコンピュータは、どちらも Web Proxy クライアントになることが可能です。コンピュータ上の Web アプリケーションが ISA Server を使用するように明示的に構成されている場合、HTTP、FTP、HTTPS、および Gopher などのすべての Web 要求は、直接 Web Proxy サービスに送信されます。他のすべての要求は、最初に Firewall サービスで処理されます。
  
### ISA Server クライアントとドメインネームシステム
  
DNS (ドメインネームシステム) の名前解決は、内部ネットワークでどの ISA クライアントを利用するかを選択するときに主に考慮すべき項目です。以下の表は、各 ISA クライアントで DNS 名前解決がどのように実行されるかを簡単に説明しています。

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >ISA Server クライアント</th>
<th style="border:1px solid black;" >名前解決方式</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SecureNAT クライアント</td>
<td style="border:1px solid black;">環境によって異なります。クライアントに内部 DNS サーバーを知らせるか、DNS クエリをクライアントから直接外部 DNS サーバーに渡すように ISA Server を構成する必要があります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Web Proxy クライアント</td>
<td style="border:1px solid black;">ISA Server Web Proxy サービスにより、単純な DNS 機能が提供されます。これは、ISA Server 自体の DNS 構成に基づきます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ファイアウォールクライアント</td>
<td style="border:1px solid black;">ISA Server Firewall サービスにより、単純な DNS 機能が提供されます。これは、ISA Server 自体の DNS 構成に基づきます。</td>
</tr>
</tbody>
</table>
  
#### ファイアウォールクライアント
  
ファイアウォールクライアントとは、ファイアウォールクライアントソフトウェアがインストールされ、有効になっているコンピュータです。ファイアウォールクライアントは、ISA Server の Firewall サービスを使用する Winsock アプリケーションを実行します。ファイアウォールクライアントが Winsock アプリケーションを使用して、あるコンピュータのオブジェクトを要求する場合、クライアントはローカルアドレステーブル (LAT) のコピーをチェックして、指定したコンピュータが LAT にあるかどうかを確認します。目的のコンピュータが LAT にない場合、要求は ISA Server Firewall サービスに送信されます。Firewall サービスは、要求を処理し、許可された適切な宛先に転送します。ファイアウォールクライアントソフトウェアは、認証に必要な Windows ユーザーの情報を ISA Server コンピュータに送信することができます。
  
ISA Server は、クライアントのセットアップ時に以下のコンポーネントをクライアント上にインストールします。
  
-   Mspclnt.ini、共有クライアント構成ファイルおよびローカルドメインテーブル
  
-     
-   Msplat.txt、共有クライアントローカルアドレステーブル
  
-     
-   ファイアウォールクライアントアプリケーション
  
-   
  
これらのコンポーネントの既定の設定は、インストール後変更することができます。新しい構成設定は、クライアント構成を更新した場合のみ有効になります。
  
詳細については、ISA Server のドキュメントの「ファイアウォールクライアントコンポーネント」を参照してください。
  
ファイアウォールクライアントのセットアップでは、個々の Winsock アプリケーションが構成されません。代わりにファイアウォールクライアントは、他のアプリケーションが使用する Winsock ダイナミックリンクライブラリ (.dll) を使用します。そのうえで、ファイアウォールクライアントは、アプリケーション呼び出しを受信し、要求を ISA Server コンピュータに転送するかどうかを決定します。詳細については、ISA Server のドキュメントの「ファイアウォールクライアントソフトウェアをインストールするには」を参照してください。
  
ファイアウォールクライアントソフトウェアは、Windows ME、Windows 95、Windows 98、Windows NT 4.0、または Windows 2000 を実行しているクライアントコンピュータにインストールできます。また、16 ビットの Winsock アプリケーションもサポートされていますが、Windows 2000 と Windows NT 4.0 の場合に限ります。
  
ファイアウォールクライアントはファイアウォールモードまたは統合モードではサポートされますが、キャッシュモードではサポートされません。モードの詳細については、ISA Server のドキュメントの「ISA Server モード」を参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### SecureNAT クライアント
  
ファイアウォールクライアントソフトウェアがインストールされていないクライアントコンピュータは、セキュアネットワークアドレス変換 (SecureNAT) クライアントです。SecureNAT クライアントは ISA Server のほとんどの機能を利用することができます。これには、上位レベルプロトコルのサポートとユーザーレベルの認証を除く、ほとんどのアクセス制御機能が含まれます。
  
SecureNAT クライアントに特別なソフトウェアは必要ありませんが、すべてのインターネットへのトラフィックが、ルーターを介して直接または間接的に、ISA Server を使用して送られるように、デフォルトゲートウェイを構成することをお勧めします。クライアントは、DHCP サービスを使用して構成することも、手動で構成することもできます。
  
SecureNAT クライアントからの要求は、基本的には Firewall サービスで処理されるため、SecureNAT クライアントは以下のセキュリティ機能を利用することができます。
  
-   アプリケーションフィルタは、プロトコルストリームを変更して、複雑なプロトコルの処理を可能にします。Windows 2000 NAT では、このメカニズムは、Windows 2000 でカーネルモード NAT エディタドライバとして記述されている NAT エディタを使用することで実現されています。
  
-     
-   Firewall サービスでは、すべての Hypertext Transfer Protocol (HTTP) 要求を Web Proxy サービスに渡すことができます。Web Proxy サービスではキャッシュが行われ、コンテンツルールが正しく適用されるようにします。
  
-   
  
#### SecureNAT および Windows 2000 NAT
  
ISA Server は、SecureNAT クライアントに ISA Server ポリシーを強制することで、Windows 2000 のネットワークアドレス変換 (NAT) 機能を拡張します。つまり、Windows 2000 NAT には固有の
  
認証メカニズムがないにもかかわらず、すべての ISA Server ルールを SecureNAT クライアントに適用することができます。また、プロトコル利用、宛先、コンテンツの種類に関するポリシーも SecureNAT クライアントに適用されます。
  
**SecureNAT クライアントとサーバーの公開**
  
SecureNAT クライアントは、ファイアウォールクライアントと同様、インターネットに情報を公開するメールサーバーなど、実際のサーバーにすることができます。サーバーを SecureNAT クライアントとして公開するためのサーバー公開ルールを構成します。さらに、サーバーを公開するためにサーバー公開ルールを使用する場合、ファイアウォールクライアントソフトウェアがサーバー公開に干渉する可能性があるので、サーバーとして SecureNAT クライアントを使用することをお勧めします。公開されたサーバーは SecureNAT クライアントであるため、ISA Server でサーバー公開ルールを作成すれば、公開サーバー専用の構成は必要ありません。ISA Server コンピュータは、公開サーバー上のデフォルトゲートウェイとして構成しなければならないことに注意してください。詳細については、ISA Server のドキュメントの「SecureNAT クライアントを構成する」を参照してください。
  
SecureNAT クライアントはファイアウォールモードまたは統合モードではサポートされますが、キャッシュモードではサポートされません。モードの詳細については、ISA Server のドキュメントの「ISA Server モード」を参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### Web Proxy クライアント
  
Web Proxy クライアントは、ISA Server の Web Proxy サービスを使用するように構成された、Hypertext Transfer Protocol (HTTP) 1.1 準拠の Web ブラウザアプリケーションを搭載するクライアントコンピュータです。各 Web ブラウザは、それぞれのユーザーインターフェイスから構成されます。
  
ファイアウォールクライアントソフトウェアをインストールするときに、ファイアウォールクライアントデスクトップ上の Web ブラウザの設定を自動的に構成することができます。その後で、Web ブラウザクライアントを再構成することができます。ISA の管理を使用して、以下の Web ブラウザプロパティを構成できます。
  
-   クライアントが接続する ISA Server とポート
  
-     
-   自動検出設定
  
-     
-   ファイアウォールクライアントの Web ブラウザが直接アクセスするコンピュータ
  
-     
-   ISA Server が使用できない場合のバックアップルート
  
-   
  
ファイアウォールクライアントソフトウェアのインストール時に、クライアントコンピュータの Web ブラウザにこれらの設定が構成されます。
  
ファイアウォールクライアントソフトウェアがインストールされていない場合は、Web ブラウザを手動で構成することができます。
  
詳細については、ISA Server のドキュメントの以下のトピックを参照してください。
  
-   クライアントのセットアップ中に Web ブラウザの構成を有効にする
  
-     
-   自動検出
  
-     
-   サーバーを直接アクセスするように構成する
  
-     
-   Web 要求のバックアップルートの構成
  
-     
-   Web Proxy サービスを使用するように Microsoft Internet Explorer 5 を構成する
  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
