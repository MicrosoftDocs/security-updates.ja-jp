---
TOCTitle: 'MS11-APR'
Title: 2011 年 4 月のセキュリティ情報
ms:assetid: 'ms11-apr'
ms:contentKeyID: 61229682
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-apr(v=Security.10)'
--- Summary

2011 年 4 月のセキュリティ情報
==============================

公開日: 2011年4月13日 | 最終更新日: 2011年10月31日

**バージョン:** 6.1

[![](../../images/Dn627261.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627261.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2011 年 4 月公開のセキュリティ情報の一覧です。

2011 年 4 月のセキュリティ情報の公開により、2011 年 4 月 7 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 4 月 13 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2011 年 4 月 13 日午前 11：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[4 月の セキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032455069&eventcategory=4) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語情報) を参照してください。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2497640) <br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する非公開で報告された 4 件の脆弱性と、一般に公開された 1 件の脆弱性を解決します。このセキュリティ更新プログラムは、Windows クライアント上の Internet Explorer 6、Internet Explorer 7 および Internet Explorer 8 について深刻度を「緊急」と評価し、Windows サーバー上の Internet Explorer 6、Internet Explorer 7 および Internet Explorer 8 について深刻度を「警告」と評価しています。Internet Explorer 9 は、これらの脆弱性による影響を受けません。<br />
<br />
最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-019">MS11-019</a></td>
<td style="border:1px solid black;">SMB クライアントの脆弱性により、リモートでコードが実行される (2511455) <br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の一般に公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。これらの脆弱性のうちで最も深刻な場合、攻撃者がクライアントの送出した SMB リクエストに対して、特別に細工された SMB 応答を返信した場合、リモートでコードが実行される可能性があります。この脆弱性が悪用されるには、ユーザーに特別な細工がされた SMB サーバーへの接続を開始させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-020">MS11-020</a></td>
<td style="border:1px solid black;">SMB サーバーの脆弱性により、リモートでコードが実行される (2508429) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性で、攻撃者が特別に細工された SMB パケットを作成し、影響を受けるコンピューターにそのパケットを送信した場合、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からのこの脆弱性を悪用しようとする攻撃を防ぎ、ネットワークを保護することができます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-027">MS11-027</a></td>
<td style="border:1px solid black;">ActiveX の Kill Bit の累積的なセキュリティ更新プログラム (2508272) <br />
<br />
このセキュリティ更新プログラムは Microsoft のソフトウェアに存在する 1 件の一般で公開された脆弱性および 2 件の非公開で報告された脆弱性を解決します。この脆弱性は、ユーザーが Internet Explorer で特定の ActiveX コントロールをインスタンス化する特別な細工がされた Web ページを表示した場合、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この更新プログラムには 3 つのサードパーティの ActiveX コントロール用の Kill Bit も含まれています。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-028">MS11-028</a></td>
<td style="border:1px solid black;">.NET Framework の脆弱性により、リモートでコードが実行される (2484015) <br />
<br />
このセキュリティ更新プログラムは Microsoft .NET Framework に存在する一般に公開された脆弱性を解決します。この脆弱性では、ユーザーが XAML ブラウザー アプリケーション (XBAP) を使用して、特別に細工された Web ページを閲覧した場合、クライアント システムで、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この脆弱性により、サーバーが ASP.NET ページの処理を許可し、攻撃者が特別に細工した ASP.NET ページをそのサーバーにアップロードして、ページを実行した場合に、Web ホスティングのシナリオと同様に、IIS を実行しているサーバー システム上で、リモートでコードが実行される可能性があります。この脆弱性は、コード アクセス セキュリティ (CAS) の制限を回避する目的で Windows .NET で悪用される可能性もあります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-029">MS11-029</a></td>
<td style="border:1px solid black;">GDI+ の脆弱性により、リモートでコードが実行される (2489979) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows GDI+ に存在する 1 件の脆弱性を解決します。この脆弱性は、ユーザーが影響を受けるソフトウェアを使用して特別に細工された画像ファイルを開いた場合、または特別に細工されたコンテンツが含まれている Web サイトを参照した場合、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-030">MS11-030</a></td>
<td style="border:1px solid black;">DNS 解決の脆弱性により、リモートでコードが実行される (2509553) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows DNS 解決の脆弱性を解決します。この脆弱性により、攻撃者がネットワークへのアクセス許可を取得し、カスタム プログラムを作成して特別に細工した LLMNR のブロードキャスト クエリを標的のシステムに送信した場合、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。この場合、LLMNR ポートはインターネットからブロックされている必要があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-031">MS11-031</a></td>
<td style="border:1px solid black;">JScript および VBScript スクリプト エンジンの脆弱性により、 リモートでコードが実行される (2514666) <br />
<br />
このセキュリティ更新プログラムは、JScript および VBScript スクリプト エンジンに存在する非公開で報告された 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web サイトを訪問すると、リモートでコードが実行される可能性があります。攻撃者は、ユーザーを Web サイトに強制的に訪問させることはできません。その代わりに攻撃者は、ユーザーをこのような Web サイトにアクセスさせるように誘導する必要があります。そのためによく用いられる方法として、電子メール メッセージやインスタント メッセージのリンクをクリックするように仕向け、クリックすると攻撃者の Web サイトに誘導されるという方法があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-032">MS11-032</a></td>
<td style="border:1px solid black;">OpenType Compact Font Format (CFF) ドライバーの脆弱性により、リモートでコードが実行される (2507618) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された OpenType Compact Font Format (CFF) ドライバーに存在する脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された CFF フォントでレンダリングされたコンテンツを表示した場合、リモートでコードが実行される可能性があります。すべての場合において、攻撃者が強制的に特別に細工したコンテンツをユーザーに表示させることはできません。その代わりに、攻撃者はユーザーを攻撃者の Web サイトに訪問させようとします。一般的には、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせ、攻撃者の Web サイトへ誘導します。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Microsoft Excel の脆弱性により、リモートでコードが実行される (2489279) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 9 件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性は、特別に細工された Excel ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-022">MS11-022</a></td>
<td style="border:1px solid black;">Microsoft PowerPoint の脆弱性により、リモートでコードが実行される (2489283) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された 3 件のMicrosoft PowerPoint に存在する脆弱性を解決します。これらの脆弱性により、特別に細工された PowerPoint ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。PowerPoint 2010 用の自動化された Microsoft Fix it ソリューション「PowerPoint 2010 の保護されたビューの編集を無効にする」が、<a href="http://support.microsoft.com/kb/2501584">サポート技術情報 2501584 で利用でき、</a>CVE-2011-0655 および CVE-2011-0656 で説明している脆弱性を悪用する攻撃の手法をブロックします。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms11-023">MS11-023</a></td>
<td style="border:1px solid black;">Microsoft Office の脆弱性により、リモートでコードが実行される (2489293) <br />
<br />
このセキュリティ更新プログラムは Microsoft Office に存在する 1 件の一般に公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされた Office ファイルを開いた場合、または特別な細工がされたライブラリ ファイルと同じネットワーク ディレクトリにある正当な Office ファイルを開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-024">MS11-024</a></td>
<td style="border:1px solid black;">Windows FAX 送付状エディターの脆弱性により、リモートでコードが実行される (2527308) <br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 2 つの公開された脆弱性を解決します。この脆弱性で、ユーザーが Windows FAX 送付状エディターを使用する特別な細工がされた FAX 送付状ファイル (.cov) を開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms11-025">MS11-025</a></td>
<td style="border:1px solid black;">Microsoft Foundation Class (MFC) ライブラリの脆弱性により、 リモートでコードが実行される (2500212) <br />
<br />
このセキュリティ更新プログラムはMicrosoft Foundation Class (MFC) ライブラリを使用して開発された特定のアプリケーションに存在する一般に公開された脆弱性を解決します。この脆弱性で、ユーザーが影響を受けるアプリケーションなどに関連した正当なファイルや、特別な細工がされたライブラリ ファイルと同じネットワーク フォルダーにあるファイルを開いた場合、リモートでコードが実行される可能性があります。攻撃は、ユーザーが信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問して、この場所から影響を受けるアプリケーションでロードされるドキュメントを開いた場合に実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft 開発者用ツールおよびソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-026">MS11-026</a></td>
<td style="border:1px solid black;">MHTML の脆弱性により、情報漏えいが起こる (2503658) <br />
<br />
このセキュリティ更新プログラムは Microsoft Windows の MHTML プロトコル ハンドラーに存在する一般に公開された脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web ページを訪問すると、情報漏えいが起こる可能性があります。Web ベースの攻撃のシナリオで、Web サイトに、この脆弱性の悪用を意図する、特別に細工されたリンクが含まれる可能性があります。この脆弱性が悪用されるには、ユーザーに Web サイトを訪問させ、特別な細工がされたリンクを開かせることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-033">MS11-033</a></td>
<td style="border:1px solid black;">ワードパッドのテキスト コンバーターの脆弱性により、リモートでコードが実行される (2485663) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP および Windows Server 2003 について深刻度を「重要」と評価しています。すべてのサポートされているエディションの Windows Vista、Windows Server2008、Windows 7、および Windows Server 2008 R2 は、この脆弱性の影響を受けません。<br />
<br />
この脆弱性は、ユーザーがワードパッドを使用して、特別に細工されたファイルを開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (2506223) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 30 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性により、攻撃者がローカルでログオンし、特別に細工したアプリケーションを実行した場合、特権の昇格が起こる可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用可能性の評価 (高→低)、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >脆弱性のタイトル</th>
<th style="border:1px solid black;" >CVE の識別番号</th>
<th style="border:1px solid black;" >Exploitability Index の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms11-025">MS11-025</a></td>
<td style="border:1px solid black;">MFC の安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3190">CVE-2010-3190</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-028">MS11-028</a></td>
<td style="border:1px solid black;">.NET Framework のスタック破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3958">CVE-2010-3958</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-032">MS11-032</a></td>
<td style="border:1px solid black;">OpenType フォントのスタック オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0034">CVE-2011-0034</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-029">MS11-029</a></td>
<td style="border:1px solid black;">GDI の整数オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0041">CVE-2011-0041</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">レイアウトの処理のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0094">CVE-2011-0094</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">この脆弱性は、限定的な標的型攻撃で 悪用されています。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel の整数のオーバーランの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0097">CVE-2011-0097</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel のヒープ オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0098">CVE-2011-0098</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel のレコード解析の WriteAV の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0101">CVE-2011-0101</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms11-023">MS11-023</a></td>
<td style="border:1px solid black;">Office コンポーネントの安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0107">CVE-2011-0107</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">MSHTML のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0346">CVE-2011-0346</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-019">MS11-019</a></td>
<td style="border:1px solid black;">SMB クライアントの応答の解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0660">CVE-2011-0660</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-020">MS11-020</a></td>
<td style="border:1px solid black;">SMB のトランザクション解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0661">CVE-2011-0661</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0662">CVE-2011-0662</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0665">CVE-2011-0665</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0666">CVE-2011-0666</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0667">CVE-2011-0667</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0670">CVE-2011-0670</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0671">CVE-2011-0671</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0672">CVE-2011-0672</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0673">CVE-2011-0673</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0674">CVE-2011-0674</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0675">CVE-2011-0675</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0676">CVE-2011-0676</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0677">CVE-2011-0677</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-022">MS11-022</a></td>
<td style="border:1px solid black;">OfficeArt の Atom の RCE の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0976">CVE-2011-0976</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel の配列のインデックスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0978">CVE-2011-0978</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel の連結リスト破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0979">CVE-2011-0979</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel のダングリング ポインターの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0980">CVE-2011-0980</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1225">CVE-2011-1225</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1226">CVE-2011-1226</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1227">CVE-2011-1227</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1228">CVE-2011-1228</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1229">CVE-2011-1229</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1230">CVE-2011-1230</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1231">CVE-2011-1231</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1232">CVE-2011-1232</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1233">CVE-2011-1233</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1235">CVE-2011-1235</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1236">CVE-2011-1236</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1237">CVE-2011-1237</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1239">CVE-2011-1239</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1240">CVE-2011-1240</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1241">CVE-2011-1241</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1242">CVE-2011-1242</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">オブジェクトの管理のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1345">CVE-2011-1345</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">この脆弱性は、限定的な標的型攻撃で悪用されています。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-033">MS11-033</a></td>
<td style="border:1px solid black;">ワードパッドのコンバーターの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0028">CVE-2011-0028</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0103">CVE-2011-0103</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel のバッファー上書きの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0104">CVE-2011-0104</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-021">MS11-021</a></td>
<td style="border:1px solid black;">Excel のデータ初期化の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0105">CVE-2011-0105</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-019">MS11-019</a></td>
<td style="border:1px solid black;">Browser Pool の破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0654">CVE-2011-0654</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-022">MS11-022</a></td>
<td style="border:1px solid black;">Techno-color Time Bandit の浮動小数点の RCE の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0655">CVE-2011-0655</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-022">MS11-022</a></td>
<td style="border:1px solid black;">Persist ディレクトリの RCE の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0656">CVE-2011-0656</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-030">MS11-030</a></td>
<td style="border:1px solid black;">DNS クエリの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0657">CVE-2011-0657</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-031">MS11-031</a></td>
<td style="border:1px solid black;">スクリプトのメモリの再割り当ての脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0663">CVE-2011-0663</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/ms11-023">MS11-023</a></td>
<td style="border:1px solid black;">Microsoft Office グラフィック オブジェクトの逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0977">CVE-2011-0977</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1234">CVE-2011-1234</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-024">MS11-024</a></td>
<td style="border:1px solid black;">FAX 送付状エディターのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3974">CVE-2010-3974</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-024">MS11-024</a></td>
<td style="border:1px solid black;">FAX 送付状の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-4701">CVE-2010-4701</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-026">MS11-026</a></td>
<td style="border:1px solid black;">MHTML の MIME 形式のリクエストの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0096">CVE-2011-0096</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。<br />
<br />
これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-034">MS11-034</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1238">CVE-2011-1238</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms11-018">MS11-018</a></td>
<td style="border:1px solid black;">Javascript の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1245">CVE-2011-1245</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="14">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/security/bulletin/ms11-034)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c3a8cec0-f947-4d4e-a6ae-c7f4f1f311b0)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0b7d0403-8965-4c62-970c-20b561f66713)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=689c5496-56c4-48a6-9f3d-b5f5aaf3e566)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f5378e7b-4619-4c42-9d9f-87b209c6d878)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ccb08a8a-f4d9-4320-8ffb-3fd4fe217987)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b031a496-aa74-4367-b2ae-24843c061745)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(緊急)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=59266a9d-a319-4309-a046-7f15c6da0136)  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2d433adb-bcaf-4c59-9405-a4892f8ccba3)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=637f4d4c-de07-4c6a-95f8-3bd0cbfe77b2)  
(KB2510581)  
(緊急)  
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fbe1e7e3-1d5f-4daf-a4a5-67fe79292963)  
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9080c5a1-e638-4047-a70a-9367f1acced7)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=50fc3869-f2fc-43c8-8049-aad62f2cb332)   
(KB2491683)  
(重要)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a8220a21-02fc-4ad6-988d-844276b2fd66)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7f0a4616-8e3e-4925-9d95-ce6e614e45ae)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6753ca98-feb4-4c7f-9969-9294038a2bbb)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=39e55bbf-c1c5-4696-bfe7-632e997cd98e)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=986f07ae-0fdc-4be2-8a74-5eb56d4300ef)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ed88f183-dd06-46f6-ae8a-a594a752f248)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6d3433ee-c2e1-433f-a3d9-c049d66e2190)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c01441da-8933-4f60-923b-d9b00db8ba3d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7ee202da-a711-42ee-bea3-7202a70e4ea0)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=eddd2964-9765-461d-9df8-2c05402948e8)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(緊急)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3797009a-b9a4-4e83-8614-e1589c8b5090)  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=29ff546e-a232-4f23-a223-c029c71ff1c6)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.6 および VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a5586246-2908-4def-9298-c16060098197)  
(KB2510587)  
(緊急)  
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3a5f65e0-bb00-4e55-b8b5-77751349a3ec)  
(KB2510581)  
(緊急)  
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=57aa7ee2-254d-40b5-9ff0-cba969daf45a)  
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2374e09a-cb3e-4bc3-bb4b-53b611025121)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b93311b4-1b8f-478d-8833-750c5e01e6f8)   
(KB2491683)  
(重要)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0f60fc99-cd88-4237-8b31-a4e618502f7e)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b01fe9a5-66a4-4683-963b-e78aea214579)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3c94bc96-99ea-44a1-9052-e69de5e21f81)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=83771177-284e-4918-86a9-980e8229c7c9)  
(重要)
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/security/bulletin/ms11-034)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[注意](http://technet.microsoft.com/security/bulletin/rating)
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b902c58a-9e2f-4352-8d2f-fffda5344598)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5c464287-3dab-4342-a38d-a12719d3b158)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=45feb35b-b24e-4160-adb0-d0b7ae530e90)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d46fe0bf-28c2-4696-87bc-dd3c8287fc28)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=64c550d4-c927-4382-91e1-473ed6790819)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=53756404-39e4-43af-81e9-81471536aa66)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(緊急)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fd284233-e177-4064-9b02-f83dcb727dbe)  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=753ed6e3-df2e-4b2d-9e9f-7275cd94d214)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.6 および VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e026f2ed-8a20-4268-9b29-04a78bde1999)  
(KB2510587)  
(緊急)  
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5b0ed0b2-07f9-43da-bb5d-5be5a45969ee)  
(KB2510581)  
(緊急)  
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=01aa2beb-9fc1-40f0-a2a4-bcd3d9cb31f8)  
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5d71d3f5-fd6b-4f3b-8389-37c899748d4b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=edda8cce-b764-4ef1-afbe-391fbd087362)   
(KB2491683)  
(重要)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bf084b4c-aac9-4cc6-bb30-87fc96ba9430)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0209a004-f23a-40d9-991f-864046f4605f)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9fbfc742-6c74-49a2-b3cc-e1d5d8c84b77)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=af320f27-bb3a-4e76-a279-4632267c8761)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5d8f14d1-85cc-478f-8b50-5c355a331f59)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9d8bbea9-c456-4569-ad96-c2cd0f5fae7e)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=979d2ec5-5114-4ec7-aa97-e9289c590cbb)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ca0fb4d3-7651-4760-83fa-b71c86cbe459)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef62db94-4f72-4245-ac9f-6391035e2516)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c8d59f49-45ec-4527-b3a8-4925f710bbfd)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(緊急)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d5adaf4e-4cd7-42ea-8202-31b5c856f5e3)  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a0192dbc-4d0d-4555-9ef7-3e10209a6389)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.6 および VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=83ce6c99-a57d-4ed1-972b-a6b6798e6675)  
(KB2510587)  
(緊急)  
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=af791715-77a1-405b-a69e-d63f75dd7ccd)  
(KB2510581)  
(緊急)  
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bf0a2966-25c4-4717-bcd6-016ce610d220)  
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3a498ff0-21d9-493a-b127-6bc20f1baf95)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f04d939a-da11-4a9f-9e03-b6c3bf3ca58b)   
(KB2491683)  
(重要)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=12b01f3a-ccf8-41c1-ac5a-e417a6ddbe95)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6c287571-54ea-4298-8b7d-b98b2c830cc3)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=897b97b0-1bab-4b1b-b417-950fab0d4a65)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9c95f81c-9812-4070-88d7-34422c638e42)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8afe86fc-58b4-4a95-b047-c09138fa4f5e)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f1abfb48-3c8a-4b2d-b739-cc61628b387d)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=87eb8b93-9829-45ec-9528-52787732044e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=79aeb3cd-7c73-467b-b91e-02c6ea01e911)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9c784734-f44f-4a3c-8223-6289f7dc2ad8)  
(深刻度 該当なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6)  
(KB2446704)  
(緊急)  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=72a513bb-f901-4992-8562-d1afe1afec8a)  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f5ad6963-2d6a-4d59-9e25-4fc088647fcd)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.6 および VBScript 5.6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b7d36bae-7ca4-4a40-9efb-13f484fa5518)  
(KB2510587)  
(緊急)  
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3f519013-ed14-41a8-aa45-cf8b095d3152)  
(KB2510581)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c71f4398-2e3b-4b81-a650-8806e618db7f)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=efb575c7-3259-49b1-b59c-89d9544e37a6)   
(KB2491683)  
(重要)  
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=03a7ee49-7bd6-4215-9779-1b48c10d08b9)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3fb450a0-d087-4f36-9301-05ffbf94cc1a)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ede38974-4e57-4ea1-8731-b91e96534693)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f58cf64a-bf31-4496-be75-5775a123338b)  
(重要)
</td>
</tr>
<tr>
<th colspan="14">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/security/bulletin/ms11-034)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
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
[(重要)](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=00c3c176-feff-4022-ac4c-2d4732ca3d78)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5ea94705-4f76-4b0d-bbbc-afb5e75204bf)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=da8dd55d-6630-484e-836c-9feeab5cc311)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d6eddff4-a242-4dec-9d84-72891db2b754)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=80bf050a-9aff-4cd4-8e2f-196b0a92b1c0)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(緊急)  
Windows Vista Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(緊急)  
Windows Vista Service Pack 1 および Windows Vista Service Pack 2:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4ff2e440-79c2-4045-b225-913d1740fdb9)  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2a17e44f-54aa-423d-b3c7-a4f404f7c28b)  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=719e2c86-30e5-4cd5-94f4-d6de54efee5f)  
(KB2510581)  
(緊急)  
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=21decb84-75ef-4bde-a802-1e661a505e94)<sup>[1]</sup>
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e7c4fc81-d1ef-4378-862b-e955d75fb2de)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=11a8f240-51b3-4e31-a24a-a235179f3396)   
(KB2491683)  
(重要)  
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e6cba040-9d7c-4777-a2f7-e4dd11dfb845)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c8fce0fb-4c90-479b-8ce9-75e60d52d256)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b4743167-9614-445a-9e91-10efdac505a8)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=79f52733-44e4-47b6-86ca-1395a095b4e7)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bc63b233-9db0-4fb1-a61c-fa7e9e44ba10)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=040f8b46-f458-4a72-a1b0-ad8a65a1194c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2878c587-6544-40b4-9288-fc3b3ce1128d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a81412d0-2516-4bf4-87f7-3e41ebf6b82b)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 のみ  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(緊急)  
Windows Vista x64 Edition Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(緊急)  
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4d826026-e62a-4cec-8682-49fbe7f65cd6)  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e708d24f-e348-4c4d-99ed-e78dd1689d01)  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=89b9d01e-bcbc-4f2c-973b-51051494f406)  
(KB2510581)  
(緊急)  
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d4ac199e-7bf8-4661-a4e5-c53719b2673a)<sup>[1]</sup>
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8d654a78-0e4f-452c-8874-fbf478813857)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=61db662e-88d7-4454-b4b7-e987728fb137)   
(KB2491683)  
(重要)  
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1c942282-0f80-46c1-aeef-1ef948e105a3)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7da10b64-d0a9-4e42-aa3a-87c657122a8c)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7e410d5c-b9f7-4a63-8300-36b2d57c6128)  
(重要)
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/security/bulletin/ms11-034)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
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
[注意](http://technet.microsoft.com/security/bulletin/rating)
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
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7d8603b8-bb52-4cf6-be8b-bb3475d30fc5)\*\*  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d5d76e90-1cef-47e8-9d8d-2c5a43f42ba3)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f8c9390a-5ca1-492a-9e35-a516de48deb5)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=31c48ba9-7774-4633-862d-5c27c3703584)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c3247886-76d0-4292-be9d-3e9b0221c46a)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)\*\*  
(KB2449741)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)\*\*  
(KB2449742)  
(緊急)  
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*\*<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fbada866-7d36-4b85-acde-fd856a998737)\*\*\*  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9894be38-a582-4c15-ad0e-cc3afab2aebc)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d8b33ffd-eff1-4a10-b6fc-3c8f01e0fec5)\*\*  
(KB2510581)  
(緊急)  
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=afd128ff-717f-4d98-b214-f2c28d59623d)\*\*<sup>[1]</sup>
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9105377e-83c7-4010-8fd6-26e42e98c2cc)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=90f56368-776b-4d45-ad68-91afbd316d25)\*\*   
(KB2491683)  
(重要)  
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fa972742-1166-4a9e-ab64-6a4f968f9c6d)\*   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=036f1285-7484-4e3b-8799-2c6c08166596)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c6ac26b8-8cc8-40fe-baab-22bf13df1aa8)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c6d58f64-bdd5-4fe6-96f4-9641b8e7b570)\*\*  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=51203a31-368b-4b47-96a5-9e9e5a55cd76)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b0cfd5e0-6de5-4863-b5e4-b223a0e36d72)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=de843115-cf98-4511-aa93-f620e4572555)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=51521b6b-94a7-4bcf-ad5f-fc304728b10f)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)\*\*  
(KB2449741)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)\*\*  
(KB2449742)  
(緊急)  
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*\*<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f4ddfcb-374d-4cad-8c61-2b988b46f628)\*\*\*  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2d7d2021-020f-4cc9-a027-258d7e5faec9)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6c2e6b87-afcd-461a-8a43-9a2fb277b18a)\*\*  
(KB2510581)  
(緊急)  
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=40e8beca-0b5a-43b0-98f8-b32a82ad65d6)\*\*<sup>[1]</sup>
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=060e8b20-edca-4427-9d60-eb57261eb668)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=22a001fc-5c2e-4539-85c9-0c2054a1777d)\*\*   
(KB2491683)  
(重要)  
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fc250c8a-ebaf-4264-9393-dc23cc372d9f)\*   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1438cec8-8dab-4510-ad75-dc6959dac0d8)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ac49f5d3-5e2f-4916-99be-a3254278da7e)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f6f6f22c-fc7f-4e96-b6b5-be3c1acecf6e)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8eaf51cd-2f6e-4bbc-bc4f-9deed03649ac)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b89b8e28-cd98-4bcc-8729-5e51d52d1e92)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e7c38b0d-7240-420a-88d3-2749a40e386f)  
(深刻度 該当なし<sup>[1]</sup>)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems のみ  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3)  
(KB2449741)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4)  
(KB2449742)  
(緊急)  
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2fd71543-0e18-4907-89b9-355d24d7db69)  
(KB2412687)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c0275df0-10ac-4500-ab86-b7e9a34f8e1d)  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.7 および VBScript 5.7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=afb49d24-1913-4e5f-a3ea-c6c9642e2017)  
(KB2510581)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2b8571cb-2dae-4bff-9f13-feb89840044c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=421024f1-aa86-459e-b6de-53851a3fcba2)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f35ecdd1-6b5c-40e7-a00b-ca083bdf5cba)  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3b93de4f-01f4-4efd-afc1-31d87b92fad2)  
(重要)
</td>
</tr>
<tr>
<th colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/security/bulletin/ms11-034)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊***急***](http://technet.microsoft.com/security/bulletin/rating)
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
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=59676b71-8b9d-4230-a9e0-b20db3e3ec7e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0dcba089-19f7-46ca-9e52-24eaebad4715)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d3ef905b-3584-4842-9ec2-cf3856305d49)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=46510959-e4a2-4c21-b33c-fd3d97b3ac3d)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(緊急)  
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8fdae09b-d1bb-4ef5-aa45-2a05f2a5e12d)  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=17ebf291-fdae-4e78-9377-871b3103ce16)<sup>[1]</sup>
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=751c45ea-0943-4948-807f-8716c6ff9198)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bf762b86-b949-4e84-8ca4-93ebe669c1b8)   
(KB2491683)  
(重要)  
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0f5a122e-dd5e-4b08-881a-f13b38642720)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=aed201c1-f1fb-4df9-8875-6f57ea0eb15b)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6e7ff003-ff3f-49bb-8e45-d869885dd8d7)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3a998678-2678-489e-8711-39322663147d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b7fd356a-56d0-4638-8901-40acfa600f25)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7ddc943b-6868-4e8f-a869-89b47133c287)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=432555cf-aed8-4329-a74f-526441521082)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(緊急)  
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=40879dfb-efa4-41ba-8d5c-22e926a55eef)  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c95ad86d-da58-4d7a-9ffd-8441f92baaa5)<sup>[1]</sup>
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=976c882a-bc07-4128-927f-82a2df46cf45)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a6793ecf-a3f6-4989-8e4c-c5c0005f9ac4)   
(KB2491683)  
(重要)  
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=658301f1-103a-48a2-9b67-61cf8e1dad50)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1a32bf04-7eed-4d27-a8e4-054b4a5b76cb)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0c0aef7e-501c-4ca3-ae7f-497a8c169121)  
(重要)
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-018](http://technet.microsoft.com/security/bulletin/ms11-018)
</td>
<td style="border:1px solid black;">
[MS11-019](http://technet.microsoft.com/security/bulletin/ms11-019)
</td>
<td style="border:1px solid black;">
[MS11-020](http://technet.microsoft.com/security/bulletin/ms11-020)
</td>
<td style="border:1px solid black;">
[MS11-027](http://technet.microsoft.com/security/bulletin/ms11-027)
</td>
<td style="border:1px solid black;">
[MS11-028](http://technet.microsoft.com/security/bulletin/ms11-028)
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-030](http://technet.microsoft.com/security/bulletin/ms11-030)
</td>
<td style="border:1px solid black;">
[MS11-031](http://technet.microsoft.com/security/bulletin/ms11-031)
</td>
<td style="border:1px solid black;">
[MS11-032](http://technet.microsoft.com/security/bulletin/ms11-032)
</td>
<td style="border:1px solid black;">
[MS11-024](http://technet.microsoft.com/security/bulletin/ms11-024)
</td>
<td style="border:1px solid black;">
[MS11-026](http://technet.microsoft.com/security/bulletin/ms11-026)
</td>
<td style="border:1px solid black;">
[MS11-033](http://technet.microsoft.com/security/bulletin/ms11-033)
</td>
<td style="border:1px solid black;">
[MS11-034](http://technet.microsoft.com/security/bulletin/ms11-034)
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
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊***急***](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[注意](http://technet.microsoft.com/security/bulletin/rating)
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
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c7b2482b-44bf-4c01-99d8-f93868659a24)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=27a3847b-695b-4f60-aea5-86b0dbe68945)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c4352802-9c5a-4c07-8303-3a4b78d3f954)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e4fa8ed0-acb0-4864-be18-29a27f8501de)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)\*  
(KB2446709)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)\*  
(KB2446710)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)\*<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2084c726-187e-41f9-9bea-da18f490d29e)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=aecc2c7a-285c-409d-be23-c5b4b5449496)\*\*<sup>[1]</sup>
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6f2a52cc-4833-448d-becc-2eac1a447410)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=465c0478-6a74-4b00-8608-938cc492549f)\*\*   
(KB2491683)  
(重要)  
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4c5c3a0f-0672-49d0-bcbd-c7f40e11d092)\*   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=665faa7e-2368-4421-9dd5-ea6df2c79498)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2fc66224-45c6-4e8f-ad00-6a1ec30b4505)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=af6db318-fbec-4286-a3a7-4081620146e5)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1e7d3f21-bdbd-4826-855d-85422aa5f836)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0005377b-443f-44ca-a890-620b2dcea6f1)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d7bcf4d7-b697-4c5f-adbc-a2b3700e0ad5)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa)  
(KB2446709)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a)  
(KB2446710)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1:  
[Microsoft .NET Framework 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df)<sup>[1]</sup>
(KB2446708)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=34d2793e-a2cd-49f6-b524-6598ea86175f)  
(緊急)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e1bc0ed8-5a93-4d01-b407-919dfd894b5f)<sup>[1]</sup>
(KB2510531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c6ca0b7c-8151-4d54-aa9b-5ec2b75d8ab6)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1a993f8c-d28a-4a95-a3c6-059f06e75461)   
(KB2506212)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=140ea384-2877-401f-ac3b-f84f6966e970)  
(注意)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=485ccf96-27a0-499e-9f52-2836b73d26d2)  
(重要)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*\*Server Core インストールは影響を受けません。この更新プログラムで解決している脆弱性は、Server Core インストール オプションを使用して Windows Server 2008 または Windows Server 2008 R2 をインストールした場合、この脆弱性による影響を受けるファイルがコンピューターに存在していたとしても、サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 に影響を与えません。しかし、更新プログラムのファイルのバージョン番号は現在コンピューターに存在するファイルのものより新しいため (より新しいバージョン番号を持つため)、この更新プログラムが提供されます。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

