---
TOCTitle: 'MS15-NOV'
Title: 2015 年 11 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms15-nov'
ms:contentKeyID: 71792331
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms15-nov(v=Security.10)'
---

2015 年 11 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日: 2015 年 11 月 11 日 | 最終更新日: 2016 年 4 月 22 日

**バージョン:** 3.1

このセキュリティ情報の概要は 2015 年 11 月公開のセキュリティ情報についてです。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3104517)</strong> <br />
このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3100773">3100773</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690585">MS15-113</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3104519)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690570">MS15-114</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Windows Journal 用のセキュリティ更新プログラム (3100213)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性で、特別に細工されたジャーナル ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691032">MS15-115</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Windows 用のセキュリティ更新プログラム (3105864)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性の最も深刻な状況では、攻撃者が特別に細工したドキュメントを開くようにユーザーを誘導した場合、または埋め込みフォントが含まれる信頼されていない Web ページにアクセスするようにユーザーを誘導した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3101746">3101746</a>
<a href="https://support.microsoft.com/ja-jp/kb/3097877">3097877</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690594">MS15-116</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3104540)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3101496">3101496</a></td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps、<br />
Microsoft Lync、<br />
Skype for Business</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690723">MS15-117</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する NDIS 用のセキュリティ更新プログラム (3101722)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows NDIS の脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690565">MS15-118</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する .NET Framework 用のセキュリティ更新プログラム (3104507)<br />
</strong>このセキュリティ更新プログラムは、Microsoft .NET Framework の脆弱性を解決します。最も深刻な脆弱性が悪用されると、攻撃者がユーザーを誘導して、侵害された Web サイトにアクセスさせるかクライアント側コードをユーザーのブラウザーに注入するように特別に設計されたメール内のリンクを開かせた場合に、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690588">MS15-119</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する Winsock 用のセキュリティ更新プログラム (3104521)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が標的とするシステムにログオンし、この脆弱性を悪用することを目的として特別に細工されたコードを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690724">MS15-120</a></td>
<td style="border:1px solid black;"><strong>サービス拒否に対処する IPSec 用のセキュリティ更新プログラム (3102939)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows のサービス拒否の脆弱性を解決します。攻撃者によりこの脆弱性が悪用された場合、サーバーが応答不能になる可能性があります。この脆弱性を悪用するには、攻撃者には有効な資格情報が必要です。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690884">MS15-121</a></td>
<td style="border:1px solid black;"><strong>なりすましに対処する Schannel 用のセキュリティ更新プログラム (3081320)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者がクライアントと正規のサーバーの間で中間者 (MiTM) 攻撃を実行した場合に、なりすましが行われる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
なりすまし</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3081320">3081320</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690720">MS15-122</a></td>
<td style="border:1px solid black;"><strong>セキュリティ機能のバイパスに対処する Kerberos 用のセキュリティ更新プログラム (3105256)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows のセキュリティ機能のバイパスを解決します。攻撃者は、標的のコンピューター上で Kerberos 認証をバイパスし、BitLocker により保護されているドライブを解読する可能性があります。バイパスが悪用される可能性があるのは、標的のシステムで PIN または USB キーを使用せずに BitLocker が有効であり、コンピューターがドメインに参加している場合に限られます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3101246">3101246</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691035">MS15-123</a></td>
<td style="border:1px solid black;"><strong>情報漏えいに対処する Skype for Business および Microsoft Lync 用のセキュリティ更新プログラム (3105872)</strong><br />
このセキュリティ更新プログラムは、Skype for Business Server および Microsoft Lync の脆弱性を解決します。この脆弱性により、攻撃者が標的のユーザーをインスタント メッセージ セッションに招待し、特別に細工された JavaScript コンテンツが含まれるメッセージをそのユーザーに送信した場合、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3101496">3101496</a><br />
<a href="https://support.microsoft.com/kb/3108096">3108096</a></td>
<td style="border:1px solid black;">Microsoft Lync、<br />
Skype for Business</td>
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
<td style="border:1px solid black;"><strong>最新のソフトウェア リリースでの<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>過去のソフトウェア リリースでの<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>サービス拒否<br />
悪用可能性評価</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2427">CVE-2015-2427</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Microsoft ブラウザーのメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6064">CVE-2015-6064</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6065">CVE-2015-6065</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6066">CVE-2015-6066</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6068">CVE-2015-6068</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6069">CVE-2015-6069</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6070">CVE-2015-6070</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6071">CVE-2015-6071</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6072">CVE-2015-6072</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Microsoft ブラウザーのメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6073">CVE-2015-6073</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6074">CVE-2015-6074</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6075">CVE-2015-6075</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6076">CVE-2015-6076</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6077">CVE-2015-6077</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Microsoft ブラウザーのメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6078">CVE-2015-6078</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6079">CVE-2015-6079</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6080">CVE-2015-6080</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6081">CVE-2015-6081</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6082">CVE-2015-6082</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6084">CVE-2015-6084</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6085">CVE-2015-6085</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6086">CVE-2015-6086</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6087">CVE-2015-6087</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">Microsoft ブラウザー ASLR バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6088">CVE-2015-6088</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690584">MS15-112</a></td>
<td style="border:1px solid black;">スクリプト エンジンのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6089">CVE-2015-6089</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690585">MS15-113</a></td>
<td style="border:1px solid black;">Microsoft ブラウザーのメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6064">CVE-2015-6064</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690585">MS15-113</a></td>
<td style="border:1px solid black;">Microsoft ブラウザーのメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6073">CVE-2015-6073</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690585">MS15-113</a></td>
<td style="border:1px solid black;">Microsoft ブラウザーのメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6078">CVE-2015-6078</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690585">MS15-113</a></td>
<td style="border:1px solid black;">Microsoft ブラウザー ASLR バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6088">CVE-2015-6088</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690570">MS15-114</a></td>
<td style="border:1px solid black;">Windows Journal のヒープ オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6097">CVE-2015-6097</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691032">MS15-115</a></td>
<td style="border:1px solid black;">Windows カーネル メモリの特権の昇格に関する脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6100">CVE-2015-6100</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691032">MS15-115</a></td>
<td style="border:1px solid black;">Windows カーネル メモリの特権の昇格に関する脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6101">CVE-2015-6101</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691032">MS15-115</a></td>
<td style="border:1px solid black;">Windows カーネル メモリの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6102">CVE-2015-6102</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691032">MS15-115</a></td>
<td style="border:1px solid black;">Windows グラフィックス メモリのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6103">CVE-2015-6103</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691032">MS15-115</a></td>
<td style="border:1px solid black;">Windows グラフィックス メモリのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6104">CVE-2015-6104</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691032">MS15-115</a></td>
<td style="border:1px solid black;">Windows カーネル メモリの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6109">CVE-2015-6109</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691032">MS15-115</a></td>
<td style="border:1px solid black;">Windows カーネルのセキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6113">CVE-2015-6113</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690594">MS15-116</a></td>
<td style="border:1px solid black;">Microsoft Office の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2503">CVE-2015-2503</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690594">MS15-116</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6038">CVE-2015-6038</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690594">MS15-116</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6091">CVE-2015-6091</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690594">MS15-116</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6092">CVE-2015-6092</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690594">MS15-116</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6093">CVE-2015-6093</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690594">MS15-116</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6094">CVE-2015-6094</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690594">MS15-116</a></td>
<td style="border:1px solid black;">Microsoft Outlook for Mac のなりすましの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6123">CVE-2015-6123</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690723">MS15-117</a></td>
<td style="border:1px solid black;">Windows NDIS の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6098">CVE-2015-6098</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690565">MS15-118</a></td>
<td style="border:1px solid black;">.NET の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6096">CVE-2015-6096</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690565">MS15-118</a></td>
<td style="border:1px solid black;">.NET の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6099">CVE-2015-6099</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690565">MS15-118</a></td>
<td style="border:1px solid black;">.NET ASLR バイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6115">CVE-2015-6115</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690588">MS15-119</a></td>
<td style="border:1px solid black;">Winsock の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2478">CVE-2015-2478</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690724">MS15-120</a></td>
<td style="border:1px solid black;">Windows IPSec のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6111">CVE-2015-6111</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690884">MS15-121</a></td>
<td style="border:1px solid black;">Schannel TLS のトリプル ハンドシェイクの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6112">CVE-2015-6112</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=690720">MS15-122</a></td>
<td style="border:1px solid black;">Windows Kerberos のセキュリティ機能のバイパス</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6095">CVE-2015-6095</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=691035">MS15-123</a></td>
<td style="border:1px solid black;">サーバー入力検証の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6061">CVE-2015-6061</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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
Internet Explorer 7  
(3100773)  
(緊急)  
Internet Explorer 8  
(3100773)  
(緊急)  
Internet Explorer 9  
(3100773)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3100213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3097877)  
(緊急)  
Windows Vista Service Pack 2  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3101722)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3100773)  
(緊急)  
Internet Explorer 8  
(3100773)  
(緊急)  
Internet Explorer 9  
(3100773)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3100213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3097877)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3101722)  
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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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
Internet Explorer 7  
(3100773)  
(警告)  
Internet Explorer 8  
(3100773)  
(警告)  
Internet Explorer 9  
(3100773)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3100213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3097877)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3101722)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3100773)  
(警告)  
Internet Explorer 8  
(3100773)  
(警告)  
Internet Explorer 9  
(3100773)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3100213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3097877)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3101722)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3100773)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3097877)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3101722)  
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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3100773)  
(緊急)  
Internet Explorer 9  
(3100773)  
(緊急)  
Internet Explorer 10  
(3100773)  
(緊急)  
Internet Explorer 11  
(3100773)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3100213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3097877)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3101722)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3100773)  
(緊急)  
Internet Explorer 9  
(3100773)  
(緊急)  
Internet Explorer 10  
(3100773)  
(緊急)  
Internet Explorer 11  
(3100773)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 x64 based Systems Service Pack 1  
(3100213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 x64 based Systems Service Pack 1  
(3097877)  
(緊急)  
Windows 7 x64 based Systems Service Pack 1  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 based Systems Service Pack 1  
(3101722)  
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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3100773)  
(警告)  
Internet Explorer 9  
(3100773)  
(警告)  
Internet Explorer 10  
(3100773)  
(警告)  
Internet Explorer 11  
(3100773)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3100213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3097877)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3101722)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3100773)  
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
(3097877)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3101722)  
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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3100773)  
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
(3097877)  
(緊急)  
Windows 8 for 32-bit Systems  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3100773)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 x64 based Systems  
(3097877)  
(緊急)  
Windows 8 x64 based Systems  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3100773)  
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
(3097877)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3100773)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 based Systems  
(3097877)  
(緊急)  
Windows 8.1 x64 based Systems  
(3101746)  
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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3100773)  
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
(3097877)  
(緊急)  
Windows Server 2012  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3100773)  
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
(3097877)  
(緊急)  
Windows Server 2012 R2  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3100773)  
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
(3097877)  
(緊急)  
Windows RT  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3100773)  
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
(3097877)  
(緊急)  
Windows RT 8.1  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3105213)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3105213)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3105213)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 x64 based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105213)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3105213)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 x64 based Systems  
(3105213)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105211)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3105211)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3105211)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3105211)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3105211)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3105211)  
(緊急)

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
[**MS15-112**](http://go.microsoft.com/fwlink/?linkid=690584)

</td>
<td style="border:1px solid black;">
[**MS15-113**](http://go.microsoft.com/fwlink/?linkid=690585)

</td>
<td style="border:1px solid black;">
[**MS15-114**](http://go.microsoft.com/fwlink/?linkid=690570)

</td>
<td style="border:1px solid black;">
[**MS15-115**](http://go.microsoft.com/fwlink/?linkid=691032)

</td>
<td style="border:1px solid black;">
[**MS15-117**](http://go.microsoft.com/fwlink/?linkid=690723)

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
**なし**

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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3097877)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3101722)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3097877)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3101722)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3097877)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3101722)  
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
(3097877)  
(緊急)  
Windows Server 2012  
(Server Core インストール)  
(3101746)  
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
(3097877)  
(緊急)  
Windows Server 2012 R2  
(Server Core インストール)  
(3101746)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
 

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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3097988)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097996)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098781)  
(重要)  
Microsoft .NET Framework 4.6  
(3098001)  
(重要)  
Microsoft .NET Framework 4.6  
(3098786)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3097988)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097996)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098781)  
(重要)  
Microsoft .NET Framework 4.6  
(3098001)  
(重要)  
Microsoft .NET Framework 4.6  
(3098786)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3101246)  
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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3097988)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097996)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098781)  
(重要)  
Microsoft .NET Framework 4.6  
(3098001)  
(重要)  
Microsoft .NET Framework 4.6  
(3098786)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3097988)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097996)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098781)  
(重要)  
Microsoft .NET Framework 4.6  
(3098001)  
(重要)  
Microsoft .NET Framework 4.6  
(3098786)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3097988)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3101246)  
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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3097989)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097996)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098781)  
(重要)  
Microsoft .NET Framework 4.6  
(3098001)  
(重要)  
Microsoft .NET Framework 4.6  
(3098786)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3097989)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097996)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098781)  
(重要)  
Microsoft .NET Framework 4.6  
(3098001)  
(重要)  
Microsoft .NET Framework 4.6  
(3098786)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 based Systems Service Pack 1  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 x64 based Systems Service Pack 1  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 x64 based Systems Service Pack 1  
(3101246)  
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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3097989)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097996)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098781)  
(重要)  
Microsoft .NET Framework 4.6  
(3098001)  
(重要)  
Microsoft .NET Framework 4.6  
(3098786)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3097989)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3101246)  
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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3097991)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097995)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098780)  
(重要)  
Microsoft .NET Framework 4.6  
(3097999)  
(重要)  
Microsoft .NET Framework 4.6  
(3098784)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 x64 based Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3097991)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097995)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098780)  
(重要)  
Microsoft .NET Framework 4.6  
(3097999)  
(重要)  
Microsoft .NET Framework 4.6  
(3098784)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 based Systems  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 based Systems  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 based Systems  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 x64 based Systems  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3097992)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3097997)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3098779)  
(重要)  
Microsoft .NET Framework 4.6  
(3098000)  
(重要)  
Microsoft .NET Framework 4.6  
(3098785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 x64 based Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3097992)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3097997)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3098779)  
(重要)  
Microsoft .NET Framework 4.6  
(3098000)  
(重要)  
Microsoft .NET Framework 4.6  
(3098785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 based Systems  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 based Systems  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 based Systems  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 x64 based Systems  
(3101246)  
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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3097991)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097995)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098780)  
(重要)  
Microsoft .NET Framework 4.6  
(3097999)  
(重要)  
Microsoft .NET Framework 4.6  
(3098784)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3097992)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3097997)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3098779)  
(重要)  
Microsoft .NET Framework 4.6  
(3098000)  
(重要)  
Microsoft .NET Framework 4.6  
(3098785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3101246)  
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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
Windows RT

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097995)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098780)  
(重要)  
Microsoft .NET Framework 4.6  
(3097999)  
(重要)  
Microsoft .NET Framework 4.6  
(3098784)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(3097997)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3098779)  
(重要)  
Microsoft .NET Framework 4.6  
(3098000)  
(重要)  
Microsoft .NET Framework 4.6  
(3098785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3105213)  
(重要)  
Microsoft .NET Framework 4.6  
(3105213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3105213)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3105213)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 x64 based Systems

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3105213)  
(重要)  
Microsoft .NET Framework 4.6  
(3105213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 x64 based Systems  
(3105213)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 x64 based Systems  
(3105213)  
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
(3105211)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3105211)  
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
(3105211)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3105211)  
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
[**MS15-118**](http://go.microsoft.com/fwlink/?linkid=690565)

</td>
<td style="border:1px solid black;">
[**MS15-119**](http://go.microsoft.com/fwlink/?linkid=690588)

</td>
<td style="border:1px solid black;">
[**MS15-120**](http://go.microsoft.com/fwlink/?linkid=690724)

</td>
<td style="border:1px solid black;">
[**MS15-121**](http://go.microsoft.com/fwlink/?linkid=690884)

</td>
<td style="border:1px solid black;">
[**MS15-122**](http://go.microsoft.com/fwlink/?linkid=690720)

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
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3101246)  
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
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3097989)  
(重要)  
Microsoft .NET Framework 4  
(3097994)  
(重要)  
Microsoft .NET Framework 4  
(3098778)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097996)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098781)  
(重要)  
Microsoft .NET Framework 4.6  
(3098001)  
(重要)  
Microsoft .NET Framework 4.6  
(3098786)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3097991)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3097995)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3098780)  
(重要)  
Microsoft .NET Framework 4.6  
(3097999)  
(重要)  
Microsoft .NET Framework 4.6  
(3098784)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3101246)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3097992)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3097997)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3098779)  
(重要)  
Microsoft .NET Framework 4.6  
(3098000)  
(重要)  
Microsoft .NET Framework 4.6  
(3098785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3092601)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3102939)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3081320)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3101246)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office スイートおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3101555)  
(重要)  
Microsoft Access 2007 Service Pack 3  
(2596614)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(3101554)  
(重要)  
Microsoft InfoPath 2007 Service Pack 3  
(2687406)  
(重要)  
Microsoft OneNote 2007 Service Pack 3  
(2889915)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(3085548)  
(重要)  
Microsoft Project 2007 Service Pack 3  
(2596770)  
(重要)  
Microsoft Publisher 2007 Service Pack 3  
(2880506)  
(重要)  
Microsoft Visio 2007 Service Pack 3  
(3101553)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3085552)  
(重要)  
Microsoft Office 2007 IME (日本語) Service Pack 3  
(2899473)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3101521)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3101529)  
(重要)  
Microsoft Access 2010 Service Pack 2 (32 ビット版)  
(3101544)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3101543)  
(重要)  
Microsoft InfoPath 2010 Service Pack 2 (32 ビット版)  
(2878230)  
(重要)  
Microsoft OneNote 2010 Service Pack 2 (32 ビット版)  
(3054978)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 ビット版)  
(3085594)  
(重要)  
Microsoft Project 2010 Service Pack 2 (32 ビット版)  
(3085614)  
(重要)  
Microsoft Publisher 2010 Service Pack 2 (32 ビット版)  
(2817478)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (32 ビット版)  
(3101526)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(2965313)  
(重要)  
Microsoft Pinyin IME 2010 (32 ビット版)  
(2899516)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3101521)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3101529)  
(重要)  
Microsoft Access 2010 Service Pack 2 (64 ビット版)  
(3101544)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3101543)  
(重要)  
Microsoft InfoPath 2010 Service Pack 2 (64 ビット版)  
(2878230)  
(重要)  
Microsoft OneNote 2010 Service Pack 2 (64 ビット版)  
(3054978)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 ビット版)  
(3085594)  
(重要)  
Microsoft Project 2010 Service Pack 2 (64 ビット版)  
(3085614)  
(重要)  
Microsoft Publisher 2010 Service Pack 2 (64 ビット版)  
(2817478)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (64 ビット版)  
(3101526)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(2965313)  
(重要)  
Microsoft Pinyin IME 2010 (64 ビット版)  
(2899516)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3101360)  
(重要)  
Microsoft Access 2013 Service Pack 1 (32 ビット版)  
(3085584)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3101499)  
(重要)  
Microsoft InfoPath 2013 Service Pack 1 (32 ビット版)  
(3054793)  
(重要)  
Microsoft OneNote 2013 Service Pack 1 (32 ビット版)  
(3101371)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 ビット版)  
(3101359)  
(重要)  
Microsoft Project 2013 Service Pack 1 (32 ビット版)  
(3101506)  
(重要)  
Microsoft Publisher 2013 Service Pack 1 (32 ビット版)  
(3085561)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (32 ビット版)  
(3101365)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3101370)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3101360)  
(重要)  
Microsoft Access 2013 Service Pack 1 (64 ビット版)  
(3085584)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3101499)  
(重要)  
Microsoft InfoPath 2013 Service Pack 1 (64 ビット版)  
(3054793)  
(重要)  
Microsoft OneNote 2013 Service Pack 1 (64 ビット版)  
(3101371)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 ビット版)  
(3101359)  
(重要)  
Microsoft Project 2013 Service Pack 1 (64 ビット版)  
(3101506)  
(重要)  
Microsoft Publisher 2013 Service Pack 1 (64 ビット版)  
(3085561)  
(重要)  
Microsoft Visio 2013 Service Pack 1 (64 ビット版)  
(3101365)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3101370)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
Microsoft Office 2013 RT Service Pack 1  
(3101360)  
(重要)  
Microsoft Excel 2013 RT Service Pack 1  
(3101499)  
(重要)  
Microsoft OneNote 2013 RT Service Pack 1  
(3101371)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3101359)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3101370)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
Microsoft Office 2016 (32 ビット版)  
(3101512)  
(重要)  
Microsoft Office 2016 (32 ビット版)  
(3101514)  
(重要)  
Microsoft Access 2016 (32 ビット版)  
(2910978)  
(重要)  
Microsoft Excel 2016 (32 ビット版)  
(3101510)  
(重要)  
Microsoft OneNote 2016 (32 ビット版)  
(2920726)  
(重要)  
Microsoft PowerPoint 2016 (32 ビット版)  
(3101509)  
(重要)  
Microsoft Project 2016 (32 ビット版)  
(2920698)  
(重要)  
Microsoft Publisher 2016 (32 ビット版)  
(2920680)  
(重要)  
Microsoft Visio 2016 (32 ビット版)  
(3101507)  
(重要)  
Microsoft Word 2016 (32 ビット版)  
(3101513)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)  
(3101512)  
(重要)  
Microsoft Office 2016 (64 ビット版)  
(3101514)  
(重要)  
Microsoft Access 2016 (64 ビット版)  
(2910978)  
(重要)  
Microsoft Excel 2016 (64 ビット版)  
(3101510)  
(重要)  
Microsoft OneNote 2016 (64 ビット版)  
(2920726)  
(重要)  
Microsoft PowerPoint 2016 (64 ビット版)  
(3101509)  
(重要)  
Microsoft Project 2016 (64 ビット版)  
(2920698)  
(重要)  
Microsoft Publisher 2016 (64 ビット版)  
(2920680)  
(重要)  
Microsoft Visio 2016 (64 ビット版)  
(3101507)  
(重要)  
Microsoft Word 2016 (64 ビット版)  
(3101513)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3102924)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3102925)  
(重要)

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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(3101558)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(3085551)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3101560)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3101564)  
(重要)

