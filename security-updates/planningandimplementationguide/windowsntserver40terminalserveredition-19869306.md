---
TOCTitle: '既存の Windows NT® Server 4.0, Terminal Server Edition システムへのセキュリティ保護'
Title: '既存の Windows NT® Server 4.0, Terminal Server Edition システムへのセキュリティ保護'
ms:assetid: 'f166a629-056e-469a-ab2d-67788d2cf2ee'
ms:contentKeyID: 19869306
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277357(v=TechNet.10)'
---

既存の Windows NT® Server 4.0, Terminal Server Edition システムへのセキュリティ保護
===================================================================================

このガイドの趣旨として、インストールを行う対象となる環境が外部の攻撃にさらされておらず、攻撃が成功していないことを前提としています。システムが汚染されている場合は、以下の基本ステップを開始する前に、システムを修正するための推奨事項に従う必要があります。ご使用のシステムまたはネットワークが攻撃にさらされているかどうかを調べる詳細な方法については、[ここ](http://www.microsoft.com/japan/technet/security/tools/detect.mspx)をクリックしてください。ここで参照する他のドキュメントやアップデートは、このキットの[目次](http://www.microsoft.com/japan/technet/security/tools/default.mspx)セクションにあります。

**ステップ 1: 現状を判断する**

既存インストール環境の現状を判断するのは容易でないことが少なくありません。個別のパッチが適用されていることを承知した上で、どのサービスが動作しているかを把握する必要があります。

Windows NT Server 4.0, Terminal Server Edition は セキュリティ上の観点からも、Web サービスとは独立して運用されるべきです。Internet Information Server (IIS) 3.0 はセキュリティ攻撃に対して脆弱であるため、Windows NT Server 4.0, Terminal Server Edition ではインストールしないことをお勧めします。また、Windows NT Server 4.0, Terminal Server Edition は IIS 4.0 をサポートしておりません。

-   システム上で動作しているアプリケーョンと Service Pack を特定することが重要です。マイクロソフトは、オペレーティング システムと Internet Explorer 上で実行している Service Pack のレベルを特定することを特に推奨します。

**ステップ 2: システムをセキュリティ保護する**

オペレーティング システムが起動する前に、ネットワークから隔離された状態にあることを確認します。これは、オペレーティング　システムが無防備な状態でネットワーク上に接続されることを避けるためです。オペレーティング システムが起動したら、次にセキュリティを強化します。システムの状況 (ステップ1で判断) によっては、次のステップの内いくつかを省略できる場合があります。

1.  [Windows NT Server 4.0, Terminal Server Edition Service Pack 6](http://www.microsoft.com/japan/technet/downloads/winnt.mspx) をインストールします。

    Windows NT 4.0 への Service Pack のインストールに関する情報は、[Windows NT Server 4.0, Terminal Server Edition SP6 Readme ファイル](http://support.microsoft.com/kb/416131)と「[Windows NT 4.0 SP6a を Systems Management Server 1.2 および 2.0 とともに展開する方法](http://support.microsoft.com/kb/238315)」に記載されています。

2.  Internet Explorer Web ブラウザをセキュリティ保護するには、次のいくつかの選択肢があります。

    -   セキュリティ ベースラインの最低条件を満たすため Internet Explorer 5.01 SP2 をインストールする。

        または

    -   新バージョンの Web ブラウザである Internet Explorer 5.5 でサポートされる追加機能を利用したい場合は、[Internet Explorer 5.5 SP2](http://www.microsoft.com/windows/ie_intl/ja/download/ie55sp2/default.mspx) をインストールする。

        または

    -   新バージョンの Web ブラウザである Internet Explorer 6 またはそれ以降でサポートされる追加機能を利用したい場合は、[Internet Explorer 6](http://www.microsoft.com/japan/ie/downloads/ie6/) をインストールする (推奨)。

        **注:** Internet Explorer 6 をインストールした場合、一部の Web サイトなどで期待された機能が動かないことが確認されています。
        また、Internet Explorer 6 をインストールする際は、Outlook Express を含む 「標準構成」以上でインストールしてください。

3.  以下に挙げる Service Pack 6 以降の重要なセキュリティ修正プログラムをインストールします。マイクロソフトは、複数の修正プログラムをインストールするたびに必要となるコンピュータの再起動を 1 度だけに留めるために、修正プログラムを相互に結びつけるコマンド ライン ツール [Qchain.exe](http://support.microsoft.com/kb/296861) を開発しました。

    -   [MS01-008](http://www.microsoft.com/japan/technet/security/bulletin/ms01-008.mspx) 修正プログラム - 間違った形式の NTLMSSP 要求がシステム特権でコードを実行させることが可能

    -   &gt;[MS00-095](http://www.microsoft.com/japan/technet/security/bulletin/ms00-095.mspx) 修正プログラム - 「レジストリ権限」の脆弱性に対処

    -   &gt;[MS00-070](http://www.microsoft.com/japan/technet/security/bulletin/ms00-070.mspx) 修正プログラム - 複数の LPC および LPC ポートの脆弱性に対処

    -   &gt;[MS00-052](http://www.microsoft.com/japan/technet/security/bulletin/ms00-052.mspx) 修正プログラム - 「相対的なシェル パス」の脆弱性に対処

**ステップ 3: 継続してセキュリティ保護する**

Terminal Server は、標準的な 1 台のサーバーには通常インストールされない多数のアプリケーションをホスティングできるよう設計されています。このため、個々のアプリケーションをセキュリティ保護するには、特別な注意を払う必要があります。

-   Microsoft Office アプリケーションのインストールと展開に関する情報については、[Microsoft Office Resource Kit Web サイト](http://www.microsoft.com/japan/office/ork/)をご覧ください。

-   マイクロソフト以外のアプリケーションのインストールとセキュリティ保護に関する情報については、各アプリケーションを参照してください。

-   システムのセキュリティ保護を維持するためには、ご使用のインストール環境に該当する次のチェックリストに従う必要があります。

    -   [Microsoft Windows NT Server 4.0 ベースライン セキュリティ チェックリスト](http://www.microsoft.com/japan/technet/archive/security/chklist/nt4svrcl.mspx)

    -   [Microsoft Windows NT Workstation 4.0 ベースライン セキュリティ チェックリスト](http://www.microsoft.com/japan/technet/archive/security/chklist/nt4wscl.mspx)

**ステップ 4: 継続的に保守を行うプログラム**

これまでのステップを通じて、良好なセキュリティ ベースラインがシステムにインストールされたことになりますが、新しい形態の攻撃に対しては脆弱になりかねません。そこで継続的な保守が必要となります。

-   [マイクロソフト セキュリティ通知サービス](http://www.microsoft.com/japan/technet/security/bulletin/notify.mspx)に加入してください。これは、マイクロソフト製品のセキュリティに関する情報を加入者へ通知するための無料の電子メール通知サービスです。

-   [Windows Update Web サイト](http://windowsupdate.microsoft.com/)にアクセスして、最新の推奨および重要アップデートをチェックしてください。

-   新しいセキュリティ修正が利用可能になったら、それを適用することが重要です。マイクロソフトは、複数の修正プログラムをインストールするたびに必要となるコンピュータの再起動を 1 度だけに留めるために、修正プログラムを相互に結びつけるコマンド ライン ツール [QChain.exe](http://support.microsoft.com/kb/296861) を開発しました。

[](#mainsection)[ページのトップへ](#mainsection)
