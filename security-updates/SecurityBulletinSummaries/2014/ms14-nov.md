---
TOCTitle: 'MS14-NOV'
Title: 2014 年 11 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms14-nov'
ms:contentKeyID: 63302250
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms14-nov(v=Security.10)'
---

2014 年 11 月のマイクロソフト セキュリティ情報の概要
====================================================

公開日: 2014 年 11 月 12 日 | 最終更新日: 2014 年 12 月 22 日

**バージョン:** 2.1

このセキュリティ情報の概要は 2014 年 11 月公開のセキュリティ情報の一覧です。

2014 年 11 月のセキュリティ情報の公開により、2014 年 11 月 7 日に公開した事前通知をこのセキュリティ情報に置き換えました。事前通知サービスの詳細については、「[マイクロソフト セキュリティ情報の事前通知](https://go.microsoft.com/fwlink/?linkid=217213)」を参照してください。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](https://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
<p> </p>  <table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度および脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518106">MS14-064</a></td>
<td style="border:1px solid black;"><strong>Windows OLE の脆弱性により、リモート コードが実行される (3011443)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 2 つの Microsoft Windows オブジェクトのリンクと埋め込みの脆弱性を解決 (OLE). Web ページを Internet Explorer のを使用して表示すると、リモートでコードが実行される可能性があります。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はプログラムのインストール、データの表示、変更または削除、あるいはすべてのユーザー権限を持つ新規アカウントの作成を行う可能性があります。お客様のアカウントを持つように構成ユーザー権利の少ないシステムでの管理者のユーザー権限で実行しているユーザーよりもこの脆弱性による影響が小さい可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;"><strong>Internet Explorer 用の累積的なセキュリティ更新プログラム (3003057)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された 17 件の Internet Explorer に存在する脆弱性を解決します。これらの中で最も深刻な脆弱性が悪用された場合、ユーザーが特別に細工された Web ページを Internet Explorer を使用して表示すると、リモートでコードが実行される可能性があります。この脆弱性が悪用された場合、攻撃者により現在のユーザーと同じ権限が取得される可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518112">MS14-066</a></td>
<td style="border:1px solid black;"><strong>Schannel の脆弱性によりリモートでコードが実行される (2992611)<br />
<br />
</strong>このセキュリティ更新プログラムは、Windows のMicrosoft セキュア チャネル (Schannel) セキュリティ パッケージに存在する、1 件の非公開で報告された脆弱性を解決します。攻撃者が、Windows サーバーに特別に細工されたパケットを送信した場合、この脆弱性により、リモートでコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513100">MS14-067</a></td>
<td style="border:1px solid black;"><strong>Microsoft XML コア サービスの脆弱性により、リモートでコードが実行される (2993958)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された 1 件の Microsoft Windows に存在する脆弱性を解決します。この脆弱性により、ログオンしたユーザーが、Internet Explorer を介して Microsoft XML コア サービス (MSXML) を呼び出すよう設計された特別な細工がされた Web サイトにアクセスした場合に、リモートでコードが実行される可能性があります。 しかし、すべての場合、攻撃者がこのような Web サイトにユーザーを強制的に訪問させる方法はないと考えられます。そのかわり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのリクエスト内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518109">MS14-068</a></td>
<td style="border:1px solid black;"><strong>Kerberos の脆弱性により特権が昇格される (3011780)</strong><br />
<br />
このセキュリティ更新プログラムは、攻撃者が、特権の無いドメイン ユーザー アカウントの特権からドメイン管理者アカウントに特権を昇格する Microsoft Windows Kerberos KDC の非公開で報告された 1 件の脆弱性を解決します。攻撃者は、ドメイン コント ローラーを含むドメイン内のコンピューターを侵害するのにこれらの特権を使用できます。この脆弱性を悪用するには、有効なドメイン資格情報を所有していることが攻撃者にとっての必要条件となります。影響を受けるコンポーネントは、ドメイン資格情報を持つ標準のユーザー アカウントにより、リモートで利用可能です。これはローカル カウントのみを持つユーザーは該当しません。セキュリティ情報の公開時点で、マイクロソフトはこの脆弱性を悪用しようとする限定的な標的型攻撃を確認していました。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518105">MS14-069</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office の脆弱性によりリモートでコードが実行される (3009710)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された 3 件の Microsoft Office に存在する脆弱性を解決します。脆弱性がリモートでコードが実行される場合、影響を受けるエディションの Microsoft Office 2007年では、特別に細工されたファイルを開きます。この脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507675">MS14-070</a></td>
<td style="border:1px solid black;"><strong>TCP/IP の脆弱性により、特権が昇格される (2989935)<br />
<br />
</strong>このセキュリティ更新プログラムは、入出力制御 (IOCTL) の処理中に発生する TCP/IP に存在する 1 件の公開された脆弱性を解決します。この脆弱性により、攻撃者がシステムにログオンし、特別に細工されたアプリケーションを実行した場合に、特権が昇格される可能性があります。攻撃者がこの脆弱性を悪用した場合、別のプロセスのコンテキストで任意のコードが実行される可能性があります。このプロセスが管理者権限で実行されている場合、攻撃者は、プログラムのインストール、データの表示、変更、削除、または、完全なユーザー権限を持つ新しいアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518113">MS14-071</a></td>
<td style="border:1px solid black;"><strong>Windows オーディオ サービスの脆弱性により、特権が昇格される (3005607)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、アプリケーションがマイクロソフトの Windows オーディオ サービスを使用している場合、特権が昇格される可能性があります。この脆弱性だけでは、任意のコードが実行されることはありません。この脆弱性は、リモートでコードが実行される可能性がある別の脆弱性と組み合わせて使用される必要があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518107">MS14-072</a></td>
<td style="border:1px solid black;"><strong>.NET Framework の脆弱性により、特権が昇格される (3005210)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された 1 件の Microsoft .NET Framework の脆弱性を解決します。この脆弱性により、攻撃者が特別な細工を施したデータを、 .NET Remotingを使用している、影響を受けるワークステーションやサーバーに送信した場合、特権が昇格される可能性があります。.NET Remoting は、アプリケーションによって広く使用されているわけではありません。.NET Remoting を使用するように特に設計されたカスタム アプリケーションのみで、システムがこの脆弱性にさらされます。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513105">MS14-073</a></td>
<td style="border:1px solid black;"><strong>Microsoft SharePoint Foundation の脆弱性により、特権が昇格される (3000431)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告されている Microsoft SharePoint Server の脆弱性を解決します。この脆弱性の悪用に成功した認証済みの攻撃者は、現在の SharePoint サイト上のユーザーのコンテキストで任意のスクリプトを実行する可能性があります。Web ベースの攻撃のシナリオでは、攻撃者はこの脆弱性の悪用を意図して特別に細工した Web サイトをホストし、その Web サイトを表示するようにユーザーを誘導する可能性があります。また、攻撃者は侵害された Web サイトおよびユーザーが提供したコンテンツや広告を受け入れるまたはホストする Web サイトを利用する可能性があります。これらの Web サイトには、これらの脆弱性を悪用する可能性のある特別に細工されたコンテンツが含まれている場合があります。しかし、すべての場合において、強制的にユーザーに攻撃者が制御するコンテンツを表示させることはできません。その代わり、ユーザーに操作を行わせることが攻撃者にとっての必要条件となります。一般的には、ユーザーに電子メール メッセージまたはインスタント メッセンジャーのメッセージのリンクをクリックさせ、攻撃者の Web サイトへユーザーを誘導します。または、電子メールで送信した添付ファイルを開かせようとします。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft サーバー ソフトウェア</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518111">MS14-074</a></td>
<td style="border:1px solid black;"><strong>リモート デスクトップ プロトコルの脆弱性により、セキュリティ機能のバイパスが起こる (3003743)<br />
<br />
</strong>このセキュリティ更新プログラムは非公開で報告された 1 件の Microsoft Windows に存在する脆弱性を解決します。この脆弱性により、リモート デスクトップ プロトコル (RDP) が監査イベントを適切にログしない場合、セキュリティ機能のバイパスが起こる可能性があります。RDP は、サポートされている Windows オペレーティング システムでは既定で有効ではありません。RDP が有効となっていないコンピューターは危険にさらされません。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=509986">MS14-076</a></td>
<td style="border:1px solid black;"><strong>インターネット インフォメーション サービス (IIS) の脆弱性により、セキュリティ機能のバイパスが起こる (2982998)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開で報告された、「IP およびドメイン制限」セキュリティ機能のバイパスにつながる Microsoft インターネット インフォメーション サービス (IIS) の脆弱性を解決します。この脆弱性により、制限またはブロックされているドメインのクライアントが制限されている Web リソースにアクセスする可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518108">MS14-077</a></td>
<td style="border:1px solid black;"><strong>Active Directory フェデレーション サービスの脆弱性により、情報漏えいが起こる (3003381)<br />
<br />
</strong>このセキュリティ更新プログラムは非公開で報告された、Active Directory フェデレーション サービス (AD FS) に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーがアプリケーションからログオフした後に、ブラウザーを開いたままにし、攻撃者がそのユーザーがログオフした直後にブラウザーでアプリケーションを再度開くと、情報漏えいが起こる可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
情報漏えい</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=509952">MS14-078</a></td>
<td style="border:1px solid black;"><strong>IME (日本語版) の脆弱性により、特権が昇格される (2992719)<br />
<br />
</strong>このセキュリティ更新プログラムは、非公開に報告された Microsoft Input Method Editor (IME) (日本語版) の 1 件の脆弱性を解決します。この脆弱性は、影響を受けるバージョンの Microsoft IME (日本語版) がインストールされているシステム上のアプリケーション サンドボックス ポリシーに基づいて、サンドボックスを回避する可能性があります。この脆弱性の悪用に成功した攻撃者は、脆弱なアプリケーションのサンドボックスを回避し、ログインしているユーザーの権限で影響を受けるシステムのアクセスを取得する可能性があります。影響を受けるシステムが管理者権限でログインされた場合、攻撃者は、プログラムをインストール、データを変更あるいは削除、または、完全な管理者権限で新しいアカウントを作成する可能性があります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">警告</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518110">MS14-079</a></td>
<td style="border:1px solid black;"><strong>カーネルモード ドライバーの脆弱性により、サービス拒否が起こる (3002885)<br />
<br />
</strong>このセキュリティ更新プログラムは非公開で報告された 1 件の Microsoft Windows に存在する脆弱性を解決します。攻撃者が、特別に細工された TrueType フォントをネットワーク共有に配置して、その後ユーザーが Windows エクスプ ローラーでそこへ移動した場合に、サービス拒否が起こる可能性があります。Web ベースの攻撃のシナリオで、攻撃者はこの脆弱性の悪用を意図した Web ページを含む Web サイトをホストする可能性があります。さらに、影響を受けた Web サイトおよびユーザー提供のコンテンツまたは広告を受け入れる、またはホストする Web サイトには、この脆弱性を悪用する可能性のある特別に細工されたコンテンツが含まれる可能性があります。しかし、すべての場合、攻撃者がこのような Web サイトにユーザーを強制的に訪問させる方法はないと考えられます。そのかわり、通常、ユーザーに攻撃者の Web サイトに接続させる電子メール メッセージまたはインスタント メッセンジャーのメッセージ内のリンクをクリックさせることにより、ユーザーを攻撃者の Web サイトに訪問させることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=21140">警告</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
 
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報の ID 番号、CVE ID の順に示されています。セキュリティ情報で深刻度が「緊急」または「重要」の脆弱性のみ掲載されています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](https://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
<p> </p>  <table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>脆弱性のタイトル</strong></td>
<td style="border:1px solid black;"><strong>CVE の識別番号</strong></td>
<td style="border:1px solid black;"><strong>最新のソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</strong></td>
<td style="border:1px solid black;"><strong>旧バージョンのソフトウェアのリリースに関する Exploitability (悪用可能性) の評価</strong></td>
<td style="border:1px solid black;"><strong>サービス拒否の悪用可能性の評価</strong></td>
<td style="border:1px solid black;"><strong>注意事項</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518106">MS14-064</a></td>
<td style="border:1px solid black;">Windows OLE オートメーション配列リモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6332">CVE-2014-6332</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518106">MS14-064</a></td>
<td style="border:1px solid black;">Windows OLE のリモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6352">CVE-2014-6352</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。<br />
<br />
この脆弱性はマイクロソフト セキュリティ アドバイザリ <a href="https://technet.microsoft.com/library/security/3010060.aspx">3010060</a>で最初に説明されました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4143">CVE-2014-4143</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer クリップボードの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6323">CVE-2014-6323</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6337">CVE-2014-6337</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer ASLR のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6339">CVE-2014-6339</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能バイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer クロス ドメインの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6340">CVE-2014-6340</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6341">CVE-2014-6341</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6342">CVE-2014-6342</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6343">CVE-2014-6343</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6344">CVE-2014-6344</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer クロス ドメインの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6345">CVE-2014-6345</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer クロス ドメインの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6346">CVE-2014-6346</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6347">CVE-2014-6347</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6348">CVE-2014-6348</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6349">CVE-2014-6349</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは特権昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6350">CVE-2014-6350</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは特権昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6351">CVE-2014-6351</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518103">MS14-065</a></td>
<td style="border:1px solid black;">Internet Explorer のメモリ破損の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6353">CVE-2014-6353</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518112">MS14-066</a></td>
<td style="border:1px solid black;">Microsoft Schannel のリモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6321">CVE-2014-6321</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513100">MS14-067</a></td>
<td style="border:1px solid black;">MSXML リモートでコードが実行される脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4118">CVE-2014-4118</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518109">MS14-068</a></td>
<td style="border:1px solid black;">Kerberos のチェックサムの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6324">CVE-2014-6324</a></td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは特権の昇格の脆弱性です。<br />
<br />
マイクロソフトはこの脆弱性を悪用しようとする限定的な攻撃を確認しました。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518105">MS14-069</a></td>
<td style="border:1px solid black;">Microsoft Office の二重削除リモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6333">CVE-2014-6333</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518105">MS14-069</a></td>
<td style="border:1px solid black;">Microsoft Office の不正なインデックス リモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6334">CVE-2014-6334</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518105">MS14-069</a></td>
<td style="border:1px solid black;">Microsoft Office の無効なポインター リモート コード実行の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6335">CVE-2014-6335</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">1- 悪用される可能性が高い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">(なし)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=507675">MS14-070</a></td>
<td style="border:1px solid black;">TCP/IP の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4076">CVE-2014-4076</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは特権昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518113">MS14-071</a></td>
<td style="border:1px solid black;">Windows オーディオ サービスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6322">CVE-2014-6322</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは特権昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518107">MS14-072</a></td>
<td style="border:1px solid black;">TypeFilterLevel の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4149">CVE-2014-4149</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは特権昇格の脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=513105">MS14-073</a></td>
<td style="border:1px solid black;">SharePoint 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4116">CVE-2014-4116</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは特権昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518111">MS14-074</a></td>
<td style="border:1px solid black;">リモート デスクトップ プロトコル (RDP) 監査失敗の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6318">CVE-2014-6318</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能バイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=509986">MS14-076</a></td>
<td style="border:1px solid black;">IIS セキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4078">CVE-2014-4078</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これはセキュリティ機能バイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518108">MS14-077</a></td>
<td style="border:1px solid black;">Active Directory フェデレーション サービスの情報漏えいの脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6331">CVE-2014-6331</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは情報漏えいの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=509952">MS14-078</a></td>
<td style="border:1px solid black;">Microsoft IME (日本語版) 特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-4077">CVE-2014-4077</a></td>
<td style="border:1px solid black;">影響なし</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">対象外</td>
<td style="border:1px solid black;">これは特権昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=518110">MS14-079</a></td>
<td style="border:1px solid black;">Windows カーネルモード ドライバーのサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2014-6317">CVE-2014-6317</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これはサービス拒否の脆弱性です。</td>
</tr>
</tbody>
</table>
  
 
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
**これらの表はどのように使用しますか?**
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3006226)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(警告)  
Internet Explorer 7  
(3003057)  
(警告)  
Internet Explorer 8  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(2989935)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 1.1 Service Pack 1  
(2978114)  
(重要)  
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
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
Windows Server 2003 Service Pack 2  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3006226)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(警告)  
Internet Explorer 7  
(3003057)  
(警告)  
Internet Explorer 8  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(2989935)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
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
Windows Server 2003 x64 Edition Service Pack 2  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3006226)  
(緊急)

