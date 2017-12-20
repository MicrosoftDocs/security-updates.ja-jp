---
TOCTitle: 'MS14-DEC'
Title: 2014 年 12 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms14-dec'
ms:contentKeyID: 63728533
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms14-dec(v=Security.10)'
---

MSRC ppDocument テンプレート

2014 年 12 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日: 2014 年 12 月 10 日

**バージョン:** 1.0

このセキュリティ情報の概要は 2014 年 12 月公開のセキュリティ情報の一覧です。

2014 年 12 月のセキュリティ情報の公開により、2014 年 12 月 5 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/ja-jp/security/gg309152.aspx)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server の脆弱性により、特権が昇格される (3009712)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された 4 件の Microsoft Exchange Server の脆弱性を解決します。これらの中で最も深刻な脆弱性により、標的となる Outlook Web App サイトにユーザーを誘導する、特別に細工された URL をユーザーがクリックした場合、特権が昇格される可能性があります。攻撃者は、特別に細工した Web サイトにユーザーを強制的に訪問させることはできません。その代わり、通常、攻撃者は電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをユーザーにクリックさせて攻撃者の Web サイトに誘導し、特別に細工した URL をクリックさせることが、攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/gg309177.aspx">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3008923)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された 14 件の Internet Explorer に存在する脆弱性を解決します。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/gg309177.aspx">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word および Microsoft Office Web Apps の脆弱性により、リモートでコードが実行される (3017301)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された Microsoft Word および Microsoft Office Web App に存在する 2 件の脆弱性を解決します。この脆弱性により、影響を受けるバージョンの Microsoft Office ソフトウェア内で、攻撃者が特別に細工した Microsoft Word ファイルをユーザーに開かせるかプレビューさせるように誘導した場合、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はプログラムのインストール、データの表示、変更または削除、あるいはすべてのユーザー権限を持つ新規アカウントの作成を行う可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/gg309177.aspx">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519135">MS14-082</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、リモートでコードが実行される (3017349)<br />
<br />
</strong>このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。影響を受けるエディションの Microsoft Office で特別に細工されたファイルを開くと、脆弱性によってリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/gg309177.aspx">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;"><strong>Microsoft Excel の脆弱性により、リモートでコードが実行される (3017347)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された Microsoft Excel に存在する 2 件の脆弱性を解決します。この脆弱性により、影響を受けるバージョンの Microsoft Office ソフトウェア内で、攻撃者が特別に細工した Microsoft Excel ファイルをユーザーに開かせるかプレビューさせるように誘導した場合、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はプログラムのインストール、データの表示、変更または削除、あるいはすべてのユーザー権限を持つ新規アカウントの作成を行う可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/gg309177.aspx">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519131">MS14-084</a></td>
<td style="border:1px solid black;"><strong>VBScript スクリプト エンジンの脆弱性により、リモートでコードが実行される (3016711)<br />
<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の VBScript スクリプト エンジンに存在する非公開で報告された脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web サイトにアクセスすると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている時に、攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピューターが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/gg309177.aspx">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519129">MS14-085</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネントの脆弱性により、情報の漏えいが起こる (3013126)<br />
<br />
</strong>このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された JPEG コンテンツを含む Web サイトを閲覧すると、情報漏えいが起こる可能性があります。この情報漏えいの脆弱性が攻撃者によって悪用された場合、システムに関する情報が取得され、他の攻撃との組み合わせによってシステムが侵害される可能性があります。この情報漏えいの脆弱性自体によって、任意のコードの実行が可能になることはありません。ただし、攻撃者はこの情報漏えいの脆弱性を他の脆弱性と組み合わせることで、Address Space Layout Randomization (ASLR) などのセキュリティ機能を回避できる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/gg309177.aspx">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">Outlook Web App のトークン スプーフィングの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6319">CVE-2014-6319</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。この脆弱性は、ソーシャル エンジニアリング攻撃でのスプーフィングに利用される可能性があります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">OWA XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6325">CVE-2014-6325</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">OWA XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6326">CVE-2014-6326</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/library/security/ms14-075">MS14-075</a></td>
<td style="border:1px solid black;">Exchange の URL リダイレクトの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6336">CVE-2014-6336</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。この脆弱性は、ソーシャル エンジニアリング攻撃でのスプーフィングに利用される可能性があります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6327">CVE-2014-6327</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer XSS フィルターのバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6328">CVE-2014-6328</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6329">CVE-2014-6329</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6330">CVE-2014-6330</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">VBScript のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer XSS フィルターのバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6365">CVE-2014-6365</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6366">CVE-2014-6366</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6368">CVE-2014-6368</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6369">CVE-2014-6369</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6373">CVE-2014-6373</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6374">CVE-2014-6374</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6375">CVE-2014-6375</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6376">CVE-2014-6376</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=521659">MS14-080</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-8966">CVE-2014-8966</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;">無効なインデックスでリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6356">CVE-2014-6356</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519132">MS14-081</a></td>
<td style="border:1px solid black;">解放後使用によって Word でリモート コードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6357">CVE-2014-6357</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519135">MS14-082</a></td>
<td style="border:1px solid black;">Microsoft Office コンポーネントの解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6364">CVE-2014-6364</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;">グローバル解放によって Excel でリモート コードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6360">CVE-2014-6360</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519133">MS14-083</a></td>
<td style="border:1px solid black;">Excel で無効なポインターによってリモート コードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6361">CVE-2014-6361</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519131">MS14-084</a></td>
<td style="border:1px solid black;">VBScript のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6363">CVE-2014-6363</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519129">MS14-085</a></td>
<td style="border:1px solid black;">Graphics コンポーネントの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6355">CVE-2014-6355</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
</tbody>
</table>
  
 
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(警告)  
Internet Explorer 7  
(3008923)  
(警告)  
Internet Explorer 8  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
(警告)  
VBScript 5.7   
(3012172)  
(警告)  
VBScript 5.8   
(3012176)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(警告)  
Internet Explorer 7  
(3008923)  
(警告)  
Internet Explorer 8  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
(警告)  
VBScript 5.7   
(3012172)  
(警告)  
VBScript 5.8   
(3012176)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3008923)  
(警告)  
Internet Explorer 7  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3012168)  
(警告)  
VBScript 5.7   
(3012172)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(緊急)  
Internet Explorer 8  
(3008923)  
(緊急)  
Internet Explorer 9  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(緊急)  
VBScript 5.8   
(IE8 を実行しているシステムのみ)<sup>[1]</sup>
(3012176)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(緊急)  
Internet Explorer 8  
(3008923)  
(緊急)  
Internet Explorer 9  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(緊急)  
VBScript 5.8   
(IE8 を実行しているシステムのみ)<sup>[1]</sup>
(3012176)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(警告)  
Internet Explorer 8  
(3008923)  
(警告)  
Internet Explorer 9  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(警告)  
VBScript 5.8   
(IE8 を実行しているシステムのみ)<sup>[1]</sup>
(3012176)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(警告)  
Internet Explorer 8  
(3008923)  
(警告)  
Internet Explorer 9  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(警告)  
VBScript 5.8   
(IE8 を実行しているシステムのみ)<sup>[1]</sup>
(3012176)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(緊急)  
Internet Explorer 9  
(3008923)  
(緊急)  
Internet Explorer 10  
(3008923)  
(緊急)  
Internet Explorer 11  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(IE8 を実行しているシステムのみ)<sup>[1]</sup>
(3012176)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(緊急)  
Internet Explorer 9  
(3008923)  
(緊急)  
Internet Explorer 10  
(3008923)  
(緊急)  
Internet Explorer 11  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(IE8 を実行しているシステムのみ)<sup>[1]</sup>
(3012176)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(警告)  
Internet Explorer 9  
(3008923)  
(警告)  
Internet Explorer 10  
(3008923)  
(警告)  
Internet Explorer 11  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(IE8 を実行しているシステムのみ)<sup>[1]</sup>
(3012176)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(IE8 を実行しているシステムのみ)<sup>[1]</sup>
(3012176)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(警告)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows RT  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3008923)  
(緊急)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-080**](http://go.microsoft.com/fwlink/?linkid=521659)

</td>
<td style="border:1px solid black;">
[**MS14-084**](http://go.microsoft.com/fwlink/?linkid=519131)

</td>
<td style="border:1px solid black;">
[**MS14-085**](http://go.microsoft.com/fwlink/?linkid=519129)

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
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(深刻度なし) <sup>[2]</sup>
VBScript 5.8   
(3012176)  
(深刻度なし) <sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3012172)  
(深刻度なし) <sup>[2]</sup>
VBScript 5.8   
(3012176)  
(深刻度なし) <sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
VBScript 5.8   
(3012176)  
(深刻度なし) <sup>[2]</sup>

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3013126)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3013126)  
(重要)

