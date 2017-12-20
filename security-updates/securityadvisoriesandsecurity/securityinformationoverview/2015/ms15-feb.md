---
TOCTitle: 'MS15-FEB'
Title: 2015 年 2 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms15-feb'
ms:contentKeyID: 64119082
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms15-feb(v=Security.10)'
---

2015 年 2 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2015 年 2 月 11 日

**バージョン:** 1.0

このセキュリティ情報の概要は 2015 年 2 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムと共に、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
<p> </p>  <table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度および脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用のセキュリティ更新プログラム (3034682)<br />
</strong><br />
このセキュリティ更新プログラムは、Internet Explorer に存在する 1 件の一般に公開された脆弱性および 40 件の非公開で報告された脆弱性を解決します。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (3036220)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の一般に公開された脆弱性および 5 件の非公開で報告された脆弱性を解決します。これらの脆弱性の最も深刻な状況では、攻撃者が特別に細工したドキュメントを開くようにユーザーを誘導した場合、または埋め込み TrueType フォントが含まれる信頼されていない Web サイトにアクセスするようにユーザーを誘導した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525536">MS15-011</a></td>
<td style="border:1px solid black;"><strong>グループ ポリシーの脆弱性により、リモートでコードが実行される (3000483)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ドメインで構成されているシステムを使用しているユーザーを、攻撃者が制御しているネットワークに接続するように攻撃者が誘導した場合、リモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用し、影響を受けるコンピューターを完全に制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525537">MS15-012</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、リモートでコードが実行される (3032328)<br />
</strong><br />
このセキュリティ更新プログラムは、非公開で報告された 3 件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性で、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525533">MS15-013</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、セキュリティ機能のバイパスが起こる (3033857)<br />
</strong><br />
このセキュリティ更新プログラムは 1 件の Microsoft Office に存在する一般で公開された脆弱性を解決します。この脆弱性により、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にセキュリティ機能のバイパスが起こる可能性があります。セキュリティ機能のバイパス自体では、任意のコードが実行されることはありません。しかし、攻撃者はこのセキュリティ機能のバイパスの脆弱性を、リモートでコードが実行される脆弱性など別の脆弱性と組み合わせて使用し、任意のコードを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522532">MS15-014</a></td>
<td style="border:1px solid black;"><strong>グループ ポリシーの脆弱性により、セキュリティ機能のバイパスが起こる (3004361)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が、man-in-the-middle 攻撃を実行し、そのためにターゲットのシステム上でグループ ポリシー セキュリティ構成エンジン ポリシー ファイルが破損するか読み取り不能になった場合にセキュリティ機能のバイパスが起こる可能性があります。この結果、システム上のグループ ポリシー設定が既定値に戻され、セキュリティが低下した状態になる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525538">MS15-015</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows の脆弱性により、特権が昇格される (3031432)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が偽装レベルのセキュリティ チェックの欠如を利用して、プロセス作成中に特権を昇格させる可能性があります。認証された攻撃者がこの脆弱性を悪用した場合、管理者の資格情報を取得および使用して特権を昇格させる可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全な管理者権限を持つ新たなアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525539">MS15-016</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネントの脆弱性により、情報の漏えいが起こる (3029944)<br />
</strong><br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された TIFF 画像を含む Web サイトを閲覧すると、情報漏えいが起こる可能性があります。この脆弱性は、攻撃者にコードの実行や特権の昇格を直接許可するものではありませんが、影響を受けるシステムをさらに侵害する目的で悪用する情報を取得する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525540">MS15-017</a></td>
<td style="border:1px solid black;"><strong>Virtual Machine Manager の脆弱性により、特権が昇格される (3035898)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Virtual Machine Manager (VMM) の脆弱性を解決します。この脆弱性により、影響を受けるシステムに攻撃者がログオンした場合、特権の昇格が起こる可能性があります。この脆弱性が悪用されるには、有効な Active Directory のログオン資格情報を所有し、これらの資格情報でログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア</td>
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
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>脆弱性のタイトル</strong></td>
<td style="border:1px solid black;"><strong>CVE の識別番号</strong></td>
<td style="border:1px solid black;"><strong>最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</strong></td>
<td style="border:1px solid black;"><strong>旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</strong></td>
<td style="border:1px solid black;"><strong>サービス拒否の悪用可能性の評価</strong></td>
<td style="border:1px solid black;"><strong>注意事項</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-8967">CVE-2014-8967</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">この脆弱性は一般で公表されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0017">CVE-2015-0017</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0018">CVE-2015-0018</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0019">CVE-2015-0019</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0020">CVE-2015-0020</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0021">CVE-2015-0021</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0022">CVE-2015-0022</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0023">CVE-2015-0023</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0025">CVE-2015-0025</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0026">CVE-2015-0026</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0027">CVE-2015-0027</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0028">CVE-2015-0028</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0029">CVE-2015-0029</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0030">CVE-2015-0030</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0031">CVE-2015-0031</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0035">CVE-2015-0035</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0036">CVE-2015-0036</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0037">CVE-2015-0037</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0038">CVE-2015-0038</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0039">CVE-2015-0039</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0040">CVE-2015-0040</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0041">CVE-2015-0041</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0042">CVE-2015-0042</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0043">CVE-2015-0043</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0044">CVE-2015-0044</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0045">CVE-2015-0045</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0046">CVE-2015-0046</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0048">CVE-2015-0048</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0049">CVE-2015-0049</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0050">CVE-2015-0050</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0051">CVE-2015-0051</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0052">CVE-2015-0052</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0053">CVE-2015-0053</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0054">CVE-2015-0054</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0055">CVE-2015-0055</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0066">CVE-2015-0066</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0067">CVE-2015-0067</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0068">CVE-2015-0068</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0069">CVE-2015-0069</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer のクロス ドメインの情報の漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0070">CVE-2015-0070</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525534">MS15-009</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0071">CVE-2015-0071</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。<br />
<br />
これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></td>
<td style="border:1px solid black;">Win32k の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0003">CVE-2015-0003</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></td>
<td style="border:1px solid black;">CNG セキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0010">CVE-2015-0010</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">この脆弱性は一般で公表されていました。<br />
<br />
これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></td>
<td style="border:1px solid black;">Win32k の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0057">CVE-2015-0057</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></td>
<td style="border:1px solid black;">Windows カーソル オブジェクトのダブル フリーの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0058">CVE-2015-0058</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525535">MS15-010</a></td>
<td style="border:1px solid black;">TrueType フォントのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0059">CVE-2015-0059</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525536">MS15-011</a></td>
<td style="border:1px solid black;">グループ ポリシーのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0008">CVE-2015-0008</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525537">MS15-012</a></td>
<td style="border:1px solid black;">Excel のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0063">CVE-2015-0063</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525537">MS15-012</a></td>
<td style="border:1px solid black;">Office のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0064">CVE-2015-0064</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525537">MS15-012</a></td>
<td style="border:1px solid black;">OneTableDocumentStream のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0065">CVE-2015-0065</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525533">MS15-013</a></td>
<td style="border:1px solid black;">Microsoft Office コンポーネントの解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6362">CVE-2014-6362</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">この脆弱性は一般で公表されていました。<br />
<br />
これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522532">MS15-014</a></td>
<td style="border:1px solid black;">グループ ポリシー セキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0009">CVE-2015-0009</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525538">MS15-015</a></td>
<td style="border:1px solid black;">Windows のプロセスの作成における特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0062">CVE-2015-0062</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525539">MS15-016</a></td>
<td style="border:1px solid black;">TIFF 処理の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0061">CVE-2015-0061</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=525540">MS15-017</a></td>
<td style="border:1px solid black;">Virtual Machine Manager における特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0012">CVE-2015-0012</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
</tbody>
</table>
  
 
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントを基に、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3021952)  
(警告)  
Internet Explorer 7  
(3021952)  
(警告)  
Internet Explorer 8  
(3021952)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3013455)  
(重要)  
Windows Server 2003 Service Pack 2  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3021952)  
(警告)  
Internet Explorer 7  
(3021952)  
(警告)  
Internet Explorer 8  
(3021952)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3013455)  
(重要)  
Windows Server 2003 x64 Edition Service Pack 2  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3021952)  
(警告)  
Internet Explorer 7  
(3021952)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3013455)  
(重要)  
Windows Server 2003 with SP2 for Itanium-based Systems  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3029944)  
(重要)

