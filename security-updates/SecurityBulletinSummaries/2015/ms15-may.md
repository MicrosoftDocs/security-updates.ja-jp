---
TOCTitle: 'MS15-MAY'
Title: 2015 年 5 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms15-may'
ms:contentKeyID: 65777924
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms15-may(v=Security.10)'
---

2015 年 5 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2015 年 5 月 13 日 | 最終更新日: 2015 年 10 月 14 日

**バージョン:** 2.0

このセキュリティ情報の概要は 2015 年 5 月公開のセキュリティ情報の一覧です。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3049563)</strong> <br />
このセキュリティ更新プログラムにより、Internet Explorer の脆弱性が解決されます。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533715">MS15-044</a></td>
<td style="border:1px solid black;"><strong>Microsoft フォント ドライバーの脆弱性により、リモートでコードが実行される (3057110)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows、Microsoft .NET Framework、Microsoft Office、Microsoft Lync、および Microsoft Silverlight の脆弱性を解決します。最も深刻な場合、ユーザーが特別な細工がされた文書を開いた場合や、TrueType フォント ファイルが埋め込まれた信頼されていない Web ページを表示した場合に、この脆弱性によりリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3057110">3057110</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Office、<br />
Microsoft Lync、<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533722">MS15-045</a></td>
<td style="border:1px solid black;"><strong>Windows Journal の脆弱性により、リモートでコードが実行される (3046002)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性で、特別に細工されたジャーナル ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533724">MS15-046</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、リモートでコードが実行される (3057181)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=534002">MS15-047</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server の脆弱性により、リモートでコードが実行される (3058083)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office サーバー ソフトウェアの脆弱性を解決します。これらの脆弱性により、認証された攻撃者が特別に細工されたページ コンテンツを SharePoint Server に送信した場合にリモートでコードが実行される可能性があります。攻撃者がこれらの脆弱性を悪用した場合、標的となる SharePoint サイト上の W3WP サービス アカウントのセキュリティ コンテキストで任意のコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533716">MS15-048</a></td>
<td style="border:1px solid black;"><strong>.NET Framework の脆弱性により、特権が昇格される (3057134)</strong><br />
このセキュリティ更新プログラムにより、Microsoft .NET Framework の脆弱性が解決されます。最も深刻な脆弱性では、ユーザーが特別に細工された部分的な信頼のアプリケーションをインストールした場合、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=534625">MS15-049</a></td>
<td style="border:1px solid black;"><strong>Silverlight の脆弱性により、特権の昇格が起こる (3058985)</strong><br />
このセキュリティ更新プログラムにより、Microsoft Silverlight の脆弱性が解決されます。この脆弱性により、影響を受けるシステムで特別に細工された Silverlight アプリケーションが実行された場合、特権の昇格が起こる可能性があります。この脆弱性を悪用するには、攻撃者は最初にシステムにログオンして、特別に作成されたアプリケーションを実行するように、ログオンしているユーザーを誘導する必要があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動は必要ありません</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=534268">MS15-050</a></td>
<td style="border:1px solid black;"><strong>サービス コントロール マネージャーの脆弱性により、特権が昇格される (3055642)</strong><br />
このセキュリティ更新プログラムは、Windows サービス コントロール マネージャー (SCM) の脆弱性を解決します。この脆弱性は、SCM が偽装レベルを不適切に検証する場合に発生します。この脆弱性により、攻撃者が最初にコンピューターにログオンし、特権を昇格させることを目的に特別に細工されたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533726">MS15-051</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (3057191)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性の中で比較的深刻なものでは、攻撃者がローカルにログオンし、カーネル モードで任意のコードを実行した場合、特権の昇格が起こる可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーが、この脆弱性を悪用することはできません。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533731">MS15-052</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルの脆弱性により、セキュリティ機能のバイパスが起こる (3050514)</strong><br />
このセキュリティ更新プログラムにより、Microsoft Windows の脆弱性が解決されます。この脆弱性により、攻撃者が影響を受けるシステムにログオンし、特別な細工がされたアプリケーションを実行した場合、セキュリティ機能のバイパスが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3050514">3050514</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533729">MS15-053</a></td>
<td style="border:1px solid black;"><strong>JScript および VBScript スクリプト エンジンの脆弱性により、セキュリティ機能のバイパスが起こる (3057263)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の Jscript および VBScript スクリプト エンジンにおける ASLR セキュリティ機能のバイパスを解決します。攻撃者はこれらの ASLR のバイパスのいずれかを、リモートでコードが実行される脆弱性など別の脆弱性と組み合わせて使用し、標的となるシステムにおいてより信頼性の高い方法で任意のコードを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533727">MS15-054</a></td>
<td style="border:1px solid black;"><strong>Microsoft 管理コンソールのファイル形式の脆弱性により、サービス拒否が起こる (3051768)</strong><br />
このセキュリティ更新プログラムにより、Microsoft Windows の脆弱性が解決されます。この脆弱性により、リモートの認証されていない攻撃者が特別に細工した .msc ファイルを含む共有をユーザーに開かせるように誘導した場合、サービス拒否が起こる可能性があります。ただし、攻撃者には、ユーザーに強制的に共有にアクセスさせるかファイルを表示させる手段はありません。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=536690">MS15-055</a></td>
<td style="border:1px solid black;"><strong>Schannel の脆弱性により、情報漏えいが起こる (3061518)<br />
</strong>このセキュリティ更新プログラムにより、Microsoft Windows の脆弱性が解決されます。この脆弱性により、Secure Channel (Schannel) が、暗号化された TLS セッションで、512 ビットの弱い Diffie-Hellman Ephemeral (DHE) キー長の使用を許可している場合、情報漏えいが起こる可能性があります。512 ビットの DHE キーを許可すると、DHE キーの交換が弱くなり、さまざまな攻撃に対して脆弱性が生じます。攻撃が成功するためには、サーバーが 512 ビットの DHE キー長をサポートしていることが必要です。Windows サーバーの既定の構成で許可される最小の DHE キー長は 1024 ビットです。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a>                                      <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3061518">3061518</a></td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1658">CVE-2015-1658</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">VBScript ASLR バイパス</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1684">CVE-2015-1684</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR バイパス</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1685">CVE-2015-1685</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">VBScript および JScript ASLR バイパス</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1686">CVE-2015-1686</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1688">CVE-2015-1688</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1689">CVE-2015-1689</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1691">CVE-2015-1691</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer クリップボードの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1692">CVE-2015-1692</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1694">CVE-2015-1694</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1703">CVE-2015-1703</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1704">CVE-2015-1704</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1705">CVE-2015-1705</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1706">CVE-2015-1706</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1708">CVE-2015-1708</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1709">CVE-2015-1709</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1710">CVE-2015-1710</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1711">CVE-2015-1711</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1712">CVE-2015-1712</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1713">CVE-2015-1713</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1714">CVE-2015-1714</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1717">CVE-2015-1717</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533730">MS15-043</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1718">CVE-2015-1718</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533715">MS15-044</a></td>
<td style="border:1px solid black;">OpenType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1670">CVE-2015-1670</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533715">MS15-044</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1671">CVE-2015-1671</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533722">MS15-045</a></td>
<td style="border:1px solid black;">Windows Journal のリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1675">CVE-2015-1675</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533722">MS15-045</a></td>
<td style="border:1px solid black;">Windows Journal のリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1695">CVE-2015-1695</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533722">MS15-045</a></td>
<td style="border:1px solid black;">Windows Journal のリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1696">CVE-2015-1696</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533722">MS15-045</a></td>
<td style="border:1px solid black;">Windows Journal のリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1697">CVE-2015-1697</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533722">MS15-045</a></td>
<td style="border:1px solid black;">Windows Journal のリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1698">CVE-2015-1698</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533722">MS15-045</a></td>
<td style="border:1px solid black;">Windows Journal のリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1699">CVE-2015-1699</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533724">MS15-046</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1682">CVE-2015-1682</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533724">MS15-046</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1683">CVE-2015-1683</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=534002">MS15-047</a></td>
<td style="border:1px solid black;">Microsoft SharePoint ページ コンテンツの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1700">CVE-2015-1700</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533716">MS15-048</a></td>
<td style="border:1px solid black;">.NET XML 復号化のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1672">CVE-2015-1672</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533716">MS15-048</a></td>
<td style="border:1px solid black;">Windows フォームの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1673">CVE-2015-1673</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=534625">MS15-049</a></td>
<td style="border:1px solid black;">Microsoft Silverlight ブラウザー外実行アプリケーションの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1715">CVE-2015-1715</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=534268">MS15-050</a></td>
<td style="border:1px solid black;">サービス コントロール マネージャーの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1702">CVE-2015-1702</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533726">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows カーネル メモリ漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1676">CVE-2015-1676</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533726">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows カーネル メモリ漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1677">CVE-2015-1677</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533726">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows カーネル メモリ漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1678">CVE-2015-1678</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533726">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows カーネル メモリ漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1679">CVE-2015-1679</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533726">MS15-051</a></td>
<td style="border:1px solid black;">Microsoft Windows カーネル メモリ漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1680">CVE-2015-1680</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533726">MS15-051</a></td>
<td style="border:1px solid black;">Win32k の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1701">CVE-2015-1701</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">永続的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533731">MS15-052</a></td>
<td style="border:1px solid black;">Windows カーネルのセキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1674">CVE-2015-1674</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533729">MS15-053</a></td>
<td style="border:1px solid black;">VBScript ASLR バイパス</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1684">CVE-2015-1684</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533729">MS15-053</a></td>
<td style="border:1px solid black;">VBScript および JScript ASLR バイパス</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1686">CVE-2015-1686</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=533727">MS15-054</a></td>
<td style="border:1px solid black;">Microsoft 管理コンソールのファイル形式のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1681">CVE-2015-1681</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">一時的</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=536690">MS15-055</a></td>
<td style="border:1px solid black;">SChannel の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1716">CVE-2015-1716</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
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
  
