---
TOCTitle: 'MS07-MAR'
Title: 2007 年 3 月のセキュリティ情報
ms:assetid: 'ms07-mar'
ms:contentKeyID: 61229641
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms07-mar(v=Security.10)'
---

 

2007 年 3 月のセキュリティ情報
==============================

公開日: 2007年3月14日

**バージョン:** 1.0

**セキュリティセントラル:** マイクロソフトは、以下のサイトにてご使用のコンピュータを守るための情報をご案内しています。

-   ホームユーザーのお客様は、[個人ユーザー向けセキュリティ](http://www.microsoft.com/japan/athome/security/default.mspx)のサイトをご覧ください。「最新のセキュリティ更新プログラムを入手する」をクリックすることでこの情報をご覧いただけます。
-   IT プロフェッショナルのお客様は、[TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)をご覧ください。

**セキュリティ更新プログラム管理:** [パッチ管理のためのセキュリティ ガイダンス](http://technet.microsoft.com/ja-jp/library/dd433786.aspx) では、セキュリティの更新プログラムを展開するための推奨事項を紹介しています。

**マイクロソフトプロダクトセキュリティ警告サービス:** セキュリティ情報を公開したことをメールでお知らせします。 購読方法は、[マイクロソフト プロダクト セキュリティ 警告サービス 日本語版](http://technet.microsoft.com/ja-jp/security/dd252948.aspx) をご覧ください。

**マイクロソフトセキュリティニュースレター:** セキュリティに関する技術文書をメールでお知らせしています。 購読方法は、[マイクロソフト セキュリティ ニュースレター 日本語版](http://technet.microsoft.com/ja-jp/security/cc307424.aspx) をご覧ください。

### セキュリティ更新プログラム

[事前通知](http://technet.microsoft.com/security/bulletin/advance)でお伝えしたとおり、月例の公開日である 2007 年 3 月 14 日に、セキュリティ情報は公開していません。

※ 事前通知は、無料のニュースレター「[セキュリティ警告サービス](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)」に登録すると電子メールで受け取ることができます。

展開
----

 
**Software Update Services:**

Microsoft Software Update Services (SUS) により、管理者は最新の優先度の高い更新プログラムやセキュリティ更新プログラムを Windows 2000 や Windows Server 2003 ベースのサーバー、ならびに Windows 2000 Professional や Windows XP Professional を実行するデスクトップ コンピュータへ迅速かつ確実に配布することができます。

SUS を使用してセキュリティ更新プログラムを配布する方法に関するより詳細な情報は [Software Update Services](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/previous/default.mspx) をご覧下さい。

**Windows Server Update Services:**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003、および SQL Server 2000 用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server:**

Microsoft System Management Server (SMS) は、更新プログラムを管理するための構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンタープライズ全体で、エンド ユーザーへの中断を最小限にして、これらの更新プログラムの制御された適用を実行することができます。セキュリティ更新プログラムを適用するための SMS 2003 の使用方法に関する詳細情報は、[SMS 2003 セキュリティ パッチ管理](http://www.microsoft.com/japan/smserver/evaluation/tips.mspx) をご覧下さい。SMS 2.0 ユーザーもまた、[Software Updates Service Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/suspack/) を活用して、セキュリティ更新プログラムの適用を支援することができます。SMS に関する情報は、[SMS Web サイト](http://www.microsoft.com/japan/smserver/default.mspx)をご覧ください。

**注意** **:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。このような場合、管理者は特定のコンピュータへの更新プログラムを対象とし、SMS のインベントリ機能を使用することができます。この手順に関する詳細情報は、[こちらの Web サイト](http://www.microsoft.com/technet/prodtechnol/sms/sms2003/patchupdate.mspx)(英語情報) をご覧下さい。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。このような場合、管理者は Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/2003/adminpack.asp) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能です) を使用してこれらの更新プログラムのインストールを行うことができます。

**Microsoft Baseline Security Analyzer:**

Microsoft Baseline Security Analyzer (MBSA) は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA に関するより詳細な情報は [Microsoft Baseline Security Analyzer Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx) をご覧ください｡

**検出および適用のガイダンス:**

マイクロソフトは今月のセキュリティ更新プログラムのための検出および適用のガイダンスを提供します。このガイダンスは、IT Pro の方達がセセキュリティ更新プログラムを適用するのに役立つ Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) のようなさまざまなツールの使用方法を理解する手助けとなります。詳細情報については、[サポート技術情報 910723](http://support.microsoft.com/kb/910723)をご覧ください。

#### 関連情報 :

**悪意のあるソフトウェアの削除ツール:**

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

Software Update Services (SUS) を使用してこのツールを配布することは**出来ない**ことにご注意ください。

**MU、WU、WSUS** **および** **SUS** **でのセキュリティ以外の優先度の高い更新プログラム** **:**

-   マイクロソフトは Windows Update (WU)、および Software Update Services (SUS) で、**セキュリティ以外**の優先度の高い 2 件の更新プログラムを公開しました。
-   マイクロソフトは Microsoft Update (MU) および Windows Server Update Services (WSUS) で、**セキュリティ以外**の優先度の高い 4 件の更新プログラムを公開しました。

この情報は、セキュリティ情報のサマリと同日に公開された Microsoft Update、Windows Update、Windows Server Update Services、および Software Update Services で公開された**セキュリティ以外**の優先度の高い更新プログラムに関する情報であることにご注意ください。これ以外の日に公開された、**セキュリティ以外**の優先度の高い更新プログラムに関する情報を提供する予定はありません。

**他のセキュリティ更新プログラムの入手方法:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security_patch)からダウンロードすることができます。「security\_patch」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ プラットフォーム用の更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate/) Web サイトからダウンロードできます。

**サポート** **:**

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は[こちら](http://support.microsoft.com/select/?target=assistance)をご覧ください。
-   製品のサポート期間の詳細は、[マイクロソフト サポート ライフサイクル Web サイト](http://www.microsoft.com/lifecycle)をご参照ください。製品別情報の詳細は、同様にマイクロソフト サポート ライフサイクル Web サイトの[製品を探す](http://support.microsoft.com/default.aspx?scid=fh;ja;complifeport)からご確認ください。

**その他のセキュリティ情報** **:**

-   [Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、マイクロソフト製品のセキュリティに関するさらなる情報を提供しています。
-   [Microsoft Software Update Services](http://www.microsoft.com/japan/sus/)
-   [Microsoft Windows Server Update Services](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx)
-   [Microsoft Baseline Security Analyzer](http://technet.microsoft.com/ja-jp/security/cc184924.aspx) : MBSA ツールのセキュリティ更新プログラムの検出に関する制限は、サポート技術情報 [306460](http://support.microsoft.com/kb/306460) をご覧下さい。
-   [Microsoft Update](http://update.microsoft.com/microsoftupdate)
-   [Windows Update](http://windowsupdate.microsoft.com/)
-   Windows Update カタログの使い方については、サポート技術情報 [323166](http://support.microsoft.com/kb/323166/) をご覧ください｡
-   [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)

**免責** **:**

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。（Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

**更新履歴** **:**

-   2007/3/14 : このセキュリティ情報ページを公開しました｡

*Built at 2014-04-18T01:50:00Z-07:00*
