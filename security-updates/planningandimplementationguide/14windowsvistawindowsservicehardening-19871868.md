---
TOCTitle: 第 14 回 Windows Vista のセキュリティ機能 ～ Windows Service Hardening ～
Title: 第 14 回 Windows Vista のセキュリティ機能 ～ Windows Service Hardening ～
ms:assetid: 'c1597167-8f2f-4d00-abe9-9c2bec400431'
ms:contentKeyID: 19871868
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362923(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 14 回 Windows Vista のセキュリティ機能 ～ Windows Service Hardening ～

公開日: 2007年2月28日

![](images/Dd362923.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/16d06765-1084-4648-8cf6-773310e71786(v=TechNet.10))は、脆弱性等が悪用された場合に、攻撃の成功の可能性を低減させるための機能 ASLR (Address Space Layout Randomization) について触れました。今回も、前回同様に普段は目に見えない部分に触れます。今回の Windows Service Hardening は、機能と言うよりは設計の変更といえます。

Windows Service Hardening が、なぜ必要なのかを始めに書かなければなりません。過去の大きなセキュリティ インシデント (事故) の多くは、ウイルス／ワームに脆弱性のあるサービスが狙われ、そのサービスが、非常に大きな権限を持っていたことが原因の一つにあります。サービスは、OS やユーザーに成り代わって各種の働きをすることで、まさに「サービス」を提供します。そのために、OS と同等の権限を有する Local System と呼ばれる権限が必要になる場合もあります。しかし、Local System 権限が不正に使用された場合には、基本的に全ての操作が制限なしに行える事になりますので、OS が完全に攻撃者に乗っ取られるなどの被害につながります。

これらの被害を防止するためには、Local System などの大きな権限を持つサービスを最小限にする必要があるのは、[過去](https://technet.microsoft.com/ja-jp/library/8d709472-cfda-4fa0-aa4d-8118d90591fc(v=TechNet.10))にもお伝えしたとおりです。それでも、なお Local System 権限を必要とするサービスは存在します。その大きな権限をもつサービスに対してどの様に「鈴」を付けるかというのが、今回の Windows Service Hardening の趣旨となります。

さて、話は変わりますが、Windows には、セッションという考え方があります。このセッションは、ユーザーのログオン単位に作られる、各ユーザー毎の作業エリアだと思ってください。サービスもこのセッションの中で動いています。サービスは、OS の起動時に必要とされる事もあり セッション \#0 を使用して活動しています。ここまでは、Windows Vista も Windows XP も変りありません。次に、ユーザーがログオンした場合を考えます。Windows XP では、最初にログオンしたユーザーは、 セッション \#0 を使用します。要するに、サービスとセッションを共有しているわけです。しかし、 Windows Vista では、最初のユーザーは、 セッション \#1 となり、サービスとセッションを明確に分離しています。これによって、一般のアプリケーションは、よりサービスに攻撃を加えにくくなりますし、サービスから、ログオン中のユーザーやアプリケーションに影響を与える事を最小限に抑えることができます。

| Windows XP のセッション                                                                   |
|-------------------------------------------------------------------------------------------|
|   ![](images/Dd362923.secpoint0014_01(ja-jp,TechNet.10).gif) |
| Windows Vista のセッション                                                                |
|   ![](images/Dd362923.secpoint0014_02(ja-jp,TechNet.10).gif) |

加えて、Windows Vista では、Windows XP と比較して Local System 権限をもつサービスが見直され、計 12 のサービスが、より低い限定された権限で動作するようになっています。Local System での動作が必要なものについても、ファイルの変更、レジストリの変更、別のサービスに関する設定の変更などを制限されており、サービスを入り口とした OS 全体の乗っ取りがより困難なものになっています。

**関連サイト：**

-   [Windows Vista でのサービスとドライバの Session 0 分離の影響](http://www.microsoft.com/japan/whdc/system/vista/services.mspx)

[![](images/Dd362923.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))

この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 購読無料

![](images/Dd362923.subscribe(ja-jp,TechNet.10).gif)

[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx)では、セキュリティに関する様々な情報を毎月お届けしています。
セキュリティ ニュースレターを[購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。

**バックナンバー**
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
