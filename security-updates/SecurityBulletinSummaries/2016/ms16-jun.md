---
TOCTitle: 'MS16-JUN'
Title: 2016 年 6 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms16-jun'
ms:contentKeyID: 73142150
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms16-jun(v=Security.10)'
---

2016 年 6 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2016 年 6 月 15 日 | 最終更新日: 2016 年 8 月 10 日

**バージョン:** 2.2

このセキュリティ情報の概要は 2016 年 6 月公開のセキュリティ情報の一覧です。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798510">MS16-063</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3163649)<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者が影響を受けるコンピューターを制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798511">MS16-068</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3163656)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限を持つユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798411">MS16-069</a></td>
<td style="border:1px solid black;"><strong>JScript および VBScript 用の累積的なセキュリティ更新プログラム (3163640)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の JScript および VBScript スクリプト エンジンに存在する脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web サイトにアクセスすると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。現在のユーザーが管理者ユーザー権限でログオンしているときに、攻撃者によりこれらの脆弱性が悪用された場合、影響を受けるコンピューターが制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798377">MS16-070</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用のセキュリティ更新プログラム (3163610)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798516">MS16-071</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows DNS サーバー用のセキュリティ更新プログラム (3164065)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、DNS サーバーに対して攻撃者が特別に細工された要求を送信した場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798378">MS16-072</a></td>
<td style="border:1px solid black;"><strong>グループ ポリシー用のセキュリティ更新プログラム (3163622)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者がドメイン コントローラーと標的のコンピューターの間のトラフィック受け渡しに対して中間者 (MiTM) 攻撃を実行した場合、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/ja-jp/kb/3159398">3159398</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798502">MS16-073</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3164028)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性で最も深刻なものでは、攻撃者が影響を受けるコンピューターにログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798504">MS16-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3164036)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工されたアプリケーションを開くと、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798505">MS16-075</a></td>
<td style="border:1px solid black;"><strong>Windows SMB サーバー用のセキュリティ更新プログラム (3164038)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/ja-jp/kb/3161561">3161561</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798506">MS16-076</a></td>
<td style="border:1px solid black;"><strong>Netlogon 用のセキュリティ更新プログラム (3167691)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、標的のネットワーク上のドメイン コントローラー (DC) にアクセスできる攻撃者が特別に細工されたアプリケーションを実行し、レプリカ ドメイン コントローラーとして DC へのセキュリティで保護されたチャネルを確立した場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/ja-jp/kb/3161561">3161561</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798850">MS16-077</a></td>
<td style="border:1px solid black;"><strong>WPAD 用のセキュリティ更新プログラム (3165191)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、Web プロキシ自動検出 (WPAD) プロトコルが対象のシステム上の脆弱なプロキシ検出プロセスにフォール バックすると、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=799136">MS16-078</a></td>
<td style="border:1px solid black;"><strong>Windows 診断ハブ用のセキュリティ更新プログラム (3165479)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるシステムにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=787067">MS16-079</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 用のセキュリティ更新プログラム (3160339)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Exchange Server に存在する脆弱性を解決します。この中で最も深刻な脆弱性では、攻撃者が制御する URL から警告またはフィルター処理をされずに読み込まれた Outlook Web Access (OWA) メッセージで、攻撃者が特別に細工した画像の URL を送信した場合に、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798620">MS16-080</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows PDF 用のセキュリティ更新プログラム (3164302)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの中で比較的深刻な脆弱性では、特別に細工された .pdf ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、現在のユーザーのコンテキストで任意のコードが実行される可能性があります。ただし、攻撃者は、特別に細工した .pdf ファイルをユーザーに強制的に開かせることはできません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798515">MS16-081</a></td>
<td style="border:1px solid black;"><strong>Active Directory 用のセキュリティ更新プログラム (3160352)<br />
</strong>このセキュリティ更新プログラムは、Active Directory の脆弱性を解決します。この脆弱性により、認証された攻撃者が複数のコンピューター アカウントを作成した場合にサービス拒否が起こる可能性があります。この脆弱性を悪用するには、攻撃者はコンピューターをドメインに参加させる権限のあるアカウントを取得する必要があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=799040">MS16-082</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows Search コンポーネント用のセキュリティ更新プログラム (3165270)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が標的のシステムにログオンし、特別な細工がされたアプリケーションを実行した場合、サービス拒否が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=798734">MS16-083</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (3167685)<br />
</strong>このセキュリティ更新プログラムは、すべてのサポートされている Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、および Windows 10 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
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
CVE の識別番号

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
[**\[MS16-063\] Internet Explorer 用の累積的なセキュリティ更新プログラム (3163649)**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0199)

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
[CVE-2016-0200](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0200)

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
[CVE-2016-3202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3202)

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
[CVE-2016-3205](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3205)

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
[CVE-2016-3206](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3206)

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
[CVE-2016-3207](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3207)

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
[CVE-2016-3210](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3210)

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
[CVE-2016-3211](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3211)

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
[CVE-2016-3212](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3212)

