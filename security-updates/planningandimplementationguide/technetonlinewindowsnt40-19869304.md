---
TOCTitle: 'TechNet Online - 既存の Windows NT 4.0 システムのセキュリティ保護'
Title: 'TechNet Online - 既存の Windows NT 4.0 システムのセキュリティ保護'
ms:assetid: '47759eb9-0cfd-4cc0-9eaa-1cf80171a38c'
ms:contentKeyID: 19869304
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277355(v=TechNet.10)'
---

TechNet Online - 既存の Windows NT 4.0 システムのセキュリティ保護
=================================================================

このガイドの趣旨として、既存のインストール環境が汚染されていないことを前提としています。システムが汚染されている場合は、以下の基本ステップを開始する前に、システムを修正するための推奨事項に従う必要があります。ご使用のシステムまたはネットワークが攻撃にさらされているかどうかを調べる詳細な方法については、[ここ](http://www.microsoft.com/japan/technet/security/tools/detect.mspx)をクリックしてください。ここで参照する他のドキュメントやアップデートは、このキットの[目次](http://www.microsoft.com/japan/technet/security/tools/default.mspx)にあります。

このガイドの情報は、次の製品に適用されます。

-   Microsoft Windows NT 4.0 Enterprise Edition

-   Microsoft Windows NT Workstation 4.0

-   Microsoft Windows NT Server 4.0

**ステップ** **1:** **現状を判断する**

既存のインストール環境の現状を判断するのは容易でないことが少なくありません。個別の修正プログラムが適用されていることを確認した上で、どのサービスが動作しているかを把握する必要があります。

-   Web サーバーは特にセキュリティ攻撃を受けやすいため、システムが Web サーバーとして用いられていない場合は、Internet Information Server (IIS) を無効または削除してください。

-   システム上で動作しているアプリケーションと Service Pack を特定することが重要です。マイクロソフトは、オペレーティング システム、Internet Explorer、IIS 上で実行している Service Pack のレベルを特定することを特に推奨します。

-   [Hfnetchk ツール](http://www.microsoft.com/japan/technet/security/tools/hfnetchk.mspx)を用いて、現在どのようなセキュリティ修正プログラムがインストールされているかを確認してください。

**ステップ** **2:** **システムをセキュリティ保護する**

オペレーティング システムが起動したら、次にセキュリティを強化します。システムの状況 (ステップ 1 で判断) によっては、次のステップの内いくつかを省略できる場合があります。

1.  [Windows NT 4.0 Service Pack 6a](http://www.microsoft.com/japan/ntserver/downloads/sp6a.mspx) をインストールします。

    Windows NT 4.0 への Service Pack のインストールに関する情報は、[Windows NT 4.0 SP6a Readme ファイル](http://www.microsoft.com/japan/ntserver/downloads/readme.htm)と「[Windows NT 4.0 SP6a を Systems Management Server 1.2 および 2.0 とともに展開する方法](http://support.microsoft.com/kb/238315)」に記載されています。

2.  Internet Explorer Web ブラウザをセキュリティ保護するには、次の 2 つの選択肢があります。

    -   新バージョンの Web ブラウザである Internet Explorer 5.5 でサポートされる追加機能を利用したい場合は、[Internet Explorer 5.5 SP2](http://www.microsoft.com/windows/ie_intl/ja/download/ie55sp2/default.mspx) をインストールする。

        または

    -   新バージョンの Web ブラウザである Internet Explorer 6 またはそれ以降でサポートされる追加機能を利用したい場合は、[Internet Explorer 6](http://www.microsoft.com/japan/ie/downloads/ie6/) をインストールする (推奨)。

        **注:** Internet Explorer 6 をインストールした場合、一部の Web サイトなどで期待された機能が動かないことが確認されています。
        また、Internet Explorer 6 をインストールする際は、Outlook Express を含む 「標準構成」以上でインストールしてください。

3.  IIS がインストールされて動作している場合、または将来それを使用する予定がある場合は、[Windows NT 4.0 Server Option Pack](http://www.microsoft.com/japan/products/ntserver/option_pack/download.htm) または [Windows NT Workstation 4.0 Option Pack](http://technet.microsoft.com/ja-jp/library/cc767904.aspx) (英語情報) のいずれかをインストールします。Option Pack をインストールすることで、IIS のバージョンが 4.0 にアップグレードされます。

    **警告:** IIS Lockdown Wizard ツールを使用する場合、Option Pack の一部である Microsoft Index Server をインストールする必要があります。

    **警告:** Service Pack 4.0 またはそれ以降で Option Pack がテストされていないという警告メッセージは無視してください。

4.  [Windows NT 4.0 Service Pack 6a](http://www.microsoft.com/japan/ntserver/downloads/sp6a.mspx)を再適用して、Windows NT 4.0 Option Pack によってインストールされるファイルをアップデートします。

5.  [Windows NT 4.0 セキュリティ ロールアップ パッケージ](http://www.microsoft.com/japan/technet/archive/security/news/nt4srp.mspx)をインストールします。この作業は、Service Pack 6a の後に行う必要があります。

6.  Windows NT 4.0 セキュリティ ロールアップ パッケージをインストールした後に、[305929](http://support.microsoft.com/kb/305929) の「この証明書には無効なデジタル署名があります」のエラーに対する修正プログラムをインストールします。

7.  [IIS 用の累積的な修正プログラム](http://www.microsoft.com/japan/technet/security/bulletin/ms01-044.mspx)に含まれるサービスを有効にしたい場合は、これをインストールします。

    **注:** オフラインでオペレーティング システムをインストールし、IIS が動作している場合、このステップが完了するまでネットワークに接続しないでください。

**ステップ** **3:** **継続してセキュリティ保護する**

システムのセキュリティ保護を維持するためには、ご使用のインストール環境に該当する次のチェックリストに従う必要があります。

-   [Microsoft Internet Information Server 4 ベースライン セキュリティ チェックリスト](http://www.microsoft.com/japan/technet/archive/security/chklist/iis4cl.mspx)

-   [Microsoft Windows NT Server 4.0 ベースライン セキュリティ チェックリスト](http://www.microsoft.com/japan/technet/archive/security/chklist/nt4svrcl.mspx)

-   [Microsoft Windows NT Workstation 4.0 ベースライン セキュリティ チェックリスト](http://www.microsoft.com/japan/technet/archive/security/chklist/nt4wscl.mspx)

**ステップ** **4: Internet Information Server** **をセキュリティ保護する**

この時点では、既にセキュリティ修正プログラムがインストールされ、良好なベースのシステムが整っています。Web サーバーは特にセキュリティ攻撃を受けやすいため、マイクロソフトはこれに対抗するいくつかのツールを提供しています。このシステム上で IIS を稼動させる場合は、このステップに従ってください。

-   [**URLScan** **セキュリティツール**](http://www.microsoft.com/japan/technet/security/tools/urlscan.mspx)**を実行します**
    URLScan は、IIS Web サーバーに到達するすべてのリクエストを選別し、管理者が作成したルールセットに適合するリクエストに対してのみ通過を許可します。これによって、適正なリクエストだけに応答することが保証されるため、サーバーのセキュリティが大幅に向上します。このツールを用いることで、管理者は長さ、文字セット、内容、およびその他の要素に基づいてリクエストをフィルタリングすることができます。既定のルールセットが用意されていますが、個々のサーバーのニーズを満たすようカスタマイズすることも可能です。

-   [**IIS Lockdown Wizard** **ツール**](http://www.microsoft.com/japan/technet/security/tools/locktool.mspx)**を実行します**
    **警告:** IIS Lockdown Wizard ツールには Microsoft Index Server が必要です。このツールを使用する場合、Option Pack から Index Server をインストールする必要があります。

    このツールを用いると、IIS 4.0 または 5.0 Web サーバーが安全に動作するよ構成することができます。このツールには 2 つのモードがあります。最も基本的な Web サーバーに適したエクスプレス モード、そしてサーバーがサポートするテクノロジを管理者が選択できるアドバンスト モードです。このツールには、最後に行われたロックダウンの結果に戻すことができるアンドゥー機能が備わっています。

**ステップ** **5:** **継続的な保守プログラム**

これまでのステップを通じて、セキュリティ保護されたベースのシステムがインストールされたことになりますが、新しい形態の攻撃に対しては脆弱になりかねません。そこで継続的な保守が必要となります。

-   [Hfnetchk ツール](http://www.microsoft.com/japan/technet/security/tools/hfnetchk.mspx)を用いて、Windows NT 4.0 オペレーティング システムの他、Internet Information Services 4.0 (IIS)、SQL Server 7.0、SQL Server 2000 (Microsoft Data Engine \[MSDE\] を含む)、および Internet Explorer 5.01 またはそれ以降に対して、どのセキュリティ修正が適用さているかを確認します。

    上述のセキュリティ保護されたベースのシステムをインストールした後に Hfnetchk ツールを実行すると、多くのセキュリティ修正がインストールされていないことが Hfnetchk ツールによって示されます。これは、正しく、また予想される結果です。このドキュメントはシステムセットアップの起点となるべきベース部分のみを提供しています。すべての重要なセキュリティ修正プログラムを確実にインストールすることを推奨しています。

    推奨されるすべての修正プログラムが確実に適用されるまで、セキュリティ保護の対象となるすべてのコンピュータに対して毎日このツールを実行してください。後に実行の頻度を少なくすることができます。新しいセキュリティ修正プログラムをインストールしたら、このツールを継続して実行し、欠如しているセキュリティ修正プログラムの確認と検出を行ってください。

-   [マイクロソフト セキュリティ通知サービス](http://www.microsoft.com/japan/technet/security/bulletin/notify.mspx)に加入してください。これは、マイクロソフト製品のセキュリティに関する情報を加入者へ通知するための無料の電子メール通知サービスです。

    [Windows Update Web サイト](http://windowsupdate.microsoft.com/)にアクセスして、最新の推奨および重要アップデートをチェックしてください。

-   新しいセキュリティ修正が利用可能になったら、それを適用することが重要です。マイクロソフトは、複数の修正プログラムをインストールするたびに必要となるコンピュータの再起動を 1 度だけに留めるために、修正プログラムを相互に結びつけるコマンド ライン ツール [QChain.exe](http://support.microsoft.com/kb/296861) を開発しました。

[](#mainsection)[ページのトップへ](#mainsection)
