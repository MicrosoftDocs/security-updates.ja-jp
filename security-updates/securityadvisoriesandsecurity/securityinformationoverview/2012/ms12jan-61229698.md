---
TOCTitle: 'MS12-JAN'
Title: 2012 年 1 月のセキュリティ情報
ms:assetid: 'ms12-jan'
ms:contentKeyID: 61229698
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms12-jan(v=Security.10)'
--- Summary

2012 年 1 月のセキュリティ情報
==============================

公開日: 2012年1月11日 | 最終更新日: 2012年1月31日

**バージョン:** 2.1

[](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627277.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)</a>[![](../../images/Dn627277.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)[](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2012 年 1 月公開のセキュリティ情報の一覧です。

2012 年 1 月のセキュリティ情報の公開により、2012 年 1 月 6 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2012 年 11 月 11 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2012 年 1 月 11 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。1 月のセキュリティ情報 Webcast に今すぐご登録ください (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](http://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=227487">MS12-004</a></td>
<td style="border:1px solid black;">Windows Media の脆弱性により、リモートでコードが実行される (2636391) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性で、特別に細工されたメディア ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235999">MS12-001</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、セキュリティ機能のバイパスが起こる (2644615) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。攻撃者がこの脆弱性を悪用した場合、ソフトウェア アプリケーションの SafeSEH セキュリティ機能がバイパスされる可能性があります。次に攻撃者は他の脆弱性を悪用し、構造化例外ハンドラーにより、任意のコードを実行する可能性があります。この脆弱性の悪用に使用されるものは、Microsoft Visual C++ .NET 2003 を使用してコンパイルされたソフトウェア アプリケーションのみです。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=229637">MS12-002</a></td>
<td style="border:1px solid black;">Windows オブジェクト パッケージャーの脆弱性により、リモートでコードが実行される (2603381) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、特別な細工が施された実行可能ファイルと同じネットワーク ディレクトリにある、パッケージ化されたオブジェクトが組み込まれた正当なファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=235400">MS12-003</a></td>
<td style="border:1px solid black;">Windows クライアント/サーバー ランタイム サブシステムの脆弱性により、特権が昇格される (2646524) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows XP、Windows Server 2003、Windows Vista、および Windows Server 2008 について深刻度を「重要」と評価しています。すべてのサポートされているエディションの Windows 7 および Windows Server 2008 R2 は、この脆弱性の影響を受けません。<br />
<br />
これらの脆弱性により、攻撃者が影響を受けるシステムにログオンし、特別に細工されたアプリケーションを実行した場合、特権が昇格される可能性があります。攻撃者は、その後、影響を受けるシステムを完全に制御し、プログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つアカウントの新規作成を行う可能性があります。この脆弱性は、中国語、日本語または韓国語のシステム ロケールで構成されているシステムでのみ悪用される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=230777">MS12-005</a></td>
<td style="border:1px solid black;">Microsoft Windows の脆弱性により、リモートでコードが実行される (2584146) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性では、悪意のある埋め込み ClickOnce アプリケーションを含む特別な細工がされた Microsoft Office ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=232510">MS12-006</a></td>
<td style="border:1px solid black;">SSL/TLS の脆弱性により、情報漏えいが起こる (2643584) <br />
<br />
このセキュリティ更新プログラムは、一般に公開された SSL 3.0 および TLS 1.0 の脆弱性を解決します。この脆弱性はプロトコル自体に影響を及ぼし、Windows オペレーティング システムに特定のものではありません。この脆弱性で、攻撃者が影響を受けるシステムから提供される暗号化された Web トラフィックを傍受した場合、情報漏えいが起こる可能性があります。TLS 1.1、TLS 1.2 および CBC モードを使用しないすべての暗号は影響を受けません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=227561">MS12-007</a></td>
<td style="border:1px solid black;">AntiXSS Library の脆弱性により、 情報漏えいが起こる (2607664) <br />
<br />
このセキュリティ更新プログラムは、1 件の非公開で報告された Microsoft Anti-Cross Site Scripting (AntiXSS) Library の脆弱性を解決します。この脆弱性により、AntiXSS Library のサニタイズ機能を使用している Web サイトに攻撃者が悪意のあるスクリプトを渡すと、情報漏えいが起こる可能性があります。その場合の情報漏えいの影響は、情報の性質自体により異なります。攻撃者は、この脆弱性により、直接コードを実行したり、ユーザーの権限を昇格させたりすることはできませんが、この脆弱性を悪用して、攻撃に使用する情報を作成し、影響を受けるコンピューターをさらに侵害しようとする可能性があります。AntiXSS Library のサニタイズ モジュールを使用するサイトのみがこの脆弱性の影響を受けます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft 開発者用ツールおよびソフトウェア</td>
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
  
| セキュリティ情報 ID                                       | 脆弱性のタイトル                                                          | CVE の識別番号                                                                   | 最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価               | 旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価       | サービス拒否の悪用可能性の評価 | 注意事項                                                         |  
|-----------------------------------------------------------|---------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|--------------------------------|------------------------------------------------------------------|  
| [MS12-001](http://go.microsoft.com/fwlink/?linkid=235999) | Windows カーネルの SafeSEH バイパスの脆弱性                               | [CVE-2012-0001](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0001) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | これはセキュリティ機能のバイパスの脆弱性です。                   |  
| [MS12-002](http://go.microsoft.com/fwlink/?linkid=229637) | オブジェクト パッケージャーの安全でない実行可能ファイルが実行される脆弱性 | [CVE-2012-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0009) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                           |  
| [MS12-003](http://go.microsoft.com/fwlink/?linkid=235400) | CSRSS の特権の昇格の脆弱性                                                | [CVE-2012-0005](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0005) | 影響なし                                                                              | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 永続的                         | (なし)                                                           |  
| [MS12-004](http://go.microsoft.com/fwlink/?linkid=227487) | MIDI のリモートでコードが実行される脆弱性                                 | [CVE-2012-0003](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0003) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                           |  
| [MS12-004](http://go.microsoft.com/fwlink/?linkid=227487) | DirectShow のリモートでコードが実行される脆弱性                           | [CVE-2012-0004](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0004) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                           |  
| [MS12-005](http://go.microsoft.com/fwlink/?linkid=230777) | アセンブリの実行の脆弱性                                                  | [CVE-2012-0013](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0013) | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | [1](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性   | 対象外                         | (なし)                                                           |  
| [MS12-006](http://go.microsoft.com/fwlink/?linkid=232510) | SSL および TLS プロトコルの脆弱性                                         | [CVE-2011-3389](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3389) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 対象外                         | これは情報の漏えいの脆弱性で、一部詳細が一般に公開されています。 |  
| [MS12-007](http://go.microsoft.com/fwlink/?linkid=227561) | AntiXSS Library バイパスの脆弱性                                          | [CVE-2012-0007](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0007) | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | [3](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 悪用コードの可能性低 | 対象外                         | これは情報漏えいの脆弱性です。                                   |
  
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
<th colspan="7">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-004](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[MS12-001](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[MS12-002](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[MS12-003](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[MS12-005](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[MS12-006](http://go.microsoft.com/fwlink/?linkid=232510)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=a142f7ba-4268-4453-a8eb-470213c028ac)  
(KB2598479)  
(緊急)  
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=89b23d72-410f-4133-9c14-24eb01e5a732)  
(KB2628259)  
(Windows XP Media Center Edition 2005 Service Pack 3 のみ)  
(緊急)  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4b168ee8-eb15-4c2c-afb0-e63d62b4a6dc)  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=feaeda8c-84ee-47be-8c68-736f0e5b1fc7)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cfc38dc2-c4c7-4a44-8e5a-b98bb9bc0396)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1bcb1d1e-9261-4a36-9256-90d3df9bd4fb)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fb0360b1-254c-4ecb-a36a-807cabfec1ab)  
(KB2585542)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0928d720-ae88-40d6-b76f-636d67da8526)  
(KB2598479)  
(緊急)  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=13d74cc6-8d8e-45ea-8cdc-c15782f6626b)  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=46386269-6e37-4710-bfef-cedfe60d881c)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=211827f2-fe6a-4e16-a90c-0cc3b60a722d)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3956db98-88d9-49fc-be51-247b40bfc272)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2c687796-4c41-4d17-b738-511d2fbfc126)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=afe6b34d-21b1-4dfa-afa6-2c5c2a678e9e)  
(KB2585542)  
重要  
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=986f1156-0190-48c2-9f39-29cacb91f0f9)  
(KB2638806)  
重要
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
[MS12-004](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[MS12-001](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[MS12-002](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[MS12-003](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[MS12-005](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[MS12-006](http://go.microsoft.com/fwlink/?linkid=232510)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3c266dfb-630d-4f32-b2ca-63955279b6a9)  
(KB2598479)  
(緊急)  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=89ae6ed0-537f-421c-b755-ef28691abd88)  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9cdfc0fe-8f43-4e13-8a1f-2b48ff9ff472)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b8e46267-7988-4fbe-ae94-68b6fdb2e7d9)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=39f5f8fb-ee4d-4b7a-9cd7-3d1e9c8abd8c)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2c39be84-1eab-4794-b3ed-e529643aca21)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e2c503a5-3f15-4a77-9a05-9ea0fbaf4503)  
(KB2585542)  
重要  
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=c23e7604-d489-4836-8b54-3b2b3d6a365c)  
(KB2638806)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=8dd1c882-4ed1-4e47-a017-7d162bd94194)  
(KB2598479)  
(緊急)  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=08be569c-e9d1-4fc5-8670-ebe9da0a2072)  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4e5783aa-6847-404c-9b75-621fa14ebbb8)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5975b01e-139b-4b9d-a0d5-a87a279bfea1)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e27d85f8-a285-4e95-85a0-0868286cc2b9)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3cf29dfd-239e-4707-92e6-952133c1c1c2)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2ad34496-40af-40cb-9f85-5d3c31543211)  
(KB2585542)  
重要  
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2f36e991-4e1a-4b8c-8cfb-e7f20d97cf0b)  
(KB2638806)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3a9b09d6-7060-47ab-9f76-c3c5acb024e6)  
(KB2598479)  
(緊急)  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3401ac20-3701-471f-9757-097a9402d761)  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=cdf8208c-d55b-428f-bdd3-26e291dfb08d)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=26079c35-4b96-42fc-ad47-138be25a6bf0)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b69bd01d-9925-4ff1-bfeb-b4473631578c)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=623c1c7d-6902-4876-9614-1b6e1ef80831)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=56deb935-9226-49f8-b705-edb3d662d8aa)  
(KB2585542)  
重要  
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2d72cf5a-cca7-4341-b862-017e3f34a3c9)  
(KB2638806)  
重要
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
[MS12-004](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[MS12-001](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[MS12-002](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[MS12-003](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[MS12-005](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[MS12-006](http://go.microsoft.com/fwlink/?linkid=232510)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=99d9b9fc-ed37-4a32-a20d-6604a1b9c4ca)  
(KB2598479)  
(緊急)  
[Windows Media Center TV Pack for Windows Vista (32 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f345e093-336d-4464-b7f8-a14398b62ebf)<sup>[1]</sup>
(KB2628642)  
重要  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4818059a-52ad-4c2e-9605-4e0f5d9da5ba)  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=44eeb0a2-ae17-4971-8a7e-e25b260c582c)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=73682d4b-3179-4488-8ba9-94ed68c4896b)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=038970b6-aeec-4e18-8dfe-887b260a7c87)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f9269bd6-8c4f-476e-8481-fc0de52a22e6)  
(KB2585542)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=44aa8d91-2b30-4191-8965-8aee2b860d50)  
(KB2598479)  
(緊急)  
[Windows Media Center TV Pack for Windows Vista (64 ビット版)](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=559d028f-9810-4c50-b65d-f567cbb15427)<sup>[1]</sup>
(KB2628642)  
重要  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=13cc2519-860d-4c64-b7f8-8f9c0bdaefcf)  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=79ceba86-59a1-4138-a5de-8df20ad81b02)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b5c33025-13d9-43d2-a415-a8a4d683a821)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=23abeb12-f2fe-43fd-9c4a-4d3d244832f8)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0403c753-d4fa-4e3d-a61b-7f816f5c352b)  
(KB2585542)  
重要
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
[MS12-004](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[MS12-001](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[MS12-002](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[MS12-003](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[MS12-005](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[MS12-006](http://go.microsoft.com/fwlink/?linkid=232510)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=787e6285-3ba5-4aae-9d8d-e3c1eca3b35d)\*  
(KB2598479)  
(緊急)  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=92df13c1-fdf6-4602-acb2-e634a1bcd9da)\*\*  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5ab87c6c-5802-4454-bce4-12501e5b816d)\*  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fbf119cf-a8ed-4266-a673-442149992f7c)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d089d9cb-382c-4e64-94c5-69b9864010b1)\*\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2fe2f398-433f-4338-a273-813185b43ea8)\*  
(KB2585542)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=9eff12b2-70a4-452b-b6bc-0d83f2edcf6c)\*  
(KB2598479)  
(緊急)  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7ff10d7f-26a6-403a-a4b7-7aff55e2fa16)\*\*  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=726ff17e-ac90-4832-91e7-46f71ad2f868)\*  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=e8e68f89-27f4-4142-94ca-58f086a98157)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1ac8a368-4298-4c1d-9cfd-924d6df563af)\*\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=f54ac30d-8e41-4df9-bd43-db6742a24d4c)\*  
(KB2585542)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Multimedia Library](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4e2edb23-7f4e-4fe4-848c-1d744e0dce9f)  
(KB2598479)  
(緊急)  
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=5e0394c9-3de4-46f6-ae7f-18d5a555532e)  
(KB2631813)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=ba2c3d57-1bdd-44f2-9233-86c7ea6f0ddb)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fc6491e8-6c3e-43a1-bc56-16c9a2fd2749)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3e08b242-2516-4cf6-b38e-35ec2b8b788d)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=3979db3b-4961-4df8-84a4-1f26672b127c)  
(KB2585542)  
重要
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
[MS12-004](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[MS12-001](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[MS12-002](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[MS12-003](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[MS12-005](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[MS12-006](http://go.microsoft.com/fwlink/?linkid=232510)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d736daf8-db6d-485f-b0cb-7f2d8c86f9a2)  
(KB2631813)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0ee22036-b7f4-40f5-8f40-a77e8faf48b2)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7422605b-7a02-4161-b7f8-92b3ccffef64)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0f433f2c-c61d-461d-af9c-0145af4b72ab)  
(KB2585542)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=21b37775-3e7b-462d-8234-7c47d52daef9)  
(KB2631813)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7444e20c-9821-4c91-9779-2728c537dd6a)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4ba46bc7-af7a-445a-84f2-b0c13674409b)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=0839fec0-b6a7-4e47-9da3-2caef44a7df4)  
(KB2585542)  
重要
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
[MS12-004](http://go.microsoft.com/fwlink/?linkid=227487)
</td>
<td style="border:1px solid black;">
[MS12-001](http://go.microsoft.com/fwlink/?linkid=235999)
</td>
<td style="border:1px solid black;">
[MS12-002](http://go.microsoft.com/fwlink/?linkid=229637)
</td>
<td style="border:1px solid black;">
[MS12-003](http://go.microsoft.com/fwlink/?linkid=235400)
</td>
<td style="border:1px solid black;">
[MS12-005](http://go.microsoft.com/fwlink/?linkid=230777)
</td>
<td style="border:1px solid black;">
[MS12-006](http://go.microsoft.com/fwlink/?linkid=232510)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=355c980d-ec2e-4b2d-a7d4-2e3dbd3a0dde)\*\*  
(KB2631813)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=4c73a16d-e9fa-48de-9dca-a6360ce3d029)\*  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=db3a4814-a409-4def-944d-4eaa540b83b0)\*\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=34542a5a-88df-4a07-b1ed-d4c845502cd8)\*  
(KB2585542)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[DirectShow](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=d4b2389e-fd9f-47c7-9afd-4077f5632c21)  
(KB2631813)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=1cc14ee8-f035-4bfc-bf38-33c6b9a2e776)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=2101663a-ed3d-4850-b79a-16960ab56b45)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=fe661936-06e1-45d3-89f6-1093504496a7)  
(KB2585542)  
重要
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

