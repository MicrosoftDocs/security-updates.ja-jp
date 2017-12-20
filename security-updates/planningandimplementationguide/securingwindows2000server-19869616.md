---
TOCTitle: 'マイクロソフトの Securing Windows 2000 Server ソリューション : 概要'
Title: 'マイクロソフトの Securing Windows 2000 Server ソリューション : 概要'
ms:assetid: '71a89c24-0bfe-4e21-aeac-89ba6f84b06d'
ms:contentKeyID: 19869616
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc723541(v=TechNet.10)'
---

マイクロソフトの Securing Windows 2000 Server ソリューション
============================================================

### 概要

最終更新日: 2004年1月21日

##### ダウンロード

[![](images/Cc723541.icon_Acrobat(ja-jp,TechNet.10).gif)マイクロソフト の Securing Windows 2000 Server ソリューション](http://download.microsoft.com/download/1/e/f/1ef30f30-6ce6-4d4c-8c0e-e813676571be/microsoft_solution_for_securing_windows_2000_server.pdf)
2.53MB
Portable Document file

##### トピック

[](#ecaa)[このドキュメントの構成](#ecaa)

[](#ebaa)[ダウンロード](#ebaa)

Securing Windows 2000 Server ソリューションは、現在および将来において安全でなければならないプロセスおよび意思決定についての理解を高めたりプロセスの実施を助けるための構造化されたガイダンスを通して、信頼性の高いコンピューティングに向けたマイクロソフトのコミットメントを強化するものです。このソリューションは Windows 2000 環境におけるセキュリティの脆弱性を低減し、情報の漏洩やセキュリティ管理にかかる費用を削減するために設計されています。

この詳細なガイドは、リスクの評価および分析、Windows 2000 Server の重要なロールの保護、最初のロックダウン フェーズが完了した後の保護された環境での操作など、Windows 2000 Server 環境を保護するためのライフ サイクル全体に関するアドバイスを提供することに焦点を当てています。

![](images/Cc723541.defau01(ja-jp,TechNet.10).gif)

### このドキュメントの構成

Securing Windows 2000 Server ソリューションは、11 の章と Test Guide、Delivery Guide、および Support Readiness Guide から構成されており、各章には該当するジョブへのサポート、スクリプト ファイル、およびテスト ケースが紹介されています。Securing Windows 2000 Server の 11 章では以下のガイダンスを提供しています。

[**第 1 章 - Securing Windows 2000 Server 入門**](https://technet.microsoft.com/ja-jp/library/18bbfc43-3d1a-4031-bc06-372064ffff72(v=TechNet.10))

最初の章では、Securing Windows 2000 Server ガイドの概要を説明します。

[**第 2 章 - セキュリティの概要を定義する**](https://technet.microsoft.com/ja-jp/library/52d2d069-16f8-4a1f-8fa8-ec6b77571799(v=TechNet.10))

この章では、組織のセキュリティ分析を実行する際に理解すべきセキュリティ コンポーネントの定義に焦点が当てられています。ここでは組織が準備資産分析を実行する方法についての一般的なガイダンスを提供し、脅威、露出、脆弱性、および対策にどのような相互関係があるかについて説明しています。

[**第 3 章 - セキュリティ リスク管理の統制について理解する**](https://technet.microsoft.com/ja-jp/library/81560275-04b7-4e40-8937-699e4b4defea(v=TechNet.10))

この章では、今日使用されている MSF および MOF を活用するセキュリティ分析の手順から、実証済みの方法について説明します。ここではセキュリティ リスク管理規定 (SRMD) が詳細に定義されています。

[**第 4 章 - セキュリティ リスク管理の統制を適用する**](https://technet.microsoft.com/ja-jp/library/07ed8438-6264-4e30-9ca9-2235687e62e7(v=TechNet.10))

特定の組織にとってどのような脅威や脆弱性が最も大きな影響を与える可能性があるかを判断するために、この章全体で SRMD の演習になっています。今日の多くのビジネスと同様のニーズを持つ架空の会社を使って、実際の脆弱性の評価をし、Windows 2000 Server 導入を決定するまでのステップを紹介しています。この章のまとめでは、提起された特定のリスクが詳細に定義、説明、そして分析されています。

[**第 5 章 - ドメイン インフラストラクチャをセキュリティで保護する**](https://technet.microsoft.com/ja-jp/library/83d7ede4-67ea-43d7-93a9-ccff8e5ca4e6(v=TechNet.10))

ドメイン レベルで組織に影響を与える、意思決定の基礎とする条件を決定することがこの章の焦点です。ここでは、Microsoft&reg Active Directory&reg サービスの設計、組織単位 (OU) の設計、さらにドメイン ポリシーについてのハイレベルな概要を提供しています。さらに、このガイドで使用した架空の顧客シナリオで導入された特定のドメイン ポリシーについて、詳細に説明しています。

[**第 6 章 - Base Windows 2000 Server のハードニング**](https://technet.microsoft.com/ja-jp/library/265d2c3d-5af6-4f6e-85ea-d674d4c314a7(v=TechNet.10))

この章では、架空の顧客 シナリオでメンバー サーバーに適用された基本設定について説明しています。たとえば、グループ ポリシーは既定の Windows 2000 Server 構成への変更を何度でも適用するのに使用されています。このシナリオのメンバー サーバーでは、説明されているグループ ポリシーはセキュリティ テンプレートの MSS Baseline.inf に格納されています。この設定を適用するには、このテンプレートをメンバー サーバー OU にリンクされているメンバー サーバー ベースライン ポリシーのグループ ポリシーにインポートします。

[**第 7 章 - 特定サーバーの役割のハードニング**](https://technet.microsoft.com/ja-jp/library/138bac60-132a-4faf-b979-503828583374(v=TechNet.10))

どのような組織のドメイン コントローラ、ファイル サーバー、ネットワーク インフラストラクチャ サーバー、および Web サーバーにも、セキュリティを最大限に確保するためにさまざまな設定が必要です。この章では、ドメイン コントローラおよびその他のプライマリ メンバーのサーバーロールをできる限り確実にするためのステップを紹介しています。

[**第 8 章 - 修正プログラムの管理**](https://technet.microsoft.com/ja-jp/library/c474ed12-f438-4d49-acaa-260df90e5e13(v=TechNet.10))

この章では、必要なすべてのセキュリティ修正プログラムで最新の環境にしておく方法、適切な時期に新しい修正プログラムを迅速かつ確実に導入する方法、さらに修正プログラムの継続的な導入を監視する方法について説明しています。

[**第 9 章 - 監査と侵入検出**](https://technet.microsoft.com/ja-jp/library/f8a8ab2f-f727-459c-aee0-c6a06f7f9fb0(v=TechNet.10))

攻撃を検知する最善の状態を提供するために、どのように環境を監査するかが第 9 章の焦点です。ここでは、攻撃が発生していることを示す動作を検知するために特に設計された、侵入検知システム ソフトウェアについても説明しています。

[**第 10 章 - インシデントへの対応**](https://technet.microsoft.com/ja-jp/library/4baf189b-f762-4c67-a5bc-f438a1274fec(v=TechNet.10))

この章では、インシデントを効果的に報告するために必要なステップや、インシデントへの典型的な対応を示すケース スタディなど、さまざまなタイプの攻撃に対応するための最善の方法が記載されています。

[**第 11 章 - 結論**](https://technet.microsoft.com/ja-jp/library/0deb6d1a-1083-4353-b645-6bdc1cbab83c(v=TechNet.10))

ソリューション ガイドのまとめです。

Microsoft Security Foundation (MSF) および Microsoft Operations Foundation (MOF) の原則に則り、マイクロソフト はセキュリティ リスク管理規定を作成しました。このガイドでは、ステップごとに現存の脅威や脆弱性を特定し、どれが最大の影響をもたらす可能性があるかについて測定します。 これらの総合的な情報および分析テクニックは、Windows 2000 Server の導入にあたっての特定のセキュリティ リスクを評価するために繰り返し使用できます。また、確実な導入のために、特定のサーバーロールや、既知の緩和されたリスクおよび脆弱性に関する推奨事項がステップ バイ ステップで詳細に説明されています。最後に、修正プログラム管理、監査および侵入検知、問題への対応についてのガイダンスが記載されています。

[](#mainsection)[ページのトップへ](#mainsection)

### ダウンロード

-   [ガイド全体をダウンロードする](http://download.microsoft.com/download/1/e/f/1ef30f30-6ce6-4d4c-8c0e-e813676571be/microsoft_solution_for_securing_windows_2000_server.pdf) (PDF ファイル、2.53MB)

-   
-   [ツールとテンプレートをダウンロードする](http://www.microsoft.com/downloads/details.aspx?familyid=9964cf42-e236-4d73-aef4-7b4fdc0a25f6&displaylang=en) (英語版)

-   

[](#mainsection)[ページのトップへ](#mainsection)

### 目次

-   概要
-   
-   [第 1 章 ‐ Securing Windows 2000 Server 入門](https://technet.microsoft.com/ja-jp/library/18bbfc43-3d1a-4031-bc06-372064ffff72(v=TechNet.10))
-   
-   [第 2 章 ‐ セキュリティの概要を定義する](https://technet.microsoft.com/ja-jp/library/52d2d069-16f8-4a1f-8fa8-ec6b77571799(v=TechNet.10))
-   
-   [第 3 章 ‐ セキュリティ リスク管理の統制について理解する](https://technet.microsoft.com/ja-jp/library/81560275-04b7-4e40-8937-699e4b4defea(v=TechNet.10))
-   
-   [第 4 章 ‐ セキュリティ リスク管理の統制を適用する](https://technet.microsoft.com/ja-jp/library/07ed8438-6264-4e30-9ca9-2235687e62e7(v=TechNet.10))
-   
-   [第 5 章 ‐ ドメイン インフラストラクチャをセキュリティで保護する](https://technet.microsoft.com/ja-jp/library/83d7ede4-67ea-43d7-93a9-ccff8e5ca4e6(v=TechNet.10))
-   
-   [第 6 章 ‐ Base Windows 2000 Server のハードニング](https://technet.microsoft.com/ja-jp/library/265d2c3d-5af6-4f6e-85ea-d674d4c314a7(v=TechNet.10))
-   
-   [第 7 章 ‐ 特定サーバーの役割のハードニング](https://technet.microsoft.com/ja-jp/library/138bac60-132a-4faf-b979-503828583374(v=TechNet.10))
-   
-   [第 8 章 ‐ 修正プログラムの管理](https://technet.microsoft.com/ja-jp/library/c474ed12-f438-4d49-acaa-260df90e5e13(v=TechNet.10))
-   
-   [第 9 章 ‐ 監査と侵入検出](https://technet.microsoft.com/ja-jp/library/f8a8ab2f-f727-459c-aee0-c6a06f7f9fb0(v=TechNet.10))
-   
-   [第 10 章 ‐ インシデントへの対応](https://technet.microsoft.com/ja-jp/library/4baf189b-f762-4c67-a5bc-f438a1274fec(v=TechNet.10))
-   
-   [第 11 章 ‐ 結論](https://technet.microsoft.com/ja-jp/library/0deb6d1a-1083-4353-b645-6bdc1cbab83c(v=TechNet.10))
-   
-   [付録 A ‐ Windows 2000 のサービスの用途](https://technet.microsoft.com/ja-jp/library/13468c13-a3f3-4b75-aadf-fec1c40fe801(v=TechNet.10))
-   
-   [付録 B ‐ レジストリのアクセス制御の変更](https://technet.microsoft.com/ja-jp/library/132e1a99-29b0-4f66-956c-d009da62a51d(v=TechNet.10))
-   
-   [付録 C ‐ オプションのファイル システムのアクセス許可](https://technet.microsoft.com/ja-jp/library/af304b67-3190-4a66-b75a-07d8fcd8585d(v=TechNet.10))
-   
-   [付録 D ‐ 信頼されていないネットワーク内にあるサーバーでの NetBIOS の無効化](https://technet.microsoft.com/ja-jp/library/cac85879-5a6d-419c-bb04-09f0a93fb668(v=TechNet.10))
-   
-   [付録 E ‐ セキュリティで保護された LDAP および SMTP 複製を行うためのドメイン コントローラでのデジタル証明書の構成](http://www.microsoft.com/japan/technet/security/prodtech/windows2000/secwin2k/a0701.mspx)
-   

[](#mainsection)[ページのトップへ](#mainsection)
