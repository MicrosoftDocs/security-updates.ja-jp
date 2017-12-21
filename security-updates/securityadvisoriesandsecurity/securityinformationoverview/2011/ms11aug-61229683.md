---
TOCTitle: 'MS11-AUG'
Title: 2011 年 8 月のセキュリティ情報
ms:assetid: 'ms11-aug'
ms:contentKeyID: 61229683
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-aug(v=Security.10)'
--- Summary

2011 年 8 月のセキュリティ情報
==============================

公開日: 2011年8月10日 | 最終更新日: 2011年10月31日

**バージョン:** 1.2

[![](../../images/Dn627262.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627262.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2011 年 8 月公開のセキュリティ情報の一覧です。

2011 年 8 月のセキュリティ情報の公開により、2011 年 8 月 5 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、[「マイクロソフト セキュリティ情報の事前通知」](http://technet.microsoft.com/security/bulletin/advance)を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 8 月 10 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2011 年 8 月 10 日午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[8 月の セキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487857) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

概要
----

 
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェアおよびダウンロード先」を参照してください。

 
<p></p>

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2559049) <br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する 5 件の非公開で報告された脆弱性と 2 件の公開された脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、 <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-058">MS11-058</a></td>
<td style="border:1px solid black;">DNS サーバーの脆弱性により、リモートでコードが実行される (2562485) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Windows DNS サーバーの脆弱性を解決します。これらの脆弱性でより深刻なものが悪用された場合、攻撃者がドメインを登録し、NAPTR DNS リソース レコードを作成したうえで、特別に細工された NAPTR クエリを標的となる DNS サーバーに送信すると、リモートでコードが実行される可能性があります。DNS の役割が有効になっていないサーバーは、危険にさらされません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms11-059">MS11-059</a></td>
<td style="border:1px solid black;">Data Access Components の脆弱性により、リモートでコードが実行される (2560656) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたライブラリ ファイルと同じネットワーク ディレクトリにある正当な Excel ファイル (.xlsx ファイルなど) を開いた場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-060">MS11-060</a></td>
<td style="border:1px solid black;">Microsoft Visio の脆弱性により、リモートでコードが実行される (2560978) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Visio に存在する脆弱性を解決します。特別に細工された Visio ファイルをユーザーが開いた場合、この脆弱性によりリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-061">MS11-061</a></td>
<td style="border:1px solid black;">リモート デスクトップ Web アクセスの脆弱性により、特権が昇格される (2546250) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件のリモート デスクトップ Web アクセスの脆弱性を解決します。この脆弱性は、クロスサイト スクリプト (XSS) の脆弱性で、特権を昇格し、標的となるユーザーのコンテキストで、攻撃者がサイト上で任意のコマンドを実行することが可能になります。Internet Explorer 8 および Internet Explorer 9 の XSS フィルターは、ユーザーがインターネット ゾーン内のリモート デスクトップ Web アクセス サーバーを閲覧するときにこの攻撃を防ぎます。Internet Explorer 8 および Internet Explorer 9 の XSS フィルターは、イントラネット ゾーンでは既定で有効になっていません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-062">MS11-062</a></td>
<td style="border:1px solid black;">リモート アクセス サービス NDISTAPI ドライバーの脆弱性により、特権が昇格される (2566454) <br />
<br />
このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP および Windows Server 2003 の非公開で報告された脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP、Windows Server 2003 について、深刻度は「重要」です。Windows Vista、Windows Server 2008、Windows 7 および Windows Server 2008 R2 はこの脆弱性の影響を受けません。<br />
<br />
この脆弱性により、攻撃者が影響を受けるコンピューターにログオンし、この脆弱性を悪用するため特別に細工されたアプリケーションを実行して、影響を受けるコンピューターを完全に制御した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-063">MS11-063</a></td>
<td style="border:1px solid black;">Windows クライアント/サーバー ランタイム サブシステムの脆弱性により、特権が昇格される (2567680) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるコンピューターにログオンし、デバイス イベント メッセージを整合性レベルの高いプロセスに送信するため特別に細工されたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-064">MS11-064</a></td>
<td style="border:1px solid black;">TCP/IP スタックの脆弱性により、サービス拒否が起こる (2563894) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。この脆弱性により、攻撃者が特別に細工された一連のインターネット制御メッセージ プロトコル (ICMP) メッセージを標的となるコンピューターに送信した場合、または特別に細工された URL リクエストを URL ベースのサービスの品質 (QoS) 機能が有効で Web コンテンツをサービスするサーバーに送信した場合、サービス拒否が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-065">MS11-065</a></td>
<td style="border:1px solid black;">リモート デスクトップ プロトコル の脆弱性によりサービス拒否が発生する (2570222) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件のリモート デスクトップ プロトコルの脆弱性を解決します。この脆弱性により、影響を受けるコンピューターが特別な細工がされた一連の RDP パケットを受け取った場合、サービス拒否が起こる可能性があります。マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃についての報告も受け取っています。既定では、リモート デスクトップ プロトコル (RDP) はどの Windows オペレーティング システムでも有効になっていません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-066">MS11-066</a></td>
<td style="border:1px solid black;">Microsoft Chart Controls の脆弱性により、情報漏えいが起こる (2567943) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の ASP .NET Chart Controls の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工した GET リクエストを Chart Controls をホストする影響を受けるサーバーに送信した場合、情報漏えいが起こる可能性があります。この脆弱性により、攻撃者は直接コードを実行したり、攻撃者自身のユーザー権限を昇格させたりはできませんが、この脆弱性を悪用し、攻撃に使用する情報を取得し、影響を受けるコンピューターをさらに侵害しようとする可能性があります。Microsoft Chart Controls を使用する Web アプリケーションだけがこの問題の影響を受けます。.NET Framework の既定のインストールは影響を受けません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft .NET Framework、 <br />
マイクロソフト開発者用ツール</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-067">MS11-067</a></td>
<td style="border:1px solid black;">Microsoft Report Viewer の脆弱性により、情報の漏えいが起こる (2578230) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft Report Viewer の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web ページを表示すると、情報漏えいが起こる可能性があります。ただし、いずれの場合も、攻撃者が強制的にユーザーをこのような Web サイトにアクセスさせることはできません。その代わりに、影響を受けた Web サイトにユーザーを誘導する電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをユーザーにクリックさせて、攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">マイクロソフト開発者用ツール</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-068">MS11-068</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、サービス拒否が起こる (2556532) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、特別に細工されたファイルを含むネットワーク共有 (または、そのようなネットワーク共有をポイントする Web サイト) をユーザーが訪問した場合、サービス拒否が起こる可能性があります。しかし、いかなるケースにおいても、攻撃者は、そのようなネットワーク共有または Web サイトにユーザーを強制的に訪問させる手段を持っていません。その代わり、電子メールやインスタント メッセンジャーのメッセージ内のリンクをユーザーにクリックさせることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">警告</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-069">MS11-069</a></td>
<td style="border:1px solid black;">.NET Framework の脆弱性により、情報漏えいが起こる (2567951) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft .NET Framework の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web ページを XAML ブラウザー アプリケーション (XBAP) を使用して表示した場合、情報漏えいが起こる可能性があります。Web ベースの攻撃では、この脆弱性の悪用に使用する Web ページが含まれる Web サイトを攻撃者がホストしているケースなどが挙げられます。また、侵害された Web サイトやユーザーによって提供されたコンテンツや広告を容認またはホストする Web サイトに、この脆弱性を悪用するために特別に細工したコンテンツが含まれている場合があります。ただし、いずれの場合も、攻撃者が強制的にユーザーをこのような Web サイトにアクセスさせることはできません。その代わりに攻撃者は、ユーザーをこのような Web サイトにアクセスさせるように誘導する必要があります。そのためによく用いられる方法として、電子メール メッセージやインスタント メッセージのリンクをクリックするように仕向け、クリックすると攻撃者の Web サイトに誘導されるという方法があります。この脆弱性は、コード アクセス セキュリティ (CAS) の制限を回避する目的で Windows .NET で悪用される可能性もあります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">警告</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft .NET Framework</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >脆弱性のタイトル</th>
<th style="border:1px solid black;" >CVE の識別番号</th>
<th style="border:1px solid black;" >最新のソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >旧バージョンのソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >サービス拒否の悪用可能性の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">ウィンドウが開く競合状態の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1257">CVE-2011-1257</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">イベント ハンドラーの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1960">CVE-2011-1960</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">Telnet ハンドラーのリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1961">CVE-2011-1961</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">XSLT のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1963">CVE-2011-1963</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-057">MS11-057</a></td>
<td style="border:1px solid black;">Style のオブジェクトのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1964">CVE-2011-1964</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-058">MS11-058</a></td>
<td style="border:1px solid black;">DNS NAPTR クエリの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1966">CVE-2011-1966</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-058">MS11-058</a></td>
<td style="border:1px solid black;">DNS の初期化されていないメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1970">CVE-2011-1970</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms11-059">MS11-059</a></td>
<td style="border:1px solid black;">Data Access Components の安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1975">CVE-2011-1975</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-060">MS11-060</a></td>
<td style="border:1px solid black;">pStream リリースの RCE の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1972">CVE-2011-1972</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-060">MS11-060</a></td>
<td style="border:1px solid black;">ブロック移動の RCE の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1979">CVE-2011-1979</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-061">MS11-061</a></td>
<td style="border:1px solid black;">リモート デスクトップ Web アクセスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1263">CVE-2011-1263</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-062">MS11-062</a></td>
<td style="border:1px solid black;">NDISTAPI の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1974">CVE-2011-1974</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-063">MS11-063</a></td>
<td style="border:1px solid black;">CSRSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1967">CVE-2011-1967</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-064">MS11-064</a></td>
<td style="border:1px solid black;">ICMP のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1871">CVE-2011-1871</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-064">MS11-064</a></td>
<td style="border:1px solid black;">TCP/IP のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1965">CVE-2011-1965</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-065">MS11-065</a></td>
<td style="border:1px solid black;">リモート デスクトップ プロトコルの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1968">CVE-2011-1968</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この脆弱性を対象とする限定的な標的型攻撃が報告されています<br />
<br />
これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-066">MS11-066</a></td>
<td style="border:1px solid black;">Chart Controls の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1977">CVE-2011-1977</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-067">MS11-067</a></td>
<td style="border:1px solid black;">レポート ビューアー コントロール XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1976">CVE-2011-1976</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
</tbody>
</table>

<p></p>

  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント
  
表 1:

 
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
</tr>
<tr>
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-057](http://technet.microsoft.com/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[MS11-058](http://technet.microsoft.com/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[MS11-059](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[MS11-061](http://technet.microsoft.com/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[MS11-062](http://technet.microsoft.com/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[MS11-063](http://technet.microsoft.com/security/bulletin/ms11-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=90312c78-1fbd-4143-b2e6-ae5c48af6f57)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a771c93b-55a4-456f-a315-d0d1f2696960)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5feb8ed7-99d2-4dd6-986f-57a7fd0c6f19)  
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
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6bc1f0ac-223d-4b0b-86cd-2ba3863955c4)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0231c103-c0cb-4705-9d92-5356b8cbb265)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=23d77f3b-13f8-49f3-9c3c-27ad217cd59e)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=acb14d82-a801-4ec7-84cc-9f131009ebcb)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=272c813b-bd39-4e63-9fa7-c5b8ed0b08d7)  
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
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d5ee6787-408d-4870-af70-9338158b161b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=09276f6e-e3f4-4b7e-996e-4ec376c103e1)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-057](http://technet.microsoft.com/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[MS11-058](http://technet.microsoft.com/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[MS11-059](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[MS11-061](http://technet.microsoft.com/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[MS11-062](http://technet.microsoft.com/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[MS11-063](http://technet.microsoft.com/security/bulletin/ms11-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=26b5fb48-346a-49f1-840f-03f218a41c20)  
(重要)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=042552ad-f46a-4bfc-9e5c-58f095eba1de)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=648596fc-fd97-438a-97be-d5d590f1c561)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c2d4aa38-9241-465d-8d65-aba73e936d0f)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8de0f2db-aa09-48cd-a13b-e26a973e9cdc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=870fdfdd-16bf-42a2-a23b-ed6045438d5e)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9c3d14d8-6716-4423-91a9-a05373227237)  
(重要)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c9e283d8-d4a2-41e2-a73c-92fae957ba3d)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=470d56d1-5789-42cc-a088-a2c8ac934ab3)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2db4098a-f4f9-4211-b55d-5d0df1409c43)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f208407-4bb3-41fe-b0d6-fc8a5e30e667)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=31af27b8-7b73-4090-94bd-2fb89d3970fc)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=64496a87-2225-402a-a94a-a8e92b17ac83)  
(重要)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5aa3a493-4188-48a9-a549-cf9ba01ed32a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1934acfa-5637-4ae9-9e9a-fc7e58930b7a)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef140089-d022-4ee8-9cc4-7fb25295a39d)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=410c72d8-3b78-4c4a-ad61-acb7f854ffc2)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-057](http://technet.microsoft.com/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[MS11-058](http://technet.microsoft.com/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[MS11-059](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[MS11-061](http://technet.microsoft.com/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[MS11-062](http://technet.microsoft.com/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[MS11-063](http://technet.microsoft.com/security/bulletin/ms11-063)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=66ddc7ce-5280-494d-bb3c-dab06e27fb5c)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a080f36e-c24f-40ac-bb40-b26cb31bcae3)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c82417ec-232f-4f84-ba2c-0ffad77e9bb5)  
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
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f25ced5-ef86-4b9d-91fb-443c9a2c1458)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3f119902-8398-4814-8229-9eb9f0980e87)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=704c1c9c-d1c1-40cb-97a7-fbb1f195f9f8)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a6ff7b27-bc21-4945-8b2e-757b6f83fa58)  
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
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d5b8ff09-237e-49f1-a566-e323ca11fbc3)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-057](http://technet.microsoft.com/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[MS11-058](http://technet.microsoft.com/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[MS11-059](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[MS11-061](http://technet.microsoft.com/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[MS11-062](http://technet.microsoft.com/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[MS11-063](http://technet.microsoft.com/security/bulletin/ms11-063)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=da9c98d1-973c-44d9-aee5-f5c4a8e8c0e1)\*\*  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d65ae4cc-d82a-42da-829f-d9479e23b7a5)\*\*  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=70065bd0-7c97-4ffc-828f-2cc245d04429)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ac2d5122-6f9b-46f5-9840-77aa7ff84308)\*  
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
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1fbaabb9-8601-4760-813d-aeedfdcafb8b)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9facff69-618f-4a64-8665-5dd6cde07de9)\*\*  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=00f28d81-3714-403c-bcd7-55f2ac97f75b)\*\*  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9ce60689-ca85-4c9f-af96-a73b1e43c10b)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5f605f6f-3854-403d-878b-637626aef78f)\*  
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
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2e7253d8-fdc7-4563-9714-21ca3c77e4b1)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=01885624-cfb1-4918-abef-ab0ea765cb04)  
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
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fe37eb6d-b1fa-496c-a0d3-19a6d35a6cb9)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-057](http://technet.microsoft.com/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[MS11-058](http://technet.microsoft.com/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[MS11-059](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[MS11-061](http://technet.microsoft.com/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[MS11-062](http://technet.microsoft.com/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[MS11-063](http://technet.microsoft.com/security/bulletin/ms11-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7019de24-8c58-4565-ada1-ca8755115096)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=12292081-23f7-4968-8cd7-17aaef2aed6a)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6bc168d9-6664-41fb-914f-dbd7514a4b0e)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f4551b77-eb09-448a-9dc5-66de846035e7)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fcdb872f-2ee2-4f74-b7ae-1b82daf66761)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef664114-6582-49d3-b332-078a7d075337)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=aafeff2d-db9a-4b3b-b620-be4ec5f5bdcc)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0fc9a501-523d-4cbb-8d99-a773089afc4c)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-057](http://technet.microsoft.com/security/bulletin/ms11-057)
</td>
<td style="border:1px solid black;">
[MS11-058](http://technet.microsoft.com/security/bulletin/ms11-058)
</td>
<td style="border:1px solid black;">
[MS11-059](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-059)
</td>
<td style="border:1px solid black;">
[MS11-061](http://technet.microsoft.com/security/bulletin/ms11-061)
</td>
<td style="border:1px solid black;">
[MS11-062](http://technet.microsoft.com/security/bulletin/ms11-062)
</td>
<td style="border:1px solid black;">
[MS11-063](http://technet.microsoft.com/security/bulletin/ms11-063)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14fe68eb-2aa6-4a59-b9d8-deeae5236af2)\*\*  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dd709da2-4cb1-482f-88eb-dfab4d3c59c6)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6a86e2cf-4e7d-4012-88c3-6957a3842dd3)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c29deec3-4672-4658-a550-dce244434cd4)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=777f3bbe-094c-411d-879d-34a5a20ae7f3)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2f4043df-c07c-4611-b06a-7fcbb7416e7d)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=82403fd3-ed75-4ea8-aa3f-ed9dda75612a)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1d6b8036-d38f-408a-a36c-027553faefc1)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b420cae3-de30-4c6c-8ed9-7431ad7ab4da)  
(重要)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

表 2

 
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
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-064](http://technet.microsoft.com/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[MS11-065](http://technet.microsoft.com/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[MS11-066](http://technet.microsoft.com/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[MS11-068](http://technet.microsoft.com/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[MS11-069](http://technet.microsoft.com/security/bulletin/ms11-069)
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
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c07e1630-43ba-491e-bd59-9eb53105986c)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=797a01dc-39fb-4511-832a-42d2975133f5)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-064](http://technet.microsoft.com/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[MS11-065](http://technet.microsoft.com/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[MS11-066](http://technet.microsoft.com/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[MS11-068](http://technet.microsoft.com/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[MS11-069](http://technet.microsoft.com/security/bulletin/ms11-069)
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
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=694ba1a6-7512-497d-a572-646a6e07b13b)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=308da543-d49d-4591-8bbc-d65c524bb0ad)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3b459bf0-7844-4740-895c-d149d56e781f)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc)  
(KB2539631)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-064](http://technet.microsoft.com/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[MS11-065](http://technet.microsoft.com/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[MS11-066](http://technet.microsoft.com/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[MS11-068](http://technet.microsoft.com/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[MS11-069](http://technet.microsoft.com/security/bulletin/ms11-069)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=114c2835-921a-4d3e-be91-dfd217fd26a9)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9713b7b8-f260-440d-a994-845f17683fe9)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0fcee476-8d7e-49a7-b6ea-89043304a653)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4d67ec00-e86a-49b6-a9a2-85b2520fa4bb)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-064](http://technet.microsoft.com/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[MS11-065](http://technet.microsoft.com/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[MS11-066](http://technet.microsoft.com/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[MS11-068](http://technet.microsoft.com/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[MS11-069](http://technet.microsoft.com/security/bulletin/ms11-069)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c01d9132-af5f-4039-8195-95f6761f2d0e)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=da219735-b8b7-4f97-b8a8-7c253838de6b)\*\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=70797adb-d693-4102-9e7c-ba1ea8fb07d0)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*\*<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8e077af5-5823-4377-a997-44b022a694d8)\*\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)\*\*  
(KB2539633)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*\*<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9babf81a-8b21-42ae-a65c-f414793516ab)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=560efa6f-c956-47cb-a2f4-a1f45278b7cd)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834)  
(KB2539633)  
(警告)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-064](http://technet.microsoft.com/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[MS11-065](http://technet.microsoft.com/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[MS11-066](http://technet.microsoft.com/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[MS11-068](http://technet.microsoft.com/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[MS11-069](http://technet.microsoft.com/security/bulletin/ms11-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=814bbdfa-7cbc-40e5-8ca3-8fed9d13ff00)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6c8dd72b-abf8-4e1f-aafc-777c1a3ef3db)  
(警告)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(警告)  
Windows 7 for 32-bit Systems のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)  
Windows 7 for 32-bit Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(警告)  
Windows 7 for 32-bit Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=085ee785-b6ad-4c68-835a-e17bc8f12a53)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d90c07c1-3c07-4989-825c-fb8453541a0e)  
(警告)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(警告)  
Windows 7 for x64-based Systems のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)  
Windows 7 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(警告)  
Windows 7 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-064](http://technet.microsoft.com/security/bulletin/ms11-064)
</td>
<td style="border:1px solid black;">
[MS11-065](http://technet.microsoft.com/security/bulletin/ms11-065)
</td>
<td style="border:1px solid black;">
[MS11-066](http://technet.microsoft.com/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[MS11-068](http://technet.microsoft.com/security/bulletin/ms11-068)
</td>
<td style="border:1px solid black;">
[MS11-069](http://technet.microsoft.com/security/bulletin/ms11-069)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9fd2b4ba-d98e-4ad6-99f2-c471335042d3)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)\*<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=67cccd09-5b82-4546-884a-d2a9e2400820)\*\*\*  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)\*  
(KB2539634)  
(警告)  
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)\*  
(KB2539635)  
(警告)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)\*<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=93752c8f-5461-4e6f-9cab-6401b985ef17)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd)<sup>[1]</sup>
(KB2487367)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a1edf843-9a2a-4334-a95f-78e75a9b3ef1)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c)  
(KB2539634)  
(警告)  
Windows Server 2008 R2 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e1f84749-77bb-42bf-a539-fb647cacff8b)  
(KB2539635)  
(警告)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e2069b12-d78b-420c-84b7-46bba12827c8)<sup>[1]</sup>
(KB2539636)  
(警告)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*\*Server Core インストールは影響を受けません。 この更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 または Windows Server 2008 R2 をインストールした場合、この脆弱性による影響を受けるファイルがコンピューターに存在していたとしても、サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 に影響を与えません。しかし、更新プログラムのファイルのバージョン番号は現在コンピューターに存在するファイルのものより新しいため (より新しいバージョン番号を持つため)、この更新プログラムが提供されます。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