</td>
</tr>
</table>
 
**MS14-080 についての注意**

Windows Technical Preview および Windows Server Technical Preview が影響を受けます。これらのオペレーティング システムを実行しているお客様は、[Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ja-jp) から入手できる更新プログラムを適用することをお勧めします。

**MS14-084 についての注意**

Windows Technical Preview および Windows Server Technical Preview に対しては VBScript 5.8 の更新を利用でき、Internet Explorer の累積的な更新プログラム 3008923 ([MS14-080](http://go.microsoft.com/fwlink/?linkid=521659)) として提供されています。Preview エディションを実行しているお客様は、[Windows Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ja-jp) から入手できる更新プログラムを適用することをお勧めします。

<sup>[1]</sup>Internet Explorer 8 がインストールされているシステムに適用されます。システムで Internet Explorer 9 以降を実行しているお客様は、Internet Explorer 累積的な更新プログラム ([MS14-080](http://go.microsoft.com/fwlink/?linkid=521659)) を適用することをお勧めします。この更新プログラムによって、MS14-084 で説明されている脆弱性も解消されます。

<sup>[2]</sup>指定ソフトウェアには深刻度が適用されません。MS14-084 で説明する脆弱性に対する、Internet Explorer を介した既知の攻撃方法はブロックされるからです。しかし多層防御策として、マイクロソフトはこのソフトウェアをご使用のお客様に、将来確認される可能性がある新しい攻撃方法の悪用を防ぐ手助けとなるよう、このセキュリティ更新プログラムの適用を推奨します。

 

### Microsoft サーバー ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
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
[**MS14-075**](https://technet.microsoft.com/ja-jp/library/security/ms14-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2996150)  
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
[**MS14-075**](https://technet.microsoft.com/ja-jp/library/security/ms14-075)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2986475)  
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
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(3011140)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 6  
(3011140)  
(重要)

</td>
</tr>
</table>
 
 

### Microsoft Office スイートおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2920793)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2596927)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2984942)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2899518)  
(緊急)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(2899519)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2553154)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(2910902)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2899518)  
(緊急)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(2899519)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2553154)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(2910902)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 および Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 (32 ビット版)  
(2910916)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版)  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (32 ビット版)  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(2910916)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 (64 ビット版)  
(2910916)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (64 ビット版)  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(2910916)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT  
(2910916)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(2910916)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2726958)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(2910929)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

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
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3018888)  
(緊急)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**その他の Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
<td style="border:1px solid black;">
[**MS14-082**](http://go.microsoft.com/fwlink/?linkid=519135)

</td>
<td style="border:1px solid black;">
[**MS14-083**](http://go.microsoft.com/fwlink/?linkid=519133)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2920729)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2920792)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2920790)  
(重要)

</td>
</tr>
</table>
 
**MS14-081 についての注意**

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
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2899581)  
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
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883050)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883050)  
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
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2  
(2910892)  
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
[**MS14-081**](http://go.microsoft.com/fwlink/?linkid=519132)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/ja-jp/security/gg309177.aspx)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2889851)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(2889851)  
(重要)

</td>
</tr>
</table>
 
**MS14-081 についての注意**

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
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、[謝辞](https://technet.microsoft.com/ja-jp/library/security/dn820091.aspx)を参照してください。

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

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://technet.microsoft.com/ja-jp/security/dn467918)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://technet.microsoft.com/ja-jp/library/bb466251.aspx) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=ja-jp) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション: [TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ja)

国ごとのローカル サポート: [Microsoft サポート](http://support.microsoft.com/common/international.aspx?ln=ja)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2014/12/10): このセキュリティ情報の概要ページを公開しました。

*Page generated 2014-12-04 13:31Z-08:00.*
