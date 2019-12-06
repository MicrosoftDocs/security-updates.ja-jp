---
TOCTitle: 'MS10-OCT'
Title: 2010 年 10 月のセキュリティ情報
ms:assetid: 'ms10-oct'
ms:contentKeyID: 61229680
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-oct(v=Security.10)'
--- 

2010 年 10 月のセキュリティ情報
===============================

公開日: 2010年10月13日 | 最終更新日: 2011年10月31日

**バージョン:** 4.1

[![](../../images/Dn627259.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627259.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2010 年 10 月公開のセキュリティ情報の一覧です。

2010 年 10 月のセキュリティ情報の公開により、2010 年 10 月 8 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/ja-jp/security/bulletin/advance)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 10 月 13 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2010 年 10 月 13 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[10 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032454437&culture=en-us) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語情報) を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071">MS10-071</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2360131)<br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する 7 件の非公開で報告された脆弱性と3 件の公開された脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-075">MS10-075</a></td>
<td style="border:1px solid black;">Windows Media Player ネットワーク共有サービスの脆弱性により、リモートでコードが実行される (2281679)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft Windows Media Player ネットワーク共有サービスの脆弱性を解決します。この脆弱性では、攻撃者が影響を受けるコンピューターに特別に細工した RTSP パケットを送信した場合、リモートでコードが実行される可能性があります。しかし、ホーム メディアへのインターネット アクセスは既定で無効にされています。この既定の構成では、この脆弱性は同じサブネット内の攻撃者のみに悪用される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-076">MS10-076</a></td>
<td style="border:1px solid black;">Embedded OpenType フォント エンジンの脆弱性により、リモートでコードが実行される (982132)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft Windows コンポーネントである Embedded OpenType (EOT) フォント エンジンに存在する脆弱性を解決します。この脆弱性により、リモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用し、影響を受けるコンピューターをリモートで完全に制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-077">MS10-077</a></td>
<td style="border:1px solid black;">NET Framework の脆弱性により、リモートでコードが実行される (2160841)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft .NET Framework の脆弱性を解決します。この脆弱性では、ユーザーが XAML ブラウザー アプリケーション (XBAP) を使用して、特別に細工された Web ページを閲覧した場合、クライアント システムで、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この脆弱性により、サーバーが ASP.NET ページの処理を許可し、攻撃者が特別に細工した ASP.NET ページをそのサーバーにアップロードして、ページを実行した場合に、Web ホスティングのシナリオと同様に、IIS を実行しているサーバー システム上で、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-072">MS10-072</a></td>
<td style="border:1px solid black;">SafeHTML の脆弱性により、情報漏えいが起こる (2412048)<br />
<br />
このセキュリティ更新プログラムは Microsoft SharePoint および Windows SharePoint サービスに存在する 1 件の公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。これらの脆弱性により、攻撃者が特別に細工したスクリプトを SafeHTML を使用して標的のサイトに送信した場合、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-073">MS10-073</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (981957)<br />
<br />
このセキュリティ更新プログラムは、一般に公開された数件の Windows カーネル モード ドライバーの脆弱性を解決します。最も深刻な脆弱性では、攻撃者が影響を受けるコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーが、この脆弱性を悪用することはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-078">MS10-078</a></td>
<td style="border:1px solid black;">OpenType フォント (OTF) 形式ドライバーの脆弱性により、特権が昇格される (2279986)<br />
<br />
このセキュリティ更新プログラムは Windows OpenType フォント (OTF) 形式ドライバーに存在する非公開で報告された脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP および Windows Server 2003 について深刻度を「重要」と評価しています。すべてのサポートされているエディションの Windows Vista、Windows Server2008、Windows 7、および Windows Server 2008 R2 は、この脆弱性の影響を受けません。<br />
<br />
この脆弱性により、ユーザーが特別な細工がされた OpenType フォントでレンダリングされたコンテンツを表示した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーが、この脆弱性を悪用することはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-079">MS10-079</a></td>
<td style="border:1px solid black;">Microsoft Word の脆弱性により、リモートでコードが実行される (2293194)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 11 件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性は、特別な細工がされた Word ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-080">MS10-080</a></td>
<td style="border:1px solid black;">Microsoft Excel の脆弱性により、リモートでコードが実行される (2293211)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 13 件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性により、ユーザーが特別な細工がされた Excel ファイルまたは特別な細工がされた Lotus 1-2-3 ファイルを開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-081">MS10-081</a></td>
<td style="border:1px solid black;">Windows コモン コントロール ライブラリの脆弱性により、リモートでコードが実行される (2296011)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Windows コモン コントロール ライブラリの脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web ページを訪問すると、リモートでコードが実行される可能性があります。ユーザーが管理者特権でログオンしている場合、攻撃者がこの脆弱性を悪用し、影響を受けるコンピューターを完全に制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-082">MS10-082</a></td>
<td style="border:1px solid black;">Windows Media Player の脆弱性により、リモートでコードが実行される (2378111)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows Media Player の脆弱性を解決します。Windows Media Player が悪意のある Web サイトでホストされている特別な細工がされたメディア コンテンツを開いた場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-083">MS10-083</a></td>
<td style="border:1px solid black;">Windows シェルおよびワードパッドの COM の検証の脆弱性により、リモートでコードが実行される (2405882)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性は、ユーザーがワードパッドを使用して、特別に細工されたファイルを開く、または、ネットワークや WebDAV 共有上のショートカット ファイルを開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-084">MS10-084</a></td>
<td style="border:1px solid black;">Windows ローカル プロシージャー コールの脆弱性により、特権が昇格される (2360937)<br />
<br />
このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP および Windows Server 2003 について深刻度を「重要」と評価しています。すべてのサポートされているエディションの Windows Vista、Windows Server2008、Windows 7、および Windows Server 2008 R2 は、この脆弱性の影響を受けません。<br />
<br />
この脆弱性で、攻撃者が影響を受けるコンピューターにログオンし、LPC メッセージをローカル LRPC サーバーに送信する特別な細工がされたコードを実行した場合、特権が昇格される可能性があります。メッセージにより、認証されたユーザーが NetworkService アカウントのコンテキストで実行されているリソースにアクセスできる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-085">MS10-085</a></td>
<td style="border:1px solid black;">SChannel の脆弱性により、サービス拒否が起こる (2207566)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Windows の SChannel (セキュリティで保護されたチャネル) のセキュリティ パッケージの脆弱性を解決します。この脆弱性で、影響を受けるコンピューターが特別な細工がされたパケット メッセージを Secure Sockets Layer (SSL) を介し受け取った場合、サービス拒否が起こる可能性があります。既定で、すべてのサポートされているエディションの Windows Vista、Windows Server 2008、Windows 7 および Windows Server 2008 R2 は SSL ネットワーク トラフィックを受け取るよう構成されていません。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-074">MS10-074</a></td>
<td style="border:1px solid black;">Microsoft Foundation Classes の脆弱性により、リモートでコードが実行される (2387149)<br />
<br />
このセキュリティ更新プログラムはMicrosoft Foundation Class (MFC) Library に存在する一般に公開された脆弱性を解決します。この脆弱性により、ユーザーが管理者ユーザー権限でログオンし MFC Library で設計されたアプリケーションを開いている場合、リモートでコードが実行されます。攻撃者がこの脆弱性を悪用した場合、現在ログオンしているユーザーと同じユーザー権限を取得する可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者が影響を受けるコンピューターを完全に制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">警告</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-086">MS10-086</a></td>
<td style="border:1px solid black;">Windows 共有クラスター ディスクの脆弱性により、改ざんが起こる (2294255)<br />
<br />
このセキュリティ更新プログラムは、共有フェールオーバー クラスターとして使用された場合の Windows Server 2008 R2 に存在する非公開で報告された脆弱性を解決します。この脆弱性により、フェールオーバー クラスター ディスクの管理用共有でデータが改ざんされる可能性があります。既定で、Windows Server 2008 R2 サーバーは、この脆弱性の影響を受けません。この脆弱性はフェールオーバー クラスターで使用されているクラスター ディスクにのみ該当します。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">警告</a><br />
改ざん</td>
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
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
| セキュリティ情報 ID                                                       | 脆弱性のタイトル                                       | CVE の識別番号                                                                   | Exploitability Index の評価                                                                     | 注意事項                                                                                                                                                                                       |  
|---------------------------------------------------------------------------|--------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-083](https://technet.microsoft.com/security/bulletin/ms10-083)       | COM の検証の脆弱性                                     | [CVE-2010-1263](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-076](https://technet.microsoft.com/security/bulletin/ms10-076)       | Embedded OpenType フォントの整数オーバーフローの脆弱性 | [CVE-2010-1883](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1883) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | 新しいオペレーティング システムでは ASLR により悪用が難しくなります。                                                                                                                          |  
| [MS10-078](https://technet.microsoft.com/security/bulletin/ms10-078)       | OpenType フォントの解析の脆弱性                        | [CVE-2010-2740](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2740) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-078](https://technet.microsoft.com/security/bulletin/ms10-078)       | OpenType フォントの検証の脆弱性                        | [CVE-2010-2741](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2741) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)       | Win32k のキーボードのレイアウトの脆弱性                | [CVE-2010-2743](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2743) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | この脆弱性は一般に公開されており、現在インターネット エコシステム上で悪用されています。                                                                                                        |  
| [MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)       | Win32k のウィンドウ クラスの脆弱性                     | [CVE-2010-2744](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2744) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | この脆弱性は一般に公開されていました。                                                                                                                                                         |  
| [MS10-082](https://technet.microsoft.com/security/bulletin/ms10-082)       | Windows Media Player のメモリ破損の脆弱性              | [CVE-2010-2745](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2745) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-081](https://technet.microsoft.com/security/bulletin/ms10-081)       | Comctl32 のヒープ オーバーフローの脆弱性               | [CVE-2010-2746](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2746) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word のスタック オーバーフローの脆弱性                 | [CVE-2010-3214](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3214) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word のブックマークの脆弱性                            | [CVE-2010-3216](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3216) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-084](https://technet.microsoft.com/security/bulletin/ms10-084)       | LPC メッセージのバッファー オーバーランの脆弱性        | [CVE-2010-3222](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3222) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | この脆弱性は一般に公開されていました。                                                                                                                                                         |  
| [MS10-075](https://technet.microsoft.com/security/bulletin/ms10-075)       | RTSP における解放後使用の脆弱性                        | [CVE-2010-3225](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3225) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-077](https://technet.microsoft.com/security/bulletin/ms10-077)       | .NET Framework x64 JIT コンパイラの脆弱性              | [CVE-2010-3228](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3228) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | Excel のファイル形式の解析の脆弱性                     | [CVE-2010-3232](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3232) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | 数式のサブシステムのメモリ破損の脆弱性                 | [CVE-2010-3234](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3234) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | 数式の Biff のレコードの脆弱性                         | [CVE-2010-3235](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3235) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | 境界外の配列の脆弱性                                   | [CVE-2010-3236](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3236) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | Negative Future Function の脆弱性                      | [CVE-2010-3238](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3238) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | その他の境界外のレコードの解析の脆弱性                 | [CVE-2010-3239](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3239) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) | 初期化されていないメモリの破損の脆弱性                 | [CVE-2010-3326](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3326) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) | 初期化されていないメモリの破損の脆弱性                 | [CVE-2010-3328](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3328) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) | 初期化されていないメモリの破損の脆弱性                 | [CVE-2010-3329](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3329) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) | 初期化されていないメモリの破損の脆弱性                 | [CVE-2010-3331](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3331) | [1](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word の初期化されていないポインターの脆弱性            | [CVE-2010-2747](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2747) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word の境界チェックの脆弱性                            | [CVE-2010-2748](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2748) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word のインデックスの脆弱性                            | [CVE-2010-2750](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2750) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word の戻り値の脆弱性                                  | [CVE-2010-3215](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3215) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word のポインターの脆弱性                              | [CVE-2010-3217](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3217) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word のヒープ オーバーフローの脆弱性                   | [CVE-2010-3218](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3218) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word のインデックスの解析の脆弱性                      | [CVE-2010-3219](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3219) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word の解析の脆弱性                                    | [CVE-2010-3220](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3220) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)       | Word の解析の脆弱性                                    | [CVE-2010-3221](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3221) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | Excel のレコードの解析の整数オーバーフローの脆弱性     | [CVE-2010-3230](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3230) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | Excel のレコード解析のメモリ破損の脆弱性               | [CVE-2010-3231](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3231) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | Lotus 1-2-3 のワークブックの解析の脆弱性               | [CVE-2010-3233](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3233) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | セルの結合のレコード ポインターの脆弱性                | [CVE-2010-3237](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3237) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | リアル タイムのデータ配列のレコードの脆弱性            | [CVE-2010-3240](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3240) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | 解析における境界外のメモリの書き込みの脆弱性           | [CVE-2010-3241](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3241) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)       | 非実態レコードの種類の解析の脆弱性                     | [CVE-2010-3242](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3242) | [2](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                                                         |  
| [MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)       | Win32k の参照カウントの脆弱性                          | [CVE-2010-2549](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2549) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | この脆弱性は一般に公開されていました。                                                                                                                                                         |  
| [MS10-085](https://technet.microsoft.com/security/bulletin/ms10-085)       | TLSv1 のサービス拒否の脆弱性                           | [CVE-2010-3229](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3229) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | 脆弱性による最も深刻な影響は、サービス拒否のみです。                                                                                                                                           |  
| [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) | HTML のサニタイズの脆弱性                              | [CVE-2010-3243](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3243) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | [MS10-072](https://technet.microsoft.com/security/bulletin/ms10-072) でもこの脆弱性を解決します。脆弱性による最も深刻な影響は、情報漏えいのみです。                                             |  
| [MS10-072](https://technet.microsoft.com/security/bulletin/ms10-072)       | HTML のサニタイズの脆弱性                              | [CVE-2010-3243](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3243) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) でもこの脆弱性を解決します。脆弱性による最も深刻な影響は、情報漏えいのみです。                                       |  
| [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) | HTML のサニタイズの脆弱性                              | [CVE-2010-3324](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3324) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | [MS10-072](https://technet.microsoft.com/security/bulletin/ms10-072) でもこの脆弱性を解決します。この脆弱性は一般に公開されていました。脆弱性による最も深刻な影響は、情報漏えいのみです。       |  
| [MS10-072](https://technet.microsoft.com/security/bulletin/ms10-072)       | HTML のサニタイズの脆弱性                              | [CVE-2010-3324](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3324) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) でもこの脆弱性を解決します。この脆弱性は一般に公開されていました。脆弱性による最も深刻な影響は、情報漏えいのみです。 |  
| [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) | CSS 特殊文字の情報漏えいの脆弱性                       | [CVE-2010-3325](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3325) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | この脆弱性は一般に公開されていました。脆弱性による最も深刻な影響は、情報漏えいのみです。                                                                                                       |  
| [MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071) | クロスドメイン、情報の漏えいの脆弱性                   | [CVE-2010-3330](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3330) | [3](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) – 機能する見込みのない悪用コード | 脆弱性による最も深刻な影響は、情報漏えいのみです。                                                                                                                                             |
  
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
[MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](https://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](https://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](https://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](https://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](https://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](https://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](https://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](https://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](https://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](https://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](https://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=3b029696-cf98-4935-b3d6-846110aaa4bb&displaylang=ja)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=c77ee103-7e97-44b2-bbf3-ee9f0de37fed&displaylang=ja)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=93580299-d764-417f-a7fa-ee441fea2bb3&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=c3799399-ca72-4dec-a2a2-3571ad0b2f63&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3966d754-d298-4e4a-9ce6-8205accd2215&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=0553fc7c-deed-4594-a133-d621551310dc&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=912a7c20-8177-4f65-b986-43fca6375ec1&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 9 シリーズ](https://www.microsoft.com/download/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c&displaylang=ja)  
(重要)  
[Windows XP 用 Windows Media Player 10 のセキュリティ更新プログラム (KB911565)](https://www.microsoft.com/download/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c&displaylang=ja)  
(重要)  
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=bbf153e7-e764-46a0-a33b-81b7288d346c&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=211d95be-5630-4af5-85a7-c50268c475a9&displaylang=ja)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=6049c879-b81a-4d10-b96b-b2837cb24834&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=22f46b3b-9be6-45ea-a639-9974324ce4bd&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=d494535a-b68e-4242-af85-5fa62f631ffc&displaylang=ja)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ff9c65fe-437c-426d-9096-dd89ff7927fd&displaylang=ja)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=05413f6c-b4be-4892-b4b3-c54dd01fd95d&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=860ff738-205d-430e-b223-b333813fc590&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja)<sup>[1]</sup>
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7fd7c675-0675-4a87-a709-edc47a30f1e2&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1ad30596-bac6-4d48-8b15-0245960c443b&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6c651bca-adb1-4172-9714-cd5a6e5d2c2a&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP 用 Windows Media Player 10 のセキュリティ更新プログラム (KB911565)](https://www.microsoft.com/download/details.aspx?familyid=0663e0e8-c5d1-4cd2-b6d3-ff78fb56bba1&displaylang=ja)  
(重要)  
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=474b5618-dfe6-40de-b59b-1fd61a05749e&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4b6f0898-8f77-4ce1-9c96-2b17c496230b&displaylang=ja)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d690846c-5e0b-4216-84cd-d17e366dd16d&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=285627b9-242d-4247-a4c8-55dc89386b62&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](https://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](https://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](https://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](https://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](https://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](https://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](https://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](https://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](https://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](https://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](https://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f64af3cd-591d-4212-94a0-3bc9a4d9782a&displaylang=ja)  
(重要)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=fbcf0e65-c9f4-47f8-b4fc-ae46a66ab339&displaylang=ja)  
(重要)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=9af37f62-5585-4ff5-9dd3-3fa0b148ae08&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7b240b65-f3ca-465c-a606-b561999c1977&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8ef4378e-21ff-4290-96ba-e00a60f372d1&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f94763e7-b1db-4043-aa79-d5be1a42307d&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3b2eb449-ad55-4dfb-a3c5-aac767de6f45&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP 用 Windows Media Player 10 のセキュリティ更新プログラム (KB911565)](https://www.microsoft.com/download/details.aspx?familyid=5479fd20-50d1-447a-8555-a98ce0723f71&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=13c08ec0-53ae-4b85-b669-8c88f6089259&displaylang=ja)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b31e18b0-da9f-4b3b-82c6-603e08b3b241&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d220f04e-9dbb-4b6d-924a-23065b48b8b6&displaylang=ja)  
(警告)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=12c3b950-b955-4820-9b4c-5206deb0cd3e&displaylang=ja)  
(重要)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=59a715a5-10ff-40e6-88e0-096c9b640799&displaylang=ja)  
(重要)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=c8052f0c-e62c-46c4-bb59-d515fa388ea8&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=70c9e826-b80b-4a20-82d2-8e52e5cca839&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja)<sup>[1]</sup>
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4a95c74b-cfd8-45b5-8887-777429d21745&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6fca5cab-7e11-4911-a6a8-f73f113b2963&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=54fc4bc6-f46c-447c-8307-afd8338e7ffb&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP 用 Windows Media Player 10 のセキュリティ更新プログラム (KB911565)](https://www.microsoft.com/download/details.aspx?familyid=a9515e69-c147-4810-8c5a-6cb94c398a95&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=02519f9e-e1c5-48a1-8420-01898c45ec01&displaylang=ja)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=1d73f0f1-6ec8-4304-a20e-345d8b6c225a&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=de908137-33e0-4f23-b32b-cc1bdbcb349c&displaylang=ja)  
(警告)
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
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=97b3f6dc-8df5-4c93-aaee-f191498c7ce4&displaylang=ja)  
(重要)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=ba194be9-24f9-4c62-9aa9-9e98c81ddba1&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=bd5878bb-f565-4303-afed-4e17b44a02f2&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)<sup>[1]</sup>
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=21637cd8-c75c-43b4-9948-be7be54af6bf&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=e8f297e2-0dfd-421a-b598-a78199ad6baa&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=64f5c311-d74a-4665-9775-ac91c6885ed3&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=1064bccb-3ce6-4a72-8788-56d8021bca91&displaylang=ja)  
(KB979687)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=8fad4f77-7c89-4684-b957-9c00ced248d3&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=873dea9d-44cc-4e16-8a6d-dca678ce3a80&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="14">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](https://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](https://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](https://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](https://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](https://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](https://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](https://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](https://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](https://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](https://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](https://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=4f656d16-2a7e-4d18-8a5a-ebf8a1a10e2b&displaylang=ja)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=191c8388-f1ef-45b6-9f07-d5654a973abe&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4a481825-d9ad-4a7c-aa89-f40fb9651961&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=29c4afb1-227d-4572-b136-a78ef7e1df77&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=e9f735ab-d995-4209-b2dc-197f53fdee0f&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=95ceafc6-e37a-4c77-b16e-c9c94a7d89bd&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=95e24a63-d21a-4756-a16e-17a977595396&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=80c99d69-4b97-4af2-8f8e-f3b300a89a5a&displaylang=ja)<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dff92449-22ad-49a8-8b28-5295a8af5b8b&displaylang=ja)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4af2f6e6-6905-498c-bfba-a565976b3365&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=75ca4e2c-b0ae-46f4-a0fc-616510c41a55&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=02c6260c-8e21-401a-992d-884c6ff7141d&displaylang=ja)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=adeb3036-62fa-4a29-b82f-ff4a50c05996&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=15d8f81b-97b0-43d9-b218-1cdd759cb2ec&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=880ad9a0-6ddd-41f4-a608-171d59a31b6a&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)<sup>[1]</sup>
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=738c8f70-b46a-4a59-bea6-078074a9c4db&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dfe7cd18-53a3-433e-9a33-bd96b04b4deb&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=277151a2-b74f-4da6-8203-e774af75e44c&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b73951f2-a7eb-4c7c-bf60-fdcfee83574f&displaylang=ja)<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c9d2261f-bd9a-4495-a2f1-3c3b2208b01e&displaylang=ja)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8c56ba29-b2a8-47a8-a605-4c54c0a7fa7c&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0a12ff95-ea5c-4c48-96c5-9494eb8f9f0d&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](https://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](https://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](https://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](https://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](https://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](https://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](https://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](https://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](https://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](https://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](https://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=0107dd61-7b3e-4fcf-9743-d9ae594b2278&displaylang=ja)\*\*  
(重要)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ea5b7c86-3878-43a9-a4bc-12e04bfbd06e&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=50386655-982e-4126-8261-2c972d695bbd&displaylang=ja)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4dff0ebe-ccba-4675-98ca-9903f1cb6763&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d5f079b0-d8e1-47fe-b9dd-41eeb463a93c&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=67eb3a70-9ca7-4184-b9fe-cc3e66b1bf36&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=fd507e7a-4516-474b-8f33-7fa8fd2afa6d&displaylang=ja)\*\*<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=4a8c2358-36ea-4757-abfc-5bffcad0a872&displaylang=ja)\*\*<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0566915f-2a1b-474b-b5f1-e1a9cedd836a&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=952b3594-d980-45b1-8fa3-49403784afbf&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=139f3bb2-eefc-4cf4-9c15-de78f5a736c1&displaylang=ja)\*\*  
(重要)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=71ecdb27-46aa-4db1-b86a-3268cda88632&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b5f53faf-61e2-4b4e-8b85-c5e8f38e5c30&displaylang=ja)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)\*\*<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=da7905a9-9587-4184-8fca-ecc636a3b67e&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=8e88d9c5-eb57-4d39-a880-a478c5f286da&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 11](https://www.microsoft.com/download/details.aspx?familyid=33a06f0e-81ab-445a-bc89-14350ebfe688&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b5f53faf-61e2-4b4e-8b85-c5e8f38e5c30&displaylang=ja)\*\*<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=612ab78c-1ff1-45d2-96cc-ae831fb0a563&displaylang=ja)\*\*<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=74ac2233-02ec-454c-8aa0-64b18071e16a&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=21128031-d935-4e2d-b001-c502a2d6022c&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=1a971fb2-7dc4-43bf-ae25-3a420bb1acf9&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a4e38a77-3835-47b3-bd86-6c039169abf5&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b9096046-8c7a-450c-b8c5-6e9fb001e6cd&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=76e46d08-22d9-4a0c-82cd-d2753d07efe6&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=5efe55b0-d34d-4f00-98b2-cc0e9807a8b9&displaylang=ja)<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d30368cb-c6e8-403e-aaf6-425f96b6211e&displaylang=ja)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2fff281a-2221-42a3-a2b7-07b5c5e66ae7&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2eca0c38-73f5-4f83-ab62-97f979716a1d&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](https://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](https://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](https://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](https://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](https://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](https://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](https://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](https://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](https://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](https://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](https://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[なし](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=6595770f-e580-4613-a83a-3b8ee4cc30f1&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=1a3953fe-ba48-4980-a65d-74e3b756d53c&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=f6cae091-e9f1-48e9-a035-4346b9c6fec6&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=b5b31499-d242-42bf-ac78-b787ffb4d602&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=bdff9057-381a-44e8-b093-84f07d8d7e3c&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](https://www.microsoft.com/download/details.aspx?familyid=59a2ef36-9c32-488b-b5b1-30b5bcd83358&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=b0d46bc3-24db-4207-b6fc-46b8cc64f075&displaylang=ja)<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=4a422192-d7fa-47e5-9661-2c65eaefaf62&displaylang=ja)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=d7a08a66-08b4-421c-afad-f2f367d4a9f0&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=f09fbc23-cb6b-4525-8e41-8c14e8d03de9&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=ffe364ee-e2ae-466c-b727-14b1a976a860&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=5759d2a3-7f35-4fa1-8ab4-17145839fa26&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=35882477-4e0a-4783-a4b4-0f1ea3398360&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)<sup>[1]</sup>
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=c47e8b74-8cfe-42d9-9362-8786687c88ad&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=35a2b1a9-6dd6-4a7e-bc0a-b4fcffa06b28&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](https://www.microsoft.com/download/details.aspx?familyid=00176d56-8a93-4780-96fc-a7ab715e7291&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=2de197c0-6d9e-460e-9509-f337fac8ee85&displaylang=ja)<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=03665687-8fd4-4afd-ac33-5f6824f51df8&displaylang=ja)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=50d27c23-5f69-40fa-b517-32c245009467&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=abc24826-b83a-4e01-be68-8e3a73c10494&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
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
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)<sup>[1]</sup>
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
対象外
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-071](https://technet.microsoft.com/ja-jp/security/bulletin/ms10-071)
</td>
<td style="border:1px solid black;">
[MS10-075](https://technet.microsoft.com/security/bulletin/ms10-075)
</td>
<td style="border:1px solid black;">
[MS10-076](https://technet.microsoft.com/security/bulletin/ms10-076)
</td>
<td style="border:1px solid black;">
[MS10-077](https://technet.microsoft.com/security/bulletin/ms10-077)
</td>
<td style="border:1px solid black;">
[MS10-073](https://technet.microsoft.com/security/bulletin/ms10-073)
</td>
<td style="border:1px solid black;">
[MS10-078](https://technet.microsoft.com/security/bulletin/ms10-078)
</td>
<td style="border:1px solid black;">
[MS10-081](https://technet.microsoft.com/security/bulletin/ms10-081)
</td>
<td style="border:1px solid black;">
[MS10-082](https://technet.microsoft.com/security/bulletin/ms10-082)
</td>
<td style="border:1px solid black;">
[MS10-083](https://technet.microsoft.com/security/bulletin/ms10-083)
</td>
<td style="border:1px solid black;">
[MS10-084](https://technet.microsoft.com/security/bulletin/ms10-084)
</td>
<td style="border:1px solid black;">
[MS10-085](https://technet.microsoft.com/security/bulletin/ms10-085)
</td>
<td style="border:1px solid black;">
[MS10-074](https://technet.microsoft.com/security/bulletin/ms10-074)
</td>
<td style="border:1px solid black;">
[MS10-086](https://technet.microsoft.com/security/bulletin/ms10-086)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=d8b563ce-5db1-4490-8a63-44833d55152b&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=b060c516-233a-4e1e-9237-698420e97b2f&displaylang=ja)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=98e0c6ac-c30b-4d39-8ed9-1fe69e7644e5&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=25fff010-3abc-45e6-979e-21d2bae49418&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Player 12](https://www.microsoft.com/download/details.aspx?familyid=4cf0e3b1-4b72-4f99-b716-2489ea42ed72&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=70622d35-4877-4cbb-bdbf-7648dc1ea8ed&displaylang=ja)\*\*<sup>[1]</sup>
(KB979687)  
(重要)  
 Windows Server 2008 R2 for x64-based Systems\*\*<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=d356af2f-eadf-4bf2-82d1-efa0d01ac92d&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=e4d27aa6-9739-4e41-9536-5f0b8d26503c&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=1de12fdf-b439-4020-9313-a193d47dcfb2&displaylang=ja)\*  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
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
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)\*\*<sup>[1]</sup>
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
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bbaa9f46-8fc7-4c44-b38c-dc3d5210f63d&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=0ead2ed9-8b2f-496e-b7d1-3ad2b04be5cc&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=44080c75-036e-4bd0-914a-74ab72189ee3&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=d0742526-b5ec-4658-82f1-c3680f33a790&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
 
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems<sup>[1]</sup>
(KB979687)  
(重要)  
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=f478020b-0305-47d5-bcb2-0758f292db29&displaylang=ja)<sup>[1]</sup>
(KB979688)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=334d39e6-8e4c-4e83-94c1-1db3d636e865&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=c1634278-5598-45e0-81c6-f18fb5ba54cf&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=1c607c7d-6144-4a39-beea-a31b62085047&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
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
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/details.aspx?familyid=bbc22169-996f-48d1-beed-0ee0dc4fbf4f&displaylang=ja&displaylang=ja)<sup>[1]</sup>
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
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
MS10-077 に関する注

<sup>[1]</sup>.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework 4.0 Client Profile は、.NET Framework 4.0 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4.0 および .NET Framework 4.0 Client Profile の両方に影響を与えます。詳細については、MSDN の記事「.NET Framework のインストール」を参照してください。

MS10-083 に関する注意

<sup>[1]</sup>同じオペレーティング システムに KB979687 と KB979688 の両方のセキュリティ更新プログラムが利用可能ですが、お客様は MS10-083 で説明している脆弱性に対し保護を行うために、両方の更新プログラムをインストールする必要があります。

Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。Server Core インストール オプションを使用してインストールしている場合、サポートされているエディションのWindows Server 2008 はこのアドバイザリで説明している脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

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
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)
</td>
<td style="border:1px solid black;">
[MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f22d10fd-cb12-43e8-88d5-2116cf4317c4&displaylang=ja)  
(KB2328360)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=ea859881-2cc5-407b-a394-5d00c5d9fd97&displaylang=ja)  
(KB2345017)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=172f3743-cdfa-42d7-aeb4-27ba0e4139f7&displaylang=ja)  
(KB2344911)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=3d9a00b8-0f80-4d36-b92a-89b61350fb36&displaylang=ja)  
(KB2344893)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Word 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ccad4871-32f2-4982-a23e-9b5824397615&displaylang=ja)<sup>[1]</sup>
(KB2344993)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=dc9b9af5-50b0-4a07-8923-a30fd5548760&displaylang=ja)<sup>[1]</sup>
(KB2345035)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32-bit エディション)
</td>
<td style="border:1px solid black;">
[Microsoft Word 2010 (32 ビット版)](https://www.microsoft.com/download/details.aspx?familyid=6c3b8690-e568-42ed-a858-0cbdd5ea3669&displaylang=ja)  
(KB2345000)  
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
[Microsoft Word 2010 (64-bit エディション)](https://www.microsoft.com/download/details.aspx?familyid=f31a1f9b-02df-4a85-a7d1-7d1e31baa30f&displaylang=ja)  
(KB2345000)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)
</td>
<td style="border:1px solid black;">
[MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=464965fa-971a-49dd-bcee-c4d91fac86a9&displaylang=ja)  
(KB2422343)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?familyid=464965fa-971a-49dd-bcee-c4d91fac86a9&displaylang=ja)  
(KB2422343)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=abd05074-8ffc-41a4-a2f3-1d8047574552&displaylang=ja)  
(KB2422352)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?familyid=abd05074-8ffc-41a4-a2f3-1d8047574552&displaylang=ja)  
(KB2422352)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=5c759c46-ead3-44ea-b7c8-a308b3140d2e&displaylang=ja)  
(KB2422398)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?familyid=5c759c46-ead3-44ea-b7c8-a308b3140d2e&displaylang=ja)  
(KB2422398)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
その他の Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)
</td>
<td style="border:1px solid black;">
[MS10-080](https://technet.microsoft.com/security/bulletin/ms10-080)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Word Viewer](https://www.microsoft.com/download/details.aspx?familyid=1cb5ab02-074d-4877-b378-7058959705ae&displaylang=ja)  
(KB2345009)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=a833a94a-2dc0-4864-9c14-e196dc54c5a7&displaylang=ja)  
(KB2345088)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=553d28ae-c352-4985-97c3-e5038414be45&displaylang=ja)  
(KB2345043)  
(重要)
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7391ec2f-12c9-483c-91d8-e3ec5754da1c&displaylang=ja)  
(KB2344875)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS10-079 に関する注意

