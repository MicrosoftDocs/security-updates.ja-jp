---
TOCTitle: 'MS09-JUN'
Title: 2009 年 6 月のセキュリティ情報
ms:assetid: 'ms09-jun'
ms:contentKeyID: 61229664
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms09-jun(v=Security.10)'
--- Summary

2009 年 6 月のセキュリティ情報
==============================

公開日: 2009年6月10日 | 最終更新日: 2009年6月11日

**バージョン:** 1.0

[![](../../images/Dn627243.onepoint_summary(ja-JP,Security.10).jpg)](http://technet.microsoft.com/ja-jp/dd251169.aspx)[![](../../images/Dn627243.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------


[MS09-018 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-018e.mspx)

[MS09-019 : Internet Explorer の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-019e.mspx)

[MS09-020 : Internet Information Services の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-020e.mspx)

[MS09-021 : Excel の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-021e.mspx)

[MS09-022 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-022e.mspx)

[MS09-023 : Windows サーチの重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-023e.mspx)

[MS09-024 : Office の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-024e.mspx)

[MS09-025 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-025e.mspx)

[MS09-026 : Windows の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-026e.mspx)

[MS09-027 : Word の重要な更新](http://www.microsoft.com/japan/security/bulletins/ms09-027e.mspx)

このセキュリティ情報は 2009 年 6 月に公開したセキュリティ情報の一覧です。

2009 年 6 月のセキュリティ情報の公開により、2009 年 6 月 5 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](http://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

マイクロソフト セキュリティ情報の公開についての自動の電子メールによる通知の購読は、[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://technet.microsoft.com/ja-jp/security/dd252948.aspx)でお申し込みください (無料)。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2009 年 6 月 10 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](http://technet.microsoft.com/ja-jp/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2009 年 6 月 10 日 午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[6 月のセキュリティ情報 Webcast (英語) に登録する。](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395225&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](http://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先 度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

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
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-018">MS09-018</a></td>
<td style="border:1px solid black;"><strong>Active Directory の脆弱性により、リモートでコードが実行される (971055)</strong><br />
<br />
このセキュリティ更新プログラムは、Microsoft Windows 2000 Server および Windows Server 2003 上の Active Directory の実装、Windows XP Professional および Windows Server 2003 にインストールされている場合の Active Directory Application Mode (ADAM) に存在する非公開で報告された 2 件の脆弱性を解決します。最も深刻な脆弱性の場合、リモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用し、影響を受けるコンピューターをリモートで完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎネットワークを保護することができます。インターネットに接続したコンピューターでは、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-022">MS09-022</a></td>
<td style="border:1px solid black;"><strong>Windows 印刷スプーラーの脆弱性により、リモートでコードが実行される (961501)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Windows 印刷スプーラーに存在する 3 件の脆弱性を解決します。最も深刻な脆弱性は、リモートでコードを実行される可能性があるもので、影響を受けるシステムが特別に細工した RPC リクエストを受信した場合です。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</strong><br />
<br />
このセキュリティ更新プログラムは Internet Explorer に存在する 7 つの非公開で報告された脆弱性と 1 つの公開された脆弱性を解決します。 より深刻な脆弱性が悪用された場合、ユーザーが Internet Explorer を使用して特別な細工がされた Web ページを表示すると、リモートでコードが実行される可能性があります。コンピューターでアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-027">MS09-027</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word の脆弱性により、リモートでコードが実行される (969514)</strong><br />
<br />
このセキュリティ更新プログラムは、ユーザーが特別に細工された Word ファイルを開いた際にリモートでコードが実行される可能性のある、非公開で報告された 2 件の脆弱性を解決します。攻撃者がこの脆弱性を悪用した場合、影響を受けるコンピューターが完全に制御される可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel の脆弱性により、リモートでコードが実行される (969462)</strong><br />
<br />
このセキュリティ更新プログラムは、ユーザーが不正な形式のレコード オブジェクトを含む特別な細工がされた Excel ファイルを開いた場合、リモートでコードが実行される可能性のあるいくつかの非公開で報告された脆弱性を解決します。攻撃者はこの脆弱性を悪用して、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-024">MS09-024</a></td>
<td style="border:1px solid black;"><strong>Microsoft Works コンバーターの脆弱性により、リモートでコードが実行される (957632)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft Works コンバーターの脆弱性を解決します。この脆弱性は、特別に細工された Works ファイルをユーザーが開いた場合に、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じ権限を取得する可能性があります。システムでアカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-026">MS09-026</a></td>
<td style="border:1px solid black;"><strong>RPC の脆弱性により、特権が昇格される (970238)</strong><br />
<br />
このセキュリティ更新プログラムは Windows リモート プロシージャー コール (RPC) マーシャリング エンジンが内部状態を適切に更新しない場合に起こる RPC 機能に存在する 1 件の公開された脆弱性を解決します。 この脆弱性で、攻撃者により任意のコードが実行され、影響を受けるコンピューターが完全に制御される可能性があります。 サポートされているエディションの Microsoft Windows は、この脆弱性の悪用による影響を受ける RPC サーバーまたはクライアントを同梱していません。 既定の構成で、この脆弱性が悪用されることはないと考えられます。 しかし、この脆弱性は Microsoft Windows RPC ランタイムに存在するため、サードパーティの RPC アプリケーションに影響を及ぼす可能性があります。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-025">MS09-025</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルの脆弱性により、特権が昇格される (968537)</strong><br />
<br />
このセキュリティ更新プログラムは、特権の昇格が起こる可能性がある一般で公開された 2 件の脆弱性および非公開で報告された 2 件の Windows カーネルの脆弱性を解決します。攻撃者はこれらの脆弱性を悪用し、任意のコードを実行し、影響を受けるコンピューターを完全に制御する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。この脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-020">MS09-020</a></td>
<td style="border:1px solid black;"><strong>インターネット インフォメーション サービス (IIS) の脆弱性により、特権が昇格される (970483)</strong><br />
<br />
このセキュリティ更新プログラムは Microsoft インターネット インフォメーション サービス (IIS) に存在する 1 件の一般に公開された脆弱性および 1 件の非公開で報告された脆弱性を解決します。これらの脆弱性で、攻撃者が特別な細工がされた HTTP リクエストを、認証を必要とする Web サイトに送信した場合、特権が昇格される可能性があります。これらの脆弱性により、攻撃者により、許可する認証の種類が指定されている IIS の構成が回避される可能性がありますが、特定のユーザーによりアクセスできるファイルを検証するファイル システム ベースのアクセス制御リスト (ACL) のチェックが回避されることはありません。これらの脆弱性が悪用された場合でも、攻撃者の行動はファイル システムの ACL により匿名ユーザー アカウントへ与えられた許可の範囲に制限されます。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-023">MS09-023</a></td>
<td style="border:1px solid black;"><strong>Windows サーチの脆弱性により、情報漏えいが起こる (963093)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows サーチの脆弱性を解決します。 この脆弱性は、ユーザーが検索を実行して最初の結果で特別に細工されたファイルが返される、または検索結果により特別に細工されたファイルをプレビューした場合に情報漏えいが起こる可能性があります。 既定で、Microsoft Windows XP および Windows Server 2003 には、Windows サーチのコンポーネントはプレインストールされていません。 これは、オプションでダウンロード可能なコンポーネントです。 サポートされているエディションの Windows Vista および Windows Server 2008 にインストールされている Windows サーチは、この脆弱性の影響を受けません。</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/rating">警告</a><br />
情報漏えい</td>
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
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。

 
<p></p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報番号</th>
<th style="border:1px solid black;" >セキュリティ情報タイトル</th>
<th style="border:1px solid black;" >CVE ID</th>
<th style="border:1px solid black;" >Exploitability Index の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-018">MS09-018</a></td>
<td style="border:1px solid black;">Active Directory の脆弱性により、リモートでコードが実行される (971055)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1138">CVE-2009-1138</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">安定した悪用コードの可能性があります。これにより、ネットワークの LDAP または LDAPS サービスが攻撃の危険にさらされるサービス拒否の状態が Windows 2000 Server で起こる可能性があります。しかし、ヒープでの追加チェックが行われるため、この脆弱性の悪用により、リモートでコードが実行される可能性は低いです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-018">MS09-018</a></td>
<td style="border:1px solid black;">Active Directory の脆弱性により、リモートでコードが実行される (971055)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1139">CVE-2009-1139</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">この脆弱性のセキュリティ上の影響はメモリ リークで、最終的にサービス拒否を引き起こす可能性があります。コードが実行される可能性はありません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-3091">CVE-2007-3091</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1140">CVE-2009-1140</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">これはドメイン間で不正に情報にアクセスできる脆弱性で、コードの実行ではなく、情報漏えいが起こる可能性が最も高くなります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1141">CVE-2009-1141</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1528">CVE-2009-1528</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1529">CVE-2009-1529</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1530">CVE-2009-1530</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1531">CVE-2009-1531</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-019">MS09-019</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (969897)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1532">CVE-2009-1532</a></td>
<td style="border:1px solid black;">DEP を無効にした Windows XP および Windows Vista 用の Internet Explorer 8:
<a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a>

DEP を有効にした Windows Vista 用の Internet Explorer 8、および Windows Server 2003 および Windows Server 2008 用の Internet Explorer 8 :
<a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">Windows XP および Windows Vista 用の Internet Explorer 8 でDEP を無効にしている環境を対象にした、安定した悪用コードが、作るられる可能性があります。
Windows Vista 用の Internet Explorer 8 で DEP を有効にしている場合、安定した悪用コードは見られないと考えられます。インターネット ゾーンで、ASLR/DEP の機能と .NET コンポーネントが既定で無効なことは、問題を緩和する要素となります。
Windows Server 2003 および Windows Server 2008 用の Internet Explorer 8 では、 セキュリティ強化の構成によって、インターネット ゾーンでスクリプトの実行ができないため、安定した悪用コードは見られないと考えられます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-020">MS09-020</a></td>
<td style="border:1px solid black;">インターネット インフォメーション サービス (IIS) の脆弱性により、特権が昇格される (970483)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1122">CVE-2009-1122</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">コードが実行される可能性は低いですが、認証が回避される状態のために、情報漏えいの可能性が高くなります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-020">MS09-020</a></td>
<td style="border:1px solid black;">インターネット インフォメーション サービス (IIS) の脆弱性により、特権が昇格される (970483)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1535">CVE-2009-1535</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">情報漏えいを引き起こす公開されたコードが存在します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;">Microsoft Office Excel の脆弱性により、リモートでコードが実行される (969462)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0549">CVE-2009-0549</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;">Microsoft Office Excel の脆弱性により、リモートでコードが実行される (969462)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0557">CVE-2009-0557</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;">Microsoft Office Excel の脆弱性により、リモートでコードが実行される (969462)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0558">CVE-2009-0558</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;">Microsoft Office Excel の脆弱性により、リモートでコードが実行される (969462)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0559">CVE-2009-0559</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">Office 2000 のみに、コードが実行される脅威が存在します。最新バージョンの Office に対してコードが実行される攻撃は起きにくいと思われます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;">Microsoft Office Excel の脆弱性により、リモートでコードが実行される (969462)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0560">CVE-2009-0560</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;">Microsoft Office Excel の脆弱性により、リモートでコードが実行される (969462)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0561">CVE-2009-0561</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-021">MS09-021</a></td>
<td style="border:1px solid black;">Microsoft Office Excel の脆弱性により、リモートでコードが実行される (969462)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1134">CVE-2009-1134</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-022">MS09-022</a></td>
<td style="border:1px solid black;">Windows 印刷スプーラーの脆弱性により、リモートでコードが実行される (961501)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0228">CVE-2009-0228</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-022">MS09-022</a></td>
<td style="border:1px solid black;">Windows 印刷スプーラーの脆弱性により、リモートでコードが実行される (961501)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0229">CVE-2009-0229</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">これは、情報漏えいの脆弱性で、コードが実行される可能性はありません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-022">MS09-022</a></td>
<td style="border:1px solid black;">Windows 印刷スプーラーの脆弱性により、リモートでコードが実行される (961501)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0230">CVE-2009-0230</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-023">MS09-023</a></td>
<td style="border:1px solid black;">Windows サーチの脆弱性により、情報漏えいが起こる (963093)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0239">CVE-2009-0239</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>3</strong> - 機能する見込みのない悪用コード</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-024">MS09-024</a></td>
<td style="border:1px solid black;">Microsoft Works コンバーターの脆弱性により、リモートでコードが実行される (957632)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1533">CVE-2009-1533</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-025">MS09-025</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、特権が昇格される (968537)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1123">CVE-2009-1123</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-025">MS09-025</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、特権が昇格される (968537)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1124">CVE-2009-1124</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-025">MS09-025</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、特権が昇格される (968537)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1125">CVE-2009-1125</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-025">MS09-025</a></td>
<td style="border:1px solid black;">Windows カーネルの脆弱性により、特権が昇格される (968537)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1126">CVE-2009-1126</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">安定した悪用コードは、Windows 2000 向けである可能性が高いです。このスタック バッファー オーバーフローの脆弱性の悪用によりコードが実行される可能性は、Windows XP および Windows Server 2003 では、/GS の保護により低減されます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-026">MS09-026</a></td>
<td style="border:1px solid black;">RPC の脆弱性により、特権が昇格される (970238)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0568">CVE-2009-0568</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">この脆弱性による、マイクロソフトのソフトウェアへの直接の影響はありません。しかし、このセキュリティ更新プログラムをインストールしていない場合、独立系ソフトウェア ベンダーの RPC サービスを実装しているワークステーションが影響を受ける可能性があります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-027">MS09-027</a></td>
<td style="border:1px solid black;">Microsoft Office Word の脆弱性により、リモートでコードが実行される (969514)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0563">CVE-2009-0563</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>2</strong> - 不安定な悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms09-027">MS09-027</a></td>
<td style="border:1px solid black;">Microsoft Office Word の脆弱性により、リモートでコードが実行される (969514)</td>
<td style="border:1px solid black;"><a href="http://cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0565">CVE-2009-0565</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/ja-jp/security/cc998259.aspx"><strong>1</strong> - 安定した悪用コードの可能性</a></td>
<td style="border:1px solid black;">(なし)</td>
</tr>
</tbody>
</table>

<p></p>

  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="8">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-018**](http://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](http://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](http://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](http://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](http://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](http://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](http://technet.microsoft.com/security/bulletin/ms09-023)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4 上の Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=bba6e20a-0345-46ae-a6f1-fd27fdee7c21&displaylang=ja)  
(KB969805)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=86378753-db24-44c2-a27d-cc0239f40ab8&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=d645ad82-13c3-4030-808b-834e86ed3298&displaylang=ja)  
(緊急)  
[Microsoft Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=fe8b3796-a407-4f41-89eb-35b4bcc24ff6&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=155a79c1-e5e4-4f62-b4b0-53aca59f20ac&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=79b0481d-a3d7-477b-928a-a98cc79374af&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Information Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=8515a294-4f25-4dc5-860a-e7ad9b6c1c01&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-018**](http://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](http://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](http://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](http://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](http://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](http://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](http://technet.microsoft.com/security/bulletin/ms09-023)
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
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 および Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Professional Service Pack 2 および Windows XP Professional Service Pack 3 上の Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=cb2c9b76-0c65-4754-9941-d45a7c74a29a&displaylang=ja)  
(KB970437)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f2119aca-a98e-4810-be52-f38241443baf&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=3d7f63ee-d7c3-48a5-902e-60625405e97d&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=827b735c-660b-4723-b688-3297e107153a&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d9e27ce1-4e7c-437f-9477-e7805a33da08&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f033fa78-c451-44f8-aa6c-a49622c37f40&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 および Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6349e046-a3f8-4ae5-b8c3-c9879cc99e8f&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional Service Pack 2 および Windows XP Professional Service Pack 3 上の Microsoft Internet Information Services 5.1](http://www.microsoft.com/downloads/details.aspx?familyid=97da589f-4534-42f6-9f29-967b5a33c542&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Search 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=759f22cb-ea7f-49dd-a200-19cb83fffd8d&displaylang=en)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=2ef3aaf0-a2a9-4c17-99ab-a0dc3d3f7e86&displaylang=ja)  
(KB970437)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=22699d09-1e68-456a-8733-bfad6667ebf5&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=088f70eb-c5c5-426a-880a-18ed386d0b56&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e5d2c81e-ffab-4e3b-a59a-a55000597213&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a24aedf0-7a31-4ee8-a9a6-998f1160c700&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=20734b70-37f1-47dd-bc09-d56f93577a55&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3769800e-af93-4a44-8a1e-b30cc54b226f&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=8982e6d2-e1f7-4208-88e3-80b159a8e21a&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Search 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=50c56dd6-c34d-4632-a779-8bcf8fdb341b&displaylang=en)  
(警告)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-018**](http://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](http://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](http://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](http://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](http://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](http://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](http://technet.microsoft.com/security/bulletin/ms09-023)
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
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=d814ce65-a193-4027-a6cd-106d388830a6&displaylang=ja)  
(KB969805)  
(重要)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=f6f99957-f74f-4446-8734-a468283eebae&displaylang=ja)  
(KB970437)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=865414f8-3f77-4fee-acc6-6684a3dc0aa4&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=72a23752-86fb-4cc9-ab8e-63ffdfae5bec&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a980b867-c67f-4c61-b6db-e55c2ca68dc0&displaylang=ja)  
(警告)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=298143f2-f37a-4a2c-86ac-9804d4ff1dad&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=62bb9e22-4f4b-4ffc-ba76-f626e94c79d5&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9356404c-d89a-4de0-b9b4-f6e1bdadf745&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=2bd4e410-dbd8-431a-b316-e1e2f1825c3a&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Search 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=e72ef31f-5161-4fe6-8ed3-6206e02cef31&displaylang=en)  
(警告)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=0d1f23c8-06eb-4996-92eb-0eb635fd6a42&displaylang=ja)  
(KB969805)  
(重要)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=1a2badc7-c0a5-4032-a009-73ebe9d76313&displaylang=ja)  
(KB970437)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=197a6cc7-4ba3-4d2e-b621-0ef3da645ef2&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=2a03d3c4-e39d-43a3-8d42-216e9551be96&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5e7d6372-9c8c-449d-88fd-afd4f92ad9e6&displaylang=ja)  
(警告)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4a5401d7-ca97-4734-a0e9-d7ffe0777e34&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=888b8dd8-d76c-42f5-a377-1f1750d3cf56&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5a3123af-173d-49eb-9997-14e82e764aee&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=ea363223-535d-4142-9aba-3890960c6259&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Search 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ffc3680-f9bf-423b-96a7-102f4cc9c240&displaylang=en)  
(警告)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=92e7808b-92ff-449d-bb73-ee8638e9ccd1&displaylang=ja)  
(KB969805)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=719efd62-fb33-447d-b6dd-2aaafbbad881&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=58efde2c-e0b8-4259-b19e-80564b834882&displaylang=ja)  
(警告)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a2d2907e-67ae-44a4-a805-8670e659ea57&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=3084f46e-02b9-4d99-a7a1-033817f9bd9f&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](http://www.microsoft.com/downloads/details.aspx?familyid=13b50993-410f-4e7a-a33a-6d9b48dbb4d1&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Information Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=e6b806eb-e2c4-4436-8964-720db593055d&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-018**](http://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](http://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](http://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](http://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](http://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](http://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](http://technet.microsoft.com/security/bulletin/ms09-023)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
(深刻度なし)
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
(深刻度なし)
</td>
<td style="border:1px solid black;">
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1, および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1, および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3ad8f037-2434-4dea-bfc3-9d3b4008b828&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e60215c3-b8b9-4e45-9d9f-b3fb0b47cce1&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6f2730e9-b4fc-4f20-96cf-73f1be63f374&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1, および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5ca227c0-f2dd-429c-a542-e08e93527214&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1, および Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c31b36f8-330c-4a0c-9a3d-7cbe9a1ab8c8&displaylang=ja)  
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
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1, および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1, および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=85c317cd-2a14-4747-9f50-3af3ddd3ae1b&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=88185088-8c2c-4bc6-89b2-87f4d4849cf7&displaylang=ja)  
(緊急)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5edb14f7-11ec-4180-9f0f-b2673f1c8d83&displaylang=ja)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1, および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=188adafe-1feb-46ad-b237-a88d35104dcd&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1, および Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d70a65f-07ce-4992-8bec-28fefd7587bc&displaylang=ja)  
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
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-018**](http://technet.microsoft.com/security/bulletin/ms09-018)
</td>
<td style="border:1px solid black;">
[**MS09-022**](http://technet.microsoft.com/security/bulletin/ms09-022)
</td>
<td style="border:1px solid black;">
[**MS09-019**](http://technet.microsoft.com/security/bulletin/ms09-019)
</td>
<td style="border:1px solid black;">
[**MS09-026**](http://technet.microsoft.com/security/bulletin/ms09-026)
</td>
<td style="border:1px solid black;">
[**MS09-025**](http://technet.microsoft.com/security/bulletin/ms09-025)
</td>
<td style="border:1px solid black;">
[**MS09-020**](http://technet.microsoft.com/security/bulletin/ms09-020)
</td>
<td style="border:1px solid black;">
[**MS09-023**](http://technet.microsoft.com/security/bulletin/ms09-023)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
(深刻度なし)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
(深刻度なし)
</td>
<td style="border:1px solid black;">
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f18356d-9f09-4d24-8361-970c0d1ccac4&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a0e3f975-57da-43fa-ac12-3d14fd6ce939&displaylang=ja)\*\*  
(警告)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=aaad301c-d232-4733-a0df-8e5d41bbfde8&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=eaa26c6c-5bf7-4099-bb21-1e03de3a25ca&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=98ba52b2-da1a-4939-a10e-d43b3a7e7ed4&displaylang=ja)\*  
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
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d0a6e8d-a31d-4f3d-a7d7-e61215bfebed&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=758edce7-2a82-4b2e-bd71-5b7075cc4b17&displaylang=ja)\*\*  
(警告)  
[Windows Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=faac92d4-4a2b-4bb5-8bd1-1519a9fa8147&displaylang=ja)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=447aaa4f-946b-4f23-b151-dcf46ea9f80e&displaylang=ja)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dbaa5a72-c267-4907-a207-525c2803d7b9&displaylang=ja)\*  
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
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bbac3deb-6c93-45aa-832c-02b915ac7f44&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=67d4c189-030d-42eb-98b9-7957ccd92592&displaylang=ja)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f33012b9-5d5b-4f72-8d49-a8e1c8bc1337&displaylang=ja)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0e3ad56-a363-44ba-af4d-b7f551c88afd&displaylang=ja)  
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

