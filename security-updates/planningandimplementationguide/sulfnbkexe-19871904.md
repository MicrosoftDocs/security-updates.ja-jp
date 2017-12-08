---
TOCTitle: 'sulfnbk.exe に関する情報'
Title: 'sulfnbk.exe に関する情報'
ms:assetid: 'fa1701e6-cb47-4f20-8e3a-4ff79cde07e0'
ms:contentKeyID: 19871904
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362959(v=TechNet.10)'
---

sulfnbk.exe に関する情報
========================

Published: 1月 10, 2002 | Updated : 4月 24, 2002

##### 目次

[](#edaa)[概要](#edaa)
[](#ecaa)[製品導入時に sulfnbk.exe を含むソフトウェア](#ecaa)
[](#ebaa)[詳細](#ebaa)
[](#eaaa)[sulfnbk.exe の再インストール方法](#eaaa)

### 概要

現在、「sulfnbk.exe ファイルはウイルスであり、削除してください」という内容のメールが多くの方に送信されております。アンチウイルスベンダー様もご紹介の通り、この情報は誤りであり、sulfnbk.exe はウイルスではありません。

このファイルは、OS が使用するファイルですが、このファイルがなくなったことによって OS が起動しなくなることはありません。また、このファイルは、Windows 98、Windows 98 Second Edition、Windows Millennium Edition に含まれ、Windows 95、Windows NT、Windows 2000、Windows XP には影響ありません。

また、以下の Web サイトにて本件に関する情報が公開されておりますので併せてご参照ください。

-   IPA
    <http://www.ipa.go.jp/security/topics/alert140108.html>![](images/Dd362959.leave-ms(ja-jp,TechNet.10).gif)

-   株式会社シマンテック
    <http://www.symantec.com/region/jp/sarcj/data/s/sulfnbk.exe_warning.html>![](images/Dd362959.leave-ms(ja-jp,TechNet.10).gif)

-   トレンドマイクロ株式会社
    [http://www.trendmicro.co.jp/vinfo/virusencyclo/default5.asp?VName=SULFNBK&VSect=T](http://www.trendmicro.co.jp/vinfo/virusencyclo/default5.asp?vname=sulfnbk&vsect=t)![](images/Dd362959.leave-ms(ja-jp,TechNet.10).gif)

-   日本ネットワークアソシエイツ株式会社
    [http://www.mcafee.com/japan/security/virHOAX.asp?v=SULFNBK&a=HOAX](http://www.mcafee.com/japan/security/virhoax.asp?v=sulfnbk&a=hoax)![](images/Dd362959.leave-ms(ja-jp,TechNet.10).gif)

[](#mainsection)[ページのトップへ](#mainsection)

### 製品導入時に sulfnbk.exe を含むソフトウェア

-   Windows 98

-   Windows 98 Second Edition

-   Windows Millennium Edition

**注:** Windows 95、Windows NT、Windows 2000、Windows XP は製品導入時に sulfnbk.exe を含んでいません。

[](#mainsection)[ページのトップへ](#mainsection)

### 詳細

sulfnbk.exe は、Windows 98、Windows 98 Second Edition、Windows Millennium Edition に付属している実行ファイルになります。 (Windows 95 には含まれません。) この実行ファイルは、DOS 形式 (8.3 形式) の Short File Name から、Long File Name に変換する際に使用されるものです。Short File Name が参照できず、判断が出来ないファイルを Long File Name として表示させる場合等に使用します。 (例えば、\[MYDOCU~1\] と表示されるようになってしまったファイル名を \[My Document\] に変更します。)

[](#mainsection)[ページのトップへ](#mainsection)

### sulfnbk.exe の再インストール方法

誤って sulfnbk.exe を削除し、再インストールを実行したい場合には、下記の手順を参照してください。

#### Windows Millennium Edition (Me) の場合

Windows Meをご使用の場合、システム設定ユーティリティを使ってファイルを復元することができます。

1.  \[スタート\] ボタンをクリックし、\[ファイル名を指定して実行\] をクリックします。

2.  \[ファイル名を指定して実行\] ダイアログ ボックスの \[名前\] ボックスに msconfig と入力し、\[OK\] ボタンをクリックします。

3.  システム設定ユーティリティ上の \[全般\] タブにある \[ファイルの抽出\] ボタンをクリックします。

4.  \[インストール ディスクからファイルを 1 つ抽出する\] ダイアログ ボックスで、抽出するファイル名に sulfnbk.exe と入力し、\[開始\] ボタンをクリックします。

5.  「ファイルの抽出」 ウィンドウで \[復元\] ボックスに、次の該当する文字を入力します。

    -   Windows Me (パッケージ版) をインスールした場合
        ```

    -   Windows Me (プレインストール) をインストールした場合
        ```

    プレインストールマシンによっては、フォルダが異なる場合があります。この場合は、プレインストールマシンの製造元様にお問い合わせください。

6.  \[ファイルの保存先\] ボックスに、抽出したファイルを保存するフォルダまでのパスを入力しファイルを抽出します。
        ```

    注: インストールしたフォルダによって、異なる場合があります。

7.  ファイルが抽出されると以下のメッセージが表示されるので、\[OK\] ボタンをクリックします。
        ```

8.  手順 6 で指定したフォルダにファイルが抽出されていることを確認してください。

#### Windows 98、Windows 98 Second Edition の場合

Windows 98、Windows 98 Second Edition をご利用のお客様は、システム ファイル チェッカーを使用してファイルを復元することができます。

1.  \[スタート\] ボタンをクリックし、\[ファイル名を指定して実行\] をクリックします

2.  \[ファイル名を指定して実行\] ダイアログ ボックスの \[名前\] ボックスに sfc と入力し、\[OK\] ボタンをクリックします。

3.  システム ファイル チェッカーの \[インストールディスクからファイルを 1 つ抽出する\] をクリックします。

4.  \[復元したいシステム ファイルを指定してください\] で、下記の文字を入力し、\[開始\] をクリックします。
        ```

        注: インストールしたフォルダによって、異なる場合があります。

5.  \[復元元\] ダイアログボックスが表示されますので、インストール元を指定してください。CD からインストールした場合には、CD ドライブに Windows 98 (Windows 98 Second Edition) の CD を入れ、CD の中の Win98 フォルダを指定します。 (NEC PC-9801/9821シリーズをご利用のお客様は、Win98n フォルダになります) インストールファイルをハードディスクにコピーしていた場合、C:\\Windows\\Options\\Cabs になります。

6.  OK をクリックします。

7.  ファイルが抽出されると、以下のメッセージが表示されるので、\[OK\] ボタンをクリックします。
        ```

詳細は、下記の弊社サポート技術情報をご覧ください。

-   Sulfnbk.exe の概要およびプログラム ファイルの置き換え方法 （301316)
    [http://support.microsoft.com/default.aspx?scid=kb;JA;301316](http://support.microsoft.com/default.aspx?scid=kb;ja;301316)

[](#mainsection)[ページのトップへ](#mainsection)
