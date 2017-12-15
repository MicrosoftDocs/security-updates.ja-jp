---
TOCTitle: 'MS16-FEB'
Title: 2016 年 2 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms16-feb'
ms:contentKeyID: 72238930
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms16-feb(v=Security.10)'
---

2016 年 2 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日: 2016 年 2 月 10 日 | 最終更新日: 2016 年 2 月 25 日

**バージョン:** 3.1

このセキュリティ情報の概要は 2016 年 2 月公開のセキュリティ情報の一覧です。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722212">MS16-009</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3134220)</strong> <br />
このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしているときに、攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピューターが制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3134814">3134814</a></td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722213">MS16-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (3134225)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=623622">MS16-012</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Windows PDF ライブラリ用のセキュリティ更新プログラム (3138938)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。Microsoft Windows PDF ライブラリによるアプリケーション プログラム インターフェイス (API) の呼び出しが適切に実施されない場合、リモートでのコード実行の脆弱性はより深刻なものとなり、攻撃者によって任意のコードがユーザーのシステム上で実行される可能性も高まります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。ただし、攻撃者も悪意を持って作成した PDF 文書をダウンロードしたり開いたりするよう強制することはできません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722340">MS16-013</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Windows Journal 用のセキュリティ更新プログラム (3134811)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性で、特別に細工されたジャーナル ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722215">MS16-014</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Windows 用のセキュリティ更新プログラム (3134228)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性のもっとも深刻な点は、攻撃者がターゲットとするシステムにログオンし、特別に細工されたアプリケーションを実行することができる場合、リモートでのコード実行が可能になるおそれがあることです。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3126041">3126041</a><br />
<a href="https://support.microsoft.com/kb/3126587">3126587</a><br />
<a href="https://support.microsoft.com/kb/3126593">3126593</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722214">MS16-015</a></td>
<td style="border:1px solid black;"><strong>リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3134226)</strong><br />
このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722536">MS16-016</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する WebDAV 用のセキュリティ更新プログラム (3136041)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が Microsoft Web Distributed Authoring and Versioning (WebDAV) クライアントを使用して特別に細工された入力をサーバーに送付した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722326">MS16-017</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処するリモート デスクトップ ディスプレイ ドライバー用のセキュリティ更新プログラム (3134700)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、認証された攻撃者が RDP を使用して目標のシステムにログオンし特別に細工されたデータを接続経由で送信した場合、特権が昇格される可能性があります。RDP は、サポートされている Windows オペレーティング システムでは既定で有効ではありません。RDP が有効となっていないコンピューターは危険にさらされません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/ja-jp/kb/3134700">3134700</a><br />
<a href="https://support.microsoft.com/ja-jp/kb/3126446">3126446</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722617">MS16-018</a></td>
<td style="border:1px solid black;"><strong>特権の昇格に対処する Windows カーネル モード ドライバー用のセキュリティ更新プログラム (3136082)</strong> <br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるシステムにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=718008">MS16-019</a></td>
<td style="border:1px solid black;"><strong>サービス拒否に対処する .NET Framework 用のセキュリティ更新プログラム (3137893)<br />
</strong>このセキュリティ更新プログラムは、Microsoft .NET Framework の脆弱性を解決します。攻撃者がクライアント側の XML Web パーツに特別に細工された XSLT を挿入した場合、この脆弱性はより深刻なものとなり、サーバーで XSLT 変換が繰り返しコンパイルされ、サービス拒否状態になるおそれがあります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722534">MS16-020</a></td>
<td style="border:1px solid black;"><strong>サービス拒否に対処する Active Directory フェデレーション サービス用のセキュリティ更新プログラム (3134222) <br />
</strong>このセキュリティ更新プログラムは、Active Directory フェデレーション サービス (ADFS) の脆弱性を解決します。攻撃者が ADFS サーバーに対するフォームベースの認証中に特定の入力データを送付した場合、サーバーは応答不能となり、サービス拒否状態になるおそれがあります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=722535">MS16-021</a></td>
<td style="border:1px solid black;"><strong>サービス拒否に対処する NPS RADIUS サーバー用のセキュリティ更新プログラム (3133043)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。攻撃者がネットワークポリシーサーバー (NPS) に特別に細工されたユーザー名を送付した場合に NPS での RADIUS 認証が妨げられ、サービス拒否状態になるおそれがあります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=723603">MS16-022</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (3135782)<br />
</strong>このセキュリティ更新プログラムは、すべてのサポートされている Windows Server 2012、Windows 8.1、Windows Server 2012 R2、Windows RT 8.1、および Windows 10 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows<br />
Adobe® Flash Player</td>
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
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-009:Internet Explorer 用の累積的なセキュリティ更新プログラム (3134220)**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0041](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)

