---
TOCTitle: 'MS12-AUG'
Title: 2012 年 8 月のセキュリティ情報
ms:assetid: 'ms12-aug'
ms:contentKeyID: 61229695
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms12-aug(v=Security.10)'
--- Summary

2012 年 8 月のセキュリティ情報
==============================

公開日: 2012年8月14日 | 最終更新日: 2012年12月12日

**バージョン:** 3.0

このセキュリティ情報の概要は 2012 年 8 月公開のセキュリティ情報の一覧です。

2012 年 8 月のセキュリティ情報の公開により、2012 年 8 月 10 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2012 年 8 月 15 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[8 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032522490&culture=en-us) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2722913) <br />
<br />
この累積的なセキュリティ更新プログラムは非公開で報告された 4 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者が現在のユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257906">MS12-053</a></td>
<td style="border:1px solid black;">リモート デスクトップの脆弱性により、リモートでコードが実行される (2723135) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件のリモート デスクトップ プロトコルの脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるコンピューターに特別な細工を施した一連の RDP パケットを送信した場合、リモートでコードが実行される可能性があります。既定では、リモート デスクトップ プロトコル (RDP) はどの Windows オペレーティング システムでも有効になっていません。RDP が有効となっていないコンピューターは危険にさらされません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">Windows ネットワーク コンポーネントの脆弱性により、 リモートでコードが実行される (2733594) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 4 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性のうちで最も深刻な場合、攻撃者が Windows 印刷スプーラー要求に対して、特別に細工された応答を返信した場合、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに直接接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254386">MS12-060</a></td>
<td style="border:1px solid black;">Windows コモン コントロールの脆弱性により、リモートでコードが実行される (2720573) <br />
<br />
このセキュリティ更新プログラムは Windows コモン コントロールに存在する非公開で報告された 1 件の脆弱性を解決します。この脆弱性により、ユーザーが、この脆弱性を悪用するために特別に細工されたコンテンツが含まれる Web サイトを訪問した場合に、リモートでコードが実行される可能性があります。しかし、すべての場合において、攻撃者がユーザーにそのような Web サイトを強制的に訪問させる方法はありません。その代わり、通常、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせて攻撃者の Web サイトに誘導することにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。悪意のあるファイルが電子メールの添付ファイルとして送信される可能性もありますが、この脆弱性が悪用されるには、ユーザーにその添付ファイルを開かせることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft SQL Server、<br />
Microsoft サーバー ソフトウェア、<br />
マイクロソフト開発者用ツール</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a></td>
<td style="border:1px solid black;">Microsoft Exchange Server WebReady ドキュメント表示の脆弱性により、リモートでコードが実行される (2740358)  <br />
このセキュリティ更新プログラムは一般に公開された Microsoft Exchange Server WebReady ドキュメント表示の脆弱性を解決します。この脆弱性により、ユーザーが特別な細工がされたファイルを Outlook Web App (OWA) を使用してプレビュー表示した場合に、Exchange Server のトランスコーディング サービスのセキュリティ コンテキストでリモートでコードが実行される可能性があります。WebReady ドキュメント表示で使用される Exchange のトランスコーディング サービスは LocalService アカウントで実行されます。LocalService アカウントはローカル コンピューターの最小限の権限しか持たないアカウントで、ネットワーク上では匿名の資格情報を提示します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257907">MS12-055</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (2731847) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a></td>
<td style="border:1px solid black;">JScript および VBScript スクリプト エンジンの脆弱性により、リモートでコードが実行される (2706045) <br />
<br />
このセキュリティ更新プログラムは、Microsoft Windows 64 ビット版の JScript および VBScript スクリプト エンジンに存在する非公開で報告された 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web サイトを訪問すると、リモートでコードが実行される可能性があります。しかし、いかなるケースでも、攻撃者はユーザーに Web サイトを見るよう強制することはできません。そのかわり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257684">MS12-057</a></td>
<td style="border:1px solid black;">Microsoft Office の脆弱性により、リモートでコードが実行される (2731879)  <br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工されたファイルを開くか、特別に細工された Computer Graphics Metafile (CGM) グラフィックス ファイルを Office ファイルに埋め込んだ場合にリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255002">MS12-059</a></td>
<td style="border:1px solid black;">Microsoft Visio の脆弱性により、リモートでコードが実行される (2733918)  <br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性は、特別に細工された Visio ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >脆弱性のタイトル</th>
<th style="border:1px solid black;" >CVE の識別番号</th>
<th style="border:1px solid black;" >最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >サービス拒否の悪用可能性の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">レイアウトのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1526">CVE-2012-1526</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">非同期 NULL オブジェクト アクセスにより、リモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2521">CVE-2012-2521</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">仮想関数テーブルの破損により、リモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2522">CVE-2012-2522</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a></td>
<td style="border:1px solid black;">JavaScript の整数オーバーフローによりリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2523">CVE-2012-2523</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a> でもこの脆弱性を解決します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257906">MS12-053</a></td>
<td style="border:1px solid black;">リモート デスクトップ プロトコルの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2526">CVE-2012-2526</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">リモート管理プロトコルのサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1850">CVE-2012-1850</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">印刷スプーラー サービスのフォーマット文字列の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1851">CVE-2012-1851</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">リモート管理プロトコルのヒープ オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1852">CVE-2012-1852</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257914">MS12-054</a></td>
<td style="border:1px solid black;">リモート管理プロトコルのスタック オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1853">CVE-2012-1853</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257907">MS12-055</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2527">CVE-2012-2527</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=256487">MS12-056</a></td>
<td style="border:1px solid black;">JavaScript の整数オーバーフローによりリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2523">CVE-2012-2523</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255327">MS12-052</a> でもこの脆弱性を解決します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=257684">MS12-057</a></td>
<td style="border:1px solid black;">CGM ファイル形式のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-2524">CVE-2012-2524</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a></td>
<td style="border:1px solid black;">Oracle Outside In の悪用される恐れのある複数の脆弱性</td>
<td style="border:1px solid black;">複数*</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">*複数の脆弱性があります。詳細については、<a href="http://go.microsoft.com/fwlink/?linkid=259630">MS12-058</a> セキュリティ情報を参照してください。<br />
<br />
これらの脆弱性が一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=255002">MS12-059</a></td>
<td style="border:1px solid black;">Visio DXF ファイル形式のバッファー オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1888">CVE-2012-1888</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=254386">MS12-060</a></td>
<td style="border:1px solid black;">MSCOMCTL.OCX の RCE の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1856">CVE-2012-1856</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃を確認しています。</td>
</tr>
</tbody>
</table>

