---
TOCTitle: 'MS16-JUL'
Title: 2016 年 7 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms16-jul'
ms:contentKeyID: 73201185
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms16-jul(v=Security.10)'
---

2016 年 7 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日: 2016 年 7 月 13 日 | 最終更新日: 2017 年 3 月 21 日

**バージョン:** 1.2

このセキュリティ情報の概要は 2016 年 7 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムと共に、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「**関連情報**」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、「**影響を受けるソフトウェア**」のセクションを参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808143">MS16-084</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3169991)<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者が影響を受けるコンピューターを制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808148">MS16-085</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3169999)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限を持つユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808144">MS16-086</a></td>
<td style="border:1px solid black;"><strong>JScript および VBScript 用の累積的なセキュリティ更新プログラム (3169996)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の JScript および VBScript スクリプト エンジンに存在する脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web サイトにアクセスすると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしているときに、攻撃者によりこれらの脆弱性が悪用された場合、影響を受けるコンピューターが制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808150">MS16-087</a></td>
<td style="border:1px solid black;"><strong>Windows 印刷 スプーラー コンポーネント用のセキュリティ更新プログラム (3170005)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性で比較的深刻なものでは、攻撃者がワークステーションまたはプリント サーバー上で中間者攻撃 (MiTM) を実行した場合、または攻撃目標のネットワーク上に不正なプリント サーバーを設定した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/ja-jp/kb/3170005">3170005</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808151">MS16-088</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用のセキュリティ更新プログラム (3170008)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。最も深刻な脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808157">MS16-089</a></td>
<td style="border:1px solid black;"><strong>Windows 保護カーネル モード用のセキュリティ更新プログラム (3170050)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。Windows 保護カーネル モードがメモリ内のオブジェクトを不適切に処理した場合、この脆弱性により情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808590">MS16-090</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3171481)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性で比較的深刻なものでは、攻撃者が影響を受けるコンピューターにログオンし、脆弱性を悪用できたり、影響を受けるコンピューターを制御できる、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808156">MS16-091</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 用のセキュリティ更新プログラム (3170048)<br />
</strong>このセキュリティ更新プログラムは、Microsoft .NET Framework の脆弱性を解決します。 この脆弱性により、攻撃者が Web ベースのアプリケーションに特別に細工された XML ファイルをアップロードした場合、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=808706">MS16-092</a></td>
<td style="border:1px solid black;"><strong>Windows カーネル用のセキュリティ更新プログラム (3171910)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性が悪用されると、Windows カーネルが、整合性の低いアプリケーションの特定のオブジェクト管理機能を使用する方法の判定に失敗した場合に、セキュリティ機能のバイパスが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=809010">MS16-093</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (3174060)<br />
</strong>このセキュリティ更新プログラムは、すべてのサポートされている Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、および Windows 10 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=817339">MS16-094</a></td>
<td style="border:1px solid black;"><strong>セキュア ブート用のセキュリティ更新プログラム (3177404)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の 1 件の脆弱性を解決します。攻撃者が対象のデバイスに影響を受けたポリシーをインストールした場合、セキュア ブートのセキュリティ機能がバイパスされる可能性があります。攻撃者がポリシーのインストールおよびセキュア ブートをバイパスするには、管理者権限か物理的なアクセス権を所持していることが必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報 ID、CVE ID の順でリストされています。掲示板での重要度評価が緊急または重要である脆弱性のみが含まれています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、「[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259)」 を参照してください。
  
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
[**MS16-084:Internet Explorer 用の累積的なセキュリティ更新プログラム (3169991)**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3204](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3204)

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
[CVE-2016-3240](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3240)

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
[CVE-2016-3241](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3241)

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
[CVE-2016-3242](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3242)

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
[CVE-2016-3243](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3243)

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
[CVE-2016-3245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3245)

