---
TOCTitle: SQL Server および MSDE を標的とした SQL Slammer ワームに関する情報
Title: SQL Server および MSDE を標的とした SQL Slammer ワームに関する情報
ms:assetid: '626ad711-945f-44ed-b8a8-c5865f070574'
ms:contentKeyID: 19870167
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362406(v=MSDN.10)'
---

SQL Server および MSDE を標的とした SQL Slammer ワームに関する情報
==================================================================

よくある質問と回答
------------------

------------------------------------------------------------------------

### 概要編

Q. Slammer ワームとは何ですか?
------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
Slammer ワームは、SQL Server 2000 および MSDE 2000 の弱点を悪用するワームです。このワームは SQL Server 2000 に対して、UDP 1434 ポート (SQL Server 2000 解決サービスで使用するポート) に対して UDP の攻撃パケットを送信します。このワームに感染した場合、「多大なトラフィックによるインターネット、および LAN の速度低下 」、「CPU 使用率 100% 」が発生します。
</td>
</tr>
</table>
 

Q. Slammer ワームが利用しているのはどのような弱点ですか?
--------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
Slammer ワームには、既知のセキュリティ上の弱点 [MS02-039「SQL Server 2000 解決サービスのバッファのオーバーランにより、コードが実行される (Q323875)」](http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx)が使用されています。
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
Slammer ワームは、SQL Server 2000 または MSDE 2000 をインストールしているコンピュータに感染する恐れがあります。次のステップを確認の上、該当する製品がインストールしていないかご確認ください。
  
<ol>
<li>
\[スタート\] - \[検索\] - \[ファイルやフォルダ(F)...\] をクリックします。  
</li>
<li>
"ファイルまたはフォルダの名前に ssnetlib.dll と入力します。  
</li>
<li>
\[検索開始\]ボタンをクリックします。  
</li>
<li>
ウインドウの右側に検索結果が表示されます。検索は少し時間がかかる場合があります。  
</li>
<li>
ファイルがシステム上に存在している場合、MSDE または SQL Server がインストールされています。  
</li>
<li>
ssnetlib.dll の上で右クリックし、 \[プロパティ\]をクリックします。  
</li>
<li>
ssnetlib.dll のプロパティが開きます。  
</li>
<li>
\[バージョン情報\] タブをクリックします。  
</li>
<li>
ファイル　バージョンを確認します。  
</li>
-   バージョンが、 2000.xx.xxx.x ではない場合は、影響を受けません。(SQL Server 2000 または MSDE 2000 ではありません。)  
-   バージョンが、 2000.80.636.0 よりも古い場合は、影響を受けるため、対策を行う必要があります。
  
