---
TOCTitle: 'MS11-SEP'
Title: 2011 年 9 月のセキュリティ情報
ms:assetid: 'ms11-sep'
ms:contentKeyID: 61229693
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-sep(v=Security.10)'
--- 

2011 年 9 月のセキュリティ情報
==============================

公開日: 2011年9月14日 | 最終更新日: 2011年9月28日

**バージョン:** 1.1

[![](../../images/Dn627272.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627272.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2011 年 9 月公開のセキュリティ情報の一覧です。
2011 年 9 月のセキュリティ情報の公開により、2011 年 9 月 9 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。
マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 9 月 14 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。
マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2011 年 9 月 14 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[9 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487951) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Bulletin Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;">WINS の脆弱性により、特権が昇格される (2571621) <br />
<br />
このセキュリティ更新プログラムは 1 件の非公開で報告された Windows インターネット ネーム サービス (WINS) の脆弱性を解決します。この脆弱性は、WINS サービスを実行している影響を受けるコンピューターで、特別に細工された WINS のレプリケーション パケットをユーザーが受信した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;">Windows コンポーネントの脆弱性により、リモートでコードが実行される (2570947) <br />
<br />
このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。正当なリッチ テキスト形式ファイル (.rtf)、テキスト ファイル (.txt)、または Word 文書 (.doc) をユーザーが開いたとしても、同じネットワーク ディレクトリに特別な細工が施されたダイナミック リンク ライブラリ (DLL) ファイルが存在していた場合、この脆弱性により、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Microsoft Excel の脆弱性により、リモートでコードが実行される (2587505) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 5 件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性は、特別に細工された Excel ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。Office のファイル検証 (OFV) をインストールおよび構成して、疑わしいファイルの表示を防ぐことにより、CVE-2011-1986 および CVE-2011-1987 で説明している脆弱性を悪用するための攻撃手法をブロックします。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Microsoft Office の脆弱性により、リモートでコードが実行される (2587634) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Office に存在する脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされた Office ファイルを開いた場合、または特別な細工がされたライブラリ ファイルと同じネットワーク ディレクトリにある正当な Office ファイルを開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Microsoft SharePoint の脆弱性により、特権が昇格される (2451858) <br />
<br />
このセキュリティ更新プログラムは Microsoft SharePoint および Windows SharePoint サービスに存在する 5 件の非公開で報告された脆弱性および 1 件の公開された脆弱性を解決します。最も深刻な脆弱性により、ユーザーが特別に細工された URL をクリックするか、特別に細工された Web サイトを訪問した場合、特権が昇格される可能性があります。最も深刻な脆弱性について、インターネット ゾーン内の SharePoint サイトをブラウズしている Internet Explorer 8 および Internet Explorer 9 ユーザーはこの危険にさらされる可能性が低くなっています。その理由は、Internet Explorer 8 および Internet Explorer 9 の XSS フィルターにより、既定でインターネット ゾーン内の攻撃が阻止されるからです。ただし、Internet Explorer 8 および Internet Explorer 9 の XSS フィルターは既定では、イントラネット ゾーンで有効になっていません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Server Software</td>
</tr>
</tbody>
</table>

<p></p>

 

Exploitability Index (悪用可能性指標)
-------------------------------------

 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。

この表はどのように使用しますか?

この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/security/cc998259.aspx) を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;">WINS のローカルの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1984">CVE-2011-1984</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;">Windows コンポーネントの安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1991">CVE-2011-1991</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel の解放後使用の WriteAV の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1986">CVE-2011-1986</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel の境界外の配列のインデックスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1987">CVE-2011-1987</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel のヒープ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1988">CVE-2011-1988</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel の条件式解析の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1989">CVE-2011-1989</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Excel の境界外の配列のインデックスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1990">CVE-2011-1990</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Office コンポーネントの安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1980">CVE-2011-1980</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Office 未初期化オブジェクト ポインターの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1982">CVE-2011-1982</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint カレンダーの XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0653">CVE-2011-0653</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">HTML のサニタイズの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。<br />
<br />
この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Editform のスクリプト挿入の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1890">CVE-2011-1890</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">連絡先情報を反映した XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1891">CVE-2011-1891</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint リモート ファイル公開の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1892">CVE-2011-1892</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1893">CVE-2011-1893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
</tbody>
</table>

<p></p>

  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-070](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[MS11-071](http://go.microsoft.com/fwlink/?linkid=223632)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=70f944b0-9bf0-4168-b150-67d2ff68df2d)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4b9debed-edbb-43e1-b755-0faf01980289)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-070](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[MS11-071](http://go.microsoft.com/fwlink/?linkid=223632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1e6ac3b2-752e-49a0-84e5-5a8dfe955299)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d44274d2-0401-4fd8-bc4f-c59f6d81c34f)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f9378339-c58e-4e84-9427-85aeb35b0d99)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=935720ee-cee0-42c2-965e-ce1b07e95e1a)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c35c71a8-13b4-47a6-9763-06f6f65327b1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=78c2ac72-da89-42a4-bff9-79551b5d3c4e)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-070](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[MS11-071](http://go.microsoft.com/fwlink/?linkid=223632)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
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
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=15840336-4886-4a1b-8c1e-2c535c3938f7)  
(重要)
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
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e80739b4-89bb-4317-8381-991244a71cb8)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-070](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[MS11-071](http://go.microsoft.com/fwlink/?linkid=223632)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
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
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a9039660-3cc2-470d-a0a5-a70f78074495)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=05c39ab3-7b57-4147-8913-df5df6005799)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5ea78a9b-b1f7-4e94-b69e-c984e1622ae9)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1499d988-fd55-4317-b859-ec170907d547)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6e2d2ea9-0af6-4d23-875d-3211722cd62f)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-070](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[MS11-071](http://go.microsoft.com/fwlink/?linkid=223632)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=76b99ab2-7e99-4aad-a419-7996bae05c48)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0f6d32de-d3ff-4af9-9b26-a4f12581f5fe)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-070](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[MS11-071](http://go.microsoft.com/fwlink/?linkid=223632)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
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
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f58cf343-946c-4e74-bd9c-40ac934a4986)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a8a451bd-3e5c-4845-9941-daabd9418776)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0fdfb1f9-20b3-4d61-8019-33d1003290c8)  
(重要)
</td>
</tr>
</table>

