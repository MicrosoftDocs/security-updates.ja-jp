---
TOCTitle: 'MS16-MAY'
Title: 2016 年 5 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms16-may'
ms:contentKeyID: 72963735
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms16-may(v=Security.10)'
---

2016 年 5 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2016 年 5 月 11 日 | 最終更新日:2016 年 5 月 27 日

**バージョン:** 2.1

このセキュリティ情報の概要は 2016 年 5 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=785873">MS16-051</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3155533)<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者が影響を受けるコンピューターを制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=785874">MS16-052</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3155538)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限を持つユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=786478">MS16-053</a></td>
<td style="border:1px solid black;"><strong>JScript および VBScript 用の累積的なセキュリティ更新プログラム (3156764)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の JScript および VBScript スクリプト エンジンに存在する脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web サイトにアクセスすると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。現在のユーザーが管理者ユーザー権限でログオンしているときに、攻撃者によりこれらの脆弱性が悪用された場合、影響を受けるコンピューターが制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=785875">MS16-054</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用のセキュリティ更新プログラム (3155544)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性で、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=786471">MS16-055</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3156754)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工されたドキュメントを開くか、特別に細工された Web サイトにアクセスすると、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=786477">MS16-056</a></td>
<td style="border:1px solid black;"><strong>Windows Journal 用のセキュリティ更新プログラム (3156761)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性で、特別に細工されたジャーナル ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=786534">MS16-057</a></td>
<td style="border:1px solid black;"><strong>Windows Shell 用のセキュリティ更新プログラム (3156987)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が、ユーザーが提供するオンライン コンテンツを受け入れる特別に細工された Web サイトを閲覧するようにユーザーを誘導するか、特別に細工されたコンテンツを開くようにユーザーを誘導した場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=746884">MS16-058</a></td>
<td style="border:1px solid black;"><strong>Windows IIS 用のセキュリティ更新プログラム (3141083)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、ローカル システムにアクセスできる攻撃者が悪意のあるアプリケーションを実行すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=786468">MS16-059</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center 用のセキュリティ更新プログラム (3150220)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、Windows Media Center で悪意のあるコードを参照する特別に細工された Media Center リンク (.mcl) ファイルを開いた場合にリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。システムに関するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=785239">MS16-060</a></td>
<td style="border:1px solid black;"><strong>Windows カーネル用のセキュリティ更新プログラム (3154846)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるシステムにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=785871">MS16-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft RPC 用のセキュリティ更新プログラム (3155520)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、認証された攻撃者が、影響を受けるホストに無効な形式のリモート プロシージャ コール (RPC) 要求を行った場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=786923">MS16-062</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3158222)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性で比較的深刻なものでは、攻撃者が影響を受けるコンピューターにログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=789066">MS16-064</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (3157993)</strong><br />
このセキュリティ更新プログラムは、すべてのサポートされている Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、および Windows 10 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe® Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=786473">MS16-065</a></td>
<td style="border:1px solid black;"><strong>.NET Framework 用のセキュリティ更新プログラム (3156757)<br />
</strong>このセキュリティ更新プログラムは、Microsoft .NET Framework の脆弱性を解決します。この脆弱性により、攻撃者が標的のセキュリティで保護されたチャネルに暗号化されていないデータを挿入してから、標的のクライアントと正規のサーバーの間で 中間者攻撃 (MiTM) を実行した場合に、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3156757">3156757</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=785792">MS16-066</a></td>
<td style="border:1px solid black;"><strong>仮想保護モード用のセキュリティ更新プログラム (3155451)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工したアプリケーションを実行して Windows におけるコードの整合性の保護をバイパスした場合に、セキュリティ機能のバイパスが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=786475">MS16-067</a></td>
<td style="border:1px solid black;"><strong>ボリューム マネージャー ドライバー用のセキュリティ更新プログラム (3155784)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、Microsoft RemoteFX を介してリモート デスクトップ プロトコル (RDP) 経由でマウントされた USB ディスクが、マウント側ユーザーのセッションに正しく関連付けられていない場合、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
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
[**\[MS16-051\] Internet Explorer 用の累積的なセキュリティ更新プログラム (3155533)**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)

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
[CVE-2016-0188](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0188)

