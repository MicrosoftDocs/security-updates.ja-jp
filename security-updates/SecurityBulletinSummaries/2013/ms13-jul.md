---
TOCTitle: 'MS13-JUL'
Title: 2013 年 7 月のセキュリティ情報
ms:assetid: 'ms13-jul'
ms:contentKeyID: 61229711
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms13-jul(v=Security.10)'
---


2013 年 7 月のセキュリティ情報
==============================

公開日: 2013年7月10日 | 最終更新日: 2013年9月9日

**バージョン:** 3.1

[![](../../images/Dn627291.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627291.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2013 年 7 月公開のセキュリティ情報の一覧です。

2013 年 7 月のセキュリティ情報の公開により、2013 年 7 月 5 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2013 年 7 月 10 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[7 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032556406&culture=en-us) (英語)。この日付以降、この Webcast は[オンデマンド](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us)で利用可能となります。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">.NET Framework および Silverlight の脆弱性により、リモートでコードが実行される (2861561) <br />
<br />
このセキュリティ更新プログラムは Microsoft .NET Framework および Microsoft Silverlight に存在する、非公開で報告された 5 件の脆弱性と公開された 2 件の脆弱性を解決します。これらの脆弱性の中で最も深刻なものの場合、信頼されているアプリケーションが特定のパターンのコードを使用すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (2850851)<br />
<br />
このセキュリティ更新プログラムは Microsoft Windows に存在する一般で公開された 2 件の脆弱性および非公開で報告された 6 件の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが TrueType フォントを含んでいる共有コンテンツを表示したときに、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性の悪用に成功した場合、影響を受けるシステムを完全に制御する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;">GDI+ の脆弱性により、 リモートでコードが実行される (2848295)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows、Microsoft Office、Microsoft Lync、および Microsoft Visual Studio に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが TrueType フォントを含んでいる共有コンテンツを表示した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office、<br />
Microsoft Visual Studio、<br />
Microsoft Lync</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2846071)  <br />
<br />
この累積的なセキュリティ更新プログラムは非公開で報告された 17 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;">Microsoft DirectShow の脆弱性により、リモートでコードが実行される (2845187)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性は、特別な細工がされた画像ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;">Windows Media フォーマット ランタイムの脆弱性により、リモートでコードが実行される (2847883)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。特別に細工されたメディア ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;">Windows Defender の脆弱性により、特権が昇格される (2847927)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Windows Defender for Windows 7 および Windows Server 2008 R2 にインストールされている場合の Windows Defender に存在する脆弱性を解決します。この脆弱性により、Windows Defender が使用するパス名のために、特権が昇格される可能性があります。攻撃者はこの脆弱性を悪用し、任意のコードを実行し、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。この脆弱性が悪用されるには、有効なログオン資格情報を所有していることが攻撃者にとっての必要条件となります。匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">Microsoft セキュリティ ソフトウェア</td>
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">配列アクセス違反の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3131">CVE-2013-3131</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">デリゲート リフレクションをバイパスする脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3132">CVE-2013-3132</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">匿名メソッドのインジェクションの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3133">CVE-2013-3133</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">配列割り当ての脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3134">CVE-2013-3134</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">デリゲート シリアル化の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3171">CVE-2013-3171</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=299844">MS13-052</a></td>
<td style="border:1px solid black;">Null ポインターの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3178">CVE-2013-3178</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k のメモリ割り当ての脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1300">CVE-2013-1300</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k の逆参照の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1340">CVE-2013-1340</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、最新のソフトウェア リリースに存在するサービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1345">CVE-2013-1345</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、最新のソフトウェア リリースに存在するサービス拒否の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3167">CVE-2013-3167</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性で、特権の昇格を引き起こす可能性があります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k のバッファー上書きの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3173">CVE-2013-3173</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301423">MS13-053</a></td>
<td style="border:1px solid black;">Win32k の読み取り AV の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3660">CVE-2013-3660</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。<br />
<br />
マイクロソフトは、特権昇格の脆弱性としてこの脆弱性を悪用しようとする標的型攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301531">MS13-054</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3129">CVE-2013-3129</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3115">CVE-2013-3115</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3143">CVE-2013-3143</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3144">CVE-2013-3144</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3145">CVE-2013-3145</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3146">CVE-2013-3146</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3147">CVE-2013-3147</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3148">CVE-2013-3148</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3149">CVE-2013-3149</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3150">CVE-2013-3150</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3151">CVE-2013-3151</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3152">CVE-2013-3152</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3153">CVE-2013-3153</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3161">CVE-2013-3161</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3162">CVE-2013-3162</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3163">CVE-2013-3163</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">マイクロソフトは、Internet Explorer 8 によりこの脆弱性を悪用しようとする標的型攻撃を確認しています。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3164">CVE-2013-3164</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">シフト JIS 文字エンコードの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3166">CVE-2013-3166</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309324">MS13-055</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3846">CVE-2013-3846</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=309326">MS13-056</a></td>
<td style="border:1px solid black;">DirectShow の任意メモリの上書きの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3174">CVE-2013-3174</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=301528">MS13-057</a></td>
<td style="border:1px solid black;">WMV ビデオ デコーダーのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3127">CVE-2013-3127</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=308992">MS13-058</a></td>
<td style="border:1px solid black;">Microsoft Windows 7 Defender の不適切なパス名の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3154">CVE-2013-3154</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
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
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.0 Service Pack 3:  
(Media Center Edition 2005 Service Pack 3 および Tablet PC Edition 2005 Service Pack 3 のみ)  
(2833951)  
(重要)  
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(Windows GDI+)  
(2834886)  
(緊急)  
Windows XP Service Pack 3  
(Windows XP Tablet PC Edition 2005 のみ)  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(緊急)  
Internet Explorer 7   
(2846071)  
(緊急)  
Internet Explorer 8   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media フォーマット ランタイム 11<sup>[1]</sup>
(wmvdecod.dll)  
(Media Center Edition のみ)  
(2834904)  
(緊急)  
Windows Media フォーマット ランタイム 9.5  
(wmvdmod.dll)  
(Media Center Edition のみ)  
(2834905)  
(緊急)  
Windows Media フォーマット ランタイム 9  
(wmvdmod.dll)  
(2803821)  
(緊急)  
Windows Media フォーマット ランタイム 9.5<sup>[2]</sup>
(wmvdmod.dll)  
(2834902)  
(緊急)  
Windows Media フォーマット ランタイム 9.5<sup>[3]</sup>
(wmvdmod.dll)  
(2834903)  
(緊急)  
Windows Media フォーマット ランタイム 11  
(wmvdecod.dll)  
(2834904)  
(緊急)  
wmv9vcm.dll (コーデック)  
(2845142)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2(2844285)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(緊急)  
Internet Explorer 7   
(2846071)  
(緊急)  
Internet Explorer 8   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media フォーマット ランタイム 9.5  
(wmvdmod.dll)  
(2803821)  
(緊急)  
Windows Media フォーマット ランタイム 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(緊急)  
Windows Media フォーマット ランタイム 11  
(wmvdecod.dll)  
(2834904)  
(緊急)  
wmv9vcm.dll (コーデック)  
(2845142)  
(緊急)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833949)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(Windows GDI+)  
(2834886)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(警告)  
Internet Explorer 7  
(2846071)  
(警告)  
Internet Explorer 8  
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media フォーマット ランタイム 9.5  
(wmvdmod.dll)  
(2803821)  
(緊急)  
wmv9vcm.dll (コーデック)  
(2845142)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832411)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(警告)  
Internet Explorer 7  
(2846071)  
(警告)  
Internet Explorer 8  
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media フォーマット ランタイム 9.5  
(wmvdmod.dll)  
(2803821)  
(緊急)  
Windows Media フォーマット ランタイム 9.5 x64  
(wmvdmod.dll)  
(2834902)  
(緊急)  
Windows Media フォーマット ランタイム 11  
(wmvdmod.dll)  
(2834904)  
(緊急)  
wmv9vcm.dll (コーデック)  
(2845142)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833940)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844285)  
(重要)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(Windows GDI+)  
(2834886)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2846071)  
(警告)  
Internet Explorer 7  
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2835622)  
(緊急)  
Microsoft .NET Framework 4.5  
(2833957)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(DirectWrite)  
(2835361)  
(緊急)  
Windows Vista Service Pack 2  
(Windows GDI+)  
(2834886)  
(緊急)  
Windows Vista Service Pack 2  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(緊急)  
Internet Explorer 8  
(2846071)  
(緊急)  
Internet Explorer 9   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
(緊急)  
wmv9vcm.dll (コーデック)  
(2845142)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2835622)  
(緊急)  
Microsoft .NET Framework 4.5  
(2833957)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(DirectWrite)  
(2835361)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(Windows GDI+)  
(2834886)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(緊急)  
Internet Explorer 8  
(2846071)  
(緊急)  
Internet Explorer 9   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 11  
(wmvdecod.dll)  
(2803821)  
(緊急)  
wmv9vcm.dll (コーデック)  
(2845142)  
(緊急)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2835622)  
(緊急)  
Microsoft .NET Framework 4.5  
(2833957)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(DirectWrite)  
(2835361)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Windows GDI+)  
(2834886)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(警告)  
Internet Explorer 8  
(2846071)  
(警告)  
Internet Explorer 9   
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(緊急)  
wmv9vcm.dll (コーデック) \[5\]  
(2845142)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.0 Service Pack 2  
(2832412)  
(緊急)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2832407)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2835622)  
(緊急)  
Microsoft .NET Framework 4.5  
(2833957)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(DirectWrite)  
(2835361)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(Windows GDI+)  
(2834886)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(警告)  
Internet Explorer 8  
(2846071)  
(警告)  
Internet Explorer 9   
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 11\[4\]  
(wmvdecod.dll)  
(2803821)  
(緊急)  
wmv9vcm.dll (コーデック) \[5\]  
(2845142)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2833941)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2833947)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2844287)  
(重要)  
Microsoft .NET Framework 3.5 Service Pack 1  
(2840629)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(Windows GDI+)  
(2834886)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
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
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2833957)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(DirectWrite)  
(2835361)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(Windows GDI+)  
(2834886)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(緊急)  
Internet Explorer 9   
(2846071)  
(緊急)  
Internet Explorer 10   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2833957)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(DirectWrite)  
(2835361)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(Windows GDI+)  
(2834886)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(緊急)  
Internet Explorer 9   
(2846071)  
(緊急)  
Internet Explorer 10   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(緊急)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2832414)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2833946)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2833957)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(DirectWrite)  
(2835361)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Windows GDI+)  
(2834886)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(警告)  
Internet Explorer 9   
(2846071)  
(警告)  
Internet Explorer 10   
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(DirectWrite)  
(2835361)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(Windows GDI+)  
(2834886)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="7">
Windows 8
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(緊急)  
Microsoft .NET Framework 3.5  
(2833959)  
(緊急)  
Microsoft .NET Framework 3.5  
(2840633)  
(重要)  
Microsoft .NET Framework 3.5  
(2844289)  
(重要)  
Microsoft .NET Framework 4.5  
(2833958)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(DirectWrite)  
(2835361)  
(緊急)  
Windows 8 for 32-bit Systems  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(緊急)  
Microsoft .NET Framework 3.5  
(2833959)  
(緊急)  
Microsoft .NET Framework 3.5  
(2840633)  
(重要)  
Microsoft .NET Framework 3.5  
(2844289)  
(重要)  
Microsoft .NET Framework 4.5  
(2833958)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(DirectWrite)  
(2835361)  
(緊急)  
Windows 8 for 64-bit Systems  
(Journal)  
(2835364)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(緊急)
</td>
</tr>
<tr>
<th colspan="7">
Windows Server 2012
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
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
[警告](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(緊急)  
Microsoft .NET Framework 3.5  
(2833959)  
(緊急)  
Microsoft .NET Framework 3.5  
(2840633)  
(重要)  
Microsoft .NET Framework 3.5  
(2844289)  
(重要)  
Microsoft .NET Framework 4.5  
(2833958)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(DirectWrite)  
(2835361)  
(緊急)  
Windows Server 2012  
(Journal)  
(2835364)(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2845187)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Media Player 12\[4\]  
(wmvdecod.dll)  
(2803821)  
(緊急)
</td>
</tr>
<tr>
<th colspan="7">
Windows RT
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[緊急](https://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5  
(2833958)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
Windows RT  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows RT  
(DirectWrite)  
(2835361)  
(緊急)
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2846071)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Media Player 12  
(wmvdecod.dll)  
(2803821)  
(緊急)
</td>
</tr>
<tr>
<th colspan="7">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-053](https://go.microsoft.com/fwlink/?linkid=301423)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
<td style="border:1px solid black;">
[MS13-055](https://go.microsoft.com/fwlink/?linkid=309324)
</td>
<td style="border:1px solid black;">
[MS13-056](https://go.microsoft.com/fwlink/?linkid=309326)
</td>
<td style="border:1px solid black;">
[MS13-057](https://go.microsoft.com/fwlink/?linkid=301528)
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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(Windows GDI+)  
(2834886)  
(緊急)
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
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(Windows GDI+)  
(2834886)  
(緊急)
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
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2833946)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2840631)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2844286)  
(重要)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2835393)  
(緊急)  
Microsoft .NET Framework 4<sup>[1]</sup>
(2840628)  
(重要)  
Microsoft .NET Framework 4.5  
(2833957)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840642)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(Windows GDI+)  
(2834886)  
(緊急)
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
Windows Server 2012 (Server Core インストール)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2832418)  
(緊急)  
Microsoft .NET Framework 3.5  
(2833959)  
(緊急)  
Microsoft .NET Framework 3.5  
(2840633)  
(重要)  
Microsoft .NET Framework 3.5  
(2844289)  
(重要)  
Microsoft .NET Framework 4.5  
(2833958)  
(緊急)  
Microsoft .NET Framework 4.5  
(2840632)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2850851)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(DirectWrite)  
(2835361)  
(緊急)
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
</table>
 