</td>
<td style="border:1px solid black;">
Internet Explorer XSS フィルターの脆弱性

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
[CVE-2016-3213](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3213)

</td>
<td style="border:1px solid black;">
WPAD の特権の昇格の脆弱性

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
[**\[MS16-068\] Microsoft Edge 用の累積的なセキュリティ更新プログラム (3163656)**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3198](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3198)

</td>
<td style="border:1px solid black;">
Microsoft Edge のセキュリティ機能のバイパス

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
[CVE-2016-3199](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3199)

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
[CVE-2016-3201](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3201)

</td>
<td style="border:1px solid black;">
Windows PDF の情報漏えいの脆弱性

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
[CVE-2016-3202](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3202)

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
[CVE-2016-3203](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3203)

</td>
<td style="border:1px solid black;">
Windows PDF のリモートでコードが実行される脆弱性

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
[CVE-2016-3214](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3214)

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
[CVE-2016-3215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3215)

</td>
<td style="border:1px solid black;">
Windows PDF の情報漏えいの脆弱性

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
[CVE-2016-3222](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3222)

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
<td style="border:1px solid black;" colspan="5">
[**\[MS16-069\] JScript および VBScript 用の累積的なセキュリティ更新プログラム (3163640)**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3205](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3205)

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
[CVE-2016-3206](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3206)

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
[CVE-2016-3207](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3207)

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
[**\[MS16-070\] Microsoft Office 用のセキュリティ更新プログラム (3163610)**](http://go.microsoft.com/fwlink/?linkid=798377)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0025](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0025)

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
[CVE-2016-3233](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3233)

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
[CVE-2016-3234](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3234)

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
[CVE-2016-3235](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3235)

</td>
<td style="border:1px solid black;">
Microsoft Office OLE DLL のサイド ローディングの脆弱性

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
[**\[MS16-071\] Microsoft Windows DNS サーバー用のセキュリティ更新プログラム (3164065)**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3227](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3227)

</td>
<td style="border:1px solid black;">
Windows DNS サーバーの解放後使用の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS16-072\] グループ ポリシー用のセキュリティ更新プログラム (3163622)**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3223](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3223)

</td>
<td style="border:1px solid black;">
グループ ポリシーの特権の昇格の脆弱性

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
[**\[MS16-073\] Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3164028)**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3218](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3218)

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
[CVE-2016-3221](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3221)

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
[CVE-2016-3232](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3232)

</td>
<td style="border:1px solid black;">
Windows Virtual PCI の情報漏えいの脆弱性

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
[**\[MS16-074\] Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3164036)**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3216](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3216)

</td>
<td style="border:1px solid black;">
Windows Graphics コンポーネントの情報漏えいの脆弱性

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
[CVE-2016-3219](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3219)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

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
[CVE-2016-3220](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3220)

