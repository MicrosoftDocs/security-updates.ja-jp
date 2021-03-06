---
TOCTitle: 'MS15-DEC'
Title: 2015 年 12 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms15-dec'
ms:contentKeyID: 72045218
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms15-dec(v=Security.10)'
---

2015 年 12 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日:2015 年 12 月 9 日 | 最終更新日:2015 年 12 月 24 日

**バージョン:** 1.3

このセキュリティ情報の概要は 2015 年 12 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699422">MS15-124</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3116180)</strong> <br />
このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3104002">3104002</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699426">MS15-125</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3116184)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699421">MS15-126</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する JScript および VBScript 用の累積的なセキュリティ更新プログラム (3116178)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の VBScript スクリプト エンジンに存在する脆弱性を解決します。この中で比較的深刻な脆弱性が悪用されると、Internet Explorer を通じて脆弱性を悪用するように特別に細工された Web サイトを攻撃者がホストして (または侵害された Web サイトや、ユーザーが提供するコンテンツまたは広告を受け入れるかホストする Web サイトを利用して)、その Web サイトを表示するようにユーザーを誘導した場合、リモートでコードが実行される可能性があります。攻撃者は「初期化しても安全」と判断された ActiveX コントロールを、Internet Explorer レンダリング エンジンを使用するアプリケーションや Microsoft Office ドキュメントに埋め込み、ユーザーを特別に細工された Web サイトに誘導する可能性もあります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699414">MS15-127</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Windows DNS 用のセキュリティ更新プログラム (3100465)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、DNS サーバーに対して攻撃者が特別に細工された要求を送信した場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=690559">MS15-128</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3104503)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows、.NET Framework、Microsoft Office、Skype for Business、Microsoft Lync、および Silverlight の脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された文書を開いた場合や、特別に細工されたフォントが埋め込まれた Web ページを表示した場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3114351">3114351</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Office、<br />
Skype for Business、Microsoft Lync、<br />
Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=691214">MS15-129</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Silverlight 用のセキュリティ更新プログラム (3106614)</strong><br />
このセキュリティ更新プログラムは、Microsoft Silverlight の脆弱性を解決します。最も深刻な脆弱性では、読み取りおよび書き込みのアクセス違反を引き起こす可能性がある特定の &quot;開く&quot; および &quot;閉じる&quot; 要求を Microsoft Silverlight が不適切に処理した場合、リモートでコードが実行される可能性があります。攻撃者は、この脆弱性を悪用するために、特別に細工された Silverlight アプリケーションを含む Web サイトをホストし、侵害された Web サイトにアクセスするようユーザーを誘導する可能性があります。また、攻撃者は、ユーザーが提供したコンテンツや広告を受け入れるかホストする Web サイトを含む、特別に細工されたコンテンツが含まれる Web サイトを利用する可能性もあります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699420">MS15-130</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Uniscribe 用のセキュリティ更新プログラム (3108670)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、ユーザーが特別な細工がされた文書を開いた場合や、特別な細工がされたフォントが含まれる信頼されていない Web ページにアクセスした場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699410">MS15-131</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3116111)</strong><br />
このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699415">MS15-132</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Windows 用のセキュリティ更新プログラム (3116162)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性により、攻撃者がローカル システムにアクセスし、特別に細工されたアプリケーションを実行した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699413">MS15-133</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する Windows PGM 用のセキュリティ更新プログラム (3116130)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が標的のシステムにログインし、既に解放されているメモリ位置への参照を競合状態によって引き起こす特別に細工されたアプリケーションを実行した場合に、特権が昇格される可能性があります。システムで脆弱性を発生させるには、Microsoft メッセージ キュー (MSMQ) がインストールされていて、Windows Pragmatic General Multicast (PGM) プロトコルが明確に有効にされている必要があります。既定の構成では MSMQ は存在しません。MSMQ がインストールされている場合は PGM プロトコルを使用できますが、既定では無効になってます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=699419">MS15-134</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Windows Media Center 用のセキュリティ更新プログラム (3108669)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの中で比較的深刻な脆弱性では、Windows Media Center で悪意のあるコードを参照する特別に細工された Media Center リンク (.mcl) ファイルを開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=708239">MS15-135</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する Windows カーネル モード ドライバー用のセキュリティ更新プログラム (3119075)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性により、攻撃者が標的のシステムにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE の識別番号**

