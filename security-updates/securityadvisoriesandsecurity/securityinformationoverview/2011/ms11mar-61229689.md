---
TOCTitle: 'MS11-MAR'
Title: 2011 年 3 月のセキュリティ情報
ms:assetid: 'ms11-mar'
ms:contentKeyID: 61229689
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-mar(v=Security.10)'
--- Summary

2011 年 3 月のセキュリティ情報
==============================

公開日: 2011年3月9日 | 最終更新日: 2011年3月17日

**バージョン:** 1.0

[![](../../images/Dn627268.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627268.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS11-015 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms11-015e.mspx)

[MS11-016 : Groove の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms11-016e.mspx)

[MS11-017 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms11-017e.mspx)

このセキュリティ情報は 2011 年 3 月に公開したセキュリティ情報の一覧です。

2011 年 3 月のセキュリティ情報の公開により、2011 年 3 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 3 月 9 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2011 年 3 月 9 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[3 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032455049&eventcategory=4)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-015">MS11-015</a></td>
<td style="border:1px solid black;"><strong>Windows Media の脆弱性により、リモートでコードが実行される (2510030)</strong><br />
<br />
このセキュリティ更新プログラムは DirectShow に存在する 1 件の一般で公開された脆弱性および Windows Media Player と Windows Media Center に存在する非公開で報告された 1 件の脆弱性を解決します。この脆弱性で最も深刻な場合は、特別に細工された Microsoft Digital Video Recording (.dvr-ms) ファイルをユーザーが開いた際に、リモートでコードが実行される可能性があります。すべての場合において、ユーザーに強制的にファイルを開かせることはできません。攻撃を成功させるためには、ユーザーを誘導してファイルを開かせる必要があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-017">MS11-017</a></td>
<td style="border:1px solid black;"><strong>リモート デスクトップ クライアントの脆弱性により、リモートでコードが実行される (2508062)</strong><br />
<br />
このセキュリティ更新プログラムは、一般に公開された 1 件の Windows リモート デスクトップ クライアントの脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたライブラリ ファイルと同じネットワーク フォルダーにある正当なリモート デスクトップ構成 (.rdp) ファイルを開いた場合、リモートでコードが実行される可能性があります。攻撃は、ユーザーが信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問して、この場所から影響を受けるアプリケーションでロードされるドキュメントを開いた場合に実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-016">MS11-016</a></td>
<td style="border:1px solid black;"><strong>Microsoft Groove の脆弱性により、リモートでコードが実行される (2494047)</strong><br />
<br />
このセキュリティ更新プログラムは、ユーザーが特別に細工されたライブラリ ファイルと同じネットワーク ライブラリにある正当な Groove に関連するファイルを開いた場合に、リモートでコードが実行される可能性のある、一般で公開された １ 件の Microsoft Groove の脆弱性を解決します。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用の可能性が高いものから順に、次に CVE ID の順に記載しています。セキュリティ情報に記載されている深刻度が緊急または重要の脆弱性のみです。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID                                                 | 脆弱性タイトル                                              | CVE ID                                                                           | Exploitability Index の評価                                                                     | 注意事項                                                                     |  
|---------------------------------------------------------------------|-------------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|  
| [MS11-017](http://technet.microsoft.com/security/bulletin/ms11-017) | リモート デスクトップの安全でないライブラリのロードの脆弱性 | [CVE-2011-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0029) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | **この脆弱性は一般に公開されています。**                                     |  
| [MS11-015](http://technet.microsoft.com/security/bulletin/ms11-015) | DirectShow の安全でないライブラリのロードの脆弱性           | [CVE-2011-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0032) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | **この脆弱性は一般に公開されており、PoC コードが存在する可能性があります。** |  
| [MS11-015](http://technet.microsoft.com/security/bulletin/ms11-015) | DVR-MS の脆弱性                                             | [CVE-2011-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0042) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | (なし)                                                                       |  
| [MS11-016](http://technet.microsoft.com/security/bulletin/ms11-016) | Microsoft Groove の安全でないライブラリのロードの脆弱性     | [CVE-2011-3146](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3146) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性 | **この脆弱性は一般に公開されており、PoC コードが存在する可能性があります。** |
  
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
[**MS11-015**](http://technet.microsoft.com/security/bulletin/ms11-015)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://technet.microsoft.com/security/bulletin/ms11-017)
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
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d8284bfa-ed6c-4647-9fb0-588e53173775)  
(KB2479943)  
(緊急)  
[Windows XP Media Center Edition 2005 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b1be30de-7e88-467d-aee2-68f88e6a7355)  
(KB2502898)  
(緊急)
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 5.2 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1aed6080-feab-4b5e-9d26-6a3f4b92434d)  
(KB2483618)  
(重要)  
[リモート デスクトップ接続 6.1 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d67e4d8c-aeb9-45e6-9555-7456c5540475)  
(KB2481109)  
(重要)  
[リモート デスクトップ接続 7.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6a01992e-c9a1-4dc9-a3ef-7410b81f17e6)  
(KB2483614)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5270b5d3-3720-42a2-a8cf-67089c0cc658)  
(KB2479943)  
(緊急)
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 6.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6d4539ef-4a05-4c7d-9489-436f7b7a3ebe) <sup>[1]</sup>
(KB2481109)  
(重要)
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
[**MS11-015**](http://technet.microsoft.com/security/bulletin/ms11-015)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://technet.microsoft.com/security/bulletin/ms11-017)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 6.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=641d5d12-0790-4551-831a-e78febad17a7) <sup>[1]</sup>
(KB2481109)  
(重要)  
[リモート デスクトップ接続 6.0 クライアント 複数言語ユーザー インターフェイス (MUI)](http://www.microsoft.com/downloads/details.aspx?displaylang=us&familyid=6fec0d06-042d-4e55-9843-009edd7d26ce)<sup>[2]</sup>
(KB2483619)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 6.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=78dbb9cf-8a18-4f0a-8edf-f1ce0c993c63) <sup>[1]</sup>
(KB2481109)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-015**](http://technet.microsoft.com/security/bulletin/ms11-015)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://technet.microsoft.com/security/bulletin/ms11-017)
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
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f9f1dde2-2219-4bf1-a497-edd011577b96) <sup>[1]</sup>
(KB2479943)  
(緊急)  
[Windows Vista 用の Windows Media Center TV Pack (32 ビット版](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1bc240b3-1938-4350-b26f-67b81a79f8a0))<sup>[2]</sup>
(KB2494132)  
(緊急)
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 6.1 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e3ea7690-386b-4cdf-889f-b3914921c56f)  
(KB2481109)  
(重要)  
[リモート デスクトップ接続 7.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3c30f67e-7c31-4553-ba3e-e056df1bf8eb)  
(KB2483614)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e11d00df-d1cf-4a33-a1be-6721cdff5995) <sup>[1]</sup>
(KB2479943)  
(緊急)  
[Windows Vista 用の Windows Media Center TV Pack (64 ビット版](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cd4c5a80-db24-4696-a248-1286c3b9f550))<sup>[2]</sup>
(KB2494132)  
(緊急)
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 6.1 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5735bed6-0e3d-46a4-85d0-14ec34a82edd)  
(KB2481109)  
(重要)  
[リモート デスクトップ接続 7.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8025482b-f58f-4f5a-a133-5563c65b21f6)  
(KB2483614)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-015**](http://technet.microsoft.com/security/bulletin/ms11-015)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://technet.microsoft.com/security/bulletin/ms11-017)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 6.1 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=31d790c9-92f9-4a2b-800b-8e8d2b570bb9)\*\*  
(KB2481109)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 6.1 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5b0a8eb5-4bc2-4054-b952-58aa645afcf5)\*\*  
(KB2481109)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 6.1 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=25da7e00-745d-4d98-9dd8-52a8a4340404)  
(KB2481109)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-015**](http://technet.microsoft.com/security/bulletin/ms11-015)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://technet.microsoft.com/security/bulletin/ms11-017)
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
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1be77daa-29b1-4dae-a87f-2cb8f7e6a305)  
(KB2479943)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems のみ:  
[リモート デスクトップ接続 7.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0768a5f4-da28-4b2e-8aff-d68f890df3e6)  
(KB2483614)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=56fb24ce-65c7-4573-b613-e424ccc1a3a6)  
(KB2479943)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems のみ:  
[リモート デスクトップ接続 7.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=935adb10-1e7e-4501-b543-8247b88f6d18)  
(KB2483614)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-015**](http://technet.microsoft.com/security/bulletin/ms11-015)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://technet.microsoft.com/security/bulletin/ms11-017)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6f45658a-1db8-4ef5-b840-4d0180d4d90e)\*\*  
(KB2479943)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:  
[リモート デスクトップ接続 7.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3fcb2e11-591e-484a-a992-2f1d563e6d17)\*\*  
(KB2483614)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[リモート デスクトップ接続 7.0 クライアント](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c29b6487-78f0-421c-810c-c5e45d6a2352)  
(KB2483614)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*\*Server Core インストールは影響を受けません。**この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用してインストールした場合、サポートされているエディションの Windows Server 2008 および Windows Server 2008 R2 に影響を与えません。このインストール オプションに関する詳細情報は MSDN コラム [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx) をご覧ください。

**MS11-015 のセキュリティ情報に関する注意**

<sup>[1]</sup> Windows Vista 用の Windows Media Center TV Pack については、下記の <sup>[2]</sup> をご覧ください。

<sup>[2]</sup> Windows Vista 用の Windows Media Center TV Pack は Original Equipment Manufacturer (OEM) のインストールの Windows Vista の Home Premium および Ultimate エディションでのみ、オプションのコンポーネントとして利用可能です。このオプション コンポーネントをシステムにインストールしているお客様は、両方の利用可能な更新プログラムをインストールする必要があります。最善策として、マイクロソフトはオペレーティング システムの更新プログラム (KB2479943) をインストールしてから、Media Center TV Pack の更新プログラム (KB2494132) をインストールすることを推奨します。

**MS11-017 のセキュリティ情報に関する注意**

<sup>[1]</sup> このダウンロードはリモート デスクトップ接続 6.0 クライアントを影響を受けないバージョンのリモート デスクトップ接続 6.1 クライアントにアップグレードします。

<sup>[2]</sup> このダウンロードはリモート デスクトップ接続 6.0 クライアント複数言語ユーザー インターフェイス (MUI) を影響を受けないバージョンのリモート デスクトップ接続 6.1 クライアント複数言語ユーザー インターフェイス (MUI) にアップグレードします。

#### Microsoft Office スイートおよびソフトウェア

 
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
Microsoft Office プログラム
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS11-016**](http://technet.microsoft.com/security/bulletin/ms11-016)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove 2007
</td>
<td style="border:1px solid black;">
[Microsoft Groove 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3981ab53-1082-4155-9000-11d8a976ff33)  
(KB2494047)  
(重要)
</td>
</tr>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。 Microsoft AutoUpdate for Mac のご利用に関する詳細は、[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)をご覧ください。

最後に、セキュリティ更新プログラムは [Microsoft Update カタログ](http://catalog.update.microsoft.com/v7/site/install.aspx) からダウンロードできます。[Microsoft Update カタログ](http://catalog.update.microsoft.com/v7/site/install.aspx) は、セキュリティ更新プログラム、ドライバーおよびサービスパックなどを含むコンテンツを検索可能なカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ番号 (例えば “MS07-036” など) を使用して検索することにより、バスケットに適用可能な更新プログラムをすべて追加することができ (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の関連情報を参照するには、[Microsoft Update カタログ よく寄せられる質問](http://http://catalog.update.microsoft.com/v7/site/install.aspx)をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/): Software Update Services の説明と Windows Server Update Services 2010 の内容の変更。すべての Windows のコンテンツが含まれます。
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

-   MS11-015 で説明している問題を報告してくださった [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html) の Matthew Watchinski 氏
-   MS11-016 で説明している問題を報告してくださった [Rapid7](http://www.rapid7.com/) の HD Moore 氏
-   MS11-017 で説明している問題を報告してくださった [Versafe Anti Fraud](http://www.versafe-login.com/) の Eyal Gruner 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2011/3/9: このセキュリティ情報ページを公開しました。
-   2011/3/17: 「影響を受けるソフトウェアおよびダウンロード先」表の MS11-015 のセキュリティ情報に関する注意で、Windows XP Home Edition Service Pack 3 および Windows XP Tablet PC Edition Service Pack 3 は影響を受けないという誤った表記を削除しました。今回の更新は情報のみの変更です。このセキュリティ情報のセキュリティ更新プログラムのファイルおよび検出ロジックへの変更はありません。これらのエディションの Windows XP をお使いのお客様で、まだこのセキュリティ更新プログラムを適用されていない場合、直ちに適用されることを推奨します。このセキュリティ更新プログラムを既に適用されているお客様は、特に対策を行う必要はありません。

*Built at 2014-04-18T01:50:00Z-07:00*
