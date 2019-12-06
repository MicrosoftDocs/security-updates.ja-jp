---
TOCTitle: 'MS07-SEP'
Title: 2007 年 9 月のセキュリティ情報
ms:assetid: 'ms07-sep'
ms:contentKeyID: 61229645
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms07-sep(v=Security.10)'
---

 

2007 年 9 月のセキュリティ情報
==============================

公開日: 2007年9月12日

**バージョン:** 1.0

イラストを交えたセキュリティ情報はこちらをご覧ください。

絵でみるセキュリティ情報
------------------------

 
[MS07-051 : Windows 2000 の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms07-051e.mspx)

[MS07-052 : Visual Studio の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms07-052e.mspx)

[MS07-053 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms07-053e.mspx)

[MS07-054 : MSN Messenger および Windows Live Messenger の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms07-054e.mspx)

このセキュリティ情報は、2007 年 9 月に公開したセキュリティ情報の一覧です。

2007 年 9 月のセキュリティ情報の公開により、2007 年 9 月 7 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2007 年 9 月 12 日午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032343783&eventcategory=4&culture=en-us&countrycode=us) (英語) をご覧ください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

#### 概要

今月のセキュリティ情報を深刻度別に下記に示します。

緊急 (1)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-051                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Microsoft エージェントの脆弱性により、リモートでコードが実行される (938827)](https://technet.microsoft.com/security/bulletin/ms07-051)                                                                                                                                                                                                                                                                                                                        |
| **概要**                     | この深刻度「緊急」の更新プログラムは非公開で報告された脆弱性を解決します。Microsoft エージェントが特定の特別な細工がされた URL を処理する方法にリモートでコードが実行される脆弱性が存在します。この脆弱性で、攻撃者により影響を受けるコンピュータでリモートでコードが実行される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [緊急](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                 |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **検出**                     | Microsoft Baseline Security Analyzer はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                                                                                                                               |
| **影響を受けるソフトウェア** | **Windows.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                     |

重要 (3)
--------

 
| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-052                                                                                                                                                                                                                                                                                                                                    |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Crystal Reports for Visual Studio の脆弱性により、リモートでコードが実行される (941522)](https://technet.microsoft.com/security/bulletin/ms07-052)                                                                                                                                                                                                                          |
| **概要**                     | この深刻度が「重要」のセキュリティ更新プログラムは、一般に公開された脆弱性を解決します。この脆弱性により、特別な細工がされた RPT ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                               |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                |
| **検出**                     | Microsoft Baseline Security Analyzer および Enterprise Update Scan Tool はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                          |
| **影響を受けるソフトウェア** | **Visual Studio.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                             |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-053                                                                                                                                                                                                                                                                                                                                                |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [Windows Services for UNIX の脆弱性により、特権の昇格が起こる (939778)](https://technet.microsoft.com/security/bulletin/ms07-053)                                                                                                                                                                                                                                                        |
| **概要**                     | この深刻度が「重要」の更新プログラムは、一般に公開された 1 件の脆弱性を解決します。特定の setuid バイナリ ファイルを実行している Windows Services for UNIX 3.0 および Windows Services for UNIX 3.5 および UNIX ベース アプリケーション用サブシステムに存在する脆弱性により、攻撃者が特権の昇格を行う可能性があります。この脆弱性で、攻撃者により特権の昇格が行われる可能性があります。 |
| **最大深刻度**               | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                           |
| **脆弱性の影響**             | 特権の昇格                                                                                                                                                                                                                                                                                                                                                                              |
| **検出**                     | Microsoft Baseline Security Analyzer および Enterprise Update Scan Tool はご使用のコンピュータにこの更新プログラムが必要であるかどうかを検出することができます。このセキュリティ更新プログラムは再起動を必要とする場合があります。                                                                                                                                                      |
| **影響を受けるソフトウェア** | **Windows Services for UNIX, UNIX ベースアプリケーション用サブシステム.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                              |

<p></p>
<p></p>
<p></p>

| セキュリティ情報 ID 番号     | マイクロソフト セキュリティ情報 MS07-054                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **タイトル**                 | [MSN Messenger および Windows Live Messenger の脆弱性により、リモートでコードが実行される (942099)](https://technet.microsoft.com/security/bulletin/ms07-054)                                                                                                                                                                                                                                                                                                                                                                |
| **概要**                     | この深刻度「重要」のセキュリティ更新プログラムは、MSN Messenger および Windows Live Messenger に存在する一般に公開された脆弱性を解決します。この脆弱性により、ユーザーが攻撃者からのビデオ チャットの誘いを受け入れた場合、リモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用し、影響を受けるコンピュータを完全に制御する可能性があります。コンピュータでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。 |
| **最大深刻度**               | [重要](https://technet.microsoft.com/security/bulletin/rating)                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **脆弱性の影響**             | リモートでコードが実行される                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **検出**                     | これらの製品は更新プログラムの自動検出および展開機能を実装しています。このセキュリティ更新プログラムは再起動を必要としません。                                                                                                                                                                                                                                                                                                                                                                                              |
| **影響を受けるソフトウェア** | **MSN Messenger, Windows Live Messenger.** 詳細な情報は、「影響を受けるソフトウェア」をご確認ください。                                                                                                                                                                                                                                                                                                                                                                                                                     |

影響を受けるソフトウェアおよびダウンロード先
--------------------------------------------

 
**この表はどのように使用しますか?**

この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウ ェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが 記載されている場合、脆弱性の深刻度も記載されています。

**注 :** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。 上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。

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
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[MS07-051](https://technet.microsoft.com/security/bulletin/ms07-051)
</td>
<td style="border:1px solid black;">
[MS07-052](https://technet.microsoft.com/security/bulletin/ms07-052)
</td>
<td style="border:1px solid black;">
[MS07-053](https://technet.microsoft.com/security/bulletin/ms07-053)
</td>
<td style="border:1px solid black;">
[MS07-054](https://technet.microsoft.com/security/bulletin/ms07-054)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<th colspan="5">
Windows オペレーティングシステム:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[緊急](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7cd248ed-d154-4dce-89ef-ceefd2700965)
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
Windows XP Service Pack 2
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
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
<th colspan="5">
Windows オペレーティング システム コンポーネント:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 2000 Service Pack 4 上の Windows Services for UNIX 3.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 2000 Service Pack 4 上の Windows Services for UNIX 3.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 上の Windows Services for UNIX 3.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 上の Windows Services for UNIX 3.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2 上の Windows Services for UNIX 3.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2 上の Windows Services for UNIX 3.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2 上の UNIX ベース アプリケーション用サブシステム
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8ab5cc43-0b9c-45eb-aa51-47568ab6ce3f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2 上の UNIX ベース アプリケーション用サブシステム
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1d21e3e8-b5f6-4044-9db6-054af836492b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Window Vista 上の UNIX ベース アプリケーション用サブシステム
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4d52e4f4-2888-42df-8163-85c648e65b29)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Window Vista x64 Edition 上の UNIX ベース アプリケーション用サブシステム
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4be667cc-c239-480b-a9a0-939bcd27f0de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
開発ツールおよびプラットフォーム:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2002 Service Pack 1  
(KB937057)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2608c83b-e1b2-4449-9a0e-1e566aac3d76) **<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2003  
(KB937058)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d612ad41-5a0d-4e13-99ea-d6a5589786d6) **<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 Service Pack 1  
(KB937059)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0b10b04b-932c-4bff-9cbc-b3eeb15064b1) **<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio 2005  
(KB937060)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=21073cc2-919c-40df-8ebb-aa3db06050d2) **<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio 2005 Service Pack 1  
(KB937061)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[重要](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=967d43c8-efba-4221-beb0-981e7deef33a) **<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
その他影響を受けるソフトウェア:
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 6.2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
MSN Messenger 7.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 7.5
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Live Messenger 8.0
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[3]</sup>**
</td>
</tr>
</table>

<p></p>

 
**備考**

**<sup>[1]</sup>** このプラットフォームで利用可能なセキュリティ更新プログラムがあります。詳細については、影響を受けるソフトウェアまたはコンポーネントの欄をご覧ください。

**<sup>[2]</sup>** Visual Studio のすべてのバージョンが影響を受けることはありません。影響を受ける特定のエディションの一覧については、該当するセキュリティ更新プログラムをご覧ください。

**<sup>[3]</sup>** このソフトウェアに対して利用可能なアップグレードがあります。詳細については、影響を受けるソフトウェアまたはコンポーネントの欄をご覧ください。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティセントラル**

組織のサーバー、デスクトップ、モバイル コンピュータに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、 [TechNet 更新プログラム管理](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet Security センター](https://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供して います。

コンシューマのお客様は [Security At Home](https://www.microsoft.com/japan/athome/security) をご覧ください。この情報は「最新のセキュ リティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](https://update.microsoft.com/microsoftupdate/)、[Windows Update](https://windowsupdate.microsoft.com/) および [Office Update](https://go.microsoft.com/fwlink/?%20linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/results.aspx?%20displaylang=ja&freetext=security_patch)からダウンロードすることができます。「security\_patch」のキ ーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の 関連情報を参照するには、サポート技術情報 [323166](https://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office Detection Tool、Microsoft Systems Management Server (SMS)、 Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに 役立ちます。詳細情報は、サポート技術情報 [910723](https://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer および Enterprise Update Scan Tool**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピュータやリモートコンピュータの未適用のセキュリティ更新プログラムの確認、一般的な セキュリティの設定の検査を行うことができます。MBSA の詳細情報は、[Microsoft Baseline Security Analyzer Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

MBSA 1.2.1 が検出できない特定のセキュリティ更新プログラムの場合、マイクロソフトは、特定のセキュリティ更新プログラム向けに Enterprise Update Scan Tool (EST) を公開しています。EST の詳細については、[Enterprise Update Scan Tool](https://support.microsoft.com/kb/894193) をご覧く ださい。

**注意:** 2007 年 10 月 9 日以降、MBSA 1.2.1 で使用されている MSSecure.XML ファイルは更新されなくなります。この日以降、 MBSA 1.2.1 で使用されている MSSecure.XML ファイルに新しいセキュリティ更新プログラムは追加されません。また、新しいバージョンの Enterprise Update Scan Tool はリリース されません。詳細情報については、[Microsoft Baseline Security Analyzer Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Software Update Services**

2007 年 7 月 10 日をもって、Software Update Services (SUS) 1.0 のサポートを終了しました。SUS 1.0 による製品サポートおよび更新プログラムの提供は、2007 年 7 月 11 日以降利用できません。詳細についてはサポート技術情報 [905682](https://support.microsoft.com/kb/905682)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003、および SQL Server 2000 用のセキュリティ更新プログラムに対応しています。Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、 管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピュータを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新 プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用の お客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコン ピュータへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピュータの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

今月:

-   マイクロソフトは Microsoft Update (MU) および Windows Server Update Services (WSUS) により、**セキュリティ以外**の優先度の高い更新プログラムを 0 件公開しました。
-   マイクロソフトは Windows Update (WU) で、Windows 用の**セキュリティ以外**の優先度の高い更新プログラムを 0 件公開しました。

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。そのほかの日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理の セキュリティ ガイド](https://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プ ログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [Microsoft ダウンロード センター](https://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security\_patch」 のキーワード探索によって容易に見つけることができます。
-   コンシューマ用プラットフォームの更新プログラムは、[Microsoft Update](https://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード セ ンターから入手することができます。詳細情報は、サポート技術情報 [913086](https://support.microsoft.com/kb/913086) を ご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてそのほかの IT プロフェッショナルとの情報交換を 行うためには、[IT Pro Security Community](https://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

マイクロソフトは顧客の保護のために協力して下さった、以下の方々に深い [謝意](https://technet.microsoft.com/security/bulletin/policy) を表します。

-   [MS07-051](https://technet.microsoft.com/security/bulletin/ms07-051) の問題を報告してくださった [Assurent Secure Technologies](https://www.assurent.com/) 社の Vulnerability Research チーム
-   [MS07-051](https://technet.microsoft.com/security/bulletin/ms07-051) の問題を報告してくださった [Palo Alto Networks](https://www.paloaltonetworks.com/) の Yamata Li 氏
-   [MS07-051](https://technet.microsoft.com/security/bulletin/ms07-051) の問題を報告してくださった [VeriSign iDEFENSE VCP](https://labs.idefense.com/) に協力している匿名のリサーチャー
-   [MS07-053](https://technet.microsoft.com/security/bulletin/ms07-053) の問題を報告してくださった [WolfeReiter](https://www.wolfereiter.com/) の Brian A. Reiter 氏
-   [MS07-054](https://technet.microsoft.com/security/bulletin/ms07-054) の問題を報告してくださった [team59](https://www.team509.com/) の Woo Shi 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原 因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報 の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または 書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連 会社 及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一 切責任を負いません。（Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害また は偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

*Built at 2014-04-18T01:50:00Z-07:00*
