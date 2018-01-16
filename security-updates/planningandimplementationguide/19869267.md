---
TOCTitle: 'Data Encryption Toolkit for Mobile PCs : 概要'
Title: 'Data Encryption Toolkit for Mobile PCs : 概要'
ms:assetid: 'abfc4696-a39a-43df-b559-133633e4bd5e'
ms:contentKeyID: 19869267
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc162811(v=TechNet.10)'
---

Data Encryption Toolkit for Mobile PCs – セキュリティ分析
=========================================================

### 概要

公開日: 2007年8月20日

**ダウンロード**

[Data Encryption Toolkit for Mobile PCs を入手する (英語)](http://www.microsoft.com/downloads/details.aspx?familyid=1a99576a-fe67-418f-88b1-81e2055fe977&displaylang=en)

大部分の組織にとって、ほんの数年前まで、ラップトップ コンピュータは比較的珍しい存在でした。一般的に、ラップトップが支給されたのは、出張の多い従業員と役員に限られていました。今日、ラップトップは従来よりも高性能になり、広く普及するようになりました。もはやラップトップは選ばれた少数の従業員に割り当てられるものではなく、組織によってはデスクトップ コンピュータよりも多くなっています。ラップトップは、記憶容量が大きくなるにつれて、あらゆる種類の機密データを保存する、ますます重要な存在になってきています。

ラップトップの台数が大幅に増えると、紛失または盗難に遭うラップトップの台数もそれに応じて増加しました。中規模から大規模まで、大部分の組織にとって、ラップトップのセキュリティは深刻な問題です。Ponemon Institute が実施した最近の調査「[Confidential Data at Risk](http://www.csoonline.com/read/080106/col_ponemon.html)」(英語) によると、調査に回答した 484 人のうち、81 パーセントが、自社において過去 12 か月の間に機密情報や社外秘のビジネス情報が保存された 1 台以上のラップトップ コンピュータが紛失したと回答しています。機材を補充するコストも高額ですが、盗難に遭ったラップトップのハード ディスク ドライブに重要なデータや機密データが保存されていた場合、セキュリティ侵害の直接コスト、間接コストはさらに高くなる可能性があります。

中には、米国連邦法や特定国家の法律で保護されている情報、州、都道府県、地域の条例で保護されている情報、業界規制で保護されている情報などもあります。ラップトップの台数が増えるにつれて、法律、規制範囲、機密性の分類なども多様になっています。ラップトップ コンピュータを紛失した場合、予防的なセキュリティ対策にどれだけ努力を注いだかに応じて、組織は高額な罰金を科せられたり社会的責任を追及されたりする可能性があります。セキュリティ侵害によって生じる直接コストや間接コストには、顧客との取引関係の維持が困難になることや、信頼性および社会的評価の失墜なども含まれます。

Microsoft は、ラップトップ コンピュータのセキュリティ問題に対処するためのツールを提供しています。ラップトップでデータを適切に暗号化すると、ラップトップが紛失や盗難に遭った場合でも、機密データの盗用をはるかに困難にすることができます。Microsoft® BitLocker™ ドライブ暗号化 (BitLocker) と暗号化ファイル システム (EFS) を適切に使用することで、さまざまな種類の一般的な攻撃から機密データを保護できます。

『*Microsoft Data Encryption Toolkit for Mobile PCs セキュリティ分析*』では、BitLocker と EFS を使用して実現できるセキュリティ レベルについて詳細な情報を提供します。Windows Vista™ Enterprise および Ultimate エディションは、このガイドで説明されているセキュリティ機能をすべてサポートします。また、一部の役立つ優れた機能は Microsoft Windows® XP でも利用できます。使用する機能と構成に応じて、複数レベルの保護を実現できます。ほとんどのセキュリティ構成に共通しますが、ハード ディスク ドライブにあるデータの暗号化を解除する場合、悪意のある攻撃者には途方もないリソースが必要になります。

『*セキュリティ分析*』は、Windows Vista と Windows XP の機能によって、組織内の特定のセキュリティ リスクをどのように軽減、または緩和するのかを理解するために役立ちます。このガイドは、次の目的に役立ちます。

-   環境に存在する一般的な脅威やリスクを特定する。

-   BitLocker と EFS を個別に、または組み合わせて使用し、特定のリスクや脅威を軽減する方法を理解する。

-   BitLocker または EFS で対処できないセキュリティ上の脅威を軽減するために準備を整える。

-   Windows Vista で利用できる特定のセキュリティ機能とテクノロジを理解する。

このガイドで説明するセキュリティ機能は、業界で認められたテクノロジを使用して開発されました。たとえば、Microsoft が実装した BitLocker と EFS の暗号化アルゴリズムは米連邦政府情報処理規格 (FIPS) 140-1 への準拠が認定されており、この実装アルゴリズムの成熟度は保証されています。業界認定テクノロジに準拠することは重要です。なぜなら、国や州が定めた一部のプライバシー保護法では、データ セキュリティのために最も優れた手法を採用しようと誠実な努力を続けた組織には、責任の免除や軽減が認められるためです。

##### トピック

[](#egaa)[対象読者](#egaa)  
[](#efaa)[章の内容](#efaa)  
[](#eeaa)[表記規則](#eeaa)  
[](#edaa)[関連情報](#edaa)  
[](#ecaa)[サポートとフィードバック](#ecaa)  
[](#ebaa)[謝辞](#ebaa)

### 対象読者

このガイドは、数十から数千のクライアント コンピュータ (特にラップトップ) に対して、ポリシーやテクノロジの採用決定または推奨の責任を負っているセキュリティ専門家を対象としています。ここで説明するテクノロジと脅威は、通常、ホーム ユーザーまたはホーム ネットワークには該当しません。次の業務に対して責任を負っているユーザーは、このガイドを読む必要があります。

-   セキュリティ ポリシーとテクノロジの採用に関して決定または推奨を行う。

-   サーバーまたはクライアントのセキュリティ ポリシーを実装する。

-   セキュリティ テクノロジを評価する。

-   セキュリティ ポリシーと他のコンピュータ管理ポリシーまたはテクノロジを統合する。

このガイドは、高度な内容を詳細に説明しており、セキュリティ、暗号化、ファイル システム、セキュリティ/システム管理の基本的なトピックを説明するものではありません。

[](#mainsection)[ページのトップへ](#mainsection)

### 章の内容

ここでは、このガイドの各章を簡単に説明します。

[第 1 章 : リスクの検討](https://technet.microsoft.com/ja-jp/library/df2c6d71-98f7-4212-b3b7-b9eb2f501348(v=TechNet.10)) - BitLocker と EFS で対処できるセキュリティ上の脅威を紹介します。また、リスクとセキュリティの利点を示す、より具体的な枠組みを提示するために、『*セキュリティ分析*』の中で挙げられるシナリオについて説明します。

[第 2 章 : BitLocker ドライブ暗号化](https://technet.microsoft.com/ja-jp/library/4e6ce820-fcac-495a-9f23-73d65d846638(v=TechNet.10)) - Windows Vista で導入された BitLocker ドライブ暗号化テクノロジに焦点を当てます。この章では、第 1 章で説明したセキュリティの脅威を BitLocker によって軽減する方法を説明します。また、組織内に強固な BitLocker の実装を構築するためのスタート地点として利用できる構成の事例も示します。

[第 3 章 : 暗号化ファイル システム](https://technet.microsoft.com/ja-jp/library/dc2cde72-a84d-4716-9a30-f62b608efda1(v=TechNet.10)) - EFS が機能する仕組み、この機能を使用して環境内の特定の脅威を軽減する方法を説明します。

[第 4 章 : BitLocker と EFS の併用](https://technet.microsoft.com/ja-jp/library/80c0d0af-2c2e-45d6-9b29-f850926296bb(v=TechNet.10)) - BitLocker と EFS を併用することで、個別に使用する場合よりも有効に脅威を軽減する方法を説明します。

[第 5 章 : 適切なソリューションを選択する](https://technet.microsoft.com/ja-jp/library/b77d6369-10e9-4e66-8c67-c9f8cb073ced(v=TechNet.10)) - セキュリティ専門家が組織に合わせて機能の適切な組み合わせと構成を選択できるように、詳細情報とツールを提供します。

[](#mainsection)[ページのトップへ](#mainsection)

### 表記規則

このガイドでは、次の表に示す表記規則が使用されます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>太字フォント</strong></td>
<td style="border:1px solid black;">コマンド、スイッチ、ファイル名など、そのまま入力する文字を示します。ユーザー インターフェイスも太字で表記されます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>斜体フォント</em></td>
<td style="border:1px solid black;"><em>斜体</em></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>&lt;斜体&gt;</em></td>
<td style="border:1px solid black;">斜体と山かっこで示されるプレースホルダ (<em>&lt;filename&gt;</em> など) は変数を表します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Monospace フォント</td>
<td style="border:1px solid black;">コードとスクリプトのサンプルを示します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>注</strong></td>
<td style="border:1px solid black;">読者に補足情報を示します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>重要</strong></td>
<td style="border:1px solid black;">読者に重要な補足情報を示します。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 関連情報
  
この『*セキュリティ分析*』に加え、『[Data Encryption Toolkit for Mobile PCs](http://technet.microsoft.com/library/cc500474.aspx)』にはユーザーの皆様に便利なその他の文書およびツールが含まれています。
  
-   『*計画および実装ガイド*』では、モバイル PC を保護するために BitLocker と EFS の利用方法を計画して実装する方法を説明します。
  
-   Microsoft 暗号化ファイル システム アシスタント ツール (EFS アシスタント) は、Windows XP や Windows Vista を実行しているコンピュータ上で、機密ファイルの検索と暗号化のプロセスを自動化するのに役立ちます。
  
-   『*EFS アシスタントの管理者ガイド*』では、事業部門または会社全体にわたって一貫した保護機能を確立するために、管理者がドメイン参加コンピュータに EFS アシスタントを展開して管理する方法を説明します。
  
意思決定者が広範囲にわたってセキュリティ機能を実現するために、または Microsoft Windows ネットワークのセキュリティ問題を深く理解するために、貴重な多くのリソースが利用可能です。Microsoft TechNet の「[Security Guidance](http://technet.microsoft.com/security/bb977553.aspx)」ページ (英語) はそのスタート地点として役立ちます。
  
「[Best Practice Guide for Securing Windows Server Active Directory Installations](http://technet.microsoft.com/ja-jp/library/cc773365.aspx)」(英語) でアドバイスを参照することができます。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### サポートとフィードバック
  
Solution Accelerators – Security and Compliance (SASC) チームは、今回またはその他のソリューション アクセラレータに関して、ユーザーの皆様からのご意見を受け付けております。コメントとフィードバックは [secwish@microsoft.com](mailto:secwish@microsoft.com?subject=technet%20の『data%20encryption%20toolkit%20for%20mobile%20pcs%20セキュリティ分析』) までお寄せください
  
ソリューション アクセラレータは、製品間の統合のために、規範的なガイダンスと自動化を提供します。このアクセラレータでは、実証済みのツールとドキュメントが利用可能なため、ユーザーは自信を持って情報テクノロジの計画、構築、展開、運用を行うことができます。さまざまなソリューション アクセラレータとその詳細を表示するには、Microsoft TechNet の「[Solution Accelerators](http://technet.microsoft.com/ja-jp/solutionaccelerators/default)」(英語) ページを参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 謝辞
  
Solution Accelerators - Security and Compliance チーム (SA-SC) は、『*Data Encryption Toolkit for Mobile PCs セキュリティ分析*』を提供してくださったチームの方々に対し、感謝の意を表します。下記の方々はこのソリューションの執筆、開発およびテストに直接関わった、または大きく貢献した方々です。
  
**開発リード**
  
Mike Smith - Lonergan - *Microsoft*
  
David Mowers - *Securitay, Inc.*
  
**プログラム マネージャ**
  
Bill Canning - *Microsoft*
  
**コンテンツ開発者**
  
Paul Flynn - *3Sharp, LLC*
  
Tommy Phillips - *Butternut Software*
  
Paul Robichaux - *3Sharp, LLC*
  
**編集者**
  
Steve Wacker - *Wadeware LLC*
  
**レビュー担当者**
  
Vijay Bharadwaj - *Microsoft*
  
Tom Daemen - *Microsoft*
  
Mike Danseglio - *Microsoft*
  
Kurt Dillard - *Microsoft*
  
Jeff Hatfield - *Wireless Ink Inc.*
  
Erik Holt - *Microsoft*
  
Russell Humphries - *Microsoft*
  
David Kennedy - *Microsoft*
  
Douglas MacIver - *Microsoft*
  
Josh Phillips
  
Greg Petersen - *Avanade Inc.*
  
Ben Wilson - *ASG Group*
  
**製品マネージャ**
  
Alain Meeus - *Microsoft*
  
Jim Stuart - *Microsoft*
  
**リリース マネージャ**
  
Karina Larson - *Microsoft*
  
**テスター**
  
Gaurav Singh Bora - *Microsoft*
  
Sumit Ajitkumar Parikh - *Infosys Technologies Ltd.*
  
Swaminathan Viswanathan - *Infosys Technologies Ltd.*
  
Swapna Rangachari Jagannathan - *Infosys Technologies Ltd.*
  
Neethu Thomas - *Infosys Technologies Ltd.*
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 目次
  
-   概要  
-   [第 1 章 : リスクの検討](https://technet.microsoft.com/ja-jp/library/df2c6d71-98f7-4212-b3b7-b9eb2f501348(v=TechNet.10))  
-   [第 2 章 : BitLocker ドライブ暗号化](https://technet.microsoft.com/ja-jp/library/4e6ce820-fcac-495a-9f23-73d65d846638(v=TechNet.10))  
-   [第 3 章 : 暗号化ファイル システム](https://technet.microsoft.com/ja-jp/library/dc2cde72-a84d-4716-9a30-f62b608efda1(v=TechNet.10))  
-   [第 4 章 : BitLocker と EFS の併用](https://technet.microsoft.com/ja-jp/library/80c0d0af-2c2e-45d6-9b29-f850926296bb(v=TechNet.10))  
-   [第 5 章 : 適切なソリューションを選択する](https://technet.microsoft.com/ja-jp/library/b77d6369-10e9-4e66-8c67-c9f8cb073ced(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
