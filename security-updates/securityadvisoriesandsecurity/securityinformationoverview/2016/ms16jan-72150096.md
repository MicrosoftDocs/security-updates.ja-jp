---
TOCTitle: 'MS16-JAN'
Title: 2016 年 1 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms16-jan'
ms:contentKeyID: 72150096
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms16-jan(v=Security.10)'
---

2016 年 1 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日: 2016 年 1 月 13 日 | 最終更新日: 2016 年 2 月 22 日

**バージョン:** 1.3

このセキュリティ情報の概要は 2016 年 1 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムと共に、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「**関連情報**」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「**影響を受けるソフトウェア**」を参照してください。

<table style="width:100%;">
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717999">MS16-001</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3124903)</strong> <br />
このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。より深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしているときに、攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピューターが制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718002">MS16-002</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3124904)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。これらの脆弱性により、ユーザーが Microsoft Edge を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718004">MS16-003</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する JScript および VBScript 用の累積的なセキュリティ更新プログラム (3125540)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の VBScript スクリプト エンジンに存在する脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web サイトにアクセスすると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしているときに、攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピューターが制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717998">MS16-004</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3124585)</strong><br />
このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3114503">3114503</a><br />
<a href="https://support.microsoft.com/kb/2920727">2920727</a><br />
<a href="https://support.microsoft.com/kb/2881029">2881029</a><br />
<a href="https://support.microsoft.com/kb/2881067">2881067</a><br />
<a href="https://support.microsoft.com/kb/3039794">3039794</a><br />
<a href="https://support.microsoft.com/kb/3124585">3124585</a></td>
<td style="border:1px solid black;">Microsoft Office、<br />
Visual Basic</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718001">MS16-005</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3124584)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの中で比較的深刻な脆弱性では、ユーザーが悪意のある Web サイトにアクセスすると、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717994">MS16-006</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Silverlight 用のセキュリティ更新プログラム (3126036)</strong><br />
このセキュリティ更新プログラムは、Microsoft Silverlight の脆弱性を解決します。この脆弱性により、特別な細工がされた Silverlight アプリケーションが含まれる侵害された Web サイトをユーザーが訪問した場合、リモートでコードが実行される可能性があります。攻撃者は、侵害された Web サイトにユーザーを強制的に訪問させることはできません。その代わり、通常、ユーザーを攻撃者の Web サイトに接続させる電子メールまたはインスタント メッセージ内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718006">MS16-007</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Windows 用のセキュリティ更新プログラム (3124901)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この中で最も深刻な脆弱性では、攻撃者が標的とするシステムにログオンし、特別に細工したアプリケーションを実行できる場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3124266">3124266</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3124263">3124263</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718007">MS16-008</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する Windows カーネル用のセキュリティ更新プログラム (3124605)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性により、攻撃者が影響を受けるシステムにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=717997">MS16-010</a></td>
<td style="border:1px solid black;"><strong>なりすましに対処する Microsoft Exchange Server 用のセキュリティ更新プログラム (3124557)</strong><br />
このセキュリティ更新プログラムは、Microsoft Exchange Server に存在する脆弱性を解決します。この中で最も深刻な脆弱性では、Outlook Web Access (OWA) が Web 要求を適切に処理せず、ユーザー入力と電子メール コンテンツをサニタイズしない場合に、なりすましが行われる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
なりすまし</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
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

 
<table style="border:1px solid black;">
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
[**MS16-001:Internet Explorer 用の累積的なセキュリティ更新プログラム (3124903)**](http://go.microsoft.com/fwlink/?linkid=717999)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0002](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0002)

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
[CVE-2016-0005](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0005)

</td>
<td style="border:1px solid black;">
Internet Explorer 特権の昇格の脆弱性

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
[**MS16-002:Microsoft Edge 用の累積的なセキュリティ更新プログラム (3124904)**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0003](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0003)

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
[CVE-2016-0024](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0024)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

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
<td style="border:1px solid black;" colspan="5">
[**MS16-003:リモートでのコード実行に対処する JScript および VBScript 用の累積的なセキュリティ更新プログラム (3125540)**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0002](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0002)

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
[**MS16-004:リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3124585)**](http://go.microsoft.com/fwlink/?linkid=717998)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6117)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint のセキュリティ機能のバイパスの脆弱性

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
<td style="border:1px solid black;">
[CVE-2016-0010](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0010)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

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
[CVE-2016-0011](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0011)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint のセキュリティ機能のバイパスの脆弱性

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
[CVE-2016-0012](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0012)

</td>
<td style="border:1px solid black;">
Microsoft Office ASLR バイパス

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
[CVE-2016-0035](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0035)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-005:特権の昇格に対処する Windows カーネル モード ドライバー用のセキュリティ更新プログラム (3124584)**](http://go.microsoft.com/fwlink/?linkid=718001)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0008](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0008)

</td>
<td style="border:1px solid black;">
Windows GDI32.dll ASLR バイパスの脆弱性

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
[CVE-2016-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0009)

</td>
<td style="border:1px solid black;">
Win32k のリモート コードが実行される脆弱性

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
[**MS16-006:リモートでのコード実行に対処する Silverlight 用のセキュリティ更新プログラム (3126036)**](http://go.microsoft.com/fwlink/?linkid=717994)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0034](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0034)

</td>
<td style="border:1px solid black;">
Silverlight ランタイムのリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
0- 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
0- 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-007:リモートでのコード実行に対処する Microsoft Windows 用のセキュリティ更新プログラム (3124901)**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0014)

</td>
<td style="border:1px solid black;">
DLL 読み込みの特権の昇格の脆弱性

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
[CVE-2016-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0015)

</td>
<td style="border:1px solid black;">
DirectShow のヒープ破損のリモートでコードが実行される脆弱性

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
[CVE-2016-0016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0016)

</td>
<td style="border:1px solid black;">
DLL 読み込みのリモート コード実行の脆弱性

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
[CVE-2016-0018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0018)

</td>
<td style="border:1px solid black;">
DLL 読み込みのリモート コード実行の脆弱性

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
[CVE-2016-0019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0019)

</td>
<td style="border:1px solid black;">
Windows リモート デスクトップ プロトコルのセキュリティ バイパスの脆弱性

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
[CVE-2016-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0020)

</td>
<td style="border:1px solid black;">
MAPI DLL 読み込みの特権の昇格の脆弱性

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
[**MS16-008:特権の昇格に対処する Windows カーネル用のセキュリティ更新プログラム (3124605)**](http://go.microsoft.com/fwlink/?linkid=718007)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0006](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0006)

</td>
<td style="border:1px solid black;">
Windows マウント ポイントの特権の昇格の脆弱性

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
[CVE-2016-0007](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0007)

</td>
<td style="border:1px solid black;">
Windows マウント ポイントの特権の昇格の脆弱性

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
[**MS16-010:なりすましに対処する Microsoft Exchange Server 用のセキュリティ更新プログラム (3124557)**](http://go.microsoft.com/fwlink/?linkid=717997)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0029)

</td>
<td style="border:1px solid black;">
Exchange のなりすましの脆弱性

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
[CVE-2016-0030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0030)

</td>
<td style="border:1px solid black;">
Exchange のなりすましの脆弱性

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
[CVE-2016-0031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0031)

</td>
<td style="border:1px solid black;">
Exchange のなりすましの脆弱性

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
[CVE-2016-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0032)

</td>
<td style="border:1px solid black;">
Exchange のなりすましの脆弱性

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
</table>
 

影響を受けるソフトウェア
------------------------

<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。

**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントを基に、インストールする必要がある更新プログラムを確認してください。

 

### Windows オペレーティング システムとコンポーネント (表 1/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=717999)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140) 

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
Internet Explorer 8  
(3124275)  
(緊急)  
Internet Explorer 9  
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3124624)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3124000)  
(緊急)  
Windows Vista Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(緊急)  
Internet Explorer 9  
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3124624)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3124000)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(警告)  
Internet Explorer 9  
(3124275)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3124624)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3124000)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(警告)  
Internet Explorer 9  
(3124275)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3124624)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3124000)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3124001)  
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
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3124624)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3124000)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
**なし**

