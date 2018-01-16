---
TOCTitle: SQL Server 2000 SQL Check ツール
Title: SQL Server 2000 SQL Check ツール
ms:assetid: '72e62222-dc93-4010-bcb2-3e12c8970c90'
ms:contentKeyID: 19871895
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362950(v=TechNet.10)'
---

SQL Server 2000 SQL Check ツール
================================

**概要**

**注** **:** 本ツールは、英語版のみですが、日本語環境でもご使用いただけます。

SQL Check は、実行されているコンピュータで Slammer ワームの影響を受ける SQL Server 2000 および MSDE 2000 のインスタンスをスキャンします。SQL Check は Windows 98、Windows ME、Windows NT 4.0、Windows 2000 および Windows XP を実行しているコンピュータで動作します。Windows NT 4.0、Windows 2000 および Windows XP を実行しているコンピュータで、SQL Check は SQL Server および SQL エージェント サービスを停止、無効にします。Windows 98 および Windows ME を実行しているコンピュータでは、影響を受けるインスタンスを検知しますが、サービスを停止または無効にはしません。

Service Pack 2 (SP2) および [MS02-039](http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx)、[MS02-043](http://www.microsoft.com/japan/technet/security/bulletin/ms02-043.mspx)、[MS02-056](http://www.microsoft.com/japan/technet/security/bulletin/ms02-056.mspx) または [MS02-061](http://www.microsoft.com/japan/technet/security/bulletin/ms02-061.mspx) で提供された修正プログラムを適用した SQL Server 2000 のインスタンス、Service Pack 3 以降のインスタンスは Slammer ワームの影響を受けません。SQL Server 7.0 以前を実行しているコンピュータもまた影響を受けません。

**注** **:** マイクロソフト セキュリティ情報 [MS02-039](http://www.microsoft.com/japan/technet/security/bulletin/ms02-039.mspx) で提供された修正プログラムがインストールされている場合、SQL Scan および SQL Check は、マイクロソフト セキュリティ情報 [MS02-061](http://www.microsoft.com/japan/technet/security/bulletin/ms02-061.mspx) で提供された修正プログラムがインストールされていないと、Slammer ワーム の影響を受けるかどうかを正しく報告しません。Slammer ワーム に対する保護に必要なセキュリティ修正プログラムがインストールされているかどうか分からない場合、\\MSSQL\\BINN フォルダの ssnetlib.dll ファイルのファイル バージョンをチェックし、そのバージョンが 2000.80.636.0 以上であることを確認して下さい。しかし、マイクロソフトは MS02-061 で説明されたセキュリティ修正プログラムを適用することを強く推奨します。この理由は、マイクロソフト セキュリティ情報 MS02-061 で説明されたそのほかの修正を含むためです。これらのツールの次のリリースはこのシナリオをさらに正確に説明するメッセージを返します。

**システム要件**

-   検索対象のオペレーティングシステム： Windows 98, Windows Me, Windows NT 4.0, Windows 2000, Windows XP

上記のシステムのいずれか。

**使用方法**

説明については、下記のダウンロードのページより readme.txt ファイルをご覧下さい。

**ダウンロード**

構成される各ファイルは [こちら](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=9552d43b-04eb-4af9-9e24-6cde4d933600) のページからダウンロードできます。

[](#mainsection)[ページのトップへ](#mainsection)