</td>
<td style="border:1px solid black;">
Internet Explorer 6  
(3003057)  
(警告)  
Internet Explorer 7  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(2989935)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978124)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
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
Windows Server 2003 with SP2 for Itanium-based Systems  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3006226)  
(緊急)  
Windows Vista Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(緊急)  
Internet Explorer 8  
(3003057)  
(緊急)  
Internet Explorer 9  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2993958)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3011780)  
(深刻度なし)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3006226)  
(緊急)  
Windows Vista x64 Edition Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(緊急)  
Internet Explorer 8  
(3003057)  
(緊急)  
Internet Explorer 9  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2993958)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3011780)  
(深刻度なし)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3006226)  
(緊急)  
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(警告)  
Internet Explorer 8  
(3003057)  
(警告)  
Internet Explorer 9  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 2.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3006226)  
(緊急)  
Windows Server 2008 for x64-based Systems Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(警告)  
Internet Explorer 8  
(3003057)  
(警告)  
Internet Explorer 9  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 2.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3006226)  
(緊急)  
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 2.0 Service Pack 2  
(2978116)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3006226)  
(緊急)  
Windows 7 for 32-bit Systems Service Pack 1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(緊急)  
Internet Explorer 9  
(3003057)  
(緊急)  
Internet Explorer 10  
(3003057)  
(緊急)  
Internet Explorer 11  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2993958)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3011780)  
(深刻度なし)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3006226)  
(緊急)  
Windows 7 for x64-based Systems Service Pack 1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(緊急)  
Internet Explorer 9  
(3003057)  
(緊急)  
Internet Explorer 10  
(3003057)  
(緊急)  
Internet Explorer 11  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2993958)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3011780)  
(深刻度なし)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3006226)  
(緊急)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(警告)  
Internet Explorer 9  
(3003057)  
(警告)  
Internet Explorer 10  
(3003057)  
(警告)  
Internet Explorer 11  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 2.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3006226)  
(緊急)  
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3006226)  
(緊急)  
Windows 8 for 32-bit Systems  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(2993958)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3011780)  
(深刻度なし)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft インターネット インフォメーション サービス 8.0  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3006226)  
(緊急)  
Windows 8 for x64-based Systems  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(2993958)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3011780)  
(深刻度なし)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft インターネット インフォメーション サービス 8.0  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3006226)  
(緊急)  
Windows 8.1 for 32-bit Systems  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(2993958)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3011780)  
(深刻度なし)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft インターネット インフォメーション サービス 8.5  
(2982998)  
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
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3006226)  
(緊急)  
Windows 8.1 for x64-based Systems  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(2993958)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3011780)  
(深刻度なし)<sup>[1]</sup>

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft インターネット インフォメーション サービス 8.5  
(2982998)  
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
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3006226)  
(緊急)  
Windows Server 2012  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft インターネット インフォメーション サービス 8.0  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 2.1  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3006226)  
(緊急)  
Windows Server 2012 R2  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft インターネット インフォメーション サービス 8.5  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 3.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3006226)  
(緊急)  
Windows RT  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT  
(2993958)  
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
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3003743)  
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
Windows RT  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3006226)  
(緊急)  
Windows RT 8.1  
(3010788)  
(重要)

