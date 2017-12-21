---
TOCTitle: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
Title: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
ms:assetid: '0c2b4ea2-89f0-4aa1-8e7a-e2fd4fce0c4f'
ms:contentKeyID: 18128082
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc720449(v=WS.10)'
---

Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
=================================================================================================

手順 3: SUS サーバーに WSUS をインストールする
----------------------------------------------

公開日: 2005年7月6日

インストール要件を確認し、オプションとして MSDE をインストールした後は、WSUS をインストールできます。以下の手順では、SUS がインストールされた Windows 2000 Server に対する既定の WSUS インストール オプションを使用しています。この場合、データベース ソフトウェアを指定し、更新プログラムをローカルに格納して、ポート 8530 のカスタム Web サイトを使用する必要があります。Windows Server 2003 を使用する場合は、データベース ソフトウェアを指定する必要はありません。ここで示す画像は、Windows Server 2003 の画面とは多少異なる場合がありますが、各手順はほとんど同じです。手順の相違点はすべて、このガイド内で注記しています。

ローカル Administrators グループのメンバであるアカウントを使用して、WSUS をインストールするサーバーにログオンする必要があります。ローカル Administrators グループのメンバのみが、WSUS をインストールできます。

SUS インストール済みの Windows 2000 Server に WSUS をインストールするには
-------------------------------------------------------------------------

1.  インストーラ ファイル **WSUSSetup.exe** をダブルクリックします。

    > [!NOTE]

>     WSUSSetup.exe の最新バージョンは、Windows Server Update Services に関する [Microsoft の Web サイト](http://go.microsoft.com/fwlink/?linkid=47374) (http://go.microsoft.com/fwlink/?LinkId=47374)で入手できます。

2.  ウィザードの開始ページで、\[次へ\] をクリックします。

3.  使用許諾契約書の内容をよく確認し、\[使用許諾契約書に同意します\]、\[次へ\] の順にクリックします。

4.  \[更新元の選択\] ページで、クライアントが更新プログラムを取得する場所を指定できます。\[更新プログラムをローカルに保存する\] チェック ボックスをオンにすると、更新プログラムは WSUS サーバー上に保存されるので、更新プログラムを保存するファイル システム内の場所を選択します。更新プログラムをローカルに保存しない場合は、クライアント コンピュータが Microsoft Update に接続して、承認された更新プログラムを取得します。

    既定のオプションのままで、\[次へ\] をクリックします。

    ![](images/Cc720449.sus2_install_3ss(ja-jp,WS.10).gif)

    **\[更新元の選択\] ページ**
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc720449.sus2_install_3s(ja-jp,ws.10).gif)

5.  \[データベースのオプション\] ページで、使用するオペレーティング システムに応じて、以下のいずれかを行います。

    -   Windows Server 2003 の場合、\[次のコンピュータに SQL Server desktop engine (Windows) をインストールする\] をクリックします。

    -   Windows 2000 Server の場合、\[次のコンピュータにある既存のデータベース サーバーを使用する\] をクリックし、\[SQL インスタンス名\] ボックスからインスタンス名を選択して、\[次へ\] をクリックします。

    ![](images/Cc720449.b25efed5-5654-485f-b34d-14686bed0240s(ja-jp,WS.10).gif)

    **\[データベースのオプション\] ページ**
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc720449.b25efed5-5654-485f-b34d-14686bed0240(ja-jp,ws.10).gif)

6.  \[Web サイトの選択\] ページで、\[Microsoft Windows Server Update Services の Web サイトを作成する\] をクリックします。

    また、このページには、この選択に基づいて、2 つの重要な URL が一覧表示されます。一つは、更新プログラムを取得するために WSUS クライアント コンピュータを関連付ける URL で、もう一つは、WSUS を構成する WSUS コンソールの URL です。

7.  \[更新プログラムのミラー化の設定\] ページで、この WSUS サーバーに対する管理役割を指定できます。これが初めてネットワークで構成した WSUS サーバーである場合、または分散管理トポロジを使用する場合、この画面をスキップしてください。

    集中管理トポロジを使用し、これが初めてネットワークで構成した WSUS サーバーでない場合、チェック ボックスをオンにし、\[サーバー名\] ボックスに追加の WSUS サーバー名を入力します。管理役割の詳細については、Microsoft Windows Server Update Services の展開に関するドキュメント を参照してください。

    既定のオプションのままで、\[次へ\] をクリックします。

    ![](images/Cc720449.f26e09d5-983c-418d-8511-8960850403efs(ja-jp,WS.10).gif)

    **\[更新プログラムのミラー化の設定\] ページ**
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc720449.f26e09d5-983c-418d-8511-8960850403ef(ja-jp,ws.10).gif)

8.  \[Microsoft Windows Server Update Services をインストールする準備ができました\] ページで、選択内容を確認して \[次へ\] をクリックします。

    ![](images/Cc720449.sus2_install_6ss(ja-jp,WS.10).gif)

    **\[Microsoft Windows Server Update Services をインストールする準備ができました\] ページ**
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc720449.sus2_install_6s(ja-jp,ws.10).gif)

9.  ウィザードの最後のページで、WSUS のインストールが正常に完了したことを確認し、\[完了\] をクリックします。

![](images/Cc720449.arrow_px_up(ja-jp,WS.10).gif)[ページのトップへ](#ctl00_rs1_eb1_panel1)