</td>
<td style="border:1px solid black;">
**脆弱性のタイトル**

</td>
<td style="border:1px solid black;">
**最新のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**過去のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**サービス拒否  
悪用可能性評価**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-124\] Internet Explorer 用の累積的なセキュリティ更新プログラム (3116180)**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6083](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6083)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6134](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6134)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6135)

</td>
<td style="border:1px solid black;">
スクリプト エンジンの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6136)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6138](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6138)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS フィルターのバイパスの脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6139](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6139)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6140](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6140)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6141](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6141)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6142](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6142)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6143](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6143)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6144](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6144)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの XSS フィルター バイパスの脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6145](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6145)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6146](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6146)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6147](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6147)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6148)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6149](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6149)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6150](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6150)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6151](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6151)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6152](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6152)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6153](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6153)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6154)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6155](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6155)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6156](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6156)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6157](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6157)

</td>
<td style="border:1px solid black;">
Internet Explorer の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6158](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6158)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6159](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6159)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6160](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6160)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6161](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6161)

</td>
<td style="border:1px solid black;">
Internet Explorer の ASLR のバイパス

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6162](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6162)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6164](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6164)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS フィルターのバイパスの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-125\] Microsoft Edge 用の累積的なセキュリティ更新プログラム (3116184)**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6139](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6139)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6140](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6140)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6142](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6142)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6148](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6148)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6151](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6151)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6153](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6153)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6154](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6154)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6155](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6155)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6158](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6158)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6159](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6159)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6161](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6161)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザー ASLR バイパス

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6168](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6168)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6169](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6169)

</td>
<td style="border:1px solid black;">
Microsoft Edge のなりすましの脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6170](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6170)

</td>
<td style="border:1px solid black;">
Microsoft Edge の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6176](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6176)

</td>
<td style="border:1px solid black;">
Microsoft Edge の XSS フィルター バイパスの脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-126\] リモートでのコード実行に対処する JScript および VBScript 用の累積的なセキュリティ更新プログラム (3116178)**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6135](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6135)

</td>
<td style="border:1px solid black;">
スクリプト エンジンの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6136](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6136)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-127\] リモートでのコード実行に対処する Microsoft Windows DNS 用のセキュリティ更新プログラム (3100465)**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6125](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6125)

</td>
<td style="border:1px solid black;">
Windows DNS の解放後使用の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-128\] リモートでのコード実行に対処する Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3104503)**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6106](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6106)

</td>
<td style="border:1px solid black;">
グラフィックス メモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6107](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6107)

</td>
<td style="border:1px solid black;">
グラフィックス メモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6108](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6108)

</td>
<td style="border:1px solid black;">
グラフィックス メモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-129\] リモートでのコード実行に対処する Silverlight 用のセキュリティ更新プログラム (3106614)**](https://go.microsoft.com/fwlink/?linkid=691214)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6114](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6114)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6165](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6165)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6166](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6166)

</td>
<td style="border:1px solid black;">
Microsoft Silverlight のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-130\] リモートでのコード実行に対処する Microsoft Uniscribe 用のセキュリティ更新プログラム (3108670)**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6130](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6130)

</td>
<td style="border:1px solid black;">
Windows の整数アンダーフローの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-131\] リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3116111)**](https://go.microsoft.com/fwlink/?linkid=699410)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6040](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6040)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6118](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6118)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6122](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6122)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6124](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6124)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6172](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6172)

</td>
<td style="border:1px solid black;">
Microsoft Office の RCE の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6177](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6177)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-132\] リモートでのコード実行に対処する Microsoft Windows 用のセキュリティ更新プログラム (3116162)**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6128](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6128)

