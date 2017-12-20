---
TOCTitle: 'Blaster ワームへの対策 ‐ Windows XP 編'
Title: 'Blaster ワームへの対策 ‐ Windows XP 編'
ms:assetid: '221c39e2-01bf-42ea-a857-a27633f5c53b'
ms:contentKeyID: 19871735
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362789(v=TechNet.10)'
---

Blaster ワームへの対策 ‐ Windows XP 編
======================================

公開日: 2003年8月13日 | 最終更新日: 2004年1月7日

### Blaster (MSBlaster) ワームに感染した場合の復旧の方法について

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >～非常に危険な亜種が発見されました～</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">2003 年 8 月 18 日 に Blaster ワームの非常に危険な<a href="https://technet.microsoft.com/ja-jp/library/207c8deb-8e10-49e1-a7de-b8e8d8c9be9e(v=TechNet.10)">亜種</a>が確認されました。この新種の Blaster ワームは、マイクロソフトの次の 2 つの脆弱性を使用しています。
<ul>
<li><a href="http://www.microsoft.com/japan/security/bulletins/ms03-007e.mspx">MS03-007: Windows コンポーネントの未チェックのバッファにより Web サーバーが侵害される (815021)</a></li>
<li><a href="http://www.microsoft.com/japan/security/bulletins/ms03-026e.mspx">MS03-026: RPC インターフェイスのバッファ オーバーランによりコードが実行される (823980)</a></li>
</ul>
<br />
  
この対策ページの [手順 5-2. MS03-007 を適用します] の手順を追加しました。
8 月 18 日以前に、すでにこのページをご覧いただき、対策を行われたお客様は、<a href="#step052">手順 5-2. MS03-007 を適用します</a>のみを行ってください。</td>
</tr>
</tbody>
</table>
 

