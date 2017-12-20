---
TOCTitle: 'MS15-JAN'
Title: 2015 年 1 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms15-jan'
ms:contentKeyID: 63893882
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms15-jan(v=Security.10)'
---

2015 年 1 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日:2015 年 1 月 14 日

**バージョン:** 1.0

このセキュリティ情報の概要は 2015 年 1 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定する手助けとなる情報も提供します。「関連情報」の欄を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次のセクション「影響を受けるソフトウェア」を参照してください。

 
<p> </p>  
<table style="border:1px solid black;">
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522536">MS15-001</a></td>
<td style="border:1px solid black;"><strong>Windows アプリケーションの互換性のキャッシュの脆弱性により、特権が昇格される (3023266)<br />
<br />
</strong>このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する一般で公開された脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。認証された攻撃者がこの脆弱性を悪用した場合、Microsoft Windows アプリケーションの互換性コンポーネントでキャッシュの変更中に実行される既存のアクセス許可の確認がバイパスされ、昇格された特権で任意のコードが実行される可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522537">MS15-002</a></td>
<td style="border:1px solid black;"><strong>Windows Telnet サービスの脆弱性により、リモートでコードが実行される (3020393)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、影響を受ける Windows サーバーに対して攻撃者が特別に細工されたパケットを送信した場合に、リモートでコードが実行される可能性があります。既定では、Telnet は、影響を受けるオペレーティング システムのリリースにはインストールされません。このサービスを手動でインストールしているユーザーのみが、この脆弱性の影響を受ける場合があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522528">MS15-003</a></td>
<td style="border:1px solid black;"><strong>Windows User Profile Service の脆弱性により、特権が昇格される (3021674)</strong><br />
<br />
このセキュリティ更新プログラムは 1 件の Microsoft Windows に存在する、一般に公表された脆弱性を解決します。この脆弱性により、攻撃者がコンピューターにログオンし、特別な細工がされたアプリケーションを実行した場合、特権が昇格される可能性があります。この脆弱性が悪用された場合、ローカルの攻撃者が昇格された特権を使用して、標的となるコンピューターで任意のコードを実行する可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522521">MS15-004</a></td>
<td style="border:1px solid black;"><strong>Windows コンポーネントの脆弱性により、特権が昇格される (3025421)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工されたアプリケーションを実行するように攻撃者が誘導した場合、特権の昇格が起こる可能性があります。攻撃者によりこの脆弱性が悪用された場合、攻撃者が現在のユーザーと同じユーザー権限を取得する可能性があります。現在のユーザーが管理者ユーザー権限でログオンしている場合、攻撃者はプログラムのインストール、データの表示、変更または削除、あるいはすべてのユーザー権限を持つ新規アカウントの作成を行う可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者ユーザー権限で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522531">MS15-005</a></td>
<td style="border:1px solid black;"><strong>Network Location Awareness サービスの脆弱性により、セキュリティ機能のバイパスが起こる (3022777)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃対象者と同じネットワーク上にいる攻撃者が、攻撃対象者によって開始された DNS および LDAP トラフィックへの応答を偽装することで、特定のサービスのファイアウォール ポリシーまたは構成が意図せず緩和され、セキュリティ機能がバイパスされる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522535">MS15-006</a></td>
<td style="border:1px solid black;"><strong>Windows エラー報告の脆弱性により、セキュリティ機能のバイパスが起こる (3004365)</strong><br />
<br />
このセキュリティ更新プログラムは、非公開で報告された 1 件の Windows エラー報告 (WER) の脆弱性を解決します。この脆弱性が攻撃者によって悪用された場合、セキュリティ機能がバイパスされる可能性があります。この脆弱性を悪用した攻撃者は、実行中のプロセスのメモリにアクセスできるようになる可能性があります。コンピューターでのユーザー権限が低い設定のアカウントを持つユーザーは、管理者特権で実行しているユーザーよりもこの脆弱性による影響が少ないと考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
セキュリティ機能のバイパス</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519134">MS15-007</a></td>
<td style="border:1px solid black;"><strong>ネットワーク ポリシー サーバーの RADIUS 実装の脆弱性により、サービス拒否が起こる (3014029)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、攻撃者がインターネット認証サービス (IAS) またはネットワーク ポリシー サーバー (NPS) に対して特別に細工されたユーザー名文字列を送信することで、IAS または NPS でサービス拒否が発生する可能性があります。サービス拒否の脆弱性が悪用されても、攻撃者によりコードが実行されたり、ユーザーの権限が昇格されることはないと思われますが、IAS または NPS で RADIUS 認証が実行できなくなる可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
サービス拒否</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522533">MS15-008</a></td>
<td style="border:1px solid black;"><strong>Windows カーネルモード ドライバーの脆弱性により、特権が昇格される (3019215)</strong><br />
<br />
このセキュリティ更新プログラムは非公開で報告された Microsoft Windows に存在する 1 件の脆弱性を解決します。この脆弱性により、影響を受けるシステムで攻撃者が特別に細工されたアプリケーションを実行した場合、特権の昇格が起こる可能性があります。この脆弱性が悪用されるには、有効な資格情報を所有し、ローカルでログオンできることが攻撃者にとっての必要条件となります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a><br />
特権の昇格</td>
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
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259) を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。
  
