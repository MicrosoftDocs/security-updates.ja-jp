---
TOCTitle: ISA Server Feature Pack
Title: ISA Server Feature Pack
ms:assetid: '5eef6503-3abe-44d2-be96-10ccae23dcbb'
ms:contentKeyID: 19869287
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc750577(v=TechNet.10)'
---

ISA Server Feature Pack
=======================

最終更新日: 2003年7月7日

**Microsoft Internet Security and Acceleration (ISA) Server 2000 Feature Pack 1** は、電子メール サーバー、Web サーバー、および Microsoft Exchange Outlook Web Access (OWA) サーバーの展開に高度なセキュリティと使いやすさを提供する機能とドキュメントのセットです。電子メール サーバーのセキュリティが向上し、不要な電子メール メッセージを排除できるようになりました。リモート Outlook ユーザーは、VPN を使用しなくても、信頼されていないネットワークを経由して Exchange Server メールへ安全にアクセスできます。インターネット攻撃の多様化に応じて ISA Server の認証機能と保護機能が強化されたので、Web および OWA サーバー コンピュータをより安全に保護することができます。新しいウィザードでは、構成を簡単に行うことができ、一般的な質問に答えます。 ISA Server Feature Pack 1 と共にインストールされるオンライン ヘルプに加え、このパッケージに含まれているドキュメントでは、この Feature Pack によって可能になった新しいシナリオの構成方法が詳しく説明されています。

ISA Server Feature Pack 1 には、これらのサーバーの公開手順を示したさまざまなドキュメントも含まれています (このページの一覧を参照)。

[ISA Server Feature Pack 1](http://www.microsoft.com/japan/isaserver/) の Web サイトへ定期的にアクセスして、最新のアップデートと詳細情報を確認してください。

##### トピック

[](#ecaa)[Web 公開](#ecaa)

[](#ebaa)[Exchange の公開](#ebaa)

[](#eaaa)[参照情報](#eaaa)

### Web 公開

Web 公開では、ローカル ネットワーク上の Web サーバーを安全に公開することができます。簡単に構成できる Web 公開ルールでは、内部 Web サーバーの HTTP オブジェクトを外部から要求されたとき、ISA Server がその要求をどのように受信し、Web サーバーに代わってどのように応答するかを指定します。基本的に Web 公開ルールは、外部から送られてきた要求を、ISA Server コンピュータの背後に配置された適切な Web サーバーにマップします。

[](#mainsection)[ページのトップへ](#mainsection)

### Exchange の公開

ISA Server を使用して Exchange を公開すれば、内部ネットワーク上の Exchange Server コンピュータへのアクセスを安全かつ簡単に構成できます。ISA Server を使用した場合、ISA Server コンピュータの背後に Exchange Server を安全に配置し、この電子メール サーバーをインターネットに公開するためのサーバー公開ルールを作成できます。Exchange Server 宛ての電子メールは実際には ISA Server コンピュータが受信しますが、クライアントからは電子メール サーバーが受け取ったように見えます。ISA Server は、トラフィックをフィルタ処理して Exchange Server に転送します。Exchange Server が外部ユーザーに直接公開されることはありません。Exchange Server は、他の内部ネットワーク サービスへのアクセスを維持したまま、セキュリティで保護された環境に置かれます。

[](#mainsection)[ページのトップへ](#mainsection)

### 参照情報

ISA Server Feature Pack 1 のドキュメントには、お客様のニーズや疑問に応えるため、目的ごとに印刷マニュアルが用意されています。よくある質問には、どのような種類のクライアントを展開するのか、ISA Server はどのようなときにユーザー要求を認証するのか、どのような場合にパケット フィルタを作成する必要があるのか、などがあります。

-   [Exchange 2000 Server の公開](https://technet.microsoft.com/ja-jp/library/c3ed9e14-fb54-4424-a017-07f7ee6d9d3b(v=TechNet.10))


-   [IP パケット フィルタの使用](https://technet.microsoft.com/ja-jp/library/822bd148-6689-470a-9baf-a0f8cb8010fe(v=TechNet.10))


-   [ISA Server および公開されているサーバーのデジタル証明書](https://technet.microsoft.com/ja-jp/library/444fd7e6-5b5e-44f0-a06e-edbafc33a82a(v=TechNet.10))


-   [ISA Server クライアントの種類](https://technet.microsoft.com/ja-jp/library/daaa0e95-338b-466c-8118-9d0fdb3ecbfb(v=TechNet.10))


-   [ISA Server で Exchange を公開する場合のトラブル シューティング](https://technet.microsoft.com/ja-jp/library/baba010d-9111-46f8-9f08-4f74afcdfc64(v=TechNet.10))


-   [ISA Server での Web 公開に関するトラブル シューティング](https://technet.microsoft.com/ja-jp/library/e43e2222-e4fb-4e37-a5b9-61a983d28674(v=TechNet.10))


-   [ISA サーバー上の Web サーバーの公開](https://technet.microsoft.com/ja-jp/library/bc59113d-fc75-4793-aec4-c635ab0ba2ad(v=TechNet.10))


-   [Microsoft ISA Server による MAPI クライアントと Exchange メールの接続](https://technet.microsoft.com/ja-jp/library/66d2bcdc-7451-423c-a5a8-357fa5f8916b(v=TechNet.10))


-   [Microsoft ISA Server を使用した POP および IMAP サービスの公開](https://technet.microsoft.com/ja-jp/library/ca60edf3-41dc-44e6-b877-a90800c59618(v=TechNet.10))


-   [Outlook Web Access サーバー公開のシナリオ](https://technet.microsoft.com/ja-jp/library/0dfd23ca-1fc3-4581-9c60-6fee28e901cc(v=TechNet.10))


-   [SMTP Filter を使用した SMTP トラフィックのフィルタ処理](https://technet.microsoft.com/ja-jp/library/a43231fa-a773-49ae-be97-d03857dd6f34(v=TechNet.10))


-   [SSL ブリッジとトンネリング](https://technet.microsoft.com/ja-jp/library/71e5fa4b-e4f0-4032-a459-447014ec5567(v=TechNet.10))


-   [Web サーバーを公開するときのリンク変換の使用](https://technet.microsoft.com/ja-jp/library/778bef2c-3e0f-4fc7-ad66-63d0b73900dd(v=TechNet.10))


-   [Web フィルタを使用した RSA SecurID の認証](https://technet.microsoft.com/ja-jp/library/58273446-6a00-4aae-8c69-eead60686e9e(v=TechNet.10))


-   [境界領域のネットワークでの Web サーバーの公開](https://technet.microsoft.com/ja-jp/library/3b975fb5-cdec-4389-9460-13fe6177c60d(v=TechNet.10))


-   [内部 Web サーバーの公開](https://technet.microsoft.com/ja-jp/library/ec702d50-f1a5-4c2a-b0b1-63d5bfbabab9(v=TechNet.10))


-   [並列境界領域のネットワークでの Web サーバーの公開](https://technet.microsoft.com/ja-jp/library/60a74e10-0ce6-44d6-b4b6-53a17588aa85(v=TechNet.10))

© 2002 Microsoft Corporation

[](#mainsection)[ページのトップへ](#mainsection)