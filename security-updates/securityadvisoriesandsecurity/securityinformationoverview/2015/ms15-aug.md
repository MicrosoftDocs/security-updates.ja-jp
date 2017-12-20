---
TOCTitle: 'MS15-AUG'
Title: 2015 年 8 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms15-aug'
ms:contentKeyID: 68229846
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms15-aug(v=Security.10)'
---

2015 年 8 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2015 年 8 月 12 日 | 最終更新日: 2015 年 12 月 2 日

**バージョン:** 3.1

このセキュリティ情報の概要は 2015 年 8 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムと共に、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「**関連情報**」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「**影響を受けるソフトウェア**」を参照してください。

<p> </p>  <table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度<br />
と脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>既知の<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3082442)</strong> <br />
このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネントの脆弱性により、リモートでコードが実行される (3078662)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows、Microsoft .NET Framework、Microsoft Office、Microsoft Lync、および Microsoft Silverlight の脆弱性を解決します。最も深刻な場合、ユーザーが特別な細工がされた文書を開いた場合や、TrueType または OpenType フォントが埋め込まれた信頼されていない Web ページを表示した場合に、この脆弱性によりリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Office、<br />
Microsoft Lync、<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、リモートでコードが実行される (3080790)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3080790">3080790</a></td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619679">MS15-082</a></td>
<td style="border:1px solid black;"><strong>RDP の脆弱性により、リモートでコードが実行される (3080348)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この中で最も深刻な脆弱性が悪用されると、攻撃者がまず標的のユーザーの現在の作業ディレクトリに特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルを配置し、ユーザーに、リモート デスクトップ プロトコル (RDP) ファイルを開くか、設計上は信頼できる DLL ファイルを読み込むが、代わりに攻撃者が特別に細工した DLL ファイルを読み込むプログラムを起動するよう誘導した場合、リモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が対象のシステムを完全に制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3080348">3080348</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619627">MS15-083</a></td>
<td style="border:1px solid black;"><strong>サーバー メッセージ ブロックの脆弱性により、リモートでコードが実行される (3073921)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工された文字列を SMB サーバーのエラー ログに送信した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619680">MS15-084</a></td>
<td style="border:1px solid black;"><strong>XML コア サービスの脆弱性により、情報漏えいが起こる (3080129)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows および Microsoft Office の脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工されたリンクをクリックした場合にメモリ アドレスを漏えいさせるか、SSL (Secure Sockets Layer) 2.0 の使用を明示的に許可することにより、情報漏えいが起こる可能性があります。しかし、すべての場合において、攻撃者がユーザーに特別に細工したリンクを強制的にクリックさせる方法はありません。通常は、電子メールまたはインスタント メッセンジャーのメッセージの誘導により、ユーザーにリンクをクリックさせることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3076895">3076895</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619646">MS15-085</a></td>
<td style="border:1px solid black;"><strong>マウント マネージャーの脆弱性により、特権が昇格される (3082487)</strong><br />
このセキュリティ更新プログラムにより、Microsoft Windows の脆弱性が解決されます。この脆弱性により、攻撃者が標的のシステムに悪意のある USB デバイスを挿入した場合、特権が昇格される可能性があります。攻撃者は、悪意のあるバイナリをディスクに書き込み、それを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3071756">3071756</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=616872">MS15-086</a></td>
<td style="border:1px solid black;"><strong>System Center Operations Manager の脆弱性により、特権が昇格される (3075158)</strong><br />
このセキュリティ更新プログラムは、Microsoft System Center Operations Manager の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された URL を使用して影響を受ける Web サイトを訪問した場合、特権が昇格される可能性があります。攻撃者は、このような Web サイトにユーザーを強制的に訪問させることはできません。その代わり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせることにより、影響を受ける Web サイトにユーザーを訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動は必要ありません</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619633">MS15-087</a></td>
<td style="border:1px solid black;"><strong>UDDI サービスの脆弱性により、特権が昇格される (3082459)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が Web ページ検索パラメーターに悪意のあるスクリプトを挿入して、クロスサイト スクリプティング (XSS) のシナリオを画策した場合に、特権が昇格される可能性があります。脆弱性の悪用には、悪意のあるスクリプトが実行される、特別に細工された Web ページにユーザーがアクセスすることが必要条件になります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動は必要ありません</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619632">MS15-088</a></td>
<td style="border:1px solid black;"><strong>安全ではないコマンド ライン パラメーターの受け渡しにより、情報漏えいが起こる (3082458)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows、Internet Explorer、および Microsoft Office の情報漏えいの脆弱性の解決に役立ちます。脆弱性を悪用するため、攻撃者は最初に Internet Explorer の別の脆弱性を使用してサンドボックス プロセスでコードを実行する必要があります。続いて攻撃者は、安全ではないコマンド ライン パラメーターを使用し、メモ帳、Visio、PowerPoint、Excel、または Word を実行して、情報漏えいに影響を及ぼす可能性があります。この脆弱性から保護するには、このセキュリティ情報に記載されている更新プログラムだけでなく、<a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a> に記載されている Internet Explorer 用の更新プログラムも適用する必要があります。同様に、影響を受ける Microsoft Office 製品を実行している場合は、<a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a> に記載されている該当する更新プログラムもインストールする必要があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619647">MS15-089</a></td>
<td style="border:1px solid black;"><strong>WebDAV の脆弱性により、情報漏えいが起こる (3076949)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が Secure Socket Layer (SSL) 2.0 を有効にされた WebDAV サーバーとの間で暗号化された SSL 2.0 セッションを強制的に確立し、中間者 (MiTM) 攻撃を使用して暗号化されたトラフィックの一部を暗号化解除した場合、情報が漏えいする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619649">MS15-090</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows の脆弱性により、特権が昇格される (3060716)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性により、攻撃者が影響を受けるシステムにログオンし、特別に細工されたアプリケーションを実行した場合、または脆弱性のあるサンドボックス アプリケーションを呼び出す特別に細工されたファイルをユーザーに開かせて、攻撃者がサンドボックスを回避できるようにした場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3060716">3060716</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620118">MS15-091</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3084525)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620204">MS15-092</a></td>
<td style="border:1px solid black;"><strong>.NET Framework の脆弱性により、特権が昇格される (3086251)<br />
</strong>このセキュリティ更新プログラムは、Microsoft .NET Framework の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された .NET アプリケーションを実行した場合、特権の昇格が起こる可能性があります。ただし、いかなるケースにおいても、攻撃者はユーザーにそのようなアプリケーションを強制的に実行させる手段を持っていません。攻撃者はユーザーがそうするように仕向ける必要があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620908">MS15-093</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用のセキュリティ更新プログラム (3088903)</strong> <br />
このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。この脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
</tbody>
</table>
 