MS13-052 に関する注意事項

<sup>[1]</sup>.NET Framework 4 および .NET Framework 4 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4 および .NET Framework 4 Client Profile。.NET Framework 4 Client Profile は、.NET Framework 4 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4 および .NET Framework 4 Client Profile の両方に影響を与えます。詳細については、MSDN の「[.NET Framework のインストール](https://msdn.microsoft.com/ja-jp/library/5a4x27ek)」を参照してください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS13-053 および MS13-055 に関する注意事項

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS13-054 に関する 注意事項

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS13-057 に関する注意事項

<sup>[1]</sup>この更新プログラムは、WindowsMediaフォーマットランタイム 11 または Windows Media Player 11 にアップグレードされたシステムにのみ提供されます。  
<sup>[2]</sup>この更新プログラムは、WindowsMediaフォーマット ランタイム9.5NL を実行しているシステムにのみ提供されます。  
<sup>[3]</sup>この更新プログラムは、WindowsMediaフォーマット ランタイム9.5L を実行しているシステムにのみ提供されます。  
\[4\]この更新プログラムは、オプションのデスクトップエクスペリエンス機能が有効にされている場合のみ提供されます。  
\[5\]この更新プログラムは、オプションのデスクトップエクスペリエンス機能が有効になっていて、wmv9vcm.dllコーデックが存在する場合にのみ提供されます。詳細に関してはセキュリティ情報をご覧ください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft Office スイートおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(2817480)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2687309)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)  
(2687276)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)  
(2687276)  
(重要)
</td>
</tr>
</table>
 
