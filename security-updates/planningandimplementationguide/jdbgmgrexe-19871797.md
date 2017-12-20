---
TOCTitle: 'jdbgmgr.exe に関する情報'
Title: 'jdbgmgr.exe に関する情報'
ms:assetid: 'b7bd571b-0aaa-4291-8ac1-f18628d5c702'
ms:contentKeyID: 19871797
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362851(v=TechNet.10)'
---

jdbgmgr.exe に関する情報
========================

公開日: 2002年5月9日

##### 目次

[](#ecaa)[概要](#ecaa)
[](#ebaa)[jdbgmgr.exe を削除した場合の復元方法](#ebaa)
[](#eaaa)[更新履歴](#eaaa)

### 概要

現在、「jdbgmgr.exe ファイルはウイルスなので、検索し削除してください」という内容のメールが多くの方に送信されております。アンチウイルスベンダー様からもご紹介の通り、この情報は誤りであり、jdbgmgr.exe はウイルスではありません。

このファイルは、Microsoft 仮想マシン (以下 Microsoft VM) で使用されるファイルです。また、このファイルは、様々な製品に含まれています。

送信されるメールの内容は、下記になります。(同内容が英語、イタリア語等、他の言語でも送信されていることが報告されています)
        ```
以下の Web サイトにて本件に関する情報が公開されておりますので併せてご参照ください。

-   弊社サポート技術情報

    [JP322993 Virus Hoax: Microsoft Debugger Registrar for Java (Jdbgmgr.exe) はウイルスではありません](http://support.microsoft.com/default.aspx?scid=kb;ja;jp322993)

-   IPA/ISEC

    <http://www.ipa.go.jp/security/topics/alert140515.html>![](images/Dd362851.leave-ms(ja-jp,TechNet.10).gif)

-   株式会社シマンテック

    <http://www.symantec.com/region/jp/sarcj/data/j/jdbgmgr.exe_file_hoax.html>![](images/Dd362851.leave-ms(ja-jp,TechNet.10).gif)

-   トレンドマイクロ株式会社

    [http://www.trendmicro.co.jp/vinfo/virusencyclo/default5.asp?VName=JDBGMGR.EXE%20HOAX](http://www.trendmicro.co.jp/vinfo/virusencyclo/default5.asp?vname=jdbgmgr.exe%20hoax)![](images/Dd362851.leave-ms(ja-jp,TechNet.10).gif)

-   日本ネットワークアソシエイツ株式会社

    [http://www.mcafee.com/japan/security/virHOAX.asp?v=Jdbgmgr.exe&a=HOAX](http://www.mcafee.com/japan/security/virhoax.asp?v=jdbgmgr.exe&a=hoax)![](images/Dd362851.leave-ms(ja-jp,TechNet.10).gif)

[](#mainsection)[ページのトップへ](#mainsection)

### jdbgmgr.exe を削除した場合の復元方法

誤って jdbgmgr.exe を削除してしまった場合は、下記の手順を参照して復元を行ってください。

#### Windows 2000 (Service Pack 未適用、または SP1、SP2、SP3 適用済)、 Windows Millennium Edition をご利用の場合

上記の製品をご利用の場合、jdbgmgr.exe はシステムファイルの保護機能により、保護されております。そのため、誤って削除してしまった場合でも、自動で復元されます。 再起動を行い、ファイルが復元されることを確認してください。

なお、お客様によっては、ご自身の設定により、システムファイルの保護機能を無効にしている場合があります。この場合、下記の \[[Windows XP, Windows 98, Windows 98 Second Edition, Windows NT 4.0 をご利用の場合](#xp98nt)\] の復元方法を参照してください。

#### Windows 2000 SP4 をご利用の場合

このファイルを復元したいお客様は Windows Update カタログから最新の Microsoft VM をインストールすることによってファイルが復元されます。Windows Update カタログの使い方については、この文書の「[Windows Update カタログの使い方について](#wucatalogue)」を参照してください。

#### Windows XP、Windows 98、Windows 98 Second Edition、Windows NT 4.0 をご利用の場合

このファイルを復元したいお客様は Windows Update から最新の Microsoft VM をインストールすることによってファイルが復元されます。

-   [Windows Update](http://windowsupdate.microsoft.com)

Microsoft VM は 「重要な更新と Service Pack」の中の「Microsoft VM セキュリティ問題の修正プログラム」と表示されますので、こちらを選択しインストールしてください。

#### Windows Update の使い方

Windows Update の使い方については、下記のサイトを参照してください。

-   [Windows Update 利用の手順](http://www.microsoft.com/japan/athome/security/update/j_musteps.mspx)

既に最新の Microsoft VM がインストールされている場合、Windows Update には表示されません。その場合は、Windows Update カタログを利用することによって Microsoft VM を取得することができます。所得方法は次のとおりです。

1.  [Windows Update](http://windowsupdate.microsoft.com) に接続します。

2.  左側のペインの \[その他のオプション\] で、\[Windows Update のカスタマイズ\] を選択します。

3.  「Windows Update のオプションを設定します」 の表示の下から \[Windows Update カタログへのリンクを関連項目の下に表示する\] のチェックボックスをオンにし、次に \[設定の保存\] をクリックします。

4.  [Windows Update](http://windowsupdate.microsoft.com) Web サイトに戻ります。

5.  左側のペインの \[関連項目\] から、\[Windows Update カタログ\] をクリックします。

6.  \[Microsoft Windows オペレーティング システムの更新を探します\] をクリックします。

7.  オペレーティング システムおよび言語を選択します。

8.  \[重要な更新と Service Pack\] を選択します。

9.  ダウンロードする修正プログラムをすべて選択し、\[ダウンロード バスケットに移動します\] をクリックし、修正プログラムをダウンロードします。
    (ここで「Microsoft VM セキュリティ問題の修正プログラム」を選択します)

#### Windows Update カタログの使い方について

Windows Update カタログの使い方については、下記のサイト、または、技術文書を参照してください。

-   [Windows Update カタログの利用手順](http://catalog.update.microsoft.com/v7/site/install.aspx)

-   [JP418435 Windows Update カタログ から Windows の更新を取得する方法](http://support.microsoft.com/default.aspx?scid=kb;ja;jp418435)

なお、Windows XP では 「重要な更新と Service Pack」 に 「Microsoft VM セキュリティ問題の修正プログラム」 が表示されないことがあります。その場合は、Windows Update カタログの 「Microsoft Windows オペレーティング システムの更新を探します」 からダウンロードしてください。

**注意** : 現在、Microsoft VM は Windows Update 以外から入手することができなくなっています。

Microsoft VM のダウンロードに関する詳細につきましては、下記のサイトをご覧ください。

-   [VM Availability](http://www.microsoft.com/japan/java/default.mspx)

[](#mainsection)[ページのトップへ](#mainsection)

### 更新履歴

-   2002/05/09: この情報を公開しました。

-   2002/05/16: 日本語メールの内容を追記しました。

-   2002/05/17: 復元方法の Windows XP に関する表記を修正しました。

-   2002/05/24: Microsoft VM のインストール手順を追記しました。

-   2002/06/03: JP322993 へのリンクを追記しました。

-   2002/08/21: Windows Update での入手に関し、注意として追記しました。

-   2002/11/19: Windows Update カタログからの入手方法について追記しました。

-   2002/12/13: Windows Update から入手できる Microsoft VM の名前を変更しました。

-   2004/01/15: Windows 2000 SP4 をご利用の場合の復元方法について追記しました。

[](#mainsection)[ページのトップへ](#mainsection)
