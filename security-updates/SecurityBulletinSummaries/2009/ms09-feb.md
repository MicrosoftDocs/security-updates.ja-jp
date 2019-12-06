---
TOCTitle: 'MS09-FEB'
Title: 2009 年 2 月のセキュリティ情報
ms:assetid: 'ms09-feb'
ms:contentKeyID: 61229661
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-feb(v=Security.10)'
--- 

2009 年 2 月のセキュリティ情報
==============================

公開日: 2009年2月11日 | 最終更新日: 2009年2月26日

**バージョン:** 1.0

絵でみるセキュリティ情報
------------------------


[MS09-002 : Internet Explorer の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-002e.mspx)

[MS09-003 : Exchange の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-003e.mspx)

[MS09-004 : SQL の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-004e.mspx)

[MS09-005 : Visio の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-005e.mspx)

このセキュリティ情報は 2009 年 2 月に公開したセキュリティ情報の一覧です。

2009 年 2 月のセキュリティ情報の公開により、2009 年 2 月 6 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 2 月 11 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 2 月 11 日 午前 11 ：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[2 月のセキュリティ 情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395122&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-002">MS09-002</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (961260)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の脆弱性を解決します。この脆弱性では、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-003">MS09-003</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange の脆弱性により、リモートでコードが実行される (959239)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Exchange Server に存在する 2 件の脆弱性を解決します。第 1 番目の脆弱性では、特別な細工がされた TNEF のメッセージが Microsoft Exchange Server に送信された場合に、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、Exchange Server サービス アカウント特権を使用し、影響を受けるコンピューターを完全に制御する可能性があります。第 2 番目の脆弱性では、特別な細工がされた MAPI コマンドが Microsoft Exchange Server に送信された場合に、サービス拒否が起こる可能性があります。攻撃者がこの脆弱性を悪用した場合、EMSMDB32 プロバイダーを使用している Microsoft Exchange System Attendant サービスおよび別のサービスが応答を停止します。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-004">MS09-004</a></td>
<td style="border:1px solid black;"><strong>SQL Server の脆弱性により、リモートでコードが実行される (959420)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft SQL Server に存在する 1 件の脆弱性を解決します。この脆弱性は、信頼できないユーザーが影響を受けるシステムへのアクセス許可を取得する、または影響を受けるシステムに SQL インジェクション攻撃が実行された場合、リモートでコードが実行される可能性があります。SQL Server 7.0 Service Pack 4、SQL Server 2005 Service Pack 3、SQL Server 2008 のシステムは、この問題の影響を受けません。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-005">MS09-005</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Visio の脆弱性により、リモートでコードが実行される (957634)</strong><br />
<br />
このセキュリティ更新プログラムは、特別に細工された Visio ファイルを表示した場合にリモートでコードが実行される可能性のある非公開で報告された Microsoft Office Visio の 3 件の脆弱性を解決します。攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  

**この表はどのように使用しますか?**  
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細情報は、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 番号                                                     | セキュリティ情報タイトル                                                     | CVE ID                                                                       | Exploitability Index の評価                                                                 | 注意事項                                                                                                                                                                               |  
|---------------------------------------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-002](https://www.microsoft.com/japan/technet/bulletin/ms09-002.mspx) | Internet Explorer 用の累積的なセキュリティ更新プログラム (961260)            | [CVE-2009-0075](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0075) | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 動作に一貫性のある攻撃コ―ドが容易に作られる可能性があります。                                                                                                                          |  
| [MS09-002](https://www.microsoft.com/japan/technet/bulletin/ms09-002.mspx) | Internet Explorer 用の累積的なセキュリティ更新プログラム (961260)            | [CVE-2009-0076](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0076) | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 動作に一貫性のある攻撃コ―ドが容易に作られる可能性があります。                                                                                                                          |  
| [MS09-003](https://www.microsoft.com/japan/technet/bulletin/ms09-003.mspx) | Microsoft Exchange の脆弱性により、リモートでコードが実行される (959239)     | [CVE-2009-0098](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0098) | [2 - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | なし                                                                                                                                                                                   |  
| [MS09-003](https://www.microsoft.com/japan/technet/bulletin/ms09-003.mspx) | Microsoft Exchange の脆弱性により、リモートでコードが実行される (959239)     | [CVE-2009-0099](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0099) | [2 - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | この脆弱性を悪用してリモートでサービス拒否を引き起こします。しかしながら、この脆弱性が悪用された攻撃の結果はサービス拒否にとどまり、リモートでコードが実行される事はないと思われます。 |  
| [MS09-004](https://www.microsoft.com/japan/technet/bulletin/ms09-004.mspx) | SQL Server の脆弱性により、リモートでコードが実行される (959420)             | [CVE-2008-5416](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-5416) | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 認証後に実際に作動する攻撃コードが一般に公開されています。                                                                                                                             |  
| [MS09-005](https://www.microsoft.com/japan/technet/bulletin/ms09-005.mspx) | Microsoft Office Visio の脆弱性により、リモートでコードが実行される (957634) | [CVE-2009-0095](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0095) | [2 - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | なし                                                                                                                                                                                   |  
| [MS09-005](https://www.microsoft.com/japan/technet/bulletin/ms09-005.mspx) | Microsoft Office Visio の脆弱性により、リモートでコードが実行される (957634) | [CVE-2009-0096](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0096) | [2 - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | なし                                                                                                                                                                                   |  
| [MS09-005](https://www.microsoft.com/japan/technet/bulletin/ms09-005.mspx) | Microsoft Office Visio の脆弱性により、リモートでコードが実行される (957634) | [CVE-2009-0097](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0097) | [2 - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | なし                                                                                                                                                                                   |
  
影響を受けるソフトウェア  
------------------------
  

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
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-002**](https://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](https://technet.microsoft.com/security/bulletin/ms09-004)
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
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=8cd902ec-e018-4b61-80f9-825d973f998e&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=dd3e2236-9cc0-478e-a46c-981ef685c0e3&displaylang=ja)  
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
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-002**](https://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](https://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e52aa1fd-e694-4322-b3ff-6abc1b4a16fe&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](https://www.microsoft.com/download/details.aspx?familyid=218809d6-a9fb-408b-a34d-ab2ac786994c&displaylang=ja)  
(KB960082)  
(重要)  
[Windows Internal Database (WYukon) Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e&displaylang=ja)  
(KB960089)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=edbf1566-b96b-4c7d-98fe-b15f8e766792&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](https://www.microsoft.com/download/details.aspx?familyid=87183155-6770-4ea2-acca-191de4d40d27&displaylang=ja)  
(KB960082)  
(重要)  
[Windows Internal Database (WYukon) x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67&displaylang=ja)  
(KB960089)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5ce78797-d1c0-40d4-84e1-1004389833be&displaylang=ja)  
(警告)
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
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-002**](https://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](https://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista および Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5f9fa4b6-85a4-43bc-b84f-6bd847799650&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e9a8c94b-b9d2-4d64-855f-b5f02ce3dfb5&displaylang=ja)  
(緊急)
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
[**MS09-002**](https://technet.microsoft.com/security/bulletin/ms09-002)
</td>
<td style="border:1px solid black;">
[**MS09-004**](https://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=2491dbf2-7cd3-44f1-bfad-77e6f760a25c&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e&displaylang=ja)\*  
(KB960089)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=794373cc-2dce-4ef5-af50-7804c622c230&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67&displaylang=ja)\*  
(KB960089)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=11985325-4b33-4077-82cf-6afc7a71c510&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 に関する注意:**

**\*Windows Server 2008 Server Core インストールは影響を受けます。** サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度でこの更新プログラムが適用されます。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

**\*\*Windows Server 2008 Server Core インストールは影響を受けません。** これらの更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 をインストールした場合、サポートされているエディションの Windows Server 2008 に影響を与えません。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

**MS09-004 に関する注意:**

更新プログラムのファイルに関する詳細情報は、「Microsoft サーバー ソフトウェア」の欄も併せてご覧ください。このセキュリティ情報は Windows オペレーティング システムおよびコンポーネントと Microsoft サーバー ソフトウェアの両方を対象としています。

#### Microsoft サーバー ソフトウェア

 
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
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-003**](https://technet.microsoft.com/security/bulletin/ms09-003)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange 2000 Server
</td>
<td style="border:1px solid black;">
[2004 年 8 月公開の Exchange 2000 Server Service Pack 3 以降の更新プログラムのロールアップ](https://www.microsoft.com/download/details.aspx?familyid=805dc856-ea60-477d-be40-6ac535a7e7e5&displaylang=ja)  
(KB959897)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1d9f0956-88bd-4e13-a86b-b1c8d4782f71&displaylang=ja)\*  
(KB959897)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=93cb3f66-ae72-4356-bdbf-35029cff6df1&displaylang=ja)\*\*  
(KB959241)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server MAPI クライアントおよび Collaboration Data Objects 1.2.1
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server MAPI クライアントおよび Collaboration Data Objects 1.2.1](https://www.microsoft.com/download/details.aspx?familyid=e17e7f31-079a-43a9-bff2-0a110307611e&displaylang=en)\*\*\*  
(緊急)
</td>
</tr>
</table>

<p></p>

 
**MS09-003 に関する注意:**

\* サーバーが Exchange サービスのアクティブ インスタンスも実行している場合、Exchange Server 2003 用の Microsoft Exchange システム管理ツールが含まれます。

\*\*32 ビット版および 64 ビット版を含みます。

\*\*\*The Microsoft Exchange Server MAPI クライアントには影響を受けるコードが含まれています。Microsoft Exchange Server MAPI クライアントを実行している場合、MS09-003 で説明している脆弱性を防ぐため、MAPI クライアントの version 6.5.8069 に更新する必要があります。

 
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
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-004**](https://technet.microsoft.com/security/bulletin/ms09-004)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c&displaylang=ja)  
(KB960082)  
(重要)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a&displaylang=ja)  
(KB960083)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2000 Itanium-based Edition Service Pack 4
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2000 Itanium-based Edition Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c&displaylang=ja)  
(KB960082)  
(重要)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2000 Itanium-based Edition Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a&displaylang=ja)  
(KB960083)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ja)  
(KB960089)  
(重要)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ja)  
(KB960090)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ja)  
(KB960089)  
(重要)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ja)  
(KB960090)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2005 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ja)  
(KB960089)  
(重要)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2005 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ja)  
(KB960090)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c&displaylang=ja)  
(KB960082)  
(重要)  
QFE のセキュリティ更新プログラム:  
[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a&displaylang=ja)  
(KB960083)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2005 Express Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ja)  
(KB960089)  
(重要)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2005 Express Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ja)  
(KB960090)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Express Edition with Advanced Services Service Pack 2
</td>
<td style="border:1px solid black;">
GDR のセキュリティ更新プログラム:  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e&displaylang=ja)  
(KB960089)  
(重要)  
QFE のセキュリティ更新プログラム:  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a&displaylang=ja)  
(KB960090)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**MS09-004 に関する注意:**