</td>
<td style="border:1px solid black;">
ATMFD.DLL の特権の昇格の脆弱性

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
[**\[MS16-075\] Windows SMB サーバー用のセキュリティ更新プログラム (3164038)**](http://go.microsoft.com/fwlink/?linkid=798505)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3225](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3225)

</td>
<td style="border:1px solid black;">
Windows SMB サーバーの特権の昇格の脆弱性

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
<td style="border:1px solid black;" colspan="5">
[**\[MS16-076\] Netlogon 用のセキュリティ更新プログラム (3167691)**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3228](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3228)

</td>
<td style="border:1px solid black;">
Windows Netlogon のメモリ破損によりリモートでコードが実行される脆弱性

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
[**\[MS16-077\] WPAD 用のセキュリティ更新プログラム (3165191)**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3213](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3213)

</td>
<td style="border:1px solid black;">
Windows WPAD の特権の昇格の脆弱性

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
[CVE-2016-3236](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3236)

</td>
<td style="border:1px solid black;">
Windows WPAD のプロキシ検出の特権の昇格の脆弱性

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
[CVE-2016-3299](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3299)

</td>
<td style="border:1px solid black;">
NetBIOS スプーフィングの脆弱性

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
[**\[MS16-078\] Windows 診断ハブ用のセキュリティ更新プログラム (3165479)**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3231](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3231)

</td>
<td style="border:1px solid black;">
Windows 診断ハブの特権の昇格の脆弱性

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
[**\[MS16-079\] Microsoft Exchange Server 用のセキュリティ更新プログラム (3160339)**](http://go.microsoft.com/fwlink/?linkid=787067)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0028](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0028)

</td>
<td style="border:1px solid black;">
Microsoft Exchange の情報漏えいの脆弱性

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
<td style="border:1px solid black;" colspan="5">
[**\[MS16-080\] Microsoft Windows PDF 用のセキュリティ更新プログラム (3164302)**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3201](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3201)

</td>
<td style="border:1px solid black;">
Windows PDF の情報漏えいの脆弱性

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
[CVE-2016-3203](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3203)

</td>
<td style="border:1px solid black;">
Windows PDF のリモートでコードが実行される脆弱性

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
[CVE-2016-3215](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3215)

</td>
<td style="border:1px solid black;">
Windows PDF の情報漏えいの脆弱性

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
[**\[MS16-081\] Active Directory 用のセキュリティ更新プログラム (3160352)**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3226](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3226)

</td>
<td style="border:1px solid black;">
Active Directory のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS16-082\] Microsoft Windows Search コンポーネント用のセキュリティ更新プログラム (3165270)**](http://go.microsoft.com/fwlink/?linkid=786475)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-3230](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-3230)

</td>
<td style="border:1px solid black;">
Windows Search コンポーネントのサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS16-083\] Adobe Flash Player のセキュリティ更新プログラム (3167685)**](http://go.microsoft.com/fwlink/?linkid=798734)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-18](http://helpx.adobe.com/jp/security/products/flash-player/apsb16-18.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度および更新プログラムの優先度の評価については、[Adobe Security Bulletin APSB16-18](http://helpx.adobe.com/jp/security/products/flash-player/apsb16-18.html) を参照してください。

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
 

影響を受けるソフトウェア
------------------------

<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。

**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントを基に、インストールする必要がある更新プログラムを確認してください。

 

### Windows オペレーティング システムとコンポーネント (表 1/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
(3160005)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158364)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3164033)  
(重要)  
Windows Vista Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158364)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3164033)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
(3160005)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158364)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3164033)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3160005)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158364)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3164033)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3161561)  
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
(3158364)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3164033)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3164033)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3164033)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3164033)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3161561)  
(重要)

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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3164033)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3164033)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3164033)  
(重要)  
Windows 8.1 for x64-based Systems  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
Internet Explorer 10  
(3160005)  
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
(3161951)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161664)  
(重要)  
Windows Server 2012  
(3164294)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3164033)  
(重要)  
Windows Server 2012  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
(3161951)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161664)  
(重要)  
Windows Server 2012 R2  
(3164294)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3164033)  
(重要)  
Windows Server 2012 R2  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3160005)  
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
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3164033)  
(重要)  
Windows RT 8.1  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3161561)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163017)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163017)  
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
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163017)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163017)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163017)  
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
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163017)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163018)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163018)  
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
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3163018)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3163018)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3163018)  
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
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3163018)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-063**](http://go.microsoft.com/fwlink/?linkid=798510)

</td>
<td style="border:1px solid black;">
[**MS16-068**](http://go.microsoft.com/fwlink/?linkid=798511)

</td>
<td style="border:1px solid black;">
[**MS16-069**](http://go.microsoft.com/fwlink/?linkid=798411)

</td>
<td style="border:1px solid black;">
[**MS16-071**](http://go.microsoft.com/fwlink/?linkid=798516)

</td>
<td style="border:1px solid black;">
[**MS16-072**](http://go.microsoft.com/fwlink/?linkid=798378)

</td>
<td style="border:1px solid black;">
[**MS16-073**](http://go.microsoft.com/fwlink/?linkid=798502)

</td>
<td style="border:1px solid black;">
[**MS16-074**](http://go.microsoft.com/fwlink/?linkid=798504)

</td>
<td style="border:1px solid black;">
[**MS16-075**](http://go.microsoft.com/fwlink/?linkid=798505)

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
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158364)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3164033)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3161561)  
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
(3158364)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3164033)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3161561)  
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
JScript 5.8 および VBScript 5.8  
(3158363)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3161664)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3164033)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3161561)  
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
Windows Server 2012 (Server Core インストール)  
(3161951)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3161664)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(3164294)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3164033)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3161561)  
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
Windows Server 2012 R2 (Server Core インストール)  
(3161951)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3159398)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3161664)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(3164294)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3164033)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(3164035)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3161561)  
(重要)

