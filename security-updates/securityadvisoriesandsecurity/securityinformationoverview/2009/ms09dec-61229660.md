---
TOCTitle: 'MS09-DEC'
Title: 2009 年 12 月のセキュリティ情報
ms:assetid: 'ms09-dec'
ms:contentKeyID: 61229660
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-dec(v=Security.10)'
--- Summary

2009 年 12 月のセキュリティ情報
===============================

公開日: 2009年12月9日 | 最終更新日: 2010年1月14日

**バージョン:** 1.0

[![](../../images/Dn627239.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/dd251169.aspx)[![](../../images/Dn627239.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------


[MS09-069 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-069e.mspx)

[MS09-070 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-070e.mspx)

[MS09-071 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-071e.mspx)

[MS09-072 : Internet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-072e.mspx)

[MS09-073 : Windows および Office の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-073e.mspx)

[MS09-074 : Project の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-074e.mspx)

このセキュリティ情報は 2009 年 12 月 9 日に公開したセキュリティ情報の一覧です。

2009 年 12 月 9 日のセキュリティ情報の公開により、2009 年 12 月 4 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 12 月 9 日 の午後 (日本時間) に配信予定です。この Web キャストでは、月例セキュリティ更新プログラムの適用優先順位に関する情報についても提供します。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 12 月 9 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[12 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407802&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----


次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細は、次の**「影響を受けるソフトウェアおよびダウンロード先」**のセクションをご覧ください。

 
<p></p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報番号</th>
<th style="border:1px solid black;" >タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動情報</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-071">MS09-071</a></td>
<td style="border:1px solid black;"><strong>インターネット認証サービスの脆弱性により、リモートでコードが実行される (974318)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性で、PEAP 認証要求の処理時に、インターネット認証サービス サーバーにより受信されたメッセージが不正確にメモリにコピーされた場合、リモートでコードが実行される可能性があります。Windows Server 2008 上で、インターネット認証サービスはネットワーク ポリシー サーバー (NPS) に置き替わります。これらの脆弱性のいずれかを攻撃者が悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。インターネット認証サービスまたはネットワーク ポリシー サーバーを使用しているサーバーが、MS-CHAP v2 を使用する PEAP 認証を使用している場合のみ、この脆弱性の影響を受けます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-074">MS09-074</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Project の脆弱性により、リモートでコードが実行される (967183)</strong><br />
<br />
この更新プログラムは非公開で報告された Microsoft Office Project に存在する 1 件の脆弱性を解決します。この脆弱性は、特別に細工された Project ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、影響を受けるシステムを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-072">MS09-072</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (976325)</strong><br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する非公開で報告された 4 件の脆弱性と、一般に公開された 1 件の脆弱性を解決します。この脆弱性では、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。Microsoft Active Template Library (ATL) ヘッダーに組み込まれた ActiveX コントロールにより、リモートでコードが実行される可能性があります。この脆弱性については、マイクロソフト セキュリティ アドバイザリ (973882) およびマイクロソフト セキュリティ情報 MS09-035 で説明しています。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-069">MS09-069</a></td>
<td style="border:1px solid black;"><strong>Local Security Authority Subsystem Service (LSASS) の脆弱性により、サービス拒否が起こる (974392)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性では、リモートで認証された攻撃者が、インターネット プロトコル セキュリティ (IPsec) を介して通信中に、特別に細工した ISAKMP メッセージを、影響を受けるシステムの Local Security Authority Subsystem Service (LSASS) に送信した場合、サービス拒否が起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-070">MS09-070</a></td>
<td style="border:1px solid black;"><strong>Active Directory フェデレーション サービスの脆弱性により、リモートでコードが実行される (971726)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。これらのうちより深刻な脆弱性で、攻撃者が特別な細工をした HTTP リクエストを ADFS 対応の Web サーバーに送信した場合、リモートでコードが実行される可能性があります。これらのいずれかの脆弱性が悪用されるには、認証されたユーザーであることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-073">MS09-073</a></td>
<td style="border:1px solid black;"><strong>ワードパッドおよび Office テキスト コンバーターの脆弱性により、リモートでコードが実行される (975539)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft ワードパッドおよび Microsoft Office テキスト コンバーターに存在する非公開で報告された脆弱性を解決します。特別に細工された Word 97 ファイルがワードパッドまたは Microsoft Office Word で開かれると、この脆弱性により、リモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用し、ユーザーと同じ特権を取得する可能性があります。コンピューターに対する特権が少ないユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  

次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号および CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**  
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID 番号                                            | 脆弱性タイトル                                                            | CVE ID                                                                           | Exploitability Index の評価                                                                     | 注意事項                                                                                                                                                                                                                                                                                                   |  
|---------------------------------------------------------------------|---------------------------------------------------------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-069](http://technet.microsoft.com/security/bulletin/ms09-069) | Local Security Authority Subsystem Service (LSASS) のリソース消費の脆弱性 | [CVE-2009-3675](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3675) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | この脆弱性により、リモートでコードが実行されることはありませんが、リモートで認証された攻撃者がこの脆弱性を悪用しようとした場合にサービス拒否が起こる可能性があります。                                                                                                                                     |  
| [MS09-070](http://technet.microsoft.com/security/bulletin/ms09-070) | ADFS のシングル サイン オンのなりすましの脆弱性                           | [CVE-2009-2508](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2508) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | この脆弱性により、なりすましが起こる可能性がありますが、リモートでコードが実行されることはありません。                                                                                                                                                                                                     |  
| [MS09-070](http://technet.microsoft.com/security/bulletin/ms09-070) | ADFS でリモートでコードが実行される脆弱性                                 | [CVE-2009-2509](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2509) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | この脆弱性は、認証された攻撃者にのみ悪用可能です。                                                                                                                                                                                                                                                         |  
| [MS09-071](http://technet.microsoft.com/security/bulletin/ms09-071) | インターネット認証サービスのメモリ破損の脆弱性                            | [CVE-2009-2505](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2505) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | リモートでコードが実行される可能性は限定されています。最も可能性の高い影響はサービス拒否です。                                                                                                                                                                                                             |  
| [MS09-071](http://technet.microsoft.com/security/bulletin/ms09-071) | MS-CHAP 認証バイパスの脆弱性                                              | [CVE-2009-3677](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3677) | [3 - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | この脆弱性によりリモートでコードが実行される可能性はありませんが、ネットワーク認証のすり抜けにより、特権が昇格される可能性があります。                                                                                                                                                                     |  
| [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) | ATL COM の初期化の脆弱性                                                  | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | なし                                                                                            | この脆弱性は [2009 年 7 月のセキュリティ情報のサマリページ](http://technet.microsoft.com/security/bulletin/ms09-jul)で既に悪用可能性指標の評価が提供されていました。それはこの脆弱性が [MS09-035 のセキュリティ情報](http://technet.microsoft.com/security/bulletin/ms09-035)で最初に解決されたためです。) |  
| [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) | 初期化されていないメモリ破損の脆弱性                                      | [CVE-2009-3671](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3671) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                     |  
| [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) | HTML オブジェクトのメモリ破損の脆弱性                                     | [CVE-2009-3672](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3672) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                     |  
| [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) | 初期化されていないメモリ破損の脆弱性                                      | [CVE-2009-3673](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3673) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                     |  
| [MS09-072](http://technet.microsoft.com/security/bulletin/ms09-072) | 初期化されていないメモリ破損の脆弱性                                      | [CVE-2009-3674](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3674) | [1 - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                     |  
| [MS09-073](http://technet.microsoft.com/security/bulletin/ms09-073) | ワードパッドおよび Office テキスト コンバーターのメモリ破損の脆弱性       | [CVE-2009-2506](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2506) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                     |  
| [MS09-074](http://technet.microsoft.com/security/bulletin/ms09-074) | Project のメモリ検証の脆弱性                                              | [CVE-2009-0102](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0102) | [2 - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                                                                                                                                                                                                                                     |
  
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
[**MS09-071**](http://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5b02d10d-1abd-4d68-826b-71dad543657a)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0cf37247-505a-4dc2-aad7-c8cb1a63b57a)  
(緊急)  
[Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7fb6261c-6895-4f79-be2c-bb110874a19c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=560e01db-5f59-4ef1-9406-f5d7e0fd4128)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=50936f51-b0a9-4e94-85bf-93f9ad74fdd1)  
(KB973904)  
(重要)
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
[**MS09-071**](http://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4d294be6-19d1-43b5-9c75-f9d30699a2e7)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=facab13f-ea31-4c71-be4c-24e44ded174f)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=def2c038-3b03-4162-a563-a6ebec756f37)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6c003629-77bf-4735-bd4a-c37c4386f869)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5448b168-6bf7-4bae-9627-b88d76c4d5c5)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c090c4c2-c277-4d8c-91e1-28286bc5443e)  
(KB973904)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=17b5206d-61e9-4663-afc7-80e98bf4d618)  
(警告)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a253c19a-c808-4115-8bd0-cf312d396abd)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=98a56425-4f88-4f0f-963b-dada8dc0d8f8)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0c9af3b5-d015-4025-bbb4-1a5113e9113f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c2bbf515-f81a-436b-947b-cbf2db85fdd9)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4b9bf156-cd34-460f-b4ad-571e37f54659)  
(KB973904)  
(重要)
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
[**MS09-071**](http://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3d49b386-133a-4d51-b6f0-cec0c70ef93e)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=6659fc40-71ee-44a9-9656-8d3ee02b5bc0)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7bdba030-e2c6-44ac-bb5f-24ae8ec372a2)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0dd50357-64f2-4286-86ba-c512e65eed2a)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a779aae1-7724-4458-94fb-a2343356ecae)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=31351b9e-b5bb-4618-990b-1089ea5a3bc2) <sup>[1]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b9678229-2473-4aae-a814-eca9ea556d17)  
(KB973904)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5a273b47-8a18-4778-9b60-8b560a1ce089)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=287e7921-8aab-42a6-b647-551d0a9adc15)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=4de4bbcd-b1b8-4482-8ef7-0d9b4a730e0c)  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=e62aba15-5eeb-46a2-a142-bfca94016c55)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=a8a9bf12-4ad6-49fd-b2b7-f379dc3309d2)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b6eb9d9b-1a43-4b30-a033-19a1db786244) <sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=257facf3-20a1-49e2-ab4c-c1ae67fe05a0)  
(KB973904)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=498f5eeb-d03e-42ee-ad6a-9d6f98c66acb)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9ce1a721-0c6a-4775-9407-9633d817d716)  
(緊急)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=72d44de7-dfc5-4667-a59f-2ee73d0e3708)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f5b003ad-af25-488a-91fb-98835a0bfeac)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1a7784ef-5d25-4de1-a293-f742b5a3473d)  
(KB973904)  
(重要)
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
[**MS09-071**](http://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
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
Windows Vista, Windows Vista Service Pack 1, および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6)  
(警告)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=40d26d40-4203-4013-b3f9-912a5b209fbd)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=47d5ada1-1d60-4233-bdd3-64918b5e1245)  
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
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1, および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab)  
(警告)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=3140527a-aa33-462b-b3a6-bfcd78b5aa0c)  
(緊急)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=1e466b48-422f-4c80-8fdf-ba61111942b1)  
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
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
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
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
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
[Windows Server 2008 for 32-bit Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968)\*  
(重要)  
[Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=d0570536-756e-4fda-883d-f2a3c4ac5bbd)\*  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=43660133-43e1-41f3-8a82-98c4a739914f)\*  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f6715abb-fd93-44ba-9854-2ecc672622da)\*  
(重要)
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
[Windows Server 2008 for x64-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b)\*  
(重要)  
[Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=0e72d0f1-2ce7-4650-b72c-bb303351aafc)\*  
(警告)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=22972970-740f-4c50-93ec-f6d49dd1b360)\*  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7d1f5e9e-a7de-4f96-89c8-510fd51f16e7)\*  
(重要)
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
[Windows Server 2008 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(警告)  
[Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(重要)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2c7765a2-3117-4dd8-94b4-0060ca16871b)  
(警告)
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
<th colspan="6">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://technet.microsoft.com/security/bulletin/rating)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=5af3be0b-2dd2-4039-90e1-2278e9c5aee5)  
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
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9d9a04c8-a019-4943-8e93-c6bfd77c8960)  
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
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://technet.microsoft.com/security/bulletin/ms09-071)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://technet.microsoft.com/security/bulletin/ms09-072)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://technet.microsoft.com/security/bulletin/ms09-069)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://technet.microsoft.com/security/bulletin/ms09-070)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bcb38127-787f-49b0-b3fb-62f6a8628d89)\*  
(警告)
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
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2c1b96f2-b3c3-4711-a9ad-b2133ea7bf81)  
(警告)
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

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意:**

