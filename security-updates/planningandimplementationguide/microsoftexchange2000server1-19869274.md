---
TOCTitle: 'Microsoft Exchange 2000 Server セキュリティ運用ガイド : 第 1 章 ‐ はじめに'
Title: 'Microsoft Exchange 2000 Server セキュリティ運用ガイド : 第 1 章 ‐ はじめに'
ms:assetid: '2a5c3409-3f1f-48f8-8634-ded56d3667cb'
ms:contentKeyID: 19869274
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277324(v=TechNet.10)'
---

Microsoft Exchange 2000 Server セキュリティ運用ガイド
=====================================================

### 第 1 章 ‐ はじめに

最終更新日: 2002年9月27日

『Microsoft Exchange 2000 Server セキュリティ運用ガイド』 へようこそ。このガイドでは、Exchange 2000 Server 環境のセキュリティを最大限に強化し、日常の運用におけるセキュリティを確実に保護する手順を説明します。

このガイドは、『Microsoft Windows 2000 Server セキュリティ運用ガイド』 の補足として用意されています。このガイドを読み進む前に Windows 2000 のガイドをくまなく読んでおくことを強くお勧めします。『Microsoft Windows 2000 Server セキュリティ運用ガイド』 の内容はこのガイドの各章に密接に関連しており、必要に応じて引用されています。また、関連する章が付録に示されています。『Microsoft Exchange 2000 Server Operations』 (英語文献、Microsoft Press、ISBN : 0-7356-1831-3) もお勧めします。Exchange 2000 の運用全般についての詳細をご理解いただけます。

##### トピック

