---
TOCTitle: 'MS17-MAR'
Title: 2017 年 3 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms17-mar'
ms:contentKeyID: 74430919
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms17-mar(v=Security.10)'
---

2017 年 3 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日: 2017 年 3 月 15 日 | 最終更新日: 2017 年 8 月 9 日

**バージョン:** 4.0

このセキュリティ情報の概要は 2017 年 3 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定するときに役立つ情報も提供します。「**関連情報**」の欄を参照してください。

既にお知らせしたように、セキュリティ更新プログラムの情報は、セキュリティ情報サイトではなく、[セキュリティ更新プログラム ガイド](https://portal.msrc.microsoft.com/ja-jp/security-guidance)で公開されます。詳細については、ブログ記事「[セキュリティ更新プログラムに対するコミットメントの促進について](https://blogs.technet.microsoft.com/jpsecurity/2016/11/09/furthering-our-commitment-to-security-updates/)」を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次の「**影響を受けるソフトウェア**」のセクションを参照してください。

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度<br />
と脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>既知の<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842208">MS17-006</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (4013073)<br />
</strong>このセキュリティ更新プログラムは、Internet Explorer の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。これらの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じ権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしているときに、攻撃者によりこの脆弱性が悪用された場合、影響を受けるコンピューターが制御される可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842207">MS17-007</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用の累積的なセキュリティ更新プログラム (4013071)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Microsoft Edge を使用して表示すると、リモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、影響を受けるコンピューターを制御する可能性があります。攻撃者は、その後、プログラムのインストール、データの表示、変更、削除などを行ったり、完全なユーザー権限を持つ新たなアカウントを作成したりする可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842215">MS17-008</a></td>
<td style="border:1px solid black;"><strong>Windows Hyper-V 用のセキュリティ更新プログラム (4013082)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この中で最も深刻な脆弱性では、ゲスト オペレーティング システム上の認証された攻撃者が、Hyper-V のホスト オペレーティング システムで任意のコードを実行させる特別に細工したアプリケーションを実行した場合、リモートでコードが実行される可能性があります。Hyper-V の役割を有効にしていないユーザーは影響を受けません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839436">MS17-009</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows PDF ライブラリ用のセキュリティ更新プログラム (4010319)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、ユーザーがオンライン上で特別に細工された PDF コンテンツを閲覧したり、特別に細工された PDF ドキュメントを開いたりした場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=843149">MS17-010</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows SMB サーバー用のセキュリティ更新プログラム (4013389)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、攻撃者が特別に細工されたメッセージを Microsoft Server Message Block 1.0 (SMBv1) サーバーに送信すると、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842211">MS17-011</a></td>
<td style="border:1px solid black;"><strong>Microsoft Uniscribe 用のセキュリティ更新プログラム (4013076)<br />
</strong>このセキュリティ更新プログラムは、Windows Uniscribe の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web サイトにアクセスしたり、特別に細工された文書を開いたりした場合に、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842212">MS17-012</a></td>
<td style="border:1px solid black;"><strong>Microsoft Windows 用のセキュリティ更新プログラム (4013078)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、攻撃者が、iSNS Server に接続して悪意のある要求をサーバーに発行する特別に細工されたアプリケーションを実行すると、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842210">MS17-013</a></td>
<td style="border:1px solid black;"><strong>Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (4013075)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows、Microsoft Office、Skype for Business、Microsoft Lync、および Microsoft Silverlight の脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web サイトにアクセスしたり、特別に細工された文書を開いたりした場合に、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Office、<br />
Skype for Business、<br />
Microsoft Lync、<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842278">MS17-014</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用のセキュリティ更新プログラム (4013241)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。最も深刻な脆弱性では、特別に細工された Microsoft Office ファイルをユーザーが開いた場合にリモートでコードが実行される可能性があります。これらの脆弱性の悪用に成功した攻撃者が、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。システムに対するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps、<br />
Microsoft サーバー ソフトウェア、<br />
Microsoft コミュニケーション プラットフォームおよびソフトウェア</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842279">MS17-015</a></td>
<td style="border:1px solid black;"><strong>Microsoft Exchange Server 用のセキュリティ更新プログラム (4013242)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Exchange Outlook Web Access (OWA) の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工された添付ファイル付きの電子メールを脆弱な Exchange サーバーに送信すると、Exchange Server においてリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842209">MS17-016</a></td>
<td style="border:1px solid black;"><strong>Windows IIS 用のセキュリティ更新プログラム (4013074)<br />
</strong>このセキュリティ更新プログラムは、Microsoft インターネット インフォメーション サービス (IIS) の脆弱性を解決します。この脆弱性により、影響を受ける Microsoft IIS Server によってホストされている特別に細工された URL をユーザーがクリックした場合に、特権の昇格が起こる可能性があります。攻撃者がこの脆弱性を悪用した場合、ユーザーのブラウザーでスクリプトを実行して、Web セッションから情報を取得できる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842216">MS17-017</a></td>
<td style="border:1px solid black;"><strong>Windows カーネル用のセキュリティ更新プログラム (4013081)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。これらの脆弱性により、攻撃者が特別に細工されたアプリケーションを実行した場合に、特権の昇格が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=842217">MS17-018</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバー用のセキュリティ更新プログラム (4013083)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、攻撃者が影響を受けるシステムにログオンして特別に細工されたアプリケーションを実行した場合に特権の昇格が起こり、影響を受けるシステムを制御する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839438">MS17-019</a></td>
<td style="border:1px solid black;"><strong>Active Directory フェデレーション サービス用のセキュリティ更新プログラム (4010320)<br />
</strong>このセキュリティ更新プログラムは、Active Directory フェデレーション サービス (ADFS) の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工した要求を ADFS サーバーに送信し、攻撃者が標的のシステムに関する機密情報を読み取ることができた場合、情報漏えいが起きる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=836272">MS17-020</a></td>
<td style="border:1px solid black;"><strong>Windows DVD メーカー用のセキュリティ更新プログラム　(3208223)<br />
</strong>このセキュリティ更新プログラムは、Windows DVD メーカーの情報漏えいの脆弱性を解決します。攻撃者がこの脆弱性を悪用すると、標的のシステムをさらに侵害する情報を取得する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839434">MS17-021</a></td>
<td style="border:1px solid black;"><strong>Windows DirectShow 用のセキュリティ更新プログラム (4010318)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、悪意のある Web サイトでホストされた特別に細工されたメディア コンテンツを Windows DirectShow で開いた場合に情報漏えいが起きる可能性があります。攻撃者がこの脆弱性を悪用すると、標的のシステムをさらに侵害する情報を取得する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=839435">MS17-022</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML Core Services 用のセキュリティ更新プログラム (4010321)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Windows の脆弱性を解決します。この脆弱性により、ユーザーが悪意のある Web サイトにアクセスすると、情報漏えいの可能性があります。しかし、すべての場合において、攻撃者がユーザーに特別に細工したリンクを強制的にクリックさせる方法はありません。一般的には、電子メールまたはインスタント メッセンジャーのメッセージの誘導により、ユーザーにリンクをクリックさせることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=844066">MS17-023</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (4014329)</strong><br />
このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10、および Windows Server 2016 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

Exploitability Index (悪用可能性指標)
-------------------------------------

<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報 ID、CVE ID の順でリストされています。セキュリティ情報での深刻度評価が緊急または重要である脆弱性のみが含まれています。

**この表はどのように使用しますか?**

この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細およびその決定方法については、「[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259)」を参照してください。

下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE 番号**                    

</td>
<td style="border:1px solid black;">
**脆弱性のタイトル**

</td>
<td style="border:1px solid black;">
**最新のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**過去のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**サービス拒否  
悪用可能性評価**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-006: Internet Explorer 用の累積的なセキュリティ更新プログラム (4013073)**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0008](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0008)

