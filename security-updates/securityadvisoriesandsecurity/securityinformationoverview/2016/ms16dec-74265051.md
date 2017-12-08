---
TOCTitle: 'MS16-DEC'
Title: 2016 年 12 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms16-dec'
ms:contentKeyID: 74265051
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms16-dec(v=Security.10)'
---

2016 年 12 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日: 2016 年 12 月 14 日 | 最終更新日: 2016 年 12 月 22 日

**バージョン:** 1.2

このセキュリティ情報の概要は 2016 年 12 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定するときに役立つ情報も提供します。「**関連情報**」の欄を参照してください。

**注:** 既にお知らせしたように、2017 年 2 月から、セキュリティ更新プログラムの情報は、セキュリティ情報サイトではなく、[セキュリティ更新プログラム ガイド](https://portal.msrc.microsoft.com/ja-jp/security-guidance)で公開されます。詳細については、ブログ記事「[セキュリティ更新プログラムに対するコミットメントの促進について](https://blogs.technet.microsoft.com/msrc/2016/11/08/furthering-our-commitment-to-security-updates/)」を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次の「**影響を受けるソフトウェア**」のセクションを参照してください。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834441">MS16-144</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3204059)</strong><br />
このセキュリティ更新プログラムは、Microsoft Uniscribe の脆弱性を解決します。この脆弱性が悪用された場合、ユーザーが特別に細工された Web サイトにアクセス、または特別に細工された文書を開いた場合に、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834442">MS16-145</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3204062)</strong><br />
このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限を持つユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834444">MS16-146</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3204066)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web サイトにアクセス、または特別に細工された文書を開いた場合に、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834947">MS16-147</a></td>
<td style="border:1px solid black;"><strong>Microsoft Uniscribe 用のセキュリティ更新プログラム (3204063)</strong><br />
このセキュリティ更新プログラムは、Windows Uniscribe の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web サイトにアクセス、または特別に細工された文書を開いた場合に、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834445">MS16-148</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用のセキュリティ更新プログラム (3204068)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。最も深刻な脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834964">MS16-149</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 用のセキュリティ更新プログラム (3205655)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性のうち、比較的深刻な脆弱性が悪用された場合、ローカルで認証された攻撃者が特別に細工されたアプリケーションを実行した場合に、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834939">MS16-150</a></td>
<td style="border:1px solid black;"><strong>保護カーネル モード用のセキュリティ更新プログラム (3205642)<br />
</strong>このセキュリティ更新プログラムは Microsoft Windows の脆弱性を解決します。この脆弱性により、標的のシステム上でローカルで認証された攻撃者が特別に細工されたアプリケーションを実行した場合、特権の昇格が起こる可能性があります。この脆弱性の悪用に成功した攻撃者が仮想信頼レベル (VTL) に違反する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834956">MS16-151</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3205651)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。攻撃者が影響を受けるシステムにログオンし、その脆弱性を悪用するように特別に細工されたアプリケーションを実行して影響を受けるシステムを完全に制御した場合に、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834960">MS16-152</a></td>
<td style="border:1px solid black;"><strong>Windows カーネル用のセキュリティ更新プログラム (3199709)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。Windows カーネルがメモリ内のオブジェクトを適切に処理しない場合に情報漏えいの脆弱性が存在します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=835768">MS16-153</a></td>
<td style="border:1px solid black;"><strong>共通ログ ファイル システム ドライバーのセキュリティ更新プログラム (3207328)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。Windows 共通ログ ファイル システム (CLFS) ドライバーがメモリ内のオブジェクトを不適切に処理した場合、この脆弱性によって情報漏えいが起こる可能性があります。ローカル攻撃のシナリオでは、攻撃者は、特別に細工したアプリケーションを実行してこの脆弱性を悪用し、影響を受けるシステムのセキュリティ対策を回避してさらに脆弱性を悪用する可能性があります。この脆弱性の悪用に成功した攻撃者が、昇格されたコンテキストでプロセスを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834443">MS16-154</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (3209498)<br />
</strong>このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10、および Windows Server 2016 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=834937">MS16-155</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 用のセキュリティ更新プログラム (3205640)<br />
</strong>このセキュリティ更新プログラムは、SQL サーバー用の Microsoft .NET 4.6.2 Framework のデータ プロバイダーの脆弱性を解決します。Microsoft .NET Framework 4.6.2 には、攻撃者に <a href="https://technet.microsoft.com/library/security/dn848375.aspx">Always Encrypted</a> 機能で保護されている情報へのアクセスを可能にするセキュリティ上の脆弱性が存在します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3210137">3210137</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3210138">3210138</a></td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報 ID、CVE 番号の順でリストされています。掲示板での重要度評価が緊急または重要である脆弱性のみが含まれています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、「[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259)」を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE 番号**                    

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
[**MS16-144: Internet Explorer 用の累積的なセキュリティ更新プログラム (3204059)**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7202)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7278](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7278)

