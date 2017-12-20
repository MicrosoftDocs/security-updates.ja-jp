---
TOCTitle: 'MS08-NOV'
Title: 2008 年 11 月のセキュリティ情報
ms:assetid: 'ms08-nov'
ms:contentKeyID: 61229655
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms08-nov(v=Security.10)'
---

 

2008 年 11 月のセキュリティ情報
===============================

公開日: 2008年11月12日 | 最終更新日: 2011年7月13日

**バージョン:** 1.0

絵でみるセキュリティ情報
------------------------

 
[MS08-068 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-068e.mspx)

[MS08-069 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-069e.mspx)

このセキュリティ情報は 2008 年 11 月に公開したセキュリティ情報の一覧です。

2008 年 11 月のセキュリティ情報の公開により、2008 年 11 月 7 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2008 年 11 月 12 日 午前 11 ：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[11 月のセキュリティ 情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374642&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

日本語版の Webcast 情報は 2008 年 11 月 12 日 の午後 (日本時間) に配信予定です。 詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

緊急 (1)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-069                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft XML コア サービスの脆弱性により、リモートでコードが実行される (955218)](http://technet.microsoft.com/security/bulletin/ms08-069)                                                                                                                                                                                                                                                                                                        |
| **概要**                     | このセキュリティ更新プログラムは Microsoft XML コア サービスに存在するいくつかの脆弱性を解決します。これらの脆弱性の中で最も深刻な脆弱性が悪用された場合、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。 |
| **最大深刻度**               | [緊急](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                      |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピューターに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                                                                              |
| **影響を受けるソフトウェア** | **Microsoft Windows. Microsoft Office.** 詳細情報は、「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                      |

重要 (1)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-068                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [SMB の脆弱性により、リモートでコードが実行される (957097)](http://technet.microsoft.com/security/bulletin/ms08-068)                                                                                                                                                                                                                                                                                                                                                                                                   |
| **概要**                     | この更新プログラムは一般に公開された Microsoft Server Message Block (SMB) プロトコルに存在する脆弱性を解決します。この脆弱性により、影響を受けるコンピューターでリモートでコードが実行される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピューターに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要です。                                                                                                                                                                                                                                                                                                                                              |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                                                                                                            |

Exploitability Index (悪用可能性指標)
-------------------------------------

 
**この表はどのように使用しますか?**

この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細情報は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。

| セキュリティ情報番号                                                | セキュリティ情報タイトル                                                                                                                    | CVE ID        | Exploitability Index の評価                                                                 | 注意事項                                                                                                    |
|---------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|---------------|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| [MS08-068](http://technet.microsoft.com/security/bulletin/ms08-068) | [SMB の脆弱性により、リモートでコードが実行される (957097)](http://technet.microsoft.com/security/bulletin/ms08-068)                        | CVE-2008-4037 | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 現在、Windows XP の脆弱性に対する悪用コードが一般に公開されています。                                       |
| [MS08-069](http://technet.microsoft.com/security/bulletin/ms08-069) | [Microsoft XML コア サービスの脆弱性により、リモートでコードが実行される (955218)](http://technet.microsoft.com/security/bulletin/ms08-069) | CVE-2008-4029 | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 情報漏えいに使われる悪用コードは、クロス ドメイン攻撃で使用されるコードのようなものである可能性があります。 |
| [MS08-069](http://technet.microsoft.com/security/bulletin/ms08-069) | [Microsoft XML コア サービスの脆弱性により、リモートでコードが実行される (955218)](http://technet.microsoft.com/security/bulletin/ms08-069) | CVE-2007-0099 | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | この脆弱性は XML ファイルを読み込む際に競合状態となります。そのため、連続して悪用するのは困難です。         |
| [MS08-069](http://technet.microsoft.com/security/bulletin/ms08-069) | [Microsoft XML コア サービスの脆弱性により、リモートでコードが実行される (955218)](http://technet.microsoft.com/security/bulletin/ms08-069) | CVE-2008-4033 | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) |                                                                                                             |

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
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=559cd4b6-24b7-4e60-8749-37d9b833d3eb&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ja)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=44c971e6-96fc-4bba-8f4a-f9d46bda2b6c&displaylang=ja)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ja)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c&displaylang=ja)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.http//www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=7493fa37-2cbf-4d66-8690-d50d63da4096&displaylang=ja)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c&displaylang=ja)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1b79f220-ebfc-49c1-963b-58bbda21b6e7&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ja)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9501b33b-d639-43e7-ad5a-9e76ed66effd&displaylang=ja)  
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
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=0a0f8385-e908-4b5f-b9bf-80b7dabfcafd&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(注意)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ja)  
(KB954459)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=57a0606d-ea7a-4e5b-8b8b-7b77a444ef75&displaylang=ja)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=347c8c83-4269-4a0e-af6f-4be2e824d22b&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(注意)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ja)  
(KB954459)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=915e001f-9aa0-4fb0-9c2a-0f0c72b4f056&displaylang=ja)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=3a65e1cd-eb4e-44b6-8868-a5a84be2cb32&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(注意)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3&displaylang=ja)  
(KB954459)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=6abf7ba9-825f-4ee2-a2fe-6b1cd9fab622&displaylang=ja)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista および Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=affbc957-1867-4bbe-924d-6f0696ae0895&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cb6c4315-8c6d-43af-978b-b190b1a1577a&displaylang=ja)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5612815f-8685-45d2-af4a-164c298a0869&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b01a5f31-8c57-4c5c-909e-b37caf0439b0&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=39443046-2093-4c87-ac7b-679deab96414&displaylang=ja)  
(KB954459)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=727ce9b6-827f-4350-b4ff-c08e8ac541a6&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=90a04164-4d02-4ce9-b3d8-bddb1ec27618&displaylang=ja)\*\*  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)\*\*  
(KB954430)  
(注意)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=dea9f227-967f-47c7-bb2a-ed68f13645d9&displaylang=ja)\*\*  
(KB954459)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=b305e894-61ec-46b4-91ee-4c9ac59bc47e&displaylang=ja)\*  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)\*\*  
(KB954430)  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b7bfe3f4-835f-402c-95b5-6d49b6935308&displaylang=ja)\*\*  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)\*\*  
(KB954430)  
(注意)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f16e2a5f-37fd-4ee1-aef0-597214323dc4&displaylang=ja)\*\*  
(KB954459)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=e8d26dfd-b347-4f10-b5b6-27dfff5e4f47&displaylang=ja)\*  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)\*\*  
(KB954430)  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4e0d1efe-70ac-459b-b330-c0149b74f520&displaylang=ja)  
(KB955069)  
(緊急)  
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(注意)  
[Microsoft XML コア サービス 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d4ae74e2-1b09-4a99-8cf5-8a8ca8ac6f7f&displaylang=ja)  
(KB954459)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=d565467d-e10f-4ddc-a278-3f81a3798686&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(注意)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
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
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(重要)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://technet.microsoft.com/security/bulletin/ms08-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)\*\*  
(KB954430)  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14&displaylang=ja)  
(KB954430)  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**\*Server Core インストールは影響を受けます。** サポートされているエディションの Windows Server 2008 および Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度でこの更新プログラムが適用されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