</td>
</tr>
</table>
 
**MS15-116 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft Office Services および Web Apps

 
<p> </p>  <table style="border:1px solid black;">
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
(3101559)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Excel Services  
(3101559)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
(3101525)  
(重要)  
Word Automation Services  
(3085511)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
Excel Services  
(3101364)  
(重要)  
Word Automation Services  
(3085477)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
(3101533)  
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
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

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
(3101367)  
(重要)

</td>
</tr>
</table>
 
**MS15-116 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft コミュニケーション プラットフォームおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync Smart Room System**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

</td>
<td style="border:1px solid black;">
[**MS15-123**](http://go.microsoft.com/fwlink/?linkid=691035)

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
Microsoft Lync Room System  
(SMART Room System 関連)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync Room System  
(SMART Room System 関連)  
(3108096)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Room System  
(Crestron RL 関連)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync Room System  
(Crestron RL 関連)  
(3108096)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

</td>
<td style="border:1px solid black;">
[**MS15-123**](http://go.microsoft.com/fwlink/?linkid=691035)

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
Microsoft Lync 2010 (32 ビット)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)  
(3096735)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)  
(3096735)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(ユーザー レベル インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(ユーザー レベル インストール)  
(3096736)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(管理レベル インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(管理レベル インストール)  
(3096738)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

</td>
<td style="border:1px solid black;">
[**MS15-123**](http://go.microsoft.com/fwlink/?linkid=691035)

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
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)  
(3101496)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)  
(3101496)  
(重要)

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
(3101496)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)  
(Skype for Business Basic)  
(3101496)  
(重要)

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
(3101496)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)  
(Skype for Business)  
(3101496)  
(重要)

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
(3101496)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)  
(Skype for Business Basic)  
(3101496)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Skype for Business 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-116**](http://go.microsoft.com/fwlink/?linkid=690594)

</td>
<td style="border:1px solid black;">
[**MS15-123**](http://go.microsoft.com/fwlink/?linkid=691035)

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
Skype for Business 2016 (32 ビット)

</td>
<td style="border:1px solid black;">
Skype for Business 2016 (32 ビット)  
(3085634)  
(重要)

</td>
<td style="border:1px solid black;">
Skype for Business 2016 (32 ビット)  
(3085634)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32 ビット)

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32 ビット)  
(3085634)  
(重要)

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32 ビット)  
(3085634)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (64 ビット)

