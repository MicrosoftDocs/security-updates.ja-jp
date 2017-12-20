---
TOCTitle: Windows Server Update Services リリース ノート
Title: Windows Server Update Services リリース ノート
ms:assetid: '4244109a-395a-4ff8-9989-ea55ab0964a3'
ms:contentKeyID: 18128137
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc720505(v=WS.10)'
---

Windows Server Update Services リリース ノート
==============================================

このドキュメントでは、Windows Server Update Services (WSUS) に影響する既知の問題について説明します。WSUS をインストールする際の推奨事項や要件も含まれています。

| ![](images/Cc720505.note(WS.10).gif)注                                                                                                                   |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| このドキュメントのコピーは、Microsoft ダウンロード センター ([http://go.microsoft.com/fwlink/?LinkId=48126](http://go.microsoft.com/fwlink/?linkid=48126)) からダウンロードできます。 |

はじめに
--------

#### 問題 1: IIS のインストールの必要性

Microsoft® Windows Server™ Update Services (WSUS) を使用するには、インターネット インフォメーション サービス (IIS) をインストールする必要があります。しかし、Microsoft Windows Server 2003 および Microsoft Windows® 2000 Server では IIS が既定でインストールされないので、IIS がインストールされていないことを通知するエラー メッセージが表示され、Windows Server Update Services セットアップを続行できない場合があります。

IIS をインストールするには

1.  コントロール パネルを開きます。
2.  \[プログラムの追加と削除\] をダブルクリックします。
3.  \[Windows コンポーネントの追加と削除\] をクリックします。
4.  \[コンポーネント\] 一覧で、\[プリケーション サーバー\] をクリックします。
5.  \[詳細\] をクリックします。
6.  \[ASP.NET\] チェック ボックスをオンにします。**ネットワーク COM+ アクセス**を有効にすると、インターネット インフォメーション サービス (IIS) が自動的に選択されます。
7.  \[インターネット インフォメーション サービス (IIS)\] を選択して\[詳細\] をクリックし、IIS のオプション コンポーネント一覧を表示します。
8.  インストールするオプション コンポーネントをすべて選択します。World Wide Web サービス オプション コンポーネントには、Active Server Pages コンポーネントやリモート管理 (HTML) などの重要なサブコンポーネントが含まれています。これらのサブコンポーネントを表示して選択するには、\[WWW (World Wide Web) サービス\]、\[詳細\] の順にクリックします。\[Windows コンポーネント ウィザード\] に戻るまで \[OK\] をクリックします。
9.  **\[次へ\]** をクリックし、\[Windows コンポーネント ウィザード\] を完了します。
10. IIS のインストール後、Windows Server Update Services セットアップを実行します。

#### 問題 2:Windows 2000 Server を実行しているサーバーでは、WSUS をインストールする前に、IIS 内に少なくとも 1 つの Web サイトが必要である

IIS 内に Web サイトが存在しない場合、Windows Server Update セットアップの実行中に、Web サイトを作成できない可能性があります。たとえば、Software Update Services (SUS) 1.0 サイトが IIS 内にある唯一のサイトであり、このサイトを削除してから WSUS をインストールした場合、この問題が発生します。

この場合、\[インターネット インフォメーション サービス (IIS) マネージャ\] スナップインを使用して、新しい Web サイトを作成する必要があります。この結果、WSUS のセットアップ中に、このサイトの選択、または新しいサイトの指定を行うことができます。

WSUS のインストールが既に試行済みで、サイトが存在しないためにセットアップが失敗している場合は、\[IIS マネージャ\] スナップインを開き、"Web Site \#1" というサイトを削除します。次に、上記の手順に従ってセットアップを再実行します。

#### 問題 3:必須コンポーネントのインストール

#### ソフトウェア要件

次の表に、サポートされている各オペレーティング システムに必要なソフトウェアを示します。WSUS セットアップを実行する前に、WSUS サーバーがこの要件の一覧を満たしていることを確認してください。これらの更新プログラムのインストール完了時に、コンピュータの再起動が必要な場合は、再起動してから WSUS をインストールしてください。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >オペレーティング システム</th>
<th style="border:1px solid black;" >要件</th>
<th style="border:1px solid black;" >ダウンロード</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">すべてのオペレーティング システム</td>
<td style="border:1px solid black;">Microsoft インターネット インフォメーション サービス (IIS) 5.0</td>
<td style="border:1px solid black;">オペレーティング システムからインストールします。
「問題 1IIS のインストールの必要性」を参照してください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">すべてのオペレーティング システム</td>
<td style="border:1px solid black;">Background Intelligent Transfer Service (BITS) 2.0</td>
<td style="border:1px solid black;">Windows Server 2003 オペレーティング システムの場合は、ダウンロード センターの「<a href="http://go.microsoft.com/fwlink/?linkid=47251">Windows Server 2003 用バックグラウンド インテリジェント転送サービス (BITS) 2.0 および WinHTTP 5.1 の更新プログラム (KB842773)</a>」(http://go.microsoft.com/fwlink/?LinkId=47251) を参照してください。
Windows Server 2000 オペレーティング システムの場合は、ダウンロード センターの「<a href="http://go.microsoft.com/fwlink/?linkid=46794">Windows 2000 用バックグラウンド インテリジェント転送サービス (BITS) 2.0 および WinHTTP 5.1 の更新プログラム (KB842773)</a>」(http://go.microsoft.com/fwlink/?LinkId=46794) を参照してください。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47358">Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003</a>
また、<a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> で重要な更新プログラムやサービス パックを検索して、Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003 をインストールすることもできます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">Microsoft SQL と完全に互換性のあるデータベース ソフトウェア</td>
<td style="border:1px solid black;">N/A</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft SQL と完全に互換性のあるデータベース ソフトウェア</td>
<td style="border:1px solid black;">Microsoft SQL Server 2000 を使用していない場合は、Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) をインストールできます。インストールするには、いくつかの手順を実行する必要があります。詳細については、後半の「Windows 2000 での MSDE 2000 のインストール」を参照してください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft Internet Explorer 6.0 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47359">Internet Explorer 6 Service Pack 1</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework Version 1.1 再配布可能パッケージ (http://go.microsoft.com/fwlink/?LinkId=47369)</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47369">Microsoft .NET Framework Version 1.1 再頒布可能パッケージ</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47368">Microsoft .NET Framework 1.1 Service Pack 1</a>
また、<a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update (http://go.microsoft.com/fwlink/?LinkId=47370)</a> で重要な更新プログラムやサービス パックを検索して、Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2000 をインストールすることもできます。</td>
</tr>
</tbody>
</table>
 

これらの要件の他に、WSUS が必要に応じてサーバーに ASP.NET バージョン 1.1 をインストールまたは構成する場合があります。WSUS セットアップにより ASP.NET が構成されます。

#### Windows 2000 上での MSDE 2000 のインストール

Windows 2000 に対して WSUS を使用していて、Microsoft SQL Server 2000 にアクセスできない場合は、WSUS セットアップを実行する前に Microsoft SQL Server 2000 Desktop Engine (MSDE) をインストールする必要があります。WSUS サーバー上に MSDE が既にインストールされている場合は、WSUS のための特別な MSDE インスタンスをセットアップする必要はありません。WSUS のセットアップ プロセスにおいて、単に既存のインスタンス名を指定してください。

Windows 2000 Server に MSDE をインストールするプロセスには、4 つの手順があります。まず、WSUS サーバー上のフォルダに MSDE アーカイブをダウンロードし、展開します。次に、コマンド プロンプトとコマンド ライン オプションを使用して MSDE セットアップを実行し、sa パスワードを設定して、インスタンス名として WSUS を割り当てます。次に、MSDE のインストールが完了したら、WSUS インスタンスが NT サービスとして実行しているかどうか確認する必要があります。最後に、MSDE にセキュリティ更新プログラムを追加して、WSUS サーバーを保護する必要があります。

#### 手順 1 :MSDE アーカイブをダウンロードして展開する

まず、WSUS サーバー上のフォルダに MSDE アーカイブをダウンロードし、展開します。[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Release A (http://go.microsoft.com/fwlink/?LinkId=47366 )](http://go.microsoft.com/fwlink/?linkid=47366) を参照してください。

#### 手順 2 :MSDE をインストールする

コマンド プロンプトとコマンド ライン オプションを使用して MSDE セットアップを実行し、sa パスワードを設定して、インスタンス名として WSUS を割り当てます。MSDE のインストールが完了したら、WSUS インスタンスが NT サービスとして実行しているかどうか確認する必要があります。

MSDE をインストールするには、次の手順に従って sa パスワードを設定してインスタンス名を割り当てます。

1.  コマンド プロンプトで、「手順 1 :MSDE アーカイブをダウンロードして展開する」で指定した MSDE インストール フォルダに移動します。
2.  次のように入力します。**setup sapwd="***&lt;パスワード&gt;***" instancename=WSUS**
    ここで、*&lt;パスワード&gt;* は、この MSDE インスタンス上の sa アカウント用の強力なパスワードで、**instancename** は、データベース インスタンスの名前を表します。別の方法として、("WSUS" の代わりに) WSUS データベースの既定のインスタンス名を使用することもできます。後者の場合、コマンド ライン パラメータで「**instancename=WSUS**」と入力する必要はありません。このコマンドを実行すると、MSDE セットアップ プログラムが起動し、sa パスワードが設定され、指定した値がこの MSDE インスタンスに割り当てられます。

#### 手順 3 :MSDE の WSUS インスタンスがインストールされていることを確認する

MSDE の WSUS インスタンスが見えることを確認します。

1.  \[スタート\] ボタン、\[ファイル名を指定して実行\] の順にクリックします。
2.  \[名前\] ボックスに**「services.msc」**と入力し、\[OK\] をクリックします。

サービスのリストを下にスクロールし、MSSQL$WSUS (インスタンス名に "WSUS" を使用した場合) または MSSQLSERVER (既定のインスタンス名を使用した場合) という名前のサービスが存在することを確認します。

#### 手順 4 :MSDE インスタンスを起動する

MSDE のインストールが完了したら、インスタンスを起動する必要があります。インスタンス名に "WSUS" を使用した場合は、"MSSQL$WSUS" を起動します。既定のインスンス名を使用した場合は、MSSQLSERVER を起動します。このサービスを起動しないと、WSUS はデータベース インスタンスを使用できません。

#### 手順 5 :MSDE を更新する

「[\[MS03-031\] SQL Server 用の累積的なセキュリティ修正プログラム](http://go.microsoft.com/fwlink/?linkid=47364)」のセキュリティ関連情報の掲示板で説明されているセキュリティ更新プログラムをダウンロードおよびインストールする必要があります。

このセキュリティ更新プログラムをダウンロードするには、「[SQL Server 2000 (32 ビット) セキュリティ修正プログラム MS03-031](http://go.microsoft.com/fwlink/?linkid=47363)」を参照してください。

#### 問題 4:最低限のディスク領域要件

次に、Windows Server Update Services のインストールに必要な最低限のディスク領域要件を示します。

-   1 GB のシステム パーティション
-   データベース ファイルを保存するための 2 GB のボリューム
-   6 GB (予測されるコンテンツ数に応じて)

#### 問題 5:WSUS の以前のバージョンでは、WSUS の最新バージョンをインストールする前に、\[プログラムの追加と削除\] を使用して以前のバージョンをアンインストールする必要がある

Windows Update Services Beta 1 または Beta 2 がインストールされているサーバー上に Windows Server Update Services をインストールする場合、まずコントロール パネルの \[プログラムの追加と削除\] を使用して、以前のバージョンをアンインストールする必要があります。

#### 問題 6:WSUS を使用するには、SQL Server 上でトリガのネスト オプションを有効にする必要がある

このオプションは既定では有効にされていますが、SQL Server 管理者によって無効にされている場合があります。

SQL Server データベースを Windows Server Update Services のデータ ストアとして使用する場合、WSUS 管理者が WSUS をインストールしてセットアップ時にこのデータベースを指定する前に、SQL Server 管理者がこのサーバー上でトリガのネスト オプションが有効にされているか確認する必要があります。

WSUS セットアップを実行すると、データベース特有のオプションである RECURSIVE\_TRIGGERS オプションが有効になります。しかし、トリガのネスト オプションは、サーバーのグローバル オプションであるため有効にはなりません。

トリガのネストが有効になっているかどうかを確認するには、次の操作を行います。

**sp\_configure 'nested triggers'**

SQL Server でトリガのネスト オプションを有効にするには、SQL Server を実行しているコンピュータ上のバッチ ファイルから次のコマンドを実行します。

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

#### 問題 7:WSUS セットアップのコマンド ライン パラメータ

WSUS の無人インストールを実行することができます。この詳細およびコマンド ライン パラーメータについては、『[Microsoft Windows Server Update Services 展開ガイド (http://go.microsoft.com/fwlink/?LinkId=41777)](http://go.microsoft.com/fwlink/?linkid=41777)』の「付録 A : 無人インストール」を参照してください。

既知の問題
----------

#### 問題 1:IIS Lockdown Wizard

Windows 2000 Server を実行しているコンピュータ上でインターネット インフォメーション サービス (IIS) を実行している場合は、Microsoft TechNet の IIS Lockdown ツールのページから、URLScan を含む IIS Lockdown Wizard の最新バージョンをインストールしてください。Microsoft は、お客様がこのツールをインストールして IIS サーバーのセキュリティの維持に役立てることを強くお勧めします。IIS Lockdown Wizard は、不要な IIS 機能を無効にすることで、セキュリティが危険にさらされるリスクを低減します。

| ![](images/Cc720505.note(WS.10).gif)注                                                                                                                                                                                                                                 |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| これらのコンポーネントは、WSUS セットアップによってインストールされません。これらのコンポーネントは、手動でインストールする必要があります。Windows Server 2003 を実行しているコンピュータに IIS Lockdown をインストールする必要はありません。Windows Server 2003 にはこの機能が組み込まれています。 |

#### 問題 2:データベース内で WSUS 構成を直接変更できない

Windows Server Update Services の構成データは、データベース (MSDE または SQL Server) 内に保存されます。ただし、データベースに直接アクセスして構成データを変更することはできません。管理者は、この方法で WSUS 構成を変更しないでください。WSUS コンソールを使用する方法、または WSUS API を呼び出す方法が、WSUS 構成の変更方法としてサポートされています。

#### 問題 3:WSUS 管理サイトにアクセスするには、アクティブ スクリプトを有効にする必要がある

Internet Explorer を使用して WSUS 管理サイトにアクセスする前に、管理者のワークステーション上でアクティブ スクリプトを許可するように Internet Explorer を構成する必要があります。

#### 問題 4:WSUS セットアップ中に IIS が再起動される

Windows Server Update Services セットアップを実行すると、IIS が予告なく再起動されます。これにより、組織内にある既存の Web サイトが影響を受ける可能性があります。

#### 問題 5:WSUS または SMS 管理ポイント (MP) の仮想ディレクトリ アクセスの変更

既定では、Windows Server Update Services のコンテンツ仮想ディレクトリに対する匿名アクセスが許可されています。この設定が認証を必要とするように変更すると、クライアントに認証エラーが送信され、更新プログラムをダウンロードするためのアクセスが拒否されます。これは、暗黙の認証が必要なときに Winhttp.dll が誤った認証コンテキストを使用するため、認証チャレンジが失敗するという既知の問題です。この問題を回避するには、WSUS サーバーおよび SMS の MP に対して、IIS 仮想ディレクトリへの匿名アクセスを確実に設定してください。

#### 問題 6:WSUS を Windows Small Business Server 2003 にインストールする場合、WSUS クライアントによるサーバーからの自己更新を有効にするには、既定の Web サイトの WSUS 仮想ルートのアクセス設定を変更する必要がある

WSUS サーバーは、既定の Web サイト (ポート 80) のホーム ディレクトリに SelfUpdate と ClientWebService の 2 つの仮想ルート (vroot) といくつかのファイルをインストールします。これにより、クライアントによる既定の Web サイトからの自己更新を実行できます。既定では、Windows Small Business Server 2003 上の既定の Web サイトによるサーバー以外の IP または localhost へのアクセスはすべて拒否されるよう構成されています。このため、仮想ルート SelfUpdate および ClientWebService によるアクセスは拒否され、クライアントは自己更新を実行できません。クライアントに自己更新のためのアクセスを付与するには、既定の Web サイトの SelfUpdate および ClientWebService 仮想ルートにおいて、次の手順を実行します。

1.  仮想ルートの \[プロパティ\] をクリックし、\[ディレクトリ セキュリティ\]、\[IP アドレスとドメイン名の制限\]、\[編集\] の順にクリックします。
2.  \[許可する\] を選択し、\[OK\] をクリックします。すべてのプロパティ ページを閉じます。

#### 問題 7:Small Business Server 上での WSUS のインストール - 統合に関する問題

-   Windows Small Business Server 2003 が ISA プロキシ サーバーを使用してインターネットにアクセスしている場合、\[設定\] ユーザー インターフェイスで以下の項目を手動で入力する必要があります。プロキシ サーバー設定、プロキシ サーバー名、およびポート
-   ISA が Windows 認証を使用している場合、プロキシ サーバーの資格情報を "&lt;ドメイン&gt;\\&lt;ユーザー&gt;" ("Internet Users" グループに属するユーザー) の形式で入力する必要があります。

#### 問題 8:あるコンピュータ グループから別のコンピュータ グループにコンピュータを移動すると、管理コンソール上でこのコンピュータが新しいグループ内に表示されるまで最大 1 時間かかる場合がある

ターゲット グループにコンピュータを始めて割り当てると、コンピュータのデータはグループ情報と一緒に変更されます。このデータは、定期的または 1 時間ごとに更新されます。したがって、あるコンピュータ グループから別のコンピュータ グループにコンピュータを移動すると、クライアント上でこのデータが更新され、変更後の状態が WSUS 管理コンソールに表示されるまで 1 時間かかる場合があります。

#### 問題 9:メンバ サーバーに WSUS をインストールした後で、このメンバ サーバーをドメイン コントローラに昇格させる場合、まず WSUS をアンインストールする必要がある

メンバ サーバーに WSUS をインストールした後で、このメンバ サーバーをドメイン コントローラに昇格させるには、次の手順を実行する必要があります。

1.  WSUS をアンインストールします。
2.  サーバーをドメイン コントローラに昇格させます。
3.  WSUS を再インストールします。

#### 問題 10:WSUS サーバーをドメイン コントローラからメンバ サーバーに降格させる場合、まず WSUS をアンインストールする必要がある

WSUS サーバーを実行しているドメイン コントローラをメンバ サーバーに降格させるには、次の手順を実行する必要があります。

1.  WSUS をアンインストールし、データベースを保持します。
2.  ASPNET というユーザー アカウントを作成します。
3.  コマンド プロンプトで、「**aspnet\_regiis -i**」と入力します。
4.  WSUS を再インストールし、保持したデータベースを使用します。

#### 問題 11:WSUS をインスールした後に .NET Framework 1.0 または 2.0 をインストールすると、WSUS 管理コンソールが表示されない

これは、.NET Framework 1.0 が IIS に登録されており、WSUS サーバーが .NET Framework 1.1 を必要とすることが原因です。この問題を解決するには、aspnet\_regiis.exe を開いて次のコマンドを実行します。ここで、*&lt;Web サイトの ID&gt;* は、次のレジストリ キーに含まれる値です。

HKLM\\Software\\Microsoft\\WindowsUpdateServices\\Server\\Setup\\IISTargetWebsiteIndex

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*&lt;Web サイトの ID&gt;*&gt;\\ROOT\\ReportingWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*&lt;Web サイトの ID&gt;*&gt;\\ROOT\\ClientWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*&lt;Web サイトの ID&gt;*&gt;\\ROOT\\SimpleAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*&lt;Web サイトの ID&gt;*&gt;\\ROOT\\WSUSAdmin
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*&lt;Web サイトの ID&gt;*&gt;\\ROOT\\AdministrationWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*&lt;Web サイトの ID&gt;*&gt;\\ROOT\\ServrSyncWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*&lt;Web サイトの ID&gt;*&gt;\\ROOT\\DssAuthWebService
-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;*&lt;Web サイトの ID&gt;*&gt;\\ROOT\\Content

#### 問題 12:リモート SQL の制限事項

WSUS は、残りの WSUS アプリケーションを実行するコンピュータ以外のコンピュータ上におけるデータベース ソフトウェアの実行を限定的にサポートします。

-   Windows 2000 Server をリモート SQL ペアにおけるフロントエンド コンピュータとして使用できません。
-   ドメイン コントローラとして構成されたサーバーをリモート SQL ペアのフロントエンドまたはバックエンドとして使用できません。
-   バックエンド コンピュータ上で、WMSDE または MSDE をデータベース ソフトウェアとして使用できません。
-   リモート サーバーにインストールされているターミナル サービスがアプリケーション モードで実行されている場合、(WSUS データベースとして使用する) リモート SQL サーバーのセットアップは失敗します。ターミナル サービス サーバーに SQL Server をインストールする場合、次の手順を実行する必要があります。
    1.  セットアップを実行する前に、コマンド プロンプトを開き、次のコマンドを入力します。**change user /install**
    2.  SQL Server のセットアップを実行します。
    3.  セットアップの実行後、コマンド プロンプトで次のコマンドを入力します。**change user /execute**
-   リモート SQL Server WSUS データベースを設定するには、フロントエンドとバックエンドの両方のコンピュータ上において、ローカル administrators セキュリティ グループのメンバである必要があります。
-   リモート SQL に関する問題の詳細については、『[Microsoft Windows Server Update Services 展開ガイド (http://go.microsoft.com/fwlink/?LinkId=41777)](http://go.microsoft.com/fwlink/?linkid=41777)』の「付録 C : リモート SQL」を参照してください。

#### 問題 13:レプリカのダウンストリーム サーバー上にある承認が、親のアップストリーム サーバー上にある承認よりも少ない

レプリカのダウンストリーム サーバー上にある承認が、親のアップストリーム サーバー上にある承認よりも少ないことがあります。これは、アップストリーム サーバー上でコンテンツのダウンロードが完了するまで、ダウンストリーム サーバーにインストールの承認が送信されないことが原因です。

#### 問題 14:同期が失敗する場合は、同期を再試行する

同期が失敗するとエラー メッセージが表示されます。この場合、まずは同期を再試行します。

#### 問題 15:WSUS の管理コンソールにアクセスしようとすると、System.IO.FileNotFoundException エラー メッセージが表示される

次のエラー メッセージが表示される場合、Network Service または ASP.NET アカウントのアクセス許可を調整する必要があります。

System.IO.FileNotFoundException:ファイル名またはアセンブリ名 *xxxxxx*.dll、またはそれらの依存関係のいずれかが見つかりませんでした。

ここで、*xxxx* はランダム名です。

Windows Server 2003 オペレーティング システムでこの問題を解決するには、Network Service アカウントに %systemroot%\\Temp への読み取り/書き込みアクセス権を付与します。Windows 2000 Server では、ASP.NET アカウントに %systemroot%\\Temp への読み取り/書き込みアクセス権を付与します。

#### 問題 16:SQL セキュリティ修正プログラム MS03-031 (KB815495)

実際にはクライアント上で更新プログラムのインストールが失敗した場合でも、WSUS サーバー上ではこの更新プログラムがインストールされていると表示される場合があります。これにより、クライアントにパッケージが再度提示される可能性があります。サーバー上で更新プログラムを承認しないことにより、この問題を回避できます。

#### 問題 17:RTM アップグレード中に IIS 設定が失われる

以前のバージョンの WSUS (RC など) がインストールされているサーバーに WSUS RTM をインストールする場合、WSUS RTM によって以前のバージョンがアンインストールされてから、新しいバージョンがインストールされます。これは、IIS で WSUS に関連のある vroot とファイルが削除されることを意味します。

既定の Web サイトに WSUS をインストールする場合、WSUS vroot に対して行ったすべての WSUS 関連の設定が失われます。たとえば、WSUS をセキュリティで保護するために、SSL 用の WSUS vroot を構成した場合、WSUS の RTM バージョンをインストールした後で、WSUS vroot を再構成する必要があります。注 :SSL が有効になっていないことを知らせる通知が WSUS コンソール上に表示されます。

既定の Web サイト以外の Web サイトに WSUS がインストールされていた場合、WSUS の Web サイト レベルにおける追加設定はすべて失われます。

#### 問題 18:ホスト ヘッダーの使用

IIS 内にある既定の Web サイト (WSUS Web サイト) にホスト ヘッダー値を割り当てる場合、既定の Web サイトへのホスト ヘッダー値を指定せずに、"未使用の IP アドレスすべて" または割り当てられた IP アドレスを IP アドレスの一覧に追加する必要があります。既定ではない Web サイトにも、同様に IP アドレスを追加してください。

**警告** :このとき、Windows® SharePoint® Services および Exchange の機能が損なわれる可能性があります。

#### 問題 19:Internet Explorer の強化が有効になっているコンピュータ上で、WSUS コンソールの URL を信頼済みサイトおよびローカル イントラネットの Web コンテンツ ゾーンに追加する必要があります。

コンピュータ上で Internet Explorer の強化 (Microsoft Windows Server 2003 の Internet Explorer 拡張セキュリティ構成コンポーネントとも呼ばれています) が有効にされている場合、WSUS コンソールを信頼済みサイトおよびローカル イントラネットの Web コンテンツ ゾーンに追加しないと、WSUS コンソールのページを開くたびに、ユーザーの資格情報を入力するようにプロンプトが表示されます。

WSUS コンソールを\[イントラネット\] および \[信頼済みサイト\] Web コンテンツ ゾーンに追加するには、次の手順を実行します。

1.  \[インターネット オプション\] を開きます (たとえば、\[スタート\] ボタン、\[コントロール パネル\]、\[インターネット オプション\] の順にクリックします)。
2.  **\[セキュリティ\]** タブで、\[イントラネット\]、\[サイト\]、\[詳細設定\] の順にクリックし、URL (http://*&lt;WSUS サーバー名&gt;*/WSUSAdmin) を追加して、\[OK\] をクリックします。
3.  \[信頼済みサイト\]、\[サイト\] の順にクリックし、WSUS コンソールの URL を追加して、\[OK\] をクリックします。\[インターネット オプション\] を終了するには、\[OK\] をもう一度クリックします。

#### 問題 20:WSUS リリース候補版からのアップグレードが失敗する

WSUS リリース候補版からのアップグレードは自己更新ツリー問題が原因で失敗することがあります。これはアップグレードを試みたときに同時に複数のクライアントが自己更新を実行した場合に発生します。

この問題を解決するには

1.  ネットワークから WSUS サーバーを切断し、クライアントがサーバーに接続できないことを確認します。
2.  コマンド プロンプトで、**iisrestart /reset** と入力して ENTER キーを押します。
3.  アップグレードを実行します。

#### 問題 21:SUS 1.0 の一部の承認が WSUS への移行に失敗する

SUS 1.0 から WSUS に移行したときに、SUS 1.0 サーバーの一部の承認が WSUS サーバーに移行できません。これは SUS 1.0 で使用できたいくつかの更新プログラムが WSUS では使用できないことが原因です。さらに、WSUS は SUS よりサポートする更新プログラムが多いため、移行処理の完了後、WSUS サーバー上の重要な更新プログラムが未承認になることがあります。

マイクロソフトでは、SUS 1.0 からの移行後、WSUS サーバー上の未承認の更新プログラムを確認することを強くお勧めします。

SUS 1.0 から WSUS への移行の詳細については、[Software Update Services から Windows Server Update Services への移行のステップバイステップ ガイドに関するページ](http://go.microsoft.com/fwlink/?linkid=48042) (http://go.microsoft.com/fwlink/?LinkId=48042) を参照してください。

#### 問題 22:WMSDE を SQL Server に移行している場合、WSUS 2.0 Service Pack 1 にアップグレードする前にこのレジストリ エントリを修正する

インストールした WMSDE を SQL Server (リモートまたはローカル) に移行済みで、WSUS 2.0 の Service Pack 1 へのアップグレードを計画している場合、次のレジストリ エントリを変更してください。

HKLM\\Software\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled

値を 1 から 0 に変更する必要があります。

#### 問題 23:リモート SQL インストールから WSUS 2.0 Service Pack 1 への移行

リモート SQL 構成で WSUS 2.0 Service Pack 1 に移行する際は、次の手順を実行します。

フロントエンド サーバー上でセットアップ パッケージをスイッチなしで実行し、アップグレードを選択します。

バックエンド サーバー上でセットアップ パッケージをスイッチなしで実行し、アップグレードを選択します。

#### 著作権

このドキュメントに記載されている情報は、このドキュメントの発行時点におけるマイクロソフトの見解を反映したものです。変化する市場状況に対応する必要があるため、このドキュメントは、記載された内容の実現に関するマイクロソフトの確約とはみなされないものとします。また、発行以降に発表される情報の正確性に関して、マイクロソフトはいかなる保証もいたしません。

このドキュメントに記載された内容は情報提供のみを目的としており、明示または黙示に関わらず、これらの情報についてマイクロソフトはいかなる責任も負わないものとします。

お客様ご自身の責任において、適用されるすべての著作権関連法規に従ったご使用を願います。このドキュメントのいかなる部分も、米国 Microsoft Corporation の書面による許諾を受けることなく、その目的を問わず、どのような形態であっても、複製または譲渡することは禁じられています。ここでいう形態とは、複写や記録など、電子的な、または物理的なすべての手段を含みます。ただしこれは、著作権法上のお客様の権利を制限するものではありません。

マイクロソフトは、このドキュメントに記載されている内容に関し、特許、特許申請、商標、著作権、またはその他の無体財産権を有する場合があります。別途マイクロソフトのライセンス契約上に明示の規定のない限り、このドキュメントはこれらの特許、商標、著作権、またはその他の無体財産権に関する権利をお客様に許諾するものではありません。

別途記載されていない場合、このソフトウェアおよび関連するドキュメントで使用している会社、組織、製品、ドメイン名、電子メール アドレス、ロゴ、人物、場所、キャラクタ、データなどの名称は架空のものです。実在する商品名、団体名、個人名、ドメイン名、電子メール アドレス、ロゴ、場所などとは一切関係ありません。

© 2005 Microsoft Corporation.All rights reserved.

Microsoft、SQL Server、Windows、および Windows Server は、米国 Microsoft Corporation の米国およびその他の国における登録商標または商標です。

記載されている会社名、製品名には、各社の商標のものもあります。
