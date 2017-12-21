---
TOCTitle: SQL Server と Exchange Server の更新の承認
Title: SQL Server と Exchange Server の更新の承認
ms:assetid: '3397f695-67be-4839-972d-c54665073c6f'
ms:contentKeyID: 18111631
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc720484(v=WS.10)'
---

SQL Server と Exchange Server の更新の承認
==========================================

### Microsoft SQL Server のインスタンスの更新

1 台のコンピュータに Microsoft SQL Server をインストールする場合、次の SQL Server のシナリオのいずれも使用可能であるため、インストール (インスタンス) が複雑になります。

-   SQL サーバーの複数のインスタンスをコンピュータに同時に インストールする

-   複数のバージョン (リリース) の SQL をインストールする

-   同じコンピュータに複数言語の SQL Server インスタンスをインストールする

-   通常、これらの複数のインスタンスを更新するために追加の操作は必要ありません。製品、更新プログラムのクラス、言語オプションなどの同期オプションを指定するときに、コンピュータに保存されている SQL Server インスタンスのバージョンに対する要件を考慮しているか確認する必要があるだけです。同期オプションの構成の詳細については、「[同期のセットアップと実行](http://www.microsoft.com/japan/technet/prodtechnol/windowsserver2003/library/wsus/wsusoperationsguidetc/a5a006b4-24f6-49d9-bf9b-ceb05934c7ec.mspx)」を参照してください。

![](images/Cc720484.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### クラスタの一部である Microsoft SQL Server と Microsoft Exchange Server の更新

Microsoft SQL Server と Microsoft Exchange Server はいずれも "クラスタ環境" にインストールできます。これらのプログラムを実行しているクラスタのサーバーで利用可能な更新プログラムがある場合、クラスタの各サーバーを個々に更新する必要があります。更新プログラムは、クラスタ構成のシーケンスでインストールすることをお勧めします。たとえば、最初にアクティブ クラスタ ノードを更新してからフェールオーバーを開始し、次のパッシブ クラスタ ノードをアクティブにしてこれを更新するという作業を、すべてのクラスタ ノードが更新されるまで実行します。

> [!NOTE]

> 1 台のサーバー上に、スタンドアロン インスタンスとクラスタ インスタンスの両方の SQL Server をインストールすることができます。この場合、アクティブ クラスタ ノードを更新すると、製品、更新プログラムのクラス、言語などの同期オプションを正しく指定している場合は、同じサーバー上のスタンドアロン インスタンスの SQL Server も更新されます。同期オプションの設定の詳細については、「[同期のセットアップと実行](http://www.microsoft.com/japan/technet/prodtechnol/windowsserver2003/library/wsus/wsusoperationsguidetc/a5a006b4-24f6-49d9-bf9b-ceb05934c7ec.mspx)」を参照してください。

![](images/Cc720484.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)
