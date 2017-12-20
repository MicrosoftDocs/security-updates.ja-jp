---
TOCTitle: 'MS14-JUN'
Title: 2014 年 6 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms14-jun'
ms:contentKeyID: 62486018
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms14-jun(v=Security.10)'
---

2014 年 6 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2014 年 6 月 11 日 | 最終更新日:2014 年 6 月 18 日

**バージョン:** 1.1

このセキュリティ情報の概要は 2014 年 6 月公開のセキュリティ情報の一覧です。

2014 年 6 月のセキュリティ情報の公開により、2014 年 6 月 6 日に公開した事前通知を、このセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2014 年 6 月 11 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[6 月の セキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032572980&culture=en-us) (英語)。

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
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >セキュリティ情報タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動の必要性</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (2969262)<br />
<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer に存在する 2 件の一般に公開された脆弱性および 57 件の非公開で報告された脆弱性を解決します。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネントの脆弱性により、リモートでコードが実行される (2967487)</strong><br />
<br />
このセキュリティ更新プログラムは、Microsoft Windows、Microsoft Office、および Microsoft Lync の非公開で報告された 2 件の脆弱性を解決します。これらの脆弱性で、特別に細工されたファイルまたは Web ページをユーザーが開いた場合にリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft Office、Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400971">MS14-034</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word の脆弱性により、リモートでコードが実行される (2969261)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。影響を受けるバージョンの Microsoft Word で特別に細工されたファイルを開くと、脆弱性によってリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=398119">MS14-033</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML コア サービスの脆弱性により、情報漏えいが起こる (2966061)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ログオンしたユーザーが、Internet Explorer を介して Microsoft XML コア サービス (MSXML) を呼び出すよう設計された特別な細工がされた Web サイトにアクセスした場合に、情報漏えいが起こる可能性があります。しかし、すべての場合、攻撃者がこのような Web サイトにユーザーを強制的に訪問させる方法はないと考えられます。そのかわり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのリクエスト内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400969">MS14-032</a></td>
<td style="border:1px solid black;"><strong>Microsoft Lync Server の脆弱性により、情報漏えいが起こる (2969258)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Lync Server に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された URL をクリックして Lync 会議に参加しようとすると、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Lync Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396824">MS14-031</a></td>
<td style="border:1px solid black;"><strong>TCP プロトコルの脆弱性により、サービス拒否が起こる (2962478)<br />
</strong><br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。攻撃者が特別に細工された一連のパケットを標的となるコンピューターに送信した場合、この脆弱性のためにサービス拒否が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400970">MS14-030</a></td>
<td style="border:1px solid black;"><strong>リモート デスクトップの脆弱性により改ざんが起こる (2969259)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が、リモート デスクトップ プロトコル (RDP) セッション中にターゲット システムと同じネットワーク セグメントにアクセスし、特別に細工された RDP パケットをターゲット システムに送信した場合、改ざんが起こる可能性があります。RDP は、サポートされている Windows オペレーティング システムでは既定で有効ではありません。RDP が有効となっていないコンピューターは危険にさらされません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
改ざん</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400970">MS14-030</a></td>
<td style="border:1px solid black;">RDP MAC の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0296">CVE-2014-0296</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは改ざんの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=396824">MS14-031</a></td>
<td style="border:1px solid black;">TCP のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1811">CVE-2014-1811</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400969">MS14-032</a></td>
<td style="border:1px solid black;">Lync Server コンテンツのサニタイズの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1823">CVE-2014-1823</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=398119">MS14-033</a></td>
<td style="border:1px solid black;">MSXML エンティティ URI の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1816">CVE-2014-1816</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400971">MS14-034</a></td>
<td style="border:1px solid black;">埋め込みフォントの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2778">CVE-2014-2778</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-0282">CVE-2014-0282</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1762">CVE-2014-1762</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1764">CVE-2014-1764</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1766">CVE-2014-1766</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1769">CVE-2014-1769</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1770">CVE-2014-1770</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">TLS サーバー証明書の再ネゴシエーションの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1771">CVE-2014-1771</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1772">CVE-2014-1772</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1773">CVE-2014-1773</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1774">CVE-2014-1774</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1775">CVE-2014-1775</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1777">CVE-2014-1777</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1778">CVE-2014-1778</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1779">CVE-2014-1779</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1780">CVE-2014-1780</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1781">CVE-2014-1781</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1782">CVE-2014-1782</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1783">CVE-2014-1783</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1784">CVE-2014-1784</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1785">CVE-2014-1785</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1786">CVE-2014-1786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1788">CVE-2014-1788</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1789">CVE-2014-1789</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1790">CVE-2014-1790</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1791">CVE-2014-1791</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1792">CVE-2014-1792</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1794">CVE-2014-1794</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1795">CVE-2014-1795</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1796">CVE-2014-1796</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1797">CVE-2014-1797</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1799">CVE-2014-1799</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1800">CVE-2014-1800</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1802">CVE-2014-1802</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1803">CVE-2014-1803</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1804">CVE-2014-1804</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1805">CVE-2014-1805</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2753">CVE-2014-2753</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2754">CVE-2014-2754</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2755">CVE-2014-2755</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2756">CVE-2014-2756</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2757">CVE-2014-2757</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2758">CVE-2014-2758</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2759">CVE-2014-2759</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2760">CVE-2014-2760</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2761">CVE-2014-2761</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2763">CVE-2014-2763</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2764">CVE-2014-2764</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2765">CVE-2014-2765</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2766">CVE-2014-2766</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2767">CVE-2014-2767</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2768">CVE-2014-2768</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2769">CVE-2014-2769</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2770">CVE-2014-2770</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2771">CVE-2014-2771</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2772">CVE-2014-2772</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2773">CVE-2014-2773</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2775">CVE-2014-2775</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2776">CVE-2014-2776</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2777">CVE-2014-2777</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400972">MS14-035</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2782">CVE-2014-2782</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Unicode スクリプト プロセッサの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この悪用可能性の評価は、影響を受ける Microsoft Windows ソフトウェアに関するものです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Unicode スクリプト プロセッサの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この悪用可能性の評価は、影響を受ける Microsoft Office ソフトウェアに関するものです。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">Unicode スクリプト プロセッサの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1817">CVE-2014-1817</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この悪用可能性の評価は、影響を受ける Microsoft Lync ソフトウェアに関するものです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">GDI+ の画像解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この悪用可能性の評価は、影響を受ける Microsoft Windows ソフトウェアに関するものです。<br />
<br />
これは、最新のソフトウェアに存在するサービス拒否の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">GDI+ の画像解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この悪用可能性の評価は、影響を受ける Microsoft Office ソフトウェアに関するものです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=400968">MS14-036</a></td>
<td style="border:1px solid black;">GDI+ の画像解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1818">CVE-2014-1818</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この悪用可能性の評価は、影響を受ける Microsoft Lync ソフトウェアに関するものです。</td>
</tr>
</tbody>
</table>
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
**これらの表はどのように使用しますか?**
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムおよびコンポーネント

 
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
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**注意**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2957689)  
(重要)  
Internet Explorer 7  
(2957689)  
(重要)  
Internet Explorer 8  
(2957689)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2003 Service Pack 2  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(注意)  
Microsoft XML コア サービス 6.0  
(2957482)  
(注意)

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
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2957689)  
(重要)  
Internet Explorer 7  
(2957689)  
(重要)  
Internet Explorer 8  
(2957689)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2003 x64 Edition Service Pack 2  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(注意)  
Microsoft XML コア サービス 6.0  
(2957482)  
(注意)

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
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2957689)  
(重要)  
Internet Explorer 7  
(2957689)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2003 with SP2 for Itanium-based Systems  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(注意)  
Microsoft XML コア サービス 6.0  
(2957482)  
(注意)

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
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2957689)  
(緊急)  
Internet Explorer 8  
(2957689)  
(緊急)  
Internet Explorer 9  
(2957689)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Vista Service Pack 2  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2957189)  
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
Internet Explorer 7  
(2957689)  
(緊急)  
Internet Explorer 8  
(2957689)  
(緊急)  
Internet Explorer 9  
(2957689)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2957189)  
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
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**注意**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Internet Explorer 7  
(2957689)  
(重要)  
Internet Explorer 8  
(2957689)  
(重要)  
Internet Explorer 9  
(2957689)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2957189)  
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
Internet Explorer 7  
(2957689)  
(重要)  
Internet Explorer 8  
(2957689)  
(重要)  
Internet Explorer 9  
(2957689)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2957189)  
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
Internet Explorer 7  
(2957689)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2957189)  
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
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
(2957689)  
(緊急)  
Internet Explorer 9  
(2957689)  
(緊急)  
Internet Explorer 10  
(2957689)  
(緊急)  
Internet Explorer 11  
(2957689)  
(緊急)  
Internet Explorer 11  
(2963950)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2965788)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(緊急)  
Internet Explorer 9  
(2957689)  
(緊急)  
Internet Explorer 10  
(2957689)  
(緊急)  
Internet Explorer 11  
(2957689)  
(緊急)  
Internet Explorer 11  
(2963950)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2965788)  
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
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**注意**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2957689)  
(重要)  
Internet Explorer 9  
(2957689)  
(重要)  
Internet Explorer 10  
(2957689)  
(重要)  
Internet Explorer 11  
(2957689)  
(重要)  
Internet Explorer 11  
(2963950)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2957189)  
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
Internet Explorer 8  
(2957689)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
(2957689)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit System  
(gdi32)  
(2964736)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2965788)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2957689)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(gdi32)  
(2964736)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2965788)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(緊急)  
Internet Explorer 11  
(2963950)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(gdi32)  
(2964736)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(gdi32)  
(2965155)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(DirectWrite)  
(2964718)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(DirectWrite)  
(2965161)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(重要)  
Microsoft XML コア サービス 3.0  
(2966631)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2957189)  
(重要)  
Windows 8.1 for 32-bit Systems  
(2961858)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2965788)  
(重要)  
Windows 8.1 for 32-bit Systems  
(2966034)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(緊急)  
Internet Explorer 11  
(2963950)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(gdi32)  
(2964736)  
(緊急)  
Windows 8.1 for x64-based Systems  
(gdi32)  
(2965155)  
(緊急)  
Windows 8.1 for x64-based Systems  
(DirectWrite)  
(2964718)  
(緊急)  
Windows 8.1 for x64-based Systems  
(DirectWrite)  
(2965161)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(重要)  
Microsoft XML コア サービス 3.0  
(2966631)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2957189)  
(重要)  
Windows 8.1 for x64-based Systems  
(2961858)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2965788)  
(重要)  
Windows 8.1 for x64-based Systems  
(2966034)  
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
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**注意**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2957689)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(gdi32)  
(2964736)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2965788)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2957689)  
(重要)  
Internet Explorer 11  
(2963950)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(gdi32)  
(2964736)  
(緊急)  
Windows Server 2012 R2  
(gdi32)  
(2965155)  
(緊急)  
Windows Server 2012 R2  
(DirectWrite)  
(2964718)  
(緊急)  
Windows Server 2012 R2  
(DirectWrite)  
(2965161)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(注意)  
Microsoft XML コア サービス 3.0  
(2966631)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2957189)  
(重要)  
Windows Server 2012 R2  
(2961858)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2965788)  
(重要)  
Windows Server 2012 R2  
(2966034)  
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
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
Internet Explorer 10  
(2957689)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(gdi32)  
(2964736)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2957189)  
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
(2957689)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(gdi32)  
(2964736)  
(緊急)  
Windows RT 8.1  
(DirectWrite)  
(2964718)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2957189)  
(重要)

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
[**MS14-035**](http://go.microsoft.com/fwlink/?linkid=400972)

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-033**](http://go.microsoft.com/fwlink/?linkid=398119)

</td>
<td style="border:1px solid black;">
[**MS14-031**](http://go.microsoft.com/fwlink/?linkid=396824)

</td>
<td style="border:1px solid black;">
[**MS14-030**](http://go.microsoft.com/fwlink/?linkid=400970)

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
[**注意**](http://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール) (Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
(Windows GDI+)  
(2957503)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(usp10)  
(2957509)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0 および Microsoft XML コア サービス 6.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
(gdi32)  
(2964736)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2957189)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2965788)  
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
(gdi32)  
(2964736)  
(緊急)  
Windows Server 2012 R2 (Server Core インストール)  
(gdi32)  
(2965155)  
(緊急)  
Windows Server 2012 R2 (Server Core インストール)  
(DirectWrite)  
(2964718)  
(緊急)  
Windows Server 2012 R2 (Server Core インストール)  
(DirectWrite)  
(2965161)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(2939576)  
(注意)  
Microsoft XML コア サービス 3.0  
(2966631)  
(注意)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2957189)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(2961858)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2965788)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(2966034)  
(重要)

