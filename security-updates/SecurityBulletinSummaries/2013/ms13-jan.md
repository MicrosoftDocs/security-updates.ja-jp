---
TOCTitle: 'MS13-JAN'
Title: 2013 年 1 月のセキュリティ情報
ms:assetid: 'ms13-jan'
ms:contentKeyID: 61229710
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms13-jan(v=Security.10)'
---


2013 年 1 月のセキュリティ情報
==============================

公開日: 2013年1月9日 | 最終更新日: 2013年3月13日

**バージョン:** 4.0

[![](../../images/Dn627290.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627290.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2013 年 1 月公開のセキュリティ情報の一覧です。

2013 年 1 月のセキュリティ情報の公開により、2013 年 1 月 4 日に公開した事前通知と 2013 年 1 月 14 日に公開した定例外の事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2013 年 1 月 9 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[1 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=en-us) (英語)。この日付以降、この Webcast は[オンデマンド](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538623&culture=en-us)で利用可能となります。

マイクロソフトはこの定例外のセキュリティ情報に関するお客様からの質問にお答えするため、2013 年 1 月 14 日午後 1：00 (太平洋標準時刻、米国およびカナダ) に Webcast を配信予定です。[2013 年 1 月 14 日の定例外セキュリティ情報の Webcast に今すぐご登録ください (英語)。](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=en-us)この日付以降、この Webcast は[オンデマンド](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032541648&culture=en-us)で利用可能となります。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

#### 概要

次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェアおよびダウンロード先」を参照してください。

 
<p> </p>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;">Internet Explorer 用のセキュリティ更新プログラム (2799329)  <br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する 1 件の一般に公開されている脆弱性を解決します。この脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、 <br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;">Windows 印刷スプーラー コンポーネントの脆弱性により、リモートでコードが実行される (2769369)  <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、プリント サーバーが特別な細工がされた印刷ジョブを受信すると、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに直接接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">XML Core Services の脆弱性により、リモートでコードが実行される (2756145) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft XML コア サービスに存在する 2 件の脆弱性を解決します。これらの脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。攻撃者は、該当の Web サイトにユーザーを強制的に訪問させることはできません。その代わり、通常、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせて攻撃者の Web サイトに誘導することにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、 <br />
Microsoft Office、 <br />
Microsoft 開発者用ツール、  <br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">System Center Operations Manager の脆弱性により、特権が昇格される (2748552)  <br />
<br />
この更新プログラムは、非公開で報告された Microsoft System Center Operations Manager に存在する 2 件の脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された URL を使用して影響を受ける Web サイトを訪問した場合、特権が昇格される可能性があります。攻撃者は、該当の Web サイトにユーザーを強制的に訪問させることはできません。そのかわり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせることにより、影響を受ける Web サイトにユーザーを訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">.NET Framework の脆弱性により、特権が昇格される (2769324)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された .NET Framework に存在する 4件の脆弱性を解決します。これらのうちで最も深刻な脆弱性では、ユーザーが XAML ブラウザー アプリケーション (XBAP) を実行する Web ブラウザーを使用して、特別に細工された Web ページを表示した場合、特権が昇格される可能性があります。これらの脆弱性は、コード アクセス セキュリティ (CAS) の制限を回避する目的で Windows .NET アプリケーションで悪用される可能性もあります。これらの脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (2778930)  <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工されたアプリケーションを実行した場合、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;">Microsoft Windows の脆弱性により、セキュリティ機能のバイパスが起こる (2785220)  <br />
<br />
このセキュリティ更新プログラムは、Microsoft Windows の SSL および TLS の実装に存在する非公開で報告された 1 件の脆弱性を解決します。この脆弱性により、攻撃者が暗号化された Web トラフィックのハンドシェイクを傍受した場合、セキュリティ機能のバイパスが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;">Open Data プロトコルの脆弱性により、サービス拒否が起こる (2769327)  <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Open Data (OData) プロトコルの脆弱性を解決します。この脆弱性により、認証されていない攻撃者が、特別に細工された HTTP 要求を影響を受けるサイトに送ることで、サービス拒否を引き起こします。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
 

Exploitability Index (悪用可能性指標)
-------------------------------------

<span></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。

この表はどのように使用しますか?

この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。

下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<p> </p>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273848">MS13-001</a></td>
<td style="border:1px solid black;">Windows 印刷スプーラー コンポーネントの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0011">CVE-2013-0011</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">MSXML 整数の切り捨ての脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0006">CVE-2013-0006</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=264923">MS13-002</a></td>
<td style="border:1px solid black;">MSXML XSLT の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0007">CVE-2013-0007</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">System Center Operations Manager Web コンソールの XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0009">CVE-2013-0009</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=261863">MS13-003</a></td>
<td style="border:1px solid black;">System Center Operations Manager Web コンソールの XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0010">CVE-2013-0010</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">WinForms のバッファ オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0002">CVE-2013-0002</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">S.DS のバッファ オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0003">CVE-2013-0003</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268279">MS13-004</a></td>
<td style="border:1px solid black;">ダブル コンストラクションの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0004">CVE-2013-0004</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273826">MS13-005</a></td>
<td style="border:1px solid black;">Win32k の不適切なメッセージ処理の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0008">CVE-2013-0008</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=273872">MS13-006</a></td>
<td style="border:1px solid black;">Microsoft SSL Version 3 および TLS プロトコルのセキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0013">CVE-2013-0013</a></td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=268284">MS13-007</a></td>
<td style="border:1px solid black;">置換サービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0005">CVE-2013-0005</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=275222">MS13-008</a></td>
<td style="border:1px solid black;">Internet Explorer の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-4792">CVE-2012-4792</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。<br />
<br />
マイクロソフトは、Internet Explorer 8 によりこの脆弱性を悪用しようとする標的型攻撃を確認しています。</td>
</tr>
</tbody>
</table>
 

影響を受けるソフトウェアおよびダウンロード先
--------------------------------------------

<span></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

これらの表はどのように使用しますか?

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。

注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。

#### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="8">
Windows XP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=20d8d873-a709-4834-a956-f3d9d82dbb73)   
(KB2799329)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dcdcf814-e39d-4515-bc5d-12e11f214d08)  
(KB2799329)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4e0d584a-c684-408c-bc47-6bd4ecaa9b8a)  
(KB2799329)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=137cc5ee-abf0-4a10-b1c4-d464331cbcfd)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.0 Service Pack 3:](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=155a2984-2cd9-40a4-abaa-c1ea21e76062)  
(KB2742607)  
(Media Center Edition 2005 Service Pack 3 および Tablet PC Edition 2005 Service Pack 3 のみ)  
(重要)  
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f35f2ea5-d60e-405a-9ed3-248e0d733c2b)   
(KB2799329)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=36c9d6a9-d939-4e19-b9f5-576fee048764)  
(KB2799329)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=396f26bd-8c8b-459d-9467-6ec17a11c9d4)  
(KB2799329)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d147f865-6a56-4db2-8d78-14f2bee6da18)  
(KB2757638)  
(緊急)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1a7cfc5a-2872-4516-a371-f42d4d3969a6)   
(KB2799329)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4b7c2bcd-a732-46ba-9d09-cc192efd4755)  
(KB2799329)  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7f134d1c-670d-4528-b755-22124aa4d8c9)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6a12de5f-de80-48e4-8276-6c420f5a2948)  
(KB2758696)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f1a2eb6e-0290-4a53-b93c-017a48b19973)  
(KB2742604)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=00304f3b-069f-49dc-a416-b0b5fb97aa4b)   
(KB2799329)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4911899c-863f-4499-9477-340ef8daad29)  
(KB2799329)  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b0cf6516-aea6-4879-9a6e-171d4825ae20)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=29985fdc-8aba-44b2-9420-970ca475052e)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=0b13a83c-1e51-4604-a09d-afb2e25646f9)  
(KB2758696)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=20d07bcd-95cc-44a2-8e3e-f88b22682e21)  
(KB2756918)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b2c635b7-56ad-426b-8bd6-4aee9deadb69)   
(KB2799329)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b33197ab-f489-4c11-a229-044b186d7dda)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=bca95077-a28f-406c-9fe4-51dbcf6adee8)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fb834cf7-d1fe-4291-8a0d-c866fdbdf0e6)  
(KB2758696)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8e2cc005-08c5-4e47-b05a-5b36fe539610)  
(KB2742596)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=95d603e8-9440-4aa6-9765-20c77a55966a)  
(KB2799329)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=64b498a6-54fc-4b88-bcc3-2cc15a16abb5)  
(KB2799329)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d477235d-60f4-420d-8161-82194b4e62e7)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8b1aef73-cfb2-4998-bca6-35cccfbb2078)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3107fadf-5ba8-48f6-bb23-0c0003b4ba76)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a35ccbff-c476-4ee2-be9c-5b6a4b1664e9)  
(KB2799329)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b427bace-5297-4593-9dd2-66847ae506c6)  
(KB2799329)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3)  
(KB2757638)  
(緊急)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=873eba5d-5a8f-410e-bad8-e9d538acf1b3)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4287381f-6f23-4a36-a7dc-f79c44bac124)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=098958e5-83cd-4ed2-b758-e970cef33325)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3ce450f1-f71f-4d5d-bf1c-db4742522d18)  
(KB2799329)  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2d1266fc-f6b0-4062-9799-7b3721c2cf52)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=0f87dd60-92c2-444c-a9ea-dfeb106c88fa)  
(KB2799329)  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2f71f8e6-309c-4bea-abde-d91040c46611)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e47425e9-f53e-4e20-a7ec-b4c552bd66eb)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c11ec9cd-1a85-4514-a1b9-9da5cdd0926b)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5091f66f-9b89-496f-95ce-9ac556faa7b5)  
(KB2742597)  
(重要)  
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=39406634-48ad-4ecf-a6be-f5a47885704b)  
(KB2742601)  
(重要)  
[Microsoft .NET Framework 3.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8cb7a04-f913-47cc-96c1-27fb7154a791)  
(KB2756919)  
(深刻度なし<sup>[2]</sup>)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d949fde9-31e7-4553-a34c-b41625a8cdc8)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ab117984-c4cb-473b-8c20-2b0d0409d8d6)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b476d44d-8a79-4857-8c3e-9d547e9b9e2d)  
(KB2736416)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285)  
(KB2799329)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d20f50ed-89c3-48cb-a78d-a44470fa1285)  
(KB2799329)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=abbc3f31-e940-4750-acb6-5af477bc8390)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3a160fc4-1bf0-4db2-aa8d-6ba4f07d196b)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=057726d1-cdb4-4488-8cd8-822dabfc62a6)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6120322b-7e04-4eeb-a9a4-11fe563a9f27)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154)  
(KB2799329)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(緊急)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c113b67f-42ca-4fea-ba45-aba6f94de154)  
(KB2799329)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1868c2ca-a184-494e-8eb3-82db45b08e32)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(緊急)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4b442601-2808-4192-aa7d-b6476668cd23)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=64249562-1fc3-436d-a9e1-4c9378b632d7)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c9e2a55e-170f-4fe1-a306-eda676fd0fdb)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d2fffc43-a88f-4fe5-9b24-5677258011b8)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0)  
(KB2742613)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a)  
(KB2742598)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127)  
(KB2756920)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4)  
(KB2736418)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fbcee22b-9801-4c9e-ba0c-eb4a54526d38)  
(KB2799329)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=18070321-8635-4c2e-b9f9-0fc58c924136)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4719776a-5ff0-491a-934e-99220d8ac3a3)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e4dfbf88-0e7f-43ca-affe-5d8ddea8657e)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0)  
(KB2742599)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3)  
(KB2756921)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup>
(KB2742595)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=12917b84-1f91-4c19-9197-a7d1e7adcdfc)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=86e5b2fc-f530-4259-af90-259b64fcdd73)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97)  
(KB2736422)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup>
(KB2736428)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e19d1373-a3f3-4f60-9142-c2484726aac8)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(重要)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 8 for 32-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1f5441f1-a66d-42c0-bf0e-2f6867d4d43a)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 8 for 32-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9f40864f-5347-44ef-bb08-afea45b5351b)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c)  
(KB2757638)  
(緊急)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(緊急)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c669190d-964c-42d3-b09d-40a397ae3a9c)  
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(重要)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 8 for 64-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9d71dc77-9c01-4a1f-b403-8a18ca10979d)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 8 for 64-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1b40baad-784a-4eba-a4ef-703250248057)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998)  
(KB2742616)  
(重要)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e)  
(KB2756923)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a)  
(KB2742614)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb)  
(KB2736693)  
(重要)  
[Management OData IIS 拡張機能](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1)  
(KB2753596)  
(重要)
</td>
</tr>
<tr>
<th colspan="8">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
なし
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 4.0<sup>[1]</sup>
(KB2758694)  
(緊急)  
Microsoft XML コア サービス 6.0<sup>[1]</sup>
(KB2757638)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5<sup>[3]</sup>
(KB2742614)  
(重要)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
Windows RT<sup>[1]</sup>
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-008](https://go.microsoft.com/fwlink/?linkid=275222)
</td>
<td style="border:1px solid black;">
[MS13-001](https://go.microsoft.com/fwlink/?linkid=273848)
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-004](https://go.microsoft.com/fwlink/?linkid=268279)
</td>
<td style="border:1px solid black;">
[MS13-005](https://go.microsoft.com/fwlink/?linkid=273826)
</td>
<td style="border:1px solid black;">
[MS13-006](https://go.microsoft.com/fwlink/?linkid=273872)
</td>
<td style="border:1px solid black;">
[MS13-007](https://go.microsoft.com/fwlink/?linkid=268284)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
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
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e2738b9-d3c2-4dfe-8a79-335d5feee55b)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e6439fef-e5e7-479b-8fc4-daacf3a39f3a)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c635ad51-4e15-461c-8927-a86d79f90b45) (Server Core インストール)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b3ed781e-b740-4153-aaf3-daafdeb91004) (Server Core インストール)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
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
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735) (Server Core インストール)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (Server Core インストール)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1511377b-0adc-455f-8caa-f3498832c735) (Server Core インストール)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=eff3a82e-f3db-4733-95aa-a68621e27068) (Server Core インストール)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4aa3e3a7-3ebc-4b47-ab62-c22243a4edcc) (Server Core インストール)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19) (Server Core インストール)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (Server Core インストール)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (Server Core インストール)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (Server Core インストール)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=782fdaa7-7607-4617-97cc-516925e06d8a) (Server Core インストール)  
(KB2742598)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b8d0c829-ccb8-41a6-86ec-a7afde21c127) (Server Core インストール)  
(KB2756920)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5) (Server Core インストール)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e) (Server Core インストール)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4c77925d-4326-483b-9d20-ad533d91c0f4) (Server Core インストール)  
(KB2736418)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8de63e96-2822-4e62-af54-bd8d4c6d5c19) (Server Core インストール)  
(KB2769369)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (Server Core インストール)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (Server Core インストール)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd979acf-ed95-4d86-a046-ca7dc53523a3) (Server Core インストール)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5b23d8db-12d3-4404-b089-0c808eec1bd0) (Server Core インストール)  
(KB2742599)  
(重要)  
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a41722e4-4b94-4539-a80e-2714269f8ae3) (Server Core インストール)  
(KB2756921)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c2d4991c-05f1-48c7-96ea-1389281985e5)<sup>[1]</sup> (Server Core インストール)  
(KB2742595)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dafc6924-d798-46b4-9fa5-ea7c35f06fa0) (Server Core インストール)  
(KB2742613)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=934a2e78-c88b-4d06-9b8f-1d0b612f3fd5) (Server Core インストール)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7fd8a313-9ee3-4665-b8ba-b129994aae1e) (Server Core インストール)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=28f51d80-d87e-4a58-9ef2-d650dd84ad97) (Server Core インストール)  
(KB2736422)  
(重要)  
[Microsoft .NET Framework 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1d22f0d5-d87d-4e4a-bbc9-49826cec79a7)<sup>[1]</sup> (Server Core インストール)  
(KB2736428)  
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
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528) (Server Core インストール)  
(KB2757638)  
(警告)  
[Microsoft XML コア サービス 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dabf372-4b31-4c9e-a660-4e0f4a65db04) (Server Core インストール)  
(KB2758694)  
(警告)  
[Microsoft XML コア サービス 6.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7e434e5-1ce8-4754-b9b4-07f3d84e0528) (Server Core インストール)  
(KB2757638)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e1251343-b585-4feb-8465-7e775ae47998) (Server Core インストール)  
(KB2742616)  
(重要)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=43bbbc5a-e175-467a-9302-810a2a09eb7e) (Server Core インストール)  
(KB2756923)  
(重要)  
[Microsoft .NET Framework 4.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f21e2bdd-b158-45d5-a6cf-a8f32f099a7a) (Server Core インストール)  
(KB2742614)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2ad7872c-a387-41a1-8606-732a6ff0701d) (Server Core インストール)  
(KB2778930)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2012](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4f0b9fb1-f1c4-4773-a956-94c8983c008a) (Server Core インストール)  
(KB2785220)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b0bbe58b-cb41-4b52-9dd2-b8b4bc0076eb) (Server Core インストール)  
(KB2736693)  
(重要)  
[Management OData IIS 拡張機能](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=77b6fb5f-10b8-4bc2-a5c3-97055c92acf1) (Server Core インストール)  
(KB2753596)  
(重要)
</td>
</tr>
</table>
 