</td>
<td style="border:1px solid black;">
Windows のハイパーリンク オブジェクト ライブラリの情報漏えいの脆弱性

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
[CVE-2016-7279](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7279)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7281)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのセキュリティ機能のバイパスの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7282)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7283](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-cve-2016-7283)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7284](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7284)

</td>
<td style="border:1px solid black;">
Internet Explorer の情報漏えいの脆弱性

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
[CVE-2016-7287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7287)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

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
[**MS16-145: Microsoft Edge 用の累積的なセキュリティ更新プログラム (3204062)**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7181](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7181)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

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
[CVE-2016-7206](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7206)

</td>
<td style="border:1px solid black;">
Microsoft Edge の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

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
[CVE-2016-7279](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7279)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7280](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7280)

</td>
<td style="border:1px solid black;">
Microsoft Edge の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

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
[CVE-2016-7281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7281)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのセキュリティ機能のバイパス

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

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
[CVE-2016-7282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7282)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

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
[CVE-2016-7286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7286)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

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
[CVE-2016-7287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7287)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

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
[CVE-2016-7288](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7288)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

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
[CVE-2016-7296](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7296)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

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
[CVE-2016-7297](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7297)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

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
[**MS16-146: Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3204066)**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7257)

</td>
<td style="border:1px solid black;">
GDI の情報漏えいの脆弱性

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
[CVE-2016-7272](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7272)

</td>
<td style="border:1px solid black;">
Windows Graphics のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7273](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7273)

</td>
<td style="border:1px solid black;">
Windows Graphics のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-147: Microsoft Uniscribe 用のセキュリティ更新プログラム (3204063)**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7274)

</td>
<td style="border:1px solid black;">
Windows Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-148: Microsoft Office 用のセキュリティ更新プログラム (3204068)**](https://go.microsoft.com/fwlink/?linkid=834445)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7257)

</td>
<td style="border:1px solid black;">
GDI の情報漏えいの脆弱性

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
[CVE-2016-7262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7262)

</td>
<td style="border:1px solid black;">
Microsoft Office のセキュリティ機能のバイパスの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7263)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7264)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

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
[CVE-2016-7265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7265)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

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
[CVE-2016-7266](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7266)

</td>
<td style="border:1px solid black;">
Microsoft Office のセキュリティ機能のバイパスの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7267](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7267)

</td>
<td style="border:1px solid black;">
Microsoft Office のセキュリティ機能のバイパスの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7268](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7268)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

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
[CVE-2016-7274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7274)

</td>
<td style="border:1px solid black;">
Windows Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7275](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7275)

</td>
<td style="border:1px solid black;">
Microsoft Office OLE DLL のサイド ローディングの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7276](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7276)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

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
[CVE-2016-7277](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7277)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

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
[CVE-2016-7289](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7289)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7290](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7290)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7291](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7291)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7300](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7300)

</td>
<td style="border:1px solid black;">
Microsoft Office の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-149: Microsoft Windows 用のセキュリティ更新プログラム (3205655)**](https://go.microsoft.com/fwlink/?linkid=834964)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7219](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7219)

</td>
<td style="border:1px solid black;">
Windows Crypto Driver の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7292](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7292)

</td>
<td style="border:1px solid black;">
Windows インストーラーの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-150: 保護カーネル モード用のセキュリティ更新プログラム (3205642)**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7271](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7271)

</td>
<td style="border:1px solid black;">
保護カーネル モードの特権の昇格の脆弱性

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
[**MS16-151: Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3205651)**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7259)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7260)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

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
[**MS16-152: Windows カーネル用のセキュリティ更新プログラム (3199709)**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7258](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7258)

</td>
<td style="border:1px solid black;">
Windows カーネル メモリ アドレスの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-153: 共通ログ ファイル システム ドライバーのセキュリティ更新プログラム (3207328)**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7295](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7295)