Exploitability Index (悪用可能性指標)
-------------------------------------

<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。

**この表はどのように使用しますか?**

この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。

下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

<p> </p>  <table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>脆弱性のタイトル</strong></td>
<td style="border:1px solid black;"><strong>CVE の識別番号</strong></td>
<td style="border:1px solid black;"><strong>過去のソフトウェア リリースでの<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>過去のソフトウェア リリースでの<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>サービス拒否<br />
悪用可能性評価</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">安全ではないコマンド ライン パラメーターを渡すことによる脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2441">CVE-2015-2441</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2442">CVE-2015-2442</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2443">CVE-2015-2443</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2444">CVE-2015-2444</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">ASLR バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2445">CVE-2015-2445</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2446">CVE-2015-2446</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2447">CVE-2015-2447</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2448">CVE-2015-2448</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">ASLR バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2449">CVE-2015-2449</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2450">CVE-2015-2450</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2451">CVE-2015-2451</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619622">MS15-079</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2452">CVE-2015-2452</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">Microsoft Office Graphics コンポーネントのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2431">CVE-2015-2431</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2432">CVE-2015-2432</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">カーネル ASLR バイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2433">CVE-2015-2433</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2435">CVE-2015-2435</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">Windows CSRSS の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2453">CVE-2015-2453</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">Windows KMD のセキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2454">CVE-2015-2454</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2455">CVE-2015-2455</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2456">CVE-2015-2456</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2458">CVE-2015-2458</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2459">CVE-2015-2459</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2460">CVE-2015-2460</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2461">CVE-2015-2461</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2462">CVE-2015-2462</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2463">CVE-2015-2463</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2464">CVE-2015-2464</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619676">MS15-080</a></td>
<td style="border:1px solid black;">Windows シェルのセキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2465">CVE-2015-2465</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1642">CVE-2015-1642</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;">安全ではないコマンド ライン パラメーターを渡すことによる脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office のリモート コードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2466">CVE-2015-2466</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2467">CVE-2015-2467</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2468">CVE-2015-2468</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2469">CVE-2015-2469</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office の整数アンダーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2470">CVE-2015-2470</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619678">MS15-081</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2477">CVE-2015-2477</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619679">MS15-082</a></td>
<td style="border:1px solid black;">リモート デスクトップ セッション ホストのなりすましの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2472">CVE-2015-2472</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619679">MS15-082</a></td>
<td style="border:1px solid black;">リモート デスクトップ プロトコル DLL プランティングのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2473">CVE-2015-2473</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619627">MS15-083</a></td>
<td style="border:1px solid black;">サーバー メッセージ ブロックのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2474">CVE-2015-2474</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619680">MS15-084</a></td>
<td style="border:1px solid black;">MSXML の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2434">CVE-2015-2434</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619680">MS15-084</a></td>
<td style="border:1px solid black;">MSXML の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2440">CVE-2015-2440</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619680">MS15-084</a></td>
<td style="border:1px solid black;">MSXML の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2471">CVE-2015-2471</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619646">MS15-085</a></td>
<td style="border:1px solid black;">マウント マネージャーの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1769">CVE-2015-1769</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=616872">MS15-086</a></td>
<td style="border:1px solid black;">System Center Operations Manager Web コンソールの XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2420">CVE-2015-2420</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619633">MS15-087</a></td>
<td style="border:1px solid black;">UDDI サービスの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2475">CVE-2015-2475</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619632">MS15-088</a></td>
<td style="border:1px solid black;">安全ではないコマンド ライン パラメーターを渡すことによる脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619309">MS15-089</a></td>
<td style="border:1px solid black;">WebDAV クライアントの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2476">CVE-2015-2476</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619649">MS15-090</a></td>
<td style="border:1px solid black;">Windows オブジェクト マネージャーの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2428">CVE-2015-2428</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619649">MS15-090</a></td>
<td style="border:1px solid black;">Windows レジストリの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2429">CVE-2015-2429</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=619649">MS15-090</a></td>
<td style="border:1px solid black;">Windows ファイル システムの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2430">CVE-2015-2430</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620118">MS15-091</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2441">CVE-2015-2441</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620118">MS15-091</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2442">CVE-2015-2442</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620118">MS15-091</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2446">CVE-2015-2446</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620118">MS15-091</a></td>
<td style="border:1px solid black;">ASLR バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2449">CVE-2015-2449</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620204">MS15-092</a></td>
<td style="border:1px solid black;">RyuJIT 最適化の特権の昇格に関する脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2479">CVE-2015-2479</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620204">MS15-092</a></td>
<td style="border:1px solid black;">RyuJIT 最適化の特権の昇格に関する脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2480">CVE-2015-2480</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620204">MS15-092</a></td>
<td style="border:1px solid black;">RyuJIT 最適化の特権の昇格に関する脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2481">CVE-2015-2481</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=620908">MS15-093</a></td>
<td style="border:1px solid black;">メモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2502">CVE-2015-2502</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
</tr>
</tbody>
</table>
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントを基に、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムとコンポーネント (表 1/3)

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(緊急)  
Internet Explorer 8  
(3078071)  
(緊急)  
Internet Explorer 9  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(緊急)  
Microsoft .NET Framework 4  
(3072309)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(緊急)  
Microsoft .NET Framework 4.6  
(3072311)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3075220)  
(重要)  
Windows Vista Service Pack 2  
(3075221)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(緊急)  
Internet Explorer 8  
(3078071)  
(緊急)  
Internet Explorer 9  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(緊急)  
Microsoft .NET Framework 4  
(3072309)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(緊急)  
Microsoft .NET Framework 4.6  
(3072311)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3075220)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3075221)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(警告)  
Internet Explorer 8  
(3078071)  
(警告)  
Internet Explorer 9  
(3078071)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(緊急)  
Microsoft .NET Framework 4  
(3072309)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(緊急)  
Microsoft .NET Framework 4.6  
(3072311)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(警告)  
Internet Explorer 8  
(3078071)  
(警告)  
Internet Explorer 9  
(3078071)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(緊急)  
Microsoft .NET Framework 4  
(3072309)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(緊急)  
Microsoft .NET Framework 4.6  
(3072311)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3078601)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(緊急)  
Internet Explorer 9  
(3078071)  
(緊急)  
Internet Explorer 10  
(3078071)  
(緊急)  
Internet Explorer 11  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3075220)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3075222)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3075226)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(緊急)  
Internet Explorer 9  
(3078071)  
(緊急)  
Internet Explorer 10  
(3078071)  
(緊急)  
Internet Explorer 11  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3075220)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3075222)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3075226)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(警告)  
Internet Explorer 9  
(3078071)  
(警告)  
Internet Explorer 10  
(3078071)  
(警告)  
Internet Explorer 11  
(3078071)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3075220)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3075222)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3075226)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3078601)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5  
(3072306)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5  
(3072306)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5  
(3072307)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5  
(3072307)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5  
(3072306)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5  
(3072307)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3078601)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3078601)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081436)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3081436)  
(緊急)  
Microsoft .NET Framework 3.5  
(3081436)  
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
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081436)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3081436)  
(緊急)  
Microsoft .NET Framework 3.5  
(3081436)  
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
<td style="border:1px solid black;" colspan="6">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-079**](http://go.microsoft.com/fwlink/?linkid=619622)

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-082**](http://go.microsoft.com/fwlink/?linkid=619679)

</td>
<td style="border:1px solid black;">
[**MS15-083**](http://go.microsoft.com/fwlink/?linkid=619627)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3078601)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3078601)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3073921)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
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
Windows Server 2012 (Server Core インストール)  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5  
(3072306)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3078601)  
(緊急)  
Microsoft .NET Framework 3.5  
(3072307)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3075220)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および MSXML コア サービス 6.0  
(3076895)  
(重要)