MS12-004 に関する注意

<sup>[1]</sup>Windows Media Center TV Pack for Windows Vista は Original Equipment Manufacturer (OEM) のインストールの Windows Vista の Home Premium および Ultimate エディションでのみ、オプションのコンポーネントとして利用可能です。このオプション コンポーネントをインストールしているお客様は、ご使用のエディションの Windows Vista 向けに用意されている更新プログラムをすべてインストールする必要があります。最善策として、マイクロソフトは該当するオペレーティング システムの更新プログラム (KB2598479 および KB2631813) をインストールしてから Windows Media Center TV Pack 更新プログラム (KB2628642) をインストールすることを推奨します。

#### Microsoft 開発者用ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Anti-Cross Site Scripting Library
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS12-007](http://go.microsoft.com/fwlink/?linkid=227561)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Anti-Cross Site Scripting Library V3.x および Microsoft Anti-Cross Site Scripting Library V4.0
</td>
<td style="border:1px solid black;">
[Microsoft Anti-Cross Site Scripting Library V3.x および Microsoft Anti-Cross Site Scripting Library V4.0](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=b3ef05ce-70fe-4f25-9aee-cb7a42a53d11)<sup>[1]</sup><sup>[2]</sup>
</td>
</tr>
</table>

<p></p>

 
MS12-007 に関する注意

<sup>[1]</sup> このダウンロードは、Microsoft Anti-Cross Site Scripting (AntiXSS) Library をこの脆弱性の影響を受けない新バージョンの Microsoft Anti-Cross Site Scripting Library にアップグレードします。

<sup>[2]</sup> このアップグレード プログラムは、マイクロソフト ダウンロード センターでのみ利用可能です。

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、Microsoft ダウンロード センターからもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

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

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

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

-   セキュリティ更新プログラムは、Microsoft ダウンロード センターからもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い [謝意](http://technet.microsoft.com/ja-jp/security/bulletin/policy) を表します。

-   MS12-001 で説明している問題を報告してくださった [Accuvant LABS](http://www.accuvant.com/) の Joshua J. Drake 氏
-   [Secunia Research](http://secunia.com/) と協力して、MS12-002 で説明している問題を報告してくださった Parvez Anwar 氏
-   MS12-003 で説明している問題を報告してくださった [Shenzhen Jowto Research Dep](http://www.jowto.com) の Kang Wu 氏
-   MS12-004 で説明している問題を報告してくださった [IBM Security System の X-Force Research](http://xforce.iss.net/) の Shane Garrett 氏
-   MS12-004 で説明している問題を報告してくださった [Google Inc.](http://www.google.com/) の Neel Mehta 氏
-   [Beyond Security の SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html) プログラムに協力して、MS12-005 で説明している問題を報告してくださった Yorick Koster 氏
-   MS12-007 で説明している問題を報告してくださった [IBM Rational Application Security](http://blog.watchfire.com/) の Adi Cohen 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](http://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](http://support.microsoft.com/?ln=ja)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](http://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2012/01/11):このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2012/01/16):MS12-003 について、CVE-2012-0005 の Exploitability Index (悪用可能性指標) に記載されている最新ソフトウェア リリースの悪用可能性の評価を修正しました。MS12-007 について、セキュリティ情報の更新をお知らせしました。詳細については、MS12-007 のセキュリティ情報を参照してください。
-   V2.1 (2012/01/31):MS12-004 について、すべてのサポートされているエディションの Windows XP、Windows Server 2003、Windows Vista および Windows Server 2008 用の KB2631813 の更新プログラム パッケージの総合的な深刻度を修正しました。詳細は MS12-004 を参照してください。

*Built at 2014-04-18T01:50:00Z-07:00*
