---
TOCTitle: 'MS11-FEB'
Title: 'マイクロソフト セキュリティ情報の事前通知 - 2012 年 2 月'
ms:assetid: 'ms11-feb'
ms:contentKeyID: 61229685
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-feb(v=Security.10)'
--- Summary

マイクロソフト セキュリティ情報の事前通知 - 2012 年 2 月
========================================================

公開日: 2012年2月15日

**バージョン:** 1.0

これはマイクロソフトが 2011 年 2 月 15 日に公開を予定しているセキュリティ情報の事前通知です。

このセキュリティ情報の事前通知は、2011 年 2 月 15 日に「2 月のセキュリティ情報」に置き換わります。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/ja-jp/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 2 月 15 日 の午後 (日本時間) に配信予定です。詳細は、「今月のワンポイント セキュリティ情報」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2011 年 2 月 15 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。 [2 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032499501) 詳細は、 [Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletinarchive) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----

 
事前通知では、セキュリティ情報 ID として、「セキュリティ情報 x」という形式を使用しています。マイクロソフト セキュリティ情報の公開時までセキュリティ情報 ID を発行していないためです。事前通知を 2 月のセキュリティ情報に置き換える際に、「セキュリティ情報 x」をマイクロソフト セキュリティ情報 ID (MSyy-xxx 形式) に置き換えます。今月のセキュリティ情報を深刻度別に下記に示します。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」をご覧ください。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動の必要性</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">セキュリティ情報 1</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">セキュリティ情報 2</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">セキュリティ情報 3</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">セキュリティ情報 4</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">セキュリティ情報 5</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">セキュリティ情報 6</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">セキュリティ情報 7</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">セキュリティ情報 8</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">セキュリティ情報 9</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
影響を受けるソフトウェア  
------------------------
  
 
事前通知では、セキュリティ情報 ID として、「セキュリティ情報 x」という形式を使用しています。マイクロソフト セキュリティ情報の公開時までセキュリティ情報 ID を発行していないためです。事前通知を 2 月のセキュリティ情報に置き換える際に、「セキュリティ情報 x」をマイクロソフト セキュリティ情報 ID (MSyy-xxx 形式) に置き換えます。今月のセキュリティ情報を深刻度別に下記に示します。
  