</td>
</tr>
</table>
 
 

### Windows オペレーティング システムとコンポーネント (表 2/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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
**なし**

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
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3161949)  
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
(3161949)  
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
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3161949)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3161949)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3161949)  
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
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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
**なし**

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

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3161949)  
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
Windows 7 for 32-bit Systems Service Pack 1  
(3161958)  
(重要)

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
Windows 7 for x64-based Systems Service Pack 1  
(3161949)  
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
Windows 7 for x64-based Systems Service Pack 1  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3161949)  
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
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3161958)  
(重要)

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
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3161949)  
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
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3157569)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
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
Windows 8.1 for x64-based Systems  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3157569)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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
Windows Server 2012  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3157569)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3162343)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161949)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3157569)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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
**なし**

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

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3161949)  
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
Windows RT 8.1  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(緊急)

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
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3163017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(緊急)

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
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(緊急)

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
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3163018)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3167685)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="8">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-076**](http://go.microsoft.com/fwlink/?linkid=798506)

</td>
<td style="border:1px solid black;">
[**MS16-077**](http://go.microsoft.com/fwlink/?linkid=798850)

</td>
<td style="border:1px solid black;">
[**MS16-078**](http://go.microsoft.com/fwlink/?linkid=799136)

</td>
<td style="border:1px solid black;">
[**MS16-080**](http://go.microsoft.com/fwlink/?linkid=798620)

</td>
<td style="border:1px solid black;">
[**MS16-081**](http://go.microsoft.com/fwlink/?linkid=798515)

</td>
<td style="border:1px solid black;">
[**MS16-082**](http://go.microsoft.com/fwlink/?linkid=799040)

</td>
<td style="border:1px solid black;">
[**MS16-083**](http://go.microsoft.com/fwlink/?linkid=798734)

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
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3161949)  
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
(3161949)  
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
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3161949)  
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
(Server Core インストール)  
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3161958)  
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

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3161561)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3161949)  
(重要)

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
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3161958)  
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
Windows Server 2012 R2  
(Server Core インストール)  
(3162343)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3161949)  
(重要)

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
(3160352)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3161958)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115107)  
(重要)  
Microsoft Visio 2007 Service Pack 3  
(3114740)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3115195)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115198)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3115130)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (32 ビット版)  
(3114872)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3115243)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3115198)  
(緊急)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3115130)  
(重要)  
Microsoft Visio 2010 Service Pack 2 (64 ビット版)  
(3114872)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3115243)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
Microsoft Visio 2013 Service Pack 1 (32 ビット版)  
(3115020)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3115173)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Visio 2013 Service Pack 1 (64 ビット版)  
(3115020)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3115173)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
Microsoft Word 2013 RT Service Pack 1  
(3115173)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115144)  
(重要)  
Microsoft Visio 2016 (32 ビット版)  
(3115041)  
(重要)  
Microsoft Word 2016 (32 ビット版)  
(3115182)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)  
(3115144)  
(重要)  
Microsoft Visio 2016 (64 ビット版)  
(3115041)  
(重要)  
Microsoft Word 2016 (64 ビット版)  
(3115182)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
Microsoft Word for Mac 2011  
(3165796)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
Microsoft Word 2016 for Mac  
(3165798)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115111)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(3115194)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2007 Service Pack 3  
(2596915)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 (32 ビット版)  
(2999465)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 (64 ビット版)  
(2999465)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115187)  
(重要)

