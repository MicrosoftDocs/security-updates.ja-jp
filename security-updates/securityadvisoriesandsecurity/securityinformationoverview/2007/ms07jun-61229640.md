---
TOCTitle: 'MS07-JUN'
Title: 2007 年 6 月のセキュリティ情報
ms:assetid: 'ms07-jun'
ms:contentKeyID: 61229640
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms07-jun(v=Security.10)'
---

 

2007 年 6 月のセキュリティ情報
==============================

公開日: 2007年6月13日 | 最終更新日: 2007年6月13日

イラストを交えたセキュリティ情報はこちらをご覧ください。

絵でみるセキュリティ情報
------------------------

 
[MS07-030 : Visio の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-030e.mspx)

[MS07-031 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-031e.mspx)

[MS07-032 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-032e.mspx)

[MS07-033 : Internet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-033e.mspx)

[MS07-034 : Outlook Express と Windows メールの重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-034e.mspx)

[MS07-035 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms07-035e.mspx)

2007 年 6 月のセキュリティ情報の公開により、2007 年 6 月 8 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2007 年 6 月 13 日午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary)(英語) をご覧ください。また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

今月のセキュリティ情報を深刻度別に下記に示します。

緊急 (4)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-031                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Microsoft Windows Schannel** **のセキュリティパッケージの脆弱性により、リモートでコードが実行される** **(935840)**](http://technet.microsoft.com/security/bulletin/ms07-031)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **概要**                     | この緊急の更新プログラムは新たに確認され、非公開で報告された Microsoft Windows の Schannel (セキュリティで保護されたチャネル) のセキュリティ パッケージの脆弱性を解決します。Schannel のセキュリティ パッケージは、SSL (Secure Sockets Layer) および TLS (Transport Level Security) のインターネット基準の認証プロトコルを実装します。この脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。しかし、この脆弱性を悪用すると、多くの場合 Internet Explorer が終了する結果となります。このコンピュータでは、SSL または TLS を使用の Web サイトへの接続は再起動するまでできない場合があります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **影響を受けるソフトウェア** | **Windows**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-033                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Internet Explorer** **用の累積的なセキュリティ更新プログラム** **(933566)**](http://technet.microsoft.com/security/bulletin/ms07-033)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **概要**                     | この「緊急」のセキュリティ更新プログラムは、5 つの新たに確認され非公開で報告された脆弱性および 1 つの新たに確認され公開された脆弱性を解決します。 1 つを除くこれらのすべての脆弱性により、ユーザーが特別な細工がされた Web ページを Internet Explorer を使用して表示した場合、リモートでコードが実行される可能性があります。 これ以外の 1 つの脆弱性により、なりすましが行われる可能性があり、また、特別な細工がされた Web ページが関連します。 リモートでコードが実行されるすべてのケースで、コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 なりすましのケースについて、脆弱性が悪用されるには、ユーザーの操作が攻撃者にとっての必要条件となります。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **影響を受けるソフトウェア** | **Windows, Internet Explorer**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
<p></p>
<p></p>
<p></p>


| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-034                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Outlook Express** **および** **Windows** **メール用の累積的なセキュリティ更新プログラム** **(929123)**](http://technet.microsoft.com/security/bulletin/ms07-034)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **概要**                     | この「緊急」のセキュリティ更新プログラムは、新たに確認され非公開で報告された 2 件の脆弱性および新たに確認され公開された 2 件の脆弱性を解決します。 この脆弱性のうち 1 件は、ユーザーが Windows Vista の Windows メールを使用して、特別に細工された電子メールを表示した際にリモートでコードが実行される可能性があります。 別の脆弱性は、ユーザーが Internet Explorer を使用して、特別に細工された Web ページを訪問した際に情報漏えいが起きる可能性があります。情報漏えいの脆弱性は、Internet Explorer が攻撃方法になる脆弱性で、Outlook Express で直接悪用される可能性はありません。 情報漏えいのケースおいて、コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **影響を受けるソフトウェア** | **Windows, Outlook Express, Windows** **メール**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
<p></p>
<p></p>
<p></p>


| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-035                                                                                                                                                                                                                                                                                                                                                                                                                  |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Win32 API** **の脆弱性により、コードが実行される** **(935839)**](http://technet.microsoft.com/security/bulletin/ms07-035)                                                                                                                                                                                                                                                                                                                              |
| **概要**                     | この「緊急」のセキュリティ更新プログラムは新たに発見され、非公開で報告された Win32 API の脆弱性を解決します。 この脆弱性により、リモートでコードが実行される、またローカルで使用された場合は特権の昇格の可能性があります。 この Win32 API のコンポーネントを使用しているアプリケーションがこの脆弱性の悪用方法として使用される可能性があります。 例えば、Internet Explorer が特別に細工した Web ページを解析する場合、この Win32 API の機能を使用します。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                             |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **検出**                     | Microsoft Baseline Security Analyzer と Enterprise Scan Tool を組み合わせ他場合、ご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。                                                                                                                                                                                                                                                                                   |
| **影響を受けるソフトウェア** | **Windows**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                 |

重要 (1)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-030                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Microsoft Visio** **の脆弱性により、リモートでコードが実行される** **(927051)**](http://technet.microsoft.com/security/bulletin/ms07-030)                                                                                                                                                                                                                                                                                                                                                           |
| **概要**                     | この「重要」の更新プログラムは、調査の段階で特定された別のセキュリティ問題と共に、新たに確認され、責任を持って報告された 2 件の脆弱性を解決します。この非公開で報告された脆弱性は、特別な細工がされた Visio ファイルをユーザーが表示した場合に悪用される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この脆弱性が悪用されるには、ユーザーの操作が必要条件となります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                                                                        |
| **影響を受けるソフトウェア** | **Office, Visio**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                        |

警告 (1)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-032                                                                                                                                                                                                                                             |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Windows Vista** **の脆弱性により、情報漏えいが起こる** **(931213)**](http://technet.microsoft.com/security/bulletin/ms07-032)                                                                                                                                                     |
| **概要**                     | この深刻度「警告」の更新プログラムは新たに確認され、非公開で報告された脆弱性を解決します。この脆弱性により、特権のないユーザーがレジストリおよびローカル ファイル システムに含まれている管理者パスワードを含むローカル ユーザー情報のデータ ストアにアクセスできる可能性があります。 |
| **最大深刻度**               | [警告](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                        |
| **脆弱性の影響**             | 情報の漏えい                                                                                                                                                                                                                                                                         |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                      |
| **影響を受けるソフトウェア** | **Windows**. 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                            |

影響を受けるソフトウェアおよびダウンロード先
--------------------------------------------

 
**この表はどのように使用しますか?**

この表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。表に記載されているソフトウェア プログラムまたはコンポーネントをチェックし、セキュリティ更新プログラムが必要かどうかを確認する必要があります。ソフトウェア プログラムまたはコンポーネントが表に記載されている場合、そのプログラムまたはコンポーネントへの脆弱性の影響とインストール可能なソフトウェアの更新プログラムへのハイパーリンクが記載されます。

**影響を受けるソフトウェア**

<p></p>

<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ></th>
<th style="border:1px solid black;" >詳細</th>
<th style="border:1px solid black;" >詳細</th>
<th style="border:1px solid black;" >詳細</th>
<th style="border:1px solid black;" >詳細</th>
<th style="border:1px solid black;" >詳細</th>
<th style="border:1px solid black;" >詳細</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報</strong> <strong>ID</strong> <strong>番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms07-030"><strong>MS07-030</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms07-031"><strong>MS07-031</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms07-032"><strong>MS07-032</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms07-033"><strong>MS07-033</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms07-034"><strong>MS07-034</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms07-035"><strong>MS07-035</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>警告</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>緊急</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Windows</strong> <strong>影響を受けるソフトウェア:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5b8e728c-cb9f-4176-93a0-bf42d6387f93&amp;displaylang=ja">警告</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3918ac76-ebb6-4886-9a9e-808eafb96b1b&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8615e6f3-415b-4c23-ba52-7eef70a11d77&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=27c7f1b9-2d1d-40cb-ad7e-bfedb6156a9c&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 with SP1 for Itanium-based Systems</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 with SP2 for Itanium-based Systems</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99&amp;displaylang=ja">緊急</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=cdf79d00-6f34-404b-8ad5-a2801ff35443&amp;displaylang=ja">警告</a></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista x64 Edition</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=89dde3f4-4123-4c97-86d8-00a83462c34b&amp;displaylang=ja">警告</a></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Windows</strong> <strong>影響を受けるオペレーティングシステムコンポーネント:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Service Pack 4 上の Internet Explorer 5.01 Service Pack 4</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3b49f1ed-abe3-4dbd-a91d-973415658f6b&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Service Pack 4 上の Internet Explorer 6 Service Pack 1</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5c958650-28d2-4dd0-96a8-dbfe79ce3f68&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2 用の Internet Explorer 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=60fb294e-a8e1-405e-a289-2d2723edf7ee&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2 用の Internet Explorer 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=086d6d6e-4703-4c6c-a7af-b6dafeeede5d&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2 用の Internet Explorer 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7ed19127-5c2d-48e4-a8d1-090dc69fd68b&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2 用の Internet Explorer 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1449eb5d-6e4c-4332-8cb6-ab9ee59c9a95&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems 用の Internet Explorer 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b628a3cc-a70c-478a-a10c-eee254ee34ab&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Service Pack 2 用の Internet Explorer 7</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c2191703-8cbd-4959-9f84-e13f21173926&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2 用の Internet Explorer 7</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=69c526b8-8b07-42bc-9bed-e18deae21c8e&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2 用の Internet Explorer 7</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a074d9c0-1fed-4753-845e-073cfce99f45&amp;displaylang=ja">警告</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2 用の Internet Explorer 7</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=744acb43-64da-48cc-ae69-9386b597eabc&amp;displaylang=ja">警告</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems 用の Internet Explorer 7</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=069c1560-b5e5-4dfe-a18d-e0507d406028&amp;displaylang=ja">警告</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista の Internet Explorer 7</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9b4d2fa7-d81e-499d-93c7-f64dc53b11b2&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista x64 Edition の Internet Explorer 7</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 2 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=27cca556-0872-4803-b610-4c895ceb99aa&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Professional x64 Edition 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be&amp;displaylang=ja">注意</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 2 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be&amp;displaylang=ja">注意</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3&amp;displaylang=ja">警告</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3&amp;displaylang=ja">警告</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 with SP1 for Itanium-based Systems 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025&amp;displaylang=ja">注意</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 with SP2 for Itanium-based Systems 用の Outlook Express 6</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025&amp;displaylang=ja">注意</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Vista 上の Windows メール</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ee57de19-44ea-48f2-ae28-e76fd2018633&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Vista x64 Edition 上の Windows メール</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=343db20f-7794-4423-b11d-885329fbdf78&amp;displaylang=ja">緊急</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Office</strong> <strong>影響を受けるソフトウェア:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Visio 2002</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fc1d0483-27e8-4541-b81d-4a47973bea30&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Visio 2003</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c47f432e-8538-42fd-92c9-7e0f1d643e8e&amp;displaylang=ja">重要</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
</tbody>
</table>

<p></p>

  
**<sup>[1]</sup>** このプラットフォームで利用可能なセキュリティ更新プログラムがあります。詳細については、影響を受けるソフトウェアまたはコンポーネントの欄をご覧ください。
  
検出および展開ツールとガイダンス  
--------------------------------
  
 
セキュリティ セントラル
  
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
  
Microsoft Software Update Services (SUS) は、最新の重要な更新プログラムを適用し、Windows ベースのシステムを最新の状態に維持するプロセスを大幅に簡素化する目的で開発されました。SUS により、重要な更新プログラムを Windows® 2000 ベースのサーバー、Windows Server™ 2003 ベースのサーバー、ならびに Windows® 2000 Professional や Windows XP Professional を実行するデスクトップ コンピュータへ迅速かつ確実に配布することができます。
  
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
  
**今月**:
  
-   マイクロソフトは Microsoft Update (MU) および Windows Server Update Services (WSUS) により、**セキュリティ以外**の優先度の高い更新プログラムを 7 件公開しました。  
-   マイクロソフトは Windows Update (WU)、および Software Update Services (SUS) で、Windows 用の**セキュリティ以外**の優先度の高い更新プログラムは公開していません。
  
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
  
-   [MS07-030](http://technet.microsoft.com/security/bulletin/ms07-030) の問題を報告してくださった [VigilantMinds Inc.](http://www.vigilantminds.com/) の Chris Ries 氏  
-   [MS07-031](http://technet.microsoft.com/security/bulletin/ms07-031) の問題を報告してくださった COSEINC 社の Thomas Lim 氏  
-   [MS07-032](http://technet.microsoft.com/security/bulletin/ms07-032) の問題を報告してくださった Robbie Sohlman 氏  
-   [MS07-033](http://technet.microsoft.com/security/bulletin/ms07-033) の問題を報告してくださった [iDefense VCP](http://idefense.com/) に協力している匿名のリサーチャー  
-   [MS07-033](http://technet.microsoft.com/security/bulletin/ms07-033) の問題についてマイクロソフトと協力してくださった [ISS](http://www.iss.net/) の Tom Cross 氏  
-   [MS07-033](http://technet.microsoft.com/security/bulletin/ms07-033) の問題を報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している匿名のリサーチャー  
-   [MS07-033](http://technet.microsoft.com/security/bulletin/ms07-033) の問題を報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している Sam Thomas 氏  
-   [MS07-033](http://technet.microsoft.com/security/bulletin/ms07-033) の問題を報告してくださった [CERT/CC](http://www.cert.org/certcc.html) の Will Dorman 氏  
-   [MS07-033](http://technet.microsoft.com/security/bulletin/ms07-033) の問題についてマイクロソフトと協力してくださった Fortinet の [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) の Haifei Li 氏  
-   [MS07-034](http://technet.microsoft.com/security/bulletin/ms07-034) の問題についてマイクロソフトと協力してくださった [SANS ISC](http://isc.sans.org/)  
-   [MS07-034](http://technet.microsoft.com/security/bulletin/ms07-034) の問題を報告してくださった 星屑|スターダスト氏および、[webappsec.jp](https://www.webappsec.jp/) の はせがわようすけ氏  
-   [MS07-035](http://technet.microsoft.com/security/bulletin/ms07-035) の問題を報告してくださった Billy Rios 氏
  
#### サポート
  
-   影響を受けるソフトウェアに記載してある製品をテストし、どのバージョンが影響を受けるか確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中の製品およびバージョンのサポート ライフサイクルを確認するためには、[マイクロソフト サポート ライフサイクル](http://support.microsoft.com/gp/lifecycle)の Web サイトをご覧ください。  
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。  
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。
  
#### 免責 :
  
本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。（Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。
  
#### 更新履歴
  
-   2007/6/13 : このセキュリティ情報ページを公開しました｡
  
*Built at 2014-04-18T01:50:00Z-07:00*