</td>
<td style="border:1px solid black;">
Internet Explorer の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0009)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0012](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0012)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0018](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0018)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0033)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0037)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0040](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0040)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0049](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0049)

</td>
<td style="border:1px solid black;">
スクリプト エンジンの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0059](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0059)

</td>
<td style="border:1px solid black;">
Internet Explorer の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0130)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0149](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0149)

</td>
<td style="border:1px solid black;">
Internet Explorer のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0154)

</td>
<td style="border:1px solid black;">
Internet Explorer 特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-007: Microsoft Edge 用の累積的なセキュリティ更新プログラム (4013071)**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0009](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0009)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0010](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0010)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0011](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0011)

</td>
<td style="border:1px solid black;">
Microsoft Edge の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0012](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0012)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0015](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0015)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0017](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0017)

</td>
<td style="border:1px solid black;">
Microsoft Edge の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0023)

</td>
<td style="border:1px solid black;">
Microsoft PDF のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0032)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0033)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのなりすましの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0034](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0034)

</td>
<td style="border:1px solid black;">
Microsoft Edge のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0035](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0035)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0037)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0065](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0065)

</td>
<td style="border:1px solid black;">
Microsoft ブラウザーの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0066](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0066)

</td>
<td style="border:1px solid black;">
Microsoft Edge のセキュリティ機能のバイパスの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0067](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0067)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0068](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0068)