<sup>[1]</sup>Microsoft Word 2007 Service Pack 2 について、セキュリティ更新プログラム パッケージ KB2344993 に加えて、お客様は MS10-079 で説明している脆弱性から保護するため、Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パックの Service Pack 2 (KB2345043) もインストールする必要があります。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS10-080 に関する注意

<sup>[1]</sup>Microsoft Office Excel 2007 Service Pack 2 について、セキュリティ更新プログラム パッケージ 2345035 に加えて、お客様は MS10-080 で説明している脆弱性から保護するため、Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パックの Service Pack 2 (KB2344875) もインストールする必要があります。

#### Microsoft サーバー ソフトウェア

 
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
Microsoft SharePoint Services および Microsoft SharePoint Foundation
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-072](https://technet.microsoft.com/security/bulletin/ms10-072)
</td>
<td style="border:1px solid black;">
[MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32-bit エディション)](https://www.microsoft.com/download/details.aspx?familyid=12fd97a9-6fb8-4b65-a497-a56587f114e1&displaylang=ja)  
(KB2345304)  
(重要)  
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64-bit エディション)](https://www.microsoft.com/download/details.aspx?familyid=58d1e91d-a037-485d-a6d9-80fbf403b108&displaylang=ja)  
(KB2345304)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010](https://www.microsoft.com/download/details.aspx?familyid=fc146fcb-c2cb-4860-a0cd-4b09fa3f44eb&displaylang=ja)  
(KB2345322)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft SharePoint Server および Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-072](https://technet.microsoft.com/security/bulletin/ms10-072)
</td>
<td style="border:1px solid black;">
[MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (32-bit エディション)](https://www.microsoft.com/download/details.aspx?familyid=aee3f2de-ccf3-4d32-b468-eede4e8afcd4&displaylang=ja)<sup>[1]</sup>
(KB2345212)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (64-bit エディション)](https://www.microsoft.com/download/details.aspx?familyid=e5e60751-242a-4fdb-9852-6d94050d3d0e&displaylang=ja)<sup>[1]</sup>
(KB2345212)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010](https://www.microsoft.com/download/details.aspx?familyid=e032aef8-dd30-41c6-99bb-8cf0491451cc&displaylang=ja)  
(KB2346298)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS10-072](https://technet.microsoft.com/security/bulletin/ms10-072)
</td>
<td style="border:1px solid black;">
[MS10-079](https://technet.microsoft.com/security/bulletin/ms10-079)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps](https://www.microsoft.com/download/details.aspx?familyid=8fb56eb9-9601-4c1e-905a-9fe4802b2c8d&displaylang=ja)  
(KB2346411)  
(重要)
</td>
 
<td style="border:1px solid black;">
Microsoft Office Web Apps<sup>[2]</sup>
(KB2346411)  
(重要)  
[Microsoft Word Web App](https://www.microsoft.com/download/details.aspx?familyid=13b24264-ec3d-44e8-81e3-82ac767defd3&displaylang=ja)<sup>[2]</sup>
(KB2345015)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS10-072 に関する注意

 <sup>[1]</sup>サポートされているエディションの Microsoft SharePoint Server 2007 について、お客様は MS10-072 で説明している脆弱性に対する保護を行うために、セキュリティ更新プログラム パッケージ KB2345212 と共に、Microsoft Windows SharePoint Services 3.0 (KB2345304) のセキュリティ更新プログラムもインストールする必要があります。

MS10-079 に関する注意

 <sup>[2]</sup> Microsoft Office Web Apps について、お客様は MS10-079 で説明している脆弱性から保護するため、KB2346411 と KB2345015 の両方のセキュリティ更新プログラムをインストールする必要があります。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

検出および適用ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](https://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](https://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](https://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](https://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](https://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および適用のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および適用に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および適用のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](https://support.microsoft.com/kb/961747) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](https://go.microsoft.com/fwlink/?linkid=50120) の Web サイトを参照してください。

Systems Management Server

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、[System Center Configuration Manager 2007](https://technet.microsoft.com/ja-jp/library/bb735860.aspx) (英語情報) も参照してください。管理者が SMS 2003 を使用してセキュリティ更新プログラムを適用する方法については、[SMS 2003 Security Patch Management](https://go.microsoft.com/fwlink/?linkid=22939)(英語情報) を参照してください。また、SMS 2.0 ユーザーも、Security Update Inventory Tool (SUIT) を活用して、セキュリティ更新プログラムを適用できます。SMS の詳細については、[Systems Management Server](https://go.microsoft.com/fwlink/?linkid=21158)(英語情報) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](https://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2.0 Administration Feature Pack](https://go.microsoft.com/fwlink/?linkid=21161) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、WSUS および SUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://www.microsoft.com/security/msrc/mapp/partners.mspx)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS10-071 で説明している問題を報告してくださった [Google Inc](https://www.google.com/). の [Sirdarckcat](https://www.sirdarckcat.net/) 氏
-   MS10-071 で説明している問題を報告してくださった Mario Heiderich 氏
-   MS10-071 で説明している問題を報告してくださった [IBM ISS X-Force](https://www.iss.net/) の Takehiro Takahashi 氏
-   MS10-071 で説明している問題を報告してくださった [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力している [Peter Vreugdenhil](https://vreugdenhilresearch.nl) 氏
-   MS10-071 で説明している問題を報告してくださった [Core Security Technologies](https://www.coresecurity.com/) の Damián Frizza 氏
-   MS10-071 で説明している問題を報告してくださった [Cigital](https://www.cigital.com/) の Aldwin Saugere 氏および Radoslav Vasilev 氏
-   MS10-071 で説明している問題を報告してくださった [Check Point](https://www.checkpoint.com/) IPS Research Center の Rodrigo Rubira Branco 氏
-   MS10-072 で説明している問題を報告してくださった [Google Inc](https://www.google.com/). の [Sirdarckcat](https://www.sirdarckcat.net/) 氏
-   MS10-072 で説明している問題を報告してくださった Mario Heiderich 氏
-   MS10-073 で説明している問題を報告してくださった [Kaspersky Lab](https://www.kaspersky.com) の Sergey Golovanov 氏、Alexander Gostev 氏、Maxim Golovkin 氏、Alexey Monastyrsky 氏と、[Design and Test Lab](https://www.dnt-lab.com) の Vitaly Kiktenko 氏および Alexander Saprykin 氏
-   MS10-073 で説明している問題を報告してくださった [Symantec](https://www.symantec.com/index.jsp) の Eric Chien 氏
-   MS10-073 で説明している問題を報告してくださった [Norman](https://www.norman.com) の Tarjei Mandt 氏
-   MS10-074 で説明している問題についてマイクロソフトに協力してくださった [Secunia Research](https://secunia.com/) の Carsten H. Eiram 氏
-   MS10-075 で説明している問題を報告してくださった [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力している Oleksandr Mirosh 氏
-   MS10-076 で説明している問題を報告してくださった [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力している Sebastian Apelt 氏
-   MS10-076 で説明している問題を [iSIGHT Partners Global Vulnerability Partnership](https://gvp.isightpartners.com/) を通して報告してくださった Ivan Fratric 氏
-   MS10-077 で説明している問題を報告してくださった [Sumatra](https://www.sumatra.nl/) の Jeroen Frijters 氏
-   MS10-078 で説明している問題を報告してくださった [siberas](https://www.siberas.de/) の Sebastian Apelt 氏
-   MS10-078 で説明している問題を報告してくださった [Core Security Technologies](https://www.coresecurity.com/) の Diego Juarez 氏
-   MS10-079 で説明している 10 件の問題を報告してくださった [VUPEN Vulnerability Research Team](https://www.vupen.com/) の Chaouki Bekrar 氏
-   MS10-079 で説明している問題を報告してくださった [VUPEN Vulnerability Research Team](https://www.vupen.com/) の Nicolas Joly 氏
-   MS10-079 で説明している問題を報告してくださった [Secunia](https://secunia.com/) の Alin Rad Pop 氏
-   MS10-080 で説明している 2 件の問題を報告してくださった [Secunia](https://secunia.com/) の Alin Rad Pop 氏
-   MS10-080 で説明している 10 件の問題を報告してくださった [VUPEN Vulnerability Research Team](https://www.vupen.com/) の Chaouki Bekrar 氏
-   MS10-080 で説明している問題を報告してくださった Omair 氏
-   MS10-080 で説明している 2 件の問題を報告してくださった [Secunia](https://secunia.com/) の Carsten H. Eiram 氏
-   MS10-081 で説明している問題を報告してくださった [Secunia](https://secunia.com/) に協力している Krystian Kloskowski (h07) 氏
-   MS10-082 で説明している問題を報告してくださった [Google Inc.](https://www.google.com/) の SkyLined 氏
-   MS10-083 で説明している問題を報告してくださった [Rapid7](https://www.rapid7.com/) の HD Moore 氏
-   MS10-083 で取り上げた多層防御の変更についてマイクロソフトに協力してくださった [IBM ISS X-Force](https://www.iss.net/) の David Dewey 氏および [Accuvant](https://www.accuvant.com/) (前 [VeriSign iDefense Labs](https://labs.idefense.com/)) の Ryan Smith 氏
-   MS10-085 で説明している問題を報告してくださった [Mu Dynamics](https://www.mudynamics.com/) の [Mu Test Suite Team](https://www.mudynamics.com/products/mu-test-suite.html)

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](https://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](https://support.microsoft.com/)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](https://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2010/10/13):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2010/10/14):MS10-077 の Windows Server 2008 および Windows Server 2008 R2 の最大深刻度を「重要」に変更しました。また、MS10-082 の Windows XP Professional x64 Edition Service Pack 2 上の Windows Media Player 11 のダウンロード リンクを修正しました。
-   V2.0 (2010/10/19):「概要」の MS10-085 についての説明を更新し、SSL ネットワーク トラフィックを受け取るよう構成されている影響を受けるコンピューターでこの脆弱性が悪用される可能性があることを明確にしました。今回の更新は情報のみの変更です。自動更新を有効にしているお客様など、すでにコンピューターを更新済みのお客様は特別な措置を講じる必要はありません。以前に、この更新プログラムをインストールしていないお客様は、この更新プログラムがシステムに必要であるかどうかを確認する必要があります。
-   V3.0 (2010/12/15):下記をお知らせするためにこのセキュリティ情報を更新しました。MS10-077 では、他の更新プロフラムおよび/または製品が正常にインストールされるのを妨げるセットアップの問題を修正するために .NET Framework 4.0 用の新しい更新プログラムが利用可能になりました。システムを正常に更新済みのお客様は、措置を講じる必要はありません。MS10-083 では、Windows Vista Service Pack 1 または Windows Server 2008上に Windows Search 4.0 をインストール後にサポート技術情報 2405882 で提供されているセキュリティ更新プログラムをインストールし、Windows Vista Service Pack 2 または Windows Server 2008 Service Pack 2 (KB979688) に移行したお客様へ Windows Vista Service Pack 2 (KB979688) 用の追加の更新プログラムを提供しました。新しい更新プログラムは、[マイクロソフト サポート技術情報 2405882](https://support.microsoft.com/kb/2405882) で入手できます。
-   V4.0 (2011/02/23:このセキュリティ情報ページを更新し、Windows 7 for x64-based Systems Service Pack 1、Windows Server 2008 R2 for x64-based Systems Service Pack 1 または Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 をインストールした後、Microsoft .NET Framework 4.0 をインストールしたお客様に Microsoft .NET Framework 4.0 (KB2416472) の MS10-077 の更新プログラム パッケージを提供するよう検出を変更したことをお知らせしました。
-   V4.1 (2011/10/31):MS10-077 に関して、Windows Server 2008 R2 for x64-based Systems 向け .NET Framework 4 に対する Server Core のインストール適用性を修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