</td>
</tr>
</table>
 
**MS14-036 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Office スイートおよびソフトウェア

 
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
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](http://go.microsoft.com/fwlink/?linkid=400971)

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
Microsoft Office 2007 Service Pack 3  
(2878233)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(2881069)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2880515)  
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
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](http://go.microsoft.com/fwlink/?linkid=400971)

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
Microsoft Office 2010 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)  
(2863942)  
(重要)  
Microsoft Office 2010 Service Pack 1 (32 ビット版)  
(2767915)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2863942)  
(重要)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2767915)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)  
(2863942)  
(重要)  
Microsoft Office 2010 Service Pack 1 (64 ビット版)  
(2767915)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2863942)  
(重要)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2767915)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 互換機能パック**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-034**](http://go.microsoft.com/fwlink/?linkid=400971)

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
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2880513)  
(重要)

</td>
</tr>
</table>
 
**MS14-036 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft コミュニケーション プラットフォームおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 Console**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](http://go.microsoft.com/fwlink/?linkid=400969)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(2968966)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](http://go.microsoft.com/fwlink/?linkid=400969)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)  
(2963285)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)  
(2963285)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

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
(2963282)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

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
(2963284)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2010

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2010  
(Web コンポーネント サーバー)  
(2963286)  
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
[**MS14-036**](http://go.microsoft.com/fwlink/?linkid=400968)

</td>
<td style="border:1px solid black;">
[**MS14-032**](http://go.microsoft.com/fwlink/?linkid=400969)

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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 ビット)  
(2881013)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(2881013)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 ビット)  
(2881013)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)  
(2881013)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 ビット)  
(2881013)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)  
(2881013)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64 ビット)  
(2881013)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)  
(2881013)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Server 2013

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync Server 2013  
(Web コンポーネント サーバー)  
(2963288)  
(重要)

