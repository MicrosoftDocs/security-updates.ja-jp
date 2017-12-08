---
TOCTitle: 第 15 回 Windows Vista のセキュリティ機能 ～ User Access Control ～
Title: 第 15 回 Windows Vista のセキュリティ機能 ～ User Access Control ～
ms:assetid: '0aabb805-c58e-42ae-9d8e-13c688a88fe7'
ms:contentKeyID: 19871869
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362924(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 15 回 Windows Vista のセキュリティ機能 ～ User Access Control ～

公開日: 2007年3月28日

![](images/Dd362924.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/c1597167-8f2f-4d00-abe9-9c2bec400431(v=TechNet.10))は、サービスが不正に使用された場合の安全性について触れました。今回は、前回の Windows Service Hardening に若干関連のある、User Access Control (UAC) について触れます。

UAC は、誤解を恐れずに簡単に言ってしまうと、管理者に対しても管理者権限を使えないように制限する機能です。とはいえ、実際問題として制限されたままでは、その PC を誰も管理できないことになりますので、条件がそろえば制限の解除 (権限使用の許可) をしなければなりません。

そのための仕組みとして、図 1 のダイアログ ボックスがあります。このダイアログ ボックスが、ログオンしているユーザーが管理者権限の必要な操作をしようとした場合に、表示され、ユーザーに管理者権限の使用がユーザーの意図したものであるかを確認します。

![](images/Dd362924.secpoint0015_01(ja-jp,TechNet.10).gif)

**図 1**

このダイアログ ボックスは、管理者ユーザーの場合の表示で、その他のユーザーの場合は、さらに管理者権限のあるアカウントのユーザー名とパスワードを求められます。この機能により、意図せずに実行してしまった不正なソフトウェアが、重要なレジストリ値を変更しようとした場合に、UAC により一旦、操作を保留しユーザーの明確な確認を取ることで、PC の「裏側」でひっそりとシステムが乗っ取られる様な事が困難になるわけです。

また、副次的な効果として、アプリケーション開発者が不用意に高い権限を使用するアプリケーションを開発しなくなる可能性があります。もちろん、UAC があっても、従来どおりのアプリケーションは、開発できますが、管理者権限が使用されるごとに UAC が操作を保留するため、ユーザーの使用感は決して良いものにならないでしょう。開発者は、それを避けるために、必然的に不要な管理者権限の使用を避けることになります。このことは、利用者にとっても“管理者権限で日常業務を行う”理由を減らし、より安全な一般ユーザーでの日常利用へ移行できる環境を作っていくことになります。

ちなみに、Windows Service Hardening と何の関係があるかと言うと、UAC が出す権限使用確認のダイアログ ボックスですが、UAC のためのサービスが表示しています。そのため、このダイアログ ボックスが表示されるときには、ダイアログ ボックスのバックが黒くなり、一般のダイアログ ボックスと明確に区別されています。

UAC の出すダイアログ ボックスが、煩わしいという理由で、UAC をオフにする方法を積極的に伝えているメディア等もありますが、よほどの理由が無い限り、この機能をオフにするべきものではないと言うことで、今回は〆させていただきます。

[![](images/Dd362924.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))

この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 購読無料

![](images/Dd362924.subscribe(ja-jp,TechNet.10).gif)

[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx)では、セキュリティに関する様々な情報を毎月お届けしています。
セキュリティ ニュースレターを[購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。

**バックナンバー**
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