<p></p>

  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1df425a-a67e-42f8-9eb5-a503f684c201)  
(KB2722913)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5afc85e3-a214-4774-93ab-17f9d199ebde)  
(KB2722913)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=213b3590-381e-437c-9391-ff6d7400f250)  
(KB2722913)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ccc3d8fb-2631-42d0-87ed-5d29d4b1f598)  
(KB2723135)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5403c78c-6b87-4788-89c3-0140b887ec6f)  
(KB2705219)  
(緊急)  
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c28e01d6-0030-417d-80dd-b34febd22ec1)  
(KB2712808)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=db21a230-0f6b-4d74-9f32-3718a59efd28)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2fdbe657-1810-4c5d-9ba8-5da148272756)  
(KB2722913)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ce5e8621-5457-4a27-9816-9ce719fd6937)  
(KB2722913)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=01784bbc-20fc-4d0f-bfcd-a5a25dd603e8)  
(KB2722913)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a8eb0583-071d-4d8e-92fb-937035411b49)  
(KB2705219)  
(緊急)  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b9e41497-5c49-45fc-8ad0-c853516609df)  
(KB2712808)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a036c343-5c6e-4484-b7f7-c7161c6880fd)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e1b9a081-0329-4db6-b026-04a332cb0b4d)  
(KB2706045)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[注意](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e5e3e9be-ba36-4fdf-93f6-a30fb087d273)  
(KB2722913)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0bced0f3-9778-4ee3-86fb-7f28b57adbce)  
(KB2722913)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=19393940-2519-4e97-89cd-de993ced31d5)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2847952f-0234-4cf6-820a-1f0a285b2fb7)  
(KB2705219)  
(重要)  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c20f475d-5211-4fdc-8a2f-4408f1baaece)  
(KB2712808)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=50090b08-3f82-4680-b871-2b18fc2386d0)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eb92185b-405a-4d96-b119-13f234a9c4ac)  
(KB2722913)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=26cda257-6607-4bd8-9152-cbcc2a753915)  
(KB2722913)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fe7a78fc-f882-4748-a9e3-04b85d136ca2)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3833d768-1dab-4a85-822f-87c7fa3db261)  
(KB2705219)  
(重要)  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ad883d42-d8bb-482b-bf36-e2007cf73f84)  
(KB2712808)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7f72ba9a-80b2-459d-acad-da6a8b900d6f)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=81f5d8a5-12e5-4227-ae6f-5aea6ffff2a5)  
(KB2706045)  
(注意)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6c5edf14-ecb6-40af-a315-b049457415d6)  
(KB2722913)  
(警告)  
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c890335b-6ceb-427a-9cc7-95ef8c26d306)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2fba3a11-3621-464d-ab22-d902195205f4)  
(KB2705219) (重要)  
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2857701f-3447-452c-a986-9f2fe42fe64d)(KB2712808)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9e647f22-2e80-4f4a-b648-615243741df2)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=862bd543-2fc5-4c4c-8d18-4623ccc68166)  
(KB2722913)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=709a85b7-d192-4bba-990a-ea98fdf6e882)  
(KB2722913)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=430a43fa-78b8-4273-81e1-3081767ddcf9)  
(KB2722913)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cbae6606-3721-48b9-ba3e-9d85df7e08b9)  
(KB2705219)  
(警告)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b4b216dc-533e-4fb4-acc8-ce5eb231320e)  
(KB2712808)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=41362740-876e-4c9e-9729-67dea6830438)  
(KB2731847)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=da933584-40ba-42a0-82fc-b84b41c6c5a4)  
(KB2722913)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ec48d017-d9ed-4b0e-b51f-0f04996088b6)  
(KB2722913)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5341a615-b737-4e48-8dfd-828725d9d513)  
(KB2722913)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e4b4e53b-69d6-4ab6-98bb-3f8871048abe)  
(KB2705219)  
(警告)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dc966826-83e6-4bdc-bc58-8b6eb8917934)  
(KB2712808)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=007b4d50-b770-4e8f-b8d0-060f7bb58ad5)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=294a7eb4-c47f-449f-8931-262bec7d6ecc)  
(KB2706045)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[注意](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=91062e12-401e-472e-a6b6-0eb7216f5264)  
(KB2722913)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=77612ea1-13fb-4c53-bbd2-8796f0d5a9ed)  
(KB2722913)  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f016949d-b931-49f3-867b-f1c64839379e)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=354e502b-3016-4c5e-8611-bc1b35e1a7eb)  
(KB2705219)  
(警告)  
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=35fb03b1-162a-4552-8bb9-6b564acbd57b)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ec759712-2f38-41a9-8b6d-c6908cc58479)  
(KB2731847)  
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
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a610d606-ca70-4dbd-9971-b6915dc4dc59)  
(KB2722913)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=defe6c53-66d7-4ea5-93b1-7487ccf19f24)  
(KB2722913)  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e5ab43bb-dbdb-4b2b-bbf2-260297ee5518)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2b8a730c-46ac-49b7-b9ae-73062d5a79f2)  
(KB2705219)  
(警告)  
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e89024ca-a9e8-4ebf-91eb-cbf8e05398e7)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=caf68d77-3315-4383-a901-ba0385ffe561)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=47b2e47f-30f1-48e8-a857-70df319011ef)  
(KB2706045)  
(注意)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6564a6a1-c8ba-4275-81b5-6664c8e3d010)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cce9a924-a74c-49e0-869f-6b9c1cd12cba)  
(KB2705219)  
(警告)  
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=57153478-4837-438a-8487-929a48fd758a)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dee601c7-4ab4-4556-8d83-90864b09d365)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=625c45f5-5ad1-4ade-8883-33019587ab49)  
(KB2722913)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b2760784-6163-4a8d-86fb-72c88ed2b8ef)  
(KB2722913)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f83f6d97-24f1-4ee0-971d-ab79071fede6)  
(KB2705219)  
(警告)  
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2bcfb574-a7d0-4d7e-b557-41bdcddfde42)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c709aabf-4b3f-4780-8b82-c6c33a211e31)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=625c45f5-5ad1-4ade-8883-33019587ab49)  
(KB2722913)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b2760784-6163-4a8d-86fb-72c88ed2b8ef)  
(KB2722913)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f83f6d97-24f1-4ee0-971d-ab79071fede6)  
(KB2705219)  
(警告)  
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2bcfb574-a7d0-4d7e-b557-41bdcddfde42)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c709aabf-4b3f-4780-8b82-c6c33a211e31)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f5bc6713-2540-4571-ae1f-04f427b33019)  
(KB2722913)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cac3b463-fb9c-474e-9e3d-bb96f7b4c14f)  
(KB2722913)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f49e3f9e-8a96-43e6-8b0a-5c9b78cd819d)  
(KB2705219)  
(警告)  
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=655182f9-110b-4b81-b140-0a5986d7343f)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f62cf24a-8926-4dde-95ac-cc5f62e448be)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ece661be-4ddf-42cc-a62b-15ce53b9d74b)  
(KB2706045)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f5bc6713-2540-4571-ae1f-04f427b33019)  
(KB2722913)  
(緊急)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cac3b463-fb9c-474e-9e3d-bb96f7b4c14f)  
(KB2722913)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f49e3f9e-8a96-43e6-8b0a-5c9b78cd819d)  
(KB2705219)  
(警告)  
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=655182f9-110b-4b81-b140-0a5986d7343f)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f62cf24a-8926-4dde-95ac-cc5f62e448be)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ece661be-4ddf-42cc-a62b-15ce53b9d74b)  
(KB2706045)  
(重要)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[注意](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f6ea664b-575c-4cf0-b479-d1a2653288ee)  
(KB2722913)  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=30a43d95-f489-49c2-a48a-a262fa196bbf)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(警告)  
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbb876e6-a6b9-4193-be5e-d84390d30f1e)  
(KB2706045)  
(注意)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f6ea664b-575c-4cf0-b479-d1a2653288ee)  
(KB2722913)  
(警告)  
[Internet Explorer 9](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=30a43d95-f489-49c2-a48a-a262fa196bbf)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(警告)  
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=bbb876e6-a6b9-4193-be5e-d84390d30f1e)  
(KB2706045)  
(注意)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=05a09f6e-b608-4430-b6d4-bb9d10d8347a)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/ja-jp/download/details.aspx?id=30537)  
(KB2705219)  
(警告)  
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=27b52fb5-ff3c-4dca-9752-1517b873c9cb)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7f17c057-939e-415d-b56a-01082695ab77)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=97004a96-0c83-421d-91a9-d55be32610c9)  
(KB2706045)  
(注意)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=05a09f6e-b608-4430-b6d4-bb9d10d8347a)  
(KB2722913)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/ja-jp/download/details.aspx?id=30537)  
(KB2705219)  
(警告)  
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=27b52fb5-ff3c-4dca-9752-1517b873c9cb)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7f17c057-939e-415d-b56a-01082695ab77)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
[JScript 5.8 および VBScript 5.8](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=97004a96-0c83-421d-91a9-d55be32610c9)  
(KB2706045)  
(注意)
</td>
</tr>
<tr>
<th colspan="6">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-052](http://go.microsoft.com/fwlink/?linkid=255327)
</td>
<td style="border:1px solid black;">
[MS12-053](http://go.microsoft.com/fwlink/?linkid=257906)
</td>
<td style="border:1px solid black;">
[MS12-054](http://go.microsoft.com/fwlink/?linkid=257914)
</td>
<td style="border:1px solid black;">
[MS12-055](http://go.microsoft.com/fwlink/?linkid=257907)
</td>
<td style="border:1px solid black;">
[MS12-056](http://go.microsoft.com/fwlink/?linkid=256487)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=354e502b-3016-4c5e-8611-bc1b35e1a7eb)  
(KB2705219)  
(警告)  
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=35fb03b1-162a-4552-8bb9-6b564acbd57b)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ec759712-2f38-41a9-8b6d-c6908cc58479)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2b8a730c-46ac-49b7-b9ae-73062d5a79f2)  
(KB2705219)  
(警告)  
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e89024ca-a9e8-4ebf-91eb-cbf8e05398e7)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=caf68d77-3315-4383-a901-ba0385ffe561)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(警告)  
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e15d2bae-1511-4d74-93cb-0d614820e175)  
(KB2705219)  
(警告)  
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=20c9a72f-a8b6-4b4c-a9ea-de93069cff3a)  
(KB2712808)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fc5b9df9-c836-407a-a1d4-364c1a885242)  
(KB2731847)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft Office スイートおよびソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-057](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[MS12-059](http://go.microsoft.com/fwlink/?linkid=255002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)  
(Windows コモン コントロール)  
(KB2726929)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)  
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cc2a0eae-5b7e-465b-ab4c-a93ae7c7c458)  
(KB2596615)  
(重要)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c2b0cb0f-db07-452f-a9a4-886124d3943e)  
(KB2596754)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)  
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cc2a0eae-5b7e-465b-ab4c-a93ae7c7c458)  
(KB2596615)  
(重要)  
[Microsoft Office 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c2b0cb0f-db07-452f-a9a4-886124d3943e)  
(KB2596754)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4e08bab7-1408-444d-bad7-a4db76c7f6d3)  
(Windows コモン コントロール)  
(KB2597986)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=953b9b69-2f66-4f71-b342-467cc05030ba)  
(KB2687501)  
(重要)  
[Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a55a33f9-1eb6-469a-967c-a483764772c3)  
(KB2687510)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=de95d8b9-51a5-43cd-8ba3-8cbb1320d099)  
(KB2687508)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=90b99372-4f13-4f3a-ae52-da6543745248)  
(KB2687501)  
(重要)  
[Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=da8a4d12-d4fc-4b6e-b65f-096dedddf529)  
(KB2687510)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Visio 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=af690cd8-cb2c-4743-96f0-ffaec77adf10)  
(KB2687508)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office Web コンポーネント
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-057](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[MS12-059](http://go.microsoft.com/fwlink/?linkid=255002)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Web コンポーネント Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Web コンポーネント Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)  
(Windows コモン コントロール)  
(KB2726929)  
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
<th colspan="4">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-057](http://go.microsoft.com/fwlink/?linkid=257684)
</td>
<td style="border:1px solid black;">
[MS12-059](http://go.microsoft.com/fwlink/?linkid=255002)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=62e87f7b-f48e-43a7-86d7-cbb8f0603ea3)  
(KB2598287)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visio Viewer 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3889e1b3-69b2-4a8f-a0d9-de8c7dc6f5ec)  
(KB2598287)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS12-060 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft サーバー ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-058](http://go.microsoft.com/fwlink/?linkid=259630)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[Microsoft SQL Server 2000 Service Pack 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=22be7d30-86f8-4a3b-ba46-b08624581c61)  
(KB983812)  
(緊急)  
QFE 用の更新プログラム:  
[Microsoft SQL Server 2000 Service Pack 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=09ebb11b-2b82-4891-8ae9-03481c0d7b29)  
(KB983811)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Analysis Services Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Analysis Services Service Pack 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3f5f7d2c-1fd1-437d-a74c-f316c2cd7818)  
(KB983813)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 for 32-bit Systems Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 for 32-bit Systems Service Pack 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Windows コモン コントロール)  
(KB2726929)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 for x64-based Systems Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 for x64-based Systems Service Pack 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Windows コモン コントロール)  
(KB2726929)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2005 for Itanium-based Systems Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 for Itanium-based Systems Service Pack 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Windows コモン コントロール)  
(KB2726929)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2005 Express Edition with Advanced Services Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2005 Express Edition with Advanced Services Service Pack 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fd9626f7-4265-48ae-94b2-68243605db6b)<sup>[1]</sup>
(Windows コモン コントロール)  
(KB2726929)(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for 32-bit Systems Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 for 32-bit Systems Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for x64-based Systems Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 for x64-based Systems Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 for Itanium-based Systems Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for 32-bit Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for x64-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2008 R2 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b1c185e9-5328-4bf7-b175-fd9d7fc64097)<sup>[2]</sup>
(Windows コモン コントロール)  
(KB2687441)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Commerce Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-058](http://go.microsoft.com/fwlink/?linkid=259630)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2002 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2002 Service Pack 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9ad19d40-16ed-47ad-b907-8a48bb64c6d3)  
(KB2716389)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2007 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7d972437-f71a-4576-b5c1-a940c0824438)  
(KB2716390)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Commerce Server 2009
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3879fecd-8360-4c01-b88e-d56e8570cafb)  
(KB2716392)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Commerce Server 2009 R2
</td>
<td style="border:1px solid black;">
[Microsoft Commerce Server 2009 R2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ce4f9470-e2b2-417e-9015-30355e837fbb)  
(KB2716393)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Host Integration Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Host Integration Server 2004 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Host Integration Server 2004 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3dde4ef1-d41f-45b0-8660-a546cbe3fc81)  
(KB2711207)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
<td style="border:1px solid black;">
[MS12-058](http://go.microsoft.com/fwlink/?linkid=259630)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=21a26e23-9d83-41b6-95be-4b48f6e76023)  
(KB2756497)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8646aaca-9829-4d3f-a77b-d24673818da7)  
(KB2756496)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2010 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4b24182a-cee9-4ca0-9cc5-c4453475999d)  
(KB2756485)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
MS12-060 に関する注意

