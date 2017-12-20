---
TOCTitle: 'W32.Slammer ワームの感染を防止するための ISA Server の構成'
Title: 'W32.Slammer ワームの感染を防止するための ISA Server の構成'
ms:assetid: '05054f74-76c6-4998-90b5-6cfba3ac5c4e'
ms:contentKeyID: 19869286
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277343(v=TechNet.10)'
---

W32.Slammer ワームの感染を防止するための ISA Server の構成
==========================================================

Microsoft® Internet Security and Acceleration (ISA) Server 2000 を使用すると、W32.Slammer ワーム (Slammer) の拡散を防止できます。しかし、なによりも先に講じるべき対策は、現在の稼働環境にある SQL サーバーの保護です (下記の「システムに修正プログラムを適用し、保護する」を参照してください)。

このドキュメントでは、Slammer が拡散する方法、サーバーへの修正プログラムの適用に関する詳細情報の参照先、ISA Server で Slammer の感染を防止する方法、および関連情報の参照先について説明します。

##### トピック

[](#efaa)[免責](#efaa)

[](#eeaa)[Slammer ワームはどのように拡散するのか](#eeaa)

[](#edaa)[システムに修正プログラムを適用し、保護する](#edaa)

[](#ecaa)[ISA Server による Slammer の阻止](#ecaa)

[](#ebaa)[サマリー](#ebaa)

[](#eaaa)[その他の情報](#eaaa)

### 免責

マイクロソフトは、この情報についていかなる責任も負わないものとします。いかなる場合も、著者は、この情報が使用されたことまたは広く知られたことに起因または関連する一切の損害に対し、責任を負わないものとします。この情報は、お客様ご自身の責任でご利用ください。

[](#mainsection)[ページのトップへ](#mainsection)

### Slammer ワームはどのように拡散するのか

Slammer は、Microsoft SQL Server 2000 を実行しているコンピュータ、および Microsoft Desktop Engine (MSDE) 2000 を実行しているコンピュータを標的とします。このワームは、SQL Server 解決サービス ポートである UDP ポート 1434 に 376 バイトを送信します。この多数のパケットが送信されることによって、サービス拒否攻撃につながります。Slammer は、メモリに常駐するプロセスとしてのみ拡散します。ワーム自身をハード ドライブに書き込むことはありません。

[](#mainsection)[ページのトップへ](#mainsection)

### システムに修正プログラムを適用し、保護する

以上は、Slammer がどのように拡散し、感染するかを簡単に説明したに過ぎません。前述のように、SQL Server 2000 セキュリティ ツールを使用して、SQL Server 2000 を実行しているコンピュータを保護することが先決課題です。SQL Server 2000 セキュリティ ツールは、SQL Server 2000 のインスタンスをスキャンしてセキュリティの脆弱性を検出し、影響を受けるファイルに更新プログラムを適用します。

SQL サーバーのセキュリティ保護の詳細については、[Download details: SQL Server 2000 Security Tools](http://www.microsoft.com/downloads/details.aspx?familyid=9552d43b-04eb-4af9-9e24-6cde4d933600) (英語) を参照してください。

[](#mainsection)[ページのトップへ](#mainsection)

### ISA Server による Slammer の阻止

以下の手順を実行することで、Slammer による感染の拡大からネットワークを保護するように ISA Server を構成できます。

この手順は、以下の条件が満たされていることを前提としています。

-   ISA Server がファイアウォール モードまたは統合モードでインストールされている。

-   
-   ISA Server が、インターネットと内部ネットワークを接続する唯一のルートである。

-   
-   IP パケット フィルタが有効である。

-   
-   内部ネットワークに対して UDP-1434 を許可するサーバー公開ルールが存在しない。

-   
-   匿名ルールが存在しない。

-   

外部への攻撃を防止するには、以下の手順を実行してください。

1.  以下のパラメータを使用してプロトコル定義を作成します。

    -   \[名前\] を「SQL Enumeration」に設定します。

    -   
    -   \[プロトコル\] を \[UDP\] に設定します。

    -   
    -   \[方向\] を \[送信\] に設定します。

    -   
    -   \[ローカル ポート\] を \[任意\] に設定します。

    -   
    -   \[リモート ポート\] を \[1434\] に設定します。

    -   

2.  3.  以下のパラメータを使用してプロトコル ルールを作成します。

    -   \[動作\] を \[拒否する\] に設定します。

    -   
    -   \[プロトコル\] を「SQL Enumeration」に設定します。

    -   
    -   \[スケジュール\] を \[常時\] に設定します。

    -   
    -   \[適用先\] を \[すべての要求\] に設定します。

    -   

4.  

[](#mainsection)[ページのトップへ](#mainsection)

### サマリー

Slammer からネットワークを防御するために最初にとるべきアクションは、SQL Server 2000 を実行しているすべてのコンピュータを保護し、修正プログラムを適用することです。さらに、ISA Server で Slammer の侵入を防止します。これらの手順を実行することで、現状の防御態勢を改善できるとともに、内部ネットワーク上のコンピュータで感染が拡大することを防止できます。

[](#mainsection)[ページのトップへ](#mainsection)

### その他の情報

以下のリンクは、この記事で説明した内容に関する詳細情報の参照先です。

-   <http://www.microsoft.com/technet/security/alerts/slammer.mspx> (英語)

-   
-   [http://www.microsoft.com/downloads/details.aspx?displaylang=ja&FamilyID=9552d43b-04eb-4af9-9e24-6cde4d933600](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9552d43b-04eb-4af9-9e24-6cde4d933600)

-   
-   [http://www.microsoft.com/japan/technet/security/bulletin/ms02-061.asp](http://www.microsoft.com/japan/technet/security/bulletin/ms02-061.mspx)

-   

[](#mainsection)[ページのトップへ](#mainsection)