<p></p>

 
Microsoft Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-073](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dee4f3d7-bc4b-47fd-8e3f-9d2b0e82d0f6)  
(KB2553072)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7faa2f90-2e64-4dbf-ac93-bb8cffc9b5fe)  
(KB2584052)  
(重要)
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
[Microsoft Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=498ac241-d728-4944-abac-ec8444ca6418)  
(KB2553073)<sup>[1]</sup>
(重要)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=df04b9ce-2daa-4b4d-a944-a873075656f9)  
(KB2553089)<sup>[1]</sup>
(重要)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=90eef02b-db1f-4fdd-bb1d-408063671e4d)  
(KB2553090)<sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=34bbee95-0e83-4705-8bfe-02e4fb22f8e7)  
(KB2584063)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 および Microsoft Excel 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4612c6e4-ac29-4cc4-9da5-88779ea3643e)  
(KB2553070)  
(重要)  
[Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1fd15144-5547-4927-8583-8d9b06819226)  
(KB2553091)  
(重要)  
[Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=18840d78-944f-400a-addc-dce7e570a569)  
(KB2553096)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3c8fd04a-9df6-4726-a9bc-811f49665981)  
(KB2584066)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 および Microsoft Excel 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d40db27b-1318-4ca7-b44f-c90bb6342109)  
(KB2553070)  
(重要)  
[Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f83800aa-6403-4341-afea-d363e54d5831)  
(KB2553091)  
(重要)  
[Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=92787e00-6f30-4020-9c1a-70270be5a623)  
(KB2553096)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 および Microsoft Office 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=85360dc1-99e7-4e3e-be6f-3795e8a8122f)  
(KB2584066)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-073](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=868f4d9f-3498-4d59-a017-59204553889c)  
(KB2598782)  
(重要)
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
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=afa79cfc-6e8a-4d0b-88aa-0d7e05031e44)  
(KB2598781)  
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
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=535fcf4a-eeb2-44eb-b2a6-9c512509c49d)  
(KB2598783)  
(重要)
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
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9796588d-238f-4694-9598-1aa8d2becb55)  
(KB2598785)  
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
<th colspan="4">
Microsoft Office Groove および Microsoft SharePoint Workspace
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-073](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
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
Microsoft Office Groove 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5ea6192b-55e5-4ca4-8d91-cc768ede8277)  
(KB2552997)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Workspace 2010 および Microsoft SharePoint Workspace 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Workspace 2010 および Microsoft SharePoint Workspace 2010 Service Pack 1 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f6ee7e43-9da9-4b96-abd0-390cfcacb885)  
(KB2566445)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Workspace 2010 および Microsoft SharePoint Workspace 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Workspace 2010 および Microsoft SharePoint Workspace 2010 Service Pack 1 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=234efac1-4f09-41f5-90a9-4a3c2e81c05e)  
(KB2566445)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-073](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f82ca5da-a55a-487c-8170-46a40000c8e3)  
(KB2553075)  
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
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=01093f22-06b7-4c9b-bff9-f54ac5d73bf8)  
(KB2553074)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
MS11-072 に関する注意

