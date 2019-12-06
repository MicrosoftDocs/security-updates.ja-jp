---
TOCTitle: 'MS11-OCT'
Title: Microsoft Security Bulletin Summary for 10月 2011
ms:assetid: 'ms11-oct'
ms:contentKeyID: 61229692
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-oct(v=Security.10)'
--- 

Microsoft Security Bulletin Summary for 10月 2011
=================================================

公開日: 2011年10月11日 | 最終更新日: 2011年10月26日

**バージョン:** 1.1

このセキュリティ情報の概要は 2011 年 10 月公開のセキュリティ情報の一覧です。

2011 年 10 月のセキュリティ情報の公開により、2011 年 10 月 7 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2011 年 10 月 12 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[10 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032487956) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](https://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

概要
----

 
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェアおよびダウンロード先」を参照してください。

 
<p></p>

<table style="border:1px solid black;">
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078">MS11-078</a></td>
<td style="border:1px solid black;"><strong>.NET Framework および Microsoft Silverlight の脆弱性により、リモートでコードが実行される (2604930)</strong> <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft .NET Framework および Microsoft Silverlight の脆弱性を解決します。この脆弱性では、ユーザーが XAML ブラウザー アプリケーション (XBAP) または Silverlight アプリケーションを使用して、特別に細工された Web ページを閲覧した場合に、クライアント システムでリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この脆弱性により、サーバーが ASP.NET ページの処理を許可し、攻撃者が特別に細工した ASP.NET ページをそのサーバーにアップロードして、ページを実行した場合に、Web ホスティングのシナリオと同様に、IIS を実行しているサーバー システム上で、リモートでコードが実行される可能性があります。この脆弱性は、コード アクセス セキュリティ (CAS) の制限を回避する目的で Windows .NET で悪用される可能性もあります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft .NET Framework、Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (2497640)</strong> <br />
<br />
このセキュリティ更新プログラムは非公開で報告された 8 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-075">MS11-075</a></td>
<td style="border:1px solid black;"><strong>Microsoft Active Accessibility の脆弱性により、リモートでコードが実行される (2623699)</strong> <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Active Accessibility コンポーネントの脆弱性を解決します。この脆弱性で、攻撃者がユーザーに特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルと同じネットワーク ディレクトリにある正当なファイルを開かせた場合、リモートでコードが実行される可能性があります。次に、正当なファイルを開いている間に Microsoft Active Accessibility コンポーネントが DLL ファイルをロードし、それに含まれている任意のコードを実行しようとする可能性があります。攻撃は、ユーザーが信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問して、この場所から影響を受けるアプリケーションでロードされるドキュメントを開いた場合に実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-076">MS11-076</a></td>
<td style="border:1px solid black;"><strong>Windows Media Center の脆弱性により、リモートでコードが実行される (2604926)</strong> <br />
<br />
このセキュリティ更新プログラムは 1 件の Windows Media Center に存在する一般に公開された脆弱性を解決します。この脆弱性で、攻撃者がユーザーに特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルと同じネットワーク ディレクトリにある正当なファイルを開かせた場合、リモートでコードが実行される可能性があります。次に、正当なファイルを開いている間に Windows Media Center が DLL ファイルをロードし、それに含まれている任意のコードを実行する可能性があります。攻撃が行われるには、ユーザーが信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問し、正当なファイルを開くことが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077">MS11-077</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (2567053)</strong> <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 4 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性のうちで最も深刻なものは、ユーザーがネットワーク共有、UNC または WebDAV の場所、あるいは電子メールの添付ファイルにある特別に細工されたフォント ファイル (.fon ファイルなど) を開くと、リモートでコードが実行される可能性があることです。リモートの攻撃が行われるには、ユーザーが信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問し、特別に細工されたフォント ファイルを開くか、そのファイルを電子メールの添付ファイルとして開くことが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-079">MS11-079</a></td>
<td style="border:1px solid black;"><strong>Microsoft Forefront Unified Access Gateway の脆弱性により、リモートでコードが実行される (2544641)</strong> <br />
<br />
このセキュリティ更新プログラムは Forefront Unified Access Gateway (UAG) に存在する 5 つの非公開で報告された脆弱性を解決します。これらの中で最も深刻な脆弱性では、ユーザーが特別な細工がされた URL を使用する影響を受ける Web サイトを訪問した場合に、リモートでコードが実行される可能性があります。しかし、攻撃者はこのような Web サイトにユーザーを強制的に訪問させることはできません。通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Forefront United Access Gateway</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-080">MS11-080</a></td>
<td style="border:1px solid black;"><strong>Ancillary Function ドライバーの脆弱性により、特権が昇格される (2592799)</strong> <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Windows Ancillary Function ドライバー (AFD) の脆弱性を解決します。この脆弱性により、攻撃者がユーザーのシステムにログオンし、特別に細工されたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-082">MS11-082</a></td>
<td style="border:1px solid black;"><strong>Host Integration Server の脆弱性により、サービス拒否が起こる (2607670)</strong> <br />
<br />
このセキュリティ更新プログラムは Host Integration Server に存在する 2 件の公開された脆弱性を解決します。リモートの攻撃者が、UDP ポート 1478 または TCP ポート 1477 および 1478 でリッスンしている Host Integration Server に、特別に細工したネットワーク パケットを送信すると、脆弱性により、サービス拒否が発生する可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。今回の場合、Host Integration Server はインターネットからブロックされている必要があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Host Integration Server</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >脆弱性のタイトル</th>
<th style="border:1px solid black;" >CVE の識別番号</th>
<th style="border:1px solid black;" >最新のソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >旧バージョンのソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >サービス拒否の悪用可能性の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-075">MS11-075</a></td>
<td style="border:1px solid black;">Active Accessibility コンポーネントの安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1247">CVE-2011-1247</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-076">MS11-076</a></td>
<td style="border:1px solid black;">Media Center の安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2009">CVE-2011-2009</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077">MS11-077</a></td>
<td style="border:1px solid black;">Win32k の NULL ポインター逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1985">CVE-2011-1985</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077">MS11-077</a></td>
<td style="border:1px solid black;">フォント ライブラリ ファイルのバッファ オーバーランの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2003">CVE-2011-2003</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077">MS11-077</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2011">CVE-2011-2011</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078">MS11-078</a></td>
<td style="border:1px solid black;">.NET Framework のクラス継承の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1253">CVE-2011-1253</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-079">MS11-079</a></td>
<td style="border:1px solid black;">ExcelTable 応答分割の XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1895">CVE-2011-1895</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">セキュリティ情報で参照されている特定のプラットフォームでの情報漏えい</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-079">MS11-079</a></td>
<td style="border:1px solid black;">ExcelTable を反映した XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1896">CVE-2011-1896</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">セキュリティ情報で参照されている特定のプラットフォームでの情報漏えい</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-079">MS11-079</a></td>
<td style="border:1px solid black;">既定を反映した XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1897">CVE-2011-1897</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">セキュリティ情報で参照されている特定のプラットフォームでの情報漏えい</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-079">MS11-079</a></td>
<td style="border:1px solid black;">Poisoned Cup のコード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1969">CVE-2011-1969</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-079">MS11-079</a></td>
<td style="border:1px solid black;">Null セッション Cookie クラッシュの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2012">CVE-2011-2012</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-080">MS11-080</a></td>
<td style="border:1px solid black;">Ancillary Function ドライバーの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2005">CVE-2011-2005</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;">スクロール イベントのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1993">CVE-2011-1993</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;">OLEAuto32.dll のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1995">CVE-2011-1995</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;">Option 要素のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1996">CVE-2011-1996</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;">OnLoad イベントのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1997">CVE-2011-1997</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;">Jscript9.dll のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1998">CVE-2011-1998</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;">Select 要素のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1999">CVE-2011-1999</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;">Body 要素のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2000">CVE-2011-2000</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081">MS11-081</a></td>
<td style="border:1px solid black;">仮想関数テーブルの破損により、リモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2001">CVE-2011-2001</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-082">MS11-082</a></td>
<td style="border:1px solid black;">snabase.exe の無限ループ DoS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2007">CVE-2011-2007</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。<br />
<br />
この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-082">MS11-082</a></td>
<td style="border:1px solid black;">未割り当てメモリ アクセス DoS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-2008">CVE-2011-2008</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。<br />
<br />
この脆弱性は一般に公開されていました。</td>
</tr>
</tbody>
</table>

<p></p>

 

影響を受けるソフトウェアおよびダウンロード先
--------------------------------------------

 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

**これらの表はどのように使用しますか?**

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。

**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。

#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="7">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-075)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-076)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-080)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3:](https://www.microsoft.com/download/details.aspx?familyid=a54a7ad5-0504-4cc6-9eca-ba9f31c35a17&displaylang=ja)  
(KB2572066)  
(Media Center Edition 2005 および Tablet PC Edition 2005 のみ)  
(緊急)  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d&displaylang=ja)  
(KB2572073)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=822f91f5-bf92-42c4-ad33-b971be37d772&displaylang=ja)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=e942554d-6cb6-4e48-a876-3470671a95a2&displaylang=ja)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=a911b5b0-5e46-4a37-83e7-595e20585c56&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=96af60b9-4b8d-4a9b-b125-10775bb48252&displaylang=ja)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=9157e677-ab3f-44b0-9735-192bc7421ba7&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=f1b2dceb-5bef-4522-9001-8dff0545d805)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d&displaylang=ja)  
(KB2572073)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=6260318c-e579-4cdf-93e3-4608892bc79e&displaylang=ja)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=f04ad852-1418-4fc4-bd57-f47895bbf3a8&displaylang=ja)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=67ebf641-1341-4642-96ba-bab5446d7b5d&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=c8fcf427-17d0-4caa-b406-50703f980862&displaylang)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0f2444ac-61bd-47cf-9c1e-da86a2b0cfb5&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9a37864e-8543-4c52-aa73-e3c190860d76)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-075)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-076)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-080)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b968b0bd-577b-4ea2-a192-a80fe7c20791&displaylang=ja)  
(KB2572069)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d&displaylang=ja)  
(KB2572073)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=172c55f3-6249-4ba3-a4a4-677a03262ff3&displaylang=ja)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=6ffbdb93-7b92-4197-bb6c-5c305e8072a8&displaylang=ja)  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=14ef20d4-3530-49b2-91b7-d278d9098023&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=09e178f8-2bd2-46e1-b975-4938ee1f304d&displaylang=ja)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3bd62bf6-3400-4c03-95fe-148112b341e8&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=29228167-b811-43d7-b4a0-91e385b598a5)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d&displaylang=ja)  
(KB2572073)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=f5a0a8db-34d4-4f0a-ab6b-7b2fb420ab91&displaylang=ja)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=7379b3bf-6af0-43cb-bf8b-505e8563fc84&displaylang=ja)  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b35c95f5-30b0-43a9-aa6a-6db63cab0dcb&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=9b8030db-1f47-4666-8cb5-1c56577f2340&displaylang)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b73f4e87-9655-46d5-beb2-ea245dcd280d&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0816d729-6769-4ca6-a14e-71750eca8d29)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=719b3da5-52ca-4d56-a2c5-69711039e59d&displaylang=ja)  
(KB2572073)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?familyid=5825cb4a-47d5-423f-b4c5-2d0fc50856c0&displaylang=ja)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=11c4878e-df58-4369-b9c0-cb0a230c92dd&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=82653b8c-0e58-440d-9702-8847f599caed)  
(KB2605295)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=a618cc19-5ebc-462e-a518-d9bfe41ed98e&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=42465652-2664-4fd5-9a22-ae847b08e7c8)  
(重要)
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-075)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-076)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-080)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb&displaylang=ja)  
(KB2572075)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=630335ac-5a30-46b4-acc1-c4d8bd289668&displaylang=ja)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=76c8124e-81b9-4a6a-bd53-fbdaf45189aa&displaylang=ja)  
(緊急)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=7de276a3-a20d-49de-82b0-51cb22ad73af&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=96b089c0-a2e7-44cb-9fc4-9569b3993afa&displaylang=ja)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=44f7f10b-86ff-470f-996a-d4aa51c4d18f&displaylang=ja)  
(KB2579686)  
(重要)  
[Windows Media Center TV Pack for Windows Vista (32 ビット版)](https://www.microsoft.com/download/details.aspx?familyid=60e50f72-4001-423c-831c-8ff1f1b8f090&displaylang=ja)<sup>[1]</sup>
(KB2579692)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ff53d01b-97b7-40d2-af88-4978f1099a7c&displaylang=ja)  
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
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb&displaylang=ja)  
(KB2572075)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=9aabd7a2-0b2f-4c42-a9cf-2ec69ae6b82d&displaylang=ja)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=3454940c-acc2-4e09-8154-075b4be1b697&displaylang=ja)  
(緊急)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=3df0c31b-344a-4163-93d2-79df1653b339&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=b79a389c-8340-4dd2-9ab1-a0943c5a220f&displaylang=ja)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=cbb66cd7-2688-410f-8a03-fd28e6ef5b01&displaylang=ja)  
(KB2579686)  
(重要)  
[Windows Media Center TV Pack for Windows Vista (64 ビット版)](https://www.microsoft.com/download/details.aspx?familyid=371c7dab-5aa6-4502-80ee-ae69b736b972&displaylang=ja)<sup>[1]</sup>
(KB2579692)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=47322e11-f1cf-4f70-b939-8cac9bbfc2bc&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-075)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-076)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-080)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)\*\*  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb&displaylang=ja)\*\*  
(KB2572075)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)\*\*<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=5660e23c-13a3-4275-ac69-38f03f17491a&displaylang=ja)\*\*  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=bd144435-1afd-4d6e-a100-fbd613eee409&displaylang=ja)\*\*  
(警告)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=1a7f9855-20ce-4fe0-a903-bd1f145075df&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7cd1ecec-8a3f-4cb2-833c-a177c9602ff5&displaylang=ja)\*  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c7498ee-eba4-44fd-8846-0b2e96c96705&displaylang=ja)\*  
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
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)\*\*  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb&displaylang=ja)\*\*  
(KB2572075)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)\*\*<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=415b1c59-f3dc-4f4f-b2eb-68692d6efc05&displaylang=ja)\*\*  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=b0c4949f-bce0-4255-a5f2-cf5ecf7416da&displaylang=ja)\*\*  
(警告)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=28a09e42-5865-48b2-af26-ebc8162c3286&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=456e450c-3928-4130-8127-e4d3f482c1ca&displaylang=ja)\*  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=40386742-f397-402e-8810-63d3d6ba12a6&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=6100e577-deb5-4395-b851-e19e0ca79507&displaylang=ja)  
(KB2572067)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=7c27128d-eaf9-4416-b8b1-9edab9102feb&displaylang=ja)  
(KB2572075)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?familyid=31e68c7f-4db5-463f-a315-92f574af080b&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=2e9930d3-ba13-446d-bfa0-60720c48203b&displaylang=ja)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=3633402b-96cb-4f36-b137-d07d1baf28c7&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-075)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-076)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-080)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems のみ:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2&displaylang=ja)  
(KB2572076)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618&displaylang=ja)  
(KB2572077)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=4de175be-bbb7-4912-ba4e-d6fe96606c9e&displaylang=ja)  
(緊急)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=b49876c7-7c65-4b6d-be9a-9f18be23037b&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=02d28e59-b38f-433a-a568-e86f9d43dd42&displaylang=ja)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=76fcf0ec-9062-4090-acb2-401355341a2b&displaylang=ja)  
(KB2579686)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=9e40bc26-f77f-4b57-9b3d-9d053c19ac56&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2&displaylang=ja)  
(KB2572076)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618&displaylang=ja)  
(KB2572077)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=16fd238e-6f65-4d38-88ae-2689817588e1&displaylang=ja)  
(緊急)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=cc0773f2-6099-4d55-9971-ee6546369c7f&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=904dec69-e8b9-4b23-a5ea-d3e7e9b9df07&displaylang=ja)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=78c099b7-4bcb-4da7-8967-512c6541c541&displaylang=ja)  
(KB2579686)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=219554e6-eb5a-42d0-90c0-42b4d0772cfd&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078)
</td>
<td style="border:1px solid black;">
[**MS11-081**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-081)
</td>
<td style="border:1px solid black;">
[**MS11-075**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-075)
</td>
<td style="border:1px solid black;">
[**MS11-076**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-076)
</td>
<td style="border:1px solid black;">
[**MS11-077**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-077)
</td>
<td style="border:1px solid black;">
[**MS11-080**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-080)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2&displaylang=ja)\*  
(KB2572076)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems のみ:  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618&displaylang=ja)\*  
(KB2572077)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)\*<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=8435781e-0f77-41d0-abb9-9b70f5b02d33&displaylang=ja)\*\*  
(警告)  
[Internet Explorer 9](https://www.microsoft.com/download/details.aspx?familyid=646a9a56-c343-45cb-a255-303602aa5a64&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c7bd50b7-03f1-4ea4-ad71-d428822c62f8&displaylang=ja)\*  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=39bd4cfb-fe61-41b8-a5a2-73a9e720fc72&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=81be7ff1-3ba2-430c-9edf-619cc246daf2&displaylang=ja)  
(KB2572076)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 のみ:  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?familyid=98403988-7438-4260-95b5-a4796dbe0618&displaylang=ja)  
(KB2572077)  
(緊急)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/details.aspx?familyid=770e7b58-6544-4f59-9893-b3eadf6d6c8a&displaylang=ja)<sup>[1]</sup>
(KB2572078)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?familyid=2676597e-c1d4-4397-8dc4-515ce3d0c5fd&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=aa816682-9652-433c-b1b4-5d0bc17b6a87&displaylang=ja)  
(KB2564958)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0d35c6d0-6d2d-42bf-a97f-4c5e01b1937e&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008** **および** **Windows Server 2008 R2 に関する注意**