</td>
</tr>
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
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
(緊急)  
Internet Explorer 8  
(3021952)  
(緊急)  
Internet Explorer 9  
(3021952)  
(緊急)  
Internet Explorer 9  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3013455)  
(重要)  
Windows Vista Service Pack 2  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
(緊急)  
Internet Explorer 8  
(3021952)  
(緊急)  
Internet Explorer 9  
(3021952)  
(緊急)  
Internet Explorer 9  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3013455)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3029944)  
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
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
(警告)  
Internet Explorer 8  
(3021952)  
(警告)  
Internet Explorer 9  
(3021952)  
(警告)  
Internet Explorer 9  
(3034196)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3013455)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
(警告)  
Internet Explorer 8  
(3021952)  
(警告)  
Internet Explorer 9  
(3021952)  
(警告)  
Internet Explorer 9  
(3034196)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3013455)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3021952)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3013455)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3029944)  
(重要)

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
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
Internet Explorer 8  
(3021952)  
(緊急)  
Internet Explorer 9  
(3021952)  
(緊急)  
Internet Explorer 9  
(3034196)  
(重要)  
Internet Explorer 10  
(3021952)  
(緊急)  
Internet Explorer 10  
(3034196)  
(重要)  
Internet Explorer 11  
(3021952)  
(緊急)  
Internet Explorer 11  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3013455)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3021952)  
(緊急)  
Internet Explorer 9  
(3021952)  
(緊急)  
Internet Explorer 9  
(3034196)  
(重要)  
Internet Explorer 10  
(3021952)  
(緊急)  
Internet Explorer 10  
(3034196)  
(重要)  
Internet Explorer 11  
(3021952)  
(緊急)  
Internet Explorer 11  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3013455)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3029944)  
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
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3021952)  
(警告)  
Internet Explorer 9  
(3021952)  
(警告)  
Internet Explorer 9  
(3034196)  
(注意)  
Internet Explorer 10  
(3021952)  
(警告)  
Internet Explorer 10  
(3034196)  
(注意)  
Internet Explorer 11  
(3021952)  
(警告)  
Internet Explorer 11  
(3034196)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3013455)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3021952)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3013455)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
Internet Explorer 10  
(3021952)  
(緊急)  
Internet Explorer 10  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3013455)  
(緊急)  
Windows 8 for 32-bit Systems  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3021952)  
(緊急)  
Internet Explorer 10  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3013455)  
(緊急)  
Windows 8 for x64-based Systems  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3021952)  
(緊急)  
Internet Explorer 11  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3013455)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3021952)  
(緊急)  
Internet Explorer 11  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3013455)  
(緊急)  
Windows 8.1 for x64-based Systems  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3029944)  
(重要)

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
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3021952)  
(警告)  
Internet Explorer 10  
(3034196)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3013455)  
(緊急)  
Windows Server 2012  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3021952)  
(警告)  
Internet Explorer 11  
(3034196)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3013455)  
(緊急)  
Windows Server 2012 R2  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
Internet Explorer 10  
(3021952)  
(緊急)  
Internet Explorer 10  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3013455)  
(緊急)  
Windows RT  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3029944)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3021952)  
(緊急)  
Internet Explorer 11  
(3034196)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3013455)  
(緊急)  
Windows RT 8.1  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3029944)  
(重要)

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
[**MS15-009**](http://go.microsoft.com/fwlink/?linkid=525534)

</td>
<td style="border:1px solid black;">
[**MS15-010**](http://go.microsoft.com/fwlink/?linkid=525535)

</td>
<td style="border:1px solid black;">
[**MS15-011**](http://go.microsoft.com/fwlink/?linkid=525536)

</td>
<td style="border:1px solid black;">
[**MS15-014**](http://go.microsoft.com/fwlink/?linkid=522532)

</td>
<td style="border:1px solid black;">
[**MS15-015**](http://go.microsoft.com/fwlink/?linkid=525538)

</td>
<td style="border:1px solid black;">
[**MS15-016**](http://go.microsoft.com/fwlink/?linkid=525539)

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
(3013455)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3029944)  
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
(3013455)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3029944)  
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
(3013455)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3029944)  
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
(3013455)  
(緊急)  
Windows Server 2012 (Server Core インストール)  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3029944)  
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
(3013455)  
(緊急)  
Windows Server 2012 R2 (Server Core インストール)  
(3023562)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3000483)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3004361)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3031432)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3029944)  
(重要)