</td>
<td style="border:1px solid black;">
Windows 共通ログ ファイル システム ドライバーの情報漏えいの脆弱性

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
[**MS16-154: Adobe Flash Player のセキュリティ更新プログラム (3202790)**](https://go.microsoft.com/fwlink/?linkid=834443)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-39](http://helpx.adobe.com/jp/security/products/flash-player/apsb16-39.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度と更新プログラムの優先度の評価については、Adobe Security Bulletin [APSB16-39](http://helpx.adobe.com/jp/security/products/flash-player/apsb16-39.html) を参照してください。

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-155: .NET Framework 用のセキュリティ更新プログラム (3205640)**](https://go.microsoft.com/fwlink/?linkid=834937)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-7270](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-7270)

</td>
<td style="border:1px solid black;">
.NET Framework の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

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

**注**:1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報 ID の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。

### Windows オペレーティング システムとコンポーネント (表 1/2)

 
<table style="border:1px solid black;">
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
(緊急)  
Microsoft Windows ハイパーリンク オブジェクト ライブラリ  
(3208481)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3204724)  
(重要)  
Windows Vista Service Pack 2  
(3205638)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3196348)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3204808)  
(重要)  
Windows Vista Service Pack 2  
(3196726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
(緊急)  
Microsoft Windows ハイパーリンク オブジェクト ライブラリ  
(3208481)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3204724)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3205638)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3196348)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3204808)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3196726)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
(警告)  
Microsoft Windows ハイパーリンク オブジェクト ライブラリ  
(3208481)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3204724)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3205638)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3196348)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3204808)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3196726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9   
(3203621)  
(警告)  
Microsoft Windows ハイパーリンク オブジェクト ライブラリ  
(3208481)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3204724)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3205638)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3196348)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3204808)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3196726)  
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
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3204724)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3205638)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3196348)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3204808)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3196726)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外                   

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3205394)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3207752)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3207752)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205394)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3207752)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3207752)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3207752)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205400)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205401)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205400)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205401)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3205408)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3205409)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205400)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205383)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205383)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3205383)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3205383)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3205383)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205383)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205383)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3205383)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3205383)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3205383)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205386)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205386)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3205386)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3205386)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3205386)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3205386)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3205386)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3205386)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3205386)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3205386)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3206632)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3206632)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3206632)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3206632)  
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
[**MS16-144**](https://go.microsoft.com/fwlink/?linkid=834441)

</td>
<td style="border:1px solid black;">
[**MS16-145**](https://go.microsoft.com/fwlink/?linkid=834442)

</td>
<td style="border:1px solid black;">
[**MS16-146**](https://go.microsoft.com/fwlink/?linkid=834444)

</td>
<td style="border:1px solid black;">
[**MS16-147**](https://go.microsoft.com/fwlink/?linkid=834947)

</td>
<td style="border:1px solid black;">
[**MS16-149**](https://go.microsoft.com/fwlink/?linkid=834964)

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
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3204724)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3205638)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3196348)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3204808)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3196726)  
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
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3204724)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3205638)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3196348)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3204808)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3196726)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3205394)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3205394)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3207752)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3207752)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3205408)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3205408)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3205408)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3205409)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3205409)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3205409)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205400)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205400)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205401)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205401)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(3206632)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(3206632)  
(重要)

</td>
</tr>
</table>
 
### Windows オペレーティング システムとコンポーネント (表 2/2)

 
<table style="border:1px solid black;">
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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3203838)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3203838)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3203838)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3203838)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3203838)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外                   

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205408)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3205409)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
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
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3205383)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3205386)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3209498)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core インストール**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-150**](https://go.microsoft.com/fwlink/?linkid=834939)

</td>
<td style="border:1px solid black;">
[**MS16-151**](https://go.microsoft.com/fwlink/?linkid=834956)

</td>
<td style="border:1px solid black;">
[**MS16-152**](https://go.microsoft.com/fwlink/?linkid=834960)

</td>
<td style="border:1px solid black;">
[**MS16-153**](https://go.microsoft.com/fwlink/?linkid=835768)

</td>
<td style="border:1px solid black;">
[**MS16-154**](https://go.microsoft.com/fwlink/?linkid=834443)

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
**なし**

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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3203838)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3204723)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3203838)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3205394)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3207752)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3205408)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3205409)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205400)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3205401)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(3206632)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
 

### Microsoft .NET Framework – セキュリティのみのリリース

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7 および Windows Server 2008 R2  
Microsoft .NET Framework 4.6.2 の更新プログラム (KB3205406)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204801)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**Important**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 10 Version 1607 for 32-bit Systems  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2016 for x64-based Systems  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204805)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204801)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(3204802)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
</table>
 
