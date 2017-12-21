---
TOCTitle: 'MS09-NOV'
Title: 2009 年 11 月のセキュリティ情報
ms:assetid: 'ms09-nov'
ms:contentKeyID: 61229667
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-nov(v=Security.10)'
--- Summary

2009 年 11 月のセキュリティ情報
===============================

公開日: 2009年11月11日 | 最終更新日: 2009年11月26日

**バージョン:** 1.0

[![](../../images/Dn627246.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/dd251169.aspx)[![](../../images/Dn627246.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------


[MS09-063 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-063e.mspx)

[MS09-064 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-064e.mspx)

[MS09-065 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-065e.mspx)

[MS09-066 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-066e.mspx)

[MS09-067 : Excel の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-067e.mspx)

[MS09-068 : Word の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-068e.mspx)

このセキュリティ情報は 2009 年 11 月 6 日に公開したセキュリティ情報の一覧です。

2009 年 11 月 11 日のセキュリティ情報の公開により、2009 年 11 月 6 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 11 月 11 日 の午後 (日本時間) に配信予定です。この Web キャストでは、月例セキュリティ更新プログラムの適用優先順位に関する情報についても提供します。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 11 月 11 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[11月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032407490&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----


次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細は、次の影響を受けるソフトウェアのセクションをご覧ください。

 
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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-063">MS09-063</a></td>
<td style="border:1px solid black;"><strong>Web Services on Devices API の脆弱性により、リモートでコードが実行される (973565)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows オペレーティング システムの Web Services on Devices API (WSDAPI) の脆弱性を解決します。この脆弱性により、影響を受ける Windows システムが特別に細工されたパケットを受け取った場合、リモートでコードが実行される可能性があります。ローカル サブネット上の攻撃者だけが、この脆弱性を悪用する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-064">MS09-064</a></td>
<td style="border:1px solid black;"><strong>ライセンス ログ サーバーの脆弱性により、リモートでコードが実行される (974783)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 1 件の Microsoft Windows 2000 の脆弱性を解決します。 攻撃者がライセンス ログ サーバーを実行しているコンピューターに特別に細工したメッセージを送信した場合、リモートでコードが実行される可能性があります。 攻撃者はこの脆弱性を悪用し、コンピューターを完全に制御する可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-065">MS09-065</a></td>
<td style="border:1px solid black;"><strong>Windows カーネル モード ドライバーの脆弱性により、リモートでコードが実行される (969947)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された数件の Windows カーネルの脆弱性を解決します。 これらの脆弱性のうち、最も深刻な脆弱性が悪用された場合、ユーザーが特別な細工がされた E mbedded OpenType (EOT) フォントでレンダリングされたコンテンツを表示すると、リモートでコードが実行される可能性があります。Web ベースの攻撃のシナリオでは、この脆弱性を悪用しようとする特別な細工がされた埋め込まれたフォントが含まれている Web サイトをホストすることが攻撃者にとっての必要条件となります。さらに、侵害された Web サイトやユーザー提供のコンテンツを受け入れる、またはホストする Web サイトには、特別に細工したコンテンツが含まれており、この脆弱性が悪用される可能性があります。攻撃者は、特別に細工した Web サイトにユーザーを強制的に訪問させることはできないと考えられます。その代わり、通常、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージ内の攻撃者の Web サイトへのリンクをクリックさせ、その Web サイトにユーザーを誘導することが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-066">MS09-066</a></td>
<td style="border:1px solid black;"><strong>Active Directory の脆弱性により、サービス拒否が起こる (973309)</strong><br />
<br />
このセキュリティ更新プログラムは Active Directory のデ ィレクトリ サービス、Active Directory Application Mode (ADAM) および Active Directory Lightweight Directory Service (AD LDS) に存在する非公開で報告された脆弱性を解決します。 この脆弱性で、特定の種類の LDAP または LDAPS リクエストの実行中、スタック領域が消耗された場合、サービス拒否が起こる可能性があります。この脆弱性の影響を受けるのは、ドメイン コントローラーおよび ADAM または AD LDS を実行するよう構成されているコンピューターのみです。 このセキュリティ更新プログラムは、すべてのサポートされているエディションの Microsoft Windows 2000 Server、Windows XP、Windows Server 2003 および Windows Server 2008 上の Active Directory、ADAM および ADLDS について、深刻度を「重要」と評価しています。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-067">MS09-067</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel の脆弱性により、リモートでコードが実行される (972652)</strong><br />
<br />
このセキュリティ更新プログラムは、いくつかの非公開で報告された Microsoft Office Excel に存在する脆弱性を解決します。 これらの脆弱性は、特別に細工された Excel ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。 システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-068">MS09-068</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word の脆弱性により、リモートでコードが実行される (976307)</strong><br />
<br />
このセキュリティ更新プログラムは、ユーザーが特別に細工された Word ファイルを開いた際にリモートでコードが実行される可能性のある、非公開で報告された 1 件の脆弱性を解決します。攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  

次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号および CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**  
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID 番号                                            | セキュリティ情報タイトル                                 | CVE ID                                                                           | Exploitability Index の評価                                                                         | 注意事項                                                                                           |  
|---------------------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|  
| [MS09-063](http://technet.microsoft.com/security/bulletin/ms09-063) | Web Services on Devices API のメモリ破損の脆弱性         | [CVE-2009-2512](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2512) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 特定のシナリオで悪用可能な、限定的なサービス拒否攻撃が存在します。                                 |  
| [MS09-064](http://technet.microsoft.com/security/bulletin/ms09-064) | ライセンス ログ サーバーのヒープ オーバーフローの脆弱性  | [CVE-2009-2523](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2523) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 攻撃は悪用が困難な競合状態に依存します。サービス拒否以外の脆弱性は、不安定になる可能性があります。 |  
| [MS09-065](http://technet.microsoft.com/security/bulletin/ms09-065) | Win32k の NULL ポインター逆参照の脆弱性                  | [CVE-2009-1127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1127) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-065](http://technet.microsoft.com/security/bulletin/ms09-065) | Win32k の不十分なデータの検証の脆弱性                    | [CVE-2009-2513](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2513) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-065](http://technet.microsoft.com/security/bulletin/ms09-065) | Win32k の EOT 解析の脆弱性                               | [CVE-2009-2514](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2514) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-066](http://technet.microsoft.com/security/bulletin/ms09-066) | LSASS の再帰によるスタック オーバーフローの脆弱性        | [CVE-2009-1928](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1928) | [**3** - 機能する見込みのない悪用コード](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 特定の状況でサービス拒否となる脆弱性が存在します。                                                 |  
| [MS09-067](http://technet.microsoft.com/security/bulletin/ms09-067) | Excel のキャッシュ メモリ破損の脆弱性                    | [CVE-2009-3127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3127) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-067](http://technet.microsoft.com/security/bulletin/ms09-067) | Excel の SxView メモリ破損の脆弱性                       | [CVE-2009-3128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3128) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-067](http://technet.microsoft.com/security/bulletin/ms09-067) | Excel の Featheader レコード メモリ破損の脆弱性          | [CVE-2009-3129](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3129) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-067](http://technet.microsoft.com/security/bulletin/ms09-067) | Excel のドキュメント解析のヒープ オーバーフローの脆弱性  | [CVE-2009-3130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3130) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-067](http://technet.microsoft.com/security/bulletin/ms09-067) | Excel の式解析のメモリ破損の脆弱性                       | [CVE-2009-3131](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3131) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-067](http://technet.microsoft.com/security/bulletin/ms09-067) | Excel のインデックス解析の脆弱性                         | [CVE-2009-3132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3132) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-067](http://technet.microsoft.com/security/bulletin/ms09-067) | Excel のドキュメント解析のメモリ破損の脆弱性             | [CVE-2009-3133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3133) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-067](http://technet.microsoft.com/security/bulletin/ms09-067) | Excel のフィールドのサニタイズの脆弱性                   | [CVE-2009-3134](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3134) | [**2** - 不安定な悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |  
| [MS09-068](http://technet.microsoft.com/security/bulletin/ms09-068) | Microsoft Office Word のファイル情報のメモリ破損の脆弱性 | [CVE-2009-3135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3135) | [**1** - 安定した悪用コードの可能性](http://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | (なし)                                                                                             |
  
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
</tr>
<tr>
<th colspan="5">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://technet.microsoft.com/security/bulletin/ms09-066)
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
[**緊急**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[**緊急**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=365a8dff-2383-42f6-b567-e545461fd135&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=45db8bb1-c81b-4d3f-a658-74f5fa445f81&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4 上の Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=297158cf-374c-45d9-b213-978e1f54d244&displaylang=ja)  
(KB973037)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://technet.microsoft.com/security/bulletin/ms09-066)
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
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=916abdad-44b7-4f9d-986a-0c3558fb8e06&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=cbe09780-f288-457a-b254-58c9c8744055&displaylang=ja)  
(KB973039)  
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
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1d0464c6-5ed8-4064-887e-618a2db09236&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=b65ddf36-a02d-4aa2-9b4f-7416dbf59e2a&displaylang=ja)  
(KB973039)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://technet.microsoft.com/security/bulletin/ms09-066)
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
なし
</td>
<td style="border:1px solid black;">
[**緊急**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5cd62750-e269-44ae-8c7c-c335e8545b9a&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=28f1c494-4e16-43b6-93d2-49e15f142ac9&displaylang=ja)  
(KB973037)  
(重要)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=44cb9029-4b19-4bad-8fc9-3efe285adb0e&displaylang=ja)  
(KB973039)  
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
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=04a7f817-f330-4003-8b25-d3e744905b12&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=509aeec0-112b-44ab-8686-43f381b61940&displaylang=ja)  
(KB973037)  
(重要)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=87f2109e-5129-467c-930f-70af31ebf5de&displaylang=ja)  
(KB973039)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=b95daac0-4c99-47a4-b0ca-9429997ea3d9&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=040e691b-1ef0-4b73-bef7-a1d77b84b0ca&displaylang=ja)  
(KB973037)  
(重要)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://technet.microsoft.com/security/bulletin/ms09-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
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
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ebf0c294-cd99-445a-a741-78253e47189f&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=54562103-1d99-42d7-8f7f-c0cbcdce90db&displaylang=ja)  
(重要)
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
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d9645fc9-f524-43f1-8b8c-94b3b4312158&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fcb87cc8-6fd7-4f16-93d6-552999462fb1&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://technet.microsoft.com/security/bulletin/ms09-063)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://technet.microsoft.com/security/bulletin/ms09-064)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://technet.microsoft.com/security/bulletin/ms09-065)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://technet.microsoft.com/security/bulletin/ms09-066)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d6a60883-b103-459a-a91b-cd6ed946cefe&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b97d48de-0f6d-4bca-b990-acf543fdb8b7&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=701abf15-7f93-41de-8d09-13404fd79a7e&displaylang=ja)\*  
(KB973037)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3dde1587-42d3-438f-8344-696a5657b9b1&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0e2b8607-10fa-406a-96a5-18290f479c48&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Active Directory および Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=17f5f9e0-5869-41da-9b3b-6e67540af1f0&displaylang=ja)\*  
(KB973037)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=841a027f-22fa-42de-93b3-57a3fe92a1d3&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=28eba3f3-99a5-424c-bc8d-a718c716699e&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](http://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

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
[**MS09-067**](http://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://technet.microsoft.com/security/bulletin/ms09-068)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=5672c8fc-8509-4962-ad86-ebc0f2575043&displaylang=ja)  
(KB973471)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0369fae5-958b-4eba-83a4-9c07e701c273&displaylang=ja)  
(KB973444)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6a6a0f5d-17dc-4a34-b9a0-0774aa287ba5&displaylang=ja)  
(KB973475)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6b77bc62-bcbb-4b9a-97d1-a49ca0582e54&displaylang=ja)  
(KB973443)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 および Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=322b24ca-aff6-4ca0-acf1-440cae0f9693&displaylang=ja) <sup>[1]</sup>
(KB973593)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-067**](http://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://technet.microsoft.com/security/bulletin/ms09-068)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e&displaylang=ja)  
(KB976830)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e&displaylang=ja)  
(KB976830)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928&displaylang=ja)  
(KB976828)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928&displaylang=ja)  
(KB976828)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6&displaylang=ja)  
(KB976831)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6&displaylang=ja)  
(KB976831)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
その他の Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-067**](http://technet.microsoft.com/security/bulletin/ms09-067)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://technet.microsoft.com/security/bulletin/ms09-068)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
<td style="border:1px solid black;">
[**重要**](http://www.microsoft.com/technet/security/bulletin/%3Ehttp://www.microsoft.com/japan/technet/security/bulletin/rating.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=19151e22-5642-456c-bd39-298574369cdb&displaylang=ja)  
(KB973484)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 および Microsoft Office Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fb36df5e-ebef-46bf-9edd-67f2c76dbdb3&displaylang=ja)  
(KB973707)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1&displaylang=ja)  
(KB973866)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1&displaylang=ja)  
(KB973866)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa&displaylang=ja)  
(KB973704)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**MS09-067 のセキュリティ情報に関する注意**

