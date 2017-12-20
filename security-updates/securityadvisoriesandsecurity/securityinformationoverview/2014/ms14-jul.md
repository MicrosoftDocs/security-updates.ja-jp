---
TOCTitle: 'MS14-JUL'
Title: 2014 年 7 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms14-jul'
ms:contentKeyID: 62554029
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms14-jul(v=Security.10)'
---

2014 年 7 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2014 年 7 月 9 日 | 最終更新日:2014 年 7 月 30 日

**バージョン:** 1.1

このセキュリティ情報の概要は 2014 年 7 月公開のセキュリティ情報の一覧です。

2014 年 7 月のセキュリティ情報の公開により、2014 年 7 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2014 年 7 月 9 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。月例 Webcast の表示、およびその他のセキュリティ情報 Webcast へのリンクについては、[Microsoft Security Bulletin Webcast (英語情報)](http://technet.microsoft.com/security/dn756352) を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (2975687)<br />
<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer に存在する 1 件の一般に公開された脆弱性および 24 件の非公開で報告された脆弱性を解決します。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402326">MS14-038</a></td>
<td style="border:1px solid black;"><strong>Windows Journal の脆弱性により、リモートでコードが実行される (2975689)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性で、特別に細工されたジャーナル ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402327">MS14-039</a></td>
<td style="border:1px solid black;"><strong>スクリーン キーボードの脆弱性により、特権が昇格される (2975685)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が低整合性プロセスの脆弱性を使用してスクリーン キーボード (OSK) を実行し、特別に細工されたプログラムを標的となるシステムにアップロードした場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402328">MS14-040</a></td>
<td style="border:1px solid black;"><strong>Ancillary Function ドライバー (AFD) の脆弱性により、特権が昇格される (2975684)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402330">MS14-041</a></td>
<td style="border:1px solid black;"><strong>DirectShow の脆弱性により、特権が昇格される (2975681)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者がまず低整合性プロセスで別の脆弱性を悪用した後、ログオンしているユーザーのコンテキストで、特別に細工されたコードを実行すると、特権が昇格される可能性があります。既定で、Windows 8、および Windows 8.1 の新しい、イマーシブな閲覧エクスペリエンスは、拡張保護モード (EPM) で稼働します。たとえば、新しい Windows タブレット上でタッチ式の Internet Explorer 11 ブラウザーを利用しているお客様は、既定で拡張保護モード (EPM) を利用しています。拡張保護モード (EPM) は、64 ビット版システム上での脆弱性の悪用を緩和するのに役立つ、強化されたセキュリティ保護を利用します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402462">MS14-042</a></td>
<td style="border:1px solid black;"><strong>Microsoft Service Bus の脆弱性により、サービス拒否が起こる (2972621)<br />
</strong><br />
このセキュリティ更新プログラムは Microsoft Service Bus for Windows Server に存在する 1 件の一般で公開された脆弱性を解決します。この脆弱性により、リモートの認証された攻撃者が、標的のシステムに一連の特別に細工された Advanced Message Queuing Protocol (AMQP) メッセージを送信するプログラムを作成して実行した場合、サービス拒否が起こる可能性があります。Microsoft Service Bus for Windows Server は、Microsoft オペレーティング システムにも付属していません。影響を受けるシステムに脆弱性が存在する条件としては、まず Microsoft Service Bus をダウンロード、インストール、および構成してから、その構成の詳細 (ファームの証明書) を他のユーザーと共有していることが必要です。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">警告</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動不要</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1763">CVE-2014-1763</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1765">CVE-2014-1765</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2785">CVE-2014-2785</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2786">CVE-2014-2786</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2787">CVE-2014-2787</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2788">CVE-2014-2788</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2789">CVE-2014-2789</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2790">CVE-2014-2790</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2791">CVE-2014-2791</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2792">CVE-2014-2792</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2794">CVE-2014-2794</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2795">CVE-2014-2795</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2797">CVE-2014-2797</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2798">CVE-2014-2798</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2800">CVE-2014-2800</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2801">CVE-2014-2801</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2802">CVE-2014-2802</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2803">CVE-2014-2803</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2804">CVE-2014-2804</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2806">CVE-2014-2806</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2807">CVE-2014-2807</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2809">CVE-2014-2809</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2813">CVE-2014-2813</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402324">MS14-037</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4066">CVE-2014-4066</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402326">MS14-038</a></td>
<td style="border:1px solid black;">Windows Journal のリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1824">CVE-2014-1824</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402327">MS14-039</a></td>
<td style="border:1px solid black;">スクリーン キーボードの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2781">CVE-2014-2781</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402328">MS14-040</a></td>
<td style="border:1px solid black;">Ancillary Function ドライバーの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-1767">CVE-2014-1767</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=402330">MS14-041</a></td>
<td style="border:1px solid black;">DirectShow の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-2780">CVE-2014-2780</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(2962872)  
(警告)  
Internet Explorer 7  
(2962872)  
(警告)  
Internet Explorer 8  
(2962872)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2961072)  
(重要)

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
(2962872)  
(警告)  
Internet Explorer 7  
(2962872)  
(警告)  
Internet Explorer 8  
(2962872)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2961072)  
(重要)

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
(2962872)  
(警告)  
Internet Explorer 7  
(2962872)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2961072)  
(重要)

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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(緊急)  
Internet Explorer 8  
(2962872)  
(緊急)  
Internet Explorer 9  
(2962872)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(緊急)  
Internet Explorer 8  
(2962872)  
(緊急)  
Internet Explorer 9  
(2962872)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2972280)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
Internet Explorer 7  
(2962872)  
(警告)  
Internet Explorer 8  
(2962872)  
(警告)  
Internet Explorer 9  
(2962872)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(警告)  
Internet Explorer 8  
(2962872)  
(警告)  
Internet Explorer 9  
(2962872)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2962872)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2961072)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(緊急)  
Internet Explorer 9  
(2962872)  
(緊急)  
Internet Explorer 10  
(2962872)  
(緊急)  
Internet Explorer 11  
(2962872)  
(緊急)  
Internet Explorer 11  
(2963952)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(緊急)  
Internet Explorer 9  
(2962872)  
(緊急)  
Internet Explorer 10  
(2962872)  
(緊急)  
Internet Explorer 11  
(2962872)  
(緊急)  
Internet Explorer 11  
(2963952)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2972280)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(警告)  
Internet Explorer 9  
(2962872)  
(警告)  
Internet Explorer 10  
(2962872)  
(警告)  
Internet Explorer 11  
(2962872)  
(警告)  
Internet Explorer 11  
(2963952)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2962872)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2961072)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2962872)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(緊急)  
Internet Explorer 11  
(2963952)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2971850)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(2974286)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2973201)  
(重要)  
Windows 8.1 for 32-bit Systems  
(2973906)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2961072)  
(重要)  
Windows 8.1 for 32-bit Systems  
(2973408)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2972280)  
(重要)  
Windows 8.1 for 32-bit Systems  
(2973932)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(緊急)  
Internet Explorer 11  
(2963952)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2971850)  
(緊急)  
Windows 8.1 for x64-based Systems  
(2974286)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2973201)  
(重要)  
Windows 8.1 for x64-based Systems  
(2973906)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2961072)  
(重要)  
Windows 8.1 for x64-based Systems  
(2973408)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2972280)  
(重要)  
Windows 8.1 for x64-based Systems  
(2973932)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2972280)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2962872)  
(警告)  
Internet Explorer 11  
(2963952)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2971850)  
(緊急)  
Windows Server 2012 R2  
(2974286)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2973201)  
(重要)  
Windows Server 2012 R2  
(2973906)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2961072)  
(重要)  
Windows Server 2012 R2  
(2973408)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2972280)  
(重要)  
Windows Server 2012 R2  
(2973932)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
(2962872)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(2961072)  
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
(2962872)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2971850)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2961072)  
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
[**MS14-037**](http://go.microsoft.com/fwlink/?linkid=402324)

</td>
<td style="border:1px solid black;">
[**MS14-038**](http://go.microsoft.com/fwlink/?linkid=402326)

</td>
<td style="border:1px solid black;">
[**MS14-039**](http://go.microsoft.com/fwlink/?linkid=402327)

</td>
<td style="border:1px solid black;">
[**MS14-040**](http://go.microsoft.com/fwlink/?linkid=402328)

</td>
<td style="border:1px solid black;">
[**MS14-041**](http://go.microsoft.com/fwlink/?linkid=402330)

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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2961072)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2961072)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2961072)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2973201)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2961072)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
(2973201)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(2973906)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2961072)  
(重要)  
Windows Server 2012 R2 (Server Core インストール)  
(2973408)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
 