</td>
<td style="border:1px solid black;">
Microsoft Edge の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0069](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0069)

</td>
<td style="border:1px solid black;">
Microsoft Edge のなりすましの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0070](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0070)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0071](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0071)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0094](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0094)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0131](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0131)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0132)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0133)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0134](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0134)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0135)

</td>
<td style="border:1px solid black;">
Microsoft Edge のセキュリティ機能のバイパス

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0136)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0137](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0137)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0138)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0140](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0140)

</td>
<td style="border:1px solid black;">
Microsoft Edge のセキュリティ機能のバイパス

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0141)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0150](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0150)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0151](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0151)

</td>
<td style="border:1px solid black;">
スクリプト エンジンのメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-008: Windows Hyper-V 用のセキュリティ更新プログラム (4013082)**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0021](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0021)

</td>
<td style="border:1px solid black;">
Hyper-V vSMB のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0051](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0051)

</td>
<td style="border:1px solid black;">
Microsoft Hyper-V ネットワーク スイッチのサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0074](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0074)

</td>
<td style="border:1px solid black;">
Hyper-V のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0075](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0075)

</td>
<td style="border:1px solid black;">
Hyper-V のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0076](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0076)

</td>
<td style="border:1px solid black;">
Hyper-V のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0095)

</td>
<td style="border:1px solid black;">
Hyper-V vSMB のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0096](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0096)

</td>
<td style="border:1px solid black;">
Hyper-V の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0097](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0097)

</td>
<td style="border:1px solid black;">
Hyper-V のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0098](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0098)

</td>
<td style="border:1px solid black;">
Hyper-V のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0099)

</td>
<td style="border:1px solid black;">
Hyper-V のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0109](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0109)

</td>
<td style="border:1px solid black;">
Hyper-V のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-009: Microsoft Windows PDF ライブラリ用のセキュリティ更新プログラム (4010319)**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0023](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0023)

</td>
<td style="border:1px solid black;">
Microsoft PDF のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-010: Microsoft Windows SMB サーバー用のセキュリティ更新プログラム (4013389)**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0143](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0143)

</td>
<td style="border:1px solid black;">
Windows SMB のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0144](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0144)

</td>
<td style="border:1px solid black;">
Windows SMB のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0145](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0145)

</td>
<td style="border:1px solid black;">
Windows SMB のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0146](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0146)

</td>
<td style="border:1px solid black;">
Windows SMB のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0147)

</td>
<td style="border:1px solid black;">
Windows SMB の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0148)

