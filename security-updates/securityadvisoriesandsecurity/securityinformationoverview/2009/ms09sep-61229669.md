---
TOCTitle: 'MS09-SEP'
Title: 2009 年 9 月のセキュリティ情報
ms:assetid: 'ms09-sep'
ms:contentKeyID: 61229669
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-sep(v=Security.10)'
--- Summary

2009 年 9 月のセキュリティ情報
==============================

公開日: 2009年9月9日 | 最終更新日: 2009年11月11日

**バージョン:** 1.0

[![](../../images/Dn627248.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/dd251169.aspx)[![](../../images/Dn627248.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------


[MS09-045 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-045e.mspx)

[MS09-046 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-046e.mspx)

[MS09-047 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-047e.mspx)

[MS09-048 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-048e.mspx)

[MS09-049 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-049e.mspx)

このセキュリティ情報は 2009 年 9 月に公開したセキュリティ情報の一覧です。

2009 年 9 月のセキュリティ情報の公開により、2009 年 9 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 9 月 9 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 9 月 9 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[9 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407486&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----


次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細は、次の影響を受けるソフトウェアのセクションをご覧ください。

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID 番号</th>
<th style="border:1px solid black;" >タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動情報</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-045">MS09-045</a></td>
<td style="border:1px solid black;"><strong>JScript スクリプト エンジンの脆弱性により、リモートでコードが実行される (971961)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された JScript スクリプト エンジンに存在する脆弱性を解決します。この脆弱性により、ユーザーが特別な細工がされたファイルを開いた場合、または特別な細工がされた Web サイトを訪問し、不正な形式のスクリプトを呼び出した場合、リモートでコードが実行される可能性があります。ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-049">MS09-049</a></td>
<td style="border:1px solid black;"><strong>ワイヤレス LAN 自動構成サービスの脆弱性により、リモートでコードが実行される (970710)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告されたワイヤレス LAN 自動構成 (WLAN AutoConfig) サービスの脆弱性を解決します。 この脆弱性によりで、ワイヤレス ネットワーク インターフェイスが有効にされているクライアントまたはサーバーが特別な細工がされたワイヤレス フレームを受信した受け取った場合、リモートでコードが実行される可能性があります。 無線 LAN カードが有効でないコンピューターはこの脆弱性による危険にはさらされません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-047">MS09-047</a></td>
<td style="border:1px solid black;"><strong>Windows Media Format の脆弱性により、リモートでコードが実行される (973812)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Windows Media Format に存在する 2 件の脆弱性を解決します。いずれの脆弱性についても、特別に細工されたメディア ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。 ユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-048">MS09-048</a></td>
<td style="border:1px solid black;"><strong>Windows TCP/IP の脆弱性により、リモートでコードが実行される (967723)</strong><br />
<br />
このセキュリティ更新プログラムは、伝送制御プロトコル/インターネット プロトコル (TCP/IP) の処理に存在する非公開で報告されたいくつかの脆弱性を解決します。この脆弱性で、攻撃者が特別に細工された TCP/IP パケットをネットワーク上で、リスニング サービスが含まれているコンピューターに送信した場合、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-046">MS09-046</a></td>
<td style="border:1px solid black;"><strong>DHTML 編集コンポーネントの Active X コントロールの脆弱性により、リモートでコードが実行される (956844)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された DHTML 編集コンポーネントの ActiveX コントロールに存在する脆弱性を解決します。攻撃者は特別な細工がされた Web ページを作成し、この脆弱性を悪用する可能性があります。 この脆弱性では、ユーザーが Web ページを表示すると、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ログオンしたユーザーと同じユーザー権限を取得する可能性があります。コンピューターで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  

次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号および CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**  
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID 番号                                            | セキュリティ情報タイトル                                                                              | CVE ID                                                                           | Exploitability Index の評価                                                                         | 注意事項                                                                                                                         |  
|---------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-045](http://technet.microsoft.com/security/bulletin/ms09-045) | JScript スクリプト エンジンの脆弱性により、リモートでコードが実行される (971961)                      | [CVE-2009-1920](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1920) | [**1 - 安定した悪用コードの可能性**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                           |  
| [MS09-046](http://technet.microsoft.com/security/bulletin/ms09-046) | DHTML 編集コンポーネントの Active X コントロールの脆弱性により、リモートでコードが実行される (956844) | [CVE-2009-2519](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2519) | [**2 - 不安定な悪用コードの可能性**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                           |  
| [MS09-047](http://technet.microsoft.com/security/bulletin/ms09-047) | Windows Media Format の脆弱性により、リモートでコードが実行される (973812)                            | [CVE-2009-2498](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2498) | [**1 - 安定した悪用コードの可能性**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                           |  
| [MS09-047](http://technet.microsoft.com/security/bulletin/ms09-047) | Windows Media Format の脆弱性により、リモートでコードが実行される (973812)                            | [CVE-2009-2499](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2499) | [**1 - 安定した悪用コードの可能性**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                           |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP の脆弱性により、リモートでコードが実行される (967723)                                  | [CVE-2008-4609](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4609) | [**3 - 機能する見込みのない悪用コード**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これはメモリを消費する種類のサービス拒否です。                                                                                   |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP の脆弱性により、リモートでコードが実行される (967723)                                  | [CVE-2009-1925](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1925) | [**2 - 不安定な悪用コードの可能性**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 悪用コードが機能する可能性はありますが、それが信頼できるものである可能性は低いです。起こる可能性の高い影響は、サービス拒否です。 |  
| [MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) | Windows TCP/IP の脆弱性により、リモートでコードが実行される (967723)                                  | [CVE-2009-1926](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1926) | [**3 - 機能する見込みのない悪用コード**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | これはメモリを消費する種類のサービス拒否です。                                                                                   |  
| [MS09-049](http://technet.microsoft.com/security/bulletin/ms09-049) | ワイヤレス LAN 自動構成サービスの脆弱性により、リモートでコードが実行される (970710)                  | [CVE-2009-1132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1132) | [**2 - 不安定な悪用コードの可能性**](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | ヒープの保護により、この脆弱性の悪用が困難となります。                                                                           |
  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  

**この表はどのように使用しますか?**  
  
この表を使用して、セキュリティ情報のリリース時に、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、セキュリティ更新プログラムがリリースされるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、脆弱性の深刻度も記載されています。
  
**注:** ひとつの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[JScript 5.1 および JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=2bb3af8d-f36c-4497-9f48-fc59bcff2583&displaylang=ja)  
(KB971961)  
(緊急)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=b2773db5-b17d-4b98-b4e2-219b23854abd&displaylang=ja)  
(KB975542)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=02b9dc42-38c2-44b1-a77c-34854f4a86c4&displaylang=ja)  
(KB968816)  
(緊急)
</td>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 <sup>[3]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=6dd4b0f8-6b54-49a6-a6df-9420f9fd3333&displaylang=ja)  
(緊急)
</td>
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**注意**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 上の JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=0af373b2-2240-4079-a748-a38d1bc06f39&displaylang=ja)  
(KB971961)  
(緊急)  
[Windows XP Service Pack 2 上の JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a&displaylang=ja) <sup>[1]</sup>
(KB971961)  
(緊急)  
[Windows XP Service Pack 3 上の JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=c933377d-e0bc-4334-bc75-029045d7a62a&displaylang=ja)  
(KB971961)  
(緊急)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=992602d8-d857-41cf-b7b1-527afdc1dc0f&displaylang=ja) <sup>[2]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 および Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=6ffc081e-f892-4818-acb9-6d79e15d473c&displaylang=ja)  
(KB968816)  
(緊急)  
(Windows XP Service Pack 2 のみ)  
[Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 および Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=31585f5a-9aaa-40da-b15a-11284b4b800c&displaylang=ja)  
(KB968816)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3 <sup>[3]</sup>
(注意)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8523d5be-88a2-4124-9b02-660f612e2a12&displaylang=ja)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=0d671004-da4e-4dbd-a066-861b53b0c59c&displaylang=ja)  
(KB971961)  
(緊急)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=9aae426d-ee9a-4736-b0a2-e0f8890a6895&displaylang=ja) <sup>[1]</sup>
(KB971961)  
(緊急)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=00bae02a-64eb-4b91-965f-da2dc987a2ff&displaylang=ja) <sup>[2]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=3780d565-d027-4f54-8fc0-05f5c3c6ba1a&displaylang=ja)  
(KB968816)  
(緊急)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c&displaylang=ja)  
(KB968816)  
(緊急)  
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=9a465f92-3067-4a5a-9882-1fc2cf796c99&displaylang=ja)  
(KB968816)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2 <sup>[3]</sup>
(注意)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dbc33f6b-61bf-409a-89b5-60002192e0e0&displaylang=ja)  
(緊急)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=6acc9d2d-b71f-4b5c-9aea-b217b6ae240b&displaylang=ja)  
(KB971961)  
(緊急)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=6af5d034-fd89-42e2-bc18-d44b7a6b0a85&displaylang=ja) <sup>[1]</sup>
(KB971961)  
(緊急)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=ecf9f7e2-3104-4de2-8b3d-99dcdcae6e62&displaylang=ja) <sup>[2]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=4ab34e3d-34cb-4e35-a2da-b348ace8a8f7&displaylang=ja)  
(KB968816)  
(緊急)  
[Windows Media Services 9.1](http://www.microsoft.com/downloads/details.aspx?familyid=61cd0581-c36e-4da6-ae95-41609adbe922&displaylang=ja)  
(KB972554)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48d82036-2fde-4bb0-a60e-92eed83ddc3f&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7478f73f-dd20-4cfa-a650-4c84f37ada2f&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=d0de3ab1-73e9-4a09-841f-81ade41a8c81&displaylang=ja)  
(KB971961)  
(緊急)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=8f48bc05-ffac-4a21-8d21-dd20355cda8a&displaylang=ja) <sup>[1]</sup>
(KB971961)  
(緊急)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=643f9e2f-2e5b-48dd-b1a0-22ccb633ed18&displaylang=ja) <sup>[2]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=8654ee33-6083-447f-ae5b-43ef8d8b613d&displaylang=ja)  
(KB968816)  
(緊急)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ce515188-db3c-4694-85da-177c8f76b68c&displaylang=ja)  
(KB968816)  
(緊急)  
[Windows Media Services 9.1](http://www.microsoft.com/downloads/details.aspx?familyid=67c46f26-e6df-4ba2-9c03-1590b31e454c&displaylang=ja)  
(KB972554)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0298ddf-026e-4137-8197-ed9d9b889825&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=88bf502d-1a7c-447a-ac4c-401e1698669b&displaylang=ja)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[JScript 5.6](http://www.microsoft.com/downloads/details.aspx?familyid=e78cf021-54f5-4526-b5f0-f781aebf9d72&displaylang=ja)  
(KB971961)  
(緊急)  
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=fb1ca290-cea4-49c0-a37e-613a654bff3c&displaylang=ja) <sup>[1]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=c948c4d8-5788-4c1a-9fb6-a969b06a888d&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=8d881ff8-f51f-4476-8cb6-2bebd5b2047f&displaylang=ja)  
(警告)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=bcb12e57-f5d6-4b4e-88ab-13c28137f11a&displaylang=ja)  
(KB971961)  
(緊急)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=80e7390f-df39-4d99-b2e1-01c7f6a951bb&displaylang=ja) <sup>[2]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e9fe967f-d78d-43c2-bbcc-5098bd20267e&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 および Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=d2bdefcc-f6b9-47c3-a55d-a4f33f967828&displaylang=ja)  
(KB968816)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d72f845-9feb-4685-a669-f9d6ab54f9ed&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=8b1b76d5-a6b0-4c2f-8768-e55e82c2c118&displaylang=ja)  
(KB971961)  
(緊急)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=24457cdd-1973-40c9-9c2d-c1a75fdfa7fa&displaylang=ja) <sup>[2]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f93470bd-2e6d-4340-88c6-bb212baf750a&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 および Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=97f00b25-fb8f-4300-80c0-c63179f32182&displaylang=ja)  
(KB968816)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b2930ff1-5f0a-4a5d-bf2a-9fb76dd8da63&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-045**](http://technet.microsoft.com/security/bulletin/ms09-045)
</td>
<td style="border:1px solid black;">
[**MS09-049**](http://technet.microsoft.com/security/bulletin/ms09-049)
</td>
<td style="border:1px solid black;">
[**MS09-047**](http://technet.microsoft.com/security/bulletin/ms09-047)
</td>
<td style="border:1px solid black;">
[**MS09-048**](http://technet.microsoft.com/security/bulletin/ms09-048)
</td>
<td style="border:1px solid black;">
[**MS09-046**](http://technet.microsoft.com/security/bulletin/ms09-046)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=df88e6e5-78d3-4fa6-858d-b935d812cada&displaylang=ja)\*  
(KB971961)  
(緊急)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=e7b07be6-a4f8-4847-9c55-9b3d2965fa77&displaylang=ja) <sup>[2]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ac3f6800-bc3e-4b35-a482-54e1a2da1ab5&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 および Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=9c111bff-aff6-4ff7-81f6-e736cfcbe3ed&displaylang=ja)\*\*  
(KB968816)  
(緊急)  
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=2801f69b-37d0-4d0f-9632-31382b824d36&displaylang=ja)\*  
(KB972554)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=35c1d5a9-a953-4fc6-90c0-d2358c7b89e6&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=f584f8ca-f6b1-4285-a44c-3df5e51e75de&displaylang=ja)\*  
(KB971961)  
(緊急)  
[JScript 5.8](http://www.microsoft.com/downloads/details.aspx?familyid=9eddbb89-4178-49c2-836a-2d292fe50936&displaylang=ja) <sup>[2]</sup>
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d1b9b4f-bf35-44aa-a660-afb2ef2c9e30&displaylang=ja)\*\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11 および Microsoft Media Foundation](http://www.microsoft.com/downloads/details.aspx?familyid=59615c8b-a07f-4326-836d-f17b2fcc4695&displaylang=ja)\*\*  
(KB968816)  
(緊急)  
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=7fad3793-174f-46db-9d0a-873a0ea8be65&displaylang=ja)\*  
(KB972554)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e46822e-f79d-492d-ad01-ee680ad324f5&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[JScript 5.7](http://www.microsoft.com/downloads/details.aspx?familyid=b84fca1d-914d-45af-a48c-d9bc5d20c6b7&displaylang=ja)  
(KB971961)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ac76ee2-b1b6-4300-9cba-af33d9dd54eb&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 に関する注意**

**\*Windows Server 2008 Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度でこの更新プログラムが適用されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 の特定のエディションには適用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

**\*\*Windows Server 2008 Server Core インストールは影響を受けません。** この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用して Windows Server 2008 をインストールした場合、サポートされているエディションの Windows Server 2008 に影響を与えません。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

**MS09-045 のセキュリティ情報に関する注意**

<sup>[1]</sup> Internet Explorer 7 がインストールされている場合

<sup>[2]</sup> Internet Explorer 8 がインストールされている場合

**MS09-048 のセキュリティ情報に関する注意**

<sup>[3]</sup> 利用可能な更新プログラムはありません。詳細情報は、[MS09-048](http://technet.microsoft.com/security/bulletin/ms09-048) の「このセキュリティ更新プログラムに関するよく寄せられる質問 (FAQ)」のセクションをご覧ください。

検出および展開ツールとガイダンス
--------------------------------


**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**注:** 2009 年 8 月 1 日より、マイクロソフトは Office Update および Office Update Inventory Tool のサポートを終了します。Microsoft Office 製品用の最新の更新プログラムを引き続き入手するためには、[Microsoft Update](http://update.microsoft.com/microsoftupdate/) をご利用ください。詳細情報は、[About Microsoft Office Update: Frequently Asked Questions](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英語情報) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトはセキュリティ更新プログラムについての検出および適用のガイダンスを提供します。このガイダンスは、IT プロフェッショナルが各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [961747](http://support.microsoft.com/kb/961747) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2009 年). すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS09-045 で説明している問題について報告してくださった Tipping Point の [Zero Day Initiative](http://www.zerodayinitiative.com/) に協力している [team509](http://www.team509.com/) の Ling 氏および Wushi 氏
-   MS09-046 で説明している問題について報告してくださった [Google Inc.](http://www.google.com/) の Tavis Ormandy 氏
-   MS09-047 で説明している問題について報告してくださった [NGS Software](http://www.ngssoftware.com/) の Peter Winter-Smith 氏
-   MS09-047 で説明している問題について報告してくださったアリス・キャロル ファンクラブの野口博司氏
-   MS09-048 で説明している問題について報告してくださった [Outpost24](http://www.outpost24.com/) の Jack C. Louis 氏
-   MS09-048 で説明している問題について報告してくださった [Recurity Labs GmbH](http://www.recurity-labs.com/) の Fabian Yamaguchi 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/09/09: このセキュリティ情報ページを公開しました。
-   2009/09/10: セキュリティ情報 MS09-048 の「影響を受けるソフトウェア」の一覧に、Windows XP Service Pack 2、Windows XP Service Pack 3 および Windows XP Professional x64 Edition Service Pack 2 を追加しました。セキュリティ情報 MS09-048 の「このセキュリティ更新プログラムに関するよく寄せられる質問 (FAQ)」の説明をご覧ください。このセキュリティ情報で提供しているセキュリティ更新プログラムに変更はありません。
-   2009/11/11: セキュリティ情報 MS09-045 の「影響を受けるソフトウェア」の一覧に Microsoft Windows 2000 Service Pack 4 上の JScript 5.7 を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
