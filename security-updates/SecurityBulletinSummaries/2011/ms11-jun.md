---
TOCTitle: 'MS11-JUN'
Title: 2011 年 6 月のセキュリティ情報
ms:assetid: 'ms11-jun'
ms:contentKeyID: 61229688
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms11-jun(v=Security.10)'
--- 

2011 年 6 月のセキュリティ情報
==============================

公開日: 2011年6月15日 | 最終更新日: 2012年1月25日

**バージョン:** 3.1

[![](../../images/Dn627267.onepoint_summary(ja-JP,Security.10).jpg)](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)[![](../../images/Dn627267.SNS300x50(ja-JP,Security.10).jpg)](https://profile.microsoft.com/regsysprofilecenter/subscriptionwizard.aspx?wizid=cbdde499-aa75-4a75-9cb3-f48eac2e7c3f&lcid=1041)

このセキュリティ情報の概要は 2011 年 6 月公開のセキュリティ情報の一覧です。

2011 年 6 月のセキュリティ情報の公開により、2011 年 6 月 10 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、[「マイクロソフト セキュリティ情報の事前通知」](https://technet.microsoft.com/ja-jp/security/bulletin/advance)を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://technet.microsoft.com/ja-jp/security/dd252948)」を参照してください。

マイクロソフトは公開したセキュリティ更新プログラムの概要を説明用スライドと音声でお伝えする日本語の Webcast 情報を 2011 年 11 月 9 日 の午後 (日本時間) に配信予定です。詳細は、「[今月のワンポイント セキュリティ情報](https://technet.microsoft.com/ja-jp/security/dd251169.aspx)」をご覧ください。

マイクロソフトはこれらのセキュリティ情報に関するお客様からの質問にお答えするため、2011 年 6 月 15 日午前 11:00 (太平洋標準時刻、米国およびカナダ) に Webcast を行う予定です。[6 月の セキュリティ情報 Webcast に今すぐご登録ください](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032455073&eventcategory=4) (英語)。この日付以降、この Webcast はオンデマンドで利用可能となります。詳細については、[Microsoft Security Summaries and Webcasts](https://go.microsoft.com/fwlink/?linkid=217214) (英語情報) を参照してください。

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-038">MS11-038</a></td>
<td style="border:1px solid black;">OLE オートメーションの脆弱性により、リモートでコードが実行される (2476490) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft Windows Object Linking and Embedding (OLE) オートメーションの脆弱性を解決します。この脆弱性により、ユーザーが、特別な細工がされた Windows メタファイル (WMF) イメージが含まれる Web サイトを訪問した場合に、リモートでコードが実行される可能性があります。しかし、すべての場合において、攻撃者がユーザーにそのような Web サイトを強制的に訪問させる方法はありません。そのため、通常、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのリクエストに含まれるリンクをクリックさせることにより、悪質な Web サイトを訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039">MS11-039</a></td>
<td style="border:1px solid black;">.NET Framework および Microsoft Silverlight の脆弱性により、リモートでコードが実行される (2514842) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft .NET Framework および Microsoft Silverlight の脆弱性を解決します。この脆弱性では、ユーザーが XAML ブラウザー アプリケーション (XBAP) または Silverlight アプリケーションを使用して、特別に細工された Web ページを閲覧した場合に、クライアント システムでリモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この脆弱性により、サーバーが ASP.NET ページの処理を許可し、攻撃者が特別に細工した ASP.NET ページをそのサーバーにアップロードして、ページを実行した場合に、Web ホスティングのシナリオと同様に、IIS を実行しているサーバー システム上で、リモートでコードが実行される可能性があります。この脆弱性は、コード アクセス セキュリティ (CAS) の制限を回避する目的で Windows .NET で悪用される可能性もあります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework、<br />
Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-040">MS11-040</a></td>
<td style="border:1px solid black;">Threat Management Gateway ファイアウォール クライアントの脆弱性により、リモートでコードが実行される (2520426) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft Forefront Threat Management Gateway (TMG) 2010 クライアント (旧 Microsoft Forefront Threat Management Gateway ファイアウォール クライアント) の脆弱性を解決します。攻撃者がこの脆弱性を悪用して、TMG ファイアウォール クライアントが使用されているシステム上で、ある特定のリクエストを作成するよう仕向けた場合に、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Forefront Threat Management Gateway</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-041">MS11-041</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーの脆弱性により、リモートでコードが実行される (2525694) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性で、ユーザーが特別に細工された OpenType フォント (OTF) を含むネットワーク共有 (またはネットワーク共有をポイントする Web サイト) を訪問した場合に、リモートでコードが実行される可能性があります。しかし、すべての場合において、攻撃者がユーザーにそのような Web サイトまたはネットワーク共有を強制的に訪問させる方法はありません。そのため、通常、電子メール メッセージまたはインスタント メッセンジャーのメッセージに含まれるリンクをユーザーにクリックさせることにより、ユーザーに Web サイトまたはネットワーク共有を訪問させることが、攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042">MS11-042</a></td>
<td style="border:1px solid black;">分散ファイル システムの脆弱性により、リモートでコードが実行される (2535512) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 2 件の Microsoft 分散ファイル システム (DFS) の脆弱性を解決します。これらの脆弱性でより深刻な脆弱性により、攻撃者がクライアントの送出した DFS リクエストに対して、特別に細工された DFS 応答を返信した場合に、リモートでコードが実行される可能性があります。攻撃者はこの脆弱性を悪用し、任意のコードを実行し、影響を受けるコンピューターを完全に制御する可能性があります。ファイアウォールによる最善策および標準のファイアウォールの既定の構成を使用することにより、組織のネットワーク境界の外部からの攻撃を防ぎ、ネットワークを保護することができます。インターネットに接続したシステムについては、最善策として最低限の数のポートしか開かないようにすることを推奨します。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-043">MS11-043</a></td>
<td style="border:1px solid black;">SMB クライアントの脆弱性により、リモートでコードが実行される (2536276) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性で、攻撃者が特別に細工された SMB の応答を起動済みのクライアントの SMB リクエストに送信した場合、リモートでコードが実行される可能性があります。この脆弱性が悪用されるには、ユーザーに特別な細工がされた SMB サーバーへの接続を開始させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-044">MS11-044</a></td>
<td style="border:1px solid black;">.NET Framework の脆弱性により、リモートでコードが実行される (2538814)  <br />
<br />
このセキュリティ更新プログラムは Microsoft .NET Framework に存在する一般に公開された脆弱性を解決します。この脆弱性では、ユーザーが XAML ブラウザー アプリケーション (XBAP) を使用して、特別に細工された Web ページを閲覧した場合、クライアント システムで、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。この脆弱性により、サーバーが ASP.NET ページの処理を許可し、攻撃者が特別に細工した ASP.NET ページをそのサーバーにアップロードして、ページを実行した場合に、Web ホスティングのシナリオと同様に、IIS を実行しているサーバー システム上で、リモートでコードが実行される可能性があります。この脆弱性は、コード アクセス セキュリティ (CAS) の制限を回避する目的で Windows .NET で悪用される可能性もあります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">Internet Explorer 用の累積的なセキュリティ更新プログラム (2530548) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された 11 件の Internet Explorer に存在する脆弱性を解決します。最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がローカル ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-052">MS11-052</a></td>
<td style="border:1px solid black;">Vector Markup Language の脆弱性により、リモートでコードが実行される (2544521) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Windows に実装された Vector Markup Language (VML) の脆弱性を解決します。このセキュリティ更新プログラムは、Windows クライアント上の Internet Explorer 6、Internet Explorer 7 および Internet Explorer 8 について深刻度を「緊急」と評価し、Windows サーバー上の Internet Explorer 6、Internet Explorer 7 および Internet Explorer 8 について深刻度を「警告」と評価しています。Internet Explorer 9 は、この脆弱性による影響を受けません。<br />
<br />
この脆弱性により、ユーザーが Internet Explorer を使用して特別に細工された Web ページを表示すると、リモートでコードが実行される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">緊急</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-037">MS11-037</a></td>
<td style="border:1px solid black;">MHTML の脆弱性により、情報漏えいが起こる (2544893) <br />
<br />
このセキュリティ更新プログラムは Microsoft Windows の MHTML プロトコル ハンドラーに存在する一般に公開された脆弱性を解決します。この脆弱性により、ユーザーが攻撃者の Web サイトから特別に細工された URL を開くと、情報漏えいが起こる可能性があります。この脆弱性が悪用されるには、通常、電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをユーザーにたどらせ、その Web サイトを訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Microsoft Excel の脆弱性により、リモートでコードが実行される (2537146) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 8 件の Microsoft Office に存在する脆弱性を解決します。これらの脆弱性は、特別に細工された Excel ファイルをユーザーが開いた場合、リモートでコードが実行される可能性があります。これらの脆弱性のいずれかが悪用された場合、攻撃者がログオン ユーザーと同じ権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。Office のファイル検証機能 (OFV) をインストールおよび構成して疑わしいファイルを開くことを防ぐことにより、CVE-2011-1272、CVE-2011-1273、および CVE-2011-1279 で説明している脆弱性を悪用するための攻撃手法をブロックします。Microsoft Excel 2010 のみが、このセキュリティ情報で説明している CVE-2011-1273 による影響を受けます。自動化された Microsoft Fix it ソリューション「Excel 2010 の保護されたビューでの編集を無効にする」がサポート技術情報 2501584 に用意されており、CVE-2011-1273 で説明している脆弱性を悪用する攻撃の手法をブロックします。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a><br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-046">MS11-046</a></td>
<td style="border:1px solid black;">Ancillary Function ドライバーの脆弱性により、特権が昇格される (2503665) <br />
<br />
このセキュリティ更新プログラムは、一般に公開された 1 件の Microsoft Windows Ancillary Function ドライバー (AFD) の脆弱性を解決します。この脆弱性により、攻撃者がユーザーのシステムにログオンし、特別に細工されたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-047">MS11-047</a></td>
<td style="border:1px solid black;">Hyper-V の脆弱性により、サービス拒否が起こる (2525835) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows Server 2008 Hyper-V および Windows Server 2008 R2 Hyper-V の脆弱性を解決します。この脆弱性により、Hyper-V サーバーがホストしているゲスト仮想マシンの 1 台で、認証済みユーザーが特別に細工されたパケットを VMBus に送信した場合、サービス拒否が起こる可能性があります。この脆弱性を悪用する場合は、有効なログオン資格情報を所持し、ゲストの仮想マシンから特別に細工されたコンテンツを送信できることが、攻撃者にとっての必要条件となります。リモートで、または匿名ユーザーが、この脆弱性を悪用することはないと思われます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-048">MS11-048</a></td>
<td style="border:1px solid black;">SMB サーバーの脆弱性により、サービス拒否が起こる (2536275) <br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性では、攻撃者が特別に細工された SMB パケットを作成し、影響を受けるコンピューターにそのパケットを送信した場合に、サービス拒否が起きる可能性があります。ファイアウォールに関するベスト プラクティスおよび標準の既定のファイアウォール構成を使用することにより、組織のネットワーク境界の外部からのこの脆弱性を悪用しようとする攻撃を防ぎ、ネットワークを保護することができます。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049">MS11-049</a></td>
<td style="border:1px solid black;">Microsoft XML エディターの脆弱性により、情報漏えいが起こる (2543893) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft XML エディターの脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Web Service Discovery (.disco) ファイルを、このセキュリティ情報に記載された影響を受けるソフトウェアで開いた場合に、情報漏えいが起こる可能性があります。この脆弱性により、攻撃者は直接コードを実行したり、ユーザーの権限を昇格させたりできませんが、攻撃者はこの脆弱性を悪用し、攻撃に使用する情報を作成し、影響を受けるコンピューターをさらに侵害しようとする可能性があります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a><br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft SQL Server、<br />
Microsoft Visual Studio</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-051">MS11-051</a></td>
<td style="border:1px solid black;">Active Directory 証明書サービスの Web 登録の脆弱性により、特権が昇格される (2518295) <br />
<br />
このセキュリティ更新プログラムは、非公開で報告された Active Directory 証明書サービスの Web 登録の脆弱性を解決します。この脆弱性は、クロスサイト スクリプト (XSS) の脆弱性で、特権を昇格し、標的となるユーザーのコンテキストで、攻撃者がサイト上で任意のコマンドを実行することが可能になります。この脆弱性を悪用された場合、特別に細工されたリンクを送信し、ユーザーにそれをクリックさせるように誘導される可能性があります。ただし、いずれの場合も、攻撃者が強制的にユーザーをこのような Web サイトにアクセスさせることはできません。その代わりに、影響を受けた Web サイトにユーザーを誘導する電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをユーザーにクリックさせて、攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/rating">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>

<p></p>

  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
 
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
この表はどのように使用しますか?
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259.aspx) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<p></p>

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ情報 ID</th>
<th style="border:1px solid black;" >脆弱性のタイトル</th>
<th style="border:1px solid black;" >CVE の識別番号</th>
<th style="border:1px solid black;" >最新のソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >旧バージョンのソフトウェアのリリースに関するコード実行の Exploitability (悪用可能性) の評価</th>
<th style="border:1px solid black;" >サービス拒否の悪用可能性の評価</th>
<th style="border:1px solid black;" >注意事項</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-037">MS11-037</a></td>
<td style="border:1px solid black;">MHTML の MIME 形式のリクエストの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1894">CVE-2011-1894</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。<br />
<br />
これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-038">MS11-038</a></td>
<td style="border:1px solid black;">OLE オートメーションのアンダーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0658">CVE-2011-0658</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039">MS11-039</a></td>
<td style="border:1px solid black;">.NET Framework の配列のオフセットの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0664">CVE-2011-0664</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-040">MS11-040</a></td>
<td style="border:1px solid black;">TMG ファイアウォール クライアントのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1889">CVE-2011-1889</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-041">MS11-041</a></td>
<td style="border:1px solid black;">Win32k の OTF の検証の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1873">CVE-2011-1873</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042">MS11-042</a></td>
<td style="border:1px solid black;">DFS のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1868">CVE-2011-1868</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042">MS11-042</a></td>
<td style="border:1px solid black;">DFS の照会応答の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1869">CVE-2011-1869</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-043">MS11-043</a></td>
<td style="border:1px solid black;">SMB 応答の解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1268">CVE-2011-1268</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-044">MS11-044</a></td>
<td style="border:1px solid black;">.NET Framework の JIT の最適化の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1271">CVE-2011-1271</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Excel の不十分なレコード検証の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1272">CVE-2011-1272</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Excel の不適切なレコード解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1273">CVE-2011-1273</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Excel の境界外の配列アクセスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1274">CVE-2011-1274</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Excel のメモリのヒープの上書きの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1275">CVE-2011-1275</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Excel のバッファー オーバーランの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1276">CVE-2011-1276</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Excel のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1277">CVE-2011-1277</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Excel の WriteAV の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1278">CVE-2011-1278</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045">MS11-045</a></td>
<td style="border:1px solid black;">Excel の境界外の WriteAV の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1279">CVE-2011-1279</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-046">MS11-046</a></td>
<td style="border:1px solid black;">Ancillary Function ドライバーの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1249">CVE-2011-1249</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">この脆弱性は一般に公開されていました。<br />
<br />
これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-047">MS11-047</a></td>
<td style="border:1px solid black;">VMBus の永続的な DoS の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1872">CVE-2011-1872</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-048">MS11-048</a></td>
<td style="border:1px solid black;">SMB リクエスト解析の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1267">CVE-2011-1267</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049">MS11-049</a></td>
<td style="border:1px solid black;">XML の外部エンティティ解決の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1280">CVE-2011-1280</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">リンク プロパティ処理のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1250">CVE-2011-1250</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">DOM 操作のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1251">CVE-2011-1251</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">toStaticHTML の情報の漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">3</a> – 機能する見込みのない悪用コード</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">ドラッグ アンド ドロップのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1254">CVE-2011-1254</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">Time 要素のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1255">CVE-2011-1255</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">DOM 変更のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1256">CVE-2011-1256</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">レイアウトのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1260">CVE-2011-1260</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">選択オブジェクトのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1261">CVE-2011-1261</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050">MS11-050</a></td>
<td style="border:1px solid black;">HTTP リダイレクトのメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1262">CVE-2011-1262</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">2</a> – 不安定な悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-051">MS11-051</a></td>
<td style="border:1px solid black;">Active Directory の証明書サービスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1264">CVE-2011-1264</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/bulletin/ms11-052">MS11-052</a></td>
<td style="border:1px solid black;">VML のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1266">CVE-2011-1266</a></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/ja-jp/security/cc998259.aspx">1</a> - 安定した悪用コードの可能性</td>
<td style="border:1px solid black;">一時的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
</tbody>
</table>

<p></p>

  
影響を受けるソフトウェアおよびダウンロード先  
--------------------------------------------
  
 
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表はどのように使用しますか?
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報をご確認ください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントがある場合は、利用可能なソフトウェア更新プログラムへのハイパーリンクが張られているほか、そのソフトウェア更新プログラムの深刻度が掲載されています。
  
注: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムをご確認ください。
  
#### Windows オペレーティング システムおよびコンポーネント
  
表 1:

 
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
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-038](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-038)
</td>
<td style="border:1px solid black;">
[MS11-039](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039)
</td>
<td style="border:1px solid black;">
[MS11-041](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-041)
</td>
<td style="border:1px solid black;">
[MS11-042](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042)
</td>
<td style="border:1px solid black;">
[MS11-043](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-043)
</td>
<td style="border:1px solid black;">
[MS11-044](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-044)
</td>
<td style="border:1px solid black;">
[MS11-050](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2371079f-fb20-4fd5-999e-e73f3701818c)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=67a25abd-f43c-4b01-b507-a109b739238f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=492310d3-bbb4-4fff-b5fe-3470c17e7681)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(深刻度 評価なし<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=26ec66af-9727-4423-90da-012ed5b30856)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4203a59a-a809-45db-a234-fef0ff5063f9)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4a49ec89-2a8f-41d9-8f0b-ee57fdf21f50)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2371079f-fb20-4fd5-999e-e73f3701818chttps://www.microsoft.com/download/ja-jp/details.aspx)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=035d5115-54b6-41d3-b9f0-890041ead178)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=af6b7627-c462-45fe-8948-70da37e60659)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e10a4c3c-2ef8-4cfc-ac9b-4d97bfa79ac1)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(深刻度 評価なし<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f6e05fef-ee8c-44ff-a106-d7b8659c8d91)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9fc734db-a177-43d2-a74a-b1fe6ea6f779)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4e4e18a4-97dc-4c5e-a078-8466913aa29e)  
(緊急)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-038](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-038)
</td>
<td style="border:1px solid black;">
[MS11-039](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039)
</td>
<td style="border:1px solid black;">
[MS11-041](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-041)
</td>
<td style="border:1px solid black;">
[MS11-042](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042)
</td>
<td style="border:1px solid black;">
[MS11-043](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-043)
</td>
<td style="border:1px solid black;">
[MS11-044](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-044)
</td>
<td style="border:1px solid black;">
[MS11-050](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7e6ff410-4552-4687-81ab-83d9c91f8af5)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3aa8f1bc-07de-451a-8244-1733247e6f2e)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2719e0fb-3cfd-47b2-906d-3e07b0e3c978)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(深刻度 評価なし<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=638f6dd6-bea0-4356-b23a-45e865a6b28b)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a3bd0012-4a45-4f96-8a51-3ff1f85d1e37)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=19557984-5088-44cc-b5ba-9bab33df8e7e)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9c1a539f-1472-4394-8354-bd549d8332e0)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4aa8c003-0353-4a5b-8aea-c01a103af393)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e9018258-5a72-47a1-8584-3d1aa52317c3)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c962531e-f580-4195-989b-cf348cc96fa7)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(深刻度 評価なし<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ce616970-343d-49f1-994d-4269b9a11448)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=70ece3b4-e5bb-469c-bfef-c8310681f5a7)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c92d94c5-5e8f-45aa-a24a-f4d0efd93732)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c194dd35-b9db-44a5-a252-38f9f803802f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f)  
(KB2478656)  
(緊急)  
[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125)  
(KB2478658)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2e07b5fa-c9fa-495b-9352-c07ce46a7e8b)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=96309c49-4822-4c47-b364-2ba65327cac5)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ea18a916-03cf-4eac-bacc-ceb006491f24)  
(緊急)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(深刻度 評価なし<sup>[2]</sup>)  
[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d)  
(KB2530095)  
(緊急)  
[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628)  
(KB2518864)  
(緊急)  
[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f58ebc9e-00e1-413c-8076-d7a44003d0c7)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80231a27-b37c-4101-a34f-19a26a040836)  
(緊急)
</td>
</tr>
<tr>
<th colspan="8">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-038](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-038)
</td>
<td style="border:1px solid black;">
[MS11-039](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039)
</td>
<td style="border:1px solid black;">
[MS11-041](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-041)
</td>
<td style="border:1px solid black;">
[MS11-042](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042)
</td>
<td style="border:1px solid black;">
[MS11-043](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-043)
</td>
<td style="border:1px solid black;">
[MS11-044](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-044)
</td>
<td style="border:1px solid black;">
[MS11-050](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f33c9e54-c2e5-498d-a798-5bbfe9e4249c)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 1 のみ:[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)  
(KB2478657)  
(緊急)  
Windows Vista Service Pack 1 のみ:[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)  
(KB2478659)  
(緊急)  
Windows Vista Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)  
(KB2478660)  
(緊急)  
Windows Vista Service Pack 1 および Windows Vista Service Pack 2:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=aded8f20-479d-40c1-9560-c0581c6f77a2)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a62edfd8-9016-4bb5-bf48-885498fa0042)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 1 のみ:[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Vista Service Pack 1 のみ:[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Vista Service Pack 1 のみ:[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(緊急)  
Windows Vista Service Pack 1 のみ:[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(緊急)  
Windows Vista Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Vista Service Pack 2 のみ:[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(緊急)  
Windows Vista Service Pack 1 および Windows Vista Service Pack 2:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fea735a8-032b-4fa6-8337-1fa411df0b88)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4cddfc68-eff6-4587-8607-63307d039489)  
(緊急)  
Windows Vista Service Pack 2 のみ:[Internet Explorer 9](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=392316fc-f531-469c-aa60-4ecf061a5354)  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4566528f-62ee-4d78-b3af-131a7cc15e1f)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 のみ [Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)  
(KB2478657)  
(緊急)  
Windows Vista x64 Edition Service Pack 1 のみ [Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)  
(KB2478659)  
(緊急)  
Windows Vista x64 Edition Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)  
(KB2478660)  
(緊急)  
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a519a5d7-bfe3-4e53-99e9-d85f7e34237f)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=962cb40c-680c-4c37-98d4-ca9789ca7270)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cb561ba6-af4d-40cc-947c-923f9cca9a7e)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 のみ [Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Vista x64 Edition Service Pack 1 のみ [Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Vista x64 Edition Service Pack 1 のみ [Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(緊急)  
Windows Vista x64 Edition Service Pack 1 のみ [Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(緊急)  
Windows Vista x64 Edition Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Vista x64 Edition Service Pack 2 のみ:[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(緊急)  
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=49dcb47b-3c79-4f69-ba07-f471304c16e2)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e0a8fbac-2c31-4cf8-9967-6171edabd560)  
(緊急)  
Windows Vista x64 Edition Service Pack 2 のみ:[Internet Explorer 9](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=44b2aa73-c318-47ac-ad87-0d24afd9cdd7)  
(緊急)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-038](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-038)
</td>
<td style="border:1px solid black;">
[MS11-039](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039)
</td>
<td style="border:1px solid black;">
[MS11-041](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-041)
</td>
<td style="border:1px solid black;">
[MS11-042](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042)
</td>
<td style="border:1px solid black;">
[MS11-043](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-043)
</td>
<td style="border:1px solid black;">
[MS11-044](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-044)
</td>
<td style="border:1px solid black;">
[MS11-050](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=0c9614d9-6f61-463d-b1fa-bd5eb2c1a5c5)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems のみ:[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)\*\*  
(KB2478657)  
(緊急)  
Windows Server 2008 for 32-bit Systems のみ:[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)\*\*  
(KB2478659)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)\*\*  
(KB2478660)  
(緊急)  
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)\*\*<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8ebfa067-0236-4454-8605-df1b99742f90)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8ab9679e-6a69-4ca3-9210-7ca4fb1980c2)\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems のみ:[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)\*\*  
(KB2518863)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Server 2008 for 32-bit Systems のみ:[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)\*\*  
(KB2518865)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Server 2008 for 32-bit Systems のみ:[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)\*\*  
(KB2518863)  
(緊急)  
Windows Server 2008 for 32-bit Systems のみ:[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)\*\*  
(KB2518865)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)\*\*  
(KB2518866)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 のみ:[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)\*\*  
(KB2518866)  
(緊急)  
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)\*\*<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b6547ff0-b059-495d-8816-bb094ac11be7)\*\*  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c9650c47-ac52-433d-b409-ce1cfe8d3e87)\*\*  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2 のみ:[Internet Explorer 9](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7f9b1ba2-8247-494b-990c-f62003188c5a)\*\*  
(緊急)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=36698775-0e4e-4980-ae4c-43542de424ca)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems のみ:[Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)\*\*  
(KB2478657)  
(緊急)  
Windows Server 2008 for x64-based Systems のみ:[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)\*\*  
(KB2478659)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)\*\*  
(KB2478660)  
(緊急)  
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2 [Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)\*\*<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd8f3713-b408-4db6-aecd-7eed2176a715)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f1d76b82-9996-4d08-894b-9c16a4b3bb1e)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=22c63fc3-2c5a-4e50-9026-2e04a6e74210)\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems のみ:[Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)\*\*  
(KB2518863)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Server 2008 for x64-based Systems のみ:[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)\*\*  
(KB2518865)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Server 2008 for x64-based Systems のみ:[Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)\*\*  
(KB2518863)  
(緊急)  
Windows Server 2008 for x64-based Systems のみ:[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)\*\*  
(KB2518865)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)\*\*  
(KB2518866)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)\*\*  
(KB2518866)  
(緊急)  
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2 [Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)\*\*<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=feff3364-4bfd-45f5-99da-9192b47ef5d4)\*\*  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7dff9f08-19cb-41dd-a315-84c1dac81510)\*\*  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2 のみ:[Internet Explorer 9](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fdf88a52-c099-44eb-95a0-650129c0e678)\*\*  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3edb613f-5bf0-4e28-9835-4afbb6ef0e01)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems のみ [Microsoft .NET Framework 2.0 Service Pack 1 および Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9)  
(KB2478657)  
(緊急)  
Windows Server 2008 for Itanium-based Systems のみ [Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390)  
(KB2478659)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2 および Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b)  
(KB2478660)  
(緊急)  
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5a61f888-c81e-4b8a-8932-2fe67df4b2ad)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f80c89c6-27ab-4f6a-afad-9c8e92cbbce4)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5bb889de-8ff6-4587-8ef9-ffb13e8d60fd)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems のみ [Microsoft .NET Framework 2.0 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Server 2008 for Itanium-based Systems のみ [Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(深刻度 評価なし<sup>[2]</sup>)  
Windows Server 2008 for Itanium-based Systems のみ [Microsoft .NET Framework 3.5](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4)  
(KB2518863)  
(緊急)  
Windows Server 2008 for Itanium-based Systems のみ [Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8)  
(KB2518865)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2 のみ:[Microsoft .NET Framework 2.0 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2 のみ:[Microsoft .NET Framework 3.5 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d)  
(KB2518866)  
(緊急)  
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d81a9219-da95-4fbf-af7f-898f553b0572)  
(緊急)
</td>
</tr>
<tr>
<th colspan="8">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-038](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-038)
</td>
<td style="border:1px solid black;">
[MS11-039](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039)
</td>
<td style="border:1px solid black;">
[MS11-041](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-041)
</td>
<td style="border:1px solid black;">
[MS11-042](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042)
</td>
<td style="border:1px solid black;">
[MS11-043](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-043)
</td>
<td style="border:1px solid black;">
[MS11-044](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-044)
</td>
<td style="border:1px solid black;">
[MS11-050](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=50ae36ff-2406-48a4-97cc-12782b6d30ac)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6)  
(KB2478661)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1 のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4)  
(KB2478662)  
(緊急)  
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9de1bf5d-6f25-496d-bc44-a32c5e8920fe)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=19a15098-1754-4536-a9ca-ff07d16464b7)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98)  
(KB2518867)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1 のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980)  
(KB2518869)  
(緊急)  
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=91b98f02-a09e-48f1-9f78-a949f7268542)  
(緊急)  
[Internet Explorer 9](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=79f846da-3b17-43c9-9016-a055c2c56975)  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1241f0f8-a5c7-420a-a5b7-b6c3caa9e5e2)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6)  
(KB2478661)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1 のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4)  
(KB2478662)  
(緊急)  
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e7f52b13-5b3d-438c-ae14-86da50c8b67a)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=50d1c677-57aa-4e3f-bdfc-6f01b5d3bfe2)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b449f23e-b3df-46e5-bfe3-98268d20ad54)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98)  
(KB2518867)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1 のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980)  
(KB2518869)  
(緊急)  
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=264107cc-68b4-401c-82f7-de64b535c18d)  
(緊急)  
[Internet Explorer 9](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e87a09f2-b755-48ef-9b85-fc78d0bfce43)  
(緊急)
</td>
</tr>
<tr>
<th colspan="8">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-038](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-038)
</td>
<td style="border:1px solid black;">
[MS11-039](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039)
</td>
<td style="border:1px solid black;">
[MS11-041](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-041)
</td>
<td style="border:1px solid black;">
[MS11-042](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-042)
</td>
<td style="border:1px solid black;">
[MS11-043](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-043)
</td>
<td style="border:1px solid black;">
[MS11-044](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-044)
</td>
<td style="border:1px solid black;">
[MS11-050](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-050)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8181c359-cd79-438a-87be-093b363d0b04)\*\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6)\*  
(KB2478661)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems のみ:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4)\*  
(KB2478662)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)\*<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b77e5be6-d3eb-4e3a-9be2-831578f0447c)\*  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9d66b1e7-dbf9-4475-a973-49fb85557eca)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=06008192-3cac-477b-a913-83eed39d8718)\*  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98)\*  
(KB2518867)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems のみ:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980)\*  
(KB2518869)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 のみ:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)\*<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8b18e6f9-96b8-4dec-bcd0-d71f1bac3eb0)\*\*  
(緊急)  
[Internet Explorer 9](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=81814b15-ebdf-4817-932b-5ea7a37fa6ed)\*\*  
(緊急)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6b63a1eb-445a-4cd3-b357-9a1dd82d7a35)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6)  
(KB2478661)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4)  
(KB2478662)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c)<sup>[1]</sup>
(KB2478663)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c00a33bc-c874-4693-b0f7-5034c5df9424)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3c8455f1-b8a0-4ba2-84a2-043d25ef75c5)  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=93a32bd9-7e67-4ace-8c45-116f91b032f9)  
(緊急)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98)  
(KB2518867)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 のみ:[Microsoft .NET Framework 3.5.1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980)  
(KB2518869)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1:[Microsoft .NET Framework 4.0](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951)<sup>[1]</sup>
(KB2518870)  
(緊急)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ab2406a8-06f7-4f88-9af4-dc136d64bc35)  
(緊急)
</td>
</tr>
</table>

