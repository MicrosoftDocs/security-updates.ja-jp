---
TOCTitle: 'Microsoft Windows Server Update Services 3.0 リリース ノート'
Title: 'Microsoft Windows Server Update Services 3.0 リリース ノート'
ms:assetid: '94d1385f-4872-4c29-8822-3a4ec5e45ae4'
ms:contentKeyID: 18128195
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc708491(v=WS.10)'
---

Microsoft Windows Server Update Services 3.0 リリース ノート
============================================================

このリリース ノートでは、Microsoft® Windows® Server Update Services (WSUS) 3.0 に影響する既知の問題と、このアプリケーションをインストールするための推奨事項および要件について説明します。このリリース ノートには、次のセクションが含まれています。

-   WSUS 3.0 サーバー インストールのシステム要件
-   WSUS 3.0 サーバー インストールの構成要件
-   WSUS 3.0 リモート コンソール インストールのシステム要件
-   WSUS 3.0 リモート コンソールの構成要件
-   クライアント インストールのシステム要件
-   WSUS 3.0 サーバー インストールのソフトウェア要件
-   WSUS 3.0 サーバー インストールのディスク領域の最小要件
-   WSUS 3.0 アップグレード要件
-   セットアップ コマンド ライン パラメータ
-   セットアップとアップグレードの問題
-   既知の問題
-   Windows Server® 2008 にインストールした WSUS 3.0
-   Windows Small Business Server 2003 にインストールした WSUS 3.0

