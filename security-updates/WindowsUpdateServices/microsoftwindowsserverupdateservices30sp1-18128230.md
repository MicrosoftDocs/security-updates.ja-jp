---
TOCTitle: 'Microsoft Windows Server Update Services 3.0 SP1 リリース ノート'
Title: 'Microsoft Windows Server Update Services 3.0 SP1 リリース ノート'
ms:assetid: 'a5aa93bf-842b-4ad4-ab0f-fe867843cb02'
ms:contentKeyID: 18128230
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc708525(v=WS.10)'
---

Microsoft Windows Server Update Services 3.0 SP1 リリース ノート
================================================================

これらのリリース ノートには、Microsoft® Windows® Server Update Services (WSUS) 3.0 Service Pack 1 に影響を及ぼす既知の問題、およびこのアプリケーションをインストールするための推奨事項と要件が記載されています。リリース ノートは、次のセクションに分かれています。

-   WSUS 3.0 SP1 サーバーのインストールのシステム要件
-   WSUS 3.0 SP1 サーバーのインストールの構成要件
-   WSUS 3.0 SP1 リモート コンソールのインストールのシステム要件
-   クライアント インストールのシステム要件
-   WSUS 3.0 SP1 サーバーのインストールのソフトウェア要件
-   WSUS 3.0 SP1 サーバーのインストールの最小ディスク領域要件
-   WSUS 3.0 SP1 のアップグレード要件
-   セットアップのコマンドライン パラメータ
-   セットアップの問題
-   アップグレードの問題
-   既知の問題
-   Windows Server® 2008 で使用する WSUS 3.0 SP1
-   Windows Small Business Server 2003 で使用する WSUS 3.0 SP1

WSUS 3.0 SP1 サーバーのインストールのシステム要件
-------------------------------------------------

#### Windows Server 2008 および Windows Server 2003 Service Pack 1 でサポートされる

WSUS 3.0 SP1 サーバーは、Windows Server 2008 および Windows Server 2003 Service Pack 1 でサポートされます。

#### Windows 2000 Server ではサポートされない

Microsoft Windows® 2000 Server は、WSUS 3.0 SP1 サーバーをサポートしないオペレーティング システムです。

#### ターミナル サービスを実行しているサーバーではサポートされない

ターミナル サービスを実行しているサーバー上で WSUS 3.0 SP1 を実行するケースが依然としてあるかもしれませんが、これはサポートされておらず、推奨もされません。リモート SQL Server 実装を使用する構成でターミナル サービスを実行しているサーバー上では、WSUS 3.0 SP1 を実行できません。ターミナル サービス ライセンス サーバー上のリモート カスタム アクション (インストールも含む) はすべて、システム アカウントとして実行されるのに対し、サーバーのシステム アカウントに、リモート SQL Server でのアクセス許可がない可能性があるため、インストールに失敗する可能性があります。

WSUS 3.0 SP1 サーバーのインストールの構成要件
---------------------------------------------

#### IIS のインストールが必要

WSUS 3.0 SP1 には、インターネット インフォメーション サービス (IIS) が必要です。これは既定では、Windows Server 2008 と Microsoft Windows Server 2003 にインストールされません。IIS をインストールしないまま WSUS 3.0 SP1 をインストールしようとすると、Windows Server Update Services Setup により、IIS がインストールされていないことを示すエラー メッセージが表示されます。

#### IIS を IIS 5.0 プロセス分離モードで実行している場合、インストールに失敗する

サーバーを Windows 2000 Server から Windows Server 2003 にアップグレードした場合、IIS は IIS 5.0 プロセス分離モードで実行されている可能性があります。また、IIS 5.0 プロセス分離モードを IIS マネージャで有効にすることも可能です。その結果、インストールに失敗します。IIS 5.0 プロセス分離モードを先に無効にしてから、WSUS 3.0 SP1 をインストールする必要があります。

#### 64 ビット プラットフォーム上に 32 ビット互換モードでインストールされた IIS コンポーネントがあると、インストールに失敗する

64 ビット プラットフォーム上では、いずれの IIS コンポーネントもネイティブ モードでインストールする必要があります。32 ビット互換モードでインストールされた IIS コンポーネントがあると、WSUS 3.0 SP1 のインストールに失敗する可能性があります。

#### プロキシサーバーが HTTP のみ、または HTTP と HTTPS の両方をサポートできる

WSUS 3.0 SP1 では、任意のプロキシ サーバーに HTTP のみをサポートさせることができます。HTTPS を実行する別のプロキシ サーバーを、コマンドライン (**wsusutil configuresslproxy**) で構成してから、WSUS サーバーを構成ウィザードまたは管理コンソールから構成する必要があります。

#### 複数の Web サイトがポート 80 で既に実行されている場合、1 つを残して他をすべて削除してから WSUS をインストールする

複数の Web サイトがポート 80 で既に実行されている場合 (たとえば、Windows® SharePoint® Services)、1 つを残して他をすべて削除してから、WSUS をインストールする必要があります。そうしないと、サーバーのクライアントが自己更新に失敗する可能性があります。

#### インストール時にウイルス対策プログラムを無効にしなければならないことがある

WSUS 3.0 SP1 のインストール時に、ウイルス対策プログラムを事前に無効にしておかないと、インストールに失敗する可能性があります。ウイルス対策プログラムを無効にした後、コンピュータを再起動して、WSUS をインストールします。コンピュータを再起動することにより、インストール プロセスがファイルにアクセスする必要があるときに、ファイルのロックを防ぐことができます。インストールの完了後には、ウイルス対策プログラムを必ず再度有効にしてください。使用しているウイルス対策プログラムとバージョンを無効にした後、再度有効にする具体的な手順については、ベンダの Web サイトにアクセスして確認してください。

