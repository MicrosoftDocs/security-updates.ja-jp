---
TOCTitle: 'マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 D ‐ 信頼されていないネットワーク内にあるサーバーでの NetBIOS の無効化'
Title: 'マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 D ‐ 信頼されていないネットワーク内にあるサーバーでの NetBIOS の無効化'
ms:assetid: 'cac85879-5a6d-419c-bb04-09f0a93fb668'
ms:contentKeyID: 19869234
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc751226(v=TechNet.10)'
---

マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 D ‐ 信頼されていないネットワーク内にあるサーバーでの NetBIOS の無効化
========================================================================================================================================

### 付録 D ‐ 信頼されていないネットワーク内にあるサーバーでの NetBIOS の無効化

ここでは、特に、一般からアクセス可能な Web サーバーや企業のメール ゲートウェイなど、信頼されていないネットワークに配置されているサーバーに関する推奨事項について説明します。本文で取り上げた Contoso のシナリオでは、どのサーバーも境界領域のネットワークには配置されていないので、ここで推奨されている手順はどのサーバーに対しても実行されていません。信頼されていないネットワークにサーバーを配置している場合は、以下の変更を検討してください。ただし、十分なテストを行って、NetBIOS (Network Basic Input/Output System) を無効にすることによるシステム管理の問題を理解しておく必要があります。

**脆弱性**

境界領域のネットワーク内にあるサーバーでは、NetBIOS およびサーバー メッセージ ブロック (SMB: Server Message Block) を含む、不要なプロトコルがすべて無効になっている必要があります。Web サーバーやドメイン ネーム システム (DNS: Domain Name System) サーバーでは、NetBIOS や SMB が動作している必要はありません。この 2 つのプロトコルは、ユーザー情報が収集される脅威に対応するために無効にする必要があります。ユーザー情報の収集は、攻撃者がさらなる攻撃を考えるためにシステム固有の情報を取得しようとするときに行う手段の 1 つです。

SMB プロトコルは、"null" セッションを使用する認証されていないユーザーに対しても、コンピュータに関するさまざまな情報を返します。取得できる情報には、ドメインや信頼の詳細、共有、ユーザー情報 (グループやユーザーの権利を含む)、レジストリ キーなどがあります。

**注** : null セッションをブロックするには、第 6 章「Base Windows 2000 Server のハードニング」 の 「MSBP セキュリティ オプション」で説明されている **RestrictAnonymous** レジストリ キーを設定します。

**対策**

NetBIOS を無効にするだけでは、SMB 通信を防止するのに十分ではありません。標準の NetBIOS ポートがない場合、SMB は TCP (Transmission Control Protocol) ポート 445 を使用するからです。これを SMB ダイレクト ホストといいます。この結果、NetBIOS と SMB の両方を個別に無効にする明示的な手順を実行する必要があります。

NetBIOS が使用するポートは次のとおりです。

-   UDP/137 (NetBIOS ネーム サービス)

-   UDP/138 (NetBIOS データグラム サービス)

-   TCP/139 (NetBIOS セッション サービス)


SMB が使用するポートは次のとおりです。

-   TCP/139

-   TCP/445

インターネットからアクセス可能なサーバーでは、**\[ローカル エリア接続のプロパティ\]** ダイアログ ボックスから **\[TCP/IP のプロパティ\]** ダイアログ ボックスを開き、**\[Microsoft ネットワーク用ファイルとプリンタ共有\]** と **\[Microsoft ネットワーク用クライアント\]** を削除して SMB を無効にする必要があります。

**SMB を無効にするには**

1.  **\[スタート\]**ボタンをクリックし、**\[設定\]** をポイントします。次に、**\[ネットワークとダイヤルアップ接続\]**をクリックします。

2.  インターネットへの接続を右クリックし、**\[プロパティ\]** をクリックします。

3.  **\[Microsoft ネットワーク用クライアント\]** をクリックし、**\[削除\]** をクリックします。

4.  アンインストールの手順に従います。

5.  **\[Microsoft ネットワーク用ファイルとプリンタ共有\]** をクリックし、**\[削除\]** をクリックします。

6.  アンインストールの手順に従います。

**NetBIOS over TCP/IP を無効にするには**

1.  デスクトップの **\[マイ コンピュータ\]** を右クリックし、**\[管理\]** をクリックします。

2.  **\[システム** ツール\] を展開し**、\[デバイス マネージャ\]** をクリックします。

3.  **\[デバイス マネージャ\]** を右クリックし、**\[表示\]** をポイントします。次に、**\[非表示のデバイスの表示\]**をクリックします。

