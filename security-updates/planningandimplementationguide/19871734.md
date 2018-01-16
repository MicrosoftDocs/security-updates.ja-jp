---
TOCTitle: 'Blaster ワームへの対策 ‐ Windows 2000/Windows NT 4.0 編'
Title: 'Blaster ワームへの対策 ‐ Windows 2000/Windows NT 4.0 編'
ms:assetid: 'df816f36-1e9e-4775-8526-c1d94fd61e6c'
ms:contentKeyID: 19871734
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362788(v=TechNet.10)'
---

Blaster ワームへの対策 ‐ Windows 2000/Windows NT 4.0 編
=======================================================

公開日: 2003年8月13日 | 最終更新日: 2004年1月8日

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
  
この対策ページの手順 5-2. MS03-007 を適用しますの手順を追加しました。

8 月 18 日以前に、すでにこのページをご覧いただき、対策を行われたお客様は、<a href="#step052">手順 5-2. MS03-007 を適用します</a>のみを行ってください。</td>
</tr>
</tbody>
</table>
 

2003 年 8 月 12 日に被害を与え始めた [Blaster ワーム](https://technet.microsoft.com/ja-jp/library/4c748477-4337-4f1a-89c5-000801bad760(v=TechNet.10)) によりコンピュータが異常終了してしまったり、Office が正しく動作しなくなるなどの問題が発生しています。このワームは、[MS03-026](http://www.microsoft.com/japan/security/bulletins/ms03-026e.mspx) として既に修正されているセキュリティ上の弱点を悪用しています。そのため、[Windows Update](http://windowsupdate.microsoft.com) などを利用して、事前に対策を行うことが望まれます。

この資料では、このワームに感染した際の復旧方法についてまとめます。
対処のシナリオとしては、以下のような手順となります。

1.  [ネットワークケーブルを抜きます](#step01)

2.  [分散 COM (DCOM) を一時的に無効にします](#step02)

3.  [msblast.exe プログラムを停止します](#step03)

4.  [ネットワークケーブルをコンピュータに接続します](#step04)

5.  5-1. [MS03-039 (MS03-026) を適用します](#step051)

    5-2. [MS03-007 を適用します](#step052)

6.  [ワームを駆除します](#step06)

7.  [手順 1.で設定した対策を、元の状態に戻します](#step07)

8.  [コンピュータを安全にお使いいただくために](#step08)

[](#mainsection)[ページのトップへ](#mainsection)

### Windows 2000/Windows NT 4.0 をお使いの方

#### 1. ネットワークケーブルを抜きます

電源投入前に、コンピュータのネットワークケーブルを抜いてください。これにより、インターネットなどのネットワークから攻撃を受けないようにします。
ダイアルアップ接続の場合には、電話回線の接続を切断します。

<p> <p/> 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.cable(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">LAN ケーブルを抜きます。コンピュータの裏面には左図のような (メーカーにより若干異なります) LAN ケーブルのポートを示すマークがあります。(ダイヤルアップの場合には電話回線を切断します。)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.plug(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">LAN ケーブルを抜く際は、ツメ (左図赤枠内の部分) をつまんだ状態で抜きます</td>
</tr>
</tbody>
</table>
  
#### 2. 分散 COM (DCOM) を一時的に無効にします
  
Blaster ワームに悪用されてしまうセキュリティ上の弱点は、RPC を経由して使用される DCOM に問題があるために発生します。そのため、DCOM を無効にすることで、この弱点そのものを無効にすることができます。
  
**注意 :** Windows 2000 で DCOM を無効にするには Windows 2000 SP 3 以上の必要があります。
  
-   [Windows の DCOM サポートを無効にする方法](http://support.microsoft.com/kb/825750)

 <p> <p/> 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.start_w2k(ja-jp,TechNet.10).jpg" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">スタートメニューから [ファイル名を指定して実行] を選びます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.dcomcnfg(ja-jp,TechNet.10).jpg" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">表示されたウインドウの名前テキストボックスに、dcomcnfg と入力し、[OK] ボタンをクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.dcomp_off(ja-jp,TechNet.10).jpg" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[既定のプロパティ] タブを表示し、[このコンピュータ上で分散 COM を有効にする] チェック ボックスがオフの状態で、[OK] ボタンをクリックします。</td>
</tr>
</tbody>
</table>
  
#### 3. msblast.exe プログラムを停止します
  
既に Blaster ワームに感染している場合、msblast.exe (**\*1**) とその亜種が動作していますので、このプログラムを停止します。  
停止するプログラムは、最初に発見された Blaster ワームが作成するプログラムです。**亜種やその他のコンピュータ ウイルスへの対策は、**[コンピュータを安全にお使いいただくために](#step08)**をご覧ください。**

<p> <p/>  
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.task1(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Ctrl + Shift キーを押しながら Esc キーを押し、タスクマネージャを実行します。
次に [プロセス] タブを表示します。
イメージ名の欄に、&quot;msblast.exe&quot; (<strong>\*1</strong>) プログラムがあれば、そのファイル名をマウスでクリックし、[プロセスの終了] ボタンをクリックします。
<strong>注意 :</strong> Blaster ワームが動作していない場合には &quot;msblast.exe&quot; (<strong>\*1</strong>) は動作していません。タスクマネージャ右上の [×] ボタンをクリックしタスクマネージャを終了してください。タスクマネージャを終了させた後は、<strong>4. ネットワークケーブルをコンピュータに接続します</strong> へ進んでください。
(<strong>\*1</strong>) Blasterワームは現在いくつかの亜種が報告されています。亜種の場合は msblast.exe と表示されず別の名前になります。
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
<li><a href="http://www.symantec.com/region/jp/">株式会社シマンテック</a><img src="images/Dd362788.leave-ms(ja-jp,TechNet.10).gif" /></li>
<li><a href="http://www.trendmicro.co.jp/home/">トレンドマイクロ株式会社</a><img src="images/Dd362788.leave-ms(ja-jp,TechNet.10).gif" /></li>
<li><a href="http://www.mcafee.com/jp/default.asp">日本ネットワークアソシエイツ株式会社</a><img src="images/Dd362788.leave-ms(ja-jp,TechNet.10).gif" /></li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.task2(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">タスクマネージャーの警告が表示されます。[はい] をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.task3(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">msblast.exe プログラムが消えたことを確認し、[×] ボタンをクリックしタスクマネージャーを終了します。</td>
</tr>
</tbody>
</table>
  
#### 4. ネットワークケーブルをコンピュータに接続します
  
いよいよセキュリティ修正プログラムの適用を行いますので、ネットワークに接続してください。  
ダイアルアップの場合は、ダイアルアップネットワークを使用してネットワークに接続します。
  
#### 5-1. MS03-039 (MS03-026) を適用します
  
Blaster ワームが悪用する MS03-026 のセキュリティ修正プログラムを入手してインストールします。

<p> <p/>  
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
<td style="border:1px solid black;"><ul>
<li><a href="http://download.microsoft.com/download/c/9/1/c9118574-50cd-48f7-b1ce-215428628bc6/windows2000-kb824146-x86-jpn.exe">Windows 2000 (PC/AT 互換機)</a></li>
<li><a href="http://download.microsoft.com/download/7/0/7/70759c24-2b31-41ca-8ca8-f91200bd0169/windowsnt4server-kb824146-x86-jpn.exe">Windows NT Server 4.0 (PC/AT 互換機)</a></li>
<li><a href="http://download.microsoft.com/download/f/5/f/f5fa8b84-df16-4b10-9f58-6d7c758b8dd8/windowsnt4workstation-kb824146-x86-jpn.exe">Windows NT Workstation 4.0 (PC/AT 互換機)</a></li>
</ul></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左のリンクをクリックし、ご利用の Windows 用の MS03-039 のセキュリティ修正プログラムをダウンロードします。
<strong>注意 :</strong>
<ul>
<li>Windows NT 4.0 用の修正プログラムは、<a href="http://www.microsoft.com/japan/ntserver/downloads/sp6a.mspx">Windows NT Server 4.0 SP6a</a> の環境にインストールすることができます。</li>
<li>Windows 2000 用の修正プログラムは、<a href="http://www.microsoft.com/japan/windows2000/downloads/servicepacks/">Windows 2000 SP2</a>、<a href="http://www.microsoft.com/japan/windows2000/downloads/servicepacks/">Windows 2000 SP3</a> または <a href="http://www.microsoft.com/japan/windows2000/downloads/servicepacks/">Windows 2000 SP4</a> の環境にインストールすることができます。</li>
</ul></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.patch03039w2k1(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保存をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.patch03039w2k2(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップをクリックし、保存をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.patch03039w2k3(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の画面が表示され修正プログラムがダウンロードされます。
ダウンロード時間の目安は以下のとおりです。
<ul>
<li>ダイヤルアップ 約 3 分程度</li>
<li>ブロードバンド (ADSL、CATV、BFLTES) 約 1 分程度</li>
</ul></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.patch03039w2k5(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップ上に修正プログラムが保存されます。
この修正プログラムをダブルクリックし実行します。
<strong>メモ :</strong> 修正プログラムのインストールが完了したら、このファイルは削除しても構いません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.patch03039w2k6(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">修正プログラムを実行すると次の画面が表示されます。
[次へ] をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.patch03039w2k7(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[同意します] をクリックし、[次へ] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.patch03039w2k8(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の画面が表示され、修正プログラムがインストールされます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.patch03039w2k9(ja-jp,TechNet.10).png" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[完了] をクリックすると再起動が要求されますので再起動を実行します。</td>
</tr>
</tbody>
</table>
  
#### 5-2. MS03-007 を適用します
  
Blaster ワームの亜種が悪用する MS03-007 のセキュリティ修正プログラムを入手してインストールします。
  
![](images/Dd362788.815021_w2k_1(ja-jp,TechNet.10).gif)
  
![](images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif)
  
次のページにアクセスします。
  
-   [MS03-007: Windows コンポーネントの未チェックのバッファにより サーバーが侵害される (815021)](http://www.microsoft.com/japan/technet/security/bulletin/ms03-007.mspx)
  
修正プログラムの欄よりご利用の Windows 用の修正プログラムをダウンロードします。
  
**注意 :**
  
-   Windows NT 4.0 用の修正プログラムは、[Windows NT Server 4.0 SP6a](http://www.microsoft.com/japan/ntserver/downloads/sp6a.mspx) の環境にインストールすることができます。
  
-   Windows 2000 用の修正プログラムは、[Windows 2000 SP2](http://www.microsoft.com/japan/windows2000/downloads/servicepacks/sp2/) または [Windows 2000 SP3](http://www.microsoft.com/japan/windows2000/downloads/servicepacks/sp3/) の環境にインストールすることができます。[Windows 2000 SP4](http://www.microsoft.com/japan/windows2000/downloads/servicepacks/sp4/) 以降にはこの問題に対する修正が含まれています。
  
Windows 2000 をお使いのお客様は、MS03-007 の代わりに以下の修正プログラムを適応することでも Blaster ワームの亜種による攻撃を防ぐことができます。(Windows 2000 用の MS03-013 の修正プログラムには、MS03-007 の修正内容が含まれています。)
  
-   [MS03-013: Windows カーネル メッセージ処理のバッファ オーバーランにより、権限が昇格する (811493)](http://www.microsoft.com/japan/technet/security/bulletin/ms03-013.mspx)
  
**注意 :**
  
-   Windows 2000 用の修正プログラムは、[Windows 2000 SP2](http://www.microsoft.com/japan/windows2000/downloads/servicepacks/sp2/) または [Windows 2000 SP3](http://www.microsoft.com/japan/windows2000/downloads/servicepacks/sp3/) の環境にインストールすることができます。[Windows 2000 SP4](http://www.microsoft.com/japan/windows2000/downloads/servicepacks/sp4/) 以降にはこの問題に対する修正が含まれています。

<p> <p/>  
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.815021_w2k_2(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[このプログラムをディスクに保存する] をクリックし、[OK] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.815021_w2k_3(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップをクリックし、保存をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.815021_w2k_4(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の画面が表示され修正プログラムがダウンロードされます。
ダウンロード時間の目安は以下のとおりです。
<ul>
<li>ダイヤルアップ 約 3 分程度</li>
<li>ブロードバンド (ADSL、CATV、BFLTES) 約 1 分程度</li>
</ul>
<br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.815021_w2k_5(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップ上に修正プログラムが保存されます。
この修正プログラムをダブルクリックし実行します。
<strong>メモ :</strong> 修正プログラムのインストールが完了したら、このファイルは削除しても構いません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.815021_w2k_6(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">修正プログラムを実行すると次の画面が表示されます。
[次へ] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.815021_w2k_7(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[同意します] をクリックし、[次へ] をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.815021_w2k_8(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の画面が表示され、修正プログラムがインストールされます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.815021_w2k_9(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[完了] をクリックすると再起動が要求されますので再起動を実行します。</td>
</tr>
</tbody>
</table>
  
#### 6. ワームを駆除します
  
ウイルス対策ソフトウェアをお使いのお客様は、最新のウイルス定義ファイルをダウンロードして、スキャンと駆除を行ってください。
  
Windows 2000 をお使いで、ウイルス対策ソフトウェアをお持ちでないお客さまは、弊社のダウンロード　センターから　Windows Blaster ワーム駆除ツール (KB833330) Windows XP および Windows 2000 向けを入手することができます。手動で削除するよりも確実で、安全に駆除をすることができます。
  
このツールの詳細については[サポート技術情報 833330](http://support.microsoft.com/kb/833330) をご覧下さい。

<p> <p/>  
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Windows Blaster ワーム駆除ツール (KB833330) Windows XP および Windows 2000 向け (PC/AT 互換機)</td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><strong>注意 :</strong> 2005 年 2 月 8 日、マイクロソフトは Blaster ワーム駆除ツールを Microsoft Windows 悪意のあるソフトウェアの削除ツールに置き換えました。 悪意のあるソフトウェアの削除ツールの関連情報を参照するには、<a href="http://support.microsoft.com/kb/890830/">こちら</a>をクリックしてください。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.blstrtl01w2k(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">保存をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.blstrtl02w2k(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップをクリックし、保存をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.blstrtl03w2k(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">デスクトップ上に修正プログラムが保存されます。
この修正プログラムをダブルクリックし実行します。
<strong>メモ :</strong> 修正プログラムのインストールが完了したら、このファイルは削除しても構いません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.blstrtl04w2k(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">駆除ツールを実行すると次の画面が表示されます。
[次へ] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.blstrtl05w2k(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[同意します] をクリックし、[次へ] をクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.blstrtl06w2k(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">左の画面が表示され、駆除ツールが実行されます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.blstrtl07w2k(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
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
        [http://www.microsoft.com/downloads/details.aspx?FamilyId=2B2409F1-A844-483A-B019-16C0442D86F6&displaylang=ja](http://www.microsoft.com/downloads/details.aspx?familyid=2b2409f1-a844-483a-b019-16c0442d86f6&displaylang=ja)

#### 7. 分散 COM (DCOM) を再度有効にします

DCOM を無効化したままでは、その他のアプリケーションに影響を与える可能性がありますので、本対策をしたのちに有効にすることをお勧めいたします。

<p> <p/>  
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.start_w2k(ja-jp,TechNet.10).jpg" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">スタートメニューから [ファイル名を指定して実行] を選びます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.dcomcnfg(ja-jp,TechNet.10).jpg" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">表示されたウインドウの名前テキストボックスに、dcomcnfg と入力し、[OK] ボタンをクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362788.dcomp_on(ja-jp,TechNet.10).jpg" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362788.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[既定のプロパティ] タブを表示し、[このコンピュータ上で分散 COM を有効にする] チェック ボックスがオンの状態で、[OK] ボタンをクリックします。</td>
</tr>
</tbody>
</table>
  
#### 8. これで対策は終了です
  
できれば、[Windows Update](http://windowsupdate.microsoft.com) を使用して、そのほかのセキュリティ修正プログラムも可能な限りインストールすることをお勧めいたします。

 
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
