---
TOCTitle: 'Microsoft Baseline Security Analyzer V1.2.1'
Title: 'Microsoft Baseline Security Analyzer V1.2.1'
ms:assetid: '73640d31-5179-4ea4-b224-45e62b9b552f'
ms:contentKeyID: 19869299
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277352(v=TechNet.10)'
---

Microsoft Baseline Security Analyzer V1.2.1
===========================================

公開日: 2004年1月20日 | 最終更新日: 2005年7月4日

**Windows XP Service Pack 2** **互換の新バージョン** **MBSA 1.2.1**: Windows XP Service Pack 2 のユーザーは SP2 のセキュリティの向上点との互換性のため、MBSA をバージョン 1.2.1 に更新する必要があります。MBSA 1.2 を実行している Windows XP SP2 ユーザーは、インターネット接続で \[スタート\] メニューからツールを実行している場合に、自動的に通知されます。MBSA はマイクロソフトのプラットフォームのための無償の脆弱性評価ツールです。これは IT プロフェッショナル向けにデザインされたツールで、全体のセキュリティ管理戦略の評価段階の手助けとなります。MBSA バージョン 1.2.1 には、Windows システムのローカル スキャンまたはリモート スキャンを行うことができるグラフィカル インターフェイスおよびコマンドライン インターフェイスが含まれます。

MBSA は、Windows 2000、Windows XP および Windows Server 2003 システム上で実行されます。MBSA は Windows NT 4.0、Windows 2000、Windows XP、Windows Server 2003、Internet Information Server (IIS) 、SQL Server、Internet Explorer (IE) および、Office の一般的なセキュリティ設定をスキャンします。MBSA はまた、Windows NT 4.0、Windows 2000、Windows XP、Windows Server 2003、IIS、SQL Server、Internet Explorer、Office、Exchange Server、Windows Media Player、Microsoft Data Access Components (MDAC)、MSXML、Microsoft 仮想マシン、Commerce Server、Content Management Server、BizTalk Server、Host Integration Server のバージョンに必要なセキュリティ修正プログラムの適用状況もスキャンします。

##### トピック