</td>
<td style="border:1px solid black;">
Windows SMB のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-011: Microsoft Uniscribe 用のセキュリティ更新プログラム (4013076)**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0072](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0072)

</td>
<td style="border:1px solid black;">
Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0083)

</td>
<td style="border:1px solid black;">
Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0084](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0084)

</td>
<td style="border:1px solid black;">
Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0085](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0085)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0086](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0086)

</td>
<td style="border:1px solid black;">
Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0087](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0087)

</td>
<td style="border:1px solid black;">
Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0088)

</td>
<td style="border:1px solid black;">
Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0089)

</td>
<td style="border:1px solid black;">
Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0090)

</td>
<td style="border:1px solid black;">
Uniscribe のリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0091](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0091)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0092](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0092)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0111](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0111)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0112](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0112)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0113](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0113)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0114)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0115](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0115)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0116](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0116)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0117](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0117)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0118)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0119](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0119)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0120](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0120)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0121](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0121)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0122)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0123](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0123)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0124)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0125)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0126](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0125)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0127)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0128)

</td>
<td style="border:1px solid black;">
Uniscribe の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-012: Microsoft Windows 用のセキュリティ更新プログラム (4013078)**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0007](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0007)

</td>
<td style="border:1px solid black;">
Device Guard のセキュリティ機能のバイパスの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0016](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0016)

</td>
<td style="border:1px solid black;">
SMBv2/SMBv3 Null Dereference のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0039](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0039)

</td>
<td style="border:1px solid black;">
Windows DLL の読み込みリモート コード実行の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0057](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0057)

</td>
<td style="border:1px solid black;">
Windows DNS クエリの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0100](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0100)

</td>
<td style="border:1px solid black;">
Windows HelpPane の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0104](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0104)

</td>
<td style="border:1px solid black;">
iSNS Server のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-013: Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (4013075)**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0001](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0001)

</td>
<td style="border:1px solid black;">
Windows GDI の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0005](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0005)

</td>
<td style="border:1px solid black;">
Windows GDI の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0014](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0014)

</td>
<td style="border:1px solid black;">
GDI+ のリモート コードが実行される脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0025](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0025)

</td>
<td style="border:1px solid black;">
Windows GDI の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0038](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0038)

</td>
<td style="border:1px solid black;">
Windows Graphics コンポーネントの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0047](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0047)

</td>
<td style="border:1px solid black;">
Windows GDI の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0060](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0060)

</td>
<td style="border:1px solid black;">
GDI+ の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0061](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0061)

</td>
<td style="border:1px solid black;">
Microsoft 色の管理の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0062](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0062)

</td>
<td style="border:1px solid black;">
GDI+ の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0063](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0063)

</td>
<td style="border:1px solid black;">
Microsoft 色の管理の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0073](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0073)

</td>
<td style="border:1px solid black;">
Windows GDI+ の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0108](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0108)

</td>
<td style="border:1px solid black;">
Windows グラフィックス コンポーネントのリモートでコードが実行される脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-014: Microsoft Office 用のセキュリティ更新プログラム (4013241)**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0006](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0006)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0019](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0019)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0020](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0020)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0027](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0027)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0029)

</td>
<td style="border:1px solid black;">
Microsoft Office のサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0030](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0030)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0031](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0031)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0052](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0052)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0053](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0053)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0105](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0105)

</td>
<td style="border:1px solid black;">
Microsoft Office の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0107](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0107)

</td>
<td style="border:1px solid black;">
Microsoft SharePoint XSS の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0129](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0129)

</td>
<td style="border:1px solid black;">
Microsoft Lync for Mac 証明書の検証の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-015: Microsoft Exchange Server 用のセキュリティ更新プログラム (4013242)**](https://go.microsoft.com/fwlink/?linkid=842279)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0110](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0110)

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-016: Windows IIS 用のセキュリティ更新プログラム (4013074)**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0055](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0055)

</td>
<td style="border:1px solid black;">
Microsoft IIS Server XSS の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-017: Windows カーネル用のセキュリティ更新プログラム (4013081)**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0050](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0050)