### Windows Server ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Service Bus for Windows Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-042**](http://go.microsoft.com/fwlink/?linkid=402462)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;" colspan="2">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Service Bus for Windows Server

</td>
<td style="border:1px solid black;" colspan="2">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 上にインストールされている Microsoft Service Bus 1.1  
(2972621)  
(警告)  
Windows Server 2012 上にインストールされている Microsoft Service Bus 1.1  
(2972621)  
(警告)  
Windows Server 2012 R2 上にインストールされている Microsoft Service Bus 1.1  
(2972621)  
(警告)

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

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

**MS14-037**

-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1763) を報告してくださった [VUPEN](http://www.vupen.com/)
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1765) を報告してくださった [Andreas Schmidt 氏](https://technet.microsoft.com/ja-JP/mailto:andreas.schmidt@siberas.de)
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1765) を報告してくださった 0016EECD9D7159A949DAD3BC17E0A939 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-1765) を報告してくださった 91fba4fa08fe776e7369ab4d96db6578 氏
-   EV (Extended Validation) 証明書セキュリティ機能のバイパスの脆弱性 (CVE-2014-2783) を報告してくださった [Eric Lawrence 氏](https://twitter.com/ericlaw)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2785) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2785) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Liu Long 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2786) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2787) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2788) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2789) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2790) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yujie Wen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2790) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Liu Long 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2791) を報告してくださった Arthur Gerkis 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2792) を報告してくださった、[HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) の AbdulAziz Hariri 氏、Matt Molinyawe 氏、Jasiel Spelman 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2794) を報告してくださった、[KnownSec](http://www.knownsec.com/) の ZhaoWei 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2795) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Hui Gao 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2797) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Royce Lu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2798) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2800) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2801) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2802) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yuki Chen 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2802) を報告してくださった Sky 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2802) を報告してくださった、[NSFOCUS Security Team](http://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](https://github.com/demi6od)
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2803) を報告してくださった AMol NAik 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2803) を報告してくださった Garage4Hackers 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2803) を報告してくださった、[Qihoo 360](http://www.360.cn/) の Yuki Chen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2804) を報告してくださった、[NSFOCUS Security Team](http://www.nsfocus.com/) の exp-sky 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2806) を報告してくださった、[NSFOCUS Security Team](http://www.nsfocus.com/) の [Chen Zhang (demi6od) 氏](https://github.com/demi6od)
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2807) を報告してくださった、Yenteasy - Security Research の José A. Vázquez 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2809) を報告してくださった [Aniway.Anyway@gmail.com 氏](mailto:aniway.anyway@gmail.com)
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-2813) を報告してくださった、[HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) の Abdul Aziz Hariri 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4066) を報告してくださった、[Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏

     

**MS14-038**

-   Windows Journal のリモート コード実行の脆弱性 (CVE-2014-1824) を報告してくださった [Hamburgers.maccoy@gmail.com 氏](mailto:hamburgers.maccoy@gmail.com)

     

**MS14-039**

-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力してスクリーン キーボードの特権の昇格の脆弱性 (CVE-2014-2781) を報告してくださった [lokihardt@asrt 氏](https://technet.microsoft.com/ja-JP/mailto:lokihardt@asrt)

     

**MS14-040**

-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Ancillary Function ドライバーの特権の昇格の脆弱性 (CVE-2014-1767) を報告してくださった [Sebastian Apelt 氏](https://technet.microsoft.com/ja-JP/mailto:sebastian.apelt@siberas.de)

     

**MS14-041**

-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して DirectShow の特権の昇格の脆弱性 (CVE-2014-2780) を報告してくださった [VUPEN](http://www.vupen.com/)

     

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

-   V1.0 (2014/07/09):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2014/07/30):MS14-037 について、Exploitability Index (悪用可能性指標) に CVE-2014-4066 の Exploitability (悪用可能性) を追加しました。今回の更新は情報のみの変更です。

*Page generated 2014-08-06 16:51Z-07:00.*