### Windows オペレーティング システムとコンポーネント (Table 2 の 1)

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140) 

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(警告)  
Internet Explorer 7  
(3049563)  
(警告)  
Internet Explorer 8  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048073)  
(緊急)  
Microsoft .NET Framework 4  
(3048074)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(3023211)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3023220)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035488)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(更新プログラムなし、注意事項を参照)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(警告)  
Internet Explorer 7  
(3049563)  
(警告)  
Internet Explorer 8  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048073)  
(緊急)  
Microsoft .NET Framework 4  
(3048074)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023220)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035488)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(更新プログラムなし、注意事項を参照)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3049563)  
(警告)  
Internet Explorer 7  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3045171)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023220)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035488)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(更新プログラムなし、注意事項を参照)  
(重要)

</td>
</tr>
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
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 7  
(3049563)  
(緊急)  
Internet Explorer 8  
(3049563)  
(緊急)  
Internet Explorer 9  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048068)  
(緊急)  
Microsoft .NET Framework 4  
(3048074)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(緊急)  
Internet Explorer 8  
(3049563)  
(緊急)  
Internet Explorer 9  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048068)  
(緊急)  
Microsoft .NET Framework 4  
(3048074)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3055642)  
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
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(警告)  
Internet Explorer 8  
(3049563)  
(警告)  
Internet Explorer 9  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048068)  
(緊急)  
Microsoft .NET Framework 4  
(3048074)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(警告)  
Internet Explorer 8  
(3049563)  
(警告)  
Internet Explorer 9  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3048068)  
(緊急)  
Microsoft .NET Framework 4  
(3048074)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3048077)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3045171)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3023213)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3035485)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3055642)  
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
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 8  
(3049563)  
(緊急)  
Internet Explorer 9  
(3049563)  
(緊急)  
Internet Explorer 10  
(3049563)  
(緊急)  
Internet Explorer 11  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(緊急)  
Internet Explorer 9  
(3049563)  
(緊急)  
Internet Explorer 10  
(3049563)  
(緊急)  
Internet Explorer 11  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3055642)  
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
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(警告)  
Internet Explorer 9  
(3049563)  
(警告)  
Internet Explorer 10  
(3049563)  
(警告)  
Internet Explorer 11  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3045171)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3055642)  
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
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 10  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5  
(3048071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(重要)  
Microsoft .NET Framework 3.5  
(3035486)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5  
(3048071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(重要)  
Microsoft .NET Framework 3.5  
(3035486)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5  
(3048072)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(重要)  
Microsoft .NET Framework 3.5  
(3035487)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5  
(3048072)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(重要)  
Microsoft .NET Framework 3.5  
(3035487)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3055642)  
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
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5  
(3048071)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(重要)  
Microsoft .NET Framework 3.5  
(3035486)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5  
(3048072)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(重要)  
Microsoft .NET Framework 3.5  
(3035487)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3055642)  
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
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3045171)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3055642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3049563)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3045171)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046002)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3055642)  
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
[**MS15-043**](https://go.microsoft.com/fwlink/?linkid=533730)

</td>
<td style="border:1px solid black;">
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-045**](https://go.microsoft.com/fwlink/?linkid=533722)

</td>
<td style="border:1px solid black;">
[**MS15-048**](https://go.microsoft.com/fwlink/?linkid=533716)

</td>
<td style="border:1px solid black;">
[**MS15-050**](https://go.microsoft.com/fwlink/?linkid=534268)

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
<td style="border:1px solid black;">
**なし**

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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3045171)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3055642)  
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
(3045171)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3055642)  
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
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(3048070)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3023215)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3032655)  
(重要)  
Microsoft .NET Framework 4  
(3023221)  
(重要)  
Microsoft .NET Framework 4  
(3032662)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023224)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035490)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3055642)  
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
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5  
(3048071)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023217)  
(重要)  
Microsoft .NET Framework 3.5  
(3035486)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3023223)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3035489)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3055642)  
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
(3045171)  
(緊急)  
Microsoft .NET Framework 3.5  
(3048072)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3023219)  
(重要)  
Microsoft .NET Framework 3.5  
(3035487)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3023222)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(3032663)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3055642)  
(重要)

