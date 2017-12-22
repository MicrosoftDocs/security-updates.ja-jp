---
TOCTitle: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
Title: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
ms:assetid: '3cb757b5-a275-4013-b2fc-98e0d34cefa9'
ms:contentKeyID: 18128135
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc720497(v=WS.10)'
---

Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
=================================================================================================

手順 2: サーバーに MSDE をインストールする (Windows 2000 のみ)
--------------------------------------------------------------

公開日: 2005年7月6日

 

Windows 2000 Server で WSUS を使用していて、Microsoft SQL Server 2000 にアクセスできない場合、WSUS セットアップを実行する前に、Microsoft SQL Server 2000 Desktop Engine (MSDE) をインストールする必要があります。このセクションでは、このタスクの詳しい手順を説明します。

Windows Server 2003 オペレーティング システムにインストールする場合、この手順は必要ありません。「手順3 : SUS サーバーに WSUS をインストールする」に進んでください。

Windows 2000 Server に MSDE をインストールするプロセスは、4 つの手順から成ります。まず、MSDE アーカイブをダウンロードし、WSUS サーバーとして使用するサーバー上のフォルダに展開します。次に、コマンド プロンプトでコマンド ライン オプションを使用して MSDE セットアップを実行し、sa パスワードを設定して、インスタンス名として WSUS を割り当てます。次に、MSDE のインストール完了後、WSUS インスタンスが Windows NT サービスとして実行されているかどうか確認する必要があります。最後に、WSUS サーバーを保護するために、MSDE にセキュリティ更新プログラムを追加する必要があります。

手順 2 では、次のような操作を実行します。

-   MSDE アーカイブをダウンロードして展開する。

-   MSDE をインストールする。

-   MSDE データベース インスタンスが動作していることを確認する。

-   MSDE を更新する。

MSDE アーカイブをダウンロードし、WSUS サーバーとして使用するサーバー上のフォルダに展開する必要があります。SQL Server 2000 Desktop Engine (MSDE 2000) Release A を入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=47366) (http://go.microsoft.com/fwlink/?LinkId=47366) にアクセスしてください。

### MSDE アーカイブを展開するには

1.  MSDE アーカイブ (MSDE2000a.exe) をダブルクリックします。

2.  使用許諾契約を読み、\[同意します\] をクリックします。

3.  \[インストール先のフォルダ\] ボックスにパスを入力して、\[完了\] をクリックします。たとえば「C:\\MSDE2000」と入力します。指定したインストール フォルダに、MSDE アーカイブから MSDE インストール ファイルがコピーされます。

    ![](images/Cc720497.e73a744c-980e-403e-9999-fabd16cbbe65(ja-jp,WS.10).gif)

    **\[インストール フォルダ\] ページ**

次に、MSDE をインストールし、sa パスワードを設定して、インスタンス名を割り当てます。

![](images/Cc720497.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### MSDE をインストールし、sa パスワードを設定して、インスタンス名を割り当てるには

1.  コマンド プロンプトで、前の手順で指定した MSDE インストール フォルダに移動します。

2.  次のように入力します。

    **setup sapwd="***password***" instancename="***WSUS***"**

    password は、MSDE のこのインスタンスに対する sa アカウントの強力なパスワードです。このコマンドにより、MSDE セットアップ プログラムが起動し、sa パスワードが設定され、MSDE のこのインスタンスの名前が WSUS となります。

![](images/Cc720497.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### MSDE の WSUS インスタンスがインストールされたことを確認するには

1.  \[スタート\] ボタン、\[ファイル名を指定して実行\] の順にクリックします。

2.  \[名前\] ボックスに「services.msc」と入力し、\[OK\] をクリックします。

3.  サービスの一覧を下にスクロールし、MSSQL$WSUS という名前のサービスが存在することを確認します。

    ![](images/Cc720497.4e0eb616-431e-459c-85d7-d5411c1c8c1f(ja-jp,WS.10).gif)

    **MSSQL$WSUS**

SQL Server 用の累積的なセキュリティ修正プログラム MS03-031 のセキュリティ関連情報で説明されているセキュリティ更新プログラムを、ダウンロードしてインストールする必要があります。SQL Server 2000 (32 ビット) のセキュリティ修正プログラム MS03-031 を入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=37271) (http://go.microsoft.com/fwlink/?LinkId=37271) にアクセスしてください。

MS03-031 に関する情報については、[Microsoft のヘルプとサポート センター](http://go.microsoft.com/fwlink/?linkid=37270)の Web サイト (http://go.microsoft.com/fwlink/?LinkId=37270) にアクセスしてください。

![](images/Cc720497.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### SQL Server 2000 (32 ビット) のセキュリティ修正プログラム MS03-031 をインストールするには

1.  **SQL Server 2000 (32 ビット) のセキュリティ修正プログラム MS03-031 (SQL2000-KB815495-8.00.0818-JPN.exe)** をダブルクリックします。

2.  \[ようこそ\] ページで、\[次へ\] をクリックします。

3.  使用許諾契約書を読み、\[使用許諾契約書の条項と条件に同意する\]、\[次へ\] の順にクリックします。

4.  \[更新するインスタンス\] ページで、\[インスタンス\] ボックスを使用して WSUS インスタンスを選択し、\[次へ\] をクリックします。

    ![](images/Cc720497.4324bb19-b6a9-4692-94c8-4cda9d4a8f36(ja-jp,WS.10).gif)

    **\[更新するインスタンス\] ページ**

5.  \[認証モード\] ページで \[Windows 認証\] を選択して、\[次へ\] をクリックします。

    ![](images/Cc720497.3fffd3ee-c18d-4745-981c-d926b0d010bb(ja-jp,WS.10).gif)

    **\[認証モード\] ページ**

6.  \[インストールの準備完了\] ページで、\[インストール\] をクリックします。

    ![](images/Cc720497.cce31dec-4439-4f00-9a69-4a59ada3072a(ja-jp,WS.10).gif)
    
    **\[インストールの準備完了\] ページ**

7.  \[修正プログラムの完了\] ページで \[完了\] をクリックします。

![](images/Cc720497.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)
