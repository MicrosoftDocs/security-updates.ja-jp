---
TOCTitle: 第 18 回 Windows Vista のセキュリティ機能 ～ Phishing Filter ～
Title: 第 18 回 Windows Vista のセキュリティ機能 ～ Phishing Filter ～
ms:assetid: '566ee918-681d-47e0-a23d-f231cb6dae9d'
ms:contentKeyID: 19871872
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362927(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 18 回 Windows Vista のセキュリティ機能 ～ Phishing Filter ～

公開日: 2007年6月27日

![](images/Dd362927.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/4f3ea3ed-8b74-4de7-972b-c450efcb957c(v=TechNet.10))は、家族と子供のためのセキュリティ機能である、Family Safety に触れました。今回は、安全なブラウザの利用ということで、フィッシングサイトからユーザーを保護するための、Phishing Filter (フィッシング フィルタ) について触れます。

フィッシング フィルタ は、Windows Vista の機能ではありますが、厳密には、Internet Explorer 7 の機能となります。そのため、Windows XP Service Pack 2 や Windows Server 2003 でも、Internet Explorer 7 のダウンロード版を導入する事で利用可能です。

さて、実際にフィッシング フィルタは、「フィッシング詐欺検出機能」という名称となります。最初に Web サイトにアクセスしたときに、以下の様なダイアログボックスが表示されます。ここで、「自動フィッシング詐欺検出機能を有効にする」を選択する事で、次回の Web サクセスからフィッシング サイトの検査がアクセスごとに行われるようになります。

![](images/Dd362927.secpoint0018_01(ja-jp,TechNet.10).gif)

**図** **1**

もし、有効にしなかった場合も、\[ツール\] - \[インターネット オプション\] - \[詳細設定\] で有効にする事ができます。(もちろん、無効にする事も可能です。)

さて、実際にフィッシング サイトにアクセスしたときの動作ですが、2 種類の警告があります。1 つ目は、「フィッシング サイトだと断定する事はできないが、疑わしいサイトの場合」で、以下の様な黄色のアドレス バーで表示されます。しかし、実際のサイトへのアクセスは可能です。

![](images/Dd362927.secpoint0018_02(ja-jp,TechNet.10).gif)

**図2**

「実際に報告を受けたフィッシング サイトと確定しているサイトにアクセスしようとした場合」は、以下の様な赤いアドレス バーで表示され、サイトへのアクセスが完全にブロックされます。

![](images/Dd362927.secpoint0018_03(ja-jp,TechNet.10).gif)

**図3**

通常は、赤いアドレス バーが表示された場合は、そのままブラウザを閉じる事をお勧めします。もしも、警告が間違っていると確信できる場合は、\[このサイトの閲覧を続行する\] をクリックする事で、本来のサイトが表示されますが、推奨しません。

もし、フィッシング サイトを発見した、または誤って警告されている場合は、マイクロソフトに通知することが可能です。すでに、そのサイトが表示されている場合は、警告画面やダイアログボックスから \[これがフィッシング Web サイトかどうか報告する\] をクリックする事で、以下の様な報告画面に移ります。報告は、日本語でも行う事が可能です。報告されたサイトは、専門担当者が本当にフィッシング サイトかどうか等を確認し、データベースに日々反映させています。

![](images/Dd362927.secpoint0018_04(ja-jp,TechNet.10).gif)

**図4**

フィッシング サイト情報は、この様な報告のほかに、専門機関や司法機関と連携して常に最新の情報が提供されるように管理されています。

もちろん、このフィッシング フィルタが 100% フィッシング サイトを検出できるわけではありませんが、Internet Explorer 7 に移行可能な方は、この機能を有効にする事を強くお勧めします。

[![](images/Dd362927.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))
この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 購読無料

![](images/Dd362927.subscribe(ja-jp,TechNet.10).gif)

[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx)では、セキュリティに関する様々な情報を毎月お届けしています。
セキュリティ ニュースレターを[購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。

**バックナンバー**
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
