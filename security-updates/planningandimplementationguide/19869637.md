---
TOCTitle: Code Red II ワームの既知の影響を排除するツール
Title: Code Red II ワームの既知の影響を排除するツール
ms:assetid: '703ec83e-ddb5-4632-b70c-65557bf014fe'
ms:contentKeyID: 19869637
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277360(v=TechNet.10)'
---

Code Red II ワームの既知の影響を排除するツール
==============================================

公開日: 2001年8月9日

マイクロソフトは、Code Red II ワームによって引き起こされる既知の被害を排除するツールを開発しました。このツールは以下の操作を実行します。

-   ワームによってインストールされた悪意のあるファイルを取り除きます。

-   システムを再起動して、メモリからワームを取り除きます。

-   既知のワームをインストールするのに使用されることが判明しているマッピングを排除します (削除されるマッピングに関しては以下の 「注意」 の欄をご覧下さい)。

-   サーバー上の IIS を恒久的に無効にするオプションを提供します。

### 注意

-   このツールを実行する事で適切な予防策の代わりとする事は出来ません。マイクロソフトはWindows NT 4.0 または Windows 2000 Web サーバーを実行している場合、[Code Red による深刻な問題に対する防護策と対処方法についての説明](http://www.microsoft.com/japan/technet/security/alerts/codeptch.mspx)で公開している作業を実行することを推奨します。ワームにまだ感染していないサーバーに関しては、この作業の実施により、システムのワームによる感染を防げるため、このツールを使用する必要がありません。

-   このツールは、/Scripts または /MSADC の IIS のマッピングを取り除きます。サーバーがこれらのマッピングを利用する必要がある場合、このツールをインストールした後に、手動でこれらのマッピングを再設定する必要があります。

-   ワームの性質のために、サーバーを再起動した後に、再度このツールを実行する必要があります。これにより、1 度目にツールを実行した際のワームの状態に関わらず、ワームを確実に排除出来ます。Windows 2000 をご利用のお客様は、ワームによりシステムファイルを置き換えられる可能性がありますので、sfc /scannow コマンドを実行して、システムファイルをスキャンすることをお勧めします。

-   **このツールによって排除されるのは、CODE RED II** **ワームによる影響のみです。CODE RED** **に関する他の変種の影響は排除しません。**

-   **ワームによってシステムが感染した場合、さらに別の種類の攻撃を受ける可能性があります。このツールは、ワームによる直接的な影響のみを排除するため、サーバーの感染中に受けた他の種類の攻撃によって引き起こされる可能性のある別の被害を取り除くことはありません。**

-   **このツールはルーターまたはファイアウォールによってインターネットから保護されている内部のサーバー上での** **CODE RED II** **ワームの影響を排除するためには有益です。マイクロソフトは、ワームに感染しているサーバーのうちインターネットに直接接続しているものに関しては**[**JP CERT WEB SITE**](http://www.jpcert.or.jp/ed/199x/99-0002-01.txt)![](images/Dd277360.leave-ms(ja-jp,TechNet.10).gif)**で公開されているガイドラインにしたがって再構築することを推奨します。さらに、感染したサーバーとネットワーク的に近い距離にあることにより、危険にさらされていると判断されるほかのサーバーも、サービスを再開する前に、再構築することが必要です。**

[](#mainsection)[ページのトップへ](#mainsection)

### このツールを使用するには、以下の手順に従ってください。

1.  [http://www.microsoft.com/Downloads/details.aspx?displaylang=en&FamilyID=9B7A1710-2B5C-4754-94D4-BC6A81A9A054](http://www.microsoft.com/downloads/details.aspx?displaylang=en&familyid=9b7a1710-2b5c-4754-94d4-bc6a81a9a054) からこのツールをダウンロードして下さい。

2.  感染しているマシンのディレクトリに、このツールを置いてください。

3.  以下のコマンドを使用して、コマンド プロンプトからこのツールを実行してください。

    ```
    toolname [-disable]
    ```
    -disable フラグにより、サーバーの IIS が恒久的に無効になります。

**注** **:** 感染の度合いにより、/Scripts または /MSADC の IIS のマッピングが削除されない場合があります。この場合は、下記の手順に従い、仮想ディレクトリの削除と修復を手動にて行ってください。

#### 仮想ディレクトリの削除と修復

作業を行っていただきます前に、[IIS の構成情報のバックアップと復元](http://www.microsoft.com/japan/technet/security/alerts/codeptch.mspx)をご覧になり、バックアップを作成していただくことをお勧めいたします。

1.  インターネット サービス マネージャ を起動します。

    Windows NT 4.0 では、**\[スタート\]** - **\[Windows NT 4.0 Option Pack\]** - **\[Microsoft Internet Information Server\]** - **\[インターネットサービスマネージャ\]** を選択します。

    Windows 2000 では、**\[スタート\]** - **\[設定\]** - **\[コントロールパネル\]** - **\[管理ツール\]** - **\[インターネットサービスマネージャ\]** を選択します。

2.  "既定の Web サイト" を展開し、サイト内のディレクトリ一覧を表示します。

3.  Scripts を選択し、プロパティを開きます。

4.  **\[仮想ディレクトリ\]** タブを選択し、セキュリティの設定は、デフォルトでは以下のようになっています。お客様の設定をご確認ください。

    -   ログアクセス - チェック

    -   このリソースに索引を付ける - チェック

    -   実行アクセス権 : スクリプトおよび実行ファイル

5.  設定を確認・修正し、**\[OK\]** ボタンをクリックします。

6.  MSADC を選択し、プロパティを開きます。

7.  **\[仮想ディレクトリ\]** タブを選択し、セキュリティの設定は、デフォルトでは以下のようになっています。お客様の設定をご確認ください。

    -   ログアクセス - チェック

    -   読み取り - チェック

    -   このリソースに索引を付ける - チェック

    -   実行アクセス権 : スクリプトおよび実行ファイル

8.  設定を確認・修正し、**\[OK\]** ボタンをクリックします。

9.  C を選択し、削除します。

10. D を選択し、削除します。

11. インターネット サービス マネージャ を終了させてください。

[](#mainsection)[ページのトップへ](#mainsection)

### 関連情報

緊急 : Code Red ワームに対する警告 - 至急修正プログラムをインストールして下さい。  
<http://www.microsoft.com/japan/technet/security/alerts/codealrt.mspx>

"Code Red" IIS ワームに関する情報  
<http://www.microsoft.com/japan/technet/security/alerts/info/codered.mspx>

[](#mainsection)[ページのトップへ](#mainsection)

##### 関連リンク

-   [Code Red IIS ワームに関する情報 (概略)](http://www.microsoft.com/japan/technet/security/alerts/info/codered.mspx)
-   [Code Red ワームに対する警告](http://www.microsoft.com/japan/technet/security/alerts/codealrt.mspx)
-   [Code Red による深刻な問題に対する防護策と対処方法についての説明](http://www.microsoft.com/japan/technet/security/alerts/codeptch.mspx)
-   [Code Red II ワームの既知の影響を排除するツール](https://technet.microsoft.com/ja-jp/library/703ec83e-ddb5-4632-b70c-65557bf014fe(v=TechNet.10))
-   [Windows 2000 Professional 用 Code Red ワーム対策ガイド](http://www.microsoft.com/japan/technet/security/alerts/codestep.mspx)
-   [よくある質問と回答](http://www.microsoft.com/japan/technet/security/alerts/codefaq.mspx)
-   [更新履歴](http://www.microsoft.com/japan/technet/security/alerts/codeuprcd.mspx)

[](#mainsection)[ページのトップへ](#mainsection)

**関連サイト**

-   [株式会社シマンテック](http://www.symantec.com/ja/jp/security_response/writeup.jsp?docid=2001-071911-5755-99)![](images/Dd277360.leave-ms(ja-jp,TechNet.10).gif)

-   [トレンドマイクロ株式会社](http://www.trendmicro.co.jp/esolution/solutiondetail.asp?solutionid=3057)![](images/Dd277360.leave-ms(ja-jp,TechNet.10).gif)

[](#mainsection)[ページのトップへ](#mainsection)
