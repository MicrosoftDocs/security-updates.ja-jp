---
TOCTitle: 'MS14-OCT'
Title: 2014 年 10 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms14-oct'
ms:contentKeyID: 63162676
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms14-oct(v=Security.10)'
---

2014 年 10 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日:2014 年 10 月 15 日

**バージョン:** 1.0

このセキュリティ情報の概要は 2014 年 10 月公開のセキュリティ情報の一覧です。

2014 年 10 月のセキュリティ情報の公開により、2014 年 10 月 10 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2014 年 10 月 15 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。月例 Webcast の表示、およびその他のセキュリティ情報 Webcast へのリンクについては、[Microsoft Security Bulletin Webcast (英語情報)](https://technet.microsoft.com/security/dn756352) を参照してください。

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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (2987107)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 14 件の Internet Explorer に存在する脆弱性を解決します。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;"><strong>.NET Framework の脆弱性により、リモートでコードが実行される (3000414)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された Microsoft .NET Framework に存在する 3 件の脆弱性を解決します。最も重大な脆弱性では、攻撃者が国際文字を含んでいる特別に細工された URI リクエストを .NET Web アプリケーションに送信した場合、リモートでコードが実行される可能性があります。.NET 4.0 アプリケーションでは、脆弱な機能 (iriParsing) が既定で無効になっています。アプリケーションがこの機能を明示的に有効にしないかぎり、この脆弱性を悪用することはできません。.NET 4.5 アプリケーションでは、iriParsing は既定で有効になっており、無効にすることはできません。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;"><strong>カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (3000061)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性のより深刻な状況では、攻撃者が特別に細工したドキュメントを開くようにユーザーを誘導した場合、または埋め込み TrueType フォントが含まれる信頼されていない Web サイトにアクセスするようにユーザーを誘導した場合、リモートでコードが実行される可能性があります。ただし、すべての場合において、攻撃者がこのような操作をユーザーに強制的に実行させる方法はないと考えられます。その代わり、通常は、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせて、ユーザーにそのような行動をとらせることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507673">MS14-059</a></td>
<td style="border:1px solid black;"><strong>ASP.NET MVC の脆弱性により、セキュリティ機能のバイパスが起こる (2990942)<br />
<br />
</strong>このセキュリティ更新プログラムは ASP.NET MVC に存在する一般に公開された脆弱性を解決します。この脆弱性により、攻撃者が、特別に細工されたリンクをクリックするようにユーザーを誘導した場合、または、この脆弱性の悪用を目的として特別に細工されたコンテンツを含む Web ページを訪問するようにユーザーを誘導した場合に、セキュリティ機能のバイパスが発生する可能性があります。Web ベースの攻撃のシナリオでは、攻撃者は Web ブラウザーを介してこの脆弱性を悪用するように特別に細工した Web サイトをホストし、その Web サイトを表示するようにユーザーを誘導する可能性があります。また、攻撃者は侵害された Web サイトおよびユーザーが提供したコンテンツや広告を受け入れる、またはホストする Web サイトを利用する可能性があります。これらの Web サイトには、この脆弱性を悪用する可能性のある特別に細工されたコンテンツが含まれている場合があります。しかし、すべての場合において、強制的にユーザーに攻撃者が制御するコンテンツを表示させることはできません。その代わり、ユーザーに操作を行わせることが攻撃者にとっての必要条件となります。一般的には、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせ、攻撃者の Web サイトへユーザーを誘導します。または、電子メールで送信した添付ファイルを開かせようとします。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">マイクロソフト開発者用ツール</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513097">MS14-060</a></td>
<td style="border:1px solid black;"><strong>Windows OLE の脆弱性により、リモートでコードが実行される (3000869)<br />
<br />
</strong>このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された OLE オブジェクトが含まれる Microsoft Office ファイルを開いた場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、現在のユーザーのコンテキストで任意のコードが実行される可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はプログラムのインストール、データの表示、変更または削除、あるいはすべてのユーザー権限を持つ新規アカウントの作成を行う可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513106">MS14-061</a></td>
<td style="border:1px solid black;"><strong>Microsoft Word および Office Web Apps の脆弱性により、リモートでコードが実行される (3000434)<br />
<br />
</strong>このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工した Microsoft Word ファイルをユーザーに開かせるように誘導した場合、リモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はプログラムのインストール、データの表示、変更または削除、あるいはすべてのユーザー権限を持つ新規アカウントの作成を行う可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services、<br />
Microsoft Office Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513107">MS14-062</a></td>
<td style="border:1px solid black;"><strong>メッセージ キュー サービスの脆弱性により、特権が昇格される (2993254)<br />
<br />
</strong>このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。攻撃者が特別に細工された Input Output Control (IOCTL) 要求をメッセージ キュー サービスに送信した場合、特権が昇格される可能性があります。この脆弱性が悪用された場合、影響を受けるシステムにフルアクセスされる可能性があります。既定で、メッセージ キューのコンポーネントはいずれの影響を受けるオペレーティング システムにもインストールされておらず、管理者特権を持つユーザーによってのみ有効にされます。この問題の影響を受ける可能性があるのは、メッセージ キューのコンポーネントを手動で有効にしたお客様のみです。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513102">MS14-063</a></td>
<td style="border:1px solid black;"><strong>FAT32 ディスク パーティション ドライバーの脆弱性により、特権が昇格される (2998579)<br />
<br />
</strong>このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。Windows FASTFAT システム ドライバーが FAT32 ディスク パーティションと対話する方法に特権の昇格の脆弱性が存在します。この脆弱性が悪用された場合、攻撃者により昇格された特権で任意のコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4123">CVE-2014-4123</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは、IE のサンドボックスのバイパスによる特権の昇格の脆弱性です。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4124">CVE-2014-4124</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4126">CVE-2014-4126</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4127">CVE-2014-4127</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4128">CVE-2014-4128</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4129">CVE-2014-4129</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4130">CVE-2014-4130</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4132">CVE-2014-4132</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4133">CVE-2014-4133</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4134">CVE-2014-4134</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4137">CVE-2014-4137</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4138">CVE-2014-4138</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4140">CVE-2014-4140</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513092">MS14-056</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4141">CVE-2014-4141</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">.NET ClickOnce の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4073">CVE-2014-4073</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">.NET Framework のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4121">CVE-2014-4121</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513095">MS14-057</a></td>
<td style="border:1px solid black;">.NET ASLR の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4122">CVE-2014-4122</a></td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;">Win32k.sys の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4113">CVE-2014-4113</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513104">MS14-058</a></td>
<td style="border:1px solid black;">TrueType フォントのリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4148">CVE-2014 -4148</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507673">MS14-059</a></td>
<td style="border:1px solid black;">MVC XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4075">CVE-2014-4075</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513097">MS14-060</a></td>
<td style="border:1px solid black;">Windows OLE のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4114">CVE-2014-4114</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513106">MS14-061</a></td>
<td style="border:1px solid black;">Microsoft Word ファイル形式の脆弱性 </td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4117">CVE-2014-4117</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513107">MS14-062</a></td>
<td style="border:1px solid black;">MQAC の任意の書き込み権限昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4971">CVE-2014-4971</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513102">MS14-063</a></td>
<td style="border:1px solid black;">Microsoft Windows ディスク パーティション ドライバーの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4115">CVE-2014-4115</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
(警告)  
Internet Explorer 7  
(2987107)  
(警告)  
Internet Explorer 8  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972105)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979574)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993254)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2998579)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
(警告)  
Internet Explorer 7  
(2987107)  
(警告)  
Internet Explorer 8  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972105)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979574)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993254)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2998579)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(2987107)  
(警告)  
Internet Explorer 7  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2972105)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979574)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2993254)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2998579)  
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
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(緊急)  
Internet Explorer 8  
(2987107)  
(緊急)  
Internet Explorer 9  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3000869)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2998579)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(緊急)  
Internet Explorer 8  
(2987107)  
(緊急)  
Internet Explorer 9  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3000869)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2998579)  
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
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(警告)  
Internet Explorer 8  
(2987107)  
(警告)  
Internet Explorer 9  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3000869)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2998579)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(警告)  
Internet Explorer 8  
(2987107)  
(警告)  
Internet Explorer 9  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3000869)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2998579)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2968292)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2972098)  
(緊急)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2979568)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3000869)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2998579)  
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
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
(緊急)  
Internet Explorer 9  
(2987107)  
(緊急)  
Internet Explorer 10  
(2987107)  
(緊急)  
Internet Explorer 11  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3000869)  
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
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
(緊急)  
Internet Explorer 9  
(2987107)  
(緊急)  
Internet Explorer 10  
(2987107)  
(緊急)  
Internet Explorer 11  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
(警告)  
Internet Explorer 9  
(2987107)  
(警告)  
Internet Explorer 10  
(2987107)  
(警告)  
Internet Explorer 11  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3000869)  
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
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2968294)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(重要)  
Microsoft .NET Framework 3.5  
(2972101)  
(緊急)  
Microsoft .NET Framework 3.5  
(2979571)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3000869)  
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
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(重要)  
Microsoft .NET Framework 3.5  
(2972101)  
(緊急)  
Microsoft .NET Framework 3.5  
(2979571)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3000869)  
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
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(重要)  
Microsoft .NET Framework 3.5  
(2972103)  
(緊急)  
Microsoft .NET Framework 3.5  
(2979573)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(緊急)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3000869)  
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
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(重要)  
Microsoft .NET Framework 3.5  
(2972103)  
(緊急)  
Microsoft .NET Framework 3.5  
(2979573)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(緊急)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Server 2012

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(重要)  
Microsoft .NET Framework 3.5  
(2972101)  
(緊急)  
Microsoft .NET Framework 3.5  
(2979571)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3000869)  
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
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(重要)  
Microsoft .NET Framework 3.5  
(2972103)  
(緊急)  
Microsoft .NET Framework 3.5  
(2979573)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(緊急)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows RT

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(3000869)  
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
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(2987107)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(緊急)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3000869)  
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
<td style="border:1px solid black;" colspan="7">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-056**](https://go.microsoft.com/fwlink/?linkid=513092)

</td>
<td style="border:1px solid black;">
[**MS14-057**](https://go.microsoft.com/fwlink/?linkid=513095)

</td>
<td style="border:1px solid black;">
[**MS14-058**](https://go.microsoft.com/fwlink/?linkid=513104)

</td>
<td style="border:1px solid black;">
[**MS14-060**](https://go.microsoft.com/fwlink/?linkid=513097)

</td>
<td style="border:1px solid black;">
[**MS14-062**](https://go.microsoft.com/fwlink/?linkid=513107)

</td>
<td style="border:1px solid black;">
[**MS14-063**](https://go.microsoft.com/fwlink/?linkid=513102)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2998579)  
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
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3000061)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2998579)  
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
Microsoft .NET Framework 3.5.1  
(2968294)  
(重要)  
Microsoft .NET Framework 3.5.1  
(2972100)  
(緊急)  
Microsoft .NET Framework 3.5.1  
(2979570)  
(重要)  
Microsoft .NET Framework 4  
(2972106)  
(緊急)  
Microsoft .NET Framework 4  
(2979575)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2972107)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979578)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3000061)  
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
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968295)  
(重要)  
Microsoft .NET Framework 3.5  
(2972101)  
(緊急)  
Microsoft .NET Framework 3.5  
(2979571)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978042)  
(緊急)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2979577)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3000061)  
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
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2968296)  
(重要)  
Microsoft .NET Framework 3.5  
(2972103)  
(緊急)  
Microsoft .NET Framework 3.5  
(2979573)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978041)  
(緊急)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2979576)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3000061)  
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
 
 

