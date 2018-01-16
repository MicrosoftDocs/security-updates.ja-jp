---
TOCTitle: Windows 2000 Professional 用 Code Red ワーム対策ガイド
Title: Windows 2000 Professional 用 Code Red ワーム対策ガイド
ms:assetid: '965ef673-a989-486b-af44-4dcfe294127d'
ms:contentKeyID: 19871748
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362802(v=TechNet.10)'
---

Windows 2000 Professional 用 Code Red ワーム対策ガイド
======================================================

公開日: 2001年8月10日

[**更新履歴**](http://technet.microsoft.com/ja-jp/library/dd362803.aspx)

##### 目次

[](#ecaa)[はじめに](#ecaa)  
[](#ebaa)[対象となる製品と環境](#ebaa)  
[](#eaaa)[対応策](#eaaa)

### はじめに

お客様の Web サーバーも含め世界中で稼動している Web サーバーを不正に利用し、インターネットに対して甚大な被害をもたらす攻撃が蔓延しています。この攻撃を行っているのは、Code Red と呼ばれるワームです。Microsoft Windows 2000 Professional にて「インターネット インフォメーション サービス」 (以下 : IIS) をカスタムインストールされているすべての方々がこのワームによる影響を受ける可能性があります。

本ページでは、Windows 2000 Professional をご使用のお客様を悪意のあるプログラムによる攻撃から守るための防御策について説明しておりますので、下記をご参照の上、対策をお願い申し上げます。

[](#mainsection)[ページのトップへ](#mainsection)

### 対象となる製品と環境

Windows 2000 Professional においてインターネット インフォメーション サービス (IIS) が動作しており、インターネットに接続しているコンピュータ (ダイアルアップ接続を含む) 。

[](#mainsection)[ページのトップへ](#mainsection)

### 対応策

#### Step 1: お客様の Windows 2000 にインターネット インフォメーション サービス (IIS) がインストールされているかどうか確認します。

1.  **\[スタート\]** メニュー、**\[設定\]** の順にクリックし、**\[コントロール パネル\]** ウインドウを開きます。

    ![](images/Dd362802.1_1s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.1_1(ja-jp,technet.10).gif)

2.  **\[コントロール パネル\]** ウインドウの **\[アプリケーションの追加と削除\]** アイコンをダブル クリックします。

    ![](images/Dd362802.1_2s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.1_2(ja-jp,technet.10).gif)

3.  **\[アプリケーションの追加と削除\]** ウインドウ左側にある、**\[Windows コンポーネントの追加と削除\]** ボタンをクリックします。

    ![](images/Dd362802.1_3s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.1_3(ja-jp,technet.10).gif)

4.  **\[Windows コンポーネント ウィザード\]** の**「インターネット インフォメーション サービス (IIS)」**のチェック ボックスを確認します。チェック ボックスにチェックが付いているならば、「インターネット インフォメーション サービス (IIS)」がインストールされていることを示します。

    ![](images/Dd362802.1_4s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.1_4(ja-jp,technet.10).gif)

    -   インターネット インフォメーション サービスがインストールされている場合は、Step 2へお進みください。

    -   インターネット インフォメーション サービスがインストールされていない場合は、Step 2 の対応策は必要ありません。今後もより安全にお使いいただくためには、Step 3 以降のステップに従ってサービスパックならびに修正モジュールを適用をすることを推奨させていただきます。

#### Step 2: インターネット インフォメーション サービスを停止させる

インターネット インフォメーション サービスが起動している場合は一度サービスを停止させる必要があります。以下の手順に従ってサービスを停止してください。

1.  **\[スタート\]** メニュー、**\[設定\]** の順にクリックし、**\[コントロール パネル\]** ウインドウを開きます。

    ![](images/Dd362802.1_1s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.1_1(ja-jp,technet.10).gif)

2.  **\[コントロール パネル\]** ウインドウの **\[管理ツール\]** アイコンをダブル クリックします。

    ![](images/Dd362802.1_2s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.1_2(ja-jp,technet.10).gif)

3.  **サービス** アイコンをダブルクリックします。

    ![](images/Dd362802.2_4s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.2_4(ja-jp,technet.10).gif)

4.  **IIS Admin Service** を選択してダブルクリックします。サービスの状態が開始になっている場合、停止のボタンを押します。

    ![](images/Dd362802.2_5s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.2_5(ja-jp,technet.10).gif)

5.  上記のダイアログの処理が完了した段階で、インターネット インフォメーション サービス が停止いたします。

    ![](images/Dd362802.2_6s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.2_6(ja-jp,technet.10).gif)

#### Step 3: Windows 2000 のサービスパックを入手します。

Windows 2000 Service Pack 2 を以下のいずれかの方法で入手し、デスクトップに保存します。

-   **ダウンロード**

    <http://www.microsoft.com/japan/windows2000/downloads/default.mspx>

    ダウンロードモジュールにはネットワークのタイプにあわせて選択する必要があります。今回の手順ではネットワークインストールのモジュールを選択してください。

    ![](images/Dd362802.2_1s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.2_1(ja-jp,technet.10).gif)

    「Windows 2000 SP2 ネットワークインストール」には 2 種類のファイルを用意しておりますが、今回の手順ではネットワークインストールのモジュールをダウンロードしてください。

-   **ダウンロード以外の入手方法**

    Windows 2000 Service Pack 2 を収録した CD-ROM を有償で入手することができます。

    【オンラインでの申し込み】
    <http://www.microsoft.com/products/info/list.aspx?view=36&type=all>

    9 月 30 日にて、無償提供を終了させていただきました。ご了承ください。

※マイクロソフトでは Windows 2000 Service Pack 2 の適用を強くお勧めしまが、特殊な事情などにより Service Pack 2 の適用が困難である場合は、Service Pack 1 を適用してください。

-   Windows 2000 Service Pack 1 日本語版
    [http://www.microsoft.com/downloads/details.aspx?FamilyID=b529f2f4-77f2-4cb5-98dd-cb00f53fc4e2&DisplayLang=ja](http://www.microsoft.com/downloads/details.aspx?familyid=b529f2f4-77f2-4cb5-98dd-cb00f53fc4e2&displaylang=ja)

1.  Windows 2000 Service Pack 2 インストーラ ファイルの保存先を指定します。この画像ではデスクトップを保存先として指定しています。

    ![](images/Dd362802.2_2s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.2_2(ja-jp,technet.10).gif)

2.  ファイルの保存が完了した後、ダイアログ ボックスを閉じてください。

    ![](images/Dd362802.2_3s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.2_3(ja-jp,technet.10).gif)

#### Step 4: ワームに対処するための修正モジュールを入手します

このワームに対処するための修正モジュールを以下からダウンロードしてデスクトップに保存します。
[http://www.microsoft.com/downloads/details.aspx?FamilyId=04A2A24E-B862-45CA-A20D-FAD30F6D0235&displaylang=ja](http://www.microsoft.com/downloads/details.aspx?familyid=04a2a24e-b862-45ca-a20d-fad30f6d0235&displaylang=ja)

1.  **「Select Language」**の三角形のボタンをクリックすると、プルダウン メニューからお使いのシステムの言語を選択できます。**「Japanese」**を選択した後、その右側にある**「GO」**ボタンをクリックします。

    ![](images/Dd362802.3_1s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.3_1(ja-jp,technet.10).gif)

2.  **「Security Update」**をクリックします。

    ![](images/Dd362802.3_2s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.3_2(ja-jp,technet.10).gif)

3.  修正モジュールはハード ディスクに保存してください。**「OK」**をクリックすると保存先を指定できます。

    ![](images/Dd362802.3_3s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.3_3(ja-jp,technet.10).gif)

4.  修正モジュールの保存先を指定します。この画像ではデスクトップを保存先として指定しています。

    ![](images/Dd362802.3_4s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.3_4(ja-jp,technet.10).gif)

5.  ファイルの保存が完了した後、ダイアログ ボックスを閉じてください。

    ![](images/Dd362802.3_5s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.3_5(ja-jp,technet.10).gif)

#### Step 5: 感染チェックツールを入手します

感染をチェックするためのツールを、以下の各社の Web ページよりダウンロードします。

**株式会社シマンテックより感染チェック ツールをダウンロードする場合**

Symantec Security Check - CodeRed Check
<http://www.symantec.com/ja/jp/security_response/writeup.jsp?docid=2001-071911-5755-99>

1.  「EXE ファイル」をクリックします。

    ![](images/Dd362802.4_1_1s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.4_1_1(ja-jp,technet.10).gif)

2.  感染チェック ツールはハード ディスクに保存してください。「OK」をクリックすると保存先を指定できます。

    ![](images/Dd362802.4_1_2s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.4_1_2(ja-jp,technet.10).gif)

3.  感染チェック ツールの保存先を指定します。この画像ではデスクトップを保存先として指定しています。

    ![](images/Dd362802.4_1_3s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.4_1_3(ja-jp,technet.10).gif)

4.  感染チェック ツールの保存が完了した後、ダイアログ ボックスを閉じてください。

    ![](images/Dd362802.4_1_4s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.4_1_4(ja-jp,technet.10).gif)

**トレンドマイクロ株式会社より感染チェック ツールをダウンロードする場合**

ワーム「CodeRed」セキュリティホール検知ツール
[http://www.trendmicro.co.jp/esolution/solutionDetail.asp?solutionId=3057](http://www.trendmicro.co.jp/esolution/solutiondetail.asp?solutionid=3057)

1.  「detect\_codered.exe」をクリックします。

    ![](images/Dd362802.4_2_1s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.4_2_1(ja-jp,technet.10).gif)

2.  感染チェック ツールはハード ディスクに保存してください。「OK」をクリックすると保存先を指定できます。

    ![](images/Dd362802.4_2_2s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.4_2_2(ja-jp,technet.10).gif)

3.  感染チェック ツールの保存先を指定します。この画像ではデスクトップを保存先として指定しています。

    ![](images/Dd362802.4_2_3s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.4_2_3(ja-jp,technet.10).gif)

4.  感染チェック ツールの保存が完了した後、ダイアログ ボックスを閉じてください。

    ![](images/Dd362802.4_2_4s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.4_2_4(ja-jp,technet.10).gif)

#### Step 6: ネットワークから切断します

修正モジュールの適用中に再度の感染を防ぐために、ネットワークから切断します。ダイアルアップによる接続の場合は、 TA/モデム との接続ケーブルをはずしてください。LAN に接続されている場合は、 LAN ケーブルを抜いてください。

#### Step 7: PC を再起動します

修正プログラムを確実に適用するために、メモリ上に存在している Code Red ワームをコンピュータの再起動により取り除きます。

#### Step 8: サービスパックを適用します

Step 3 で入手したサービスパックをインストールします。

1.  Step 3でダウンロードした「sp2express.exe」をダブルクリックすると、「Windows 2000 Service Pack セットアップ」ウィザードが表示されます。追加使用許諾契約書にご同意いただけたならば、「同意します」のチェック ボックスをチェックし、「インストール」ボタンをクリックしてインストールを開始します。

    ![](images/Dd362802.7_1s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.7_1(ja-jp,technet.10).gif)

2.  インストールにはお使いの環境によって多少時間がかかります。インストールが終了すると、「Step 9」の画面になります。

    ![](images/Dd362802.7_2s(ja-jp,TechNet.10).gif)

    [拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.7_2(ja-jp,technet.10).gif)

#### Step 9: PC を再起動します

サービスパックのセットアップにより、再起動を要求されますので、再起動してください。

![](images/Dd362802.8_1s(ja-jp,TechNet.10).gif)

[拡大表示する](https://technet.microsoft.com/ja-jp/dd362802.8_1(ja-jp,technet.10).gif)
Windows 2000 Service Pack 2 のインストールが完了すると、再起動を行います。もし、ドキュメントなど作業中のファイルがあればそれらを保存し、「再起動」ボタンをクリックしてください。

#### Step 10: 修正モジュールを適用します

Step 4 で入手した修正モジュールをインストールします。

![](images/Dd362802.9_1(ja-jp,TechNet.10).gif)

Step 4でダウンロードした「q300972\_w2k\_sp3\_x86\_ja.exe」をダブルクリックすると、修正モジュールのインストールが始まります。インストールが終了するとこのような画面が表示され、「OK」ボタンをクリックするとインストールが終了します。

#### Step 11: PC を再起動します

修正モジュールのセットアップ終了後、再起動します。

#### Step 12: 感染の確認と駆除をします

Step 5 で入手した感染チェックツールを使い、ワームに感染していないことを確認します。確認方法およびツールの使用方法につきましては以下の各社 Web ページをご参照ください。

-   ワーム「CodeRed」セキュリティホール検知ツール
    [http://www.trendmicro.co.jp/esolution/solutionDetail.asp?solutionId=3057](http://www.trendmicro.co.jp/esolution/solutiondetail.asp?solutionid=3057)

-   Symantec Security Check - CodeRed Check
    <http://www.symantec.com/region/jp/securitycheck/index.html>

上記対応策の適用が不可能な場合には、以下の「Code Red による深刻な問題に対する防護策と対処方法についての説明 」をご参照ください。

IIS セキュリティ対策情報サイト
<http://technet.microsoft.com/library/dd362800.aspx>

[](#mainsection)[ページのトップへ](#mainsection)

##### 関連リンク

-   [Code Red IIS ワームに関する情報 (概略)](https://technet.microsoft.com/ja-jp/library/6f2181fc-63dc-47ba-bef8-274dcf46e2f5(v=TechNet.10))
-   [Code Red ワームに対する警告](https://technet.microsoft.com/ja-jp/library/51c63253-c045-480f-9559-67c7c47c47e6(v=TechNet.10))
-   [Code Red による深刻な問題に対する防護策と対処方法についての説明](https://technet.microsoft.com/ja-jp/library/d4170d68-6db8-48b1-bbf1-624ff15ff143(v=TechNet.10))
-   [Code Red II ワームの既知の影響を排除するツール](https://technet.microsoft.com/ja-jp/library/703ec83e-ddb5-4632-b70c-65557bf014fe(v=TechNet.10))
-   [Windows 2000 Professional 用 Code Red ワーム対策ガイド](https://technet.microsoft.com/ja-jp/library/965ef673-a989-486b-af44-4dcfe294127d(v=TechNet.10))
-   [よくある質問と回答](https://technet.microsoft.com/ja-jp/library/1ce261cd-67cb-452a-ad50-83018ed6072b(v=TechNet.10))
-   [更新履歴](https://technet.microsoft.com/ja-jp/library/d0803687-3916-46c2-a9e2-47183f757099(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
