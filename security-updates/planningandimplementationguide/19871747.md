---
ms:assetid: '6f2181fc-63dc-47ba-bef8-274dcf46e2f5'
ms:contentKeyID: 19871747
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362801(v=TechNet.10)'
---

"Code Red" IIS ワームに関する情報
=================================

最終更新日: 2001年7月27日

パッチが適用されていないインターネット上の IIS を悪用し、コンピュータ ワームとして働く悪意のあるコードが見つかっています。"Code Red" と名付けられたこのワームは、Windows NT 4 および Windows 2000 インデックス サービスの既知のセキュリティ ホールに乗じて、Web サイトの破壊や DoS (サービス拒否) ツールのインストールといったいくつかの損害の一つを発生させる恐れがあります。この脆弱性に対処するパッチは2001 年 6 月 18 日にリリースされています。これについては マイクロソフト セキュリティ情報 [MS01-033](http://www.microsoft.com/japan/technet/security/bulletin/ms01-033.mspx) に記述されています。

Code Red ワームを分析した結果、このワームはパッチを適用していない IIS に感染することがわかっています。感染するとまず Web ページにいたずら書きが書き込まれ、続いて分散サービス拒否 (DDoS) 攻撃の起動に用いられる不当なコードがロードされます。感染した Web ページには "Hacked by Chinese!" という言葉と http://www.worm.com へのリンクが表示されるとともに、www.whitehouse.gov への攻撃を起動するようシステムを整える DDoS コードが実行される場合があります。 このワームは、１つのシステムに感染した後、インターネット上のパッチが適用されていない他の IIS のシステムへと増殖を試みます。

マイクロソフト セキュリティ情報 [MS01-033](http://www.microsoft.com/japan/technet/security/bulletin/ms01-033.mspx) で提供されているパッチは、このワームが悪用する脆弱性を排除するものであり、適用することによりシステムをこの攻撃から保護することができます。システムがこのワームに感染した場合は直ちにネットワークから取り除き、CERT® Coordination Center の草案によるガイドラインで指定されている方法でソフトウェアとデータを再インストールしてください。このガイドラインは http://www.cert.org/tech\_tips/root\_compromise.html から入手できます。またシステムをリストアしたら、MS01-033 に記述されたパッチを適用し、この攻撃に対する脆弱性を未然に予防してください。

[](#mainsection)[ページのトップへ](#mainsection)