MS11-027 に関する注意

<sup>[1]</sup> この特定のオペレーティング システムは、このセキュリティ情報で説明している脆弱性の影響を受けません。この利用可能な更新プログラムは、サード パーティのコントロール用の Kill bit を設定します。

MS11-028 に関する注意

<sup>[1]</sup>.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework 4.0 Client Profile は、.NET Framework 4.0 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4.0 および .NET Framework 4.0 Client Profile の両方に影響を与えます。詳細については、 「[NET Framework のインストール](http://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

MS11-029 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 IDの下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS11-031 に関する注意

<sup>[1]</sup>Internet Explorer 9 をインストールしているコンピューターはこの脆弱性の影響を受けないため、この更新プログラムは必要ありません。Internet Explorer 9 にアップグレードしていないコンピューターは、インストールされている JScript および VBScript のバージョン用の正しい更新プログラムが必要になります。お使いのコンピューターにインストールされている JScript よび VBScript のバージョンの確認方法については、このセキュリティ情報を参照してください。

MS11-024 に関する注意

2 つの更新プログラムが同じオペレーティング システムを対象としている場合、両方の更新プログラムをインストールしてください。

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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="5">
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-021](http://technet.microsoft.com/security/bulletin/ms11-021)
</td>
<td style="border:1px solid black;">
[MS11-022](http://technet.microsoft.com/security/bulletin/ms11-022)
</td>
<td style="border:1px solid black;">
[MS11-023](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-023)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
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
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6c87c2a9-3705-4680-8a9b-63b6ec83674d)  
(KB2509461)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=db2c5cfe-588c-4646-b86a-3fb8248f7af4)  
(KB2466169)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0d215ab6-c9be-4f43-9501-658bb7ef008e)  
(KB2464617)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6c87c2a9-3705-4680-8a9b-63b6ec83674d)  
(KB2509461)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=916a076d-d754-4092-b23d-c8826db7e397)  
(KB2502786)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2ce8349f-79b1-41ef-a1c0-cbe40ccf9f20)  
(KB2464588)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8b68cf68-1606-4649-b860-a64702c6cf33)  
(KB2509503)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5ae34fe0-03bd-48a9-a7ac-de8f7b1aff90)<sup>[1]</sup>
(KB2464583)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6b2526fe-a061-4a17-992e-ac867bef130e)  
(KB2464594)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dbba0cd4-ab72-4e2b-9524-fd6be27f0b02)  
(KB2509488)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32-bit エディション)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a427f0e2-b74d-4ef3-bec4-0a101d09bfa3)  
(KB2466146)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (32-bit エディション)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=549ca7f0-44bf-4965-a9d2-aa5e8dac2238)  
(KB2519975)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (64-bit エディション)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (64-bit エディション)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=13dca35d-2209-4c5c-9150-d6db2bb3b496)  
(KB2466146)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2010 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef62deae-2b07-41c9-a4bf-b746566e59ee)  
(KB2519975)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="5">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-021](http://technet.microsoft.com/security/bulletin/ms11-021)
</td>
<td style="border:1px solid black;">
[MS11-022](http://technet.microsoft.com/security/bulletin/ms11-022)
</td>
<td style="border:1px solid black;">
[MS11-023](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-023)
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
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
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
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5)  
(KB2505924)  
(重要)
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
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918)  
(KB2505927)  
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
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef1e612f-d8e3-4628-9fe4-ad136f0debd3)  
(KB2525412)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ef1e612f-d8e3-4628-9fe4-ad136f0debd3)  
(KB2525412)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0c323a12-6385-4666-ad39-a9516a8eda14)  
(KB2505935)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
その他の Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-029](http://technet.microsoft.com/security/bulletin/ms11-029)
</td>
<td style="border:1px solid black;">
[MS11-021](http://technet.microsoft.com/security/bulletin/ms11-021)
</td>
<td style="border:1px solid black;">
[MS11-022](http://technet.microsoft.com/security/bulletin/ms11-022)
</td>
<td style="border:1px solid black;">
[MS11-023](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-023)
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
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2d75786a-2368-4ef2-970b-fa2e57d63ca9)  
(KB2466158)  
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
Microsoft PowerPoint Viewer 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6e23d3c3-2944-42ea-80b3-0663af60d0f1)  
(KB2464623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=44a703f5-b581-4900-bdbb-0f0e8d9bf0e6)  
(KB2519984)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=946cc611-4d75-4728-b9d3-1c8b557b02c2)  
(KB2466156)  
(重要)
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=913efc28-7deb-47b8-8c22-8eb5fc2631e4)  
(KB2464635)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
MS11-029 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 IDの下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS11-021 に関する注意

