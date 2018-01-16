---
TOCTitle: Windows を標的とした Blaster ワームに関する情報
Title: Windows を標的とした Blaster ワームに関する情報
ms:assetid: 'e1e3b9ea-4267-4955-82b0-2cedd0d6fad4'
ms:contentKeyID: 19870168
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362407(v=MSDN.10)'
---

Windows を標的とした Blaster ワームに関する情報
===============================================

よくある質問と回答
------------------

------------------------------------------------------------------------

### 概要編

Q. Blaster ワームとは何ですか?
------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
Blaster ワームは、[MS03-026](http://www.microsoft.com/japan/technet/security/bulletin/ms03-026.mspx) で警告しているネットワーク上の別のコンピュータの機能を使うための技術である RPC (リモート プロシージャ コール) の脆弱性 (弱点) を悪用するワームです。このワームは ネットワークを通じて MS03-026 の脆弱性の対策が終わっていないコンピュータを探し、脆弱性を悪用して msblast.exe などのワームの実行ファイルをコンピュータに送り込まれ、実行されます。このワームに感染した場合、「Windows の異常終了または再起動」、「ネットワークに接続されている他のコンピュータへの攻撃」が発生します。
</td>
</tr>
</table>


Q. Blaster ワームが利用しているのはどのような弱点ですか?
--------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
Blaster ワームには、既知のセキュリティ上の弱点 [MS03-026「RPC インターフェイスのバッファ オーバーランによりコードが実行される (823980)」](http://www.microsoft.com/japan/technet/security/bulletin/ms03-026.mspx)が使用されています。
</td>
</tr>
</table>
 

Q. 私のコンピュータに感染するのでしょうか?
------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
Blaster ワームは、Windows 製品をインストールしているコンピュータに感染する恐れがあります。  
製品の詳細については、[こちら](https://technet.microsoft.com/4c748477-4337-4f1a-89c5-000801bad760)をご覧ください。
</td>
</tr>
</table>
 

Q. RPC とは何ですか?
--------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
PRC (リモート プロシージャ コール) は、プログラムがネットワークの別のコンピュータ上のプログラムからのサービスを要求するために使用することができるプロトコルです。RPC を使用するプログラムは、通信をサポートするネットワーク プロトコルを認識する必要がないため、RPC により、相互運用性が得られます。RPCでは、要求を行うプログラムは、クライアントで、サービスを提供しているプログラムがサーバーとなります。
</td>
</tr>
</table>
 

Q. このワームにより、メールや IRC などで個人情報が外部に送られたりしますか?
---------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
いいえ。このワームにより個人情報が外部に流出されることはありません。
</td>
</tr>
</table>
 

Q. 感染したことを確認するには、どのようにすればよいのですか?
------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
感染の確認方法は本[ワームへの対策](https://technet.microsoft.com/4c748477-4337-4f1a-89c5-000801bad760)の「[Step 3: Blaster ワームの感染の確認](https://technet.microsoft.com/4c748477-4337-4f1a-89c5-000801bad760)」をご覧ください。  
</td>
</tr>
</table>
 

Q. メールでこのワームが送られてくることはありますか?
----------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
いいえ。メールでこのワームが送られてくることはありません。
</td>
</tr>
</table>
 

Q. この "MS03-026 の脆弱性" とは何ですか?
-----------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
ある特定の状況下において、Windows RPC サービスで、メッセージの入力チェックが適切に行われないために発生する脆弱性です。この特定のエラーにより、RPC が有効なポートをリッスンする、基本となる Distributed Component Object Model (DCOM) インターフェイスに影響が及びます。攻撃者が不正な RPC メッセージを送信した場合、コンピュータ上の RPC サービスが異常終了し、攻撃者の任意のコードが実行される可能性があります。
  
攻撃者はこの脆弱性を悪用し、リモート コンピュータを完全に制御する可能性があります。これにより、攻撃者はたとえば Web ページの変更、ハード ディスクの再フォーマット、新規のユーザーをローカル管理者グループに追加するなど、そのサーバー上で任意の操作を実行する可能性があります。

</td>
</tr>
</table>
 

Q. マイクロソフトはセキュリティ問題について何か告知活動をしていたのですか?
--------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
はい。マイクロソフトは 7 月に入り、いくつかの緊急対応をご検討いただきたいセキュリティ修正プログラムを公開させていただきました。お客様に緊急レベルの修正プログラムの意味と、適用を行っていただくお願いのために以下の情報を 7 月に公開し、マイクロソフト製品の登録ユーザーおよび各種ニュースレター購読ユーザーに、このことをお知らせするメールを配信いたしました。

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><ul>
<li><a href="http://www.microsoft.com/japan/security/">緊急レベルのセキュリティ修正プログラムについて</a></li>
</ul></td>
</tr>
</tbody>
</table>
 

</td>
</tr>
</table>
 

Q. ウイルスと脆弱性の違いは何ですか?マイクロソフトがウイルスを作っているのですか?
---------------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
ウイルスは、マイクロソフトで作成したものではありません。 本ウイルス (ワーム) は、MS03-026 の Windows の脆弱性を悪用して、悪意を持つユーザーがインターネットに配布したものです。
  
コンピュータ ウイルス、脆弱性の詳細については[こちらのページ](http://www.microsoft.com/japan/security/bulletins/security_rating.mspx)をご覧ください。
  
 

</td>
</tr>
</table>
 

Q. Windows NT Workstation 4.0 は感染しますか?
---------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
はい。感染の可能性があります。
</td>
</tr>
</table>
 

Q. Windows が突然終了してしまいますがなぜでしょうか?
----------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
本ウイルスは、RPC と呼ばれる機能に対して不正な情報を送信することで、コンピューターに侵入します。侵入に失敗した場合に RPC が異常終了することがあります。Windows XP は、RPC が異常終了した場合、復旧のために 30 秒後に再起動することをユーザーに通知し、自動的に再起動します。
</td>
</tr>
</table>
 

### 対策編

Q. 修正プログラムを適用せずにこのワームから身を守るにはどうしますか?
--------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
[こちら](https://technet.microsoft.com/4c748477-4337-4f1a-89c5-000801bad760)の回避策を実行してください。
</td>
</tr>
</table>
 

Q. 回避策は Windows XP と Windows 2000 では異なるのでしょうか?
--------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
はい。Windows 2000 では「インターネット接続ファイアウォール」の機能はありません。このため、回避策の 1 つである「インターネット接続ファイアウォールを使用する」は適用できません。
</td>
</tr>
</table>
 

Q. 実際に感染した場合、どのような手順で復旧するのでしょうか?
------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
[本ワームへの対策](https://technet.microsoft.com/4c748477-4337-4f1a-89c5-000801bad760)の「[Step 4: Blaster ワームの駆除](https://technet.microsoft.com/4c748477-4337-4f1a-89c5-000801bad760)」をご覧ください。
</td>
</tr>
</table>
 

Q. Windows NT Workstation 4.0 はどのように対策すればよいか?
-----------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
Windows NT Server 4.0 用の [MS03-026](http://www.microsoft.com/japan/technet/security/bulletin/ms03-026.mspx) の修正プログラムを適用することができます。しかしながら、Windows NT Workstation 4.0 は、すでにサポートを終了しております。できるかぎり早期にサポート対象のオペレーティング システムへのアップグレードをお願いします。
</td>
</tr>
</table>
 

Q. 修正プログラムを社内のコンピュータに配布する方法を教えてください。
---------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">セキュリティ修正プログラムは、配布の範囲が社内である場合自由に配布可能です。配布の方法は数多くあります。
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li>ファイル共有を利用する方法<br />
ファイルサーバー上に、修正プログラムを配置し、各ユーザーに実行していただくことで、配布を行います。</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><ul>
<li>グループポリシー または、ログオンスクリプトを利用する方法<br />
Active Directory 等による、修正プログラムの配布</li>
</ul></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li><a href="http://www.microsoft.com/japan/technet/windowsserver/wsus/20/default.mspx">Microsoft Software Update Services</a> による配布</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><ul>
<li><a href="http://www.microsoft.com/japan/smserver/">Microsoft Systems Management Server</a> による配布</li>
</ul></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

</td>
</tr>
</table>
 

Q. 社内の影響を受けるコンピュータを検出するツールはありますか?
--------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
現在のところ提供されていません。
</td>
</tr>
</table>
 

Q. ISA Server でこのウイルスから保護することはできますか?
---------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
はい。ISA Server によって、Blaster ワームの外部からの攻撃を防ぐことができます。  
設定方法など詳細については、次のサイトをご参照ください。

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><ul>
<li><a href="https://technet.microsoft.com/63536aad-57c3-497f-abb5-d975b12bfbe7">ISA Server で Blaster トラフィックを防ぐ方法</a></li>
</ul></td>
</tr>
</tbody>
</table>
 

</td>
</tr>
</table>
 

Q. MS03-026 では Blaster 対策は不十分ですか?
--------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
いいえ。Blaster ワームの対策としては MS03-026 を適用することで問題ありません。  
しかしながら、Blaster ワームの亜種が発生した場合に MS03-039 の脆弱性を悪用される危険があります。そのため、MS03-026 を含む MS03-039 の適用を強く推奨いたします。
</td>
</tr>
</table>
 

[<img src="images/dd362407.arrow_px_up(ja-jp,TechNet.10).gif" alt="ページのトップへ" width="7" height="9" />](#top) [ページのトップへ](#top)
