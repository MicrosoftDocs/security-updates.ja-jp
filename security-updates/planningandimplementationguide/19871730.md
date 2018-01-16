---
TOCTitle: 'ウイルス情報 : BadTrans.B ワームに関する情報'
Title: 'ウイルス情報 : BadTrans.B ワームに関する情報'
ms:assetid: '7f0c26d2-a535-47b8-8999-05339f875592'
ms:contentKeyID: 19871730
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362784(v=TechNet.10)'
---

BadTrans.B ワームに関する情報
=============================

公開日: 2001年11月27日

##### トピック

[](#ez)[はじめに](#ez)
[](#ewc)[BadTrans.B ワームの影響を受ける恐れのある製品](#ewc)
[](#ehd)[本ワームへの対策](#ehd)

はじめに
--------

現在、BadTrans.B ワームと呼ばれる BadTrans.A の亜種が被害範囲を広げています。 (別名に W32/BadTrans.B-mm, W32.Badtrans.B@mm, W32/Badtrans@MM, Backdoor-NK.svr, BadTrans, I-Worm.Badtrans, W32.Badtrans.13312@mm 等があります) このワームは以下の方法で感染を広げていくことが判明しています。

-   Internet Explorer の既知の脆弱性を利用した E-mail による感染、拡大

本ワームが利用する Internet Explorer の脆弱性 ([不適切な MIME ヘッダーが原因で Internet Explorer が電子メールの添付ファイルを実行する (MS01-020)](http://www.microsoft.com/japan/technet/security/bulletin/ms01-020.mspx)) は、9 月よりインターネット上で猛威を振るった Nimda ワームや、ALIZ ワームで使用されたものと同一のものです。

この問題点に関しては、既に対策プログラムが公開されています。本ページにある対策情報に基づいて対応してください。

[不適切な MIME ヘッダーが原因で Internet Explorer が電子メールの添付ファイルを実行する (MS01-020)](http://www.microsoft.com/japan/technet/security/bulletin/ms01-020.mspx)

また、以下の Web サイトにて本ワームに関する情報が公開されておりますので併せてご参照ください。

-   IPA  
    <http://www.ipa.go.jp/security/topics/newvirus/badtrans-b.html>![](images/Dd362784.leave-ms(ja-jp,TechNet.10).gif)

-   株式会社シマンテック  
    <http://www.symantec.com/region/jp/sarcj/data/w/w32.badtrans.b@mm.html>![](images/Dd362784.leave-ms(ja-jp,TechNet.10).gif)

-   トレンドマイクロ株式会社 バッドトランスB対策Web  
    [http://www.trendmicro.co.jp/vinfo/virusencyclo/default5.asp?VName=WORM\_BADTRANS.B](http://www.trendmicro.co.jp/vinfo/virusencyclo/default5.asp?vname=worm_badtrans.b)![](images/Dd362784.leave-ms(ja-jp,TechNet.10).gif)

-   マカフィー株式会社  
    [http://www.mcafee.com/japan/security/virB2001.asp?v=W32/Badtrans@MM](http://www.mcafee.com/japan/security/virb2001.asp?v=w32/badtrans@mm)![](images/Dd362784.leave-ms(ja-jp,TechNet.10).gif)

本ワームへの対策に関する情報を以下に記載いたします。

本対応を行われていないお客様は、至急対応をお願いいたします。

[](#mainsection)[ページのトップへ](#mainsection)

BadTrans.B ワームの影響を受ける恐れのある製品
---------------------------------------------

Internet Explorer の Web ブラウザコントロールを利用している以下の製品等

-   Microsoft Outlook

-   Microsoft Outlook Express

**注意 :** 上記は一例であり、共通コンポーネントである Web ブラウザコントロールを使用しているメールソフトウェアは他にも多数ございます。

**参考 :** Windows XP、Macintosh 用の Internet Explorer は、BadTrans.B ワームの影響を受けません。

[](#mainsection)[ページのトップへ](#mainsection)

本ワームへの対策
----------------

本ワームへの対策としては、Internet Explorer 5.01 Service Pack 2 / 5.5 Service Pack 2 をインストールするか、Internet Explorer 6 の Outlook Express を含む標準構成以上でのインストールを行ってください。

この対策をとる事によってワームに対して自動的に感染することはなくなります。しかし、添付ファイルを意図的に開くことなどによる感染は防止できませんので、不用意にそのような行為を行わないよう注意してください。

### Internet Explorer 管理者キットを使ってインストールをする

企業において大規模インストールを実施する場合、インストール後の設定 (Proxy 情報、ホームページの設定等) も含めて展開をすることが可能な Internet Explorer 管理者キット の利用をお勧めします。展開におけるコスト削減、効率化に役立ちます。

-   Internet Explorer 管理者キット  
    <http://www.microsoft.com/japan/ieak/>

-   Internet Explorer を複数の PC に効率的に展開するためのガイド  
    <http://technet.microsoft.com/library/cc709377.aspx>

### Internet Explorer ダウンロード対応プロバイダからダウンロードする

Internet Explorer をより高速にダウンロードすることが可能なプロバイダをご紹介します。対応プロバイダに関しては下記のページで紹介していますのでご確認ください。

-   Internet Explorer ダウンロード対応 ISP 一覧  
    http://www.microsoft.com/japan/ie/downloads/isp/

### マイクロソフトのサイトからダウンロードする

マイクロソフトが提供しているダウンロードサーバーから必要となるモジュールを入手する形でインストールを実施します。

-   Internet Explorer 5.01 SP2 (Windows 2000 SP2 に含まれています)

-   Internet Explorer 5.5 SP2

-   Internet Explorer 6

最新バージョンの Internet Explorer は次の Web サイトから入手できます。  
<http://www.microsoft.com/japan/windows/downloads/default.mspx>

**重要 :** IE 6 をセットアップする場合は、必ず Outlook Express を含む標準構成以上でセットアップしてください。

[](#mainsection)[ページのトップへ](#mainsection)
