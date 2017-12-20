---
TOCTitle: 'MS08-JAN'
Title: 2008 年 1 月のセキュリティ情報
ms:assetid: 'ms08-jan'
ms:contentKeyID: 61229650
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms08-jan(v=Security.10)'
---

 

2008 年 1 月のセキュリティ情報
==============================

公開日: 2008年1月4日 | 最終更新日: 2008年1月28日

**バージョン:** 1.2

イラストを交えたセキュリティ情報はこちらをご覧ください。

絵でみるセキュリティ情報
------------------------

 
[MS08-001 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-001e.mspx)

[MS08-002 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-002e.mspx)

このセキュリティ情報は、2008 年 1 月に公開したセキュリティ情報の一覧です。

2008 年 1 月のセキュリティ情報の公開により、2008 年 1 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2008 年 1 月 9 日 午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[1 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357213&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

日本語版の Webcast 情報は 2008 年 1 月 9 日 の午後 (日本時間) に配信予定です。今月よりポッドキャスティング (RSS フィード) 配信を開始致します。 詳細は、 「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

今月のセキュリティ情報を深刻度別に下記に示します。

緊急 (1)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-001                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Windows TCP/IP の脆弱性により、リモートでコードが実行される (941644)](http://technet.microsoft.com/security/bulletin/ms08-001)                                                                                                                                                                                                                                                                                    |
| **概要**                     | この深刻度が「緊急」のセキュリティ更新プログラムは、2 件の非公開で報告された伝送制御プロトコル/インターネット プロトコル (TCP/IP) の処理の脆弱性を解決します。攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                      |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                       |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とします。                                                                                                                                                                                                                                |
| **影響を受けるソフトウェア** | **Windows.** 詳細については、「影響受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                |

重要 (1)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-002                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [LSASS の脆弱性により、ローカルで特権が昇格される (943485)](http://technet.microsoft.com/security/bulletin/ms08-002)                                                                                                                                                                                                                                                                                                                                                                              |
| **概要**                     | この深 刻度「重要」の更新プログラムは非公開で報告された Microsoft Windows Local Security Authority Subsystem Service (LSASS) の脆弱性を解決します。 この脆弱性により、昇格された特権で攻撃者により任意のコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。 攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **脆弱性の影響**             | ローカルの特権の昇格                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とします。                                                                                                                                                                                                                                                                                                               |
| **影響を受けるソフトウェア** | **Windows.** 詳細については、「影響受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                                                                                               |

影響を受けるソフトウェア
------------------------

 
**この表はどのように使用しますか?**

この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが 記載されている場合、脆弱性の深刻度も記載されています。

**注** **:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。

#### 影響を受けるソフトウェア

![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)このマークをクリックして、更新プログラムをダウンロードしてください。

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
詳細
</th>
<th style="border:1px solid black;" >
詳細
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-001**](http://technet.microsoft.com/security/bulletin/ms08-001)
</td>
<td style="border:1px solid black;">
[**MS08-002**](http://technet.microsoft.com/security/bulletin/ms08-002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="3">
Windows 影響を受けるソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
警告 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=980f5457-c7b5-421c-8643-0e57429ec156&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=7956632e-17d9-4876-8340-84fe3e43e5cc&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=0a766242-2342-4fa0-9b66-8953c54a2211&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=6a4cf182-8e36-490e-aefe-edb7b3a0df9c&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=2e8bc7d5-fe81-4ed5-9efa-360738d160ee&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=51fc657b-2b4a-4725-a744-d279e027c4a5&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=12397b47-b18f-4d4d-b8d7-adec8ff310d5&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=19d993f9-06dd-4dc4-b0cc-c59e822eb8fa&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=f19fd790-a4e6-4a8a-8077-d1bbfe37ecca&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=2c2264f7-ebbb-40ab-9dbf-9b4e313665a7&displaylang=ja)
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=0382a195-aa3d-409b-8a79-9fe61588d8a9&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Small Business Server 2003 Service Pack 1、Windows Small Business Server 2003 R2、Windows Small Business Server 2003 R2 Service Pack 2、および Windows Home Server
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=23c0e03a-db66-4618-bce0-af55e5c1b067&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627229.exeIcon(ja-JP,Security.10).gif)](http://www.microsoft.com/downloads/details.aspx?familyid=5f6a37b1-c604-47c9-932f-485db2eda133&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピュータに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、 [TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet Security センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供して います。

コンシューマのお客様は [Security At Home](http://www.microsoft.com/japan/athome/security) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?%20linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の 関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、 Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに 役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer** **および** **Enterprise Update Scan Tool**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。 MBSA の詳細情報については、 [Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**注意:** 2007 年 10 月 9 日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルは更新されていません。この日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルに新しいセキュリティ更新プログラムは追加されていません。また、新しいバージョンの Enterprise Scan Tool はリリースされません。 MBSA の詳細情報については、 [Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) を使用することにより、管理者は Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Windows 2000 およびそれ以降のオペレーティングシステムに対する Exchange Server 2003 および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

System Center Configuration Manager (SCCM) 2007 は更新プログラムの検出に WSUS 3.0 を使用します。SCCM 2007 Software Update Management に関する詳細については、[System Center Configuration Manager 2007 サイト](http://www.microsoft.com/japan/systemcenter/configmgr/default.mspx)をご覧ください。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、 管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新 プログラムの適用を管理することができます。SMS の次期製品である System Center Configuration Manager 2007 が発売されました。[System Center Configuration Manager 2007 サイト](http://www.microsoft.com/japan/systemcenter/configmgr/default.mspx)をご覧ください。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用の お客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供さ れた更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコン ピュータへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

今月:

-   マイクロソフトは Microsoft Update (MU) および Windows Server Update Services (WSUS) により、**セキュリティ以外** の優先度の高い更新プログラムを 5 件公開しました。
-   マイクロソフトは Windows Update (WU) で、Windows 用の**セキュリティ以外**の優先度の高い更新プログラムを 2 件公開しました。

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。そのほかの日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プ ログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [Microsoft ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)か らダウンロードすることができます。「security update」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード セ ンターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) を ご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてそのほかの IT プロフェッショナルとの情報交換を 行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS08-001 に説明されている問題について報告してくださった [IBM Internet Security Systems X-Force](http://www.iss.net/)の Alex Wheeler 氏および Ryan Smith 氏
-   MS08-002 に説明されている問題について報告してくださった [SkyRecon](http://www.skyrecon.com/) の Thomas Garnier 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原 因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報 の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または 書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連 会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一 切責任を負いません。（Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   2008/01/24: 2008 年 1 月のセキュリティ情報を更新し、Windows Small Business Server 2003 Service Pack 2 をセキュリティ情報 MS08-001 の影響を受けるソフトウェアとして追加しました。
-   2008/01/28: 2008 年 1 月のセキュリティ情報を更新し、Windows Small Business Server 2003 Service Pack 1、Windows Small Business Server 2003 R2、Windows Small Business Server 2003 R2 Service Pack 2、および Windows Home Server をセキュリティ情報 MS08-001 の影響を受けるソフトウェアとして追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
