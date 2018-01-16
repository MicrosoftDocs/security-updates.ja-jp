---
TOCTitle: 第 24 回 Windows Vista のセキュリティ機能 ～ Security Development Lifecycle ～
Title: 第 24 回 Windows Vista のセキュリティ機能 ～ Security Development Lifecycle ～
ms:assetid: '4862fcbb-49df-4a61-932c-1cc671909977'
ms:contentKeyID: 19871878
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362933(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 24 回 Windows Vista のセキュリティ機能 ～ Security Development Lifecycle ～

公開日: 2007年12月26日

![](images/Dd362933.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/c8793631-1493-430d-a2e0-473fd9817c01(v=TechNet.10))は、スパイウェアの脅威に備える方法として Windows Defender について触れました。今回は、Windows Vista のセキュリティ機能と本コラムの総括として、Security Development Lifecycle (SDL) について触れます。

SDL は、Windows Vista のセキュリティ機能ではありません。しかし、セキュリティ機能群と大きな関係があります。SDL は、その名の通り、安全な製品開発のための開発と出荷後もメンテナンスを行うためのマイクロソフトのルールです。通常の開発プロセスでは、開発終了までを規定していますが、SDL は、製品出荷後も規定されている点が通常のプロセスとの違いであり、「ライフサイクル」と呼称するゆえんです。Windows Vista もこのルールに則って企画・設計・開発が行われました。

この SDL では、機能の要件と合わせてセキュリティ要件が検討されます。全ての機能について、外部や他の機能との接続点を詳細に分析し、どの様な脅威があるか、また将来において脆弱性が発見された場合にどの様な事が起こり得るかが検討されています。この作業は、脅威分析 (Threat Modeling) と呼ばれ、発見された脅威には緩和策が検討され、その機能が攻撃を受けた場合にも直接的に被害が発生しないようにしています。この緩和策の一例が今までのセキュリティ機能といえます。もちろん、目に見えない内部のコードにも緩和策は埋め込まれています。

この様な緩和策や、セキュリティ機能も正しく実装されていなければ意味がありません。その事を検証するために、セキュリティに特化したテストが通常の品質テストとは別に行われます。開発中の段階では、プログラム コードに潜む脆弱性を検査するためのツールによるテストや、Fuzzing と呼ばれる手法による数十万回の攻撃試験、人の手・目による攻撃試験、プログラム コードのレビューを行っています。

そうして、開発がある程度すすみ、製品として形となった段階で、最終セキュリティ レビュー (Final Security Review: FSR) が行われます。FSR では、社外のセキュリティの専門家に、プログラム コードや設計書などの情報を開示し、マイクロソフトとは別の視点や手法で完成直前の製品を攻撃してもらいます。それにより、実世界の攻撃に耐えることを確認して、完成・出荷となります。

その後も、セキュリティレ スポンスとして、Windows Vista の脆弱性や Windows Vista を狙った不正な活動を監視しており、それぞれについて対応を行います。その一例が、セキュリティ情報 (セキュリティ更新プログラム)、セキュリティ アドバイザリや安全に使用するためのガイダンスです。

製品の脆弱性が少ない事がセキュリティの 1 つの指標であることは確かですが、脆弱性に関係なく安全を脅かす事象は発生します。本当の意味の「セキュリティで保護された製品」というのは、製品出荷後も提供元がどこまで対応するかを含めた総合力です。今、攻撃の対象が OS からアプリケーションに移っている中で、Windows Vista だけではなく、その上で動くアプリケーションとそのアプリケーションを提供するベンダーや SIer も、「セキュリティで保護された製品」とは何かを考える時期であることは確かだということを、お伝えさせていただき本コラムの最終回といたします。

[![](images/Dd362933.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))

この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 購読無料

![](images/Dd362933.subscribe(ja-jp,TechNet.10).gif)

[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx) では、セキュリティに関する様々な情報を毎月お届けしています。
セキュリティ ニュースレターを [購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。

**バックナンバー**
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