</td>
</tr>
</table>
 
**MS15-009 および MS15-010 に関する注意事項**

Windows Technical Preview および Windows Server Technical Preview が影響を受けます。これらのオペレーティング システムを実行しているお客様は、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できる更新プログラムをご使用のコンピューターに適用することをお勧めします。

**MS15-011 に関する注意事項**

<sup>[1]</sup>Windows Server 2003 は影響を受けますが、そのための更新プログラムは公開されていません。詳細に関してはセキュリティ情報をご覧ください。

 

### Microsoft サーバー ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft System Center Virtual Machine Manager 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-017**](http://go.microsoft.com/fwlink/?linkid=525540)

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
Microsoft System Center Virtual Machine Manager 2012 R2 更新プログラムのロールアップ 4

</td>
<td style="border:1px solid black;">
Microsoft System Center Virtual Machine Manager 2012 R2 更新プログラムのロールアップ 4  
(VMM Server の更新プログラム 2992024)<sup>[1]</sup>
(重要)

</td>
</tr>
</table>
 
**MS15-017 に関する注意事項**

<sup>[1]</sup>このソフトウェアを実行しているお客様は、MS15-017 に記載されている脆弱性を解決するために、Microsoft System Center 2012 R2 - Virtual Machine Manager 2012 R2 UR5 のセキュリティ更新プログラム (KB3023195) をダウンロードしてインストールする必要があります。詳細に関してはセキュリティ情報をご覧ください。

 

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
[**MS15-012**](http://go.microsoft.com/fwlink/?linkid=525537)

</td>
<td style="border:1px solid black;">
[**MS15-013**](http://go.microsoft.com/fwlink/?linkid=525533)

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
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2920788)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(2956099)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2920795)  
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
[**MS15-012**](http://go.microsoft.com/fwlink/?linkid=525537)

</td>
<td style="border:1px solid black;">
[**MS15-013**](http://go.microsoft.com/fwlink/?linkid=525533)

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
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版) (校正ツール)  
(2956073)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2956058)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(2956081)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(2956066)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2920748)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版) (校正ツール)  
(2956073)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2956058)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(2956081)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(2956066)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2920748)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 および Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-012**](http://go.microsoft.com/fwlink/?linkid=525537)

</td>
<td style="border:1px solid black;">
[**MS15-013**](http://go.microsoft.com/fwlink/?linkid=525533)

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
Microsoft Office 2013 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (32 ビット版)  
(2920753)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版)  
(2910941)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(2920753)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(2910941)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (64 ビット版)  
(2920753)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)  
(2910941)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(2920753)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(2910941)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2920753)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(2920753)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS15-012**](http://go.microsoft.com/fwlink/?linkid=525537)

</td>
<td style="border:1px solid black;">
[**MS15-013**](http://go.microsoft.com/fwlink/?linkid=525533)

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
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2956092)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2920791)<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2956097)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(2956098)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
**MS15-012 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

<sup>[1]</sup>更新プログラム 2920791 は、同時にリリースされた [MS14-083](http://go.microsoft.com/fwlink/?linkid=519133) で説明されている脆弱性にも対処します。

 

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
[**MS15-012**](http://go.microsoft.com/fwlink/?linkid=525537)

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
(2920810)  
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
[**MS15-012**](http://go.microsoft.com/fwlink/?linkid=525537)

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
Microsoft Web Applications 2010 Service Pack 2  
(2956070)  
(重要)

</td>
</tr>
</table>
 
**MS15-012 に関する注意事項**

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

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=107349)からダウンロードできます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージを Microsoft ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ja)

国ごとのローカル サポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx?ln=ja)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation およびその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性など、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2015/02/11):このセキュリティ情報の概要ページを公開しました。

*Page generated 2015-02-06 12:47Z-08:00.*