</td>
<td style="border:1px solid black;">
**なし**

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
Internet Explorer 8  
(3124275)  
(緊急)  
Internet Explorer 9  
(3124275)  
(緊急)  
Internet Explorer 10  
(3124275)  
(緊急)  
Internet Explorer 11  
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3124000)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(緊急)  
Internet Explorer 9  
(3124275)  
(緊急)  
Internet Explorer 10  
(3124275)  
(緊急)  
Internet Explorer 11  
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3124000)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(警告)  
Internet Explorer 9  
(3124275)  
(警告)  
Internet Explorer 10  
(3124275)  
(警告)  
Internet Explorer 11  
(3124275)  
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
(3124000)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3124275)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3124000)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
**なし**

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
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
**なし**

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
(3124275)  
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
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
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
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
**なし**

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
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124275)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3124001)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124266)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124266)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3124266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124266)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124266)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3124266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124263)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124263)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3124263)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3124263)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3124263)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3124263)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-001**](http://go.microsoft.com/fwlink/?linkid=699422)

</td>
<td style="border:1px solid black;">
[**MS16-002**](http://go.microsoft.com/fwlink/?linkid=718002)

</td>
<td style="border:1px solid black;">
[**MS16-003**](http://go.microsoft.com/fwlink/?linkid=718004)

</td>
<td style="border:1px solid black;">
[**MS16-005**](http://go.microsoft.com/fwlink/?linkid=718001)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3124624)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3124000)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3124001)  
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
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3124624)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3124000)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3124001)  
(重要)

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
(3124625)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3124000)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3124001)  
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
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3124001)  
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
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3124001)  
(重要)