**\*\*Server Core インストールは影響を受けません。** この更新プログラムで解決されている脆弱性は、Server Core インストールオプションを使用してインストールされたサポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 は、影響を受けません。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

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
Microsoft Office スイート、システム、およびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3&displaylang=ja)  
(KB951535)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System および 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245&displaylang=ja)  
(KB951550)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
その他の Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://technet.microsoft.com/security/bulletin/ms08-069)
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
Microsoft Word Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3&displaylang=ja)  
(KB951535)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245&displaylang=ja)  
(KB951550)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web および Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245&displaylang=ja)  
(KB951550)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 および Microsoft Office SharePoint Server 2007 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=a208f2b5-2b0d-43bb-8f8a-58d4a3fc64f5&displaylang=ja)  
(KB951597)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 および Microsoft Office SharePoint Server 2007 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c&displaylang=ja)  
(KB951597)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c&displaylang=ja)  
(KB951597)  
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

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): 2008 年のコンテンツでは、Software Update Services (SUS) および Windows Server Update Services (WSUS) の情報が変更されました。すべての Windows のコンテンツが含まれます
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

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

-   MS08-069 で説明している問題について報告してくださった Gregory Fleischer 氏
-   MS08-069 で説明している問題について報告してくださった [Minded Security](http://www.mindedsecurity.com/) の Stefano Di Paola 氏
-   MS08-069 で説明している問題について報告してくださった [SecTheory](http://www.sectheory.com/) の Robert Hansen 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2008/11/12: このセキュリティ情報ページを公開しました。
-   2008/04/30: このセキュリティ情報を更新し、セキュリティ情報 MS08-069 の影響を受けるソフトウェアに 32-bit および x64-based エディションの Windows Vista Service Pack 2 上の Microsoft XML コア サービス 4.0 (KB954430) および 32-bit, x64-based および Itanium-based エディションの Windows Server 2008 Service Pack 2 上の Microsoft XML コア サービス 4.0 (KB954430) を追加しました。KB952068 の更新プログラムを正常にインストールされたお客様は、この更新プログラムの再インストールの必要はありません。
-   2008/10/14: このセキュリティ情報を更新し、影響を受けるソフトウェアに 32-bit および x64-based エディションの Windows 7 および 32-bit, x64-based および Itanium-based エディションの Windows Server 2008 R 2 の Microsoft XML コア サービス 4.0 (KB954430) を追加しました。これは検出の変更のみで、バイナリへの変更はありません。KB954430 の更新プログラムを正常にインストールされたお客様は、この更新プログラムの再インストールの必要はありません。
-   2011/07/13: このセキュリティ情報を更新し、MS08-069 の影響を受けるソフトウェアに32-bit および x64-based エディションの Windows 7 Service Pack 1、ならびに x64-based および Itanium-based エディションの Windows Server 2008 R2 Service Pack 1 の Microsoft XML コア サービス 4.0 (KB954430) を追加しました。これは検出の変更のみで、バイナリへの変更はありません。 KB954430 の更新プログラムを正常にインストールされたお客様は、この更新プログラムの再インストールの必要はありません。

*Built at 2014-04-18T01:50:00Z-07:00*