</td>
<td style="border:1px solid black;">
Windows カーネルの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0101](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0101)

</td>
<td style="border:1px solid black;">
Windows の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0102](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0102)

</td>
<td style="border:1px solid black;">
Windows の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0103](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0103)

</td>
<td style="border:1px solid black;">
Windows レジストリの特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-018: Windows カーネルモード ドライバー用のセキュリティ更新プログラム (4013083)**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0024](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0024)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0026](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0026)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0056](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0056)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0078](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0078)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0079](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0079)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0080](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0080)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0081](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0081)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0082](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0082)

</td>
<td style="border:1px solid black;">
Win32k の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-019: Active Directory フェデレーション サービス用のセキュリティ更新プログラム (4010320)**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0043](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0043)

</td>
<td style="border:1px solid black;">
Microsoft Active Directory フェデレーション サービスの情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
一時的

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-020: Windows DVD メーカー用のセキュリティ更新プログラム　(3208223)**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0045](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0045)

</td>
<td style="border:1px solid black;">
Windows DVD メーカーのクロスサイト リクエスト フォージェリの脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-021: Windows DirectShow 用のセキュリティ更新プログラム (4010318)**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0042)

</td>
<td style="border:1px solid black;">
Windows DirectShow の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
2 - 悪用される可能性は低い

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-022: Microsoft XML Core Services 用のセキュリティ更新プログラム (4010321)**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0022](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0022)