4.  **\[プラグ アンド プレイではないドライバ\]** を展開します。

5.  **\[NetBios over Tcpip\]** を右クリックし、**\[無効\]** をクリックします。

これによって、TCP/445 および UDP 445 上での SMB ダイレクト ホスト リスナが無効になります。

**注** : この手順で nbt.sys ドライバが無効になります。**\[TCP/IP 詳細設定\]** ダイアログ ボックスの **\[WINS\] タブには、\[NetBIOS over TCP/IP を無効にする\]** オプションがあります。このオプションを選択しても、TCP ポート 139 上でリッスンする NetBIOS セッション サービスが無効になるだけです。SMB が完全に無効になるわけではありません。SMB を完全に無効にするには、上の手順に従ってください。

**潜在的な影響**

どのシステムも SMB を使ってこのサーバーに接続することはできなくなります。このサーバーはネットワーク上で共有されているフォルダにアクセスできなくなります。また、多くの管理ツールはこのサーバーに接続できなくなります。

[](#mainsection)[ページのトップへ](#mainsection)

### 目次

-   [概要](https://technet.microsoft.com/ja-jp/library/71a89c24-0bfe-4e21-aeac-89ba6f84b06d(v=TechNet.10))

-   [第 1 章 ‐ Securing Windows 2000 Server 入門](https://technet.microsoft.com/ja-jp/library/18bbfc43-3d1a-4031-bc06-372064ffff72(v=TechNet.10))

-   [第 2 章 ‐ セキュリティの概要を定義する](https://technet.microsoft.com/ja-jp/library/52d2d069-16f8-4a1f-8fa8-ec6b77571799(v=TechNet.10))

-   [第 3 章 ‐ セキュリティ リスク管理の統制について理解する](https://technet.microsoft.com/ja-jp/library/81560275-04b7-4e40-8937-699e4b4defea(v=TechNet.10))

-   [第 4 章 ‐ セキュリティ リスク管理の統制を適用する](https://technet.microsoft.com/ja-jp/library/07ed8438-6264-4e30-9ca9-2235687e62e7(v=TechNet.10))

-   [第 5 章 ‐ ドメイン インフラストラクチャをセキュリティで保護する](https://technet.microsoft.com/ja-jp/library/83d7ede4-67ea-43d7-93a9-ccff8e5ca4e6(v=TechNet.10))

-   [第 6 章 ‐ Base Windows 2000 Server のハードニング](https://technet.microsoft.com/ja-jp/library/265d2c3d-5af6-4f6e-85ea-d674d4c314a7(v=TechNet.10))

-   [第 7 章 ‐ 特定サーバーの役割のハードニング](https://technet.microsoft.com/ja-jp/library/138bac60-132a-4faf-b979-503828583374(v=TechNet.10))

-   [第 8 章 ‐ 修正プログラムの管理](https://technet.microsoft.com/ja-jp/library/c474ed12-f438-4d49-acaa-260df90e5e13(v=TechNet.10))

-   [第 9 章 ‐ 監査と侵入検出](https://technet.microsoft.com/ja-jp/library/f8a8ab2f-f727-459c-aee0-c6a06f7f9fb0(v=TechNet.10))

-   [第 10 章 ‐ インシデントへの対応](https://technet.microsoft.com/ja-jp/library/4baf189b-f762-4c67-a5bc-f438a1274fec(v=TechNet.10))

-   [第 11 章 ‐ 結論](https://technet.microsoft.com/ja-jp/library/0deb6d1a-1083-4353-b645-6bdc1cbab83c(v=TechNet.10))

-   [付録 A ‐ Windows 2000 のサービスの用途](https://technet.microsoft.com/ja-jp/library/13468c13-a3f3-4b75-aadf-fec1c40fe801(v=TechNet.10))

-   [付録 B ‐ レジストリのアクセス制御の変更](https://technet.microsoft.com/ja-jp/library/132e1a99-29b0-4f66-956c-d009da62a51d(v=TechNet.10))

-   [付録 C ‐ オプションのファイル システムのアクセス許可](https://technet.microsoft.com/ja-jp/library/af304b67-3190-4a66-b75a-07d8fcd8585d(v=TechNet.10))

-   付録 D ‐ 信頼されていないネットワーク内にあるサーバーでの NetBIOS の無効化

-   [付録 E ‐ セキュリティで保護された LDAP および SMTP 複製を行うためのドメイン コントローラでのデジタル証明書の構成](http://www.microsoft.com/japan/technet/security/prodtech/windows2000/secwin2k/a0701.mspx)


[](#mainsection)[ページのトップへ](#mainsection)
