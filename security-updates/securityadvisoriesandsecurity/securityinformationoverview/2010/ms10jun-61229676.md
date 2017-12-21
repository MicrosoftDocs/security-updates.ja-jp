---
TOCTitle: 'MS10-JUN'
Title: 2010 年 6 月のセキュリティ情報
ms:assetid: 'ms10-jun'
ms:contentKeyID: 61229676
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-jun(v=Security.10)'
--- Summary

2010 年 6 月のセキュリティ情報
==============================

公開日: 2010年6月9日 | 最終更新日: 2011年9月14日

**バージョン:** 1.0

[![](../../images/Dn627255.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627255.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS10-032 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-032e.mspx)

[MS10-033 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-033e.mspx)

[MS10-034 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-034e.mspx)

[MS10-035 : Internet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-035e.mspx)

[MS10-036 : Office の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-036e.mspx)

[MS10-037 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-037e.mspx)

[MS10-038 : Office の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-038e.mspx)

[MS10-039 : SharePoint の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-039e.mspx)

[MS10-040 : インターネット インフォメーション サービスの重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-040e.mspx)

[MS10-041 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms10-041e.mspx)

このセキュリティ情報は 2010 年 6 月に公開したセキュリティ情報の一覧です。

2010 年 6 月のセキュリティ情報の公開により、2010 年 6 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 6 月 9 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2010 年 6 月 9 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[6 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427727&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-033">MS10-033</a></td>
<td style="border:1px solid black;">メディア解凍の脆弱性により、リモートでコードが実行される (979902)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性で、ユーザーが特別に細工されたメディア ファイルを開くか、または Web サイトや Web コンテンツを配信するアプリケーションから特別な細工がされたストリーミング コンテンツを受け取った場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者によりローカル ユーザーと同じ権限が取得される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-034">MS10-034</a></td>
<td style="border:1px solid black;">ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (980195)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された 2 件のマイクロソフトのソフトウェアの脆弱性を解決します。このセキュリティ更新プログラムの深刻度はすべてのサポートされているエディションの Microsoft Windows 2000、Windows XP、Windows Vista および Windows 7 について「緊急」、すべてのサポートされているエディションの Windows Server 2003、Windows Server2008 および Windows Server 2008 R2 について「警告」と評価しています。詳細情報は、このセクションの「影響を受けるソフトウェアおよび影響を受けないソフトウェア」のサブセクションをご覧ください。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-035">MS10-035</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (982381)<br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する非公開で報告された 5 件の脆弱性と、一般に公開された 1 件の脆弱性を解決します。これらの脆弱性の中で最も深刻な脆弱性が悪用された場合、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、 Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-032">MS10-032</a></td>
<td style="border:1px solid black;">Windows カーネル モード ドライバーの脆弱性により、特権が昇格される (979559)<br />
<br />
このセキュリティ更新プログラムは Windows カーネル モード ドライバーに存在する 2 件の公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。これらの脆弱性により、ユーザーが特別な細工がされた TrueType フォントでレンダリングされたコンテンツを表示した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-036">MS10-036</a></td>
<td style="border:1px solid black;">Microsoft Office の COM の検証の脆弱性により、リモートでコードが実行される (983235)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された 1 件の Microsoft Office の COM の検証の脆弱性を解決します。この脆弱性により、ユーザーが影響を受けるバージョンの Microsoft Office で特別に細工された Excel、Word、Visio、Publisher または PowerPoint ファイルを表示した場合、リモートでコードが実行される可能性があります。この脆弱性は、電子メールを介して、自動的に悪用されることはありません。ユーザーが電子メール メッセージで送信された添付ファイルを開かない限り、攻撃は行われません。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-037">MS10-037</a></td>
<td style="border:1px solid black;">OpenType Compact Font Format (CFF) ドライバーの脆弱性により、特権が昇格される (980218)<br />
<br />
このセキュリティ更新プログラムは Windows OpenType Compact Font Format (CFF) ドライバーに存在する非公開で報告された脆弱性を解決します。この脆弱性により、ユーザーが特別な細工がされた CFF フォントでレンダリングされたコンテンツを表示した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-038">MS10-038</a></td>
<td style="border:1px solid black;">Microsoft Office Excel の脆弱性により、リモートでコードが実行される (2027452)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 14 件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性は、特別に細工された Excel ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性の中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Excel ファイルを開くと、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-039">MS10-039</a></td>
<td style="border:1px solid black;">Microsoft SharePoint の脆弱性により、特権が昇格される (2028554)<br />
<br />
このセキュリティ更新プログラムは Microsoft SharePoint に存在する 1 件の公開された脆弱性および 2 件の非公開で報告された脆弱性を解決します。最も深刻な脆弱性で、攻撃者が標的となる SharePoint サイトのユーザーに特別な細工がされたリンクをクリックさせた場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、 Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-040">MS10-040</a></td>
<td style="border:1px solid black;">インターネット インフォメーション サービスの脆弱性により、リモートでコードが実行される (982666)<br />
<br />
このセキュリティ更新プログラムは非公開で報告されたインターネット インフォメーション サービス (IIS) の脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされた HTTP リクエストを受信すると、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピューターを完全に制御する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms10-041">MS10-041</a></td>
<td style="border:1px solid black;">Microsoft .NET Framework の脆弱性により、改ざんが起こる (981343)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft .NET Framework の脆弱性を解決します。この脆弱性により、検出される事なく 、署名済み XML コンテンツが改ざんされる可能性があります。カスタム アプリケーションでは、セキュリティの影響は、特定のアプリケーションで署名済みコンテンツがどう使用されているかによります。署名済み XML メッセージが安全なチャネル (SSL) で送信されるシナリオの場合、この脆弱性の影響を受けません。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
改ざん</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、 Microsoft .NET Framework</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用の可能性が高いものから順に、次に CVE ID の順に記載しています。セキュリティ情報に記載されている深刻度が緊急または重要の脆弱性のみです。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID                                                        | 脆弱性タイトル                                       | CVE ID                                                                           | Exploitability Index の評価                                                                     | 注意事項                                                                                                                                      |  
|----------------------------------------------------------------------------|------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)        | Win32k のウィンドウ作成の脆弱性                      | [CVE-2010-0485](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)        | Help.aspx XSS の脆弱性                               | [CVE-2010-0817](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | この脆弱性はマイクロソフト セキュリティ アドバイザリ [983438](http://technet.microsoft.com/security/advisory/983438) で最初に報告されました。 |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel オブジェクトのスタック オーバーフローの脆弱性  | [CVE-2010-0822](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel レコードのメモリ破損の脆弱性                   | [CVE-2010-0824](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel レコードのメモリ破損の脆弱性                   | [CVE-2010-1245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel の RTD メモリ破損の脆弱性                      | [CVE-2010-1246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel のメモリ破損の脆弱性                           | [CVE-2010-1247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel HFPicture のメモリ破損の脆弱性                 | [CVE-2010-1248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel のメモリ破損の脆弱性                           | [CVE-2010-1249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel の EDG メモリ破損の脆弱性                      | [CVE-2010-1250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel の ADO オブジェクトの脆弱性                    | [CVE-2010-1253](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Mac Office Open XML のアクセス許可の脆弱性           | [CVE-2010-1254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)        | 初期化されていないメモリ破損の脆弱性                 | [CVE-2010-1259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)        | メモリ破損の脆弱性                                   | [CVE-2010-1262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-036](http://technet.microsoft.com/security/bulletin/ms10-036)        | COM の検証の脆弱性                                   | [CVE-2010-1263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-033](http://www.microsoft.com/japan/security/bulletin/ms10-033.mspx) | メディア圧縮の脆弱性                                 | [CVE-2010-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)        | クロス ドメインの情報の漏えいの脆弱性                | [CVE-2010-0255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | この脆弱性はマイクロソフト セキュリティ アドバイザリ [980088](http://technet.microsoft.com/security/advisory/980088) で最初に報告されました。 |  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)        | Win32k の不適切なデータ検証の脆弱性                  | [CVE-2010-0484](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037)        | OpenType CFF フォント ドライバーのメモリ破損の脆弱性 | [CVE-2010-0819](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel レコード解析のメモリ破損の脆弱性               | [CVE-2010-0821](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel のメモリ破損の脆弱性                           | [CVE-2010-0823](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel のレコード スタック破損の脆弱性                | [CVE-2010-1251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)        | Excel の 文字列変数の脆弱性                          | [CVE-2010-1252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)        | Win32k の TrueType フォントの解析の脆弱性            | [CVE-2010-1255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040)        | IIS 認証のメモリ破損の脆弱性                         | [CVE-2010-1256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-033](http://www.microsoft.com/japan/security/bulletin/ms10-033.mspx) | MJPEG のメディア圧縮の脆弱性                         | [CVE-2010-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                        |  
| [MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041)        | XML 署名の HMAC Truncation の回避の脆弱性            | [CVE-2009-0217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | これはなりすましおよび改ざんの脆弱性です。                                                                                                    |  
| [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)        | toStaticHTML の情報の漏えいの脆弱性                  | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | この脆弱性は [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039) にも影響を及ぼします。                                       |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)        | toStaticHTML の情報の漏えいの脆弱性                  | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | この脆弱性は [MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035) にも影響を及ぼします。                                       |  
| [MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)        | Sharepoint ヘルプ ページのサービス拒否の脆弱性       | [CVE-2010-1264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | (なし)                                                                                                                                        |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
この表はどのように使用しますか?
  
この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、脆弱性の深刻度も記載されています。
  
注: ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
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
<th style="border:1px solid black;" >
</th>
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
<th colspan="8">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[MS10-034](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=60c8579b-1540-40d8-80a0-956edadd63ce)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow) (DirectX 9)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a) <sup>[1]</sup>
(KB975562)  
(緊急)  
[Windows Media フォーマット ランタイム 9](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8417c0ac-bb6d-48f1-8237-77a4bdd8ccb2) <sup>[2]</sup>
(KB978695)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1f929739-08a1-4faf-9ccf-5f1f43c5bb9e)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d3955983-0079-476e-a488-99713097259c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0a6c09e5-c655-41a0-a133-78d55267a527)  
(深刻度なし)<sup>[1]</sup>
[Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2f27eeb-54be-40be-a00e-72867090b8e7)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5d645891-31e9-42c4-b12b-eb351473fd0c)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[MS10-034](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=023a777a-3d83-4a4e-8029-da8b095b074b)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5)  
(KB975562)  
(緊急)  
Windows XP Service Pack 2 のみ:  
[Windows Media フォーマット ランタイム 9、Windows Media フォーマット ランタイム 9.5 および Windows Media フォーマット ランタイム 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3)  
(KB978695)  
(緊急)  
Windows XP Service Pack 3 のみ:  
[Windows Media フォーマット ランタイム 9、Windows Media フォーマット ランタイム 9.5 および Windows Media フォーマット ランタイム 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ebbccd82-c637-4c88-86ea-d39ae713c085)  
(KB978695)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=55c05cb8-aa6c-460b-9aa7-084842dab280)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b42a17c5-997e-4504-ba5b-bfa62166b460)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows XP Media Center Edition 2005 のみ:  
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
(重要)  
Windows XP Media Center Edition 2005 および Windows XP Tablet PC Edition 2005 のみ:  
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
(重要)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8e3aac9d-7747-435f-9678-f621e314e070)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452)  
(KB975562)  
(緊急)  
[Windows Media フォーマット ランタイム 9.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2)  
(KB978695)  
(緊急)  
[Windows Media フォーマット ランタイム 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=80006082-55f2-4857-9d2c-276c758b5555) <sup>[3]</sup>
(KB978695)  
(緊急)  
[Windows Media フォーマット ランタイム 11](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc)  
(KB978695)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(重要)  
[Windows Media エンコーダー 9 x64](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f3e462fb-df95-4b79-a8bc-5359c2967503)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7780af61-a206-49aa-a805-a49bdcbb5419)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dc835b94-3368-4c1c-8f29-40517c73540e)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad) (KB979909)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[MS10-034](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[警告](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[警告](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a)  
(KB975562)  
(緊急)  
[Windows Media フォーマット ランタイム 9.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bb580e94-8c02-46f1-b7f6-e7d4373cb1c5)  
(KB978695)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0ddf95ac-dd49-4cb1-b6f6-bd4e987b0f06)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f0187b69-3ed9-494c-89f1-90a35e22078c)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0761c207-5465-4f42-b61f-bd02efcef27d) <sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c)  
(KB979907)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe)  
(KB975562)  
(緊急)  
[Windows Media フォーマット ランタイム 9.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=41faf16f-c7a8-4ce0-b388-a65478576163)  
(KB978695)  
(緊急)  
[Windows Media フォーマット ランタイム 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=80006082-55f2-4857-9d2c-276c758b5555) <sup>[3]</sup>
(KB978695)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(重要)  
[Windows Media エンコーダー 9 x64](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(重要)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4aa0ec4f-5502-4f2a-9732-975518c34444)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=81644c43-22c0-4c61-b395-3264516516a6)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=50b8ee2e-31f8-473d-83d1-822c89c28070)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=87e13912-f861-4985-ab9d-260a5898dfd4)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=023572ff-ce5d-4428-a96b-1245db6ff312) <sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8)  
(重要)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c)  
(KB975562)  
(緊急)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f34bc115-022b-46b0-9517-806bd0fc73c5)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=123bf547-9005-451f-9eba-97a68037304e)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea) <sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[MS10-034](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 1 のみ:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b64107f2-990a-42df-a75a-5bf371709fd6)  
(KB975562)  
(緊急)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=75e4c9cb-a55a-4e2a-9c97-60a40353cae3)  
(KB979482)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9fab91da-1528-4df9-a2dd-90e57a3c24cf)  
(KB979332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=661c9528-917d-4df6-a330-c89f39dc5ce4)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=640f9216-3e99-46b6-aac8-cd051eedad3c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=363b503a-2e1e-4284-a029-9695d2acfcb6)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=01382926-2313-4769-a0a5-262c4f9f18a1) <sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
Windows Vista Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(重要)  
Windows Vista Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(重要)  
Windows Vista Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb) (KB979910)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 のみ:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0754addb-2f04-45c9-8594-174b8b8b297c)  
(KB975562)  
(緊急)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c9f033f6-f587-494d-b968-1316f1deed06)  
(KB979482)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=63bba49e-6d80-47b3-b109-fa9b2392af4f)  
(KB979332)  
(重要)  
[Windows Media エンコーダー 9 x64](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e19aeef8-6bef-45ee-bc9f-3e4b81a58e33)  
(KB979332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f) <sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
Windows Vista x64 Edition Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(重要)  
Windows Vista x64 Edition Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(重要)  
Windows Vista x64 Edition Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[MS10-034](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[警告](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[警告](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=22d550fe-ba35-4750-a9d6-624858b67c94)\*  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems のみ:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=18fd814b-51f3-470b-a5bd-97be752298d9)\*\*  
(KB975562)  
(緊急)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5c5e2dfc-0078-4f2a-9c2e-75e45bb7638e)\*  
(KB979482)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1ce1e47f-b1c3-4480-bafd-74f8b12e2171)\*\*  
(KB979332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bed14484-7fc5-455d-b996-3192467543cc)\*\*  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=24ed08c7-a474-4458-8269-3b9de5e22385)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e78ad607-d209-48c4-b0f3-ed4c70993174)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=84a54246-5d9e-49e2-8170-af48b43f984d)\*<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
(重要)  
Windows Server 2008 for 32-bit Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
(重要)  
Windows Server 2008 for 32-bit Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=09025626-4116-4a31-8700-215382898ee2)\*  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems のみ:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4e40da51-23ee-44f0-9ea0-99bda8cca731)\*\*  
(KB975562)  
(緊急)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bfc0b62c-2d79-48dd-896f-d05057c02e8c)\*  
(KB979482)  
(緊急)  
[Windows Media エンコーダー 9 x86](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=93cc5ace-6382-4a2f-875b-9348b7e198a6)\*\*  
(KB979332)  
(重要)  
[Windows Media エンコーダー 9 x64](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d650a7d7-5620-4bb7-a7ad-0848dd28dae3)\*\*  
(KB979332)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a24554e8-213b-4c24-b062-ec424d64128e)\*\*  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=38286e43-89a6-4895-8ff9-69452df38706)\*<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
(重要)  
Windows Server 2008 for x64-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
(重要)  
Windows Server 2008 for x64-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems のみ:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=120c68f5-4575-4e2a-912a-eed52736c403)  
(KB975562)  
(緊急)  
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6e5753ab-848d-475f-917d-ba70f70b65f5)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8ad19eba-9821-48b4-a942-4ee4f002f913) <sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(重要)  
Windows Server 2008 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(重要)  
Windows Server 2008 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[MS10-034](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a)  
(重要)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=63567e99-087d-4804-953a-f23bdeba7772)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5bce87fe-dcbb-4638-b248-3f0755537b00)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5c835885-9375-4882-a92f-4d4cfcacc005)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=588167cb-f62a-4fb8-8a18-ac15dc322495)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646)  
(重要)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1c45d0c8-1629-470b-8167-c6bf66054595)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-032](http://technet.microsoft.com/security/bulletin/ms10-032)
</td>
<td style="border:1px solid black;">
[MS10-033](http://technet.microsoft.com/security/bulletin/ms10-033)
</td>
<td style="border:1px solid black;">
[MS10-034](http://technet.microsoft.com/security/bulletin/ms10-034)
</td>
<td style="border:1px solid black;">
[MS10-035](http://technet.microsoft.com/security/bulletin/ms10-035)
</td>
<td style="border:1px solid black;">
[MS10-037](http://technet.microsoft.com/security/bulletin/ms10-037)
</td>
<td style="border:1px solid black;">
[MS10-040](http://technet.microsoft.com/security/bulletin/ms10-040)
</td>
<td style="border:1px solid black;">
[MS10-041](http://technet.microsoft.com/security/bulletin/ms10-041)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[緊急](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[警告](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[警告](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1331f2bc-7479-4be7-a413-52afb488a330)\*  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=901f7c89-02af-4f87-8592-dad318997d77)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=45242c7c-3752-44bf-a766-024ad7d28f53)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a49532d7-53f6-4190-aaf6-b1a818924764)\*  
(KB979916)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7d636f82-e828-468c-ac36-808ff9d37c7f)  
(重要)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM コンポーネント)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7a1ee54f-3f73-4557-9071-5af236e70937)  
(KB979482)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4958b221-2776-43d7-9e1c-1e1cb318a694)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=52c04d85-911f-47be-852e-c9bb4934744d)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Information Services 7.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(重要)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

\*\*Server Core インストールは影響を受けません。この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用してインストールした場合、サポートされているエディションの Windows Server 2008 および Windows Server 2008 R2 に影響を与えません。このインストール オプションに関する詳細情報は MSDN コラム [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx) をご覧ください。

MS10-033 に関する注意

<sup>[1]</sup> Quartz.dll (DirectShow) (DirectX 9) 用の更新プログラムは DirectX 9.0a、DirectX 9.0b および DirectX 9.0c にも適用することができます。

<sup>[2]</sup> この更新プログラム パッケージは、Windows Media デジタル著作権管理 (DRM) 対応プレーヤー用の更新プログラム (KB891122) をインストールしている Microsoft Windows 2000 上の Windows Media Format 9 SDK ランタイムに適用されます。詳細情報は、サポート技術情報 [974316](http://support.microsoft.com/kb/974316) をご覧ください。

<sup>[3]</sup> Windows Media フォーマット ランタイム 9.5 x64 Edition をインストールした場合、Windows Media フォーマット ランタイム 9.5 および Windows Media フォーマット ランタイム 9.5 x64 Edition のセキュリティ更新プログラムを適用して、このセキュリティ情報で説明している脆弱性から完全に防御する必要があります。

MS10-035 に関する注意

<sup>[1]</sup> このセキュリティ情報で説明している脆弱性はこのソフトウェアに影響を及ぼさないため、この更新プログラムに対して深刻度は適用されません。しかし、[MS09-054](http://technet.microsoft.com/security/bulletin/ms09-054) のセキュリティ更新プログラム適用後の問題を修正するために、この更新プログラムを提供します。詳細情報は、「このセキュリティ更新プログラムに関するよく寄せられる質問 (FAQ)」の「この累積的な更新プログラムはそのほかのセキュリティ関連以外の機能への変更を含みますか?」をご覧ください。

MS10-040 に関する注意

<sup>[1]</sup> このオペレーティング システムは認証に対する保護の強化がインストールされている場合のみ、この脆弱性の影響を受けます。マイクロソフト サポート技術情報 [973917](http://support.microsoft.com/kb/973917) をご覧ください。詳細情報は、「このセキュリティ更新プログラムに関するよく寄せられる質問 (FAQ)」のセクションをご覧ください。

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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
Microsoft Office スイート、システムおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-036](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f)  
(KB982299)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=80fdd134-2a86-4115-aea1-841f19af92e3)  
(KB982311)  
(重要)  
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=757b5d8f-ade5-4896-b152-43f76516bcf1) <sup>[2]</sup>
(KB982133)  
(重要)  
[Microsoft Office PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc) <sup>[2]</sup>
(KB982157)  
(重要)  
[Microsoft Office Publisher 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=87bac893-81ec-4ede-aca1-a9aa48b92cd4) <sup>[2]</sup>
(KB982122)  
(重要)  
[Microsoft Office Visio 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a) <sup>[2]</sup>
(KB982126)  
(重要)  
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d2c40eb5-1149-4466-840c-84f406f64245) <sup>[2]</sup>
(KB982134)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)  
(KB982133)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1 および 2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System Service Pack 1 および 2007 Microsoft Office System Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6deb4fb0-cbfc-40df-8f62-35fa1db0e167)  
(KB982312)  
(重要)  
[Microsoft Office Excel 2007 Service Pack 1 および Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec) <sup>[3]</sup>
(KB982308)  
(重要)  
[Microsoft Office PowerPoint 2007 Service Pack 1 および Microsoft Office PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=decb834d-3958-45cc-a5ae-4283adb2462a) <sup>[3]</sup>
(KB982158)  
(重要)  
[Microsoft Office Publisher 2007 Service Pack 1 および Microsoft Office Publisher 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6a74b986-1e99-4aa1-828f-757a36896f65) <sup>[3]</sup>
(KB982124)  
(重要)  
[Microsoft Office Visio 2007 Service Pack 1 および Microsoft Office Visio 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d5df052e-1f38-4308-bcca-296cff22729b) <sup>[3]</sup>
(KB982127)  
(重要)  
[Microsoft Office Word 2007 Service Pack 1 および Microsoft Office Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755) <sup>[3]</sup>
(KB982135)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 および Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec) <sup>[1]</sup>
(KB982308)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-036](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=16c71ab8-9284-407a-856a-93c67995f125)  
(KB2028866)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd)  
(KB2028864)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528)  
(KB2078051)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="4">
Other Office Software
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-036](http://technet.microsoft.com/security/bulletin/ms10-036)
</td>
<td style="border:1px solid black;">
[MS10-038](http://technet.microsoft.com/security/bulletin/ms10-038)
</td>
<td style="border:1px solid black;">
[MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer Service Pack 1 および Microsoft Office Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 および Microsoft Office Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=033b3bf3-7826-4064-b001-11e4dce2d91a)  
(KB982333)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0)  
(KB982331)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office InfoPath 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4f79d376-0ea2-4218-9200-3c34c83ba336)  
(KB980923)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office InfoPath 2007 Service Pack 1 および Microsoft Office InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2007 Service Pack 1 および Microsoft Office InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6)  
(KB979441)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 1 および Microsoft Office SharePoint Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=52a55423-f33b-4cd1-919d-806972a553df) <sup>[1]</sup>
(KB979445)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=52a55423-f33b-4cd1-919d-806972a553df) <sup>[1]</sup>
(KB979445)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90) <sup>[1]</sup>
(KB979445)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90) <sup>[1]</sup>
(KB979445)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS10-036 に関する注意

