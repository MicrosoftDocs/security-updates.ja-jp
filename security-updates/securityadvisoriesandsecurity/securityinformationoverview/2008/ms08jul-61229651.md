---
TOCTitle: 'MS08-JUL'
Title: 2008 年 7 月のセキュリティ情報
ms:assetid: 'ms08-jul'
ms:contentKeyID: 61229651
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms08-jul(v=Security.10)'
---

 

2008 年 7 月のセキュリティ情報
==============================

公開日: 2008年7月9日 | 最終更新日: 2009年2月12日

**バージョン:** 1.0

絵でみるセキュリティ情報
------------------------

 
[MS08-037 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-037e.mspx)

[MS08-038 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-038e.mspx)

[MS08-039 : Exchange Server の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-039e.mspx)

[MS08-040 : SQL Server の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms08-040e.mspx)

このセキュリティ情報は 2008 年 7 月に公開したセキュリティ情報の一覧です。

2008 年 7 月のセキュリティ情報の公開により、2008 年 7 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2008 年 7 月 9 日 午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[7 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357221&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

日本語版の Webcast 情報は 2008 年 7 月 9 日 の午後 (日本時間) に配信予定です。 詳細は、 「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

重要 (4)
--------

 

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-037                                                                                                                                                                                                                                                                                                                                                                       |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**DNS の脆弱性により、なりすましが行われる (953230)**](http://technet.microsoft.com/security/bulletin/ms08-037)                                                                                                                                                                                                                                                                                               |
| **概要**                     | このセキュリティ更新プログラムは非公開で報告された Windows ドメイン ネーム システム (DNS) に存在する 2 つの脆弱性を解決します。これらの脆弱性により、なりすましが行われる可能性があります。これらの脆弱性は DNS クライアントと DNS サーバーの両方に存在し、リモートの攻撃者は攻撃者のインターネット上のコンピュータに向いたネットワーク トラフィックを攻撃者のコンピュータにリダイレクトする可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                  |
| **脆弱性の影響**             | なりすまし                                                                                                                                                                                                                                                                                                                                                                                                     |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要です。                                                                                                                                                                                                                                        |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                               |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-038                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Windows エクスプローラの脆弱性により、リモートでコードが実行される (950582)**](http://technet.microsoft.com/security/bulletin/ms08-038)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **概要**                     | このセキュリティ更新プログラムは、特別な細工がされた保存された検索ファイルが開かれ、保存された場合、リモートでコードが実行される可能性のある Windows エクスプローラに存在する一般に公開された脆弱性を解決します。ユーザーが管理者ユーザー権限でログオンしている場合、この脆弱性が悪用されると、攻撃者により影響を受けるコンピュータが完全に制御される可能性があります。その後、攻撃者はプログラムをインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピュータのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要です。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **影響を受けるソフトウェア** | **Microsoft Windows.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
<p></p>
<p></p>
<p></p>


| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-039                                                                                                                                                                                                                                                                                                                                                  |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Exchange Server の Outlook Web Access の脆弱性により、特権の昇格が起こる (953747)**](http://technet.microsoft.com/security/bulletin/ms08-039)                                                                                                                                                                                                                                          |
| **概要**                     | このセキュリティ更新プログラムは非公開で報告された 2 件の Microsoft Exchange Server の Outlook Web Access (OWA) の脆弱性を解決します。 攻撃者がこれらの脆弱性を悪用した場合、OWA の各クライアントのセッション データへのアクセス権を取得し、特権を昇格する可能性があります。その後、攻撃者は各クライアントの OWA セッションでユーザーが実行可能なすべての動作を実行する可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                             |
| **脆弱性の影響**             | 特権の昇格                                                                                                                                                                                                                                                                                                                                                                                |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                                                                                       |
| **影響を受けるソフトウェア** | **Microsoft Exchange Server.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                                                                                                  |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS08-040                                                                                                                                                                                                                                                                                  |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [**Microsoft SQL Server の脆弱性により、特権が昇格される (941203)**](http://technet.microsoft.com/security/bulletin/ms08-040)                                                                                                                                                                                             |
| **概要**                     | このセキュリティ更新プログラムは、非公開で報告された 4 件の脆弱性を解決します。この脆弱性により、攻撃者がコードを実行し、コンピュータが完全に制御される可能性があります。認証された攻撃者は、プログラムのインストール、データの表示、変更、削除、または完全な管理者権限を持つ新たなアカウントを作成する可能性があります。 |
| **最大深刻度**               | [重要](http://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                             |
| **脆弱性の影響**             | 特権の昇格                                                                                                                                                                                                                                                                                                                |
| **検出**                     | Microsoft Baseline Security Analyzer は、この更新プログラムがご使用のコンピュータに必要であるかについて検出できます。このセキュリティ更新プログラムは再起動が必要な場合があります。                                                                                                                                       |
| **影響を受けるソフトウェア** | **Microsoft Windows, Microsoft SQL Server.** 詳細情報は、下記のリンクの事前通知の Web ページの「影響を受けるソフトウェア」のセクションをご覧ください。                                                                                                                                                                    |

影響を受けるソフトウェアおよびダウンロード先
--------------------------------------------

 
**この表はどのように使用しますか?**

この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新 プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが 記載されている場 合、脆弱性の深刻度も記載されています。

**注:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。

#### Windows オペレーティング システム

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
DNS クライアントのセキュリティ更新プログラム:  
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=269c219c-9d6b-4b12-b621-c70cd07cdd22&displaylang=ja)  
(重要)  
DNS サーバーのセキュリティ更新プログラム:  
[Microsoft Windows 2000 Server Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=332aa92f-a1ad-42a0-87d0-485d2d41335b&displaylang=ja)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
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
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
DNS クライアントのセキュリティ更新プログラム:  
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=ed989a33-7a9e-4423-93a8-b38907467cdf&displaylang=ja)  
(重要)  
DNS サーバー対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
DNS クライアントのセキュリティ更新プログラム:  
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a2b016fa-b108-4e8e-b41b-4ca89002907b&displaylang=ja)  
(重要)  
DNS サーバー対象外
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
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
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=1c0ae18b-1f17-44b3-a337-b36e7de437a7&displaylang=ja)  
(KB948110)  
(重要)  
[Windows Internal Database (WYukon) Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf&displaylang=ja)  
(KB948109)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
DNS クライアントのセキュリティ更新プログラム:  
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4ef5033c-9843-4e0b-bfad-fcaf05d7dab9&displaylang=ja)  
(重要)  
DNS サーバーのセキュリティ更新プログラム:  
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d1fcb794-e6a5-4c28-b3b3-9cd88f468a42&displaylang=ja)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=1c0ae18b-1f17-44b3-a337-b36e7de437a7&displaylang=ja)  
(KB948110)  
(重要)  
[Windows Internal Database (WYukon) x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf&displaylang=ja)  
(KB948109)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
DNS クライアントのセキュリティ更新プログラム:  
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=66624a1f-38bf-4af7-936d-3131474ffe1f&displaylang=ja)  
(重要)  
DNS サーバーのセキュリティ更新プログラム:  
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=040a1ba8-21b0-439e-bf21-1acd1c43b162&displaylang=ja)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
DNS クライアントのセキュリティ更新プログラム:  
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=facc80da-61d6-49c5-872d-a1980b66ae3e&displaylang=ja)  
(重要)  
DNS サーバーのセキュリティ更新プログラム:  
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=c63e3ee6-6055-4313-b0f1-fec7408886bb&displaylang=ja)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista および Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=06739ca6-7368-4acb-bb67-7e8146071a29&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
DNS クライアント対象外  
DNS サーバー対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=74ea0893-7c2f-4fad-ad27-588ad953b046&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
DNS クライアント対象外  
DNS サーバー対象外
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS08-040**](http://technet.microsoft.com/security/bulletin/ms08-040)
</td>
<td style="border:1px solid black;">
[**MS08-038**](http://technet.microsoft.com/security/bulletin/ms08-038)
</td>
<td style="border:1px solid black;">
[**MS08-037**](http://technet.microsoft.com/security/bulletin/ms08-037)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf&displaylang=ja)\*  
(KB948109)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=189a4170-b495-4904-9cbd-209e7494d303&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
DNS クライアント対象外  
DNS サーバーのセキュリティ更新プログラム:  
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?familyid=1fcea8f4-b233-42e1-b913-c4fcae276c7b&displaylang=ja)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f6aaa5-49fc-4a16-bc34-8514e214b8cf&displaylang=ja)\*  
(KB948109)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=85d8701d-f8c7-4079-8a21-a3a9d5ba71ce&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
DNS クライアント対象外  
DNS サーバーのセキュリティ更新プログラム:  
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=afac5bbc-71fa-457b-8b0a-f5902d37bfd0&displaylang=ja)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=b30ee4f0-850f-4ff3-86a4-663603a0a802&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
DNS クライアント対象外  
DNS サーバー対象外
</td>
</tr>
</table>