[](#egaa)[MOF (Microsoft Operations Framework) について](#egaa)

[](#efaa)[Get Secure と Stay Secure](#efaa)

[](#eeaa)[このガイドの範囲](#eeaa)

[](#edaa)[各章の概要](#edaa)

[](#ecaa)[このガイドの対象読者](#ecaa)

[](#ebaa)[まとめ](#ebaa)

[](#eaaa)[詳細情報](#eaaa)

### MOF (Microsoft Operations Framework) について

環境内でのシステム運用を最大限に合理化するには、効率的な運用管理が必要です。運用チームを支援するため、マイクロソフトは MOF (Microsoft Operations Framework) を開発しました。MOF は基本的に、運用に関するベスト プラクティス、原則、モデルを集大成した運用ガイドです。MOF ガイドラインに従うことによって、基幹業務のための運用システムのセキュリティ、信頼性、可用性、サポートや管理の容易性を維持することができます。

MOF プロセス モデルは、次のように統合された 4 つの作業領域で構成されます。

-   変更

-   
-   運用

-   
-   サポート

-   
-   最適化

-   

これら 4 つのフェーズはらせん状のライフ サイクルを形成しています (図 1.1)。このライフ サイクルは、個別のアプリケーションに始まり、複数のデータ センターを含んだ運用環境全体に至る、あらゆるレベルの運用作業に当てはまります。このガイドでは、セキュリティの運用という視点から MOF を利用します。

![](images/Dd277324.e2k0101(ja-jp,TechNet.10).gif)

**図 1.1: MOF ライフ サイクル**

プロセス モデルは、20 のサービス管理機能 (SMF)、および、統合チーム モデル、リスク モデル各 1 つから構成されます。ライフ サイクルを構成する各作業領域の終わりで運用管理レビュー (レビュー マイルストーン) を実施し、レビュー対象の作業領域における SMF の有効性を評価します。

このモデルは、MOF のエキスパートでなければ理解も利用もできないというものではありません。MOF の基本方針をよく理解すれば、運用環境の管理や、その信頼性、可用性、および安定性の維持に役立ちます。

MOF の詳細と企業環境での利用方法については、Microsoft Operations Framework の Web サイトをご覧ください。詳細については、この章の終わりにある「詳細情報」を参照してください。

[](#mainsection)[ページのトップへ](#mainsection)

### Get Secure と Stay Secure

2001 年 10 月、マイクロソフトはストラテジック テクノロジー プロテクション プログラム (STPP : Strategic Technology Protection Program) という計画を開始しました。このプログラムの目的は、マイクロソフトが提供するセキュリティ関連の製品、サービス、サポートを統合することです。Microsoft では、セキュリティで保護された環境を維持するプロセスを Get Secure (セキュリティの確保) と Stay Secure (セキュリティの維持) という 2 つの関連するフェーズに分けて考えています。

#### Get Secure (セキュリティの確保)

最初のフェーズは Get Secure (セキュリティの確保) です。組織が適切なレベルのセキュリティを確保するためには、「マイクロソフト セキュリティ ツール キット」にあるセキュリティ確保のガイドラインに従います。このツール キットはオンラインで入手できます (このツール キットと STPP の詳細については、「詳細情報」を参照してください)。

#### Stay Secure (セキュリティの維持)

第 2 のフェーズは Stay Secure (セキュリティの維持) です。セキュリティが確保された環境を構築することと、そのセキュリティを維持することとは、まったく別のものです。コンピューティング環境を構築し、稼働を開始した後で、セキュリティを維持し、脅威への防御策を整え、攻撃を受けたときには有効な対抗手段をとるという一連の対策を新たに考える必要があります。

[](#mainsection)[ページのトップへ](#mainsection)

### このガイドの範囲

このガイドでは、Exchange 2000 を搭載したサーバーで構成される環境のセキュリティを確立し、維持するために必要な作業に主眼を置きます。OWA フロントエンド サーバーとバックエンド サーバーから成るサーバーに対して定義された 2 つの特定の役割について説明することを目的としています。IMAP4 (Internet Message Access Protocol 4) または POP3 (Post Office Protocol 3) のセキュリティで保護された実行方法については触れません。

このガイドは、Exchange の総合的なセキュリティ戦略の一部をなす資料として使用するためのものであり、セキュリティで保護された環境の確立と維持に関する事項をすべて網羅したマニュアルではありません。次の図は、そうした領域の概略を示したもので、このガイドでは白い文字で書かれたグレイのボックス部分について説明します。その他のグレイの部分は、「Microsoft Windows 2000 Server セキュリティ運用ガイド」で説明されています。

![](images/Dd277324.e2k0102(ja-jp,TechNet.10).gif)

**図 1.2: Exchange の総合的なセキュリティ対策に関するこのガイドの範囲**

**メモ** 「Microsoft Windows 2000 Server セキュリティ運用ガイド」は Web サイトから入手可能です。詳細については、この章の末尾の「詳細情報」を参照してください。

次のフローチャートは、サーバーのセキュリティを確立し (Get Secure)、その状態を保つ (Stay Secure) ために必要な作業を示したものです。また、このフローチャートには、各作業に関するこのガイドと「Microsoft Windows 2000 Server セキュリティ運用ガイド」の章が示してあります。

![](images/Dd277324.e2k0103(ja-jp,TechNet.10).gif)

**図 1.3: Get Secure (セキュリティの確保) と Stay Secure (セキュリティの維持) のフェーズを示すプロセス フローチャート**

[](#mainsection)[ページのトップへ](#mainsection)

### 各章の概要

このガイドは以下の章構成になっています。各章ではテーマごとにセキュリティ運用プロセスの一部を説明します。どの章も、全体または必要な情報だけ読んでも理解できるように工夫されています。

#### 第 2 章 ‐ Exchange 2000 環境のセキュリティを確保する

Exchange は相互に依存するコンポーネントから成る複雑なアプリケーションです。Exchange のセキュリティを確保するには、このコンポーネント間の関係を理解し、それを考慮したセキュリティ設計を行う必要があります。この章では Exchange 2000 環境に対する全般的なリスクを説明します。また、次の第 3 章で出てくるバックエンド サーバーとフロントエンド サーバーの 2 つのサーバーの役割についても説明します。そして「Microsoft Windows 2000 Server セキュリティ運用ガイド」とリンクさせながら、セキュリティがどのようにこれら 2 種類のサーバーで実行されるのかを説明します。

#### 第 3 章 ‐ 役割に基づいて Exchange 2000 サーバーのセキュリティを強化する

この章では、バックエンド サーバーの役割と OWA (Outlook Web Access) フロントエンド サーバーの役割についてセキュリティ保護し、そのセキュリティを強化するための手順を説明します。Exchange 2000 サーバーのセキュリティを最大限に強化するため、Windows 2000 環境のセキュリティを確保するための変更について説明します。

#### 第 4 章 ‐ Exchange の通信セキュリティを強化する

この章は Exchange 2000 Server とクライアント (Outlook など) 間の通信の保護について説明します。OWA サーバー設置のためのファイアウォールの検討事項を確認し、OWA サーバーからクライアントへのトラフィックだけでなく、OWA サーバーから内部 Exchange バックエンド サーバーへのトラフィックにおけるセキュリティの確保についても検証します。また、SMTP トラフィックのセキュリティ保護についても説明します。

[](#mainsection)[ページのトップへ](#mainsection)

### このガイドの対象読者

このガイドは、組織の Exchange 2000 のセキュリティ保護の担当者、および Windows 2000 と IT セキュリティの全般的な基本方針に詳しい人を対象にしています。

[](#mainsection)[ページのトップへ](#mainsection)

### まとめ

この章では、ガイド全体の内容を示し、各章の概要を紹介しました。また、STTP (Strategic Technology Protection Program) の概要も説明しました。このガイドの構成を理解した時点で、第 1 章から通読するか、必要な箇所だけを選んで読むかを決めることができます。セキュリティ業務が実効性を発揮するためには、どれか 1 つの面だけで改善を図るのではなく、すべての面で対策を講じる必要があるため、ぜひ全章を通してお読みください。

[](#mainsection)[ページのトップへ](#mainsection)

### 詳細情報

-   企業における MOF の利点についての詳細 (英語)
    <http://www.microsoft.com/technet/solutionaccelerators/cits/mo/mof/default.mspx>

-   
-   Strategic Technology Protection Program の情報
    <http://www.microsoft.com/japan/security/guidance/default.mspx>

-   
-   マイクロソフト セキュリティ ツール キット
    <http://www.microsoft.com/japan/technet/security/tools/default.mspx>

-   
-   Microsoft Strategic Technology Protection Program (STPP) Web サイト
    <http://www.microsoft.com/japan/security/guidance/default.mspx>

-   
-   Windows 2000 Server セキュリティ運用ガイド
    [http://www.microsoft.com/japan/technet/security/prodtech/
    /windows2000/staysecure/default.mspx](http://www.microsoft.com/japan/technet/security/prodtech/windows2000/staysecure/default.mspx)

-   
-   Microsoft Exchange 2000 Server セキュリティ運用ガイド
    [http://www.microsoft.com/japan/technet/security/prodtech/
    exchangeserver/opsguide/default.mspx](https://technet.microsoft.com/ja-jp/library/5adcd128-c106-4554-96f2-05b737609fd6(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)

### 目次

-   [概要](https://technet.microsoft.com/ja-jp/library/5adcd128-c106-4554-96f2-05b737609fd6(v=TechNet.10))
-   
-   第 1 章 ‐ はじめに
-   
-   [第 2 章 ‐ Exchange 環境のセキュリティを確保する](https://technet.microsoft.com/ja-jp/library/460b9ff3-7430-4c17-ac2a-cedb5d768e43(v=TechNet.10))
-   
-   [第 3 章 ‐ 役割に基づいて Exchange 2000 サーバーのセキュリティを強化する](https://technet.microsoft.com/ja-jp/library/b41b1f18-5372-4009-8ef7-49740f56ab32(v=TechNet.10))
-   
-   [第 4 章 ‐ Exchange の通信セキュリティを強化する](https://technet.microsoft.com/ja-jp/library/5c43a166-9c33-403d-ad45-66c51e1897f3(v=TechNet.10))
-   

[](#mainsection)[ページのトップへ](#mainsection)
