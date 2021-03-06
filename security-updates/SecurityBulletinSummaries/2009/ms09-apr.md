---
TOCTitle: 'MS09-APR'
Title: 2009 年 4 月のセキュリティ情報
ms:assetid: 'ms09-apr'
ms:contentKeyID: 61229658
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-apr(v=Security.10)'
--- 

2009 年 4 月のセキュリティ情報
==============================

公開日: 2009年4月15日 | 最終更新日: 2009年4月15日

**バージョン:** 1.0

[![](../../images/Dn627237.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/dd251169.aspx)

絵でみるセキュリティ情報
------------------------

<span></span>
[MS09-009 : Excel の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-009e.mspx)

[MS09-010 : Windows および Office の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-010e.mspx)

[MS09-011 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-011e.mspx)

[MS09-012 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-012e.mspx)

[MS09-013 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-013e.mspx)

[MS09-014 : Internet Explorer の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-014e.mspx)

[MS09-015 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-015e.mspx)

[MS09-016: ISA Server の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-016e.mspx)

このセキュリティ情報は 2009 年 4 月に公開したセキュリティ情報の一覧です。

2009 年 4 月のセキュリティ情報の公開により、2009 年 4 月 10 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 4 月 15 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 4 月 15 日 午前 11 ：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[4 月のセキュリティ 情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395126)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----

<span></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。
影響を受けるソフトウェアの詳細は、次の**影響を受けるソフトウェア**のセクションをご覧ください。

 
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-010">MS09-010</a></td>
<td style="border:1px solid black;"><strong>ワードパッドおよび Office テキスト コンバーターの脆弱性により、リモートでコードが実行される (960477)</strong><br />
<br />
このセキュリティ更新プログラムは 2 つの公開された脆弱性と 2 つの非公開で報告された Microsoft ワードパッドおよび Microsoft Office テキスト コンバーターに存在する脆弱性を解決します。特別な細工がされたファイルが Microsoft ワードパッドまたは Microsoft Office Word で開かれると、これらの脆弱性により、リモートでコードが実行される可能性があります。信頼されないソースからの Microsoft Office、RTF、Write または WordPerfect ファイルを、影響を受けるワードパッドまたは Microsoft Office Word を使用して開かないでください。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-013">MS09-013</a></td>
<td style="border:1px solid black;"><strong>Windows HTTP サービスの脆弱性により、リモートでコードが実行される (960803)</strong><br />
<br />
このセキュリティ更新プログラムは一般で公開された Microsoft Windows HTTP Services (WinHTTP) に存在する 1 件の脆弱性および 2 件の非公開で報告された脆弱性を解決します。最も深刻な脆弱性は、リモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-011">MS09-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft DirectShow の脆弱性により、リモートでコードが実行される (961373)</strong><br />
<br />
この更新プログラムは非公開で報告された Microsoft DirectX に存在する脆弱性を解決します。この脆弱性は、特別な細工がされた MJPEG ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-014">MS09-014</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (963027)</strong><br />
<br />
この累積的なセキュリティ更新プログラムは Internet Explorer に存在する 4 つの非公開で報告された脆弱性と 2 つの公開された脆弱性を解決します。これらの脆弱性により、ユーザーが特別な細工がされた Web ページを Internet Explorer を使用して表示した場合、またはユーザーが HTTP プロトコルを介し攻撃者のサーバーに接続した場合、リモートでコードが実行される可能性があります。システムのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-009">MS09-009</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel の脆弱性により、リモートでコードが実行される (968557)</strong><br />
<br />
このセキュリティ更新プログラムは、Microsoft Office Excel の非公開で報告された 1 件の脆弱性、一般に公開された 1 件の脆弱性を解決します。これらの脆弱性は、特別に細工された Excel ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者がこれらの脆弱性を悪用した場合、影響を受けるシステムが完全に制御される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターのアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-012">MS09-012</a></td>
<td style="border:1px solid black;"><strong>Windows の脆弱性により、特権が昇格される (959454)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 4 つの公開された脆弱性を解決します。これらの脆弱性により、攻撃者がコンピューターにログオンすることが許可され、次に特別な細工がされたアプリケーションを実行した場合に、特権の昇格が起こる可能性があります。この脆弱性が悪用されるには、ローカル コンピューターでコードを実行できることが攻撃者にとっての必要条件となります。攻撃者によりこれらの脆弱性のいずれかが悪用された場合、影響を受けるコンピューターが完全に制御される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-016">MS09-016</a></td>
<td style="border:1px solid black;"><strong>Microsoft ISA Server および Forefront Threat Management Gateway (Medium Business Edition) の脆弱性により、サービス拒否が起こる (961759)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Internet Security and Acceleration (ISA) Server および Microsoft Forefront Threat Management Gateway (TMG), Medium Business Edition (MBE) に存在する非公開で報告された 1 件の脆弱性および一般で公開された 1 件の脆弱性を解決します。これらの脆弱性では、攻撃者が影響を受けるシステムに特別に細工したネットワーク パッケージを送信した場合にサービス拒否を起こす、またはユーザーが攻撃者の制御している悪質な URL のリンク先をクリックする、または web サイトを訪問した場合に情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Forefront Edge Security</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-015">MS09-015</a></td>
<td style="border:1px solid black;"><strong>SearchPath の複合的脅威の脆弱性により、特権が昇格される (959426)</strong><br />
<br />
このセキュリティ更新プログラムは、一般で公開された Windows の SearchPath 機能の脆弱性を解決します。この脆弱性は、ユーザーが特別に細工されたファイルを特定の場所にダウンロードし、ファイルをロード可能なアプリケーションを特定の状況で開いた場合に、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">警告</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号および CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報番号                                                | セキュリティ情報タイトル                                                                                                                | CVE ID                                                                           | Exploitability Index の評価                                                                         | 注意事項                                                                                                                                                                                                                                |  
|---------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-009](https://technet.microsoft.com/security/bulletin/ms09-009) | Microsoft Office Excel の脆弱性により、リモートでコードが実行される (968557)                                                            | [CVE-2009-0100](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0100)     | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                  |  
| [MS09-009](https://technet.microsoft.com/security/bulletin/ms09-009) | Microsoft Office Excel の脆弱性により、リモートでコードが実行される (968557)                                                            | [CVE-2009-0238](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0238)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | **この脆弱性は現在インターネット エコシステム上で悪用されています。**                                                                                                                                                                   |  
| [MS09-010](https://technet.microsoft.com/security/bulletin/ms09-010) | ワードパッドおよび Office テキスト コンバーターの脆弱性により、リモートでコードが実行される (960477)                                    | [CVE-2008-4841](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4841)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | **この脆弱性は現在インターネット エコシステム上で悪用されています。**                                                                                                                                                                   |  
| [MS09-010](https://technet.microsoft.com/security/bulletin/ms09-010) | ワードパッドおよび Office テキスト コンバーターの脆弱性により、リモートでコードが実行される (960477)                                    | [CVE-2009-0087](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0087)     | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | これは複数のコード パスのため、複雑な脆弱性です。ほとんどの悪用コードは一貫性のない結果をもたらします。既定の問題を緩和する要素はこの攻撃の方法から保護します。                                                                         |  
| [MS09-010](https://technet.microsoft.com/security/bulletin/ms09-010) | ワードパッドおよび Office テキスト コンバーターの脆弱性により、リモートでコードが実行される (960477)                                    | [CVE-2009-0088](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0088)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | この脆弱性は悪用される可能性はありますが、影響を受けるのは、旧バージョンおよび旧式の一般的ではないファイル形式のみです。2007 Microsoft Office system や Microsoft Office 2003 Serivce Pack 3 などの新しいバージョンは影響を受けません。 |  
| [MS09-010](https://technet.microsoft.com/security/bulletin/ms09-010) | ワードパッドおよび Office テキスト コンバーターの脆弱性により、リモートでコードが実行される (960477)                                    | [CVE-2009-0235](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0235)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | このメモリの破損の脆弱性は容易に悪用が可能です。                                                                                                                                                                                        |  
| [MS09-011](https://technet.microsoft.com/security/bulletin/ms09-011) | Microsoft DirectShow の脆弱性により、リモートでコードが実行される (961373)                                                              | [CVE-2009-0084](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0084)     | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                  |  
| [MS09-012](https://technet.microsoft.com/security/bulletin/ms09-012) | Windows の脆弱性により、特権が昇格される (959454)                                                                                       | [CVE-2008-1436](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-1436)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | **この脆弱性は現在インターネット エコシステム上で悪用されています。**                                                                                                                                                                   |  
| [MS09-012](https://technet.microsoft.com/security/bulletin/ms09-012) | Windows の脆弱性により、特権が昇格される (959454)                                                                                       | [CVE-2009-0078](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0078)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | **この脆弱性は現在インターネット エコシステム上で悪用されています。**                                                                                                                                                                   |  
| [MS09-012](https://technet.microsoft.com/security/bulletin/ms09-012) | Windows の脆弱性により、特権が昇格される (959454)                                                                                       | [CVE-2009-0079](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0079)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | **この脆弱性は現在インターネット エコシステム上で悪用されています。**                                                                                                                                                                   |  
| [MS09-012](https://technet.microsoft.com/security/bulletin/ms09-012) | Windows の脆弱性により、特権が昇格される (959454)                                                                                       | [CVE-2009-0080](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0080)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | **この脆弱性は現在インターネット エコシステム上で悪用されています。**                                                                                                                                                                   |  
| [MS09-013](https://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP サービスの脆弱性により、リモートでコードが実行される (960803)                                                              | [CVE-2009-0086](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0086)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | この技術は広範囲にわたり使用されているため、複数の攻撃の方法および悪用の機会があり、容易に制御可能なメモリの脆弱性です。                                                                                                                |  
| [MS09-013](https://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP サービスの脆弱性により、リモートでコードが実行される (960803)                                                              | [CVE-2009-0089](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0089)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | 悪用ツールが公開されました。                                                                                                                                                                                                            |  
| [MS09-013](https://technet.microsoft.com/security/bulletin/ms09-013) | Windows HTTP サービスの脆弱性により、リモートでコードが実行される (960803)                                                              | [CVE-2009-0550](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)\*\* | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | 悪用コードが公開されました。                                                                                                                                                                                                            |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 用の累積的なセキュリティ更新プログラム (963027)                                                                       | [CVE-2008-2540](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | この脆弱性が悪用されるには、別のアプリケーションがユーザーの知らない間にコンピューターにファイルを保存することができることが攻撃者にとっての必要条件となるため、現時点ではこの問題の既存の攻撃方法はありません。                        |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 用の累積的なセキュリティ更新プログラム (963027)                                                                       | [CVE-2009-0550](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550)\*\* | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | 悪用コードが公開されました。                                                                                                                                                                                                            |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 用の累積的なセキュリティ更新プログラム (963027)                                                                       | [CVE-2009-0551](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0551)     | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                  |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 用の累積的なセキュリティ更新プログラム (963027)                                                                       | [CVE-2009-0552](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0552)     | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | Internet Explorer 7 の問題を緩和する要素がコードの実行を防ぎます Internet Explorer 6 およびそれ以前のバージョンは、すべての更新プログラムが適用された最新の状態でない場合、悪用される可能性が高くなります。                             |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 用の累積的なセキュリティ更新プログラム (963027)                                                                       | [CVE-2009-0553](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0553)     | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | (なし)                                                                                                                                                                                                                                  |  
| [MS09-014](https://technet.microsoft.com/security/bulletin/ms09-014) | Internet Explorer 用の累積的なセキュリティ更新プログラム (963027)                                                                       | [CVE-2009-0554](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0554)     | [1 - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)         | (なし)                                                                                                                                                                                                                                  |  
| [MS09-015](https://technet.microsoft.com/security/bulletin/ms09-015) | SearchPath の複合的脅威の脆弱性により、特権が昇格される (959426)                                                                        | [CVE-2008-2540](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540)\*   | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 攻撃の詳細が公開されました。                                                                                                                                                                                                            |  
| [MS09-016](https://technet.microsoft.com/security/bulletin/ms09-016) | Microsoft ISA Server および Forefront Threat Management Gateway (Medium Business Edition) の脆弱性により、サービス拒否が起こる (961759) | [CVE-2009-0077](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0077)     | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | サービス ベースのサービス拒否が起こる可能性が非常に高いです。しかし、コードが実行される可能性はありません。                                                                                                                             |  
| [MS09-016](https://technet.microsoft.com/security/bulletin/ms09-016) | Microsoft ISA Server および Forefront Threat Management Gateway (Medium Business Edition) の脆弱性により、サービス拒否が起こる (961759) | [CVE-2009-0237](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-0237)          | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 情報の漏えいが起こる可能性があります。コードが実行される可能性は極めて低いです。                                                                                                                                                        |
  
\*2 種類の更新プログラムにより、同じ脆弱性が解決されます。詳細情報は、該当するセキュリティ情報を参照してください。
  
\*\*2 種類の更新プログラムにより、同じ脆弱性が解決されます。詳細情報は、該当するセキュリティ情報を参照してください。
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
<span></span>
**この表はどのように使用しますか?**
  
この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、脆弱性の深刻度も記載されています。
  
**注:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
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
</tr>
<tr>
<th colspan="7">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=552d322a-5282-42c7-9c1e-1d8c494a7318&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=39d5468e-5733-4c3e-9e75-3adac8ac8cb9&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 8.1](https://www.microsoft.com/download/details.aspx?familyid=0ec5b7c7-13d3-467a-b24e-3cc6fb47adf6&displaylang=ja)  
(緊急)  
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=8b98ed5c-a3ab-45a7-a61e-349eae304bc6&displaylang=ja)\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=7799fd05-5b26-449f-8a14-50227c9164d1&displaylang=ja)  
(緊急)  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=87f0c380-5c31-4099-a6a9-c12f9d69b03b&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=52b756e7-636f-4d9e-8a17-dbf467bfbe4d&displaylang=ja)  
(KB952004)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=c4e408d7-6716-4a12-ad3a-8029667f5c84&displaylang=ja)  
(深刻度なし)
</td>
</tr>
<tr>
<th colspan="7">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=50a8519a-503e-43dd-a78a-c1bc764fd213&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=35af4151-1858-4c9a-85e4-9ff45feca1a4&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=feb5d821-f210-40e8-b1aa-2ca3170df8df&displaylang=ja)\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=052c29fc-e8df-402c-9ab1-1079bc738e1b&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=55d6729a-9f96-4da4-b564-676c0a0c9390&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=90fe715e-8190-43e9-9c43-df5be564d923&displaylang=ja)  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=73d2324f-be59-4b0c-b1ac-9876a13c2c03&displaylang=ja)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3de0684d-605c-489b-bdc7-08bce9b2d4f6&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=49b16f0f-f6c3-4ca8-8041-392f4f7b5bbb&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=f1be8b7c-4874-4342-99b3-76ff725fbb9a&displaylang=ja)\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=84c62211-2e82-4ccc-9f9b-26462b026d86&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=191c2f20-89ae-4e1c-bdd4-24b4abfe6b6c&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a794c32a-9a0c-47d9-9c57-ff5d4a8e4944&displaylang=ja)  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b2f12ae5-0e46-47e1-ac5b-93550d030189&displaylang=ja)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b743a7fe-7bf4-420d-a72e-39471e5659fa&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
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
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2233a4d2-7c8a-4c89-b020-100d9afb43c8&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=42509f5a-d0f9-444a-9445-5eabdb555011&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=c1b4cd76-1dd6-43fa-bb9a-20c428985bfd&displaylang=ja)\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f73a3669-c17f-4b18-8456-96cb7d52ed86&displaylang=ja)  
(重要)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6a45dbd0-0520-4d9b-b76e-3f5109dd310d&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=25adec10-db8c-4cac-bf74-2c784678150a&displaylang=ja)  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=42aba890-8b76-4c5a-8fb6-609797d19831&displaylang=ja)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=992bb0cd-fbc7-4a7c-9088-f7f9d9a3ead0&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7373ea32-bc2e-49f1-8b9f-4eeda5acc74c&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=f0e1e1db-94a5-451c-ab11-6b431fa065f1&displaylang=ja)\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=03a9d581-2bd5-4151-9826-17b96e16f606&displaylang=ja)  
(重要)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=60ccc1d6-ea31-420c-b630-d7878a8dc527&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b014c399-f404-4cb2-8f9d-864df382efeb&displaylang=ja)  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a0609f65-82d9-4d82-9f48-f3266e8de123&displaylang=ja)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f0a58e8c-7d63-4d7d-ba95-b3787cf408f0&displaylang=ja)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=e840b9cb-f1f4-482a-aa07-eb6b42b477c4&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=05e33cc5-cff6-4c71-be71-285f66a95e01&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[DirectX 9.0](https://www.microsoft.com/download/details.aspx?familyid=8f36c215-fa8a-40c2-b680-6b1fece03b8d&displaylang=ja)\*\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=53d13c07-80b0-4f05-b372-a2dac17e6157&displaylang=ja)  
(重要)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0abaa2fb-7c4f-4149-993d-1575888bfc84&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=6ada372b-ba17-433e-b022-d2c57b35af8a&displaylang=ja)  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=fda8837c-e5d2-4489-9b44-4c24a1102e77&displaylang=ja)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=00c6479d-f81f-445d-b8e4-7b71d77d540a&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
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
[Windows Vista および Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f071d770-3b6b-4040-9911-d4de8cde4c68&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d743849d-f3b5-4114-adef-ade2716d55ac&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows Vista および Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=f111b99a-e555-4f29-8d1f-e9ec03d5cf1f&displaylang=ja)  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows Vista および Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=d0ea1598-45cb-4c79-8945-caae98969675&displaylang=ja)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=2b672d45-f33b-4edc-9f22-2f2c8c726a8b&displaylang=ja)  
(警告)
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
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7ceef2d0-f316-48d1-aecc-d74f91cc5e1f&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=d191c8dc-a965-4a6a-b6d8-1470505eb55f&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=fa153bdc-6b48-4df2-9e5e-abacd6da782c&displaylang=ja)  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6dd82f4b-bb33-41ec-90a7-9ef91329b240&displaylang=ja)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=7576e7d5-5bb1-4a53-b568-1ee0500ce721&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-013**](https://technet.microsoft.com/security/bulletin/ms09-013)
</td>
<td style="border:1px solid black;">
[**MS09-011**](https://technet.microsoft.com/security/bulletin/ms09-011)
</td>
<td style="border:1px solid black;">
[**MS09-014**](https://technet.microsoft.com/security/bulletin/ms09-014)
</td>
<td style="border:1px solid black;">
[**MS09-012**](https://technet.microsoft.com/security/bulletin/ms09-012)
</td>
<td style="border:1px solid black;">
[**MS09-015**](https://technet.microsoft.com/security/bulletin/ms09-015)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=4c36548f-c8c9-4318-91e2-9e0501339548&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e2c6313c-3ba9-4f7c-b259-b4582a390146&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows Server 2008 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=9e3c7b52-65a7-42fb-beb5-1b374934737f&displaylang=ja)\*  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows Server 2008 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=d58702af-bbf8-4f1b-ae72-ced9ef23d581&displaylang=ja)\*  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=6b73cf5e-66fe-4b7d-95fc-91a1c262c1e5&displaylang=ja)\*  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=1c3f0997-a8a9-4340-ae0c-2c4d6792c65c&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ebbade9d-704c-440b-8796-6d64225ac01a&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows Server 2008 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=eebb4d4d-29d2-4247-8cbb-63a3b17585ec&displaylang=ja)\*  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows Server 2008 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=20bf4e9b-909b-4bc3-ae43-322d74a4f1c3&displaylang=ja)\*  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=7e60847c-b341-4c38-bc25-2e3cf2d4ae14&displaylang=ja)\*  
(警告)
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
[Windows Server 2008 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=0885b3b0-b78e-4980-902d-dff3886bcaac&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1b04aa6f-b787-4122-bf82-0d150618fe7a&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
MSDTC Transaction Facility update:  
[Windows Server 2008 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=cc383c24-b0f6-47c1-9e89-6a378b09e82f&displaylang=ja)  
(KB952004)  
(重要)  
Windows Service Isolation update:  
[Windows Server 2008 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=bcc2b18f-67db-4109-a9f4-764f985423ee&displaylang=ja)  
(KB956572)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=de1c2b4b-af47-4b9a-8363-720e5527573c&displaylang=ja)  
(警告)
</td>
</tr>
</table>
 
**Windows Server 2008 に関する注意:**

**\*Windows Server 2008 Server Core インストールは影響を受けます。** サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度でこの更新プログラムが適用されます。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

**\*\*Windows Server 2008 Server Core インストールは影響を受けません。**この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用して Windows Server 2008 をインストールした場合、サポートされているエディションの Windows Server 2008 に影響を与えません。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

**MS09-010 に関する注意:**

その他の更新ファイルについては、**Microsoft Office スイートおよびソフトウェア**のセクションをご覧ください。このセキュリティ情報は Windows オペレーティング システムおよびコンポーネントと Microsoft Office スイートおよびソフトウェアの両方を対象としています。

**MS09-011 に関する注意:**

\*\*\*DirectX 9.0 のセキュリティ更新プログラムは DirectX 9.0a, DirectX 9.0b, および DirectX 9.0c にも該当します。

#### Microsoft Office スイートおよびソフトウェア

 
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
Microsoft Office スイート,システム, およびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](https://technet.microsoft.com/security/bulletin/ms09-009)
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
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=95876927-e612-414c-bdec-3632a3100415&displaylang=ja)  
(KB921606)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3dc8b670-25a5-4f46-b7de-12bc693b628a&displaylang=ja)  
(KB959964)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e1db55c6-78fb-498d-89a5-9ad54d971546&displaylang=ja)  
(KB933399)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9a52bf4b-05f6-4b73-94b9-28ed7e20f86c&displaylang=ja)  
(KB959988)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d9dbfa63-c0cb-4c84-9b8a-6e52568045b0&displaylang=ja)  
(KB959995)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=50d8630b-1365-4007-81a0-18c0d6d4b86e&displaylang=ja)\*  
(KB959997)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](https://technet.microsoft.com/security/bulletin/ms09-009)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=52271140-89be-4b9c-baa2-cea09097d703&displaylang=ja)  
(KB968695)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=f6e407eb-11a5-433f-8006-4b822953ca98&displaylang=ja)  
(KB968694)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Other Office Software
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-010**](https://technet.microsoft.com/security/bulletin/ms09-010)
</td>
<td style="border:1px solid black;">
[**MS09-009**](https://technet.microsoft.com/security/bulletin/ms09-009)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c72e6087-b48f-4d2d-8366-01d9f5ff6b6c&displaylang=ja)  
(KB959993)  
(重要)  
[Microsoft Office Excel Viewer](https://www.microsoft.com/download/details.aspx?familyid=58b3929c-5373-47a4-aa97-66d179758792&displaylang=ja)  
(KB960000)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=05f7c517-e551-4dcd-b24a-5d548f2d09cf&displaylang=ja)  
(KB960003)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](https://www.microsoft.com/download/details.aspx?familyid=d763fae3-b2af-47f9-a554-ec786766b3c3&displaylang=ja)  
(KB960476)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>
 
**MS09-010 に関する注意点:**

その他の更新ファイルについては、**Windows オペレーティング システムとコンポーネント**のセクションをご参照ください。このセキュリティ情報は Windows オペレーティング システムおよびコンポーネントとMicrosoft サーバー ソフトウェアの両方を対象としています。

**MS09-009 に関する注意点:**

\*Microsoft Office Excel 2007 Service Pack 1 については、お客様がこのセキュリティ情報で説明している脆弱性から保護するために Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 も併せてインストールする必要があります。

#### Microsoft サーバーおよびセキュリティソフトウェア

 
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Forefront
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-016**](https://technet.microsoft.com/security/bulletin/ms09-016)
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
Microsoft Forefront Threat Management Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Threat Management Gateway, Medium Business Edition](https://www.microsoft.com/download/details.aspx?familyid=6abf9fb4-42d0-4c67-935f-8dc67850148b&displaylang=ja)\*  
(KB968075)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Internet Security and Acceleration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS09-016**](https://technet.microsoft.com/security/bulletin/ms09-016)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=adf623fa-2d74-4f2a-9835-4b8debdb0e1b&displaylang=ja)\*\*  
(KB960995)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=d1d55ab6-3de5-4811-9693-8d43f49f5fe8&displaylang=ja)  
(KB960995)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Internet Security and Acceleration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Internet Security and Acceleration Server 2006](https://www.microsoft.com/download/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770&displaylang=ja)  
(KB968078)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2006 Supportability Update](https://www.microsoft.com/download/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770&displaylang=ja)  
(KB968078)  
(重要)  
[Microsoft Internet Security and Acceleration Server 2006 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770&displaylang=ja)  
(KB968078)  
(重要)
</td>
</tr>
</table>
 
**MS09-016 に関する注意点:**

\*Microsoft Forefront Threat Management Gateway, Medium Business Edition は Windows Essential Business Server 2008 のスタンドアロン製品およびコンポーネントとして出荷されました。

\*\*Microsoft ISA Server 2004 Standard Edition はスタンドアロン製品として出荷されました。また、Microsoft ISA Server 2004 Standard Edition は Windows Small Business Server Enterprise Edition Service Pack 1 および Windows Small Business Server 2003 R2 Enterprise Edition のコンポーネントとしても出荷されました。

検出および展開ツールとガイダンス
--------------------------------

<span></span>
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](https://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](https://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](https://update.microsoft.com/microsoftupdate/)、[Windows Update](https://windowsupdate.microsoft.com/) および [Office Update](https://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](https://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](https://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](https://support.microsoft.com/kb/894199/en-us) (英語情報): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2009 年). すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](https://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](https://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](https://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](https://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS09-009 で説明している問題について報告してくださった [FortiGuard Global Security Research Team](https://www.fortiguardcenter.com/) の Haifei Li 氏
-   MS09-010 で説明している問題について報告してくださった [VeriSign iDefense Labs](https://labs.idefense.com/) の Sean Larsson 氏および Jun Mao 氏
-   MS09-010 で説明している問題について報告してくださった Fortinet の [FortiGuard Global Security Research Team](https://www.fortiguardcenter.com/) と リサーチャー
-   MS09-010 で説明している問題について報告してくださった [VeriSign iDefense Labs](https://labs.idefense.com/) とリサーチャー
-   MS09-011 で説明している問題について報告してくださった [Kryptos Logic](https://www.kryptoslogic.com/) の Piotr Bania 氏
-   MS09-012 で説明しているいくつかの問題について報告してくださった [Argeniss](https://www.argeniss.com/) の Cesar Cerrudo 氏
-   MS09-013 で説明している問題について報告してくださった [iSIGHT Partners](https://www.isightpartners.com/) の Greg MacManus 氏
-   MS09-013 で説明している問題について報告してくださった [Google Inc.](https://www.google.com/corporate) の Wan-Teh Chang 氏および Cem Paya 氏
-   MS09-014 で説明している問題について報告してくださった [Aviv Raff 氏](https://aviv.raffon.net/)
-   MS09-014 で説明している問題について報告してくださった [Google Inc.](https://www.google.com/) の Michal Zalewski 氏
-   MS09-014 で説明している問題について報告してくださった [iSIGHT Partners Labs](https://www.isightpartners.com/)の Ivan Fratric 氏
-   MS09-014 で説明している問題について報告してくださった [Google Inc.](https://www.google.com/) の Skylined 氏
-   MS09-014 で説明している問題について報告してくださった [VenusTech](https://www.venustech.com.cn/) の ADLab
-   MS09-015 で説明している問題について報告してくださった [Aviv Raff 氏](https://aviv.raffon.net/)
-   MS09-016 で説明している問題について報告してくださった New York State Chief Information Officer / Office for Technology

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/04/15: このセキュリティ情報ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
