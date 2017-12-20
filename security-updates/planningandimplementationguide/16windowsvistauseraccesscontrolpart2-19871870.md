---
TOCTitle: 第 16 回 Windows Vista のセキュリティ機能 ～ User Access Control Part 2 ～
Title: 第 16 回 Windows Vista のセキュリティ機能 ～ User Access Control Part 2 ～
ms:assetid: '0c535b42-0481-47ce-9a9a-21b9ff246da6'
ms:contentKeyID: 19871870
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362925(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 16 回 Windows Vista のセキュリティ機能 ～ User Access Control Part 2 ～

公開日: 2007年4月25日

![](images/Dd362925.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/c1597167-8f2f-4d00-abe9-9c2bec400431(v=TechNet.10))は、管理者権限などの使用を制限するユーザー アクセス制御 (UAC: User Access Control) について触れ、UACをオフにすることを推奨しない事を書きました。今回は、オフにしたいような状況への対処方法について触れます。

UAC は、セキュリティと利便性を語る上での実例なのかもしれません。今まで管理者権限を無制限に使えたところに、管理者権限を制限したわけですから不便を感じる場合もあるでしょう。これが、いわゆるアプリケーションの互換性につながってきます。不便を感じるだけであれば、まだしも権限が完全に不足して動作しないアプリケーションがある可能性があります。その様なアプリケーションは、日常的に管理者権限を必要とするような処理をしてしまっているのだと思われます。例えば、ユーザーデータを、Program files以下に格納するとか、Local Machine レジストリを書きかえるとか・・・

この様な、アプリケーションでも使えなければ困ります。セキュリティを考えても全く利用できないのは、過剰なトレードオフが発生しているとしかいえません。その様な場合に、全体としてのセキュリティレベルを落とすことなく、そのアプリケーションに付いてのみセキュリティを弱める等の措置ができれば、利便性とのバランスを確保できるわけです。

そのためのツールが、[Application Compatibility Tool Kit (ACT)](https://technet.microsoft.com/ja-jp/library/c2b4d368-fc7f-447e-9b3a-908976fb9000(v=TechNet.10)) になります。このツール自体は、Vistaよりも前から提供されており、Vista にも対応した最新版が、ACT 5.0 となります。OS のバージョンアップにより既存のアプリケーションの動作が期待通りではないときに、このツールで原因の分析と対策が行なえます。対策の方法は、アプリケーションに影響を与えている特定の機能をそのアプリケーションに対してのみ、以前のバージョンと類似した動作への変更、機能自体のオフが可能です。ACT をインストールし、\[Microsoft Application Compatibility Toolkit 5.0\] - \[Compatibility Administrator\] を使って、Compatibility Fix として、UAC の動作で管理権限が常に要求される RunAsAdmin を指定する事で、権限不足で動作しないケースを回避できます。

![](images/Dd362925.secpoint0016_01(ja-jp,TechNet.10).gif)

**図** **1**

ためしに、メモ帳 (notepad) に対して、RunAsAdmin の Fix を適用してみると画面 2 の様に、メモ帳の起動ごとに、UAC を通じて管理者権限が与えられます。

![](images/Dd362925.secpoint0016_02(ja-jp,TechNet.10).gif)

**図** **2**

しかし、安易にこの Fix をアプリケーションに適用すると折角 UAC により権限を抑えて実行している意味がなくなってしまいますので、他に方法が無い場合の最後の手段とて使うようにしたいですね。他の Fix で対応できる場合もありますので、Standard User Analyzer を使って分析してみる事からはじめてみるのも面白いかもしれません。

[![](images/Dd362925.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))

この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 購読無料

![](images/Dd362925.subscribe(ja-jp,TechNet.10).gif)

[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx)では、セキュリティに関する様々な情報を毎月お届けしています。
セキュリティ ニュースレターを[購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。

**バックナンバー**
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