<p> </p>  
<table style="width:100%;">
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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522536">MS15-001</a></td>
<td style="border:1px solid black;">Microsoft アプリケーションの互換性インフラストラクチャの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0002">CVE-2015-0002</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">この脆弱性は一般で公表されていました。<br />
<br />
これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522537">MS15-002</a></td>
<td style="border:1px solid black;">Windows Telnet サービスのバッファ オーバーフローの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0014">CVE-2015-0014</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これはリモートでコードが実行される脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522528">MS15-003</a></td>
<td style="border:1px solid black;">Microsoft User Profile Service の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0004">CVE-2015-0004</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">この脆弱性は一般で公表されていました。<br />
<br />
これは、特権の昇格の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522521">MS15-004</a></td>
<td style="border:1px solid black;">ディレクトリ トラバーサルの特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0016">CVE-2015-0016</a></td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">0- 悪用の事実を確認済み</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。<br />
<br />
この脆弱性は、限定的な標的型攻撃でサンドボックスのバイパスとして悪用されています。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522531">MS15-005</a></td>
<td style="border:1px solid black;">NLA セキュリティ機能のバイパスの脆弱性 - CVE-2015-0006</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0006">CVE-2015-0006</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522535">MS15-006</a></td>
<td style="border:1px solid black;">Windows エラー報告のセキュリティ機能のバイパスの脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0001">CVE-2015-0001</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これはセキュリティ機能のバイパスの脆弱性です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=519134">MS15-007</a></td>
<td style="border:1px solid black;">ネットワーク ポリシー サーバーの RADIUS 実装のサービス拒否の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0015">CVE-2015-0015</a></td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">3- 悪用される可能性は非常に低い</td>
<td style="border:1px solid black;">永続的</td>
<td style="border:1px solid black;">これは、サービス拒否の脆弱性です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=522533">MS15-008</a></td>
<td style="border:1px solid black;">WebDAV の特権の昇格の脆弱性</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-0011">CVE-2015-0011</a></td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">2 - 悪用される可能性は低い</td>
<td style="border:1px solid black;">該当なし</td>
<td style="border:1px solid black;">これは、特権の昇格の脆弱性です。</td>
</tr>
</tbody>
</table>
  
 
  
影響を受けるソフトウェア  
------------------------
  
<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。
  
これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。
  
**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合があります。上記の各セキュリティ情報の番号の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。
  
### Windows オペレーティング システムおよびコンポーネント

 
<p> </p>  
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows Server 2003**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems<sup>[1]</sup>
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2003 with SP2 for Itanium-based Systems  
(3019215)  
(重要)