</td>
<td style="border:1px solid black;">
Internet Explorer のセキュリティ機能のバイパスの脆弱性

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
[CVE-2016-3248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3248)

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
[CVE-2016-3259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3259)

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
[CVE-2016-3260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3260)

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
<td style="border:1px solid black;">
[CVE-2016-3261](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3261)

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
[CVE-2016-3264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3264)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

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
[CVE-2016-3273](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3273)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

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
[CVE-2016-3274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3274)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

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
[CVE-2016-3277](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3277)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

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
[**MS16-085:Microsoft Edge 用の累積的なセキュリティ更新プログラム (3169999)**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3244](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3244)

</td>
<td style="border:1px solid black;">
Microsoft Edge のセキュリティ機能のバイパス

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
[CVE-2016-3246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3246)

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
[CVE-2016-3248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3248)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

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
[CVE-2016-3259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3259)

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
<td style="border:1px solid black;">
[CVE-2016-3260](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3260)

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
<td style="border:1px solid black;">
[CVE-2016-3264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3264)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

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
[CVE-2016-3265](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3265)

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
<td style="border:1px solid black;">
[CVE-2016-3269](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3269)

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
<td style="border:1px solid black;">
[CVE-2016-3271](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3271)

</td>
<td style="border:1px solid black;">
スクリプト エンジンの情報漏えいの脆弱性

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
[CVE-2016-3273](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3273)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

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
[CVE-2016-3274](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3274)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

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
[CVE-2016-3276](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3276)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

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
[CVE-2016-3277](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3277)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

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
[**MS16-086:JScript および VBScript 用の累積的なセキュリティ更新プログラム (3169996)**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3204](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3204)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-087:Windows 印刷スプーラー用のセキュリティ更新プログラム (3170005)**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3238](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3238)

</td>
<td style="border:1px solid black;">
Windows 印刷スプーラーのリモートでコードが実行される脆弱性

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
[CVE-2016-3239](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3239)