| ![](images/Cc708491.note(WS.10).gif)注                                                                                                                                                                                             |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| このドキュメントのコピーは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=71220) ([http://go.microsoft.com/fwlink/?LinkId=71220](http://go.microsoft.com/fwlink/?linkid=71220)、英語情報の場合があります) からダウンロードできます。 |

重要な構成の問題 : 構成ウィザードでプロキシ サーバー パスワードを上書きする必要があります。
-------------------------------------------------------------------------------------------

ユーザー名とパスワードによる認証を要求するプロキシ サーバーを使用している場合、WSUS サーバー構成ウィザードを実行するときにプロキシ サーバー パスワードを上書きしないと、WSUS サーバーは更新プログラムの同期に失敗します。構成ウィザードはセットアップの最後に自動的に起動するため、この問題が原因で、古いバージョンの WSUS から WSUS 3.0 にアップグレードした後に同期エラーが発生することがあります。

この問題を回避するには、アップグレード後に構成ウィザードをキャンセルするか、構成ウィザードの実行時に正しいプロキシ パスワードを再入力します。この問題が発生した後で回復するには、\[オプション\] ページの \[更新元\] と \[プロキシ サーバー\] に移動し、プロキシ パスワードを再入力してから、設定を保存します。

WSUS 3.0 サーバー インストールのシステム要件
--------------------------------------------

#### WSUS 3.0 サーバーは、Windows Server 2003 Service Pack 1 および Windows Server 2008 でサポートされています。

WSUS 3.0 サーバーは、Windows Server 2003 Service Pack 1 および Windows Server 2008 でサポートされています。

#### WSUS 3.0 サーバーの Windows 2000 Server での実行はサポートされない

Microsoft Windows® 2000 Server は WSUS 3.0 サーバーに対応しているオペレーティング システムではありません。

#### ターミナル サービスを実行しているサーバーでは WSUS 3.0 はサポートされない

ターミナル サービスを実行しているサーバーでも WSUS 3.0 を実行できる場合もありますが、これはサポートされていません。またお勧めしません。リモート SQL Server の実装を使用している構成の場合、ターミナル サービスを実行しているサーバーでは WSUS 3.0 は実行できません。ターミナル サーバーのライセンス サーバー上でのリモート カスタム操作 (インストールを含む) はすべてシステム アカウントとして実行され、サーバーのシステム アカウントにリモート SQL Server のアクセス許可がない場合があるので、インストールに失敗します。

WSUS 3.0 サーバー インストールの構成要件
----------------------------------------

#### IIS をインストールする必要がある

Microsoft Windows Server Update Services 3.0 を使用するには、インターネット インフォメーション サービス (IIS) が必要です。IIS は、既定では Microsoft Windows Server 2003 または Windows Server 2008 にはインストールされません。IIS なしで WSUS 3.0 をインストールしようとすると、Windows Server Update Services のセットアップ画面で、IIS がインストールされていないことを通知するエラー メッセージが表示されます。

#### IIS が IIS 5.0 分離モードで実行されている場合にインストールが失敗する

サーバーを Windows 2000 Server から Windows Server 2003 にアップグレードした場合、IIS は IIS 5.0 互換モードで実行されています。IIS マネージャで IIS 5.0 分離モードを有効にすることもできます。この場合インストールは失敗します。WSUS 3.0 をインストールする前に、IIS 5.0 分離モードを無効にする必要があります。

#### 64 ビットのプラットフォームに IIS コンポーネントが 32 ビット互換モードでインストールされていると、WSUS 3.0 のインストールに失敗する

IIS のすべてのコンポーネントは 64 ビットのプラットフォームにネイティブ モードでインストールする必要があります。IIS のいずれかのコンポーネントが 32 ビット互換モードでインストールされていると、WSUS 3.0 のインストールに失敗することがあります。

#### プロキシ サーバーは HTTP と HTTPS の両方をサポートする必要がある

ルート WSUS サーバー (Microsoft Update から直接更新を取得する WSUS サーバー) を構成する際、WSUS サーバーとインターネットの間にプロキシ サーバーがある場合は、そのプロキシ サーバーが HTTP と HTTPS の両方をサポートしている必要があります。

#### ポート 80 で複数の Web サイトが実行済みの場合、WSUS をインストールする前に 1 つを残してその他のサイトをすべて削除する

ポート 80 で複数の Web サイトを実行している場合 (Windows® SharePoint® Services など)、WSUS をインストールする前に、1 つを残してその他すべてのサイトを削除する必要があります。この作業を行わない場合、サーバー クライアントが自己更新に失敗します。

#### WSUS 3.0 のインストール時にウイルス対策プログラムを無効にする必要がある

WSUS 3.0 をインストールするとき、ウイルス対策プログラムを無効にしないとインストールを正常に実行できない場合があります。ウイルス対策プログラムを無効にし、コンピュータを再起動してから WSUS のインストールを開始してください。コンピュータを再起動することにより、インストール プロセスでアクセスするファイルがロックされるのを防ぎます。インストールの完了後、再びウイルス対策プログラムを有効にしてください。ウイルス対策プログラムとバージョンを無効にしてから再び有効にする方法については、ウイルス対策プログラムのベンダの Web サイトを参照してください。

| ![](images/Cc708491.Caution(WS.10).gif)注意                                                                                                                                                                                                                               |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| この回避策によって、コンピュータやネットワークが悪意のあるユーザーや、ウイルスなどの悪意のあるソフトウェアの攻撃を受けやすくなる可能性があります。したがって、この回避策を推奨できませんが、ユーザーの判断でこの方法を採用できるように情報を提供しています。この回避策は各自の責任で使用してください。 |

| ![](images/Cc708491.note(WS.10).gif)注                                                                                                                                                                                                                                     |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ウイルス対策プログラムは、コンピュータをウイルスから保護するのが目的です。ウイルス対策プログラムが無効のときに、信頼していない発行元からのファイルをダウンロードしたり開いたりしないでください。同様に、信頼していない Web サイトにアクセスしたり、電子メールの添付ファイルを開いたりしないでください。 |

#### WSUS 3.0 では、SQL Server でトリガのネスト オプションを有効にする必要がある

トリガのネスト オプションは既定では有効になっていますが、SQL Server 管理者が無効にしている場合があります。

SQL Server データベースを Windows Server Update Services のデータ ストアとして使用する場合は、WSUS 3.0 の管理者が WSUS 3.0 をインストールしてセットアップ中にこのデータベースを指定する前に、SQL Server の管理者がこのサーバー上でトリガのネスト オプションが有効であることを確認する必要があります。

WSUS 3.0 セットアップを実行すると、RECURSIVE\_TRIGGERS オプションが有効になります。これはデータベースに固有のオプションです。ただし、トリガのネスト オプションはサーバーのグローバル オプションであるため有効になりません。

トリガのネスト オプションが有効になっているかどうかを確認するには、次のコマンドを実行します。

**sp\_configure 'nested triggers'**

SQL Server でトリガのネスト オプションを有効にするには、SQL Server を実行しているコンピュータでバッチ ファイルから次のコマンドを実行します。

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

サーバーに SQL Server Management Studio がない場合は、コマンド ラインから SQL スクリプトを実行できます。Microsoft SQL Server 2005 のコマンド ライン クエリ ユーティリティは [Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=70728) (http://go.microsoft.com/fwlink/?LinkId=70728、英語情報の場合があります) から入手できます。最初に **sqlcmd** を実行してください。

Windows Internal Database に対して SQL スクリプトを実行する場合は、同じダウンロード ページから SQL Native Client をダウンロードする必要があります。

#### リモート SQL の制限事項と要件

WSUS 3.0 は、他の WSUS アプリケーションを実行するコンピュータ以外のコンピュータ上では、データベース ソフトウェアの実行をサポートします。リモート SQL インストールを構成するための要件がいくつかあります。

-   ドメイン コントローラとして構成されたサーバーをリモート SQL ペアのバックエンドとして使用することはできません。
-   リモート SQL インストールのフロントエンド サーバーとして使用するコンピュータでターミナル サーバーを実行しないでください。
-   バックエンド コンピュータで Windows Server 2003 を実行している場合は、そのコンピュータのデータベース ソフトウェアに最低でも Microsoft SQL Server 2005 Service Pack 1 を使用する必要があります。これは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=66143) (http://go.microsoft.com/fwlink/?LinkId=66143) から入手できます。Windows Server® 2008 を実行している場合は SQL Server 2005 Service Pack 2 が必要です。
-   フロントエンド コンピュータとバックエンド コンピュータの両方が同一の Active Directory ドメインに参加している必要があります。それぞれ別のドメインに属している場合、WSUS セットアップを実行する前にクロスドメインの信頼関係を確立する必要があります。
-   リモート SQL 構成でインストールした WSUS 2.0 を WSUS 3.0 にアップグレードする場合は、既存のデータベースを保持したまま、バックエンド コンピュータで WSUS 2.0 をアンインストールする必要があります (コントロール パネルの \[プログラムの追加と削除\] を使用)。次に、SQL Server 2005 SP1 または SP2 をインストールして既存のデータベースをアップグレードします。最後に、フロントエンド コンピュータに WSUS 3.0 をインストールします。

#### 特定の Internet Explorer 7 のプレ リリース版およびターミナル サービスが既にインストールされている場合は、WSUS をインストールできません。

Internet Explorer 7 の特定のリリース候補がターミナル サービスと共に存在する場合は、WSUS のセットアップが失敗します。

WSUS 3.0 リモート コンソール インストールのシステム要件
-------------------------------------------------------

WSUS 3.0 リモート コンソールは、次のプラットフォームにインストールできます。

-   Windows Server 2008
-   Windows Vista®
-   Windows Server 2003 SP1
-   Windows XP SP2

WSUS 3.0 リモート コンソールの構成要件
--------------------------------------

#### リモート管理コンソールと WSUS 3.0 サーバーの間にブロードバンド接続を使用する必要があります。

WSUS 3.0 サーバーとリモート管理コンソールの間の接続がナローバンドの WAN 接続の場合、パフォーマンス的に問題があります。更新プログラムとコンピュータの表示にフィルタを適用することで、表示される更新プログラムとコンピュータの数を制限できますが、リモート管理コンソールと WSUS 3.0 サーバーの間の接続にブロードバンド接続を使用することをお勧めします。リモート コンソールにパフォーマンス上の問題がある場合、ターミナル サーバーを使用してリモート管理を行うことをお勧めします。

クライアント インストールのシステム要件
---------------------------------------

自動更新は WSUS クライアント ソフトウェアです。次のどのオペレーティング システム上の WSUS でも使用できます。

-   Windows Vista
-   Windows Server 2008
-   Microsoft Windows Server 2003 の任意のエディション
-   Microsoft Windows XP Professional SP2
-   Microsoft Windows 2000 Professional SP4、Windows 2000 Server SP4、または Windows 2000 Advanced Server SP4

WSUS 3.0 サーバー インストールのソフトウェア要件
------------------------------------------------

次の表に、Windows Server 2003 SP1 プラットフォームに必要なソフトウェアを示します。Windows Server 2008 に必要なソフトウェアについては、「Windows Server 2008 にインストールした WSUS 3.0」のセクションに記載されています。

WSUS 3.0 セットアップを実行する前に、WSUS 3.0 サーバーがこの要件の一覧を満たしていることを確認してください。インストール完了時に、いずれかの更新プログラムによりコンピュータの再起動が必要な場合は、再起動してから WSUS 3.0 をインストールしてください。

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
<td style="border:1px solid black;">オペレーティング システムからインストールします。
「問題 1 : IIS をインストールする必要がある」を参照してください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework Version 2.0 再頒布可能パッケージ (x86)</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=68935">Microsoft ダウンロード センター</a>で、Microsoft .NET Framework Version 2.0 再頒布可能パッケージ (x86) についてのページ (http://go.microsoft.com/fwlink/?LinkId=68935、英語情報の場合があります) を参照してください。64 ビット プラットフォームの場合は、<a href="http://go.microsoft.com/fwlink/?linkid=70637">Microsoft ダウンロード センター</a>で、Microsoft .NET Framework Version 2.0 再頒布可能パッケージ (x64) についてのページ (http://go.microsoft.com/fwlink/?LinkId=70637、英語情報の場合があります) を参照してください。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 用の Microsoft 管理コンソール 3.0</td>
<td style="border:1px solid black;">これは、WSUS 3.0 UI を使用するための前提条件です。<a href="http://go.microsoft.com/fwlink/?linkid=70412">Microsoft ダウンロード センター</a>で、Windows Server 2003 用の Microsoft 管理コンソール 3.0 についてのページ (KB907265、http://go.microsoft.com/fwlink/?LinkId=70412、英語情報の場合があります) を参照してください。64 ビット プラットフォームの場合は、<a href="http://go.microsoft.com/fwlink/?linkid=70638">Microsoft ダウンロード センター</a>で、Windows Server 2003 x64 Edition 用の Microsoft 管理コンソール 3.0 についてのページ (KB907265、http://go.microsoft.com/fwlink/?LinkId=70638、英語情報の場合があります) を参照してください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">これは、WSUS 3.0 UI を使用するための前提条件です。<a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft ダウンロード センター</a>で、Microsoft Report Viewer 再頒布可能パッケージ 2005 についてのページ (http://go.microsoft.com/fwlink/?LinkId=70410、英語情報の場合があります) を参照してください。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005 (オプション)</td>
<td style="border:1px solid black;">互換性のあるバージョンの SQL Server がまだインストールされていない場合、WSUS 3.0 は Windows Internal Database をインストールします。完全な SQL Server データベースの使用を計画している場合は、少なくとも Windows Server 2003 上で SQL Server 2005 SP1 を使用する必要があります。これは、<a href="http://go.microsoft.com/fwlink/?linkid=66143">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=66143) から入手できます。Windows Server 2008 の場合は、SQL Server 2005 SP2 が必要です。これは、<a href="http://go.microsoft.com/fwlink/?linkid=84823">Microsoft ダウンロード センター</a> (http://go.microsoft.com/fwlink/?LinkId=84823) から入手できます。</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc708491.note(WS.10).gif)注                                                                                                                                                                                                                                                                    |  
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| 以前に WSUS 2.0 をインストールし、SQL Server 2000 または SQL Server Desktop Engine 2000、または SQL Server 2005 SP 1 (Windows Server 2008 の場合は SQL Server 2005 SP2) 以前の SQL Server データベースを使用している場合は、WSUS 3.0 インストール プログラムは Windows® Internal Database をインストールし、データベースを移行します。 |
  
WSUS 3.0 サーバー インストールのディスク領域の最小要件  
------------------------------------------------------
  
次に、Windows Server Update Services をインストールするための最低限のディスク領域要件を示します。
  
-   システム パーティションに 1 GB  
-   データベース ファイルの保存に 2 GB のボリューム  
-   コンテンツの保存に 20 GB のボリューム
  
| ![](images/Cc708491.Important(WS.10).gif)重要                                  |  
|-------------------------------------------------------------------------------------------------------------|  
| WSUS 3.0 は圧縮ドライブにインストールできません。選択したドライブが圧縮されていないことを確認してください。 |
  
WSUS 3.0 アップグレード要件  
---------------------------
  
#### インストールされている WSUS が正常に動作することを確認し、アップグレードの前に WSUS データベースをバックアップする
  
以前のバージョンから WSUS 3.0 にアップグレードする場合は、現在のインストールが正常に動作することを確認し、アップグレードの前に WSUS データベースをバックアップします。
  
1.  イベント ログの最近のエラー、ダウンストリーム サーバーとアップストリーム サーバーの同期の問題、クライアントが報告しない問題をチェックします。続行する前に、これらの問題が解決済みであることを確認します。  
2.  必要に応じて、DBCC CHECKDB を実行し、WSUS データベースのインデックスが正常に作成されていることを確認します。CHECKDB の詳細については、「[DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948)」(http://go.microsoft.com/fwlink/?LinkId=86948) を参照してください。  
3.  WSUS データベースをバックアップします。
  
#### Software Update Services 1.0 をアンインストールする必要がある
  
同じコンピュータに Software Update Services 1.0 がインストールされていると、WSUS 3.0 のインストールに失敗します。WSUS 3.0 をインストールする前に、Software Update Services 1.0 をアンインストールしてください。
  
#### WSUS 3.0 のベータ バージョンから RTM バージョンへのアップグレードはサポートされていないが、RC バージョンから RTM バージョンへのアップグレードは許可されている
  
WSUS 3.0 のベータ バージョンが既にインストールされている場合は、RTM バージョンをインストールする前に、ベータ バージョンをアンインストールしてデータベースを削除する必要があります。RTM バージョンへのアップグレードは RC バージョンからのみ可能です。
  
#### 64 ビットのオペレーティング システムでは WSUS 2.0 から WSUS 3.0 にアップグレードできない
  
64 ビットのオペレーティング システムでは、WSUS 2.0 はサポートされていません。64 ビットのオペレーティング システムで WSUS 2.0 から WSUS 3.0 にアップグレードすることはできません。
  
セットアップ コマンド ライン パラメータ  
---------------------------------------
  
WSUS コマンド ライン パラメータを使用すると、WSUS 3.0 の無人インストールを実行できます。次の表に、WSUS 3.0 のコマンド ライン パラメータを示します。
  
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
<td style="border:1px solid black;">サイレント インストールを実行します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">製品をアンインストールします。Windows Internal Database インスタンスがインストールされている場合は、同時にアンインストールします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">必要条件のみ確認します。製品のインストールは実行せずに、システムを調査し、必要条件が満たされない場合はそれを報告します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">コマンドライン パラメータと説明を表示します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">バージョン 2.0 の WSUS からアップグレードします。このオプションで有効なパラメータは /q (サイレント インストール) のみです。このオプションで有効なプロパティは DEFAULT_WEBSITE のみです。</td>
</tr>
</tbody>
</table>
  
次の表に、WSUS 3.0 のコマンド ライン プロパティを示します。
  
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
<td style="border:1px solid black;">0=コンテンツはローカルにホスト、1=Microsoft Update 上にホスト。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CONTENT_DIR</td>
<td style="border:1px solid black;">コンテンツ ディレクトリへのパス。既定値は、<em>WSUSInstallationDrive</em><strong>\WSUS\WSUSContent</strong> です。<em>WSUSInstallationDrive</em> は空き領域が最大のローカル ドライブです。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Windows Internal Database データ ディレクトリ。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">名前は、<em>サーバー名</em>\<em>SQL インスタンス名</em> の形式で表示されます。データベース インスタンスが、ローカル コンピュータ上にある場合は、%COMPUTERNAME% 環境変数を使用します。既存のインスタンスがない場合、既定では %COMPUTERNAME%\WSUS になります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DEFAULT_WEBSITE</td>
<td style="border:1px solid black;">0=ポート 8530。1=ポート 80。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PREREQ_CHECK_LOG</td>
<td style="border:1px solid black;">ログ ファイルのパスおよびファイル名。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CONSOLE_INSTALL</td>
<td style="border:1px solid black;">0=WSUS サーバーをインストール。1=コンソールのみをインストール。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ENABLE_INVENTORY</td>
<td style="border:1px solid black;">0=一覧機能をインストールしない。1=一覧機能をインストール。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_DATABASE</td>
<td style="border:1px solid black;">0=データベースを保持、1=データベースを削除。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DELETE_CONTENT</td>
<td style="border:1px solid black;">0=コンテンツ ファイルを保持、1=コンテンツ ファイルを削除。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_LOGS</td>
<td style="border:1px solid black;">0=ログ ファイルを保持。1=ログ ファイルを削除 (/u インストール スイッチと共に使用します)。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=現在のデータベースを使用、1=データベースを作成</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">MSI 進捗状況メッセージを返すウィンドウ ハンドル。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=Microsoft Update 向上プログラムに参加、0=参加しない</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=データベースにコンテンツの場所を書き込まない、0=データベースにコンテンツの場所を書き込む (ネットワーク負荷分散のため)</td>
</tr>
</tbody>
</table>
  
#### 使用例
  
```  
WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (install in quiet mode using port 8530) WSUSSetup.exe /q /u (uninstall WSUS)  
```  
| ![](images/Cc708491.Important(WS.10).gif)重要                                                                                                                                   |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| WSUS 3.0 を QUIET モード (/q) でインストールし、コンピュータがすべての前提条件を満たしていない場合は、インストールによって WSUSPreReqCheck.xml というファイルが生成され、%TEMP% ディレクトリに保存されます。 |
  
セットアップの問題  
------------------
  
#### WSUS 3.0 セットアップ時に IIS が再起動する
  
WSUS 3.0 セットアップが通知なしに IIS を再起動するので、組織内の既存の Web サイトに影響する可能性があります。IIS が実行されていない場合、WSUS 3.0 のセットアップにより IIS が起動します。
  
#### 既存の WSUS データベースへの接続が開いているとインストールに失敗する
  
既存のインストールから WSUS 3.0 にアップグレードするとき、既存の WSUS データベースへの接続がまだ開いている場合は (たとえば SQL Server Management Studio が開いている場合)、インストールに失敗することがあります。接続をすべて閉じ、WSUS 3.0 を再インストールしてください。
  
#### WSUS のセットアップで間違ったデータベース ファイル ディレクトリが表示される
  
WSUS セットアップ プログラムの準備完了画面で、データベースの場所がデータベースの場所の親ディレクトリとして間違って表示されます。たとえば、既定の場所は %systemdrive%\\WSUS\\UpdateServicesDbFiles ですが、この場所は %systemdrive%\\WSUS として間違って表示されます。
  
#### 既定の言語が英語以外の Multilingual User Interface 言語パックを使用しているコンピュータに WSUS をインストールした場合、ヘルプは英語ではなく既定の言語で表示される
  
既定の言語が英語以外の Multilingual User Interface 言語パックを使用しているコンピュータの場合、現在のユーザーのロケールが英語のときでも WSUS をインストールすることができます。UI は英語で表示されますが、ヘルプを英語で表示するには対応策が必要です。英語版のヘルプ .chm ファイル ((*WSUSInstallDir*\\documentation\\mui\\0409\\WSUS30Help.chm) をメイン ドキュメント ディレクトリ (*WSUSInstallDir*\\documentation\\WSUS30Help.chm) にコピーします。この時点でヘルプはすべての言語で正しく表示されるはずです。
  
アップグレードの問題  
--------------------
  
#### WSUS 3.0 RC から WSUS 3.0 RTM にアップグレードすると、SSL 証明書が WSUS Web サイトに割り当てられなくなる
  
WSUS 3.0 RC から WSUS 3.0 RTM にアップグレードするときに、WSUS Web サイトは削除され、再作成されます。その結果、SSL 証明書は、 WSUS Web サイトに割り当てられなくなります。アップグレード後に証明書の再割り当てを行う必要があります。
  
#### アップグレードの失敗からの回復
  
WSUS 2.0 から WSUS 3.0 にアップグレードしようとして何らかの理由で失敗した場合は、WSUS 2.0 を再インストールし、バックアップからデータベースを復元する必要があります。
  
#### 以前のインストールの WSUS 3.0 データベースがあると WSUS 2.0 から WSUS 3.0 にアップグレードできない
  
以前に WSUS 3.0 をインストールし、その後 WSUS 2.0 を再インストールした場合は、WSUS 3.0 を再インストールする前に、コンピュータから WSUS 3.0 データベースを削除する必要があります。
  
#### WSUS 3.0 にアップグレードする前にコンピュータ名を変更すると、アップグレードが失敗することがある
  
WSUS 2.0 をインストールした後、および WSUS 3.0 にアップグレードする前にコンピュータ名を変更した場合、アップグレードが失敗する場合があります。
  
次のスクリプトを使用して、ASPNET Administrators および WSUS Administrators グループの削除と再追加を行ってください。次に、アップグレードを再度実行してください。
  
*&lt;DBLocation&gt;* をデータベースがインストールされているフォルダと置き換えて、*&lt;ContentDirectory&gt;* をローカルの保存フォルダと置き換える必要があります。
  
```  
sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=name from sysusers WHERE name like '%ASPNET' EXEC sp\_revokedbaccess @asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=name from sysusers WHERE name like '%WSUS Administrators' EXEC sp\_revokedbaccess @wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=HOST\_NAME()+'\\ASPNET' EXEC sp\_grantlogin @asplogin EXEC sp\_grantdbaccess @asplogin EXEC sp\_addrolemember webService,@asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=HOST\_NAME()+'\\WSUS Administrators' EXEC sp\_grantlogin @wsusadminslogin EXEC sp\_grantdbaccess @wsusadminslogin EXEC sp\_addrolemember webService,@wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "backup database SUSDB to disk=N'*&lt;ContentDirectory&gt;*\\SUSDB.Dat' with init"  
```
  
#### セットアップにより、以前のデータベース バックアップが上書きされる
  
WSUS 3.0 のセットアップにより、セットアップ時に指定したディレクトリにデータベースが追加されます。既定では、これは *%systemdrive%*\\WSUS\\UpdateServicesDbFiles です。このディレクトリに以前のデータベース バックアップがある場合、新しいデータベースによって上書きされます。データベースがあるコンピュータに更新プログラムを適用する前に、Administrators はデータベース ファイルをバックアップする必要があります。
  
#### WSUS 2.0 上で MSDE から SQL Server 2000 または SQL Server 2005 に移行した場合、レジストリ値の変更が必要
  
WSUS 2.0 がインストール済みで、SQL Server 2000 または SQL Server 2005 から移行した場合、**HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** の値を 1 から 0 に変更する必要があります。この作業を行う前に WSUS 3.0 にアップグレードしようとすると失敗します。
  
#### WSUS 2.0 のセットアップを開始してキャンセルした場合、WSUS レジストリ キーが削除される
  
WSUS 2.0 のセットアップを開始してからキャンセルした場合、WSUS レジストリ キーは削除されます。既に WSUS 3.0 をインストールしている場合、問題になる可能性があります。WSUS 2.0 のアンインストールを開始してからキャンセルし、その後 WSUS 2.0 から WSUS 3.0 へのアップグレードを試みた場合も、同様の問題が発生します。
  
#### WSUS 3.0 をアンインストールして、ログ ファイルをそのままにしておくと、再インストールの後でファイルは正しいアクセス許可を持たない可能性がある
  
WSUS 3.0 をアンインストールする場合、インストールのログ ファイルを保存するオプションがあります。WSUS 3.0 を再インストールする場合、古いログ ファイルはアクセス許可を失います (通常は WSUS Administrators のみ)。ログ ファイルのアクセス許可を回復してください。
  
#### WSUS 3.0 RC の後に Windows SharePoint Services がインストールされた場合は、特定の条件のもとで WSUS 3.0 RTM にアップグレートできる
  
WSUS 3.0 RC をインストールした後で同じコンピュータに Windows SharePoint Services をインストールした場合、WSUS 3.0 RTM へのアップグレードは、カスタム ポート (ポート 853) を選択した場合のみ実行できます。このインストールをコマンド ラインから実行するには、コマンド シェルを開いて、「**WSUSSetup /q / g/ DEFAULT\_WEBSITE=0**」と入力します。(UI を使用してこのインストールを行うには、「**WSUSSetup /g DEFAULT\_WEBSITE=0**」を入力します)。
  
Multilingual User Interface 言語パックのインストールされたコンピュータに WSUS をインストールした場合、ヘルプはユーザーの現在の言語ではなく、既定の言語で表示される
  
#### WSUS 2.0 クライアントに "該当なし" 状態の更新プログラムが含まれる場合、WSUS 3.0 へのアップグレード後、その更新プログラムがしばらくの間 "不明" と表示される
  
WSUS 2.0 サーバーに "該当なし" 状態の更新プログラムを含むクライアントがある場合、サーバーを WSUS 3.0 にアップグレードした後、しばらくの間その更新プログラムが "不明" 状態として表示されます。クライアントが次にスキャンを実行した後、更新状態は "該当なし" に戻します。
  
既知の問題  
----------
  
#### 複数のダウンロード エラーが表示される場合やクライアントの同期に何度も失敗する場合のトラブルシューティング
  
WSUS 3.0 クライアントで複数のダウンロード エラーが報告される場合や、クライアントが WSUS 3.0 サーバーとの同期に長時間にわたり失敗する場合は、クライアントのダウンロード キャッシュが破損している可能性があります。この状態から回復するには、ファイル システムからクライアントのダウンロード キャッシュを削除します。
  
クライアントのダウンロード キャッシュを削除するには
  
1.  クライアント コンピュータで、**%windir%\\SoftwareDistribution\\Download** にあるすべてのファイルとサブディレクトリを削除します。  
2.  クライアント コンピュータを WSUS 3.0 と再び同期して、更新プログラムのインストールを試みます。このインストールに失敗して、WU\_E\_DM\_NOTDOWNLOADED, 更新プログラムはダウンロードされていません。というエラーが表示されます。  
3.  この失敗の後、クライアント コンピュータが自動的にダウンロードを再開するので、インストールを続行できます。
  
#### 同期が失敗する場合は、同期を再試行する
  
同期が失敗した場合は、トラブルシューティングの最初に、もう一度サーバーの同期を試みてください。2 回目以降の同期にも失敗した場合は、[Windows Server Update Services 3.0 操作ガイド](http://go.microsoft.com/fwlink/?linkid=81072) (http://go.microsoft.com/fwlink/?LinkId=81072、英語情報の場合があります) のトラブルシューティングに関する説明を参照してください。
  
#### WSUS 3.0 の構成をデータベースから直接変更できない
  
Windows Server Update Services の構成データは SQL Server データベースに保存されます。ただし、データベースに直接アクセスして構成データを変更することはできません。データベースに直接アクセスして WSUS 3.0 の構成を変更しないでください。WSUS 3.0 の構成を変更するには、WSUS 3.0 のコンソールを使用するか、WSUS 3.0 の API を呼び出す必要があります。
  
#### ディスク クォータが有効になっていると、ダウンロードの失敗が速やかに報告されない
  
ディスク クォータが有効で、そのクォータに達した場合、WSUS サーバーで更新プログラムのダウンロードが失敗しても速やかに報告されないことがあります。この問題を防ぐには、ディスク クォータを無効にするか、クォータを大きくしてください。
  
#### SSL を使用して WSUS 3.0 を導入すると、クライアント コンピュータが 0x8024400a エラー コードを返して失敗する
  
クライアント コンピュータは、SSL を使用して WSUS 3.0 サーバーと通信していると、"0x8024400a" エラー コードを返して失敗する場合があります。この問題に対処する更新プログラムについては、[KB 905422](http://go.microsoft.com/fwlink/?linkid=70593) (http://go.microsoft.com/fwlink/?LinkId=70593) を参照してください。
  
#### WSUS をアンインストールしても WSUS Administrators ドメイン アカウントが削除されない
  
WSUS Administrators グループは、ローカル アカウントではなくドメイン アカウントとしてドメイン コントローラに作成されるので、このドメイン アカウントを使用したすべてのインストールは、WSUS のアンインストール時にアカウントを削除すると、無効になります。したがって、WSUS をアンインストールしても、WSUS Administrators ドメイン アカウントは削除されません。
  
#### ダウンストリーム サーバーをアップストリーム サーバーに変換すると、カタログ サイトの更新プログラムを再インポートする必要がある
  
ダウンストリーム サーバーをアップストリーム サーバーに昇格させるときは、カタログ サイトの更新プログラムもすべて再インポートする必要があります。再インポートしないと、サイトは新しいカタログ サイトの更新プログラムの改訂版をこのサーバーに同期できません。
  
#### IIS で SSL を使用する場合に、\[セキュリティで保護されたチャネル (SSL) を要求する\] をオンにしていなければ暗号化しないでアクセスできる
  
証明書をインストールして SSL を使用するように IIS をセットアップした場合、\[セキュリティで保護されたチャネル (SSL) を要求する\] オプションをオンにしていなければ、暗号化されていない HTTP を介してサイトにアクセスできます。詳細については、[暗号化の有効化についてのページ](http://go.microsoft.com/fwlink/?linkid=70601) (http://go.microsoft.com/fwlink/?LinkId=70601、英語情報の場合があります) を参照してください。
  
#### %windir%\\TEMP フォルダの読み取り/書き込みアクセス許可がないとカタログ サイトのインポートに失敗する
  
カタログ サイトのインポートを実行するとき、Network Service アカウントに %windir%\\TEMP フォルダの読み取り/書き込みアクセス許可がなければ、次のようなエラー メッセージが表示されてインポートは失敗します。"サーバーは要求を処理できませんでした。---&gt; ファイル 'C:\\WINDOWS\\TEMP\\*tempFileName*.dll' が見つかりませんでした。"
  
#### WSUS 2.0 を実行しているダウンストリーム レプリカ サーバーと WSUS 3.0 を同期すると、パフォーマンスが低下する
  
WSUS 3.0 をアップストリーム サーバーにインストールし、WSUS 2.0 を実行しているダウンストリーム レプリカ サーバーと同期しようとすると、パフォーマンスが低下する可能性があります。この問題に対処するには、[KB 910847](http://go.microsoft.com/fwlink/?linkid=70669) (http://go.microsoft.com/fwlink/?LinkId=70669) を参照してください。
  
#### メール サーバーが停止状態またはアクセス不能の場合に、通知なしに電子メール通知に失敗する
  
ネットワークの電子メール サーバーがオフラインの場合、WSUS 3.0 は電子メール通知の送信に失敗し、エラーを表示しません。ただし、イベント ログにイベント 10052 (HealthCoreEmailNotificationRed) が書き込まれます。
  
#### アップストリーム サーバーで変更した設定がダウンストリーム サーバーに直ちに適用されない
  
アップストリーム サーバーの構成を変更すると、実際に構成の変更が有効になるまでに時間がかかる場合があります。たとえば、新しい言語を選択するなど、アップストリーム サーバーで設定を変更し、直後にダウンストリーム サーバーの同期をトリガしても、変更が反映されません。変更は次回スケジュールされている同期でダウンストリーム サーバーに適用されます。アップストリーム サーバーにある更新プログラムの数が多いほど、適用にかかる時間が長くなります。
  
#### WSUS 3.0 をアンインストールしてもデータベース インスタンスがアンインストールされない
  
WSUS 3.0 をアンインストールしても、データベース インスタンスはアンインストールされません。インスタンスは複数のアプリケーションで共有されている可能性があり、削除されると他のアプリケーションに障害が生じます。
  
Windows Internal Database をアンインストールする必要がある場合は、次のコマンドでアプリケーションをアンインストールできます。
  
(32 ビット プラットフォーム)
  
```  
msiexec /x {CEB5780F-1A70-44A9-850F-DE6C4F6AA8FB} callerid=ocsetup.exe  
```  
(64 ビット プラットフォーム)
  
```  
msiexec /x {BDD79957-5801-4A2D-B09E-852E7FA64D01} callerid=ocsetup.exe  
```  
Windows Internal Database Service Pack 2 を Windows Server 2008 からアンインストールする場合は、サーバー マネージャを使用します。
  
ただし、アプリケーションを削除しても既定の .mdf ファイルと .ldf ファイルは削除されないので、次に WSUS 3.0 のインストールを試みると失敗します。これらのファイルは %windir%\\SYSMSI\\SSEE ディレクトリから削除できます。
  
#### ダウンストリーム サーバーがそのアップストリーム サーバーを変更する場合に、状態が "不明" の更新プログラムが "適用なし" と報告される
  
ダウンストリーム サーバーが別のアップストリーム サーバーとの同期を開始すると、状態が "不明" の更新プログラムが新しいアップストリーム サーバーで "適用なし" と報告されます。この状態は一時的なものであり、クライアントの同期後に、ダウンストリーム サーバーが次回その状態を報告するときには訂正されます。
  
#### WSUS 3.0 レプリカ サーバーが同じ名前の複数のコンピュータを管理している場合に、ロールアップの報告に失敗する
  
WSUS 3.0 レプリカ サーバーが同じ名前の複数のコンピュータを管理している場合、ロールアップの報告に失敗します。その結果、ルートの WSUS サーバーに提供されるレポートが不完全になります。この問題は、レプリカ サーバーで重複しているコンピュータ エントリを 1 つだけ残して他のすべてを削除すると解決します。
  
#### サーバー クリーンアップ ウィザードをリモート コンソールから複数のサーバーに実行しているとき、1 つのサーバーがタイムアウトになると、すべてのサーバーとの接続が切断される
  
1 つのリモート コンソールから複数のサーバーにサーバー クリーンアップ ウィザードを実行できますが、いずれかのサーバーでクリーンアップ プロセスがタイムアウトになると、コンソールとすべてのサーバーとの接続が切断されます。データは保持されますが、管理者はサーバーごとにリモート接続をリセットする必要があります。
  
#### サーバー クリーンアップ ウィザードで、3 か月後ではなく、30 日後にファイルが削除される
  
サーバー クリーンアップの一部のテキストは不正確です。次のように解釈してください。「有効期限が切れていて、3 か月間承認されていない更新プログラムを削除する。また、3 か月間承認されていない更新プログラムの古い改訂版を削除する。」正確な期間は 30 日で、3 か月ではありません。
  
#### 立て続けに接続を開始して停止すると、設定ウィザードで "no failure" というエラー メッセージが表示される
  
WSUS を設定する際、サーバーに関する基本的な情報を転送するために、アップストリーム サーバー (Microsoft Update またはイントラネットのアップストリーム サーバー) に接続する必要があります。\[接続の開始\] をクリックし、すぐに \[接続の停止\] をクリックすると、"同期エラーはありませんでした。" というエラー メッセージが表示されます。
  
#### Windows Vista RTM を使用している WSUS クライアントでも Microsoft Update で更新を検索できる
  
以前のバージョンの WSUS では、Windows Vista RTM を使用しているクライアントは、WSUS サーバーからしか更新を入手できませんでした。WSUS 3.0 RTM では、Vista クライアントも Microsoft Update から更新を入手できます。コントロール パネルから Windows Update を起動し、\[Microsoft Update サービスからの更新プログラムをオンラインで確認する\] リンクをクリックすると、Vista クライアントから Microsoft Update に移動できます。グループ ポリシーのオプション \[Windows Update のすべての機能へのアクセスを削除する\] が有効になっている場合は、Windows Update に前述のリンクは表示されません。
  
Windows Server 2008 上の WSUS 3.0  
---------------------------------
  
#### サポートされているバージョン
  
WSUS 3.0 では、32 ビットと 64 ビットの両方のバージョンの Windows Server 2008 をサポートしています。
  
#### 必要条件
  
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
<td style="border:1px solid black;">オペレーティング システムからインストールします。次のコンポーネントが有効になっていることを確認してください。
Windows 認証
静的コンテンツ
ASP.NET
6.0 管理互換性
IIS メタベース互換性</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework Version 2.0 再頒布可能パッケージ (x86)</td>
<td style="border:1px solid black;">Windows Server 2008 では、オペレーティング システムの一部としてインストールされているため不要です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft 管理コンソール 3.0</td>
<td style="border:1px solid black;">Windows Server 2008 では、オペレーティング システムの一部としてインストールされているため不要です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">これは、WSUS UI を使用するための前提条件です。<a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft ダウンロード センター</a>で、Microsoft Report Viewer 再頒布可能パッケージ 2005 についてのページ (http://go.microsoft.com/fwlink/?LinkId=70410) を参照してください。</td>
</tr>
</tbody>
</table>
  
#### 問題 1 : WSUS 3.0 の実行前に IIS 7.0 の構成ファイルを更新する必要がある
  
Windows Server 2008 で WSUS 3.0 を実行する前に、IIS 構成ファイルを更新する必要があります。次の手順を実行します。
  
1. 次の場所にある IIS 構成ファイルを開きます。%WINDIR%\\system32\\inetsrv\\applicationhost.config
  
2. &lt;System.webServer&gt;&lt;modules&gt; タグに &lt;add name="CustomErrorMode"&gt; がある場合は削除します。
  
3. &lt;System.webServer&gt;&lt;modules&gt; タグに、&lt;remove name="CustomErrorMode"&gt; を追加します。
  
タグは次のようになります。
  
```  
 &lt;System.webServer&gt; &lt;modules&gt; &lt;remove name="CustomErrorMode"&gt; &lt;/modules&gt; &lt;/System.webServer&gt;  
```
  
#### 問題 2 : Windows Server 2008 Beta 3 でカスタム ポートに WSUS 3.0 をインストールしたい場合は、事前に Web サイトの作成が必要
  
WSUS 3.0 を Windows Server 2008 Beta 3 にインストールしたい場合、かつ WSUS がカスタム ポート 8530 を使用するように構成したい場合、WSUS インストール プログラムを起動する前に、ポート 8530 に "WSUS の管理" という名前の Web サイトを作成する必要があります。
  
Windows Small Business Server 2003 にインストールした WSUS 3.0  
--------------------------------------------------------------
  
#### 問題 1 : IIS 仮想ルートが特定の IP アドレスやドメイン名に制限されていると、WSUS 3.0 サーバーが自動更新できない
  
Windows Small Business Server のインストールによっては、既定の IIS Web サイトに "IP アドレスとドメイン名の制限" が構成されている場合があります。その場合、サーバーの Windows Update クライアントは更新されない場合があります。
  
#### 問題 2 : Small Business Server での WSUS 3.0 のインストール - 統合に関する問題
  
-   Windows Small Business Server 2003 で ISA プロキシ サーバーを使用してインターネットにアクセスしている場合は、\[設定\] ユーザー インターフェイスに、プロキシ サーバー設定、プロキシ サーバー名、およびポートを入力する必要があります。  
-   ISA で Windows 認証を使用している場合は、プロキシ サーバーの資格情報を、"ドメイン\\ユーザー" (Internet Users グループのメンバ) の形式で入力する必要があります。
  
#### 問題 3 : Windows SBS ウィザードを使用しないでネットワークにサブネットを追加した場合、ウィザードの手順を実行する必要がある
  
WSUS サーバーのセットアップ プロセスによってサーバーに 2 つの IIS 仮想ルート (SelfUpdate と ClientWebService) がインストールされます。また、クライアント コンピュータが既定の Web サイトから自動更新できるように、一部のファイルが既定の Web サイト (ポート 80) のホーム ディレクトリの下に配置されます。既定では、既定の Web サイトは、サーバーに接続しているローカル ホストや特定のサブネット以外の IP アドレスへのアクセスを拒否するように構成されています。その結果、ローカル ホストや特定のサブネットにないクライアント コンピュータは自動更新できません。Microsoft Windows Small Business Server 2003 (Windows SBS) ウィザードを使用しないでネットワークにサブネットを追加した場合は、次の手順を実行する必要があります。
  
1.  \[サーバー管理\] で、\[詳細管理\]、\[インターネット インフォメーション サービス\]、\[Web サイト\]、\[既定の Web サイト\] の順に展開し、\[Selfupdate\] 仮想ディレクトリを右クリックして \[プロパティ\] をクリックします。  
2.  \[ディレクトリ セキュリティ\] をクリックします。  
3.  \[IP アドレスとドメイン名の制限\] の \[編集\] をクリックし、\[許可するアクセス\] をクリックします。  
4.  \[OK\] をクリックし、\[ClientWebService\] 仮想ディレクトリを右クリックして \[プロパティ\] をクリックします。  
5.  \[ディレクトリ セキュリティ\] をクリックします。  
6.  \[IP アドレスとドメイン名の制限\] の \[編集\] をクリックし、\[許可するアクセス\] をクリックします。
  
#### 著作権情報
  
このドキュメントはプレリリースのソフトウェア製品を対象にしており、最終製品のリリース前に大幅に変更される可能性があります。このドキュメントには、Microsoft Corporation が所有する機密情報が記載されています。このドキュメントは受領者とマイクロソフトとの間の秘密保持契約に従って開示されます。このドキュメントは情報提供のみを目的とし、マイクロソフトは明示または黙示のいずれにおいても保証するものではありません。URL およびその他のインターネット Web サイトの参照を含め、このドキュメント内の情報は予告なしに変更される場合があります。このドキュメントの使用または使用結果から生じるリスクは、すべてお客様ご自身が負うものとします。特に断りのない限り、例に使用されている会社、組織、製品、ドメイン名、電子メール アドレス、ロゴ、人物、場所、出来事はすべて架空のものです。実在する会社、組織、製品、ドメイン名、電子メール アドレス、ロゴ、人物、場所、出来事とのかかわりを意図するものではなく、推測すべきものではありません。お客様ご自身の責任において、適用されるすべての著作権関連法規に従ったご使用を願います。このドキュメントのいかなる部分も、米国 Microsoft Corporation の書面による許諾を受けることなく、その目的を問わず、どのような形態であっても、複製または譲渡することは禁じられています。ここでいう形態とは、複写や記録など、電子的な、または物理的なすべての手段を含みます。ただしこれは、著作権法上のお客様の権利を制限するものではありません。
  
マイクロソフトは、このドキュメントに記載されている内容に関し、特許、特許申請、商標、著作権、またはその他の無体財産権を有する場合があります。別途マイクロソフトのライセンス契約上に明示の規定のない限り、このドキュメントはこれらの特許、商標、著作権、またはその他の無体財産権に関する権利をお客様に許諾するものではありません。
  
© 2007 Microsoft Corporation.All rights reserved.
  
Microsoft、SQL Server、Windows、および Windows Server は、米国 Microsoft Corporation の米国およびその他の国における登録商標または商標です。
  
その他すべての商標は、各社が所有する商標です。