<p></p>

 
Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

MS11-039 に関する注意

<sup>[1]</sup>.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework 4.0 Client Profile は、.NET Framework 4.0 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4.0 および .NET Framework 4.0 Client Profile の両方に影響を与えます。詳細については、MSDN の「[.NET Framework のインストール](https://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS11-044 に関する注意

<sup>[1]</sup>.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework version 4 の再配布可能パッケージは、次の 2 種類のプロファイルで利用可能です:.NET Framework 4.0 および .NET Framework 4.0 Client Profile が影響を受けます。.NET Framework 4.0 Client Profile は、.NET Framework 4.0 のサブセットです。この更新プログラムで解決されている脆弱性は .NET Framework 4.0 および .NET Framework 4.0 Client Profile の両方に影響を与えます。詳細については、MSDN の「[.NET Framework のインストール](https://msdn.microsoft.com/ja-jp/library/5a4x27ek.aspx)」を参照してください。

<sup>[2]</sup> このセキュリティ情報で説明している脆弱性はこのソフトウェアに影響を及ぼさないため、この更新プログラムに対して深刻度は適用されません。しかし、マイクロソフトは、将来的に特定される可能性がある新しい攻撃方法を防ぐ多層防御策として、このソフトウェアをご使用のお客様に、このセキュリティ更新プログラムの適用を推奨します。

表 2

 
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
</tr>
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
[MS11-052](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-052)
</td>
<td style="border:1px solid black;">
[MS11-037](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-037)
</td>
<td style="border:1px solid black;">
[MS11-046](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-046)
</td>
<td style="border:1px solid black;">
[MS11-047](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-047)
</td>
<td style="border:1px solid black;">
[MS11-048](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-048)
</td>
<td style="border:1px solid black;">
[MS11-051](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-051)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6c760c7f-94f1-437f-a645-fd33b50d03f4)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=0b88f9e9-3439-44e5-92c8-66a3c97cb03d)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=03b45ad8-cc6b-473b-8112-bd513ed97f5d)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ce5bc2d7-9438-4bf0-be5e-be9dd00c3286&displaylang=ja)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a1db7736-f3e4-45df-af1d-52746978a0a8)  
重要
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
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c94c0d17-fdbe-41b3-a23d-98f43f907b89)  
(緊急)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ff955dc3-58ca-40ea-b7f1-9ff40c37f997)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ed502ece-737e-44cb-84fd-8a0d1bc321c8)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7b211b02-a005-46a3-ad1d-d4baaeec8289&displaylang=ja)  
重要
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=71497891-41a2-476d-b524-4eb5cecb9639)  
重要
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
<th colspan="7">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-052](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-052)
</td>
<td style="border:1px solid black;">
[MS11-037](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-037)
</td>
<td style="border:1px solid black;">
[MS11-046](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-046)
</td>
<td style="border:1px solid black;">
[MS11-047](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-047)
</td>
<td style="border:1px solid black;">
[MS11-048](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-048)
</td>
<td style="border:1px solid black;">
[MS11-051](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-051)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[注意](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5dafb455-969e-4be9-8735-d4ee0682d22f)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ba3beb80-a921-489e-a6ff-a7b2d665ada6)  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a8038325-0d14-445b-a5d9-ce7ac1fa44b5)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6427ea5d-05d0-4367-805c-9cb305802b3c&displaylang=ja)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c614cb8b-223e-4f84-b94c-f15747760aa5)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ef90d6c1-ea7f-4c32-9c90-0303e04c7436)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e78829d0-8215-4e56-8959-ebd3bc8e9a91)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3bec943e-5758-4439-a947-a8fafd30edec)  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f7bcbad-f647-4fbb-88d4-b19c54db6f00)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e7f65891-32c0-4817-b3b2-d8be73145df9&displaylang=ja)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9a951087-25c5-4f5c-8407-a1585491ae0b)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=62944095-33d6-4131-be32-a79d9ec4d4a9)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1e822515-9f0a-4ef0-bb70-d4889d200f47)  
(警告)  
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=47a0fdc6-7576-4c32-b8fd-cbb05d57599d)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ca8b1d09-9f80-417b-99b1-8f86e86e1f11&displaylang=ja)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 with SP2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dd48b93b-24fa-45a3-91fb-9f9f9418c49f)  
重要
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
<th colspan="7">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-052](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-052)
</td>
<td style="border:1px solid black;">
[MS11-037](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-037)
</td>
<td style="border:1px solid black;">
[MS11-046](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-046)
</td>
<td style="border:1px solid black;">
[MS11-047](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-047)
</td>
<td style="border:1px solid black;">
[MS11-048](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-048)
</td>
<td style="border:1px solid black;">
[MS11-051](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-051)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista Service Pack 1 および Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e541f1bb-c9bf-4dc8-96ec-58a3de5ba7fd)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd059690-52b0-4b37-9fbb-d9906ae46fed)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ebea38a7-1fbe-4141-a529-52d7a7326d6a&displaylang=ja)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=b69e3bda-940b-4524-a724-0af4ae0ec719)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 および Windows Vista Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5f0007c3-8d11-4940-8766-1112e3777aae)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6c7d7162-ef19-49f4-a8fc-5db7415445a4)  
(緊急)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=256bb26f-df9e-4259-881b-e8313a9fafa8)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=54833350-a385-4a31-995a-9ddc38798c21&displaylang=ja)  
重要
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e3a26bc5-1757-4b38-9cae-419c919f4877)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 および Windows Vista x64 Edition Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=fadf6f12-1f09-4d49-93b1-8fce01400b4f)  
重要
</td>
<td style="border:1px solid black;">
対象外
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
[MS11-052](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-052)
</td>
<td style="border:1px solid black;">
[MS11-037](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-037)
</td>
<td style="border:1px solid black;">
[MS11-046](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-046)
</td>
<td style="border:1px solid black;">
[MS11-047](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-047)
</td>
<td style="border:1px solid black;">
[MS11-048](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-048)
</td>
<td style="border:1px solid black;">
[MS11-051](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-051)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[注意](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4446121a-0aab-4fbc-ba74-68d7650e8bca)\*\*  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ed089de4-c9ec-4ac7-a711-5f7cb29c05bc)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6a3bbd67-94db-40b2-8786-cb39a493ec92&displaylang=ja)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e34e4cf9-cdae-4240-8574-950c0be00822)\*  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=8960dd62-7cf7-41cb-97b2-b082bd1750aa)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for 32-bit Systems および Windows Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=46ade106-e0cb-4c71-8230-793a15062823)\*\*  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=01399fc7-dc2b-461e-a1a5-751a3b61bde0)\*\*  
(警告)  
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=dd32b7c6-daa1-47aa-807f-25a678790cf2)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4cb870f3-9878-4075-b8fd-2ee90c8e3bc8&displaylang=ja)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=a3604f05-26b2-451b-9153-0e718158371e)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=24789423-72b7-48d1-bdc1-f0e5174d99bb)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=0abc6908-ac6a-4da3-843a-af6841ccc1db)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for x64-based Systems および Windows Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6141a1c5-ecaf-4553-9d27-dd6e5c4a13fd)\*\*  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=16a8b78a-3979-4cc7-bbe5-6d962aa64336)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e1243011-00e6-49f2-a676-c04cb805d36a&displaylang=ja)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e8a82b44-e1d8-45f8-b8b8-b1f74e1efce0)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 for Itanium-based Systems および Windows Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=057f1356-9c70-4457-a1df-69334fdab467)  
重要
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
[MS11-052](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-052)
</td>
<td style="border:1px solid black;">
[MS11-037](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-037)
</td>
<td style="border:1px solid black;">
[MS11-046](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-046)
</td>
<td style="border:1px solid black;">
[MS11-047](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-047)
</td>
<td style="border:1px solid black;">
[MS11-048](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-048)
</td>
<td style="border:1px solid black;">
[MS11-051](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-051)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=27e767d8-84e3-434f-bb8d-3b2303774ad0)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c3647646-658a-423b-b0cb-bba7613b67e7&displaylang=ja)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=63d8b801-5178-474b-a21e-72a0ce501d3e)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for 32-bit Systems および Windows 7 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cf9e5ecd-68f7-4982-b4ed-be80859b757c)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=747ba56a-0d47-4946-99a4-bae1f11ea748)  
(緊急)
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7996511d-4b8e-49c3-a0fa-4da907a6c947&displaylang=ja)  
重要
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cd7d3cb9-cb60-4b62-b0df-a38fe21802e9)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows 7 for x64-based Systems および Windows 7 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2707650a-604c-4044-acc4-07a30b5640d8)  
重要
</td>
<td style="border:1px solid black;">
対象外
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
[MS11-052](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-052)
</td>
<td style="border:1px solid black;">
[MS11-037](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-037)
</td>
<td style="border:1px solid black;">
[MS11-046](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-046)
</td>
<td style="border:1px solid black;">
[MS11-047](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-047)
</td>
<td style="border:1px solid black;">
[MS11-048](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-048)
</td>
<td style="border:1px solid black;">
[MS11-051](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-051)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[警告](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[注意](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cff7f53d-0fd6-48f8-a9d6-bf19e0a32905)\*\*  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=40354f73-4f4d-4a4a-abac-f8a3d4c3ae5f&displaylang=ja)\*\*  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e67c73ca-d0f9-40c1-8b6e-25b1b13caa3a)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=c9c6c36d-a455-42f7-b7d4-9fb9824c07cb)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f9824310-772d-4e1e-980e-11e2db3ac53e)\*  
重要
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for x64-based Systems および Windows Server 2008 R2 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=1da04414-6210-43ea-8e0a-cf21cf144076)\*\*  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=4dd2c0f4-b29c-4648-a123-83d3ae6a878f)  
(警告)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=22853823-8f63-4258-8991-1ad50e58a0d9&displaylang=ja)  
(注意)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=72d1d6b6-e8bd-492b-b65a-82060beef441)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 for Itanium-based Systems および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=0533d293-e186-4d39-a925-ab3d9ed46290)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
Microsoft Windows Server 2008 および Windows Server 2008 R2 に関する注意

