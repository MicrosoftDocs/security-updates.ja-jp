---
TOCTitle: 'ウイルス情報 : SQL Server を標的とした SQLSPIDA ワームに関する情報'
Title: 'ウイルス情報 : SQL Server を標的とした SQLSPIDA ワームに関する情報'
ms:assetid: 'afc397da-0087-4244-b102-783ff29a5946'
ms:contentKeyID: 19871900
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362955(v=TechNet.10)'
---

SQL Server を標的とした SQLSPIDA ワームに関する情報
===================================================

公開日: 2002年5月22日

##### トピック

[](#eeaa)[はじめに](#eeaa)
[](#edaa)[影響を受ける恐れのある製品](#edaa)
[](#ecaa)[本ワームへの対策](#ecaa)
[](#ebaa)[対策による影響](#ebaa)
[](#eaaa)[osql コマンドについて](#eaaa)

### はじめに

SQLSPIDA ワームと呼ばれる Microsoft SQL Server を対象としたワームが確認されています。弊社では、このワームによる影響からお客様の環境を守るため、情報を公開いたします。(別名に JS\_SQLSPIDA.B, BAT\_SQLSPIDA.B. Digispid.B.Worm, JS\_SQLSpida.B, Hacktool.IPStealer, JS.Spida.B, SQLSnake, SQLSpida, MS SQL Worm等があります)

本ワームは SQL Server に対して、TCP 1433 ポートから、sa ログイン (ユーザー)、パスワード 無し (ブランク) で接続を試み感染活動を行います。 したがって、下記の場合には、このワームの影響を受けません。

-   SQL Server が使用している　TCP 1433 ポートをインターネットとの接続を行っているルータもしくはファイヤウォールで遮断している場合

-   sa に対して適切なパスワードを設定している場合

-   SQL Server の認証モードとして Windows 認証 (統合セキュリティ) を利用している場合

また、以下の Web サイトにて本ワームに関する情報が公開されておりますので併せてご参照ください。

-   株式会社シマンテック    
    [http://securityresponse.symantec.com/avcenter/venc/data/digispid.b.worm.html](http://www.symantec.com/region/jp/sarcj/data/d/digispid.b.worm.html)![](images/Dd362955.leave-ms(ja-jp,TechNet.10).gif)

-   トレンドマイクロ株式会社 (英語)    
    [http://www.antivirus.com/vinfo/virusencyclo/default5.asp?VName=JS\_SQLSPIDA.B](http://www.antivirus.com/vinfo/virusencyclo/default5.asp?vname=js_sqlspida.b)![](images/Dd362955.leave-ms(ja-jp,TechNet.10).gif)

-   日本ネットワークアソシエイツ株式会社 (英語)    
    <http://vil.nai.com/vil/content/v_99499.htm>![](images/Dd362955.leave-ms(ja-jp,TechNet.10).gif)

[](#mainsection)[ページのトップへ](#mainsection)

### 影響を受ける恐れのある製品

-   Microsoft SQL Server 2000 Enterprise Edition

-   Microsoft SQL Server 2000 Standard Edition

-   Microsoft SQL Server 2000 Personal Edition

-   Microsoft SQL Server 2000 Developer Edition

-   Microsoft SQL Server 2000 Desktop Engine (MSDE)

-   Microsoft SQL Server 7.0 Enterprise Edition

-   Microsoft SQL Server 7.0 Standard Edition

-   Microsoft SQL Server 7.0 Desktop Edition

-   Microsoft Data Engine 1.0 (MSDE)

-   Microsoft SQL Server 6.5

-   Microsoft SQL Server Workstation System 6.5

-   Microsoft SQL Server 6.0

-   Microsoft SQL Workstation 6.0

-   Microsoft SQL Server 4.21a

-   Microsoft SQL Server 4.21a Workstation System

SQL Server/MSDE を使用する可能性のある製品

-   Microsoft SQL Server 2000 Windows CE Edition

-   Microsoft Small Business Server 4.0

-   Microsoft Small Business Server 4.5

-   Microsoft Small Business Server 2000

-   Microsoft BackOffice Server 4.0

-   Microsoft BackOffice Server 4.5

-   Microsoft BackOffice Server 2000

-   Microsoft Windows Media Rights Manager version 1.0

-   Microsoft Windows Media Rights Manager version 7 SDK

-   Microsoft Application Center 2000

-   Microsoft BizTalk Server 2000

-   Microsoft Content Management Server 2001

-   Microsoft Commercial Internet System 1.0

-   Microsoft Commercial Internet System 2.0

-   Microsoft Commercial Internet System 2.5

-   Microsoft Merchant Server 1.0

-   Microsoft Commerce Server 2000

-   Microsoft Site Server 3.0 Commerce Edition

-   Microsoft Site Server 3.0

-   Microsoft Site Server 2.0 Enterprise Edition

-   Microsoft Site Server 2.0

-   Microsoft Visual Studio 6.0 Enterprise Edition (Visual Studio 6.0 Pluspack)

-   Microsoft Visual Studio 6.0 Professional Edition (Visual Studio 6.0 Pluspack)

-   Microsoft Visual Basic 6.0 Enterprise Edition (Visual Studio 6.0 Pluspack)

-   Microsoft Visual Basic 6.0 Professional Edition (Visual Studio 6.0 Pluspack)

-   Microsoft Visual C++ 6.0 Enterprise Edition (Visual Studio 6.0 Pluspack)

-   Microsoft Visual C++ 6.0 Professional Edition (Visual Studio 6.0 Pluspack)

-   Microsoft Visual InterDev 6.0 Professional Edition (Visual Studio 6.0 Pluspack)

-   Microsoft Visual J++ 6.0 Professional Edition (Visual Studio 6.0 Pluspack)

-   Microsoft Visual Studio.net Enterprise Architect

-   Microsoft Visual Studio.net Enterprise Architect (MSDN Deluxe Edition)

-   Microsoft Visual Studio.net Enterprise Developer

-   Microsoft Visual Studio.net Enterprise Developer (MSDN Deluxe Edition)

-   Microsoft Message Queue Server 1.0

-   Microsoft Internet Security and Acceleration Server 2000 Standard Edition

-   Microsoft Internet Security and Acceleration Server 2000 Enterprise Edition

-   Microsoft Internet Information Server 4.0

-   Microsoft Internet Information Services 5.0

-   Microsoft Internet Information Services 5.1

-   Microsoft Systems Management Server

-   Microsoft Host Integration Server 2000

-   Microsoft Proxy Server 1.0

-   Microsoft Proxy Server 2.0

-   Microsoft Office 2000 Professional

-   Microsoft Office 2000 Premium

-   Microsoft Office 2000 Developer

-   Microsoft Office XP Professional

-   Microsoft Office XP Developer

-   Microsoft Office XP Professional with FrontPage

-   Microsoft Access 2000

-   Microsoft Access 2002

-   Microsoft FrontPage 2002

-   Microsoft Office Server Extensions

-   Microsoft SharePoint Team Services

-   Microsoft Project Central

-   Microsoft Visio 2000 Enterprise Edition

-   Microsoft Visio Professional 2002 with Enterprise Network Tools

-   Microsoft Visio Enterprise Network Tools 2002

-   Microsoft Project 2000

-   Microsoft GroupBoard 1.2

[](#mainsection)[ページのトップへ](#mainsection)

### 本ワームへの対策

SQL Server の認証モードに Windows 認証 (統合セキュリティ) を利用している場合には、sa のログイン (ユーザー) を利用することができないため、このワームによる影響は受けません。混合モード (混合セキュリティ) または標準セキュリティ (SQL Server 6.5 以前) を利用している場合には、以下の対応が必要となります。

SQL Server の sa ログイン (ユーザー) のパスワードを設定することで対策できます。

SQL Server へのパスワードの設定は、以下の方法で行います。

1.  コマンドプロンプトまたは、MS-DOS プロンプトを開きます。

2.  osql コマンドを入力し実行します。osql コマンドの詳細は下記 「osql コマンドについて」 をご覧ください。

    実際に設定するパスワード文字列に置き換えてください。また、他人に類推されにくく、辞書などに無いフレーズに置き換えてください。 なお、対象の SQL Server が名前付きインスタンスである場合、下記の "localhost" を適切なインスタンス名に置き換えてください。
        ```
        osql.exe -U sa -P -S localhost -Q "sp_password NULL, '(Password)', 'sa'"
        ```

3.  手順 2 の結果を確認します。成功すると、次のメッセージが表示されます。
        ```
        パスワードが変更されました。
        ```

また、SQL Server の最新のセキュリティ修正プログラムを適用することを強く推奨します。最新のセキュリティ修正プログラムは次のサイトをご覧ください

-   [MS02-020: SQL 拡張プロシージャ機能に未チェックのバッファが含まれる (Q319507)](http://www.microsoft.com/japan/technet/security/bulletin/ms02-020.mspx)

[](#mainsection)[ページのトップへ](#mainsection)

### 対策による影響

他のアプリケーションから、SQL Server に対して sa を使用し接続している場合、sa のパスワードを変更することで、SQL Server へ接続できなくなることがあります。この場合、アプリケーション側の設定を変更し、sa での接続にパスワードを設定してください。

[](#mainsection)[ページのトップへ](#mainsection)

### osql コマンドについて

osql コマンドは、デフォルトでは以下の場所にインストールされています。

(SQL Server 2000)
\\Program Files\\Microsoft SQL Server\\80\\Tools\\Binn

(SQL Server 7.0)
\\MSSQL70\\Binn

(SQL Server 6.5)
\\MSSQL65\\Binn

(MSDE)
\\MSSQL70\\Binn  または  \\Program Files\\Microsoft SQL Server\\80\\Tools\\Binn

オプションの説明 :

 
<p></p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">-U :</td>
<td style="border:1px solid black;">SQL Server に接続するためのログイン (ユーザー) を指定します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">-P :</td>
<td style="border:1px solid black;">ログイン(ユーザー)のパスワードを指定します。<br />
このドキュメントでは、 パスワードなしの sa を使用しているためパスワードの指定を行っておりません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">-S :</td>
<td style="border:1px solid black;">SQL Server が動作しているインスタンス (サーバー) を指定します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">-Q :</td>
<td style="border:1px solid black;">SQL Server に対して指定したクエリの実行を要求し、実行後に、このコマンドを終了させるオプションです。<br />
&quot;(ダブルコーテーション) で囲まれた部分がクエリ文字列になります。</td>
</tr>
</tbody>
</table>

osql コマンドおよび SQL Server の詳細につきましては、SQL Server に付属する Books Online、ヘルプ、製品マニュアルをご参照ください。

[](#mainsection)[ページのトップへ](#mainsection)