</td>
</tr>
</table>
 
**MS15-044 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

**MS15-043、MS15-044、および MS15-045 に関する注意事項**

Windows Technical Preview および Windows Server Technical Preview が影響を受けます。これらのオペレーティング システムを実行しているお客様は、[Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) の更新プログラムをご使用のコンピューターに適用することをお勧めします。

MS15-044 に限定で、Microsoft .NET Framework 4.6 RC 用の更新プログラムも提供されています。これは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=107349)からのみ入手できます。

**MS15-050 に関する注意事項**

Windows Server 2003 は影響を受けますが、そのための更新プログラムは公開されていません。詳細に関してはセキュリティ情報をご覧ください。



### Windows オペレーティング システムとコンポーネント (Table 2 の 2)

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
<td style="border:1px solid black;">
**なし**                                             

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)                                      

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.6 および VBScript 5.6  
(3050946)  
(重要)  
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.6 および VBScript 5.6  
(3050946)  
(重要)  
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.6 および VBScript 5.6  
(3050946)  
(重要)  
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3061518)  
(重要)

</td>
</tr>
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
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
Windows Vista Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3061518)  
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
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3061518)  
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
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3061518)  
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
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3061518)  
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
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3061518)  
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
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3061518)  
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
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3061518)  
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
[**MS15-051**](https://go.microsoft.com/fwlink/?linkid=533726)

</td>
<td style="border:1px solid black;">
[**MS15-052**](https://go.microsoft.com/fwlink/?linkid=533731)

</td>
<td style="border:1px solid black;">
[**MS15-053**](https://go.microsoft.com/fwlink/?linkid=533729)

</td>
<td style="border:1px solid black;">
[**MS15-054**](https://go.microsoft.com/fwlink/?linkid=533727)

</td>
<td style="border:1px solid black;">
[**MS15-055**](https://go.microsoft.com/fwlink/?linkid=536690)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.7 および VBScript 5.7  
(3050945)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.8 および VBScript 5.8  
(3050941)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3061518)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3045171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3050514)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3051768)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3061518)  
(重要)

</td>
</tr>
</table>
 
**MS15-053 および MS15-054 に関する注意事項:**

Windows Technical Preview および Windows Server Technical Preview が影響を受けます。これらのオペレーティング システムを実行しているお客様は、[Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) の更新プログラムをご使用のコンピューターに適用することをお勧めします。

 

### Microsoft サーバー ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://go.microsoft.com/fwlink/?linkid=534002)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)  
(2760412)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)  
(2760412)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://go.microsoft.com/fwlink/?linkid=534002)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(3017815)  
(重要)  
Microsoft SharePoint Server 2010 Service Pack 2  
(2553219)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(3017815)  
(重要)  
Microsoft SharePoint Server 2010 Service Pack 2  
(2956192)  
(重要)

