---
TOCTitle: 第 23 回 Windows Vista のセキュリティ機能 ～ Windows Defender ～
Title: 第 23 回 Windows Vista のセキュリティ機能 ～ Windows Defender ～
ms:assetid: 'c8793631-1493-430d-a2e0-473fd9817c01'
ms:contentKeyID: 19871877
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362932(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 23 回 Windows Vista のセキュリティ機能 ～ Windows Defender ～

公開日: 2007年11月28日

![](images/Dd362932.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/13931ae3-30fd-4b8d-b8c8-5b1ef570fe31(v=TechNet.10))は、Microsoft BitLocker ドライブ暗号化 (BitLocker) について触れました。今回は、Windows Defender について触れます。

Windows Defender は、Windows Vista の機能であり、Windows XP では、[別途ダウンロード可能な追加機能](http://www.microsoft.com/japan/athome/security/spyware/software/default.mspx) として提供しています。 Windows Defender は、ブラウザ、電子メールやアプリケーションのバンドルから侵入しようとするスパイウェアなどのユーザーが「望ましくないソフトウェア」を検出、隔離するための機能になります。一言で言えば、Windows のスパイウェア対策機能となります。この「望ましくないソフトウェア」には、ブラウザの設定を強制的に変更するようなブラウザハイジャッカーや、広告を出し続けるようなアドウェアなども含まれています。

Windows Defender の機能は、大別すると 2 つに分かれており、1 つが、ファイルのコピーや、ブラウザの挙動を常に監視し、侵入を未然に食い止める常時監視の機能。もう 1 つが、ディスクやレジストリを走査し、スパイウェアの侵入がないかを確認する定期的なスキャン機能です。

2 つの機能を組み合わせているのは、定期的なスキャン機能により、常時監視の時には、発見できなかったスパイウェアも、最新の定義ファイルによるスキャンを行うことで後から発見できる場合もあるためです。 「望ましくないソフトウェア」は、通常のウイルス等と違い即座に悪意のあるプログラムと判断する事ができません。「望ましくないソフトウェア」は、ユーザーがその機能を正しく認識し、望んで使用しているかによって判断が分かれます。たとえば、パソコンの監視ソフトの場合、ユーザーがリモート監視の為などで意図的に導入する事もあれば、知らず知らずの内に導入され、コッソリと監視されている場合もあります。前者の場合は、正しい用途のソフトウェアとなり、後者は、「望ましくないソフトウェア」となります。 Windows Defender では、この判断をするために SpyNet と呼ばれる評価機能があり、ユーザーが、「望ましくないソフトウェア」をレポートする事が可能です。その評価によって、大多数のユーザーがどの様に判断しているかを確認し、定義ファイル作成の材料にしています。

定義ファイルは、新たな「望ましくないソフトウェア」が発見される毎に更新され、Windows Update (Microsoft Update) を通じて配信されます。長期にわたり定義ファイルを更新しない場合や、スキャンを行っていない場合は、Windows Defender が、更新およびスキャンをするように通知を行います。

「望ましくないソフトウェア」は、ユーザーの使用感を悪くするのはもちろんですが、場合によっては OS の動作を妨げ、色々なトラブルを引き起こします。サポートに問い合わせがある、不正終了やパフォーマンスの低下は、突き詰めて調べてみると「望ましくないソフトウェア」が原因であったことも少なくはありません。

Windows Defender は、「望ましくないソフトウェア」から、ユーザーを守ると供に、OS の安定性を向上させるための重要な機能でもあります。もし、有効にしていない場合は、\[コントロールパネル\] - \[セキュリティ\] - \[Windows Defender\] を選択して、有効にすることをお勧めします。

[![](images/Dd362932.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))

この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 購読無料

![](images/Dd362932.subscribe(ja-jp,TechNet.10).gif)

[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx) では、セキュリティに関する様々な情報を毎月お届けしています。
セキュリティ ニュースレターを [購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。

**バックナンバー**
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
