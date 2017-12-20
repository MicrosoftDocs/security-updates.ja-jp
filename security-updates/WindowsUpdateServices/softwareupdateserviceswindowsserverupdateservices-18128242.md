---
TOCTitle: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
Title: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
ms:assetid: 'b7551dd1-0e02-4cf8-9095-1596b354c913'
ms:contentKeyID: 18128242
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc708537(v=WS.10)'
---

Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
=================================================================================================

**手順 1: Software Update Services から移行するための WSUS インストール要件を確認する**

公開日: 2005年7月6日

以下に、既定のオプションを使用する WSUS インストールにおいて基準となるインストール要件を示します。その他のインストールに対するハードウェアおよびソフトウェア要件については、Microsoft Windows Server Update Services の展開に関するドキュメントを参照してください。

最大 500 台のクライアント コンピュータを処理するサーバーのハードウェア推奨事項は、次のとおりです。

-   1 GHz プロセッサ

-   1 GB RAM

### ソフトウェア要件

以下に、WSUS をサポートする各オペレーティング システムに必要なソフトウェアの一覧を示します。WSUS セットアップを実行する前に、WSUS サーバーに使用するコンピュータが、この一覧の要件を満たしていることを確認してください。インストール完了時に、これらの更新プログラムのいずれかでコンピュータの再起動が必要となる場合、サーバーを再起動してから WSUS をインストールしてください。

#### Windows Server 2003

Windows Server 2003 上で WSUS を実行する場合、以下のソフトウェアが必要です。

-   Microsoft インターネット インフォメーション サービス (IIS) 6.0。

-   バックグラウンド インテリジェント転送サービス (BITS) 2.0。これを入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=47251) (http://go.microsoft.com/fwlink/?LinkId=47251) にアクセスしてください。

-   Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003。これを入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=47358) (http://go.microsoft.com/fwlink/?LinkId=47358) にアクセスしてください。

    または、[Windows Update](http://go.microsoft.com/fwlink/?linkid=47370) (http://go.microsoft.com/fwlink/?linkid=47370) で重要な更新プログラムや Service Pack を検索して、Microsoft .NET Framework 1.1 Service Pack 1 for Windows Server 2003 をインストールします。

#### Windows 2000 Server

Windows 2000 Server 上で WSUS を実行する場合、以下のソフトウェアが必要です。

-   Microsoft インターネット インフォメーション サービス (IIS) 5.0。IIS のインストール方法については、Microsoft Windows Server Update Services の展開に関するドキュメント、または Windows 2000 Server のヘルプとサポート センターを参照してください。

-   バックグラウンド インテリジェント転送サービス (BITS) 2.0。これを入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=46794) (http://go.microsoft.com/fwlink/?LinkId=46794) にアクセスしてください。

-   Microsoft SQL と完全に互換性のあるデータベース ソフトウェア。Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Release A を入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=47366) (http://go.microsoft.com/fwlink/?LinkId=47366) を参照してください。

-   Microsoft Internet Explorer 6.0 Service Pack 1。これを入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=47359) (http://go.microsoft.com/fwlink/?LinkId=47359) にアクセスしてください。

-   Microsoft .NET Framework Version 1.1 再頒布可能パッケージ。これを入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=47369) (http://go.microsoft.com/fwlink/?LinkId=47369) にアクセスしてください。

-   Microsoft .NET Framework 1.1 Service Pack 1。これを入手するには、[ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=47379) (http://go.microsoft.com/fwlink/?LinkId=47379) にアクセスしてください。

    または、[Windows Update](http://go.microsoft.com/fwlink/?linkid=47370) (http://go.microsoft.com/fwlink/?linkid=47370) で重要な更新プログラムや Service Pack を検索して、Microsoft .NET Framework 1.1 Service Pack 1 for Windows 2000 Server をインストールします。

![](images/Cc708537.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### ディスク要件と推奨事項

WSUS をインストールするには、サーバーのファイル システムが次の要件を満たしている必要があります。

-   システム パーティションと WSUS をインストールするパーティションは両方とも、NTFS ファイル システムでフォーマットされている必要があります。

-   システム パーティションには、1 GB 以上の空き領域が必要です。

-   WSUS がコンテンツを格納するボリュームには、6 GB 以上の空き領域が必要です。推奨は 30 GB です。

-   WSUS セットアップが Windows SQL Server 2000 Desktop Engine (WMSDE) をインストールするボリュームには、2 GB 以上の空き領域が必要です。

![](images/Cc708537.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)