</td>
</tr>
</table>
 
**MS15-080、MS15-084 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Windows オペレーティング システムとコンポーネント (表 2/3)

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046017)  
(重要)  
Windows Vista Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046017)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3073893)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3046017)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3073893)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3046017)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3046017)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3046017)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3046017)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3046017)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3046017)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3076949)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3081436)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3081436)  
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
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3081436)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3081436)  
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
<td style="border:1px solid black;" colspan="6">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-085**](http://go.microsoft.com/fwlink/?linkid=619646)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
<td style="border:1px solid black;">
[**MS15-088**](http://go.microsoft.com/fwlink/?linkid=619632)

</td>
<td style="border:1px solid black;">
[**MS15-089**](http://go.microsoft.com/fwlink/?linkid=619647)

</td>
<td style="border:1px solid black;">
[**MS15-090**](http://go.microsoft.com/fwlink/?linkid=619649)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3073893)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3046017)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3073893)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3046017)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3046017)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3079757)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3060716)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3071756)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3046017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3060716)  
(重要)

</td>
</tr>
</table>
 
**MS15-087 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Windows オペレーティング システムとコンポーネント (表 3/3)

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(緊急)  
Internet Explorer 8  
(3087985)  
(緊急)  
Internet Explorer 9  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(緊急)  
Internet Explorer 8  
(3087985)  
(緊急)  
Internet Explorer 9  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(警告)  
Internet Explorer 8  
(3087985)  
(警告)  
Internet Explorer 9  
(3087985)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(警告)  
Internet Explorer 8  
(3087985)  
(警告)  
Internet Explorer 9  
(3087985)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(緊急)  
Internet Explorer 9  
(3087985)  
(緊急)  
Internet Explorer 10  
(3087985)  
(緊急)  
Internet Explorer 11  
(3087985)  
(緊急)

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(緊急)  
Internet Explorer 9  
(3087985)  
(緊急)  
Internet Explorer 10  
(3087985)  
(緊急)  
Internet Explorer 11  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(警告)  
Internet Explorer 9  
(3087985)  
(警告)  
Internet Explorer 10  
(3087985)  
(警告)  
Internet Explorer 11  
(3087985)  
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
Internet Explorer 8  
(3087985)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081436)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3081436)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081444)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081436)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3081436)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081444)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-091**](http://go.microsoft.com/fwlink/?linkid=620118)

</td>
<td style="border:1px solid black;">
[**MS15-092**](http://go.microsoft.com/fwlink/?linkid=620204)

</td>
<td style="border:1px solid black;">
[**MS15-093**](http://go.microsoft.com/fwlink/?linkid=620908)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

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
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
Microsoft .NET Framework 4.6  
(3083184)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
### Microsoft サーバー ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft System Center 2012 Operations Manager**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;" colspan="2">
[**MS15-086**](http://go.microsoft.com/fwlink/?linkid=616872)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;" colspan="2">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager

</td>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager  
(更新プログラムのロールアップ 8 をインストール)  
(3071089)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager Service Pack 1

</td>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager Service Pack 1  
(更新プログラムのロールアップ 10 をインストール)  
(3071088)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft System Center 2012 Operations Manager R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-086**](http://go.microsoft.com/fwlink/?linkid=616872)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager R2

</td>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager R2  
(更新プログラムのロールアップ 7 をインストール)  
(3064919)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft BizTalk Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-086**](http://go.microsoft.com/fwlink/?linkid=616872)

</td>
<td style="border:1px solid black;">
[**MS15-087**](http://go.microsoft.com/fwlink/?linkid=619633)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2010

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2010  
(3087119)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2013

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2013  
(3087119)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2013 R2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2013 R2  
(3087119)  
(重要)

</td>
</tr>
</table>
 
**MS15-087 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft Office スイートおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3054890)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2687409)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(3054888)  
(緊急)  
Microsoft Office 2007 Service Pack 3  
(2596650)  
(緊急)  
Microsoft Office 2007 Service Pack 3  
(2837610)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(3054992)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(3055051)  
(重要)  
Microsoft Visio 2007 Service Pack 3  
(2965280)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3055052)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 5.0  
(2825645)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3054846)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2965310)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3055037)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2553313)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2598244)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3055044)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 ビット版)  
(3055033)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (32 ビット版)  
(3054876)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3055039)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3054846)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2965310)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3055037)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2553313)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2598244)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3055044)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 ビット版)  
(3055033)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (64 ビット版)  
(3054876)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3055039)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3039734)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3039798)  
(緊急)  
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3054816)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3054991)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 ビット版)  
(3055029)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (32 ビット版)  
(3054929)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3055030)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3039734)  
(重要)  
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3039798)  
(緊急)  
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3054816)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3054991)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 ビット版)  
(3055029)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (64 ビット版)  
(3054929)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3055030)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3039798)  
(緊急)  
Microsoft Office 2013 RT Service Pack 1  
(3054816)  
(重要)  
Microsoft Excel 2013 RT Service Pack 1  
(3054991)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3055029)  
(重要)  
Microsoft Visio 2013 RT Service Pack 1  
(3054929)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3055030)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)  
(3085538)  
(緊急)  
Microsoft Visio 2016 (32 ビット版)  
(2920708)  
(重要)  
Microsoft Word 2016 (32 ビット版)  
(2920691)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)  
(3085538)  
(緊急)  
Microsoft Visio 2016 (64 ビット版)  
(2920708)  
(重要)  
Microsoft Word 2016 (64 ビット版)  
(2920691)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3081349)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2016

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2016  
(3082420)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**その他の Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
<td style="border:1px solid black;">
[**MS15-084**](http://go.microsoft.com/fwlink/?linkid=619680)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2986254)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3055053)  
(重要)  
Microsoft Word Viewer  
(3055054)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 5.0  
(2825645)  
(重要)

</td>
</tr>
</table>
 
**MS15-080、MS15-081、MS15-084 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft Office Services および Web Apps

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3054960)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3054858)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3054974)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-081**](http://go.microsoft.com/fwlink/?linkid=619678)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3055003)  
(重要)

</td>
</tr>
</table>
 
**MS15-081 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft コミュニケーション プラットフォームおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3075591)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)  
(3075593)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)  
(3075593)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(ユーザー レベル インストール)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(ユーザー レベル インストール)  
(3075592)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(管理レベル インストール)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(管理レベル インストール)  
(3075590)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)  
(3055014)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)  
(Skype for Business Basic)  
(3055014)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)  
(Skype for Business)  
(3055014)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)  
(Skype for Business Basic)  
(3055014)  
(緊急)