</td>
<td style="border:1px solid black;">
Skype for Business 2016 (64 ビット)  
(3085634)  
(重要)

</td>
<td style="border:1px solid black;">
Skype for Business 2016 (64 ビット)  
(3085634)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64 ビット)

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64 ビット)  
(3085634)  
(重要)

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64 ビット)  
(3085634)  
(重要)

</td>
</tr>
</table>
 
**MS15-116 に関する注意**

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

-   V1.0 (2015/11/11): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2015/11/12): MS15-115 に既知の問題 KB3097877 を追加しました。マイクロソフトは、Windows のセキュリティ更新プログラム 3097877 のインストール後、特定の電子メールを閲覧した際にクラッシュが発生するという一部のお客様からの報告について原因を調査しています。現在、早急に再調査中です。
-   V2.0 (2015/12/10): MS15-115 の KB3097877 を更新し、最初の更新プログラムによっていくつかのアプリケーションが予期せず終了する可能性があるという問題を修正するために Windows 7 および Windows Server 2008 R2 用の更新プログラム 3097877 を再リリースしたことをお知らせしました。既に Windows 7 または Windows Server 2008 R2 システムにこの更新プログラムを正常にインストールしたお客様も、この更新プログラムを再インストールする必要があります。
-   V2.1 (2015/12/10): MS15-122 の概要を更新し、攻撃者が CVE-2015-6095 を悪用して標的のコンピューターに物理的にアクセスするという要件の記載を削除しました。これは情報のみの変更です。既に正常に更新プログラムをインストールされたお客様は、特別な措置を講じる必要はありません。
-   V2.2 (2015/12/18): このセキュリティ情報の概要ページを更新し、概要の表の MS15-116 および MS15-123 に既知の問題を追加しました。セキュリティ更新プログラム 3101496 をインストールすると、連絡先リストのタイトルバーに “Lync” と表示されます。この問題は、Lync 2013 (Skype for Business) クライアントで表示されるよう Skype for Business のユーザー インターフェイスを設定した場合に発生します。マイクロソフトはこの問題を調査しており、情報を入手し次第この文書に追加情報を掲載します。
-   V3.0 (2016/02/10): MS15-118 に関して、セキュリティ情報の概要ページを更新し、サポート技術情報 3318750 で説明されている既知の問題に対処する更新プログラム 3098785 を再リリースしたことをお知らせしました。Windows 8.1、Windows RT、または Windows Server 2012 R2 を実行しているお客様は、完全に更新されたバージョンの .NET Framework 4.5.x が搭載されているコンピューターに .NET Framework 4.6 をインストール後に、この問題が発生する可能性があります。マイクロソフトは、再リリースされた更新プログラム 3098785 をダウンロードおよびインストールするために、新規更新プログラムのスキャンを推奨します。詳細は、[サポート技術情報 3318750](https://support.microsoft.com/kb/3318750)を参照してください。
-   V3.1 (2016/04/22): このセキュリティ情報の概要のページを更新し、概要の表の MS15-112 に既知の問題を追加しました。セキュリティ更新プログラム 3100773 をインストールすると、韓国語の文字を正しく入力することができません。この既知の問題の解決策に関する詳細は、[サポート技術情報 3154996](https://support.microsoft.com/ja-jp/kb/3154996) を参照してください。

*Page generated 2016-04-21 10:52-07:00.*
