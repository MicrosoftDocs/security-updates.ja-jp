---
TOCTitle: 'MS09-JUL'
Title: 2009 年 7 月のセキュリティ情報
ms:assetid: 'ms09-jul'
ms:contentKeyID: 61229663
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-jul(v=Security.10)'
--- Summary

2009 年 7 月のセキュリティ情報
==============================

公開日: 2009年7月15日 | 最終更新日: 2010年3月10日

**バージョン:** 1.0

[![](../../images/Dn627242.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/dd251169.aspx)[![](../../images/Dn627242.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------


[MS09-028 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-028e.mspx)

[MS09-029 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-029e.mspx)

[MS09-030 : Publisher の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-030e.mspx)

[MS09-031 : ISA Server の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-031e.mspx)

[MS09-032 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-032e.mspx)

[MS09-033 : Virtual PC および Virtual Server の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-033e.mspx)

[MS09-034 : Internet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-034e.mspx)

[MS09-035 : Visual Studio の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-035e.mspx)

このセキュリティ情報は 2009 年 7 月に公開したセキュリティ情報の一覧です。

2009 年 7 月 29 日に緊急リリースしました[セキュリティ情報 MS09-034](http://technet.microsoft.com/security/bulletin/ms09-034) および [セキュリティ情報 MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035) に関する情報を追加しました。

2009 年 7 月のセキュリティ情報の公開により、2009 年 7 月 10 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 7 月 15 日 の午後 (日本時間) に配信しました。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 7 月 15 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行いました。この Webcast はオンデマンドで視聴可能です。詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはこの定例外の緊急セキュリティ情報リリースについて、[2009 年 7 月 28 日 午後 1 ：00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&eventcategory=4&culture=en-us&countrycode=us) および [午後 4:00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&eventcategory=4&culture=en-us&countrycode=us) (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----


次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細は、次の影響を受けるソフトウェアのセクションをご覧ください。

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-029">MS09-029</a></td>
<td style="border:1px solid black;"><strong>Embedded OpenType フォント エンジンの脆弱性により、リモートでコードが実行される (961371)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows コンポーネントである Embedded OpenType (EOT) フォント エンジンに存在する脆弱性を解決します。これらの脆弱性により、リモートでコードが実行される可能性があります。攻撃者によりこれらの脆弱性のいずれかが悪用された場合、影響を受けるコンピューターがリモートで完全に制御される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-028">MS09-028</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow の脆弱性により、リモートでコードが実行される (971633)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft DirectShow に存在する 1 件の公開された脆弱性および 2 件の非公開で報告された脆弱性を解決します。この脆弱性では、特別に細工された QuickTime メディア ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性が悪用された場合、攻撃者によりローカル ユーザーと同じ権限が取得される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-032">MS09-032</a></td>
<td style="border:1px solid black;"><strong>ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (973346)</strong><br />
<br />
このセキュリティ更新プログラムは、現在悪用されている責任ある開示方法で報告された脆弱性を解決します。Microsoft Video ActiveX コントロールの脆弱性により、ユーザーが Internet Explorer で、特別に細工された Web ページを閲覧し、ActiveX コントロールが開始された場合、リモートでコードが実行される可能性があります。この ActiveX コントロールは、Internet Explorer でインスタンス化されることを意図していません。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-034">MS09-034</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (972260)</strong><br />
<br />
これは、マイクロソフト セキュリティ情報 <a href="http://technet.microsoft.com/security/bulletin/ms09-035">MS09-035</a> と同時に公開している定例外の累積的なセキュリティ更新プログラムです。(MS09-035 は Microsoft Active Template Library (ATL) の影響を受けるバージョンを使用して開発されたコンポーネントおよびコントロールに存在する脆弱性を説明しています。) 多層防御の対策として、この Internet Explorer 用の累積的なセキュリティ更新プログラムは、<a href="http://technet.microsoft.com/security/advisory/973882">マイクロソフト セキュリティ アドバイザリ (973882)</a> および マイクロソフト セキュリティ情報 <a href="http://technet.microsoft.com/security/bulletin/ms09-035">MS09-035</a> で説明しているように、ATL の影響を受けるバージョンで開発されたコンポーネントおよびコントロールの Internet Explorer での既知の攻撃の方法による影響を緩和する手助けとなります。<br />
また、この累積的なセキュリティ更新プログラムは非公開で報告された 3 件のInternet Explorer に存在する脆弱性も解決します。 この脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。 システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-033">MS09-033</a></td>
<td style="border:1px solid black;"><strong>Virtual PC および Virtual Server の脆弱性により、特権が昇格する (969856)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Virtual PC および Microsoft Virtual Server に存在する 1 件の脆弱性を解決します。この脆弱性が悪用された場合、攻撃者により任意のコードが実行され、影響を受けるゲスト オペレーティング システムが完全に制御される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、 または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Virtual PC, Virtual Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-031">MS09-031</a></td>
<td style="border:1px solid black;"><strong>Microsoft ISA Server 2006 の脆弱性により、特権が昇格される (970953)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Internet Security and Acceleration (ISA) Server 2006 に存在する脆弱性を解決します。この脆弱性で、攻撃者が管理者ユーザー アカウントになりすますことができた場合、特権が昇格される可能性があります。ISA サーバーで Radius ワン タイム パスワード (OTP) 認証および Kerberos の制約付き委任での認証委任が設定されていない場合、この脆弱性の影響は受けません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft ISA Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-030">MS09-030</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Publisher の脆弱性により、リモートでコードが実行される (969516)</strong><br />
<br />
このセキュリティ更新プログラムは、ユーザーが特別に細工された Publisher のファイルを表示するとリモートでコードが実行される可能性のある、非公開で報告された Microsoft Office Publisher の脆弱性を解決します。攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-035">MS09-035</a></td>
<td style="border:1px solid black;"><strong>Visual Studio の Active Template Library の脆弱性により、リモートでコードが実行される (969706)</strong><br />
<br />
このセキュリティ更新プログラムは、責任ある開示方法で報告された Visual Studio に含まれている、一般向けのバージョンの Microsoft Active Template Library (ATL) のいくつかの脆弱性を解決します。 このセキュリティ更新プログラムは、特にコンポーネントおよびコントロールの開発者に向けられたものです。 ATL を使用してコンポーネントおよびコントロールを作成、配布する開発者はこのセキュリティ情報で提供している更新プログラムをインストールし、このセキュリティ情報で説明している脆弱性の影響を受けないコンポーネントおよびコントロールを作成するためのガイダンスに従い、お客様に配布する必要があります。<br />
このセキュリティ情報は、影響を受けるバージョンの ATL を使用して作成したコンポーネントまたはコントロールをユーザーが読み込んだ場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">警告</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  

次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号および CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**  
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID 番号                                            | セキュリティ情報タイトル                                                                       | CVE ID                                                                       | Exploitability Index の評価                                                                     | 注意事項                                                              |  
|---------------------------------------------------------------------|------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|  
| [MS09-028](http://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow の脆弱性により、リモートでコードが実行される (971633)                     | [CVE-2009-1537](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537) | [1- 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)      | **この脆弱性は現在インターネット エコシステム上で悪用されています。** |  
| [MS09-028](http://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow の脆弱性により、リモートでコードが実行される (971633)                     | [CVE-2009-1538](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                |  
| [MS09-028](http://technet.microsoft.com/security/bulletin/ms09-028) | Microsoft DirectShow の脆弱性により、リモートでコードが実行される (971633)                     | [CVE-2009-1539](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539) | [1- 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)      | (なし)                                                                |  
| [MS09-029](http://technet.microsoft.com/security/bulletin/ms09-029) | Embedded OpenType フォント エンジンの脆弱性により、リモートでコードが実行される (961371)       | [CVE-2009-0231](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                |  
| [MS09-029](http://technet.microsoft.com/security/bulletin/ms09-029) | Embedded OpenType フォント エンジンの脆弱性により、リモートでコードが実行される (961371)       | [CVE-2009-0232](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                |  
| [MS09-030](http://technet.microsoft.com/security/bulletin/ms09-030) | Microsoft Office Publisher の脆弱性により、リモートでコードが実行される (969516)               | [CVE-2009-0566](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                |  
| [MS09-031](http://technet.microsoft.com/security/bulletin/ms09-031) | Microsoft ISA Server 2006 の脆弱性により、特権が昇格される (970953)                            | [CVE-2009-1135](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                |  
| [MS09-032](http://technet.microsoft.com/security/bulletin/ms09-032) | ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (973346)                              | [CVE-2008-0015](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | **この脆弱性は現在インターネット エコシステム上で悪用されています。** |  
| [MS09-033](http://technet.microsoft.com/security/bulletin/ms09-033) | Virtual PC および Virtual Server の脆弱性により、特権が昇格する (969856)                       | [CVE-2009-1542](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 不安定な悪用攻撃により、コードの実行が機能する可能性があります。      |  
| [MS09-034](http://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 用の累積的なセキュリティ更新プログラム (972260)                              | [CVE-2009-1917](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 安定した悪用攻撃により、コードの実行が機能する可能性があります。      |  
| [MS09-034](http://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 用の累積的なセキュリティ更新プログラム (972260)                              | [CVE-2009-1918](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 不安定な悪用攻撃により、コードの実行が機能する可能性があります。      |  
| [MS09-034](http://technet.microsoft.com/security/bulletin/ms09-034) | Internet Explorer 用の累積的なセキュリティ更新プログラム (972260)                              | [CVE-2009-1919](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 不安定な悪用攻撃により、コードの実行が機能する可能性があります。      |  
| [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio の Active Template Library の脆弱性により、リモートでコードが実行される (969706) | [CVE-2009-0901](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 安定した悪用攻撃により、コードの実行が機能する可能性があります。      |  
| [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio の Active Template Library の脆弱性により、リモートでコードが実行される (969706) | [CVE-2009-2493](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 安定した悪用攻撃により、コードの実行が機能する可能性があります。      |  
| [MS09-035](http://technet.microsoft.com/security/bulletin/ms09-035) | Visual Studio の Active Template Library の脆弱性により、リモートでコードが実行される (969706) | [CVE-2009-2495](http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これは、情報漏えいの脆弱性で、コードが実行される可能性はありません。  |
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="5">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
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
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3&displaylang=ja)  
(緊急)  
[DirectX 8.1](http://www.microsoft.com/downloads/details.aspx?familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d&displaylang=ja)\*\*\*  
(緊急)  
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda&displaylang=ja)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=89d941f0-3f71-46e3-8096-716561396b72&displaylang=ja)  
(深刻度なし\*\*)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd&displaylang=ja)  
(緊急)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282&displaylang=ja)  
(緊急)

</td>
</tr>
<tr>
<th colspan="5">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
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
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6914167b-6961-480c-a4d4-808cd58a035b&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=09d585cb-481d-4767-875e-9c6ebe456b80&displaylang=ja)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=24701af8-b87e-4e85-9463-f50755a1b6ad&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=22bed634-5227-4a22-8df5-801f3e2e232a&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=c874c8f8-0449-42b1-8d8b-901040069568&displaylang=ja)  
(緊急)
  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00&displaylang=ja)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4&displaylang=ja)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba&displaylang=ja)  
(緊急)
  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab&displaylang=ja)  
(緊急)

</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc&displaylang=ja)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af&displaylang=ja)  
(警告)
  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606&displaylang=ja)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e&displaylang=ja)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d&displaylang=ja)  
(警告)
  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd&displaylang=ja)  
(警告)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042&displaylang=ja)\*\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071&displaylang=ja)  
(警告)

</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1, および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1, および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1, および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45&displaylang=ja)  
(深刻度なし\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43&displaylang=ja)  
(緊急)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1, および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1, および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1, および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7&displaylang=ja)  
(深刻度なし\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb&displaylang=ja)  
(緊急)

</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-029**](http://technet.microsoft.com/security/bulletin/ms09-029)
</td>
<td style="border:1px solid black;">
[**MS09-028**](http://technet.microsoft.com/security/bulletin/ms09-028)
</td>
<td style="border:1px solid black;">
[**MS09-032**](http://technet.microsoft.com/security/bulletin/ms09-032)
</td>
<td style="border:1px solid black;">
[**MS09-034**](http://technet.microsoft.com/security/bulletin/ms09-034)
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
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995&displaylang=ja)\*  
(深刻度なし\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead&displaylang=ja)\*  
(警告)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae&displaylang=ja)\*  
(警告)

</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0&displaylang=ja)\*  
(深刻度なし\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516&displaylang=ja)\*  
(警告)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93&displaylang=ja)\*  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a&displaylang=ja)  
(深刻度なし\*\*)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d&displaylang=ja)  
(警告)
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 に関する注意**

