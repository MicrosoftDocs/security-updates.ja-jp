---
TOCTitle: 'MS10-MAY'
Title: 2010 年 5 月のセキュリティ情報
ms:assetid: 'ms10-may'
ms:contentKeyID: 61229678
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-may(v=Security.10)'
--- Summary

2010 年 5 月のセキュリティ情報
==============================

公開日: 2010年5月12日 | 最終更新日: 2010年5月20日

**バージョン:** 1.0

[![](../../images/Dn627257.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627257.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS10-030 : Outlook Express と Windows メールの重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-030e.mspx)

[MS10-031 : Office の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-031e.mspx)

このセキュリティ情報は 2010 年 5 月 12 日に公開したセキュリティ情報の一覧です。

2010 年 5 月 12 日のセキュリティ情報の公開により、2010 年 5 月 7 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 5 月 12 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2010 年 5 月 12 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[5 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427724&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-030">MS10-030</a></td>
<td style="border:1px solid black;"><strong>Outlook Express および Windows メールの脆弱性により、リモートでコードが実行される (978542)</strong><br />
<br />
このセキュリティ更新プログラムは Outlook Express、Windows メールおよび Windows Live メールに存在する非公開で報告された脆弱性を解決します。この脆弱性により、ユーザーが悪意のある電子メール サーバーに接続した場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-031">MS10-031</a></td>
<td style="border:1px solid black;"><strong>Microsoft Visual Basic for Applications (VBA) の脆弱性により、リモートでコードが実行される (978213)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Visual Basic for Applications に存在する脆弱性を解決します。この脆弱性は、ホスト アプリケーションが特別に細工されたファイルを表示し、Visual Basic for Applications ランタイムに渡す場合に、リモートでコードが実行される可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft Visual Basic for Applications</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用の可能性が高いものから順に、次に CVE ID の順に記載しています。セキュリティ情報に記載されている深刻度が緊急または重要の脆弱性のみです。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID                                                 | 脆弱性タイトル                                                    | CVE ID                                                                           | Exploitability Index の評価                                                                     | 注意事項                                                                                                                        |  
|---------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-031](http://technet.microsoft.com/security/bulletin/ms10-031) | VBE6.DLL スタック メモリの破損の脆弱性                            | [CVE-2010-0815](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0815) | [**2**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性 | (なし)                                                                                                                          |  
| [MS10-030](http://technet.microsoft.com/security/bulletin/ms10-030) | Outlook Express および Windows メールの整数オーバーフローの脆弱性 | [CVE-2010-0816](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0816) | [**2**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性 | ヒープを保護するセキュリティ強化により、Windows Vista およびそれ以降のオペレーティング システムでの悪用の可能性は低くなります。 |
  
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
</tr>
<tr>
<th colspan="2">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 5.5 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=661f5de3-a593-4961-8e8d-2777797eb5c5)  
(KB978542)  
(緊急)  
[Microsoft Outlook Express 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cda75174-b535-4559-a52d-b5ec3a1df349)  
(KB978542)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=99707c3d-a3cb-47da-b38e-8ae0227fd703)  
(KB978542)  
(緊急)  
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=99707c3d-a3cb-47da-b38e-8ae0227fd703) <sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=44bc97bb-6f76-4c96-af72-69daaea80fff)  
(KB978542)  
(緊急)  
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=44bc97bb-6f76-4c96-af72-69daaea80fff) <sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=eb9742fc-0934-4b38-9ec4-3597fc71ec00)  
(KB978542)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5678515a-97ea-4e00-8700-d3f2fcdc0efc)  
(KB978542)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft Outlook Express 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=60ef635b-cb6d-402f-b904-e69b519d797f)  
(KB978542)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a970c869-24fe-4ef4-b189-7a6bac2411f1)  
(KB978542)  
(緊急)  
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a970c869-24fe-4ef4-b189-7a6bac2411f1) <sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9a7853b5-4f9f-4467-9530-eea2efd504a5)  
(KB978542)  
(緊急)  
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9a7853b5-4f9f-4467-9530-eea2efd504a5) <sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5f77a640-247c-4ed2-9fca-4b7344f4dc7c)\*\*  
(KB978542)  
(緊急)  
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5f77a640-247c-4ed2-9fca-4b7344f4dc7c)\*\*<sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b0eab011-5847-44e4-bc0d-5c5355e1e8d0)\*\*  
(KB978542)  
(緊急)  
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b0eab011-5847-44e4-bc0d-5c5355e1e8d0)\*\*<sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=da01ae82-895e-4739-916f-a63b9095a076)  
(KB978542)  
(緊急)  
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=da01ae82-895e-4739-916f-a63b9095a076) <sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1f0c17be-ba4c-4a1c-b9c3-8ac368800947) <sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a70f15e1-512c-44ca-a308-928e237ac0ce) <sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-030**](http://technet.microsoft.com/security/bulletin/ms10-030)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2e25c02-38ce-4868-a01a-39fc7d2a4150)\*\*<sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Live メール](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=53ed1055-b5ee-4fde-9550-f8b401916467) <sup>[1]</sup>
(KB978542)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*\*Server Core インストールは影響を受けません。** この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用してインストールした場合、サポートされているエディションの Windows Server 2008 および Windows Server 2008 R2 に影響を与えません。このインストール オプションに関する詳細情報は MSDN コラム [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英語情報) および [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(en-us,vs.85).aspx) (英語情報) をご覧ください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/r2-compare-core-installation.aspx) (英語情報) をご覧ください。