</td>
<td style="border:1px solid black;">
Windows 印刷スプーラーの特権の昇格の脆弱性

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
[**MS16-088:Microsoft Office 用のセキュリティ更新プログラム (3170008)**](http://go.microsoft.com/fwlink/?linkid=808151)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3278](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3278)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

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
[CVE-2016-3279](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3279)

</td>
<td style="border:1px solid black;">
Microsoft Office のセキュリティ機能のバイパスの脆弱性

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
[CVE-2016-3280](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3280)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

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
[CVE-2016-3281](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3281)

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
[CVE-2016-3282](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3282)

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
[CVE-2016-3283](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3283)

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
[CVE-2016-3284](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3284)

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
<td style="border:1px solid black;" colspan="5">
[**MS16-089:Windows 保護カーネル モード用のセキュリティ更新プログラム (3170050)**](http://go.microsoft.com/fwlink/?linkid=808157)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3256)

</td>
<td style="border:1px solid black;">
Windows 保護カーネルの情報漏えいの脆弱性

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
<td style="border:1px solid black;" colspan="5">
[**MS16-090:Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3171481)**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3249)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

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
[CVE-2016-3250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3250)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

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
[CVE-2016-3251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3251)

</td>
<td style="border:1px solid black;">
Win32k の情報漏えいの脆弱性

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
[CVE-2016-3252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3252)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

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
[CVE-2016-3254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3254)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

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
[CVE-2016-3286](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3286)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

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
[**MS16-091:.NET Framework 用のセキュリティ更新プログラム (3170048)**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3255)

</td>
<td style="border:1px solid black;">
.NET の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

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
[**MS16-092:Windows カーネル用のセキュリティ更新プログラム (3171910)**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3258](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3258)

</td>
<td style="border:1px solid black;">
Windows ファイル システムのセキュリティ機能のバイパス

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
[CVE-2016-3272](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3272)

</td>
<td style="border:1px solid black;">
Windows カーネルの情報漏えいの脆弱性

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
[**MS16-093:Adobe Flash Player のセキュリティ更新プログラム (3174060)**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-25](http://helpx.adobe.com/jp/security/products/flash-player/apsb16-25.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度および更新プログラムの優先度の評価については、[Adobe Security Bulletin APSB16-25](http://helpx.adobe.com/jp/security/products/flash-player/apsb16-25.html) を参照してください。

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
<td style="border:1px solid black;" colspan="5">
[**MS16-094:セキュア ブート用のセキュリティ更新プログラム (3177404)**](http://go.microsoft.com/fwlink/?linkid=817339)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3287](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3287)

</td>
<td style="border:1px solid black;">
セキュア ブートのセキュリティ機能のバイパス

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
<td style="border:1px solid black;" colspan="6">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)                   

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)                   

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)                   

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3170106)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3170455)  
(緊急)

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
Internet Explorer 9  
(3170106)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3170455)  
(緊急)

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3170106)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3170455)  
(緊急)

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
Internet Explorer 9  
(3170106)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3170455)  
(緊急)

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
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3170455)  
(緊急)

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
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
(3170455)  
(緊急)

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
Internet Explorer 11  
(3170106)  
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
(3170455)  
(緊急)

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
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
(3170455)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

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
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3170455)  
(緊急)

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
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
(3170455)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
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
(3170455)  
(緊急)

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
(3170106)  
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
(3170455)  
(緊急)

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
(3170106)  
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
(3170455)  
(緊急)

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3170106)  
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
(3170455)  
(緊急)

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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163912)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163912)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163912)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163912)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163912)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163912)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163912)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163912)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3172985)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3172985)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3172985)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3172985)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3172985)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3172985)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3172985)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3172985)  
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
[**MS16-084**](http://go.microsoft.com/fwlink/?linkid=808143)

</td>
<td style="border:1px solid black;">
[**MS16-085**](http://go.microsoft.com/fwlink/?linkid=808148)

</td>
<td style="border:1px solid black;">
[**MS16-086**](http://go.microsoft.com/fwlink/?linkid=808144)

</td>
<td style="border:1px solid black;">
[**MS16-087**](http://go.microsoft.com/fwlink/?linkid=808150)

</td>
<td style="border:1px solid black;">
[**MS16-089**](http://go.microsoft.com/fwlink/?linkid=808157)

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
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3169659)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3170455)  
(緊急)

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
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3169659)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3170455)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

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
JScript 5.8 および VBScript 5.8  
(3169658)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3170455)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

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
Windows Server 2012 (Server Core インストール)  
(3170455)  
(緊急)

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
Windows Server 2012 R2 (Server Core インストール)  
(3170455)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6  
(3164025)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6  
(3164025)  
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
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3163244)  
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
<td style="border:1px solid black;" colspan="6">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
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
<td style="border:1px solid black;" colspan="6">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 8.1 for 32-bit Systems  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3170377)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3175677)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3170377)  
(重要)  
Windows 8.1 for x64-based Systems  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3175677)  
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163246)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163250)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164023)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3170377)  
(重要)  
Windows Server 2012  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3175677)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3170377)  
(重要)  
Windows Server 2012 R2  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3175677)  
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3170377)  
(重要)  
Windows RT 8.1  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3175677)  
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
Windows 10 for 32-bit Systems  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163912)  
(重要)  
Microsoft .NET Framework 4.6  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163912)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163912)  
(重要)  
Microsoft .NET Framework 4.6  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163912)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163912)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3172985)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3172985)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3172985)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3172985)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3174060)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3172985)  
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
[**MS16-090**](http://go.microsoft.com/fwlink/?linkid=808590)

</td>
<td style="border:1px solid black;">
[**MS16-091**](http://go.microsoft.com/fwlink/?linkid=808156)

</td>
<td style="border:1px solid black;">
[**MS16-092**](http://go.microsoft.com/fwlink/?linkid=808706)

</td>
<td style="border:1px solid black;">
[**MS16-093**](http://go.microsoft.com/fwlink/?linkid=809010)

</td>
<td style="border:1px solid black;">
[**MS16-094**](http://go.microsoft.com/fwlink/?linkid=817339)

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
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3168965)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3168965)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3163245)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163251)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164025)  
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

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163246)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163250)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164023)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3170377)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3175677)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3168965)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3163247)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3163291)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3164024)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3170377)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(3169704)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3175677)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115306)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3115311)  
(緊急)

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115315)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3115322)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (32 ビット版)  
(3115246)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32 ビット版)  
(3115118)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3115317)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3115315)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3115322)  
(重要)  
Microsoft Outlook 2010 Service Pack 2 (64 ビット版)  
(3115246)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64 ビット版)  
(3115118)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3115317)  
(緊急)

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3115262)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (32 ビット版)  
(3115259)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (32 ビット版)  
(3115254)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3115292)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3115262)  
(重要)  
Microsoft Outlook 2013 Service Pack 1 (64 ビット版)  
(3115259)  
(重要)  
Microsoft PowerPoint 2013 Service Pack 1 (64 ビット版)  
(3115254)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3115292)  
(緊急)

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Excel 2013 RT Service Pack 1  
(3115262)  
(重要)  
Microsoft Outlook 2013 RT Service Pack 1  
(3115259)  
(重要)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3115254)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3115292)  
(緊急)

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Excel 2016 (32 ビット版)  
(3115272)  
(重要)  
Microsoft Outlook 2016 (32 ビット版)  
(3115279)  
(重要)  
Microsoft Word 2016 (32 ビット版)  
(3115301)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 ビット版)  
(3115272)  
(重要)  
Microsoft Outlook 2016 (64 ビット版)  
(3115279)  
(重要)  
Microsoft Word 2016 (64 ビット版)  
(3115301)  
(緊急)

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3170463)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3170463)  
(緊急)

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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3170460)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3170460)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115308)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(3115309)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3115114)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115393)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115395)  
(緊急)

