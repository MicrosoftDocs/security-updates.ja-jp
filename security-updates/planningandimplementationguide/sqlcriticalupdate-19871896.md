---
TOCTitle: SQL Critical Update
Title: SQL Critical Update
ms:assetid: '8e036289-2cbb-4d14-96d9-82c5024e5f93'
ms:contentKeyID: 19871896
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362951(v=TechNet.10)'
---

SQL Critical Update
===================

**概要**

SQL Critical Update は、実行されているコンピュータで Slammer ワームの影響を受ける SQL Server 2000 および MSDE 2000 のインスタンスをスキャンし、影響を受けるファイルを更新します。SQL Critical Update は Windows 98、Windows ME、Windows NT 4.0、Windows 2000、および Windows XP を実行するコンピュータで動作します。

Service Pack 2 (SP2) および [MS02-039](http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx)、[MS02-043](http://www.microsoft.com/japan/technet/security/bulletin/ms02-043.mspx)、[MS02-056](http://www.microsoft.com/japan/technet/security/bulletin/ms02-056.mspx) または [MS02-061](http://www.microsoft.com/japan/technet/security/bulletin/ms02-061.mspx) で提供された修正プログラムを適用した SQL Server 2000 のインスタンス、Service Pack 3 以降のインスタンスは Slammer ワームの影響を受けません。SQL Server 7.0 以前を実行しているコンピュータもまた影響を受けません。

-   SQL Critical Update はローカル マシンで実行する必要があります。

**制限 :**

-   SQL Critical Update はローカル コンピュータで実行する必要があります。

-   SQL Critical Update は、確認した脆弱性を常に修正します。単に SQL Server のインスタンスを無効にするための使用はできません。

-   SQL Critical Update は SP3 をインストールしません。 脆弱である可能性のあるファイルをアップデートするだけです。

-   SQL Critical Update は、実行している SQL Critical Update の言語と同じ言語の MSDE インストールだけを修正します。

-   SQL Critical Update を実行するユーザーは、Program Files ディレクトリ内の SQL Server ファイルを置き換える権限を持っている必要があります。

-   SQL Critical Update は、修正される SQL Server のインスタンスごとに ssnetlib.dll ファイルが存在する場合のみ機能します。

**システム要件**

-   オペレーティングシステム： Windows 98, Windows ME, Windows NT 4.0, Windows 2000, Windows XP
    SQL Server 2000 評価版, クラスタ構成をご利用のお客様も適用可能です。

上記のシステムのいずれか。

**使用方法**

説明については、下記のダウンロードのページより readme.txt ファイルをご覧下さい。

**ダウンロード**

構成される各ファイルは [こちら](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9552d43b-04eb-4af9-9e24-6cde4d933600) のページからダウンロードできます。

[](#mainsection)[ページのトップへ](#mainsection)