<sup>[1]</sup>Microsoft Excel 2007 Service Pack 2 について、セキュリティ更新プログラム パッケージ KB2464583 に加えて、お客様はこのセキュリティ情報で説明している脆弱性から保護するため、Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2 (KB2466156) もインストールする必要があります。

MS11-022 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 IDの下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

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
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-022](http://technet.microsoft.com/security/bulletin/ms11-022)
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
Microsoft Office Web Apps
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Web App](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9847dc05-7d4a-4a64-9e6a-622d3fa171f9)  
(KB2520047)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS11-022 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 IDの下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft 開発者用ツールおよびソフトウェア

 
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
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-025](http://technet.microsoft.com/ja-jp/security/bulletin/ms11-025)
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
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e9501082-a651-452b-8c1a-43987ffd3102)  
(KB2465373)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ee64d83b-6c06-4ccf-b12d-99e2a7a7b18d)  
(KB2538218)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e6a8e024-12ee-43d5-9aae-4c721505d6df)  
(KB2538241)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010 および Microsoft Visual Studio 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7fd643a8-8e05-4d27-8853-33f79f01cb26)  
(KB2542054)  
(重要)  
[Microsoft Visual Studio 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1a21c9db-dfa3-4a07-a1e0-89a8069b7c17)  
(KB2565057)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2005 Service Pack 1 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ae2e1a40-7b45-4fe9-a20f-2ed2923aca62)  
(KB2538242)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual C++ 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2008 Service Pack 1 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a821847e-4c44-45c0-9128-61c822bb3280)  
(KB2538243)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual C++ 2010 および Microsoft Visual C++ 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual C++ 2010 再頒布可能パッケージ](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fe558aed-9274-415f-8a0f-d9d8622fb35b)  
(KB2467173)  
(重要)  
[Microsoft Visual C++ 2010 再頒布可能パッケージ Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7557d29b-731b-4abb-8815-2b87a4132efb)  
(KB2565063)  
(重要)
</td>
</tr>
</table>