</td>
<td style="border:1px solid black;">
DLL 読み込みのリモート コード実行の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0059](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0059)

</td>
<td style="border:1px solid black;">
Internet Explorer の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0063](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0063)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0064](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0064)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0067](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0067)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0068](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0068)

</td>
<td style="border:1px solid black;">
Internet Explorer 特権の昇格の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0069](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0069)

</td>
<td style="border:1px solid black;">
Internet Explorer 特権の昇格の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0071](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0071)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0072](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0072)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-011:Microsoft Edge 用の累積的なセキュリティ更新プログラム (3134225)**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0060)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0061)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0062)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリの破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0077](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0077)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0080)

</td>
<td style="border:1px solid black;">
Microsoft Edge ASLR バイパス

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0084)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-012:リモートでのコード実行に対処する Microsoft Windows PDF ライブラリ用のセキュリティ更新プログラム (3138938)**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0046](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0046)

</td>
<td style="border:1px solid black;">
Microsoft Windows Reader の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0058](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0058)

</td>
<td style="border:1px solid black;">
Microsoft PDF ライブラリ バッファ オーバーフローの脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-013:リモートでのコード実行に対処する Windows Journal 用のセキュリティ更新プログラム (3134811)**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0038](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0038)

</td>
<td style="border:1px solid black;">
Windows ジャーナルのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-014:リモートでのコード実行に対処する Microsoft Windows 用のセキュリティ更新プログラム (3134228)**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0040](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0040)

</td>
<td style="border:1px solid black;">
Windows の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0041](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0041)

</td>
<td style="border:1px solid black;">
DLL 読み込みのリモート コード実行の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0042)

</td>
<td style="border:1px solid black;">
Windows DLL 読み込みのリモート コード実行の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
[CVE-2016-0044](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0044)

</td>
<td style="border:1px solid black;">
Windows DLL 読み込みのサービス拒否の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0049](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0049)

</td>
<td style="border:1px solid black;">
Windows Kerberos のセキュリティ機能のバイパス

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-015:リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3134226)**](http://go.microsoft.com/fwlink/?linkid=722214)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0022)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;" colspan="2">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0039](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0039)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint XSS の脆弱性

</td>
<td style="border:1px solid black;">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;" colspan="2">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0052](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0052)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;" colspan="2">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0053](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0053)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;" colspan="2">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0054](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0054)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;" colspan="2">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0055](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0055)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;" colspan="2">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0056](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0056)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;" colspan="2">
1- 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-016:特権の昇格に対処する WebDAV 用のセキュリティ更新プログラム (3136041)**](http://go.microsoft.com/fwlink/?linkid=722536)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0051](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0051)

</td>
<td style="border:1px solid black;">
WebDAV の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-017:特権の昇格に対処するリモート デスクトップ ディスプレイ ドライバー用のセキュリティ更新プログラム (3134700)**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0036](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0036)

</td>
<td style="border:1px solid black;">
リモート デスクトップ プロトコル (RDP) の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-018:特権の昇格に対処する Windows カーネル モード ドライバー用のセキュリティ更新プログラム (3136082)**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0048](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0048)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-019:サービス拒否に対処する.NET Framework 用のセキュリティ更新プログラム (3137893)**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0033)

</td>
<td style="border:1px solid black;">
.NET Framework スタック オーバーフローのサービス拒否の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;">
[CVE-2016-0047](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0047)

</td>
<td style="border:1px solid black;">
Windows Forms の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-020:サービス拒否に対処する Active Directory フェデレーション サービス用のセキュリティ更新プログラム (3134222)**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0037)

</td>
<td style="border:1px solid black;">
Microsoft Active Directory フェデレーション サービスのサービス拒否の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
3- 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
[**MS16-021:サービス拒否に対処する NPS RADIUS サーバー用のセキュリティ更新プログラム (3133043)**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0050](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0050)