</td>
</tr>
</table>
 
 

### Windows オペレーティング システムとコンポーネント (表 2/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3121918)  
(重要)  
Windows Vista Service Pack 2  
(3109560)  
(重要)  
Windows Vista Service Pack 2  
(3110329)  
(重要)  
Windows Vista Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3121918)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3109560)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3110329)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3121918)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3109560)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3110329)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3121918)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3109560)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3110329)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3121918)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3109560)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3110329)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3121918)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3109560)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3110329)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3121461)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3121918)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3109560)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3110329)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3121461)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3121918)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3109560)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3110329)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3121918)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3109560)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3110329)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3108664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3121918)  
(重要)  
Windows 8 for 32-bit Systems  
(3109560)  
(重要)  
Windows 8 for 32-bit Systems  
(3110329)  
(重要)  
Windows 8 for 32-bit Systems  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3121918)  
(重要)  
Windows 8 for x64-based Systems  
(3109560)  
(重要)  
Windows 8 for x64-based Systems  
(3110329)  
(重要)  
Windows 8 for x64-based Systems  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3121918)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3109560)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3110329)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3121918)  
(重要)  
Windows 8.1 for x64-based Systems  
(3109560)  
(重要)  
Windows 8.1 for x64-based Systems  
(3110329)  
(重要)  
Windows 8.1 for x64-based Systems  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3121918)  
(重要)  
Windows Server 2012  
(3109560)  
(重要)  
Windows Server 2012  
(3110329)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3121918)  
(重要)  
Windows Server 2012 R2  
(3109560)  
(重要)  
Windows Server 2012 R2  
(3110329)  
(重要)  
Windows Server 2012 R2  
(3121461)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3121918)  
(重要)  
Windows RT  
(3110329)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3121918)  
(重要)  
Windows RT 8.1  
(3110329)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3124266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3124266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3124266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3124266)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3124263)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3124263)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3124263)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3124263)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-007**](http://go.microsoft.com/fwlink/?linkid=718006)

</td>
<td style="border:1px solid black;">
[**MS16-008**](http://go.microsoft.com/fwlink/?linkid=718007)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3121212)  
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
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3121212)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3121918)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3121212)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office スイートおよびソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2881067)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(3114541)  
(緊急)  
Microsoft Excel 2007 Service Pack 3  
(3114540)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(3114429)  
(重要)  
Microsoft Visio 2007 Service Pack 3  
(3114421)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3114549)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

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
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2881029)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3114553)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3114554)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3114564)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 ビット版)  
(3114396)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (32 ビット版)  
(3114402)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3114557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3114553)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3114554)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3114564)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3114564)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 ビット版)  
(3114396)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (64 ビット版)  
(3114402)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3114557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

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
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3039794)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3114486)  
(緊急)  
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3114504)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 ビット版)  
(3114482)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (32 ビット版)  
(3114489)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3114494)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3114486)  
(緊急)  
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3114504)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 ビット版)  
(3114482)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (64 ビット版)  
(3114489)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3114494)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3114486)  
(緊急)  
Microsoft Excel 2013 RT Service Pack 1  
(3114504)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3114482)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3114494)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

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
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)  
(2920727)  
(重要)  
Microsoft Office 2016 (32 ビット版)  
(3114527)  
(緊急)  
Microsoft Excel 2016 (32 ビット版)  
(3114520)  
(重要)  
Microsoft PowerPoint 2016 (32 ビット版)  
(3114518)  
(重要)  
Microsoft Visio 2016 (32 ビット版)  
(3114511)  
(重要)  
Microsoft Word 2016 (32 ビット版)  
(3114526)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)  
(3114527)  
(緊急)  
Microsoft Office 2016 (64 ビット版)  
(3114520)  
(重要)  
Microsoft Excel 2016 (64 ビット版)  
(3114520)  
(重要)  
Microsoft PowerPoint 2016 (64 ビット版)  
(3114518)  
(重要)  
Microsoft Visio 2016 (64 ビット版)  
(3114511)  
(重要)  
Microsoft Word 2016 (64 ビット版)  
(3114526)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3133699)  
(緊急)  
Microsoft PowerPoint for Mac 2011  
(3133699)  
(緊急)  
Microsoft Word for Mac 2011  
(3133699)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3133711)  
(緊急)  
Microsoft PowerPoint 2016 for Mac  
(3133711)  
(緊急)  
Microsoft Word 2016 for Mac  
(3133711)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**その他の Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

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
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(3114546)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114547)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114569)  
(緊急)