</td>
</tr>
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
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

</td>
<td style="border:1px solid black;">
[**MS15-047**](https://go.microsoft.com/fwlink/?linkid=534002)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

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
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1  
(3039736)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3054792)  
(重要)

</td>
</tr>
</table>
 
**MS15-046 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2883029)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085544)  
(重要)

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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

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
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2881073)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2965311)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2999412)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2965242)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(2965240)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32-bit エディション)  
(2999420)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(2965237)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2881073)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2965311)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2999412)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2965242)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(2965240)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64-bit エディション)  
(2999420)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(2965237)  
(重要)

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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

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
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(2975808)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(2986216)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32-bit エディション)  
(2975816)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(2965307)  
(重要)

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
(2975808)  
(重要)  
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(2986216)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64-bit エディション)  
(2975816)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(2965307)  
(重要)

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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2975808)  
(重要)  
Microsoft Excel 2013 RT Service Pack 1  
(2986216)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(2975816)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(2965307)  
(重要)

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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

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
Microsoft Office for Mac 2011  
(3048688)  
(重要)  
Microsoft Excel for Mac 2011  
(3048688)  
(重要)  
Microsoft PowerPoint for Mac 2011  
(3048688)  
(重要)  
Microsoft Word for Mac 2011  
(3048688)  
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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

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
Microsoft PowerPoint Viewer

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint Viewer  
(2956195)  
(重要)

