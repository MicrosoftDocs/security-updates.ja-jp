---
TOCTitle: 'MS09-JAN'
Title: 2009 年 1 月のセキュリティ情報
ms:assetid: 'ms09-jan'
ms:contentKeyID: 61229662
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-jan(v=Security.10)'
--- Summary

2009 年 1 月のセキュリティ情報
==============================

公開日: 2009年1月14日 | 最終更新日: 2009年1月14日

**バージョン:** 1.0

絵でみるセキュリティ情報
------------------------


[MS09-001 : Winodws の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-001e.mspx)

このセキュリティ情報は 2009 年 1 月に公開したセキュリティ情報の一覧です。

2009 年 1 月のセキュリティ情報の公開により、2009 年 1 月 9 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 1 月 14 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 1 月 14 日 午前 11 ：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[1 月のセキュリティ 情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395120&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----


 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID 番号</th>
<th style="border:1px solid black;" >タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動情報</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-001">MS09-001</a></td>
<td style="border:1px solid black;"><strong>SMB の脆弱性により、リモートでコードが実行される (958687)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Server Message Block (SMB) プロトコルに存在する非公開で報告された 2 つの脆弱性と公開されている 1 つの脆弱性を解決します。これらの脆弱性により、影響を受けるコンピューターでリモートでコードが実行される可能性があります。これらの脆弱性で、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部から行われる攻撃を防ぎネットワークを保護することができます。インターネットに接続したコンピューターでは、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  

**この表はどのように使用しますか?**  
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細情報は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報番号                                                | セキュリティ情報タイトル                                  | CVE ID                                                                       | Exploitability Index の評価                                                                     | 注意事項                                                                                                                                                                                                                                                                                                                                           |  
|---------------------------------------------------------------------|-----------------------------------------------------------|------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | SMB の脆弱性により、リモートでコードが実行される (958687) | [CVE-2008-4114](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4114) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | この脆弱性を悪用して、リモートでコードを実行することはできません。一般に公開された検証用コードが存在し、この脆弱性を悪用してリモートでサービス拒否を引き起こします。                                                                                                                                                                               |  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | SMB の脆弱性により、リモートでコードが実行される (958687) | [CVE-2008-4834](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4834) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これはリモートでコードが実行される脆弱性ですが、悪用コードが機能する可能性は低いと思われます。詳細は、Microsoft Security Vulnerability Research & Defense ブログ[優先的な SMB のセキュリティ情報の適用](http://blogs.technet.com/srd/archive/2009/01/09/ms09-001-prioritizing-the-deployment-of-the-smb-bulletin.aspx) (英語情報) をご覧ください。 |  
| [MS09-001](http://technet.microsoft.com/security/bulletin/ms09-001) | SMB の脆弱性により、リモートでコードが実行される (958687) | [CVE-2008-4835](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4835) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これはリモートでコードが実行される脆弱性ですが、悪用コードが機能する可能性は低いと思われます。詳細は、Microsoft Security Vulnerability Research & Defense ブログ[優先的な SMB のセキュリティ情報の適用](http://blogs.technet.com/srd/archive/2009/01/09/ms09-001-prioritizing-the-deployment-of-the-smb-bulletin.aspx) (英語情報) をご覧ください。 |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  

**この表はどのように使用しますか?**  
  
この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、脆弱性の深刻度も記載されています。
  
**注:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=e0678d14-c1b5-457a-8222-8e7682760ed4&displaylang=ja)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=eeafcdc5-df39-4b29-b6f1-7d32b64761e1&displaylang=ja)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=26898401-f669-4542-ad93-199ed1fe9a2a&displaylang=ja)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=588ca8e8-38a9-47ed-9c41-09aaf1022e49&displaylang=ja)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ee59441c-1e8f-4425-ae8d-dec14e7f13fb&displaylang=ja)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=caec9321-fa5b-42f0-9f26-61f673fe6eef&displaylang=ja)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista および Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=9179c463-c10a-452a-990f-b7e37cdd889b&displaylang=ja)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6b26952e-b59d-4b0f-a52d-025e45ecd233&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-001**](http://technet.microsoft.com/security/bulletin/ms09-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=7245b411-7c9e-41e5-9841-4c586336086c&displaylang=ja)\*  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=a241eaad-95a0-442b-978f-f21a6f0c7db4&displaylang=ja)\*  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=ab7c7015-20bb-4a0c-977a-969f4e2a5189&displaylang=ja)  
(警告)
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008** **に関する注意**

**\*Windows Server 2008 Server Core** **インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度でこの更新プログラムが適用されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 の特定のエディションには適用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

検出および展開ツールとガイダンス
--------------------------------


**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/en-us) (英語情報) のコンテンツでは、Software Update Services (SUS) および Windows Server Update Services (WSUS) の情報が変更されました。すべての Windows のコンテンツが含まれます
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS09-001 で説明している問題を報告してくださった [Tipping Point](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している匿名のリサーチャー
-   MS09-001 で説明している別の問題を報告してくださった [Tipping Point](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している匿名のリサーチャー

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/01/14: このセキュリティ情報ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
