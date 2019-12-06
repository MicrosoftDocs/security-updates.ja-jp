---
TOCTitle: 'MS09-OCT'
Title: 2009 年 10 月のセキュリティ情報
ms:assetid: 'ms09-oct'
ms:contentKeyID: 61229668
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-oct(v=Security.10)'
--- 

2009 年 10 月のセキュリティ情報
===============================

公開日: 2009年10月14日 | 最終更新日: 2010年6月23日

**バージョン:** 1.0

[![](../../images/Dn627247.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/dd251169.aspx)[![](../../images/Dn627247.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------


[MS09-050 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-050e.mspx)

[MS09-051 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-051e.mspx)

[MS09-052 : Windows Media Player の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-052e.mspx)

[MS09-053 : Internet Information Services の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-053e.mspx)

[MS09-054 : Internet Explorer の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-054e.mspx)

[MS09-055 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-055e.mspx)

[MS09-056 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-056e.mspx)

[MS09-057 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-057e.mspx)

[MS09-058 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-058e.mspx)

[MS09-059 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-059e.mspx)

[MS09-060 : Office の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-060e.mspx)

[MS09-061 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-061e.mspx)

[MS09-062 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-062e.mspx)

このセキュリティ情報は 2009 年 10 月 14 日に公開したセキュリティ情報の一覧です。

2009 年 10 月 14 日のセキュリティ情報の公開により、2009 年 10 月 9 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 10 月 14 日 の午後 (日本時間) に配信します。なお、今月より月例セキュリティ更新プログラムの適用優先順位に関する情報を提供します。詳細は、10 月 14 日午後配信予定の「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 10 月 14 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[10 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407488&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-050">MS09-050</a></td>
<td style="border:1px solid black;"><strong>SMBv2 の脆弱性により、リモートでコードが実行される (975517)</strong><br />
<br />
このセキュリティ更新プログラムは、Server Message Block Version 2 (SMBv2) に存在する 1 件の一般で報告された脆弱性および非公開で報告された 2 件の脆弱性を解決します。攻撃者が特別に細工した SMB パケットを Server サービスを実行しているコンピューターに送信した場合、最も深刻な脆弱性により、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-051">MS09-051</a></td>
<td style="border:1px solid black;"><strong>Windows Media Runtime の脆弱性により、リモートでコードが実行される (975682)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Windows Media Runtime に存在する 2 件の脆弱性を解決します。これらの脆弱性で、ユーザーが特別な細工がされたメディア ファイルを開くか、または Web サイトや Web コンテンツを配信するアプリケーションから特別な細工がされたストリーミング コンテンツを受け取った場合、リモートでコードが実行される可能性があります。これらの脆弱性が悪用された場合、攻撃者によりローカル ユーザーと同じ権限が取得される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-052">MS09-052</a></td>
<td style="border:1px solid black;"><strong>Windows Media Player の脆弱性により、リモートでコードが実行される (974112)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows Media Player の脆弱性を解決します。 この脆弱性で、特別な細工がされた ASF ファイルが Windows Media Player 6.4 を使用して再生された場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-054">MS09-054</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (974455)</strong><br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する非公開で報告された 3 件の脆弱性と一般に公開された 1 件の脆弱性を解決します。この脆弱性では、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。Windows Presentation Foundation (WPF) のプラグインを実行している Firefox ユーザーで、それを無効にしていない場合もまた、このセキュリティ更新プログラムを適用する必要があります。この問題に関する詳細情報は、「HTML のコンポーネント処理の脆弱性 - CVE-2009-2529」のよく寄せられる質問をご覧ください。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-055">MS09-055</a></td>
<td style="border:1px solid black;"><strong>ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (973525)</strong><br />
<br />
この累積的なセキュリティ更新プログラムは、非公開で報告された現在悪用されている共通した複数の ActiveX コントロールの脆弱性を解決します。脆弱なバージョンの Microsoft Active Template Library (ATL) を使用してコンパイルされた影響を受ける ActiveX コントロールに存在する脆弱性により、ユーザーが特別な細工がされた Web ページを Internet Explorer で表示し、ActiveX コントロールをインスタンス化した場合、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-060">MS09-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用の Microsoft ATL (Active Template Library) の ActiveX コントロールの脆弱性により、リモートでコードが実行される (973965)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Office 用の Microsoft ATL (Active Template Library) の ActiveX コントロールに存在するいくつかの非公開で報告された脆弱性を解決します。これらの脆弱性により、ユーザーが悪意のある Web サイトでホストされている特別な細工がされたコンポーネントまたはコントロールを読み込んだ場合、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-061">MS09-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET 共通言語ランタイムの脆弱性により、リモートでコードが実行される (974378)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft .NET Framework および Microsoft Silverlight に存在する 3 件の脆弱性を解決します。 この脆弱性により、ユーザーが特別に細工された Web ページを XAML ブラウザー アプリケーション (XBAP) または Silverlight アプリケーションを実行可能な Web ブラウザーで閲覧した場合、または攻撃者がユーザーを誘導して特別に細工した Microsoft .NET アプリケーションを実行させた場合に、クライアント システム上で、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。 この脆弱性により、サーバーが ASP.NET ページの処理を許可し、攻撃者が特別に細工した ASP.NET ページをそのサーバーへのアップロードに成功して実行した場合に、IIS を実行しているサーバー システム上で、リモートでコードが実行される可能性があります (Web ホスティング シナリオの場合)。 この脆弱性のため、Microsoft .NET アプリケーション、Silverlight アプリケーション、XBAP および ASP.NET ページで悪意のないものは侵害される危険はありません。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-062">MS09-062</a></td>
<td style="border:1px solid black;"><strong>GDI+ の脆弱性により、リモートでコードが実行される (957488)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Windows GDI+ に存在する数件の脆弱性を解決します。これらの脆弱性は、ユーザーが影響を受けるソフトウェアを使用して特別に細工された画像ファイルを開いた場合、または特別に細工されたコンテンツが含まれる Web サイトを参照した場合、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer、<br />
Microsoft .NET Framework、<br />
Microsoft Office、<br />
Microsoft SQL Server、<br />
Microsoft 開発ツール、<br />
Microsoft Forefront</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-053">MS09-053</a></td>
<td style="border:1px solid black;"><strong>インターネット インフォメーション サービスの FTP サービスの脆弱性により、リモートでコードが実行される (975254)</strong><br />
<br />
このセキュリティ更新プログラムは、一般に公開された 2 件のマイクロソフト インターネット インフォメーション サービス (IIS) 5.0、マイクロソフト インターネット インフォメーション サービス (IIS) 5.1、マイクロソフト インターネット インフォメーション サービス (IIS) 6.0 およびマイクロソフト インターネット インフォメーション サービス (IIS) 7.0の FTP サービスの脆弱性を解決します。 IIS 7.0 では、FTP サービス 6.0 だけが影響を受けます。この脆弱性により、IIS 5.0 で FTP サービスを実行しているシステムで、リモートでコードが実行される (RCE)、または IIS 5.0、IIS 5.1、IIS 6.0 または IIS 7.0 で FTP サービスを実行しているシステムでサービス拒否が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-056">MS09-056</a></td>
<td style="border:1px solid black;"><strong>Windows CryptoAPI の脆弱性により、なりすましが行われる (974571)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 2 つの公開された脆弱性を解決します。この脆弱性により、攻撃者がエンド ユーザーが認証に使用した証明書のアクセス許可を取得する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
なりすまし</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-057">MS09-057</a></td>
<td style="border:1px solid black;"><strong>インデックス サービスの脆弱性により、リモートでコードが実行される (969059)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性で、攻撃者がその ActiveX コンポーネントへの呼び出しを介しインデックス サービスを呼び出す悪意のある Web ページをセット アップした場合、リモートでコードが実行される可能性があります。この呼び出しには悪意のある URL が含まれ、この脆弱性が悪用された場合、Web ページを閲覧しているユーザーの特権でクライアント コンピューターへのアクセスが攻撃者により取得される可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-058">MS09-058</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルの脆弱性により、特権が昇格される (971486)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された数件の Windows カーネルの脆弱性を解決します。最も深刻な脆弱性では、攻撃者がシステムにログオンし、特別に細工したアプリケーションを実行した場合、特権の昇格を起こす可能性があります。この脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-059">MS09-059</a></td>
<td style="border:1px solid black;"><strong>Local Security Authority Subsystem Service (LSASS) の脆弱性により、サービス拒否が起こる (975467)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が NTLM 認証のプロセス中に、不正に細工したパケットを送信した場合、サービス拒否が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  

次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号および CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**  
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID 番号                                            | セキュリティ情報タイトル                                                                                                                   | CVE ID                                                                           | Exploitability Index の評価                                                                         | 注意事項                                                                                                                                                                                                                                                                                                                                                                                         |  
|---------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-050](https://technet.microsoft.com/security/bulletin/ms09-050) | SMBv2 の脆弱性により、リモートでコードが実行される (975517)                                                                                | [CVE-2009-2526](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2526) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これは限定的なサービス拒否の脆弱性です。                                                                                                                                                                                                                                                                                                                                                         |  
| [MS09-050](https://technet.microsoft.com/security/bulletin/ms09-050) | SMBv2 の脆弱性により、リモートでコードが実行される (975517)                                                                                | [CVE-2009-2532](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2532) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-050](https://technet.microsoft.com/security/bulletin/ms09-050) | SMBv2 の脆弱性により、リモートでコードが実行される (975517)                                                                                | [CVE-2009-3103](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3103) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 悪用コードが一般に公開されています。                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-051](https://technet.microsoft.com/security/bulletin/ms09-051) | Windows Media Runtime の脆弱性により、リモートでコードが実行される (975682)                                                                | [CVE-2009-0555](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0555) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-051](https://technet.microsoft.com/security/bulletin/ms09-051) | Windows Media Runtime の脆弱性により、リモートでコードが実行される (975682)                                                                | [CVE-2009-2525](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2525) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-052](https://technet.microsoft.com/security/bulletin/ms09-052) | Windows Media Player の脆弱性により、リモートでコードが実行される (974112)                                                                 | [CVE-2009-2527](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2527) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-053](https://technet.microsoft.com/security/bulletin/ms09-053) | インターネット インフォメーション サービスの FTP サービスの脆弱性により、リモートでコードが実行される (975254)                             | [CVE-2009-2521](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2521) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これはサービス拒否の脆弱性です。悪用コードが一般に公開されています。                                                                                                                                                                                                                                                                                                                             |  
| [MS09-053](https://technet.microsoft.com/security/bulletin/ms09-053) | インターネット インフォメーション サービスの FTP サービスの脆弱性により、リモートでコードが実行される (975254)                             | [CVE-2009-3023](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3023) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 悪用コードが一般に公開されています。                                                                                                                                                                                                                                                                                                                                                             |  
| [MS09-054](https://technet.microsoft.com/security/bulletin/ms09-054) | Internet Explorer 用の累積的なセキュリティ更新プログラム (974455)                                                                          | [CVE-2009-1547](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1547) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-054](https://technet.microsoft.com/security/bulletin/ms09-054) | Internet Explorer 用の累積的なセキュリティ更新プログラム (974455)                                                                          | [CVE-2009-2529](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2529) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-054](https://technet.microsoft.com/security/bulletin/ms09-054) | Internet Explorer 用の累積的なセキュリティ更新プログラム (974455)                                                                          | [CVE-2009-2530](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2530) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | Microsoft Windows 2000 システムでは、ヒープの保護が無いため悪用可能指標の評価は [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) と高くなります。                                                                                                                                                                                                 |  
| [MS09-054](https://technet.microsoft.com/security/bulletin/ms09-054) | Internet Explorer 用の累積的なセキュリティ更新プログラム (974455)                                                                          | [CVE-2009-2531](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2531) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     |                                                                                                                                                                                                                                                                                                                                                                                                  |  
| [MS09-055](https://technet.microsoft.com/security/bulletin/ms09-055) | ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (973525)                                                                          | [CVE-2009-2493](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | なし                                                                                                | (この脆弱性は、[7 月のセキュリティ情報](https://technet.microsoft.com/security/bulletin/ms09-jul)の悪用可能性指標の評価でお知らせしているものです。この脆弱性は、セキュリティ情報 [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) で最初に対処されたためです。) [MS09-060](https://technet.microsoft.com/security/bulletin/ms09-060) の該当する CVE 番号も併せてご覧ください。 |  
| [MS09-056](https://technet.microsoft.com/security/bulletin/ms09-056) | Windows CryptoAPI の脆弱性により、なりすましが行われる (974571)                                                                            | [CVE-2009-2510](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2510) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これはなりすましの脆弱性です。                                                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-056](https://technet.microsoft.com/security/bulletin/ms09-056) | Windows CryptoAPI の脆弱性により、なりすましが行われる (974571)                                                                            | [CVE-2009-2511](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2511) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これはなりすましの脆弱性です。                                                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-057](https://technet.microsoft.com/security/bulletin/ms09-057) | インデックス サービスの脆弱性により、リモートでコードが実行される (969059)                                                                 | [CVE-2009-2507](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2507) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-058](https://technet.microsoft.com/security/bulletin/ms09-058) | Windows カーネルの脆弱性により、特権が昇格される (971486)                                                                                  | [CVE-2009-2515](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2515) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-058](https://technet.microsoft.com/security/bulletin/ms09-058) | Windows カーネルの脆弱性により、特権が昇格される (971486)                                                                                  | [CVE-2009-2516](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2516) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | この脆弱性は、ネットワーク共有が使用させれている環境ではサービス拒否が、ローカルで使用されていれば特権の昇格が起こります。                                                                                                                                                                                                                                                                       |  
| [MS09-058](https://technet.microsoft.com/security/bulletin/ms09-058) | Windows カーネルの脆弱性により、特権が昇格される (971486)                                                                                  | [CVE-2009-2517](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2517) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これはサービス拒否の脆弱性です。                                                                                                                                                                                                                                                                                                                                                                 |  
| [MS09-059](https://technet.microsoft.com/security/bulletin/ms09-059) | Local Security Authority Subsystem Service (LSASS) の脆弱性により、サービス拒否が起こる (975467)                                           | [CVE-2009-2524](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2524) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これは限定的なサービス拒否の脆弱性です。                                                                                                                                                                                                                                                                                                                                                         |  
| [MS09-060](https://technet.microsoft.com/security/bulletin/ms09-060) | Microsoft Office 用の Microsoft ATL (Active Template Library) の ActiveX コントロールの脆弱性により、リモートでコードが実行される (973965) | [CVE-2009-0901](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901) | なし                                                                                                | (この脆弱性は、[7 月のセキュリティ情報](https://technet.microsoft.com/security/bulletin/ms09-jul)の悪用可能性指標の評価でお知らせしているものです。この脆弱性は、セキュリティ情報 [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) で最初に対処されたためです。)                                                                                                               |  
| [MS09-060](https://technet.microsoft.com/security/bulletin/ms09-060) | Microsoft Office 用の Microsoft ATL (Active Template Library) の ActiveX コントロールの脆弱性により、リモートでコードが実行される (973965) | [CVE-2009-2493](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | なし                                                                                                | (この脆弱性は、[7 月のセキュリティ情報](https://technet.microsoft.com/security/bulletin/ms09-jul)の悪用可能性指標の評価でお知らせしているものです。この脆弱性は、セキュリティ情報 [MS09-035](https://technet.microsoft.com/security/bulletin/ms09-035) で最初に対処されたためです。) [MS09-055](https://technet.microsoft.com/security/bulletin/ms09-055) の該当する CVE 番号も併せてご覧ください。 |  
| [MS09-060](https://technet.microsoft.com/security/bulletin/ms09-060) | Microsoft Office 用の Microsoft ATL (Active Template Library) の ActiveX コントロールの脆弱性により、リモートでコードが実行される (973965) | [CVE-2009-2495](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これは情報漏えいの脆弱性です。                                                                                                                                                                                                                                                                                                                                                                   |  
| [MS09-061](https://technet.microsoft.com/security/bulletin/ms09-061) | Microsoft .NET 共通言語ランタイムの脆弱性により、リモートでコードが実行される (974378)                                                     | [CVE-2009-0090](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0090) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-061](https://technet.microsoft.com/security/bulletin/ms09-061) | Microsoft .NET 共通言語ランタイムの脆弱性により、リモートでコードが実行される (974378)                                                     | [CVE-2009-0091](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0091) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-061](https://technet.microsoft.com/security/bulletin/ms09-061) | Microsoft .NET 共通言語ランタイムの脆弱性により、リモートでコードが実行される (974378)                                                     | [CVE-2009-2497](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2497) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | インターネットに影響を与える攻撃となる見込み                                                                                                                                                                                                                                                                                                                                                     |  
| [MS09-062](https://technet.microsoft.com/security/bulletin/ms09-062) | GDI+ の脆弱性により、リモートでコードが実行される (957488)                                                                                 | [CVE-2009-2500](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2500) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-062](https://technet.microsoft.com/security/bulletin/ms09-062) | GDI+ の脆弱性により、リモートでコードが実行される (957488)                                                                                 | [CVE-2009-2501](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2501) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-062](https://technet.microsoft.com/security/bulletin/ms09-062) | GDI+ の脆弱性により、リモートでコードが実行される (957488)                                                                                 | [CVE-2009-2502](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2502) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-062](https://technet.microsoft.com/security/bulletin/ms09-062) | GDI+ の脆弱性により、リモートでコードが実行される (957488)                                                                                 | [CVE-2009-2503](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2503) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-062](https://technet.microsoft.com/security/bulletin/ms09-062) | GDI+ の脆弱性により、リモートでコードが実行される (957488)                                                                                 | [CVE-2009-2504](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2504) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-062](https://technet.microsoft.com/security/bulletin/ms09-062) | GDI+ の脆弱性により、リモートでコードが実行される (957488)                                                                                 | [CVE-2009-2518](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2518) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-062](https://technet.microsoft.com/security/bulletin/ms09-062) | GDI+ の脆弱性により、リモートでコードが実行される (957488)                                                                                 | [CVE-2009-2528](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2528) | [**1** - 安定した悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |  
| [MS09-062](https://technet.microsoft.com/security/bulletin/ms09-062) | GDI+ の脆弱性により、リモートでコードが実行される (957488)                                                                                 | [CVE-2009-3126](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3126) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                                                                                                           |
  
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
<th colspan="13">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://technet.microsoft.com/security/bulletin/ms09-059)
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
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**なし**](https://technet.microsoft.com/security/bulletin/rating)
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
[DirectShow WMA 音声コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(緊急)  
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8f850a82-61f9-447b-a0aa-a2c192cc5d2e)  
(KB954155)  
(緊急)  
[オーディオ圧縮マネージャー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6dfd5405-cabe-4bd7-9330-b6bde1d99194)  
(KB975025)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=13035ef7-7e47-487c-8b7c-7795d33ce7de)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=26515c7b-d7a6-4405-96b5-a518dcb39d38)  
(緊急)  
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8154ba37-0fbc-4d31-9d6e-0b21586ad65a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=edfea805-9544-4dc0-a52c-d7594205657b)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f3fef608-dafb-4b37-a65a-9cc4ae8e2c4c)  
(KB958869)  
(緊急)  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ecf78619-80fa-417d-852b-1b5b2cf574e2)  
(KB971108)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3e534aa8-29c2-4379-9f57-931a6ff47418)  
(KB971110)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e6f5e730-85cc-4c08-a50d-c456b1e9f5bc)  
(KB971111)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7fecd367-aaff-458b-91bc-8925c8e57528)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=52b9198d-b65f-467a-a5ab-141e23d64a86)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b34d94b5-b828-4e16-a636-04344c60d945)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bdfa6583-28a2-4d6b-91d2-157a8518b664)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="13">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr>
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
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
[DirectShow WMA 音声コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(緊急)  
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4516c219-e357-485e-a52b-23dcb8ee49d8)  
(KB954155)  
(緊急)  
(Windows XP Service Pack 2 のみ)  
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=746d3440-5a6a-421e-9286-7b534a1dfe54)  
(KB954155)  
(緊急)  
(Windows XP Service Pack 3 のみ)  
[オーディオ圧縮マネージャー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6ecc7129-8caa-4daf-a8e2-8f3536225fb3)  
(KB975025)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b2efe1ac-d8d7-41bb-b87d-fc5e22afef0f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9aacf890-afb4-46a7-a13f-dd9fe3c0ca4a)  
(緊急)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=dc166dc6-577f-4d8d-94df-dd963233dd85)  
(緊急)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8799159d-df69-49f6-9db5-49147690ce0c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=171d43d3-669c-4923-b266-e47591833c05)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1bc56c26-1c7c-47e3-94f4-37af7e00392c)  
(KB953295)  
(緊急)  
(Tablet PC Edition 2005 および Media Center Edition 2005 のみ)  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e2acde20-a6d3-4135-b6eb-1214f743d474)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2ae0bdd4-f8b2-420a-b1ac-d2cdaa87c828)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9c5ab624-e37b-418a-a919-d8f652b15679)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=768fd74e-0a2f-4353-ac22-65d0d6321739)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=cece4c55-0756-4357-9d2d-6709e8426068)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e997ea40-668e-40df-bd50-0ca53437b375) <sup>[1]</sup>
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[DirectShow WMA 音声コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a)  
(KB969878)  
(緊急)  
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4729de51-8fd8-46c6-b4ad-9c9f25202684)  
(KB954155)  
(緊急)  
Windows Media Format SDK 9.5 x64 Edition の [Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2)  
(KB954155)  
(緊急)  
Windows Media Format SDK 11 の [Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a866a490-6d3a-4ecd-acf4-770312ba2fd6)  
(KB954155)  
(緊急)  
[オーディオ圧縮マネージャー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b)  
(KB975025)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a9e7dfd8-7ba1-4f14-8e60-92ef00d91467)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=89a2cf2a-a7a2-4d4b-aa6f-24dde288d500)  
(緊急)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bd54e595-25f2-4839-a838-2a0f809bde2b)  
(緊急)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=77b18fc2-e769-47c6-8e72-916716a49e58)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=171d43d3-669c-4923-b266-e47591833c05)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ad92503a-8c91-4d73-98b0-942d7961637d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=819dd2d1-cad5-4784-9baf-185d8a76df5d)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ad29696d-4611-4a12-9dfa-74fa6866b759)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=270ec100-5ba1-4f8c-aa36-105d30ad57bf)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5459b7d4-1fab-4a04-ab9d-b8323505c1e2)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=17008892-7950-44c4-850d-002c8d73495f) <sup>[1]</sup>
(重要)
</td>
</tr>
<tr>
<th colspan="13">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://technet.microsoft.com/security/bulletin/ms09-059)
</td>
</tr>
<tr>
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
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[DirectShow WMA 音声コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4fe0dff5-04d9-4409-8d1d-52419537126b)  
(KB969878)  
(緊急)  
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=00b3cb86-c9eb-4fbe-987e-2b0d94271d87)  
(KB954155)  
(緊急)  
[オーディオ圧縮マネージャー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ab1803ff-2371-487f-a7b6-95747c46ba4e)  
(KB975025)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5f82d01c-573e-425e-b9f2-86a54f377b19)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8101625d-ee93-46e5-aec2-3bdbf2d86472)  
(緊急)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4647bcf1-69fb-4ad6-9e03-7bc22d8a914b)  
(緊急)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9eae7eca-1a6f-4397-a6e2-7dda6b9d5276)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f3249c99-82e4-45dc-a254-28e647e822c8)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d1b4a58b-f0b1-4400-a6e6-0255b0513bd1) (KB953298)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=414466a4-39a0-476d-9a43-ae7674cbd6a0)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=48256ea3-b433-4e84-9019-22300069cfc1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78072164-84d1-44da-8ede-2a9d212d47a9)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1e3f3842-f8fd-4969-a2cf-706db38d7580)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9dff4662-7771-4bdc-87ec-7899d79b3a55) <sup>[1]</sup>
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[DirectShow WMA 音声コーデック](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c116ae9d-e416-4b7d-be75-4b4b2ebcc33a)  
(KB969878)  
(緊急)  
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=13ba4839-7fa9-4bbb-95f6-3fafb6c49f20)  
(KB954155)  
(緊急)  
Windows Media Format SDK 9.5 x64 Edition の [Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=fe0d51b2-345e-4eb7-a036-d8c3f6a683d2)  
(KB954155)  
(緊急)  
[オーディオ圧縮マネージャー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=46daf7c7-1cd3-4f47-9c7a-d5eb6ea7327b)  
(KB975025)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows Media Player 6.4](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=65e9036e-2e1b-40ff-a84b-c507107bcce8)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2f966053-01eb-4a23-a9d5-71deac2498ea)  
(緊急)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e7d77bd9-8317-42f3-9ad1-a0b8bfa65b53)  
(緊急)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=708a549d-11fd-43bf-a6e1-309e3205d59d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1ad3f7b3-58d5-4507-ae20-a265e47cee9c)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=eb95e8d9-6ef5-4526-99d2-507e50de049b)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=61bded07-201e-4815-ac1e-468bf907e063)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d170cef9-f5d2-4fcd-997b-e778ad5a6797)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8aa1f97d-ad53-4450-bb93-4a147dd10a87)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=95286b8d-4b53-4e6c-af59-e9e18fad3559)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8df7a2d9-2f97-4f18-84e8-415a1632cf09) <sup>[1]</sup>
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
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
[Microsoft Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=79a1a94d-3b47-47e9-9476-2f591c3f6a59)  
(緊急)  
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=07e66c09-2cd7-47ba-bf87-d3da602184b4)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=575e75d9-e348-4fbb-9eaa-43240e4d715e)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d4a328b5-5470-46b0-86c7-cfe0e6a3ea01) (KB953300)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=491874d4-5eea-4545-9b7d-3861857c862e) (KB974417)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a678ceb9-a37a-4c29-8bd1-f209922990e5)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b99d4d9b-e0cc-4a8c-ad99-6a53958b37c8)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2ede1eb9-7f5f-411d-bbc3-5db46d80e0bb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=fb5678b9-5ef1-42db-902e-c9ea02880e0a)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=faef714b-5f46-47f2-bea7-881df05a1bc0)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=83c77015-7f96-4c0d-bd56-60aef90ea2f8) <sup>[1]</sup>
(重要)
</td>
</tr>
<tr>
<th colspan="13">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://technet.microsoft.com/security/bulletin/ms09-059)
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
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=29842c0c-8930-4b5f-83c6-1a718974b63f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f17ee0ea-f1e2-49f4-9f90-60296246ddfe)  
(KB954155)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f6995616-2a84-4c26-9599-26f1314873ed)  
(緊急)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e8f6014f-950b-4e11-a105-51d298069f1a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7313c03b-8844-4086-a0cc-43dfdb3ca48c)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6f99521e-86b3-4083-9132-e5ac06d40b63) (KB974468)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882) (KB974292)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233) (KB974467)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=19aa01f3-026d-4264-85f8-216d0597969b)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bb96eb1c-66a2-4276-9773-eea22179bcd4)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8b5a9a95-9439-40c8-acef-000b919daa04)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista、Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=04ae306b-0d0d-4767-ab54-cc11aec477ed)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=30e5410d-0942-4964-9037-52330488efda) (KB974291)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8) (KB974469)  
(緊急)
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4) (KB974470)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=acf6f3e6-282e-4f05-9060-8d0ebb874b97)  
(警告)
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=62ed5d0a-5ca6-4942-80c9-7808b14cb6b5)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=26905f12-92c7-4d45-99e7-227f03d2cb82)  
(KB954155)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b3de5236-afdd-436e-8648-5382d564cc99)  
(緊急)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=85978f28-5fc0-481b-9b03-2021c785889b)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7216bcb1-ff16-402b-ad1b-1500d46d0157)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6f99521e-86b3-4083-9132-e5ac06d40b63) (KB974468)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3cf329c6-6d3d-41eb-bb72-8ba241df0882) (KB974292)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7438eb1e-6e86-4aa1-b1f4-f71a7699d233) (KB974467)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8f5f0c1d-1dd6-47fa-aef2-d3c96c8fc06e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bce096c8-833b-45c8-99cd-1280f0744f2f)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4a60f789-1a4a-49a8-8d13-fda989ed40be)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition、Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=58c995ca-f308-4e07-8e60-2e542384d95d)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=30e5410d-0942-4964-9037-52330488efda) (KB974291)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8) (KB974469)  
(緊急)
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f) (KB953297)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4) (KB974470)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=13a3fe0b-e300-4568-aa08-d586ab8d5434)  
(警告)
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<th colspan="13">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://technet.microsoft.com/security/bulletin/ms09-059)
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
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**注意**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ff6bfcf3-76c9-4c45-b57d-22f94458dd6e)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2eaa9857-a147-4f31-9bf4-b9e2cf4c15c3)\*\*  
(KB954155)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72dd580e-eb53-41da-a5c0-a392ad388bfc)\*\*  
(緊急)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1baf7e96-ba3e-47e7-8ea3-eb092e653a39)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=51eb56fa-8204-45f3-86d7-6d03a2c8d78d)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=30e5410d-0942-4964-9037-52330488efda)\*\*  
(KB974291)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974469)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=fd1694af-8873-43aa-9243-91f7cde452b7)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d9c5039f-d0cf-4d84-850f-f2f7701dcb79)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f9b487af-fe73-42a8-b240-d59c4321f95b)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=71aec6f6-a36b-465e-8885-b094dfd30423)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f2f617c2-f149-4e9b-bfdd-08ed0f3f99db)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974470)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=71aec6f6-a36b-465e-8885-b094dfd30423)\*  
(警告)
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=aff6f9c7-4a72-48f2-b750-204d796c7daa)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media オーディオ音声デコーダー](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=70aabba3-53d6-4b52-be83-6d3f3869ecbd)\*\*  
(KB954155)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0111d741-bda4-4a50-a12b-d3337ff4441d)\*\*  
(緊急)  
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7a4b755b-7fa0-43aa-8862-c1d0c7d94c2c)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=131b047a-ae93-4a99-83e5-71d5a79e96ea)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=30e5410d-0942-4964-9037-52330488efda)\*\*  
(KB974291)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)\*\*  
(KB974469)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=41bc4cdb-273a-4a6e-80d9-c8ce20e32da9)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=db969ddc-708e-42b7-9956-6c27bf346bbb)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0d8a2a3e-d7d4-47fb-8364-16fce28e4d38)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=88f4189f-71fe-404a-869e-3f76692acf94)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=deb84cb8-2ba3-47e3-9185-2bbc5b0a7e18)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)\*\*  
(KB953297)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)\*\*  
(KB974470)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=88f4189f-71fe-404a-869e-3f76692acf94)\*  
(警告)
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7b70108b-7f59-4898-ab4e-76be990de878)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e81f30b7-ef05-4488-b62a-d330e17129cf)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3d16c5bf-ee5c-4220-9755-5cb92eac2aae)  
(注意)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)  
(KB953297)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=30e5410d-0942-4964-9037-52330488efda)  
(KB974291)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=72fe9066-2397-439d-82fb-2b7f9d2bcce8)  
(KB974469)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a4f42085-1cb9-4b8d-a931-85be71fdf06d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a221451a-cb4e-4a43-a225-4b1e86e87525)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8962f0b6-f346-4e88-9d83-4d15b699dd9d)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=abc94857-37d8-4bb8-ad9e-46e687fca40e)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=78ac8b97-8327-4ae1-8bb0-6cf227f3968f)  
(KB953297)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=614a92ee-0512-4ccc-b6b8-32ebcec8e6a4)  
(KB974470)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
同上
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3e0f0b1c-ca5d-43fc-9770-73396a5f191c)  
(警告)
</td>
<td style="border:1px solid black;">
同上
</td>
</tr>
<tr>
<th colspan="13">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://technet.microsoft.com/security/bulletin/ms09-059)
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
なし
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
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
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
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=89d1fb78-68cd-48dd-afc2-15a79ebe9fde)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b64bcc14-38a7-45b9-8f85-acc573777506)  
(重要)
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
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ad6f06d5-27db-445d-a8b2-c42adc90afc0)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=35b85783-90df-4f67-a3cb-02351432133e)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
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
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=10d9f7ac-65f4-437c-91cc-171632c69b0e)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=809e29f3-ec68-4a2b-b04e-11759dd16001)  
(重要)
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
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=70cd0270-77e9-492a-82d9-798364640c10)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=97010f2c-6c10-4fda-84fd-6c8749968db5)  
(重要)
</td>
</tr>
<tr>
<th colspan="13">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-050**](https://technet.microsoft.com/security/bulletin/ms09-050)
</td>
<td style="border:1px solid black;">
[**MS09-051**](https://technet.microsoft.com/security/bulletin/ms09-051)
</td>
<td style="border:1px solid black;">
[**MS09-052**](https://technet.microsoft.com/security/bulletin/ms09-052)
</td>
<td style="border:1px solid black;">
[**MS09-054**](https://technet.microsoft.com/security/bulletin/ms09-054)
</td>
<td style="border:1px solid black;">
[**MS09-055**](https://technet.microsoft.com/security/bulletin/ms09-055)
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
<td style="border:1px solid black;">
[**MS09-053**](https://technet.microsoft.com/security/bulletin/ms09-053)
</td>
<td style="border:1px solid black;">
[**MS09-056**](https://technet.microsoft.com/security/bulletin/ms09-056)
</td>
<td style="border:1px solid black;">
[**MS09-057**](https://technet.microsoft.com/security/bulletin/ms09-057)
</td>
<td style="border:1px solid black;">
[**MS09-058**](https://technet.microsoft.com/security/bulletin/ms09-058)
</td>
<td style="border:1px solid black;">
[**MS09-059**](https://technet.microsoft.com/security/bulletin/ms09-059)
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
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**注意**](https://technet.microsoft.com/security/bulletin/rating)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
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
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f50307d6-7869-4996-9ff7-23f87d08994b)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bcd2b944-6852-48f2-820b-cce7d195e391)\*\*  
(注意)
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
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ce78c019-ec08-4ec6-abec-334f5ec5cb76)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=597ac3a7-e02d-49a5-9b8e-d097e867acea)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
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
[Windows Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9b6a28ae-b3f2-42b0-8209-e3950ec37abb)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=85e76e55-3766-4ffe-9a18-8655de935b7c)  
(注意)
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
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6442a77a-3c0d-4beb-b2d2-2885376c2135)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4aac0e3e-9b49-4a4a-ab17-707ff03b4d9b)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

**\*\*Server Core インストールは影響を受けません。**この更新プログラムで解決されている脆弱性は、Server Core インストールオプションを使用してインストールされたサポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 は、影響を受けません。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

**セキュリティ情報 MS09-061 に関する注意**

「影響を受けるソフトウェアおよびダウンロード先」セクション内の他のソフトウェアのセクションも併せてご覧ください。同じセキュリティ情報 ID 番号に関する情報を記載しています。このセキュリティ情報は複数のソフトウェアを対象にしています。

**セキュリティ情報 MS09-062 に関する注意**

「影響を受けるソフトウェアおよびダウンロード先」セクション内の他のソフトウェアのセクションも併せてご覧ください。同じセキュリティ情報 ID 番号に関する情報を記載しています。このセキュリティ情報は複数のソフトウェアを対象にしています。

**セキュリティ情報 MS09-059 に関する注意**

<sup>[1]</sup> このオペレーティング システムが影響を受けるのは、KB968389 「認証に対する保護の強化」の更新プログラム ([セキュリティ アドバイザリ 973811](https://technet.microsoft.com/security/advisory/973811) をご覧ください) がインストールされている場合だけです。詳細情報は、[MS09-059](https://technet.microsoft.com/security/bulletin/ms09-059) の「このセキュリティ更新プログラムに関するよく寄せられる質問 (FAQ)」のセクションをご覧ください。

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
</tr>
<tr>
<th colspan="3">
Microsoft Office スイートおよびソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-060**](https://technet.microsoft.com/security/bulletin/ms09-060)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Outlook 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=04878c2c-eb97-426f-be08-89036a6799db)  
(KB973702)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d) <sup>[2]</sup>
(KB974811)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=79e2b2e8-d5e8-4014-b489-720af2b5083d)  
(KB973705)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=48752ab4-5928-476d-a8bc-e998d188b1f7) <sup>[3]</sup>
(KB972580)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Outlook 2007 Service Pack 1 および Microsoft Office Outlook 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d39234a3-c62c-44ba-a626-3179a183ca09)  
(KB972363)  
(緊急)
</td>
<td style="border:1px solid black;">
[2007 Microsoft Office System Service Pack 1 および 2007 Microsoft Office System Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec) \[4\]  
(KB972581)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-060**](https://technet.microsoft.com/security/bulletin/ms09-060)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
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
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2002 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=920ee70b-c5c1-47b5-8f33-938ffe14eea4)  
(KB975365)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio Viewer
</td>
<td style="border:1px solid black;">
Microsoft Visio 2002 Viewer <sup>[1]</sup>
(緊急)  
Microsoft Office Visio 2003 Viewer <sup>[1]</sup>
(緊急)  
[Microsoft Office Visio Viewer 2007 Service Pack 1 および Microsoft Office Visio Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d20004c5-dd01-459e-8120-5f127e20c085)  
(KB973709)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio Viewer 2007 Service Pack 1 および Microsoft Office Visio Viewer 2007 Service Pack 2](https://www.microsoft.com/https://www.microsoft.com/download/details.aspx?familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec&displaylang=ja) \[4\]  
(KB972581)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Project
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2002 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b4ac7fbe-dd19-4940-a576-89a6b7ed602d) <sup>[2]</sup>
(KB974811)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer、Microsoft Office Excel Viewer および Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer 2003 Service Pack 3 および Microsoft Office Excel Viewer 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=48752ab4-5928-476d-a8bc-e998d188b1f7) <sup>[3]</sup>
(KB972580)  
(重要)  
[Microsoft Office Excel Viewer、PowerPoint Viewer 2007、PowerPoint Viewer 2007 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec) \[4\]  
(KB972581)  
(重要)  
[PowerPoint Viewer 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec) \[4\]  
(KB972581)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=98d7c4ab-f8ca-4806-a609-453fb29b02ec) \[4\]  
(KB972581)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6f96de9a-62d8-428f-9567-51d55c129be6)  
(KB973636)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**セキュリティ情報 MS09-060 に関する注意**

