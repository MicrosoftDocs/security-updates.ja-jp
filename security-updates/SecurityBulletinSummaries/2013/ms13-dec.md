---
TOCTitle: 'MS13-DEC'
Title: 2013 年 12 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms13-dec'
ms:contentKeyID: 61229708
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms13-dec(v=Security.10)'
---

2013 年 12 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日:2013 年 12 月 11 日

**バージョン:** 1.0

このセキュリティ情報の概要は 2013 年 12 月公開のセキュリティ情報の一覧です。

2013 年 12 月のセキュリティ情報の公開により、2013 年 12 月 6 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2013 年 12 月 11 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[12 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557386&culture=en-us) (英語)。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
<p> </p>
<table style="border:1px solid black;">
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics Component の脆弱性により、リモートでコードが実行される (2908005)</strong><br />
<br />
このセキュリティ更新プログラムは、Microsoft Windows、Microsoft Office、および Microsoft Lync の一般に公開された脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された TIFF ファイルが含まれるコンテンツを表示した場合、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office、<br />
Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (2898785)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 7 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></td>
<td style="border:1px solid black;"><strong>Windows の脆弱性により、リモートでコードが実行される (2893294)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。ユーザーまたはアプリケーションが特別な細工がされた署名付きのポータブルの実行可能 (PE) ファイルを影響を受けるシステム上で実行またはインストールした場合、この脆弱性によりリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></td>
<td style="border:1px solid black;"><strong>Microsoft Scripting Runtime オブジェクト ライブラリの脆弱性により、リモートでコードが実行される (2909158)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、特別な細工がされた Web サイトまたは特別な細工がされたコンテンツをホストする Web サイトをユーザーに訪問させるように攻撃者が誘導した場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server の脆弱性により、リモートでコードが実行される (2915705)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft Exchange Server に存在する 3 件の一般に公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。これらの脆弱性の中で最も深刻なものは、Microsoft Exchange Server の WebReady ドキュメント表示およびデータ損失防止機能に存在します。攻撃者がこれらの脆弱性を悪用し、影響を受ける Exchange Server 上のユーザーに特別な細工がされたファイルを含む電子メール メッセージを送信した場合、LocalService アカウントのセキュリティ コンテキストで、リモートでコードが実行される可能性があります。LocalService アカウントはローカル システムの最小限の権限しか持たないアカウントで、ネットワーク上では匿名の資格情報を提示します。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Server の脆弱性により、リモートでコードが実行される (2904244)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された複数の Microsoft Office サーバー ソフトウェアに存在する脆弱性を解決します。これらの脆弱性により、認証された攻撃者が特別に細工されたページ コンテンツを SharePoint Server に送信した場合にリモートでコードが実行される可能性があります。攻撃者がこれらの脆弱性を悪用した場合、標的となる SharePoint サイト上の W3WP サービス アカウントのセキュリティ コンテキストで任意のコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;"><strong>Windows カーネル モード ドライバーの脆弱性により、特権が昇格される (2880430)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 5 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性でより深刻なものが悪用された場合、攻撃者がユーザーのシステムにログオンして特別な細工が施されたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></td>
<td style="border:1px solid black;"><strong>LRPC クライアントの脆弱性により、特権が昇格される (2898715)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性があると、攻撃者が LRPC サーバーを偽装して、特別に細工した LPC ポート メッセージを LRPC クライアントに送信した場合に、特権の昇格が起こる可能性があります。攻撃者がこの脆弱性を悪用した場合、プログラムのインストール、データの表示、変更、削除、または完全な管理者権限を持つ新たなアカウントの作成が行われる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></td>
<td style="border:1px solid black;"><strong>ASP.NET SignalR の脆弱性により、特権が昇格される (2905244)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の ASP.NET SignalR の脆弱性を解決します。この脆弱性により、攻撃者が特別な細工が施された JavaScript を標的となったユーザーのブラウザーに送信した場合、特権が昇格される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動不要</td>
<td style="border:1px solid black;">マイクロソフト開発者用ツール</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性により、情報の漏えいが起こる (2909976)</strong><br />
<br />
このセキュリティ更新プログラムは、ユーザーが悪意のあるウェブサイト上でホストされる Office ファイルを開こうとすると情報の漏えいが起こる、非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。攻撃者がこの脆弱性の悪用に成功した場合、標的となる SharePoint またはその他の Microsoft Office サーバー サイトで現在のユーザーの認証に使用するアクセス トークンを確認することができます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 共有コンポーネントの脆弱性により、セキュリティ機能のバイパスが起こる<br />
(2905238)</strong><br />
<br />
このセキュリティ更新プログラムは、一般に公開された 1 件の Microsoft Office 共有コンポーネントの脆弱性を解決します。この脆弱性は現在悪用されています。この脆弱性により、COM コンポーネントのインスタンス化機能を持つ Web ブラウザー (Internet Explorer など) で、特別に細工された Web ページを閲覧すると、セキュリティ機能のバイパスが起こる可能性があります。Web 閲覧攻撃シナリオでは、この脆弱性を悪用することに成功した攻撃者は、広い範囲の脆弱性からユーザーを保護する Address Space Layout Randomization (ASLR) セキュリティ機能をバイパスする可能性があります。セキュリティ機能のバイパス自体では、任意のコードが実行されることはありません。しかし、攻撃者はこの ASLR バイパスの脆弱性を、リモートでコードが実行される脆弱性など別の脆弱性と組み合わせて使用し、ASLR バイパスを利用することで、任意のコードを実行する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
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
  