2003 年 8 月 12 日に被害を与え始めた [Blaster ワーム](https://technet.microsoft.com/ja-jp/library/4c748477-4337-4f1a-89c5-000801bad760(v=TechNet.10)) によりコンピュータが異常終了してしまったり、Office が正しく動作しなくなるなどの問題が発生しています。このワームは、[MS03-026](http://www.microsoft.com/japan/security/bulletins/ms03-026e.mspx) として既に修正されているセキュリティ上の弱点を悪用しています。そのため、[Windows Update](http://windowsupdate.microsoft.com) などを利用して、事前に対策を行うことが望まれます。

この資料では、このワームに感染した際の復旧方法についてまとめます。
対処のシナリオとしては、以下のような手順となります。

1.  [ネットワークケーブルを抜きます](#step01)

2.  [インターネット接続ファイアウォールを有効にします](#step02)

3.  [msblast.exe プログラムを停止します](#step03)

4.  [ネットワークケーブルをコンピュータに接続します](#step04)

5.  5-1. [MS03-039 (MS03-026) を適用します](#step051)

    5-2. [MS03-007 を適用します](#step052)

6.  [ワームを駆除します](#step06)

7.  [手順 1.で設定した対策を、元の状態に戻します](#step07)

8.  [コンピュータを安全にお使いいただくために](#step08)

[](#mainsection)[ページのトップへ](#mainsection)

### Windows XP をお使いの方

#### 1. ネットワークケーブルを抜きます

電源投入前に、コンピュータのネットワークケーブルを抜いてください。これにより、インターネットなどのネットワークから攻撃を受けないようにします。
ダイアルアップ接続の場合には、電話回線の接続を切断します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.cable(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">LAN ケーブルを抜きます。コンピュータの裏面には左図のような (メーカーにより若干異なります) LAN ケーブルのポートを示すマークがあります。(ダイヤルアップの場合には電話回線を切断します。)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.plug(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">LAN ケーブルを抜く際は、ツメ (左図赤枠内の部分) をつまんだ状態で抜きます</td>
</tr>
</tbody>
</table>
  
#### 2. インターネット接続ファイアウォールを有効にします
  
Windows XP には、インターネット接続ファイアウォールが搭載されています。この機能を使うことにより、ワームによる攻撃を防ぐことができます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.a04g5_01(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[スタート] メニューから [コントロールパネル] を開き、[ネットワークとインターネット接続] を選択します。
左のような画面が表示されない場合は、次の手順に進んでください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.a04g5_02(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">続いて [ネットワーク接続] をクリックしてください。(下のような画面表示の場合もあります。)
<a href="http://www.microsoft.com/japan/technet/security/alerts/images/netcon_clasic.gif">このような画面表示</a>の場合は、[ネットワーク接続] をダブルクリックしてください。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.a04g5_03(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">使用しているネットワーク接続設定を選択して、[ネットワークタスク] の [この接続の設定を変更する] をクリックします。
<strong>注意 :</strong> 左図では <strong>[LAN または高速インターネット]</strong> 内の「ローカルエリア接続」が選択されていますが、接続方法によって異なりますので、ご注意ください。
ここではインターネットを接続するために使用されているネットワーク接続を選択してください。たとえば、モデムを使ってインターネットに接続されている場合のネットワーク接続は <strong>[ダイヤルアップ]</strong> 内に表示されます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.a04g5_04(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[詳細設定] タブをクリックして、[インターネットからのこのコンピュータへのアクセスを制限したり防いだりして、コンピュータとネットワークを保護する] という項目のチェックをオンにします。</td>
</tr>
</tbody>
</table>
  
#### 3. msblast.exe プログラムを停止します
  
既に Blaster ワームに感染している場合、msblast.exe (**\*1**) とその亜種が動作していますので、このプログラムを停止します。  
停止するプログラムは、最初に発見された Blaster ワームが作成するプログラムです。**亜種やその他のコンピュータ ウイルスへの対策は、**[コンピュータを安全にお使いいただくために](#step08)**をご覧ください。**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.task1(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Ctrl + Shift キーを押しながら Esc キーを押し、タスクマネージャを実行します。
次に [プロセス] タブを表示します。
イメージ名の欄に、&quot;msblast.exe&quot; (<strong>*1</strong>) プログラムがあれば、そのファイル名をマウスでクリックし、[プロセスの終了] ボタンをクリックします。
<strong>注意 :</strong> Blaster ワームが動作していない場合には &quot;msblast.exe&quot; (<strong>*1</strong>) は動作していません。タスクマネージャ右上の [×] ボタンをクリックしタスクマネージャを終了してください。タスクマネージャを終了させた後は、<strong>4. ネットワークケーブルをコンピュータに接続します</strong> へ進んでください。
(<strong>*1</strong>) Blaster ワームは現在いくつかの亜種が報告されています。亜種の場合は msblast.exe と表示されず別の名前になります。
<strong>その亜種</strong><br />
既に Blaster ワームとその亜種に感染している場合、下記のいずれかが動作していますので、”msblast.exe” とこれらのプログラムを停止します。
<ul>
<li>Nstask32.exe</li>
<li>Penis32.exe</li>
<li>Teekids.exe</li>
<li>Winlogin.exe</li>
<li>Win32sockdrv.dl</li>
<li>Yuetyutr.dll</li>
</ul>
<br />
  
詳細はウイルス対策ソフトベンダーの Web サイトをご覧ください。
<ul>
<li><a href="http://www.symantec.com/region/jp/">株式会社シマンテック</a><img src="images/Dd362789.leave-ms(ja-jp,TechNet.10).gif" /></li>
<li><a href="http://www.trendmicro.co.jp/home/">トレンドマイクロ株式会社</a><img src="images/Dd362789.leave-ms(ja-jp,TechNet.10).gif" /></li>
<li><a href="http://www.mcafee.com/jp/default.asp">日本ネットワークアソシエイツ株式会社</a><img src="images/Dd362789.leave-ms(ja-jp,TechNet.10).gif" /></li>
</ul>
<br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.task2(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">タスクマネージャーの警告が表示されます。[はい] をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.task3(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">msblast.exe プログラムが消えたことを確認し、[×] ボタンをクリックしタスクマネージャーを終了します。</td>
</tr>
</tbody>
</table>
  
#### 4. ネットワークケーブルをコンピュータに接続します
  
いよいよセキュリティ修正プログラムの適用を行いますので、ネットワークに接続してください。  
ダイアルアップの場合は、ダイアルアップネットワークを使用してネットワークに接続します。
  
#### 5-1. MS03-039 (MS03-026) を適用します
  
Blaster ワームが悪用する MS03-026 のセキュリティ修正プログラムを入手してインストールします。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">MS03-026 の修正を含む <a href="http://www.microsoft.com/japan/technet/security/bulletin/ms03-039.mspx">MS03-039</a> が公開されました。ここでは MS03-039 のインストール手順を説明しています。</td>
</tr>
</tbody>
</table>

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://download.microsoft.com/download/c/9/3/c93838c2-2d8a-4b43-9a32-4846b5e950dc/windowsxp-kb824146-x86-jpn.exe">MS03-039 セキュリティ修正プログラム</a></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左のリンクをクリックし、MS03-039 のセキュリティ修正プログラムをダウンロードします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.patch03039xp1(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保存をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.patch03039xp2(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップをクリックし、保存をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.patch03039xp3(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">右の画面が表示され修正プログラムがダウンロードされます。
ダウンロード時間の目安は以下のとおりです。
<ul>
<li>ダイヤルアップ 約 3 分程度</li>
<li>ブロードバンド (ADSL、CATV、BFLTES) 約 1 分程度</li>
</ul></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.patch03039xp4(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップ上に修正プログラムが保存されます。
この修正プログラムをダブルクリックし実行します。
<strong>メモ :</strong> 修正プログラムのインストールが完了したら、このファイルは削除しても構いません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.patch03039xp5(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">修正プログラムを実行すると次の画面が表示されます。
[次へ] をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.patch03039xp6(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[同意します] をクリックし、[次へ] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.patch03039xp7(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">右の画面が表示され、修正プログラムがインストールされます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.patch03039xp8(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[完了] をクリックすると再起動が要求されますので再起動を実行します。</td>
</tr>
</tbody>
</table>
  
#### 5-2. MS03-007 を適用します
  
Blaster ワームの亜種が悪用する MS03-007 のセキュリティ修正プログラムを入手してインストールします。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://download.microsoft.com/download/2/6/c/26c5bdb0-9f86-4f07-b4ed-f91648e138f1/q815021_wxp_sp2_x86_jpn.exe">MS03-007 セキュリティ修正プログラム</a></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左のリンクをクリックし、MS03-007 のセキュリティ修正プログラムをダウンロードします。</td>
</tr>
</tbody>
</table>
  
[Microsoft.com Japan](http://www.microsoft.com/japan/) サイト の左側のメニューから \[ダウンロード\] をクリックし、[ダウンロード センター](http://www.microsoft.com/downloads/search.aspx?displaylang=ja)に進みます。 ダウンロードの検索のキーワードに "815021" と入力し検索を実行します。
  
["Windows XP セキュリティ修正プログラム : IIS 経由のリモート攻撃を可能にする ntdll.dll の脆弱性"](http://www.microsoft.com/downloads/details.aspx?familyid=84fc577d-f2d5-47b8-ab98-77ba7501b00b&displaylang=ja) をクリックし、セキュリティ修正プログラムを入手することができます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.815021_xp_2(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保存をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.815021_xp_3(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップをクリックし、保存をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.815021_xp_4(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の画面が表示され修正プログラムがダウンロードされます。
ダウンロード時間の目安は以下のとおりです。
<ul>
<li>ダイヤルアップ 約 3 分程度</li>
<li>ブロードバンド (ADSL、CATV、BFLTES) 約 1 分程度</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.815021_xp_5(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップ上に修正プログラムが保存されます。
この修正プログラムをダブルクリックし実行します。
<strong>メモ :</strong> 修正プログラムのインストールが完了したら、このファイルは削除しても構いません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.815021_xp_6(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">修正プログラムを実行すると次の画面が表示されます。
[次へ] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.815021_xp_7(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[同意します] をクリックし、[次へ] をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.815021_xp_8(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の画面が表示され、修正プログラムがインストールされます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.815021_xp_9(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[完了] をクリックすると再起動が要求されますので再起動を実行します。</td>
</tr>
</tbody>
</table>
  
#### 6. ワームを駆除します
  
ウイルス対策ソフトウェアをお使いのお客様は、最新のウイルス定義ファイルをダウンロードして、スキャンと駆除を行ってください。
  
ウイルス対策ソフトウェアをお持ちでないお客さまは、弊社のダウンロード　センターから　Windows Blaster ワーム駆除ツール (KB833330) Windows XP および Windows 2000 向けを入手することができます。手動で削除するよりも確実で、安全に駆除をすることができます。
  
このツールの詳細については[サポート技術情報 833330](http://support.microsoft.com/default.aspx?scid=kb;ja;833330) をご覧下さい。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Windows Blaster ワーム駆除ツール (KB833330) Windows XP および Windows 2000 向け</td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><strong>注 :</strong> 2005 年 2 月 8 日、マイクロソフトは Blaster ワーム駆除ツールを Microsoft Windows 悪意のあるソフトウェアの削除ツールに置き換えました。 悪意のあるソフトウェアの削除ツールの関連情報を参照するには、<a href="http://support.microsoft.com/kb/890830/">こちら</a>をクリックしてください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.blstrtl01(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保存をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.blstrtl02(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップをクリックし、保存をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.blstrtl03(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップ上に修正プログラムが保存されます。
この修正プログラムをダブルクリックし実行します。
<strong>メモ :</strong> 修正プログラムのインストールが完了したら、このファイルは削除しても構いません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.blstrtl04(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">駆除ツールを実行すると次の画面が表示されます。
[次へ] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.blstrtl05(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[同意します] をクリックし、[次へ] をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.blstrtl06(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の画面が表示され、駆除ツールが実行されます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.blstrtl07(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[完了] をクリックします。
駆除ツールが正しく実行された場合、この画面が表示されます。完了後、再起動を実行する必要はありません。</td>
</tr>
</tbody>
</table>
 

また、ウイルス対策ソフトウェア ベンダー各社により提供されている駆除ツールを入手し、駆除を行うことも可能です。これらツールの使用方法については、ウイルス対策ソフトウェア ベンダー各社の紹介ページをご確認ください。

**注意 :** 修正プログラムインストール後の再起動により msblast.exe が再度起動され、ネットワークに接続できないことがあります。そのときは、手順 3 をご覧になり、再度 msblast.exe のプロセスを停止してください。

-   株式会社シマンテック
    <http://www.symantec.co.jp>

    -   W32.Blaster.Worm 駆除ツール (無償駆除ツール)
        <http://www.symantec.co.jp/region/jp/sarcj/data/w/w32.blaster.worm.removal.tool.html>

    -   W32.Welchia.Worm 駆除ツール (無償駆除ツール)
        <http://www.symantec.co.jp/region/jp/sarcj/data/w/w32.welchia.worm.removal.tool.html>

-   トレンドマイクロ株式会社提供
    <http://www.trendmicro.com/jp/home/personal.htm>

    -   トレンドマイクロ システム クリーナ ver. 3.0（TSC) (無償駆除ツール)
        [http://www.trendmicro.co.jp/esolution/solutionDetail.asp?solutionId=4700](http://www.trendmicro.co.jp/esolution/solutiondetail.asp?solutionid=4700)
        Blaster ワームおよび亜種に対応

-   日本ネットワークアソシエイツ株式会社
    <http://www.nai.com/japan/>

    -   AVERTウイルス駆除ツールStinger（スティンガー）(無償駆除ツール)
        <http://www.nai.com/japan/security/stinger.asp>
        Blaster ワームおよび亜種に対応

-   株式会社ラック
    <http://www.lac.co.jp>

    -   Blaster ワーム 対策ツール
        <http://www.lac.co.jp/business/sns/intelligence/report/download/download.html>

#### 7. インターネット接続ファイアウォールを無効にして、元の設定の状態に戻します

**メモ :** インターネット接続ファイアウォールを有効にしていると、オンラインゲームなどのソフトウェアが動作しなくなる場合があります。しかし、インターネット接続ファイアウォールは、コンピュータを安全に使用していただくのに非常に有効な機能です。インターネット接続ファイアウォールを有効にしたままで、何も問題が発生していない場合は、**インターネット接続ファイアウォールを有効のままでお使いいただくことを、マイクロソフトは強くお勧めします。**

**注意 :** 実際の画面表示と異なる場合があります。お客様の環境にあわせて設定を行ってください。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.a04g5_01(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[スタート] メニューから [コントロールパネル] を開き、[ネットワークとインターネット接続] を選択します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.a04g5_02(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">続いて [ネットワーク接続] をクリックしてください。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.a04g5_03(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">現在のネットワーク接続設定を選択して、[ネットワークタスク] の [この接続の設定を変更する] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.a04g5_05(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[詳細設定] タブをクリックして、[インターネットからのこのコンピュータへのアクセスを制限したり防いだりして、コンピュータとネットワークを保護する] という項目のチェックをオフにします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362789.icf_off(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362789.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の図のような警告が表示されるので、[はい] をクリックします。</td>
</tr>
</tbody>
</table>
  
#### 8. これで対策は終了です
  
できれば、[Windows Update](http://windowsupdate.microsoft.com) を使用して、そのほかのセキュリティ修正プログラムも可能な限りインストールすることをお勧めいたします。
  
また、Windows XP の Service Pack 1 の適用は、可能な限り行ってください。Windows XP Service Pack 1 は、[ここ](http://www.microsoft.com/japan/windowsxp/pro/downloads/servicepacks/sp1/)から入手できます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >コンピュータを安全にお使いいただくために</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Blaster ワームの対策はこれで終了ですが、コンピュータ ウイルスには<a href="https://technet.microsoft.com/ja-jp/library/207c8deb-8e10-49e1-a7de-b8e8d8c9be9e(v=TechNet.10)">亜種</a>と呼ばれるものがあり、お客様のコンピュータが他のウイルスに感染していないとは限りません。
残念ながら、コンピュータ ウイルスは日々作成され、進化しています。感染を防ぐために、ウイルス対策プログラムをご利用いただくことを強くお勧めします。
コンピュータを安全にお使いいただくため、<a href="http://www.microsoft.com/japan/security/protect/">こちら</a>のページをご覧いただき、ぜひ実践してください。</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[ページのトップへ](#mainsection)
