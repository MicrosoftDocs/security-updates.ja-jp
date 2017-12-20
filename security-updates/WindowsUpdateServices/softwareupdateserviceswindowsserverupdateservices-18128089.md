---
TOCTitle: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
Title: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
ms:assetid: '457e42ed-f357-44a4-9f7e-7e61f6c3ea94'
ms:contentKeyID: 18128089
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc720527(v=WS.10)'
---

Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
=================================================================================================

### 手順 5: SUS から WSUS にコンテンツと承認を移行する

公開日: 2005年7月6日

WSUS の構成と同期が完了したので、次に、使用している環境の SUS サーバーのコンテンツと承認を WSUS サーバーに移行できます。まず、ローカル SUS サーバーのコンテンツと承認を移行します。他に SUS コンピュータが存在する場合、各SUSサーバーでリモート移行作業の準備を行った後、リモートのすべてのコンテンツと承認を移行し、これらの承認を WSUS ターゲット グループにマップできます。これはオプションの手順です。

手順 5 では、次のような操作を実行します。

-   ローカルのコンテンツと承認を移行する。

-   リモートSUSサーバーの 承認をマップするための WSUS ターゲット グループを作成する (オプション)。

-   WSUS への移行用に、リモートSUSサーバー 上の コンテンツを共有する (オプション)。

-   リモートSUSサーバーのコンテンツと承認を移行し、WSUSサーバー上で承認を WSUS ターゲット グループにマップする (オプション)。

ローカル SUS のコンテンツと承認を移行するには、WSUSutil.exe を使用します。既定では、WSUSutil.exe は次の場所にあります。

&lt;WSUS インストール ドライブ&gt;:\\Program Files\\Update Services\\Tools

SUS の承認またはコンテンツをインポートするには、WSUS サーバー上のローカル Administrators グループのメンバである必要があります。これらの操作は、WSUS サーバー自身からのみ実行できます。また、WSUSutil.exe は、32 ビット プラットフォームでのみ実行できます。

更新プログラムや承認を移動するとき、SUS が実行されている必要はありません。ただし、コンテンツまたは承認を移行する前に、SUS が同期中でないことを必ず確認してください。WSUSutil.exe では、承認と更新プログラムの両方を移動できますが、このどちらか一方、または両方を移行することは必須ではありません。

### ローカルのコンテンツと承認を SUS から移行し、WSUS の All Computers ターゲット グループに承認をマップするには

1.  コマンド プロンプトで、WSUSutil.exe が含まれているディレクトリに移動します。

2.  次のように入力します。

    **wsusutil.exe migratesus /content** &lt;ローカル SUS コンテンツのパス&gt; **/approvals** &lt;SUS サーバー名&gt; **/log** &lt;ファイル名&gt;

    たとえば、次のように入力します。

    **wsusutil.exe migratesus /content c:\\sus\\content\\cabs /approvals sus1 /log local\_migration.log**

リモートの承認を WSUS コンピュータ グループにマップする処理は、オプションです。この処理は、単一の場所に複数の SUS サーバーがあり、これらを 1 つの WSUS サーバーに統合する場合に便利です。リモートの SUS の承認を WSUS コンピュータ グループにマップするには、まず、WSUS 上にこのグループを作成します。

![](images/Cc720527.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### コンピュータ グループを作成するには

1.  WSUS コンソールのツール バーで、\[コンピュータ\] をクリックします。

2.  \[タスク\] で、\[コンピュータ グループの作成\] をクリックします。

3.  \[グループ名\] ボックスに新しいコンピュータ グループの名前を入力し、\[OK\] をクリックします。

WSUS ターゲット グループの作成が完了したら、WSUSutil.exe を使用して、リモートの承認とコンテンツを移行できます。このコマンド ライン ユーティリティは、HTTP を使用してリモートの SUS インストールから承認を取得し、SMB を使用して更新プログラムをコピーします。リモート コンピュータから更新プログラムをコピーするため、このツールには、リモートの SUS Content フォルダおよびそのすべてのサブフォルダに対する共有の読み取りアクセス許可が必要です。

![](images/Cc720527.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### WSUS への移行用に SUS のリモート コンテンツを共有するには

1.  リモート SUS コンピュータ上で、ファイル システム内の SUS コンテンツの場所に移動します。既定では、SUS のコンテンツは、C:\\SUS\\Content\\ に格納されています。

2.  Content フォルダを右クリックし、\[共有とセキュリティ\] をクリックするか、または Windows 2000 を実行しているコンピュータの場合、\[共有\] をクリックします。

3.  Content フォルダの \[プロパティ\] ダイアログ ボックスで、\[このフォルダを共有する\] をクリックします。

4.  \[セキュリティ\] タブをクリックし、Everyone グループが Content フォルダに対する NTFS 読み取りアクセス許可を持っていることを確認します。

5.  \[OK\] をクリックします。

6.  移行するすべての SUS サーバーに対してこの手順を繰り返します。

![](images/Cc720527.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### リモートのコンテンツと承認を SUS から移行し、WSUS のカスタム コンピュータ グループに承認をマップするには

1.  コマンド プロンプトで、WSUSutil.exe が含まれているフォルダに移動します。

2.  次のように入力します。

    **wsusutil.exe migratesus /content** &lt;リモート SUS コンテンツの場所&gt; **/approvals** &lt;SUS サーバー名&gt;  **"**&lt;WSUS ターゲット グループ名&gt;**" /log** &lt;ファイル名&gt;

    たとえば、次のように入力します。

    **wsusutil.exe migratesus /content \\\\sus1\\content\\cabs /approvals sus1 "all desktops" /log remote\_migration.log**

![](images/Cc720527.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)