> [!NOTE]
> この対応策により、コンピュータやネットワークが、悪意のあるユーザーやウイルスなどの悪意のあるソフトウェアによる攻撃に対して脆弱になる可能性があります。この対応策は推奨事項ではありません。この情報を提供したのは、ユーザー自身の判断の下で行えるようにするためです。この対応策はユーザー自身の責任において実行してください。 

> [!NOTE]
> ウイルス対策プログラムは、コンピュータをウイルスから保護する助けとなることを目的としています。ウイルス対策プログラムを無効にしているときには、信頼できないソースからファイルをダウンロードしたり、そのファイルを開いたりしないでください。また、信頼できない Web サイトにアクセスしたり、メールの添付ファイルを開いたりすることも避けてください。 

#### SQL Server で、ネストされたトリガのオプションを有効にする必要がある

ネストされたトリガのオプションは、既定で有効ですが、SQL Server の管理者が無効にしている可能性があります。

SQL Server データベースを Windows Server Update Services のデータ ストアとして使用する予定である場合、SQL Server の管理者は、ネストされたトリガのオプションがサーバーで有効にされた後に、WSUS 3.0 SP1 の管理者が WSUS 3.0 SP1 をインストールし、セットアップ時にそのデータベースを指定することを確認する必要があります。

WSUS 3.0 SP1 のセットアップ プログラムにより、RECURSIVE\_TRIGGERS オプションが有効になります。これは、データベースに固有のオプションです。しかし、ネストされたトリガのオプションは、有効になりません。こちらは、サーバーのグローバル オプションです。

ネストされたトリガのオプションが有効であるかどうかを確認するには、次のコマンドを使用します。

**sp\_configure 'nested triggers'**

ネストされたトリガのオプションを SQL Server で有効にするには、SQL Server を実行しているコンピュータでバッチ ファイルから次のコマンドを実行します。

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

サーバーに SQL Server Management Studio がない場合、コマンドラインから SQL スクリプトを実行すると良いでしょう。Microsoft SQL Server 2005 コマンドライン クエリ ユーティリティは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=70728) (http://go.microsoft.com/fwlink/?LinkId=70728) から入手できます。開始するには、**sqlcmd** を実行します。

SQL スクリプトを Windows Internal Database に対して実行する場合には、同じダウンロード ページから SQL Server Native Client もダウンロードする必要があります。

#### リモート SQL の制限事項および要件

WSUS 3.0 SP1 では、WSUS 3.0 SP1 アプリケーションの残りの部分をインストールしたコンピュータとは別のコンピュータ上で、データベース ソフトウェアを実行できます。リモート SQL インストールを構成するには、要件がいくつかあります。

-   ドメイン コントローラとして構成されたサーバーを、リモート SQL ペアのバック エンドに使用することはできません。
-   リモート SQL インストールのフロントエンド サーバーになるコンピュータ上で、ターミナル サーバーを実行していてはなりません。
-   バックエンド コンピュータで Windows Server 2003 を実行している場合には、データベース ソフトウェアに少なくとも Microsoft SQL Server 2005 Service Pack 1 ([Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=66143) (http://go.microsoft.com/fwlink/?LinkId=66143) から入手可能) を、Windows Server® 2008 を実行している場合には、同様に SQL Server 2005 Service Pack 2 を使用する必要があります。
-   フロントエンド コンピュータおよびバックエンド コンピュータの両方を、同じ Active Directory ドメインに参加させる必要があります。そうしないと、別々のドメインに存在する場合、WSUS のセットアップを実行する前に、ドメイン間でクロスドメイン信頼を確立する必要があります。
-   WSUS 2.0 を既にリモート SQL 構成にインストールしてあり、WSUS 3.0 SP1 にアップグレードする場合、バックエンド コンピュータから WSUS 2.0 をアンインストール (コントロール パネルの**プログラムの追加と削除**を使用) する必要があります。なお、その間、既存のデータベースはそのまま保持します。次に、SQL Server 2005 SP1 か SP2 をインストールし、既存のデータベースをアップグレードします。最後に、フロントエンド コンピュータに WSUS 3.0 SP1 をインストールします。

WSUS 3.0 SP1 リモート コンソールのインストールのシステム要件
------------------------------------------------------------

WSUS 3.0 SP1 リモート コンソールは、次のプラットフォームにインストールできます。

-   Windows Server 2008
-   Windows Vista® 以上
-   Windows Server 2003 SP1 以上
-   Windows XP SP2 以上

クライアント インストールのシステム要件
---------------------------------------

自動更新は、WSUS のクライアント ソフトウェアです。次のオペレーティング システム上で WSUS と連携できます。

-   Windows Vista 以上
-   Windows Server 2008 以上
-   Microsoft Windows Server 2003 の任意のエディション
-   Microsoft Windows XP Professional SP2 以上
-   Microsoft Windows 2000 Professional SP4、Windows 2000 Server SP4、または Windows 2000 Advanced Server with SP4

WSUS 3.0 SP1 サーバーのインストールのソフトウェア要件
-----------------------------------------------------

Windows Server 2003 SP1 プラットフォームに必要なソフトウェアを、次の表に示します。Windows Server 2008 に必要なソフトウェアは、Windows Server 2008 で WSUS 3.0 SP1 を使用するケースを扱うセクションで説明します。

WSUS 3.0 SP1 のセットアップを実行する前に、WSUS 3.0 SP1 サーバーがこの一覧に記載された要件すべてを確実に満たすようにしてください。これらの更新プログラムのインストール完了時に、コンピュータの再起動を求められたら、再起動を実行してから WSUS 3.0 SP1 のインストールを実行する必要があります。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >要件</th>
<th style="border:1px solid black;" >詳細</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft インターネット インフォメーション サービス (IIS)</td>
<td style="border:1px solid black;">オペレーティング システムからインストールします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework Version 2.0 再頒布可能パッケージ</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=68935">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=68935) で、Microsoft .NET Framework Version 2.0 再頒布可能パッケージ (x86) について確認します。64 ビット プラットフォームの場合は、<a href="http://go.microsoft.com/fwlink/?linkid=70637">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=70637) で、Microsoft .NET Framework Version 2.0 再頒布可能パッケージ (x64) について確認します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 用 Microsoft 管理コンソール 3.0</td>
<td style="border:1px solid black;">これは、WSUS 3.0 SP1 ユーザー インターフェイスを使用するための前提条件です。<a href="http://go.microsoft.com/fwlink/?linkid=70412">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=70412) で、Windows Server 2003 用 Microsoft 管理コンソール 3.0 (KB907265) について確認します。64 ビット プラットフォームの場合は、<a href="http://go.microsoft.com/fwlink/?linkid=70638">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=70638) で、Windows Server 2003 x64 Edition 用 Microsoft 管理コンソール 3.0 (KB907265) について確認します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">これは、WSUS 3.0 SP1 ユーザー インターフェイスを使用するための前提条件です。<a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=70410) で、Microsoft Report Viewer 再頒布可能パッケージ 2005 について確認します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005 (オプション)</td>
<td style="border:1px solid black;">SQL Server の互換バージョンがまだインストールされていない場合、WSUS 3.0 SP1 により Windows Internal Database がインストールされます。SQL Server のフル データベースを使用する予定の場合、Windows Server 2003 では最低でも SQL Server 2005 SP1 (<a href="http://go.microsoft.com/fwlink/?linkid=66143">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=66143)で入手可能)、Windows Server 2008 では SQL Server 2005 SP2 (<a href="http://go.microsoft.com/fwlink/?linkid=84823">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=84823)で入手可能) を使用する必要があります。</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc708525.note(WS.10).gif)注                                                                                                                                                                                                                                                                                                                      |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 以前に WSUS 2.0 がインストールされたことがあり、WSUS 2.0 で現在 SQL Server 2000、SQL Server Desktop Engine 2000、または SQL Server 2005 SP1 (Windows Server 2008 では SQL Server 2005 SP2) より前のいずれかの SQL Server データベースが使用されている場合、WSUS 3.0 SP1 インストール プログラムにより、Windows® Internal Database のインストール、およびデータベースの移行が行われます。 |
  
