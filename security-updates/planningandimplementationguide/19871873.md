---
TOCTitle: 第 19 回 Windows Vista のセキュリティ機能 ～ 証明書の検証 ～
Title: 第 19 回 Windows Vista のセキュリティ機能 ～ 証明書の検証 ～
ms:assetid: 'b139a207-7635-49f9-bf1e-675cf503ee79'
ms:contentKeyID: 19871873
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362928(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 19 回 Windows Vista のセキュリティ機能 ～ 証明書の検証 ～

公開日: 2007年7月25日

![](images/Dd362928.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/566ee918-681d-47e0-a23d-f231cb6dae9d(v=TechNet.10))は、フィッシング サイトからユーザーを保護するための、Phishing Filter (フィッシング フィルタ) に触れました。今回も、安全なブラウザの利用ということで、証明書に関する Internet Explorer の改善について触れます。

Windows Vista や Windows XP Service Pack 2 向けに提供している Internet Explorer 7 は、Web サイトの発行元をより確実に検証できるように、「証明書」をより明確に表示するように機能強化しています。

Internet Explorer 6 までは、証明書に関する情報は、メニューからページのプロパティを参照するか、ステータスバーの小さなアイコンで判断するしかありませんでした。また、証明書に何らかの異常がある場合でも、接続時にダイアログボックスによる警告が行われるのみでした。

Internet Explorer 7 では、まず証明書に異常が認められるサイトは、何らかの危険が潜む可能性のあるサイトとして、サイトの表示そのものをブロックします。

![](images/Dd362928.secpoint0019_01(ja-jp,TechNet.10).gif)

**図** **1**

これにより、正しい証明書を提示したように見せかけるサイトによって、被害にあう事を防止します。しかしながら、正式な証明機関より発行されていない、個人発行の証明書を暗号化のためなどに使用しているサイトもあります。その様なサイトに、接続する必要がある場合は、ブロック画面から、「このサイトの閲覧を続行する」を選択する事で、本来のページが表示されますが、お勧めできません。

次に、正常な証明書についても、2 段階に分けて安全性の確認を行っています。1 つは、従来の HTTPS (SSL) 接続と同等の安全性、もう 1 つが EV (Extended Validation) SSL と呼ばれる新しい方式による接続時の安全性です。

従来の証明書は、アドレスバーも白く、鍵マークのみが表示されます。

![](images/Dd362928.secpoint0019_02(ja-jp,TechNet.10).gif)

**図2**

しかし、EV-SSL 方式では、アドレスバーを緑にすることで、従来よりも安全な接続方式であることを利用者に知らせます。

![](images/Dd362928.secpoint0019_03(ja-jp,TechNet.10).gif)

**図3**

この EV-SSL の従来との違いは、証明書を発行するときにより厳しく、証明書を利用する企業・個人を審査している点にあります。これにより、証明書の内容と実際の取得企業との差異が無いことが、発行期間により確認されているため、従来の証明書よりも信頼できるわけです。

[![](images/Dd362928.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))

この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 購読無料

![](images/Dd362928.subscribe(ja-jp,TechNet.10).gif)

[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx)では、セキュリティに関する様々な情報を毎月お届けしています。
セキュリティ ニュースレターを[購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。

**バックナンバー**
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
