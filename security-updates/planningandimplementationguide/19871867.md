---
TOCTitle: 第 13 回 Windows Vista のセキュリティ機能 ～ Address Space Layout Randomization ～
Title: 第 13 回 Windows Vista のセキュリティ機能 ～ Address Space Layout Randomization ～
ms:assetid: '16d06765-1084-4648-8cf6-773310e71786'
ms:contentKeyID: 19871867
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362922(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 13 回 Windows Vista のセキュリティ機能 ～ Address Space Layout Randomization ～

公開日: 2007年1月24日

![](images/Dd362922.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社  
セキュリティ レスポンス チーム  
小野寺 匠 著

さて、Windows Vista の発売も目前です。今回から Windows Vista のセキュリティ機能について触れてみようと思います。今回は、数あるセキュリティ機能の中でも、OS 全体にかかわるが、まったくと言って良い程ユーザーの目に触れることのない機能 ASLR (Address Space Layout Randomization) について書きます。

ASLR は、語弊を恐れずに簡単に言ってしまうと「脆弱性を悪用した不正なコードの実行を難しくする」機能となります。Windows XP のDEP (Data Execute Prevention)、Visual Studio の /GS オプションと同様の目的となりますが、着目点が違います。DEPは、主にハードウェアの機能を利用してバッファオーバーランを阻止 (検出) します。/GS は、ソフトウェア的に同様のことを行います。言い換えると、不正にメモリを書き換えるような行為を防止する機能です。ASLR は、DEP, /GS のようなアプローチではなく、DEP, /GS や他の防御壁を突破して動作したコードの正常な実行を妨げることで、不正なプログラムの侵入防止を目標にしています。

Windows は、多くのコンポーネントをメモリに読み込みながら、アプリケーションを動かしています。このとき、コンポーネントを読み込むごとに、メモリの読み込み位置を計算していると、同じコンポーネントが複数回呼ばれるような場合は、非効率になってしまいます。そこで、Windows のコンポーネントの多くは、BIND 処理とよばれる、メモリの読み込み位置の指定が行われ、各コンポーネントが最適化されています。

しかし、そのことで、Windows の特定の機能がいつもメモリ上の同じ場所に位置しますので、不正なコードが Windows の機能を呼び出すことも容易となる一面もあります。ASLR では、Windows の起動時に、この読み込み位置を掻き混ぜ、毎回違うメモリアドレスに読み込まれるようにしています。起動時にこの処理が行われるのは、アドレスを固定する最適化とセキュリティのバランスを取る事を目指しているからです。

これにより、不正なコードの開発者は Windows の機能を使用する際に、メモリの位置を固定値で呼び出すのではなく、機能を探し出すコードを余分に書く必要があります。これにより、今まで以上にプログラミングが困難になりますし、追加のコードによりプログラムが大きくなるため、脆弱性を悪用しても、悪意のある人物の意図した通りに攻撃対象の Windows にコードが埋め込めない可能性も出てきます。

![](images/Dd362922.alsr-001(ja-jp,TechNet.10).gif)![](images/Dd362922.alsr-002(ja-jp,TechNet.10).gif)

(左図 : メモリ位置の例) (右図 : 別の起動時のメモリ位置の例)

とはいえ、この機能は、不正なコードの実行を不可能にするものではありません。不正なコードの実行を難しくする重要な要素ですが、この機能の存在が、ソフトウェア開発でセキュリティ上問題のあるコードを書いたり、セキュリティ更新プログラムを適用しないで良いという理由にはなりえません。引き続き、従来からの努力は継続していかなければなりません。その上で、もし、ASLR の前にある多くのセキュリティ機能や、そもそもの脆弱性をゼロに近づける取り組みをすり抜けた場合にでも、コードが実際には機能しないかもしれない可能性を残すことができる点で、有効な防御策となります。

[![](images/Dd362922.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))

この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 購読無料

![](images/Dd362922.subscribe(ja-jp,TechNet.10).gif)

[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx)では、セキュリティに関する様々な情報を毎月お届けしています。
セキュリティ ニュースレターを[購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。

**バックナンバー**
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