</td>
<td style="border:1px solid black;">
Windows ライブラリの読み込みのリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6132](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6132)

</td>
<td style="border:1px solid black;">
Windows ライブラリの読み込みのリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6133](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6133)

</td>
<td style="border:1px solid black;">
Windows ライブラリの読み込みのリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-133\] 特権の昇格に対処する Windows PGM 用のセキュリティ更新プログラム (3116130)**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6126](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6126)

</td>
<td style="border:1px solid black;">
Windows PGM UAF の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-134\] 特権の昇格に対処する Windows PGM 用のセキュリティ更新プログラム (3116130)**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6127](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6127)

</td>
<td style="border:1px solid black;">
Windows Media Center の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6131](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6131)

</td>
<td style="border:1px solid black;">
Media Center のライブラリ解析 RCE の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS15-135\] 特権の昇格に対処する Windows カーネル モード ドライバー用のセキュリティ更新プログラム (3119075)**](https://go.microsoft.com/fwlink/?linkid=708239)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6171](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6171)

</td>
<td style="border:1px solid black;">
Windows カーネル メモリの特権の昇格に関する脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6173](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6173)

</td>
<td style="border:1px solid black;">
Windows カーネル メモリの特権の昇格に関する脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6174](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6174)

</td>
<td style="border:1px solid black;">
Windows カーネル メモリの特権の昇格に関する脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6175](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6175)

</td>
<td style="border:1px solid black;">
Windows カーネル メモリの特権の昇格に関する脆弱性

</td>
<td style="border:1px solid black;">
0- 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 

影響を受けるソフトウェア
------------------------

<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。

**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントを基に、インストールする必要がある更新プログラムを確認してください。

 

### Windows オペレーティング システムとコンポーネント (表 1/2)

 
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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(緊急)  
Internet Explorer 8  
(3104002)  
(緊急)  
Internet Explorer 9  
(3104002)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(緊急)  
Microsoft .NET Framework 4  
(3099866)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(緊急)  
Microsoft .NET Framework 4.6  
(3099874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(緊急)  
Internet Explorer 8  
(3104002)  
(緊急)  
Internet Explorer 9  
(3104002)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3105579)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(緊急)  
Microsoft .NET Framework 4  
(3099866)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(緊急)  
Microsoft .NET Framework 4.6  
(3099874)  
(緊急)

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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(警告)  
Internet Explorer 8  
(3104002)  
(警告)  
Internet Explorer 9  
(3104002)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3105579)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(緊急)  
Microsoft .NET Framework 4  
(3099866)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(緊急)  
Microsoft .NET Framework 4.6  
(3099874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(警告)  
Internet Explorer 8  
(3104002)  
(警告)  
Internet Explorer 9  
(3104002)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3105579)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(緊急)  
Microsoft .NET Framework 4  
(3099866)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(緊急)  
Microsoft .NET Framework 4.6  
(3099874)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3105579)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3109094)  
(緊急)

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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(緊急)  
Internet Explorer 9  
(3104002)  
(緊急)  
Internet Explorer 10  
(3104002)  
(緊急)  
Internet Explorer 11  
(3104002)  
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
Windows 7 for 32-bit Systems Service Pack 1  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(緊急)  
Internet Explorer 9  
(3104002)  
(緊急)  
Internet Explorer 10  
(3104002)  
(緊急)  
Internet Explorer 11  
(3104002)  
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
Windows 7 for x64-based Systems Service Pack 1  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(緊急)

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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(警告)  
Internet Explorer 9  
(3104002)  
(警告)  
Internet Explorer 10  
(3104002)  
(警告)  
Internet Explorer 11  
(3104002)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(警告)

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
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3109094)  
(緊急)

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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
Windows 8 for 32-bit Systems  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5  
(3099863)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
Windows 8 for x64-based Systems  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5  
(3099863)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
Windows 8.1 for 32-bit Systems  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5  
(3099864)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
Windows 8.1 for x64-based Systems  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5  
(3099864)  
(緊急)

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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5  
(3099863)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5  
(3099864)  
(緊急)

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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
Windows RT  
(3109094)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
Windows RT 8.1  
(3109094)  
(緊急)

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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116869)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116869)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3116869)  
(緊急)  
Microsoft .NET Framework 3.5  
(3116869)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116869)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116869)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3116869)  
(緊急)  
Microsoft .NET Framework 3.5  
(3116869)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116900)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116900)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3116900)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116900)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116900)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3116900)  
(緊急)

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
[**MS15-124**](https://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS15-125**](https://go.microsoft.com/fwlink/?linkid=699426)

</td>
<td style="border:1px solid black;">
[**MS15-126**](https://go.microsoft.com/fwlink/?linkid=699421)

</td>
<td style="border:1px solid black;">
[**MS15-127**](https://go.microsoft.com/fwlink/?linkid=699414)

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

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
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3105579)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3109094)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3105579)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3109094)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(3105578)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)

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
Windows Server 2012  
(Server Core インストール)  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5  
(3099863)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)

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
Windows Server 2012 R2  
(Server Core インストール)  
(3100465)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3109094)  
(緊急)  
Microsoft .NET Framework 3.5  
(3099864)  
(緊急)