\*Server Core インストールは影響を受けます。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされているかどうかに関わらず、この更新プログラムの深刻度は同じです。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

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
Microsoft Office スイートおよびコンポーネント
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-045](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045)
</td>
<td style="border:1px solid black;">
[MS11-049](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2002 Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=853c0663-94f7-4634-98ad-47ca4b1f7b1e)  
(KB2541003)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f38f183a-9c64-406b-9bf6-807cb2d55e56)  
(KB2541025)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=5b271f87-a279-419f-9437-ded224fa19f1)<sup>[1]</sup>
(KB2541007)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32-bit エディション)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (32 ビット版)](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=baba7ec1-4a5e-4e13-9d0e-9085a39a0554)  
(KB2523021)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (64-bit エディション)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 (64-bit エディション)](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d6e9f422-43b0-4da5-8356-c38482e8eebb)  
(KB2523021)  
重要
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
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-045](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045)
</td>
<td style="border:1px solid black;">
[MS11-049](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d12d0868-4f28-4c0a-ab61-338878064b70)  
(KB2555786)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9e2d348b-c753-4eab-838c-370cd5af5e14)  
(KB2555785)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3c58555c-1eba-42fe-a10f-b30af9031e44)  
(KB2555784)  
重要
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
[Open XML File Format Converter for Mac](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6118d5f5-b6fd-4584-be25-209534772379)  
(KB2555787)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft InfoPath
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-045](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045)
</td>
<td style="border:1px solid black;">
[MS11-049](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049)
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
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2007 Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=88eedb0b-a2cf-4a1b-b1b9-0b2926c25872)  
(KB2510061)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2010 (32-bit エディション)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 (32-bit エディション)](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=90ffe910-bd9c-48aa-8007-2b43e1a99999)  
(KB2510065)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft InfoPath 2010 (64-bit エディション)
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft InfoPath 2010 (64-bit エディション)](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=f3244003-fb63-44d8-bedc-6399c39aacba)  
(KB2510065)  
重要
</td>
</tr>
<tr>
<th colspan="3">
その他の Office ソフトウェア
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-045](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-045)
</td>
<td style="border:1px solid black;">
[MS11-049](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=77c1e7e2-207f-46fd-81f2-43a25eddc010)  
(KB2541015)  
重要
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
[Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=3512a033-871d-49ec-a8d2-1b9c7dec4936)  
(KB2541012)  
重要
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
</table>