</td>
<td style="border:1px solid black;">
Microsoft XML Core Services の情報漏えいの脆弱性

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
0 - 悪用の事実を確認済み

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-023: Adobe Flash Player のセキュリティ更新プログラム (4014329)**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB17-07](http://helpx.adobe.com/jp/security/products/flash-player/apsb17-07.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度と更新プログラムの優先度の評価については、Adobe Security Bulletin [APSB17-07](http://helpx.adobe.com/jp/security/products/flash-player/apsb17-07.html) を参照してください。

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 

影響を受けるソフトウェア
------------------------

<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。

**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合もあります。上記の各セキュリティ情報 ID の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。

### Windows オペレーティング システムとコンポーネント (表 1/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(緊急)  
Microsoft Internet Messaging API  
(3218362)  
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
Windows Vista Service Pack 2  
(4012598)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4012583)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3217587)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4017018)  
(緊急)  
Windows Vista Service Pack 2  
(4012584)  
(重要)  
Windows Vista Service Pack 2  
(4012497)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(緊急)  
Microsoft Internet Messaging API  
(3218362)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3211306)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012598)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012583)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3217587)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4017018)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(4012584)  
(重要)  
Windows Vista x64 Edition Service Pack 2  
(4012497)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(警告)  
Microsoft Internet Messaging API  
(3218362)  
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
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4012598)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4012583)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3217587)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4012021)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4017018)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4012584)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4012497)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4012204)  
(警告)  
Microsoft Internet Messaging API  
(3218362)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3211306)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(4012598)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(4012583)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3217587)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(4012021)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(4017018)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(4012584)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(4012497)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

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
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(4012598)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(4012583)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3217587)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(4017018)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(4012584)  
(重要)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(4012497)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
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
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
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
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012215)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
セキュリティのみ

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
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
月例のロールアップ

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
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4012204)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4012217)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012204)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012606)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025338)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4012606)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025338)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013198)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025344)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013198)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025344)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025339)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025339)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1703 for 32-bit Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025342)  
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
Windows 10 Version 1703 for x64-based Systems

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4025342)  
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
<td style="border:1px solid black;" colspan="9">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4013429)  
(警告)

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(4013429)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-006**](https://go.microsoft.com/fwlink/?linkid=842208)

</td>
<td style="border:1px solid black;">
[**MS17-007**](https://go.microsoft.com/fwlink/?linkid=842207)

</td>
<td style="border:1px solid black;">
[**MS17-008**](https://go.microsoft.com/fwlink/?linkid=842215)

</td>
<td style="border:1px solid black;">
[**MS17-009**](https://go.microsoft.com/fwlink/?linkid=839436)

</td>
<td style="border:1px solid black;">
[**MS17-010**](https://go.microsoft.com/fwlink/?linkid=843149)

</td>
<td style="border:1px solid black;">
[**MS17-011**](https://go.microsoft.com/fwlink/?linkid=842211)

</td>
<td style="border:1px solid black;">
[**MS17-012**](https://go.microsoft.com/fwlink/?linkid=842212)

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

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
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

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
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(4012598)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(4012583)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3217587)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(4017018)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(4012584)  
(重要)  
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(4012497)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2(Server Core インストール)  
(3211306)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2(Server Core インストール)  
(4012598)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2(Server Core インストール)  
(4012583)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3217587)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(4017018)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(4012584)  
(重要)  
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(4012497)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012212)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012212)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012215)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012215)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(緊急)

</td>
</tr>
</table>
 
**MS17-013 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Windows オペレーティング システムとコンポーネント (表 2/2)

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(4012373)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4011981)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(4012497)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3205715)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3214051)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(3216916)  
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
(4012373)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4011981)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(4012497)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3205715)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3214051)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(3216916)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

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
(4012373)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4011981)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(4012497)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3217882)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3214051)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(3216916)  
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
(4012373)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(4011981)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(4012497)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3217882)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3214051)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(3216916)  
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
(4012373)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(4011981)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(4012497)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3217882)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3214051)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(3216916)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4015548)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(4015551)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012606)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4013198)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1703 for 32-bit Systems

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
<td style="border:1px solid black;">
Windows 10 Version 1703 for x64-based Systems

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
<td style="border:1px solid black;" colspan="9">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(4014329)  
(緊急)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-016**](https://go.microsoft.com/fwlink/?linkid=842209)

</td>
<td style="border:1px solid black;">
[**MS17-017**](https://go.microsoft.com/fwlink/?linkid=842216)

</td>
<td style="border:1px solid black;">
[**MS17-018**](https://go.microsoft.com/fwlink/?linkid=842217)

</td>
<td style="border:1px solid black;">
[**MS17-019**](https://go.microsoft.com/fwlink/?linkid=839438)

</td>
<td style="border:1px solid black;">
[**MS17-020**](https://go.microsoft.com/fwlink/?linkid=836272)

</td>
<td style="border:1px solid black;">
[**MS17-021**](https://go.microsoft.com/fwlink/?linkid=839434)

</td>
<td style="border:1px solid black;">
[**MS17-022**](https://go.microsoft.com/fwlink/?linkid=839435)

</td>
<td style="border:1px solid black;">
[**MS17-023**](https://go.microsoft.com/fwlink/?linkid=844066)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(4012373)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(4011981)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(4012497)  
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
Microsoft XML コア サービス 3.0  
(3216916)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(4012373)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(4011981)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(4012497)  
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
Microsoft XML コア サービス 3.0  
(3216916)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012212)  
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
Microsoft XML コア サービス 3.0  
(4012212)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(4012215)  
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
Microsoft XML コア サービス 3.0  
(4012215)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012214)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012217)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012213)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4012216)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft XML コア サービス 3.0  
(4013429)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
 

### Microsoft Office スイートおよびソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3127945)  
(緊急)  
Microsoft Office 2007 Service Pack 3  
(3141535)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3178676)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(3178683)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3127958)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3178688)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)  
(3178686)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(3178690)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(3178687)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3127958)  
(緊急)  
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3178688)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)  
(3178686)  
(重要)  
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(3178690)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(3178687)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (32 ビット版)  
(3172542)  
(重要)  
Microsoft Word 2013 Service Pack 1 (32 ビット版)  
(3172464)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 Service Pack 1 (64 ビット版)  
(3172542)  
(重要)  
Microsoft Word 2013 Service Pack 1 (64 ビット版)  
(3172464)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT Service Pack 1  
(3172542)  
(重要)  
Microsoft Word 2013 RT Service Pack 1  
(3172464)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32 ビット版)  
(3178673)  
(重要)  
Microsoft Word 2016 (32 ビット版)  
(3178674)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64 ビット版)  
(3178673)  
(重要)  
Microsoft Word 2016 (64 ビット版)  
(3178674)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office for Mac 2011**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel for Mac 2011  
(3198809)  
(重要)  
Microsoft Excel for Mac 2011  
(3212218)  
(重要)  
Microsoft Word for Mac 2011  
(3198809)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 2016 for Mac  
(重要)  
Microsoft Excel 2016 for Mac  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**その他の Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(3178677)  
(重要)  
Microsoft Office 互換機能パック Service Pack 3  
(3178682)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3178680)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3178693)  
(緊急)  
Microsoft Word Viewer  
(3178653)  
(緊急)

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3178694)  
(重要)