<p></p>

 
**Windows Server 2008 に関する注意**

**\*Windows Server 2008 Server Core インストールは影響を受けます。** サポートされているエディションの Windows Server 2008 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、同じ深刻度でこの更新プログラムが適用されます。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx)をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

**\*\*Windows Server 2008 Server Core インストールは影響を受けません。** この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用して Windows Server 2008 をインストールした場合、サポートされているエディションの Windows Server 2008 に影響を与えません。このインストール オプションに関する詳細情報は、[Server Core](http://www.microsoft.com/japan/windowsserver2008/servercore.mspx)をご覧ください。Windows Server 2008 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core のインストールオプションの比較](http://www.microsoft.com/japan/windowsserver2008/editions/core.mspx)をご覧ください。

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
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4">
Microsoft Office スイート,システム, およびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-027**](http://technet.microsoft.com/security/bulletin/ms09-027)
</td>
<td style="border:1px solid black;">
[**MS09-021**](http://technet.microsoft.com/security/bulletin/ms09-021)
</td>
<td style="border:1px solid black;">
[**MS09-024**](http://technet.microsoft.com/security/bulletin/ms09-024)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3663e9f2-a952-4238-b902-90b5b09feb38&displaylang=ja)  
(KB969600)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=dd16e243-b8e2-4afb-86b6-4d60214598eb&displaylang=ja)  
(KB969683)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4bf95806-3d32-411b-9779-a81aebad45e9&displaylang=ja)  
(KB957838)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f1323be1-15f2-491b-abae-c03ba1394398&displaylang=ja)  
(KB969602)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=dd80ce95-0aec-4493-b9d1-c3dad95c3415&displaylang=ja)  
(KB969680)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b0ba8c9e-75ee-46bd-9e92-d4e6599309ad&displaylang=ja)  
(KB957646)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7cbc2587-2c8c-49b4-9f40-e4cdccb61ecd&displaylang=ja)  
(KB969603)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=10156044-a5a4-4312-98a7-1b1ced625ddb&displaylang=ja)  
(KB969681)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Works 6-9 ファイル コンバーターを含む Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a7ba3ea7-d06a-4c14-9107-9b92ef68fcae&displaylang=ja)\*\*\*  
(KB968326)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1 および 2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 Service Pack 1 および Microsoft Office Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7e205108-4c28-4cab-a4d0-4ed3fd696473&displaylang=ja)  
(KB969604)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 および Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2bcd565a-6acb-407d-80da-0398526ddf99&displaylang=ja)\*  
(KB969682)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=bd47e1e5-cd2e-4c08-9864-471e97f38ca3&displaylang=ja)  
(KB969559)  
(重要)
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-027**](http://technet.microsoft.com/security/bulletin/ms09-027)
</td>
<td style="border:1px solid black;">
[**MS09-021**](http://technet.microsoft.com/security/bulletin/ms09-021)
</td>
<td style="border:1px solid black;">
[**MS09-024**](http://technet.microsoft.com/security/bulletin/ms09-024)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
(深刻度なし)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550&displaylang=ja)  
(KB969661)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550&displaylang=ja)  
(KB969661)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58&displaylang=ja)  
(KB971822)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58&displaylang=ja)  
(KB971822)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6&displaylang=ja)  
(KB971824)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6&displaylang=ja)  
(KB971824)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="4">
その他の Office ソフトウェア
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID 番号**
</td>
<td style="border:1px solid black;">
[**MS09-027**](http://technet.microsoft.com/security/bulletin/ms09-027)
</td>
<td style="border:1px solid black;">
[**MS09-021**](http://technet.microsoft.com/security/bulletin/ms09-021)
</td>
<td style="border:1px solid black;">
[**MS09-024**](http://technet.microsoft.com/security/bulletin/ms09-024)
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
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](http://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=20e6933d-85f8-4cec-9534-893789cd053e&displaylang=ja)  
(KB969685)  
(重要)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=ac0530dc-7f63-4ad0-85c1-784ad28156cf&displaylang=ja)  
(KB969686)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b&displaylang=ja)  
(KB969614)  
(重要)  
[Microsoft Office Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b&displaylang=ja)  
(KB969614)  
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
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=63bd8f14-e736-46ce-af66-d30f17461e5a&displaylang=ja)  
(KB969613)  
(重要)
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8be8457-b0b6-455e-907e-d13be883adf2&displaylang=ja)  
(KB969679)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?familyid=628280fe-e035-4274-85f2-393d9bad543c&displaylang=ja)  
(KB967043)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762)  
(KB967044)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 1 および Microsoft Office SharePoint Server 2007 Service Pack 2 (32 ビット版)](http://www.microsoft.com/downloads/details.aspx?familyid=862e6ad1-8124-4060-93b1-2b882ef5ce3d&displaylang=ja)\*\*  
(KB969737)  
(重要)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 および Microsoft Office SharePoint Server 2007 Service Pack 2 (64 ビット版)](http://www.microsoft.com/downloads/details.aspx?familyid=b7b6e611-2c5d-4639-add9-972055789ecd&displaylang=ja)\*\*  
(KB969737)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**MS09-021 に関する注意**

\*Microsoft Office Excel 2007 Service Pack 1 および Microsoft Office Excel 2007 Service Pack 2 について、KB969682 に加え、お客様は [Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 1 および Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2 (KB969679)](http://www.microsoft.com/downloads/details.aspx?familyid=a8be8457-b0b6-455e-907e-d13be883adf2&displaylang=ja) をインストールして、このセキュリティ情報で説明している脆弱性から防御する必要があります。

\*\*この更新プログラムは、Excel サービスがインストールされているサーバーに適用されます。例えば、既定の構成の Microsoft Office SharePoint Server 2007 Enterprise および Microsoft Office SharePoint Server 2007 For Internet Sites などが挙げられます。Microsoft Office SharePoint Server 2007 Standard は Excel サービスを含みません。

**MS09-024 に関する注意**

\*\*\*Microsoft Office Word 2003 に影響を受ける Works コンバーターをインストールしている場合、危険にさらされます。Microsoft Office Word 2003 用の Works コンバーターは、[Microsoft Works 6-9 ファイル コンバーター](http://www.microsoft.com/downloads/details.aspx?familyid=bf41401e-70fa-465d-ae2e-cf44dbf05297&displaylang=ja)でダウンロードできます。

検出および展開ツールとガイダンス
--------------------------------


**セキュリティ セントラル**

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細情報は、[TechNet 更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)をご覧ください。[セキュリティ TechCenter](http://technet.microsoft.com/ja-jp/security/default.aspx)では、製品に関するセキュリティ情報を提供しています。

コンシューマーのお客様は [セキュリティ At Home](http://www.microsoft.com/japan/protect) をご覧ください。この情報は「最新のセキュリティ更新プログラムを入手する」をクリックすることによってもご覧いただけます。

セキュリティ更新プログラムは [Microsoft Update](http://update.microsoft.com/microsoftupdate/)、[Windows Update](http://windowsupdate.microsoft.com/) および [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) から利用可能です。セキュリティ更新プログラムは[マイクロソフト ダウンロード センター](http://www.microsoft.com/downloads/results.aspx?displaylang=ja&freetext=security%20update)からダウンロードすることができます。「security update」のキーワード探索によって容易に見つけることができます。さらに、セキュリティ更新プログラムは Windows Update カタログからダウンロードできます。「アップデートのカタログ」の関連情報を参照するには、サポート技術情報 [323166](http://support.microsoft.com/kb/323166) をご覧ください。

**検出および適用のガイダンス**

マイクロソフトは今月のセキュリティ更新プログラムについての検出および適用のガイダンスを提供しました。このガイダンスは、IT プロフェッショナルが Windows Update、Microsoft Update、Office Update、Microsoft Baseline Security Analyzer (MBSA)、Office 検出 Tool、Microsoft Systems Management Server (SMS)、Extended Security Update Inventory Tool および Enterprise Update Scan Tool (EST) など、各種ツールを使用したセキュリティ更新プログラムの適用方法を理解するのに役立ちます。詳細情報は、サポート技術情報 [910723](http://support.microsoft.com/kb/910723) をご覧ください。

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

-   MS09-018 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Joshua J. Drake 氏
-   MS09-018 で説明している問題について報告してくださった [Beaverton School District](http://www.beaverton.k12.or.us/home/) の Justin Wyatt 氏
-   MS09-019 で説明している問題について報告してくださった [Google Inc.](http://www.google.com/) の David Bloom 氏
-   MS09-019 で説明している問題について報告してくださった [Core Security Technologies](http://www.coresecurity.com/) の Jorge Luis Alvarez Medina 氏
-   MS09-019 で説明している問題について報告してくださった Fortinet の [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) の Haifei Li 氏
-   MS09-019 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   MS09-019 で説明している問題について [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった Peter Vreugdenhil 氏
-   MS09-019 で説明している問題について [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった Wushi 氏
-   MS09-019 で説明している問題について [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった Nils 氏
-   MS09-020 で説明している問題について報告してくださった [Palo Alto Networks](http://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS09-021 で説明している問題について報告してくださった Fortinet の [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) の Bing Liu 氏
-   MS09-021 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Sean Larsson 氏および Joshua Drake 氏
-   MS09-021 で説明している問題について報告してくださった [TELUS Security Labs Vulnerability Research Team](http://telussecuritylabs.com/)
-   MS09-021 で説明している問題について報告してくださった [Secunia](http://secunia.com/) の Carsten H. Eiram 氏
-   MS09-021 で説明している問題について報告してくださった [TippingPoint](http://www.tippingpoint.com/) および [Zero Day Initiative](http://www.zerodayinitiative.com/)
-   MS09-022 で説明している問題について報告してくださった [VeriSign iDefense Labs](http://labs.idefense.com/) の Jun Mao 氏
-   MS09-023 で説明している問題について報告してくださった [IBM Rational Application Security](http://blog.watchfire.com/) の Yair Amit 氏
-   MS09-024 で説明している問題について報告してくださった [NGS Software](http://www.ngssoftware.com/) の Shaun Colley 氏および[(株)フォティーンフォティ技術研究所](http://www.fourteenforty.jp/)の鵜飼 裕司 氏
-   MS09-025 で説明している問題について報告してくださった Thomas Garnier 氏
-   MS09-027 で説明している問題について [Zero Day Initiative](http://www.zerodayinitiative.com/) と協力して報告してくださった、[team509](http://www.team509.com/) の Wushi 氏
-   MS09-027 で説明している問題について報告してくださった [VUPEN Security](http://www.vupen.com/) の Nicolas Joly 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](http://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](http://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2009/06/10: このセキュリティ情報ページを公開しました。
-   2009/06/11: このセキュリティ情報ページを更新し、CVE-2009-1138 について、Exploitability Index (悪用可能性指標) の 「Exploitability Index の評価」および「注意事項」を修正しました。

*Built at 2014-04-18T01:50:00Z-07:00*