影響を受けるソフトウェアの詳細は、次の影響を受けるソフトウェアのセクションをご覧ください。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリテ ィ更新プログラムがあるかどうかを確認してください。 ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度 が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="8">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 1
</td>
<td style="border:1px solid black;">
セキュリティ情報 2
</td>
<td style="border:1px solid black;">
セキュリティ情報 3
</td>
<td style="border:1px solid black;">
セキュリティ情報 4
</td>
<td style="border:1px solid black;">
セキュリティ情報 5
</td>
<td style="border:1px solid black;">
セキュリティ情報 7
</td>
<td style="border:1px solid black;">
セキュリティ情報 8
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(警告)  
Internet Explorer 7  
(緊急)  
Internet Explorer 8  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(警告)  
Internet Explorer 7  
(緊急)  
Internet Explorer 8  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 1
</td>
<td style="border:1px solid black;">
セキュリティ情報 2
</td>
<td style="border:1px solid black;">
セキュリティ情報 3
</td>
<td style="border:1px solid black;">
セキュリティ情報 4
</td>
<td style="border:1px solid black;">
セキュリティ情報 5
</td>
<td style="border:1px solid black;">
セキュリティ情報 7
</td>
<td style="border:1px solid black;">
セキュリティ情報 8
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
Windows Server 2003 Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(深刻度なし<sup>[1]</sup>)  
Internet Explorer 7  
(警告)  
Internet Explorer 8  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(重要)
</td>
<td style="border:1px solid black;">
対象外
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
Windows Server 2003 x64 Edition Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(深刻度なし<sup>[1]</sup>)  
Internet Explorer 7  
(警告)  
Internet Explorer 8  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(重要)
</td>
<td style="border:1px solid black;">
対象外
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
Windows Server 2003 with SP2 for Itanium-based Systems  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(深刻度なし<sup>[1]</sup>)  
Internet Explorer 7  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 1
</td>
<td style="border:1px solid black;">
セキュリティ情報 2
</td>
<td style="border:1px solid black;">
セキュリティ情報 3
</td>
<td style="border:1px solid black;">
セキュリティ情報 4
</td>
<td style="border:1px solid black;">
セキュリティ情報 5
</td>
<td style="border:1px solid black;">
セキュリティ情報 7
</td>
<td style="border:1px solid black;">
セキュリティ情報 8
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(緊急)  
Internet Explorer 8  
(緊急)  
Internet Explorer 9  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(緊急)  
Internet Explorer 8  
(緊急)  
Internet Explorer 9  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 1
</td>
<td style="border:1px solid black;">
セキュリティ情報 2
</td>
<td style="border:1px solid black;">
セキュリティ情報 3
</td>
<td style="border:1px solid black;">
セキュリティ情報 4
</td>
<td style="border:1px solid black;">
セキュリティ情報 5
</td>
<td style="border:1px solid black;">
セキュリティ情報 7
</td>
<td style="border:1px solid black;">
セキュリティ情報 8
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7\*\*  
(警告)  
Internet Explorer 8\*\*  
(警告)  
Internet Explorer 9\*\*  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7\*\*  
(警告)  
Internet Explorer 8\*\*  
(警告)  
Internet Explorer 9\*\*  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2\*  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 1
</td>
<td style="border:1px solid black;">
セキュリティ情報 2
</td>
<td style="border:1px solid black;">
セキュリティ情報 3
</td>
<td style="border:1px solid black;">
セキュリティ情報 4
</td>
<td style="border:1px solid black;">
セキュリティ情報 5
</td>
<td style="border:1px solid black;">
セキュリティ情報 7
</td>
<td style="border:1px solid black;">
セキュリティ情報 8
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(緊急)  
Internet Explorer 9  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(緊急)  
Internet Explorer 9  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 1
</td>
<td style="border:1px solid black;">
セキュリティ情報 2
</td>
<td style="border:1px solid black;">
セキュリティ情報 3
</td>
<td style="border:1px solid black;">
セキュリティ情報 4
</td>
<td style="border:1px solid black;">
セキュリティ情報 5
</td>
<td style="border:1px solid black;">
セキュリティ情報 7
</td>
<td style="border:1px solid black;">
セキュリティ情報 8
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 8\*\*  
(警告)  
Internet Explorer 9\*\*  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1\*  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 

Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。 サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*\*\*Server Core インストールは影響を受けます。 サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムの深刻度は低くなります。このインストール オプションの詳細については、TechNet の記事 [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

セキュリティ情報 2 に関する注意

<sup>[1]</sup>このセキュリティ情報で説明されている脆弱性のための既知の攻撃ベクトルは、規定の構成ではブロックされるため、深刻度は指定のソフトウェアに対するセキュリティ更新にはあてはまりません。しかし多重防護の基準により、マイクロソフトはこのソフトウェアの使用者がこのセキュリティ更新を適用することを推奨します。

セキュリティ情報 4 に関する注意

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile は影響を受けます。.NET Framework Version 4 再頒布可能パッケージは、.NET Framework 4 および .NET Framework 4 Client Profile の 2 つのプロファイルで使用可能です。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムが対応する脆弱性は、.NET Framework 4 および .NET Framework 4 Client Profile のどちらにも影響します。詳細については、MSDN の記事、「[.NET Framework のインストール](http://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

「影響を受けるソフトウェア」のセクションのその他のソフトウェア カテゴリもご覧ください。同じセキュリティ情報番号の更新プログラム ファイルが複数あります。このセキュリティ情報は 1 種類以上のソフトウェアを対象にしています。

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 9
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 および Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 および Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 および Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 および Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 

#### Microsoft Server ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 6
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 および Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 および Microsoft SharePoint Server 2010 Service Pack 1  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 6
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 および Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 および Microsoft SharePoint Foundation 2010 Service Pack 1 (sts)  
(重要)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft 開発者ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
セキュリティ情報 4
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 4  
(緊急)
</td>
</tr>
</table>

<p></p>

 
セキュリティ情報 4 に関する注意

「影響を受けるソフトウェア」のセクションのその他のソフトウェア カテゴリもご覧ください。同じセキュリティ情報番号の更新プログラム ファイルが複数あります。このセキュリティ情報は 1 種類以上のソフトウェアを対象にしています。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキ ュリティ更新プログラムを管理してください。 詳細については、TechNet 更新プログラム管理センターを参照してください。 [セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。 一般のお客様は[セーフティとセキュリティ センター](http://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることで もアクセスできます。

セキュリティ更新プログラムは、Microsoft Update および [Windows Update](http://go.microsoft.com/fwlink/?%20linkid=21130) から入手できます。 セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&amp;freetext=%u30bb%u30ad%u30e5%u30ea%20%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&amp;displaylang=ja)からもダウンロードすることができます。 「セキュリティ更新プログラム」のキーワード 探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中の マイクロソフトのソフトウェアを最新に保つことができます。 Microsoft AutoUpdate for Mac のご利用の詳細については 、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-%20c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、Microsoft Update カタログからダウンロードできます。 Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタロ グで、Windows Update および Microsoft Update でご利用になれます。 セキュリティ情報番号 (例えば「MS07-036」など ) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを 含む)、選択しているフォルダーにダウンロードできます。 「Microsoft Update カタログ」の詳細については、Microsoft Update カタログ よく寄せられる質問を参照してください。

検出および適用のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および適用に関して、ガイダンスを提供しています 。 このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および適用のための多様なツールの 使用方法を理解するのに役立つ推奨策および情報が含まれています。 詳細については、サポート技術情報 961747 を参照し てください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピュ ーターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。 MBSA の詳細については、Microsoft Baseline Security Analyzer を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペ レーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレー ティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセ キュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

System Center Configuration Manager 2007

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの 配布や管理の複雑なタスクを簡素化します。 Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プ ログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することがで きます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨 されるアクションについて報告します。 Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者 によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいていま す。 管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、ソフトウェアの更新管理を参照してください。 Configuration Manager の詳細については、 [System Center Configuration Manager](http://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企 業向けソリューションを提供します。 SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースの システムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することが できます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って 、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、マイクロソフト サポート ライフサイクルを参照してください。 現在利用可能な SMS の後 継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management (英語情報) を参照してください。 SMS の詳細につ いては、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注: SMS は Microsoft Baseline Security Analyzer を使用して、セ キュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。 これらのツールにより 検出されないソフトウェアの更新プログラムもあります。 管理者は、特定のシステムに対する更新プログラムを対象とし 、これらの場合に SMS のインベントリ機能を使用することができます。 この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。 コンピューターの再起動後、管理者 権限を必要とするセキュリティ更新プログラムもあります。 管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja-nec) で入手可 能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込 みをすることがあります。 これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったり する可能性があります。 [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) ( 英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報 ) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効 率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケ ーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開する予定です。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/): Software Update Services の説明と Windows Server Update Services の内容の変更。すべての Windows のコンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報): Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) パートナー](http://www.microsoft.com/ja-jp/security/msrc/mapp.aspx)に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の戦略

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策 に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?%20pocid=&amp;freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%20%u30b0%u30e9%u30e0&amp;displaylang=ja)からもダウンロードできます。 「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマ プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウ ンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。 詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086) を 参照してください。

IT Pro セキュリティ コミュニティ

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピック について他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナ ル セキュリティ コミュニティ](http://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。 そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバー ジョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありまし たら、[マイクロソフト セキュ リティ情報センター](http://www.microsoft.com/ja-jp/security/sic.aspx)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因で ある場合、無償でサポートをご提供いたします。 利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/)を参照 してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポート をご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[世界のヘルプとサポート](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

*Built at 2014-04-18T01:50:00Z-07:00*
