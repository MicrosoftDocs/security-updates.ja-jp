---
TOCTitle: 'MS15-MAR'
Title: 2015 年 3 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms15-mar'
ms:contentKeyID: 64978232
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms15-mar(v=Security.10)'
---

2015 年 3 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2015 年 3 月 11 日

**バージョン:** 1.0

このセキュリティ情報の概要は 2015 年 3 月公開のセキュリティ情報の一覧です。

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
<td style="border:1px solid black;"><strong>影響を受ける<br />
ソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3032359)</strong> <br />
このセキュリティ更新プログラムにより、いくつかの Internet Explorer の脆弱性が解決されます。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526467">MS15-019</a></td>
<td style="border:1px solid black;"><strong>VBScript スクリプト エンジンの脆弱性により、リモートでコードが実行される (3040297)</strong> <br />
このセキュリティ更新プログラムは、Microsoft Windows の VBScript スクリプト エンジンに存在する脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web サイトにアクセスすると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている時に、攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピューターが完全に制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526456">MS15-020</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows の脆弱性により、リモートでコードが実行される (3041836)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性によって、特別に細工された Web サイトを訪れるか、特別に細工されたファイルを開くか、特別に細工された DLL ファイルを含む作業ディレクトリでファイルを開くと、リモートでコードが実行される可能性があります</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;"><strong>Adobe フォント ドライバ の脆弱性により、リモートでコードが実行される (3032323)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性では、特別に細工されたファイルまたは Web サイトをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用し、影響を受けるコンピューターを完全に制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526461">MS15-022</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、リモートでコードが実行される (3038999)</strong><br />
このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。これらの脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3038999/ja">3038999</a></td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526460">MS15-023</a></td>
<td style="border:1px solid black;"><strong>カーネルモード ドライバーの脆弱性により、特権が昇格される (3034344)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性では、攻撃者がコンピューターにログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全な管理者権限を持つ新たなアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526465">MS15-024</a></td>
<td style="border:1px solid black;"><strong>PNG 処理 の脆弱性により、情報漏えいが起こる (3035132)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の 1 件の脆弱性を解決します。この脆弱性により、攻撃者がユーザーに特別な細工がされた PNG 画像を開くよう誘導した場合、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526462">MS15-025</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルの脆弱性により、特権が昇格される (3038680)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性でもっとも深刻なものでは、攻撃者が影響を受けるコンピューターにログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性を悪用する攻撃者は、影響を受けるシステムにログオンする別のユーザー アカウントのセキュリティ コンテキストで任意のコードを実行する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つことができる新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3038680/ja">3038680</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526458">MS15-026</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server の脆弱性により、特権が昇格される (3040856)</strong> <br />
このセキュリティ更新プログラムは、Microsoft Exchange Server の脆弱性を解決します。これらの中で最も深刻な脆弱性により、標的となる Outlook Web App サイトにユーザーを誘導する、特別に細工された URL をユーザーがクリックした場合、特権が昇格される可能性があります。攻撃者は、特別に細工した Web サイトにユーザーを強制的に訪問させることはできません。その代わり、通常、攻撃者は電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをユーザーにクリックさせて攻撃者の Web サイトに誘導し、特別に細工した URL をクリックさせることが、攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動は必要ありません</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522530">MS15-027</a></td>
<td style="border:1px solid black;"><strong>NETLOGON の脆弱性でなりすましが行われる可能性があります (3002657)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の 1 件の脆弱性を解決します。この脆弱性により、ドメイン参加システムにログオンした攻撃者が、別のドメイン参加システムとの接続を確立する特別に細工されたアプリケーションを実行した場合に、なりすましが行われる可能性があります。攻撃者はドメイン参加システムにログオンしてネットワーク トラフィックを監視できることが必要です。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
なりすまし</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526468">MS15-028</a></td>
<td style="border:1px solid black;"><strong>Windows タスク スケジューラの脆弱性により、セキュリティ機能のバイパスが起こる (3030377)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の 1 件の脆弱性を解決します。この脆弱性により、限定された権限を持つユーザーが影響を受けるシステムでタスク スケジューラーを使用して実行権限のないファイルを実行できるようになる可能性があります。攻撃者がこの脆弱性を悪用した場合、ACL チェックがバイパスされ、特権の実行可能ファイルが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526464">MS15-029</a></td>
<td style="border:1px solid black;"><strong>Microsoft Photo Decoder コンポーネントの脆弱性により、情報の漏えいが起こる (3035126)</strong> <br />
このセキュリティ更新プログラムは、Microsoft Windows の 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された JPEG XR (.JXR) 画像を含む Web サイトを閲覧すると、情報漏えいが起こる可能性があります。この脆弱性は、攻撃者にコードの実行や特権の昇格を直接許可するものではありませんが、影響を受けるシステムをさらに侵害する目的で悪用する情報を取得する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526466">MS15-030</a></td>
<td style="border:1px solid black;"><strong>リモート デスクトップ プロトコルの脆弱性によりサービス拒否が発生する (3039976)</strong><br />
このセキュリティ更新プログラムは、Microsoft Windows の 1 件の脆弱性を解決します。この脆弱性により、攻撃者がメモリでオブジェクトの適切な解放を失敗させる複数のリモート デスクトップ プロトコル (RDP) セッションを作成する場合に、サービス拒否が発生する可能性があります。RDP は、サポートされている Windows オペレーティング システムでは既定で有効ではありません。RDP が有効となっていないコンピューターは危険にさらされません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=528542">MS15-031</a></td>
<td style="border:1px solid black;"><strong>Schannel の脆弱性により、セキュリティ機能のバイパスが起こる (3046049)<br />
</strong>このセキュリティ更新プログラムでは、一般に知られている FREAK 手法を悪用した攻撃の対象となる Microsoft Windows の脆弱性を解決します。この手法は Windows オペレーティング システムに限らず、業界全体で問題になっています。中間者 (MiTM: man-in-the-middle) 攻撃者はこの脆弱性を悪用することで、TLS 接続の RSA キーのキー長さを強制的に EXPORT グレードの長さまでダウングレードできます。安全性の低い暗号によって Schannel を使用してリモート TLS サーバーに接続するすべての Windows システムが、この脆弱性の影響を受けます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/kb/3046049/ja">3046049</a></td>
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
<td style="border:1px solid black;"><strong>最新のソフトウェア リリースでの<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>過去のソフトウェア リリースでの<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>サービス拒否<br />
悪用可能性評価</strong></td>
<td style="border:1px solid black;"><strong>注意事項</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">VBScript のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0032">CVE-2015-0032</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0056">CVE-2015-0056</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0072">CVE-2015-0072</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">この脆弱性は一般で公表されていました。<br />
<br />
これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0099">CVE-2015-0099</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0100">CVE-2015-0100</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1622">CVE-2015-1622</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1623">CVE-2015-1623</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1624">CVE-2015-1624</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1625">CVE-2015-1625</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この脆弱性は一般で公表されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1626">CVE-2015-1626</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1627">CVE-2015-1627</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526452">MS15-018</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1634">CVE-2015-1634</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526467">MS15-019</a></td>
<td style="border:1px solid black;">VBScript のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0032">CVE-2015-0032</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526456">MS15-020</a></td>
<td style="border:1px solid black;">WTS のリモート コードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0081">CVE-2015-0081</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526456">MS15-020</a></td>
<td style="border:1px solid black;">DLL の植え付けリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0096">CVE-2015-0096</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;">Adobe フォント ドライバーのサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0074">CVE-2015-0074</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;">Adobe フォント ドライバーの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0087">CVE-2015-0087</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;">Adobe フォント ドライバーでコードがリモートで実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0088">CVE-2015-0088</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;">Adobe フォント ドライバーの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0089">CVE-2015-0089</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;">Adobe フォント ドライバーでコードがリモートで実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0090">CVE-2015-0090</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;">Adobe フォント ドライバーでコードがリモートで実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0091">CVE-2015-0091</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;">Adobe フォント ドライバーでコードがリモートで実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0092">CVE-2015-0092</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526457">MS15-021</a></td>
<td style="border:1px solid black;">Adobe フォント ドライバーでコードがリモートで実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0093">CVE-2015-0093</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526461">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Office コンポーネントの解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0085">CVE-2015-0085</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526461">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0086">CVE-2015-0086</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526461">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft Word ローカル ゾーン リモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0097">CVE-2015-0097</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526461">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1633">CVE-2015-1633</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526461">MS15-022</a></td>
<td style="border:1px solid black;">Microsoft SharePoint XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1636">CVE-2015-1636</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526460">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows カーネル メモリ漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0077">CVE-2015-0077</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526460">MS15-023</a></td>
<td style="border:1px solid black;">Win32k の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0078">CVE-2015-0078</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526460">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows カーネル メモリ漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0094">CVE-2015-0094</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526460">MS15-023</a></td>
<td style="border:1px solid black;">Microsoft Windows カーネル メモリ漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0095">CVE-2015-0095</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526465">MS15-024</a></td>
<td style="border:1px solid black;">改ざんされた PNG 解析情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0080">CVE-2015-0080</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526462">MS15-025</a></td>
<td style="border:1px solid black;">レジストリ仮想化の特権昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0073">CVE-2015-0073</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526462">MS15-025</a></td>
<td style="border:1px solid black;">偽装レベルチェック特権昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0075">CVE-2015-0075</a></td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526458">MS15-026</a></td>
<td style="border:1px solid black;">OWA の変更された Canary パラメータのクロスサイト スクリプティング脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1628">CVE-2015-1628</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526458">MS15-026</a></td>
<td style="border:1px solid black;">ExchangeDLP クロスサイトスクリプティングの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1629">CVE-2015-1629</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526458">MS15-026</a></td>
<td style="border:1px solid black;">監査レポートのクロスサイトスクリプティングの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1630">CVE-2015-1630</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526458">MS15-026</a></td>
<td style="border:1px solid black;">Exchange の偽造された会議出席依頼なりすましの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1631">CVE-2015-1631</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはなりすましの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526458">MS15-026</a></td>
<td style="border:1px solid black;">Exchange エラーメッセージのクロスサイトスクリプティング脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1632">CVE-2015-1632</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">4 - 影響されない</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522530">MS15-027</a></td>
<td style="border:1px solid black;">NETLOGON のなりすましの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0005">CVE-2015-0005</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはなりすましの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526468">MS15-028</a></td>
<td style="border:1px solid black;">タスク スケジューラのセキュリティ機能バイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0084">CVE-2015-0084</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526464">MS15-029</a></td>
<td style="border:1px solid black;">JPEG XR パーサー情報漏えい脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0076">CVE-2015-0076</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=526466">MS15-030</a></td>
<td style="border:1px solid black;">リモート デスクトップ プロトコル (RDP) のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0079">CVE-2015-0079</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=528542">MS15-031</a></td>
<td style="border:1px solid black;">Schannel セキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1637">CVE-2015-1637</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">この脆弱性は一般で公表されていました。<br />
<br />
これはセキュリティ機能のバイパスの脆弱性です。</td>
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
(3032359)  
(警告)  
Internet Explorer 7  
(3032359)  
(警告)  
Internet Explorer 8  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3030403)  
(警告)  
VBScript 5.7   
(3030398)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3033889)  
(緊急)  
Windows Server 2003 Service Pack 2  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
(警告)  
Internet Explorer 7  
(3032359)  
(警告)  
Internet Explorer 8  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3030403)  
(警告)  
VBScript 5.7   
(3030398)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3033889)  
(緊急)  
Windows Server 2003 x64 Edition Service Pack 2  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3032359)  
(警告)  
Internet Explorer 7  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.6   
(3030403)  
(警告)  
VBScript 5.7   
(3030398)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3033889)  
(緊急)  
Windows Server 2003 with SP2 for Itanium-based Systems  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3035132)  
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
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(緊急)  
Internet Explorer 8  
(3032359)  
(緊急)  
Internet Explorer 9  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3033889)  
(緊急)  
Windows Vista Service Pack 2  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(緊急)  
Internet Explorer 8  
(3032359)  
(緊急)  
Internet Explorer 9  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3033889)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035132)  
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
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
(3032359)  
(警告)  
Internet Explorer 8  
(3032359)  
(警告)  
Internet Explorer 9  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3033889)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(警告)  
Internet Explorer 8  
(3032359)  
(警告)  
Internet Explorer 9  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3033889)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3033889)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3035132)  
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
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(緊急)  
Internet Explorer 9  
(3032359)  
(緊急)  
Internet Explorer 10  
(3032359)  
(緊急)  
Internet Explorer 11  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3033889)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(緊急)  
Internet Explorer 9  
(3032359)  
(緊急)  
Internet Explorer 10  
(3032359)  
(緊急)  
Internet Explorer 11  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3033889)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3035132)  
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
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(警告)  
Internet Explorer 9  
(3032359)  
(警告)  
Internet Explorer 10  
(3032359)  
(警告)  
Internet Explorer 11  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3033889)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3033889)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3035132)  
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
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3033889)  
(緊急)  
Windows 8 for 32-bit Systems  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3033889)  
(緊急)  
Windows 8 for x64-based Systems  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3033889)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3033889)  
(緊急)  
Windows 8.1 for x64-based Systems  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3035132)  
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
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3033889)  
(緊急)  
Windows Server 2012  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3033889)  
(緊急)  
Windows Server 2012 R2  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035132)  
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
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(3033889)  
(緊急)  
Windows RT  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3035132)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3032359)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3033889)  
(緊急)  
Windows RT 8.1  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035132)  
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
[**MS15-018**](http://go.microsoft.com/fwlink/?linkid=526452)

</td>
<td style="border:1px solid black;">
[**MS15-019**](http://go.microsoft.com/fwlink/?linkid=526467)

</td>
<td style="border:1px solid black;">
[**MS15-020**](http://go.microsoft.com/fwlink/?linkid=526456)

</td>
<td style="border:1px solid black;">
[**MS15-021**](http://go.microsoft.com/fwlink/?linkid=526457)

</td>
<td style="border:1px solid black;">
[**MS15-023**](http://go.microsoft.com/fwlink/?linkid=526460)

</td>
<td style="border:1px solid black;">
[**MS15-024**](http://go.microsoft.com/fwlink/?linkid=526465)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
VBScript 5.7   
(3030398)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3033889)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3035132)  
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
VBScript 5.7   
(3030398)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3033889)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3035132)  
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
VBScript 5.8   
(3030630)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3033889)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3035132)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3033889)  
(緊急)  
Windows Server 2012 (Server Core インストール)  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3035132)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3033889)  
(緊急)  
Windows Server 2012 R2 (Server Core インストール)  
(3039066)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3032323)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3034344)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3035132)  
(重要)

