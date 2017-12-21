---
TOCTitle: 'MS13-MAR'
Title: 2013 年 3 月のセキュリティ情報
ms:assetid: 'ms13-mar'
ms:contentKeyID: 61229713
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms13-mar(v=Security.10)'
---


2013 年 3 月のセキュリティ情報
==============================

公開日: 2013年3月13日 | 最終更新日: 2013年3月22日

**バージョン:** 1.1

[![](../../images/Dn627293.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627293.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2013 年 3 月公開のセキュリティ情報の一覧です。

2013 年 3 月のセキュリティ情報の公開により、2013 年 3 月 8 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「マイクロソフト セキュリティ情報の事前通知」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2013 年 3 月 13 日 の午後 (日本時間) に配信予定です。詳細は、「 [今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx) 」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2013 年 3 月 13 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[3 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538636&culture=en-us) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

#### 概要

次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェアおよびダウンロード先」を参照してください。

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >セキュリティ情報タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動の必要性</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=279923">MS13-021</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2809289)  <br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する非公開で報告された 8 件の脆弱性と、一般に公開された 1 件の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=275737">MS13-022</a></td>
<td style="border:1px solid black;">Silverlight の脆弱性により、リモートでコードが実行される (2814124) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された 1 件の Microsoft Silverlight の脆弱性を解決します。この脆弱性により、攻撃者がこの脆弱性を悪用する特別に細工された Silverlight アプリケーションを含む Web サイトをホストし、ユーザーにその Web サイトを表示するよう誘導した場合、リモートでコードが実行される可能性があります。また、攻撃者は侵害された Web サイトおよびユーザーが提供したコンテンツや広告を受け入れるまたはホストする Web サイトを利用する可能性があります。このような Web サイトには、この脆弱性を悪用する可能性のある特別に細工されたコンテンツが含まれている場合があります。しかし、すべての場合において、攻撃者がユーザーに Web サイトを強制的に訪問させる方法はありません。その代わり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャー メッセージ内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。バナー広告など、影響を受けるシステムに Web コンテンツを配信する方法を使用して、特別に細工した Web コンテンツの表示を可能にする場合もあります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=276801">MS13-023</a></td>
<td style="border:1px solid black;">Microsoft Visio Viewer 2010 の脆弱性により、リモートでコードが実行される (2801261)  <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性は、特別に細工された Visio ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=271610">MS13-024</a></td>
<td style="border:1px solid black;">SharePoint の脆弱性により、特権の昇格が起こる (2780176)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 4 件の Microsoft SharePoint および Microsoft SharePoint Foundation の脆弱性を解決します。最も深刻な脆弱性により、標的となる SharePoint サイトにユーザーを誘導する、特別に細工された URL をユーザーがクリックした場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282355">MS13-025</a></td>
<td style="border:1px solid black;">Microsoft OneNote の脆弱性により、情報漏えいが起こる (2816264)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft OneNote に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者がユーザーに特別な細工がされた OneNote ファイルを開くよう誘導した場合、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=280673">MS13-026</a></td>
<td style="border:1px solid black;">Microsoft Office for Mac の脆弱性により、情報漏えいが起こる (2813682)  <br />
<br />
このセキュリティ更新プログラムは、Microsoft Office for Mac に存在する非公開で報告された 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された電子メール メッセージを開くと、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=282639">MS13-027</a></td>
<td style="border:1px solid black;">カーネルモード ドライバーの脆弱性により、特権の昇格が起こる (2807986)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 3 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性により、攻撃者がシステムへのアクセスを獲得した場合、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
| セキュリティ情報 ID                                       | 脆弱性のタイトル                                              | CVE の識別番号                                                                   | 最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価               | 旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価       | サービス拒否の悪用可能性の評価 | 注意事項                               |  
|-----------------------------------------------------------|---------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------------------------------|----------------------------------------|  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer OnResize の解放後使用の脆弱性               | [CVE-2013-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0087) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer saveHistory の解放後使用の脆弱性            | [CVE-2013-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0088) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CMarkupBehaviorContext の解放後使用の脆弱性 | [CVE-2013-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0089) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CCaret の解放後使用の脆弱性                 | [CVE-2013-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0090) | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CElement の解放後使用の脆弱性               | [CVE-2013-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0091) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer GetMarkupPtr の解放後使用の脆弱性           | [CVE-2013-0092](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0092) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer onBeforeCopy の解放後使用の脆弱性           | [CVE-2013-0093](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0093) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer removeChild の解放後使用の脆弱性            | [CVE-2013-0094](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0094) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-021](http://go.microsoft.com/fwlink/?linkid=279923) | Internet Explorer CTreeNode の解放後使用の脆弱性              | [CVE-2013-1288](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1288) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | この脆弱性は一般で公開されていました。 |  
| [MS13-022](http://go.microsoft.com/fwlink/?linkid=275737) | Silverlight 二重逆参照の脆弱性                                | [CVE-2013-0074](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0074) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                                                                                | 対象外                         | (なし)                                 |  
| [MS13-023](http://go.microsoft.com/fwlink/?linkid=276801) | Visio Viewer のツリー オブジェクトの種類の混同の脆弱性        | [CVE-2013-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0079) | 影響なし                                                                              | [2](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの作成困難 | 対象外                         | (なし)                                 |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | コールバック関数の脆弱性                                      | [CVE-2013-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0080) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | SharePoint XSS の脆弱性                                       | [CVE-2013-0083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0083) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | SharePoint ディレクトリ トラバーサルの脆弱性                  | [CVE-2013-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0084) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                 |  
| [MS13-024](http://go.microsoft.com/fwlink/?linkid=271610) | バッファー オーバーフローの脆弱性                             | [CVE-2013-0085](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0085) | 影響なし                                                                              | [3](http://technet.microsoft.com/ja-jp/security/cc998259) - 悪用コードの可能性低      | 一時的                         | これは、サービス拒否の脆弱性です。     |  
| [MS13-025](http://go.microsoft.com/fwlink/?linkid=282355) | バッファー サイズの検証の脆弱性                               | [CVE-2013-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0086) | 影響なし                                                                              | [3](http://technet.microsoft.com/ja-jp/security/cc998259) - 悪用コードの可能性低      | 対象外                         | これは情報漏えいの脆弱性です。         |  
| [MS13-026](http://go.microsoft.com/fwlink/?linkid=280673) | 意図していないコンテンツが読み込まれる脆弱性                  | [CVE-2013-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0095) | [3](http://technet.microsoft.com/ja-jp/security/cc998259) - 悪用コードの可能性低      | [3](http://technet.microsoft.com/ja-jp/security/cc998259) - 悪用コードの可能性低      | 対象外                         | これは情報漏えいの脆弱性です。         |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 記述子の脆弱性                                    | [CVE-2013-1285](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1285) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | (なし)                                 |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 記述子の脆弱性                                    | [CVE-2013-1286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1286) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | (なし)                                 |  
| [MS13-027](http://go.microsoft.com/fwlink/?linkid=282639) | Windows USB 記述子の脆弱性                                    | [CVE-2013-1287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1287) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | (なし)                                 |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
<span></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ace6994d-7482-40de-84ad-a87853a35860)   
(2809289)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=50c59794-4ec7-404a-b316-dae314521ebb)  
(2809289)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7e5d96a7-d9f5-4832-b4f9-b6e0148c655b)  
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ba528d03-b0a6-40a5-a6bd-13c062a8a877)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=795cef4e-9c01-447f-916c-e52e69eca4a3)   
(2809289)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=16993a2c-1fe1-4c1e-bcd9-db1a7dd4a058)  
(2809289)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=66a08524-883d-4d67-82cc-2c0f55c56b31)  
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4f8a48d4-b1bb-465c-a232-d29fe94d1429)   
(2807986)  
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
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e3c911b3-7fdd-4105-a20a-eef65b0908e3)   
(2809289)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0f58d63e-0d2c-41d2-9792-edbb2f4a539d)  
(2809289)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e6b63da9-a414-40ee-b877-4fb0d62bacba)  
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=835651b7-79fb-4d50-b48e-f02173062253)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eaf2c568-089a-4c2f-bca6-da83f7332de9)   
(2809289)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5a18b139-2773-44c8-85f9-8dce24249e71)  
(2809289)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d6feba92-f014-4521-b6c4-7f5f358a3ce3)  
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9d5f1ed1-f33b-4c90-9b29-ee8ac587d31b)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=088fd3ec-62e1-4737-8132-6b51219ed37f)   
(2809289)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=799748d8-056d-4139-86e1-9bd0cb0151b4)  
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=28d441e7-abcf-4cc9-84e0-572e5b79aab7)   
(2807986)  
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
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0bf77905-1199-4219-a67d-1e9ad3f63757)  
(2809289)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=76e328f8-4f86-4e50-b7e0-22db0385ab01)  
(2809289)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c26f74fc-e224-4533-a4e3-b52125dca5cd)   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b8472bc7-9e20-4238-adcf-a1e1a91687a1)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7b652bb4-7a0a-437b-bcc5-ebbbb820c559)  
(2809289)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=67b09398-ceb6-403c-bba4-261d9d9dea98)  
(2809289)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3f1795a5-4376-4929-8748-743840ec2154)   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e412c54a-a93d-4c5b-9b13-40b59d1dff35)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0303fcb1-34d5-47da-b6ee-18222fe3235a)  
(2809289)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=337068a5-9281-4db6-9ff1-5282cdfa0763)  
(2809289)  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c672c196-5072-468c-8d88-34534fa219fd)   
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f22b9327-1430-44cb-a609-ea1bb9b7b8f8)  
(2809289)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0496cbfe-77d2-4de6-b78d-937225dc8974)  
(2809289)  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5c40f237-b4c8-41eb-a649-baad46dfa13c)   
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=09e4832c-b95e-4581-a73b-49cb6a60c1df)  
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=af2e8e83-fb8f-4ba5-83ec-8bd4347a5fe6)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0)  
(2809289)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085)   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b07b63d5-925d-4c4f-ae19-18a9b141eaa0)  
(2809289)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=54c619b7-e156-4f07-a90e-56ed9a618085)   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c72f78be-e6a8-43b4-9303-7c93dd11d502)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d)  
(2809289)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae)   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=610da6c6-e8a9-4726-ae54-11f01fb5ab2d)  
(2809289)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=86f2a369-d71d-4a36-95ed-d5be89cbbbae)   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6a8a22d6-0e6e-4d3b-afd0-d4841274ade0)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6)  
(2809289)  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37)   
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cf5f65e1-93ae-4ec3-84d2-eb017efdc9d6)  
(2809289)  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c5018865-7162-4d8d-86fc-aacd6d5f0a37)   
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3436d1d1-bf20-40cc-8c51-f093da67c8a9)  
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=01498cd0-e27e-4256-8f21-7a6eeedfb77c)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7c348fe3-f4f0-4f22-8a7f-8563705c1f64)   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 8 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=de4ec125-c337-4615-b39b-8456658dae22)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0c503b83-5b13-41da-a5ff-7519bc244521)   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 8 for 64-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c1539e94-0635-4f51-8172-a96a737d81d3)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
[Internet Explorer 10](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f9b299f1-8a73-40b2-9942-e6419496bb39)   
(2809289)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
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
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10<sup>[1]</sup>   
(2809289)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-021](http://go.microsoft.com/fwlink/?linkid=279923)
</td>
<td style="border:1px solid black;">
[MS13-027](http://go.microsoft.com/fwlink/?linkid=282639)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f1ca4fe0-3ee3-4162-a9fa-48c54fc8b08e) (Server Core インストール)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8b61f3e5-0cf9-4eab-8a59-829957135dd6) (Server Core インストール)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e) (Server Core インストール)   
(2807986)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=84ba3686-14ed-4aac-8db1-4438aa9e0a2e) (Server Core インストール)   
(2807986)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2012](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=959c78e1-29d9-40a3-9eb3-1206c09e3752) (Server Core インストール)   
(2807986)  
(重要)
</td>
</tr>
</table>
 