<p></p>

 
MS11-045 に関する注意

<sup>[1]</sup> Microsoft Office Excel 2007 Service Pack 2 の場合は、セキュリティ更新プログラム パッケージ KB2541007 に加えて、このセキュリティ情報で説明している脆弱性から保護するために Word/Excel/PowerPoint 2007 ファイル形式用 Microsoft Office 互換機能パック Service Pack 2 (KB2541012) もインストールする必要があります。

MS11-049 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft サーバー ソフトウェア

 
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
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-049](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 for Itanium-based Systems Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 x64 Edition Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 for Itanium-based Systems Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 for Itanium-based Systems Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 Express Edition Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 Express Edition Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Express Edition Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 Express Edition Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 Express Edition Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition with Advanced Services Service Pack 3
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e)  
(KB2494113)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 3](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867)  
(KB2494112)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Express Edition with Advanced Services Service Pack 4
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad)  
(KB2494120)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2005 Express Edition with Advanced Services Service Pack 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57)  
(KB2494123)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server Management Studio Express (SSMSE) 2005
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server Management Studio Express (SSMSE) 2005](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=34c3ba21-b158-4e6d-82ba-831053d41161)  
(KB2546869)  
重要  
QFE 用の更新プログラム:  
対象外
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server Management Studio Express (SSMSE) 2005 x64 Edition
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server Management Studio Express (SSMSE) 2005 x64 Edition](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=34c3ba21-b158-4e6d-82ba-831053d41161)  
(KB2546869)  
重要  
QFE 用の更新プログラム:  
対象外
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 for 32-bit Systems Service Pack 1
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c)<sup>[1]</sup>
(KB2494096)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 for 32-bit Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c)<sup>[1]</sup>
(KB2494100)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2008 for x64-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c)<sup>[1]</sup>
(KB2494096)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 for x64-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c)<sup>[1]</sup>
(KB2494100)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 for Itanium-based Systems Service Pack 1
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c)  
(KB2494096)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 for Itanium-based Systems Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c)  
(KB2494100)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2008 for 32-bit Systems Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276)<sup>[1]</sup>
(KB2494089)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 for 32-bit Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91)<sup>[1]</sup>
(KB2494094)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 for x64-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276)<sup>[1]</sup>
(KB2494089)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 for x64-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91)<sup>[1]</sup>
(KB2494094)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2008 for Itanium-based Systems Service Pack 2
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276)  
(KB2494089)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 for Itanium-based Systems Service Pack 2](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91)  
(KB2494094)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 R2 for 32-bit Systems
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 R2 for 32-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41)<sup>[1]</sup>
(KB2494088)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 R2 for 32-bit Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4)<sup>[1]</sup>
(KB2494086)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2008 R2 for x64-based Systems
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41)<sup>[1]</sup>
(KB2494088)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 R2 for x64-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4)<sup>[1]</sup>
(KB2494086)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2008 R2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
GDR 用の更新プログラム:  
[SQL Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41)  
(KB2494088)  
重要  
QFE 用の更新プログラム:  
[SQL Server 2008 R2 for Itanium-based Systems](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4)  
(KB2494086)  
重要
</td>
</tr>
</table>

