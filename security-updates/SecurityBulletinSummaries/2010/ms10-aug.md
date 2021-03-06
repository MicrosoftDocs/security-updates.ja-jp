---
TOCTitle: 'MS10-AUG'
Title: 2010 年 8 月のセキュリティ情報
ms:assetid: 'ms10-aug'
ms:contentKeyID: 61229671
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms10-aug(v=Security.10)'
--- 

2010 年 8 月のセキュリティ情報
==============================

公開日: 2010年8月3日 | 最終更新日: 2010年9月2日

**バージョン:** 1.0

[![](../../images/Dn627250.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627250.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

絵でみるセキュリティ情報
------------------------

 
[MS10-046 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-046e.mspx)

[MS10-047 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-047e.mspx)

[MS10-048 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-048e.mspx)

[MS10-049 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-049e.mspx)

[MS10-050 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-050e.mspx)

[MS10-051 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-051e.mspx)

[MS10-052 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-052e.mspx)

[MS10-053 : Internet Explorer の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-053e.mspx)

[MS10-054 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-054e.mspx)

[MS10-055 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-055e.mspx)

[MS10-056 : Word の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-056e.mspx)

[MS10-057 : Excel の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-057e.mspx)

[MS10-058 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-058e.mspx)

[MS10-059 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-059e.mspx)

[MS10-060 : Windows の重要な更新](https://www.microsoft.com/japan/security/bulletins/ms10-060e.mspx)

このセキュリティ情報は 2010 年 8 月に公開したセキュリティ情報の一覧です。

2010 年 8 月 3 日のセキュリティ情報 (定例外) の公開により、2010 年 7 月 31 日に定例外で公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://technet.microsoft.com/security/bulletin/advance)」をご覧ください。

また、2010 年 8 月 11 日に定例リリースしました 14 件のセキュリティ情報に関する情報を追加しました。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2010 年 8 月 11 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

また、マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問を解決するため、2010 年 8 月 11 日 午後 1:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[8 月のセキュリティ情報 Webcast (英語) に登録する。](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454431&eventcategory=4&culture=en-us&countrycode=us)詳細は、[Microsoft Security Bulletin Summaries and Webcasts](https://technet.microsoft.com/security/bulletin/summary) (英語) をご覧ください。

マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の優先度の高い更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄をご覧ください。

### セキュリティ情報

概要
----

 
次の表は今月のセキュリティ情報を深刻度順にまとめたものです。

影響を受けるソフトウェアの詳細は、次の影響を受けるソフトウェアおよびダウンロード先のセクションをご覧ください。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >タイトルおよび概要</th>
<th style="border:1px solid black;" >最大深刻度および脆弱性の影響</th>
<th style="border:1px solid black;" >再起動情報</th>
<th style="border:1px solid black;" >影響を受けるソフトウェア</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-046">MS10-046</a></td>
<td style="border:1px solid black;"><strong>Windows シェルの脆弱性により、リモートでコードが実行される (2286198)</strong><br />
<br />
このセキュリティ更新プログラムは1 件の Windows シェルに存在する一般で公開された脆弱性を解決します。この脆弱性により、特別に細工したショートカットのアイコンが表示された場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-049">MS10-049</a></td>
<td style="border:1px solid black;"><strong>SChannel の脆弱性により、リモートでコードが実行される (980436)</strong><br />
<br />
このセキュリティ更新プログラムは Windows のセキュリティで保護されたチャネル (SChannel) のセキュリティ パッケージの非公開で報告された脆弱性 1 件と公開された脆弱性 1 件を解決します。解決する脆弱性のうち、より深刻な脆弱性については、インターネット Web ブラウザーを介してこれらの脆弱性の悪用を意図して設計された特別な細工がされた Web サイトをユーザーが訪問した場合にリモートでコードが実行される可能性があります。しかし、すべての場合において、これらの Web サイトに強制的にユーザーを訪問させることはできません。その代わり、攻撃者はユーザーを攻撃者の Web サイトに訪問させようとします。一般的には、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせ、攻撃者の Web サイトへ誘導します。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-051">MS10-051</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML コア サービスの脆弱性により、リモートでコードが実行される (2079403)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft XML コア サービスに存在する 1 件の脆弱性を解決します。この脆弱性では、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。攻撃者は、これらの Web サイトにユーザーを強制的に訪問させることはできません。通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-052">MS10-052</a></td>
<td style="border:1px solid black;"><strong>Microsoft MPEG Layer-3 コーデックの脆弱性により、リモートでコードが実行される (2115168)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 1 件の MPEG Layer-3 オーディオ コーデックの脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたメディア ファイルを開くか、または Web サイトや Web コンテンツを配信するアプリケーションから特別な細工がされたストリーミング コンテンツを受け取った場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-053">MS10-053</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (2183461)</strong><br />
<br />
この累積的なセキュリティ更新プログラムは非公開で報告された 6 件の Internet Explorer に存在する脆弱性を解決します。これらの脆弱性の中で最も深刻な脆弱性が悪用された場合、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-054">MS10-054</a></td>
<td style="border:1px solid black;"><strong>SMB サーバーの脆弱性により、リモートでコードが実行される (982214)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された複数の Microsoft Windows に存在する脆弱性を解決します。これらの中で最も深刻な脆弱性では、攻撃者が特別に細工された SMB パケットを作成し、そのパケットを影響を受けるコンピューターに送信した場合、リモートでコードが実行される可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からのこの脆弱性を悪用しようとする攻撃を防ぎ、ネットワークを保護することができます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-055">MS10-055</a></td>
<td style="border:1px solid black;"><strong>Cinepak Codec の脆弱性により、リモートでコードが実行される (982665)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Cinepak Codec に存在する脆弱性を解決します。この脆弱性で、ユーザーが特別な細工がされたメディア ファイルを開くか、または Web サイトや Web コンテンツを配信するアプリケーションから特別な細工がされたストリーミング コンテンツを受け取った場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ローカルのユーザーと同じユーザー権限を取得する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-056">MS10-056</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Word の脆弱性により、リモートでコードが実行される (2269638)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 4 件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性で最も深刻な場合、特別に細工された RTF 形式の電子メール メッセージをユーザーが開く、またはプレビューした場合、リモートでコードが実行される可能性があります。これらの脆弱性が悪用された場合、攻撃者によりローカル ユーザーと同じ権限が取得される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-060">MS10-060</a></td>
<td style="border:1px solid black;"><strong>Microsoft .NET 共通言語ランタイムおよび Microsoft Silverlight の脆弱性により、リモートでコードが実行される (2265906)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Microsoft .NET Framework および Microsoft Silverlight に存在する 2 件の脆弱性を解決します。これらの脆弱性により、ユーザーが特別に細工された Web ページを XAML ブラウザー アプリケーション (XBAPs) または Silverlight アプリケーションを実行できる Web ブラウザーで表示した場合、または攻撃者がユーザーを誘導して特別に細工した Microsoft .NET アプリケーションを実行させた場合に、クライアント システム上で、リモートでコードが実行される可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。これらの脆弱性により、サーバーが ASP.NET ページの処理を許可し、攻撃者が特別に細工した ASP.NET ページをそのサーバーにアップロードできる場合に、Web ホスティングのシナリオと同様に、IIS を実行しているサーバー システム上で、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、Microsoft .NET Framework、Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-047">MS10-047</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルの脆弱性により、特権が昇格される (981852)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された複数の Microsoft Windows に存在する脆弱性を解決します。これらの中で最も深刻な脆弱性では、攻撃者がローカルでログオンし、特別に細工したアプリケーションを実行した場合、特権が昇格される可能性があります。これらの脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-048">MS10-048</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (2160329)</strong><br />
<br />
このセキュリティ更新プログラムは Windows カーネルモード ドライバーに存在する 1 件の公開された脆弱性および 4 件の非公開で報告された脆弱性を解決します。最も深刻な脆弱性では、攻撃者が影響を受けるコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはありません。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-050">MS10-050</a></td>
<td style="border:1px solid black;"><strong>Windows ムービー メーカーの脆弱性により、リモートでコードが実行される (981997)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 1 件の Windows ムービー メーカーの脆弱性を解決します。この脆弱性は、攻撃者が特別に細工した ムービー メーカーのプロジェクト ファイルを送信して、ユーザーに特別に細工したファイルを表示させた場合にリモートでコードが実行される可能性があります。コンピューターでユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-057">MS10-057</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office Excel の脆弱性により、リモートでコードが実行される (2269707)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Office に存在する 1 件の脆弱性を解決します。この脆弱性は、特別に細工された Excel ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、ログオンしたユーザーと同じユーザー権限を取得する可能性があります。システムで、アカウントのユーザー権限を低く設定している場合、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性の影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-058">MS10-058</a></td>
<td style="border:1px solid black;"><strong>TCP/IP の脆弱性により、特権が昇格される (978886)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft Windows に存在する脆弱性を解決します。これらの脆弱性で、最も深刻な場合、特定の入力バッファー処理のエラーにより、特権の昇格が起こる可能性があります。標的のシステムにログオン可能な攻撃者は、この脆弱性を悪用して、システム レベルの特権で任意のコードを実行する可能性があります。その後、攻撃者はプログラムのインストール、データの表示、変更、削除、または完全なユーザー権限を持つ新たなアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/ms10-059">MS10-059</a></td>
<td style="border:1px solid black;"><strong>サービスのトレース機能の脆弱性により、特権が昇格される (982799)</strong><br />
<br />
このセキュリティ更新プログラムは、一般に公開された １ 件、および 非公開で報告された 1 件のサービスのトレース機能の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工されたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効なログオン資格情報を所持し、ローカルでログオンできることが攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーにより、この脆弱性が悪用されることはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、悪用の可能性が高いものから順に、次に CVE ID の順に記載しています。セキュリティ情報に記載されている深刻度が緊急または重要の脆弱性のみです。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報のリリース後 30 日以内に機能する悪用コードが公開される可能性を確認してください。適用の優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味に関する詳細は、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) をご覧ください。
  
| セキュリティ情報 ID                                                 | 脆弱性タイトル                                                                         | CVE ID                                                                           | Exploitability Index の評価                                                                         | 注意事項                                                                                                                                                    |  
|---------------------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-060](https://technet.microsoft.com/security/bulletin/ms10-060) | Microsoft Silverlight のメモリ破損の脆弱性                                             | [CVE-2010-0019](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0019) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-052](https://technet.microsoft.com/security/bulletin/ms10-052) | MPEG Layer-3 オーディオ デコーダーのバッファー オーバーフローの脆弱性                  | [CVE-2010-1882](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1882) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-047](https://technet.microsoft.com/security/bulletin/ms10-047) | Windows カーネルのデータ初期化の脆弱性                                                 | [CVE-2010-1888](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1888) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-058](https://technet.microsoft.com/security/bulletin/ms10-058) | Windows ネットワーキングの整数のオーバーフローの脆弱性                                 | [CVE-2010-1893](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1893) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-048](https://technet.microsoft.com/security/bulletin/ms10-048) | Win32k の例外処理の脆弱性                                                              | [CVE-2010-1894](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1894) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | **この脆弱性は一般に公開されています。**                                                                                                                    |  
| [MS10-048](https://technet.microsoft.com/security/bulletin/ms10-048) | Win32k のプール オーバーフローの脆弱性                                                 | [CVE-2010-1895](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1895) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-048](https://technet.microsoft.com/security/bulletin/ms10-048) | Win32k のユーザー入力の検証の脆弱性                                                    | [CVE-2010-1896](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1896) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-048](https://technet.microsoft.com/security/bulletin/ms10-048) | Win32k のウィンドウ作成の脆弱性                                                        | [CVE-2010-1897](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1897) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-060](https://technet.microsoft.com/security/bulletin/ms10-060) | Microsoft Silverlight および Microsoft .NET Framework CLR の仮想メソッドの委任の脆弱性 | [CVE-2010-1898](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1898) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-056](https://technet.microsoft.com/security/bulletin/ms10-056) | Word のレコードの解析の脆弱性                                                          | [CVE-2010-1900](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1900) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-056](https://technet.microsoft.com/security/bulletin/ms10-056) | Word の RTF 形式の解析エンジンのメモリ破損の脆弱性                                     | [CVE-2010-1901](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1901) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-055](https://technet.microsoft.com/security/bulletin/ms10-055) | Cinepak Codec の展開の脆弱性                                                           | [CVE-2010-2553](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2553) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-059](https://technet.microsoft.com/security/bulletin/ms10-059) | トレースのメモリ破損の脆弱性                                                           | [CVE-2010-2555](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2555) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-053](https://technet.microsoft.com/security/bulletin/ms10-053) | 初期化されていないメモリ破損の脆弱性                                                   | [CVE-2010-2557](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2557) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | この脆弱性は、緩和策となるデータ実行防止機能のない Internet Explorer 6 での悪用が高いと考えられます。                                                       |  
| [MS10-053](https://technet.microsoft.com/security/bulletin/ms10-053) | HTML レイアウトのメモリ破損の脆弱性                                                    | [CVE-2010-2560](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2560) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-057](https://technet.microsoft.com/security/bulletin/ms10-057) | Excel のメモリ破損の脆弱性                                                             | [CVE-2010-2562](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2562) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-050](https://technet.microsoft.com/security/bulletin/ms10-050) | ムービー メーカーのメモリ破損の脆弱性                                                  | [CVE-2010-2564](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2564) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-046](https://technet.microsoft.com/security/bulletin/ms10-046) | ショートカット アイコンの読み込みの脆弱性                                              | [CVE-2010-2568](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2568) | [**1**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 安定した悪用コードの可能性     | **この脆弱性は現在インターネット エコシステムで悪用されています。**                                                                                         |  
| [MS10-047](https://technet.microsoft.com/security/bulletin/ms10-047) | Windows カーネルのダブル フリーの脆弱性                                                | [CVE-2010-1889](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1889) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-056](https://technet.microsoft.com/security/bulletin/ms10-056) | Word の RTF 形式の解析のバッファー オーバーフローの脆弱性                              | [CVE-2010-1902](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1902) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | Windows Vista および Windows 7 では、追加のヒープ緩和策のメカニズムにより悪用の可能性は低減されます。                                                       |  
| [MS10-056](https://technet.microsoft.com/security/bulletin/ms10-056) | Word HTML リンクオブジェクトのメモリ破損の脆弱性                                       | [CVE-2010-1903](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1903) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-054](https://technet.microsoft.com/security/bulletin/ms10-054) | SMB のプール オーバーフローの脆弱性                                                    | [CVE-2010-2550](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2550) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | 悪用はコードの実行よりもサービス拒否の可能性が高いと考えられます。                                                                                          |  
| [MS10-053](https://technet.microsoft.com/security/bulletin/ms10-053) | 初期化されていないメモリ破損の脆弱性                                                   | [CVE-2010-2556](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2556) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-053](https://technet.microsoft.com/security/bulletin/ms10-053) | 競合状態のメモリ破損の脆弱性                                                           | [CVE-2010-2558](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2558) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-053](https://technet.microsoft.com/security/bulletin/ms10-053) | 初期化されていないメモリ破損の脆弱性                                                   | [CVE-2010-2559](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2559) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-051](https://technet.microsoft.com/security/bulletin/ms10-051) | Msxml2.XMLHTTP.3.0 応答処理のメモリ破損の脆弱性                                        | [CVE-2010-2561](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2561) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | (なし)                                                                                                                                                      |  
| [MS10-049](https://technet.microsoft.com/security/bulletin/ms10-049) | SChannel の不正な形式の証明書リクエストのリモートでコードが実行される脆弱性            | [CVE-2010-2566](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2566) | [**2**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 不安定な悪用コードの可能性     | 悪用はサービス拒否になる可能性が高いと考えられます。リモートでコード実行される可能性は低いと考えられます。                                                  |  
| [MS10-049](https://technet.microsoft.com/security/bulletin/ms10-049) | TLS/SSL の再ネゴシエーションの脆弱性                                                   | [CVE-2009-3555](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3555) | [**3**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | これは、なりすましの脆弱性です。[マイクロソフト セキュリティ アドバイザリ 977377](https://technet.microsoft.com/security/advisory/977377) で説明しています。 |  
| [MS10-053](https://technet.microsoft.com/security/bulletin/ms10-053) | イべント ハンドラーのクロス ドメインの脆弱性                                           | [CVE-2010-1258](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1258) | [**3**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | これは、情報漏えいの脆弱性です。                                                                                                                            |  
| [MS10-058](https://technet.microsoft.com/security/bulletin/ms10-058) | IPv6 のメモリ破損の脆弱性                                                              | [CVE-2010-1892](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1892) | [**3**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | これは、サービス拒否の脆弱性です。                                                                                                                          |  
| [MS10-054](https://technet.microsoft.com/security/bulletin/ms10-054) | SMB の変数の検証の脆弱性                                                               | [CVE-2010-2551](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2551) | [**3**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | これは、サービス拒否の脆弱性です。                                                                                                                          |  
| [MS10-054](https://technet.microsoft.com/security/bulletin/ms10-054) | SMB のスタック消費の脆弱性                                                             | [CVE-2010-2552](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2552) | [**3**](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) - 機能する見込みのない悪用コード | これは、サービス拒否の脆弱性です。                                                                                                                          |
  
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
<th colspan="14">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-046**](https://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](https://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](https://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](https://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](https://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](https://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](https://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](https://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](https://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](https://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](https://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](https://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](https://technet.microsoft.com/security/bulletin/ms10-059)
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
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=12361875-b453-45e8-852b-90f2727894fd)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ff00381c-e74b-48e5-9dd9-34dbedd906a2)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=dbdbbe5e-2ef9-4704-80c4-27ef28fd95ef)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=08159149-17de-4640-8818-cb7bd4811531)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bc949915-4e16-4897-a295-2f99102548ab)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4b489f8c-ada0-4051-8284-0a941c04d2ed)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1662780f-370a-425b-9917-c601eb54a375)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6e5e16f8-c140-4a1d-b898-8417a6bfd4d8)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5ddb5e34-f97a-47c6-96c8-ba2ed06ccb77)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e3574047-5ce5-4461-94aa-4eb3258d5e71)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=deeac521-d3a2-4019-8176-c9228e733cf4)  
(重要)
</td>
<td style="border:1px solid black;">
[ムービー メーカー 2.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b211664b-434d-4626-816f-c77510cfd44d)<sup>[1]</sup>
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
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3b44bd67-48e2-497f-9165-42a702e2cc0d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=eaffa70c-6f2b-4e66-b1bc-64bdbbbcd34f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4d4e8eeb-a0b2-41c6-9ee4-3f4beb44195e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b7f28d7a-6b27-4059-865b-5fd55edb6299)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=96b7a562-af16-4f0d-840c-838fb12e7419)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5296fb82-c446-4681-a9a0-0f80a2e248be)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f8ae3978-bad6-4201-8357-2d212ab703ef)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=fd6cc359-e72e-46ec-a08b-763934e3e115)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5cff5d6e-11a5-40ed-92ac-e12d287919e6)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d6c5455e-bc31-4842-aef4-ebff92324323)  
(重要)
</td>
<td style="border:1px solid black;">
[ムービー メーカー 2.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=decb1fe6-adc8-44f7-89c5-f25767f0cefe)<sup>[1]</sup>
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
<th colspan="14">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-046**](https://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](https://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](https://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](https://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](https://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](https://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](https://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](https://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](https://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](https://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](https://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](https://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](https://technet.microsoft.com/security/bulletin/ms10-059)
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
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=32fe91ef-5a8d-4095-90ee-2ca216696b09)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f76d68df-97e5-489c-a5f6-0c378c1f62ae)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=31ce233e-4d2d-404b-84a8-683319ba8ef7)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9c2110ec-7e6c-4e73-9785-0a8196095ea0)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b0370e1e-dedf-4fe8-a06c-0e0f0a674205)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8753ae27-60a4-475a-b8bc-6a7764480295)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=772e765d-0502-4b0b-bde8-d4f62b96db64)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=230e8559-e6df-49d5-acb5-b0cd4bde0bf4)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=59395f00-90f4-4b68-8dd3-03ff611c1bc8)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=923de214-c4fa-41e6-8307-2c5a37f13e8e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4543bcf0-3505-407b-a5a9-6250ece6fbac)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4d784b57-8564-4e7e-8f61-f897398e7ea5)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=fdfad4ca-37c4-4ac5-bebc-a5ad61299503)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d92f5e69-43cf-4615-aa3b-41f9f40bb57b)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=fd3e9d06-1f8b-4ef7-84f6-61e85a1767b8)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=863edf45-0d3b-4408-a47c-258dc4a4fd94)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=03804f59-748e-4832-98e4-2d88564bd10a)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9ef1c600-bb93-4800-81b8-8c64b369c194)  
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
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=63aa5f8a-fe47-4892-b905-b54e4f3b6580)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9ef992c3-96e9-4533-b844-07424a6054b3)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d87ac8b3-41fb-4cdd-b305-181a0024d85c)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=782e2963-4a52-4a1d-b99a-34ba841038a7)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5e730064-8270-4d63-b497-c5ebeddea1fc)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e4f4f8b3-7a39-4d77-a46b-02c86ad159c3)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=648cfca5-19eb-4658-a6ad-fe546c4c44b9)  
(KB983582)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1e53f250-2d4b-4f61-86ee-9f9f3a9c0b48)  
(KB983583)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f96b8154-9976-41b0-b9d7-d79887fe9364)  
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
<th colspan="14">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-046**](https://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](https://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](https://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](https://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](https://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](https://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](https://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](https://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](https://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](https://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](https://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](https://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](https://technet.microsoft.com/security/bulletin/ms10-059)
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
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
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
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
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
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=52748886-6280-4247-8cbd-f64db229ee66)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=aca69406-f795-4398-968f-959fe3a74e89)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=bbfaadf8-ab38-456c-956a-ea18c64236c9)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=535c563e-cdac-4e3d-96b0-9947ea22deca)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2062566b-8b81-43c2-875d-9c06d4e3fa82)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9087a3aa-aa55-41f6-8c4c-f322e4aa8681)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=60c81415-b61e-44a4-8dd9-cedec99eb70f)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)  
(KB983587)  
(緊急)  
Windows Vista Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=155bbb5c-247e-4bed-a287-527d978b7967)  
(KB983588)  
(緊急)  
Windows Vista Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)  
(KB983589)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4486f97c-4cf8-4236-bfc3-b50e72e2a5c1)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c9345207-7242-4b71-bf80-b52031e08f8c)  
(重要)
</td>
<td style="border:1px solid black;">
[ムービー メーカー 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8aded9dd-08d6-4b19-955f-0d8414868cf9)<sup>[1]</sup>
(重要)  
[ムービー メーカー 2.6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a1d8ed0d-a3b5-416a-ab8b-77501da62132)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4684c4df-0a5c-4dba-82e5-059378737118)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=dfb31aa2-7457-4581-9e28-7984a360edf4)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=37648e95-05c2-4802-9a0f-660200baa229)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e2835ed1-5ca6-4347-8ff1-e694b1ac49ff)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=577131cd-1229-4746-89d7-84d75f29e1f0)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=cd1185e3-ca22-4197-a53b-e7a2806ac352)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=65b04e29-8e39-46de-94e8-b653969b1ffd)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=10c9d5f1-53ed-459b-a663-e69bdb845a6b)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=469b732d-ca62-4a48-bb55-99f2ae4ddcf5)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)  
(KB983587)  
(緊急)  
Windows Vista x64 Edition Service Pack 1 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=155bbb5c-247e-4bed-a287-527d978b7967)  
(KB983588)  
(緊急)  
Windows Vista x64 Edition Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)  
(KB983589)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b547898e-f8a9-49dc-b49d-cffec5a001bc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=1620e7ac-3913-478d-8120-e9f46d98f453)  
(重要)
</td>
<td style="border:1px solid black;">
[ムービー メーカー 6.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4baff9ae-dd25-4942-b45e-f281d0e1f4ac)<sup>[1]</sup>
(重要)  
[ムービー メーカー 2.6](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0a226592-8f98-4f67-ac60-1d00cbc56598)<sup>[2]</sup>
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=18152cd4-815f-425f-8694-fbabcbe80609)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=110f932f-d13c-4486-a295-e6068d5d8d7a)  
(重要)
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-046**](https://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](https://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](https://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](https://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](https://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](https://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](https://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](https://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](https://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](https://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](https://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](https://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](https://technet.microsoft.com/security/bulletin/ms10-059)
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
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
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
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
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
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3aabd189-7d4c-4c9f-8854-f33127b1c309)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6e0253d4-f0c0-4f28-ba08-6907c2fcb339)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=73b5f45c-c9d6-491f-8483-98838b2a7c04)\*  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8239cb9e-bb5a-4157-8038-33d0b329eaee)\*\*  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=409b9298-1e7d-48cf-9872-ffbdc56ebe53)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a94e2e38-116a-4b63-9328-6c33e63bbbfe)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)\*\*  
(KB983587)  
(緊急)  
Windows Server 2008 for 32-bit Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=155bbb5c-247e-4bed-a287-527d978b7967)\*\*  
(KB983588)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)\*\*  
(KB983589)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=611765ab-b3f3-45db-92b2-ee040b9cfd27)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a8b1a3f7-7147-494e-bfc0-b1979b9578e6)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=844404be-f2e8-47bc-9650-9e2bbe383814)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4c9b3e60-e166-40c9-8938-3cba0a399c47)\*  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=29c6fc2d-d318-4a63-9ab2-82e84272aaf2)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a96891ff-8771-47b3-81bb-8640adb6c098)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=43ece408-4aa7-4819-b3f6-7f0719ed3213)\*  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5ef8abf0-c89e-4911-8d77-42400d9a398f)\*\*  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9b869bab-0797-4f83-8c64-23dda9983c8d)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=602dd3f6-0d09-4546-b1db-d7b6b04edb66)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)\*\*  
(KB983587)  
(緊急)  
Windows Server 2008 for x64-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=155bbb5c-247e-4bed-a287-527d978b7967)\*\*  
(KB983588)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)\*\*  
(KB983589)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=131f3512-1585-462e-a4f1-3f359aac44bd)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c1c25cb7-7e82-4c14-9666-aff52dd308b4)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=08491c73-66b1-4c4c-8740-ea596a730fc1)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=fa84e547-2190-402f-9467-2450deeff565)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=cfe227b5-6660-49f8-9d71-a997dd83de0b)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3b16a422-0ee9-4eab-9cfe-e7688ffa0d76)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b6faee94-e821-432d-bfa2-9008664566af)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2f1eee63-2cca-4ec5-b196-36de3c0054cf)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=24d8f0a3-51a9-46c1-b870-a2239bf600e4)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=616c39f7-137a-40b9-b691-bc33c0aef7e1)  
(KB983587)  
(緊急)  
Windows Server 2008 for Itanium-based Systems のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=155bbb5c-247e-4bed-a287-527d978b7967)  
(KB983588)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2 のみ:  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7712e8ad-dea4-4a43-8a7b-dc154510c104)  
(KB983589)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=972efd3a-ec1e-49b2-835e-76f4b21b5b79)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=45fe5135-aa89-4f60-8cdb-ec0edc9a7e77)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8aa12902-c234-4fd9-bba3-6767eafc38fc)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=84f89dca-108c-4956-9aa2-866e17a872fc)  
(重要)
</td>
</tr>
<tr>
<th colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-046**](https://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](https://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](https://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](https://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](https://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](https://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](https://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](https://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](https://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](https://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](https://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](https://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](https://technet.microsoft.com/security/bulletin/ms10-059)
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
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
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
Windows 7 for 32-bit Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=22e62b5c-e4c1-47d0-ae4a-8bd2d70d0a0a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=71716507-7080-4102-991e-6afc7cc377d5)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=31d0f5ac-2cff-42a1-8f18-128bbfc4e57d)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ecaf42e0-a288-40c1-8602-21e967a87408)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=8d58ebc4-a5f9-4318-a6f1-168c1bcdae3c)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2e782ac9-b5d5-490e-a01a-7d4481eab224)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=77d0c428-237c-4dab-9645-6400dd9e65f8)  
(KB983590)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a7d60864-5942-47ed-a6f3-1c07b4833a14)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=68bddf4b-b597-477e-80e4-9293d7160496)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=3a5a088e-644a-4a0e-9a09-0370bcd97688)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ce6233f3-2ee5-4329-908d-ba9b28ecc553)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=9499f771-c388-4de3-a5c7-8cc8b00b4395)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c457d8ec-83b7-446f-b77c-e47d4187e616)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a4f6d7c2-b475-4900-82f0-75f5be0b7b63)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ca57a47a-9111-4abe-9356-4962ca2c1d65)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ad1ddf94-d714-4b36-8256-42bf79d03a90)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=24751193-592f-4c44-a8d6-f4112d4f011b)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=77d0c428-237c-4dab-9645-6400dd9e65f8)  
(KB983590)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b00ec47c-402e-4207-a4c9-6c1900f254f8)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=5ff09e03-d662-4b23-ab26-d25ca2ba58df)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=163fe2bd-f999-47c1-9a35-c4fc868bda51)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=146270fa-cd6f-440a-aa3e-e93af0bff447)  
(重要)
</td>
</tr>
<tr>
<th colspan="14">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-046**](https://technet.microsoft.com/security/bulletin/ms10-046)
</td>
<td style="border:1px solid black;">
[**MS10-049**](https://technet.microsoft.com/security/bulletin/ms10-049)
</td>
<td style="border:1px solid black;">
[**MS10-051**](https://technet.microsoft.com/security/bulletin/ms10-051)
</td>
<td style="border:1px solid black;">
[**MS10-052**](https://technet.microsoft.com/security/bulletin/ms10-052)
</td>
<td style="border:1px solid black;">
[**MS10-053**](https://technet.microsoft.com/security/bulletin/ms10-053)
</td>
<td style="border:1px solid black;">
[**MS10-054**](https://technet.microsoft.com/security/bulletin/ms10-054)
</td>
<td style="border:1px solid black;">
[**MS10-055**](https://technet.microsoft.com/security/bulletin/ms10-055)
</td>
<td style="border:1px solid black;">
[**MS10-060**](https://technet.microsoft.com/security/bulletin/ms10-060)
</td>
<td style="border:1px solid black;">
[**MS10-047**](https://technet.microsoft.com/security/bulletin/ms10-047)
</td>
<td style="border:1px solid black;">
[**MS10-048**](https://technet.microsoft.com/security/bulletin/ms10-048)
</td>
<td style="border:1px solid black;">
[**MS10-050**](https://technet.microsoft.com/security/bulletin/ms10-050)
</td>
<td style="border:1px solid black;">
[**MS10-058**](https://technet.microsoft.com/security/bulletin/ms10-058)
</td>
<td style="border:1px solid black;">
[**MS10-059**](https://technet.microsoft.com/security/bulletin/ms10-059)
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
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
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
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**警告**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[**重要**](https://technet.microsoft.com/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
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
Windows Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0d9dd09b-db40-462b-88b0-4dbb8180e81f)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c9aeea25-ca14-4b42-9018-a27c9d8899c4)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a48cdac5-4d78-49b5-a6d8-ecf6c58cace2)\*  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=e7757bbc-3ef0-421d-ab57-0083a302c77b)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=52642a8d-1081-4496-848e-9b03baf3fdac)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=77d0c428-237c-4dab-9645-6400dd9e65f8)\*  
(KB983590)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c1ad1248-07f1-42d4-baa4-8a20837ec7b4)\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6bbc9cb1-0b59-4473-adf9-2ce2f0f94c0a)\*  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a1f95600-34e5-44b3-b2cb-b2b2cbf645cb)\*  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=333fb6e4-f867-4dcb-beb3-2d88e428ca2e)\*  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ce2bb5d4-f661-44e3-ac28-0b81f7b72670)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b7c2e91f-ca8a-4237-99c8-ca53c91cf73e)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft XML コア サービス 3.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=b4d3210e-f3ad-4dbb-9390-6e98eeb99eaa)  
(警告)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7b457d04-03a9-4eb0-ba6a-ab45267e4f74)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=783fb42c-3698-4b1d-a692-3ff319578931)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=77d0c428-237c-4dab-9645-6400dd9e65f8)  
(KB983590)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=f23dec0f-a33b-4d8c-a86d-0e9368ae7ff5)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=2543191a-09cb-4417-bbb2-aac4d9a2a756)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=c3cd7f2f-e198-4fbd-a65d-21a1bf51eb61)  
(重要)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=62034ecb-a6bd-46c5-a03d-9642880bc2d6)  
(重要)
</td>
</tr>
</table>