MS13-021 に関する注意事項

<sup>[1]</sup>Windows RT セキュリティ更新プログラムは [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) からの提供となります。

#### Microsoft Office スイートおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-023](http://go.microsoft.com/fwlink/?linkid=276801)
</td>
<td style="border:1px solid black;">
[MS13-025](http://go.microsoft.com/fwlink/?linkid=282355)
</td>
<td style="border:1px solid black;">
[MS13-026](http://go.microsoft.com/fwlink/?linkid=280673)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=01cc4410-1107-472f-96-f234304a91ca77)   
(2687505)  
(緊急)
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
Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24065dd5-251b-4a3c-bb44-8d552a1f265e)   
(2687505)  
(緊急)
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
Microsoft Visio 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7a1a21e7-3137-4201-a005-cc66379fc1c5)   
(2760762)  
深刻度なし<sup>[1]</sup>
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
Microsoft Visio 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7b7d39f0-a341-4d48-8177-329cccb5a7f1)   
(2760762)  
深刻度なし<sup>[1]</sup>
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
Microsoft Office 2010 Filter Pack Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Filter Pack Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f10db48f-a980-47bf-83a5-c0da4e615114)   
(2553501)  
深刻度なし<sup>[1]</sup>
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
Microsoft Office 2010 Filter Pack Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Filter Pack Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=70d3372b-74a8-4b68-b6c4-18863835915d)   
(2553501)  
深刻度なし<sup>[1]</sup>
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
Microsoft OneNote 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jpdetails.aspx?familyid=da4bfd31-65b9-496b-aa98-4fa8b729dcf3)   
(2760600)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft OneNote 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft OneNote 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=10fc7350-e1d4-40b6-a5d1-8670263faf05)   
(2760600)  
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
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d7aef20a-922b-4495-b473-1afa4a7ac514)   
(2817449)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4960674b-1cb4-499a-999e-7aa4d4c49e5e)   
(2817452)  
(重要)
</td>
</tr>
</table>
 