WSUS 3.0 SP1 サーバーのインストールの最小ディスク領域要件  
---------------------------------------------------------
  
Windows Server Update Services をインストールするための最小ディスク領域要件は、次のとおりです。
  
-   システム パーティション上に 1 GB  
-   データベース ファイルを格納するボリュームには 2 GB  
-   コンテンツを格納するボリュームには 20 GB
  
| ![](images/Cc708525.Important(WS.10).gif)重要                                                                |  
|-------------------------------------------------------------------------------------------------------------------------------------------|  
| WSUS 3.0 SP1 を圧縮ドライブにインストールすることはできません。インストール先に選択したドライブが圧縮されていないことを確認してください。 |
  
WSUS 3.0 SP1 のアップグレード要件  
---------------------------------
  
#### WSUS インストールが正常に実行されていることを確認し、WSUS データベースをバックアップしてから、アップグレードする
  
前のバージョンから WSUS 3.0 SP1 にアップグレードしている場合、現在のインストールが正常に実行されていることを確認し、WSUS データベースをバックアップしてから、アップグレードします。
  
1.  イベント ログに記録されている最近のエラー、ダウンストリーム サーバーとアップストリーム サーバーとの間の同期問題、または報告を行わないクライアントの問題がないかどうかを確認します。続行する前に、これらの問題を必ず解決してください。  
2.  DBCC CHECKDB を実行して、WSUS データベースが正常にインデックス付けされていることを確認すると良いでしょう。DBCC CHECKDB の詳細については、「[DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948)」(http://go.microsoft.com/fwlink/?LinkId=86948) を参照してください。  
3.  WSUS データベースをバックアップします。
  
#### WSUS が使用するポートを手動で変更している場合、アンインストールしてからアップグレードする
  
WSUS のポートを変更するときには、手動で行うのではなく、必ず wsusutil ユーティリティを使用してください。ポートを手動で変更した場合、および以前に Software Update Services 1.0 から WSUS 2.0 にアップグレードした場合には、次の操作を行います。
  
1.  WSUS 3.0 をまだインストールしていない場合、WSUS 2.0 をアンインストールします。その際、データベースとコンテンツはそのまま保持します (WSUS 3.0 を既にインストールしてある場合には、アンインストールします。その際、データベースとコンテンツはそのまま保持します)。  
2.  既定の Web サイトを開始し、SUS 1.0 を一時的に有効にします。ただし、アンインストーラからアクセスできるようにします。  
3.  SUS 1.0 をアンインストールします。  
4.  WSUS 3.0 をインストールします。
  
#### Software Update Services 1.0 は、アンインストールする必要がある
  
Software Update Services 1.0 がインストールされているコンピュータでは、WSUS 3.0 SP1 のインストールに失敗します。Software Update Services 1.0 をアンインストールしてから、WSUS 3.0 SP1 をインストールする必要があります。
  
#### 64 ビットオペレーティング システムでは、WSUS 2.0 から WSUS 3.0 SP1 にアップグレードできない
  
WSUS 2.0 は、64 ビットオペレーティング システムではサポートされません。64 ビットオペレーティング システムでは、WSUS 2.0 から WSUS 3.0 SP1 にアップグレードできません。
  
セットアップのコマンドライン パラメータ  
---------------------------------------
  
WSUS コマンドライン セットアップ プログラムを使用して、WSUS 3.0 SP1 の無人インストールを実行できます。WSUS 3.0 SP1 セットアップで使用できるコマンドライン パラメータを、次の表に示します。
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >オプション</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>/q</strong></td>
<td style="border:1px solid black;">無人インストールを実行します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">製品をアンインストールします。また、Windows Internal Database のインスタンスがインストールされている場合、それもアンインストールします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">前提条件の確認のみ行います。製品のインストールは行わず、システムを調査し、満たしていない前提条件があれば、それを報告します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">コマンドライン パラメータとその説明を表示します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">前のバージョンの WSUS からアップグレードします (SUS 1.0 からはアップグレードしないでください)。このオプションで唯一有効なパラメータは、/q です (無人インストール)。このオプションで唯一有効なプロパティは、DEFAULT_WEBSITE です。</td>
</tr>
</tbody>
</table>
  
WSUS 3.0 SP1 セットアップで使用できるコマンドライン プロパティを、次の表に示します。
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >プロパティ</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">CONTENT_LOCAL</td>
<td style="border:1px solid black;">0 = コンテンツをローカルにホスト、1 = Microsoft Update 上でホスト</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CONTENT_DIR</td>
<td style="border:1px solid black;">コンテンツ ディレクトリへのパス。既定では、<em>WSUSInstallationDrive</em><strong>\WSUS\WSUSContent</strong> です。ここで、<em>WSUSInstallationDrive</em> は、空き領域が最大のローカル ドライブです。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Windows Internal Database のデータ ディレクトリへのパス。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">名前は <em>ServerName</em>\<em>SQLInstanceName</em> の形式で表示される必要があります。データベース インスタンスがローカル マシンにある場合、%COMPUTERNAME% 環境変数を使用します。既存のインスタンスがない場合には、%COMPUTERNAME%\WSUS が既定になります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DEFAULT_WEBSITE</td>
<td style="border:1px solid black;">0 = ポート 8530、1 = ポート 80。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PREREQ_CHECK_LOG</td>
<td style="border:1px solid black;">ログ ファイルのパスおよびファイル名。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CONSOLE_INSTALL</td>
<td style="border:1px solid black;">0 = WSUS サーバーのインストール、1 = コンソールのみインストール。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ENABLE_INVENTORY</td>
<td style="border:1px solid black;">0 = インベントリ機能をインストールしない、1 = インベントリ機能をインストールする。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_DATABASE</td>
<td style="border:1px solid black;">0 = データベースを保持、1 = データベースを削除。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DELETE_CONTENT</td>
<td style="border:1px solid black;">0 = コンテンツ ファイルを保持、1 = コンテンツ ファイルを削除。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_LOGS</td>
<td style="border:1px solid black;">0 = ログ ファイルを保持、1 = ログ ファイルを削除 (/u インストール スイッチと併用)。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0 = 現在のデータベースを使用、1 = データベースを新規作成。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">MSI 進行状況メッセージを返すウィンドウの処理。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1 = Microsoft Update 向上プログラムに参加する、0 = Microsoft Update 向上プログラムに参加しない。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1 = データベースにコンテンツの場所を書き込まない、0 = データベースにコンテンツの場所を書き込む (NLB のため)。</td>
</tr>
</tbody>
</table>
  
#### 使用例
  
```  
WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (install in quiet mode using port 8530) WSUSSetup.exe /q /u (uninstall WSUS)  
```  
| ![](images/Cc708525.Important(WS.10).gif)重要                                                                                                                                           |  
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| WSUS 3.0 SP1 を QUIET モード (/q) でインストールし、コンピュータが前提条件をすべて満たしているわけではない場合、インストールにより WSUSPreReqCheck.xml というファイルが生成され、%TEMP% ディレクトリに保存されます。 |
  
セットアップの問題  
------------------
  
#### WSUS 3.0 SP1 のセットアップ時に、IIS が再起動される
  
WSUS 3.0 SP1 のセットアップ プログラムにより、予告なしに IIS が再起動されます。これにより、組織内の既存の Web サイトが影響を受けることがあります。IIS が実行されていない場合、WSUS 3.0 SP1 のセットアップ プログラムにより開始されます。
  
#### 接続が既存の WSUS データベースに開かれている場合、インストールに失敗することがある
  
既存のインストールから WSUS 3.0 SP1 にアップグレードしており、かつ接続が既存の WSUS データベースに依然として開かれている (たとえば、SQL Server Management Studio が開かれている) 場合、インストールに失敗する可能性があります。接続をすべて閉じてから、WSUS 3.0 SP1 を再度インストールしてください。
  
#### WSUS セットアップにより、データベース ファイルに対して間違ったディレクトリが示される
  
WSUS セットアップでは、\[**インストールの準備が整いました**\] 画面でデータベースの場所がその親ディレクトリにある、と誤って報告されます。たとえば、既定の場所は %systemdrive%\\WSUS\\UpdateServicesDbFiles ですが、この場所は誤って %systemdrive%\\WSUS と表示されます。
  
#### Multilingual User Interface 言語パックをインストール済みの、既定言語が英語以外のコンピュータに WSUS がインストールされる場合、ヘルプは英語以外の既定言語で表示される。
  
Multilingual User Interface 言語パックをインストールした、既定言語が英語以外のコンピュータに対しても、現在のユーザーのロケールが英語の場合、WSUS をインストールできます。UI は英語で表示されますが、ヘルプを英語で表示するには、対応策を施す必要があります。英語版の Help.chm ファイル (*WSUSInstallDir*\\documentation\\mui\\0409\\WSUS30Help.chm)を、メインのドキュメント ディレクトリ (*WSUSInstallDir*\\documentation\\WSUS30Help.chm) にコピーします。この時点で、ヘルプはすべての言語で正しく表示されるはずです。
  
アップグレードの問題  
--------------------
  
#### 失敗したアップグレードからの回復
  
以前のバージョンの WSUS (WSUS 3.0、WSUS 2.0 SP1、または WSUS 2.0) から WSUS 3.0 SP1 にアップグレードしている場合、アップグレードに失敗することがあります。
  
1.  前のバージョンの WSUS を再インストールします。  
2.  アップグレード作業を行う前に作成したバックアップから、データベースを復元します (大半のケースでは、WSUS によりバックアップが自動的に作成されます。場所については、WSUSSetup.log ファイルを参照してください)。  
3.  ログを確認して、失敗の原因を判断し、問題を解決します。  
4.  WSUS のアップグレードを再度試みます。
  
#### 以前のインストールが残した WSUS 3.0 SP1 データベースがある場合、WSUS 2.0 から WSUS 3.0 SP1 にアップグレードできない
  
WSUS 3.0 SP1 をインストールした後に、WSUS 2.0 を再インストールしたことがある場合、コンピュータから WSUS 3.0 SP1 のデータベースを削除してから、WSUS 3.0 SP1 を再インストールする必要があります。
  
#### WSUS 3.0 SP1 へのアップグレード前にコンピュータ名を変更すると、アップグレードに失敗することがある
  
WSUS 2.0 をインストールした後、WSUS 3.0 SP1 にアップグレードする前にコンピュータ名を変更すると、アップグレードに失敗します。
  
次のスクリプトを使用して、ASPNET および WSUS Administrators の各グループの削除と再追加を行ってください。その後、アップグレードを再度実行します。
  
*&lt;DBLocation&gt;* はデータベースのインストール先フォルダに、*&lt;ContentDirectory&gt;* はローカル ストレージ フォルダに置き換える必要があります。
  
```  
sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=name from sysusers WHERE name like '%ASPNET' EXEC sp\_revokedbaccess @asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=name from sysusers WHERE name like '%WSUS Administrators' EXEC sp\_revokedbaccess @wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=HOST\_NAME()+'\\ASPNET' EXEC sp\_grantlogin @asplogin EXEC sp\_grantdbaccess @asplogin EXEC sp\_addrolemember webService,@asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=HOST\_NAME()+'\\WSUS Administrators' EXEC sp\_grantlogin @wsusadminslogin EXEC sp\_grantdbaccess @wsusadminslogin EXEC sp\_addrolemember webService,@wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "backup database SUSDB to disk=N'*&lt;ContentDirectory&gt;*\\SUSDB.Dat' with init"  
```
  
#### セットアップにより、以前のデータベース バックアップが上書きされる
  
WSUS 3.0 SP1 のセットアップ プログラムにより、データベースが既定のディレクトリ (*drive*\\WSUS) に追加されます (ここで、*drive* は空き領域が最大のローカル NTFS ドライブ)。データベース バックアップがこのディレクトリにある場合、上書きされることがあります。管理者は現在のバージョンのデータベースのバックアップを別の場所に保存してから、WSUS 3.0 SP1 にアップグレードする必要があります。
  
#### WSUS 2.0 上で、MSDE から SQL Server 2000 または SQL Server 2005 に移行した場合、レジストリ値を変更する必要がある
  
WSUS 2.0 をインストール済みで、SQL Server 2000 か SQL Server 2005 へ移行した場合、**HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** の値を 1 から 0 に変更する必要があります。変更しないで WSUS 3.0 SP1 にアップグレードしようとすると、失敗します。
  
#### WSUS 2.0 のセットアップを開始してキャンセルすると、WSUS のレジストリ キーが削除される
  
WSUS 2.0 のセットアップを開始した後でキャンセルすると、WSUS のレジストリ キーが削除されます。WSUS 3.0 SP1 を既にインストールしてある場合、これにより問題が生じることがあります。WSUS 2.0 のアンインストールを開始した後にキャンセルし、その後 WSUS 2.0 から WSUS 3.0 SP1 にアップグレードしようとしたときにも、同じ問題が生じます。
  
#### WSUS 3.0 SP1 をアンインストールする際にログ ファイルをそのまま残しておくと、再インストール後に正しいアクセス許可を持てなくなる
  
WSUS 3.0 SP1 をアンインストールする際に、インストールのログ ファイルを保持するオプションがあります。WSUS 3.0 SP1 を再インストールすると、この古いログ ファイルはアクセス許可 (通常はWSUS Administrators 向けのみ) を失います。これらのログ ファイルに対するアクセス許可を復元する必要があります。
  
#### WSUS 2.0 クライアントにステータスが "該当なし" の更新プログラムがある場合、WSUS 3.0 SP1 にアップグレードした後しばらくの間は、ステータスが "不明" とされる
  
WSUS 2.0 サーバーに、ステータスが**該当なし**の更新プログラムを持つクライアントがある場合、サーバーが WSUS 3.0 SP1 にアップグレードされた後しばらくの間は、これらの更新プログラムのステータスが**不明**とされます。更新状態は、クライアントが次回検索を行った後に、**該当なし**に戻ります。
  
既知の問題  
----------
  
#### 複数のダウンロード エラーまたは繰り返し発生するクライアント同期の失敗のトラブルシューティング
  
WSUS 3.0 SP1 クライアントが、複数のダウンロード エラーを報告したり、長期にわたって WSUS 3.0 SP1 サーバーとの同期に失敗する場合、クライアントのダウンロード キャッシュが破損している可能性があります。この状態から回復するには、ファイル システムからクライアントのダウンロード キャッシュを削除してみます。
  
クライアントのダウンロード キャッシュを削除するには
  
1.  クライアント コンピュータ上で次の場所にあるファイルおよびサブディレクトリをすべて削除します : **%windir%\\SoftwareDistribution\\Download**  
2.  クライアント コンピュータと WSUS 3.0 SP1 との同期を再度実行し、更新プログラムのインストールを試みます。このときには、次のエラーが表示されて失敗するはずです :**WU\_E\_DM\_NOTDOWNLOADED, "更新プログラムはダウンロードされていません。"**  
3.  この失敗の後、クライアント コンピュータはダウンロードを自動的に再開し、インストールを続行できるようになります。
  
#### 同期に失敗した場合、同期をやり直す
  
同期に失敗した場合、トラブルシューティングとして最初に行うべきことは、サーバーとの同期を再度試みることです。それ以降の同期にも失敗する場合には、[「Windows Server Update Services 3.0 Operations Guide」](http://go.microsoft.com/fwlink/?linkid=81072)(http://go.microsoft.com/fwlink/?LinkId=81072) のトラブルシューティング情報を参照してください。
  
#### データベースにある WSUS 3.0 SP1 構成を直接変更することは、サポートされていない
  
Windows Server Update Services では、その構成データを SQL Server データベースに格納します。しかし、このデータベースに直接アクセスして構成データを変更することは、サポートされていません。データベースに直接アクセスして WSUS 3.0 SP1 の構成を変更しないでください。変更するには、WSUS 3.0 SP1 コンソールを使用するか、WSUS 3.0 SP1 API を呼び出します。
  
#### ディスク クォータが有効の場合、ダウンロードの失敗がすぐには報告されない
  
ディスク クォータが有効で、クォータに達した場合、WSUS サーバーで更新プログラムのダウンロードに失敗しても、すぐには報告されないことがあります。この問題を回避するには、ディスク クォータを無効にするか、クォータを増やします。
  
#### SSL を使用して WSUS 3.0 SP1 を展開すると、エラー コード 0x8024400a を返して、クライアント コンピュータが停止することがある
  
SSL を使用して WSUS 3.0 SP1 サーバーと通信すると、エラー コード 0x8024400a を返して、クライアント コンピュータが停止することがあります。この問題に対処した更新プログラムについては、[KB 905422](http://go.microsoft.com/fwlink/?linkid=70593) (http://go.microsoft.com/fwlink/?LinkId=70593) を参照してください。
  
#### WSUS をアンインストールしても、WSUS Administrators ドメイン アカウントは削除されない
  
WSUS Administrators グループは、ドメイン コントローラでのドメイン アカウント (ローカル アカウントではなく) として作成されます。そのため、このドメイン アカウントを使用するインストールはすべて、WSUS のアンインストール時にアカウントが削除されると、無効になります。したがって、WSUS をアンインストールしても、WSUS Administrators ドメイン アカウントは削除されません。
  
#### ダウンストリーム サーバーをアップストリーム サーバーに変換すると、カタログ サイトの更新プログラムを再度インポートする必要がある
  
ダウンストリーム サーバーをアップストリーム サーバーに昇格すると、カタログ サイトの更新プログラムをすべて再度インポートする必要があります。そうしないと、サイトはこのサーバーに対する新しいカタログ サイトの更新プログラムの改定に失敗します。
  
#### SSL を備えた IIS を使用している場合、\[保護されたチャンネル (SSL) を要求する\] をオンにしない限り、暗号化しないアクセスが依然として可能となる
  
証明書をインストールして、SSL を使用するよう IIS をセットアップすると、オプション \[**保護されたチャンネル (SSL) を要求する**\] をオンにしない限り、暗号化されていない HTTP を介してサイトにアクセスできてしまいます。詳細については、[IIS](http://go.microsoft.com/fwlink/?linkid=98084) のドキュメント (http://go.microsoft.com/fwlink/?LinkId=98084) を参照してください。
  
#### %windir%\\TEMP フォルダへの読み取り/書き込みアクセス許可がないと、カタログ サイトのインポートに失敗することがある
  
カタログ サイトをインポートするとき、Network Service アカウントに %windir%\\TEMP フォルダへの読み取り/書き込みアクセス許可がないと、次のようなエラー メッセージが表示され、インポートに失敗することがあります : サーバーが要求を処理できませんでした。---&gt; ファイル "C:\\WINDOWS\\TEMP\\*tempFileName*.dll" が見つかりません。
  
#### WSUS 3.0 SP1 と WSUS 2.0 を実行するダウンストリーム レプリカ サーバーとの間で同期する際、パフォーマンスが低下することがある
  
WSUS 3.0 SP1 をアップストリーム サーバーにインストールし、WSUS 2.0 を実行するダウンストリーム レプリカ サーバーと同期しようとすると、パフォーマンスの問題が発生することがあります。この問題に対処するには、[KB 910847](http://go.microsoft.com/fwlink/?linkid=70669) (http://go.microsoft.com/fwlink/?LinkId=70669) を参照してください。
  
#### メール サーバーがダウンしているか到達できない場合、メール通知が予告なしに停止する
  
ネットワークのメール サーバーがオフラインである場合、WSUS 3.0 SP1 は予告なしに、メール通知の送信を停止します。ただし、イベント ログにイベント 10052 (HealthCoreEmailNotificationRed) を書き込みます。
  
#### アップストリーム サーバーの設定の変更が、ダウンストリーム サーバーにすぐにはプッシュされない
  
アップストリーム サーバーの構成が変更されても、この構成の変更が実際に反映されるまでに、時間がしばらくかかることがあります。たとえば、別の言語を選択するなどしてアップストリーム サーバーの設定を変更し、ダウンストリーム サーバーで同期をすぐにトリガしても、変更は反映されません。その代わり、スケジュールされた次回の同期のときに、ダウンストリーム サーバーにプッシュされます。待ち時間は、アップストリーム サーバー上に存在する更新内容の件数に応じて増加します。
  
#### WSUS 3.0 SP1 をアンインストールしても、データベース インスタンスはアンインストールされない
  
WSUS 3.0 SP1 をアンインストールしても、データベース インスタンスはアンインストールされません。インスタンスは複数のアプリケーションが共有している可能性があるので、削除すると、他のアプリケーションが停止してしまいます。
  
Windows Internal Database をアンインストールする必要がある場合、次のコマンドでアプリケーションをアンインストールできます。
  
(32 ビット プラットフォームの場合)
  
```  
msiexec /x {CEB5780F-1A70-44A9-850F-DE6C4F6AA8FB} callerid=ocsetup.exe  
```  
(64 ビット プラットフォームの場合)
  
```  
msiexec /x {BDD79957-5801-4A2D-B09E-852E7FA64D01} callerid=ocsetup.exe  
```  
Windows Server 2008 から Windows Internal Database Service Pack 2 をアンインストールするには、サーバー マネージャを使用します。
  
ただし、アプリケーションを削除しても、既定の .mdf および .ldf の各ファイルは削除されないことがあります。その結果、それ以降の WSUS 3.0 SP1 のインストールに失敗します。これらのファイルは、%windir%\\SYSMSI\\SSEE ディレクトリから削除できます。
  
#### ダウンストリーム サーバーがアップストリーム サーバーを変更すると、ステータスが "不明" の更新プログラムが、"該当なし" として報告される
  
ダウンストリーム サーバーが別のアップストリーム サーバーから同期を開始すると、ステータスが**不明**の更新プログラムが、新しいアップストリーム サーバーで**該当なし**として報告されます。このステータスは一時的なものであり、ダウンストリーム サーバーが次回ステータスを報告するとき、クライアントの同期が完了した後に、訂正されます。
  
#### 1 つのリモート コンソールから複数台のサーバー上でサーバー クリーンアップ ウィザードを実行する場合、1 台のサーバーでタイムアウトすると、すべてのサーバーとの接続が失われる
  
1 つのリモート コンソールから複数台のサーバー上でサーバー クリーンアップ ウィザードを実行できます。ただし、いずれか 1 台のサーバーでクリーンアップ プロセスがタイムアウトすると、コンソールはすべてのサーバーとの接続を失います。データは失われませんが、管理者は各サーバーとのリモート接続をリセットする必要があります。
  
#### 立て続けに接続の開始と停止を行うと、構成ウィザードにエラー メッセージ "同期エラーはありませんでした" が表示される
  
WSUS を構成する際には、サーバーについての基本情報を転送するために、アップストリーム サーバー (Microsoft Update かイントラネットのアップストリーム サーバー) に接続する必要があります。\[**接続を開始**\] をクリックした直後に \[**接続を停止**\] をクリックすると、誤ってエラー メッセージ "同期エラーはありませんでした" が表示されます。
  
Windows Server 2008 で使用する WSUS 3.0 SP1  
-------------------------------------------
  
#### サポート対象のバージョン
  
WSUS 3.0 SP1 は、32 ビットと 64 ビットのバージョンの Windows Server 2008 をサポートします。
  
#### 前提条件
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >要件</th>
<th style="border:1px solid black;" >詳細</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft インターネット インフォメーション サービス (IIS)</td>
<td style="border:1px solid black;">オペレーティング システムからインストールします。次のコンポーネントが有効であることを確認します。
<ul>
<li>Windows 認証<br />
<br />
</li>
<li>静的コンテンツ<br />
<br />
</li>
<li>ASP.NET<br />
<br />
</li>
<li>6.0 管理互換<br />
<br />
</li>
<li>6.0 IIS Metabase Compatibility<br />
<br />
</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework Version 2.0 再頒布可能パッケージ (x86)</td>
<td style="border:1px solid black;">Windows Server 2008 では不要です。オペレーティング システムの一部として既にインストールされているからです。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft 管理コンソール 3.0</td>
<td style="border:1px solid black;">Windows Server 2008 では不要です。オペレーティング システムの一部として既にインストールされているからです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">これは、WSUS ユーザー インターフェイスを使用するための前提条件です。<a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=70410) で、Microsoft Report Viewer 再頒布可能パッケージ 2005 について確認します。</td>
</tr>
</tbody>
</table>
  
#### セキュリティ構成ウィザードの使用
  
Windows Server 2008 では、セキュリティ構成ウィザード (SCW) を実行する際に、WSUS ロールを選択し、その依存関係を有効にすることができます。SCW を実行するには、\[**スタート**\] ボタンをクリックし、\[**管理ツール**\] をポイントします。次に、\[**セキュリティ構成ウィザード**\] をクリックします。
  
SCW を WSUS ロールと併用する際には、次の問題が生じることが知られています。
  
-   **WSUS で使用されていなくても、Windows Internal Database サービスが有効にされます。**Windows Internal Database か SQL Server データベースのいずれか一方のデータベースを使用するよう、WSUS を構成します。WSUS が SQL Server と一緒にインストールされており、SCW で WSUS ロールを選択すると、Windows Internal Database サービスが有効になります。これは、サービスがインストールされていても WSUS で使用されていない場合であっても、当てはまります。Windows Internal Database ではなく、SQL Server データベースを使用している場合、Windows Internal Database サービスを無効にする必要があります。  
-   **カスタム Web サイトでは、WSUS のファイアウォール ルールは、既定で選択されません。**WSUS をカスタム Web サイト (ポート 8530 または 8531) にインストールする場合、SCW で WSUS ロールを選択しても、必要なファイアウォール ルールは、自動的には選択されません。WSUS サーバーに Secure Sockets Layer (SSL) が構成されているかどうかに基づいて、WSUS の該当するファイアウォール ルールを有効にする必要があります。
  
Windows Small Business Server 2003 で使用する WSUS 3.0 SP1  
----------------------------------------------------------
  
#### IIS 仮想ルートが特定の IP アドレスまたはドメイン名に限定されている場合、WSUS 3.0 SP1 は自己を更新できない
  
Windows Small Business Server の一部のインストールでは、既定の IIS Web サイトの **IP アドレスおよびドメイン名の設定に制限**があります。その場合、サーバー上の Windows Update クライアントは、自己を更新できない可能性があります。
  
#### WSUS 3.0 SP1 を Small Business Server にインストールする際に発生する統合の問題
  
-   Windows Small Business Server 2003 で ISA プロキシ サーバーを使用してインターネットに接続する場合、\[**設定**\] ユーザー インターフェイスに**プロキシ サーバー設定、プロキシ サーバー名、およびポート**を入力する必要があります。  
-   ISA が Windows 認証を使用している場合、プロキシ サーバーの証明書を *DOMAIN*\\*user* の形式で入力し、ユーザーを Internet Users グループのメンバとする必要があります。
  
#### Windows SBS ウィザードを使用しないでネットワークにサブネットを追加した場合、この手順を実行する必要がある
  
WSUS サーバー セットアップ プロセスにより、SelfUpdate および ClientWebService という 2 つの IIS vroot がサーバーにインストールされます。また、既定の Web サイト (ポート 80) のホーム ディレクトリの下に、ファイルがいくつか配置されます。これにより、クライアント コンピュータはこの既定の Web サイトを介して自己を更新できます。既定では、既定の Web サイトは localhost 以外の IP アドレスへのアクセス、およびサーバーに関連付けられた特定のサブネットへのアクセスは、すべて拒否するよう構成されています。その結果、localhost にないか、またはこれら特定のサブネットにあるクライアント コンピュータは、自己を更新できません。Microsoft Windows Small Business Server 2003 (Windows SBS) ウィザードを使用しないで、ネットワークにサブネットを追加した場合、次の手順を実行する必要があります。
  
1.  \[サーバー管理\] で、\[**詳細管理**\]、\[**インターネット インフォメーション サービス**\]、\[**Web サイト**\]、\[**既定の Web サイト**\] の順に展開し、\[**Selfupdate**\] 仮想ディレクトリを右クリックして、\[**プロパティ**\] をクリックします。  
2.  \[**ディレクトリ セキュリティ**\] をクリックします。  
3.  \[**IP アドレスとドメイン名の制限**\] で、\[**編集**\] をクリックし、\[**許可する**\] をクリックします。  
4.  \[**OK**\] をクリックし、\[**ClientWebService**\] 仮想ディレクトリを右クリックして、\[**プロパティ**\] をクリックします。  
5.  \[**ディレクトリ セキュリティ**\] をクリックします。  
6.  \[**IP アドレスとドメイン名の制限**\] で、\[**編集**\] をクリックし、\[**許可する**\] をクリックします。
  
著作権情報  
----------
  
URL およびその他のインターネット Web サイトの参照を含め、このドキュメント内の情報は予告なしに変更される場合があります。特に断りのない限り、例に使用されている会社、組織、製品、ドメイン名、電子メール アドレス、ロゴ、人物、場所、出来事はすべて架空のものです。実在する会社、組織、製品、ドメイン名、電子メール アドレス、ロゴ、人物、場所、出来事とのかかわりを意図するものではなく、推測すべきものではありません。お客様ご自身の責任において、適用されるすべての著作権関連法規に従ったご使用を願います。このドキュメントのいかなる部分も、米国 Microsoft Corporation の書面による許諾を受けることなく、その目的を問わず、どのような形態であっても、複製または譲渡することは禁じられています。ここでいう形態とは、複写や記録など、電子的な、または物理的なすべての手段を含みます。ただしこれは、著作権法上のお客様の権利を制限するものではありません。
  
マイクロソフトは、このドキュメントに記載されている内容に関し、特許、特許申請、商標、著作権、またはその他の無体財産権を有する場合があります。別途マイクロソフトのライセンス契約上に明示の規定のない限り、このドキュメントはこれらの特許、商標、著作権、またはその他の無体財産権に関する権利をお客様に許諾するものではありません。
  
© 2007 Microsoft Corporation. All rights reserved.
  
Microsoft、SQL Server、Windows、および Windows Server は、米国 Microsoft Corporation の米国およびその他の国における登録商標または商標です。
  
その他すべての商標は、各社が所有する商標です。
