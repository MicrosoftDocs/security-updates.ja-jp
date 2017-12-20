---
TOCTitle: 'Windows Server Update Services 3.0 SP2 リリース ノート'
Title: 'Windows Server Update Services 3.0 SP2 リリース ノート'
ms:assetid: 'b3723422-489d-47b7-abfa-663353647da0'
ms:contentKeyID: 21743289
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd939886(v=WS.10)'
---

Windows Server Update Services 3.0 SP2 リリース ノート
======================================================

これらのリリース ノートでは、Windows Server Update Services 3.0 Service Pack 2 (WSUS 3.0 SP2) リリースについて説明します。 このドキュメントは次のセクションで構成されています。

1.  このリリースの新機能
2.  WSUS 3.0 SP2 サーバー インストールのシステム要件
3.  WSUS サーバー の構成の前提条件とベスト プラクティス推奨事項
4.  Windows Small Business Server の前提条件
5.  WSUS 3.0 SP2 リモート コンソール インストールのシステム要件
6.  クライアント インストールのシステム要件
7.  アップグレード要件と推奨事項
8.  WSUS 3.0 SP2 のインストール
9.  WSUS 3.0 SP2 無人インストールのセットアップ コマンド ライン パラメータ
10. 既知の問題

このリリースの新機能
--------------------