<sup>[1]</sup> マイクロソフトは、Microsoft Visio Viewer 2002 および Microsoft Visio Viewer 2003 をご使用のすべてのお客様に、この脆弱性を解決するために最新バージョンの Microsoft Visio Viewer 2007 にアップグレードすることを推奨します。

**セキュリティ情報 MS09-062 に関する注意**

<sup>[2]</sup> これらの更新プログラムは同一のものです。

<sup>[3]</sup> これらの更新プログラムは同一のものです。

\[4\] これらの更新プログラムは同一のものです。

「影響を受けるソフトウェアおよびダウンロード先」セクション内の他のソフトウェアのセクションも併せてご覧ください。同じセキュリティ情報 ID 番号に関する情報を記載しています。このセキュリティ情報は複数のソフトウェアを対象にしています。

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
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
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
SQL Server 2000 Reporting Services Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新プログラム:  
対象外  
QFE 更新プログラム:  
[SQL Server 2000 Reporting Services Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=33554f96-5af7-4683-a537-9db293b67b8d)  
(KB970899)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新プログラム:  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23) <sup>[1]</sup>
(KB970895)  
(緊急)  
QFE 更新プログラム:  
[SQL Server 2005 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235) <sup>[1]</sup>
(KB970896)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23) <sup>[1]</sup>
(KB970895)  
(緊急)  
QFE 更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235) <sup>[1]</sup>
(KB970896)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d971a262-1dfb-498c-a4f3-59fdc1b85d23) <sup>[1]</sup>
(KB970895)  
(緊急)  
QFE 更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=76d3d653-e9a0-48bc-afae-d3553f7b9235) <sup>[1]</sup>
(KB970896)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 更新プログラム:  
[SQL Server 2005 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0d878f4b-71e8-4170-9a14-1bce684811ce) <sup>[2]</sup>
(KB970892)  
(緊急)  
QFE 更新プログラム:  
[SQL Server 2005 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f) <sup>[2]</sup>
(KB970894)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0d878f4b-71e8-4170-9a14-1bce684811ce) <sup>[2]</sup>
(KB970892)  
(緊急)  
QFE 更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f) <sup>[2]</sup>
(KB970894)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 for Itanium-based Systems Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0d878f4b-71e8-4170-9a14-1bce684811ce) <sup>[2]</sup>
(KB970892)  
(緊急)  
QFE 更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e6f307c1-8b21-406e-9c6f-b1a3a1e9a98f) <sup>[2]</sup>
(KB970894)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
**セキュリティ情報 MS09-062 に関する注意**