<sup>[1]</sup> 利用可能な更新プログラムはありません。詳細情報は、「このセキュリティ更新プログラムに関するよく寄せられる質問 (FAQ)」のセクションをご覧ください。

<sup>[2]</sup> この更新プログラムに加えて、お客様は Microsoft Office 2003 Service Pack 3 (KB982311) 用の更新プログラムをインストールして、このセキュリティ情報で説明している脆弱性から防御する必要があります。

<sup>[3]</sup> この更新プログラムに加えて、お客様は 2007 Microsoft Office System Service Pack 1 および 2007 Microsoft Office System Service Pack 2 (KB982312) 用の更新プログラムをインストールして、このセキュリティ情報で説明している脆弱性から防御する必要があります。

MS10-038 に関する注意

<sup>[1]</sup> Microsoft Office Excel 2007 Service Pack 1 および Microsoft Office Excel 2007 Service Pack 2 について、KB982308 に加え、お客様は Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2 用のセキュリティ更新プログラム KB982331 をインストールして、このセキュリティ情報で説明している脆弱性から防御する必要があります。

MS10-039 に関する注意

<sup>[1]</sup> サポートされているエディションの Microsoft Office SharePoint Server 2007 について、お客様はこのセキュリティ情報で説明している脆弱性に対する保護を行うために、セキュリティ更新プログラム パッケージ KB979445 とともに、Microsoft Windows SharePoint Services 3.0 (KB983444) のセキュリティ更新プログラムもインストールする必要があります。