MS13-054 に関する注意事項

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Visual Studio .NET 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Visual Studio .NET 2003 Service Pack 1<sup>[1]</sup>
(2856545)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Silverlight
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
[MS13-052](https://go.microsoft.com/fwlink/?linkid=299844)
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
Mac にインストールされている Microsoft Silverlight 5  
(2847559)  
(緊急)  
Mac にインストールされている Microsoft Silverlight 5 Developer Runtime  
(2847559)  
(緊急)  
32 ビット版の Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(2847559)  
(緊急)  
x64-based 版の Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(2847559)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(2847559)  
(緊急)  
32 ビット版の Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(2847559)  
(緊急)  
x64-based 版の Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(2847559)  
(緊急)  
すべてのサポートされているリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(2847559)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>
 
MS13-052 に関する注意事項

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS13-054 に関する注意事項

<sup>[1]</sup>この更新プログラムは、マイクロソフト ダウンロードセンターからのみ入手可能です。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft コミュニケーション プラットフォームおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Lync
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-054](https://go.microsoft.com/fwlink/?linkid=301531)
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
Microsoft Lync 2010 (32 ビット)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)  
(2843160)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)  
(2843160)  
(緊急)
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
(2843162)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(管理レベル インストール)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(管理レベル インストール)  
(2843163)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 ビット)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 ビット)  
(2817465)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 ビット)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 ビット)  
(2817465)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 ビット)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 ビット)  
(2817465)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64 ビット)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64 ビット)  
(2817465)  
(緊急)
</td>
</tr>
</table>
 