</td>
<td style="border:1px solid black;">
Internet Explorer のセキュリティ機能のバイパス

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
[CVE-2016-0189](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

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
<td style="border:1px solid black;">
[CVE-2016-0192](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

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
[CVE-2016-0194](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0194)

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
<td style="border:1px solid black;" colspan="5">
[**\[MS16-052\] Microsoft Edge 用の累積的なセキュリティ更新プログラム (3155538)**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0186](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0186)

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
[CVE-2016-0191](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0191)

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
[CVE-2016-0192](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0192)

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
[CVE-2016-0193](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0193)

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
[**\[MS16-053\] JScript および VBScript 用の累積的なセキュリティ更新プログラム (3156764)**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0187](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0187)

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
[CVE-2016-0189](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0189)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

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
[**\[MS16-054\] Microsoft Office 用のセキュリティ更新プログラム (3155544)**](https://go.microsoft.com/fwlink/?linkid=785875)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0126](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0126)

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
[CVE-2016-0140](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0140)

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
[CVE-2016-0183](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0183)

</td>
<td style="border:1px solid black;">
Microsoft Office Graphics の RCE の脆弱性

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
[CVE-2016-0198](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0198)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**\[MS16-055\] Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3156754)**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0168](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0168)

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
一時的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0169](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0169)

</td>
<td style="border:1px solid black;">
Windows Graphics コンポーネントの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
一時的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0170](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0170)

</td>
<td style="border:1px solid black;">
Windows Graphics コンポーネントの RCE の脆弱性

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
[CVE-2016-0184](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0184)

</td>
<td style="border:1px solid black;">
Direct3D の解放後使用の脆弱性

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
[CVE-2016-0195](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0195)

</td>
<td style="border:1px solid black;">
Windows Imaging Component のメモリ破損の脆弱性

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
[**\[MS16-056\] Windows Journal 用のセキュリティ更新プログラム (3156761)**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0182](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0182)

</td>
<td style="border:1px solid black;">
Journal のメモリ破損の脆弱性

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
[**\[MS16-057\] Windows Shell 用のセキュリティ更新プログラム (3156987)**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0179](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0179)

</td>
<td style="border:1px solid black;">
Windows Shell のリモートでコードが実行される脆弱性

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
[**\[MS16-058\] Windows IIS 用のセキュリティ更新プログラム (3141083)**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0152](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0152)