<sup>[1]</sup> Microsoft Office Excel 2007 Service Pack 2 の場合は、セキュリティ更新プログラム パッケージ KB2553073、KB2553089 および KB2553090 に加えて、このセキュリティ情報で説明している脆弱性から保護するために Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2 (KB2553074) もインストールする必要があります。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS11-074 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft サーバー ソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
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
Microsoft Office SharePoint Server 2007 Service Pack 2 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dd532201-485c-4270-88d3-63bd3f24327e)  
(KB2553093)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=ad52c341-13ce-4b53-87b4-269cb3f41275)  
(KB2508964)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=fd6189c9-ab3b-441f-a901-6ac7f3b202aa)  
(KB2553001)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d9601fae-4a80-45cd-a49b-ef441856d7e4)  
(KB2553002)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=55b60e2f-ec68-4ccb-803a-5d03add8a1f1)  
(KB2553003)<sup>[1]</sup>
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (64 エディション)
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1086a5b0-e441-4e26-a8d1-924a20121dde)  
(KB2553093)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=8cbb365a-6568-4e63-8b81-bbddb36c559e)  
(KB2508964)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b1466366-e2ae-498e-b964-135e034e7348)  
(KB2553001)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bb788c8d-8383-4e53-ac05-2a7dd9b83e70)  
(KB2553002)<sup>[1]</sup>
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e8e1a5bb-a552-45fe-8e81-e05fbfbb57ee)<sup>[1]</sup>
(重要)  
(KB2553003)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0c150328-6a15-4852-a09c-4063142bd946)  
(KB2553094)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1 (osrchwfe)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c17eb04d-cbbc-457e-a424-4ee26b7a9654)  
(KB2494022)  
(重要)  
[Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1 (osrv)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2a80a849-b712-47d4-9def-9395ee54a265)  
(KB2560885)  
(重要)
  
[Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe)](http://www.microsoft.com/downloads/ja-jp/details.aspx?displaylang=ja&familyid=b84c2bcb-0327-4916-871e-7a5c19b8c41b)(KB2560890) (重要)  
[Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmawfe)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1597f295-02a9-4479-9d52-f18f0e83eaba)  
(KB2566456)  
(重要)  
[Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1 (dlc)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e6b666a4-a795-441c-9bda-23e2de2e7b05)  
(KB2566954)  
(重要)  
[Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmamui)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=57592ce4-5d99-45c2-830f-380d67af8899)  
(KB2566958)  
(重要)  
[Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1 (wosrv)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=dd64a635-1e55-4b4d-9718-9b94c31c5625)  
(KB2566960)  
(重要)

</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Forms Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Forms Server 2007 Service Pack 2 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Forms Server 2007 Service Pack 2 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c4c8ad7e-50bd-460e-9678-d8c72c6ee7ab)  
(KB2553005)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Forms Server 2007 Service Pack 2 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Forms Server 2007 Service Pack 2 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7390b526-f411-45a4-8587-8077b473ac17)  
(KB2553005)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Data Bridge Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove Data Bridge Server 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5958247e-204e-409c-bdc1-7aff06e854b8)  
(KB2552999)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove Management Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove Management Server 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6b5b4caf-6a95-487d-ac17-c4435225af3a)  
(KB2552998)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010 および Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 および Microsoft Groove Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=71c0f217-5112-4dca-b9aa-46c69f6099e4)  
(KB2508965)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
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
Microsoft Office Web Apps 2010 および Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Excel Web App 2010 および Microsoft Excel Web App 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=73d49094-a9cf-407e-8921-1b22fbc30427)  
(KB2553095)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 および Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=288a7394-b8d5-4445-bd4c-65bbf4b10eaf)  
(KB2566449)  
(重要)  
[Microsoft Word Web App 2010 および Microsoft Word Web App 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=152ff9f4-d720-41af-8f89-793133ece037)  
(KB2566450)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Windows SharePoint Services および Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 識別名
</td>
<td style="border:1px solid black;">
[MS11-072](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[MS11-074](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 2.0
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 2.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=71e32745-cb05-4b87-a447-741ccdac7450)  
(KB2494007)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0f306cbd-a652-4e77-b394-1a6dc38ba83c)  
(KB2493987)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3137e4c6-783d-4461-88bd-90da064e3105)  
(KB2493987)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 および Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 および Microsoft SharePoint Foundation 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0db799e2-896f-464b-8cd5-ecf2014f0588)  
(KB2494001)  
(重要)
</td>
</tr>
</table>