MS13-054 に関する注意事項

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。 

#### Microsoft セキュリティ ソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
スパイウェア対策ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-058](https://go.microsoft.com/fwlink/?linkid=308992)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 用の Windows Defender (x86)
</td>
<td style="border:1px solid black;">
Windows 7 用の Windows Defender (x86)   
(2847927)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 用の Windows Defender (x64)
</td>
<td style="border:1px solid black;">
Windows 7 用の Windows Defender (x64)   
(2847927)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 (x64) にインストールされている Windows Defender
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 (x64) にインストールされている Windows Defender   
(2847927)  
(重要)
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

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](https://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](https://technet.microsoft.com/ja-jp/systemcenter/bb545936) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](https://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](https://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet.microsoft.com/ja-jp/library/cc749197) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
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
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://go.microsoft.com/fwlink/?linkid=21127)を表します。

MS13-052

-   TrueType フォントの解析の脆弱性 (CVE-2013-3129) を報告してくださった [F-13 Laboratory](https://www.f13-labs.net/) の Ling Chuan Lee 氏と Lee Yee Chan 氏
-   配列アクセス違反の脆弱性 (CVE-2013-3131) を報告してくださった Alon Fliess 氏
-   デリゲート リフレクションをバイパスする脆弱性 (CVE-2013-3132) を報告してくださった [Context Information Security](https://www.contextis.com/) の James Forshaw 氏
-   匿名メソッドのインジェクションの脆弱性 (CVE-2013-3133) を報告してくださった [Context Information Security](https://www.contextis.com/) の James Forshaw 氏
-   デリゲート シリアル化の脆弱性 (CVE-2013-3171) を報告してくださった [Context Information Security](https://www.contextis.com/) の James Forshaw 氏
-   Null ポインターの脆弱性 (CVE-2013-3178) を報告してくださった Vitaliy Toropov 氏

MS13-053

-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Win32k のメモリ割り当ての脆弱性 (CVE-2013-1300) を報告してくださった MWR Labs の Jon Butler 氏と Nils 氏
-   Win32k 逆参照の脆弱性 (CVE-2013-1340) を報告してくださった [Dr.Web](https://drweb.com/) の Alexander Chizhov 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Win32k のウィンドウ ハンドルの脆弱性 (CVE-2013-1345) を報告してくださった匿名のリサーチャー
-   TrueType フォントの解析の脆弱性 (CVE-2013-3129) を報告してくださった [F13 Laboratory](https://www.f13-labs.net/) の Ling Chuan Lee 氏と Lee Yee Chan 氏
-   Win32k の情報漏えいの脆弱性 (CVE-2013-3167) を報告してくださった [Tencent PC Manager](https://guanjia.qq.com) の Yinliang 氏
-   Win32k バッファー オーバーフローの脆弱性 (CVE-2013-3172) を報告してくださった [Google Inc](https://www.google.com/) の [Mateusz "j00ru" Jurczyk 氏](https://j00ru.vexillium.org/)
-   Win32k のバッファー上書きの脆弱性 (CVE-2013-3173) の問題を報告してくださった [Qihoo 360 Security Center](https://www.360.cn/) の Wen Yujie 氏と Guo Pengfei 氏

MS13-054

-   TrueType フォントの解析の脆弱性 (CVE-2013-3129) を報告してくださった [F13 Laboratory](https://www.f13-labs.net/) の Ling Chuan Lee 氏と Lee Yee Chan 氏

MS13-055

-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3115) を報告してくださった [Google Security Team](https://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3143) を報告してくださった SkyLined 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3144) を報告してくださった Simon Zuckerbraun 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3145) を報告してくださった Toan Pham Van 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3146) を報告してくださった Toan Pham Van 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3147) を報告してくださった[Aniway.Anyway@gmail.com](mailto:aniway.anyway@gmail.com) 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3148) を報告してくださった Bluesea 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3149) を報告してくださった Bluesea 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3150) を報告してくださった[Omair](https://krash.in/) 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3151) を報告してくださった Toan Pham Van 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3152) を報告してくださった匿名のリサーチャー
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3153) を報告してくださった e6af8de8b1d4b2b6d5ba2610cbf9cd38 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3161) を報告してくださった [Google Security Team](https://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3162) を報告してくださった [Google Security Team](https://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3163) を報告してくださった Jose Antonio Vazquez Gonzalez 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3164) を報告してくださった [Security-Assessment.com](https://www.security-assessment.com/) の Scott Bell 氏
-   Shift JIS 文字エンコードの脆弱性 (CVE-2013-3166) を報告してくださった Masato Kinugawa 氏
-   このセキュリティ情報に記載されている多層防御の変更 (CVE-2013-4015) についてマイクロソフトに協力してくださった IBM X-Force の Mark Yason 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3846) を報告してくださった Amol Naik 氏

MS13-056

-   DirectShow の任意メモリの上書きの脆弱性 - CVE-2013-3174 を報告してくださった Andrés Gómez Ramírez 氏

MS13-057

-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力して、WMV ビデオ デコーダーのリモートでコードが実行される脆弱性 (CVE-2013-3127) を報告してくださった匿名のリサーチャー

MS13-058

-   Microsoft Windows 7 Defender の不適切なパス名の脆弱性 (CVE-2013-3154) を報告してくださった [Reserve Bank of Australia](https://www.rba.gov.au/) の Alton Blom 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)
-   Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](https://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2013/07/10):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2013/07/11):MS13-055 について、Exploitability Index (悪用可能性指標) での CVE-2013-3163 の悪用可能性評価を更新しました。マイクロソフトは、Internet Explorer 8 によりこの脆弱性を悪用しようとする標的型攻撃を確認しています。今回の更新は情報のみの変更です。
-   V2.0 (2013/08/14):MS13-052 について、このセキュリティ情報ページを更新し、更新プログラム 2840628、2840632、2840642、2844285、2844286、2844287、および 2844289 を再リリースしました。MS13-057 について、このセキュリティ情報ページを更新し、Windows 7 および Windows 2008 R2 用の更新プログラム 2803821 を再リリースしました。お客様は、システムに適応する再リリース版の更新プログラムをインストールする必要があります。詳細については、それぞれのセキュリティ情報を参照してください。
-   V3.0 (2013/08/28):MS13-057 について、このセキュリティ情報ページを更新し、Windows XP、Windows Server 2003、Windows Vista、および Windows Server 2008 用のセキュリティ更新プログラム 2803821、Windows XP および Windows Server 2003 用のセキュリティ更新プログラム 2834902、Windows XP 用のセキュリティ更新プログラム 2834903、Windows XP および Windows Server 2003 用のセキュリティ更新プログラム 2834904、Windows XP 用のセキュリティ更新プログラム 2834905 を再リリースしました。Windows XP、Windows Server 2003、Windows Vista および Windows Server 2008 をご使用のお客様は、システムに適応する再リリース版の更新プログラムをインストールする必要があります。詳細については、セキュリティ情報を参照してください。
-   V3.1 (2013/09/09):MS13-055 について、Exploitability Index (悪用可能性指標) に CVE-2013-3846 の Exploitability (悪用可能性) を追加しました。今回の更新は情報のみの変更です。

*Built at 2014-04-18T01:50:00Z-07:00*