<p> </p>
<table style="width:100%;">
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
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344108">MS13-096</a></td>
<td style="border:1px solid black;">Microsoft Graphics コンポーネントのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3906">CVE-2013-3906</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。<br />
<br />
マイクロソフトは、Microsoft Office 製品でこの脆弱性を悪用しようとする標的型攻撃を確認しています。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5045">CVE-2013-5045</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5046">CVE-2013-5046</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5047">CVE-2013-5047</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5048">CVE-2013-5048</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5049">CVE-2013-5049</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5051">CVE-2013-5051</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344111">MS13-097</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5052">CVE-2013-5052</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325389">MS13-098</a></td>
<td style="border:1px solid black;">WinVerifyTrust Signature Validation の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3900">CVE-2013-3900</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">マイクロソフトはこの脆弱性を悪用しようとする標的型攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344112">MS13-099</a></td>
<td style="border:1px solid black;">Microsoft Scripting Runtime オブジェクト ライブラリの解放後使用 (Use-After-Free) の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5056">CVE-2013-5056</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329771">MS13-100</a></td>
<td style="border:1px solid black;">SharePoint ページ コンテンツの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5059">CVE-2013-5059</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3899">CVE-2013-3899</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k の解放後使用の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3902">CVE-2013-3902</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">TrueType フォントの解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3903">CVE-2013-3903</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Port-Class ドライバーのダブル フェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3907">CVE-2013-3907</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=325387">MS13-101</a></td>
<td style="border:1px solid black;">Win32k の整数オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5058">CVE-2013-5058</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=344110">MS13-102</a></td>
<td style="border:1px solid black;">LRPC クライアントのバッファー オーバーランの脆弱性 </td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3878">CVE-2013-3878</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329969">MS13-103</a></td>
<td style="border:1px solid black;">SignalR XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5042">CVE-2013-5042</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=330934">MS13-104</a></td>
<td style="border:1px solid black;">トークンのハイジャックの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5054">CVE-2013-5054</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃を確認しました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">MAC 無効の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1330">CVE-2013-1330</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般で公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">Oracle Outside In の悪用される恐れのある複数の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5763">CVE-2013-5763</a><br />
<br />
および<br />
<br />
<a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5791">CVE-2013-5791</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これらの脆弱性が一般に公開されていました。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329830">MS13-105</a></td>
<td style="border:1px solid black;">OWA XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5072">CVE-2013-5072</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=329967">MS13-106</a></td>
<td style="border:1px solid black;">HXDS ASLR の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-5057">CVE-2013-5057</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。<br />
<br />
この脆弱性は一般で公開されていました。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃を確認しました。</td>
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

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows XP**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows XP Service Pack 3

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(緊急)  
Internet Explorer 7   
(2898785)  
(緊急)  
Internet Explorer 8   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.7  
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2898715)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(緊急)  
Internet Explorer 7   
(2898785)  
(緊急)  
Internet Explorer 8   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.6  
(2892076)  
(緊急)  
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2898715)  
(重要)