<p></p>

 
MS11-049 に関する注意

<sup>[1]</sup> この更新プログラムは対応する Express および Express with Advanced Services Editions にも適用されます。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft 開発者用ツールおよびソフトウェア

 
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
Microsoft Silverlight
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-039](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039)
</td>
<td style="border:1px solid black;">
[MS11-049](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
<td style="border:1px solid black;">
なし
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 4
</td>
<td style="border:1px solid black;">
Mac にインストールされている [Microsoft Silverlight 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8)  
(KB2512827)  
(緊急)  
すべてのリリースの Microsoft Windows クライアントにインストールされている [Microsoft Silverlight 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8)  
(KB2512827)  
(緊急)  
すべてのリリースの Microsoft Windows サーバーにインストールされている [Microsoft Silverlight 4](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8) \*\*  
(KB2512827)  
(緊急)
</td>
<td style="border:1px solid black;">
対象外
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Visual Studio
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-039](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-039)
</td>
<td style="border:1px solid black;">
[MS11-049](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-049)
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
[重要](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2005 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2005 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=e5ce8a9a-e89b-4095-9f21-7e6f307fbf2b)  
(KB2251481)  
重要
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Studio 2008 Service Pack 1
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2008 Service Pack 1](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=cc01bce9-3f38-4590-9c6e-a4048c886d33)  
(KB2251487)  
重要
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio 2010
</td>
<td style="border:1px solid black;">
対象外
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio 2010](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=213b820f-dcba-4895-b339-b50eeb92524d)  
(KB2251489)  
重要
</td>
</tr>
</table>