**MS10-030 の注意**

<sup>[1]</sup> Windows Live メールは、このオペレーティング システムでは既定でインストールされておらず、これを別途インストールした場合に、この脆弱性が存在します。

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
Microsoft Office スイート、システムおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-031**](http://technet.microsoft.com/security/bulletin/ms10-031)
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
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3 <sup>[1]</sup>](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=72c23b0f-4e24-4334-bc8a-334adc8bc42b)  
(KB976380)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3 <sup>[1]</sup>](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f8eac9bc-8389-4ac8-8b29-9a8180d9fd34)  
(KB976382)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System Service Pack 1 および 2007 Microsoft Office System Service Pack 2 <sup>[1]</sup>](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=160ad53e-6475-4550-90c2-444e4abea730)  
(KB976321)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**MS10-031 に関する注意**

<sup>[1]</sup> Microsoft Office 用のこれらの更新プログラムはすべてのサポートされている Microsoft Office スイートおよびこの脆弱性の影響を受ける共有 Office コンポーネントを含むその他の Microsoft Office ソフトウェアに適用されます。これらの例としては、サポートされているバージョンの Microsoft Office Visio および Microsoft Office Project などがあります。

この「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリもご覧ください。同じセキュリティ情報 ID の更新プログラムがあります。このセキュリティ情報は複数のソフトウェア カテゴリに該当しています。

#### Microsoft 開発ツールおよびソフトウェア

 
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
Microsoft Visual Basic for Applications
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-031**](http://technet.microsoft.com/security/bulletin/ms10-031)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic for Applications](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=436a8a66-352e-44d1-a610-c825083ad24a) <sup>[1]</sup>
(KB974945)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK
</td>
<td style="border:1px solid black;">
Microsoft Visual Basic for Applications SDK <sup>[2]</sup><sup>[3]</sup>
(緊急)
</td>
</tr>
</table>

<p></p>

 
**MS10-031 に関する注意**

<sup>[1]</sup> この更新プログラムのパッケージは、サポートされているバージョンの Microsoft Visual Basic for Applications ランタイム (Vbe6.dll) に適用され、マイクロソフト ダウンロード センターからのみご利用可能です。

<sup>[2]</sup> サポートされるバージョンの VBA SDK は、Microsoft Visual Basic for Applications SDK 6.3、Microsoft Visual Basic for Applications SDK 6.4 および Microsoft Visual Basic for Applications SDK 6.5 です。

<sup>[3]</sup> このセキュリティ情報で説明している脆弱性を解決する独立系ソフトウェア ベンダー (ISV) 向けの更新されたバージョンの Visual Basic for Applications SDK は、[Summit Software Company](http://www.summsoft.com/) からご利用できます。

この「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリもご覧ください。同じセキュリティ情報 ID の更新プログラムがあります。このセキュリティ情報は複数のソフトウェア カテゴリに該当しています。

検出および展開ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**注:** 2009 年 8 月 1 日より、マイクロソフトは Office Update および Office Update Inventory Tool のサポートを終了します。Microsoft Office 製品用の最新の更新プログラムを引き続き入手するためには、[Microsoft Update](http://update.microsoft.com/microsoftupdate/) をご利用ください。詳細情報は、[About Microsoft Office Update: Frequently Asked Questions](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英語情報) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトはセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [961747](http://support.microsoft.com/kb/961747) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

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

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2010 年). すべての Windows のコンテンツが含まれます。
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

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS10-030 で説明している 1 つの問題について報告してくださった Protek Research Lab の Francis Provencher 氏
-   MS10-031 で説明している 1 つの問題について報告してくださった [NSFocus Security Team](http://www.nsfocus.com/)

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2010/05/12: このセキュリティ情報ページを公開しました。
-   2010/05/13: このセキュリティ情報ページを更新し、MS10-030 の再起動の要件を修正しました。
-   2010/05/20: このセキュリティ情報を更新し、Windows 7 および Windows Server 2008 R2 上の Windows メールに対する MS10-030 の誤った情報を削除しました。また、MS10-031 の影響を受けるソフトウェアに注意を追加し、すべてのサポートされる Microsoft Office スイートおよび影響を受けるバージョンの VBE6.dll が含まれているその他の Microsoft Office ソフトウェアに適用する Microsoft Office 用の更新プログラムの明確な説明を加えました。

*Built at 2014-04-18T01:50:00Z-07:00*