<sup>[1]</sup> Microsoft Office Excel 2007 Service Pack 1 および Microsoft Office Excel 2007 Service Pack 2 について、KB973593 のセキュリティ更新プログラムに加え、お客様は [Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2 用のセキュリティ更新プログラム (KB973704)](http://www.microsoft.com/downloads/details.aspx?familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa&displaylang=ja) をインストールして、このセキュリティ情報で説明している脆弱性から防御する必要があります。

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
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報). Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

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

-   MS09-063 で説明している問題について報告してくださった [Google Inc.](http://www.google.com/) の Neel Mehta 氏
-   MS09-064 で説明している問題について報告してくださった [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) の Cody Pierce 氏
-   MS09-065 で説明している問題について報告してくださった Agin Sun 氏
-   MS09-065 で説明している問題について報告してくださった [Google Inc.](http://www.google.com/) の Tavis Ormandy
-   MS09-067 で説明している 3 つの問題について報告してくださった [Fortinet の FortiGuard Labs](http://www.fortiguard.com/) の Bing Liu 氏
-   MS09-067 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   MS09-067 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Sean Larsson 氏
-   MS09-067 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayintiative.com/) に協力している匿名のリサーチャー
-   MS09-067 で説明している 4 つの問題について報告してくださった [VUPEN Security](http://www.vupen.com/) Nicolas Joly 氏
-   MS09-068 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Jun Mao 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/11/11: このセキュリティ情報ページを公開しました。
-   2009/11/26: ライセンス ログ サーバーのヒープ オーバーフローの脆弱性 - CVE-2009-2523 の注意事項を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
