---
TOCTitle: 'MS07-JUL'
Title: 2007 年 7 月のセキュリティ情報
ms:assetid: 'ms07-jul'
ms:contentKeyID: 61229639
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms07-jul(v=Security.10)'
---

 

2007 年 7 月のセキュリティ情報
==============================

公開日: 2007年7月11日 | 最終更新日: 2008年3月26日

イラストを交えたセキュリティ情報はこちらをご覧ください。

絵でみるセキュリティ情報
------------------------

 
[MS07-036 : Excel の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-036e.mspx)

[MS07-037 : Publisher 2007 の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-037e.mspx)

[MS07-038 : Windows Vista の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-038e.mspx)

[MS07-039 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-039e.mspx)

[MS07-040 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-040e.mspx)

[MS07-041 : Windows XP Professional の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-041e.mspx)

このセキュリティ情報は、2007 年 7 月に公開したセキュリティ情報の一覧です。

2007 年 7 月のセキュリティ情報の公開により、2007 年 7 月 6 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2007 年 7 月 11 日午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032343783&eventcategory=4&culture=en-us&countrycode=us)(英語) をご覧ください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

今月のセキュリティ情報を深刻度別に下記に示します。

緊急 (3)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-036                                                                                                                                                                                                                                                                                                                                                                                                                |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft Excel の脆弱性により、リモートでコードが実行される (936542)](http://technet.microsoft.com/security/bulletin/ms07-036)                                                                                                                                                                                                                                                                                                                        |
| **概要**                     | この深刻度「緊急」の更新プログラムは、調査の段階で特定された別のセキュリティ問題と共に、公開された 1 件の脆弱性および非公開で報告された 2 件の脆弱性を解決します。これらの脆弱性は、特別な細工がされた Excel ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                           |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要としません。                                                                                                                                                                                                                                                                   |
| **影響を受けるソフトウェア** | **Office, Excel**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                         |


<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-039                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Windows Active Directory の脆弱性により、リモートでコードが実行される (926122)](http://technet.microsoft.com/security/bulletin/ms07-039)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **概要**                     | この深刻度「緊急」のセキュリティ更新プログラムは、Windows 2000 Server および Windows Server 2003 の Active Directory の実装に存在する非公開で報告された脆弱性を解決します。この脆弱性により、リモートでコードが実行される、またはサービス拒否の状態が起こる可能性があります。 この脆弱性が悪用された場合、サービス拒否が起こる可能性が最も高いといえます。 しかし、リモートでコードが実行される可能性もあります。 Windows Server 2003 で、攻撃者が有効なログインの資格情報を得た場合、脆弱性を悪用する可能性があります。 攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピュータが完全に制御される可能性があります。 攻撃者は、その後、プログラムのインストール、データの表示、変更、削除、または新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **影響を受けるソフトウェア** | **Windows**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-040                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [.NET Framework の脆弱性により、リモートでコードが実行される (931212)](http://technet.microsoft.com/security/bulletin/ms07-040)                                                                                                                                                                                                                                                                                                                                            |
| **概要**                     | この更新プログラムは非公開で報告された脆弱性を解決します。このうち 2 件の脆弱性は、.NET Framework がインストールされているクライアントのコンピュータでリモートが実行されるもので、1 件は、ASP.NET を実行している Web サーバーで情報漏えいが起こる可能性があります。リモート コードが実行されるすべての場合で、コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                              |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                                            |
| **影響を受けるソフトウェア** | **.NET Framework**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                           |

重要 (2)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-037                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft Office Publisher 2007 の脆弱性により、リモートでコードが実行される (936548)](http://technet.microsoft.com/security/bulletin/ms07-037)                                                                                                                                                                                                                                                                                                                                                                 |
| **概要**                     | この深刻度が「重要」の更新プログラムは、一般に公開された 1 件の脆弱性を解決します。この脆弱性により、特別な細工がされた Microsoft Office Publisher 2007 ファイルをユーザーが表示すると、リモートでコードが実行される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この脆弱性が悪用されるには、それが予期されていますが、ユーザー側での操作が攻撃者にとっての必要条件となります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要としません。                                                                                                                                                                                                                                                                                                                            |
| **影響を受けるソフトウェア** | **Office, Publisher**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                              |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-041                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft インターネット インフォメーション サービスの脆弱性により、リモートでコードが実行される (939373)](http://technet.microsoft.com/security/bulletin/ms07-041)                                                                                                                                                                                                                                                                                                                                                  |
| **概要**                     | この深刻度「重要」のセキュリティ更新プログラムは、非公開で報告された脆弱性を解決します。この脆弱性は、攻撃者が Windows XP Professional Service Pack 2 上のインターネット インフォメーション サービス (IIS) でホストされた Web ページに特別に細工した URL リクエストを送信した場合、リモートでコードが実行される可能性があります。IIS 5.1 は Windows XP Professional Service Pack 2 に既定でインストールされることはありません。攻撃者はこの脆弱性を悪用し、影響を受けるコンピュータを完全に制御する可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                                                                                       |
| **影響を受けるソフトウェア** | **Windows XP Professional**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                             |

警告 (1)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-038                                                                                                                                                                                                                             |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Windows Vista ファイアウォールの脆弱性により、情報漏えいが起こる (935807)](http://technet.microsoft.com/security/bulletin/ms07-038)                                                                                                                                 |
| **概要**                     | この深刻度「警告」の更新プログラムは非公開で報告された脆弱性を解決します。この脆弱性により、未承諾の受信ネットワーク トラフィックがネットワーク インターフェイスにアクセスできる可能性があります。攻撃者は影響を受けるホストに関する情報を収集する可能性があります。 |
| **最大深刻度**               | [警告](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                        |
| **脆弱性の影響**             | 情報漏えい                                                                                                                                                                                                                                                           |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                      |
| **影響を受けるソフトウェア** | **Windows** **Vista**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                  |

影響を受けるソフトウェアおよびダウンロード先
--------------------------------------------

 
**この表はどのように使用しますか?**

この表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。表に記載されているソフトウェア プログラムまたはコンポーネントをチェックし、セキュリティ更新プログラムが必要かどうかを確認する必要があります。ソフトウェア プログラムまたはコンポーネントが表に記載されている場合、そのプログラムまたはコンポーネントへの脆弱性の影響とインストール可能なソフトウェアの更新プログラムへのハイパーリンクが記載されます。

**影響を受けるソフトウェア**

 
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
<th style="border:1px solid black;" >
詳細
</th>
<th style="border:1px solid black;" >
詳細
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報** **ID** **番号**
</td>
<td style="border:1px solid black;">
[**セキュリティ情報MS07-036**](http://technet.microsoft.com/security/bulletin/ms07-036)
</td>
<td style="border:1px solid black;">
[**セキュリティ情報MS07-037**](http://technet.microsoft.com/security/bulletin/ms07-037)
</td>
<td style="border:1px solid black;">
[**セキュリティ情報MS07-038**](http://technet.microsoft.com/security/bulletin/ms07-038)
</td>
<td style="border:1px solid black;">
[**セキュリティ情報MS07-039**](http://technet.microsoft.com/security/bulletin/ms07-039)
</td>
<td style="border:1px solid black;">
[**セキュリティ情報MS07-040**](http://technet.microsoft.com/security/bulletin/ms07-040)
</td>
<td style="border:1px solid black;">
[**セキュリティ情報MS07-041**](http://technet.microsoft.com/security/bulletin/ms07-041)
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
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="7">
Windows 影響を受けるソフトウェア:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 2000 Server Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=812e62c5-6e19-4b3b-8a10-861b871e1b41&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional Service Pack 2
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=fccbfe90-f838-47df-8310-352e2fb47132&displaylang=ja)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=28e84603-8159-4429-aaff-a1020531e84f&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=28e84603-8159-4429-aaff-a1020531e84f&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=107902f9-be94-457f-a936-519efbd64779&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=107902f9-be94-457f-a936-519efbd64779&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb&displaylang=ja)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[警告](http://www.microsoft.com/downloads/details.aspx?familyid=e9b64746-6afa-4a30-833d-e058e000c821&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[警告](http://www.microsoft.com/downloads/details.aspx?familyid=0df5d190-3ad7-42d5-8629-43c47ec450cb&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64 Edition
</td>
<td style="border:1px solid black;">
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
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7">
Windows 影響を受けるオペレーティングシステムコンポーネント:
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0  
(KB928367)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=91d7afe4-069b-4ce8-976e-9a01345a8603&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0  
(KB930494)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=829a2c5b-11ec-4ed7-91ab-6961034147bc&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB928366)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=281fb2cd-c715-4f05-a01f-0455d2d9ebfb&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB933854)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=2495e656-1e0a-4b83-90da-821e68067a71&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1  
(KB929729)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=7eea368d-7b82-4583-8537-30351718a4e9&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0  
(KB928365)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=ba3ceb78-8e1b-4c38-adfd-e8bc95ae548d&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0  
(KB929916)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=cbc9f3cf-c3c3-45c4-82e3-e11398bc2cd2&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7">
Office 影響を受けるソフトウェア:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Excel 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/downloads/details.aspx?familyid=83d94d8e-dda6-4d74-b40d-476c2f0a3af4&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
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
Excel 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=5e09d13b-d4b0-48fd-9880-73c180570267&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
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
Excel 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=9d93c0ce-5124-4234-ba84-3c27005e010f&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
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
Excel 2003 Viewer
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=11f42977-8828-494a-a183-d1aba827b708&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
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
Excel 2007
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=9ab28283-0320-4527-b033-5e80ef32cd34&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
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
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=e592ae5b-09ac-4f5b-b457-a54c9850ad4a&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
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
Publisher 2007
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/downloads/details.aspx?familyid=25d272e7-f2dd-4342-92be-7ebc2e770b44&displaylang=ja)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>

<p></p>

 
**<sup>[1]</sup>** このプラットフォームで利用可能なセキュリティ更新プログラムがあります。詳細については、影響を受けるソフトウェアまたはコンポーネントの欄をご覧ください。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピュータに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet Security センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマのお客様は [Security At Home](http://www.microsoft.com/japan/athome/security) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security_patch)からダウンロードすることができます。「security\_patch」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer** **および** **Enterprise Scan Tool**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報は、[Microsoft Baseline Security Analyzer Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

MBSA 1.2.1 が検出できない特定のセキュリティ更新プログラムの場合、マイクロソフトは、特定のセキュリティ更新プログラム向けに Enterprise Scan Tool (EST) を公開しています。EST の詳細については、[Enterprise Scan Tool](http://support.microsoft.com/kb/894193) をご覧ください。

**注意:** 2007 年 10 月 9 日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルは更新されなくなります。この日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルに新しいセキュリティ更新プログラムは追加されません。また、新しいバージョンの Enterprise Scan Tool はリリースされません。 詳細情報については、[Microsoft Baseline Security Analyzer Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Software Update Services**

Microsoft Software Update Services (SUS) は、最新の重要な更新プログラムを適用し、Windows ベースのシステムを最新の状態に維持するプロセスを大幅に簡素化する目的で開発されました。SUS により、重要な更新プログラムを Windows? 2000 ベースのサーバー、Windows Server? 2003 ベースのサーバー、ならびに Windows? 2000 Professional や Windows XP Professional を実行するデスクトップ コンピュータへ迅速かつ確実に配布することができます。

**Software Update Services** でこのセキュリティ更新プログラムを適用する方法に関する情報は、[Software Update Services の概要](http://www.microsoft.com/japan/windowsserversystem/sus/susoverview.mspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003、および SQL Server 2000 用のセキュリティ更新プログラムに対応しています。Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。 SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピュータへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

このツールは Software Update Services (SUS) により**配布されない**ことに注意してください。

#### MU、WU、WSUS および SUS でのセキュリティ以外の優先度の高い更新プログラム

今月:

-   マイクロソフトは Microsoft Update (MU) および Windows Server Update Services (WSUS) により、**セキュリティ以外**の優先度の高い更新プログラムを 4 件公開しました。
-   マイクロソフトは Windows Update (WU)、および Software Update Services (SUS) で、Windows 用の**セキュリティ以外**の優先度の高い更新プログラムを 1 件公開しました。

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、Windows Server Update Services および Software Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。そのほかの日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理の セキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [Microsoft ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security\_patch」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてそのほかの IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

マイクロソフトは顧客の保護のために協力して下さった、以下の方々に深い [謝意](http://technet.microsoft.com/security/bulletin/policy) を表します。

-   [MS07-037](http://technet.microsoft.com/security/bulletin/ms07-037) の問題を報告してくださった [eEye](http://eeye.com/)
-   [MS07-038](http://technet.microsoft.com/security/bulletin/ms07-038) の問題を報告してくださった [Symantec](http://www.symantec.com/index.jsp) の Jim Hoagland 氏および Ollie Whitehouse 氏
-   [MS07-039](http://technet.microsoft.com/security/bulletin/ms07-039) の問題を報告してくださった [NGSSoftware](http://www.nextgenss.com/) の Peter Winter-Smith 氏
-   [MS07-039](http://technet.microsoft.com/security/bulletin/ms07-039) の問題を報告してくださった [IBM Internet Security Systems x-Force](http://xforce.iss.net/) の Neel Mehta 氏
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-033) の問題を報告してくださった [OWASP](http://www.owasp.org/) 社の Dinis Cruz 氏
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-033) の問題を報告してくださった [Security Assessment](http://www.smsiinc.com/) のPaul Craig 氏
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) の問題を報告してくださった [Sumatra](http://www.sumatra.nl/) のJeroen Frijters氏
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) の問題を報告してくださった [UK CPNI](http://www.cpni.gov.uk/) と協力している [ProCheckUp](http://www.procheckup.com/)
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) の問題を報告してくださった [Portcullis Computer Security Ltd](http://www.portcullis-security.com/) の Ferruh T. Mavituna 氏
-   [MS07-040](http://technet.microsoft.com/security/bulletin/ms07-040) についてマイクロソフトに協力および追加情報を提供してくださった [TrueSec](http://www.truesec.com/) の Johannes Gumbel 氏
-   [MS07-041](http://technet.microsoft.com/security/bulletin/ms07-041) についてマイクロソフトに協力および追加情報を提供してくださった [Watchfire](http://http://www.watchfire.com/) の Jonathan Afek 氏 および Adi Sharabani 氏
-   [MS07-041](http://technet.microsoft.com/security/bulletin/ms07-041) についてマイクロソフトに協力および追加情報を提供してくださった [NGS Software](http://www.ngssoftware.com/) の Peter Winter-Smith 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。（Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   2007/7/11 : このセキュリティ情報ページを公開しました｡
-   2008/3/26 : 「影響を受けるソフトウェア」の表に Windows Vista Service Pack 1、Windows Vista x64 Edition Service Pack 1、 Windows Server 2008、Windows Server 2008 for Itanium-based Systems、および Windows Server 2008 x64 Edition を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
