---
TOCTitle: 'MS13-SEP'
Title: 2013 年 9 月のセキュリティ情報
ms:assetid: 'ms13-sep'
ms:contentKeyID: 61229717
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms13-sep(v=Security.10)'
---


2013 年 9 月のセキュリティ情報
==============================

公開日: 2013年9月11日 | 最終更新日: 2013年11月7日

**バージョン:** 1.0

[![](../../images/Dn636401.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn636401.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2013 年 9 月公開のセキュリティ情報の一覧です。

2013 年 9 月のセキュリティ情報の公開により、2013 年 9 月 6 日に公開した事前通知を、このセキュリティ情報の概要に置き換えました。事前通知サービスの詳細については、[「マイクロソフト セキュリティ情報の事前通知」](http://go.microsoft.com/fwlink/?linkid=217213)を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2013 年 9 月 11 日 の午後 (日本時間) に配信予定です。詳細は、「 [今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/security/dd251169.aspx) 」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2013 年 9 月 11 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[9 月の セキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032557378&culture=en-us) (英語)。この日付以降、この Webcast は[オンデマンド](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032538733&culture=en-us)で利用可能となります。

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Microsoft SharePoint Server の脆弱性により、リモートでコードが実行される (2834052)<br />
<br />
このセキュリティ更新プログラムは Microsoft Office Server ソフトウェアに存在する 1 件の一般に公開された脆弱性および 9 件の非公開で報告された脆弱性を解決します。攻撃者が最も深刻な脆弱性を悪用し、影響を受けるサーバーに対して特別に細工されたパケットを送信すると、W3WP サービス アカウントのコンテキストにてリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=307055">MS13-068</a></td>
<td style="border:1px solid black;">Microsoft Outlook の脆弱性により、リモートでコードが実行される (2756473)<br />
<br />
この更新プログラムは非公開で報告された Microsoft Outlook に存在する脆弱性を解決します。ユーザーが Microsoft Outlook の影響を受けるバージョンを使って特別に細工された電子メール メッセージを開くかブレビューした場合、脆弱性によってリモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2870699)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された 10 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320629">MS13-070</a></td>
<td style="border:1px solid black;">OLE の脆弱性により、リモートでコードが実行される (2876217)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された OLE オブジェクトを開いた場合、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314046">MS13-071</a></td>
<td style="border:1px solid black;">Windows テーマ ファイルの脆弱性により、リモートでコードが実行される (2864063)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーがコンピューターで特別に細工された Windows テーマを適用した場合、リモートでコードが実行される可能性があります。すべての場合において、ユーザーに強制的にファイルを開かせたり、テーマを適用させたりすることはできません。攻撃を成功させるためには、ユーザーを誘導してファイルを開かせたり、テーマを適用させたりする必要があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Microsoft Office の脆弱性により、リモートでコードが実行される (2845537)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された13 件の Microsoft Office に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、Microsoft Office ソフトウェアの影響を受けるバージョンで特別に細工されたファイルが開かれると、リモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a></td>
<td style="border:1px solid black;">Microsoft Excel の脆弱性により、リモートでコードが実行される (2858300)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 3 件の Microsoft Office に存在する脆弱性を解決します。ユーザーが Microsoft Excel の影響を受けるバージョン、または影響を受ける Microsoft Office の他のソフトウェアで、特別に細工されたファイルを開くと、最も深刻な脆弱性によってリモートでコードが実行される可能性があります。攻撃者により、最も深刻な脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308989">MS13-074</a></td>
<td style="border:1px solid black;">Microsoft Access の脆弱性により、リモートでコードが実行される (2848637)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 3 件の Microsoft Office に存在する脆弱性を解決します。ユーザーが、影響を受けるバージョンの Microsoft Access で特別に細工された Access ファイルを開くと、脆弱性によってリモートでコードが実行される可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318022">MS13-075</a></td>
<td style="border:1px solid black;">Microsoft Office IME (中国語版) の脆弱性により、特権が昇格される (2878687)<br />
<br />
この更新プログラムは非公開で報告された Microsoft Office IME (中国語版) に存在する 1 件の脆弱性を解決します。ログオンした攻撃者が、簡体字中国語版 Microsoft Pinyin IME 内のツール バーから Internet Explorer を起動すると、この脆弱性により、特権が昇格される可能性があります。攻撃者によりこの脆弱性が悪用された場合、カーネルモード内の任意のコードが実行される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全な管理者権限を持つ新たなアカウントを作成する可能性があります。この脆弱性で影響を受けるのは、Microsoft Pinyin IME 2010 の実装のみです。その他のバージョンの簡体字中国語版 IME およびその他の実装の IME は影響を受けません。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">カーネルモード ドライバーの脆弱性により、 特権が昇格される (2876315)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 7 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320630">MS13-077</a></td>
<td style="border:1px solid black;">Windows サービス コントロール マネージャーの脆弱性により、特権が昇格される (2872339)<br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、認証ユーザーが特別に細工されたアプリケーションを実行するように攻撃者が誘導した場合、特権の昇格が起こる可能性があります。この脆弱性を悪用するには、攻撃者は有効なログイン資格情報を所有し、ローカルでログオンするか、特別な細工がされたアプリケーションを実行するようにユーザーを誘導する必要があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318021">MS13-078</a></td>
<td style="border:1px solid black;">FrontPage の脆弱性により、情報漏えいが起こる (2825621)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft FrontPage に存在する 1 件の脆弱性を解決します。この脆弱性により、特別に細工された FrontPage ドキュメントをユーザーが開いた場合に情報漏えいが起こる可能性があります。この脆弱性は、自動的に悪用されることはありません。攻撃を成功させるためには、ユーザーを誘導して特別に細工されたドキュメントを開かせる必要があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320666">MS13-079</a></td>
<td style="border:1px solid black;">Active Directory の脆弱性により、サービス拒否が起こる (2853587)<br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Active Directory に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者が特別に細工したクエリを Lightweight Directory Access Protocol (LDAP) サービスに送信した場合、サービス拒否 (DoS) が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
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
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">SharePoint のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0081">CVE-2013-0081</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1315">CVE-2013-1315</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">MAC 無効の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1330">CVE-2013-1330</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">SharePoint XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3179">CVE-2013-3179</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">POST XSS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3180">CVE-2013-3180</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3847">CVE-2013-3847</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3848">CVE-2013-3848</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a> にも影響を及ぼします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3849">CVE-2013-3849</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3857">CVE-2013-3857</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a> にも影響を及ぼします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3858">CVE-2013-3858</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a><a href="http://go.microsoft.com/fwlink/?linkid=293350"></a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=307055">MS13-068</a></td>
<td style="border:1px solid black;">メッセージ証明書の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3870">CVE-2013-3870</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3201">CVE-2013-3201</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3202">CVE-2013-3202</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3203">CVE-2013-3203</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3204">CVE-2013-3204</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3205">CVE-2013-3205</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3206">CVE-2013-3206</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3207">CVE-2013-3207</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3208">CVE-2013-3208</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3209">CVE-2013-3209</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320631">MS13-069</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3845">CVE-2013-3845</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Internet Explorer 11 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320629">MS13-070</a></td>
<td style="border:1px solid black;">OLE プロパティの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3863">CVE-2013-3863</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=314046">MS13-071</a></td>
<td style="border:1px solid black;">Windows テーマ ファイルのリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-0810">CVE-2013-0810</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">XML の外部エンティティ解決の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3160">CVE-2013-3160</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3847">CVE-2013-3847</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a> にも影響を及ぼします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3848">CVE-2013-3848</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3849">CVE-2013-3849</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a> にも影響を及ぼします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3850">CVE-2013-3850</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3851">CVE-2013-3851</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3852">CVE-2013-3852</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3853">CVE-2013-3853</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3854">CVE-2013-3854</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3855">CVE-2013-3855</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3856">CVE-2013-3856</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3857">CVE-2013-3857</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a> にも影響を及ぼします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=299217">MS13-072</a></td>
<td style="border:1px solid black;">Word のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3858">CVE-2013-3858</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a> にも影響を及ぼします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1315">CVE-2013-1315</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は <a href="http://go.microsoft.com/fwlink/?linkid=293350">MS13-067</a> にも影響を及ぼします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a></td>
<td style="border:1px solid black;">Microsoft Office のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3158">CVE-2013-3158</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=293351">MS13-073</a></td>
<td style="border:1px solid black;">XML の外部エンティティ解決の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3159">CVE-2013-3159</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308989">MS13-074</a></td>
<td style="border:1px solid black;">Access のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3155">CVE-2013-3155</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308989">MS13-074</a></td>
<td style="border:1px solid black;">Access ファイル形式のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3156">CVE-2013-3156</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=308989">MS13-074</a></td>
<td style="border:1px solid black;">Access のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3157">CVE-2013-3157</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318022">MS13-075</a></td>
<td style="border:1px solid black;">中国語版 IME の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3859">CVE-2013-3859</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Win32k の複数フェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1341">CVE-2013-1341</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Win32k の複数フェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1342">CVE-2013-1342</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Win32k の複数フェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1343">CVE-2013-1343</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Win32k の複数フェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-1344">CVE-2013-1344</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Win32k の複数フェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3864">CVE-2013-3864</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Win32k の複数フェッチの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3865">CVE-2013-3865</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">1</a> - 悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320624">MS13-076</a></td>
<td style="border:1px solid black;">Win32k の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3866">CVE-2013-3866</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、Windows 8 と Windows Server 2012 R2 のサービス拒否の脆弱性です。<br />
<br />
Windows 8.1 と Windows Server 2012 R2 は影響を受けません。<br />
<br />
これは情報漏えいの脆弱性で、影響を受ける他のソフトウェア上で特権の昇格を引き起こす可能性があります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320630">MS13-077</a></td>
<td style="border:1px solid black;">サービス コントロール マネージャーのダブル フリーの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3862">CVE-2013-3862</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">2</a> - 悪用コードの作成困難</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=318021">MS13-078</a></td>
<td style="border:1px solid black;">XML の情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3137">CVE-2013-3137</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=320666">MS13-079</a></td>
<td style="border:1px solid black;">リモートの匿名 DoS の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2013-3868">CVE-2013-3868</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259">3</a> - 悪用コードの可能性低</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。<br />
<br />
Windows 8.1 と Windows Server 2012 R2 は影響を受けません。</td>
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
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
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
(2870699)  
(緊急)  
Internet Explorer 7   
(2870699)  
(緊急)  
Internet Explorer 8   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2876217)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2864063)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 3  
(2876315)  
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
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2870699)  
(緊急)  
Internet Explorer 7   
(2870699)  
(緊急)  
Internet Explorer 8   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2876217)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2864063)  
(重要)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2  
(2876315)  
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
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
(2870699)  
(警告)  
Internet Explorer 7  
(2870699)  
(警告)  
Internet Explorer 8  
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2876217)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2864063)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2876315)  
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
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2870699)  
(警告)  
Internet Explorer 7  
(2870699)  
(警告)  
Internet Explorer 8  
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2876217)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2864063)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2876315)  
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
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 6   
(2870699)  
(警告)  
Internet Explorer 7  
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2876217)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2864063)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2876315)  
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
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
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
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
Internet Explorer 7  
(2870699)  
(緊急)  
Internet Explorer 8  
(2870699)  
(緊急)  
Internet Explorer 9   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2864063)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2870699)  
(緊急)  
Internet Explorer 8  
(2870699)  
(緊急)  
Internet Explorer 9   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2864063)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
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
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
なし
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
Internet Explorer 7  
(2870699)  
(警告)  
Internet Explorer 8  
(2870699)  
(警告)  
Internet Explorer 9   
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2864063)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory サービス  
(2853587)  
(重要)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2870699)  
(警告)  
Internet Explorer 8  
(2870699)  
(警告)  
Internet Explorer 9   
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2864063)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory サービス  
(2853587)  
(重要)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2864063)  
(深刻度なし)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2876315)  
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
<th colspan="7">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
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
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2870699)  
(緊急)  
Internet Explorer 9   
(2870699)  
(緊急)  
Internet Explorer 10   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2872339)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2870699)  
(緊急)  
Internet Explorer 9   
(2870699)  
(緊急)  
Internet Explorer 10   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2872339)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
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
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2870699)  
(警告)  
Internet Explorer 9   
(2870699)  
(警告)  
Internet Explorer 10   
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2872339)  
(重要)
</td>
<td style="border:1px solid black;">
Active Directory サービス  
(2853587)  
(重要)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2872339)  
(重要)
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
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
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
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 8 for 32-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows 8 for 64-bit Systems  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
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
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2870699)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory サービス  
(2853587)  
(重要)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
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
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
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
なし
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
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10   
(2870699)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows RT  
(2876315)  
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
<th colspan="7">
Server Core インストール オプション
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-069](http://go.microsoft.com/fwlink/?linkid=320631)
</td>
<td style="border:1px solid black;">
[MS13-070](http://go.microsoft.com/fwlink/?linkid=320629)
</td>
<td style="border:1px solid black;">
[MS13-071](http://go.microsoft.com/fwlink/?linkid=314046)
</td>
<td style="border:1px solid black;">
[MS13-076](http://go.microsoft.com/fwlink/?linkid=320624)
</td>
<td style="border:1px solid black;">
[MS13-077](http://go.microsoft.com/fwlink/?linkid=320630)
</td>
<td style="border:1px solid black;">
[MS13-079](http://go.microsoft.com/fwlink/?linkid=320666)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な 深刻度
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
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)
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
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory サービス  
(2853587)  
(重要)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
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
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory サービス  
(2853587)  
(重要)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
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
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2872339)
</td>
<td style="border:1px solid black;">
Active Directory サービス  
(2853587)  
(重要)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
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
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2876315)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Active Directory サービス  
(2853587)  
(重要)  
Active Directory Lightweight Directory Service (AD LDS)  
(2853587)  
(重要)
</td>
</tr>
</table>
 
 

#### Microsoft Office スイートおよびソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="6">
Microsoft Office 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-068](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[MS13-072](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[MS13-073](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[MS13-074](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[MS13-075](http://go.microsoft.com/fwlink/?linkid=318022)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3  
(MSO)  
(2817474)  
(重要)  
Microsoft Word 2003 Service Pack 3  
(2817682)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2003 Service Pack 3  
(2810048)  
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
<th colspan="6">
Microsoft Office 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-068](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[MS13-072](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[MS13-073](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[MS13-074](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[MS13-075](http://go.microsoft.com/fwlink/?linkid=318022)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2007 Service Pack 3  
(2825999)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(MSO)  
(2760411)  
(重要)  
Microsoft Office 2007 Service Pack 3  
(MSPTLS)  
(2597973)  
(重要)  
Microsoft Word 2007 Service Pack 3  
(2767773)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(2760583)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Access 2007 Service Pack 3  
(2596825)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Microsoft Office 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-068](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[MS13-072](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[MS13-073](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[MS13-074](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[MS13-075](http://go.microsoft.com/fwlink/?linkid=318022)
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
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 1 (32 ビット版)  
(2794707)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 1 (32 ビット版)  
(2760769)  
(重要)  
Microsoft Word 2010 Service Pack 1 (32 ビット版)  
(2767913)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (32 ビット版)  
(2760597)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Access 2010 Service Pack 1 (32 ビット版)  
(2687423)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Pinyin IME 2010 (32-bit バージョン)  
(2687413)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 2 (32 ビット版)  
(2794707)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(2760769)  
(重要)  
Microsoft Word 2010 Service Pack 2 (32 ビット版)  
(2767913)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (32 ビット版)  
(2760597)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Access 2010 Service Pack 2 (32 ビット版)  
(2687423)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 1 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 1 (64 ビット版)  
(2794707)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 1 (64 ビット版)  
(2760769)  
(重要)  
Microsoft Word 2010 Service Pack 1 (64 ビット版)  
(2767913)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 1 (64 ビット版)  
(2760597)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Access 2010 Service Pack 1 (64 ビット版)  
(2687423)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Pinyin IME 2010 (64 ビット版)  
(2687413)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Outlook 2010 Service Pack 2 (64 ビット版)  
(2794707)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(2760769)  
(重要)  
Microsoft Word 2010 Service Pack 2 (64 ビット版)  
(2767913)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2010 Service Pack 2 (64 ビット版)  
(2760597)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Access 2010 Service Pack 2 (64 ビット版)  
(2687423)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Microsoft Office 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-068](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[MS13-072](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[MS13-073](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[MS13-074](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[MS13-075](http://go.microsoft.com/fwlink/?linkid=318022)
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
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
なし
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
対象外
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (32 ビット版)  
(2768017)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Access 2013 (32 ビット版)  
(2810009)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2013 (64 ビット版)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 (64 ビット版)  
(2768017)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Access 2013 (64 ビット版)  
(2810009)  
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
対象外
</td>
<td style="border:1px solid black;">
Microsoft Excel 2013 RT  
(2768017)  
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
<th colspan="6">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-068](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[MS13-072](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[MS13-073](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[MS13-074](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[MS13-075](http://go.microsoft.com/fwlink/?linkid=318022)
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
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Office for Mac 2011  
(2877813)  
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
<th colspan="6">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-068](http://go.microsoft.com/fwlink/?linkid=307055)
</td>
<td style="border:1px solid black;">
[MS13-072](http://go.microsoft.com/fwlink/?linkid=299217)
</td>
<td style="border:1px solid black;">
[MS13-073](http://go.microsoft.com/fwlink/?linkid=293351)
</td>
<td style="border:1px solid black;">
[MS13-074](http://go.microsoft.com/fwlink/?linkid=308989)
</td>
<td style="border:1px solid black;">
[MS13-075](http://go.microsoft.com/fwlink/?linkid=318022)
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
Microsoft Office 互換機能パック Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2760823)  
(重要)
</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2760588)  
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
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2817683)  
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
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(2760590)  
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
 

#### Microsoft サーバー ソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Portal Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-067](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Portal Server 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 2.0  
(2810061)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-067](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (32 ビット版)  
(2760420)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)
</td>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 3 (64 ビット版)  
(2760420)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-067](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 1 (wss)  
(2810067)  
(緊急)  
Microsoft SharePoint Server 2010 Service Pack 1 (coreserver)  
(2817393)  
(緊急)  
Microsoft SharePoint Server 2010 Service Pack 1 (wosrv)  
(2817372)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2 (wss)  
(2810067)  
(緊急)  
Microsoft SharePoint Server 2010 Service Pack 2 (coreserver)  
(2817393)  
(緊急)  
Microsoft SharePoint Server 2010 Service Pack 2 (wosrv)  
(2817372)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2013
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-067](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013
</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2013  
(2817315)  
(重要)  
Microsoft SharePoint Server 2013 (coreserverloc)  
(2810083)  
(重要)  
Microsoft SharePoint Server 2013 (wacserver)  
(2817305)  
(重要)
</td>
</tr>
</table>
 
MS13-067 に関する注意事項

「影響を受けるソフトウェア」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。 このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft Office Services および Web Apps

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft SharePoint Server 2007
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-067](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32 ビット版)
</td>
<td style="border:1px solid black;">
Excel Services  
(2760589)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64 ビット版)
</td>
<td style="border:1px solid black;">
Excel Services  
(2760589)  
(重要)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft SharePoint Server 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-067](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Excel Services  
(2760595)  
(緊急)  
Microsoft Business Productivity Servers  
(2553408)  
(緊急)  
Word Automation Services  
(2760755)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(2760595)  
(緊急)  
Microsoft Business Productivity Servers  
(2553408)  
(緊急)  
Word Automation Services  
(2760755)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2010
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-067](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Excel Web App 2010 Service Pack 1  
(2760594)  
(緊急)  
Microsoft Word Web App 2010 Service Pack 1  
(2817384)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Excel Web App 2010 Service Pack 2  
(2760594)  
(緊急)  
Microsoft Word Web App 2010 Service Pack 2  
(2817384)  
(緊急)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Office Web Apps 2013
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-067](http://go.microsoft.com/fwlink/?linkid=293350)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013  
(2817305)  
(重要)
</td>
</tr>
</table>
 
MS13-067 に関する注意事項

「影響を受けるソフトウェア」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。 このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### プロダクティビティ ソフトウェア

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft FrontPage 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS13-078](http://go.microsoft.com/fwlink/?linkid=318021)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft FrontPage 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft FrontPage 2003 Service Pack 3  
(2825621)  
(重要)
</td>
</tr>
</table>
 

検出および展開ツールとガイダンス
--------------------------------

<span></span>
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](http://go.microsoft.com/fwlink/?linkid=69903)を参照してください。[TechNet セキュリティ TechCenter](http://go.microsoft.com/fwlink/?linkid=21171) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](http://go.microsoft.com/fwlink/?linkid=85102)を参照してください。この情報には「セキュリティ更新プログラム」リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索で容易に見つけられます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](http://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](http://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ番号 (たとえば “MS13-001” など) を使用して検索することにより、バスケットに適用可能な更新プログラムをすべて追加することができ (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](http://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](http://support.microsoft.com/kb/961747/ja) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](http://technet.microsoft.com/ja-jp/wsus/default) の Web サイトを参照してください。

System Center Configuration Manager

System Center Configuration Manager のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。System Center Configuration Manager で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

System Center Configuration Manager の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。System Center Configuration Manager のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。System Center Configuration Manager の詳細については、[System Center テクニカル リソース](http://technet.microsoft.com/ja-jp/systemcenter/bb980621)を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager については、前のセクション「System Center Configuration Manager」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](http://technet.microsoft.com/ja-jp/systemcenter/bb545936) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](http://www.microsoft.com/downloads/ja-jp/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet.microsoft.com/ja-jp/library/cc749197) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](http://support.microsoft.com/kb/894199/ja): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](http://support.microsoft.com/kb/913086/ja) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](http://go.microsoft.com/fwlink/?linkid=21127)を表します。

MS13-067

-   Microsoft Office のメモリ破損の脆弱性 (CVE-2013-1315) を報告してくださった [CERT/CC](http://www.cert.org/) の Will Dormann 氏
-   MAC 無効の脆弱性 (CVE-2013-1330) を報告してくださった Alexandre Herzog 氏
-   SharePoint XSS の脆弱性 (CVE-2013-3179) を報告してくださった Vulnerability Research Laboratory の Benjamin Kunz Mejri 氏
-   Microsoft Word の複数メモリ破損の脆弱性 (CVE-2013-3847、CVE-2013-3848、CVE-2013-3849、CVE-2013-3857、CVE-2013-3858) を報告してくださった [Google Security Team](http://www.google.com/) の Mateusz Jurczyk、Ivan Fratric、および Ben Hawkes 氏

MS13-068

-   メッセージ証明書の脆弱性 (CVE-2013-3870) について報告してくださった [n.runs AG](https://www.nruns.com/) の Alexander Klink 氏

MS13-069

-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3201) を報告してくださった Jose Antonio Vazquez Gonzalez 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3202) を報告してくださった Jose Antonio Vazquez Gonzalez 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3203) を報告してくださった Arthur Gerkis 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3204) を報告してくださった [Google Security Team](http://www.google.com/) の Ivan Fratric 氏と Ben Hawkes 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3205) を報告してくださった[Corelan](http://www.corelangcv.com/) の Peter 'corelanc0d3r' Van Eeckhoutte 氏
-   Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3205) を報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Bo Qu 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3206) を報告してくださった Arthur Gerkis 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3207) を報告してくださった Arthur Gerkis 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3208) を報告してくださった Arthur Gerkis 氏
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3209) を報告してくださった匿名のリサーチャー
-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して Internet Explorer のメモリ破損の脆弱性 (CVE-2013-3845) を報告してくださった Jose Antonio Vazquez Gonzalez 氏

MS13-070

-   [HP](http://www.hpenterprisesecurity.com/products) の [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して OLE プロパティの脆弱性 (CVE-2013-3863) を報告してくださった G. Geshev 氏

MS13-071

-   [VeriSign iDefense Labs](http://labs.idefense.com/) と協力して Windows テーマ ファイルのリモート コード実行の脆弱性 (CVE-2013-0810) を報告してくださった Eduardo Prado 氏

MS13-072

-   XML 外部エンティティ解決の脆弱性 (CVE-2013-3160) を報告してくださった [Positive Technologies](http://www.ptsecurity.com/) の Timur Yunusov 氏、Alexey Osipov 氏、および Ilya Karpov 氏
-   Microsoft Word の複数メモリ破損の脆弱性 (CVE-2013-3847、CVE-2013-3848、CVE-2013-3849、CVE-2013-3850、CVE-2013-3851、CVE-2013-3852、CVE-2013-3853、CVE-2013-3854、CVE-2013-3855、CVE-2013-3856、CVE-2013-3857、CVE-2013-3858) を報告してくださった [Google Security Team](http://www.google.com/) の Mateusz Jurczyk 氏、Ivan Fratric 氏、および Ben Hawkes 氏

MS13-073

-   Microsoft Office のメモリ破損の脆弱性 (CVE-2013-1315) を報告してくださった [CERT/CC](http://www.cert.org/) の Will Dormann 氏
-   Microsoft Office のメモリ破損の脆弱性 (CVE-2013-3158) を報告してくださった [CERT/CC](http://www.cert.org/) の Will Dormann 氏
-   XML 外部エンティティ解決の脆弱性 (CVE-2013-3159) を報告してくださった [Positive Technologies](http://www.ptsecurity.com/) の Timur Yunusov 氏、Alexey Osipov 氏、および Ilya Karpov 氏

MS13-074

-   Access のメモリ破損の脆弱性 (CVE-2013-3155) を報告してくださった [Secunia SVCRP](http://secunia.com/) の Kaveh Ghaemmaghami 氏
-   Access ファイル形式のメモリ破損の脆弱性 (CVE-2013-3156) を報告してくださった [Secunia SVCRP](http://secunia.com/) の Kaveh Ghaemmaghami 氏
-   Access のメモリ破損の脆弱性 (CVE-2013-3157) を報告してくださった [Secunia SVCRP](http://secunia.com/) の Kaveh Ghaemmaghami 氏

MS13-075

-   中国語版 IME の脆弱性 (CVE-2013-3859) を報告してくださった [VulnHunt](http://www.vulnhunt.com/) の Wei Wang 氏

MS13-076

-   Win32k の複数フェッチの脆弱性 (CVE-2013-1341) を報告してくださった [Google Inc](http://www.google.com/) の [Gynvael Coldwind](http://gynvael.coldwind.pl/) 氏と [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 氏
-   Win32k の複数フェッチの脆弱性 (CVE-2013-1342) を報告してくださった [Google Inc](http://www.google.com/) の [Gynvael Coldwind](http://gynvael.coldwind.pl/) 氏と [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 氏
-   Win32k の複数フェッチの脆弱性 (CVE-2013-1343) を報告してくださった [Google Inc](http://www.google.com/) の [Gynvael Coldwind](http://gynvael.coldwind.pl/) 氏と [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 氏
-   Win32k の複数フェッチの脆弱性 (CVE-2013-1344) を報告してくださった [Google Inc](http://www.google.com/) の [Mateusz "j00ru" Jurczyk 氏](http://j00ru.vexillium.org/)
-   Win32k の複数フェッチの脆弱性 (CVE-2013-3864) を報告してくださった [Google Inc](http://www.google.com/) の [Gynvael Coldwind](http://gynvael.coldwind.pl/) 氏と [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 氏
-   Win32k の複数フェッチの脆弱性 (CVE-2013-3865) を報告してくださった [Google Inc](http://www.google.com/) の [Gynvael Coldwind](http://gynvael.coldwind.pl/) 氏と [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org/) 氏
-   Win32k の特権の昇格の脆弱性 (CVE-2013-3866) を報告してくださった [Qihoo 360 Security Center](http://www.360.cn/)

MS13-078

-   「XML の情報の漏えいの脆弱性」(CVE-2013-3137) を報告してくださった [Positive Technologies](http://www.ptsecurity.com/) の Timur Yunusov 氏

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)
-   Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   国ごとのローカルサポート:[Microsoft サポート](http://support.microsoft.com/common/international.aspx)

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2013/09/11):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2013/11/07): MS13-067 について、Microsoft Office Web Apps Server 2013 (2817305) 更新プログラムの製品名を修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