[](#egaa)[ダウンロード サイト](#egaa)  
[](#efaa)[MBSA バージョン 1.2.1 の新しい向上点](#efaa)  
[](#eeaa)[よく寄せられる質問 (FAQ)](#eeaa)  
[](#edaa)[MBSA とスクリプト](#edaa)  
[](#ecaa)[SMS 2003 Software Update Scanning Toolsをお使いの場合](#ecaa)  
[](#ebaa)[SMS 2.0 Software Update Services Feature Pack をお使いの場合](#ebaa)  
[](#eaaa)[その他のリソース](#eaaa)

### ダウンロード サイト

以下のバージョンの MBSA を以下のサイトからダウンロードすることができます。  
日本語: [http://download.microsoft.com/download/c/8/2/c823a585-f5dc-4947-9d92-72652bcd2576/MBSASetup-JA.msi](http://download.microsoft.com/download/c/8/2/c823a585-f5dc-4947-9d92-72652bcd2576/mbsasetup-ja.msi)  
英語 : [http://download.microsoft.com/download/9/0/7/90769f0c-c025-48bf-a9c7-60072d0cb717/MBSASetup-EN.msi](http://download.microsoft.com/download/9/0/7/90769f0c-c025-48bf-a9c7-60072d0cb717/mbsasetup-en.msi)  
フランス語 : [http://download.microsoft.com/download/9/5/9/959a3e95-2d0f-46ac-8418-ec057d1b3bc1/MBSASetup-FR.msi](http://download.microsoft.com/download/9/5/9/959a3e95-2d0f-46ac-8418-ec057d1b3bc1/mbsasetup-fr.msi)  
ドイツ語 : [http://download.microsoft.com/download/0/3/1/0313a008-9dbd-4cb1-ac4d-47bec92bbebd/MBSASetup-DE.msi](http://download.microsoft.com/download/0/3/1/0313a008-9dbd-4cb1-ac4d-47bec92bbebd/mbsasetup-de.msi)  

インストールをすぐに開始するには、\[このプログラムを現在の場所から実行する\] を選択してください。後でインストールをする場合、または、ダウンロードしたファイルをコンピュータにコピーするには、\[このプログラムをディスクに保存する\] を選択してください。

#### ダウンロードに関する注意

このツールを実行する前に readme.html ファイルをご覧ください。readme.html ファイルにはシステム要件、スキャン オプション、ツール サポート オプションに関する重要な情報が含まれています。

[](#mainsection)[ページのトップへ](#mainsection)

### MBSA バージョン 1.2.1 の新しい向上点

MBSA 1.2.1 には、1.2 の優れたスキャン機能がすべて含まれており、さらに次の追加機能が追加されました。

-   Windows XP Service Pack 2 のセキュリティの向上点のサポート

-   更新プログラムおよび必要なアクションを確認するための明確なガイダンス

-   各スコアについてサマリ カウントを表示することによる、さらに容易な結果の優先順位付け

MBSA V1.2 では、以下の新たな機能が利用可能となり、それらの機能に関しては、[MBSA ホワイト ペーパー](https://technet.microsoft.com/ja-jp/library/179eb54a-cd69-44e7-bbad-a3fad47b2465(v=TechNet.10))にて詳細な説明がされています。

#### ローカライズ :

今回の MBSA のリリースでは、日本語、ドイツ語、フランス語にて利用可能です。

#### サポート製品の追加 :

MBSA では、以下の製品のセキュリティ修正プログラムのスキャンを行うことができます。

-   Microsoft Office (ローカル スキャンのみ。製品リストを参照ください。)

-   Exchange Server 2003

-   Microsoft Data Access Components (MDAC) 2.5、2.6、2.7 および 2.8

-   Microsoft 仮想マシン

-   MSXML 2.5、2.6、3.0 および 4.0

-   BizTalk Server 2000、2002 および 2004

-   Commerce Server 2000 および 2002

-   Content Management Server (CMS) 2001 および 2002

-   Host Integration Server (HIS) 2000、2004 および SNA Server 4.0

代替ファイルのバージョンをサポート （セキュリティ修正プログラムのスキャンでチェックされるファイル詳細の複数のセットが有効になります）

#### 構成チェックの追加 :

-   インターネット接続ファイアウォール (ICF) の構成チェック

-   自動更新の構成チェック

-   Internet Explorer のゾーンの構成チェック （カスタム Internet Explorer ゾーンの解釈、Windows Server 2003 の Internet Explorer セキュリティ強化の構成のチェック）

-   MBSA ツール のバージョンチェック （MBSA の新バージョンのリリースをチェック）

-   MBSA CLI スイッチのサポートの追加 (-unicode, -nvc)

[](#mainsection)[ページのトップへ](#mainsection)

### よく寄せられる質問 (FAQ)

MBSA および他のマイクロソフト セキュリティ ツールに関してよく寄せられる質問と答えは以下のページをご覧ください。  
[http://www.microsoft.com/japan/technet/security/tools/Tools/mbsa1/qa.mspx](http://www.microsoft.com/japan/technet/security/tools/mbsa1/qa.mspx)

[](#mainsection)[ページのトップへ](#mainsection)

### MBSA とスクリプト

MBSA とスクリプトを組み合わせた活用方法は、以下のページをご覧ください。  
[http://www.microsoft.com/japan/technet/security/tools /Tools/mbsa1/script.mspx](https://technet.microsoft.com/ja-jp/library/6d3b8c34-dd2d-456b-ab3a-a902883d410d(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)

### SMS 2003 Software Update Scanning Toolsをお使いの場合

MBSA 1.2 のデータベースを利用可能な新しいSMS Software Update Scanning Tools に更新していただく必要がございます。詳細は、以下のサイトをご覧下さい。  
[SMS 2003 Software Update Scanning Tools](http://www.microsoft.com/japan/smserver/downloads/2003/featurepacks/suspack/)

[](#mainsection)[ページのトップへ](#mainsection)

### SMS 2.0 Software Update Services Feature Pack をお使いの場合

MBSA 1.2 のデータベースを利用可能な新しいSMS Software Update Services Feature Pack に更新していただく必要がございます。詳細は、以下のサイトをご覧下さい。  
[SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/suspack/)

[](#mainsection)[ページのトップへ](#mainsection)

### その他のリソース

-   詳細 （新機能、スキャン オプション、V1.2 で修正された脆弱性など） は以下のサイトをご覧ください。
    [Microsoft Baseline Security Analyzer (MBSA) 1.2 のリリース](http://support.microsoft.com/?kbid=320454)

-   MBSA に関する技術的ホワイト ペーパーは、以下のサイトからダウンロードすることができます。
    [ホワイト ペーパー : Microsoft Baseline Security Analyzer V1.2](https://technet.microsoft.com/ja-jp/library/179eb54a-cd69-44e7-bbad-a3fad47b2465(v=TechNet.10))

-   Microsoft Baseline Security Analyzer のスキャン結果を、Microsoft Office Visio 2003 ネットワーク図で視覚的に確認することができます。
    [Microsoft Office Visio 2003 Connector for MBSA](http://www.microsoft.com/japan/technet/security/tools/mbsavisio.mspx)

-   [Microsoft Operations Manager 2005 用](http://www.microsoft.com/japan/mom/techinfo/default.mspx) MBSA 管理パックに関する情報 (監視シナリオ、展開手順、操作タスク、参照コンテンツなど) は以下のガイドをご覧ください。
    [Microsoft Baseline Security Analyzer (MBSA) 管理パック ガイド](http://www.microsoft.com/downloads/details.aspx?familyid=57f9a6a3-35a4-40c8-a5f3-9d598f430366&displaylang=ja)

MBSA は Microsoft のために Shavlik Technologies LLC (<http://www.shavlik.com/>) によって開発されました。

[](#mainsection)[ページのトップへ](#mainsection)

##### 関連リンク

-   [Microsoft Office Visio 2003 Connector for MBSA](http://www.microsoft.com/japan/technet/security/tools/mbsavisio.mspx)
-   [SMS 2003 Software Update Scanning Tools](http://www.microsoft.com/japan/smserver/downloads/2003/featurepacks/suspack/)
-   [SMS 2.0 Feature Packs](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/)

[](#mainsection)[ページのトップへ](#mainsection)

##### ダウンロード

MBSA 1.2 用データベースファイル

[![](images/Dd277352.icon_Text(ja-jp,TechNet.10).gif)mssecure\_1041.cab (日本語)](http://go.microsoft.com/fwlink/?linkid=18120)

[![](images/Dd277352.icon_Text(ja-jp,TechNet.10).gif)mssecure\_1033.cab (英語)](http://go.microsoft.com/fwlink/?linkid=18922)

[![](images/Dd277352.icon_Text(ja-jp,TechNet.10).gif)mssecure\_1036.cab (フランス語)](http://go.microsoft.com/fwlink/?linkid=18122)

[![](images/Dd277352.icon_Text(ja-jp,TechNet.10).gif)mssecure\_1031.cab (ドイツ語)](http://go.microsoft.com/fwlink/?linkid=18121)

[](#mainsection)[ページのトップへ](#mainsection)
