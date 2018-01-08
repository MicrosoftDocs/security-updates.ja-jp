---
TOCTitle: 'MS11-JAN'
Title: 2011 年 1 月のセキュリティ情報
ms:assetid: 'ms11-jan'
ms:contentKeyID: 61229686
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-jan(v=Security.10)'
--- 

2011 年 1 月のセキュリティ情報
==============================

公開日: 2011年1月12日 | 最終更新日: 2011年1月12日

**バージョン:** 1.0

[![](../../images/Dn627265.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627265.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS11-001 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms11-001e.mspx)

[MS11-002 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms11-002e.mspx)

このセキュリティ情報は 2011 年 1 月に公開したセキュリティ情報の一覧です。

2011 年 1 月のセキュリティ情報の公開により、2011 年 1 月 7 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 1 月 12 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2011 年 1 月 12 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[1 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454958&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----

 
次の表は今月のセキュリティ情報を深刻度順にまとめたものです。

影響を受けるソフトウェアの詳細は、次の影響を受けるソフトウェアおよびダウンロード先のセクションをご覧ください。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動情報</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-002">MS11-002</a></td>
<td style="border:1px solid black;"><strong>Microsoft Data Access Components の脆弱性により、リモートでコードが実行される (2451910)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Data Access Components に存在する脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-001">MS11-001</a></td>
<td style="border:1px solid black;"><strong>Windows Backup Manager の脆弱性により、リモートでコードが実行される (2478935)</strong><br />
<br />
このセキュリティ更新プログラムは 1 件の Windows Backup Manager に存在する一般に公開された脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたライブラリ ファイルと同じネットワーク ディレクトリにある Windows Backup Manager ファイルを開いた場合、リモートでコードが実行される可能性があります。攻撃が行われるには、ユーザーが信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問し、その場所から正当なファイルを開くことが攻撃者にとっての必要条件となり、これにより、Windows Backup Manager が特別な細工がされたライブラリ ファイルを読み込む可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用の可能性が高いものから順に、次に CVE ID の順に記載しています。セキュリティ情報に記載されている深刻度が緊急または重要の脆弱性のみです。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID                                                 | 脆弱性タイトル                                        | CVE ID                                                                           | Exploitability Index の評価                                                                     | 注意事項                                   |  
|---------------------------------------------------------------------|-------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|--------------------------------------------|  
| [MS11-001](http://technet.microsoft.com/security/bulletin/ms11-001) | Backup Manager の安全でないライブラリのロードの脆弱性 | [CVE-2010-3145](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3145) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | **この脆弱性は一般に公開されていました。** |  
| [MS11-002](http://technet.microsoft.com/security/bulletin/ms11-002) | DSN のオーバーフローの脆弱性                          | [CVE-2011-0026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0026) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | (なし)                                     |  
| [MS11-002](http://technet.microsoft.com/security/bulletin/ms11-002) | ADO レコードのメモリの脆弱性                          | [CVE-2011-0027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0027) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | (なし)                                     |
  
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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-002**](http://technet.microsoft.com/security/bulletin/ms11-002)
</td>
<td style="border:1px solid black;">
[**MS11-001**](http://technet.microsoft.com/security/bulletin/ms11-001)
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
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7951fd7b-6b0a-4168-8519-312a62ff3289)  
(KB2419632)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ce06bfdc-7b0d-4e65-9a13-e009e3a6a9f0)  
(KB2419635)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-002**](http://technet.microsoft.com/security/bulletin/ms11-002)
</td>
<td style="border:1px solid black;">
[**MS11-001**](http://technet.microsoft.com/security/bulletin/ms11-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d451ced7-c9c7-4c41-9d44-8f8929fca390)  
(KB2419635)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3f2c8cfa-819e-4fd9-93ba-b687eb2d46fe)  
(KB2419635)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft Data Access Components 2.8 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8dbcbb91-464b-4eb3-b7e5-afe82febf8d7)  
(KB2419635)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-002**](http://technet.microsoft.com/security/bulletin/ms11-002)
</td>
<td style="border:1px solid black;">
[**MS11-001**](http://technet.microsoft.com/security/bulletin/ms11-001)
</td>
</tr>
<tr>
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=13445e4a-099a-4edd-864e-c44f42940500)  
(KB2419640)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4eeaad20-729c-4594-8853-e4ae55e9d491)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fd6b806e-50d4-4f4d-96e1-7c71fca4c543)  
(KB2419640)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b2839cd0-1958-4a22-9aac-0e0aa8f2b52c)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-002**](http://technet.microsoft.com/security/bulletin/ms11-002)
</td>
<td style="border:1px solid black;">
[**MS11-001**](http://technet.microsoft.com/security/bulletin/ms11-001)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3d0885ac-97b3-46b5-970d-cc810270fba3)\*  
(KB2419640)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f33c57e-343c-4cdb-b667-af18a8779ad2)\*  
(KB2419640)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5ecc8180-6baa-4f4b-a392-4b45a30469fc)  
(KB2419640)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-002**](http://technet.microsoft.com/security/bulletin/ms11-002)
</td>
<td style="border:1px solid black;">
[**MS11-001**](http://technet.microsoft.com/security/bulletin/ms11-001)
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
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3dfd4f1c-e7a5-4686-8d2c-b7a5a53c5333)  
(KB2419640)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cf30e5c0-811b-4ecd-a6b2-874000d25074)  
(KB2419640)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-002**](http://technet.microsoft.com/security/bulletin/ms11-002)
</td>
<td style="border:1px solid black;">
[**MS11-001**](http://technet.microsoft.com/security/bulletin/ms11-001)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cc9bac5a-3eaa-46fb-9ef4-c511b5f57996)\*  
(KB2419640)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Data Access Components 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ba2612ec-ffad-4cd3-85c6-ba07f70a0d24)  
(KB2419640)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**System Center Configuration Manager 2007**

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法に関する詳細情報は、[Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) (英語情報) をご覧ください。Configuration Manager に関する詳細情報は、[System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx) (英語情報) をご覧ください。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

**注:** System Management Server 2003 は、2010 年 1 月 13 日 にメインストリーム サポートを終了します。 詳細情報は、製品ライフサイクルのページをご覧ください。 現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」をご覧ください。

管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細は、[Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英語情報) をご覧ください。 SMS に関する情報は、[Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。 管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。 この手順に関する情報は、[SMS のソフトウェア配布機能を使用してソフトウェア更新プログラムを展開する](http://www.microsoft.com/japan/technet/sms/2003/library/patchupdate.mspx)をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。 管理者は、Elevated Rights Deployment Tool ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) で入手可能) を使用して、これらの更新プログラムをインストールすることができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/): Software Update Services の説明と Windows Server Update Services の内容の変更。すべての Windows のコンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services.](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報): Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

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

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い謝意を表します。

-   MS11-002 で説明している問題を報告してくださった [TippingPoint のゼロデイ イニシアティブ (ZDI)](http://www.zerodayinitiative.com/) に協力している Abdul Aziz Hariri 氏
-   MS11-002 で説明している問題を報告してくださった [TippingPoint のゼロデイ イニシアティブ (ZDI)](http://www.zerodayinitiative.com/) に協力している Peter Vreugdenhil 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2011/1/12: このセキュリティ情報ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
