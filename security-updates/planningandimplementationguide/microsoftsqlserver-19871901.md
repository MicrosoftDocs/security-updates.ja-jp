---
TOCTitle: 'ウイルス情報 : Microsoft SQL Server を狙ったワームに関する情報'
Title: 'ウイルス情報 : Microsoft SQL Server を狙ったワームに関する情報'
ms:assetid: '107bfe63-e2f6-43da-9d30-2b0d5f925257'
ms:contentKeyID: 19871901
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362956(v=TechNet.10)'
---

Microsoft SQL Server を狙ったワームに関する情報
===============================================

公開日: 2001年11月28日 | 最終更新日: 2001年11月30日

##### トピック

[](#ehaa)[はじめに](#ehaa)
[](#egaa)[Microsoft SQL Server を狙ったワームの影響を受ける恐れのある製品](#egaa)
[](#efaa)[ワームの影響](#efaa)
[](#eeaa)[確認方法](#eeaa)
[](#edaa)[詳細](#edaa)
[](#ecaa)[対策](#ecaa)
[](#ebaa)[対策による影響](#ebaa)
[](#eaaa)[osql コマンドについて](#eaaa)

### はじめに

現在、CBLAD と呼ばれる SQL Server を対象としたワームが活動範囲を広げています。

CBLAD は、SQL Server に対して、sa ログイン (ユーザー)、パスワード 無し (ブランク) で接続を試み、トロイの木馬の設置などを行います。 そのため、 sa に対して適切なパスワードを設定している場合、または SQL Serverの認証モードとしてWindows 認証 (統合セキュリティ) を利用している場合には、このワームの影響を受けることはありません。

本ワームは、製品の脆弱性を利用するものではなく、SQL Server の運用上の脆弱性を利用しているため、パスワードの設定を正しく行うことでワームの侵入を防ぐことが出来ます。

[](#mainsection)[ページのトップへ](#mainsection)

### Microsoft SQL Server を狙ったワームの影響を受ける恐れのある製品

直接対策が必要な製品

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

-   Microsoft BizTalk Accelerator for Suppliers 1.0

-   Microsoft BizTalk Accelerator for RosettaNet 1.0

-   Microsoft BizTalk Adapter for SAP 1.0

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

### ワームの影響

現時点では、後述のようにワームの本体が廃棄されていることから、このワームが感染することによる直接の影響はありません。

しかしながら、 sa にパスワードが設定されていないことが悪意のあるユーザーに通知されるために、別途 SQL Server を踏み台にし悪用される危険があります。

SQL Server は、通常のインストール状態では、SYSTEM アカウント、もしくはローカル コンピュータまたはドメインの管理者権限を持つユーザーで実行されています。

そのため SQL Server の 管理者である sa ログイン (ユーザー) での侵入を許してしまうと、SQL Server で全てのコマンドを実行できることを意味し、OS の管理者 (Administrator) と同等またはそれ以上の権限で他のアプリケーションを動作させることが可能です。

[](#mainsection)[ページのトップへ](#mainsection)

### 確認方法

確認作業は、必ず、 SQL Server が実行されているサーバーにローカル ログオンし行ってください。

以下の条件に合致する場合感染の可能性があります。

-   ディスク内を検索し、 dnsserver.exe が発見された場合

-   以下のレジストリが存在する場合

    HKLM\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Run
    キー: TaskReg
    値 : (dnsserver.exe への完全なパス)

以下の方法で sa のパスワードが正しく設定されているかどうか確認することが可能です。

1.  コマンドプロンプトまたは、MS-DOS プロンプトを開きます。

2.  osql コマンドライン ユーティリティがインストールされているフォルダに移動するために、以下のコマンドを入力し実行します。

    (SQL Server 2000 の場合)
    cd \\Program Files\\Microsoft SQL Server\\80\\Tools\\Binn

    (SQL Server 7.0 の場合)
    cd \\MSSQL70\\Binn

    (SQL Server 6.5)
    cd \\MSSQL65\\Binn

    (MSDE)
    cd \\MSSQL70\\Binn  または  cd \\Program Files\\Microsoft SQL Server\\80\\Tools\\Binn

3.  次のコマンドを入力し実行します。ただし、確認する対象の SQL Server が名前付きインスタンス（SQL Server 2000 のみ）である場合、下記の "localhost" を適切なインスタンス名に置き換えてください。

    osql -U sa -P -S localhost -Q

4.  手順 3 の結果を確認します。

    "ログインが正しくありません。" などのログインに失敗したことを示すメッセージが表示された場合、 sa にはパスワードが設定されています。

    特にメッセージが表示されること無く、コマンドプロンプトが表示される場合は、 sa にパスワードは設定されていません。

以下の方法で TCP ポート 1433 が使われているかどうか確認することが可能です。

1.  コマンドプロンプトまたは、MS-DOS プロンプトを開きます。

2.  次のコマンドを入力し実行します。

    netstat -a -n | find "1433"

3.  手順 2 の結果を確認します。

    何も表示されずに、コマンドプロンプトが表示される場合は、ポート 1433 は使用されていません。

    以下の情報が表示された場合は、 ポート 1433 が使用されています。
        ```

[](#mainsection)[ページのトップへ](#mainsection)

### 詳細

CBLAD は、SQL Server に対して TCP ポート 1433 を利用して接続を試みます。

ポート 1433 は、SQL Server を規定のインスタンスでセットアップした場合に使用されます。名前付きインスタンスでセットアップした場合には初回起動時に未使用のTCPポートを動的に割り当てるため、1433を使用しているとは限りません。

接続後、次のログイン情報を使用して接続を試みます。

ユーザー名 : SA
パスワード : (無し)

sa は、SQL Server に対する全権限を持った特別なログイン (ユーザー) です。

SQL Server のバージョンやインストール方法および、インストール時に選択したオプションによっては、sa の初期パスワードは、設定されない状態でインストールされます。

SQL Server への接続に成功すると、ワームは以下の動作を行います。

-   インターネット上の IRC サーバーに接続し感染したことを通知する。

-   FTP サーバーに接続しトロイの木馬を取得し実行する

IRC サーバー bots.kujikiri.net の TCP ポート 6669 に対して接続し、接続に成功したことを通知するメッセージ送信します。 このメッセージにより、悪意のあるユーザーが、送信元の SQL Server に容易に侵入可能なことを知ることになります。

FTP サーバーへの接続は、 SQL Server の xp\_cmdshell システム ストアド プロシージャ (汎用拡張プロシージャ) を利用して行われます。 これにより、 IP アドレス 207.29.192.160 に対して ユーザー名 ftp、パスワード foo.com で接続します。

接続の後、 dnsserver.exe を取得し実行しますが、 dnsserver.exe は、すでに 上記 ftp サイトより削除され取得することは出来ません。そのため、実際には、 dnsserver.exe の実行は行われません。

また、ftp サーバーより速やかに dnsserver.exe が削除されたため、どのような動作をするものであるかは現在のところ確認できていません。

しかしながら、今後、同種の手順にて SQL Server の運用上の脆弱性を利用したセキュリティ攻撃が行われる可能性があるため、以下の対策を必ず行うようにしてください。

[](#mainsection)[ページのトップへ](#mainsection)

### 対策

SQL Server の認証モードにWindows 認証 (統合セキュリティ) を利用している場合には、sa のログイン (ユーザ) を利用することができないため、このワームによる影響は受けません。混合モード (混合セキュリティ) または標準セキュリティ (SQL Server 6.5 以前) を利用している場合には、以下の対応が必要となります。

SQL Server の sa ログイン (ユーザー) のパスワードを設定することで対策できます。

SQL Server へのパスワードの設定は、以下の方法で行います。

1.  コマンドプロンプトまたは、MS-DOS プロンプトを開きます。

2.  次のコマンドを入力し実行します。

    実際に設定するパスワード文字列に置き換えてください。また、他人に類推されにくく、辞書などに無いフレーズに置き換えてください。 なお、対象の SQL Server が名前付きインスタンスである場合、下記の "localhost" を適切なインスタンス名に置き換えてください。
        ```

3.  手順 2 の結果を確認します。成功すると、以下が表示されます。
        ```

[](#mainsection)[ページのトップへ](#mainsection)

### 対策による影響

他の製品または、お客様により作成されたアプリケーションから、SQL Server に対して sa を使用し接続している場合、sa のパスワードを変更することで、SQL Server へ接続できなくなることがございます。その際は、アプリケーション側の設定を変更するようお願いいたします。

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

オプションの説明

 
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
