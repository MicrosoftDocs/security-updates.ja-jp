---
TOCTitle: 'MS10-NOV'
Title: 2010 年 11 月のセキュリティ情報
ms:assetid: 'ms10-nov'
ms:contentKeyID: 61229679
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-nov(v=Security.10)'
--- Summary

2010 年 11 月のセキュリティ情報
===============================

公開日: 2010年11月10日 | 最終更新日: 2011年4月14日

**バージョン:** 1.0

[![](../../images/Dn627258.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627258.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS10-087 : Office の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-087e.mspx)

[MS10-088 : PowerPoint の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-088e.mspx)

[MS10-089 : Forefront Unified Access Gateway (UAG) の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-089e.mspx)

このセキュリティ情報は 2010 年 11 月に公開したセキュリティ情報の一覧です。

2010 年 11 月のセキュリティ情報の公開により、2010 年 11 月 5 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 11 月 10 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2010 年 11 月 10 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[11 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032454441)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-087">MS10-087</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、リモートでコードが実行される (2423930)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Office に存在する 1 件の一般に公開された脆弱性および 5 件の非公開で報告された脆弱性を解決します。これらの脆弱性で最も深刻な場合、特別に細工されたリッチ テキスト形式 (RTF) の電子メール メッセージをユーザーが開く、またはプレビューした場合、リモートでコードが実行される可能性があります。これらの脆弱性が悪用された場合、攻撃者によりローカル ユーザーと同じ権限が取得される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-088">MS10-088</a></td>
<td style="border:1px solid black;"><strong>Microsoft PowerPoint の脆弱性により、リモートでコードが実行される (2293386)</strong><br />
<br />
このセキュリティ更新プログラムは、ユーザーが特別な細工がされた PowerPoint ファイルを開いた場合、リモートでコードが実行される可能性がある非公開で報告された Microsoft PowerPoint に存在する 2 つの脆弱性を解決します。攻撃者がこれらの脆弱性のいずれかを悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-089">MS10-089</a></td>
<td style="border:1px solid black;"><strong>Forefront Unified Access Gateway (UAG) の脆弱性により、特権が昇格される (2316074)</strong><br />
<br />
このセキュリティ更新プログラムは Forefront Unified Access Gateway (UAG) に存在する 4 つの非公開で報告された脆弱性を解決します。これらの中で最も深刻な脆弱性で、ユーザーが特別な細工がされた URL を使用して影響を受ける Web サイトを訪問した場合、特権が昇格される可能性があります。しかし、攻撃者はこのような Web サイトにユーザーを強制的に訪問させることはできません。通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Forefront United Access Gateway</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用の可能性が高いものから順に、次に CVE ID の順に記載しています。セキュリティ情報に記載されている深刻度が緊急または重要の脆弱性のみです。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID                                                 | 脆弱性タイトル                                                                        | CVE ID                                                                           | Exploitability Index の評価                                                                         | 注意事項                                                                                       |  
|---------------------------------------------------------------------|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|  
| [MS10-088](http://technet.microsoft.com/security/bulletin/ms10-088) | PowerPoint の解析のバッファー オーバーフローの脆弱性                                  | [CVE-2010-2572](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2572) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-089](http://technet.microsoft.com/security/bulletin/ms10-089) | UAG XSS の特権の昇格の脆弱性                                                          | [CVE-2010-2733](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2733) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-089](http://technet.microsoft.com/security/bulletin/ms10-089) | Forefront Unified Access Gateway の UAG モバイル ポータル Web サイト上の XSS の脆弱性 | [CVE-2010-2734](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2734) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087) | RTF のスタック バッファ オーバーフローの脆弱性                                        | [CVE-2010-3333](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3333) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087) | Office アートのレコード描画の脆弱性                                                   | [CVE-2010-3334](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3334) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087) | 描画の例外処理の脆弱性                                                                | [CVE-2010-3335](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3335) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087) | セキュリティで保護されていないライブラリのロードの脆弱性- CVE-2010-3337               | [CVE-2010-3337](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3337) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | **この脆弱性は一般に公開されています**                                                         |  
| [MS10-089](http://technet.microsoft.com/security/bulletin/ms10-089) | Signurl.asp の XSS の脆弱性                                                           | [CVE-2010-3936](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3936) | [**1**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087) | PowerPoint の整数アンダーフローのヒープ破損の脆弱性                                   | [CVE-2010-2573](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573) | [**2**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | [MS10-088](http://technet.microsoft.com/security/bulletin/ms10-088) でもこの脆弱性を解決します |  
| [MS10-088](http://technet.microsoft.com/security/bulletin/ms10-088) | PowerPoint の整数アンダーフローのヒープ破損の脆弱性                                   | [CVE-2010-2573](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573) | [**2**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-087](http://technet.microsoft.com/security/bulletin/ms10-087) | MSO のラージ SPID の読み取り AV の脆弱性                                              | [CVE-2010-3336](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3336) | [**2**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                         |  
| [MS10-089](http://technet.microsoft.com/security/bulletin/ms10-089) | UAG のリダイレクトのなりすましの脆弱性                                                | [CVE-2010-2732](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2732) | [**3**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | これはなりすましの脆弱性です                                                                   |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
**この表はどのように使用しますか?**
  
この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、脆弱性の深刻度も記載されています。
  
**注:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Microsoft Office スイートおよびソフトウェア

 
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
Microsoft Office スイートおよびコンポーネント  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://technet.microsoft.com/security/bulletin/ms10-088)
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
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f32648e3-2fb5-472c-932f-360e5d3c0931)  
(KB2289169)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3efbf9f6-734a-46ac-8f92-87b6ec819bfa)  
(KB2413272)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=07a6cf76-2cea-4c54-b66d-50e9eed108ac)  
(KB2289187)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=108286d4-fb68-40d6-a7b1-64b3a4eb87ee)  
(KB2413304)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=be0c5878-60c0-4700-8836-50d369b51d04)  
(KB2289158)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0b308508-0e1e-4e90-b2b8-7e32bfc5dbf4)  
(KB2289161)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=534c6a2a-e7c6-4adf-8b81-e009a2b5fff4)  
(KB2289161)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://technet.microsoft.com/security/bulletin/ms10-088)
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
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac <sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac <sup>[1]</sup>
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ad1b1984-b2b2-49b3-a1dd-385b77d9248a&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8bd6ca3b-8004-4e8d-a09d-220dcbbce799)  
(KB2454823)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=b846d255-a7d4-4a2c-a084-d434c29fe676&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
その他の Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://technet.microsoft.com/security/bulletin/ms10-087)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://technet.microsoft.com/security/bulletin/ms10-088)
</td>
</tr>
<tr>
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=df826b79-7398-45de-943c-6f6f0af1b4e3)  
(KB2413381)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**MS10-087 に関する注意**