MS13-023 に関する注意事項

<sup>[1]</sup> 指定ソフトウェアのこの更新プログラムには深刻度が適用されません。この脆弱性に対する既知の攻撃方法は、ブロックされるためです。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p> </p>
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
[MS13-022](http://go.microsoft.com/fwlink/?linkid=275737)
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
Mac にインストールされている Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Mac にインストールされている [Microsoft Silverlight 5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)   
(2814124)   
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
Mac にインストールされている [Microsoft Silverlight 5 Developer Runtime](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)   
(2814124)   
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている [Microsoft Silverlight 5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)   
(2814124)   
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている [Microsoft Silverlight 5 Developer Runtime](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)   
(2814124)   
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている [Microsoft Silverlight 5](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)   
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime
</td>
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている [Microsoft Silverlight 5 Developer Runtime](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=75eef049-1f39-47b4-9a1e-839974fc89b9)  
(2814124)   
(緊急)
</td>
</tr>
</table>
 

#### Microsoft サーバー ソフトウェア

 
<p> </p>
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
[MS13-024](http://go.microsoft.com/fwlink/?linkid=271610)
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
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Server 2010 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a9e8acbd-90e5-4acd-aa8f-b743a352787b)<sup>[1]</sup>   
(wasrv)  
(2553407)  
(緊急)
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
[MS13-024](http://go.microsoft.com/fwlink/?linkid=271610)
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
Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=293666ec-3290-4c6f-a7f6-b44c9b7fa0a6)   
(2687418)  
(重要)
</td>
</tr>
</table>
 
MS13-024 に関する注意事項

<sup>[1]</sup>サポートされているエディションのMicrosoft SharePoint Server 2010 について、お客様はこのセキュリティ情報で説明している脆弱性に対する保護を行うために、Microsoft SharePoint 2010 用のセキュリティ更新プログラム パッケージ (2553407) と共に、Microsoft SharePoint Foundation 2010 のセキュリティ更新プログラム (2687418) もインストールする必要があります。

検出および展開ツールとガイダンス
--------------------------------

<span></span>
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://go.microsoft.com/fwlink/?linkid=69903)を参照してください。[TechNet セキュリティ TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://go.microsoft.com/fwlink/?linkid=85102)を参照してください。この情報には「セキュリティ更新プログラム」リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索で容易に見つけられます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ番号 (たとえば “MS13-001” など) を使用して検索することにより、バスケットに適用可能な更新プログラムをすべて追加することができ (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747/ja) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/wsus/default) の Web サイトを参照してください。

System Center Configuration Manager

System Center Configuration Manager のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。System Center Configuration Manager で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

System Center Configuration Manager の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。System Center Configuration Manager のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。System Center Configuration Manager の詳細については、[System Center テクニカル リソース](http://technet.microsoft.com/ja-jp/systemcenter/bb980621)を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager については、前のセクション「System Center Configuration Manager」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet.microsoft.com/ja-jp/library/cc749197) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 水曜日に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199/ja) :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

MS13-021

-   Internet Explorer OnResize の解放後使用の脆弱性 (CVE-2013-0087) を報告してくださった [TELUS Security Labs](http://telussecuritylabs.com/) の Arseniy Akuney 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer saveHistory の解放後使用の脆弱性 (CVE-2013-0088) を報告してくださった匿名のリサーチャー
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer CMarkupBehaviorContext の解放後使用の脆弱性 (CVE-2013-0089) を報告してくださった匿名のリサーチャー
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer CCaret の解放後使用の脆弱性 (CVE-2013-0090) を報告してくださったHarmony Security の Stephen Fewer 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer CCaret の解放後使用の脆弱性 (CVE-2013-0090) を報告してくださった SkyLined 氏
-   [Exodus Intelligence](https://www.exodusintel.com/) と協力して Internet Explorer CElement の解放後使用の脆弱性 (CVE-2013-0091) を報告してくださった Yenteasy - Security Research の Jose A Vazquez 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer GetMarkupPtr の解放後使用の脆弱性 (CVE-2013-0092) を報告してくださった [Aniway.Aniway@gmail.com](mailto:aniway.aniway@gmail.com) 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer onBeforeCopy の解放後使用の脆弱性 (CVE-2013-0093) を報告してくださったAniway.Aniway@gmail.com 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力してInternet Explorer removeChild の解放後使用の脆弱性 (CVE-2013-0094) を報告してくださった Simon Zuckerbraun 氏
-   Internet Explorer CTreeNode の解放後使用の脆弱性 (CVE-2013-1288) についてマイクロソフトに協力して下さった [Venustech](http://www.venustech.com.cn/) ADLab の Gen Chen 氏
-   Internet Explorer CTreeNode の解放後使用の脆弱性 (CVE-2013-1288) についてマイクロソフトに協力して下さった [Qihoo 360 Security Center](http://www.360.cn/)

MS13-022

-   Silverlight 二重逆参照の脆弱性 (CVE-2013-0074) を報告してくださった [Context Information Security](http://www.contextis.com/) の James Forshaw 氏

MS13-023

-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して Visio Viewer ActiveX のツリー オブジェクトの種類の混同の脆弱性 (CVE-2013-0079) を報告してくださった[Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 氏

MS13-024

-   コールバック関数の脆弱性 (CVE-2013-0080) を報告してくださった [BugSec](http://www.bugsec.com/) の Emanuel Bronshtein 氏
-   SharePoint XSS の脆弱性 (CVE-2013-0083) を報告してくださった INR Labs ([Network Intelligence India](http://niiconsulting.com/)) の Sunil Yadav 氏
-   SharePoint ディレクトリ トラバーサルの脆弱性 (CVE-2013-0084) について報告してくださった [n.runs AG](http://www.nruns.com/) の Moritz Jodeit 氏

MS13-025

-   バッファー サイズの検証の脆弱性 (CVE-2013-0086) を報告してくださった の Christopher Gabriel 氏

MS13-026

-   意図していないコンテンツが読み込まれる脆弱性 (CVE- 2013-0095) の問題を報告してくださった [Nick Semenkovich](https://technet.microsoft.com/ja-JP/mailto:semenko@alum.mit.edu) 氏

MS13-027

-   Windows USB 記述子の脆弱性 (CVE-2013-1285) を報告してくださった NCC Group の Andy Davis 氏
-   Windows USB 記述子の脆弱性 (CVE-2013-1286) を報告してくださった NCC Group の Andy Davis 氏
-   Windows USB 記述子の脆弱性 (CVE-2013-1287) を報告してくださった NCC Group の Andy Davis 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617.aspx)
-   Windows を実行しているコンピューターのウィルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2013/03/13):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2013/03/22): MS13-026 について、「概要」のセクションでセキュリティ情報のタイトルを修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
