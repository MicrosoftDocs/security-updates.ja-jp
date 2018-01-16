---
TOCTitle: Data Encryption Toolkit for Mobile PCs
Title: Data Encryption Toolkit for Mobile PCs
ms:assetid: '77403c60-81c4-48c4-b2ee-cbf410572bf0'
ms:contentKeyID: 19885833
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc162808(v=TechNet.10)'
---

Data Encryption Toolkit for Mobile PCs : 計画および実装ガイド
=============================================================

### 概要

公開日: 2007年9月14日

**ダウンロード**

[Data Encryption Toolkit for Mobile PCs を入手する (英語)](http://www.microsoft.com/downloads/details.aspx?familyid=1a99576a-fe67-418f-88b1-81e2055fe977&displaylang=en)

*Data Encryption Toolkit for Mobile PCs 計画および実装ガイド*』では、モバイル PC のデータを保護するための戦略の一環として Microsoft®  BitLocker™  ドライブ暗号化 (BitLocker) と暗号化ファイル システム (EFS) を使用する場合の、計画および実装のプロセスについて説明します。

##### トピック

[](#e5c)[BitLocker の簡単な概要](#e5c)  
[](#ebd)[EFS の簡単な概要](#ebd)  
[](#e5d)[各章の要約](#e5d)  
[](#eue)[対象読者](#eue)  
[](#ebf)[表記規則](#ebf)  
[](#e1g)[サポートとフィードバック](#e1g)  
[](#eih)[謝辞](#eih)
<span id="E5C"></span>

BitLocker の簡単な概要
----------------------

BitLocker は、コンピュータのデータとオペレーティング システムを厳重に保護する、Windows Vista™ オペレーティング システムの新しい重要なセキュリティ機能です。BitLocker はボリューム全体の暗号化テクノロジであり、インストールされたオペレーティング システムがオフラインのときに何者かがコンピュータを改ざんしようとした場合に、データが表示されないようにすることができます。BitLocker は、互換性のある Trusted Platform Module (TPM) マイクロチップと BIOS を使用することで高度なデータ保護機能を実現し、初期ブート コンポーネントの整合性も保証するため、この両者が装備されたコンピュータで最も効果を上げます。また、外付け USB キーをトークンとして使用し、スタートアップ キーを保存することもできます。

[](#mainsection)[ページのトップへ](#mainsection)

<span id="EBD"></span>
EFS の簡単な概要
----------------

EFS では、高度な標準ベースの暗号化アルゴリズを使用した、透過的なファイル暗号化および暗号化解除を行うことができます。適切な暗号化キーを所持していない個人またはプログラムは、ファイルが含まれているコンピュータを物理的に所有していても、暗号化されたデータを解読することはできません。コンピュータおよびそのファイル システムへのアクセスを許可されたユーザーでも、データを表示することはできません。

EFS は、ファイル内のデータの保護に使用される対称暗号化と、対称暗号化で使用されるキーの保護に使用される非対称暗号化という 2 種類の暗号化を組み合わせたものです。

[Windows 2000 Server Resource Kit](http://www.microsoft.com/technet/prodtechnol/windows2000serv/reskit/default.mspx?mfr=true) の『*Distributed Systems Guide*』(英語) に、EFS の概要と Microsoft Windows® 2000 の EFS に関する詳細が紹介されています。この情報をオンラインで検索するには、\[Windows 2000 Server Resource Kit\] の目次で *\[Distributed Systems Guide\]*、**\[Distributed Security\]** の順に展開し、**\[Encrypting File System\]**

Windows 2000、Windows XP Professional、Windows Server® 2003、および Windows Vista の EFS には違いがあります。Windows XP Professional Resource Kit (英語) で Windows 2000 と Windows XP Professional の EFS の実装の違いが、「[Encrypting File System in Windows XP and Windows Server 2003](https://technet.microsoft.com/ja-jp/library/dc261d01-f76c-dd44-94f5-2a5e027fdfa7(v=TechNet.10))」 で Windows XP と Windows Server 2003 の変更点が説明されています。Windows XP Professional と Windows Vista の EFS の違いについては、このガイドの「[第 2 章 : 構成および展開タスク](https://technet.microsoft.com/ja-jp/library/a69e5f04-8f25-43a6-86b9-e8279021d108(v=TechNet.10))」で説明されています。

[](#mainsection)[ページのトップへ](#mainsection)

<span id="E5D"></span>
各章の要約
----------

*計画および実装ガイド*

-   [第 1 章 : 計画に際しての考慮事項](https://technet.microsoft.com/ja-jp/library/54de4f8c-d962-4744-b2da-99f7ad7953df(v=TechNet.10))。この章では、現在の環境を評価したり保護が必要なリソースや最適なセキュリティ メソッドを決定するために実行する必要のある計画の各ステップを含め、Windows Vista BitLocker および両方の種類の EFS の展開に関連した計画立案時の考慮事項について説明します。

-   [第 2 章 : 構成および展開タスク](https://technet.microsoft.com/ja-jp/library/a69e5f04-8f25-43a6-86b9-e8279021d108(v=TechNet.10))。この章では、展開タスクの一部として実行する必要のある具体的な構成タスクについて説明します。このようなタスクとして、BitLocker の構成の選択、ディスク暗号化の構成、組織での EFS の使用方法を制御および管理するための Active Directory® ディレクトリ サービスのグループ ポリシー オブジェクトの設定などがあります。この章で説明する構成タスクは、通常は準備のためのタスクであり、いったん実行してしまえば BitLocker および EFS を展開するための環境の準備が整います。また、この章では、ユーザーの環境で BitLocker および EFS を使用可能にするために各コンピュータで実行する展開タスクについても説明します。たとえば、一部のコンピュータでは BIOS を更新して、BitLocker を動作できるようにする必要があります。

-   [第 3 章 : 運用および回復のシナリオ](https://technet.microsoft.com/ja-jp/library/01754723-3e94-4bec-8284-02e2a4e91593(v=TechNet.10))。この章では、BitLocker および EFS で保護されたコンピュータを継続的に運用する方法について説明します。たとえば、キー マテリアルや証明書が紛失するか侵害された場合に、暗号化されたデータの復元という組織のニーズに対処する方法について検討します。

[](#mainsection)[ページのトップへ](#mainsection)

<span id="EUE"></span>
対象読者
--------

このガイドは、数十台から数千台のクライアント コンピュータ (特にラップトップや Tablet PC コンピュータ) で構成されたコンピュータ ネットワークの設計、計画、実装を担当する IT 専門家を対象としています。次の業務に対して責任を負う担当者は、このガイドを読む必要があります。

-   サーバーまたはクライアントのセキュリティ ポリシーの実装。

-   セキュリティまたはシステム管理アーキテクチャの設計と実装。

-   セキュリティ テクノロジの評価。

-   セキュリティ ポリシーと他のコンピュータ管理ポリシーまたはテクノロジとの統合。

[](#mainsection)[ページのトップへ](#mainsection)

<span id="EBF"></span>
表記規則
--------

 
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
<td style="border:1px solid black;">Monospace フォント
<br />
</td>
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
  
<span id="E1G"></span>
サポートとフィードバック  
------------------------
  
Solution Accelerators – Security and Compliance (SA-SC) チームは、今回またはその他のソリューション アクセラレータに関して、ユーザーの皆様からのご意見を受け付けております。コメントとフィードバックは [secwish@microsoft.com](mailto:secwish@microsoft.com?subject=data%20encryption%20toolkit%20for%20mobile%20pcs%20security%20analysis) (英語のみ)
  
ソリューション アクセラレータは、製品間の統合のために、規範的なガイダンスと自動化を提供します。このアクセラレータでは、実証済みのツールとドキュメントが利用可能なため、ユーザーは自信を持って情報テクノロジの計画、構築、展開、運用を行うことができます。さまざまなソリューション アクセラレータとその詳細を確認するには、Microsoft TechNet の 「[Microsoft Solution Accelerator TechCenter](http://technet.microsoft.com/ja-jp/solutionaccelerators/default.aspx)」 ページを参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
<span id="EIH"></span>
謝辞  
----
  
SA-SC チームは、『*Data Encryption Toolkit for Mobile PCs 計画および実装ガイド*
  
**開発リード**
  
Mike Smith - Lonergan - *Microsoft*
  
David Mowers - *Securitay, Inc.*
  
**プログラム マネージャ**
  
Bill Canning - *Microsoft*
  
**コンテンツ開発者**
  
Roger A. Grimes - *Microsoft*
  
Paul Robichaux - *3Sharp, LLC*
  
**編集者**
  
Steve Wacker - *Wadeware LLC*
  
**レビュー担当者**
  
Randy Armknecht - *Calamos Investments*
  
Vijay Bharadwaj - *Microsoft*
  
Marcus Bluestein - *Kraft Kennedy & Lesser, Inc.*
  
Dean Chen - *Waggener Edstrom Worldwide*
  
Tom Daemen - *Microsoft*
  
Mike Danseglio - *Microsoft*
  
Erik Holt - *Microsoft*
  
Russell Humphries - *Microsoft*
  
David Kennedy - *Microsoft*
  
Luca Lorenzini
  
Douglas MacIver - *Microsoft*
  
Sanjay Pandit - *Microsoft*
  
Greg Petersen - *Avanade*
  
Matt Setzer - *Microsoft*
  
Stan Shkolnik - *Deloitte Touche Tohmatsu*
  
Michael Trotman - *United States Postal Service (USPS)*
  
Richard Trusson - *Microsoft*
  
Mike Wolfe - *Microsoft*
  
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
  
#### 目次
  
-   概要  
-   [第 1 章 : 計画に際しての考慮事項](https://technet.microsoft.com/ja-jp/library/54de4f8c-d962-4744-b2da-99f7ad7953df(v=TechNet.10))  
-   [第 2 章 : 構成および展開タスク](https://technet.microsoft.com/ja-jp/library/a69e5f04-8f25-43a6-86b9-e8279021d108(v=TechNet.10))  
-   [第 3 章 : 運用および回復のシナリオ](https://technet.microsoft.com/ja-jp/library/01754723-3e94-4bec-8284-02e2a4e91593(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