<p></p>

 
**Windows Server 2008 および Windows Server 2008 R2 に関する注意**

**\*Server Core インストールは影響を受けます。**サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションに関する詳細情報は、[Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Server Core インストール オプションは Windows Server 2008 および Windows Server 2008 R2 の特定のエディションにのみ適用する事ができます。詳細は、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)をご覧ください。

**\*\*Server Core インストールは影響を受けません。**この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用してインストールした場合、サポートされているエディションの Windows Server 2008 および Windows Server 2008 R2 に影響を与えません。このインストール オプションに関する詳細情報は MSDN コラム [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx) をご覧ください。

**MS10-050 に関する注意**

<sup>[1]</sup> これらのバージョンの Windows ムービー メーカーは、表示されたオペレーティング システムと出荷されます。

<sup>[2]</sup> Windows ムービー メーカー 2.6 はオプションのダウンロードで、表示されたオペレーティング システムにインストールすることが可能です。

**MS10-060 に関する注意**

「影響を受けるソフトウェアおよびダウンロードの場所」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は 1 種類以上のソフトウェアを対象にしています。

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
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-056**](https://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](https://technet.microsoft.com/security/bulletin/ms10-057)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=978eb887-25b6-4dde-a2ec-d2d1e7f1a434)  
(KB2251389)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=032e1530-8736-4e1c-a704-967679227619)  
(KB2264397)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=4360bcec-0731-4d4a-89eb-7d28a4607f06)  
(KB2251399)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7cecbce3-bbb7-47d1-bda3-64d7e0f69f62)  
(KB2264403)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=0d7210a3-662e-41e7-affc-ae94f9d89388) <sup>[1]</sup>
(KB2251419)  
(緊急)
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
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-056**](https://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](https://technet.microsoft.com/security/bulletin/ms10-057)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**最大深刻度**
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
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d2f44d4a-7cd8-4514-b3ff-1770bc47d595)  
(KB2284171)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=d2f44d4a-7cd8-4514-b3ff-1770bc47d595)  
(KB2284171)  
(重要)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6ece112f-0ca7-4b1f-ad20-603950edee66)  
(KB2284162)  
(重要)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=6ece112f-0ca7-4b1f-ad20-603950edee66)  
(KB2284162)  
(重要)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a7b834a3-5a44-42d4-afe9-6ef207333834)  
(KB2284179)  
(重要)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=a7b834a3-5a44-42d4-afe9-6ef207333834)  
(KB2284179)  
(重要)
</td>
</tr>
<tr>
<th colspan="3">
その他 Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-056**](https://technet.microsoft.com/security/bulletin/ms10-056)
</td>
<td style="border:1px solid black;">
[**MS10-057**](https://technet.microsoft.com/security/bulletin/ms10-057)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
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
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=39fe2229-9201-4270-bdc1-20bc8e30a766)  
(KB2251437)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2
</td>
<td style="border:1px solid black;">
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=ed5b9671-651d-41f3-aed3-93ee8a28657f)  
(KB2277947)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](https://www.microsoft.com/download/details.aspx?familyid=feb121ad-e5f6-40e2-bf12-045ae5c2a754)  
(KB2092914)  
(重要)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
**MS10-056 に関する注意**

<sup>[1]</sup>Microsoft Office Word 2007 Service Pack 2 について、お客様は MS10-056 で説明している脆弱性を阻止するため、セキュリティ更新プログラム パッケージ KB2251419 に加えて Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2 用のセキュリティ更新プログラム (KB2277947) もインストールする必要があります。

#### Microsoft 開発ツールおよびソフトウェア

 
<p></p>

<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**
</td>
<td style="border:1px solid black;">
[**MS10-060**](https://technet.microsoft.com/security/bulletin/ms10-060)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**最大深刻度**
</td>
<td style="border:1px solid black;">
[**緊急**](https://technet.microsoft.com/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 2
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 2](https://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup> Mac にインストールされている場合  
(KB982926)  
(緊急)  
[Microsoft Silverlight 2](https://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup> すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている場合  
(KB982926)  
(緊急)  
[Microsoft Silverlight 2](https://www.microsoft.com/getsilverlight/get-started/install/default.aspx)<sup>[1]</sup> すべてのサポートされているリリースの Microsoft Windows サーバー\*\* にインストールされている場合  
(KB982926)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Silverlight 3
</td>
<td style="border:1px solid black;">
[Microsoft Silverlight 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850) <sup>[2]</sup> Mac にインストールされている場合  
(KB978464)  
(緊急)  
[Microsoft Silverlight 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850)<sup>[2]</sup> すべてのサポートされているリリースの Microsoft Windows クライアントにインストールされている場合  
(KB978464)  
(緊急)  
[Microsoft Silverlight 3](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7e3f6c16-1339-49bc-a60c-ddc6c3a54850)<sup>[2]</sup>すべてのサポートされているリリースの Microsoft Windows サーバー\*\* にインストールされている場合  
(KB978464)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
**MS10-060 に関する注意**

**\*Server Core インストールは影響を受けません。**この更新プログラムが解決している脆弱性は、Server Core インストールオプションを使用してインストールした場合、サポートされているエディションの Windows Server 2008 および Windows Server 2008 R2 に影響を与えません。このインストール オプションに関する詳細情報は MSDN コラム [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) をご覧ください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細は、[Server Core インストールオプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx) をご覧ください。

<sup>[1]</sup> このダウンロードは、Microsoft Silverlight 2 を、これらの脆弱性の影響を受けないより新しいバージョンの Microsoft Silverlight にアップグレードします。

<sup>[2]</sup> この更新プログラムは Microsoft Silverlight をこれらの脆弱性による影響を受けないより新しいビルドにアップグレードします。

「影響を受けるソフトウェアおよびダウンロードの場所」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は 1 種類以上のソフトウェアを対象にしています。

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

Windows Server Update Services によるセキュリティ更新プログラムの配布に関する詳細は [Windows Server Update Services Web サイト](https://technet.microsoft.com/ja-jp/wsus/default.aspx) をご覧ください｡

**Systems Management Server**

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、構成可能なエンタープライズ ソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのコンピューターを識別し、エンド ユーザーへの中断を最小限にして、エンタープライズ全体にこれらの更新プログラムの適用を管理することができます。管理者が SMS 2003 を使用してセキュリティ更新プログラムを展開する方法に関する詳細情報は [SMS 2003 セキュリティ パッチの管理](https://www.microsoft.com/japan/smserver/evaluation/capabilities/patch.mspx)をご覧下さい。SMS 2.0 をご使用のお客様は、セキュリティ更新プログラムの適用を補助するツールである [SMS Software Update Services Feature Pack](https://www.microsoft.com/japan/smserver/evaluation/overview/featurepacks/suspack.mspx) を使用することもできます。SMS に関する情報は、[Microsoft Systems Management Server](https://www.microsoft.com/japan/smserver/default.mspx) をご覧ください。

**注:** SMS は Microsoft Baseline Security Analyzer および Microsoft Office 検出ツールを活用してセキュリティ情報で提供された更新プログラムの検出と適用について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のコンピューターへの更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順に関する情報は、[Deploying Software Updates Using the SMS Software Distribution Feature](https://www.microsoft.com/japan/technet/prodtechnol/sms/sms2003/patchupdate.mspx) をご覧ください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、SMS 2.0 Administration Feature Pack の上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja) および [SMS 2.0 Administration Feature Pack](https://www.microsoft.com/japan/smserver/downloads/20/featurepacks/adminpack/) で利用可能) は、これらの更新プログラムのインストールに使用することができます。

**Update Compatibility Evaluator および Application Compatibility Toolkit**

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit 5.0](https://www.microsoft.com/download/details.aspx?displaylang=ja&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価するために必要なツールやドキュメントが含まれています。

### 関連情報

#### MU、WU、および WSUS でのセキュリティ以外の優先度の高い更新プログラム

Windows Update および Microsoft Update のセキュリティ以外のリリースの詳細は、次をご覧ください。

-   サポート技術情報 [894199](https://support.microsoft.com/kb/894199/): Software Update Services の説明と Windows Server Update Services 2010 の内容の変更。すべての Windows のコンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services.](https://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報): Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。この様な保護環境を提供するセキュリティ ソフトウェア ベンダーの情報は、[Microsoft Active Protections Program (MAPP) Partners](https://www.microsoft.com/security/msrc/mapp/partners.mspx) (英語情報) に記載されている各社の Web サイトをご覧ください。

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

この問題を連絡し、顧客の保護に協力して下さった下記の方に対し、マイクロソフトは深い謝意を表します。

-   MS10-046 で説明している問題を報告してくださった [VirusBlokAda](https://www.vba.com.by/) の Sergey I. Ulasen 氏および Oleg Kupreev 氏
-   MS10-046 で説明している問題を報告してくださった [AV-Test](https://www.av-test.org/) の Andreas Marx 氏および Maik Morgenstern 氏
-   MS10-046 で説明している問題についてマイクロソフトと協力してくださった [CERT/CC](https://www.cert.org/) の Will Dormann 氏
-   MS10-046 で説明している問題についてマイクロソフトと協力してくださった Niels Teusink 氏
-   MS10-046 で説明している問題についてマイクロソフトと協力してくださった Stefan Kanthak 氏
-   MS10-047 で説明している 3 件の問題を報告してくださった [Google Inc.](https://www.google.com/) の Tavis Ormandy 氏
-   MS10-048 で説明している問題を報告してくださった [Google Inc.](https://www.google.com/) の Tavis Ormandy 氏
-   MS10-048 で説明している 2 件の問題を報告してくださった [MoonSols](https://moonsols.com/) の Matthieu Suiche 氏
-   MS10-048 で対応した多層防御の変更についてマイクロソフトと協力してくださった [MoonSols](https://moonsols.com/) の Matthieu Suiche 氏
-   MS10-048 で説明している問題を報告してくださった [Core Security Technologies](https://www.coresecurity.com/) の Nicolás Economou 氏
-   MS10-049 で説明している問題を報告してくださった [PhoneFactor](https://www.phonefactor.com/) の Marsh Ray 氏および Steve Dispensa 氏
-   MS10-050 で説明している問題を報告してくださった [Secunia](https://secunia.com/) の Dyon Balding 氏
-   MS10-051 で説明している問題を報告してくださった [Google Inc.](https://www.google.com/) の SkyLined 氏
-   MS10-052 で説明している問題を報告してくださった [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力している n.runs AG の Moritz Jodeit 氏
-   MS10-053 で説明している問題を報告してくださった [Google Inc.](https://www.google.com/) の David Bloom 氏
-   MS10-053 で説明している問題を報告してくださった [VUPEN Vulnerability Research Team](https://www.vupen.com) の Nicolas Joly 氏
-   MS10-053 で説明している問題を報告してくださった Gambino ZaDarkSide 氏
-   MS10-054 で説明している問題を報告してくださった [stratsec](https://www.stratsec.net/) の Laurent Gaffié 氏
-   MS10-054 で説明している問題を報告してくださった [Sourcefire VRT](https://www.sourcefire.com/services/sf_vrt.html) の Todd Wease 氏と Richard Johnson 氏
-   MS10-054 で説明している問題を報告してくださった [Codenomicon](https://www.codenomicon.com/) の Riku Hietamaki 氏と Joshua Morin 氏
-   MS10-055 で説明している問題を報告してくださった [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力している匿名のリサーチャー
-   MS10-056 で説明している問題を [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と協力し報告してくださった [team509](https://www.team509.com/) の L.W.Z 氏
-   MS10-056 で説明している問題を [VeriSign iDefense Labs](https://labs.idefense.com/) と協力し報告してくださった [team509](https://www.team509.com/) の Wushi 氏
-   MS10-056 で説明している問題を [VeriSign iDefense Labs](https://labs.idefense.com/) と協力し報告してくださった [team509](https://www.team509.com/)
-   MS10-056 で説明している問題を報告してくださった [Check Point](https://www.checkpoint.com/) IPS Research Team の Rodrigo Rubira Branco 氏
-   MS10-056 で説明している問題を[TippingPoint](https://www.tippingpoint.com/) の[Zero Day Initiative](https://www.zerodayinitiative.com/) と協力し報告してくださいった匿名のリサーチャー
-   MS10-057 で説明している問題を報告してくださった [Core Security Technologies](https://www.coresecurity.com/) の Damián Frizza 氏
-   MS10-058 で説明している問題を報告してくださった [Fourteenforty Research Institute, Inc.](https://www.fourteenforty.jp/) の Darren Willis 氏
-   MS10-058 で説明している問題を報告してくださった [MoonSols](https://moonsols.com/) の Matthieu Suiche 氏
-   MS10-059 で説明している 2 件の問題についてマイクロソフトと協力してくださった [Argeniss](https://www.argeniss.com/) の Cesar Cerrudo 氏
-   MS10-060 で説明している問題を報告してくださった の Carsten Book 氏
-   MS10-060 で説明している問題を報告してくださった [Eamon Nerbonne](https://eamon.nerbonne.org/) 氏

#### サポート

-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などありましたら、[マイクロソフト セキュリティ情報センター](https://www.microsoft.com/japan/security/sicinfo.mspx)までご連絡ください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いた します。マイクロソフト プロダクト サポートへの連絡方法は [こちら](https://support.microsoft.com/select/?target=assistance) をご覧ください。

#### 免責 :

本セキュリティ情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失 利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。(Microsoft Corporation、その関連会社またはこれらの者の供給者がかかる損害の発生可能性を了知している場合を含みます。) 結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴 :

-   2010/08/03: このセキュリティ情報ページを公開しました。
-   2010/08/11: 8 月の定例セキュリティ情報 MS10-047 から MS10-060 を追加しました。
-   2010/09/02: このセキュリティ情報を更新し、Word 2007 をご使用のお客様に、このセキュリティ情報で説明している脆弱性を阻止するためにセキュリティ更新プログラム パッケージ KB2251419 に加えて、セキュリティ更新プログラム パッケージ KB2277947 もインストールする必要があることをお知らせするためにMS10-056 に関する注意を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