**\*Windows Server 2008 Server Core インストールは影響を受けません。** この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用して Windows Server 2008 をインストールした場合、サポートされているエディションの Windows Server 2008 に影響を与えません。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx)をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

**MS09-032 のセキュリティ情報に関する注意**

**\*\***このセキュリティ情報で説明している脆弱性はこのソフトウェアに影響を与えないため、この更新プログラムに深刻度は適用されません。しかし、マイクロソフトは、将来的に特定される可能性がある新しい攻撃方法を防ぐ多層防御策として、このソフトウェアをご使用のお客様に、このセキュリティ更新プログラムの適用を推奨します。

**MS09-028 のセキュリティ情報に関する注意**

\*\*\* The update for DirectX 8.1 also applies to DirectX 8.1b\*\*\*The update for DirectX 8.1 also applies to DirectX 8.1b\*\*\*DirectX 8.1 用の更新プログラムは DirectX 8.1b にも適用することができます。
\*\*\*\* DirectX 9.0 用のセキュリティ更新プログラムは DirectX 9.0a、DirectX 9.0b および DirectX 9.0c にも適用することができます。

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
Microsoft Office スイート, システム, およびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-030**](http://technet.microsoft.com/security/bulletin/ms09-030)
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
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8&displaylang=ja)  
(KB969693)  
(重要)
</td>
</tr>
</table>