<sup>[1]</sup> SQL Server 2005 Service Pack 2 をご使用のお客様で、Reporting Services SharePoint の依存性がある場合、マイクロソフト ダウンロード センターから [Microsoft SharePoint テクノロジ用 Microsoft SQL Server 2005 Reporting Services アドイン](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f4d4d0ae-e5d4-4ed1-8d78-7137578161ce)もインストールする必要があります。

<sup>[2]</sup> SQL Server 2005 Service Pack 3 をご使用のお客様で、Reporting Services SharePoint の依存性がある場合、マイクロソフト ダウンロード センターから [Microsoft SharePoint テクノロジ用 Microsoft SQL Server 2005 Reporting Services アドイン](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=648766ac-2a35-4238-a3f4-c26d7077f2a9)もインストールする必要があります。

「影響を受けるソフトウェアおよびダウンロード先」セクション内の他のソフトウェアのセクションも併せてご覧ください。同じセキュリティ情報 ID 番号に関する情報を記載しています。このセキュリティ情報は複数のソフトウェアを対象にしています。

#### Microsoft 開発ツールおよびソフトウェア

 
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
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
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
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
Mac にインストールされた [Microsoft Silverlight 2](https://www.microsoft.com/japan/silverlight/download.aspx) <sup>[1]</sup>
(KB970363)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
すべてのリリースされた Microsoft Windows クライアントにインストールされた [Microsoft Silverlight 2](https://www.microsoft.com/japan/silverlight/download.aspx) <sup>[1]</sup>
(KB970363)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight
</td>
<td style="border:1px solid black;">
すべてのリリースされた Microsoft Windows サーバー \*\* にインストールされた [Microsoft Silverlight 2](https://www.microsoft.com/japan/silverlight/download.aspx) <sup>[1]</sup>
(KB970363)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
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
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9e3b52d3-b211-4d62-891c-ae8f2e4ffc6c)  
(KB971022)  
(深刻度の評価なし <sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e186aeed-e9d7-4a02-84b3-bbed116ca060)  
(KB971023)  
(深刻度の評価なし <sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2008
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4fa10c93-ce20-43df-a725-ef4c77353747)  
(KB972221)  
(深刻度の評価なし <sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b904dee8-8a26-43f8-8ca9-86ad12cfdb52)  
(KB972222)  
(深刻度の評価なし <sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた Microsoft Visual FoxPro 8.0 Service Pack 1  
(KB971104)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた  
[Microsoft Visual FoxPro 8.0 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=e5d0d515-4b36-4025-bc6f-1c5cdf09e1af)  
(KB971104)  
(深刻度の評価なし <sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた Microsoft Visual FoxPro 9.0 Service Pack 2  
(KB971105)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた  
[Microsoft Visual FoxPro 9.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2a930f56-59ac-49a6-830f-bfae7c540ec7)  
(KB971105)  
(深刻度の評価なし <sup>[2]</sup>)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Report Viewer
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-061**](https://technet.microsoft.com/security/bulletin/ms09-061)
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2005 Service Pack 1 再頒布可能パッケージ
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2005 Service Pack 1 再頒布可能パッケージ](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0dfaf300-2b53-4678-a779-0d805ddfe538)  
(KB971117)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 再頒布可能パッケージ
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 再頒布可能パッケージ](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=42ed040f-cf94-4754-b0b3-c8016fbcbe22)  
(KB971118)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Report Viewer 2008 再頒布可能パッケージ Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Report Viewer 2008 再頒布可能パッケージ Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6aaa74bd-a46e-4478-b4e1-2063d18d2d42)  
(KB971119)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Platform SDK Redistributable: GDI+
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Platform SDK Redistributable: GDI+](https://www.microsoft.com/download/details.aspx?familyid=6a63ab9c-df12-4d41-933c-be590feaa05a)  
(KB975337)  
(深刻度の評価なし <sup>[2]</sup>)
</td>
</tr>
</table>

<p></p>

 
**セキュリティ情報 MS09-061 に関する注意**

<sup>[1]</sup> このダウンロードは、Microsoft Silverlight 2 から脆弱性を解決する Microsoft Silverlight 3 にアップグレードします。

**\*\*Server Core インストールは影響を受けません。**この更新プログラムで解決されている脆弱性は、Server Core インストールオプションを使用してインストールされたサポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 は、影響を受けません。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

「影響を受けるソフトウェアおよびダウンロード先」セクション内の他のソフトウェアのセクションも併せてご覧ください。同じセキュリティ情報 ID 番号に関する情報を記載しています。このセキュリティ情報は複数のソフトウェアを対象にしています。

**セキュリティ情報 MS09-062 に関する注意**

<sup>[2]</sup> これらのソフトウェアについて、マイクロソフトはこのセキュリティ情報で説明している脆弱性に関連する攻撃の方法を確認していないため、この更新プログラムには該当する深刻度がありません。しかし、このセキュリティ更新プログラムは、アプリケーションの更新バージョンを公開できるよう、このソフトウェアを使用している開発者に提供されます。

「影響を受けるソフトウェアおよびダウンロード先」セクション内の他のソフトウェアのセクションも併せてご覧ください。同じセキュリティ情報 ID 番号に関する情報を記載しています。このセキュリティ情報は複数のソフトウェアを対象にしています。

#### Microsoft セキュリティ ソフトウェア

 
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
Microsoft Forefront Security
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-062**](https://technet.microsoft.com/security/bulletin/ms09-062)
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
Microsoft Forefront Client Security 1.0
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 にインストールされた  
[Microsoft Forefront Client Security 1.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c0ce624c-8df3-4223-8a7a-5cba4ac334a8)  
(KB975962)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**セキュリティ情報 MS09-062 に関する注意**

「影響を受けるソフトウェアおよびダウンロード先」セクション内の他のソフトウェアのセクションも併せてご覧ください。同じセキュリティ情報 ID 番号に関する情報を記載しています。このセキュリティ情報は複数のソフトウェアを対象にしています。

検出および展開ツールとガイダンス
--------------------------------


**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](https://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](https://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](https://update.microsoft.com/microsoftupdate/)、[Windows Update](https://windowsupdate.microsoft.com/) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](https://support.microsoft.com/kb/323166) をご覧ください。

**注:** 2009 年 8 月 1 日より、マイクロソフトは Office Update および Office Update Inventory Tool のサポートを終了します。Microsoft Office 製品用の最新の更新プログラムを引き続き入手するためには、[Microsoft Update](https://update.microsoft.com/microsoftupdate/) をご利用ください。詳細情報は、[About Microsoft Office Update: Frequently Asked Questions](https://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英語情報) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトはセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [961747](https://support.microsoft.com/kb/961747) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](https://support.microsoft.com/kb/894199/en-us) (英語情報): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2009 年). すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](https://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](https://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](https://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](https://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](https://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](https://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS09-050 で説明している問題について報告してくださった [Netherlands Forensics Institute](https://www.nederlandsforensischinstituut.nl/) の [Matthieu Suiche 氏](https://www.msuiche.net/)
-   MS09-051 で説明している問題について報告してくださった [Zero Day Initiative](https://www.zerodayinitiative.com/) の Ivan Fratric 氏および [McAfee Avert Labs](https://www.avertlabs.com/) の Jun Xie 氏
-   MS09-051 で説明している問題について報告してくださった [Adobe Systems, Inc.](https://www.adobe.com/) の Vinay Anantharaman 氏
-   MS09-052 で説明している問題について報告してくださった [Palo Alto Networks](https://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS09-054 で説明している問題について報告してくださった [Google Inc.](https://www.google.com/) の SkyLined 氏
-   MS09-054 で説明している問題について報告してくださった [IBM ISS X-Force](https://www.iss.net/) の Mark Dowd 氏
-   MS09-054 で説明している問題について報告してくださった [TippingPoint](https://www.tippingpoint.com/) および [the Zero Day Initiative](https://www.zerodayinitiative.com/)
-   MS09-054 で説明している問題について報告してくださった [TippingPoint](https://www.tippingpoint.com/) および [the Zero Day Initiative](https://www.zerodayinitiative.com/) に協力している eshu.co.uk の Sam Thomas 氏
-   MS09-056 で説明している問題についてマイクロソフトに協力いただいた [Citrix](https://www.citrix.com/) の Ian Wright 氏および Jean-Luc Giraud 氏
-   MS09-056 で説明している問題について報告してくださった [IOActive](https://www.ioactive.com/) の Dan Kaminsky 氏
-   MS09-057 で説明している問題について報告してくださった [Palo Alto Networks](https://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS09-058 で説明している 2 件の問題について報告してくださった [Google Inc.](https://www.google.com/) の Tavis Ormandy 氏および Neel Mehta 氏
-   MS09-058 で説明している問題について報告してくださった [NSFocus Security Team](https://www.nsfocus.com/)
-   MS09-060 で説明している問題について報告してくださった [IBM ISS X-Force](https://www.iss.net/) の David Dewey 氏
-   MS09-058 で説明している 2 件の問題について報告してくださった [VeriSign iDefense Labs](https://labs.idefense.com/) の Ryan Smith 氏
-   MS09-061 で説明している問題について報告してくださった [Pavel Minaev 氏](https://int19h.org/)
-   MS09-061 で説明している問題について報告してくださった [Sumatra](https://www.sumatra.nl/) の Jeroen Frijters 氏
-   MS09-062 で説明している問題について報告してくださった [Palo Alto Networks](https://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS09-062 で説明している問題について報告してくださった [SkyRecon](https://www.skyrecon.com/) の Thomas Garnier 氏
-   MS09-062 で説明している問題について報告してくださった [VeriSign iDefense Labs](https://labs.idefense.com/) Wushi 氏
-   MS09-062 で説明している問題について報告してくださった [Zero Day Initiative](https://www.zerodayinitiative.com/) の Ivan Fratric 氏
-   MS09-062 で説明している 2 件の問題について報告してくださった [Google Inc.](https://www.google.com/) の Tavis Ormandy 氏
-   MS09-062 で説明している問題について報告してくださった Carlo Di Dato (aka shinnai) 氏
-   MS09-062 で説明している問題について報告してくださった [VeriSign iDefense Labs](https://labs.idefense.com/) の Marsu Pilami 氏
-   MS09-062 で説明している問題について報告してくださった [Secunia](https://secunia.com/) の Carsten H. Eiram 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/10/14: このセキュリティ情報ページを公開しました。
-   2009/10/19: このセキュリティ情報ページを更新し、MS09-054 の Firefox ユーザー向け情報を提供しました。
-   2009/10/29: このセキュリティ情報ページを更新し、Microsoft Office Visio Viewer 2007 Service Pack 1 および Microsoft Office Visio Viewer 2007 Service Pack 2 を MS09-062 の影響を受けるソフトウェアに追加し、また、セキュリティ情報 MS09-062 に関する注意を追加し、SQL Server 2005 をご使用のお客様で、Reporting Services SharePoint の依存性がある場合についての注釈を追加しました。
-   2009/11/03: このセキュリティ情報ページを更新し、アプリケーションの互換性問題を解決する MS09-054 向け修正プログラムを公開したことをお知らせしました。この更新プログラムを既に適用しているお客様は、マイクロソフト サポート技術情報 976749 で提供している修正プログラムをインストールすることができます。
-   2009/11/05: このセキュリティ情報ページを更新し、セキュリティ情報 MS09-060 および MS09-062 の影響を受けるソフトウェアから Microsoft Office Visio Viewer 2007 のオリジナル バージョンを削除しました。
-   2009/11/11: このセキュリティ情報ページを更新し、セキュリティ情報 MS09-051 の検出の問題を解決する Microsoft Windows 2000 Service Pack 4 上のオーディオ圧縮マネージャー用の更新プログラムの再リリースをお知らせしました。これは検出の変更のみで、バイナリへの変更はありません。更新プログラムがシステムに正しくインストールされたお客様は、この更新プログラムを再インストールする必要はありません。
-   2010/01/13: Microsoft Expression Web、Microsoft Expression Web 2、Microsoft Office Groove 2007、および Microsoft Office Groove 2007 Service Pack 1を MS09-062 の「影響を受けるソフトウェア」の表から削除しました。
-   2010/06/23: MS09-061 の影響を受けるソフトウェアから Windows 7 および Windows Server 2008 R2 上の .NET Framework 1.1 Service Pack 1 を削除しました。

*Built at 2014-04-18T01:50:00Z-07:00*
