---
TOCTitle: 'Microsoft Baseline Security Analyzer (MBSA) Version 1.2.1 Q&A'
Title: 'Microsoft Baseline Security Analyzer (MBSA) Version 1.2.1 Q&A'
ms:assetid: '4ff09cdb-ecda-4ec6-a620-115bc41476a6'
ms:contentKeyID: 19869103
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd229318(v=MSDN.10)'
---

Microsoft Baseline Security Analyzer (MBSA) Version 1.2.1 Q&A
=============================================================

公開日: 2004年1月20日 | 最終更新日: 2006年7月3日

|     |
|-----|
|     |

<showratings></showratings>
マイクロソフトのセキュリティに対する継続的なコミットメントおよび企業のセキュリティのコンプライアンスに役立てるために、マイクロソフトは 2005 年 7 月にマイクロソフト製品に対する無償のスタンドアロンのセキュリティ更新プログラムのスキャン ツールとして MBSA 2.0 をリリースしました。

マイクロソフトの更新プログラムおよび Windows Server Update Services (WSUS) テクノロジーに基づき、MBSA 2.0 お客様に Microsoft Update および WSUS と調和している信頼できるセキュリティと、64-bit および XP が組み込まれたオペレーティング システムのサポートおよび新たなマイクロソフト製品がリリースされた際に動的なサポートが提供されます。サポートされている最新の製品 ([こちら （英語）](https://technet.microsoft.com/ja-jp/library/cc708427)をご覧ください) の WSUS のベースラインを満たしているお客様は、その環境ですでに MBSA 2.0 をご使用されているはずです。

MBSA 2.0、Microsoft Update および WSUSでサポートされていない旧式の製品をご使用になっているお客様に対して、マイクロソフトは将来的にリリースされる予定の旧式用の新たなサポート ツールを提供するためにパートナーと協力しています。MBSA のスキャン ツールのように、この新たな旧式用のスキャン ツールはお客様に無償で提供されます。

WSUS でサポートされていない製品をご使用になる予定のお客様に対しては、マイクロソフトはこの旧式用の新しいツールがリリースされるまで、包括的なセキュリティ更新プログラムを入手するために [Enterprise Scan Tool](http://support.microsoft.com/default.aspx?id=894193) に組み込まれた以前のバージョンの MBSA 1.2.1 のツールをご利用になることを推奨します。

お客様が十分なテストおよび緩和のための時間を確保するために、旧式用のセキュリティ更新プログラムのツールがご利用可能になった後 6 ヵ月間、マイクロソフトは引き続き、旧式のセキュリティ更新プログラムの検出のための MBSA 1.2.1 のツールのサポートを行ないます。

この新たな旧式用のスキャン ツールのリリースは、2007 年の第一四半期に予定されています。

------------------------------------------------------------------------

<expandcollapseall title="すべての回答を参照する"></expandcollapseall>

 

MBSA は NT を引き続きサポートしますか？
---------------------------------------

マイクロソフトは 2004 年 12 月 31 日に Windows NT のサポートを終了しました。しかし、MBSA 1.2.x の NT のプラットフォームでセキュリティ更新プログラムを検出するための機能は削除されていません。リリースされている Windows NT 用の更新プログラムは mssecure.xml ファイルから削除されていません。さらに、MBSA 1.2.x は引き続き IIS 4.0、 SQL および NT のセキュリティの誤構成をサポート以外の方法で、スキャンします。

MBSA 1.2.1 で Windows Server 2003 SP1 をスキャンできますか？
------------------------------------------------------------

はい。 MBSA 1.2.1 は、 Windows Server 2003 SP1 のスキャンが可能です。しかし、Windows ファイアウォールの検査結果として 「Windows ファイアウォールのテストは、エラーにより実行されません。(0x800706d9)」が表示される場合があります。 これは、Windows Server 2003 SP1 の既定では、Windows ファイアウォールが動作していないためです。 Windows ファイアウォールのサービス (Windows Firewall/Internet Connection Sharing (ICS)) を動作させることでスキャン可能です。 Windows ファイアウォールを有効にする際には、既存のネットワークサービスが適切に提供できることを確認し、適切な例外設定を行った後に有効にしてください。

MBSA の検出カタログ (mssecure.xml) がマイクロソフト以外のツールで使用することに何か制限はありますか?
----------------------------------------------------------------------------------------------------

はい。次の制限が MBSA の検出カタログにあります。
ファイル内のデータは、マイクロソフトの知的所有権を示し、マイクロソフトが著作 権を所有しています。いかなる方法によるデータの変更も、不足している更新の検出が不正確に、または矛盾した検出の原因となる可能性があります。ファイル スキーマの変更は、マイクロソフトにより随時行われる場合があります。検出カタログのデータもまた、外部のソースとともに、各更新プログラムのサポート技 術情報およびセキュリティ情報から取得される場合もあります。技術上の理由により、特定のセキュリティ情報のファイルから、データが省略される場合があり ます。どのデータがファイルに存在するか、または存在しないかは、MBSA 更新プログラム検出外で意味を持つと解釈されるべきではありません。ファイル内の情報は、マイクロソフトのセキュリティ更新プログラム/セキュリティ情報 のみについて、ダウンロード センターのリリースされたパッケージに基づきます。また、修正プログラムのように、カタログに追加されたファイルの詳細を持たない、より新しいセキュリ ティ以外の更新があることが一般的です。

MBSA 以外でのカタログ (mssecure.xml) の使用はサポートされていません。さらに、エラーまたは XML ファイル内で不足するデータは、MBSA によりサポートされているシナリオに影響を及ぼす場合のみ、修正されます。プロダクト サポートは技術的な質問にはお答えできませんが、ケースバイケースの原則で、商業的に合理的な範囲 (最善を尽くして) で支援を提供します。ファイル自体を別のマイクロソフト以外の製品に再配布することはできません。マイクロソフトの著作権を侵害することとは別に、ファイ ルが古くなり、定期的に更新されない場合、コンピュータは古い情報を使用してスキャンされる可能性があり、重要なセキュリティ更新プログラムは検出されま せん。MBSA は使用されるごとに、このファイルの最新バージョンを自動的にダウンロードするよう設計されています。検出カタログと同様、MBSA 自体を、そのほかのマイクロソフト以外の製品に再配布または統合することはできません。

HFNetchk および MBSA 1.1.1 以前用の XMLDB の更新の更新がされていないようですが、どうしてですか?
-----------------------------------------------------------------------------------------------

HFNetchk および、MBSA 1.1.1 以前用の XMLDB の更新 は、 2004 年 7 月 14 日をもって終了いしました。[MBSA 1.2. への移行](http://www.microsoft.com/japan/technet/security/tools/mbsahomej.mspx#xsltsection126121120120)をご覧頂き、最新の MBSA をご利用下さい。

MBSA のどのバージョンがサポートされますか?
------------------------------------------

MBSA 1.2.1 および 2.0 です。スタンドアロンの MBSA 1.2.1 のライフサイクルについては、[こちら](http://www.microsoft.com/japan/technet/security/tools/mbsahome.mspx)をご覧ください。

MBSA Version 1.2 および 1.2.1 ではどのようなオペレーティングシステムがサポートされていますか?
---------------------------------------------------------------------------------------------

MBSA は Microsoft Windows 2000 Server、Windows 2000 Professional、Windows XP Home Edition、Windows XP Professional、Windows Server 2003 を実行しているコンピュータにインストールし、実行することができます。MBSA は、Microsoft Windows NT 4.0 Server および Windows NT 4.0 Workstation、Windows 2000 Server、Windows 2000 Professional、Windows XP Professional、および Windows Server 2003 に対し、ネットワーク上でスキャンすることができます。Windows NT 4.0 を実行しているコンピュータ上では、mbsacli.exe /hfからMBSA を実行する際に、ローカルでスキャンを行うことができます。Windows 95、98 または Me などのシステム上での実行、または、それらのシステムに対してスキャンはできません。

**新しいバージョンであるMBSA 1.2.1はWindows XP Service Pack 2との互換性のために必要です**。Windows XP Service Pack 2 のユーザーは Service Pack 2 のセキュリティ強化機能との互換性のため、MBSA をバージョン 1.2.1 に更新する必要があります。MBSA 1.2 を実行している Windows XP SP2 ユーザーは、インターネット接続で \[スタート\] メニューからツールを実行する時に、自動的に通知されます。

MBSA はどのようなアプリケーションやプログラムをスキャンしますか?
----------------------------------------------------------------

MBSA V1.2.1 は Windows NT 4.0、Windows 2000、Windows XP、Windows Server 2003、Microsoft Internet Information Services (IIS) 4.0、5.0、5.1 および 6.0、Microsoft Internet Explorer (IE) 5.01 およびそれ以降のバージョン、Microsoft SQL Server 7.0 および 2000、Microsoft Office 2000、XP、および 2003 のセキュリティ上の誤った構成がないかスキャンします。

<table border="1" bordercolor="#CCCCCC" cellpadding="3" cellspacing="0" id="EDE">
<thead>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#CCCCCC" id="colEFE">
**製品**
</td>
<td style="border:1px solid black;" bgcolor="#CCCCCC" id="colEJE">
**MBSA V1.1.1**
</td>
<td style="border:1px solid black;" bgcolor="#CCCCCC" id="colENE">
**MBSA 1.2.1**
</td>
</tr>
</thead>
<tbody>
<tr valign="top">
<td style="border:1px solid black;">
Windows 2000

</td>
<td style="border:1px solid black;">
○

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
Windows XP

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;">
Windows NT 4.0 およびそれ以降のバージョン（リモートスキャンのみ）

</td>
<td style="border:1px solid black;">
○

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
Windows Server 2003

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;">
Internet Explorer 5.01 およびそれ以降のバージョン

</td>
<td style="border:1px solid black;">
○

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
Windows Media Player 6.4 およびそれ以降のバージョン

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;">
IIS 4.0、5.0、5.1 および 6.0

</td>
<td style="border:1px solid black;">
○

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
SQL Server 7.0 および 2000 (Microsoft Data Engine を含む)

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;">
Exchange 5.5 および 2000 (Exchange 管理ツールを含む)

</td>
<td style="border:1px solid black;">
○

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
Exchange Server 2003

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
未対応

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;">
Microsoft Office (ローカルスキャンのみ、[製品リスト](http://office.microsoft.com/assistance/preview.aspx?assetid=ha01088416)を参照ください。)

</td>
<td style="border:1px solid black;">
未対応

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
Microsoft Data Access Components (MDAC) 2.5、2.6、2.7 および 2.8

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
未対応

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;">
Microsoft 仮想マシン

</td>
<td style="border:1px solid black;">
未対応

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
MSXML 2.5、2.6、3.0 および 4.0

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
未対応

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;">
BizTalkR Server 2000、2002 および 2004

</td>
<td style="border:1px solid black;">
未対応

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
Commerce Server 2000 および 2002

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
未対応

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;">
Content Management Server (CMS) 2001 および 2002

</td>
<td style="border:1px solid black;">
未対応

</td>
<td style="border:1px solid black;">
○

</td>
</tr>
<tr valign="top">
<td style="border:1px solid black;" bgcolor="#EEEEEE">
Host Integration Server (HIS) 2000、2004、および SNA Server 4.0

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
未対応

</td>
<td style="border:1px solid black;" bgcolor="#EEEEEE">
○

</td>
</tr>
</tbody>
</table>
 

**注:** インストールされない製品では、MBSA V1.2.1 でスキャンが行われてもセキュリティ修正プログラムのチェックは行われず、セキュリティ修正プログラムのスキャン結果のレポートのテーブルに一覧表示されません。

MBSA では、現在、Front Page Server Extensions および Outlook Express など、上記のリストに記載されていない製品のセキュリティ修正プログラムのチェックは行われません。また、MBSA では、Windows Embedded ファミリーまたは 64-bit 版のコンピュータに対してのインストール、スキャンもサポートされていません。

MBSA V1.2.1 ではどの言語がサポートされていますか?
-------------------------------------------------

MBSA V1.2.1 は、英語、ドイツ語、日本語、フランス語版で利用可能です。mssecure.xml ファイルは、これらの 4 つの言語にローカライズされ、マイクロソフト ダウンロードセンターから利用可能になった場合、ドイツ語、日本語、フランス語のコンピュータで、スキャンを行う際、MBSA により自動的にダウンロードされ、使用することができます。ローカライズ版の mssecure.xml ファイルがダウンロードできない場合、MBSA は、英語版の mssecure.xml ファイルを使用し、セキュリティ修正プログラムのスキャン部分では、チェックサムのチェックを無効にし、英語以外のコンピュータをスキャンします

MBSA セキュリティレポートはどこに保存されますか?
------------------------------------------------

セキュリティ レポートは、既定では、XML ファイルとして %userprofile%\\SecurityScans に保存されます。

スキャン結果でフラグが付けられた更新プログラムをインストールしたにもかかわらず、MBSA で誤ったセキュリティ更新プログラムのレポートが出力されるのはなぜですか?
------------------------------------------------------------------------------------------------------------------------------------------------------------

マイクロソフトが発行するセキュリティ修正プログラムには、ツールでは容易にスキャンできない項目が含まれている場合があります。たとえば、 MS99-041 には、パッチは含まれておらず、ユーザーがシステムの特定のサービスを修正するためのツールが含まれています。このようなタイプのセキュリティ情報を「注 意」または「警告」メッセージと呼びます。既定で、HFNetChk はこれらの「Note」および「Warning」メッセージを表示します。これらのメッセージを抑制するには、-s スイッチを使用する必要があります。MBSA でも、既定では「Note」および「Warning」メッセージが表示されますが、セキュリティ情報に示される修正が適用されているかどうかをツールで確 認できないことを示す青色のアスタリスクでマークされます。ユーザーが特定の「Note」や「Warning」の修正プログラムを適用した後も、これらの ツールのスキャン レポートに同じセキュリティ情報が表示され続けます。「Note」メッセージの詳細については、[サポート技術情報 306460](http://support.microsoft.com/?kbid=306460) を参照してください。

ま た、予測よりも新しいファイル バージョンを持つ場合、そのファイルを含む修正プログラムが表示される可能性があります。（その場合、スキャン レポートに黄色の X がマークされます） これらの警告メッセージは、以前のセキュリティ関連の修正プログラムがコンピュータに適用された後、セキュリティ以外の修正プログラムによってアップデー トされたファイルがある場合に表示します。MBSA V1.2.1 では、代替のファイル バージョンが使用されることにより、このようなケースの多くを解決し、特定のセキュリティ修正プログラムのためにチェックされるファイル詳細の複数のセッ トを有効にします。このファイル詳細のセットは、セキュリティ修正プログラムのファイルおよびセキュリティ以外の修正プログラムのファイルの両方をカバー することができます。

MBSA と Windows Update で結果が異なるのはなぜですか?
----------------------------------------------------

MBSA と Windows Update (以下 WU) は異なる方法でシステムを分析します。たとえば、WU は Windows オペレーティング システムの重要な更新だけを調査します。一方、MBSA は Windows オペレーティング システムや SQL Server などのその他の マイクロソフト 製品についてインストールされていないセキュリティ修正プログラムをレポートします。

たとえば、MS02-008 や MS02-009 のように、セキュリティ修正プログラムが再リリースされる場合もあります。MBSA は、常に、システムに最新バージョンの修正プログラムがインストールされていることを確認します。MS02-008 や MS02-009 の元のバージョンをインストールしていた場合、新しいリリースが入手可能であるため、MBSA は新しいセキュリティ修正プログラムがインストールされていないとレポートします。一方、Windows Update ではシステムの別の要素を調べて修正プログラムの有無を確認するので、新しいバージョンが入手可能であることを示されない場合があります。しばらくの間、 過去にインストールした可能性のあるセキュリティ修正プログラムについて、インストールされていないと MBSA がレポートした場合は、当該のセキュリティ情報を参照の上、最新バージョンをインストールしていることを確認してください。

また、同様の理由で、バージョンが更新されていなくても MBSA と Windows Update で検出結果が異なる場合がございます。その場合は、MBSA の「結果の詳細情報」を参照して、検出された理由を確認してください。

マ イクロソフトはこのようなツール間でのレポート結果の不一致を認識しています。解決し、MBSA、Windows Update、Microsoft Software Update Services、および SMS 2.0 Software Update Services Feature Packで将来的に同じ規則に従って Windows システム上の修正プログラムの有無を調べるようにする作業を続けています。これによって、各顧客がそれぞれのニーズに合った最適なツールで一貫性のある結 果を得ることを目指します。

そのほかのツールがコンピュータに互換性がないと通知する場合でも、なぜ MBSA は互換性があると通知することがあるのですか?
---------------------------------------------------------------------------------------------------------------------

Windows により現在使用されているファイルを置き換える更新プログラムがあります。いくつかのファイルは、Windows の最初の起動時にメモリに読み込まれ、次回の再起動までリロードされません。MBSA はディスク上のファイルをチェックするため、次の再起動まで有効とならなくても、更新プログラムがインストールされたと報告します。このため、使用されたツールに関わらず、マイクロソフトは全体のセキュリティ管理戦略の一部として強力な更新プログラム適用ツールを使用することを推奨します。SMS、 SUS、多くのサード パーティの製品のようなツールは、更新プログラムの再起動の必要性を追跡し、強制します。

MBSA スキャンレポートの評価はどのように解釈すればよいですか?
------------------------------------------------------------

スキャンしたコンピュータ上で脆弱性が発見されたかどうかにより、MBSA は、レポートの評価の欄に様々なアイコンを表示します。システム構成チェックでは、重要なチェックに不合格である場合（セキュリティ修正プログラムが必要、ユーザーが空白のパスワードを使用している場合など） 赤色の X が表示されます。重要でないチェックに不合格となった場合 （アカウントに有効期限のないパスワードが設定されている、など） 黄色の X が表示されます。チェックに合格した場合（その特定のチェックでは問題が発見されなかった場合）、緑色のチェックマークが表示されます。最適な方法のチェック（監査が有効にされている場合など）のチェックには、青色のアスタリスクが表示され、スキャンが行われているコンピュータに関する情報を単に提供するチェック（スキャンを行ったコンピュータのオペレーティング システムのバージョンなど） には、青色の追加情報アイコンが表示されます。

セキュリティ修正プログラムのチェックでは、スキャンをしたコンピュータに必要なセキュリティ修正プログラムが MBSA により確認されない場合、赤色の X が表示されます。警告メッセージ （コンピュータに最新の Service Pack がインストールされていない場合など） には黄色の X が表示されます。また、注意のメッセージ（コンピュータ上にインストールされていると確定できないセキュリティ修正プログラムがある場合など）には、青色のアスタリスクが表示されます。現在、システム構成のチェックで、評価を変更、再度割り当てることができません。しかし、-s オプションを mbsacli.exe /hf および mbsacli.exe で使用し、注意および警告の表示を無効にすることができます。また、(mbsacli.exe /hf で) -fq オプションを使用し、それぞれのセキュリティ修正プログラムがスキャン レポートで表示されるのを無効にすることができます。

IIS のスキャンをしようとすると、「IIS Base Admin COM オブジェクトへの接続が行われませんでした」というエラーメッセージが表示されるのはなぜですか?
------------------------------------------------------------------------------------------------------------------------------------------------

このエラーは、（対象のコンピュータ上で） スキャンが行われている IIS のバージョンが MBSA が実行されているコンピュータよりも新しいバージョンである場合に起こる可能性があります。また、これはスキャンを開始するコンピュータ上に IIS Common Files がインストールされていないことを示します。エラー コード (0x80070005) が返された場合、リモートの IIS のコンピュータによってアクセスが拒否されたことが示されます。これは、IIS を実行しているリモート コンピュータが “net use” にて認証、スキャンされ、この “net use” の接続では、IIS の管理に認証が提供されないため、リモートの IIS コンピュータへの呼び出しが、異常終了し、「アクセスが拒否されました」というメッセージが表示される可能性があります。詳細は、readme.html ファイル （MBSA とともにインストールされます） の「システム要件」の欄、または MBSA ヘルプ ファイル （MBSA の GUI の右側のペインにリンクが表示されます） を参照ください。IIS 6.0 Server をリモートでスキャンする際には、ローカルコンピュータ上に IIS 6.0 Common Files が必要であることにご注意ください。

Windows XP Home Edition で空白のパスワードがチェックされないのはなぜですか?
---------------------------------------------------------------------------

MBSA は、単純なファイル共有を使用する Windows XP コンピュータで、空白のパスワードを設定したローカル ユーザーアカウントをチェックしません。（単純なファイル共有を有効に設定したドメインに追加されていない Windows XP Home Edition および Windows XP Professional を実行するコンピュータを含みます）これらのコンピュータでは、既定で、空白のパスワードが設定されたユーザーアカウントで、ネットワークを利用してリモートのコンピュータにログオン、またはメインの物理コンソールログオンの画面以外でのそのほかのログオンはすべて無効です。

MBSA は Microsoft Personal Security Advisor (MPSA) を置き換えるものですか?
--------------------------------------------------------------------------

はい。MBSA は MPSA を置き換えるものです。MBSA は、以前の Microsoft Personal Security Advisor (MPSA) のすべてのチェックが含まれた、MPSA ツールのスーパーセットです。MBSA では、新しいアプリケーションのチェック (IIS や SQL など) を実行したり、サーバーとワークステーションの両方を、ローカルでも、ネットワーク経由でリモートでもスキャンできます。

MBSA は HFNetChk を置き換えるものですか ?
-----------------------------------------

MBSA Version 1. 2.1 では、MBSA コマンド ライン インターフェイス (mbsacli.exe) によって HFNetChk のすべてのスイッチを利用できます。MBSA コマンド ライン インターフェイスを使用して、mbsacli.exe による MBSA スキャン （システム構成およびセキュリティ修正プログラムの適用状況のチェック） および mbsacli.exe /hf による HFNetChk スキャン （セキュリティ修正プログラムの適用状況のチェックのみ） の両方を実行することができます。

MBSA Version 1.2.1 を使って HFNetChk スタイルのスキャンを実行するにはどのようにしますか?
----------------------------------------------------------------------------------------

スタンドアロンの HFNetChk ツールを使い慣れているユーザーは、MBSA Version 1. 2.1 を使って同じタイプのスキャンを実行できます。MBSA Version 1. 2.1 のコマンド ライン インターフェイスには、HFNetChk スタイルのチェックを指定するフラグ (/hf) が用意されています。ユーザーは、"mbsacli.exe /hf" の /hf フラグの後に有効な HFNetChk のスイッチを指定して実行できます。"hfnetchk.exe" を呼び出すスクリプトを作成していた場合は、これを "mbsacli.exe /hf" に置き換えて、その後に有効な HFNetChk のフラグを指定するだけで済みます。

MBSA が HFNetChk よりも優れている点は何ですか?
----------------------------------------------

MBSA は HFNetChk の機能のスーパーセットです。HFNetChk はセキュリティ修正プログラムとサービスパックのみを処理しますが、MBSA は使いやすいインターフェイスと新しい機能を提供します。新しい機能としては、Windows デスクトップやサーバーで強力なパスワードなど一般的なセキュリティの構成を検査する機能、IIS や SQL Server を実行するサーバーに対してセキュリティの構成の一般的な問題をスキャンする機能、および Microsoft Office、Outlook、Internet Explorer のセキュリティ ゾーンの設定の問題をチェックする機能などがあります。MBSA によって、ユーザーは 2 つの独立したツールではなく、1 つのツールで、適用されていないセキュリティ修正プログラムと、システム設定の構成の問題をスキャンすることができます

プロキシサーバーで認証が必要な場合に、スキャンを実行するために必要なファイルをダウンロードするにはどうすればよいですか?
-----------------------------------------------------------------------------------------------------------------------

マイクロソフト Web サイト [http://go.microsoft.com/fwlink/?LinkId=18922](http://go.microsoft.com/fwlink/?linkid=18922) から、署名付きの英語版の mssecure.cab ファイルを手動でダウンロードし、MBSA V1.2.1 でのセキュリティ修正プログラムのチェックに使用することができます。ダウンロードした CAB ファイルを MBSA のインストール フォルダに配置します。（MBSA V1.1.1 を実行し、この英語版の CAB ファイルをダウンロードし、MBSA インストール フォルダに配置する場合、"mssecure.cab" と名前を付けて保存するかまたは、ダウンロードした後、スキャンの前に "mssecure.cab" に名前を変更する必要があります） CAB ファイルを手動でダウンロードする際、ユーザーは、定期的に再ダウンロードし、マイクロソフトからリリースされている最新の mssecure.cab ファイルがコンピュータのスキャンで使用されることを確認してください。マイクロソフトは、新たなセキュリティ情報を公開または更新した際に、 mssecure ファイルの更新版をリリースします。

mssecure.cab のローカライズ版は、以下のサイトから手動でダウンロードすることができます。

-   ドイツ語版 mssecure.cab ファイル:[http://go.microsoft.com/fwlink/?LinkId=18121](http://go.microsoft.com/fwlink/?linkid=18121)

-   日本語版 mssecure.cab ファイル:[http://go.microsoft.com/fwlink/?LinkId=18120](http://go.microsoft.com/fwlink/?linkid=18120)

-   フランス語版 mssecure.cab ファイル:[http://go.microsoft.com/fwlink/?LinkId=18122](http://go.microsoft.com/fwlink/?linkid=18122)

    これらは、オフラインで使用するために、署名済みの mssecure.cab ファイルをダウンロード可能な唯一のサポートされている場所です。

Microsoft Office 製品の更新プログラムのスキャンは、必要となるファイルをダウンロードするために、多少異なる手順を使用します。

-   <http://go.microsoft.com/fwlink/?linkid=18842> から INVCIF.EXE をダウンロードします。

-   <http://go.microsoft.com/fwlink/?linkid=18452> から INVCM.EXE をダウンロードします。

INVCIF.EXE を実行し、\[はい\] をクリックし、Office 更新インベントリ ツールをインストールして下さい。EULA を読み、その事項に同意し、コンテンツを拡張するためのローカル ディレクトリ (例 : C:\\TEMP) を指定して下さい。これは、CIFS という名前のディレクトリとともに、2 つのファイル (PatchData.XML および InventoryCatalog.HTML) を作成します。PUIDS.CIF という名前のファイルもまた CIFS ディレクトリに抽出されます。これらの 2 つのファイルおよびディレクトリを、スキャンを行っているコンピュータの C:\\Microsoft Baseline Security Analyzer\\OfficeUpd ディレクトリにコピーします。既存のファイルを上書きすることを確認するメッセージが表示されたら、\[はい\] をクリックします。

INVCM.EXE も同様の手順で実行し、作成された3つのファイル（Inventory.exe、Convert.exe および OUdetect.dll）をスキャンを行っているコンピュータの C:\\Microsoft Baseline Security Analyzer\\OfficeUpd ディレクトリにコピーし、既存のファイルを上書します。

デスクトップのアイコン、\[スタート\] メニューから MBSA を実行するか、C:\\Microsoft Baseline Security Analyzer フォルダで mbsacli.exe を使用してコマンド プロンプトを開きます。

**注:** 手 動でファイルをダウンロードする場合、ユーザーは定期的に再ダウンロードし、マイクロソフトによる最新リリースがコンピュータのスキャンで使用されている ようにして下さい。マイクロソフトは、新しいセキュリティ情報がリリース、または更新された場合、ファイルの更新されたバージョンをリリースします。

マイクロソフトは mssecure.xml ファイルの文書化および/またはサポートを提供していますか?
--------------------------------------------------------------------------------------

mssecure.xml ファイルは、MBSA または SMS Feature Pack とともに使用される際にのみサポートされます。マイクロソフトは、新しいバージョンの MBSA および SMS に基づき、このファイルスキーマを変更する可能性があり、したがって他のツールによる使用のためにこのスキーマに関する文書は提供されません。

MBSA を使用する際、どのバージョンの mssecure.xml がダウンロードされますか?
--------------------------------------------------------------------------

MBSA は、スキャンを行うコンピュータの言語に一致する mssecure.cab ファイルをダウンロードし、ローカライズ版の xml ファイルが抽出され、スキャンで使用されます。たとえば、ユーザーが日本語の Windows のコンピュータをリモートでスキャンしている場合、MBSA により、日本語版の mssecure.cab ファイルがダウンロードされ、そのファイルがリモートスキャンで使用されます。英語以外のコンピュータを複数で組み合わせてスキャンする場合、MBSA がコンピュータのスキャンを開始すると MBSA により、スキャンされるコンピュータの言語に一致する mssecure ファイルがダウンロードされます。一致する言語のローカライズ版の mssecure ファイルが使用できない場合、MBSA のすべてのローカライズ版のビルドは、代わりに英語版の mssecure.cab ファイルをダウンロードし使用します。（その際、英語以外のコンピュータをスキャンする場合は、チェックサムのチェックが無効にされます） MBSA では、セキュリティ修正プログラムのデータは、mssecure.cab ファイルの言語に一致する言語で表示されます。たとえば、ドイツ語版の MBSA をフランス語の Windows コンピュータで使用し、フランス語のコンピュータをリモートでスキャンする場合、スキャンの結果は、スキャンしたコンピュータによって提供される情報（日付、ファイル名など） および mssecure.xml から取得される情報 （これらはフランス語で表示されます）を除きドイツ語で表示されます。（ドイツ語版の MBSA が使用されているため）

ローカライズ版の mssecure ファイルが利用可能になるまで MBSA によって行われるすべてのコンピュータ スキャンで英語版の mssecure.cab ファイルが使用されます。

MBSA を実行するのに必要なサービスおよびポートは何ですか?
--------------------------------------------------------

必要なサービスは readme.html ファイル （MBSA とともにインストールされます） のシステム要件のセクションの下および MBSA ヘルプ ファイル （MBSA の左ペインにリンクがあります） に記載されています。mssecure.cab ファイルは、HTTP を介し、マイクロソフト ダウンロード センターからダウンロードされます。リモート コンピュータのスキャンは、TCP ポート 139 および 445 を使用して実行されます。ファイアウォールまたはフィルタリング ルータが 2 つのネットワークを分離するマルチドメインの環境では、TCP ポート 139、445 および UDP ポート 137 および 138 を開き、MBSA がスキャンを行うリモートネットワークに接続、認証を行えるようにする必要があります。

MBSA Version 1.2.1 は Software Update Services (SUS) とどのように連携しますか?
------------------------------------------------------------------------------

MBSA Version 1. 2.1 は、ローカルの SUS サーバーが配布可能なセキュリティ修正プログラムが適用されているかスキャンすることが可能になります。ユーザーは、MBSA UI または MBSA コマンド ライン インターフェイスで、このオプションを選択できます。これによって、スキャン実行時にツールによってダウンロードされた mssecure.xml ファイル内の入手可能なすべてのセキュリティ修正プログラムの一覧ではなく、ローカルの SUS サーバー上にある承認されたセキュリティ修正プログラムの一覧を使って実行されます。SUS UI で承認されたすべてのセキュリティ修正プログラムは （過去の修正が含まれる更新など）、MBSA によってスキャンされることにご注意ください。SUS の詳細については、<http://www.microsoft.com/japan/windowsserversystem/sus/default.mspx>を参照してください。

SUS スキャンオプションを使用したときに古い累積更新プログラムが検出されないようにできます?
-----------------------------------------------------------------------------------------

SUS スキャンオプションを有効にして更新プログラムのスキャンをおこなった場合に、SUS によって許可された古い更新プログラムが検出されることがあります。 SUS スキャンオプションを使用しない場合 (既定の動作) は、新しい更新プログラムに含まれている古い更新プログラムを検出しません

SUS スキャンオプションは、SUS に許可されている全ての更新プログラムが適用されているかを検査するため、新しい更新プログラムまたは累積的な更新プログラムで置き換えられているかどうかにかかわらず、インストールされていない更新プログラムがすべて表示されます。

新しい更新プログラムにより置き換えられた古い更新は、SUS の許可リストで許可を取り消す(許可のチェックを外す)事でMBSAの検査対象から外れ、表示されることはなくなります。

SUS の許可リストから許可を取り消した更新プログラムが MBSA で検出されるのはなぜですか?
-------------------------------------------------------------------------------------

SUS の許可リストに許可されている更新プログラムが残っているためです。 SUS は、複数の言語、製品バージョンの更新を一括して取り扱うことが可能であるため、同じ更新が、言語、製品バージョン毎に複数登録されています。そのため、一つの更新の許可を取り消しても許可された更新が残っていることがあります。更新の許可を取り消す(許可のチェックを外す)場合には、サポート技術情報の番号等で、許可リストを検索し全ての更新の許可が取り消されていることを確認してください。

MBSA は Systems Management Server (SMS) とどのように連携しますか?
-----------------------------------------------------------------

SMS 2.0 Software Update Services Feature Pack または SMS 2003 は、企業顧客に対して、Windows NT 4.0、Windows 2000、および Windows XP クライアントのセキュリティ修正プログラムの管理ソリューションを提供します。SMS は MBSA テクノロジを使って、クライアント コンピュータにインストールされているか、または適用可能なセキュリティ更新プログラムを自動的に、システムの実行中にスキャンします。このデータは、 Systems Management Server のインベントリ情報に変換されて追加され、Web ベースのレポート機能を使って、1 ヶ所から表示できます。システム管理者は、Systems Management Server を使用して配布するための最新の Windows の修正プログラムを選択して、マイクロソフト から直接インポートできます。詳細については、<http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/default.mspx> (SMS 2.0 について)、または<http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx> (SMS 2003 について) をご覧下さい。SMS を使用してセキュリティ スキャンを処理しているユーザーは、MBSA 1.2.1 にアップグレードする必要はありません。この理由は、MBSA 1.2 と MBSA 1.2.1 では、セキュリティ更新プログラムのスキャン論理に変更はないためです。

MBSA でDNS コンピュータまたはドメイン名がサポートされないのはなぜですか?
------------------------------------------------------------------------

MBSA は、NetBIOS コンピュータおよびドメイン名を受付け、DNS コンピュータまたはドメイン名 （完全修飾ドメイン名）を受け付けません。MBSA は、NetBIOS ドメイン名およびコンピュータ名を domain\\computername または workgroup\\computername の形式で受け付けます。

MBSA では、同時に何台のコンピュータのスキャンを行うことができますか?
--------------------------------------------------------------------

MBSA (GUI および CLI) は、一度に 10,000 台までのコンピュータをスキャンすることができます。10,000 台以上のコンピュータをもつドメインまたはネットワークをスキャンする際、一度に 10,000 台のコンピュータに対して、複数のスキャンを行う必要があります。mbsacli.exe を -fh スイッチ （テキスト ファイルに NetBIOS コンピュータ名を入力し、スキャンを行う） または -fip スイッチとともに使用し （テキスト ファイルに IP アドレスを入力し、スキャンを行う） を使用した場合、それぞれのスキャンに指定できるのは最大 128 のコンピュータ名および IP アドレスまでです。

マイクロソフトは MBSA をサポートしますか?
-----------------------------------------

はい。このツールは マイクロソフト サポート (PSS) によってサポートされます。ユーザーは、MBSA に関する公開ニュースグループに技術的な質問を投稿することもできます。

-   ニュース サーバー : Msnews.microsoft.com
-   ニュースグループ : Microsoft.public.security.baseline\_analyzer

MBSA に関する質問やコメントはどのように提出すればよいですか?
------------------------------------------------------------

MBSA に関するディスカッションを行うための公開ニュースグループがあります。

-   ニュース サーバー : Msnews.microsoft.com
-   ニュースグループ : Microsoft.public.security.baseline\_analyzer

HFNetchk モード (/hf) 時に、 -nvc を使用しても、MBSA のバージョンが確認されませんが、どうしてですか?
----------------------------------------------------------------------------------------------------

HFNetchk モード のヘルプ (/hf /?) の内容に誤りがあります。 -nvc を使用した場合は MBSA の新しいバージョンをチェックしません。 MBSA のバージョンを確認したい場合には、 -nvc オプションを適用する必要はありません。 この誤りは日本語版のみで確認されており、次期バージョン以降で対応予定です。

------------------------------------------------------------------------

### 関連情報

-   [Microsoft Baseline Security Analyzer](http://www.microsoft.com/japan/technet/security/tools/mbsahome.mspx)
-   [Microsoft Baseline Security Analyzer ホワイトペーパー](http://www.microsoft.com/japan/technet/security/tools/mbsawp.mspx)
-   [日本語版 Microsoft Baseline Security Analyzer 1.2 正式公開のお知らせと利用上の注意点](http://support.microsoft.com/?kbid=320454)
-   ホームユーザー向け: MBSA によるセキュリティ対策
-   [MBSA とスクリプト](http://www.microsoft.com/japan/technet/security/tools/mbsa1/script.mspx)

[![](images/dd229318.arrow_px_up(ja-jp,MSDN.10).gif)ページのトップへ](#top)