</td>
</tr>
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(警告)  
Internet Explorer 7  
(2898785)  
(重要)  
Internet Explorer 8  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(緊急)  
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2898715)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(警告)  
Internet Explorer 7  
(2898785)  
(重要)  
Internet Explorer 8  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(緊急)  
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2898715)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2898785)  
(警告)  
Internet Explorer 7  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.6   
(2892076)  
(緊急)  
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2893984)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2898715)  
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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
Windows Vista Service Pack 2  
(2901674)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(緊急)  
Internet Explorer 8  
(2898785)  
(緊急)  
Internet Explorer 9   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2893984)  
(警告)  
Windows Vista Service Pack 2  
(2887069)  
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
Windows Vista x64 Edition Service Pack 2  
(2901674)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(緊急)  
Internet Explorer 8  
(2898785)  
(緊急)  
Internet Explorer 9   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2893984)  
(警告)  
Windows Vista x64 Edition Service Pack 2  
(2887069)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2901674)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(重要)  
Internet Explorer 8  
(2898785)  
(重要)  
Internet Explorer 9   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2893984)  
(警告)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2887069)  
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
Windows Server 2008 for x64-based Systems Service Pack 2  
(2901674)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(重要)  
Internet Explorer 8  
(2898785)  
(重要)  
Internet Explorer 9   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2893984)  
(警告)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(2887069)  
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
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2901674)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2893984)  
(警告)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2887069)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(緊急)  
Internet Explorer 9   
(2898785)  
(緊急)  
Internet Explorer 10   
(2898785)  
(緊急)  
Internet Explorer 11   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2893984)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1  
(2887069)  
(重要)

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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(緊急)  
Internet Explorer 9   
(2898785)  
(緊急)  
Internet Explorer 10   
(2898785)  
(緊急)  
Internet Explorer 11   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2893984)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1  
(2887069)  
(重要)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(重要)  
Internet Explorer 9   
(2898785)  
(重要)  
Internet Explorer 10   
(2898785)  
(重要)  
Internet Explorer 11   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2893984)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2887069)  
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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2893984)  
(重要)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2887069)  
(重要)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2893984)  
(警告)  
Windows 8 for 32-bit Systems  
(2887069)  
(重要)

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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2893984)  
(警告)  
Windows 8 for x64-based Systems  
(2887069)  
(重要)

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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2893984)  
(警告)

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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2893984)  
(警告)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2893984)  
(警告)  
Windows Server 2012  
(2887069)  
(重要)

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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2893984)  
(警告)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(2893984)  
(警告)  
Windows RT  
(2887069)  
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
対象外

</td>
<td style="border:1px solid black;">
Internet Explorer 11   
(2898785)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2893984)  
(警告)

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
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-097**](https://go.microsoft.com/fwlink/?linkid=344111)

</td>
<td style="border:1px solid black;">
[**MS13-098**](https://go.microsoft.com/fwlink/?linkid=325389)

</td>
<td style="border:1px solid black;">
[**MS13-099**](https://go.microsoft.com/fwlink/?linkid=344112)

</td>
<td style="border:1px solid black;">
[**MS13-101**](https://go.microsoft.com/fwlink/?linkid=325387)

</td>
<td style="border:1px solid black;">
[**MS13-102**](https://go.microsoft.com/fwlink/?linkid=344110)

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
**なし**

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2901674)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2893984)  
(警告)

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
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2901674)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.7   
(2892075)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2893984)  
(警告)

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
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2893984)  
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
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2893984)  
(警告)

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
(2893294)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Script 5.8   
(2892074)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2893984)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
**MS13-096 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft Office スイートおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

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
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3 (2850047)  
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
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

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
**なし**

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
(2817641)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2850022)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

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
**なし**

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
(2817670)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)  
(2850016)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2817670)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(2850016)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)  
(2817670)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)  
(2850016)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2817670)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(2850016)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (32 ビット版)  
(2850064)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)  
(2850064)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT  
(2850064)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**その他の Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

</td>
<td style="border:1px solid black;">
[**MS13-104**](https://go.microsoft.com/fwlink/?linkid=330934)

</td>
<td style="border:1px solid black;">
[**MS13-106**](https://go.microsoft.com/fwlink/?linkid=329967)

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
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2817641)  
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
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2850047)  
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
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2817641)  
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
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 1  
(2817670)  
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
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft PowerPoint 2010 Viewer Service Pack 2  
(2817670)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
**MS13-096 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft サーバー ソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
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
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 (coreserverloc)  
(2850058)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 3  
(2903911)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 2  
(2903903)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2010 Service Pack 3  
(2905616)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
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
[**MS13-105**](https://go.microsoft.com/fwlink/?linkid=329830)

</td>
<td style="border:1px solid black;">
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 2

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 2  
(2880833)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 3

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 3  
(2880833)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
**MS13-100 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft Office Services および Web Apps

 
<p> </p>
<table style="border:1px solid black;">
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
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
Microsoft Business Productivity Servers  
(2553298)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2553298)  
(重要)

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
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
Microsoft SharePoint Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Business Productivity Servers  
(2837629)  
(重要)  
Excel Services  
(2837631)  
(重要)

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
[**MS13-100**](https://go.microsoft.com/fwlink/?linkid=329771)

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
Microsoft Office Web Apps 2013

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2910228)  
(重要)

