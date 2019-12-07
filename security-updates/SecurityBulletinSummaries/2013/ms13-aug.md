---
TOCTitle: 'MS13-AUG'
Title: 2013 年 8 月のセキュリティ情報
ms:assetid: 'ms13-aug'
ms:contentKeyID: 61229707
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms13-aug(v=Security.10)'
---


2013 年 8 月のセキュリティ情報
==============================

公開日: 2013年8月14日 | 最終更新日: 2013年8月28日

**バージョン:** 3.0

[![](../../images/Dn627287.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627287.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2013 年 8 月公開のセキュリティ情報の一覧です。

2013 年 8 月のセキュリティ情報の公開により、2013 年 8 月 9 日に公開した事前通知を、このセキュリティ情報の概要に置き換えました。事前通知サービスの詳細については、[「マイクロソフト セキュリティ情報の事前通知」](https://go.microsoft.com/fwlink/?linkid=217213)を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2013 年 8 月 14 日 の午後 (日本時間) に配信予定です。詳細は、「 [今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/security/dd251169.aspx) 」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2013 年 8 月 14 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[8 月の セキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557295&culture=en-us) (英語)。この日付以降、この Webcast は[オンデマンド](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us)で利用可能となります。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

### セキュリティ情報に関する情報

#### 概要

次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2862772)  <br />
<br />
このセキュリティ更新プログラムは非公開で報告された 11 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314044">MS13-060</a></td>
<td style="border:1px solid black;">Unicode スクリプト プロセッサの脆弱性により、リモートでコードが実行される (2850869)<br />
<br />
このセキュリティ更新プログラムは、Microsoft Windows に含まれる Unicode スクリプト プロセッサに存在する非公開で報告された脆弱性を解決します。ユーザーが特別な細工がされた文書または Web ページを Embedded OpenType フォントをサポートしているアプリケーションで表示した場合、この脆弱性により、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=317381">MS13-061</a></td>
<td style="border:1px solid black;">Microsoft Exchange Server の脆弱性により、リモートでコードが実行される (2876063)<br />
<br />
このセキュリティ更新プログラムは Microsoft Exchange Server に存在する公開された 3 件の脆弱性を解決します。Microsoft Exchange Server の WebReady ドキュメント表示およびデータ損失防止機能に脆弱性が存在します。この脆弱性により、ユーザーが特別な細工がされたファイルを Outlook Web App (OWA) を使用してプレビュー表示した場合に、Exchange Server のトランスコーディング サービスのセキュリティ コンテキストでリモートでコードが実行される可能性があります。WebReady ドキュメント表示で使用される Exchange のトランスコーディング サービスは LocalService アカウントのユーザー資格を使用して実行されます。データ損失防止機能には、Exchange サーバーが特別な細工をされたメッセージを受信した場合、フィルタリング管理サービスのセキュリティ コンテキストでコードがリモートで実行される可能性のあるコードがあります。Exchange のフィルタリング管理サービスでは、LocalService アカウントのユーザー資格を使用します。LocalService アカウントはローカル システムの最小限の権限しか持たないアカウントで、ネットワーク上では匿名の資格情報を提示します。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309337">MS13-062</a></td>
<td style="border:1px solid black;">リモート プロシージャ コールの脆弱性により、特権が昇格される (2849470)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工した RPC 要求を送信した場合、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309338">MS13-063</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、特権が昇格される (2859537)<br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する 1 件の一般に公開された脆弱性および 3 件の非公開で報告された脆弱性を解決します。最も深刻な脆弱性では、攻撃者がローカルでログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314043">MS13-064</a></td>
<td style="border:1px solid black;">Windows NAT ドライバーの脆弱性により、サービス拒否が起こる (2849568)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Windows の Windows NAT ドライバーの脆弱性を解決します。この脆弱性により、攻撃者が Windows NAT Driver サービスを実行している標的のサーバーに特別に細工された ICMP パケットを送信した場合、サービス拒否が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314047">MS13-065</a></td>
<td style="border:1px solid black;">ICMPv6 の脆弱性により、サービス拒否が起こる (2868623)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。攻撃者が特別に細工された ICMP パケットを標的となるコンピューターに送信した場合、この脆弱性のためにサービス拒否が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309325">MS13-066</a></td>
<td style="border:1px solid black;">Active Directory フェデレーション サービスの脆弱性により、情報漏えいが起こる (2873872) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Active Directory フェデレーション サービス (ADFS) の脆弱性を解決します。この脆弱性のために、ADFS によって使用されるサービス アカウントに関連して情報漏えいが起こる可能性があります。アカウント ロックアウト ポリシーが構成されている場合、攻撃者が企業ネットワークの外部からログオンしようとしたために、ADFS によって使用されるサービス アカウントがアカウント ロックアウトになる可能性があります。これにより、ADFS インスタンスに依存するすべてのアプリケーションでサービス拒否が発生する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3184">CVE-2013-3184</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3187">CVE-2013-3187</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3188">CVE-2013-3188</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3189">CVE-2013-3189</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3190">CVE-2013-3190</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3191">CVE-2013-3191</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3193">CVE-2013-3193</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3194">CVE-2013-3194</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=313330">MS13-059</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3199">CVE-2013-3199</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314044">MS13-060</a></td>
<td style="border:1px solid black;">Uniscribe フォント解析エンジンのメモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3181">CVE-2013-3181</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=317381">MS13-061</a></td>
<td style="border:1px solid black;">Oracle Outside In の悪用される恐れのある複数の脆弱性</td>
<td style="border:1px solid black;">複数*</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">*複数の脆弱性があります。詳細については、マイクロソフト セキュリティ情報 MS13-061 を参照してください。<br />
<br />
これらの脆弱性が一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309337">MS13-062</a></td>
<td style="border:1px solid black;">リモート プロシージャ コールの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3175">CVE-2013-3175</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309338">MS13-063</a></td>
<td style="border:1px solid black;">ASLR セキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-2556">CVE-2013-2556</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309338">MS13-063</a></td>
<td style="border:1px solid black;">Windows カーネル メモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3196">CVE-2013-3196</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309338">MS13-063</a></td>
<td style="border:1px solid black;">Windows カーネル メモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3197">CVE-2013-3197</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309338">MS13-063</a></td>
<td style="border:1px solid black;">Windows カーネル メモリの破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3198">CVE-2013-3198</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314043">MS13-064</a></td>
<td style="border:1px solid black;">Windows NAT のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3182">CVE-2013-3182</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=314047">MS13-065</a></td>
<td style="border:1px solid black;">ICMPv6 の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3183">CVE-2013-3183</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309325">MS13-066</a></td>
<td style="border:1px solid black;">AD FS の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3185">CVE-2013-3185</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
</tbody>
</table>
  
影響を受けるソフトウェア  
------------------------
  
<span></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
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
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(緊急)  
Internet Explorer 7   
(2862772)  
(緊急)  
Internet Explorer 8   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2850869)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2859537)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(緊急)  
Internet Explorer 7   
(2862772)  
(緊急)  
Internet Explorer 8   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2850869)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2849470)  
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
対象外
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
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
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(警告)  
Internet Explorer 7  
(2862772)  
(警告)  
Internet Explorer 8  
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2850869)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 1.x  
(Windows Server 2003 R2 Service Pack 2 のみ)  
(2868846)  
(深刻度なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(警告)  
Internet Explorer 7  
(2862772)  
(警告)  
Internet Explorer 8  
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2850869)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2849470)  
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
Active Directory フェデレーション サービス 1.x  
(Windows Server 2003 R2 x64 Edition Service Pack 2 のみ)  
(2868846)  
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2862772)  
(警告)  
Internet Explorer 7  
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2850869)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2849470)  
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
対象外
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2862772)  
(緊急)  
Internet Explorer 8  
(2862772)  
(緊急)  
Internet Explorer 9   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2868623)  
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
(2862772)  
(緊急)  
Internet Explorer 8  
(2862772)  
(緊急)  
Internet Explorer 9   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
Internet Explorer 7  
(2862772)  
(警告)  
Internet Explorer 8  
(2862772)  
(警告)  
Internet Explorer 9   
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 2.0  
(2843638)  
(重要)  
Active Directory フェデレーション サービス 1.x  
(2868846)  
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2862772)  
(警告)  
Internet Explorer 8  
(2862772)  
(警告)  
Internet Explorer 9   
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 2.0  
(2843638)  
(重要)  
Active Directory フェデレーション サービス 1.x  
(2868846)  
(深刻度なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2862772)  
(緊急)  
Internet Explorer 9   
(2862772)  
(緊急)  
Internet Explorer 10   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2862772)  
(緊急)  
Internet Explorer 9   
(2862772)  
(緊急)  
Internet Explorer 10   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2862772)  
(警告)  
Internet Explorer 9   
(2862772)  
(警告)  
Internet Explorer 10   
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 2.0  
(2843638)  
(重要)  
Active Directory フェデレーション サービス 1.x  
(2868846)  
(深刻度なし)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
Internet Explorer 10   
(2862772)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2849568)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 2.1  
(2843638)  
(重要)  
Active Directory フェデレーション サービス 2.1  
(2843639)  
(深刻度なし)
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2862772)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows RT  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows RT  
(2868623)  
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
[MS13-059](https://go.microsoft.com/fwlink/?linkid=313330)
</td>
<td style="border:1px solid black;">
[MS13-060](https://go.microsoft.com/fwlink/?linkid=314044)
</td>
<td style="border:1px solid black;">
[MS13-062](https://go.microsoft.com/fwlink/?linkid=309337)
</td>
<td style="border:1px solid black;">
[MS13-063](https://go.microsoft.com/fwlink/?linkid=309338)
</td>
<td style="border:1px solid black;">
[MS13-064](https://go.microsoft.com/fwlink/?linkid=314043)
</td>
<td style="border:1px solid black;">
[MS13-065](https://go.microsoft.com/fwlink/?linkid=314047)
</td>
<td style="border:1px solid black;">
[MS13-066](https://go.microsoft.com/fwlink/?linkid=309325)
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
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2868623)  
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
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2868623)  
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
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2859537)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
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
(2849470)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2868623)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>
 

#### Microsoft サーバー ソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-061](https://go.microsoft.com/fwlink/?linkid=317381)
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
Microsoft Exchange Server 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2873746)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2  
(2874216)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2866475)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積更新プログラム 1
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積更新プログラム 1  
(2874216)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積更新プログラム 2
</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積更新プログラム 2  
(2874216)  
(緊急)
</td>
</tr>
</table>
 

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

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja) :Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

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