<p></p>

 
MS11-039 に関する注意

\*\*Server Core インストールは影響を受けません。サポートされているエディションの Windows Server 2008 または Windows Server 2008 R2 では、Server Core インストール オプションを使用してインストールされている場合、この更新プログラムにより解決される脆弱性の影響を受けません。このインストール オプションの詳細については、TechNet の記事 [Server Core](https://www.microsoft.com/japan/windowsserver2008/technologies/server-core.mspx) および [Windows Server 2008 R2 の Server Core](https://www.microsoft.com/japan/windowsserver2008/r2/technologies/server-core.mspx) を参照してください。Windows Server 2008 および Windows Server 2008 R2 の特定のエディションでは、Server Core インストール オプションが使用できないことに注意してください。詳細については、[Server Core インストール オプションの比較](https://www.microsoft.com/japan/windowsserver2008/r2/editions/core-installation.mspx)を参照してください。

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

MS11-049 に関する注意

「影響を受けるソフトウェアおよびダウンロード先」のセクションのその他のソフトウェア カテゴリで、同じセキュリティ情報 ID の下の複数の更新ファイルを確認してください。このセキュリティ情報は、複数のソフトウェアを対象にしています。

#### Microsoft セキュリティ ソフトウェア

 
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
Microsoft Forefront
</th>
</tr>
<tr>
<td style="border:1px solid black;">
セキュリティ情報 ID
</td>
<td style="border:1px solid black;">
[MS11-040](https://technet.microsoft.com/ja-jp/security/bulletin/ms11-040)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
総合的な深刻度
</td>
<td style="border:1px solid black;">
[緊急](https://technet.microsoft.com/ja-jp/security/bulletin/rating)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Forefront Threat Management Gateway 2010 クライアント
</td>
<td style="border:1px solid black;">
[Microsoft Forefront Threat Management Gateway 2010 クライアント](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=d1c85acd-a6df-4634-9cd4-c562ad92097e)  
(緊急)
</td>
</tr>
</table>

<p></p>

 

検出および展開ツールとガイダンス
--------------------------------

 
セキュリティ セントラル

組織のサーバー、デスクトップ、モバイル コンピューターに適用する必要があるソフトウェアおよびセキュリティ更新プログラムを管理してください。詳細については、[TechNet 更新プログラム管理センター](https://technet.microsoft.com/ja-jp/updatemanagement/bb245732)を参照してください。[セキュリティ TechCenter](https://technet.microsoft.com/ja-jp/security/default.aspx) では、マイクロソフト製品に関するセキュリティ情報を提供しています。一般のお客様は[セーフティとセキュリティ センター](https://www.microsoft.com/ja-jp/security/default.aspx)を参照してください。この情報には "最新のセキュリティ更新プログラム" リンクをクリックすることでもアクセスできます。

セキュリティ更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) および [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) から入手できます。セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードすることができます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。

Microsoft Office for Mac をご利用のお客様は、Microsoft AutoUpdate for Mac を使用して、ご利用中のマイクロソフトのソフトウェアを最新に保つことができます。Microsoft AutoUpdate for Mac のご利用の詳細については、「[更新プログラムを自動的にチェックする](https://mac2.microsoft.com/help/office/14/ja-jp/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea)」を参照してください。

さらに、セキュリティ更新プログラムは、[Microsoft Update カタログ](https://go.microsoft.com/fwlink/?linkid=96155)からダウンロードできます。Microsoft Update カタログは、セキュリティ更新プログラム、ドライバーおよび Service Pack などが含まれるコンテンツを検索するカタログで、Windows Update および Microsoft Update でご利用になれます。セキュリティ情報番号 (たとえば「MS07-036」など) を使用して検索することで、バスケットに適用可能な更新プログラムをすべて追加でき (異なる言語の更新プログラムを含む)、選択しているフォルダーにダウンロードできます。「Microsoft Update カタログ」の詳細については、[Microsoft Update Catalog FAQ](https://go.microsoft.com/fwlink/?linkid=97900) (英語情報) を参照してください。

検出および展開のガイダンス

マイクロソフトは、セキュリティ更新プログラムの検出および展開に関して、ガイダンスを提供しています。このガイダンスには、IT プロフェッショナルがセキュリティ更新プログラムの検出および展開のための多様なツールの使用方法を理解するのに役立つ推奨策および情報が含まれています。詳細については、[サポート技術情報 961747](https://support.microsoft.com/kb/961747) を参照してください。

Microsoft Baseline Security Analyzer

Microsoft Baseline Security Analyzer は、管理者によりローカル コンピューターやリモート コンピューターの未適用のセキュリティ更新プログラムの確認、一般的なセキュリティの設定の検査を行うことができます。MBSA の詳細については、[Microsoft Baseline Security Analyzer](https://go.microsoft.com/fwlink/?linkid=21134) を参照してください。

Windows Server Update Services

Windows Server Update Services (WSUS) を使用することにより、管理者は Microsoft Windows 2000 オペレーティング システムおよびそれ以降、Office XP およびそれ以降、Microsoft Windows 2000 およびそれ以降のオペレーティング システムに対する Exchange Server 2003、および SQL Server 2000 用の最新の重要な更新プログラムおよびセキュリティ更新プログラムを迅速に、かつ確実に適用することができます。

Windows Server Update Services でこのセキュリティ更新プログラムを適用する方法については、[Microsoft Windows Server Update Services (WSUS)](https://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) の Web サイトを参照してください。

System Center Configuration Manager 2007

Configuration Manager 2007 のソフトウェアの更新管理は、企業での IT システムへの更新プログラムの配布や管理の複雑なタスクを簡素化します。Configuration Manager 2007 で、IT 管理者はマイクロソフト製品の更新プログラムを、デスクトップ、ラップトップ、サーバー、モバイル デバイスなどのさまざまなデバイスに配布することができます。

Configuration Manager 2007 の自動化された脆弱性評価機能は、更新プログラムの必要性を確認し、推奨されるアクションについて報告します。Configuration Manager 2007 のソフトウェアの更新管理は、世界中の IT 管理者によく知られている実績のある更新の基盤である Microsoft Windows Software Update Services (WSUS) に基づいています。管理者が Configuration Manager 2007 を使用して更新プログラムを展開する方法の詳細については、[ソフトウェアの更新管理](https://www.microsoft.com/japan/systemcenter/configmgr/products/updatemgmt.mspx)を参照してください。Configuration Manager の詳細については、[System Center Configuration Manager](https://www.microsoft.com/japan/systemcenter/configmgr/default.mspx) を参照してください。

Systems Management Server 2003

Microsoft Systems Management Server (SMS) は更新プログラムを管理するための、優れた構成が可能な企業向けソリューションを提供します。SMS により、管理者はセキュリティ更新プログラムを必要とする Windows ベースのシステムを識別し、エンド ユーザーの中断を最小限にして、企業全体にこれらの更新プログラムの適用を管理することができます。

注: System Management Server 2003 は 2010 年 1 月 12 日を持って、メインストリーム サポートを終了しました。製品のライフサイクルの詳細については、[マイクロソフト サポート ライフサイクル](https://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle)を参照してください。現在利用可能な SMS の後継である System Center Configuration Manager 2007 については、前のセクション「System Center Configuration Manager 2007」を参照してください。

セキュリティ更新プログラムを適用するための SMS 2003 の使用方法については、[Scenarios and Procedures for Microsoft Systems Management Server 2003:Software Distribution and Patch Management](https://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=ja) (英語情報) を参照してください。SMS の詳細については、[Systems Management Server](https://technet.microsoft.com/ja-jp/systemcenter/bb545936.aspx) を参照してください。

注 : SMS は Microsoft Baseline Security Analyzer を使用して、セキュリティ情報で提供された更新プログラムの検出と展開について広範なサポートを提供します。これらのツールにより検出されないソフトウェアの更新プログラムもあります。管理者は、特定のシステムに対する更新プログラムを対象とし、これらの場合に SMS のインベントリ機能を使用することができます。この手順の詳細については、[Deploying Software Updates Using the SMS Software Distribution Feature](https://go.microsoft.com/fwlink/?linkid=33341) (英語情報) を参照してください。コンピューターの再起動後、管理者権限を必要とするセキュリティ更新プログラムもあります。管理者は、上位権利での展開ツール ([SMS 2003 Administration Feature Pack](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=ja-nec) で入手可能) を使用して、これらの更新プログラムをインストールできます。

Update Compatibility Evaluator および Application Compatibility Toolkit

更新プログラムはアプリケーションを実行させるために、たびたび同じファイルやレジストリ構成に書き込みをすることがあります。これにより、非互換性が起こったり、セキュリティ更新プログラムの適用時間が長くなったりする可能性があります。[Application Compatibility Toolkit](https://www.microsoft.com/download/ja-jp/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) (英語情報) に含まれている [Update Compatibility Evaluator](https://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) (英語情報) コンポーネントでインストールされているアプリケーションに対し、Windows の更新プログラムのテストおよび確認を効率化することができます。

Application Compatibility Toolkit (ACT) には、お客様の環境に Microsoft Windows Vista、Windows Update、Microsoft Security Update または Windows Internet Explorer の新しいバージョンを適用する前に、アプリケーションの互換性問題を評価し、緩和するために必要なツールやドキュメントが含まれています。

### 関連情報

#### Microsoft Windows 悪意のあるソフトウェアの削除ツール

マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしました。

#### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/en-us/wsus/bb456965.aspx) (英語情報) : Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

#### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

#### セキュリティの計画とコミュニティ

更新プログラムの管理の計画

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

他のセキュリティ更新プログラムの入手先:

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://www.microsoft.com/downloads/ja-jp/results.aspx?pocid=&freetext=%u30bb%u30ad%u30e5%u30ea%u30c6%u30a3%u66f4%u65b0%u30d7%u30ed%u30b0%u30e9%u30e0&displaylang=ja)からもダウンロードできます。「セキュリティ更新プログラム」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の WindowsUpdate で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086) を参照してください。

IT Pro Security Community

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://technet.microsoft.com/ja-jp/security/cc136632.aspx)にアクセスしてください。

#### 謝辞

この問題を連絡し、顧客の保護に協力してくださった下記の方に対し、マイクロソフトは深い[謝意](https://technet.microsoft.com/ja-jp/security/bulletin/policy)を表します。

-   MS11-037 に対する変更について協力してくださった [Google Security Team](https://www.google.com/) の Billy Rios 氏および Eduardo Vela Nava 氏
-   MS11-038 で説明している問題を報告してくださった [Palo Alto Networks](https://www.paloaltonetworks.com/) の Yamata Li 氏
-   MS11-039 で説明している問題を報告してくださった Michael J. Liu 氏
-   MS11-041 で説明している問題を報告してくださった [www.korosoft.net](https://www.korosoft.net/) の Koro 氏
-   MS11-042 で説明している問題を報告してくださった [NGS Software](https://www.ngssoftware.com/) の Laurent Gaffié 氏
-   MS11-044 で説明している問題についてマイクロソフトに協力してくださった Dan Kaminsky 氏
-   MS11-045 で説明している問題を報告してくださった [Fortinet's FortiGuard Labs](https://www.fortiguard.com/) の Bing Liu 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com/) に協力して、MS11-045 で説明している問題を報告してくださった匿名のリサーチャー
-   [VeriSign iDefense Labs](https://labs.idefense.com/) に協力して、MS11-045 で説明している問題を報告してくださった Omair 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com/) に協力して、MS11-045 で説明している問題を報告してくださった匿名のリサーチャー
-   [VeriSign iDefense Labs](https://labs.idefense.com/) に協力して、MS11-045 で説明している問題を報告してくださった [Agarri](https://www.agarri.fr/) の Nicolas Gregoire 氏
-   MS11-045 で説明している問題を報告してくださった Omair 氏
-   MS11-045 で説明している問題を報告してくださった [CERT/CC](https://www.cert.org/) の Will Dormann 氏
-   MS11-046 で説明している問題を報告してくださった Chris S. 氏および [Shadowserver Foundation](https://www.shadowserver.org) の Steven Adair 氏
-   MS11-047 で説明している問題を報告してくださった [Core Security Technologies](https://www.coresecurity.com/) の Nicolas Economou 氏
-   MS11-049 で説明している問題を報告してくださった [Cigital](https://www.cigital.com) の Jesse Ou 氏
-   MS11-050 で説明している問題を報告してくださった [Google Inc.](https://www.google.com/) の Robert Swiecki 氏
-   MS11-050 で説明している問題を報告してくださった [NSFOCUS Security Team](https://www.nsfocus.com/)
-   [Beyond Security の SecuriTeam Secure Disclosure](https://www.beyondsecurity.com/ssd.html) プログラムに協力して、MS11-050 で説明している問題を報告してくださった匿名のリサーチャー
-   MS11-050 で説明している問題を報告してくださった [IBM Rational Application Security](https://blog.watchfire.com/) の Adi Cohen 氏
-   MS11-050 で説明している問題についてマイクロソフトに協力してくださった [Trend Micro](https://www.trendmicro.com/)
-   MS11-050 で説明している問題を報告してくださった [Norman](https://www.norman.com) の Nirmal Singh Bhary 氏
-   [VeriSign iDefense Labs](https://labs.idefense.com/) と協力して、MS11-050 で説明している問題を報告してくださった匿名のリサーチャー
-   [TippingPoint's](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力して、MS11-050 で説明している問題を報告してくださった Damian Put 氏
-   MS11-050 で説明している問題を報告してくださった [salesforce.com](https://www.salesforce.com/) の Product Security チームの Yoel Gluck 氏、Yogesh Badwe 氏、および Varun Badhwar 氏
-   [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力して、MS11-050 で説明している問題を報告してくださった Jose Antonio Vazquez Gonzalez 氏
-   [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力して、MS11-050 で説明している問題を報告してくださった匿名のリサーチャー
-   [TippingPoint](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力して、MS11-050 で説明している問題を報告してくださった Peter Winter-Smith 氏
-   [TippingPoint's](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) と連携して、MS11-050 で取り上げた多層防御についてマイクロソフトに協力してくださった
-   [Harmony Security](https://www.harmonysecurity.com/) の Stephen Fewer 氏
-   MS11-051 で説明している問題を報告してくださった Ruggero Strabla 氏、[Emaze](https://www.emaze.net/)Networks、および [Saipem Security Team](https://www.saipem.com/)
-   [TippingPoint's](https://www.tippingpoint.com/) の [Zero Day Initiative](https://www.zerodayinitiative.com/) に協力して、MS11-052 で説明している問題を報告してくださった匿名のリサーチャー

#### サポート

-   ここに記載されているソフトウェアをテストし、影響を受けるバージョンまたはエディションを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。
-   セキュリティ関連、およびセキュリティ更新プログラムに関するご質問や、ご不明な点などがありましたら、[マイクロソフト セキュリティ情報センター](https://go.microsoft.com/fwlink/?linkid=21131)までご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償でサポートをご提供いたします。利用可能なサポート オプションの詳細については、[マイクロソフト サポート オンライン](https://support.microsoft.com/?ln=ja)を参照してください。
-   その他、製品に関するご質問は、マイクロソフト プロダクト サポートまでご連絡ください。マイクロソフトでは、お問い合わせの内容が弊社製品の不具合が原因である場合、無償またはインシデントの未消費にてサポートをご提供いたします。マイクロソフト プロダクト サポートへの連絡方法の詳細については、[こちら](https://go.microsoft.com/fwlink/?linkid=21155)を参照してください。

#### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

#### 更新履歴

-   V1.0 (2011/06/15):このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2011/06/15):MS11-042 において、Windows 7 for 32-bit Systems Service Pack 1、Windows 7 for x64-based Systems Service Pack 1、Windows Server 2008 R2 for x64-based Systems Service Pack 1、および Windows Server 2008 R2 for Itanium-based Systems Service Pack 1 が「影響を受けるソフトウェアおよびダウンロード先」サブセクションから削除されています。今回の更新は情報のみの変更です。このセキュリティ情報のセキュリティ更新プログラムのファイルおよび検出ロジックへの変更はありません。
-   V2.0 (2011/08/10):MS11-043 を再リリースし、サポートされているすべてのオペレーティング システム用に安定性の問題に対処する更新プログラムを再提供しました。更新済みの場合も MS11-043 を再インストールしてください。また、MS11-049 を再リリースし、Microsoft Visual Studio 2005 Service Pack 1 向けの更新プログラムの検出に対して変更を行い、関連ソフトウェアの検出を追加したことをお知らせします。MS11-049 のセキュリティ更新プログラム ファイルに対する変更はありません。更新済みのお客様は MS11-049 を再インストールする必要はありません。
-   V2.1 (2011/10/31):MS11-039 および MS11-044 を更新し、Windows Server 2008 R2 for x64-based System 上の .NET Framework 4 の Server Core インストールの適用オプションを修正しました。
-   V3.0 (2011/11/09):MS00-037 を再リリースし、すべてのサポートされているエディションの Windows XP および Windows Server 2003 用の更新プログラムを再提供しました。2011 年 6 月 15 日に最初に提供された更新プログラムを既に正常にインストールされているお客様を含め、これらのオペレーティング システムを使用しているお客様は、再提供された更新プログラムをインストールする必要があります。
-   V3.1 (2012/01/25):MS11-049 について、「影響を受けるソフトウェアおよびダウンロード先」のセクションに、この更新プログラムは 32 ビット版および x64-based の SQL Server 2008、SQL Server 2008 R2 Express および Express Advanced Editions にも適用されることを説明した項目を追加しました。

*Built at 2014-04-18T01:50:00Z-07:00*