**\*Server Core インストールは影響を受けません。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションに関する詳細情報は MSDN コラム [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) (英語情報) および [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(en-us,vs.85).aspx) (英語情報) をご覧ください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Compare Server Core Installation Option](http://www.microsoft.com/windowsserver2008/en/us/r2-compare-core-installation.aspx) (英語情報) をご覧ください。

**MS09-070 のセキュリティ情報に関する注意:**

<sup>[1]</sup> Windows Server 2003 R2 で、Active Directory フェデレーション サービスが有効に設定された環境のみ、影響を受けます。

<sup>[2]</sup> Windows Server 2003 R2 x64 Edition で、Active Directory フェデレーション サービスが有効に設定された環境のみ、影響を受けます。

**MS09-073 のセキュリティ情報に関する注意:**

**「影響を受けるソフトウェアおよびダウンロード先」**のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は 1 種類以上のソフトウェアを対象にしています。

#### Microsoft Office スイートおよびソフトウェア

 
<p></p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Microsoft Office スイート、システムおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-074**](http://technet.microsoft.com/security/bulletin/ms09-074)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=bc3ec3ba-2cec-43ab-b184-c222794231f2)  
(KB975008)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=b4a4126c-b0b3-4db2-b6f5-0e67519c2a5f)  
(KB975051)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
その他の Microsoft Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-074**](http://technet.microsoft.com/security/bulletin/ms09-074)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://technet.microsoft.com/security/bulletin/ms09-073)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Project 2000
</td>
<td style="border:1px solid black;">
[Microsoft Project 2000 Service Release 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=135c010a-55f4-4385-b67d-96ea06ef881a)  
(KB961083)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Project 2002
</td>
<td style="border:1px solid black;">
[Microsoft Project 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=c55ef8fe-8f66-42fc-a298-de6f8886b3e4)  
(KB961079)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Project 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=2ea8ca39-f130-439a-92d5-77e9ef050105)  
(KB961082)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=807426a1-8b78-4681-a606-dc39f4d7b64a)  
(KB977304)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=f3ff8bb6-d047-42f1-9331-b6df85fff9fd)  
(KB974882)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**MS09-073 のセキュリティ情報に関する注意:**

