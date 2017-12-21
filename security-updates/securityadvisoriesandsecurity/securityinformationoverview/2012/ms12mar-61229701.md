---
TOCTitle: 'MS12-MAR'
Title: 2012 年 3 月のセキュリティ情報
ms:assetid: 'ms12-mar'
ms:contentKeyID: 61229701
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms12-mar(v=Security.10)'
--- Summary

2012 年 3 月のセキュリティ情報
==============================

公開日: 2012年3月14日

**バージョン:** 1.0

[](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627281.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627281.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)[](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2012 年 3 月公開のセキュリティ情報の一覧です。

2012 年 3 月のセキュリティ情報の公開により、2012 年 3 月 9 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2012 年 3 月 14 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2012 年 3 月 14 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[3 月のセキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499508) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">リモート デスクトップの脆弱性により、リモートでコードが実行される (2671387) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件のリモート デスクトップ プロトコルの脆弱性を解決します。これらのうちより深刻な脆弱性で、攻撃者が影響を受けるコンピューターに特別に細工された一連の RDP パケットを送信した場合、リモートでコードが実行される可能性があります。既定では、リモート デスクトップ プロトコル (RDP) はどの Windows オペレーティング システムでも有効になっていません。RDP が有効となっていないコンピューターは危険にさらされません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235401">MS12-017</a></td>
<td style="border:1px solid black;">DNS サーバーの脆弱性により、サービス拒否が起こる (2647170) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、リモートの認証されていない攻撃者が特別な細工がされた DNS クエリをターゲット DNS サーバーに送信した場合に、サービス拒否の状態が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235364">MS12-018</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (2641653) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235362">MS12-021</a></td>
<td style="border:1px solid black;">Visual Studio の脆弱性により、特権が昇格される (2651019) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Visual Studio に存在する 1 件の脆弱性を解決します。この脆弱性により、Visual Studio が使用するパスに攻撃者が特別に細工したアドインを配置し、より高い特権を持つユーザーに Visual Studio を起動させた場合、特権の昇格が起こる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーが、この脆弱性を悪用することはないと思われます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Visual Studio</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235361">MS12-022</a></td>
<td style="border:1px solid black;">Expression Design の脆弱性により、リモートでコードが実行される (2651018) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft Expression Design に存在する 1 件の脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたダイナミック リンク ライブラリ (DLL) ファイルと同じネットワーク ディレクトリにある正当なファイル (.xpr ファイルや .DESIGN ファイルなど) を開いた場合、リモートでコードが実行される可能性があります。正当なファイルを開いている間に Microsoft Expression Design が DLL ファイルをロードし、それに含まれている任意のコードを実行しようとする可能性があります。攻撃は、ユーザーが信頼されないリモート ファイル システムの場所または WebDAV 共有を訪問して、この場所から影響を受けるアプリケーションでロードされる正当なファイル (.xpr ファイルや .DESIGN ファイルなど) を開いた場合に実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Expression Design</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=239573">MS12-019</a></td>
<td style="border:1px solid black;">DirectWrite の脆弱性により、サービス拒否が起こる (2665364) <br />
<br />
このセキュリティ更新プログラムは、1 件の Windows DirectWrite に存在する一般に公開された脆弱性を解決します。Instant Messenger ベースの攻撃シナリオでは、攻撃者が特別に細工された Unicode 文字のシーケンスを Instant Messanger クライアントへ直接送信すると、この脆弱性によりサービス拒否が起きる場合があります。特別に細工された Unicode 文字のシーケンスを DirectWrite がレンダリングすると、ターゲット アプリケーションが応答しなくなることがあります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">警告</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235401">MS12-017</a></td>
<td style="border:1px solid black;">DNS のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0006">CVE-2012-0006</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235364">MS12-018</a></td>
<td style="border:1px solid black;">PostMessage 機能の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0157">CVE-2012-0157</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">リモート デスクトップ プロトコルの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0002">CVE-2012-0002</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは承認を必要としないリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232664">MS12-020</a></td>
<td style="border:1px solid black;">ターミナル サーバーのサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0152">CVE-2012-0152</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。<br />
<br />
サービス拒否の影響を受けるのは最新のバージョンのみです。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235362">MS12-021</a></td>
<td style="border:1px solid black;">Visual Studio のアドインの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0008">CVE-2012-0008</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235361">MS12-022</a></td>
<td style="border:1px solid black;">Expression Design の安全でないライブラリのロードの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0016">CVE-2012-0016</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 悪用コードの可能性</td>
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
<th colspan="5">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=18a1fe48-1318-4b93-afad-206950bb1ae5)  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2922411c-9755-461b-9904-f6940322af19)  
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
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eccf865d-399a-4862-b26f-f35580419875)  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e72b6b1f-68f5-4e1a-878e-290a5f03ca30)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
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
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b69b4b9b-c0a1-4c1e-b081-8529eaf1536a)  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b04da098-666f-4760-90da-d2a17e78bf47)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=599e5db1-3bf1-4d44-bc7c-81bc545c58ec)  
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
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8081e67f-288c-4714-bff8-e0ff9777692f)  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=647eaf09-3959-439e-8418-fd25221eb6b9)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=482c2890-8d4c-4e13-820f-d5ff256b6a3a)  
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
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=521baa02-5d7a-4cba-8a1a-2af1b6e4cbe4)  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=92f3af60-9a9b-4419-9e95-55f5cb54cf00)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ccd0f116-73c2-4471-a6d9-e07d1dbdd406)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=39abdf7b-ea9d-4b95-a28d-4140374d531d)  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f4e73a92-583b-4352-b19d-7a8e3ef162b7)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7da5b341-6a6f-46de-8d01-448da38e9908)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e5970daf-4440-42fa-8efc-e6190c6a22aa)  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ead9d29b-becf-448e-bff4-d5bb12d02c64)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1ba25d9c-0fef-471f-8e30-045fe9586a9c)  
(警告)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fef2c1d7-2004-43d7-aa49-673c6f374670)\*  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=233c62b7-f2b1-49ce-9a7f-e51435be0d26)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dd547364-f6bb-453c-9e4d-6b80dfc47fbb)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=45a4784e-5051-4628-9a19-d53f30c1fdf3)\*\*  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ffae13f-3432-4849-a2da-a76f96d7ceb3)\*  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=56eae770-5990-4e1b-8b48-3d0602fcc72b)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5ff65fc2-5969-4d7e-9c72-9a2096dafdcf)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=503cb9c0-d6db-4deb-a555-67af0b25739b)\*\*  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=67581250-50fd-4f4c-a3cc-45ce2662b0c3)  
(KB2621440)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=eeb5385c-fb81-4d33-af2a-986e6cf14ee2)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="5">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=16b0195c-84d3-4c08-8b98-ff2c80d144e1)  
(KB2621440)  
(緊急)  
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3a6c7fdf-105a-4886-ad52-c892f37e32d1)  
(KB2667402)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=75fd93ff-5be5-42b5-ab00-3378e545c271)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f3a14012-38ae-490e-a48e-7c851f82a7e6)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=40b62d08-d2a2-4900-b01c-46fc761973d0)  
(KB2621440)  
(緊急)  
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1bbe7cda-4bee-4d65-8127-3c13624a1168)  
(KB2667402)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=71ffba4c-d816-45a9-abef-131915885bc8)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=760b5aa4-4e65-4ff1-9ae2-771234803bf0)  
(警告)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-020](http://go.microsoft.com/fwlink/?linkid=232664)
</td>
<td style="border:1px solid black;">
[MS12-017](http://go.microsoft.com/fwlink/?linkid=235401)
</td>
<td style="border:1px solid black;">
[MS12-018](http://go.microsoft.com/fwlink/?linkid=235364)
</td>
<td style="border:1px solid black;">
[MS12-019](http://go.microsoft.com/fwlink/?linkid=239573)
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
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7c1774cc-e00c-47f3-97a2-bc90de857793)\*  
(KB2621440)  
(緊急)  
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7ec21f41-1673-4592-b45c-6438ad57e08c)\*  
(KB2667402)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=19a4f3d1-24d2-41af-a41a-e5cc2c6232e8)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=22d6a234-6447-4854-8119-4fddd3c6e1bb)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=86095b20-5869-4b55-8777-ee0af82aaf37)\*\*  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=6a07f99c-8ab4-4e44-8d48-6ac787dd2b51)  
(KB2621440)  
(緊急)  
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=469aa1f6-ed89-4649-8736-eaa5e2ad44ee)  
(KB2667402)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cb5ac981-e8e5-4df7-84bb-7a2a916d0ce9)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=dc5c336f-329c-4a56-8b24-555e3c8afd50)  
(警告)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p></p>

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
[MS12-021](http://go.microsoft.com/fwlink/?linkid=235362)
</td>
<td style="border:1px solid black;">
[MS12-022](http://go.microsoft.com/fwlink/?linkid=235361)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=99d7c39a-14f1-4e7e-8a4f-2466b16821eb)  
(KB2669970)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f80235ae-da15-4527-93b3-c2f31ec2f387)  
(KB2644980)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010 Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e2aaec35-b2c0-48f0-8a51-34e44f6d12fb)  
(KB2645410)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Expression Design
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-021](http://go.microsoft.com/fwlink/?linkid=235362)
</td>
<td style="border:1px solid black;">
[MS12-022](http://go.microsoft.com/fwlink/?linkid=235361)
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
Microsoft Expression Design
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=49e12f3a-718d-4d54-82be-b78efb372d07)  
(KB2675064)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Design Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=899c6860-6081-429b-971a-4d689444920f)  
(KB2667724)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2ca4fb5a-3ab4-410b-b42b-075eb1d70410)  
(KB2667725)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Design 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73b44e97-6dda-4e24-9758-e86a1de4c0c8)  
(KB2667727)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Expression Design 4
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Expression Design 4](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=be56221e-4271-42dc-a6e4-ebf0290e4ad8)  
(KB2667730)  
(重要)
</td>
</tr>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

System Center Configuration Manager 2007

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](http://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。Configuration Manager の詳細については、[System Center Configuration Manager](http://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d-) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/ja-jp/security/bulletin/policy)を表します。

-   MS12-018 で説明している問題を報告してくだささった [Nikolaos Bougalis](https://technet.microsoft.com/ja-JP/mailto:nikb@bougalis.net) 氏
-   MS12-019 で説明している問題を報告してくださった Khaled M. Salameh 氏
-   MS12-020 で説明している問題を報告してくださった [TippingPoint](http://www.tippingpoint.com/) の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している Luigi Auriemma 氏
-   MS12-021 で説明している問題を報告してくださった [Laplinker](http://www.laplinker.com) 氏
-   MS12-022 で説明している問題を報告してくださった [Laplinker](http://www.laplinker.com) 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](http://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/?ln=ja)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2012/03/14): このセキュリティ情報の概要ページを公開しました。

*Built at 2014-04-18T01:50:00Z-07:00*