</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3003057)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(2993958)  
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
(3005607)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3003743)  
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
Windows RT 8.1  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="14">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-064**](https://go.microsoft.com/fwlink/?linkid=518106)

</td>
<td style="border:1px solid black;">
[**MS14-065**](https://go.microsoft.com/fwlink/?linkid=518103)

</td>
<td style="border:1px solid black;">
[**MS14-066**](https://go.microsoft.com/fwlink/?linkid=518112)

</td>
<td style="border:1px solid black;">
[**MS14-067**](https://go.microsoft.com/fwlink/?linkid=513100)

</td>
<td style="border:1px solid black;">
[**MS14-068**](https://go.microsoft.com/fwlink/?linkid=518109)

</td>
<td style="border:1px solid black;">
[**MS14-070**](https://go.microsoft.com/fwlink/?linkid=507675)

</td>
<td style="border:1px solid black;">
[**MS14-071**](https://go.microsoft.com/fwlink/?linkid=518113)

</td>
<td style="border:1px solid black;">
[**MS14-072**](https://go.microsoft.com/fwlink/?linkid=518107)

</td>
<td style="border:1px solid black;">
[**MS14-074**](https://go.microsoft.com/fwlink/?linkid=518111)

</td>
<td style="border:1px solid black;">
[**MS14-076**](https://go.microsoft.com/fwlink/?linkid=509986)

</td>
<td style="border:1px solid black;">
[**MS14-077**](https://go.microsoft.com/fwlink/?linkid=518108)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
<td style="border:1px solid black;">
[**MS14-079**](https://go.microsoft.com/fwlink/?linkid=518110)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3006226)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3011780)  
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
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3006226)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール) (2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール) (2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3011780)  
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
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3006226)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5.1  
(2978120)  
(重要)  
Microsoft .NET Framework 4  
(2978125)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978128)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(2991963)  
(警告)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3006226)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール) (2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978121)  
(重要)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(2978127)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール) (3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール) (2982998)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール) (3002885)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3006226)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2992611)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2993958)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3011780)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 3.5  
(2978122)  
(重要)  
Microsoft .NET Framework 4.5.1/4.5.2  
(2978126)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3003743)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(2982998)  
(重要)

