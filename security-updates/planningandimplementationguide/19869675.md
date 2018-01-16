---
TOCTitle: '新共通基準セキュリティ評価体系 (CCITSE) と Windows 2000 に関する評価'
Title: '新共通基準セキュリティ評価体系 (CCITSE) と Windows 2000 に関する評価'
ms:assetid: 'cb666629-d6e3-4a21-866d-96737cb115f3'
ms:contentKeyID: 19869675
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc723510(v=TechNet.10)'
---

新共通基準セキュリティ評価体系 (CCITSE) と Windows 2000 に関する評価
====================================================================

最終更新日: 2001年4月18日

C2 は、コンピュータ システムに関するセキュリティ評価レベルの 1 つで、NSA (National Security Agency: 国家安全保障局) の NCSC (National Computer Security Center: 国家コンピュータ セキュリティ センター) によって定められました。C2 評価を獲得したコンピュータ システム構成のセキュリティ機能は、米国政府により、機密ではないが取り扱いに注意を要するデータの使用に対して、十分強力で信頼できるものであると判断されました。米国 TCSEC (Trusted Computer Systems Evaluation Criteria: 信用されるコンピュータ システム評価基準)、いわゆる Orange Book が C2 評価の標準を規定しました。イギリスの CESG (Computer and Electronics Security Group: コンピュータおよびエレクトロニクス セキュリティ グループ) も ITSEC (European Information Technology Security Evaluation Criteria: 欧州情報技術セキュリティ評価基準) を利用して製品を評価しました。Windows NT 3.5 および Windows NT 4.0 は、TCSEC と ITSEC の両基準に関する評価を問題なく終了しました (<http://technet.microsoft.com/library/cc767091.aspx> : 英語)。

1998 年後半、米国を含む各国政府は共通基準と呼ばれる新しいセキュリティ評価体系を採用しました。共通基準は TCSEC および ITSEC の両方の処理を置き換えるものです。今後、Windows 2000 とその後継製品は共通基準の下で評価されることになります。この文書は Windows 2000 の評価に関する Microsoft の計画についての背景情報を提供します。

### 共通基準

新しい評価体系は、情報技術セキュリティ評価に関する共通基準 (Common Criteria for Information Technology Security Evaluation:CCITSE) と呼ばれます。共通基準は国際標準であるため、共通基準下にある国の評価機関により発行された評価結果は国際的に認められます。共通基準の下で、製品のクラス (OS など)はセキュリティ機能要求を規定する「保護プロファイル」の要件に対して評価されます。保護プロファイルは、セキュリティ要件を満たすことが期待されるOS、ファイアウォール、スマートカード、および他の製品への適用に向けて開発されることが考えられます。共通基準は、評価対象製品に対して、一連の評価保証レベル (Evaluation Assurance Levels:EAL) を規定します。EAL が高いほど、製品のセキュリティ機能が正しく効率的に動作することの確実性が増します。具体的な共通基準評価活動についての詳細は、[NCSC の Web サイト](http://www.niap-ccevs.org/) (英語) を参照してください。共通基準の公式 Web サイトは、<http://www.commoncriteria.org/> (英語) です。

#### 制御されたアクセスの保護プロファイル

NCSC は、TCSEC C2 要件の代わりとなる、制御されたアクセス保護プロファイル (Controlled Access Protection Profile:CAPP) を開発しました。CAPP は、情報技術 (IT) 製品に対する、一組のセキュリティ機能および保証要求を規定します。CAPP に準拠した製品は、個別のユーザーおよびデータオブジェクト上のアクセス制限を可能にするアクセス制御に対応します。CAPP に準拠した製品は、システム内で発生したセキュリティ関連のイベントを記録する監査機能も提供します。CAPP は、分散 OS (ネットワーク構成) について、CAPP に準拠するかどうかを評価できるように作成されました。CAPP に関する情報は次のサイトから入手できます。[http://www.niap-ccevs.org/cc-scheme/pp/PP\_OS\_CA\_V1.d.pdf](http://www.niap-ccevs.org/cc-scheme/pp/pp_os_ca_v1.d.pdf) (英語)

#### CAPP と C2 の関係

CAPP は TCSEC のクラス C2 の要件から派生したものです。CAPP は TCSEC クラス C2 による要求と同等のセキュリティ機能および保証を記述します。

#### CAPP 準拠システムとしての Windows 2000

Windows 2000 は CAPP 準拠システムに対する要件に適合するように設計されている上、多くの点でより高度な機能をもっています。Microsoft は、ネットワーク OS に関する共通基準の下で Windows 2000 を評価すると表明しています。この評価手法により、Windows 2000 Profesional ベースのワークステーション、Windows 2000 ベースおよび Advanced Server ベースのサーバー、Windows 2000 ベースのドメインコントローラがまとめて評価されることになります。これらのシステムは、Windows 2000 ディレクトリサービス、IPSec サービス、暗号化ファイルシステム (EFS)、修復サービス、およびドメインベースのポリシー管理などの機能を備え、活用します。

#### Windows 2000 CC 評価記録

Windows NT 3.5 および Windows NT 4.0 の C2 評価の中で、評価者は、Microsoft の内部設計仕様と、評価者と Microsoft 開発者との間で行われる臨時の技術的な Q&A に基づいた作業を完了しました。新しい CC 評価過程で、ベンダーは、指定された CC の内容に関する要求を満たす単一のパッケージを作成して、評価記録を提供することが求められます。たとえば、各 Windows 2000 の外部セキュリティ関連インターフェイスは、実装する特定のセキュリティ確認と導入する特定のセキュリティ効果を明記しなければなりません。Microsoft は、Windows 2000 について、CC 準拠の設計仕様および対応するテスト記録を作成するための投資を行っています。Microsoft は、Windows 2000 の後継製品向けにこの CC 準拠記録を維持する意向です。

#### Windows 2000 に関する評価の現状

Microsoftは、現在、評価記録の準備段階にあります。この目的は、共通基準評価要件に適合する記録を生成することです。記録は膨大な量で、EAL4 の共通基準保証要件を満たすために必要な下記の事項から構成されます。

-   セキュリティ関連の Windows 2000 外部インターフェイスに関する設計仕様、および


-   Windows 2000 セキュリティ関連外部インターフェイスの効果に関するテスト報告


Microsoftは、評価記録の大部分が準備できた段階 (2001 年上半期) で、Windows 2000 評価についての正式な提出を行う予定です。

正式な提出の後、独立した評価者が、共通基準評価方法にしたがって、記録の正確性および完成度を調べることになります。米国 NIAP (National Information Assurance Partnership:国家情報保証連合) は評価の監督および承認を行います。[NIAP](http://www.niap-ccevs.org/cc-scheme/getting-product-evaluated.cfm) (英語) は、米国における CC 評価機関です。CC 評価の完了時に作成される最終的な評価技術報告書 (Evaluation Technical Report:ETR) は NIAP に提出されて認定を受けます。

[](#mainsection)[ページのトップへ](#mainsection)