<p></p>

 

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
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-035**](http://technet.microsoft.com/security/bulletin/ms09-035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e&displaylang=ja)  
(KB971089)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197&displaylang=ja)  
(KB971090)  
(警告)  
[Microsoft Visual Studio 2005 Service Pack 1\*](http://www.microsoft.com/downloads/details.aspx?familyid=9d7ee45b-9892-41b5-ac08-5fde9cde1b42&displaylang=ja)  
(KB973673)  
(警告)
  
[Microsoft Visual Studio 2005 Service Pack 1 64-bit Hosted Visual C++ Tools](http://www.microsoft.com/downloads/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2&displaylang=ja)  
(KB973830)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Embedded CE 6.0
</td>
<td style="border:1px solid black;">
[Windows Embedded CE 6.0\*\*](http://www.microsoft.com/downloads/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8&displaylang=ja)  
(KB974616)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](http://www.microsoft.com/downloads/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c&displaylang=ja)  
(KB971091)  
(警告)  
[Microsoft Visual Studio 2008\*](http://www.microsoft.com/downloads/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd&displaylang=ja)  
(KB973674)  
(警告)
  
[Microsoft Visual Studio 2008 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb&displaylang=ja)  
(KB971092)  
(警告)
  
[Microsoft Visual Studio 2008 Service Pack 1\*](http://www.microsoft.com/downloads/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f&displaylang=ja)  
(KB971092)  
(警告)

</td>
</tr>
<tr>
<th colspan="2">
Microsoft Visual C++
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-035**](http://technet.microsoft.com/security/bulletin/ms09-035)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2005 Service Pack 1 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2&displaylang=ja)  
(KB973544)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2008 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93&displaylang=ja)  
(KB973551)  
(警告)  
[Microsoft Visual C++ 2008 Service Pack 1 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c&displaylang=ja)  
(KB973552)  
(警告)

</td>
</tr>
</table>

<p></p>

 
**注: MS09-035**     
\*スマート デバイス 向けの ATL を使用したモバイル アプリケーション用
\*\*Windows Embedded CE 6.0 の月例の更新プログラムをインストールします (2009 年 12 月)。この更新プログラムは、[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8&displaylang=ja)でのみご利用いただけます。

#### Microsoft サーバーおよびセキュリティ ソフトウェア

 
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
Microsoft Internet Security and Acceleration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-031**](http://technet.microsoft.com/security/bulletin/ms09-031)
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
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](http://www.microsoft.com/downloads/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19&displaylang=ja)  
(KB970811)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2006 Supportability Update](http://www.microsoft.com/downloads/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476&displaylang=ja)  
(KB970811)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2006 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5&displaylang=ja)  
(KB971143)  
(重要)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft 仮想化ソフトウェア

 
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
Microsoft Virtual PC
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://technet.microsoft.com/security/bulletin/ms09-033)
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
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2004 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad&displaylang=ja)  
(KB969856)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2007
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a&displaylang=ja)  
(KB969856)  
(重要)  
[Microsoft Virtual PC 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0&displaylang=ja)  
(KB969856)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2007 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual PC 2007 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a&displaylang=ja)  
(KB969856)  
(重要)  
[Microsoft Virtual PC 2007 x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0&displaylang=ja)  
(KB969856)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Virtual Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-033**](http://technet.microsoft.com/security/bulletin/ms09-033)
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
Microsoft Virtual Server 2005
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005](http://www.microsoft.com/downloads/details.aspx?familyid=092a389a-2296-4c3b-a160-2523154ec764&displaylang=ja)  
(KB969856)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57&displaylang=ja)  
(KB969856)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 x64 Edition
</td>
<td style="border:1px solid black;">
[Microsoft Virtual Server 2005 R2 x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57&displaylang=ja)  
(KB969856)  
(重要)
</td>
</tr>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------