</td>
</tr>
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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2 (リモート デスクトップ クライアント 7.0 をインストール済み)  
(3023299)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2 (リモート デスクトップ クライアント 7.0 をインストール済み)  
(3023299)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3019215)  
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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3019978)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1 (リモート デスクトップ クライアント 8.0 をインストール済み)  
(3020387)  
(重要)  
Windows 7 for 32-bit Systems Service Pack 1 (リモート デスクトップ クライアント 8.1 をインストール済み)  
(3020388)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 7 for 32-bit Systems Service Pack 1  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3019978)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1 (リモート デスクトップ クライアント 8.0 をインストール済み)  
(3020387)  
(重要)  
Windows 7 for x64-based Systems Service Pack 1 (リモート デスクトップ クライアント 8.1 をインストール済み)  
(3020388)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3019215)  
(重要)

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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3019978)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (リモート デスクトップ クライアント 8.0 をインストール済み)  
(3020387)  
(重要)  
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (リモート デスクトップ クライアント 8.1 をインストール済み)  
(3020388)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows 8 および Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 8 for 32-bit Systems  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3022777) )  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 8 for x64-based Systems  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3022777) )  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3022777) )  
(重要)

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
(3019215)  
(重要)

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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3014029)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="9">
**Windows RT および Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT

</td>
<td style="border:1px solid black;">
Windows RT  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows RT  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows RT  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows RT  
(3019215)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3019215)  
(重要)

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
[**MS15-001**](http://go.microsoft.com/fwlink/?linkid=522536)

</td>
<td style="border:1px solid black;">
[**MS15-002**](http://go.microsoft.com/fwlink/?linkid=522537)

</td>
<td style="border:1px solid black;">
[**MS15-003**](http://go.microsoft.com/fwlink/?linkid=522528)

</td>
<td style="border:1px solid black;">
[**MS15-004**](http://go.microsoft.com/fwlink/?linkid=522521)

</td>
<td style="border:1px solid black;">
[**MS15-005**](http://go.microsoft.com/fwlink/?linkid=522531)

</td>
<td style="border:1px solid black;">
[**MS15-006**](http://go.microsoft.com/fwlink/?linkid=522535)

</td>
<td style="border:1px solid black;">
[**MS15-007**](http://go.microsoft.com/fwlink/?linkid=519134)

</td>
<td style="border:1px solid black;">
[**MS15-008**](http://go.microsoft.com/fwlink/?linkid=522533)

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
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core インストール)  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3023266)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3020393)  
(緊急)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3021674)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3019978)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3022777)  
(重要)

</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core インストール)  
(3004365)  
(重要)

</td>
<td style="border:1px solid black;">
該当なし

</td>
<td style="border:1px solid black;">
該当なし

</td>
</tr>
</table>
 
**MS15-005 に関する注意**    
<sup>[1]</sup>Windows Server 2003 は影響を受けますが、そのための更新プログラムは公開されていません。詳細に関してはセキュリティ情報をご覧ください。

 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび確認を効率化する手助けをします。

利用可能なこれらのツールおよび他のツールの詳細については、「[セキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、[謝辞](https://technet.microsoft.com/ja-jp/library/security/dn820091.aspx)を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/kb/894199/ja): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/windowsserver/bb332157.aspx) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=107349)からダウンロードできます。「security\_patch」のキーワード探索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージをマイクロソフト ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/kb/913086/ja) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うためには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。そのほかのバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[マイクロソフト サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナルのためのセキュリティ ソリューション:[TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ:[ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/contactus/cu_sc_virsec_master?ln=ja)

国ごとのローカル サポート:[その他の地域のサポート](http://support.microsoft.com/common/international.aspx?ln=ja)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation 及びその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。さらに、Microsoft Corporation 及びその関連会社は、本文書に含まれている情報の使用及び使用結果につき、正確性、真実性等、いかなる表明・保証も行いません。Microsoft Corporation、その関連会社及びこれらの権限ある代理人による口頭または書面による一切の情報提供またはアドバイスは、保証を意味するものではなく、かつ上記免責条項の範囲を狭めるものではありません。Microsoft Corporation、その関連会社及びこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含む全ての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2015/01/14):このセキュリティ情報の概要ページを公開しました。

*Page generated 2015-01-08 14:01Z-08:00.*