</ol>
対策方法は[「SQL Server および MSDE を標的とした SQL Slammer ワームに関する情報」](http://www.microsoft.com/japan/technet/security/alerts/slammer.mspx)をご覧ください

</td>
</tr>
</table>
 

Q. MSDE 2000 はどのような製品に含まれますか?
--------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
MSDE 2000 は、以下の製品に同梱されています。
  
-   Microsoft SQL Server 2000 Enterprise Edition  
-   Microsoft SQL Server 2000 Standard Edition  
-   Microsoft SQL Server 2000 Personal Edition  
-   Microsoft SQL Server 2000 Developer Edition  
-   Microsoft Small Business Server 2000  
-   Microsoft Visual Studio .NET Enterprise Architect (および同 MSDN Deluxe Edition)  
-   Microsoft Visual Studio .NET Enterprise Developer (および同 MSDN Deluxe Edition)  
-   Microsoft Visual Studio .NET Professional (および同 MSDN Deluxe Edition)  
-   Microsoft Visual Studio .NET Academic  
-   Microsoft Visual C++ .NET Standard  
-   Microsoft Visual Basic .NET Standard  
-   Microsoft Visual C\# .NET Standard  
-   Microsoft Visual J\#  
-   Microsoft Office XP Developer  
-   Microsoft .NET Framework SDK  
-   Microsoft Access 2002  
-   Microsoft Visio Enterprise Network Tools (VENT)  
-   Microsoft Office XP  
-   Microsoft Biztalk Server 2002 Partner Edition  
-   Microsoft Host Integration Server 2000  
-   Microsoft Windows Server 2003 RC1  
    (Microsoft Windows Server 2003 **RC2** は Slammer ワームの影響を受けません。 **RC2** については[こちら](http://www.microsoft.com/japan/windowsserver2003/preview/default.mspx)をご覧ください。)
  
注意 : 上記製品の既定のインストールでは、MSDE 2000 がインストールされることはありません。 MSDE 2000 が既定でインストールされる製品は、[「SQL Server および MSDE を標的とした SQL Slammer ワームに関する情報」](http://www.microsoft.com/japan/technet/security/alerts/slammer.mspx)の「MSDE 2000 を既定でインストールする製品」をご覧ください。

</td>
</tr>
</table>
 

Q. MSDE 2000 とは何ですか?
--------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
MSDE 2000 とはマイクロソフトおよびサードパーティのいくつかの製品に含まれるデータベース エンジンです。ほとんどの場合、MSDE は SQL Server 2000 を必要としない状況でこれらのアプリケーションを使用するお客様に、代わりになるものとして提供されます。MSDE 2000 は必ずしも既定でインストールされているわけではありません。
</td>
</tr>
</table>
 

Q. MSDE を含んだ製品を販売しています。どのような対策をとればよいでしょうか?
---------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
MSDE 2000 を含んだ製品を販売されている ISV 様は、[こちら](http://www.microsoft.com/japan/sql/prodinfo/previousversions/techinfo/administration/2000/security/isvswithmsdes.mspx)のページをご覧ください。
</td>
</tr>
</table>
 

### 対策編

Q. MS02-061 に MS02-039 は含まれますか?
---------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
はい。MS02-061 は、MS02-039 の修正を含んでいます。
</td>
</tr>
</table>
 

Q. MSDE 2000 の Service Pack 3 をインストールするとエラーが表示されます。
-------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
ダウンロードしたファイルに含まれている sp3readme.htm の [「3.7 Desktop Engine SP3 のインストール」](http://www.microsoft.com/japan/sql/downloads/2000/sp3readme.htm#_install_desktop_engine_sp3) - **「SQL Server 2000 Desktop Engine をアップグレードする方法」**をご覧の上、コマンドプロンプトより各ステップ順に実行してください。
</td>
</tr>
</table>
 

Q. SQL Server Service Pack 3 がインストールされたか確認する方法はありますか?
----------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
ダウンロードしたファイルに含まれている sp3readme.htm の [「1.3 SQL Server または Analysis Services の現在のバージョンの識別」](http://www.microsoft.com/japan/sql/downloads/2000/sp3readme.htm#_identifying_the_current_version_of_sql_server_or_analysis_services)をご覧ください。
</td>
</tr>
</table>
 

Q. Application Center 2000 はどのように対策すれば良いのですか?
--------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
Application Center 2000 の Slammer ワームの対策については、下記サポート技術情報をご確認ください。
  
-   [813115: \[FIX\] Application Center 2000 の MSDE 2000 の脆弱性が W32.Slammer ワームによって利用される](http://support.microsoft.com/default.aspx?scid=kb;ja;813115)

</td>
</tr>
</table>
 

Q. Application Center 2000 用の MSDE インスタンスに、MSDE SP3 を適用しても問題ないですか?
-----------------------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
いいえ。Application Center 2000 用の MSDE インスタンスに、MSDE SP3 を適用することはできません。 現時点の Application Center 2000 用の MSDE インスタンスに対する Slammer ワーム対策は、下記サポート技術情報をご確認ください。
  
-   [813115: \[FIX\] Application Center 2000 の MSDE 2000 の脆弱性が W32.Slammer ワームによって利用される](http://support.microsoft.com/default.aspx?scid=kb;ja;813115)

</td>
</tr>
</table>
 

Q. Application Center 2000 用の MSDE インスタンスに、MS02-061 を適用しても問題ないですか?
-----------------------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
はい。Application Center 2000 用の MSDE インスタンスに、MS02-061 を適用できます。 現時点の Application Center 2000 用の MSDE インスタンスに対する Slammer ワーム対策は、下記サポート技術情報をご確認ください。
  
-   [813115: \[FIX\] Application Center 2000 の MSDE 2000 の脆弱性が W32.Slammer ワームによって利用される](http://support.microsoft.com/default.aspx?scid=kb;ja;813115)

</td>
</tr>
</table>
 

Q. BizTalk Server を使用しています。SQL Server 2000 Service Pack 3 のインストール時に以下のエラーが発生してインストールができません。スクリプト実行エラー : sp1\_serv\_uni.sql (1)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
MDAC 2.7 をインストールしている環境で、BizTalk Server をご使用の場合に、このエラーが発生します。 SQL Server 2000 Service Pack 3 適用時には、BizTalk Server のサービスを停止してから実行してください。
</td>
</tr>
</table>
 

Q. Microsoft Server Appliance Kit 2.0 Add-On Pack でインストールされる MSDE には、どのように対策すればいいのですか?
-------------------------------------------------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
Microsoft Server Appliance Kit は、Windows 2000 および MSDE 英語版をベースに MUI により日本語表示が可能になっております。 そのため、MSDE の修正プログラムは、[英語版](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=9552d43b-04eb-4af9-9e24-6cde4d933600)をご利用ください。
</td>
</tr>
</table>
 

Q. SQL Server 2000 Service Pack 3a は SQL Slammer ワームの影響を受けますか?
---------------------------------------------------------------------------

<table border="0" cellpadding="0" cellspacing="0" style="margin-top:10px" width="100%">
<tr>
<td style="border:1px solid black;" valign="top" width="2%">
**A.**
</td>
<td style="border:1px solid black;" rowspan="2" valign="top" width="98%">
いいえ、受けません。SQL Server 2000 Service Pack 3a は SQL Slammer ワームが悪用する [MS02-039](http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx) の修正が含まれています。
</td>
</tr>
</table>
 

[<img src="images/dd362406.arrow_px_up(ja-jp,TechNet.10).gif" alt="ページのトップへ" width="7" height="9" />](#top) [ページのトップへ](#top)