<sup>[1]</sup> この更新プログラムは、Microsoft Office 2003 用の更新プログラム KB2726929 と同じです。

<sup>[2]</sup> この更新プログラムは、Microsoft Office 2007 用の更新プログラム KB2687441 と同じです。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual FoxPro
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro 8.0 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0bef712a-b9e0-4ea9-98bf-68db366c8b8b)  
(KB2708940)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual FoxPro 9.0 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 9.0 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1ee09491-4871-41ca-a39c-8360d5a568d4)  
(KB2708941)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Visual Basic
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-060](http://go.microsoft.com/fwlink/?linkid=254386)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Basic 6.0 ランタイム
</td>
<td style="border:1px solid black;">
[Visual Basic 6.0 ランタイム](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=847ec64b-95be-463b-bdfb-969e91fe3207)  
(KB2708437)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
MS12-060 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://go.microsoft.com/fwlink/?linkid=69903)を参照してください。[セキュリティ TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://go.microsoft.com/fwlink/?linkid=85102)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747/ja) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

System Center Configuration Manager

System Center Configuration Manager のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。System Center Configuration Manager で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

System Center Configuration Manager の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。System Center Configuration Manager のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が System Center Configuration Manager を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](http://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。System Center Configuration Manager の詳細については、[System Center Configuration Manager](http://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager については、前のセクション「System Center Configuration Manager」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d%20-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet.microsoft.com/ja-jp/library/cc749197) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199/ja) :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

-   [VeriSign iDefense Labs](http://labs.idefense.com/) に協力して、MS12-052 で説明している問題を報告してくださった GWSlabs
-   [Beyond Security の SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) プログラムに協力して、MS12-052 で説明している問題を報告してくださった Derek Soeder 氏
-   MS12-052 で説明している問題を報告してくださった [Trend Micro](http://www.trendmicro.com/) の Sung-ting Tsai 氏および Ming-Chieh Pan 氏
-   MS12-052 で説明している問題を報告してくださった [Google's Chrome Security Team](http://chrome.google.com/) の Cris Neckar 氏
-   MS12-053 で説明している問題を報告してくださった NCC Group の Edward Torkington 氏
-   MS12-054 で説明している 4 件の問題を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS12-055 で説明している問題を報告してくださった [Google Inc.](http://www.google.com/) の [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 氏
-   MS12-056 で説明している問題を報告してくださった [Google Chrome Security Team](http://chrome.google.com/) の Cris Neckar 氏
-   MS12-057 で説明している問題を報告してくださった [Andrei Costin](http://www.andreicostin.com) 氏
-   MS12-058 で説明している 13 件の問題を報告してくださった [CERT/CC](http://www.cert.org/) の Will Dorman 氏
-   MS12-059 で説明している問題を報告してくださった [TippingPoint](http://www.hpenterprisesecurity.com/products/hp-tippingpoint-network-security/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している Alexander Gavrun 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617.aspx)
-   Windows を実行しているコンピューターのウィルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2012/08/15):このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2012/10/10):MS12-053、MS12-054、MS12-055、および MS12-058 の更新プログラム パッケージの再リリースに合わせてセキュリティ情報の概要ページを更新しました。お客様は、マイクロソフト セキュリティ アドバイザリ 2749655 で説明したデジタル証明書の問題を回避するために再リリースされた更新プログラム パッケージを適用する必要があります。詳細については、セキュリティ情報を参照してください。
-   V3.0 (2012/12/12):MS12-057 では、影響を受けるすべてのエディションの Microsoft Office 2010 用の KB2553260 および KB2589322 更新プログラムは、それぞれ KB2687501 および KB2687510 更新プログラムに置き換えられました。MS12-059 では、影響を受けるすべてのエディションの Microsoft Visio 2010 用の KB2597171 更新プログラムは KB2687508 更新プログラムに置き換えられました。MS12-060 では、影響を受けるすべてのバリエーションの Microsoft Office 2003、Microsoft Office 2003 Web Components、および Microsoft SQL Server 2005 上の Windows コモン コントロール用の KB2687323 更新プログラムは KB2726929 更新プログラムに置き換えられました。

*Built at 2014-04-18T01:50:00Z-07:00*
