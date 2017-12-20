---
TOCTitle: WSUS Service Pack 1 リリース ノート
Title: WSUS Service Pack 1 リリース ノート
ms:assetid: '937ecfe9-e8e0-41ac-85f7-4b65956f3d1e'
ms:contentKeyID: 18128194
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc708486(v=WS.10)'
---

WSUS Service Pack 1 リリース ノート
===================================

公開日: 2006年6月2日

このドキュメントでは、Windows Server Update Services Service Pack 1 (WSUS SP1) に影響する既知の問題について説明します。WSUS SP1 に関する情報の後に、WSUS の初期リリース ノートに含まれていたすべての情報を記載しています。WSUS インストール時の推奨事項と要件もここでご確認ください。

##### トピック

![](images/Cc708486.arrow_px_down(ja-jp,WS.10).gif)[WSUS SP1 の新機能](#id0e2)
![](images/Cc708486.arrow_px_down(ja-jp,WS.10).gif)[WSUS SP1 にアップグレードする前に](#id0elb)
![](images/Cc708486.arrow_px_down(ja-jp,WS.10).gif)[WSUS の初期リリース ノートの内容](#id0ead)

### WSUS SP1 の新機能

WSUS SP1 は WSUS のサービス パック リリースです。WSUS SP1 を適用すると、WSUS のセキュリティ、信頼性、拡張性、互換性、およびパフォーマンスが強化されます。新機能と強化点は次のとおりです。

-   Windows Vista クライアントのサポート : Windows Vista を実行しているコンピュータを、WSUS SP1 Server によって更新できます。

-   サポートされるクライアント言語の増加 : Office と Windows Vista で使用できるすべての言語がサポートされます。

-   WMSDE の新バージョン : WSUS SP1 を適用すると、WMSDE インスタンスは WMSDE SP4 にアップグレードされます (WSUS RTM では WMSDE SP3 を使用しています)。

-   パフォーマンスの向上 : WSUS SP1 ではさまざまな点でパフォーマンスが強化され、ユーザー インターフェイスの応答時間がより速くなります。

-   すべての修正プログラムを同梱 : WSUS SP1 には、WSUS RTM 以降にリリースされた変更と修正プログラムがすべて含まれています。

-   SQL Server 2005 のサポート : SQL Server 2005、SQL Server 2005 Service Pack 1 適用済み、SQL Server 2005 Service Pack 2 適用済みが対象となります。

![](images/Cc708486.arrow_px_up(ja-jp,WS.10).gif)[ページのトップへ](#ctl00_rs1_eb1_panel1)

### WSUS SP1 にアップグレードする前に

次に示す問題は WSUS SP1 へのアップグレードに特有のものです。以前このトピックの「はじめに」に記載した問題と要件は引き続き有効であり、ここには記載しません。たとえば、以前「はじめに」に記載したセットアップの要件は引き続き有効です。

#### 問題 1 : データベースのバックアップ用に十分なディスク領域があることを確認する

WSUS RTM からアップグレードする場合、WSUS SP1 セットアップでは自動的に WSUS データベースのバックアップが作成されます。したがって、WSUS サーバーのファイル システムに、WSUS データベースのバックアップを保存するための十分なディスク領域があることを確認する必要があります。ディスク領域が不足していると、WSUS SP1 セットアップは失敗します。

**十分なディスク領域があるかどうかを確認するには**

1.  Windows エクスプローラを起動し、WSUS データベースの保存先フォルダに移動します。既定では、データベースは次の場所にインストールされます。

        <DriveLetter>:\WSUS\MSSQL$WSUS\Data\

2.  **Cｔｒｌ** キーを押しながら SUSDB.MDF および SUSDB\_log.LDF を選択し、右クリックして \[プロパティ\] をクリックします。

3.  プロパティ ダイアログ ボックスで、\[ディスク上のサイズ\] の値を確認します。WSUS SP1 をインストールするには、ディスクの空き領域がこの値以上である必要があります。

4.  \[スタート\] ボタンをクリックして \[マイ コンピュータ\] をクリックし、WSUS のインストール先ディスクに必要な空き領域があることを確認します。

何らかの理由で WSUS SP1 セットアップが失敗した場合は、バックアップしたデータベースを手動で復元する必要があります。WSUS データベースの復元の手順については、[WSUS 操作ガイド](http://technet.microsoft.com/ja-jp/library/cc720431.aspx) (英語) を参照してください。

#### 問題 2 : WSUS SP1 がアップグレードできるのは WSUS RTM のみ

WSUS SP1 を使用してアップグレードできるのは、WSUS RTM だけです。現段階では、WSUS リリース候補版からのアップグレードはサポートされていません。WSUS リリース候補版やそれ以前の WSUS のビルドがインストールされている場合は、これらのビルドをアンインストールしてから WSUS SP1 を実行する必要があります。

#### 問題 3 : WSUS SP1 のアップグレード中、サーバー上の IIS サービスが停止する

アップグレード処理中は、WSUS SP1 アップグレード インストーラによって、サーバー上のインターネット インフォメーション サービス (IIS) が停止されます。アップグレード中、サーバー上の IIS でホストされているすべての Web サイトは使用できなくなります。アップグレードが終了すると、IIS は自動的に起動します。

#### 問題 4 : アップグレード中、WSUS API を呼び出すアプリケーションは実行不可

WSUS アプリケーション インターフェイス (API) 呼び出しは、WSUS SP1 インストーラと競合し、アップグレードが失敗する原因となります。このとき、アップグレードを完了するにはサーバーの再起動が必要というメッセージが表示されます。

#### 問題 5 : アップグレードが失敗した場合、アップグレード プロセスの最初に作成したバックアップ データベースを使用して WSUS サーバーを以前の状態に復元できる

アップグレード プロセスの最初に、WSUS SP1 アップグレード インストーラによって、バックアップ データベースが作成されます。アップグレードが失敗した場合は、WSUS サーバーを以前の状態に手動で復元できます。これには、次の操作を行います。

1.  WSUSSetup\_%timestamp%.log を開いて、バックアップ データベースの場所を確認します。このログ ファイルは %programfiles%\\Update Services\\LogFiles フォルダにあります。このファイルに、バックアップ データベース ファイルの場所が記録されています。

2.  WSUS サーバー上にバックアップ データベースを復元します。

3.  WSUS を削除 (またはアンインストール) します。データベースを保持するかどうかを尋ねるプロンプトが表示されたら、保持するよう選択します。

4.  WSUS を再インストールします。既存のデータベースを使用するかどうかを尋ねるプロンプトが表示されたら、使用するよう選択します。

![](images/Cc708486.arrow_px_up(ja-jp,WS.10).gif)[ページのトップへ](#ctl00_rs1_eb1_panel1)

### WSUS の初期リリース ノートの内容

以下は、WSUS の初期リリース ノートの内容です。WSUS SP1 では、次に示す問題はいずれも解決されていません。参考としてお使いください。

#### はじめに

##### 問題 1 : IIS をインストールする必要がある

Microsoft® Windows Server™ Update Services (WSUS) を使用するには、インターネット インフォメーション サービス (IIS) をインストールする必要があります。しかし、Microsoft Windows Server 2003 および Microsoft Windows® 2000 Serverでは IIS が既定でインストールされていないので、IIS がインストールされていないことを通知するエラー メッセージが表示され、Windows Server Update Services セットアップを続行できない場合があります。

IIS をインストールするには

1.  コントロール パネルを開きます。

2.  \[プログラムの追加と削除\] をダブルクリックします。

3.  \[Windows コンポーネントの追加と削除\] をクリックします。

4.  \[コンポーネント\] 一覧で、\[アプリケーション サーバー\] をクリックします。

5.  \[詳細\] をクリックします。

6.  \[ASP.NET\] チェック ボックスをオンにします。ネットワーク COM+ アクセスを有効にすると、インターネット インフォメーション サービス (IIS) が自動的に選択されます。

7.  \[インターネット インフォメーション サービス (IIS)\] を選択し、\[詳細\] をクリックして、IIS のオプション コンポーネント一覧を表示します。

8.  インストールするすべてのオプション コンポーネントを選択します。World Wide Web サービス オプション コンポーネントには、Active Server Pages コンポーネントやリモート管理 (HTML) などの重要なサブコンポーネントが含まれています。これらのサブコンポーネントを表示して選択するには、\[WWW (World Wide Web) サービス\]、\[詳細\] の順にクリックします。\[Windows コンポーネント ウィザード\] に戻るまで \[OK\] をクリックします。

9.  \[次へ\] をクリックし、\[Windows コンポーネント ウィザード\] を完了します。

10. IIS のインストール後、Windows Server Update Services セットアップを実行します。

##### 問題 2 : Windows 2000 Server を実行しているサーバーでは、WSUS をインストールする前に、IIS に少なくとも 1 つの Web サイトが必要である

IIS に Web サイトが存在しない場合は、Windows Server Update セットアップの実行中に、Web サイトを作成できないことがあります。これはたとえば、Software Update Services (SUS) 1.0 サイトが IIS 内の唯一のサイトであり、このサイトを削除してから WSUS をインストールした場合などです。

この場合は、\[インターネット インフォメーション サービス (IIS) マネージャ\] スナップインを使用して、新しい Web サイトを作成する必要があります。これにより、WSUS のセットアップ中に、このサイトを選択したり新しいサイトを指定したりできます。

WSUS のインストールを既に試みていて、サイトが存在しないためにセットアップが失敗している場合は、\[IIS マネージャ\] スナップインを開き、"Web Site \#1" というサイトを削除します。次に、前に説明した手順に従ってセットアップを再実行します。

##### 問題 3 : 必須コンポーネントのインストール

**ソフトウェア要件**

次の表は、サポートされる各オペレーティング システムに必要なソフトウェアを示しています。WSUS セットアップを実行する前に、WSUS サーバーがこの要件の一覧を満たしていることを確認してください。インストール完了時に、いずれかの更新プログラムによりコンピュータの再起動が必要な場合は、再起動してから WSUS をインストールしてください。

 
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
<td style="border:1px solid black;">オペレーティング システムからインストールします。<br />
「問題 1 : IIS をインストールする必要がある」を参照してください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">すべてのオペレーティング システム</td>
<td style="border:1px solid black;">Background Intelligent Transfer Service (BITS) 2.0</td>
<td style="border:1px solid black;">Windows Server 2003 オペレーティング システムの場合は、ダウンロード センターの <a href="http://go.microsoft.com/fwlink/?linkid=47251">Windows Server 2003 用 Background Intelligent Transfer Service (BITS) 2.0 および WinHTTP 5.1 の更新プログラム (KB842773) についてのページ</a> (http://go.microsoft.com/fwlink/?LinkId=47251) (英語) を参照してください。<br />
<br />
Windows Server 2000 オペレーティング システムの場合は、ダウンロード センターの <a href="http://go.microsoft.com/fwlink/?linkid=46794">Windows 2000 用 Background Intelligent Transfer Service (BITS) 2.0 および WinHTTP 5.1 の更新プログラム (KB842773) についてのページ</a> (http://go.microsoft.com/fwlink/?LinkId=46794) (英語) を参照してください。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47358">Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003</a><br />
<br />
または、<a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> で重要な更新プログラムや Service Pack を検索して、Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003 をインストールすることもできます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">Microsoft SQL と完全に互換性のあるデータベース ソフトウェア</td>
<td style="border:1px solid black;">N/A</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft SQL と完全に互換性のあるデータベース ソフトウェア</td>
<td style="border:1px solid black;">Microsoft SQL Server 2000 を使用していない場合は、Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) をインストールできます。これには、いくつかの手順を実行する必要があります。詳細については、後の「Windows 2000 での MSDE 2000 のインストール」を参照してください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft Internet Explorer 6.0 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47359">Internet Explorer 6 Service Pack 1</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework Version 1.1 再配布可能パッケージ</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47369">Microsoft .NET Framework Version 1.1 再配布可能パッケージ</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Server</td>
<td style="border:1px solid black;">Microsoft .NET Framework 1.1 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=47368">Microsoft .NET Framework 1.1 Service Pack 1</a><br />
<br />
または、<a href="http://go.microsoft.com/fwlink/?linkid=47370">Windows Update</a> で重要な更新プログラムや Service Pack を検索して、Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2000 をインストールすることもできます。</td>
</tr>
</tbody>
</table>
 

これらの要件に加えて、WSUS は必要に応じてサーバー上に ASP.NET バージョン 1.1 をインストールまたは構成する場合があります。WSUS セットアップにより ASP.NET が構成されます。

##### Windows 2000 での MSDE 2000 のインストール

WSUS に Windows 2000 を使用して Microsoft SQL Server 2000 にアクセスできない場合は、WSUS を実行する前に Microsoft SQL Server 2000 Desktop Engine (MSDE) をインストールする必要があります。WSUS サーバーに既に MSDE がインストールされている場合は、WSUS 用の特別な MSDE インスタンスをセットアップする必要はありません。WSUS のセットアップ プロセスでは、単に既存のインスタンス名を指定します。

Windows 2000 Server に MSDE をインストールするプロセスは、4 つの手順から成ります。まず、MSDE アーカイブをダウンロードし、WSUS サーバー上のフォルダに展開します。次に、コマンド プロンプトとコマンド ライン オプションを使用して MSDE セットアップを実行し、sa パスワードを設定して、インスタンス名として WSUS を割り当てます。次に、MSDE のインストールの完了後、WSUS インスタンスが NT サービスとして実行されているかどうかを確認する必要があります。最後に、WSUS サーバーを保護するために、MSDE にセキュリティ更新プログラムを追加する必要があります。

##### 手順 1 : MSDE アーカイブをダウンロードして展開する

MSDE アーカイブをダウンロードし、WSUS サーバー上のフォルダに展開する必要があります。[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Release A](http://go.microsoft.com/fwlink/?linkid=47366) (英語) を参照してください。

##### 手順 2 : MSDE をインストールする

コマンド プロンプトとコマンド ライン オプションを使用して MSDE セットアップを実行し、sa パスワードを設定して、インスタンス名として WSUS を割り当てます。MSDE のインストールの完了後、WSUS インスタンスが NT サービスとして実行されているかどうかを確認する必要があります。

MSDE をインストールするには、次の手順に従って、sa パスワードを設定してインスタンス名を割り当てます。

1.  コマンド プロンプトで、「手順 1: MSDE アーカイブをダウンロードして展開する」で指定した MSDE インストール フォルダに移動します。

2.  次のように入力します。**setup sapwd="**&lt;パスワード&gt;**" instancename=WSUS**
    &lt;パスワード&gt; は、この MSDE インスタンス上の sa アカウント用の強力なパスワードで、**instancename** は、データベース インスタンスの名前です。別の方法として、WSUS データベースの既定のインスタンス名を ("WSUS" の代わりに) 使用することもできます。その場合は、コマンド ライン パラメータで「instancename=WSUS」と入力する必要はありません。このコマンドにより、MSDE セットアップ プログラムが起動し、sa パスワードが設定され、指定した名前がこの MSDE インスタンスに割り当てられます。

##### 手順 3 : MSDE の WSUS インスタンスがインストールされていることを確認する

1.  \[スタート\] ボタン、\[ファイル名を指定して実行\] の順にクリックします。

2.  \[名前\] ボックスに「services.msc」と入力し、\[OK\] をクリックします。

サービスのリストを下にスクロールし、MSSQL$WSUS (インスタンス名に "WSUS" を使用した場合) または MSSQLSERVER (既定のインスタンス名を使用した場合) という名前のサービスが存在することを確認します。

##### 手順 4 : MSDE インスタンスを起動する

MSDE のインストールが完了してから、インスタンスを起動する必要があります。インスタンス名に "WSUS" を使用した場合は、"MSSQL$WSUS" を起動します。既定のインスタンス名を使用した場合は、MSSQLSERVER を起動します。このサービスを起動しないと、WSUS はデータベース インスタンスを使用できません。

##### 手順 5 : MSDE を更新する

[SQL Server 用の累積的なセキュリティ修正プログラム MS03-031](http://go.microsoft.com/fwlink/?linkid=47364) のセキュリティ関連情報で説明されているセキュリティ更新プログラムを、ダウンロードおよびインストールする必要があります。

このセキュリティ更新プログラムをダウンロードするには、[SQL Server 2000 (32 ビット) セキュリティ修正プログラム MS03-031](http://go.microsoft.com/fwlink/?linkid=47363) (英語) を参照してください。

##### 問題 4 : 最低限のディスク領域要件

次に、Windows Server Update Services をインストールするための最低限のディスク領域要件を示します。

-   システム パーティションに 1 ギガバイト (GB)

-   データベース ファイルを保存するための 2 GB のボリューム

-   6 GB (予測されるコンテンツ数に応じて)

##### 問題 5 : WSUS の最新バージョンをインストールする前に、\[プログラムの追加と削除\] を使用して以前のバージョンをアンインストールする必要がある

Windows Update Services Beta 1 または Beta 2 がインストールされているサーバー上に Windows Server Update Services をインストールするには、最初にコントロール パネルの \[プログラムの追加と削除\] を使用して、以前のバージョンをアンインストールする必要があります。

##### 問題 6 : WSUS では、SQL Server でトリガのネスト オプションを有効にする必要がある

このオプションは既定では有効になっていますが、SQL Server 管理者によって無効にされている場合もあります。
SQL Server データベースを Windows Server Update Services のデータ ストアとして使用する場合は、WSUS 管理者が WSUS をインストールしてセットアップ時にこのデータベースを指定する前に、SQL Server 管理者がこのサーバー上でトリガのネスト オプションが有効であることを確認する必要があります。
WSUS セットアップを実行すると、RECURSIVE\_TRIGGERS オプションが有効になります。これはデータベース固有のオプションです。ただし、トリガのネスト オプションはサーバーのグローバル オプションであるため有効になりません。
トリガのネストが有効になっているかどうかを確認するには、次の操作を行います。

**sp\_configure 'nested triggers'**
SQL Server でトリガのネスト オプションを有効にするには、SQL Server を実行しているコンピュータでバッチ ファイルから次を実行します。
**sp\_configure 'nested triggers', 1**
**GO**
**RECONFIGURE**
**GO**

##### 問題 7 : WSUS セットアップのコマンド ライン パラメータ

WSUS の無人インストールを実行することができます。この詳細およびコマンド ライン パラーメータについては、[Microsoft Windows Server Update Services の展開に関するドキュメント](https://technet.microsoft.com/ja-jp/library/ace052df-74e7-4d6a-b5d4-f7911bb06b40(v=WS.10)) で、無人インストールについて説明している付録 A を参照してください。

#### 既知の問題

##### 問題 1 : IIS Lockdown Wizard

Windows2000 Server を実行しているコンピュータ上でインターネット インフォメーション サービス (IIS) を実行している場合は、Microsoft TechNet の IIS Lockdown ツールのページから、URLScan を含む IIS Lockdown Wizard の最新バージョンをインストールしてください。このツールをインストールして IIS サーバーのセキュリティの維持に役立てることを強くお勧めします。IIS Lockdown Wizard は、IIS の不要な機能を無効にすることで、セキュリティ リスクの可能性を低減します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>注</strong><br />
WSUS セットアップでは、これらのコンポーネントはインストールされません。これらは手動でインストールする必要があります。Windows Server 2003 を実行しているコンピュータに IIS Lockdown をインストールする必要はありません。Windows Server 2003 にはこの機能が組み込まれています。</td>
</tr>
</tbody>
</table>
 

#### 問題 2 : WSUS 構成をデータベースから直接変更できない

Windows Server Update Services の構成データは、データベース (MSDE または SQL Server) 内に保存されます。ただし、データベースに直接アクセスして構成データを変更することはできません。管理者は、この方法で WSUS 構成を変更しないでください。サポートされている WSUS 構成の変更方法は、WSUS コンソールを使用する方法か、WSUS API を呼び出す方法です。

#### 問題 3 : WSUS 管理サイトにアクセスするには、アクティブ スクリプティングを有効にする必要がある

Internet Explorer を使用して WSUS 管理サイトにアクセスする前に、管理者のワークステーションから、アクティブ スクリプティングを許可するよう Internet Explorer を構成する必要があります。

#### 問題 4 : WSUS セットアップ時に IIS が再起動される

Windows Server Update Services セットアップを実行すると、IIS が通知なく再起動されます。これにより、組織内の既存の Web サイトが影響を受ける可能性があります。

#### 問題 5 : WSUS または SMS 管理ポイント (MP) の仮想ディレクトリ アクセスの変更

既定では、Windows Server Update Services のコンテンツ仮想ディレクトリには、匿名アクセスが許可されています。認証が必要となるようこの設定を変更すると、クライアントは認証エラーを受信し、更新プログラムをダウンロードするためのアクセスが拒否されます。これは、暗黙の認証が必要となるときに Winhttp.dll で誤った認証コンテキストが使用され、認証チャレンジが失敗するという既知の問題です。この問題を回避するには、WSUS サーバーおよび SMS の MP に、IIS 仮想ディレクトリへの匿名アクセスをセットアップしてください。

#### 問題 6 : WSUS を Windows Small Business Server 2003 にインストールする場合、WSUS クライアントによるサーバーからの自己更新を有効にするには、既定の Web サイトの WSUS 仮想ルートのアクセス設定を変更する必要がある

WSUS サーバーは既定の Web サイト (ポート 80) のホーム ディレクトリに、SelfUpdate と ClientWebService の 2 つの仮想ルート (vroot) といくつかのファイルをインストールします。これにより、クライアントは既定の Web サイトから自己更新を実行できます。既定では、Windows Small Business Server 2003 では、既定の Web サイトは、サーバー以外の IP または localhost へのアクセスがすべて拒否されるよう構成されています。このため、仮想ルート SelfUpdate および ClientWebService はアクセスを拒否され、クライアントは自己更新を実行できません。クライアントに自己更新のためのアクセスを付与するには、既定の Web サイトの SelfUpdate および ClientWebService 仮想ルートで、次の手順を実行します。

-   仮想ルートの \[プロパティ\] をクリックし、\[ディレクトリ セキュリティ\]、\[IP アドレスとドメイン名の制限\]、\[編集\] の順にクリックします。

-   \[許可する\] を選択し、\[OK\] をクリックします。すべてのプロパティ ページを閉じます。

#### 問題 7 : Small Business Server での WSUS のインストール - 統合に関する問題

-   Windows Small Business Server 2003 で ISA プロキシ サーバーを使用してインターネットにアクセスしている場合は、\[設定\] ユーザー インターフェイスに、プロキシ サーバー設定、プロキシ サーバー名、およびポートを手動で入力する必要があります。

-   ISA で Windows 認証を使用する場合は、プロキシ サーバーの資格情報を、"&lt;ドメイン&gt;\\&lt;ユーザー&gt;" ("Internet Users" グループに属するユーザー) の形式で入力する必要があります。

#### 問題 8 : コンピュータ グループのコンピュータを別のコンピュータ グループに移動すると、管理コンソールでこのコンピュータが新しいグループとして表示されるまでに最大 1 時間かかる場合がある

コンピュータを最初にターゲット グループに割り当てると、コンピュータのデータがこのグループ情報によって変更されます。このデータは、定期的または 1 時間ごとに更新されます。したがって、コンピュータ グループのコンピュータを別のコンピュータ グループに移動すると、クライアント上でこのデータが更新され、変更後の状態が WSUS 管理コンソールに表示されるまでに 1 時間かかることがあります。

#### 問題 9 : メンバ サーバーに WSUS をインストールした後で、このメンバ サーバーをドメイン コントローラに昇格する場合、最初に WSUS をアンインストールする必要がある

メンバ サーバーに WSUS をインストールした後で、このメンバ サーバーをドメイン コントローラに昇格するには、次の手順を実行する必要があります。

1.  WSUS をアンインストールします。

2.  サーバーをドメイン コントローラに昇格します。

3.  WSUS を再インストールします。

#### 問題 10 : WSUS サーバーをドメイン コントローラからメンバ サーバーに降格する場合、最初に WSUS をアンインストールする必要がある

ドメイン コントローラで WSUS サーバーを実行している場合に、このドメイン コントローラをメンバ サーバーに降格するには、次の手順を実行する必要があります。

1.  WSUS をアンインストールし、データベースを保持します。

2.  ASPNET というユーザー アカウントを作成します。

3.  コマンド プロンプトで、「aspnet\_regiis -i」と入力します。

4.  WSUS を再インストールし、保持したデータベースを使用します。

#### 問題 11 : WSUS のインストール後に .NET Framework 1.0 または 2.0 をインストールした場合に、WSUS 管理コンソールが表示されない

これは、IIS には .NET Framework 1.0 が登録されていて、WSUS サーバーは .NET Framework 1.1 を必要とすることが原因です。この問題を解決するには、aspnet\_regiis.exe を開いて次のコマンドを実行します。&lt;Web サイトの ID&gt; は、次のレジストリ キーに含まれる値です。

HKLM\\Software\\Microsoft\\WindowsUpdateServices\\Server\\Setup\\IISTargetWebsiteIndex

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;Web サイトの ID&gt;\\ROOT\\ReportingWebService

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;Web サイトの ID&gt;\\ROOT\\ClientWebService

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;Web サイトの ID&gt;\\ROOT\\SimpleAuthWebService

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;Web サイトの ID&gt;\\ROOT\\WSUSAdmin

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;Web サイトの ID&gt;\\ROOT\\AdministrationWebService

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;Web サイトの ID&gt;\\ROOT\\ServrSyncWebService

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;Web サイトの ID&gt;\\ROOT\\DssAuthWebService

-   %windir%\\Microsoft.NET\\Framework\\v1.1.4322\\\\aspnet\_regiis.exe -s W3SVC\\&lt;Web サイトの ID&gt;\\ROOT\\Content

#### 問題 12 : リモート SQL の制限事項

WSUS は、他の WSUS アプリケーションを実行するコンピュータ以外のコンピュータ上では、データベース ソフトウェアの実行を限定的にサポートします。

-   Windows 2000 Server は、リモート SQL ペアにおけるフロントエンド コンピュータとして使用できません。

-   リモート SQL ペアのフロントエンドおよびバックエンドのいずれにも、ドメイン コントローラとして構成したサーバーを使用できません。

-   バックエンド コンピュータでは、データベース ソフトウェアに WMSDE または MSDE を使用できません。

-   リモート SQL に関する問題の詳細については、[Microsoft Windows Server Update Services の展開に関するドキュメント](http://technet.microsoft.com/library/cc708532.aspx) (英語) で、リモート SQL について説明している付録 C を参照してください。

#### 問題 13 : レプリカのダウンストリーム サーバーにある承認が、親のアップストリーム サーバーにあるものよりも少ない

レプリカのダウンストリーム サーバーにある承認が、親のアップストリーム サーバーにあるものよりも少ない場合、アップストリーム サーバー上でのコンテンツのダウンロードが完了するまでは、ダウンストリーム サーバーにインストールの承認が送られないことが原因です。

#### 問題 14 : 最初の同期が失敗した後の再同期

同期が失敗した場合、トラブルシューティングとして最初に行うことは、サーバーの同期をもう一度試すことです。2 回目の同期も失敗した場合は、『WSUS Operations Guide』([WSUS 操作ガイド](http://technet.microsoft.com/ja-jp/library/cc720431.aspx)、英語) で、トラブルシューティングに関する情報を参照してください。

#### 問題 15 : WSUS の管理コンソールにアクセスしようとすると、System.IO.FileNotFoundException エラー メッセージが表示される

次のエラー メッセージを受け取ったときは、Network Service または ASP.NET アカウントのアクセス許可を調整することが必要な場合があります。

System.IO.FileNotFoundException : ファイルまたはアセンブリ名 xxxxxx、またはその依存関係の 1 つが見つかりませんでした

xxxx はランダム名です。

Windows Server 2003 オペレーティング システムでこの問題を解決するには、Network Service アカウントに %systemroot%\\Temp への読み取り/書き込みアクセス権を付与します。Windows 2000 Server では、ASP.NET アカウントに %systemroot%\\Temp への読み取り/書き込みアクセス権を付与します。

#### 問題 16 : SQL セキュリティ修正プログラム MS03-031 (KB815495)

この更新プログラムは、クライアント上で実際にはインストールが失敗した場合でも、WSUS サーバーではインストールされたものとして表示されることがあります。これは、パッケージがクライアントに再度提示されることを招く可能性があります。サーバーで更新プログラムを承認しないことで、この問題を回避できます。

#### 問題 17 : RTM アップグレード中に、IIS 設定が失われる

以前のバージョンの WSUS (RC など) がインストールされているサーバーに WSUS RTM をインストールする場合、WSUS RTM によって以前のバージョンがアンインストールされてから、新しいバージョンがインストールされます。これは、IIS で WSUS に関連付けられている vroot とファイルが削除されることを意味します。

既定の Web サイトに WSUS をインストールする場合は、WSUS vroot に対して行ったすべての WSUS 関連の設定が失われます。たとえば、WSUS をセキュリティで保護するために、SSL 用の WSUS vroot を構成した場合、WSUS の RTM バージョンをインストールした後、それらを再構成する必要があります。注 : WSUS コンソールに、SSL が有効になっていないことを知らせる通知が表示されます。

既定の Web サイト以外の Web サイトに WSUS がインストールしていた場合は、WSUS の Web サイト レベルの追加設定はすべて失われます。

#### 問題 18 : ホスト ヘッダーの使用

IIS で既定の Web サイト (WSUS Web サイト) にホスト ヘッダー値を割り当てる場合は、既定の Web サイトへのホスト ヘッダー値を指定せずに、IP アドレスの一覧に "未使用の IP アドレスすべて" または割り当てられた IP アドレスを追加する必要があります。既定ではない Web サイトにも同様に追加してください。

**警告** : これは、Microsoft SharePoint および Exchange の機能を損なうおそれがあります。

#### 問題 19 : WSUS コンソールの URL は、Internet Explorer の強化が有効になっているコンピュータ上で、信頼済みサイトおよびローカル イントラネットの Web コンテンツ ゾーンに追加する必要があります。

コンピュータで Internet Explorer の強化 (Microsoft Windows Server 2003 の Internet Explorer 拡張セキュリティ構成コンポーネントとも呼ばれています) を有効にしている場合、WSUS コンソールを信頼済みサイトおよびローカル イントラネットの Web コンテンツ ゾーンに追加しないと、WSUS コンソールのページを開こうとするたびに、ユーザーの資格情報を入力するよう求められます。

WSUS コンソールを\[イントラネット\] および \[信頼済みサイト\] Web コンテンツ ゾーンに追加するには、次の手順を実行します。

1.  \[インターネット オプション\] を開きます (これを開く手順の一例としては、\[スタート\] ボタン、\[コントロール パネル\]、\[インターネット オプション\] の順にクリックします)。

2.  \[セキュリティ\] タブで、\[イントラネット\]、\[サイト\]、\[詳細設定\] の順にクリックし、URL (http://&lt;WSUS サーバー名&gt;/WSUSAdmin) を追加して、\[OK\] をクリックします。

3.  \[信頼済みサイト\]、\[サイト\] の順にクリックし、WSUS コンソールの URL を追加して、\[OK\] をクリックします。\[インターネット オプション\] を終了するには、\[OK\] をもう一度クリックします。

#### 著作権情報

このドキュメントに記載されている情報は、発行日におけるマイクロソフトの見解を示すものです。マイクロソフトは市場の変化に対応する必要があるため、このドキュメントの内容に関する責任をマイクロソフトは問われないものとします。また、発行日以降に発表される情報の正確性を保証できません

このドキュメントに記載された内容は情報提供のみを目的としており、明示、黙示または法律の規定にかかわらず、これらの情報についてマイクロソフトはいかなる責任も負わないものとします。

お客様ご自身の責任において、適用されるすべての著作権関連法規に従ったご使用を願います。このドキュメントのいかなる部分も、米国 Microsoft Corporation の書面による許諾を受けることなく、その目的を問わず、どのような形態であっても、複製または譲渡することは禁じられています。ここでいう形態とは、複写や記録など、電子的な、または物理的なすべての手段を含みます。ただしこれは、著作権法上のお客様の権利を制限するものではありません。

マイクロソフトは、このドキュメントに記載されている内容に関し、特許、特許申請、商標、著作権、またはその他の無体財産権を有する場合があります。別途マイクロソフトのライセンス契約上に明示の規定のない限り、このドキュメントはこれらの特許、商標、著作権、またはその他の無体財産権に関する権利をお客様に許諾するものではありません。

別途記載されていない場合、このソフトウェアおよび関連するドキュメントで使用している会社、組織、製品、ドメイン名、電子メール アドレス、ロゴ、人物、場所、出来事などの名称は架空のものです。実在する商品名、団体名、個人名などとは一切関係ありません。

![](images/Cc708486.arrow_px_up(ja-jp,WS.10).gif)[ページのトップへ](#ctl00_rs1_eb1_panel1)