<p></p>

 
MS11-072 に関する注意

<sup>[2]</sup>この更新プログラムは、既定の構成の Microsoft Office SharePoint Server 2007 Enterprise、Microsoft Office SharePoint Server 2007 for Internet Sites などの Excel Services がインストールされているサーバーに適用されます。Microsoft Office SharePoint Server 2007 Standard は Excel Services を含みません。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS11-074 に関する注意

<sup>[1]</sup> サポートされているエディションの Microsoft Office SharePoint Server 2007 について、お客様はこのセキュリティ情報で説明している脆弱性に対する保護を行うために、Microsoft Office SharePoint 2007 用のセキュリティ更新プログラム パッケージ (KB2508964、KB2553001、KB2553002、および KB2553003) とともに、Microsoft Windows SharePoint Services 3.0 のセキュリティ更新プログラム (KB2493987) もインストールする必要があります。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

検出および適用ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://go.microsoft.com/fwlink/?linkid=69903)を参照してください。[セキュリティ TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://go.microsoft.com/fwlink/?linkid=85102)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および適用のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および適用に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および適用のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[マイクロソフト サポート技術情報 961747](http://support.microsoft.com/kb/961747) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134)を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/wsus/default.aspx) の Web サイトを参照してください。

System Center Configuration Manager 2007

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx)を参照してください。Configuration Manager の詳細については、[System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx) を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199) :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](http://support.microsoft.com/kb/913086) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

-   MS11-070 で説明している問題を報告してくださった [Core Security Technologies](http://www.coresecurity.com/) の Nicolas Economou 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、MS11-072 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-072 で説明している問題を報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Sean Larsson 氏
-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して、MS11-072 で説明している問題を報告してくださった匿名のリサーチャー
-   [TippingPoint](http://www.tippingpoint.com/)  の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-072 で説明している問題を報告してくださった匿名のリサーチャー
-   [TippingPoint](http://www.tippingpoint.com/)  の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力して、MS11-072 で説明している問題を報告してくださった Omair 氏
-   [Secunia Research](http://secunia.com/) と協力して、MS11-073 で説明している問題を報告してくださった Parvez Anwar 氏
-   MS11-073 で説明している問題を報告してくださった [CERT/CC](http://www.cert.org/) の David Warren 氏
-   MS11-074 で説明している問題を報告してくださった [Critical Path Training, LLC](http://www.criticalpathtraining.com/) の Andrew Connell 氏
-   MS11-074 で説明している問題を報告してくださった [Raytheon](http://www.raytheon.com/) の David Feldman 氏
-   MS11-074 で説明している問題を報告してくださった [IBM Rational Application Security](http://blog.watchfire.com/) の Adi Cohen 氏
-   MS11-074 で説明している問題についてマイクロソフトに協力してくださった [Trend Micro](http://www.trendmicro.com/)
-   MS11-074 で説明している問題を報告してくださった [ITT](http://www.itt.com/) の Pedro Jimenez 氏
-   MS11-074 で説明している問題を報告してくださった [Seeker (自動アプリケーション セキュリティ テスト ソリューション)](http://www.seekersec.com/)
-   MS11-074 で説明している問題を報告してくださった [Agarri](http://www.agarri.fr/) の Nicolas Grégoire 氏
-   MS11-074 で説明している問題を報告してくださった [LaValley Consulting, LLC](http://www.lavalley.net) の Jim LaValley 氏
-   MS11-074 で多層防御の更新についてマイクロソフトと協力してくださった [Seeker](http://www.seekersec.com) の Irene Abezgauz 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](http://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社 またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行ないません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません (Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます)。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2011/09/14): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2011/09/28): MS11-074 を更新し、Microsoft Office SharePoint Server 2010 および Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe) 用の 更新プログラム (KB2560890) の更新リンクを追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