</td>
<td style="border:1px solid black;">
Active Directory フェデレーション サービス 3.0  
(3003381)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3002885)  
(警告)

</td>
</tr>
</table>
 
**MS14-064、MS14-065 および MS14-067 に関する注意**

Windows Technical Preview 、および Windows Server Technical Preview は影響を受けます。これらのオペレーティング システムを実行しているお客様は、 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) を通じて利用可能な更新プログラムを適用することを推奨します。

**MS14-068 に関する注意**

Windows Technical Preview 、および Windows Server Technical Preview は影響を受けます。これらのオペレーティング システムを実行しているお客様は、 [Windows Update](https://go.microsoft.com/fwlink/?linkid=21130) を通じて利用可能な更新プログラムを適用することを推奨します。

<sup>[1]</sup>現在、このセキュリティ情報が解決する脆弱性はないため、セキュリティ評価はこのオペレーティング システムには適用されません。 この更新プログラムは追加で、いずれの既知の脆弱性も修正しない[多層防御](https://technet.microsoft.com/en-us/library/security/dn848375.aspx)強化を提供します。

**MS14-078 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。 

 

### Microsoft Office スイートおよびソフトウェアe

 
<p> </p>  <table style="border:1px solid black;">
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
[**MS14-069**](https://go.microsoft.com/fwlink/?linkid=518105)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**警告**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Word 2007 Service Pack 3  
(2899527)  
(重要)

</td>
<td style="border:1px solid black;">
Microsoft Office 2007 IME (日本語版)  
(2889913)  
(警告)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**その他 Microsoft Office ソフトウェア**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-069**](https://go.microsoft.com/fwlink/?linkid=518105)

</td>
<td style="border:1px solid black;">
[**MS14-078**](https://go.microsoft.com/fwlink/?linkid=509952)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer

</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(2899553)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3

</td>
<td style="border:1px solid black;">
Microsoft Office 互換機能パック Service Pack 3  
(2899526)  
(重要)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
**MS14-078 に関する注意**

このセキュリティ情報は、複数のソフトウェアを対象にしています。影響を受けるその他のソフトウェアについては、このセクションの他の表を参照してください。 

 

### Microsoft サーバー ソフトウェア

 
<p> </p>  <table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft SharePoint Server 2010**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS14-073**](https://go.microsoft.com/fwlink/?linkid=513105)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](https://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2

</td>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 Service Pack 2  
(2889838)  
(重要)

</td>
</tr>
</table>
 
 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールについては、「[セキュリティ ツール](https://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。 

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトは、責任ある脆弱性の公開により、顧客の保護に支援くださったセキュリティ コミュニティの人々の貢献を評価します。詳細は、[Acknowledgments](https://technet.microsoft.com/library/security/dn820091.aspx) (英語) を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja):Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](https://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](https://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](https://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](https://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](https://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

**IT Pro Security Community**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](https://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](https://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](https://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](https://support.microsoft.com/contactus/cu_sc_virsec_master)

国ごとのローカルサポート:[Microsoft サポート](https://support.microsoft.com/common/international.aspx)

### 免責

この文書に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2014/11/12): このセキュリティ情報の概要ページを公開しました。
-   V2.0 (2014/11/19): セキュリティ情報を更新し、MS14-068 の定例外での公開と、MS14-066 について、更新プログラム 2992611 が Windows Server 2008 R2 および Windows Server 2012 を実行しているシステムに再提供されたことをお知らせしました。
-   V2.1 (2014/12/22): セキュリティ情報概要は、MS14-076 の影響を受けるソフトウェアの項目に Windows 2012 Server Core インストール、および Windows 2012 R2 Server Core インストールを含めるために更新されました。

*Page generated 2014-12-19 13:20Z-08:00.*