<sup>[1]</sup> Microsoft Office 2004 for Mac 用のセキュリティ更新プログラム (KB2505924) は 2011 年 4 月 13 日付けで、利用可能です。詳細は、セキュリティ情報をご覧ください。

**MS10-088 に関する注意**

<sup>[1]</sup> Microsoft Office 2004 for Mac 用のセキュリティ更新プログラム (KB2505924) は 2011 年 4 月 13 日付けで、利用可能です。詳細は、セキュリティ情報をご覧ください。

#### Microsoft リモート アクセス ソフトウェア

 
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
Microsoft Forefront Unified Access Gateway
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-089**](http://technet.microsoft.com/security/bulletin/ms10-089)
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
Microsoft Forefront Unified Access Gateway
</td>
<td style="border:1px solid black;">
[Forefront Unified Access Gateway 2010](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=5f2ee08e-e289-47db-bd3f-7b9cfc1eb985) <sup>[1]</sup>
(KB2433585)  
(重要)  
[Forefront Unified Access Gateway 2010 Update 1](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=db0b70c8-1fa5-4d92-9888-3500c7566b19) <sup>[1]</sup>
(KB2433584)  
(重要)  
[Forefront Unified Access Gateway 2010 Update 2](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=4e3ee07a-771c-46ee-959f-82389bab67d7) <sup>[1]</sup>
(KB2418933)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**MS10-089 に関する注意**

<sup>[1]</sup> この更新プログラムは、マイクロソフト ダウンロード センターでのみ利用可能です。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/) および [Windows Update](http://windowsupdate.microsoft.com/) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update) からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。

最後に、セキュリティ更新プログラムは [Microsoft Update カタログ](http://catalog.update.microsoft.com/v7/site/install.aspx) からダウンロードできます。[Microsoft Update カタログ](http://catalog.update.microsoft.com/v7/site/install.aspx)は、セキュリティ更新プログラム、ドライバーおよびサービスパックなどを含むコンテンツを検索可能なカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ番号 (例えば “MS07-036” など) を使用して検索することにより、バスケットに適用可能な更新プログラムをすべて追加することができ (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の関連情報を参照するには、[Microsoft Update カタログ よく寄せられる質問](http://catalog.update.microsoft.com/v7/site/faq.aspx)をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

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

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い謝意を表します。

-   MS10-087 で説明している問題を [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった匿名のリサーチャー
-   MS10-087 で説明している問題を [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して報告してくださった [team509](http://www.team509.com/)
-   MS10-087 で説明している問題を報告してくださった [Secunia](http://secunia.com/) の Dyon Balding 氏
-   MS10-087 で説明している問題を報告してくださった [CERT Coordination Center](http://www.cert.org/certcc.html) の Will Dorman 氏
-   MS10-087 で説明している問題を報告してくださった [TippingPoint の Zero Day Initiative](http://www.zerodayinitiative.com/)
-   MS10-087 で説明している問題を報告してくださった [VUPEN Vulnerability Research Team](http://www.vupen.com/) の Chaouki Bekrar 氏
-   MS10-087 で説明している問題を報告してくださった [Fortinet の FortiGuard Labs](http://www.fortiguard.com/) の Haifei Li 氏
-   MS10-087 で説明している問題を報告してくださった [ACROS Security](http://www.acrossecurity.com) の Simon Raner 氏
-   MS10-088 で説明している 「PowerPoint の解析のバッファー オーバーフローの脆弱性 - [CVE-2010-2572](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2572)」を報告してくださった [Secunia Research](http://secunia.com/) の Alin Rad Pop 氏
-   MS10-088 で説明している 「PowerPoint の整数アンダーフローの脆弱性 - [CVE-2010-2573](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573)」を [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった匿名のリサーチャー
-   MS10-089 で説明している 3 つの問題に関して、マイクロソフトに協力してくださった [BugSec](http://www.bugsec.com/) の Eyal Gruner 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2010/11/10: このセキュリティ情報ページを公開しました。
-   2010/11/10: MS10-088 のセキュリティ情報について、影響を受けるバージョンを "Microsoft PowerPoint Viewer" から "Microsoft PowerPoint Viewer 2007 Service Pack 2" に修正しました。今回の更新は情報のみの変更です。自動更新を有効にしているお客様など、すでにコンピューターを更新済みのお客様は特別な措置を講じる必要はありません。この更新プログラムを以前にインストールしていないお客様は、更新後の「影響を受けるソフトウェア」の一覧を基に、この更新プログラムがシステムに必要であるかどうかを確認する必要があります。
-   2010/11/18: MS10-087 について、Exploitability Index を修正し CVE-2010-2573 をこの更新プログラムが解決する脆弱性として追加しました。今回の更新は情報のみの変更です。
-   2010/12/16: このセキュリティ情報ページを更新し、 Microsoft Office 2008 for Mac 用 (KB2476512) および Open XML File Format Converter for Mac 用 (KB2476511) のセキュリティ更新プログラムが利用可能となったことをお知らせしました。
-   2011/04/14: このセキュリティ情報ページを更新し、Microsoft Office 2004 for Mac 用のセキュリティ更新プログラム (KB2505924) が利用可能となったことをお知らせしました。詳細は、MS10-087 および MS10-088 をご覧ください。

*Built at 2014-04-18T01:50:00Z-07:00*