MS13-059

-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3184) を報告してくださった、[Corelan](https://www.corelangcv.com/) の Peter 'corelanc0d3r' Van Eeckhoutte 氏
-   プロセス整合性レベルの割り当ての脆弱性 (CVE-2013-3186) を報告してくださった、[Google Security Team](https://www.google.com/) の Fermin J. Serna 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/)と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3187) を報告してくださった Arthur Gerkis 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3188) を報告してくださった、[Security-Assessment.com](https://www.security-assessment.com/) の Scott Bell 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3189) を報告してくださった、[Security-Assessment.com](https://www.security-assessment.com/) の Scott Bell 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3190) を報告してくださった、[Google Security Team](https://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3191) を報告してくださった、[Google Security Team](https://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   EUC-JP 文字エンコードの脆弱性 (CVE-2013-3192) を報告してくださった Alex Inführ 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/)と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3193) を報告してくださった Jose Antonio Vazquez Gonzalez 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/)と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3194) を報告してくださった Arthur Gerkis 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/)と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3199) を報告してくださった匿名のリサーチャー
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/)と協力して、このセキュリティ情報に含まれている多層防御の変更についてマイクロソフトと協力してくださった [VUPEN Security](https://www.vupen.com) 氏

MS13-060

-   Uniscribe フォント解析エンジンのメモリ破損の脆弱性 (CVE-2013-3181) を報告してくださった、[Mozilla](https://www.mozilla.org/) の Bob Clary 氏

MS13-063

-   ASLR セキュリティ機能のバイパスの脆弱性 (CVE-2013-2556) について [HP の](https://www.hpenterprisesecurity.com/products)[Zero Day Initiative](https://www.zerodayinitiative.com/) と協力してくださった [VUPEN Security](https://www.vupen.com)
-   ASLR セキュリティ機能のバイパスの脆弱性 (CVE-2013-2556) について協力してくださった [Nsfocus Security Team](https://www.nsfocus.com/) の Yang Yu 氏
-   Windows カーネル破損の脆弱性 (CVE-2013-3196) を報告してくださった [Google Inc](https://www.google.com/) の [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 氏
-   Windows カーネル破損の脆弱性 (CVE-2013-3197) を報告してくださった [Google Inc](https://www.google.com/) の [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 氏
-   Windows カーネル破損の脆弱性 (CVE-2013-3198) を報告してくださった [Google Inc](https://www.google.com/) の [Mateusz "j00ru" Jurczyk](https://j00ru.vexillium.org/) 氏

MS13-065

-   ICMPv6 の脆弱性 (CVE-2013-3183) を報告してくださった Symantec の Basil Gabriel 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)
-   Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](https://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2013/08/14):このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2013/08/21):MS13-066 について、このセキュリティ情報ページを更新し、Windows Server 2008 および Windows Server 2008 R2 上の Active Directory フェデレーション サービス 2.0 用の更新プログラム 2843638 の再提供をお知らせしました。詳細については、セキュリティ情報を参照してください。
-   V3.0 (2013/08/28):MS13-061 について、このセキュリティ情報ページを更新し、Microsoft Exchange Server 2013 の累積更新プログラム 1 および Microsoft Exchange Server 2013 の累積更新プログラム 2 用の更新プログラム 2874216 の再提供をお知らせしました。詳細については、セキュリティ情報を参照してください。

*Built at 2014-04-18T01:50:00Z-07:00*
