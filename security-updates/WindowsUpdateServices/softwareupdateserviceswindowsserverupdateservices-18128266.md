---
TOCTitle: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
Title: Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
ms:assetid: 'c86e95dc-381f-47a2-b761-1fe0f13ad3f4'
ms:contentKeyID: 18128266
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc708553(v=WS.10)'
---

Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド
=================================================================================================

概要
----

公開日: 2005年7月6日
**ダウンロード**

[Software Update Services から Windows Server Update Services への移行のファースト ステップ ガイド](http://www.microsoft.com/downloads/details.aspx?familyid=150e795e-ae32-4d47-a6b8-e01f918aae93&displaylang=ja)

このガイドでは、Microsoft Windows Server 2003 オペレーティング システム (Web Edition とすべての 64 ビット バージョンを除く) または Windows® 2000 Server を実行している Microsoft Software Update Services (SUS) コンピュータに、Microsoft Windows Server Update Services (WSUS) をインストールする手順について説明します。SUS がインストールされていないコンピュータに WSUS をインストールしてから、SUS の承認および更新プログラムを移行する場合、Microsoft Windows Server Update Services の展開に関するホワイト ペーパーを参照してください。

Windows Server Update Services (WSUS) は、Software Update Services (SUS) の後継バージョンです。SUS サーバーを WSUS サーバーにアップグレードすることはできませんが、承認および更新プログラムを SUS から新規の WSUS サーバーに移行することはサポートされています。したがって、同じ更新プログラムを再度ダウンロードする必要はなく、承認済みの更新プログラムを再承認する必要もありません。複数の SUS サーバーを使用して、ネットワーク上で特定の役割を果たしている各コンピュータに更新プログラムを配布する場合、承認を移行する際、SUS の承認を WSUS のコンピュータ グループにマップできます。これにより、複数の SUS サーバーを単一の WSUS サーバーに統合できます。

WSUS を運用環境に導入する方法は単純です。同一のコンピュータに WSUS と SUS をインストールでき、両方が機能します。また、ネットワーク上で SUS 環境と WSUS 環境を同時に実行することも可能です。ただし、SUS サーバーを WSUS サーバーに同期したり、WSUS サーバーを SUS サーバーに同期したりすることはできません。移行後、この 2 つの更新ソリューションは、互いに完全に独立して動作します。このため、クライアント コンピュータの更新には SUS を使用しながら、運用環境で WSUS をテストできます。WSUS のテストが完了し、新しいソリューションが準備できた時点で、SUS の使用を停止できます。

**メモ**   このドキュメントをダウンロードするには、[ここをクリック](http://www.microsoft.com/downloads/details.aspx?familyid=150e795e-ae32-4d47-a6b8-e01f918aae93&displaylang=ja)してください。

![](images/Cc708553.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)