-   Windows Server® 2008 R2 との統合
-   Windows Server 2008 R2 での BranchCache 機能のサポート
-   Windows 7 クライアントのサポート
-   Windows Update エージェント (WUA) クライアントの機能向上。 新しい WUA クライアントは、パフォーマンスやユーザー エクスペリエンスを向上するためのさまざまな機能を提供するほか、お客様からのフィードバックに基づいて多数の問題を修正します。
    -   クライアントのスキャン時間が、以前のバージョンよりも高速になります。
    -   WSUS サーバーが管理するコンピュータで、フル検索を実行しなくても、同じ WSUS サーバーに対して "範囲指定" スキャンを実行できるようになりました。このため、Windows Defender のように Microsoft Update API を使用するアプリケーションでは、スキャンに要する時間が大幅に短縮されます。
    -   Windows Update エージェント (WUA) のユーザー エクスペリエンスの向上により、ユーザーは更新プログラムを整理できるようになります。また、更新プログラムの価値および動作がより明確になります。
    -   WSUS コンソールでは、イメージ化されたコンピュータはよりわかりやすく表示されます。 詳細については、「[Windows 2000、Windows Server 2003、または Windows XP のイメージを使用してセットアップされた Windows 2000 ベース、Windows Server 2003 ベース、または Windows XP ベースのコンピュータが WSUS コンソールに表示されない](http://go.microsoft.com/fwlink/?linkid=159749)」というタイトルの記事を参照してください。
-   新機能 :
    -   自動承認規則に、すべてのコンピュータまたは特定のコンピュータ グループの承認の期日および時間を指定する機能が含まれました。
    -   ダウンストリーム サーバーで言語選択を処理する方法が変更され、特定の言語の更新プログラムのみをダウンロードしようとすると、新しい警告ダイアログが表示されるようになりました。
    -   新しい更新レポートとコンピュータの状態レポートを使用して、インストールが承認された更新プログラムをフィルタできます。 これらのレポートを WSUS コンソールから実行したり、アプリケーション プログラミング インターフェイス (API) を使用して、この機能を独自のレポートに統合したりすることができます。
-   ユーザー インターフェイスは、クライアントとサーバーの両方の WSUS 3.0 の Service Pack 1 と Service Pack 2 の間で互換性があります。
-   ソフトウェアの更新プログラム
-   次の Windows Update エージェントの既知の問題は、このリリースで解決されました。
    1.  WSUS 3.0 SP2 と Windows 7 には、新しい Windows Update エージェント (Windows XP、Windows Vista、Windows Server 2000、Windows Server 2003、および Windows Server 2008 用) が含まれています。 このリリースでは、 非対話型セッションで非ローカル システムの呼び出し側によって呼び出されるた API が失敗する問題を解決しました。
    2.  Windows Update エージェントのバージョン 7.2.6001.788 で解決された問題。 このリリースでは、 Windows Update Web ページまたは Microsoft Update Web ページから 80 以上の更新プログラムを同時にインストールしようとすると、エラー コード 0x80070057 を受け取る問題を解決しました。
    3.  Windows Update エージェントのバージョン 7.2.6001.784 での改善点と解決された問題。 この更新プログラムでは、 Windows Update のスキャン時間と署名の更新の配信速度が向上し、Windows インストーラの再インストール機能がサポートされ、エラー メッセージングが向上しました。

<span id="BKMK_SysReqWSUS30SP2"></span>
WSUS 3.0 SP2 サーバー インストールのシステム要件
------------------------------------------------

ここでは、WSUS 3.0 SP2 のインストールで必要となるソフトウェア要件およびハードウェア要件について説明します。

### WSUS サーバー ソフトウェアの前提条件

-   次のサポートされているオペレーティング システムのいずれかがインストールされている必要があります。
    -   Windows Server 2008 R2
    -   Windows Server 2008 SP1 以降のバージョン
 
        <table style="border:1px solid black;">
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" ><img src="images/Dd939886.Warning(WS.10).gif" />警告</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;">Windows Server 2008 R2 へのアップグレード前に WSUS 3.0 SP2 を Windows Server 2008 にインストール済みである場合は、Windows Server 2008 R2 へのアップグレードは失敗します。 詳細については、「<a href="#bkmk_knownissues">既知の問題</a>」セクションを参照してください。
        </td>
        </tr>
        </tbody>
        </table>
 

    -   Windows Server 2003 SP1 以降のバージョン
    -   Windows Small Business Server 2008
    -   Windows Small Business Server 2003

    追加の前提条件が Windows Small Business Server に適用されることに注意してください。 詳細については、「Windows Small Business Server の前提条件」セクションを参照してください。
-   インターネット インフォメーション サービス (IIS) 6.0 以降のバージョン
-   Microsoft .NET Framework 2.0 以降のバージョン
-   次のサポートされているデータベースのいずれかがインストールされている必要があります。
    -   Microsoft SQL Server 2008 Standard Edition または Enterprise Edition
    -   Microsoft SQL Server 2005 SP3 以降のバージョン
    -   Windows Internal Database

    SQL Server のサポートされているバージョンがどれもインストールされていない場合は、WSUS 3.0 SP2 セットアップ ウィザードで Windows Internal Database がインストールされます。
-   Microsoft 管理コンソール 3.0
-   Microsoft Report Viewer 再頒布可能パッケージ 2008

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939886.Important(WS.10).gif" />重要</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2008 R2 では WSUS 3.0 SP2 が必要です。Windows Server 2008 R2 をインストールする場合は、WSUS 3.0 SP2 をインストールする必要があります。Windows Server 2008 R2 に WSUS 3.0 SP1 をインストールしないでください。

リモート SQL 構成のフロントエンド サーバー上のターミナル サービスでの WSUS 3.0 SP2 の使用は、サポートされていません。
</td>
</tr>
</tbody>
</table>
 

### WSUS 管理コンソール ソフトウェアの前提条件

-   以下のサポートされているオペレーティング システムのいずれかが必要です。 Windows Server 2008 R2、Windows Server 2008、Windows Server 2003 SP2 以降のバージョン、Windows Small Business Server 2008 または Windows Small Business Server 2003、Windows Vista、または Windows XP SP2
-   Microsoft .NET Framework 2.0 以降のバージョン
-   Microsoft 管理コンソール 3.0
-   Microsoft Report Viewer 再頒布可能パッケージ 2008

### WSUS サーバーのハードウェア最小要件

基本的なサーバー インストールで必要となるハードウェアの最小要件を次に示します。 サポートされているハードウェア構成の詳細については、[http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832) の『WSUS 3.0 SP2 展開ガイド』(英語版の可能性があります) を参照してください。

-   システム パーティションと WSUS 3.0 SP2 をインストールするパーティションは両方とも、NTFS ファイル システムでフォーマットされている必要があります。
-   システム パーティションには、1 GB 以上の空き領域が必要です。
-   データベース ファイルを保存するボリュームには、2 GB 以上の空き領域が必要です。
-   コンテンツを保存するボリュームには、20 GB 以上の空き領域が必要です。30 GB が推奨されます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939886.Important(WS.10).gif" />重要</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">WSUS 3.0 SP2 は圧縮ドライブにインストールできません。
</td>
</tr>
</tbody>
</table>
 

WSUS サーバー の構成の前提条件とベスト プラクティス推奨事項
-----------------------------------------------------------

WSUS 3.0 SP2 をインストールする前に、このセクションの該当するタスクを終了していることを確認してください。

### IIS

-   サーバー マネージャの Web サーバー (IIS) の役割サービスのページで、必要な機能および既定の IIS の役割サービスすべてに加えて、 \[ASP.NET\]、\[Windows 認証\]、\[動的なコンテンツの圧縮\]、および \[IIS 6 管理互換\] の役割サービスをインストールします。
-   IIS が IIS 5.0 分離モードで実行されていると、インストールに失敗します。IIS 5.0 分離モードを無効にしてから WSUS 3.0 SP2 をインストールしてください。
-   IIS コンポーネントが 64 ビットのプラットフォームに 32 ビット互換モードでインストールされていると、WSUS 3.0 SP2 のインストールに失敗します。 IIS のすべてのコンポーネントは 64 ビットのプラットフォームにネイティブ モードでインストールする必要があります。

### プロキシ サーバー

WSUS 3.0 SP2 では、プロキシ サーバーでサポートできるのは HTTP のみです。 ベスト プラクティスとして、コマンド ライン (**wsusutil configuresslproxy**) を使用して HTTPS を実行する 2 番目のプロキシ サーバーを構成してから、構成ウィザードまたは管理コンソールから WSUS サーバーを構成してください。

### ポート 80 で実行している Web サイト

ポート 80 で実行している Web サイト (たとえば、Windows SharePoint Services) が 2 つ以上ある場合、WSUS をインストールする前に 1 つを残してすべてを削除してください。 この作業を行わない場合、サーバーのクライアントが自己更新に失敗します。

### ウイルス対策プログラム

WSUS 3.0 SP2 をインストールするとき、ウイルス対策プログラムを無効にしないとインストールを正常に実行できない場合があります。 ウイルス対策ソフトウェアを無効にし、コンピュータを再起動してから WSUS をインストールしてください。 コンピュータを再起動することにより、インストール プロセスでアクセスするファイルがロックされるのを防ぎます。 インストールの完了後、再びウイルス対策ソフトウェアを有効にしてください。 ウイルス対策ソフトウェアとバージョンを無効にしてから再び有効にする方法については、ウイルス対策ソフトウェアのベンダの Web サイトを参照してください。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939886.Caution(WS.10).gif" />注意</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">この回避策によって、コンピュータやネットワークが悪意のあるユーザーや、ウイルスなどの悪意のあるソフトウェアの攻撃を受けやすくなる可能性があります。 したがって、この回避策を推奨できませんが、ユーザーの判断でこの方法を採用できるように情報を提供しています。 この回避策は各自の責任で使用してください。

ウイルス対策ソフトウェアは、コンピュータをウイルスから保護するのが目的です。 ウイルス対策プログラムが無効のときに、信頼していない発行元からのファイルをダウンロードしたり開いたりしないでください。同様に、信頼していない Web サイトにアクセスしたり、電子メールの添付ファイルを開いたりしないでください。
</td>
</tr>
</tbody>
</table>
 

### SQL Server でのトリガのネスト オプション

SQL Server データベースを Windows Server Update Services のデータ ストアとして使用する場合は、WSUS の管理者が WSUS 3.0 SP2 をインストールする前に、SQL Server の管理者がこのサーバー上でトリガのネスト オプションが有効であることを確認する必要があります。トリガのネスト オプションは既定では有効になっていますが、SQL Server 管理者が無効にしている場合があります。WSUS 3.0 SP2 セットアップを実行すると、RECURSIVE\_TRIGGERS オプションが有効になります。これはデータベースに固有のオプションです。ただし、トリガのネスト オプションはサーバーのグローバル オプションであるため有効になりません。

### リモート SQL の制限事項と要件

WSUS 3.0 SP2 は、WSUS 3.0 SP2 アプリケーションを実行するコンピュータ以外のコンピュータ上では、互換性のあるバージョンの SQL Server ソフトウェアの実行をサポートします。 リモート SQL インストールを構成するためには、以下の要件を適用します。

-   リモート SQL ペアのバックエンドのドメイン コントローラとして構成されているサーバーを使用することはできません。
-   リモート SQL インストールのフロントエンド サーバーとして使用するコンピュータではターミナル サービスを実行できません。
-   フロントエンド コンピュータとバックエンド コンピュータの両方が同一の Active Directory ドメインに参加している必要があります。 それぞれ別のドメインに属している場合、WSUS セットアップを実行する前に、ドメイン間でクロスドメインの信頼関係を確立してください。
-   リモート SQL 構成で既にインストールした WSUS 2.0 を WSUS 3.0 SP2 にアップグレードする場合は、WSUS をインストールする前に次のことを実行してください。
    1.  既存のデータベースを保持したまま、WSUS 2.0 をアンインストールします (コントロール パネルの \[プログラムの追加と削除\] を使用)。
    2.  SQL Server 2005 SP2 または SQL Server 2008 をインストールして既存のデータベースをアップグレードします。

### WSUS 3.0 SP2 セットアップ時に IIS が再起動する

WSUS 3.0 SP2 セットアップが通知なしに IIS を再起動するので、組織内の既存の Web サイトに影響する可能性があります。 ベスト プラクティスとしては、このインストールで影響を受ける部署に事前に連絡してください。IIS が実行されていない場合、WSUS 3.0 SP2 のセットアップによりセットアップ中に IIS が起動することに注意してください。

Windows Small Business Server の前提条件
----------------------------------------

WSUS 3.0 SP2 を Windows Small Business Server にインストールする場合、次の前提条件が適用されます。

### IIS 仮想ルートが特定の IP アドレスやドメイン名に制限されている場合

Windows Small Business Server のインストールによっては、既定の IIS Web サイトに "IP アドレスとドメイン名の制限" が構成されている場合があります。 この場合、サーバーの Windows Update クライアントは更新されない場合があります。制限を削除してから WSUS 3.0 SP2 をインストールしてください。

### ISA プロキシ サーバーを使用する場合

-   Windows Small Business Server で ISA プロキシ サーバーを使用してインターネットにアクセスしている場合は、\[設定\] ユーザー インターフェイス (UI) に、**プロキシ サーバー設定、プロキシ サーバー名、およびポート**を入力する必要があります。
-   ISA で Windows 認証を使用している場合は、プロキシ サーバーの資格情報を *DOMAIN*\\*user* の形式で入力してください。 ユーザーは、Internet Users グループのメンバである必要があります。

### ネットワークにサブネットを追加しており Windows Small Business Server ウィザードを使用していない場合

WSUS サーバーのセットアップ プロセスによってサーバーに 2 つの IIS 仮想ルート (SelfUpdate と ClientWebService) がインストールされます。また、クライアント コンピュータが既定の Web サイトから自動更新できるように、一部のファイルが既定の Web サイト (ポート 80) のルート ディレクトリの下に配置されます。 既定では、既定の Web サイトは、サーバーに接続しているローカル ホストや特定のサブネット以外の IP アドレスへのアクセスを拒否するように構成されています。 したがって、ローカル ホストや特定のサブネットにないクライアント コンピュータは自動更新できません。 Microsoft Windows Small Business Server ウィザードを使用しないでネットワークにサブネットを追加した場合は、次の手順を実行してください。

1.  \[サーバー管理\] で、\[詳細管理\]、\[インターネット インフォメーション サービス\]、\[Web サイト\]、\[既定の Web サイト\] の順に展開し、\[Selfupdate\] 仮想ディレクトリを右クリックして \[プロパティ\] をクリックします。
2.  \[ディレクトリ セキュリティ\] をクリックします。
3.  \[IP アドレスとドメイン名の制限\] の \[編集\] をクリックし、\[許可するアクセス\] をクリックします。
4.  \[OK\] をクリックし、\[ClientWebService\] 仮想ディレクトリを右クリックして \[プロパティ\] をクリックします。
5.  \[ディレクトリ セキュリティ\] をクリックします。
6.  \[IP アドレスとドメイン名の制限\] の \[編集\] をクリックし、\[許可するアクセス\] をクリックします。

WSUS 3.0 SP2 リモート コンソール インストールのシステム要件
-----------------------------------------------------------

WSUS 3.0 SP2 リモート コンソールは、次のオペレーティング システムのいずれかにインストールできます。

-   Windows Server 2008 R2、Windows Server 2008 SP1 以降のバージョン、Windows Server 2003 SP2 以降のバージョン、Windows Small Business Server 2003、Windows Small Business Server 2005、または Windows Small Business Server 2008、Windows Vista、または Windows XP Professional SP3 以降のバージョン

WSUS クライアント インストールのシステム要件
--------------------------------------------

自動更新 (WSUS クライアント ソフトウェア) は、以下のオペレーティング システムのいずれかにインストールできます。

-   Windows Server 2008 R2、Windows Server 2008 SP1 以降のバージョン、Windows Server 2003 SP2 以降のバージョン、Windows Small Business Server 2003、Windows Small Business Server 2005、または Windows Small Business Server 2008、Windows Vista、Windows XP Professional RTM、Windows XP Professional SP1、Windows XP Professional SP2、Windows XP Professional SP3 以降のバージョン、Windows 2000 SP4、または Windows 7 クライアント。

アップグレード要件と推奨事項
----------------------------

次のバージョンの WSUS は WSUS 3.0 SP2 にアップグレードできます。以前のバージョンをアンインストールする必要はありません。

-   WSUS 2.0、2.0 SP1、3.0、および 3.0 SP1

WSUS 1.0 から WSUS 3.0 SP2 へのアップグレードはサポートされていません。 Software Update Services (SUS) 1.0 をアンインストールしてから WSUS 3.0 SP2 をインストールしてください。

Windows Server 2008 R2 では WSUS 3.0 SP2 が必要です。Windows Server 2008 R2 をインストールする場合は、WSUS 3.0 SP2 をインストールする必要があります。Windows Server 2008 R2 に WSUS 3.0 SP1 をインストールしないでください。

#### WSUS 3.0 SP2 にアップグレードする前に

1.  イベント ログの最近のエラー、ダウンストリーム サーバーとアップストリーム サーバー間の同期の問題、およびクライアント レポートの問題を確認します。 これらの問題を解決してからアップグレードしてください。

2.  必要に応じて、DBCC CHECKDB を実行し、WSUS データベースのインデックスが正常に作成されていることを確認します。 DBCC CHECKDB の詳細については、[DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948) を参照してください。

3.  WSUS データベースをバックアップします。WSUS 3.0 SP2 セットアップでは、既定のディレクトリに新しいデータベースを追加します。このディレクトリは *&lt;ドライブ&gt;*\\WSUS (*&lt;ドライブ&gt;* は、最大の空き領域を持つローカルの NTFS ドライブ) にあります。 このディレクトリにデータベース バックアップが既にある場合、そのバックアップは上書きされます。 ベスト プラクティスとしては、別の場所に WSUS の現在のバージョンのデータベース バックアップを保存してから、WSUS 3.0 SP2 にアップグレードしてください。

4.  WSUS を使用してレポートを手動で変更して (つまり、Wsusutil ユーティリティを使用せずに)、SUS 1.0 または WSUS 2.0 を現在実行している場合は、既定の Web サイトを起動してから SUS 1.0 または WSUS 2.0 64 ビットをアンインストールしてください。

5.  既存の WSUS データベースへの接続が開いていると (たとえば SQL Server Management Studio が開いている場合)、インストールに失敗することがあります。 すべての接続を閉じてから WSUS 3.0 SP2 をインストールしてください。

### アップグレードの失敗からの回復

WSUS の以前のバージョンから WSUS 3.0 SP2 にアップグレードしようとして (サポートされていない SUS 1.0 からのアップグレード以外の何らかの理由で) 失敗した場合は、次のタスクを実行してください。

1.  WSUS の以前のバージョンを再インストールします。
2.  アップグレードを実行する前に作成したバックアップからデータベースを復元します。以前にインストールされた既存の WSUS 3.0 SP2 データベースがあると、アップグレードを正常に終了できません。 多くの場合、WSUS でもバックアップが自動的に作成されます。 場所については、WSUSSetup.log ファイルを参照してください。
3.  ログを確認して失敗の原因を判断し、問題を解決します。
4.  WSUS 3.0 SP2 をインストールします。

### WSUS 3.0 SP2 にアップグレードする前にコンピュータ名を変更すると、アップグレードが失敗することがある

WSUS 2.0 をインストールした後、および WSUS 3.0 SP2 にアップグレードする前にコンピュータ名を変更した場合、アップグレードが失敗する場合があります。

次のスクリプトを使用して、ASPNET Administrators および WSUS Administrators グループの削除と再追加を行ってください。 次に、アップグレードを再度実行してください。

        ```

### WSUS 2.0 上で MSDE から SQL Server 2008 または SQL Server 2005 に移行した場合、レジストリ値の変更が必要

WSUS 2.0 をインストール済みで、SQL Server 2008 または SQL Server 2005 に移行した場合、HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled の値を 1 から 0 に変更する必要があります。この作業を行わないで WSUS 3.0 SP2 にアップグレードしようとすると失敗します。

### WSUS 3.0 SP2 をアンインストールして、ログ ファイルをそのままにしておくと、再インストールの後でファイルは適切なアクセス許可を持たない可能性がある

WSUS 3.0 SP2 をアンインストールする場合、インストールのログ ファイルを保存するオプションがあります。WSUS 3.0 SP2 を再インストールする場合、古いログ ファイルはアクセス許可を失う可能性があります (通常は WSUS Administrators のみ)。 ベスト プラクティスとしては、インストール後にこれらのログ ファイルでアクセス許可を確認してください。

### WSUS 2.0 クライアントに "該当なし" 状態の更新プログラムが含まれる場合、WSUS 3.0 SP2 へのアップグレード後、その更新プログラムがしばらくの間 "不明" と表示される

既存の WSUS 2.0 サーバーに "該当なし" の更新プログラムが含まれるクライアントがある場合、WSUS 3.0 SP2 へのアップグレード後、これらの更新プログラムがしばらくの間 "不明" 状態と表示される可能性があります。 クライアントが次にスキャンを実行した後、更新状態は "該当なし" に戻ります。

WSUS 3.0 SP2 のインストール
---------------------------

『Microsoft Windows Server Update Services 3.0 SP2 のファースト ステップ ガイド』([http://go.microsoft.com/fwlink/?LinkId=139836](http://go.microsoft.com/fwlink/?linkid=139836)) に、Windows サーバー マネージャまたは WSUSSetup.exe ファイルを使用して WSUS 3.0 SP2 をインストールする手順が記載されています。

WSUS のインストール方法と使用方法の詳細については、次を参照してください。

『WSUS Deployment Guide』([http://go.microsoft.com/fwlink/?LinkId=139832](http://go.microsoft.com/fwlink/?linkid=139832))

『WSUS Operations Guide』([http://go.microsoft.com/fwlink/?LinkId=139838](http://go.microsoft.com/fwlink/?linkid=139838))

WSUS 3.0 SP2 無人インストールのセットアップ コマンド ライン パラメータ
----------------------------------------------------------------------

WSUS コマンド ライン セットアップ プログラムを使用すると、WSUS 3.0 SP2 の無人インストールを実行できます。次の表に、WSUS 3.0 SP2 セットアップのコマンド ライン パラメータを示します。

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
<td style="border:1px solid black;">アンインストールします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">前提条件チェック。 システムを調査し、前提条件が満たされていない場合は報告します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">コマンド ライン パラメータとその説明を表示します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">以前のバージョンの WSUS からアップグレードします (SUS 1.0 からのアップグレードはサポートされていません)。 このオプションで有効なパラメータは /q (サイレント インストール) のみです。 このオプションで有効なプロパティは DEFAULT_WEBSITE のみです。</td>
</tr>
</tbody>
</table>
  
次の表に、WSUS 3.0 SP2 のコマンド ライン プロパティを示します。
  
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
<td style="border:1px solid black;">コンテンツ ディレクトリへのパス。 既定値は、<em>WSUSInstallationDrive\WSUS\WSUSContent</em> です。<em>WSUSInstallationDrive</em> は空き領域が最大のローカル ドライブです。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Windows Internal Database データ ディレクトリへのパス。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">名前は、<em>サーバー名</em>\<em>SQL インスタンス名</em> の形式で表示されます。 データベース インスタンスが、ローカル コンピュータ上にある場合は、%COMPUTERNAME% 環境変数を使用します。 既存のインスタンスがない場合、既定では %COMPUTERNAME%\WSUS になります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DEFAULT_WEBSITE</td>
<td style="border:1px solid black;">0=ポート 8530、1=ポート 80。</td>
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
<td style="border:1px solid black;">0=ログ ファイルを保持、1=ログ ファイルを削除 (/u インストール スイッチと共に使用します)。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=現在のデータベースを使用、1=データベースを作成</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">Windows インストーラの進捗状況メッセージを返すウィンドウ ハンドル。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=Microsoft Update 向上プログラムに参加、0=Microsoft Update 向上プログラムに参加しない。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=データベースにコンテンツの場所を書き込まない、0=データベースにコンテンツの場所を書き込む (ネットワーク負荷分散のため)</td>
</tr>
</tbody>
</table>
  
### 使用例
  
```  
WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (ポート 8530 を使用して QUIET モードでインストール) WSUSSetup.exe /q /u (WSUS をアンインストール)  
```
 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ><img src="images/Dd939886.Important(WS.10).gif" />重要</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">WSUS 3.0 SP2 を QUIET モード (/q) でインストールし、コンピュータがすべての前提条件を満たしていない場合は、インストールによって WSUSPreReqCheck.xml というファイルが生成され、%TEMP% ディレクトリに保存されます。
</td>
</tr>
</tbody>
</table>
 

<span id="BKMK_KnownIssues"></span>
既知の問題
----------

-   WSUS インストール ウィザードが正常に終了すると、ユーザーは \[完了\] をクリックすることを求められます。 まれに、エラー ダイアログ ボックスで「サーバーと通信中にエラーが発生したため、ウィザードを閉じる必要があります。WSUS サーバー設定ウィザードは、WSUS 3.0 コンソールの \[オプション\] ページから再起動できます。」というメッセージが表示されます。インストール オプションが保存されたことを確認するには、WSUS 管理コンソールの \[オプション\] ページを開いて、各セクションの設定を確認してください。
-   **Windows Update エージェント (WUA) クライアントのローカライズされたバージョンは WSUS 3.0 SP2 以降でリリースされます**。 これは、Windows 7 のローカリゼーション スケジュールに依存しているためです。 WSUS 3.0 SP2 リリースとローカライズされたリリースの WUA クライアントの間の期間に、WUA クライアントは 5 つの言語 (英語、ドイツ語、フランス語、スペイン語、および日本語) のみをサポートします。
-   **この SP2 から導入された新しい更新レポートとコンピュータの状態レポートは、ダウンストリーム WSUS 3.0 SP1 サーバーを WSUS 3.0 SP2 サーバーから管理している環境では機能しません**。 新しいレポート機能を SP1 サーバーに対して実行する場合は、次のエラー メッセージが表示されます。"レポートを生成中にエラーが発生しました。 レポートを再度実行するか、問題が解決しない場合は、ネットワーク管理者に問い合わせてください。" レポートを再度実行しても問題が解決することはなく、これはネットワーク関連の問題でもありません。 新しいレポートは、SP1 には存在しない API 機能に依存しています。しかし、SP2 管理コンソールは、SP1 サーバーを管理しているときに、新しいレポートをブロックしません。
-   **SSL が証明書名なしで構成されている場合、WSUS 3.0 SP2 へのアップグレードは失敗します**。 SSL を構成する場合は証明書名が必要です。
-   **Windows Internal Database を実行している WSUS 3.0 SP2 が Windows Server 2008 にインストールされている場合、Windows Server 2008 R2** にアップグレードできません。 Windows Server 2008 R2 へのアップグレードを続行する前に、互換性チェック エラー メッセージが表示され、Windows Internal Database を無効にする必要があることが示されます。 Windows Server 2008 R2 へのアップグレードを続行する前に、Windows Internal Database をアップグレードする必要があります。 Windows Internal Database のアップグレードの手順および詳細な説明については、「[Windows 内部データベースの Service Pack の入手方法」](http://go.microsoft.com/fwlink/?linkid=162104) (http://go.microsoft.com/fwlink/?LinkId=162104) を参照してください。

著作権情報
----------

URL およびその他のインターネット Web サイトの参照を含め、このドキュメント内の情報は予告なしに変更される場合があります。 特に断りのない限り、例に使用されている会社、組織、製品、ドメイン名、電子メール アドレス、ロゴ、人物、場所、出来事はすべて架空のものです。 実在する会社、組織、製品、ドメイン名、電子メール アドレス、ロゴ、人物、場所、出来事とのかかわりを意図するものではなく、推測すべきものではありません。 お客様ご自身の責任において、適用されるすべての著作権関連法規に従ったご使用を願います。 このドキュメントのいかなる部分も、米国 Microsoft Corporation の書面による許諾を受けることなく、その目的を問わず、どのような形態であっても、複製または譲渡することは禁じられています。ここでいう形態とは、複写や記録など、電子的な、または物理的なすべての手段を含みます。ただしこれは、著作権法上のお客様の権利を制限するものではありません。

マイクロソフトは、このドキュメントに記載されている内容に関し、特許、特許申請、商標、著作権、またはその他の無体財産権を有する場合があります。 別途マイクロソフトのライセンス契約上に明示の規定のない限り、このドキュメントはこれらの特許、商標、著作権、またはその他の無体財産権に関する権利をお客様に許諾するものではありません。

© 2009 Microsoft Corporation. All rights reserved.

Microsoft、Active Directory、ActiveX、Authenticode、Excel、InfoPath、Internet Explorer、MSDN、Outlook、Visual Studio、Win32、Windows、Windows Server、および Windows Vista は、米国 Microsoft Corporation および/またはその関連会社の商標です。

その他すべての商標は、各社が所有する商標です。
