---
TOCTitle: 'MS09-MAR'
Title: 2009 年 3 月のセキュリティ情報
ms:assetid: 'ms09-mar'
ms:contentKeyID: 61229665
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-mar(v=Security.10)'
--- 

2009 年 3 月のセキュリティ情報
==============================

公開日: 2009年3月11日 | 最終更新日: 2009年3月12日

**バージョン:** 1.0

[![](../../images/Dn627244.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/dd251169.aspx)

絵でみるセキュリティ情報
------------------------


[MS09-006 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-006e.mspx)

[MS09-007 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-007e.mspx)

[MS09-008 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms09-008e.mspx)

このセキュリティ情報は 2009 年 3 月に公開したセキュリティ情報の一覧です。

2009 年 3 月のセキュリティ情報の公開により、2009 年 3 月 6 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 3 月 11 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 3 月 11 日 午前 11 ：00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[3 月のセキュリティ 情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395124)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----


 
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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-006">MS09-006</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルの脆弱性により、リモートでコードが実行される (958690)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された数件の Windows カーネルの脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが影響を受けるコンピューターで特別な細工がされた EMF または WMF 画像ファイルを表示すると、攻撃者によりリモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-007">MS09-007</a></td>
<td style="border:1px solid black;"><strong>SChannel の脆弱性により、なりすましが行われる (960225)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Windows の SChannel (セキュリティで保護されたチャネル) のセキュリティ パッケージの脆弱性を解決します。この脆弱性により、攻撃者がエンド ユーザーの使用した認証用の証明書へのアクセスを取得した場合、なりすましを行う可能性があります。お客様が影響を受けるのは、攻撃者が他の方法を介して認証に使用する証明書の公開キーのコンポーネントを入手した場合のみです。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
なりすまし</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms09-008">MS09-008</a></td>
<td style="border:1px solid black;"><strong>DNS および WINS サーバーの脆弱性により、なりすましが行われる (962238)</strong><br />
<br />
このセキュリティ更新プログラムは Windows DNS サーバーおよび Windows WINS サーバーに存在する 2 つの非公開で報告された脆弱性と 2 つの公開された脆弱性を解決します。これらの脆弱性で、リモートの攻撃者によりインターネットでコンピューター向けのネットワーク トラフィックが攻撃者のコンピューターにリダイレクトされる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
なりすまし</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  

次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号および CVE ID の順に記載しています。
  
**この表はどのように使用しますか?**  
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報番号                                                | セキュリティ情報タイトル                                              | CVE ID                                                                       | Exploitability Index の評価                                                                         | 注意事項                                                                                                                                             |  
|---------------------------------------------------------------------|-----------------------------------------------------------------------|------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-006](https://technet.microsoft.com/security/bulletin/ms09-006) | Windows カーネルの脆弱性により、リモートでコードが実行される (958690) | [CVE-2009-0081](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0081) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | 確実に機能するコードの実行よりもむしろ、動作に一貫性のあるサービス拒否が行われる可能性があります。                                                   |  
| [MS09-006](https://technet.microsoft.com/security/bulletin/ms09-006) | Windows カーネルの脆弱性により、リモートでコードが実行される (958690) | [CVE-2009-0082](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0082) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 確実に機能するコードの実行よりもむしろ、動作に一貫性のあるサービス拒否が行われる可能性があります。                                                   |  
| [MS09-006](https://technet.microsoft.com/security/bulletin/ms09-006) | Windows カーネルの脆弱性により、リモートでコードが実行される (958690) | [CVE-2009-0083](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0083) | [**3** - 機能する見込みのない悪用コード](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) | ローカルでの脅威は、確実に機能するコードの実行よりもむしろ、動作に一貫性のあるサービス拒否が行われるか、または情報漏えいが起こる可能性があります。   |  
| [MS09-007](https://technet.microsoft.com/security/bulletin/ms09-007) | SChannel の脆弱性により、なりすましが行われる (960225)                | [CVE-2009-0085](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0085) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 確実な悪用には多くの必要条件があり、お客様に対する重大な攻撃シナリオの可能性は低いと思われます。                                                     |  
| [MS09-008](https://technet.microsoft.com/security/bulletin/ms09-008) | DNS および WINS サーバーの脆弱性により、なりすましが行われる (962238) | [CVE-2009-0093](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0093) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 動作に一貫性のあるなりすましを行う検証用コードが作成される可能性がありますが、悪質なコードが実行可能な攻撃コードが作成される可能性は非常に低いです。 |  
| [MS09-008](https://technet.microsoft.com/security/bulletin/ms09-008) | DNS および WINS サーバーの脆弱性により、なりすましが行われる (962238) | [CVE-2009-0094](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0094) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 動作に一貫性のあるなりすましを行う検証用コードが作成される可能性がありますが、悪質なコードが実行可能な攻撃コードが作成される可能性は非常に低いです。 |  
| [MS09-008](https://technet.microsoft.com/security/bulletin/ms09-008) | DNS および WINS サーバーの脆弱性により、なりすましが行われる (962238) | [CVE-2009-0233](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0233) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 動作に一貫性のあるなりすましを行う検証用コードが作成される可能性がありますが、悪質なコードが実行可能な攻撃コードが作成される可能性は非常に低いです。 |  
| [MS09-008](https://technet.microsoft.com/security/bulletin/ms09-008) | DNS および WINS サーバーの脆弱性により、なりすましが行われる (962238) | [CVE-2009-0234](https://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0234) | [**2** - 不安定な悪用コードの可能性](https://technet.microsoft.com/ja-jp/security/cc998259.aspx)     | 動作に一貫性のあるなりすましを行う検証用コードが作成される可能性がありますが、悪質なコードが実行可能な攻撃コードが作成される可能性は非常に低いです。 |
  
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
</tr>
<tr>
<th colspan="4">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-006**](https://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](https://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](https://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=98bb7d40-89a0-470a-8eb7-06f15072a635&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](https://www.microsoft.com/download/details.aspx?familyid=bf7065bc-c183-4a78-8d46-72fe7385c07c&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4 上の DNS サーバー](https://www.microsoft.com/download/details.aspx?familyid=110354f7-5ece-4c4d-b563-3adba6ac0116&displaylang=ja)  
(961063)  
(重要)  
[Microsoft Windows 2000 Server Service Pack 4 上の WINS サーバー](https://www.microsoft.com/download/details.aspx?familyid=4319abb3-1ea2-466a-a815-c0b3b86b4462&displaylang=ja)  
(961064)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-006**](https://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](https://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](https://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=e09641ba-6cbe-4095-82b5-703d3a7dc33b&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?familyid=942d87f6-3cb1-4d36-a70a-70d9c34488f3&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=d0d704c6-48c2-4907-b6c3-2455d7cf21c8&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition および Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=6d02306e-9e2e-4ae8-bd21-8a2c1a229472&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-006**](https://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](https://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](https://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=f5cfb8da-e7cc-4183-8631-507c2a406500&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=0b3f6fdd-276e-4267-99d8-8f00d91ad6a2&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2 上の DNS サーバー](https://www.microsoft.com/download/details.aspx?familyid=6cc42c9e-c34e-4577-8b23-9e07e2369878&displaylang=ja)  
(961063)  
(重要)  
[Windows Server 2003 Service Pack 1 および Windows Server 2003 Service Pack 2 上の WINS サーバー](https://www.microsoft.com/download/details.aspx?familyid=049e5db5-7315-4188-99fd-4a54833e6bf2&displaylang=ja)  
(961064)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ecf75c70-8489-41ad-9759-3a07e13957be&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?familyid=ce98ff55-f565-469d-bbd2-32b681faf908&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2 上の DNS サーバー](https://www.microsoft.com/download/details.aspx?familyid=b1f81fd2-0099-4450-8543-0459561d22d0&displaylang=ja)  
(961063)  
(重要)  
[Windows Server 2003 x64 Edition および Windows Server 2003 x64 Edition Service Pack 2 上の WINS サーバー](https://www.microsoft.com/download/details.aspx?familyid=4a393c63-eff5-4c8c-9c3f-33ce45c32428&displaylang=ja)  
(961064)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=04be3d7e-7dda-4dca-887a-e7a8156ede1c&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=5ca3c72c-cadb-4b0a-b3a3-fb81d0bfd7b3&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems 上の DNS サーバー](https://www.microsoft.com/download/details.aspx?familyid=d3ed7d9a-d652-4bd0-aecc-5a415bec6c59&displaylang=ja)  
(961063)  
(重要)  
[Windows Server 2003 with SP1 for Itanium-based Systems および Windows Server 2003 with SP2 for Itanium-based Systems 上の WINS サーバー](https://www.microsoft.com/download/details.aspx?familyid=37e3a75e-0a5d-4df0-881f-cdb87efa4dcf&displaylang=ja)  
(961064)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-006**](https://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](https://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](https://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista および Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=4b1aaaba-f355-4265-83c0-50b901856ced&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista および Windows Vista Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=21086a04-402a-4940-8358-7fa63508102b&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=0fcac480-d6db-4a94-8c7d-b7319282cf56&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition および Windows Vista x64 Edition Service Pack 1](https://www.microsoft.com/download/details.aspx?familyid=c75a2ea9-b42f-457b-be09-5c8fa0339388&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="4">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-006**](https://technet.microsoft.com/security/bulletin/ms09-006)
</td>
<td style="border:1px solid black;">
[**MS09-007**](https://technet.microsoft.com/security/bulletin/ms09-007)
</td>
<td style="border:1px solid black;">
[**MS09-008**](https://technet.microsoft.com/security/bulletin/ms09-008)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=38851df2-4fb5-4d28-9d15-181c260cf8cf&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?familyid=47b361ce-624b-466c-b5c5-8703f6532615&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems 上の DNS サーバー](https://www.microsoft.com/download/details.aspx?familyid=92e89882-d656-4b61-a05c-3afb44895f08&displaylang=ja)\*  
(961063)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=ec15acc4-3e0f-4414-9383-61c122ff1382&displaylang=ja)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems](https://www.microsoft.com/download/details.aspx?familyid=5c81ac45-60e6-4121-ab6b-d3b3179aacc4&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems 上の DNS サーバー](https://www.microsoft.com/download/details.aspx?familyid=be068d06-5939-4ad8-8191-e85931ed610f&displaylang=ja)\*  
(961063)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=eead6f93-10fd-4492-8137-481d9876a5fe&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?familyid=bf8f5a86-1757-4f9b-b632-d4aa7005a9f8&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 に関する注意:**

**\*Windows Server 2008 Server Core インストールは影響を受けます。** サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度でこの更新プログラムが適用されます。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/servercore.mspx) をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/editions/core.mspx) をご覧ください。

検出および展開ツールとガイダンス
--------------------------------


**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](https://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[Microsoft TechNet セキュリティ センター](https://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](https://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](https://update.microsoft.com/microsoftupdate/)、[Windows Update](https://windowsupdate.microsoft.com/) および [Office Update](https://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](https://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](https://support.microsoft.com/kb/910723) をご覧ください。

**Microsoft Baseline Security Analyzer**

Microsoft Baseline Security Analyzer は、管理者によりローカルコンピューターやリモートコンピューターの未適 用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細情報については、[Microsoft Baseline Security Analyzer (MBSA) Web サイト](https://technet.microsoft.com/ja-jp/security/cc184924.aspx)をご覧ください。

**Windows Server Update Services**

Windows Server Update Services (WSUS) により、最新の状態を維持するために重要な更新プログラムを迅速かつ確実に配布することができます。WSUS は Windows 2000 以降のオペレーティング システム用のセキュリティ更新プログラム、Office XP 以降の Office 用のセキュリティ更新プログラム、Exchange Server 2003 およびそれ以降のバージョン、SQL Server 2000 およびそれ以降のバージョン用のセキュリティ更新プログラムに対応しています。

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/overview.mspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンを公開しました。

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](https://support.microsoft.com/kb/894199/en-us) (英語情報): Software Update Services および Windows Server Update Services におけるコンテンツの変更について (2009 年). すべての Windows のコンテンツが含まれます。
-   [New, Revised, and Released Updates for Microsoft Products Other Than Microsoft Windows.](https://technet.microsoft.com/en-us/wsus/bb466214.aspx) (英語情報)

この情報はセキュリティ情報と同日に公開予定の Microsoft Update、Windows Update、および Windows Server Update Services での**セキュリティ以外**の優先度の高い更新プログラムに**のみ**関連することに注意してください。その他の日に公開される**セキュリティ以外**の更新プログラムに関する情報は**提供しません**。

#### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[パッチ管理のセキュリティ ガイド](https://technet.microsoft.com/ja-jp/library/dd433786.aspx)で、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは [マイクロソフト ダウンロード センター](https://www.microsoft.com/downloads/search.aspx?displaylang=ja)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。
-   コンシューマー用プラットフォームの更新プログラムは、[Microsoft Update](https://update.microsoft.com/microsoftupdate) でご利用になれます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細情報は、サポート技術情報 [913086](https://support.microsoft.com/kb/913086) をご覧ください。

**IT Pro Security Zone Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについてその他の IT プロフェッショナルとの情報交換を行うためには、[IT Pro Security Community](https://go.microsoft.com/fwlink/?linkid=21164) (英語) をご覧下さい。

#### 謝辞

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/security/bulletin/policy)を表します。

-   MS09-006 で説明している問題について報告してくださった [Helmut Buhler](https://home.arcor.de/clipboarder/) 氏
-   MS09-006 で説明している問題について報告してくださった [SkyRecon](https://www.skyrecon.com/) 社の Thomas Garnier 氏
-   MS09-007 で説明している問題について報告してくださった [Secretaria da Fazenda do Estado do Rio Grande do Sul](https://www.sefaz.rs.gov.br/)
-   MS09-007 で説明している問題について報告してくださった [Cia de Processamento de Dados do Estado do Rio Grande do Sul](https://www.procergs.rs.gov.br/)
-   MS09-008 で説明している 2 件の問題についてマイクロソフトに協力していただいている Kevin Day 氏
-   MS09-008 で説明している 2 件の問題についてマイクロソフトに協力していただいている [Georgia Tech Information Security Centerl](https://www.gtisc.gatech.edu/) の Dave Dagon 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/03/11: このセキュリティ情報ページを公開しました。
-   2009/03/12: このセキュリティ情報ページを更新し、MS09-008 に関する謝辞に関する情報を変更しました。

*Built at 2014-04-18T01:50:00Z-07:00*