</td>
</tr>
</table>
 
**MS13-100 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft コミュニケーション プラットフォームおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

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
Microsoft Lync 2010 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)  
(2899397)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)  
(2899397)  
(重要)

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
(2899393)  
(重要)

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
(2899395)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-096**](https://go.microsoft.com/fwlink/?linkid=344108)

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
Microsoft Lync 2013 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (32 ビット)  
(2850057)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (32 ビット)  
(2850057)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 (64 ビット)  
(2850057)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013  
(64 ビット)  
(2850057)  
(重要)

</td>
</tr>
</table>
 
**MS13-096 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

### Microsoft 開発者用ツールおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**ASP.NET**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-103**](https://go.microsoft.com/fwlink/?linkid=329969)

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
ASP.NET SignalR

</td>
<td style="border:1px solid black;">
ASP.NET SignalR 1.1.x   
(2903919)  
(重要)  
ASP.NET SignalR 2.0.x   
(2903919)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Visual Studio Team Foundation Server**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS13-103**](https://go.microsoft.com/fwlink/?linkid=329969)

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
Microsoft Visual Studio Team Foundation Server 2013

</td>
<td style="border:1px solid black;">
Microsoft Visual Studio Team Foundation Server 2013   
(2903566)  
(重要)

</td>
</tr>
</table>
 
 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

-   Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。
-   Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。
-   Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](https://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://go.microsoft.com/fwlink/?linkid=21127)を表します。

**MS13-096**

-   Microsoft Graphics コンポーネントのメモリ破損の脆弱性 (CVE-2013-3906) を報告してくださった McAfee Labs IPS Team の Haifei Li 氏

**MS13-097**

-   Internet Explorer の特権の昇格の脆弱性 (CVE-2013-5045) を報告してくださった Context Information Security の James Forshaw 氏
-   Internet Explorer の特権の昇格の脆弱性 (CVE-2013-5046) を報告してくださった Context Information Security の James Forshaw 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-5047) を報告してくださった [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) の Abdul-Aziz Hariri 氏
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-5048) を報告してくださった匿名のリサーチャー
-   [HP](https://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-5049) を報告してくださった Jose Antonio Vazquez Gonzalez 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-5051) を報告してくださった、[OUSPG](https://www.ee.oulu.fi/research/ouspg/) の Atte Kettunen 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-5052) を報告してくださった [Palo Alto Networks](https://www.paloaltonetworks.com/) の Bo Qu 氏
-   このセキュリティ情報に組み込まれている Internet Explorer XSS Filter の多層防御を変更するため、マイクロソフトと協力してくださった Alex Inführ 氏

**MS13-098**

-   WinVerifyTrust Signature Validation の脆弱性 (CVE-2013-3900) を報告してくださった [Kingsoft Internet Security Software Co. Ltd](https://www.ijinshan.com/) の Kingsoft インターネット セキュリティ センター

**MS13-101**

-   Win32k のメモリ破損の脆弱性 (CVE-2013-3899) を報告してくださった [Qihoo](https://www.360.cn/) の Renguang Yuan 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com/) に協力して、Win32k のメモリ破損の脆弱性 (CVE-2013-3899) を報告してくださった匿名のリサーチャー
-   TrueType フォントの解析の脆弱性 (CVE-2013-3903) を報告してくださった [F13 Laboratory](https://www.f13-labs.net/) の Ling Chuan Lee 氏
-   Win32k の整数オーバーフローの脆弱性 (CVE-2013-5058) を報告してくださった [Core Security Technologies](https://www.coresecurity.com/) の Nicolas Economou 氏

**MS13-102**

-   LRPC クライアントのバッファー オーバーランの脆弱性 (CVE-2013-3878) を報告してくださった [Qihoo](https://www.360.cn/) の Renguang Yuan 氏

**MS13-104**

-   トークンのハイジャックの脆弱性について報告してくださった、[Adallom](https://www.adallom.com/) の Noam Liran 氏 (CVE-2013-5054)

**MS13-105**

-   OWA XSS の脆弱性 (CVE-2013-5072) を報告してくださった [Minded Security](https://www.mindedsecurity.com/) ([Criteo](https://www.criteo.com/) 代理)

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

-   V1.0 (2013/12/11):このセキュリティ情報の概要ページを公開しました。

 

*Page generated 2014-05-09 17:27Z-07:00.*