**\*Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

**\*\*Server Core インストールは影響を受けません。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

**MS11-078 に関する注意**

<sup>[1]</sup>**.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。**.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「[.NET Framework のインストール](https://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

**MS11-076 に関する注意**

<sup>[1]</sup>Windows Media Center TV Pack for Windows Vista は Original Equipment Manufacturer (OEM) のインストールの Windows Vista の Home Premium および Ultimate エディションでのみ、オプションのコンポーネントとして利用可能です。このオプション コンポーネントを x64-based システムにインストールしているお客様は、両方の利用可能な更新プログラムをインストールする必要があります。最善策として、マイクロソフトはオペレーティング システムの更新プログラム (KB2579686) をインストールしてから、Windows Media Center TV Pack の更新プログラム (KB2579692) をインストールすることを推奨します。32-bit システムに Media Center TV Pack をインストールしているお客様は、KB2579692 のみをインストールする必要があります。

#### Microsoft サーバー ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Host Integration Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-082**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-082)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=b7536139-63ea-482a-8d1c-0faad1fcfaa4&displaylang=ja)  
(KB2578757)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2006
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2006 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=3bc0c89c-56b2-4463-b671-2a58bed9667b&displaylang=ja)  
(KB2579597)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Host Integration Server 2009
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2009](https://www.microsoft.com/download/details.aspx?familyid=28716ed4-f215-4c69-b6b8-63fbeecefc5b&displaylang=ja)  
(KB2579598)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2010
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2010](https://www.microsoft.com/download/details.aspx?familyid=dbbd67d8-68aa-424d-8eaf-a273a71624d1&displaylang=ja)  
(KB2579599)  
(重要)
</td>
</tr>
</table>

<p></p>

 

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-078**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-078)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
Mac にインストールされている [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f&displaylang=ja)  
(KB2617986)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f&displaylang=ja)  
(KB2617986)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている [Microsoft Silverlight 4](https://www.microsoft.com/download/details.aspx?familyid=8bde4992-bdf7-4345-835a-4e1fbfcd8c5f&displaylang=ja)\*\*  
(KB2617986)
</td>
</tr>
</table>

<p></p>

 
**MS11-078** ***に**関する*注意**

**\*\*Server Core インストールは影響を受けません。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft リモート アクセス ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Forefront Unified Access Gateway
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 識別名**
</td>
<td style="border:1px solid black;">
[**MS11-079**](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-079)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**総合的な深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Unified Access Gateway
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Unified Access Gateway 2010](https://www.microsoft.com/download/details.aspx?familyid=770ad8ba-4d9a-404e-9515-6ed1e41682df&displaylang=ja)<sup>[1]</sup>
(KB2522482)  
(重要)  
[Microsoft Forefront Unified Access Gateway 2010 Update 1](https://www.microsoft.com/download/details.aspx?familyid=b0de8d20-9c25-41c0-9c02-d263b9ed22fa&displaylang=ja)<sup>[1]</sup>
(KB2522483)  
(重要)  
[Microsoft Forefront Unified Access Gateway 2010 Update 2](https://www.microsoft.com/download/details.aspx?familyid=166bdfcb-5088-4471-9d51-a3071ac13b73&displaylang=ja)<sup>[1]</sup>
(KB2522484)  
(重要)  
[Microsoft Forefront Unified Access Gateway 2010 Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=8b6ad2ae-e168-45d9-bd3f-5590e0cbd2b5&displaylang=ja)<sup>[1]</sup>
(KB2522485)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**MS11-079** **に関する注意**

<sup>[1]</sup>この更新プログラムは、マイクロソフト ダウンロード センターから利用可能です。

検出および適用ツールとガイダンス
--------------------------------

 
**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](https://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](https://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](https://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](https://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](https://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](https://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

**検出および適用のガイダンス**

マイクロソフトは、セキュリティ更新プログラムの検出および適用に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および適用のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](https://support.microsoft.com/kb/961747) を参照してください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](https://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

**System Center Configuration Manager 2007**

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](https://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。Configuration Manager の詳細については、[System Center Configuration Manager](https://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

**注**: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](https://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

**注** : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](https://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199)
-   :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/bb456965.aspx)
-   (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086) を参照してください。

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   [Adobe Systems, Inc.](https://www.adobe.com)
-   の Anshul Kothari 氏および Nishant Kaushik 氏と協力して、MS11-075 で説明している問題を報告してくださった
-   [Mila Parkour](https://contagiodump.com)
-   氏
-   MS11-077 で説明している問題を報告してくださった [BitDefender](https://www.bitdefender.com/) の Andrei Lutas 氏
-   MS11-077 で説明している問題を報告してくださった [Norman](https://www.norman.com/) の Tarjei Mandt 氏
-   MS11-077 で説明している問題を報告してくださった Maik Wellmann 氏
-   MS11-077 で説明している問題を報告してくださった [CERT/CC](https://www.cert.org/) の Will Dorman 氏
-   [Beyond Security の SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html)
-   プログラムに協力して、MS11-078 で説明している問題を報告してくださった匿名の貢献者
-   MS11-079 で説明している問題を報告してくださった [Tenable Network Security](https://www.tenable.com/)
-   MS11-079 で説明している問題を報告してくださった [SEC Consult Unternehmensberatung GmbH](https://www.sec-consult.com/)の Elisabeth Demeter 氏
-   MS11-080 で説明している問題を報告してくださった [National University of Defense Technology](https://www.nudt.edu.cn/) の Bo Zhou 氏
-   MS11-081 で説明している問題を報告してくださった McAfee Labs の Vishwas Sharma 氏
-   MS11-018 で説明している 2 件の問題を報告してくださった [Greplin](https://www.greplin.com) の David Bloom 氏
-   [TippingPoint](https://www.tippingpoint.com)
-   の
-   [Zero Day Initiative](https://www.zerodayinitiative.com)
-   に協力して、MS11-081 で説明している 2 件の問題を報告してくださった Ivan Fratric 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com)
-   に協力して、MS11-081 で説明している問題を報告してくださった
-   [GWSlabs](https://www.gwslabs.com)
-   [TippingPoint](https://www.tippingpoint.com)
-   の
-   [Zero Day Initiative](https://www.zerodayinitiative.com)
-   に協力して、MS11-081 で説明している問題を報告してくださった Sebastian Apelt 氏
-   [TippingPoint](https://www.tippingpoint.com)
-   の
-   [Zero Day Initiative](https://www.zerodayinitiative.com)
-   に協力して、MS11-081 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-081 に組み込まれている多層防御についてマイクロソフトと協力してくださった [Google Inc.](https://www.google.com) の Eduardo Vela Nava 氏および [Greplin](https://www.greplin.com) の David Bloom 氏
-   MS11-081 に組み込まれている多層防御についてマイクロソフトと協力してくださった [Soroush Dalili](https://www.secproject.com) 氏
-   MS11-081 に組み込まれている多層防御についてマイクロソフトと協力してくださった [Google Inc.](https://www.google.com) の Billy Rios 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](https://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](https://support.microsoft.com/)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](https://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   2011/10/12:このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2011/10/27):MS11-078 を更新し、Windows Server 2008 R2 for x64-based System 上の .NET Framework 4 の Server Core インストールの適用オプションを修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