<p></p>

 

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

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://go.microsoft.com/fwlink/?linkid=50120) の Web サイトを参照してください。

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

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199)
-   :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

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

-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、MS11-018 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-018 で説明している問題についてマイクロソフトに協力してくださった [MITRE](http://mitre.org/)
-   MS11-018 で説明している問題についてマイクロソフトに協力してくださった [Google Inc.](http://www.google.com/) の Michal Zalewski 氏
-   MS11-018 で説明している 2 件の問題を報告してくださった [Google Inc.](http://www.google.com/) の David Bloom 氏
-   [TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-018 で説明している問題を報告してくださった、[Harmony Security](http://www.harmonysecurity.com/) の Stephen Fewer 氏
-   MS11-021 で説明している 2 件の問題を報告してくださった [Secunia Research](http://secunia.com/) の Alin Rad Pop 氏
-   MS11-021 で説明している問題を報告してくださった [Telus Security Labs](http://www.telussecuritylabs.com) の Muhammad Junaid Bohio 氏
-   [TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-021 で説明している 3 件の問題を報告してくださった Aniway 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、MS11-021 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-021 で説明している問題を報告してくださった [Check Point Vulnerability Discovery Team](http://www.checkpoint.com/) (VDT) の Rodrigo Rubira Branco 氏
-   [TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-021 で説明している問題を報告してくださった匿名のリサーチャー
-   [TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-021 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-022 で説明している 3 件の問題を報告してくださった [TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   MS11-023 で説明している問題を報告してくださった [Fortinet's FortiGuard Labs](http://www.fortiguard.com/) の Haifei Li 氏
-   [TippingPoint's](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-023 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-024 で説明している問題についてマイクロソフトに協力してくださった [Secunia](http://secunia.com/) の Carsten Eiram 氏
-   MS11-026 で説明している問題についてマイクロソフトに協力してくださった [Google Security Team](http://www.google.com/)
-   MS11-027 で説明している問題を報告してくださった Carnegie Mellon University Information Security Office の Chris Ries 氏
-   [iSIGHT Partners](http://www.isightpartners.com/) Global Vulnerability Partnership に協力して、MS11-027 で説明している問題を報告してくださった RadLSneak 氏
-   MS11-029 で説明している問題を報告してくださった [VUPEN Threat Protection Program](http://www.vupen.com/english/services/tpp-index.php) の Nicolas Joly 氏と Chaouki Bekrarfor 氏
-   MS11-030 で説明している問題を報告してくださった [Google Inc.](http://www.google.com/) の Neel Mehta 氏
-   MS11-031 で説明している問題についてマイクロソフトに協力してくださった [Mozilla](http://www.mozilla.org/) の [Jesse Ruderman](http://www.squarefree.com/) 氏
-   MS11-032 で説明している問題を報告してくださった [Fontlab Ltd.](http://www.fontlab.com/) の Adam Twardoch 氏
-   MS11-033 で説明している問題を報告してくださった [Secunia](http://secunia.com/) の Carsten Eiram 氏
-   MS11-034 で説明している 30 件の問題を報告してくださった [Norman](http://www.norman.com/) の Tarjei Mandt 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](http://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2011/04/13):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2011/04/14):このセキュリティ情報ページを更新して、MS11-019 の「概要」の脆弱性の説明を明確にしました。
-   V2.0 (2011/04/16):MS11-032 について、CVE-2011-0034 の「Exploitability Index の評価」を「1 – 安定した悪用コードの可能性」に修正しました。
-   V3.0 (2011/04/22):このセキュリティ情報ページを更新し、MS11-025 の再リリース版のセキュリティ更新プログラムを提供しました。
-   V3.1 (2011/04/28):MS11-024 について、Exploitability Index を修正し CVE-2010-4701 をこの更新プログラムが解決する脆弱性として追加しました。今回の更新は情報のみの変更です。
-   V4.0 (2011/05/17):セキュリティ情報 MS11-018 を再リリースし、サポートされているエディションの Windows XP および Windows Server 2003 上の Internet Explorer 7 用の更新プログラムを再提供しました。バイナリへの変更はありません。影響を受けるお客様にのみ、更新プログラムが提供される予定です。更新プログラムを手動でインストールしたお客様および検出ロジックに対する変更の対象となっていない構成を実行しているお客様については、何の操作も行う必要はありません。
-   V5.0 (2011/06/15):MS11-025 において、Microsoft Visual Studio 2005 Service Pack 1、Microsoft Visual Studio 2008 Service Pack 1、Microsoft Visual Studio 2010、Microsoft Visual C++ 2005 Service Pack 1 再頒布可能パッケージ、および Microsoft Visual C++ 2008 Service Pack 1 再頒布可能パッケージを対象とする更新プログラムを再提供しました。この更新プログラムを以前にインストールしたユーザーは、この新しいパッケージを影響を受けるコンピューターにインストールする必要があります。
-   V6.0 (2011/08/10):MS11-025 において、影響を受けるソフトウェアに Microsoft Visual Studio 2010 Service Pack 1 (KB2565057) および Microsoft Visual C++ 2010 再頒布可能パッケージ Service Pack 1 (KB2565063) を追加しました。
-   V6.1 (2011/10/31):MS11-028 を更新し、Windows Server 2008 R2 for x64-based System 上の .NET Framework 4 の Server Core インストールの適用オプションを修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