</td>
</tr>
</table>
 
**MS15-128 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Windows オペレーティング システムとコンポーネント (表 2/2)

 
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
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2  
(3108371)  
(重要)  
Windows Vista Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109094)  
(重要)

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
Windows Vista x64 Edition Service Pack 2  
(3108371)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**

</td>
<td style="border:1px solid black;" colspan="3">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3108371)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3109094)  
(重要)

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
Windows Server 2008 for x64-based Systems Service Pack 2  
(3108371)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3109094)  
(重要)

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
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3108371)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3109103)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3109094)  
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
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3108670)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3108371)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3109103)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3108670)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3108371)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3109103)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3109094)  
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
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3108670)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3108371)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3108670)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3108371)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3109094)  
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
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 8 for 32-bit Systems  
(3108347)  
(重要)  
Windows 8 for 32-bit Systems  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3109094)  
(重要)

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
Windows 8 for x64-based Systems  
(3108347)  
(重要)  
Windows 8 for x64-based Systems  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3109094)  
(重要)

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
Windows 8.1 for 32-bit Systems  
(3108347)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3109094)  
(重要)

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
Windows 8.1 for x64-based Systems  
(3108347)  
(重要)  
Windows 8.1 for x64-based Systems  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3109094)  
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
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012  
(3108347)  
(重要)  
Windows Server 2012 R2  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109094)  
(重要)

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
Windows Server 2012 R2  
(3108347)  
(重要)  
Windows Server 2012  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109094)  
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
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT  
(3108347)  
(重要)  
Windows RT  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(3109094)  
(重要)

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
Windows RT 8.1  
(3108347)  
(重要)  
Windows RT 8.1  
(3108381)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3109094)  
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
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3116869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3116869)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3116869)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3116869)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3116869)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3116869)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3116900)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3116900)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3116900)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3116900)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3116900)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3116900)  
(重要)

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
[**MS15-130**](https://go.microsoft.com/fwlink/?linkid=699420)

</td>
<td style="border:1px solid black;">
[**MS15-132**](https://go.microsoft.com/fwlink/?linkid=699415)

</td>
<td style="border:1px solid black;">
[**MS15-133**](https://go.microsoft.com/fwlink/?linkid=699413)

</td>
<td style="border:1px solid black;">
[**MS15-134**](https://go.microsoft.com/fwlink/?linkid=699419)

</td>
<td style="border:1px solid black;">
[**MS15-135**](https://go.microsoft.com/fwlink/?linkid=708239)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3108670)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3108347)  
(重要)  
Windows Server 2012  
(Server Core インストール)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3109094)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3108347)  
(重要)  
Windows Server 2012 R2  
(Server Core インストール)  
(3108381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3109103)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3109094)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office スイートおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://go.microsoft.com/fwlink/?linkid=699410)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085616)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085549)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(3114422)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3114458)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://go.microsoft.com/fwlink/?linkid=699410)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3085612)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3085528)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3114403)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3114415)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3101532)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3085612)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3085528)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3114403)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3114415)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3101532)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://go.microsoft.com/fwlink/?linkid=699410)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3114342)  
(緊急)

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
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3114342)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://go.microsoft.com/fwlink/?linkid=699410)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (32 ビット版)  
(3114382)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (64 ビット版)  
(3114382)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://go.microsoft.com/fwlink/?linkid=699410)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Word 2013 RT Service Pack 1  
(3114342)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://go.microsoft.com/fwlink/?linkid=699410)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Microsoft Excel for Mac 2011  
(3119517)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3119518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**その他の Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
<td style="border:1px solid black;">
[**MS15-131**](https://go.microsoft.com/fwlink/?linkid=699410)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3114457)  
(緊急)  
Microsoft Office 互換機能パック Service Pack 3  
(3114431)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114433)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114478)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
**MS15-128 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft コミュニケーション プラットフォームおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007 Console**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(3115875)  
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
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)  
(3115871)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)  
(3115871)  
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
(3115872)  
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
(3115873)  
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
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)  
(3114351)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)  
(Skype for Business Basic)  
(3114351)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)  
(Skype for Business)  
(3114351)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)  
(Skype for Business Basic)  
(3114351)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Skype for Business 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (32 ビット)