**「影響を受けるソフトウェアおよびダウンロード先」**のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 識別名の下の複数の更新ファイルを確認してください。このセキュリティ情報は 1 種類以上のソフトウェアを対象にしています。

検出および展開ツールとガイダンス
--------------------------------


**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**注:** 2009 年 8 月 1 日より、マイクロソフトは Office Update および Office Update Inventory Tool のサポートを終了します。Microsoft Office 製品用の最新の更新プログラムを引き続き入手するためには、[Microsoft Update](http://update.microsoft.com/microsoftupdate/) をご利用ください。詳細情報は、[About Microsoft Office Update: Frequently Asked Questions](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx) (英語情報) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトはセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [961747](http://support.microsoft.com/kb/961747) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](http://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](http://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](http://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](http://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](http://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](http://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](http://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](http://support.microsoft.com/kb/894199/en-us) (英語情報): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2009 年). すべての Windows のコンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報): Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](http://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](http://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](http://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS09-072 で説明している問題について報告してくださった [Verisign iDefense Labs](http://labs.idefense.com/) の Ryan Smith 氏
-   MS09-072 で説明している問題について [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった eshu.co.uk の Sam Thomas 氏
-   MS09-072 で説明している問題について [Verisign iDefense Labs](http://labs.idefense.com/) と協力して報告してくださった [team509](http://www.team509.com/)
-   MS09-072 で説明している問題について [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった匿名のリサーチャー
-   MS09-072 で説明している別の問題について [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった匿名のリサーチャー
-   MS09-073 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Sean Larsson 氏および Jun Mao 氏
-   MS09-074 で説明している問題について報告してくださった [Fortinet's FortiGuard Labs](http://www.fortiguard.com/) の Bing Liu 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/12/09: このセキュリティ情報ページを公開しました。
-   2009/12/10: このセキュリティ情報を更新し、「概説」の MS09-071 についての情報を更新しました。また、MS09-073 の再起動の要件を修正しました。
-   2010/01/14: このセキュリティ情報ページを更新し、MS09-073 の更新プログラム パッケージ Microsoft Office Word 2002 Service Pack 3 (KB975008) および Microsoft Office Word 2003 Service Pack 3 (KB975051) の名称を変更し、それぞれ Microsoft Office XP Service Pack 3 (KB975008) および Microsoft Office 2003 Service Pack 3 (KB975051) としました。

*Built at 2014-04-18T01:50:00Z-07:00*