MS11-066 に関する注意

<sup>[1]</sup>.NET Framework 4 Client Profile は影響を受けません。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 に影響を及ぼしますが、.NET Framework 4 Client Profile には影響しません。詳細については、MSDN の「[.NET Framework のインストール](http://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS11-069 に関する注意

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「[.NET Framework のインストール](http://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

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
Microsoft Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-060](http://technet.microsoft.com/security/bulletin/ms11-060)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=866d64b3-7147-4b5f-80fe-4d3317f140df)  
(KB2553009)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a0eeabde-5a92-45ae-aef6-81b7bdb4e0cd)  
(KB2553010)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio 2010 および Microsoft Visio 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 および Microsoft Visio 2010 Service Pack 1 (32-bit エディション)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6da236c2-0ef5-4c13-8393-673b70298a77)  
(KB2553008)  
(重要)  
[Microsoft Visio 2010 および Microsoft Visio 2010 Service Pack 1 (64-bit エディション)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b7f5f2a9-116a-41ef-a19e-a7dd0947d2cb)  
(KB2553008)  
(重要)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft 開発者用ツールおよびソフトウェア

 
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
Chart Controls
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-066](http://technet.microsoft.com/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[MS11-067](http://technet.microsoft.com/security/bulletin/ms11-067)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Chart Controls for Microsoft .NET Framework 3.5 Service Pack 1
</td>
<td style="border:1px solid black;">
[Chart Controls for Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8a80cc03-0db9-4446-9ce6-159ad02cab52)  
(KB2500170)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Studio および Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-066](http://technet.microsoft.com/security/bulletin/ms11-066)
</td>
<td style="border:1px solid black;">
[MS11-067](http://technet.microsoft.com/security/bulletin/ms11-067)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=59231988-5413-4238-a3aa-32a127871430)  
(KB2548826)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 再頒布可能パッケージ
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=28bf2ae0-9e21-4201-b7f1-a207abc2866f)  
(KB2579115)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS11-066 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

検出および適用ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および適用のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および適用に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および適用のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

System Center Configuration Manager 2007

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](http://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。Configuration Manager の詳細については、[System Center Configuration Manager](http://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS11-057 で説明している問題を報告してくださった [Opera Software ASA](http://www.opera.com/) の Yngve N. Pettersen 氏
-   MS11-057 で説明している問題を報告してくださった [Lostmon Lords](http://lostmon.blogspot.com) 氏
-   MS11-057 で説明している問題を報告してくださった [Security Professionals Network Inc.](http://www.sec-pro.net/) の Makoto Shiotsuki 氏
-   MS11-057 で説明している問題を報告したくださった、[TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している匿名のリサーチャー
-   MS11-057 で説明している 2 件の問題を報告してくださった、[TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している [Harmony Security](http://www.harmonysecurity.com/) の Stephen Fewer 氏
-   ms11-057 に含まれている多層防御の変更についてマイクロソフトと協力してくださった [Google Inc.](http://www.google.com/) の Michal Zalewski 氏
-   MS11-058 で説明している問題を報告してくださった [Zengel Medizintechnik GmbH](http://www.zmt.info/) の Grischa Zengel 氏
-   MS11-060 で説明している 2 件の問題を報告してくださった [Baidu Security Team](http://www.baidu.com) の Linlin Zhao 氏
-   MS11-061 で説明している問題を報告してくださった Sven Taute 氏
-   MS11-062 で説明している問題を報告してくださった の Lufeng Li 氏
-   MS11-063 で説明している問題を報告してくださった Winsider Seminars & Solutions Inc. の Alex Ionescu 氏
-   MS11-066 で説明している問題を報告してくださった Context Information Security の Nico Leidecker 氏と James Forshaw 氏
-   MS11-067 で説明している問題を報告してくださった [Gotham Digital Science](http://www.gdssecurity.com/) の Adam Bixby 氏
-   MS11-068 で説明している問題を報告してくださった [Qihoo 360 Security Center](http://www.360.cn/) の Zheng Wenbin 氏
-   MS11-069 で説明している問題を報告してくださった Michael J. Liu 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](http://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2011/08/10):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2011/08/11):MS11-059 を更新し、「概要」セクションの再起動に関する情報をを修正しました。MS11-065 を更新し、CVE-2011-1968 について Exploitability Index (悪用可能性指標) の「注意事項」を修正しました。MS11-068 を更新し、Windows Server 2008 および Windows Server 2008 R2 の Server Core に関する記述を改訂しました。
-   V1.2 (2011/10/31):MS11-066 および MS11-069 を更新し、Windows Server 2008 R2 for x64-based System 上の .NET Framework 4 の Server Core インストールの適用オプションを修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