</td>
</tr>
</table>
 
**MS17-013 および MS17-014 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft Office Services および Web Apps

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Excel Services (32 ビット版)  
(3178678)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Excel Services (64 ビット版)  
(3178678)  
(重要)

</td>
</tr>
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Excel Services  
(3178685)  
(重要)  
Word Automation Services  
(3178684)  
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Excel Services  
(3172431)  
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3178689)  
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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3172457)  
(重要)

</td>
</tr>
</table>
 
**MS17-014 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft サーバー ソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Foundation 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013 Service Pack 1  
(3172540)  
(重要)

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
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 Service Pack 1  
(4012178)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 14

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2013 の累積的な更新プログラム 14  
(4012178)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Exchange Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
<td style="border:1px solid black;">
[**MS17-015**](https://go.microsoft.com/fwlink/?linkid=842279)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 の累積的な更新プログラム 3

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Exchange Server 2016 の累積的な更新プログラム 3  
(4012178)  
(重要)

</td>
</tr>
</table>
 
**MS17-014 および MS17-015 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft コミュニケーション プラットフォームおよびソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Skype for Business 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Skype for Business 2016 (32 ビット版)  
(3178656)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32 ビット版)  
(3178656)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Skype for Business 2016 (64 ビット版)  
(3178656)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64 ビット版)  
(3178656)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2013**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32 ビット)  
(Skype for Business)  
(3172539)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32 ビット)  
(Skype for Business Basic)  
(3172539)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)  
(Skype for Business)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64 ビット)  
(Skype for Business)  
(3172539)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)  
(Skype for Business Basic)

</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64 ビット)  
(Skype for Business Basic)  
(3172539)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 ビット)  
(4010299)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 ビット)  
(4010299)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

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
(4010300)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(管理者レベル インストール)

</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(管理者レベル インストール)  
(4010301)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 Console**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 Console  
(4010303)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Live Meeting 2007 アドイン**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 アドイン

