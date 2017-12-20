---
TOCTitle: Service Pack 2 の新機能
Title: Service Pack 2 の新機能
ms:assetid: 'a944cb73-d900-42bb-b7aa-92916dead408'
ms:contentKeyID: 18122289
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747629(v=WS.10)'
---

Service Pack 2 の新機能
=======================

Rights Management サービス (RMS) Service Pack 2 (SP2) では、次の機能がサポートされます。

-   **Microsoft® SQL Server™ 2005 のネイティブ サポート**。以前のリリースの RMS では、SQL Server 2005 で RMS を使用するには対応策が必要でした。この対応策の詳細については、Microsoft サポート技術情報の記事 913372 ([http://go.microsoft.com/fwlink/?LinkId=68638](http://go.microsoft.com/fwlink/?linkid=68638)) を参照してください。RMS SP2 ではこの問題は修正されています。
-   **Microsoft Office SharePoint® Server 2007**。今回のリリースでは、Office SharePoint Server 2007 がサポートされています。Office SharePoint Server 2007 ドキュメント ライブラリは、Office SharePoint Server 2007 権限に基づいて、ドキュメントにダウンロード時のアクセス許可を自動的に適用します。これは、Office SharePoint Server 2007 サーバーに RMS SP2 クライアントをインストールすることで可能になります。RMS SP2 サーバーと Office SharePoint Server 2007 を同一のコンピュータにインストールすることはお勧めしません。
-   **ログ データベースに書き込まれるメッセージのセキュリティの向上**。今回のリリースでは、RMS サーバーから RMS ログ データベースへのメッセージ キュー メッセージがデジタル署名されます。
-   **サーバーのバッチ サイズの拡大**。今回のリリースでは、RMS 対応アプリケーションが、RMS サーバーに対する単一のライセンス要求から、複数の異なるユーザー アカウントの複数の使用ライセンスを取得できるようになりました。権利保護された同一のコンテンツに対して複数のライセンス要求を実行することによるオーバーヘッドが削減され、パフォーマンスが向上します。
-   **フォレストにまたがるグループの拡張の強化**。今回のリリースでは、複数のフォレストにまたがる RMS グループ拡張の手段として、RMS サーバー上で実行される新しい ASP.NET Web サービスに対する簡易オブジェクト アクセス プロトコル (SOAP) 要求が使用されます。