</td>
</tr>
</table>
 
**MS16-088 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft Office Services および Web Apps

 
<table style="border:1px solid black;">
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115312)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115285)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft SharePoint Server 2016

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2016  
(3115299)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
(3115318)  
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
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3115289)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Office Online Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-088**](http://go.microsoft.com/fwlink/?linkid=808151)

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
Office Online Server

</td>
<td style="border:1px solid black;">
Office Online Server  
(3115386)  
(重要)

</td>
</tr>
</table>
 
**MS16-088 に関する注意事項**

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
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、[謝辞](https://technet.microsoft.com/ja-jp/library/security/mt674627.aspx)を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/ja-jp/kb/894199):Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

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

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについては、サポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/ja-jp/contactus/cu_sc_virsec_master)

国ごとのローカル サポート:[その他の地域のサポート](http://support.microsoft.com/ja-jp/common/international.aspx)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性など、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社およびこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2016/07/13): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2016/08/01): 概要の表の MS16-087 に既知の問題を追加しました。お客様の環境でネットワーク印刷を使用している場合、更新プログラム 3170005 を適用後、プリンター ドライバーのインストールの際に警告が発行されたり、通知なしにドライバーのインストールが失敗することがあります。更新プログラムおよび既知の問題の詳細については、[マイクロソフト サポート技術情報 3170005](https://support.microsoft.com/ja-jp/kb/3170005) を参照してください。
-   V1.2 (2017/03/21): このセキュリティ情報の概要ページを更新し、MS16-084 について Internet Explorer 9、Internet Explorer 10、および Internet Explorer 11 が CVE-2016-3276 の影響を受けないため、Exploitability Index (悪用可能性指標) からこの脆弱性を削除しました。これは情報のみの変更です。

*Page generated 2017-03-17 13:55-07:00.*