</td>
<td style="border:1px solid black;">
Windows DLL 読み込みのリモートでコードが実行される脆弱性

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
[**\[MS16-059\] Windows Media Center 用のセキュリティ更新プログラム (3150220)**](https://go.microsoft.com/fwlink/?linkid=786468)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0185](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0185)

</td>
<td style="border:1px solid black;">
Windows Media Center のリモートでコードが実行される脆弱性

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
[**\[MS16-060\] Windows カーネル用のセキュリティ更新プログラム (3154846)**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0180](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0180)

</td>
<td style="border:1px solid black;">
Windows カーネルの特権の昇格の脆弱性

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
[**\[MS16-061\] Microsoft RPC 用のセキュリティ更新プログラム (3155520)**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0178](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0178)

</td>
<td style="border:1px solid black;">
RPC Network Data Representation Engine のリモートでコードが実行される脆弱性

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
[**\[MS16-062\] Windows カーネルモード ドライバー用のセキュリティ更新プログラム (3158222)**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0171](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0171)

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
[CVE-2016-0173](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0173)

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
[CVE-2016-0174](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0174)

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
[CVE-2016-0175](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0175)

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
[CVE-2016-0176](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0176)

</td>
<td style="border:1px solid black;">
Microsoft DirectX グラフィック カーネル サブシステムの特権の昇格の脆弱性

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
[CVE-2016-0196](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0196)

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
[CVE-2016-0197](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0197)

</td>
<td style="border:1px solid black;">
Microsoft DirectX グラフィック カーネル サブシステムの特権の昇格の脆弱性

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
[**\[MS16-064\] Adobe Flash Player のセキュリティ更新プログラム (3157993)**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-15](https://helpx.adobe.com/jp/security/products/flash-player/apsb16-15.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度および更新プログラムの優先度の評価については、[Adobe Security Bulletin APSB16-15](https://helpx.adobe.com/jp/security/products/flash-player/apsb16-15.html) を参照してください。

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
[**\[MS16-065\] .NET Framework 用のセキュリティ更新プログラム (3156757)**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0149](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0149)

</td>
<td style="border:1px solid black;">
TLS/SSL の情報漏えいの脆弱性

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
[**\[MS16-066\] 仮想保護モード用のセキュリティ更新プログラム (3155451)**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0181](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0181)

</td>
<td style="border:1px solid black;">
ハイパーバイザーによるコードの整合性のセキュリティ機能のバイパス

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
[**\[MS16-067\] ボリューム マネージャー ドライバー用のセキュリティ更新プログラム (3155784)**](https://go.microsoft.com/fwlink/?linkid=786475)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0190](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0190)

</td>
<td style="border:1px solid black;">
リモート デスクトップ プロトコルのドライブ リダイレクトの情報漏えいの脆弱性

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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158991)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3156013)  
(緊急)  
Windows Vista Service Pack 2  
(3156016)  
(緊急)  
Windows Vista Service Pack 2  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3155178)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3141083)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3154070)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158991)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3156013)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(3156016)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3155178)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3141083)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3150220)  
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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3154070)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158991)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3156013)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3156016)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3141083)  
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
Internet Explorer 9  
(3154070)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158991)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3156013)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3156016)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3141083)  
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
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158991)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3156013)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3141083)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(3156016)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3155178)  
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
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(3156016)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3155178)  
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
(3150220)  
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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3156016)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3156019)  
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
(3156013)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3156016)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3156019)  
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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(3156016)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3155178)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3156059)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3150220)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(緊急)  
Windows 8.1 for x64-based Systems  
(3156016)  
(緊急)  
Windows 8.1 for x64-based Systems  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3155178)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3156059)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3150220)  
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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3154070)  
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
(3156013)  
(緊急)  
Windows Server 2012  
(3156016)  
(緊急)  
Windows Server 2012  
(3156019)  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(緊急)  
Windows Server 2012 R2  
(3156016)  
(緊急)  
Windows Server 2012 R2  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3156059)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3154070)  
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
(3156013)  
(緊急)  
Windows RT 8.1  
(3156016)  
(緊急)  
Windows RT 8.1  
(3156019)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3155178)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3156059)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156387)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3156387)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3156387)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3156387)  
(緊急)

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
(3156387)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156387)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3156387)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3156387)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3156387)  
(緊急)

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
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3156421)  
(緊急)

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
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3156421)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-051**](https://go.microsoft.com/fwlink/?linkid=785873)

</td>
<td style="border:1px solid black;">
[**MS16-052**](https://go.microsoft.com/fwlink/?linkid=785874)

</td>
<td style="border:1px solid black;">
[**MS16-053**](https://go.microsoft.com/fwlink/?linkid=786478)

</td>
<td style="border:1px solid black;">
[**MS16-055**](https://go.microsoft.com/fwlink/?linkid=786471)

</td>
<td style="border:1px solid black;">
[**MS16-056**](https://go.microsoft.com/fwlink/?linkid=786477)

</td>
<td style="border:1px solid black;">
[**MS16-057**](https://go.microsoft.com/fwlink/?linkid=786534)

</td>
<td style="border:1px solid black;">
[**MS16-058**](https://go.microsoft.com/fwlink/?linkid=746884)

</td>
<td style="border:1px solid black;">
[**MS16-059**](https://go.microsoft.com/fwlink/?linkid=786468)

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
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3158991)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3156013)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3156016)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3156019)  
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
(3141083)  
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
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3158991)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3156013)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3156016)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3156019)  
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
(3141083)  
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

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
JScript 5.8 および VBScript 5.8  
(3155413)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3156013)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3156016)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3156019)  
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
(3156013)  
(緊急)  
Windows Server 2012 (Server Core インストール)  
(3156016)  
(緊急)  
Windows Server 2012 (Server Core インストール)  
(3156019)  
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
(3156013)  
(緊急)  
Windows Server 2012 R2 (Server Core インストール)  
(3156016)  
(緊急)  
Windows Server 2012 R2 (Server Core インストール)  
(3156019)  
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
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3153199)  
(重要)  
Windows Vista Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3153199)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6  
(3142037)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3153199)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3153199)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6  
(3142037)  
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
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3153199)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3142023)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3153199)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3153199)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3153199)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3153199)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3153199)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3153199)  
(重要)  
Windows 8.1 for x64-based Systems  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
<td style="border:1px solid black;" colspan="8">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3153199)  
(重要)  
Windows Server 2012  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142032)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3155784)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3153199)  
(重要)  
Windows Server 2012 R2  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3155784)  
(重要)

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
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3153199)  
(重要)  
Windows RT 8.1  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
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
<td style="border:1px solid black;" colspan="8">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
(重要)  
Microsoft .NET Framework 4.6  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3156387)  
(重要)

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
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156387)  
(重要)  
Microsoft .NET Framework 4.6  
(3156387)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3156387)  
(重要)

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
Windows 10 Version 1511 for 32-bit Systems  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3156421)  
(重要)

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
Windows 10 Version 1511 for x64-based Systems  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3163207)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3156421)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3156421)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS16-060**](https://go.microsoft.com/fwlink/?linkid=785239)

</td>
<td style="border:1px solid black;">
[**MS16-061**](https://go.microsoft.com/fwlink/?linkid=785871)

</td>
<td style="border:1px solid black;">
[**MS16-062**](https://go.microsoft.com/fwlink/?linkid=786923)

</td>
<td style="border:1px solid black;">
[**MS16-064**](https://go.microsoft.com/fwlink/?linkid=789066)

</td>
<td style="border:1px solid black;">
[**MS16-065**](https://go.microsoft.com/fwlink/?linkid=786473)

</td>
<td style="border:1px solid black;">
[**MS16-066**](https://go.microsoft.com/fwlink/?linkid=785792)

</td>
<td style="border:1px solid black;">
[**MS16-067**](https://go.microsoft.com/fwlink/?linkid=786475)

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
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3153199)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)  
(3156017)  
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
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3153199)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3156017)  
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
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3153199)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3142024)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142033)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142037)  
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
Windows Server 2012  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3153199)  
(重要)  
Windows Server 2012  
(Server Core インストール)  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142025)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142032)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142035)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3155784)  
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
(3153171)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3153704)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3153199)  
(重要)  
Windows Server 2012 R2  
(Server Core インストール)  
(3156017)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3142026)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3142030)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3142036)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3155784)  
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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2984938)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2984943)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3115116)  
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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3115121)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3054984)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3101520)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3115123)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3115121)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3054984)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3101520)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3115123)  
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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(3115016)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3115025)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(3115016)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3115025)  
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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3115016)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3115025)  
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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)  
(3115103)  
(重要)  
Microsoft Word 2016 (32 ビット版)  
(3115094)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)  
(3115103)  
(重要)  
Microsoft Word 2016 (64 ビット版)  
(3115094)  
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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Word for Mac 2011  
(3155776)  
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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 for Mac  
(3155777)  
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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(3115115)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3115132)  
(緊急)

