---
TOCTitle: Microsoft Windows Server Update Services の概要
Title: Microsoft Windows Server Update Services の概要
ms:assetid: '10f776a2-8e7c-491c-832c-7f0c2be39cfe'
ms:contentKeyID: 18111622
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc720446(v=WS.10)'
---

Microsoft Windows Server Update Services の概要
===============================================

Windows Server Update Services (WSUS) を使用すると、Microsoft Update を通じてリリースされる更新プログラムを入手するプロセスを完全に管理し、ネットワーク内のサーバーとクライアント コンピュータにそれらの更新プログラムを配布できます。

### WSUS ソリューション

WSUS ソリューションでは、次のもので構成される管理インフラストラクチャが提供されます。

-   **Microsoft Update**: Microsoft の Web サイトです。WSUS コンポーネントはこの Web サイトに接続して、Microsoft 製品の更新プログラムを取得します。

-   **Windows Server Update Services サーバー**: 企業のファイアウォールの内側にある Microsoft Windows 2000 Server Service Pack 3 (SP3) または Microsoft Windows Server 2003 オペレーティング システムを実行しているコンピュータ上にインストールされるサーバー コンポーネントです。WSUS サーバー ソフトウェアでは、管理者が Web ベースのツールを使用して更新プログラムを管理および配布することができます。このツールには、企業ネットワーク内にあり、Windows オペレーティング システムを実行しているコンピュータであれば、どのコンピュータからでも Internet Explorer を使用してアクセスできます。さらに、WSUS サーバーは、他の WSUS サーバーの更新元となることも可能です。WSUS の実装においては、利用可能な更新プログラムを入手するには、ネットワーク内の 1 つ以上の WSUS サーバーを Microsoft Update に接続する必要があります。管理者は、ネットワーク セキュリティおよび構成に基づいて、その他に Microsoft Update に直接接続するサーバーの台数を決定できます。

-   **自動更新**: Windows 2000 (SP3以降)、Windows XP、および Windows Server 2003 オペレーティング システムに組み込まれているクライアント コンピュータ コンポーネントです。自動更新を使用すると、サーバーとクライアント コンピュータの両方が、Microsoft Update から、または WSUS を実行しているサーバーから更新プログラムを入手できます。

![](images/Cc720446.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)