</td>
</tr>
</table>
 
**MS15-018、MS15-019、MS15-020、MS15-021、MS15-023 への注意**

Windows Technical Preview および Windows Server Technical Preview が影響を受けます。これらのオペレーティング システムを実行しているお客様は、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) の更新プログラムをご使用のコンピューターに適用することをお勧めします。



### Windows オペレーティング システムとコンポーネント (Table 2 の 2)

 
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)                                            

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3033395)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3002657)  
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
Windows Server 2003 Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3033395)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3002657)  
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
Windows Server 2003 x64 Edition Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3033395)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3002657)  
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
Windows Server 2003 with SP2 for Itanium-based Systems  
(3046049)  
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046049)  
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3046049)  
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
Windows 7 for 32-bit Systems Service Pack 1  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3035017)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(3036493)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3035017)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(3036493)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3046049)  
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3046049)  
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
Windows 8 for 32-bit Systems  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3046049)  
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046049)  
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3035126)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046049)  
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
[**MS15-025**](http://go.microsoft.com/fwlink/?linkid=526462)

</td>
<td style="border:1px solid black;">
[**MS15-027**](http://go.microsoft.com/fwlink/?linkid=522530)

</td>
<td style="border:1px solid black;">
[**MS15-028**](http://go.microsoft.com/fwlink/?linkid=526468)

</td>
<td style="border:1px solid black;">
[**MS15-029**](http://go.microsoft.com/fwlink/?linkid=526464)

</td>
<td style="border:1px solid black;">
[**MS15-030**](http://go.microsoft.com/fwlink/?linkid=526466)

</td>
<td style="border:1px solid black;">
[**MS15-031**](http://go.microsoft.com/fwlink/?linkid=528542)

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
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3002657)  
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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3002657)  
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
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3046049)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3035131)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3002657)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3030377)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3035017)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3046049)  
(重要)