</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007 アドイン  
(4010304)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Lync for Mac**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
<td style="border:1px solid black;">
[**MS17-014**](https://go.microsoft.com/fwlink/?linkid=842278)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync for Mac 2011

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft Lync for Mac 2011  
(4012487)  
(重要)

</td>
</tr>
</table>
 
**MS17-013 および MS17-014 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

### Microsoft 開発者用ツールおよびソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-013**](https://go.microsoft.com/fwlink/?linkid=842210)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
サポートされているすべてのリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5  
(4013867)  
(**緊急**)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
サポートされているすべてのリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime

</td>
<td style="border:1px solid black;">
サポートされているすべてのリリースの Microsoft Windows クライアントにインストールされている Microsoft Silverlight 5 Developer Runtime  
(4013867)  
(**緊急**)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
サポートされているすべてのリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5

</td>
<td style="border:1px solid black;">
サポートされているすべてのリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5  
(4013867)  
(**緊急**)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
サポートされているすべてのリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime

</td>
<td style="border:1px solid black;">
サポートされているすべてのリリースの Microsoft Windows サーバーにインストールされている Microsoft Silverlight 5 Developer Runtime  
(4013867)  
(**緊急**)

</td>
</tr>
</table>
 
**MS17-013 に関する注意事項**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。

 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび検証を効率化するのに役立ちます。

利用可能なこれらのツールと他のツールの詳細については、「[IT 管理者向けセキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、「[謝辞](https://technet.microsoft.com/ja-jp/library/security/mt745121.aspx)」を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/ja-jp/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

「[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168)」(英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security update」のキーワード検索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージを Microsoft ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/ja-jp/kb/913086) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション: [TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ: [ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/ja-jp/contactus/cu_sc_virsec_master)

国ごとのローカル サポート: [インターナショナル サポート](http://support.microsoft.com/ja-jp/common/international.aspx)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2017/03/15): このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2017/04/12): このセキュリティ情報の概要ページを更新し、次の更新についてお知らせしました。
    -   MS17-013 では、Windows Vista および Windows Server 2008 用の更新プログラム 4017018 をリリースしました。この更新プログラムは、CVE-2017-0038 に対する更新プログラム 4012583 のみを置き換えるもので、この脆弱性を包括的に解決します。マイクロソフトは、影響を受けるソフトウェアを実行しているお客様が、このセキュリティ情報で説明されている脆弱性から完全に保護するために、このセキュリティ更新プログラムをインストールすることを推奨します。詳細については、[マイクロソフト サポート技術情報 4017018](https://support.microsoft.com/ja-jp/kb/4017018) を参照してください。
    -   MS17-014 では、Office for Mac 2011 について CVE-2017-0027 を包括的に解決するために、マイクロソフトはセキュリティ更新プログラム 3212218 をリリースしました。マイクロソフトは、Office for Mac 2011 を実行するお客様が、このセキュリティ情報で説明されている脆弱性から完全に保護するために、更新プログラム 3212218 をインストールすることを推奨します。詳細については、[マイクロソフト サポート技術情報 3212218](https://support.microsoft.com/ja-jp/kb/3212218) を参照してください。
    -   MS17-021 では、CVE-2017-0042 に適用する Windows Server 2012 用のセキュリティ更新プログラムが利用可能になったことをお知らせしました。Windows Server 2012 を実行するお客様は、この脆弱性から完全に保護するために、更新プログラム 4015548 (セキュリティのみ) または 4015551 (月例のロールアップ) をインストールする必要があります。その他のバージョンの Microsoft Windows を実行しているお客様は、特別な措置を講じる必要はありません。
-   V2.1 (2017/04/18): CVE-2017-0022 について、Exploitability Index (悪用可能性指標) を「0 - 悪用の事実を確認済み」に修正しました。これは情報のみの変更です。
-   V3.0 (2017/05/10): MS17-013 に関して、マイクロソフトは 影響を受けるエディションの Windows Server 2008 用セキュリティ更新プログラム 4017018 を再リリースしました。この再リリースは、セキュリティ更新プログラムとして再分類されました。マイクロソフトは、CVE-2017-0038 から完全に保護するために更新プログラム 4017018 をインストールすることを推奨します。既にこの更新プログラムをインストールされたお客様は、特別な措置を講じる必要はありません。
-   V4.0 (2017/08/09): MS17-007 関して、マイクロソフトは CVE-2017-0071 に包括的に対処するために、すべてのバージョンの Windows 10 用に 7 月のセキュリティ更新プログラムをリリースしました。Windows 10 for 32-bit Systems、Windows 10 for x64-based Systems、Windows 10 Version 1703 for 32-bit Systems、および Windows 10 Version 1703 for x64-based Systems は、この脆弱性の影響を受けるため、「影響を受ける製品」一覧に追加されました。2017 年 7 月のセキュリティ更新プログラムをインストールしていないお客様は、この脆弱性から完全に保護するために、この更新プログラムをインストールすることを推奨します。

*Page generated 2017-08-02 12:34-07:00.*
