---
TOCTitle: 'MS08-MAR'
Title: 2008 年 3 月のセキュリティ情報
ms:assetid: 'ms08-mar'
ms:contentKeyID: 61229653
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms08-mar(v=Security.10)'
---

 

2008 年 3 月のセキュリティ情報
==============================

公開日: 2008年3月7日 | 最終更新日: 2008年4月17日

**バージョン:** 1.0

イラストを交えたセキュリティ情報はこちらをご覧ください。

絵でみるセキュリティ情報
------------------------

 
[MS08-014 : Excel の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms08-014e.mspx)

[MS08-015 : Outlook の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms08-015e.mspx)

[MS08-016 : Office の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms08-016e.mspx)

[MS08-017 : Office Web コンポーネントの重要な更新](https://www.microsoft.com/japan/security/bulletins/ms08-017e.mspx)

このセキュリティ情報は、2008 年 3 月に公開したセキュリティ情報の一覧です。

2008 年 3 月のセキュリティ情報の公開により、2008 年 3 月 7 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2008 年 3 月 12 日 午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[3 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357213&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

日本語版の Webcast 情報は 2008 年 3 月 12 日 の午後 (日本時間) に配信予定です。また、ポッドキャスティング (RSS フィード) 配信も行っております。 詳細は、 「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

今月のセキュリティ情報を深刻度別に下記に示します。

緊急 (4)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-014                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft Excel の脆弱性により、リモートでコードが実行される (949029)](https://technet.microsoft.com/security/bulletin/ms08-014)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **概要**                     | このセキュリティ更新プログラムは、ユーザーが特別な細工がされた Excel ファイルを表示した場合、リモートでコードが実行される可能性がある非公開および公開で報告された数件のMicrosoft Office Excel に存在する脆弱性を解決します。 攻撃者によりこれらの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。この更新プログラムは、再起動を必要としません。                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **影響を受けるソフトウェア** | **Microsoft Office.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-015                                                                                                                                                                                                                                                                                                                                                                                                                         |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft Outlook の脆弱性により、リモートでコードが実行される (949031)](https://technet.microsoft.com/security/bulletin/ms08-015)                                                                                                                                                                                                                                                                                                                               |
| **概要**                     | このセキュリティ更新プログラムは非公開で報告された Microsoft Office Outlook に存在する脆弱性を解決します。 クライアントに特別に細工された mailto URI が渡された場合、この脆弱性により Outlook の処理のコンテキストでリモートでコードが実行される可能性があります。 攻撃者がユーザーの既存の電子メールを読み、新しいメールをすべて攻撃者が制御するコンピュータにリダイレクトする可能性があります。 この脆弱性は Outlook のプレビュー ウィンドウで悪用されません。 |
| **最大深刻度**               | [緊急](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                    |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。この更新プログラムは、再起動を必要としません。                                                                                                                                                                                                                                                                                      |
| **影響を受けるソフトウェア** | **Microsoft Office.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                               |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-016                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft Office の脆弱性により、リモートでコードが実行される (949030)](https://technet.microsoft.com/security/bulletin/ms08-016)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **概要**                     | このセキュリティ更新プログラムは、ユーザーが不正な Office ファイルを表示した場合、リモートでコードが実行される可能性がある非公開で報告された Microsoft Office に存在する 2 件の脆弱性を解決します。攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。この更新プログラムは、再起動を必要としません。                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **影響を受けるソフトウェア** | **Microsoft Office.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |


<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-017                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft Office Web コンポーネントの脆弱性により、リモートでコードが実行される (933103)](https://technet.microsoft.com/security/bulletin/ms08-017)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **概要**                     | この深刻度が「緊急」のセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Office Web コンポーネントの脆弱性を解決します。 これらの脆弱性により、ユーザーが特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。 攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。 攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **影響を受けるソフトウェア** | **Microsoft Office Web コンポーネント.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

影響を受けるソフトウェア
------------------------

 
**この表はどのように使用しますか?**

この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが 記載されている場合、脆弱性の深刻度も記載されています。

**注** **:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。

 
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
[**MS08-014**](https://technet.microsoft.com/security/bulletin/ms08-014)
</td>
<td style="border:1px solid black;">
[**MS08-015**](https://technet.microsoft.com/security/bulletin/ms08-015)
</td>
<td style="border:1px solid black;">
[**MS08-016**](https://technet.microsoft.com/security/bulletin/ms08-016)
</td>
<td style="border:1px solid black;">
[**MS08-017**](https://technet.microsoft.com/security/bulletin/ms08-017)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="5">
Office スイート およびソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=72735aa1-e22c-40ed-8c79-38fba89979aa&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=9cf8aafa-71a5-4017-b53c-4e80ef6e1188&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=f7f90c30-1bfd-406b-a77f-612443e30185&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=907f96d5-d1e9-4471-b41c-3ac811e63038&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=296e5f2c-f594-41c8-a20a-3e4c40ae3948&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=280bb2ac-b21a-46b5-8751-5a50fbebf107&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=9f25922c-d3c2-4ef1-b164-8a21a77d29aa&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel 2007
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=e7634cb5-9531-4284-9554-4168fc488e0c&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=e9251d71-9098-4125-ae91-7d4c83ea58ad&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=714a49cd-5bca-4719-96a1-e1077f279533&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=59853687-d885-4059-9460-ee403855dbd8&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Outlook 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=fccc7c4c-8496-4682-bd46-6590503c1bf2&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Outlook 2007
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=4e2baf00-88eb-4eb6-961a-54245b363c21&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=95dceb37-b35f-46db-b280-db0f3b298aa9&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
重要 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=8fe8c32a-6d7a-482b-97c6-42562f089ee4&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
その他のソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web コンポーネント 2000  
(KB931660)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=806c654a-35e3-4385-855a-4b803249bfcf&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web コンポーネント 2000  
(KB932031)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=f54d2a5e-c0ed-4f70-9746-38dd61c8e9d7&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web コンポーネント 2000  
(KB933367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=d71b23fa-a873-406d-bad7-e38e565dee39&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web コンポーネント 2000  
(KB933369)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=2fe10ccd-40cb-4090-b83d-eae3d4eca174&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web コンポーネント 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=5fddd54f-7a33-4ea3-b68d-b96a9bae509d&displaylang=en)  
**<sup>[2]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web コンポーネント 2000  
(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=5fddd54f-7a33-4ea3-b68d-b96a9bae509d&displaylang=en)  
**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web コンポーネント 2000  
(KB941305)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=71de76ba-b62c-4a7a-a78a-9317f5255b13&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web コンポーネント 2000  
(KB948257)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
緊急 [![](../../images/Dn627232.exeIcon(ja-JP,Security.10).gif)](https://www.microsoft.com/download/details.aspx?familyid=526d87bd-c3da-412e-8765-c15987ae9b01&displaylang=ja)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2002 Service Pack 1 (KB933367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 Service Pack 1 (KB933369)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft BizTalk Server 2000 (KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2002(KB939714)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2000 (KB941305)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Security and Acceleration Server 2000 Service Pack 2 (KB948257)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
</table>

<p></p>

 
**注：**

**<sup>[1]</sup>** セキュリティ更新プログラムがこのオペレーティングシステムに利用です。詳細については、表に記載されている影響を受けるソフトウェアまたはコンポーネントおよび適切なセキュリティ情報をご覧ください。 

**<sup>[2]</sup>** このセキュリティ更新プログラムは Microsoft BizTalk Server 2000 に関連しています。詳細については、表に記載されている影響を受けるソフトウェアまたはコンポーネントおよび適切なセキュリティ情報をご覧ください。 

**<sup>[3]</sup>** このセキュリティ更新プログラムは Microsoft BizTalk Server 2002 に関連しています。詳細については、表に記載されている影響を受けるソフトウェアまたはコンポーネントおよび適切なセキュリティ情報をご覧ください。 

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピュータに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、 [TechNet 更新プログラム管理](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet Security センター](https://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供して います。

コンシューマのお客様は [Security At Home](https://www.microsoft.com/japan/athome/security) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](https://update.microsoft.com/microsoftupdate/)、[Windows Update](https://windowsupdate.microsoft.com/) および [Office Update](https://go.microsoft.com/fwlink/?%20linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の 関連情報を参照するには、サポート技術情報 [323166](https://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、 Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに 役立ちます。詳細情報は、サポート技術情報 [910723](https://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer** **および** **Enterprise Update Scan Tool**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、 [Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**注意:** 2007 年 10 月 9 日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルは更新されていません。この日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルに新しいセキュリティ更新プログラムは追加されていません。また、新しいバージョンの Enterprise Scan Tool はリリースされません。MBSA の詳細情報については、 [Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) を使用することにより、管理者は Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Windows 2000 およびそれ以降のオペレーティングシステムに対する Exchange Server 2003 および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

System Center Configuration Manager (SCCM) 2007 は更新プログラムの検出に WSUS 3.0 を使用します。SCCM 2007 Software Update Management に関する詳細については、[System Center Configuration Manager 2007 サイト](https://www.microsoft.com/japan/systemcenter/configmgr/default.mspx)をご覧ください。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、 管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新 プログラムの適用を管理することができます。SMS の次期製品である System Center Configuration Manager 2007 が発売されました。[System Center Configuration Manager 2007 サイト](https://www.microsoft.com/japan/systemcenter/configmgr/default.mspx)をご覧ください。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用の お客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供さ れた更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコン ピュータへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

今月:

-   マイクロソフトは Microsoft Update (MU) および Windows Server Update Services (WSUS) により、**セキュリティ以外** の優先度の高い更新プログラムを 2 件公開しました。
-   マイクロソフトは Windows Update (WU) で、Windows 用の**セキュリティ以外**の優先度の高い更新プログラムを 3 件公開しました。

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。そのほかの日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](https://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プ ログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [Microsoft ダウンロード センター](https://www.microsoft.com/downloads/search.aspx?displaylang=ja)か らダウンロードすることができます。「security update」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ用プラットフォームの更新プログラムは、[Microsoft Update](https://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード セ ンターから入手することができます。詳細情報は、サポート技術情報 [913086](https://support.microsoft.com/kb/913086) を ご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてそのほかの IT プロフェッショナルとの情報交換を 行うためには、[IT Pro Security Community](https://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原 因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS08-014 に説明されている問題について報告してくださった [SAIC](https://www.saic.com/) の Mike Scott 氏
-   MS08-014 に説明されている問題について報告してくださった [VeriSign](https://www.verisign.com/) の Barry Greenstein 氏
-   MS08-014 に説明されている問題について報告してくださった [iDefense Labs](https://labs.idefense.com/) の Greg MacManus 氏
-   MS08-014 に説明されている問題について報告してくださった [JFE Systems](https://www.jfe-systems.com/) の Yoshiya Sasaki 氏
-   MS08-014 に説明されている問題について報告してくださった [Fortinet](https://www.fortinet.com/) の Bing Liu 氏
-   MS08-014 に説明されている問題について報告してくださった [iDefense Labs](https://idefense.com/)
-   MS08-014 に説明されている問題について報告してくださった [TippingPoint DVLabs](https://dvlabs.tippingpoint.com/) の Cody Pierce 氏
-   MS08-014 に説明されている問題について報告してくださった [Websense Security Labs](https://www.websense.com/) の Moti Joseph 氏および Dan Hubbard 氏
-   MS08-015 に説明されている問題について報告してくださった [iDefense Labs](https://labs.idefense.com/) の Greg MacManus 氏
-   [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力し、 MS08-016 に説明されている問題について報告してくださった Arnaud Dovi 氏
-   MS08-016 に説明されている問題について報告してくださった匿名の発見者
-   MS08-017 に説明されている問題について報告してくださった [VigilantMinds Inc.](https://www.vigilantminds.com/) の Chris Ries 氏
-   MS08-017 に説明されている問題について報告してくださった [Finjan](https://www.finjan.com/) の Yuval Ben-Itzhak 氏
-   MS08-017 に説明されている問題について報告してくださった [Finjan](https://www.finjan.com/) の Golan Yosef 氏
-   MS08-017 に説明されている問題について報告してくださった NCNIPC の Xiao Hui 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原 因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報 の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または 書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連 会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一 切責任を負いません。（Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   2008/03/12: このセキュリティ情報ページを公開しました。
-   2008/03/13: このセキュリティ情報ページを更新し、Microsoft Office Web コンポーネント 2000 (KB931660) 用のセキュリティ更新プログラムのダウンロード先を追加しました。
-   2008/03/27: このセキュリティ情報ページを更新し、MS08-017 の発見者を追加しました。
-   2008/04/17: このセキュリティ情報ページを更新し、影響を受けるソフトウェアに Microsoft Office Word Viewer 2003 および Microsoft Office Word Viewer 2003 Service Pack 3 を追加しました。。

*Built at 2014-04-18T01:50:00Z-07:00*