MS13-002 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

<sup>[1]</sup>Windows RT セキュリティ更新プログラムは [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) からの提供となります。

MS13-004 に関する注意

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「[.NET Framework のインストール](https://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

<sup>[2]</sup> 指定ソフトウェアのこの更新プログラムには深刻度が適用されません。このセキュリティ情報で説明する脆弱性に対する既知の攻撃方法は、既定の構成でブロックされるからです。しかし多層防御策として、マイクロソフトはこれらのソフトウェアをご使用のお客様に、このセキュリティ更新プログラムの適用を推奨します。

<sup>[3]</sup> Windows RT セキュリティ更新プログラムは [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) から提供されます。

MS13-005 に関する注意

<sup>[1]</sup> Windows RTセキュリティ更新プログラムは [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) からの提供となります。

MS13-006 に関する注意

<sup>[1]</sup> Windows RTセキュリティ更新プログラムは [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) からの提供となります。

MS13-007 に関する注意

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「[.NET Framework のインストール](https://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

#### Microsoft Office スイートおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d108d56c-f9fb-4823-b38e-3d2f838592de)  
(KB2760574)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(緊急)
</td>
</tr>
</table>
 
MS13-002 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Visual Studio Team Foundation Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7ba27dc9-4e9c-4ab5-867e-888c01716e11)  
(KB2687499)  
(緊急)
</td>
</tr>
</table>
 
MS13-002 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft サーバー ソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-003](https://go.microsoft.com/fwlink/?linkid=261863)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 2 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=31e1e6cc-9617-416b-8c91-5c026502d5f6)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-003](https://go.microsoft.com/fwlink/?linkid=261863)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 5.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fb21c3f8-b3fd-42f2-9c34-e5fbd8cad689)  
(KB2687497)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft System Center Operations Manager
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-002](https://go.microsoft.com/fwlink/?linkid=264923)
</td>
<td style="border:1px solid black;">
[MS13-003](https://go.microsoft.com/fwlink/?linkid=261863)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center Operations Manager 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f848d74d-fdae-4a19-a0f5-12d2d4389db9)<sup>[1]</sup>
(KB2809182)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft System Center Operations Manager 2007 R2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft System Center Operations Manager 2007 R2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4e1ab3bd-af0c-41f8-8ebc-1cdc68a3ee37)<sup>[1]</sup><sup>[2]</sup>
(KB2783850)  
(重要)
</td>
</tr>
</table>
 
MS13-002 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS13-003 に関する注意

<sup>[1]</sup>この更新プログラムは、マイクロソフト ダウンロード センターからのみ入手可能です。

<sup>[2]</sup>この更新プログラムは、累積的なものであり、指定ソフトウェア用の以前の累積的な更新プログラムを置き換えるものです。

検出および展開ツールとガイダンス
--------------------------------

<span></span>
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](https://go.microsoft.com/fwlink/?linkid=69903)を参照してください。[TechNet セキュリティ TechCenter](https://go.microsoft.com/fwlink/?linkid=21171) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](https://go.microsoft.com/fwlink/?linkid=85102)を参照してください。この情報には「セキュリティ更新プログラム」リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索で容易に見つけられます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](https://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](https://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ番号 (たとえば “MS13-001” など) を使用して検索することにより、バスケットに適用可能な更新プログラムをすべて追加することができ (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](https://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](https://support.microsoft.com/kb/961747/ja) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](https://technet.microsoft.com/ja-jp/wsus/default) の Web サイトを参照してください。

System Center Configuration Manager

System Center Configuration Manager のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。System Center Configuration Manager で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

System Center Configuration Manager の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。System Center Configuration Manager のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。System Center Configuration Manager の詳細については、[System Center テクニカル リソース](https://technet.microsoft.com/ja-jp/systemcenter/bb980621)を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager については、前のセクション「System Center Configuration Manager」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](https://technet.microsoft.com/ja-jp/systemcenter/bb545936) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](https://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet.microsoft.com/ja-jp/library/cc749197) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 水曜日に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja)
-   :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/ja-jp/wsus/bb456965)
-   (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://go.microsoft.com/fwlink/?linkid=21127)を表します。

-   MS13-002 で説明している問題を報告してくださった [Agarri](https://www.agarri.fr/) の Nicolas Grégoire 氏
-   MS13-003 で説明している問題を報告してくださった BAE Systems Detica の Andy Yang 氏
-   MS13-004 で説明している問題を報告してくださった [iSIGHT Partners Labs](https://www.isightpartners.com/) の Jon Erickson 氏
-   [Tipping Point](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力してMS13-004 で説明している 2 つの問題を報告してくださった Vitaliy Toropov 氏
-   MS13-004 で説明されている問題を報告してくださった Context Information Security の James Forshaw 氏
-   MS13-006 で説明している問題を報告してくださった [Kenichiro Katayama](https://twitter.com/pin_ptr) 氏
-   MS13-008 で説明している問題について、マイクロソフトと協力してくださった [Exodus Intelligence](https://www.exodusintel.com)

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617.aspx)
-   Windows を実行しているコンピューターのウィルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](https://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2013/01/09):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2013/01/10):MS13-002 で、Windows Server 2008 for 32-bit Systems Service Pack 2 にインストールされた Microsoft XML コア サービス 4.0 および Windows Server 2008 for 32-bit Systems Service Pack 2 上のMicrosoft XML コア サービス 6.0 について、影響を受けるソフトウェアへの Server Core インストールのエントリを追加しました。この更新は情報のみの変更です。システムを正常に更新済みのお客様は、措置を講じる必要はありません。
-   V2.0 (2013/01/16):マイクロソフト セキュリティ情報 MS13-008、Internet Explorer 用のセキュリティ更新プログラム (2799329)、また、この定例外のセキュリティ情報に関する Webcast のリンク先も追加しました。
-   V3.0 (2013/01/29):セキュリティ情報 MS13-004 を再リリースし、潜在的な互換性の問題があることがわかっている特定の構成で実行されている Windows 7 および Windows Server 2008 R2 用の KB2756920 更新プログラムを再度提供しました。詳細に関してはセキュリティ情報をご覧ください。
-   V4.0 (2013/03/13):セキュリティ情報 MS13-003 を再リリースし、Microsoft System Center Operations Manager 2007 Service Pack 1 の更新プログラムが利用可能になったことをお知らせしました。その他の更新プログラムについては、この再リリースによる影響はありません。詳細に関してはセキュリティ情報をご覧ください。

*Built at 2014-04-18T01:50:00Z-07:00*
