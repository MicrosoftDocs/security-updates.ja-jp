---
TOCTitle: SQL Server 2000 SQL Check ツール
Title: SQL Server 2000 SQL Check ツール
ms:assetid: 'a508ea10-a903-4bf6-a57b-e376604b0f14'
ms:contentKeyID: 19871898
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362953(v=TechNet.10)'
---

SQL Server 2000 SQL Check ツール
================================

**概要**

**注** **:** 本ツールは、英語版のみですが、日本語環境でもご使用いただけます。

SQL Scan (Sqlscan.exe) は、Windows NT 4.0、Windows 2000、Windows XP 上で動作する Microsoft SQL Server 2000 および SQL Server 2000 Desktop Engine (MSDE 2000) のインスタンスを検索し、Slammer ワームの影響を受ける可能性のある SQL Server のインスタンスを検知します。SQL Scan は個々のコンピュータ、Windows ドメインまたは特定の IP アドレスの範囲をスキャンします。

Service Pack 2 (SP2) および [MS02-039](http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx)、[MS02-043](http://www.microsoft.com/japan/technet/security/bulletin/ms02-043.mspx)、[MS02-056](http://www.microsoft.com/japan/technet/security/bulletin/ms02-056.mspx) または [MS02-061](http://www.microsoft.com/japan/technet/security/bulletin/ms02-061.mspx) で提供された修正プログラムを適用した SQL Server 2000 のインスタンス、Service Pack 3 以降のインスタンスは Slammer ワームの影響を受けません。SQL Server 7.0 以前を実行しているコンピュータもまた影響を受けません。

**注** **:** SQL Scan は、Windows 2000 以降のオペレーティングシステムで動作します。

**注** **:** 感染した SQL Server インスタンスのシャットダウンは成功しない場合があります。プロセスを終了するために、システム管理ツールの使用が必要な場合もあります。

SQL Scan は Windows 98 または Windows ME で実行されている SQL Server のインスタンスを検索しません。さらに、SQL Scan はコマンド プロンプトから起動された SQL Server のインスタンスを検出しません。

SQL Scan は、ネットワークの SQL Server 2000 および SQL Server 2000 Desktop Edition (MSDE 2000) のすべてのインスタンスを列挙します。SQL Scan 実行時には、次の項目の 1 つを指定する必要がります。

1.  ドメイン

2.  IP アドレスの範囲

3.  単一コンピュータ名

SQL Scan をリモート コンピュータを対象として使用する場合、ユーザーはドメイン管理者であることが必要です。または、そのローカル コンピュータの管理者であることが必要です。

SQL Scan は ssnetlib.dll または sqlserver.exe ファイルのいずれかの名前が変更されている場合、正確な結果を返しません。これらのファイルを元の名前に戻す必要があります。

SQL Scan はクラスタ化されたコンピュータではサポートされません。SQL インスタンスを無効にする、およびシャット ダウンするためには、これらのコンピュータで手動で行う必要があります。

**システム要件**

-   検索対象のオペレーティングシステム： Windows NT 4.0, Windows 2000, Windows XP

上記のシステムのいずれか。

**ダウンロード**

構成される各ファイルは [こちら](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9552d43b-04eb-4af9-9e24-6cde4d933600) のページからダウンロードできます。

[](#mainsection)[ページのトップへ](#mainsection)