<p></p>

 
**\*Windows Server 2008 Server Core は、この脆弱性の影響を受けます。** サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度が適用されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 の特定のエディションには適用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

#### Microsoft サーバーソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<caption>Microsoft SQL Server</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-040"><strong>MS08-040</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 7.0 Service Pack 4</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0&amp;displaylang=ja">SQL Server 7.0 Service Pack 4</a><br />
(KB948113)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0&amp;displaylang=ja">SQL Server 7.0 Service Pack 4</a><br />
(KB948113)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2000 Service Pack 4</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e&amp;displaylang=ja">SQL Server 2000 Service Pack 4</a><br />
(KB948110)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4&amp;displaylang=ja">SQL Server 2000 Service Pack 4</a><br />
(KB948111)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2000 Itanium-based Edition Service Pack 4</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e&amp;displaylang=ja">SQL Server 2000 Itanium-based Edition Service Pack 4</a><br />
(KB948110)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4&amp;displaylang=ja">SQL Server 2000 Itanium-based Edition Service Pack 4</a><br />
(KB948111)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2005 Service Pack 2</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7&amp;displaylang=ja">SQL Server 2005 Service Pack 2</a><br />
(KB948109)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3&amp;displaylang=ja">SQL Server 2005 Service Pack 2</a><br />
(KB948108)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005 x64 Edition Service Pack 2</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7&amp;displaylang=ja">SQL Server 2005 x64 Edition Service Pack 2</a><br />
(KB948109)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3&amp;displaylang=ja">SQL Server 2005 x64 Edition Service Pack 2</a><br />
(KB948108)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQL Server 2005 with SP2 for Itanium-based Systems</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7&amp;displaylang=ja">SQL Server 2005 with SP2 for Itanium-based Systems</a><br />
(KB948109)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3&amp;displaylang=ja">SQL Server 2005 with SP2 for Itanium-based Systems</a><br />
(KB948108)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Data Engine (MSDE) 1.0 Service Pack 4</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0&amp;displaylang=ja">Microsoft Data Engine (MSDE) 1.0 Service Pack 4</a><br />
(KB948113)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=c95b2cb3-51a4-44e4-b9f4-9416e9ce16a0&amp;displaylang=ja">Microsoft Data Engine (MSDE) 1.0 Service Pack 4</a><br />
(KB948113)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4fd1f86a-94a2-43d8-9b0a-774c81426d9e&amp;displaylang=ja">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</a><br />
(KB948110)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8316bc5e-8c2d-4710-8acc-b815ccc81cd4&amp;displaylang=ja">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</a><br />
(KB948111)<br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft SQL Server 2005 Express Edition Service Pack 2</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7&amp;displaylang=ja">Microsoft SQL Server 2005 Express Edition Service Pack 2</a><br />
(KB948109)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3&amp;displaylang=ja">Microsoft SQL Server 2005 Express Edition Service Pack 2</a><br />
(KB948108)<br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft SQL Server 2005 Express Edition with Advanced Services Service Pack 2</td>
<td style="border:1px solid black;">GDR のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=4c9851cc-2c4c-4190-872c-84993a7623b7&amp;displaylang=ja">Microsoft SQL Server 2005 Express Edition with Advanced Services Service Pack 2</a><br />
(KB948109)<br />
(重要)<br />
<br />
QFE のセキュリティ更新プログラム:<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a60bb7e7-ef4e-4cbd-b63a-0ad7bd1402b3&amp;displaylang=ja">Microsoft SQL Server 2005 Express Edition with Advanced Services Service Pack 2</a><br />
(KB948108)<br />
(重要)</td>
</tr>
</tbody>
</table>