</td>
</tr>
</table>
 
**MS16-004 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft 開発者用ツールおよびソフトウェア

 
<table style="border:1px solid black;">
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
[**MS16-006**](http://go.microsoft.com/fwlink/?linkid=717994)

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
(3126036)  
(緊急)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(3126036)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(3126036)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3126036)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(3126036)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3126036)  
(緊急)

</td>
</tr>
</table>
 
 

### Microsoft サーバー ソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3114503)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3114503)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3124557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 10  
(3124557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 11  
(3124557)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

</td>
<td style="border:1px solid black;">
[**MS16-010**](http://go.microsoft.com/fwlink/?linkid=717997)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016  
(3124557)  
(重要)

</td>
</tr>
</table>
 
**MS16-004 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft Visual Basic ソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Basic 6.0 ランタイム**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-004**](http://go.microsoft.com/fwlink/?linkid=717998)

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
Visual Basic 6.0 ランタイム

</td>
<td style="border:1px solid black;">
Visual Basic 6.0 ランタイム  
(3096896)  
(重要)

</td>
</tr>
</table>
 
**MS16-004 に関する注意事項**

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

-   V1.0 (2016/01/13): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2016/01/14): CVE-2016-0034 の悪用可能性指標を訂正しました。これは情報のみの変更です。
-   V1.2 (2016/01/20): 概要の表の MS16-004 に、既知の問題の参照を追加しました。詳細は、[サポート技術情報 3114503](https://support.microsoft.com/kb/3114503) を参照してください。
-   V1.3 (2016/02/22): MS16-001 に関して、Internet Explorer 7 用の更新プログラム 3124275 を影響を受けるソフトウェアの表から削除しました。これは、Internet Explorer 7 はこのセキュリティ情報で説明されている脆弱性の影響を受けないためです。詳細は、[サポート技術情報 3124275](https://support.microsoft.com/en-us/kb/3124275) を参照してください。概要の表の MS16-004 に、既知の問題の参照を追加しました。詳細は、以下のサポート技術情報を参照してください。
    -   [サポート技術情報 2920727](https://support.microsoft.com/kb/2920727)
    -   [サポート技術情報 2881029](https://support.microsoft.com/kb/2881029)
    -   [サポート技術情報 2881067](https://support.microsoft.com/en-us/kb/2881067)
    -   [サポート技術情報 3039794](https://support.microsoft.com/en-us/kb/3039794)
    -   [サポート技術情報 3124585](https://support.microsoft.com/en-us/kb/3124585)

*Page generated 2016-02-19 14:41-08:00.*