</td>
<td style="border:1px solid black;">
Skype for Business 2016 (32 ビット)  
(3114372)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32 ビット)

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32 ビット)  
(3114372)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (64 ビット)

</td>
<td style="border:1px solid black;">
Skype for Business 2016 (64 ビット)  
(3114372)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64 ビット)

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64 ビット)  
(3114372)  
(緊急)

</td>
</tr>
</table>
 
**MS15-128 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft 開発者用ツールおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-128**](https://go.microsoft.com/fwlink/?linkid=690559)

</td>
<td style="border:1px solid black;">
[**MS15-129**](https://go.microsoft.com/fwlink/?linkid=691214)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5  
(3106614)  
(緊急)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(3106614)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(3106614)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(緊急)

</td>
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5  
(3106614)  
(緊急)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(3106614)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(3106614)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3106614)  
(緊急)

</td>
</tr>
</table>
 
**MS15-128 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールの詳細については、「[セキュリティ ツール](https://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。

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
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージを Microsoft ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/ja-jp/kb/913086) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ja)

国ごとのローカル サポート: [インターナショナル サポート](https://support.microsoft.com/common/international.aspx?ln=ja)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation およびその関連会社は、本文書に含まれている情報の使用および使用結果につき、正確性、真実性など、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社およびこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2015/12/09): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2015/12/11): このセキュリティ情報の概要ページを更新し、CVE-2015-6124 の悪用可能性評価を修正しました。これは情報のみの変更です。
-   V1.2 (2015/12/17): このセキュリティ情報の概要ページを更新し、概要の表に既知の問題 3104002 を追加しました。この問題を解決するために、修正プログラム 3125446 をインストールしてください。詳細については、[サポート技術情報 3104002](https://support.microsoft.com/ja-jp/kb/3104002)を参照してください。
-   V1.3 (2015/12/24): このセキュリティ情報の概要ページを更新し、MS15-128 の概要の表に既知の問題の参照を追加しました。この問題は、Lync 2013 用の更新プログラム 3114351 をインストール後、Skype 2015 for Business の会議録音のビデオが行方不明になるという問題に関係します。詳細については、[サポート技術情報 3114351](https://support.microsoft.com/ja-jp/kb/3114351)を参照してください。

*Page generated 2015-12-23 12:34-08:00.*