</td>
<td style="border:1px solid black;">
ネットワーク ポリシー サーバーの RADIUS 実装のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="6">
[**MS16-022: Adobe Flash Player のセキュリティ更新プログラム (3135782)**](http://go.microsoft.com/fwlink/?linkid=723603)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-04](http://helpx.adobe.com/security/products/flash-player/apsb16-04.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度および更新プログラムの優先度に関しては、[Adobe Security Bulletin APSB16-04](http://helpx.adobe.com/security/products/flash-player/apsb16-04.html) を参照してください。

</td>
<td style="border:1px solid black;" colspan="2">
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
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
(3134814)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3126587)  
(重要)  
Windows Vista Service Pack 2  
(3126593)  
(重要)  
Windows Vista Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3126587)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3126593)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3126587)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3126593)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3126587)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3126593)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(3134814)  
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
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3126587)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3126593)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
(3134814)  
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
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3126587)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3126587)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3126587)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3124280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3126587)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3123294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3126587)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3126593)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3126041)  
(重要)  
Windows 8.1 for 32-bit Systems  
(3126434)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3124280)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3123294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3126587)  
(重要)  
Windows 8.1 for x64-based Systems  
(3126593)  
(重要)  
Windows 8.1 for x64-based Systems  
(3126041)  
(重要)  
Windows 8.1 for x64-based Systems  
(3126434)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3124280)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3134814)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3123294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126587)  
(重要)  
Windows Server 2012  
(3126593)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3124280)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3123294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3115858)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126587)  
(重要)  
Windows Server 2012 R2  
(3126593)  
(重要)  
Windows Server 2012 R2  
(3126041)  
(重要)  
Windows Server 2012 R2  
(3126434)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3124280)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3134814)  
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
(3126587)  
(重要)  
Windows RT 8.1  
(3126593)  
(重要)  
Windows RT 8.1  
(3126434)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3124280)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3135174)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3135174)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3135174)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135174)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135174)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3135174)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3135174)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3135174)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3135173)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(3135173)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3135173)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3135173)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3135173)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(3135173)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-009**](http://go.microsoft.com/fwlink/?linkid=722212)

</td>
<td style="border:1px solid black;">
[**MS16-011**](http://go.microsoft.com/fwlink/?linkid=722213)

</td>
<td style="border:1px solid black;">
[**MS16-012**](http://go.microsoft.com/fwlink/?linkid=623622)

</td>
<td style="border:1px solid black;">
[**MS16-013**](http://go.microsoft.com/fwlink/?linkid=722340)

</td>
<td style="border:1px solid black;">
[**MS16-014**](http://go.microsoft.com/fwlink/?linkid=722215)

</td>
<td style="border:1px solid black;">
[**MS16-016**](http://go.microsoft.com/fwlink/?linkid=722536)

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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3126587)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3126593)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3126041)  
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
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3126587)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3126593)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3126041)  
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
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3126587)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3126593)  
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
Windows Server 2012 (Server Core インストール)  
(3126587)  
(重要)  
Windows Server 2012 (Server Core インストール)  
(3126593)  
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
Windows Server 2012 R2  
(Server Core インストール)  
(3123294)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3126587)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(3126593)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(3126041)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
 