<p></p>

 

 
<p></p>

<table style="border:1px solid black;">
<caption>Microsoft Exchange Server</caption>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID 番号</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms08-039"><strong>MS08-039</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>最大深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating"><strong>重要</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Server 2003 Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e099c1d1-5af6-4d6c-b735-9599412b3131&amp;displaylang=ja">Microsoft Exchange Server 2003 Service Pack 2</a><br />
(重要)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Exchange Server 2007</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=086a2a13-a1de-4b1d-bd12-b148bfd2dafa&amp;displaylang=ja">Microsoft Exchange Server 2007</a><br />
(重要)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Exchange Server 2007 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=63e7f26c-92a8-4264-882d-f96b348c96ab&amp;displaylang=ja">Microsoft Exchange Server 2007 Service Pack 1</a><br />
(重要)</td>
</tr>
</tbody>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピュータに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、 [TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では 、製品に関するセキュリティ情報を提供して います。

コンシューマのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security_patch)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。

最後にセキュリティ更新プログラムは、[Microsoft Update カタログ](http://catalog.update.microsoft.com/v7/site/install.aspx)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ番号 (例えば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダにダウンロードできます。「Microsoft Update カタログ」の関連情報を参照するには、[Microsoft Update カタログ「よく寄せられる質問」](http://catalog.update.microsoft.com/v7/site/faq.aspx)をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer** **および** **Enterprise Update Scan Tool**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、 [Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ 確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、 Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003、および SQL Server 2000 用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピュータへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   [Microsoft Knowledge Base Article 894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): 2008 年のコンテンツでは、Software Update Services (SUS) および Windows Server Update Services (WSUS) の情報が変更されました。すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プ ログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [Microsoft ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)か らダウンロードすることができます。「security update」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれ ます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリース の ISO CD イメージをマイクロソフト ダウンロード セ ンターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) を ご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについ てそのほかの IT プロフェッショナルとの情報交換を 行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS08-037 に説明されている問題について報告してくださった [IOActive](http://www.ioactive.com/) の Dan Kaminsky 氏
-   MS08-039 に説明されている問題について報告してくださった [Context Information Security 社](http://www.contextis.co.uk/) の Michael Jordan 氏
-   MS08-040 に説明されている問題について報告してくださった匿名の発見者
-   MS08-040 に説明されている問題について報告してくださった匿名の発見者
-   [iDefense VCP](http://labs.idefense.com/) と協力し、MS08-040 に説明されている問題について報告してくださった [Insomnia Security](http://www.insomniasec.com/) の Brett Moore 氏
-   MS08-040 に説明されている問題について報告してくださった匿名の発見者

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、 [マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフト では、お問い合わせの内容が弊社製品の不具合が原 因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。（Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2008/07/9: このセキュリティ情報ページを公開しました。
-   2009/02/12: 「影響を受けるソフトウェアおよびそのダウンロード先」 の Windows オペレーティング システムの表で MS08-040 の Windows 2000 Service Pack 4 の Microsoft SQL Server 2000 Desktop Engine (WMSDE) に関する誤った記載を削除しました。

*Built at 2014-04-18T01:50:00Z-07:00*