</td>
</tr>
</table>
 
**MS14-036 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

**MS14-030**

-   RDP MAC の脆弱性 (CVE-2014-0296) を報告してくださった [Tripwire](http://www.tripwire.com/) の Andrew Swoboda 氏と Tyler Reguly 氏

     

**MS14-033**

-   MSXML エンティティ URI の脆弱性 (CVE-2014-1816) を報告してくださった Christian Kulenkampff 氏

     

**MS14-034**

-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、埋め込みフォントの脆弱性 (CVE-2014-2778) を報告してくださった s3tm3m

     

**MS14-035**

-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0282) を報告してくださった Simon Zuckerbraun 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-0282) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Renguang Yuan 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1762) を報告してくださった、[HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) の AbdulAziz Hariri 氏、Matt Molinyawe 氏、Jasiel Spelman 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1764) を報告してくださった [VUPEN](http://www.vupen.com/)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1766) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1766) を報告してくださった Andreas Schmidt 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1766) を報告してくださった IronRock 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1766) を報告してくださった匿名のリサーチャー
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1769) を報告してくださった、[OUSPG](https://www.ee.oulu.fi/research/ouspg/) の Atte Kettunen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1769) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Liu Long 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1769) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1769) を報告してくださった、[HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) の AbdulAziz Hariri 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1769) を報告してくださった、[NSFOCUS Security Team](http://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](http://weibo.com/demi6od)
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1769) を報告してくださった、Trend Micro の Yuki Chen 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1770) を報告してくださった、[Corelan](http://www.corelangcv.com/) の Peter 'corelanc0d3r' Van Eeckhoutte 氏
-   TLS サーバー証明書の再ネゴシエーションの脆弱性 (CVE-2014-1771) を報告してくださった、Institut National de Recherche en Informatique et en Automatique (INRIA) の Prosecco チーム
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1772) を報告してくださった [Omair](http://krash.in/) 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1772) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Liu Long 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1772) を報告してくださった、[Trend Micro](http://www.trendmicro.com/) の Jack Tang 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1772) を報告してくださった [Venustech Active-Defense Laboratory](http://www.venustech.com.cn/)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1773) を報告してくださった John Villamil 氏と Sean Larsson 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1773) を報告してくださった、[NSFOCUS Security Team](http://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](http://weibo.com/demi6od)
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1774) を報告してくださった AMol NAik 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1775) を報告してくださった、[Harmony Security](http://www.harmonysecurity.com/) の Stephen Fewer 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1775) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Hui Gao 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1775) を報告してくださった、TELUS Security Labs の Vulnerability Research Team の Arezou Hosseinzad-Amirkhizi 氏
-   Internet Explorer の情報漏えいの脆弱性 (CVE-2014-1777) を報告してくださった、[Context Information Security](http://www.contextis.com/) の James Forshaw 氏
-   Internet Explorer の特権の昇格の脆弱性 (CVE-2014-1778) を報告してくださった、[Context Information Security](http://www.contextis.com/) の James Forshaw 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1779) を報告してくださった匿名のリサーチャー
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1780) を報告してくださった [Soroush Dalili](http://www.secproject.com/) 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1781) を報告してくださった [NSFOCUS Security Team](http://www.nsfocus.com/)
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1782) を報告してくださった lokihardt@ASRT 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1782) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Liu Long 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1782) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Zhibin Hu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1782) を報告してくださった、[Trend Micro](http://www.trendmicro.com/) の Yuki Chen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1782) を報告してくださった、[knownseci](http://www.knownsec.com/) の ZhaoWei 氏
-   [iSIGHT Partners GVP Program](https://gvp.isightpartners.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1782) を報告してくださった 35c27308b34d55904da10770e5303503 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1782) を報告してくださった IronRock 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1782) を報告してくださった Sabre 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1783) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1784) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1784) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1784) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Zhibin Hu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1785) を報告してくださった SkyLined 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1785) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1785) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1786) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1788) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1789) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1789) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1790) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1791) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1792) を報告してくださった、[Corelan](http://www.corelangcv.com/) の Peter 'corelanc0d3r' Van Eeckhoutte 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1792) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1794) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1795) を報告してくださった、[FireEye](http://www.fireeye.com/) の Xiaobo Chen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1796) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Hui Gao 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1797) を報告してくださった Gareth Heyes 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1799) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Zhibin Hu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1799) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1799) を報告してくださった 0016EECD9D7159A949DAD3BC17E0A939 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1799) を報告してくださった Sweetchip 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1799) を報告してくださった Sabre 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1799) を報告してくださった、[NCC Group](https://www.nccgroup.com/) の Edward Torkington 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1799) を報告してくださった 4f7df027b11a6a44d72b1fa4da62bae7 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1799) を報告してくださった Sky 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1800) を報告してくださった SkyLined 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1802) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1803) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1803) を報告してくださった [Aniway.Anyway@gmail.com 氏](https://technet.microsoft.com/ja-JP/library////c(v=Security.10))
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1804) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Royce Lu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1804) を報告してくださった、[Trend Micro](http://www.trendmicro.com/) の Yuki Chen 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1805) を報告してくださった lokihardt@ASRT 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2753) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Liu Long 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2754) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Liu Long 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2755) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Xin Ouyang 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2755) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Zhibin Hu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2756) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2756) を報告してくださった 0016EECD9D7159A949DAD3BC17E0A939 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2757) を報告してくださった Simon Zuckerbraun 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2758) を報告してくださった匿名のリサーチャー
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2759) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2759) を報告してくださった、[VeriSign iDefense Labs](http://labs.idefense.com/) の Sabre 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2760) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Zhibin Hu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2761) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2761) を報告してくださった 0016EECD9D7159A949DAD3BC17E0A939 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2763) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2764) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2764) を報告してくださった、[NSFOCUS Security Team](http://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](http://weibo.com/demi6od)
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2764) を報告してくださった匿名のリサーチャー
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2765) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2766) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2767) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2768) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2768) を報告してくださった、[Trend Micro](http://www.trendmicro.com/) の Yuki Chen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2769) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2769) を報告してくださった [Venustech Active-Defense Laboratory](http://www.venustech.com.cn/)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2770) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Xin Ouyang 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2771) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Royce Lu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2772) を報告してくださった、[Harmony Security](http://www.harmonysecurity.com/) の Stephen Fewer 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2773) を報告してくださった [Keen Team](http://www.k33nteam.org/)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2773) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2775) を報告してくださった、[HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) の AbdulAziz Hariri 氏、Matt Molinyawe 氏、Jasiel Spelman 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2776) を報告してくださった、[HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) の AbdulAziz Hariri 氏、Matt Molinyawe 氏、Jasiel Spelman 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2777) を報告してくださった [VUPEN](http://www.vupen.com/)
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2782) を報告してくださった匿名のリサーチャー
-   このセキュリティ情報に含まれている多層防御の変更についてマイクロソフトと協力してくださった、[Cyber Defense Institute, Inc.](http://www.cyberdefense.jp/) の Noriaki Iwasaki 氏

     

**MS14-036**

-   Unicode スクリプト プロセッサの脆弱性 (CVE-2014-1817) を報告してくださった、[Security-Assessment.com](http://www.security-assessment.com/) の Scott Bell 氏
-   GDI+ の画像解析の脆弱性 (CVE-2014-1818) を報告してくださった、[Google Security Team](http://www.google.com/) の Mateusz Jurczyk 氏、Ivan Fratric 氏、および Ben Hawkes 氏

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja):Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)

国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2014/06/11):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2014/06/18):MS14-035 について、Exploitability Index (悪用可能性指標) に CVE-2014-2782 の Exploitability (悪用可能性) を追加しました。今回の更新は情報のみの変更です。

*Page generated 2014-10-07 16:53Z-07:00.*