</td>
</tr>
</table>
 
**MS15-031 に関する注意事項:**

Windows Technical Preview および Windows Server Technical Preview が影響を受けます。これらのオペレーティング システムを実行しているお客様は、[Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) の更新プログラムをご使用のコンピューターに適用することをお勧めします。

 

### Microsoft サーバー ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

</td>
<td style="border:1px solid black;">
[**MS15-026**](http://go.microsoft.com/fwlink/?linkid=526458)

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
(3040856)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 7

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 7  
(3040856)  
(重要)

</td>
</tr>
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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

</td>
<td style="border:1px solid black;">
[**MS15-026**](http://go.microsoft.com/fwlink/?linkid=526458)

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
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)  
(2881068)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)  
(2881068)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (32 ビット版)  
(2881068)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (64 ビット版)  
(2881068)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

</td>
<td style="border:1px solid black;">
[**MS15-026**](http://go.microsoft.com/fwlink/?linkid=526458)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wssloc)  
(2956208)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2 (wssloc)  
(2956208)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

</td>
<td style="border:1px solid black;">
[**MS15-026**](http://go.microsoft.com/fwlink/?linkid=526458)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 (sts)  
(2956175)  
(重要)  
Microsoft SharePoint Foundation 2013 (wssloc)  
(2956183)  
(重要)  
Microsoft SharePoint Foundation 2013 (smsloc)  
(2760508)  
(重要)  
Microsoft SharePoint Server 2013 (acsrvloc)  
(2956180)  
(重要)  
Microsoft SharePoint Server 2013 (coreserverloc)  
(2956153)  
(重要)  
Microsoft SharePoint Server 2013 (eduloc)  
(2760554)  
(重要)  
Microsoft SharePoint Server 2013 (ifsloc)  
(2880473)  
(重要)  
Microsoft SharePoint Server 2013 (lpsrvloc)  
(2737989)  
(重要)  
Microsoft SharePoint Server 2013 (ppsmaloc)  
(2881078)  
(重要)  
Microsoft SharePoint Server 2013 (vsrvloc)  
(2956181)  
(重要)  
Microsoft SharePoint Server 2013 (wasrvloc)  
(2760361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1 (sts)  
(2956175)  
(重要)  
Microsoft SharePoint Foundation 2013 Service Pack 1 (wssloc)  
(2956183)  
(重要)  
Microsoft SharePoint Foundation 2013 Service Pack 1 (smsloc)  
(2760508)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (acsrvloc)  
(2956180)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (coreserverloc)  
(2956153)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (eduloc)  
(2760554)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (ifsloc)  
(2880473)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (lpsrvloc)  
(2737989)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (ppsmaloc)  
(2881078)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (vsrvloc)  
(2956181)  
(重要)  
Microsoft SharePoint Server 2013 Service Pack 1 (wasrvloc)  
(2760361)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
**MS15-022 の注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

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
(2984939)  
(重要)  
Microsoft Excel 2007 Service Pack 3  
(2956103)  
(重要)  
Microsoft PowerPoint 2007 Service Pack 3  
(2899580)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(2956109)  
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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

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
(2956076)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2956138)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (32 ビット版) (oart)  
(2883100)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版) (oartconv)  
(2889839)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(2956142)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (32-bit エディション)  
(2920812)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(2956139)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2956076)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2956138)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (64 ビット版) (oart)  
(2883100)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版) (oartconv)  
(2889839)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(2956142)  
(重要)  
Microsoft PowerPoint 2010 Service Pack 2 (64-bit エディション)  
(2920812)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(2956139)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2013 および Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

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
Microsoft Office 2013 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版)  
(2956151)  
(重要)  
Microsoft Word 2013 (32 ビット版)  
(2956163)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)  
(2956151)  
(重要)  
Microsoft Word 2013 (64 ビット版)  
(2956163)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)  
(2956151)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(2956163)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)  
(2956151)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(2956163)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2956151)  
(重要)  
Microsoft Word 2013 RT  
(2956163)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(2956151)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(2956163)  
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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

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
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2956188)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2956189)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3 (wordconv)  
(2956107)  
(緊急)  
Microsoft Office 互換機能パック Service Pack 3 (xlconv)  
(2956106)  
(重要)

</td>
</tr>
</table>
 
**MS15-022 の注意**

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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

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
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services (wdsrv)  
(2956136)  
(緊急)

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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Excel Services (xlsrvloc)  
(2956143)  
(重要)  
Word Automation Services (wdsrvloc)  
(2920731)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Excel Services (xlsrvloc)  
(2956143)  
(重要)  
Word Automation Services (wdsrvloc)  
(2920731)  
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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

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
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Web Applications 2010 Service Pack 2 (wacloc2010)  
(2956069)  
(緊急)  
Microsoft Office Web Apps Server 2010 Service Pack 2 (wacloc2010)  
(2956069)  
(緊急)

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
[**MS15-022**](http://go.microsoft.com/fwlink/?linkid=526461)

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
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(wacserver2013)  
(2956158)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(wacserver2013)  
(2956158)  
(緊急)

</td>
</tr>
</table>
 
**MS15-022 の注意**

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

国ごとのローカル サポート: [Microsoft サポート](http://support.microsoft.com/common/international.aspx?ln=ja)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性など、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社およびこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2015/03/11):このセキュリティ情報の概要ページを公開しました。

*Page generated 2015-03-10 9:05Z-07:00.*