</td>
</tr>
</table>
 
 

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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(3115117)  
(緊急)

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
[**MS16-054**](https://go.microsoft.com/fwlink/?linkid=785875)

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
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3115124)  
(緊急)

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

利用可能なこれらのツールおよび他のツールの詳細については、「[セキュリティ ツール](https://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。

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

-   V1.0 (2016/05/11):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2016/05/12):このセキュリティ情報の概要ページを更新し、MS16-061 の脆弱性の影響を「特権の昇格」から「リモートでコードが実行される」に変更しました。また、CVE 2016-0178 のタイトルを「RPC Network Data Representation Engine のリモートでコードが実行される脆弱性」に変更しました。これは、情報のみの変更です。
-   V1.2 (2016/05/16):このセキュリティ情報の概要ページを更新し、MS16-067 において Windows 8.1 および Windows RT 8.1 がこのセキュリティ情報で説明されている脆弱性による影響を受けないため、脆弱性の深刻度を「対象外」に変更しました。既に更新プログラム 3155784 を適用されたお客様は、特別な措置を講じる必要はありません。これは、情報のみの変更です。
-   V2.0 (2016/05/16):このセキュリティ情報の概要ページを更新し、MS16-064 について Adobe Security Bulletin APSB16-15 に含まれる脆弱性を解決する更新プログラム 3163207 のリリースをお知らせします。更新プログラム 3163207 は、以前このセキュリティ情報で提供していた更新プログラムを置き換えます (更新プログラム 3157993)。マイクロソフトは、Adobe Security Bulletin APSB16-15 で説明されている脆弱性からシステムを保護するために、更新プログラム 3163207 を直ちにインストールすることを強く推奨します。
-   V2.1 (2016/05/27):概要の表の MS16-065 に既知の問題を追加しました。Lync Server 2010、Lync Server 2013、または Skype for Business Server 2015 のフロント エンド サーバーまたは Standard Edition Server 上で MS16-065 に含まれているいずれかのセキュリティ更新プログラムをインストールした後で、内部ユーザー向けのいくつかの会議モダリティが機能しなくなります。この既知の問題の解決策に関する詳細は、[サポート技術情報 3165438](https://support.microsoft.com/ja-jp/kb/3165438) を参照してください。

*Page generated 2016-05-25 12:52-07:00.*