**MS16-155 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft .NET Framework – 月例のロールアップ リリース

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft .NET Framework**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Vista および Windows Server 2008 R2  
Microsoft .NET Framework 2.0、4.5.2、4.6 用の更新プログラム (KB3210142)**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Vista for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210129)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210139)  
(重要)  
Microsoft .NET Framework 4.6  
(3210136)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210129)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210139)  
(重要)  
Microsoft .NET Framework 4.6  
(3210136)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210129)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210139)  
(重要)  
Microsoft .NET Framework 4.6  
(3210136)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210129)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210139)  
(重要)  
Microsoft .NET Framework 4.6  
(3210136)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7 および Windows Server 2008 R2  
Microsoft .NET Framework 3.5.1、4.5.2、4.6/4.6.1、4.6.2 用の更新プログラム (KB3205402)**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210131)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210139)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210136)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210131)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210139)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210136)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210131)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210139)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210136)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210131)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012  
Microsoft .NET Framework 3.5、4.5.2、4.6/4.6.1、4.6.2 用の更新プログラム (KB3205403)**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210130)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210138)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210133)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205377)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1 and Windows Server 2012 R2  
Microsoft .NET Framework 3.5、4.5.2、4.6/4.6.1、4.6.2 用の更新プログラム (KB3205404)**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210132)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210137)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210135)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205378)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210132)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210137)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210135)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205378)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210132)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210137)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210135)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205378)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows 10 Version 1607 for 32-bit Systems  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2016 for x64-based Systems  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-155**](https://go.microsoft.com/fwlink/?linkid=834937)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210131)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210136)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205379)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210130)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210138)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210133)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205377)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3210132)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3210137)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3210135)  
(重要)  
Microsoft .NET Framework 4.6.2  
(3205378)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems (Server Core インストール)  
(3206632)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6.2  
(重要)

</td>
</tr>
</table>
 
**MS16-155 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Excel 2007 Service Pack 3  
(3128019)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3128025)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2883033)  
(緊急)  
Microsoft Office 2007 Service Pack 3  
(3128020)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128032)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3118380)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2889841)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3128037)  
(重要)  
Microsoft Publisher 2010 Service Pack 2 (32 ビット版)  
(3114395)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3128034)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3128032)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3118380)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2889841)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3128037)  
(重要)  
Microsoft Publisher 2010 Service Pack 2 (64 ビット版)  
(3114395)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3128034)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3128008)  
(重要)  
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3127968)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3128008)  
(重要)  
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3127968)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3128008)  
(重要)  
Microsoft Office 2013 RT Service Pack 1  
(3127968)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32 ビット版)  
(3128016)  
(重要)  
Microsoft Office 2016 (32 ビット版)  
(3127986)  
(重要)  
Microsoft Office 2016 (32 ビット版)  
(重要)<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 ビット版)  
(3128016)  
(重要)  
Microsoft Office 2016 (64 ビット版)  
(3127986)  
(重要)  
Microsoft Office 2016 (64 ビット版)  
(重要)<sup>[1]</sup>

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3198808)  
(重要)  
Microsoft Excel for Mac 2011  
(3198808)  
(重要)  
Microsoft Word for Mac 2011  
(3198808)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac  
(3198800)  
(重要)  
Microsoft Excel 2016 for Mac  
(3198800)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
その他の Office ソフトウェア

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128022)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(3128024)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3128023)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3128044)  
(重要)  
Microsoft Word Viewer  
(3127995)  
(緊急)

</td>
</tr>
</table>
 
<sup>[1]</sup>クイック実行 (C2R) バージョンのみの参照用です。

**MS16-148 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft Office Services および Web Apps

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)

</td>
<td style="border:1px solid black;">
Excel Services  
(3127892)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Excel Services  
(3127892)  
(重要)

</td>
</tr>
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
Excel Services  
(3128029)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3128026)  
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
[**MS16-148**](https://go.microsoft.com/fwlink/?linkid=834445)

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
(3128035)  
(重要)

</td>
</tr>
</table>
 
**MS16-148 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび検証を効率化する手助けをします。

利用可能なこれらのツールと他のツールの詳細については、「[IT 管理者向けセキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、「[謝辞](https://technet.microsoft.com/ja-jp/library/security/mt674627.aspx)」を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/ja-jp/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社のアクティブ保護 Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security update」のキーワード検索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション: [TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ: [ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/ja-jp/contactus/cu_sc_virsec_master)

国ごとのローカル サポート: [インターナショナル サポート](http://support.microsoft.com/ja-jp/common/international.aspx)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2016/12/14): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2016/12/22): MS16-148 について、CVE-2016-7298 を CVE-2016-7274 に変更しました。これは情報のみの変更です。既に正常に更新プログラムをインストールされたお客様は、特別な措置を講じる必要はありません。
-   V1.2 (2016/12/22): 2016 年 12 月 14 日公開のセキュリティと品質ロールアップ 3210137 および 3210138 に、Windows 8.1、Windows Server 2012 R2、および Windows Server 2012 上の .NET Framework 4.5.2 に影響を与える既知の問題が含まれています。この問題は、2016 年 12 月 14 日公開のロールアップによって置き換えらえた 2016 年 11 月 16 日公開の品質ロールアップ プレビューにも存在していました。この問題により、同一のコンピューター上の Microsoft SQL Server のインスタンスに接続するアプリケーションが「provider: 共有メモリ プロバイダー, error: 15 - 機能はサポートされていません」というエラー メッセージを生成します。
    詳細については、サポート技術情報 [3214106](https://support.microsoft.com/ja-jp/kb/3214106) を参照してください。

*Page generated 2016-12-21 14:08-08:00.*
