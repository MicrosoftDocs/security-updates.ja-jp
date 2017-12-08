---
TOCTitle: '第 8 回 動いてなければ危険じゃない ～ Reduce Attacking Surface (2) ～ サービスの権限の最小化'
Title: '第 8 回 動いてなければ危険じゃない ～ Reduce Attacking Surface (2) ～ サービスの権限の最小化'
ms:assetid: '8d709472-cfda-4fa0-aa4d-8118d90591fc'
ms:contentKeyID: 19871862
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362917(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 8 回 動いてなければ危険じゃない ～ Reduce Attacking Surface (2) ～ サービスの権限の最小化

公開日: 2006年8月23日

![](images/Dd362917.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/c637f3cf-9822-431b-a344-9f352a231c98(v=TechNet.10))は、サービスそのものが動作する数を減らすことで攻撃に対処する方法を取り上げました。今回は、動作しているサービスが攻撃を受けた時に被害を最小限に抑えるために、サービスの権限の最小化についてお話します。

サービスは、幾つか特別な部分もありますが、Windows 上で動作しているプログラムである点では、通常のアプリケーションと変わりがありません。1 番の違いは、通常のアプリケーションは、ログオンしているユーザーの権限で動作していますが、サービスは、特定のユーザーが動作させているわけではないということです。Windows の起動時にサービスが自動的に起動している場合もあり、これは、ユーザーがログオンする前に行われています。そもそも、「ログオン」自体もサービスが提供しています。では、「誰の権限で動作しているか？」という疑問がでてきます。この答えは、サービスを動作させるためのユーザー (正確には、アカウント) があり、それが使用されているということです。

このアカウントには、主に、以下の 3 つのアカウントが使用されます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >権限の強さ</th>
<th style="border:1px solid black;" >アカウント名</th>
<th style="border:1px solid black;" >概要</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">強</td>
<td style="border:1px solid black;">Local System</td>
<td style="border:1px solid black;">OS と同等の権限を持つ、もっとも強い権限を持つアカウント</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">中</td>
<td style="border:1px solid black;">Network Service</td>
<td style="border:1px solid black;">ネットワーク接続を行うサービス向けの、権限が制限されたアカウント</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">弱</td>
<td style="border:1px solid black;">Local Service</td>
<td style="border:1px solid black;">各 PC 上でも動作するサービス向けの、権限が制限されたアカウント</td>
</tr>
</tbody>
</table>
  
最も簡単に各サービスの権限を最小にするには、使用するアカウントを権限の弱いものに変更する事ですが、すでに動作済みのサービスのアカウントを変更すると、必要な権限が無いために正常に動作しない場合もあり安易には変更できません。
  
また、これらの OS が最初から持っているビルトイン アカウントの他に、管理者が特別に作成したアカウントを使用することもあります。このアカウントは、通常のユーザーと同じアカウントですが、「ユーザー権利の割り当て」という機能を使って、「特権」を与えることでサービス用のアカウントとして使用することができます。この、「特権」こそが、各アカウントで何ができるかを決定する権限の正体となります。
  
特権の中には、「オペレーティング システムの一部として機能」という最も強力な権限があり、ほぼ全ての操作が可能です。Local System アカウントは、この特権を持っているため、正しく使えば便利な反面、攻撃を受け不正にのっとられた場合に非常に危険な状況になります。この様な、本当に特別な特権もあれば、「操作チェックのバイパス」の様な全てのアカウントに与えられる、セキュリティ上はあまり害の無い特権もあります。これらの特権を必要最小限に特定のアカウントに付与することで、そのアカウントを使用したサービスが攻撃を受けて乗っ取られても被害を抑えることができるというわけです。
  
さて、Windows 標準のサービスも Local System を使っていますが、これは、サービスが他のユーザー アカウントに成り代って作業を行ったり、OS の深部を管理したりするために OS と同等の操作を必要とするためです。しかし、実際にその様な権限は、サービスの起動直後の短い時間にだけ必要であったりする場合もあります。このように、権限を使用する時間が限られている場合は、その特権を後から破棄することが可能です。一度破棄すると二度と特権を取り戻すことができないため、Local System で起動していても安全性を確保することが可能です。
  
なお、Windows Vista では、サービスが使用するアカウントおよび特権がさらに制限されています。また、追加された新しい機能により、使用できるネットワーク ポートや、通信相手も制限しています。
  
**関連サイト：**
  
-   [サービスおよびサービス アカウントのセキュリティ計画ガイド](http://www.microsoft.com/japan/technet/security/topics/serversecurity/serviceaccount/default.mspx)
  
-   [脅威とその対策 : Windows Server 2003 と Windows XP のセキュリティ設定](http://www.microsoft.com/japan/technet/security/topics/serversecurity/tcg/tcgch01n.mspx)
  
-   [Windows Server 2003 セキュリティ ガイド](http://www.microsoft.com/japan/technet/security/prodtech/windowsserver2003/w2003hg/s3sgch01.mspx)
  
![](images/Dd362917.btn_reg_today(ja-jp,TechNet.10).jpg)
  
この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### バックナンバー
  
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
