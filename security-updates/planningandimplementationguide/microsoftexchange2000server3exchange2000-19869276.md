---
TOCTitle: 'Microsoft Exchange 2000 Server セキュリティ運用ガイド : 第 3 章 ‐ 役割に基づいて Exchange 2000 サーバーのセキュリティを強化する'
Title: 'Microsoft Exchange 2000 Server セキュリティ運用ガイド : 第 3 章 ‐ 役割に基づいて Exchange 2000 サーバーのセキュリティを強化する'
ms:assetid: 'b41b1f18-5372-4009-8ef7-49740f56ab32'
ms:contentKeyID: 19869276
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277326(v=TechNet.10)'
---

Microsoft Exchange 2000 Server セキュリティ運用ガイド
=====================================================

### 第 3 章 ‐ 役割に基づいて Exchange 2000 サーバーのセキュリティを強化する

最終更新日: 2004年4月6日

##### トピック

[](#ehaa)[テスト環境](#ehaa)

[](#egaa)[OWA フロントエンド サーバーとバックエンド サーバーの使用](#egaa)

[](#efaa)[Exchange 2000 環境で使用するサーバーの役割ごとのセキュリティ確保](#efaa)

[](#eeaa)[Exchange サーバー ポリシー](#eeaa)

[](#edaa)[付加的なセキュリティ対策](#edaa)

[](#ecaa)[Exchange クラスタに関する考慮事項](#ecaa)

[](#ebaa)[セキュリティ テンプレートのダウンロード](#ebaa)

[](#eaaa)[まとめ](#eaaa)

これまでの章では、Exchange 2000 環境のセキュリティ確保に関する一般的な推奨事項を述べてきました。この章では、実際の IT 環境内で Exchange 2000 サーバーに割り当てられる役割に基づいて、Exchange 2000 サーバーのセキュリティを強化することに焦点を絞って推奨事項を述べます。

Windows 2000 環境で動作する Exchange 2000 のセキュリティを向上するには、Windows 2000 のセキュリティを確保することが大前提となります。特定のサーバーの役割のセキュリティに関する推奨事項は「Windows 2000 Server セキュリティ運用ガイド」に述べられていますが、この章では、それらの推奨事項を拡張して、Exchange 2000 のセキュリティに関する推奨事項を述べます。特に、OWA (Outlook Web Access) フロントエンド サーバーと Exchange バックエンド サーバーの役割について詳しく説明します。

**メモ** : この章には、「Windows 2000 Server セキュリティ運用ガイド」の第 3 章および第 4 章の推奨事項を補足する情報が記載されています。上記の 2 つの章は、簡単に参照できるように、このガイドにも付録として収録されています。「Windows 2000 Server セキュリティ運用ガイド」の詳細については、この章の末尾の「詳細情報」を参照してください。

### テスト環境

本稼動環境に変更を加える前に、IT システムのセキュリティに対する変更をテスト環境内で徹底的に評価する必要があります。本稼動環境にできるだけ近いテスト環境を構築してください。最低限でも、複数のドメイン コントローラをテスト環境に含めると共に、本稼動環境で使用するメンバ サーバーの役割をすべて含めておきます。

このテストでは、変更の適用が環境に悪影響を及ぼさないことを確認すると同時に、セキュリティのレベルが意図したとおりに向上するかどうかを確認します。テスト環境で、すべての変更の妥当性を徹底的に検証し、セキュリティ上の脆弱性がないかどうかを評価します。

**メモ** : 脆弱性の評価は、事前に書面で許可を得た人だけが実施できるようにする必要があります。

[](#mainsection)[ページのトップへ](#mainsection)

### OWA フロントエンド サーバーとバックエンド サーバーの使用

既定の設定では、どの Exchange 2000 サーバーも OWA 機能を持ち、HTTP (Hypertext Transfer Protocol) 経由のユーザー接続を受け付けます。これは、既定のインストールでは、OWA を構成するコンポーネントが Exchange サーバーにインストールされるからです。しかし、中規模以上の環境では、OWA へのアクセス用のフロントエンド/バックエンド ソリューションを実装することが望ましくなります。この場合、ユーザーは、フロントエンド サーバーに接続します。フロントエンド サーバーは、要求を受け付け、Active Directory 内のユーザー資格情報を確認した後、適切なバックエンド Exchange サーバーに要求を転送します。バックエンド サーバーは、メールボックスおよびパブリック フォルダへのアクセスを提供します。このフロントエンド/バックエンド ソリューションには、以下のような利点があります。

-   ユーザーは、自分がアクセスするサーバーの名前を知らなくても、ローカル Exchange サーバーにアクセスできます。

-   
-   メールボックスが置かれているサーバーの名前は表示されません。

-   
-   複数のフロントエンド サーバーの間で負荷を分散することができます。

-   
-   SSL (Secure Sockets Layer) のオーバーヘッドをフロントエンド サーバーに振り分けることができます。

-   
-   バックエンド サーバーの手前のファイアウォールを増設することで、バックエンド サーバーのセキュリティをさらに強化できます。

-   

**メモ**

-   フロントエンド サーバーは POP3 接続および IMAP4 接続にも使用できますが、このガイドでは、HTTP 接続と MAPI 接続だけを有効にする場合を想定しています。

-   
-   Exchange における OWA フロントエンド/バックエンド サーバー環境の詳細については、この章の末尾の「詳細情報」を参照してください。

-   

[](#mainsection)[ページのトップへ](#mainsection)

### Exchange 2000 環境で使用するサーバーの役割ごとのセキュリティ確保

このガイドには、Exchange 2000 サーバーの役割に対するセキュリティを変更するためのセキュリティ テンプレートが用意されています。これらのテンプレートを適用するには、グループ ポリシーの設定にテンプレートをインポートする必要があります。

サーバーの役割とそれらのセキュリティ強化に使用するテンプレートは、次の表に示すとおりです。

**表 3.1 Exchange 2000 サーバーの役割**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >サーバーの役割</th>
<th style="border:1px solid black;" >説明</th>
<th style="border:1px solid black;" >セキュリティ テンプレート</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">OWA サーバー</td>
<td style="border:1px solid black;">Outlook Web Access 専用の OWA フロントエンド サーバー</td>
<td style="border:1px solid black;">Baseline.inf および OWA front-end Incremental.inf</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Exchange 2000 バックエンド サーバー</td>
<td style="border:1px solid black;">メールボックスとパブリック フォルダへのアクセスおよびルーティング用のサーバー</td>
<td style="border:1px solid black;">Baseline.inf および Exchange back-end Incremental.inf</td>
</tr>
</tbody>
</table>
  
上記のテンプレートのほかに、ドメイン コントローラ用の基準グループ ポリシーに追加のセキュリティ テンプレートを適用する必要があります。「Windows 2000 Server セキュリティ運用ガイド」に記載されている設定では、Exchange が環境に含まれているとは想定していないため、Exchange 2000 に対応するための変更が必要になります。
  
Exchange の処理をサポートできるようにドメイン コントローラの設定を変更するためのテンプレートとして、Exchange DC Incremental.inf が用意されています。このテンプレートは、ドメイン コントローラ組織単位 (OU) のグループ ポリシー オブジェクト (GPO) にインポートしてください。下の表に示すように、実際に変更されるセキュリティ オプションは 1 つだけです。
  
**表 3.2 Exchange 2000 をサポートするドメイン コントローラ上のセキュリティ オプション**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >オプション</th>
<th style="border:1px solid black;" >Windows 2000 Server のセキュリティ運用</th>
<th style="border:1px solid black;" >Exchange 2000 Server のセキュリティ運用</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">匿名接続の追加を制限する</td>
<td style="border:1px solid black;">明示的な匿名アクセス権がない場合アクセスを許可しない</td>
<td style="border:1px solid black;">なし (既定のアクセス権に依存)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">セキュリティ監査のログを記録できない場合は直ちにシステムをシャットダウンする</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">無効</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">アカウント ログオン イベントの監査</td>
<td style="border:1px solid black;">成功と失敗</td>
<td style="border:1px solid black;">失敗</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ログオン イベントの監査</td>
<td style="border:1px solid black;">成功と失敗</td>
<td style="border:1px solid black;">失敗</td>
</tr>
</tbody>
</table>
  
Outlook 2000 クライアントおよび Outlook 2002 クライアントはグローバル カタログに匿名でアクセスして情報を照会するので、匿名接続の制限の設定を変更する必要があります。「Windows 2000 Server セキュリティ運用ガイド」に記載されている設定のままでは、Outlook ユーザーが内部メールを送信できず、外部アドレスを使用しなければならなくなります。
  
**メモ** : この問題の詳細については、マイクロソフト サポート技術情報 JP309622「\[XADM\] Q299687 Windows 2000 セキュリティ修正プログラムを適用後にクライアントがグローバルアドレス一覧を参照できない」を参照してください。
  
他の設定は、Exchange 2000 によって多数の成功ログオン イベントが生成されることに対応するために変更されます。ログオン イベントに対して成功の監査を有効にすると、セキュリティ ログが短時間で満杯になります。
  
**メモ** : この問題の詳細については、マイクロソフト サポート技術情報 Q316685「Active Directory-Integrated Domain Name Is Not Displayed in DNS Snap-in with Event ID 4000 and 4013 Messages」(英語情報) を参照してください。
  
#### Exchange 2000 サーバーの役割をサポートするための Active Directory 構造
  
「Windows 2000 Server セキュリティ運用ガイド」では、用意されているセキュリティ テンプレートの適用を容易にする組織単位 (OU) 構造が推奨されています。この組織単位構造は、簡単な変更を加えるだけで、ここで述べる 2 つのサーバーの役割が組み込まれるように拡張できます。Exchange 2000 はアプリケーションなので、\[アプリケーション サーバー\] 組織単位の下位に \[Exchange Server\] 組織単位を作成し、\[Exchange Server\] 組織単位の下位に各サーバーの役割に対応する組織単位を追加します。
  
2 つの新しいサーバーの役割を組み込んだ推奨組織単位構造を下の図に示します。
  
![](images/Dd277326.e2k0301s(ja-jp,TechNet.10).gif)
  
**図 3.1: Exchange Server OU およびアプリケーション サーバー OU を追加した OU 構造**
  
[拡大表示する](https://technet.microsoft.com/ja-jp/dd277326.e2k0301s(ja-jp,technet.10).gif)
  
**メモ** : このガイドで示している推奨事項に対応する OU 構造を作成する際は、「Windows 2000 Server セキュリティ運用ガイド」に示されている組織単位の詳細な作成手順を参照してください。
  
#### セキュリティ テンプレートをダウンロードする
  
この後の説明で言及しているセキュリティ テンプレートは、下記からダウンロードいただけます。  
[http://www.microsoft.com/downloads/details.aspx?displaylang=en&FamilyID=9989D151-5C55-4BD3-A9D2-B95A15C73E92](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=9989d151-5c55-4bd3-a9d2-b95a15c73e92)
  
Windows 2000 Service Pack 2 を使用している場合は、以下のマイクロソフト サポート技術情報で解説されている問題が確認されているため、最新のサービスパックを適用してください。
  
-   [295444](http://support.microsoft.com/kb/295444) SCE がサービスのレジストリ キーにあるサービスの SACL エントリを変更できない
  
-     
-   [272560](http://support.microsoft.com/kb/272560) 競合条件の発生によってグループ ポリシーの変更が失われることがある
  
-   
  
**警告** : このガイドのセキュリティ テンプレートは、環境内のセキュリティを強化するように設計されています。これらのテンプレートをインストールすると、環境内の機能が失われる可能性があり、基幹業務アプリケーションに障害が生じないとも限りません。したがって、これらのテンプレートを本稼動環境に展開する前に、徹底したテストを実施することが不可欠です。さらに、環境を適切に変更しておくことも重要です。新しいセキュリティ設定を適用する前に、各ドメイン コントローラとサーバーをバックアップしておきます。バックアップには、必ずシステム状態データを含めてください。システム状態データには、レジストリ データが含まれるほか、ドメイン コントローラ上では、Active Directory 内のすべてのオブジェクトが含まれます。
  
**メモ** : 「Windows 2000 Server セキュリティ運用ガイド」に記載されているドメイン コントローラ基準ポリシーとメンバ サーバー基準ポリシーでは、LAN Manager 認証レベルが NTLMv2 のみに設定されます。Outlook クライアントが Exchange サーバーおよびドメイン コントローラと正常に通信するには、それらのクライアントも NTLMv2 だけを使用するように構成する必要があります。
  
ここでは、このガイドに用意されているセキュリティ テンプレートをこの章で示した組織単位 (OU) 構造にインポートする手順を示します。
  
**ドメイン コントローラのグループ ポリシー オブジェクトを作成してセキュリティ テンプレートをインポートする方法**
  
1.  \[Active Directory ユーザーとコンピュータ\] で、\[Domain Controllers\] を右クリックし、\[プロパティ\] を選択します。
  
2.  3.  \[グループ ポリシー\] タブで、\[新規\] をクリックし、新しいグループ ポリシー オブジェクトを追加します。
  
4.  5.  「Exchange DC ポリシー」と入力し、**Enter** キーを押します。
  
6.  7.  \[上へ\] を繰り返しクリックし、\[Exchange DC ポリシー\] を一覧の先頭に移動します。
  
8.  9.  \[編集\] をクリックします。
  
10. 11. \[Windows の設定\] を展開し、\[セキュリティの設定\] を右クリックして \[ポリシーのインポート\] を選択します。
  
    **メモ** : メニューに \[ポリシーのインポート\] が表示されない場合は、\[グループ ポリシー\] ウィンドウを閉じた後、手順 4. および 5. を繰り返してください。
  
12. 13. \[ポリシーのインポート\] ダイアログ ボックスで、C:\\SecurityOps\\Templates に移動し、Exchange DC Incremental.inf をダブルクリックします。
  
14. 15. グループ ポリシーを閉じ、\[OK\] をクリックします。
  
16. 17. すべてのドメイン コントローラにポリシーが複製されるように、ドメイン コントローラ間の複製を強制実行します。
  
18. 19. イベント ログを開き、ポリシーが正しくダウンロードされており、サーバーがドメイン内の他のドメイン コントローラと通信できていることを確認します。
  
20. 21. 各ドメイン コントローラを 1 つずつ再起動します。その都度、正しく再起動されたことを確認してください。
  
22. 
  
**Exchange サーバーのグループ ポリシー オブジェクトを作成してセキュリティ テンプレートをインポートする方法**
  
1.  \[Active Directory ユーザーとコンピュータ\] で、\[メンバ サーバー\]、\[アプリケーション サーバー\]、\[Exchange サーバー\] を順に展開し、\[OWA フロントエンド サーバー\] を右クリックし、\[プロパティ\] をクリックします。
  
2.  3.  \[グループ ポリシー\] タブで、\[新規\] をクリックし、新しいグループ ポリシー オブジェクトを追加します。
  
4.  5.  「OWA ポリシー」と入力し、**Enter** キーを押します。
  
6.  7.  \[編集\] をクリックします。
  
8.  9.  \[Windows の設定\] を展開して、\[セキュリティの設定\] を右クリックし、\[ポリシーのインポート\] をクリックします。
  
    **メモ** : メニューに \[ポリシーのインポート\] が表示されない場合は、\[グループ ポリシー\] ウィンドウを閉じた後、手順 4. および 5. を繰り返してください。
  
10. 11. \[ポリシーのインポート\] ダイアログ ボックスで、C:\\SecurityOps\\Templates に移動し、OWA Front-end Incremental.inf をダブルクリックします。
  
12. 13. グループ ポリシーを閉じ、\[OK\] をクリックします。
  
14. 15. \[バックエンド サーバー\] 組織単位に対しても、手順 1. ～ 7. を実施します。ただし、テンプレートは、Exchange Back-end Incremental.inf を適用する必要があります。
  
16. 17. すべてのドメイン コントローラにポリシーが複製されるように、ドメイン コントローラ間の複製を強制実行します。
  
18. 19. 各役割に対応するサーバーを適切な組織単位の中に移動します。
  
20. 21. サーバー上で secedit /refreshpolicy machine\_policy /enforce コマンドを実行し、ポリシーをダウンロードします。
  
22. 23. イベント ログを開き、ポリシーが正しくダウンロードされており、サーバーがドメイン コントローラおよびドメイン内の他のサーバーと通信できていることを確認します。OU 内のサーバーの 1 つをテストした結果、問題がなければ、OU 内の残りのサーバーを移動し、セキュリティを適用します。
  
    **メモ** : グループ ポリシーのダウンロードが成功したかどうかを確認する方法の詳細については、「付録 A」を参照してください。「付録 A」には、「Windows 2000 Server セキュリティ運用ガイド」の「第 3 章 Windows 2000 グループ ポリシーを使ったセキュリティ管理」が収録されています。
  
24. 25. 各サーバーを再起動します。その都度、正しく再起動されたことを確認してください。
  
26. 
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### Exchange サーバー ポリシー
  
Windows 2000 では、監査、セキュリティオプション、レジストリ設定値、ファイルへのアクセス許可、サービスなど、さまざまなセキュリティ設定値を定義することができます。「Windows 2000 Server セキュリティ運用ガイド」には、これらの設定の多くに関して推奨値が示されていますが、Exchange 2000 を運用する場合も、基本的には同じ推奨値を使用できます。特に変更が必要となるのは、各種サービスに関する設定です。また、ファイルへのアクセス許可についても若干の変更が必要になります。Exchange サーバー組織単位は \[メンバ サーバー\] 組織単位の下層にあるので、メンバ サーバー基準ポリシーで定義されている設定値が Exchange サーバーに継承されます。Exchange ポリシーでは、継承した設定値に対し 2 とおりの変更を加えます。まず、Windows 2000 の基本機能に不要なサービスのうち、Exchange 2000 の運用には必要なサービスを有効にします。次に、Exchange 2000 に用意されている付加的なサービスのうち、それぞれの役割の Exchange サーバーでは不要となるサービスを無効にします。
  
**メモ** : Exchange 増分ポリシーでは明示的に言及していませんが、NNTP (Network News Transfer Protocol) は Windows 2000 メンバ サーバー基準ポリシーによって無効化されます。このサービスは Exchange のインストールには必須ですが、Exchange の運用中は、ニュースグループ機能を使用しない限り不要です。
  
#### Exchange バックエンド サーバー ポリシー
  
Exchange バックエンド サーバー ポリシーでは、サービスに関する設定とファイル アクセス制御リストの設定を定義します。
  
**Exchange バックエンド サーバーのサービス ポリシー**
  
Exchange 2000 バックエンド ポリシーでは、下の表に示すサービスを構成します。
  
**表 3.3 Exchange バックエンド サーバー基準ポリシーによるサービスの構成**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >サービス名</th>
<th style="border:1px solid black;" >スタートアップ モード</th>
<th style="border:1px solid black;" >理由</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange IMAP4</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">サーバーで IMAP4 をサポートしないので不要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange Information Store</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">メールボックス ストアとパブリック フォルダ ストアへのアクセスに必要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange POP3</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">サーバーで POP3 をサポートしないので不要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Search</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">コア機能には不要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Event Service</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">下位互換性を確保する以外の目的では不要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange Site Replication Service</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">下位互換性を確保する以外の目的では不要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Management</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">メッセージ追跡に必要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Management Instrumentation</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">Microsoft Exchange の管理に必要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange MTA Stacks</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">下位互換性または X.400 コネクタとの互換性を確保する以外の目的では不要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange System Attendant</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">Exchange の保守やその他のタスクに必要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Routing Engine</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">Exchange サーバー間におけるメッセージ転送の調整に必要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IPSEC Policy Agent</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">サーバー上に IPSec ポリシーを実装するために必要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RPC Locator</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">ドメイン コントローラおよびクライアントとの通信に必要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IIS Admin Service</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">Exchange Routing Engine に必要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">NT LM Security Support Provider</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">System Attendant に必要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SMTP</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">Exchange トランスポートに必要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">World Wide Web Publishing Service</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">OWA フロントエンド サーバーとの通信に必要</td>
</tr>
</tbody>
</table>
  
**メモ** : Exchange System Attendant を起動する前に、以下のサービスを開始しておく必要があります。
  
-   Event Log
  
-     
-   NT LM Security Support Provider
  
-     
-   Remote Procedure Call (RPC)
  
-     
-   Remote Procedure Call (RPC) Locator
  
-     
-   Server
  
-     
-   Workstation
  
-   
  
**無効化されるサービス**
  
このガイドでは、Exchange 2000 のコア機能に不必要なサービスをすべて無効にしています。実際の環境では、ここで無効化したサービスを有効に戻さなければ、必要な機能を使用できないことがあります。ここでは、バックエンド サーバーの増分ポリシーによって無効化されるサービスについて説明します。
  
**Event Service**
  
Exchange Server 5.5 で採用された Exchange Server Event Service は、パブリック フォルダまたは各ユーザーのメールボックスでフォルダ イベントが発生したときにトリガされるサーバー側スクリプトをサポートするサービスです。Exchange 2000 にも、Exchange 5.5 イベント スクリプトとの下位互換性を確保することを目的として Exchange Event Service が用意されています。MSDN から入手できる『Exchange 2000 ソフトウェア開発キット (SDK)』に記載されているように、Exchange 2000 用に新規作成するアプリケーションでは、Exchange Event Service ではなくネイティブな Web Storage System イベントを使用してください。詳細については、この章の末尾の「詳細情報」を参照してください。
  
**Microsoft Search**
  
インフォメーション ストア プロセスでは、ストア内のドキュメントの参照と検索を高速化するために、共通キーフィールドを使用します。Outlook ユーザーは、インデックスを通じてドキュメントをより簡単に検索することができます。フルテキスト インデックスを使用すると、クライアントが検索を行う前にインデックスが構築されるので、高速な検索が可能になります。フルテキスト インデックスには、添付データも含めることができます。
  
これらのインデックスを提供するのが Microsoft Search サービスです。インデックスを作成、更新、または削除するには、インフォメーション ストア サービスと Search サービスの両方が稼動している必要があります。
  
**Microsoft Exchange Site Replication Service**
  
これは、既存の Exchange 5.5 サイトに Exchange 2000 サーバーを追加する場合に、Exchange 5.x サイトおよび構成情報を Active Directory のパーティション (名前付けコンテキスト) に複製できるようにするサービスです。
  
**Microsoft Exchange MTA Stacks**
  
これは、Exchange 2000 Server を外部システムに接続するための追加コンポーネントです。外部環境に対しては、メッセージ転送エージェント (MTA) によって X.400 コネクタおよびゲートウェイ コネクタを経由したメッセージ ルーティングが行われます。このサービスでは、\\Program Files\\Exchsrvr\\Mtadata ディレクトリにあるインフォメーション ストア サービスの外部に専用のメッセージ キューが維持されます。
  
**Exchange バックエンド サーバーのファイル アクセス制御リスト ポリシー**
  
Exchange バックエンド サーバー ポリシーでは、いくつかのディレクトリに対するアクセス制御リスト (ACL) を変更します。変更前と変更後の設定を下の表に示します。
  
**表 3.4 Exchange バックエンド サーバー ポリシーによって構成されるファイル アクセス制御リスト**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >ディレクトリ</th>
<th style="border:1px solid black;" >変更前の ACL</th>
<th style="border:1px solid black;" >変更後の ACL</th>
<th style="border:1px solid black;" >サブディレクトリに適用されるか</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">%systremdrive%\Inetpub\mailroot</td>
<td style="border:1px solid black;">Everyone : フル アクセス</td>
<td style="border:1px solid black;">Domain Admins : フル アクセス
ローカル システム : フル アクセス</td>
<td style="border:1px solid black;">はい</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%systremdrive%\Inetpub\nntpfile\</td>
<td style="border:1px solid black;">Everyone : フル アクセス</td>
<td style="border:1px solid black;">Domain Admins : フル アクセス
ローカル システム : フル アクセス</td>
<td style="border:1px solid black;">はい</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%systremdrive%\Inetpub\nntpfile\root</td>
<td style="border:1px solid black;">Everyone : フル アクセス</td>
<td style="border:1px solid black;">Everyone : フル アクセス</td>
<td style="border:1px solid black;">はい</td>
</tr>
</tbody>
</table>
  
**メモ** : サーバー上で NNTP を使用しないので、nntpfile ディレクトリおよびその下位のサブディレクトリに対する設定は、厳密に言うと定義する必要がありません。しかし、ファイル システムへの制限を強化すると共に、今後 NNTP を使用する場合にも対応できるように、ここでは、これらのディレクトリとサブディレクトリに対しても設定を定義しています。
  
**OWA フロントエンド サーバー ポリシー**
  
OWA フロントエンド ポリシーでは、サービスに関する設定とファイル アクセス制御リストの設定を定義します。
  
**OWA フロントエンド サーバーのサービス ポリシー**
  
このサーバーの役割は、Web ベースの電子メールのサポートだけに限られているので、既定の構成でインストールされる Exchange サービスの多くを無効化できます。OWA フロントエンド サーバー ポリシーでは、下の表に示すサービスを構成します。
  
**表 3.5 OWA フロントエンド サーバー ポリシーによるサービスの構成**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >サービス名</th>
<th style="border:1px solid black;" >スタートアップ モード</th>
<th style="border:1px solid black;" >理由</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange IMAP4</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">OWA サーバーで IMAP4 をサポートしないので不要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange Information Store</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">メールボックス ストアおよびパブリック フォルダ ストアがないため不要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange POP3</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">OWA サーバーで POP3 をサポートしないので不要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Search</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">検索するストアがないので不要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Event</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">下位互換性を確保する以外の目的では不要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange Site Replication Service</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">下位互換性を確保する以外の目的では不要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Management</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">メッセージの追跡に必要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange MTA</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">下位互換性または X.400 コネクタとの互換性を確保する以外の目的では不要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Routing Engine</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">Exchange のルーティング機能に必要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IPSEC Policy Agent</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">OWA サーバー上に IPSec フィルタを実装するために必要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RPC Locator</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">ドメイン コントローラとの通信および System Attendant の起動に必要</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IIS Admin Service</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">MSExchange Routing Engine に必要</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">World Wide Web Publishing Service</td>
<td style="border:1px solid black;">自動</td>
<td style="border:1px solid black;">OWA フロントエンド サーバーとのクライアント通信に必要</td>
</tr>
</tbody>
</table>
  
**OWA フロントエンド サーバー ポリシーによって無効化されるサービス**
  
バックエンド構成の場合と同様に、実際の環境では、ここで無効化したサービスを有効に戻さなければ、必要な機能を使用できないことがあります。ここでは、OWA フロントエンド サーバーの増分ポリシーによって無効化されるサービスについて説明します。
  
**Microsoft Exchange POP3 および Microsoft Exchange IMAP4**
  
第 2 章で述べたように、Exchange の機能のうち、どの機能が実際の環境に必要で、どの機能が不要なのかを明確にしてください。多くの場合、POP3 クライアントや IMAP4 クライアントは存在しないので、これらのサービスはグループ ポリシーで無効化することができます。ただし、サービスを無効化する前に、それらのサービスを必要とするカスタム プログラムを環境内で使用していないことを確認してください。
  
**System Attendant**
  
フロントエンド サーバーで System Attendant が必要となるのは、サーバーに対して構成変更を行う場合だけなので、このガイドに用意されているテンプレートでは、System Attendant を無効化しています。このため、特定のサーバーを OWA フロントエンド サーバーにするときや、OWA フロントエンド サーバー ポリシーが既に適用されているサーバーに対して変更を実施するときは、最初に、System Attendant を関連サービスと共に一時的に開始しておく必要があります。
  
**OWA フロントエンド サーバー グループ ポリシーが適用されているサーバーの構成を変更する方法**
  
1.  \[サービス\] 管理ツールを起動します。
  
2.  3.  \[NT LM Security Support Provider\] を右クリックし、\[プロパティ\] をクリックします。
  
4.  5.  \[スタートアップの種類\] ボックスの一覧の \[自動\] をクリックします。
  
6.  7.  \[適用\] をクリックします。
  
8.  9.  \[開始\] をクリックします。
  
10. 11. \[OK\] をクリックします。
  
12. 13. System Attendant に対しても、手順 2. ～ 6. を繰り返します。
  
14. 15. 構成を必要に応じて変更します。
  
16. 17. \[サービス\] 管理ツールを起動します。
  
18. 19. \[System Attendant\] を右クリックし、\[プロパティ\] をクリックします。
  
20. 21. \[スタートアップの種類\] ボックスの一覧の \[無効\] をクリックします。
  
22. 23. \[適用\] をクリックします。
  
24. 25. \[停止\] をクリックします。
  
26. 27. \[OK\] をクリックします。
  
28. 29. NT LM Security Support Provider に対しても、手順 2. ～ 6. を繰り返します。
  
30. 
  
**Microsoft Exchange Information Store**
  
このサーバーにはメールが配信されないので、このサービスは不要です。通常の Exchange 2000 サーバーには、ドライブ文字 M: がマップされたドライブがありますが、Information Store サービスをインストールしていないサーバーにはドライブ M がありません。これは、Exchange Installable File System によってマップされるドライブが存在しないためです。
  
なお、フロントエンド サーバーをブリッジヘッド サーバーとする SMTP コネクタを作成する場合には、配信不能通知 (NDR) の配信のために少なくとも 1 つ以上のメールボックス ストアを作成し、マウントする必要があります。
  
**Microsoft Exchange Management**
  
このサービスは、Exchange 2000 Server Service Pack 2 に含まれています。このサービスを使うと、Exchange 2000 からディレクトリにアクセスするときに使用するドメイン コントローラまたはグローバル カタログ サーバーを指定できます。また、メッセージの追跡にも、このサービスが必要になります。このサービスを無効化しても、Exchange のコア機能は影響を受けません。通常、Exchange の機能を監査するときはメッセージの追跡が必要になりますが、OWA フロントエンド サーバーはメールのルーティングではなくメールへのアクセスに使用されるので、Microsoft Exchange Management Service を OWA フロントエンド サーバー上で実行する必要はありません。
  
**SMTP サービス**
  
OWA フロントエンド サーバーは、OWA サーバーとしてしか機能しないので、SMTP を必要としません。フロントエンド サーバーをゲートウェイとしても使用するか、IMAP4 または POP3 用のフロントエンド サーバーとしても使用する場合は、フロントエンド サーバーが SMTP メールを受信できるように SMTP サービスを有効化する必要があります。フロントエンド サーバーを SMTP ゲートウェイとしても使用する場合は、さらに、インフォメーション ストア サービスと System Attendant サービスを有効化する必要があります。
  
**OWA フロントエンド サーバーのファイル アクセス制御リスト ポリシー**
  
このポリシーによるファイル アクセス制御リストの定義は、バックエンド サーバー ポリシーによる定義とまったく同じです。詳細については、前の「Exchange バックエンド サーバーのファイル アクセス制御リスト ポリシー」を参照してください。
  
#### セキュリティ強化環境における Exchange のインストールと更新
  
この章では、これまで、既存の Exchange サーバーを適切な組織単位に移動して環境内のセキュリティ レベルを向上する手順を述べてきましたが、ここでは、新しい Exchange サーバーの扱いについて述べます。セキュリティを最大限に高めるには、新しいサーバーを適切な組織単位に追加したうえで、Exchange のインストールを開始する必要があります。しかし、この環境では Exchange のコア サービスだけが有効化されており、サーバーがロックダウンされているため、既定の設定のままでは Exchange をインストールしたり、Exchange を今後のサービス パックにアップグレードすることはできません。ロックダウンされたサーバーに Exchange または Exchange Service Pack をインストールするには、以下の手順に従ってください。
  
**メモ** : 既にセキュリティで保護されているサーバーに Exchange 2000 をインストールするときには、"デジタル署名未検出" のエラーメッセージが表示されますが、これはサーバーのセキュリティが強化されていることを意味するものであり、無視してインストールを続行できます。
  
**ロックダウンされているサーバーに Exchange または Exchange Service Pack をインストールする方法**
  
1.  \[サービス\] 管理ツールを起動します。
  
2.  3.  \[Distributed Transaction Coordinator\] を右クリックし、\[プロパティ\] をクリックします。
  
4.  5.  \[スタートアップの種類\] ボックスの一覧の \[自動\] をクリックします。
  
6.  7.  \[適用\] をクリックします。
  
8.  9.  \[開始\] をクリックします。
  
10. 11. \[OK\] をクリックします。
  
12. 13. Network News Transport Protocol (NNTP) と Windows Installer についても、手順 2. ～ 6. を繰り返します。
  
    **メモ** : OWA フロントエンド サーバーの組織単位に含まれているサーバーに対して上記の手順を実施する場合は、Windows Management Instrumentation に対しても、手順 2. ～ 6. を繰り返してください。
  
14. 15. Exchange 2000 または最新の Exchange 2000 Service Pack をインストールします。
  
    **メモ** : Exchange 2000 のインストールが終了するときに、Microsoft Search サービスが開始されなかったことを示すダイアログ ボックスが表示されることがありますが、これは、インストール先のサーバーが既にセキュリティで保護されていたためであり、致命的なエラーではないので無視してかまいません。
  
16. 17. \[サービス\] 管理ツールを起動します。
  
18. 19. \[Distributed Transaction Coordinator\] を右クリックし、\[プロパティ\] をクリックします。
  
20. 21. \[スタートアップの種類\] ボックスの一覧の \[無効\] をクリックします。
  
22. 23. \[適用\] をクリックします。
  
24. 25. \[停止\] をクリックします。
  
26. 27. \[OK\] をクリックします。
  
28. 29. Network News Transport Protocol (NNTP) と Windows Installer についても、手順 2. ～ 6. を繰り返します。
  
30. 
  
**メモ** : OWA フロントエンド サーバーの組織単位に含まれているサーバーに対して上記の手順を実施する場合は、Windows Management Instrumentation に対しても、手順 9. ～ 14. を繰り返してください。
  
**メモ** : OWA フロントエンド サーバーおよび Exchange バックエンド サーバーの増分ポリシーでは、セキュリティで保護されたドメイン コントローラと Exchange サーバーが通信できるように NTLMv2 が有効化されますが、Exchange のインストールを開始する前にサーバーを適切な組織単位に移動しておかないと、サーバーがドメイン コントローラに接続することはできなくなります。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 付加的なセキュリティ対策
  
グループ ポリシー テンプレートによるセキュリティ強化のほかに、Exchange 2000 サーバー上に実装しておくべき付加的なセキュリティ対策がいくつかあります。ここでは、これらのセキュリティ対策について述べます。
  
#### IIS Lockdown ツール
  
Exchange 2000 サーバーにセキュリティ テンプレートを適用した後、特に OWA フロントエンド サーバーを対象として、IIS (Internet Information Services) 上で付加的なセキュリティ制御を適用する必要があります。IIS Lockdown ツールを使うと、IIS に対する変更操作を大幅に自動化することができます。このツールでは IIS の強化に必要な設定を指定しますが、このツールで IIS を強化した後も、Exchange 2000 サーバーをバックエンド サーバーまたは OWA フロントエンド サーバーとして引き続き使用することができます。
  
**メモ** : IIS Lockdown ツールは、<http://www.microsoft.com/japan/technet/security/tools/locktool.mspx> から入手できます。
  
IIS Lockdown ツールには、ほとんどの基本的な Web サーバーに適したエクスプレス モードと、サーバー側でサポートする技術を管理者が選択できるアドバンスト モードの 2 つのモードがあります。最後に実行したロックダウンを取り消して、元に戻す機能も用意されています。
  
IIS Lockdown ツールには、IIS サーバーに対するすべての要求を監視し、特定のルールを満たす要求だけを通過させる URLScan も実装されています。有効な要求だけをサーバーに処理させることができるので、サーバーのセキュリティが大幅に向上します。URLScan では、長さや文字セットなどに基づいて要求をフィルタリングすることができます。既定のルールが用意されており、実際のサーバーのニーズに合わせてルールをカスタマイズできます。
  
**Exchange 2000 OWA フロントエンド サーバーをロックダウンする方法**
  
1.  サーバー上に IISLockd.exe をインストールし、このツールを起動します。
  
2.  3.  \[次へ\] をクリックします。
  
4.  5.  使用許諾契約書の内容を確認し、\[I Agree\] をクリックして、\[次へ\] をクリックします。
  
6.  7.  サーバー テンプレート \[Exchange 2000 (OWA、PF Management、IM、SMTP、NNTP)\] を選択し、\[View template settings\] チェック ボックスをオンにした後、\[次へ\] をクリックします。
  
8.  9.  \[Internet Services\] ダイアログ ボックスに、"Web Service (HTTP)"、"FTP"、"SMTP"、および "NNTP" の 4 つのサービスが表示されます。チェックボックスが淡色表示されているサービスは、インストールされていないか、既に無効化されています。\[Web Service (HTTP)\] だけが有効化されていることを確認し、\[次へ\] をクリックします。
  
    **メモ** : OWA フロントエンド セキュリティ テンプレートを適用した後で IIS Lockdown ツールを実行すると、\[Web Service (HTTP)\] だけが有効化され、その他のサービスは無効化されます。
  
10. 11. \[Script Maps\] ダイアログ ボックスでは、特定の ISAPI アプリケーションに関連付けられているスクリプト マップを削除して、そのアプリケーションのサポートを無効化することができます。Exchange 2000 テンプレート内に実装されている既定の設定値を下の表に示します。Active Server Pages だけが有効化され、その他のスクリプト マッピングは無効化されます。\[次へ\] をクリックします。
  
    **表 3.6 IISLockDown を Exchange 2000 テンプレートと共に使用した場合の既定のスクリプト マッピング設定**

 
    <table style="border:1px solid black;">
    <colgroup>
    <col width="33%" />
    <col width="33%" />
    <col width="33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th style="border:1px solid black;" >種類</th>
    <th style="border:1px solid black;" >エントリ</th>
    <th style="border:1px solid black;" >状態</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;">Active Server Pages</td>
    <td style="border:1px solid black;">.asp</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;">Index Server の Web インターフェイス</td>
    <td style="border:1px solid black;">.htw、.ide、.idq</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;">サーバーサイド インクルード</td>
    <td style="border:1px solid black;">.stm、.shtm、.shtml</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;">インターネット データ コネクタ</td>
    <td style="border:1px solid black;">.idc</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;">HTR スクリプト</td>
    <td style="border:1px solid black;">.htr</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;">インターネット印刷</td>
    <td style="border:1px solid black;">.printer</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    </tbody>
    </table>
  
    **メモ** : .htr スクリプト マップのサポートを無効化すると、OWA のパスワード変更機能を使用できなくなります。IIS Lockdown ツールでは、OWA のパスワード変更機能が既定の設定で無効化されます。
  
12. 13. \[Additional Security\] ダイアログ ボックスには、既定の IIS インストールから作成された既定の仮想ディレクトリを削除したり、特定のディレクトリとすべての System32 実行可能ファイルにファイル ACL を適用するためのオプションがあります。\[次へ\] をクリックします。
  
    削除されるディレクトリは、下の表に示すとおりです。
  
    **表 3.7 IISLockdown によって削除される仮想ディレクトリ**

 
    <table style="border:1px solid black;">
    <colgroup>
    <col width="33%" />
    <col width="33%" />
    <col width="33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th style="border:1px solid black;" >名前</th>
    <th style="border:1px solid black;" >仮想ディレクトリ</th>
    <th style="border:1px solid black;" >既定の場所</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;">IIS Samples</td>
    <td style="border:1px solid black;">\IISSamples</td>
    <td style="border:1px solid black;">c:\inetpub\iissamples</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;">IISHelp</td>
    <td style="border:1px solid black;">\IISHelp</td>
    <td style="border:1px solid black;">c:\winnt\help\iishelp</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;">MSADC</td>
    <td style="border:1px solid black;">\MSADC</td>
    <td style="border:1px solid black;">c:\program files\common files\system\msadc</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;">Scripts</td>
    <td style="border:1px solid black;">\Scripts</td>
    <td style="border:1px solid black;">c:\inetpub\scripts</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;">IISAdmin</td>
    <td style="border:1px solid black;">\IISAdmin</td>
    <td style="border:1px solid black;">c:\winnt\system32\inetsrv\iisadmin</td>
    </tr>
    </tbody>
    </table>
  
14. 15. IIS Lockdown ツールは、ファイル システムへのアクセスを制限するために、Web Anonymous Users および Web Applications の 2 つの新しいグループを OWA サーバー上に作成します。この 2 つのグループには、それぞれ匿名ユーザーと匿名アプリケーション アカウントが格納されます。通常は、Web Anonymous Users グループに IUSR\_&lt;computername&gt; が格納され、Web Applications グループに IWAM\_&lt;computername&gt; が格納されます。次に、IIS Lockdown ツールは、これらのグループに対し、以下のディレクトリへの書き込みアクセスを禁止します。
  
    C:\\inetpub\\wwwroot
  
    C:\\Program Files\\Exchsrvr\\ExchWeb
  
    さらに、c:\\winnt\\system32 フォルダの cmd.exe など、すべてのシステム ユーティリティへの実行アクセスを禁止します。ただし、基準テンプレートのグループ ポリシーでは、フル コントロールを持つ Administrators グループだけにアクセスを許可するアクセス制御エントリ (ACE) を System ディレクトリ内の実行ファイルに適用し、その他のユーザーやグループは定義しません。グループ ポリシーを再適用すると、これらの設定で IIS Lockdown ツールの設定が上書きされることに注意してください。
  
16. 17. URLScan をインストールするように促すメッセージが表示されます。既定の設定で、URLScan がインストールされるようになっているので、そのまま \[次へ\] をクリックします。
  
18. 19. どのような処理が実行されるのかを確認し、\[次へ\] をクリックします。
  
20. 21. セキュリティが強化されているため \[Installing Unknown Software Package\] ダイアログ ボックスが表示されますが、\[はい\] をクリックして続行します。
  
22. 23. 実際に行った変更の詳細を示すレポートが生成されます。このレポートには、エラーの有無も示されます。一部の NTFS ディレクトリに ACL を適用できなかったことを示すエラーがレポートに含まれていますが、これらのディレクトリは、OWA サーバーの構成中に削除したメールボックスとパブリック フォルダです。\[次へ\] をクリックします。
  
24. 25. \[完了\] をクリックします。
  
26. 
  
**メモ** : Exchange 2000 バックエンド サーバー上で IIS Lockdown ツールを実行する手順は、基本的に上記の手順と同じですが、手順 5. では HTTP と SMTP が有効化されていることを確認してください。
  
#### OWA フロントエンド サーバーに対する IIS Lockdown ツールと URLScan の設定を変更する
  
IIS Lockdown ツールと URLScan の既定の設定は、実際の環境に応じて変更できます。URLScan の設定は、&lt;WinDir&gt;\\System32\\Inetsrv\\Urlscan にある URLScan.ini ファイルに格納されています。OWA と URLScan を有効化した状態で問題が発生した場合は、&lt;WinDir&gt;\\System32\\Inetsrv\\Urlscan にある Urlscan.log ファイルをチェックし、拒否された要求のリストを確認してください。
  
**メモ** : IIS Lockdown ツールと URLScan のトラブルシューティングおよび構成の詳細については、マイクロソフト サポート技術情報 JP309677「\[XADM\] IIS Lockdown Wizard を Exchange 2000 環境で使用する場合の問題および調整方法」を参照してください。
  
**OWA のパスワード変更サポート**
  
IIS Lockdown ツールの既定の設定では、.htr ファイルが無効化されます。.htr ファイルが無効化されていると、OWA のパスワード変更機能を使用できません。.htr ファイルが無効化されている場合は、ユーザーが混乱してヘルプ デスクに問い合わせが殺到しないように、\[パスワードの変更\] ボタンを非表示にしてください。
  
**メモ** : OWAの \[パスワードの変更\] ボタンを無効化する方法については、マイクロソフト サポート技術情報 JP297121「\[XWEB\] Outlook Web Access の \[オプション\] ページにある \[パスワードの変更\] ボタンを非表示にする方法」を参照してください。
  
**電子メールのブロック**
  
URLScan.ini ファイルの \[DenyUrlSequences\] セクションには、明示的にブロックされる文字のリストが含まれていますが、これが OWA へのアクセスに影響を及ぼす可能性があります。以下の文字シーケンスが含まれている電子メールの題名またはメール フォルダ名は、ブロックされます。
  
-   ..
  
-     
-   ./
  
-     
-   \\
  
-     
-   %
  
-     
-   &
  
-   
  
**メモ** : URLScan.ini ファイルの 「..」 は、題名の末尾がピリオドになっている電子メール メッセージをブロックします。
  
#### メールボックス ストアとパブリック フォルダ ストアをマウント解除および削除する
  
OWA フロントエンド サーバーの役割はバックエンド サーバーに要求を転送することだけに限られているので、OWA フロントエンド サーバー上に Exchange Server メールボックスおよびパブリック フォルダを置く必要はありません。これらは、バックエンド Exchange サーバーによって管理されます。したがって、これらのストアは、マウント解除して削除することができます。
  
**メールボックス データベースとパブリック フォルダ データベースをマウント解除および削除する方法**
  
1.  \[サービス\] 管理ツールを起動します。
  
2.  3.  \[NTLM Security Support Provider\] を右クリックし、\[プロパティ\] をクリックします。
  
4.  5.  \[スタートアップの種類\] ボックスの一覧の \[自動\] をクリックします。
  
6.  7.  \[適用\] をクリックします。
  
8.  9.  \[開始\] をクリックします。
  
10. 11. \[OK\] をクリックします。
  
12. 13. System Attendant に対しても、手順 2. ～ 6. を繰り返します。
  
14. 15. OWA フロントエンド サーバー上で Exchange システム マネージャを起動します。
  
16. 17. \[サーバー\]、\[OWA フロントエンド サーバー\]、\[最初のストレージ グループ\] を順に展開します。
  
18. 19. メールボックス ストアが現在マウントされている場合は、\[メールボックス ストア\] を右クリックし、\[ストアのディスマウント\] をクリックします。次に、\[はい\] をクリックし、メールボックス ストアをマウント解除します。
  
20. 21. \[メールボックス ストア\] を右クリックし、\[プロパティ\] をクリックします。
  
22. 23. \[データベース\] タブをクリックし、\[起動時にこのストアをマウントしない\] チェック ボックスをオンにして、\[OK\] をクリックします。
  
24. 25. パブリック フォルダ ストアが現在マウントされている場合は、\[パブリック フォルダ ストア\] を右クリックし、\[ストアのディスマウント\] をクリックします。次に、\[はい\] をクリックし、パブリック フォルダ ストアをマウント解除します。
  
26. 27. \[パブリック フォルダ ストア\] を右クリックし、\[削除\] をクリックします。
  
28. 29. \[はい\] をクリックして \[OK\] をクリックし、バックエンド サーバーを選択して \[OK\] をクリックします。
  
30. 31. \[はい\] をクリックしてパブリック フォルダ ストアを削除し、\[OK\] をクリックしてダイアログ ボックスを閉じます。
  
32. 33. OWA サーバーを再起動します。
  
34. 
  
**メモ**
  
-   NT LM Security Support Provider と System Attendant を再度無効化する必要はありません。これらは、サーバーの再起動時に自動的に無効化されます。
  
-     
-   フロントエンド サーバー上で SMTP を使用する場合は、メールボックス ストアをマウントする必要があります。
  
-     
-   通常の Exchange 2000 サーバーには、ドライブ文字 M: がマップされたドライブがありますが、メールボックス ストアとパブリック フォルダ ストアをマウント解除すると、ドライブ M が削除されます。これは、Exchange Installable File System によってマップされるドライブが存在しないためです。
  
-   
  
特定の仮想ディレクトリへのパスが無効であることを示すイベント エラー (イベント ID 101) がシステム ログに記録されます。また、インターネット サービス マネージャ コンソール上では、Public、Exchange、Exadmin の各仮想ディレクトリの状態が \[停止\] と表示されます。これらのエラーは、IIS サーバー上に Exchange Server をインストールしてサーバーを再起動した後で発生します。再起動後、まず IIS (W3SVC) サービスが開始し、続いて Exchange インフォメーション ストア サービスが開始します。インフォメーション ストア サービスは、上記の 3 つの仮想ドライブの割り当て先であるマップされた仮想ドライブ (M:) を管理しますが、マップされたドライブがまだ作成されていないため、IIS がエラー メッセージを返します。グループ ポリシーを通じてセキュリティを適用するとインフォメーション ストア サービスが無効化されるので、マップされた仮想ドライブがマウントされることはなく、その後も、これらのエラーがイベント ログに書き込まれますが、無視しても問題はありません。
  
**メモ** : イベント ログ ID 101 の詳細については、マイクロソフト サポート技術情報 JP259373「\[XADM\] W3SVC が イベント ID 101 をシステム イベント ログに出力する」を参照してください。
  
#### SMTP バナーを変更する
  
外部にさらす情報が少ないほど、システムが攻撃を受けにくくなります。ハッカーが Exchange のバージョン情報を取得する手口の 1 つとして、Telnet 経由で SMTP サービスに接続する方法があります。既定の設定では、Exchange サーバー上の SMTP サービスに接続したときに、次のバナーが表示されるようになっています。
  
220 &lt;ホスト名&gt; . &lt;ドメイン&gt; .com Microsoft ESMTP MAIL Service, Version: 5.0.2195.1600 ready at &lt;現在の日付&gt; and &lt;時間&gt;.
  
すべてのバックエンド Exchange サーバーに対して、このバナーからバージョン情報を削除することを検討してください。また、SMTP サービスの無断使用を禁止する旨の文言をバナーに含めることも考えられます。
  
**Windows 2000 の SMTP バナーを変更する方法**
  
1.  MetaEdit などのメタベース編集ツールを使って、次の行を探します。
  
    Lm\\Smtpsvc\\ &lt;virtual server number&gt;.
  
2.  3.  \[Edit\] をクリックし、\[New\] をクリックします。次に \[String\] をクリックします。
  
4.  5.  \[ID\] ボックスのエントリが \[Other\] になっていることを確認し、ID ボックスの右側に 10 進数で「36907」と入力します。
  
6.  7.  \[Data\] ボックスに、新しいバナーを入力します。
  
8.  9.  SMTP 仮想サーバーまたは SMTP サービスをいったん停止してから再開します。
  
10. 
  
バナーが正しく変更されているかどうかを確認するには、仮想サーバーのポート 25 (既定の設定) に Telnet で接続します。"ESMTP MAIL Service, Version: 5.0.2195.1600" のバナーの代わりに新しいバナーが表示されていることを確認します。ただし、SMTP サービス プロパティを通じて入力した完全修飾ドメイン名と日時は、従来どおり表示されます。
  
#### Exchange Domain Servers グループのロックダウン
  
既定のインストールでは、フォレスト内のドメインごとに、Exchange Domain Servers グループが 1 つずつ作成されます。このグループには、ドメイン内の各 Exchange サーバーに対応するコンピュータ アカウントが格納されます。Exchange Domain Servers グループには、フォルダ内のすべての Exchange パブリック フォルダ ストアおよびメールボックス ストアへのアクセスが既定の設定で許可されます。EDSLock スクリプトを実行すると、ストアを提供しているローカル サーバーだけがメールボックス ストアにアクセスできるように、アクセスを制限することができます。
  
**メモ** : EDSLock スクリプトの詳細については、マイクロソフト サポート技術情報 JP313807「\[XADM\] Exchange ドメイン サーバー グループに対する Exchange 2000 のセキュリティを強化する」を参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### Exchange クラスタに関する考慮事項
  
このガイドでは、クラスタ環境内の Exchange 2000 については特に説明していませんが、Exchange 2000 をクラスタ環境内で使用するには、以下のような変更をセキュリティ設定に加える必要があります。
  
-   Windows 2000 クラスタでは NTLMv2 がサポートされていないので、クラスタ サーバーおよびドメイン コントローラ上で NTLM を有効にします。詳細については、マイクロソフト サポート技術情報 JP272129「Windows 2000 クラスタの "参加" ノードでクラスタ サービスが起動しない」を参照してください。
  
-     
-   Exchange バックエンド サーバーのセキュリティ テンプレート内で NT LM Security Support Provider (NTLMSSP) の設定を変更します。NTLMSSP を 0 に設定する必要があります。
  
    MACHINE\\System\\CurrentControlSet\\Control\\LSA\\MSV1\_0\\NtlmMinServerSec=4,0
  
-     
-   Exchange バックエンド サーバーのセキュリティ テンプレート内でクラスタ サービスを有効化します。
  
-     
-   クラスタでは IPSec がサポートされていないので、OWA フロントエンド/バックエンド通信に IPSec を使用しないように設定します。詳細については、マイクロソフト サポート技術情報 Q306677「IPSec Is Not Designed for Failover」(英語情報) を参照してください。
  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### セキュリティ テンプレートのダウンロード
  
[こちらからセキュリティ テンプレートをダウンロードしてください](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=9989d151-5c55-4bd3-a9d2-b95a15c73e92)
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### まとめ
  
エンタープライズのセキュリティを確保するには、Exchange サーバーのセキュリティを強化することが欠かせません。Windows 2000 環境のセキュリティを強化すると共に、この章と前の章に記載されている推奨事項に従えば、Exchange 環境が攻撃にさらされるリスクを大幅に低減することができます。
  
#### 詳細情報
  
-   Windows 2000 Server セキュリティ運用ガイド  
    [http://www.microsoft.com/japan/technet/security/prodtech/  
    windows2000/staysecure/default.mspx](http://www.microsoft.com/japan/technet/security/prodtech/windows2000/staysecure/default.mspx)
  
-     
-   Windows 2000 セキュリティ フィックスがグローバル カタログ サーバーに対して及ぼす影響の詳細  
    <http://support.microsoft.com/default.aspx?scid=kb;ja;jp309622>
  
-     
-   セキュリティ ログに書き込まれるログオン イベントに対して成功の監査を有効化する方法 (英語)  
    [http://support.microsoft.com/default.aspx?scid=kb;en-us;Q316685](http://support.microsoft.com/default.aspx?scid=kb;en-us;q316685)
  
-     
-   ネイティブな Web Storage System イベントの詳細 (英語)  
    http://msdn2.microsoft.com/en-us/library/ms879504.aspx
  
    『Exchange 2000 ソフトウェア開発キット (SDK)』 （英語）
  
    [http://www.microsoft.com/downloads/details.aspx?FamilyId=71A0BB09-1CC9-4EE7-A3B8-5CBD71402EAA&displaylang;=en](http://www.microsoft.com/downloads/details.aspx?familyid=71a0bb09-1cc9-4ee7-a3b8-5cbd71402eaa&displaylang=en)
  
-     
-   IIS Lockdown ツールのダウンロード  
    <http://www.microsoft.com/japan/technet/security/tools/locktool.mspx>
  
-     
-   IIS Lockdown ツールと URLScan のトラブルシューティングおよび構成の詳細  
    <http://support.microsoft.com/default.aspx?scid=kb;ja;jp309677>
  
-     
-   OWAの \[パスワードの変更\] ボタンを無効化する方法  
    <http://support.microsoft.com/default.aspx?scid=kb;ja;jp297121>
  
-     
-   イベント ログ ID 101 の詳細  
    <http://support.microsoft.com/default.aspx?scid=kb;ja;jp259373>
  
-     
-   EDSLock スクリプトの詳細  
    <http://support.microsoft.com/default.aspx?scid=kb;ja;jp313807>
  
-     
-   Windows 2000 クラスタで NTLMv2 がサポートされていないことに関する詳細  
    <http://support.microsoft.com/default.aspx?scid=kb;ja;jp272129>
  
-     
-   OWA フロントエンド/バックエンド通信に IPSec を使用しないように設定する方法 (英語)  
    [http://support.microsoft.com/default.aspx?scid=kb;en-us;Q306677](http://support.microsoft.com/default.aspx?scid=kb;en-us;q306677)
  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 目次
  
-   [概要](https://technet.microsoft.com/ja-jp/library/5adcd128-c106-4554-96f2-05b737609fd6(v=TechNet.10))  
-     
-   [第 1 章 ‐ はじめに](https://technet.microsoft.com/ja-jp/library/2a5c3409-3f1f-48f8-8634-ded56d3667cb(v=TechNet.10))  
-     
-   [第 2 章 ‐ Exchange 環境のセキュリティを確保する](https://technet.microsoft.com/ja-jp/library/460b9ff3-7430-4c17-ac2a-cedb5d768e43(v=TechNet.10))  
-     
-   第 3 章 ‐ 役割に基づいて Exchange 2000 サーバーのセキュリティを強化する  
-     
-   [第 4 章 ‐ Exchange の通信セキュリティを強化する](https://technet.microsoft.com/ja-jp/library/5c43a166-9c33-403d-ad45-66c51e1897f3(v=TechNet.10))  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