**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**注:** 2009 年 8 月 1 日より、マイクロソフトは Office Update および Office Update Inventory Tool のサポートを終了します。Microsoft Office 製品用の最新の更新プログラムを引き続き入手するためには、[Microsoft Update](http://update.microsoft.com/microsoftupdate/) をご利用ください。詳細情報は、[About Microsoft Office Update: Frequently Asked Questions](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英語情報) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2009 年). すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS09-028 で説明している問題について報告してくださった [SkyRecon](http://www.skyrecon.com/) の Thomas Gamier 氏および [Qihoo 360 Security Center](http://www.360.cn/) の Zheng Wenbin 氏、Liu Qi 氏および Song Shenlei 氏
-   MS09-028 で説明している問題について報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS09-028 で説明している問題について報告してくださった [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) の Aaron Portnoy 氏および TippingPoint's [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している匿名のリサーチャー、[SkyRecon](http://www.skyrecon.com/) の Thomas Garnier 氏、および [Palo Alto Networks](http://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS09-029 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/)
-   MS09-029 で説明している問題について報告してくださった [Google Inc.](http://www.google.com/) の Tavis Ormandy 氏
-   MS09-029 で説明している問題について報告してくださった Thomas Garnier 氏
-   MS09-030 で説明している問題について [VersiSign iDefense Labs](http://www.idefense.com/) と協力して報告してくださった [Labo Skopia](http://www.laboskopia.com/) の Lionel d'Hauenens 氏
-   MS09-032 で説明している問題について報告してくださった [IBM ISS X-Force](http://www.iss.net/) の Ryan Smith 氏および Alex Wheeler 氏
-   MS09-033 で説明している問題について [Google Inc.](http://www.google.com/) の Julien Tinnes 氏および Tavis Ormandy 氏
-   MS09-034 で説明している問題について [VeriSign iDefense Labs](http://labs.idefense.com/) の Peter Vreugdenhil 氏
-   MS09-034 で説明している問題について [TippingPoint](http://www.tippingpoint.com/) と [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった [team509](http://www.team509.com/) の Wushi 氏および Ling 氏
-   MS09-034 で説明している問題について [TippingPoint](http://www.tippingpoint.com/) と [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった Peter Vreugdenhil 氏
-   MS09-035 で説明している問題について報告してくださった [IBM ISS X-Force](http://www.iss.net/) の David Dewey 氏
-   MS09-035 で説明している 2 件の問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Ryan Smith 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/07/15: このセキュリティ情報ページを公開しました。
-   2009/07/16: MS09-029 のセキュリティ情報の再起動情報を更新しました。
-   2009/07/29: マイクロソフト セキュリティ情報 MS09-034 Internet Explorer の累積的なセキュリティ更新プログラム (972260) および MS09-035 Visual Studio の Active Template Library の脆弱性により、リモートでコードが実行される (969706)を追加しました。また、これらの定例外リリースに関するWebcastのリンクを追加しました。
-   2009/08/05: Microsoft Windows 2000 Service Pack 4 上の Microsoft Internet Explorer 6 Service Pack 1 用の更新プログラムを再公開しました。Microsoft Windows 2000 Service Pack 4 上の Internet Explorer 6 Service Pack 1 用の最初の更新プログラムをインストール済みのお客様は、既に保護されています。 しかし、Internet Explorer 6 Service Pack 1 の韓国語版をインストール済みのお客様は、システムを保護し、印刷の問題を解決するために Windows 2000 上の Microsoft Internet Explorer 6 Service Pack 1 用の更新プログラムの再インストールが必要になる場合があります。 詳細は、マイクロソフト セキュリティ情報 MS09-034 をご覧ください。
-   2009/08/14: MS09-035 の再リリースをお知らせするために更新しました。MS09-035 は、スマート デバイス向けの ATL を使用した モバイル アプリケーション用コンポーネントおよびコントロールをVisual Studio を使用して作成する開発者向けのMicrosoft Visual Studio 2005 Service Pack 1 (KB973673)、Microsoft Visual Studio 2008 (KB973674) および Microsoft Visual Studio 2008 Service Pack 1 (KB973675) 用の新しい更新プログラムを提供するために再リリースされました。MS09-035 に含まれる再起動の要件を修正しました。
-   2009/08/20: DirectX 8.1 において「影響を受けるソフトウェア」を明確にするために、MS09-028 の補足説明を追加しました。
-   2009/08/26: Windows XP Service Pack 2、Windows XP Service Pack 3 および Windows XP Professional x64 Edition Service Pack 2 用の MS09-029 の日本語版の更新プログラムの再リリースをお知らせするために更新しました。最初の更新プログラムを適用したすべてのお客様はすでにMS09-029 で説明している脆弱性に対して保護されています。しかし、Windows XP Service Pack 2、Windows XP Service Pack 3、または Windows XP Professional x64 Edition Service Pack 2 の日本語版をインストール済みのお客様は、システムの保護を追加し、印刷の問題を解決するために Windows XP Service Pack 2、Windows XP Service Pack 3 および Windows XP Professional x64 Edition Service Pack 2 用の更新プログラムの再インストールが必要です。詳細は、マイクロソフト セキュリティ情報 MS09-029 をご覧ください。
-   2010/01/13: このセキュリティ情報を更新し、MS09-035 の影響を受けるソフトウェアに Windows Embedded CE 6.0 を追加しました。Windows Embedded CE 6.0 用の更新プログラムのパッケージ (KB974616) はマイクロソフト ダウンロード センターのみでご利用いただける累積的な更新プログラムです。Windows Embedded CE 6.0 プラットフォームをご使用のお客様はこの累積的な更新プログラムの適用を検討してください。
-   2010/03/10: このセキュリティ情報を更新し、MS09-033 の影響を受けるソフトウェアに Microsoft Virtual Server 2005 を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