この「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリもご覧ください。同じセキュリティ情報 ID の更新プログラムがあります。このセキュリティ情報は複数のソフトウェア カテゴリに該当しています。

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
Windows SharePoint Services
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS10-039](http://technet.microsoft.com/security/bulletin/ms10-039)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
最大深刻度
</td>
<td style="border:1px solid black;">
[重要](http://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 1 および Microsoft Windows SharePoint Services 3.0 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 および Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3841ceda-d0af-4e5e-8a1a-7dd954850783)  
(KB983444)  
(重要)  
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 および Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f)  
(KB983444)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS10-039 に関する注意

この「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリもご覧ください。同じセキュリティ情報 ID の更新プログラムがあります。このセキュリティ情報は複数のソフトウェア カテゴリに該当しています。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

検出および適用のガイダンス

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

Windows Server Update Services

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

Systems Management Server

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

注: SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

Update Compatibility Evaluator および Application Compatibility Toolkit

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

更新プログラムの管理の計画

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) をご覧ください。

IT Pro Security Zone Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い謝意を表します。

-   MS10-032 で説明している問題を報告してくださった [VUPEN Vulnerability Research Team](http://www.vupen.com/) の Sebastien Renaud 氏
-   MS10-032 で説明している問題について、マイクロソフトに協力してくださった [Secunia Research](http://secunia.com/)
-   MS10-033 で説明している 2 件の問題を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS10-034 で説明している問題を報告してくださった [NGS Software](http://www.ngssoftware.com/) の Shaun Colley 氏
-   MS10-034 で説明している問題を報告してくださった Carnegie Mellon University Computing Services の Chris Ries 氏
-   MS10-035 および MS10-039 で説明している問題を報告してくださった [Casaba Security](http://www.casabasecurity.com/) の Chris Weber 氏
-   MS10-035 で説明している問題を報告してくださった [三井物産セキュアディレクション株式会社](http://www.mbsd.jp/)の Takeshi Terada 氏
-   MS10-035 で説明している問題を報告してくださった [Google Inc.](http://www.google.com/) の Michal Zalewski 氏
-   MS10-035 で説明している 2 件の問題を報告してくださった [Matasano Security](http://www.matasano.com/) の Chris Rohlf 氏
-   MS10-035 で説明している問題を [TippingPoint](http://www.tippingpoint.com/)の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった Peter Vreugdenhil 氏
-   MS10-036 に含まれている多層防御の変更に関して協力してくださった [IBM ISS X-Force](http://www.iss.net/) の David Dewey 氏および、以前は、[VeriSign iDefense Labs](http://labs.idefense.com/)で、現在は [Accuvant](http://www.accuvant.com/) の Ryan Smith 氏
-   MS10-037 で説明している問題を報告してくださった [Secunia](http://secunia.com/) に協力している Laserforce International の Chris Carton 氏
-   MS10-038 で説明している問題を報告してくださった、 [TippingPoint](http://www.tippingpoint.com/) の[Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している匿名のリサーチャー
-   MS10-038 で説明している 8 件の問題を報告してくださった [VUPEN Vulnerability Research Team](http://www.vupen.com/) の Nicolas Joly 氏
-   MS10-038 で説明している問題を報告してくださった、 [Fortinet の FortiGuard Labs](http://www.fortiguard.com/) の Bing Liu 氏
-   MS10-038 で説明している 2 件の問題を報告してくださった [Secunia](http://secunia.com/) の Carsten Eiram 氏
-   MS10-038 で説明している問題を報告してくださった、 [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している匿名のリサーチャー
-   MS10-038 で説明している問題を報告してくださった、Gilbert Public Schools in Gilbert, AZ の Rick Glaspie 氏
-   MS10-039 で説明している問題を報告してくださった Dallas County Community College District の Rik Jones 氏
-   MS10-041 で、多層防御を変更して解決された ASP.NET のリクエストの検証機能の回避問題を報告してくださった [WhiteHat Security](http://www.whitehatsec.com/) の Arian Evans 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2010/06/09: このセキュリティ情報ページを公開しました。
-   2010/06/10: このセキュリティ情報を更新し、「影響を受けるソフトウェアおよびダウンロード先」の MS10-033 に関する注意を更新しました。
-   2011/09/14: このセキュリティ情報を再リリースし、Microsoft Windows 2000 および Windows XP 上の Internet Explorer 用に更新プログラムを再提供して、検出ロジックの問題を解決しました。 セキュリティ更新プログラムのファイルへの変更はありません。 システムを正常に更新済みのお客様は、措置を講じる必要はありません。

*Built at 2014-04-18T01:50:00Z-07:00*
