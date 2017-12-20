---
TOCTitle: 'Microsoft Baseline Security Analyzer V1.2 とスクリプト'
Title: 'Microsoft Baseline Security Analyzer V1.2 とスクリプト'
ms:assetid: '6d3b8c34-dd2d-456b-ab3a-a902883d410d'
ms:contentKeyID: 19869654
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277363(v=TechNet.10)'
---

Microsoft Baseline Security Analyzer V1.2 とスクリプト
======================================================

最終更新日: 2004年3月17日

##### トピック

[](#ehaa)[概要](#ehaa)
[](#egaa)[背景](#egaa)
[](#efaa)[よく寄せられる質問](#efaa)
[](#eeaa)[始めに](#eeaa)
[](#edaa)[サンプル \#1](#edaa)
[](#ecaa)[サンプル \#2](#ecaa)
[](#ebaa)[サンプル \#3](#ebaa)
[](#eaaa)[有効なチェック ID](#eaaa)

### 概要

MBSA (Microsoft® Baseline Security Analyzer) は、Windows® ベースの 1 台以上のコンピュータについて、セキュリティの構成に問題が無いかをスキャンするためのツールです。MBSA は Windows ベースのコンピュータをスキャンし、オペレーティング システムと、Windows 2000 Server の IIS (Internet Information Services) や SQL Server™ などのインストールされているその他のコンポーネントについて、セキュリティの構成に問題がないかどうかをチェックしたり、推奨されるセキュリティ修正プログラムがインストールされ、最新の状態になっているかどうかをチェックしたりします。この文書では、MBSA のサンプル スクリプトに関するガイダンスを提供します。このガイダンスは、MBSA が行えるスキャンの範囲を広げ、レポーティング機能をより高いレベルに拡張する方法を説明するものです。サンプル スクリプトを使用した際の結果については補償されません。これらのサンプルは MBSA 1.2 のみにより生成される XML レポートを使用します。これらのレポートのスキーマはマイクロソフトにより文書化されておらず、MBSA で使用する以外の用途ではサポートされていません。マイクロソフトは予告なく、このスキーマに変更を行う場合もあります。

この文書を、関連する[サンプル スクリプトのダウンロード](http://www.microsoft.com/downloads/details.aspx?familyid=42661e18-93c2-4ce2-85d6-3679defe1a3e&displaylang=en) (英語) とともに使用して下さい。

[](#mainsection)[ページのトップへ](#mainsection)

### 背景

MBSA は個々のレポートを XML 形式で生成し、これらのレポートの表示方法としては個々の表示のみをサポートします。組み込みのダッシュボードや結果の概要表示はありません。さらに、バッチモードで入力ファイル (/fh および /fip オプション) からコンピュータ名や IP アドレスを読み込む場合、スキャンできるホスト数に制限があります。また別の制限として、ローカル コンピュータをスキャンするためには、ローカル管理者の権限が必要です。

こういった制限にたいして、スクリプトを使用し MBSA の機能を拡大するすばらしい方法がいくつかあります。この文書はコマンド ラインの例、およびこれらの制限の多くを解決するために必要となるサンプル スクリプトを提供します。これらはサンプルであるため、各自のニーズに合わせて機能を拡張することもできます。

[](#mainsection)[ページのトップへ](#mainsection)

### よく寄せられる質問

**Q:** **どのような人物** **(管理者、ユーザー、総括管理者)** **がこれらの出力レポートを使用するのですか?**

A: ローカル管理者でないユーザーでも、コンピュータのセキュリティ レベルをチェックできます。(管理者がいつコンピュータをリモートでスキャンしたかによります。) 管理者権限があれば、さらに強固なスキャン方法を確立することができ、さらに多くのコンピュータをスキャンし、結果をそのほかのソリューションに統合するといったことも可能です。総括管理者が利用する場合は、スキャン結果のダッシュボードにアクセスし、各項目やパーセントによるセキュリティ レベルの表示を見る事ができます。

**Q:** **これらのスクリプトはどのような問題や制限の手助けとなりますか?**

A: BatchScan.js では、mbsacli.exe の /fh、/fip パラメータを使用して指定できる IP アドレス数、ホスト数の制限をバイパスする方法、MBSA 形式で /c パラメータを使用してスキャンするコンピュータを 1 台指定する場合の制限をバイパスする方法を提案します。Rollup.js は個別のレポートを結合して各セキュリティ修正プログラムの適用状況などの総合結果を出す方法を提案します。そして Rollup.xslt はみやすい概要表示の方法や特定のコンピュータやセキュリティ レベルへドリル ダウンして表示する方法を提案します。

**Q:** **これらのレポートは組織をさらにセキュアにするためにどのように使用することができますか?**

A: これらのチェック項目またはセキュリティ情報のフィルタを許可することにより、また、組織全体の概要表示を見ることができるようにすることで、最大の危険をもたらすコンピュータをより迅速に発見し、隔離することができます。特定の脆弱性について、クイック ボタンをクリックすることにより、スキャン結果にもとづいてコンピュータが一覧表示されます。

**Q:** **これらのスクリプトおよび出力レポートをカスタマイズするためには何ができますか?**

A: コマンド ライン パラメータにより、1 つまたは複数のセキュリティ情報または チェック IDを選択することができるので、単にコマンド ラインを変更することにより、要約される/レポートされるデータの範囲を制御することができます。XSLT および XML を熟知している場合、XML レポートを SMS 2.0 および SMS 2003 MIF テキスト ファイル形式に変換し、SQL レポートの集中化とセキュリティ管理の拡張を行うためにSMS データベース内にカスタム グループ クラスを作成するなど、そのほかのソリューションとのさらに興味深い統合を行うこともできます。別の例としては、特定のセキュリティ情報の展開時に使用される変更リクエスト IDなどのセキュリティ情報の識別子をローカルで管理している概要の XML ファイルに挿入することもできます。

**Q:** **これらのスクリプトは何を行いますか?**

A: サンプル \#1 は 2 段階にわけたスキャンの実行方法を示します。段階 1 では、ローカル管理者権限を使用してスキャン対象の各コンピュータに結果レポートをプッシュします。段階 2 はスキャンされたコンピュータをローカルで使用することにより、ローカル管理者でなくても、レポートを表示することを許可します。サンプル \#2 は、テキスト ファイルを使用し、無限の台数のコンピュータをスキャンする方法を示しています。サンプル \#3 は、簡単に使用できるダッシュボードを用いてセキュリティ構成の状態や修正プログラムの適用率をパーセントで表示し、全体のメトリックスの結果を要約して表示する方法を示しています。

[](#mainsection)[ページのトップへ](#mainsection)

### 始めに

この文書には、スクリプト使用の可能性を示す 3 つのサンプルがあります。サンプルを使用する前に、次の事をおこなってください。まず、MBSA 1.2 がローカル コンピュータの既定のインストール フォルダ (C:\\Program files\\Microsoft Baseline Security Analyzer) にインストールされているか確認して下さい。BatchScan.js サンプルは、スキャン中にこの場所を使用します。次に、ダウンロード センターからスクリプト ファイルを入手し、C:\\MBSASamples など、ローカルのフォルダにインストールして下さい。そして、この文書の各セクションに含まれているコマンド例に基づいて notepad.exe または適切なエディタを使用して、バッチ ファイルを作成します。

また、**有効なチェック** **ID** のセクションを必ずご覧下さい。そのセクションでは、各チェックの識別番号一覧を提供しており、チェックの名前は MBSA のユーザー インターフェースで表示されるものです。

[](#mainsection)[ページのトップへ](#mainsection)

### サンプル \#1

このサンプルは 2 段階のスキャンを実行するよう設計されています。1) 第 1 段階は対象となるコンピュータをスキャンし、スキャン結果を更新します。2) 次の段階では、ユーザーが自分のコンピュータのセキュリティ レベルをチェックするために必要なローカル管理者権限を持たない場合のチェック方法です。これにはいくつかの前提条件があります。まず、スキャン対象のコンピュータの一覧に多くのコンピュータがあるということです。(このケースについては、サンプル \#2 をご参照下さい。) 次の前提は、各コンピュータには複数のユーザーがいるということです。サンプル \#1 はスキャン結果で 1 つ以上のユーザー プロファイルを更新するようには設計されていません。各ユーザー プロファイルに出力レポートをコピーするためには、スキャンの第 1 段階部分のスクリプトにコードを追加する必要がありますが、これは難しくはありません。このサンプルを実行する前に、使用されているコマンド ライン オプションを確認し、これらの機能を製品文書で調べてください。スキャンに費やされる時間を削減するために、サンプルは MBSA により実行されるチェックをセキュリティ更新の適用状況のみに制限します。また、SUS 1.0 を使用しており、承認されない更新 (SUS サーバーの管理者により承認されない更新) について結果を表示しない必要がある場合、/sus オプションを使用して下さい。

**ScanDemo.bat**: スキャンの第 1 段階を実行し、スキャン結果を後で表示できるよう、結果をユーザー プロファイルにコピーします。
        ```
**ViewingDemo.bat**: ローカル管理者ではないユーザーがスキャン結果レポートを表示します。(この操作が容易に行えるよう、ユーザーにデスクトップ ショートカットを与えることを検討して下さい。)
        ```
![](images/Dd277363.mbsasc01(ja-jp,TechNet.10).jpg)
[](#mainsection)[ページのトップへ](#mainsection)

### サンプル \#2

このサンプルは、入力ファイルから、無制限の数のコンピュータまたは IP アドレスをスキャンする方法を示しています。メモ帳でファイルを作成し、そのファイルにホストまたは IP アドレスを必要なだけ入力して下さい。もちろん、SMS または LDAP クエリを使用して、それぞれ SMS コレクションまたは AD コンテナからデータを取得し txt ファイルを作成することも可能です。UNICODE でエンコードされた txt ファイルを使用するようになっているか、BatchScan.js を必ず確認して下さい。この理由は、エディタや他のツールを使用して作成された出力ストリームのエンコードに基づいてサンプルに変更を加える必要がでる場合があるためです。

**BatchScanDemo.bat**:
        ```
[](#mainsection)[ページのトップへ](#mainsection)

### サンプル \#3

このサンプルは一連のサンプルの中でも重要なものです。その理由は、このサンプルはレポート機能を提供し、サンプル \#2 からの結果を応用し、無制限の数の報告を提供することができるためです。コマンド ラインでチェック ID またはセキュリティ情報 ID を指定することにより、スクリプトで特定のアイテムを検索することができます。完了後、結果の xml ファイルをブラウザで開くと、特定のコンピュータを表示するための "&gt;&gt;" および "&lt;&lt;" ボタンがあることがわかります。最後に Excel で XML データ ソースを作成し、それを使用してピボットグラフを作成します。次に Excel を使用して結果の円グラフを生成することができます。これらの例に示されているように、/nologo コマンド ライン パラメータを必ず使用してください。

IE-Rollup.XML および Patch-Rollup.XML というサンプル ファイルが提供されています。これにより、自分でレポートを作成したり、ロールアップの実行を待たくなくても、動作を確認することが可能です。単にブラウザで開いて下さい。(Rollup.xslt が同じフォルダに存在することを確認して下さい。)

**SingleCheckRollupDemo.bat**:
        ```
**SinglePatchRollupDemo.bat**:
        ```
**MultiCheckRollupDemo.bat**: 容易に使用できるように、すべてのチェック ID を単一のコマンド ラインで提供します。
        ```
![](images/Dd277363.mbsasc02(ja-jp,TechNet.10).jpg)
**MultiPatchRollupDemo.bat**: 容易に使用できるよう、セキュリティ情報 ID を単一のコマンド ラインで指定します。これらは最大深刻度「緊急」のセキュリティ情報のみです。そのほかのセキュリティ情報は含まれていません。
        ```
![](images/Dd277363.mbsasc03(ja-jp,TechNet.10).gif)
**GroupIDRollupDemo.bat**: グループ レベルのチェック ID を使用する方法および「MDAC のセキュリティ更新」などのグループの結果を要約する方法をです。
        ```
![](images/Dd277363.mbsasc04(ja-jp,TechNet.10).jpg)
**注** **:** サンプル \#3 を使用する場合、次の問題が起こる可能性があることに注意する必要があります。

1.  SecurityScans フォルダに特定のコンピュータのレポートが複数含まれている場合、そのコンピュータの古いレポートは概要データに含まれます。このため、新しいスキャンを開始する時は、すべてのレポートをアーカイブ場所に移動することが最も好ましいでしょう。こうすることにより、スキャンされる各コンピュータのスキャン結果レポートは最新のものが 1 つ存在することになります。

2.  特定のセキュリティ情報またはチェックがロール アップされる場合、アイテムが 1 台または複数のコンピュータの結果レポートに存在しない可能性もあります。アイテムがコンピュータに存在しない場合、そのチェックを「パスした」と考えられます。たとえば、2004 年1 月に作成されたレポートのセットで MS04-004 を検索すると、MS04-004 チェックをパスしたすべてのコンピュータが示されます。問題は MS04-004 が 2004 年 2 月までリリースされなかったことです。このため、スキャンが実行された時、この脆弱性はスキャンされませんでした。ロール アップしているレポートのセットが、対象となるセキュリティ情報を含んでいるとされている更新カタログ (MSSecure.XML) のバージョンに基づいていることを確認して下さい。

3.  ロールアップ プロセスは完了するまでにしばらくかかります! これらのサンプルに精通したら、最初は少数のレポートを使用し、コンピュータでのスキャンおよびロールアップに要する時間の感覚をつかんで下さい。また、コマンド ラインにロール アップに含めるアイテムが多いほど、ロールアップに時間を要します。

[](#mainsection)[ページのトップへ](#mainsection)

### 有効なチェック ID

サンプル \#3 を使用する場合、有効なチェック ID の値はこの表に示す通りです。このサンプルは、結果の XML 出力の名前を自動的に抽出しますが、ID はロールアップに必要な特定のチェックを指定するために使用される必要があります。

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >チェック ID</th>
<th style="border:1px solid black;" >チェック名</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">101</td>
<td style="border:1px solid black;">Windows のバージョン</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">102</td>
<td style="border:1px solid black;">ファイル システム</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">104</td>
<td style="border:1px solid black;">ローカル アカウントのパスワードのテスト</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">106</td>
<td style="border:1px solid black;">パスワードの有効期限</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">107</td>
<td style="border:1px solid black;">Guest アカウント</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">110</td>
<td style="border:1px solid black;">自動ログオン</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">115</td>
<td style="border:1px solid black;">Windows のセキュリティの更新</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">117</td>
<td style="border:1px solid black;">匿名ユーザーの制限</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">118</td>
<td style="border:1px solid black;">IE のゾーン</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">119</td>
<td style="border:1px solid black;">監査</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">121</td>
<td style="border:1px solid black;">共有</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">122</td>
<td style="border:1px solid black;">管理者アカウント</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">123</td>
<td style="border:1px solid black;">サービス</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">124</td>
<td style="border:1px solid black;">マクロのセキュリティ</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">126</td>
<td style="border:1px solid black;">Windows Media Player のセキュリティの更新</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">127</td>
<td style="border:1px solid black;">Exchange Server のセキュリティの更新</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">174</td>
<td style="border:1px solid black;">Office のセキュリティの更新</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">176</td>
<td style="border:1px solid black;">管理者グループ用の IE セキュリティ強化の構成</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">177</td>
<td style="border:1px solid black;">管理者グループ以外用の IE のセキュリティ強化の構成</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">178</td>
<td style="border:1px solid black;">インターネット接続ファイアウォール</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">179</td>
<td style="border:1px solid black;">自動更新</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">201</td>
<td style="border:1px solid black;">ドメイン コントローラの IIS のテスト</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">203</td>
<td style="border:1px solid black;">SQL Server/MSDE のセキュリティ モデル</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">204</td>
<td style="border:1px solid black;">Sysadmin ロール メンバ</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">205</td>
<td style="border:1px solid black;">公開された SQL Server/MSDE のパスワード</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">206</td>
<td style="border:1px solid black;">SQL の Guest アカウント</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">207</td>
<td style="border:1px solid black;">CmdExec ロール</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">212</td>
<td style="border:1px solid black;">SQL Server/MSDE のセキュリティの更新</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">213</td>
<td style="border:1px solid black;">レジストリのアクセス権</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">215</td>
<td style="border:1px solid black;">Sysadmins</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">216</td>
<td style="border:1px solid black;">フォルダのアクセス権</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">217</td>
<td style="border:1px solid black;">SQL Server/MSDE のアカウント パスワードのテスト</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">218</td>
<td style="border:1px solid black;">サービス アカウント</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">219</td>
<td style="border:1px solid black;">SQL Server/MSDE の状態</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">301</td>
<td style="border:1px solid black;">ドメイン コントローラの SQL のテスト</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">302</td>
<td style="border:1px solid black;">IIS のセキュリティの更新</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">307</td>
<td style="border:1px solid black;">IIS ログの有効化</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">308</td>
<td style="border:1px solid black;">サンプル アプリケーション</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">309</td>
<td style="border:1px solid black;">IISAdmin の仮想ディレクトリ</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">311</td>
<td style="border:1px solid black;">IIS 親パス</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">314</td>
<td style="border:1px solid black;">IIS の状態</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">315</td>
<td style="border:1px solid black;">IIS Lockdown ツール</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">316</td>
<td style="border:1px solid black;">MSADC と Scripts の仮想ディレクトリ</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">415</td>
<td style="border:1px solid black;">MDAC のセキュリティの更新</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">416</td>
<td style="border:1px solid black;">Commerce Server のセキュリティの更新</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">417</td>
<td style="border:1px solid black;">MSXML のセキュリティの更新</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">418</td>
<td style="border:1px solid black;">Microsoft VM のセキュリティの更新</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">419</td>
<td style="border:1px solid black;">BizTalk Server のセキュリティの更新</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">420</td>
<td style="border:1px solid black;">Content Management Server Site Builder のセキュリティの更新</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">421</td>
<td style="border:1px solid black;">Content Management Server のセキュリティの更新</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">422</td>
<td style="border:1px solid black;">Host Integration Server のセキュリティの更新</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">423</td>
<td style="border:1px solid black;">Content Management Server Site Stager のセキュリティの更新</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