### Windows オペレーティング システムとコンポーネント (表 2/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6  
(3127233)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6  
(3127233)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6  
(3127233)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3133043)  
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
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6  
(3127233)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3133043)  
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
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(3122646)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(3127219)  
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
<td style="border:1px solid black;" colspan="7">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
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
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122661)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127233)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3133043)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
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
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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
**なし**

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
Windows 8.1 for 32-bit Systems  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(重要)  
Microsoft .NET Framework 3.5  
(3127222)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(重要)  
Microsoft .NET Framework 3.5  
(3127222)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122649)  
(重要)  
Microsoft .NET Framework 3.5  
(3127221)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122655)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127227)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3133043)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(重要)  
Microsoft .NET Framework 3.5  
(3127222)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 3.0  
(3134222)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3133043)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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
Windows RT 8.1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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
**なし**

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
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135174)  
(重要)  
Microsoft .NET Framework 4.6  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135174)  
(重要)  
Microsoft .NET Framework 4.6  
(3135174)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
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
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135173)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
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
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3135173)  
(重要)  
Microsoft .NET Framework 4.6.1  
(3135173)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe® Flash Player  
(3135782)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-017**](http://go.microsoft.com/fwlink/?linkid=722326)

</td>
<td style="border:1px solid black;">
[**MS16-018**](http://go.microsoft.com/fwlink/?linkid=722617)

</td>
<td style="border:1px solid black;">
[**MS16-019**](http://go.microsoft.com/fwlink/?linkid=718008)

</td>
<td style="border:1px solid black;">
[**MS16-020**](http://go.microsoft.com/fwlink/?linkid=722534)

</td>
<td style="border:1px solid black;">
[**MS16-021**](http://go.microsoft.com/fwlink/?linkid=722535)

</td>
<td style="border:1px solid black;">
[**MS16-022**](http://go.microsoft.com/fwlink/?linkid=723603)

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
(3134214)  
(重要)

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
(3133043)  
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
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)  
(3134214)  
(重要)

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
(3133043)  
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
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(3122648)  
(重要)  
Microsoft .NET Framework 3.5.1  
(3127220)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122656)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127229)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
(3133043)  
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
Windows Server 2012 (Server Core インストール)  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122649)  
(重要)  
Microsoft .NET Framework 3.5  
(3127221)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122655)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127227)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122658)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127230)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
(3133043)  
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
Windows Server 2012 R2 (Server Core インストール)  
(3126446)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3134214)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(3122651)  
(重要)  
Microsoft .NET Framework 3.5  
(3127222)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3122654)  
(重要)  
Microsoft .NET Framework 4.5.2  
(3127226)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3122660)  
(重要)  
Microsoft .NET Framework 4.6/4.6.1  
(3127231)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 3.0  
(3134222)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
(3133043)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114742)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(3114741)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3114748)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114752)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3114759)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3114755)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3114752)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3114759)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3114755)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114734)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3114724)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3114734)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3114724)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114734)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3114724)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114698)  
(重要)  
Microsoft Word 2016 (32 ビット版)  
(3114702)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 ビット版)  
(3114698)  
(重要)  
Microsoft Word 2016 (64 ビット版)  
(3114702)  
(緊急)

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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3137721)  
(重要)  
Microsoft Word for Mac 2011  
(3137721)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 for Mac  
(3134241)  
(重要)  
Microsoft Word 2016 for Mac  
(3134241)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114548)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(3114745)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114747)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114773)  
(重要)

</td>
</tr>
</table>
 
**MS16-015 に関する注意**

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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114432)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Excel Services  
(3114432)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114401)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114335)  
(重要)  
Word Automation Services  
(3114481)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114407)  
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
(3114338)  
(重要)

</td>
</tr>
</table>
 
**MS16-015 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft サーバー ソフトウェア

 
<table style="border:1px solid black;">
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
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
Microsoft SharePoint Server 2013 Service Pack 1  
(3039768)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS16-015**](http://go.microsoft.com/fwlink/?linkid=722214)

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
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3114733)  
(重要)

</td>
</tr>
</table>
 
**MS16-015 に関する注意**

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

-   V1.0 (2016/02/10): このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2016/02/12): このセキュリティ情報の概要ページを更新し、MS16-014 の Microsoft Windows Vista、Windows Server 2008、Windows Server 2008 for Itanium-based Systems、Windows 8.1、および Windows Server 2012 R2 用の更新プログラム 3126041 が利用可能になったことをお知らせしました。このセキュリティ情報で説明されている脆弱性から保護するため、この適用可能な更新プログラムを適用してください。大半のお客様は自動更新が有効になっており、この更新プログラムが自動的にダウンロードおよびインストールされるため、特別な措置を講じる必要はありません。MS16-021 の CVE-2016-0050 の悪用可能性評価を訂正しました。
-   V3.0 (2016/02/17): MS16-015 に関して、2016 年 2 月 16 日現在利用可能な Microsoft Office 2016 for Mac 用の更新プログラム 3134241、および Microsoft Office for Mac 2011 用の更新プログラム 3137721 を追加しました。詳細は、[サポート技術情報 3134241](https://support.microsoft.com/kb/3134241)および[サポート技術情報 3137721](https://support.microsoft.com/kb/3137721)を参照してください。
-   V3.1 (2016/02/25): 概要の表の MS16-014 に、既知の問題の参照を追加しました。詳細は、[サポート技術情報 3126041](https://support.microsoft.com/kb/3126041)を参照してください。また、2 番目の既知の問題には回避策などが追加されましたので、[サポート技術情報 3126587](https://support.microsoft.com/kb/3126587)を参照してください。

*Page generated 2016-02-24 13:45-08:00.*