更新プログラムのファイルに関する詳細情報は、「Microsoft サーバー ソフトウェア」の欄も併せてご覧ください。このセキュリティ情報は Windows オペレーティング システムおよびコンポーネントと Microsoft サーバー ソフトウェアの両方を対象としています。

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
Microsoft Office Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-005**](https://technet.microsoft.com/security/bulletin/ms09-005)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2002
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a30cef3f-9eaf-45bd-9a25-4b65302362cb&displaylang=ja)  
(KB955654)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Visio 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c9cb589e-1a37-485d-8402-7f42bcd7a1a9&displaylang=ja)  
(KB955655)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4b711e89-8de2-4f17-8afc-691e0604ff82&displaylang=ja)  
(KB957831)  
(重要)
</td>
</tr>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------


**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよ びセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](https://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](https://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](https://update.microsoft.com/microsoftupdate/)、[Windows Update](https://windowsupdate.microsoft.com/) および [Office Update](https://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/results.aspx?%20displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけること ができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](https://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](https://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができ ます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およ びそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応し ています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範 なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は 、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用すること ができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?familyid=7bd3a16e-1899%20-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](https://support.microsoft.com/kb/894199/en-us) (英語情報): 2009 年のコンテンツでは、Software Update Services (SUS) および Windows Server Update Services (WSUS) の情報が変更されました。すべての Windows のコンテンツが含まれます
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](https://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](https://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ 管理のセキュリティ ガイド](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](https://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報 は、サポート技術情報 [913086](https://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](https://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS09-002 で説明している問題について報告してくださった [TippingPoint](https://www.tippingpoint.com/) および [Zero Day Initiative](https://www.zerodayinitiative.com/)
-   MS09-002 で説明している問題について報告してくださった [TippingPoint](https://www.tippingpoint.com/) および [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力している Sam Thomas 氏 [(https://eshu.co.uk/)](https://eshu.co.uk/)
-   MS09-003 で説明している問題について報告してくださった [VoIPshield Systems](https://www.voipshield.com/)
-   MS09-004 で説明している問題について報告してくださった [SEC Consult Vulnerability Lab](https://www.sec-consult.com/) の Bernhard Mueller 氏
-   MS09-005 で説明している問題について報告してくださった Bing Liu の Fortinet's [FortiGuard Global Security Research Team](https://www.fortiguardcenter.com/)

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などあり ましたら、[マイクロソフト セキュリティ 情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/02/11: このセキュリティ情報ページを公開しました。
-   2009/02/17: MS09-003 の影響を受けるソフトウェアに Microsoft Exchange Server MAPI クライアントを追加しました。
-   2009/02/26: このセキュリティ情報を更新し、MS09-003 の Exchange System Management Tools for Exchange Server 2003 に関連する注意を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