</td>
</tr>
</table>
 
**MS15-044 および MS15-046 に関する注意事項**

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
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2965233)  
(重要)  
Excel Services  
(2956194)  
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
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3023055)  
(重要)  
Excel Services  
(3039725)  
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
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(2956140)  
(重要)  
Microsoft Excel Web Apps 2010 Service Pack 2  
(2956193)  
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
[**MS15-046**](https://go.microsoft.com/fwlink/?linkid=533724)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3039748)  
(重要)

</td>
</tr>
</table>
 
**MS15-046 に関する注意事項**

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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

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
(3051467)  
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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

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
(3051464)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)  
(3051464)  
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
(3051465)  
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
(3051466)  
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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

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

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)  
(3039779)  
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
(3039779)  
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
(3039779)  
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
(3039779)  
(緊急)

</td>
</tr>
</table>
 
**MS15-044 に関する注意**

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
[**MS15-044**](https://go.microsoft.com/fwlink/?linkid=533715)

</td>
<td style="border:1px solid black;">
[**MS15-049**](https://go.microsoft.com/fwlink/?linkid=534625)

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
Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5  
(3056819)  
(緊急)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(3056819)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(3056819)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(緊急)

</td>
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5  
(3056819)  
(重要)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(3056819)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(3056819)  
(重要)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(3056819)  
(重要)

</td>
</tr>
</table>
 
**MS15-044 に関する注意**

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

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=107349)からダウンロードできます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージを Microsoft ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/ja-jp/kb/913086) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ja)

国ごとのローカル サポート: [Microsoft サポート](https://support.microsoft.com/common/international.aspx?ln=ja)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation およびその関連会社は、本文書に含まれている情報の使用および使用結果につき、正確性、真実性など、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社およびこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2015/05/13): このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2015/10/14): このセキュリティ情報の概要ページを更新し、MS15-046 において以前リリースした更新プログラム (2965282) に伴う問題に対処した Microsoft Office 2007 用の新しい更新プログラム (3085544) が利用可能になったことをお知らせしました。Microsoft Office 2007 を実行しているお客様は、このセキュリティ情報で説明されている脆弱性から完全に保護されるために、更新プログラム 3085544 をできる限り早急にインストールすることを推奨します。その他の Microsoft Office ソフトウェアを実行しているお客様は、特別な措置を講じる必要はありません。詳細情報およびダウンロードリンクは、サポート技術情報 3085544 を参照してください。

*Page generated 2015-10-08 16:32-07:00.*
