---
TOCTitle: Microsoft Windows Server Update Services の概要
Title: Microsoft Windows Server Update Services の概要
ms:assetid: '2e23c54b-62e3-4d06-aa68-a5960a55169d'
ms:contentKeyID: 18128130
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc720490(v=WS.10)'
---

Microsoft Windows Server Update Services の概要
===============================================

**概要**
公開日: 2005年6月17日

**ダウンロード**

[Microsoft Windows Server Update Services の概要](http://www.microsoft.com/downloads/details.aspx?familyid=2478d594-a29c-483c-9dc1-9740bf3081a5&displaylang=ja)

Microsoft® Windows™ Server Update Services (WSUS) は、情報テクノロジ管理者が Microsoft Windows 2000 Server、Windows Server 2003、Windows XP の各オペレーティング システムに、Microsoft 製品の最新の更新プログラムを展開できるようにするツールです。WSUS を使用することで、Microsoft Update を通じてリリースされる更新プログラムをネットワーク内のコンピュータに配布する処理を全面的に管理できます。

**メモ**   このドキュメントをダウンロードするには、[ここをクリック](http://www.microsoft.com/downloads/details.aspx?familyid=2478d594-a29c-483c-9dc1-9740bf3081a5&displaylang=ja)してください。

### WSUS ソリューション

WSUS では、次のもので構成される管理インフラストラクチャが提供されます。

#### 

##### 

##### 

##### Microsoft Update

WSUS コンポーネントが Microsoft 製品の更新プログラムを取得するために接続する、Microsoft の Web サイトです。

##### Windows Server Update Services サーバー

企業ファイアウォールの内側にある、Windows® 2000 Server Service Pack 4 (SP4) または Windows Server 2003 オペレーティング システムを実行しているコンピュータにインストールされる、サーバー コンポーネントです。WSUS サーバーには、管理者が Web ベースのツールを通じて更新プログラムを管理および配布する際に必要となる機能が用意されています。これらの機能には、企業ネットワーク内のあらゆる Windows コンピュータから Internet Explorer を介してアクセスできます。さらに、WSUS サーバーは、組織内の他の WSUS サーバーの更新元となることも可能です。更新元として動作する WSUS サーバーを、アップストリーム サーバーといいます。WSUS の実装においては、利用可能な更新プログラム情報を入手するには、ネットワーク内の 1 台以上の WSUS サーバーを Microsoft Update に接続する必要があります。管理者は、ネットワーク セキュリティおよび構成に基づいて、その他に Microsoft Update に直接接続するサーバーの台数を決定できます。

##### 自動更新

Windows 2000 SP3、Windows XP、および Windows Server 2003 オペレーティング システムに組み込まれているクライアント コンピュータ コンポーネントです。自動更新を使用すると、サーバーとクライアント コンピュータの両方が、Microsoft Update から、または WSUS を実行しているサーバーから更新プログラムを入手できます。

![](images/Cc720490.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#mainsection)