</td>
</tr>
</table>
 
**MS16-070 に関する注意事項**

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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115196)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115014)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115244)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115170)  
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
[**MS16-070**](http://go.microsoft.com/fwlink/?linkid=798377)

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
(3115134)  
(重要)

</td>
</tr>
</table>
 
**MS16-070 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft サーバー ソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-079**](http://go.microsoft.com/fwlink/?linkid=787067)

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
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(3151086)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-079**](http://go.microsoft.com/fwlink/?linkid=787067)

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
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(3151097)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-079**](http://go.microsoft.com/fwlink/?linkid=787067)

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
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3150501)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 11

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 11  
(3150501)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 12

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 12  
(3150501)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-079**](http://go.microsoft.com/fwlink/?linkid=787067)

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
Microsoft Exchange Server 2016

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016  
(3150501)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 の累積的な更新プログラム 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 の累積的な更新プログラム 1  
(3150501)  
(重要)

</td>
</tr>
</table>
 

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

-   V1.0 (2016/06/15): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2016/06/16): 概要の表の MS16-072 に既知の問題を追加しました。MS16-072 の更新プログラムは、ユーザー グループ ポリシーが取得されるセキュリティ コンテキストを変更します。この仕様上の動作変更の詳細については、[サポート技術情報 3163622](https://support.microsoft.com/ja-jp/kb/3163622) を参照してください。MS16-074 について概要を更新し、攻撃手段の説明を修正しました。これは、情報のみの変更です。
-   V2.0 (2016/06/17): このセキュリティ情報の概要ページを更新し、定例外のセキュリティ情報 MS16-083 の公開をお知らせしました。
-   V2.1 (2016/06/23): 更新プログラム 3161561 について、概要の表の MS16-075 および MS16-076 に既知の問題を追加しました。UNC Hardened Access 機能を使用して相互認証を必要とするよう構成されたコンピューターのドメイン DFS 名前空間 (たとえば、\\\\contoso.com\\SYSVOL) にアクセスしようとすると、「アクセス拒否」のエラー メッセージが表示されます。マイクロソフトは引き続きこの問題について調査し、詳細情報が提供可能になり次第この情報ページで公開する予定です。詳細情報については、[サポート技術情報 3161561](https://support.microsoft.com/ja-jp/kb/3161561) 参照してください。
-   V2.2 (2016/08/10): セキュリティ情報のページを更新し、MS16-077 について脆弱性 CVE-2016-3299 を追加しました。これは情報のみの変更です。既に正常に更新プログラムをインストールされたお客様は、特別な措置を講じる必要はありません。

*Page generated 2016-08-09 17:39-07:00.*