</td>
</tr>
</table>
 
**MS15-080 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft 開発者用ツールおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-080**](http://go.microsoft.com/fwlink/?linkid=619676)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5  
(3080333)  
(緊急)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(3080333)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(3080333)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3080333)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(3080333)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3080333)  
(緊急)

</td>
</tr>
</table>
 
**MS15-080 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールの詳細については、「[セキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、[謝辞](https://technet.microsoft.com/ja-jp/library/security/dn903755.aspx)を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/ja-jp/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージを Microsoft ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/ja-jp/kb/913086) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ja)

国ごとのローカル サポート: [インターナショナル サポート](http://support.microsoft.com/common/international.aspx?ln=ja)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation およびその関連会社は、本文書に含まれている情報の使用および使用結果につき、正確性、真実性など、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社およびこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2015/08/12): このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2015/08/19): このセキュリティ情報の概要を更新し、定例外の 1 つのセキュリティ情報 MS15-093 を 8 月のセキュリティ情報のリリースに追加しました。この追加のセキュリティ情報は Internet Explorer の脆弱性を解決します。詳細については、MS15-093 を参照してください。
-   V3.0 (2015/10/14): MS15-081 について、セキュリティ情報の概要ページを更新し、Microsoft Office 2016、Microsoft Visio 2016、および Microsoft Word 2016 用の更新プログラム パッケージが利用可能になったことをお知らせしました。Microsoft Office 2016、Microsoft Visio 2016、または Microsoft Word 2016 を実行しているお客様は、MS15-081 に記載されている脆弱性から保護するために、該当する更新プログラムを適用する必要があります。自動更新を有効にしている大多数のお客様は、更新プログラムが自動的にダウンロードおよびインストールされるため、特別な措置を講じる必要はありません。
-   V3.1 (2015/12/02): このセキュリティ情報の概要ページを更新し、MS15-085 (3071756) および MS15-090 (3060716) に関連する更新プログラムのサポート技術情報に、既知の問題の説明を追加したことをお知らせしました。詳細は、概要の表に記載されているハイパーリンクを参照してください。

*Page generated 2015-12-01 10:00Z-08:00.*