### Microsoft 開発者用ツールおよびソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET MVC**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-059**](https://go.microsoft.com/fwlink/?linkid=507673)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 2.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 2.0  
(2993939)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 3.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 3.0  
(2993937)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 4.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 4.0  
(2993928)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 5.0

</td>
<td style="border:1px solid black;">
ASP.NET MVC 5.0  
(2992080)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
ASP.NET MVC 5.1

</td>
<td style="border:1px solid black;">
ASP.NET MVC 5.1  
(2994397)  
(重要)

</td>
</tr>
</table>
 
 

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
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2883031)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(2883032)  
(重要)

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
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)  
(2883008)  
(重要)  
Microsoft Word 2010 Service Pack 1 (32 ビット版)  
(2883013)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2883008)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(2883013)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)  
(2883008)  
(重要)  
Microsoft Word 2010 Service Pack 1 (64 ビット版)  
(2883013)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2883008)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(2883013)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(3004865)  
(重要)

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
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2883031)  
(重要)

</td>
</tr>
</table>
 
**MS14-061 に関する注意**

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
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883098)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Word Automation Services  
(2883098)  
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
[**MS14-061**](https://go.microsoft.com/fwlink/?linkid=513106)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010  
(2889827)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 Service Pack 1  
(2889827)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2010 Service Pack 2  
(2889827)  
(重要)

</td>
</tr>
</table>
 
**MS14-061 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](https://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://go.microsoft.com/fwlink/?linkid=21127)を表します。

**MS14-056**

-   Internet Explorer の特権の昇格の脆弱性 (CVE-2014-4123) を報告してくださった、[Context Information Security](https://www.contextis.com/) の James Forshaw 氏
-   Internet Explorer の特権の昇格の脆弱性 (CVE-2014-4124) を報告してくださった、[Context Information Security](https://www.contextis.com/) の James Forshaw 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4126) を報告してくださった Rohit Mothe 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4127) を報告してくださった、[Palo Alto Networks](https://www.paloaltonetworks.com/) の Bo Qu 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com/) と協力して、Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4128) を報告してくださった Omair 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4128) を報告してくださった Jason Kratzer 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4129) を報告してくださった、[Venustech の ADLab](https://www.venustech.com.cn/)
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4130) を報告してくださった Sky 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4132) を報告してくださった、[Qihoo 360](https://www.360.cn/) の Zhibin Hu 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4132) を報告してくださった、Yenteasy - Security Research の José A. Vázquez 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4133) を報告してくださった、[Qihoo 360](https://www.360.cn/) の Zhibin Hu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4134) を報告してくださった、[Qihoo 360](https://www.360.cn/) の Zhibin Hu 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4137) を報告してくださった、[Qihoo 360](https://www.360.cn/) の Liu Long 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4138) を報告してくださった SkyLined 氏
-   Internet Explorer の ASLR バイパスの脆弱性 (CVE-2014-4140) を報告してくださった John Villamil 氏 (@day6reak)
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2014-4141) を報告してくださった、[Corelan](https://www.corelangcv.com/) の Peter 'corelanc0d3r' Van Eeckhoutte 氏

**MS14-057**

-   .NET ClickOnce の特権の昇格の脆弱性 (CVE-2014-4073) を報告してくださった、[Context Information Security](https://www.contextis.com/) の James Forshaw 氏

**MS14-058**

-   Win32k.sys の特権の昇格の脆弱性 (CVE-2014-4113) についてマイクロソフトに協力してくださった [CrowdStrike Intelligence Team](https://www.crowdstrike.com/)
-   Win32k.sys の特権の昇格の脆弱性 (CVE-2014-4113) についてマイクロソフトに協力してくださった [FireEye, Inc.](https://www.fireeye.com/)
-   TrueType フォント解析の特権の昇格の脆弱性 (CVE-2014-4148) についてマイクロソフトに協力してくださった [FireEye, Inc.](https://www.fireeye.com/)

**MS14-060**

-   Windows OLE のリモートでコードが実行される脆弱性 (CVE-2014-4114) を報告してくださった [iSIGHT Partners](https://www.isightpartners.com/)

**MS14-061**

-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Microsoft Word ファイル形式の脆弱性 (CVE-2014-4117) を報告してくださった 3S Labs

**MS14-063**

-   Windows ディスク パーティション ドライバーの特権の昇格の脆弱性 (CVE-2014-4115) を報告してくださった、[Cisco Talos](https://www.sourcefire.com/solutions/research) の Marcin 'Icewall' Noga 氏

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja):Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master)

国ごとのローカルサポート:[Microsoft サポート](https://support.microsoft.com/common/international.aspx)

### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2014/10/15):このセキュリティ情報の概要ページを公開しました。

*Page generated 2014-10-13 14:39Z-07:00.*
