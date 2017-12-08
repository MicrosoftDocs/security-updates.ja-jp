---
TOCTitle: 'Code Red による深刻な問題に対する防護策と対処方法についての説明 ‐ Internet Information Server/Service をご利用いただいているお客様へ'
Title: 'Code Red による深刻な問題に対する防護策と対処方法についての説明 ‐ Internet Information Server/Service をご利用いただいているお客様へ'
ms:assetid: 'd4170d68-6db8-48b1-bbf1-624ff15ff143'
ms:contentKeyID: 19871746
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362800(v=TechNet.10)'
---

Code Red による深刻な問題に対する防護策と対処方法についての説明
===============================================================

### Internet Information Server/Service をご利用いただいているお客様へ

公開日: 2001年8月8日

##### トピック

[](#enaa)[はじめに](#enaa)
[](#emaa)[対象となる製品および環境](#emaa)
[](#elaa)[Code Red とは](#elaa)
[](#ekaa)[詳細](#ekaa)
[](#ejaa)[対処方法 (Windows NT 4.0/Small Business Server 4.5)](#ejaa)
[](#eiaa)[対処方法 (Windows 2000/Small Business Server 2000)](#eiaa)
[](#ehaa)[対処方法 (サービスパックまたは修正モジュールの適用が困難な場合)](#ehaa)
[](#egaa)[駆除方法](#egaa)
[](#efaa)[IIS の構成情報のバックアップと復元](#efaa)
[](#eeaa)[ファイアウォール製品について](#eeaa)
[](#edaa)[プロキシ製品について](#edaa)
[](#ecaa)[ウィルス検出ソフトについて](#ecaa)
[](#ebaa)[関連情報](#ebaa)
[](#eaaa)[本件に関する一般ユーザー様向け問い合わせ窓口](#eaaa)

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Microsoft Windows 95/98/Me をお使いのみなさまへ</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Code Red ワームは Microsoft Windows 95/98/Me に対しては<strong>影響を与えませんので、対策の必要はありません</strong>。</td>
</tr>
</tbody>
</table>
  
**重要**  
本文書で説明している対策は Code Red II ワームに関する防御と駆除を目的とした必要最低限の対策です。その他の脆弱性を標的にした攻撃からもシステムを保護する為に、包括的な対策を行うことを強く推奨します。マイクロソフトでは IIS 4.0 もしくは IIS 5.0 を実行するシステムのセキュリティを確保するために必要な手順を明文化しています。
  
### はじめに
  
以下の公的機関にて公開されているように、お客様の Web サーバーも含め世界中で稼動している Web サーバーを不正に利用し、インターネットに対して甚大な被害をもたらす攻撃が蔓延しております。  
<http://www.ipa.go.jp/security/ciadr/vul/20010727codered.html>![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
この攻撃を行っているのは、Code Red と呼ばれるワームです。  
本文書では、弊社製 Web サーバーである Internet Information Server および Internet Information Services (以下 IIS) をご使用のお客様を悪意のあるプログラムによる攻撃から守るための防御策について説明しておりますので、是非ご一読いただきセキュアなサイト運営のためにご活用ください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 対象となる製品および環境
  
#### IIS 及び Index Server/Service を搭載するオペレーティング システム製品
  
-   Microsoft Windows 2000 Server, Windows 2000 Advanced Server または Windows 2000 Datacenter Server
  
-   Microsoft Windows 2000 Professional
  
-   Microsoft Windows NT 4.0 Option Pack のインストールされている Windows NT Server 4.0 または Windows NT Server Enterprise Edition 4.0
  
-   Microsoft Windows NT Server 4.0 Terminal Server Edition
  
-   Microsoft Windows Powered 等のアプライアンス製品
  
-   Microsoft BackOffice Small Business Server version 4.0, 4.5, 及び 2000
  
-   Microsoft BackOffice Server version 4.0, 4.5, 及び 2000
  
-   Windows XP Technical Beta および Whistler Server Technical Beta (Build 2505 未満のビルド)
  
-   Windows XP プレビュープログラム (対処済みです)
  
#### IIS のセットアップが必要な サーバー製品
  
-   Microsoft Site Server version 3.0
  
-   Microsoft Exchange 2000 Server
  
-   Microsoft SharePoint Portal Server 2001
  
-   Microsoft Application Center 2000
  
-   Microsoft BizTalk Server 2000
  
-   Microsoft Commerce Server 2000
  
#### IIS もしくは Index Server/Service を必要とし、Code Red ワームの影響を受ける可能性のある製品
  
-   Microsoft Exchange Server 5.x の OWA 機能
  
-   Microsoft SQL Server 7.0, 2000 の SQLXML 機能
  
-   Microsoft SQL Server 7.0, 2000 の Full Text Search 機能
  
-   Microsoft SQL Server 7.0, 2000の SQL Server Windows CE Edition に対するレプリケーション パブリッシャ機能
  
-   Microsoft Proxy Server 1.0 及び 2.0
  
-   Microsoft Windows Media Rights Manager 1.0 及び 7.0
  
-   Microsoft Office XP で提供されている SharePoint Team Services 機能
  
-   Microsoft Office 2000 で提供されている Office Server Extensions 機能
  
-   Microsoft Project 2000 で提供されている Project Central 機能
  
-   Microsoft FrontPage で提供される FrontPage Server Extensions 機能
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### Code Red とは
  
Code Red は、ワームに分類される不正なプログラムです。弊社製 Web サーバーである Internet Information Server および Internet Information Services (以下 IIS) の 脆弱性を利用して不正な活動を行います。このワームが、活動を行うと、お客様に以下の被害をもたらします。
  
-   IIS の異常終了
  
-   多大なトラフィックによるインターネット、および LAN の速度低下
  
-   コンテンツの改ざん (英語版でのみ発生いたします)
  
-   トロイの木馬の設置
  
また、このワームに感染すると、 インターネットや LAN 上にある他の IIS を探し出し次々と伝染します。その結果、お客様の大切な取引先のサーバーやネットワークに対しても被害を与えてしまう可能性があります。
  
尚、Code Red ワームは Windows 95, 98, Me に対しては影響を与えません。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 詳細
  
ワームは、「[Index Server ISAPI エクステンションの未チェックのバッファにより Web サーバーが攻撃される (MS01-033)](http://www.microsoft.com/japan/technet/security/bulletin/ms01-033.mspx)」の脆弱性を悪用し不正な HTTP リクエストを送ることでバッファオーバーランを発生させコンピューター内部に侵入します。侵入によりメモリ上に、以下の機能を持っているコードを展開します。
  
-   他の IIS を探し出し感染(伝染) する機能
  
-   ディスク上に トロイの木馬を作成する機能
  
-   レジストリを変更し、IIS の仮想フォルダを追加する機能
  
ワームが、IIS に対して感染した場合または感染を試みた場合 IIS のログファイルに以下のような情報を残します。IIS が異常終了した場合には、ログを残さない場合があります。
  
<codesnippet language displaylanguage containsmarkup="false"> GET /default.ida XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX XXXXXXXXXXXXXXXXXXX%u9090%u6858%ucbd3%u7801%u9090%u6858%ucbd3%u7801%u9090 %u6858%ucbd3%u7801%u9090%u9090%u8190%u00c3%u0003%u8b00%u531b%u53ff%u0078%u0000%u00=a   
```  
注 : ログは 1 行です。
  
<codesnippet language displaylanguage containsmarkup="false"> GET /default.ida NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNN NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNN NNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNNN NNNNNNNNNNNNNNNN%u9090%u6858%ucbd3%u7801%u9090%u6858%ucbd3%u7801%u9090%u6858 %ucbd3%u7801%u9090%u9090%u8190%u00c3%u0003%u8b00%u531b%u53ff%u0078%u0000%u00=a   
```  
注 : ログは 1 行です。
  
ログファイルの記録方法によっては、以下のように残る場合もあります。
  
<codesnippet language displaylanguage containsmarkup="false"> GET /default.ida GET /default.ida   
```  
上記以外につきましても、拡張子 ida および idq へのアクセスは Code Red または同様のワーム等による攻撃を受けている可能性があります。また、ファイアウォール製品、プロキシ製品 および ウィルス検出ソフトは、Code Red ワームによるセキュリティ攻撃に対しては、有効では無い場合が大半である点にご注意ください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 対処方法 (Windows NT 4.0/Small Business Server 4.5)
  
**対象環境**  
Microsoft Windows NT 4.0 Option Pack のインストールされている Windows NT Server 4.0 または Windows NT Server Enterprise Edition 4.0 および Small Business Server 4.5
  
下記の手順に従って対処を行ってください。
  
1.  **サービスパックの入手**  
    このワームに対して対処するための修正モジュールを適用するには、 Windows NT 4.0 Service Pack 6a が必要です。
  
    サービスパックは、以下から入手可能です。
  
    1.  Web からダウンロード  
        [http://www.microsoft.com/japan/products/ntupdate/nt4sp6/](http://www.microsoft.com/japan/ntserver/downloads/sp6a.mspx)
  
    2.  ダウンロード以外の入手方法  
        Windows NT 4.0 Service Pack 6a を収録した CD-ROM を有償で入手することができます。
  
        -   【オンラインでの申し込み】  
            [サービスパック オーダーセンター](http://www.microsoft.com/japan/products/shop/)で申込みをすることで有償で入手することができます。
  
        9 月 30 日にて、無償提供を終了させていただきました。ご了承ください。
  
2.  **修正モジュールの入手**  
    このワームに対する修正モジュールを含め多くのセキュリティ問題を解決するセキュリティ ロールアップ パッケージの適用をお勧めいたします。

 
    <table style="border:1px solid black;">
    <colgroup>
    <col width="100%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>推奨</strong> : Code Red と異なる脆弱性を利用する亜種 (Code Blue や Code Green) の発生が報告されておりますので、対策としてこれらの脆弱性に関してより包括的な対応となる <strong>SRP</strong> または <strong>MS01-044 の累積的な修正プログラム</strong>の適用をお勧めいたします。
    <a href="http://www.microsoft.com/downloads/details.aspx?displaylang=ja&amp;familyid=7dd8f695-fa97-4378-b57b-7bccf3533be3">http://www.microsoft.com/downloads/details.aspx?displaylang=ja&amp;FamilyID=7DD8F695-FA97-4378-B57B-7BCCF3533BE3</a><br />
    ダウンロード先のリストから Japanese Language Version を選択してください。</td>
    </tr>
    </tbody>
    </table>
 

    1.  「Windows NT 4.0 Service Pack 6a 以降のセキュリティ ロールアップ パッケージ (SRP) の提供を開始」
        <http://www.microsoft.com/japan/technet/archive/security/news/nt4srp.mspx>

        SRP 適用後に Compaq Smart アレイ コントローラの 1 つを搭載しているコンピュータで問題が発生する場合があることが確認されました。また、現在調査中ですが、Compaq 製以外のコンピュータでも同様の現象が発生する可能性がございます。OEM プレインストール製コンピュータをご利用のお客様も、SRP パッケージをご適用前に、以下の KB の内容をご参照ください。

        [JP305228](http://support.microsoft.com/default.aspx?scid=kb;ja;jp305228) Windows NT 4.0 セキュリティ ロールアップ パッケージ適用後 STOP 0xA 発生

    2.  特殊な事情などにより上記モジュールが適用できない場合は、Code Red ワームの問題にのみ対処可能な修正モジュールの適用をお願いいたします。

        **PC/AT 互換機用 :**
        [http://www.microsoft.com/downloads/details.aspx?displaylang=ja&FamilyID=440B6F36-1659-44AD-892D-14CD490C9AFD](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=440b6f36-1659-44ad-892d-14cd490c9afd)
        ダウンロード先のリストから Japanese Language Version を選択してください。

        **NEC PC-9800シリーズ用 :**
        [http://download.microsoft.com/download/winntsp/PatchNEC/q300972/NT4/JA/JPNQ300972n.exe](http://download.microsoft.com/download/winntsp/patchnec/q300972/nt4/ja/jpnq300972n.exe)

 
        <table style="border:1px solid black;">
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" >注 : 8 月 9 日に MS01-033 が再リリースされています。</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;">8 月 9 日に公開されたこの修正モジュールは、下記の 2 点が修正されています。
        <ul>
        <li>SP6a が適用されているコンピュータに対してのみ適用できます。</li>
        <li>SP6a と MS01-033 の適用順に関わらず、双方の修正が有効です。</li>
        </ul>
        この修正に関しましては、<a href="http://www.microsoft.com/japan/technet/security/bulletin/ms01-033.mspx"><strong>こちら</strong></a>でより詳細な情報を提供しております。現在 Microsoft サイトよりダウンロードできるこの修正モジュールはすべて 8 月 9 日に公開された新しい修正モジュールです。
        既に 8 月 8 日以前にリリースされた修正モジュールの適用を行っているお客様は、Code Red II ワームへの対策としては十分ですが、今後、一部の修正プログラムを適用する際に、8 月 9 日以降に公開された新しい修正プログラムを適用する必要があります。早い段階での新しい修正プログラムの適用をお勧めします。
        <strong>8 月 8 日以前の修正モジュールの破棄と新しい修正モジュールの適用方法</strong>
        <ol>
        <li>8 月 8 日以前にリリースされた修正モジュールをアンインストールします。</li>
        <li>8 月 9 日にリリースされた修正モジュールをインストールします。</li>
        </ol>
        この修正モジュールのリリース時期の判別につきましては、FAQ の「<a href="https://technet.microsoft.com/ja-jp/library/1ce261cd-67cb-452a-ad50-83018ed6072b(v=TechNet.10)">8 月 8 日以前に公開された Windows NT 用修正プログラムと、8 月 9 日以降に公開された Windows NT 用修正プログラムを見分ける方法はありますか ?</a>」をご覧ください。</td>
        </tr>
        </tbody>
        </table>
 

3.  **感染チェックツールの入手**
    感染する危険性をチェックするためのツールは、次の 2 社より提供されております。

    -   ワーム「CodeRED」セキュリティホール検知ツール (トレンドマイクロ社)
        [http://www.trendmicro.co.jp/esolution/solutionDetail.asp?solutionId=3057](http://www.trendmicro.co.jp/esolution/solutiondetail.asp?solutionid=3057)![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)

    -   Symantec Security Check - CodeRed Check (シマンテック社)
        <http://www.symantec.com/region/jp/securitycheck/index.html>![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)

    Windows NT 4.0 をお使いのお客様で SRP を適用して対策を行った場合、トレンドマイクロ社 / シマンテック社のチェックツールをご使用いただいた際に対策後においても警告が出る場合がございます。これは、チェックツールが、 MS01-033 の適用をを対策済みの要件としているために起こります。しかしながら、SRP の適用によっても同等の対策は行われるため、問題はございません。

4.  **ネットワークからの隔離**
    修正モジュールの適用中に再度の感染を防ぐために、ネットワークから切断します。LAN に接続されている場合は、 LAN ケーブルを抜いてください。ダイアルアップによる接続の場合は、 TA/モデム との接続ケーブルをはずしてください。

5.  **再起動**
    修正プログラムを確実に適用するために、メモリ上に存在している Code Red ワームをコンピューターの再起動により取り除きます。

6.  **サービスパックの適用**
    サービスパックを適用します。

7.  **再起動**
    サービスパックのセットアップにより、再起動を要求されますので、再起動してください。

8.  **修正モジュールの適用**
    再起動後、修正モジュールを適用します。

9.  **再起動**
    修正モジュールのセットアップにより自動的に再起動されます。

10. **感染の確認と駆除**
    現在、感染していないことを確認します。 確認方法およびツールの使用方法につきましては各社の Web ページをご参照ください。

    感染している場合の駆除方法につきましては、[駆除方法](#egaa)をご参照ください。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >NT 4.0 上で IIS 4.0 をご利用の環境において</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">URL リダイレクト機能を利用した Web サイトに対して Code Red ワームのような非常に長いリクエストが送信された場合に、IIS が異常終了する問題が確認されました。本問題は <a href="http://www.microsoft.com/japan/technet/security/bulletin/ms01-033.mspx">MS01-033</a> とは異なる原因により発生いたします。この問題の詳細および修正プログラムの入手方法につきましては、セキュリティ情報 <a href="http://www.microsoft.com/japan/technet/security/bulletin/ms01-044.mspx">MS01-044</a> をご覧ください。
尚、URL のリダイレクトは既定の状態では使用されておりません。</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[ページのトップへ](#mainsection)

### 対処方法 (Windows 2000/Small Business Server 2000)

**対象環境**
Microsoft Windows 2000 Server, Windows 2000 Advanced Server または Microsoft Windows 2000 Professional および Small Business Server version 2000

下記の手順に従って対処を行ってください。

1.  **サービスパックの入手**
    この脆弱性以外の問題にも合わせて対処するために、Windows 2000 Service Pack 2 の適用を強くお勧めいたします。

    Windows 2000 Service Pack 2 は、以下から入手可能です。

    1.  Web からダウンロード
        <http://www.microsoft.com/windows2000/downloads/servicepacks/sp2/sp2ja.mspx>

    2.  ダウンロード以外の入手方法
        Windows 2000 Service Pack 2 を収録した CD-ROM を有償で入手することができます。

        -   【オンラインでの申し込み】
            [サービスパック オーダーセンター](http://www.microsoft.com/japan/products/shop/)で申込みをすることで有償で入手することができます。

        9 月 30 日にて、無償提供を終了させていただきました。ご了承ください。

    特殊な事情などにより Service Pack 2 の適用が困難である場合は、Service Pack 1 をご適用ください。修正モジュールの適用には、 Service Pack 1 以降が必要です。

    **Windows 2000 Service Pack 1 日本語版 :**
    <http://www.microsoft.com/japan/windows2000/downloads/servicepacks/sp1/>

 
    <table style="border:1px solid black;">
    <colgroup>
    <col width="100%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>注意</strong> : W2k SP1, SP2 で多数の修正が行われております。 安定した稼動を行うためには、<strong>全てのサーバーで SP1、SP2 のいずれかに統一して</strong>運用していただくことを強く推奨いたします。</td>
    </tr>
    </tbody>
    </table>
  
2.  **修正モジュールの入手**  
    このワームに対処するための修正モジュールは以下からダウンロード可能です。Code Red と異なる脆弱性を利用する亜種 (Code Blue や Code Green) の発生が報告されておりますので、対策としてこれらの脆弱性に関してより包括的な対応となる修正プログラムの適用をお勧めいたします。
  
    **PC/AT 互換機用 :**  
    [http://www.microsoft.com/downloads/details.aspx?displaylang=ja&FamilyID=F74552AC-4313-4F93-9412-539DCA0753EB](http://www.microsoft.com/downloads/details.aspx?displaylang=ja&familyid=f74552ac-4313-4f93-9412-539dca0753eb)  
    ダウンロード先のリストから Japanese を選択してください。
  
    **NEC PC-9800シリーズ用 :**  
    [http://download.microsoft.com/download/winntsp/PatchNEC/q300972/NT4/JA/JPNQ300972n.exe](http://download.microsoft.com/download/winntsp/patchnec/q300972/nt4/ja/jpnq300972n.exe)  
    ダウンロード先のリストから Japanese NEC を選択してください。
  
3.  **感染チェックツールの入手**  
    感染する危険性をチェックするためのツールは、次の 2 社より提供されております。
  
    -   Symantec Security Check - CodeRed Check  
        <http://www.symantec.com/region/jp/securitycheck/index.html>![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
    -   ワーム「CodeRED」セキュリティホール検知ツール  
        [http://www.trendmicro.co.jp/esolution/solutionDetail.asp?solutionId=3057](http://www.trendmicro.co.jp/esolution/solutiondetail.asp?solutionid=3057)![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
4.  **ネットワークからの隔離**  
    修正モジュールの適用中に再度の感染を防ぐために、ネットワークから切断します。LAN に接続されている場合は、 LAN ケーブルを抜いてください。ダイアルアップによる接続の場合は、 TA/モデム との接続ケーブルをはずしてください。
  
5.  **再起動**  
    修正プログラムを確実に適用するために、メモリ上に存在している Code Red ワームをコンピューターの再起動により取り除きます。
  
6.  **サービスパックの適用**  
    サービスパックを適用します。
  
7.  **再起動**  
    サービスパックのセットアップにより、再起動を要求されますので、再起動してください。
  
8.  **修正モジュールの適用**  
    再起動後、修正モジュールを適用します。
  
9.  **再起動**  
    修正モジュールのセットアップにより自動的に再起動されます。
  
10. **感染の確認と駆除**  
    現在、感染していないことを確認します。 確認方法およびツールの使用方法につきましては各社の Web ページをご参照ください。
  
    感染している場合の駆除方法につきましては、[駆除方法](#extermination)をご参照ください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 対処方法 (サービスパックまたは修正モジュールの適用が困難な場合)
  
サービスパックや、修正モジュールの適用がアプリケーションの互換性やお客様の運用ポリシーにより不可能である場合、以下の方法で問題を緩和することが可能です。
  
しかしながら、以下の方法は根本的な対処ではなく応急的な対処であるため、設定の変更やアプリケーションのインストールにより問題を再発させる危険があります。また、お客様の Web サイトで、Index Server の検索コンポーネント idq.dll を利用している場合には、これらの機能を使用することが不可能となりますので、ご注意ください。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>注</strong> : 以下の製品 および 機能は、.idq, .ida へのアプリケーションマッピングを使用します。そのため以下をご利用のお客様は必ず 対処方法 (Windows 2000) に従った対処が必要となります。
<ul>
<li>Microsoft SharePoint Portal Server 2001</li>
<li>Microsoft Exchange 2000 Server の OWA 機能</li>
<li>Microsoft FrontPage Server Extensions</li>
<li>Microsoft SharePoint Team Services (Office XP 付属機能)</li>
</ul></td>
</tr>
</tbody>
</table>
 

#### アプリケーションマッピングの削除

idq および ida に対するリクエストを IIS が処理しない設定にすることで対処する方法です。

作業を行っていただきます前に、[IIS の構成情報のバックアップと復元](#efaa)をご覧になり、バックアップを作成していただくことをお勧めいたします。

1.  インターネット サービス マネージャ を起動します。

    Windows NT 4.0 では、**\[スタート\]** - **\[Windows NT 4.0 Option Pack\]** - **\[Microsoft Internet Information Server\]** - **\[インターネット サービス マネージャ\]** を選択します。Windows 2000 では、**\[スタート\]** - **\[設定\]** - **\[コントロールパネル\]** - **\[管理ツール\]** - **\[インターネット サービス マネージャ\]** を選択します。

2.  コンピューター名を選択し、プロパティを開きます。

    ![](images/Dd362800.Image_not_found(ja-jp,TechNet.10).gif)

3.  **\[インターネット インフォメーション サービス\]** タブを選択します。

    ![](images/Dd362800.Image_not_found(ja-jp,TechNet.10).gif)

4.  **\[マスタプロパティ\]** リストボックスから &lt;WWW サービス&gt; を選択し、**\[編集\]** ボタンをクリックします。

5.  **\[ホームディレクトリ\]** タブを選択します。

    ![](images/Dd362800.Image_not_found(ja-jp,TechNet.10).gif)

6.  **\[構成\]** ボタンをクリックします。

7.  **\[アプリケーションのマッピング\]** タブを選択します。

    ![](images/Dd362800.Image_not_found(ja-jp,TechNet.10).gif)

8.  アプリケーションのマッピングの一覧から、.ida を選択し、**\[削除\]** ボタンをクリックします。

9.  アプリケーションのマッピングの一覧から、.idq を選択し、**\[削除\]** ボタンをクリックします。

10. **\[OK\]** ボタンをクリックします。

11. "継承/優先" ダイアログが表示される場合があります。表示された場合は、12. に進む前に、下記の 継承/優先 ダイアログの対処方法 をお読みください。

12. **\[OK\]** ボタンをクリックし、マスタプロパティを閉じます。

13. **\[OK\]** ボタンをクリックし、プロパティを閉じます。

14. 以上で作業終了です。インターネット サービス マネージャ を終了させてください。

**-- 継承/優先 ダイアログの対処方法です**

"継承/優先" ダイアログ には、マスタプロパティと違う設定のサイトやノードがある場合に表示され、その一覧が表示されます。

このダイアログが表示された場合、対応方法は、2 つあります。

1.  全てのノードをマスタプロパティと同じ設定に統一する。

    1.  **\[すべて選択(S)\]** ボタンをクリックします。

    2.  **\[OK\]** ボタンをクリックし、継承/優先 ダイアログを閉じます。

2.  個別に、idq, ida の設定を行う。

    個別に行う場合は、マスタプロパティに行った設定を、各ノードに対してひとつづつ行っていく必要があります。設定方法につきましては、マスタプロパティと同様です。

この方法では、 IIS の再インストールを行った場合に .ida .idq の設定が元に戻るために新たに対処する必要があります。

[](#mainsection)[ページのトップへ](#mainsection)

### 駆除方法

駆除が必要な場合は、 Code Red ワームにより設置されたトロイの木馬の削除と変更されたレジストリを修復する必要があります。

 
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Code Red II ワームの既知の影響を排除するツールをリリースしました。本ツールは Code Red II によって受けた影響のみ排除することを目的として提供されていることに注意してください。他の新種のワームの影響は排除しません。ツールの入手方法と作業手順は、<a href="http://technet.microsoft.com/library/dd277360.aspx">こちら</a>を参照してください。ツールの利用を行わず、手作業による駆除を行う場合は、以降の手順に従ってください。</td>
</tr>
</tbody>
</table>
  
#### トロイの木馬の停止、及び再起動の予防方法
  
起動しているトロイの木馬の停止と再度動き出すことを予防します。この作業は、一度ログオフする必要があります。
  
1.  **\[スタート\] - \[プログラム\] - \[コマンドプロンプト\]** を起動します。 以下は、コマンドプロンプトでの操作となります。
  
2.  C: と入力しリターンキーを入力します。
  
3.  cd \\ と入力しリターンキーを入力します。
  
4.  dir /ah と入力しコマンドプロンプトに表示されるファイルの一覧に explorer.exe があるかを確認します。  
    ファイルがある場合は 手順 5、6 の操作を行う必要があります。
  
5.  attrib -h -s explorer.exe と入力しリターンキーを入力します。
  
6.  ren explorer.exe explorer.bin と入力しリターンキーを入力します。
  
7.  D: と入力しリターンキーを入力します。
  
8.  cd \\ と入力しリターンキーを入力します。
  
9.  dir /ah と入力しコマンドプロンプトに表示されるファイルの一覧に explorer.exe があるかを確認します。  
    ファイルがある場合は 手順 10、11 の操作を行う必要があります。
  
10. attrib -h -s explorer.exe と入力しリターンキーを入力します。
  
11. ren explorer.exe explorer.bin と入力しリターンキーを入力します。
  
12. ログオフします。
  
13. 再度ログオンします。
  
#### トロイの木馬の削除
  
Code Red ワームは、トロイの木馬を含めて下記の最大 2 種類のファイルを設置します。
  
-   explorer.exe(トロイの木馬の停止、及び再起動の予防方法 にて行った操作で、 explorer.bin に名称が変更されています)
  
-   root.exe
  
explorer.exe については、Windows NT/2000 の正規のコンポーネントとファイル名が同一ですのでご注意ください。
  
1.  **\[スタート\] - \[プログラム\] - \[コマンドプロンプト\]** を起動します。 以下は、コマンドプロンプトでの操作となります。
  
2.  C: と入力しリターンキーを入力します。
  
3.  cd \\ と入力しリターンキーを入力します。
  
4.  dir と入力しコマンドプロンプトに表示されるファイルの一覧に explorer.bin があるかを確認します。  
    ファイルがある場合は 手順 5 の操作を行う必要があります。
  
5.  del /f explorer.bin と入力しリターンキーを入力します。
  
6.  D: と入力しリターンキーを入力します。
  
7.  cd \\ と入力しリターンキーを入力します。
  
8.  dir /ah と入力しコマンドプロンプトに表示されるファイルの一覧に explorer.bin があるかを確認します。  
    ファイルがある場合は、手順 9 の操作を行う必要があります。
  
9.  del /f explorer.bin と入力しリターンキーを入力します。
  
10. C: と入力しリターンキーを入力します。
  
11. cd \\inetpub\\Scripts と入力しリターンキーを入力します。
  
12. dir /ah と入力しコマンドプロンプトに表示されるファイルの一覧に root.exe があるかを確認します。  
    ファイルがある場合は、手順 13、14 の操作を行う必要があります。
  
13. attrib -h -s root.exe と入力しリターンキーを入力します。
  
14. del /f root.exe と入力しリターンキーを入力します。
  
15. cd \\Program Files\\Common Files\\system\\MSADC と入力しリターンキーを入力します。
  
16. dir /ah と入力しコマンドプロンプトに表示されるファイルの一覧に root.exe があるかを確認します。  
    ファイルがある場合は、手順 17、18 の操作を行う必要があります。
  
17. attrib -h -s root.exe と入力しリターンキーを入力します。
  
18. del /f root.exe と入力しリターンキーを入力します。
  
19. D: と入力しリターンキーを入力します。
  
20. cd \\inetpub\\Scripts と入力しリターンキーを入力します。
  
21. dir /ah と入力しコマンドプロンプトに表示されるファイルの一覧に root.exe があるかを確認します。  
    ファイルがある場合は、手順 22、23 の操作を行う必要があります。
  
22. attrib -h -s root.exe と入力しリターンキーを入力します。
  
23. del /f root.exe と入力しリターンキーを入力します。
  
24. cd \\Program Files\\Common Files\\system\\MSADC と入力しリターンキーを入力します。
  
25. dir /ah と入力しコマンドプロンプトに表示されるファイルの一覧に root.exe があるかを確認します。  
    ファイルがある場合は、手順 26、27 の操作を行う必要があります。
  
26. attrib -h -s root.exe と入力しリターンキーを入力します。
  
27. del /f root.exe と入力しリターンキーを入力します。
  
28. exit と入力しリターンキーを入力し、コマンドプロンプトを終了させます。
  
#### 仮想ディレクトリの削除と修復
  
作業を行っていただきます前に、[IIS の構成情報のバックアップと復元](#efaa)をご覧になり、バックアップを作成していただくことをお勧めいたします。
  
1.  インターネット サービス マネージャ を起動します。
  
    Windows NT 4.0 では、**\[スタート\] - \[Windows NT 4.0 Option Pack\] - \[Microsoft Internet Information Server\] - \[インターネット サービス マネージャ\]** を選択します。Windows 2000 では、**\[スタート\] - \[設定\] - \[コントロールパネル\] - \[管理ツール\] - \[インターネット サービス マネージャ\]** を選択します。
  
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
  
9.  仮想ディレクトリ "C" が存在する場合には、削除します。
  
10. 仮想ディレクトリ "D" が存在する場合には、削除します。
  
11. インターネット サービス マネージャ を終了させてください。
  
#### レジストリの修復
  
1.  **\[スタート\]** - **\[ファイル名を指定して実行(R)\]** をクリックし、"ファイル名を指定して実行" ダイアログを開きます。
  
2.  名前 (O): に regedit と入力します。
  
3.  **\[OK\]** ボタンをクリックします。
  
4.  マイコンピューター の横にある ![](images/Dd362800.plus(ja-jp,TechNet.10).gif) マークをクリックするとマークが に変わりマイコンピューターの内容を表示します。
  
5.  手順 4. と同様の操作で、再度 マイコンピュータから HKEY\_LOCAL\_MACHINE、SOFTWARE、Microsoft、Windows NT、CurrentVersion、Winlogon と順に開きます。
  
6.  最後に開いた Winlogon を選択し、右側に格納されている情報を表示します。
  
7.  名前が SFCDisable のものがある場合には、データを確認し、0xffffff9d になっている場合は、0 に変更してください。
  
8.  レジストリエディタを終了します。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### IIS の構成情報のバックアップと復元
  
お客様の環境において、アプリケーションマッピングの削除や、仮想ディレクトリの変更により Web アプリケーションやコンテンツに異常が出た場合、すばやくそして簡単に復旧できるよう構成のバックアップをお勧めいたします。
  
#### IIS 構成情報のバックアップ
  
1.  インターネット サービス マネージャ を起動します。
  
    Windows NT 4.0 では、\[スタート\] - \[Windows NT 4.0 Option Pack\] - \[Microsoft Internet Information Server\] - \[インターネット サービス マネージャ\] を選択します。Windows 2000 では、\[スタート\] - \[設定\] - \[コントロールパネル\] - \[管理ツール\] - \[インターネット サービス マネージャ\] を選択します。
  
2.  コンピューター名を選択し、構成のバックアップ/復元 を選択します。
  
3.  **\[バックアップの作成(C)...\]** ボタンをクリックし、構成のバックアップ ダイアログを表示します。
  
4.  構成のバックアップ名に、適当な名前を入力します。
  
    例) codered-backup
  
5.  **\[OK\]** ボタンをクリックします。
  
6.  バックアップ 一覧に作成したバックアップが追加されていることを確認します。
  
7.  **\[閉じる\]** ボタンをクリックします。
  
#### IIS 構成情報の復元
  
1.  インターネット サービス マネージャ を起動します。
  
    Windows NT 4.0 では、\[スタート\] - \[Windows NT 4.0 Option Pack\] - \[Microsoft Internet Information Server\] - \[インターネット サービス マネージャ\] を選択します。Windows 2000 では、\[スタート\] - \[設定\] - \[コントロールパネル\] - \[管理ツール\] - \[インターネット サービス マネージャ\] を選択します。
  
2.  コンピューター名を選択し、構成のバックアップ/復元 を選択します。
  
3.  "IIS 構成情報のバックアップ" で作成したバックアップを選択します。
  
4.  **\[復元\]** ボタンをクリックします。
  
5.  以下のメッセージが表示されます。
  
    <codesnippet language displaylanguage containsmarkup="false">復元は長く時間のかかる操作です。 現在のすべての構成を削除し、すべてのサービスを停止させて、再起動させます。 続行しますか ?  
```
  
6.  現在の構成と、復元するバックアップをよく確認し、問題が無ければ **\[はい\]** ボタンをクリックします。
  
7.  マウスカーソルが 砂時計 になり、復元が開始されます。
  
8.  復元が終了すると、以下のメッセージが表示されます。
  
    <codesnippet language displaylanguage containsmarkup="false">操作は正常に終了しました。  
```
  
9.  **\[閉じる\]** ボタンをクリックします。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### ファイアウォール製品について
  
ファイアウォールに保護された環境においても、HTTP アクセスを一部でも許可している場合には攻撃を防ぐことができません。
  
Code Red ワームは、特別なポートを開くことなく、通常のリクエストを装って、 Web サーバーに到達し感染するため、ワームよって発信されたリクエストはファイアウォール自身を通過することができます。管理者はファイアウォールの設定を再確認する必要があります。
  
ファイアウォール製品の中には、リクエストの内容を検証し不正なリクエストを遮断する機能を持っているものもありますが、その場合につきましても Code Red 用の設定が別途必要になります。 各ファイアウォール製品の仕様・設定方法につきましては、販売店、納入業者、メーカーサポート等にお問い合わせいただきますようお願いいたします。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### プロキシ製品について
  
プロキシ製品につきましても、ファイアウォール製品と同様の理由により Code Red ワームに対処することができません。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### ウィルス検出ソフトについて
  
基本的にウィルス検出ソフトにつきましては、 Code Red ワームのセキュリティ攻撃に対して有効に機能しない場合があります。
  
お客様の安全のために、ウィルス検出ソフトを導入していただいております場合も対策をお願いいたします。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 関連情報
  
TechNet セキュリティ センター  
<http://www.microsoft.com/japan/technet/security/>
  
緊急 : Code Red ワームに対する警告 - 至急修正プログラムをインストールして下さい。-  
<http://technet.microsoft.com/library/dd362798.aspx>
  
"Code Red" IIS ワームに関する情報  
<http://technet.microsoft.com/library/dd362801.aspx>
  
Code Red II ワームの既知の影響を排除するツール  
<http://technet.microsoft.com/library/dd277360.aspx>
  
Windows 2000 Professional 用 Code Red ワーム対策ガイド  
<http://technet.microsoft.com/library/dd362802.aspx>
  
よくある質問と回答  
<http://technet.microsoft.com/library/dd362362.aspx>
  
Index Server ISAPI エクステンションの未チェックのバッファにより Web サーバーが攻撃される (MS01-033)  
[http://www.microsoft.com/japan/technet/security/bulletin/MS01-033.mspx](http://www.microsoft.com/japan/technet/security/bulletin/ms01-033.mspx)
  
マイクロソフト セキュリティ情報：用語集  
<http://www.microsoft.com/japan/security/glossary.mspx>
  
System File Protection 機能  
<http://www.microsoft.com/japan/msdn/windows/>
  
TREND Micro CodeRED.A  
[http://www.trendmicro.co.jp/virusinfo/default3.asp?VName=CodeRED%2EA](http://www.trendmicro.co.jp/virusinfo/default3.asp?vname=codered%2ea)![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
TREND Micro CodeRED.B  
[http://www.trendmicro.co.jp/virusinfo/default3.asp?VName=CodeRED%2EB](http://www.trendmicro.co.jp/virusinfo/default3.asp?vname=codered%2eb)![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
TREND Micro CodeRED.C  
[http://www.trendmicro.co.jp/virusinfo/default3.asp?VName=CodeRED%2EC](http://www.trendmicro.co.jp/virusinfo/default3.asp?vname=codered%2ec)![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
Trendmicro CodeRED.C 自動駆除ツール  
[http://www.trendmicro.co.jp/esolution/solutionDetail.asp?solutionId=3067](http://www.trendmicro.co.jp/esolution/solutiondetail.asp?solutionid=3067)![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
CodeRed Worm  
<http://www.symantec.com/region/jp/sarcj/data/c/codered_worm.html>![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 本件に関する一般ユーザー様向け問い合わせ窓口
  
今回の Code Red ワームの問題に対し、弊社ではマイクロソフト Web サイトでの本文書による IIS セキュリティ対策の告知とともに、「マイクロソフト IIS セキュリティ情報センター」を設置いたしました。当窓口では IIS のセキュリティパッチ適用に関し本文書や関連する弊社 Web サイト上の情報だけではわかりづらいといった場合のご質問や IIS Web ページ改ざんに関する技術的対応方法の情報提供を目的としております。通常の製品サポートを行うものではありませんので、Code Red ワーム以外のお問い合わせにつきましては、当センターではお答えいたしかねますことをご理解願います。また、ご質問の内容によりましては弊社の有償サポートをご案内させていただくこともあります。当センターの主旨を是非ご理解いただきご利用くださいますようお願い申し上げます。
  
セキュリティ情報に関する窓口
  
Microsoft セキュリティ情報センターでは、セキュリティに関するお問い合わせをお受けします。  
詳細については以下のホームページをご参照ください。
  
Microsoft セキュリティ情報センター  
<http://www.microsoft.com/japan/security/sicinfo/default.mspx>
  
**ご利用方法 :**  
弊社 IIS をお使いの正規ユーザーに限ります。お名前、ご住所、電話番号、E メールアドレスをお伺いいたしますのでご了承ください。
  
**注意事項 :**  
セキュリティ対策作業実施に伴う、お客様のアプリケーション稼働環境保証、検証等は当窓口ではお答えできかねます。Web サイト公開情報をもとに、お客様自らテストを実施するか、ソフトウェアベンダー様やシステムインテグレーター様にお問い合わせいただくようお願い申し上げます。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 関連リンク
  
-   [Code Red IIS ワームに関する情報 (概略)](https://technet.microsoft.com/ja-jp/library/6f2181fc-63dc-47ba-bef8-274dcf46e2f5(v=TechNet.10))  
-   [Code Red ワームに対する警告](https://technet.microsoft.com/ja-jp/library/51c63253-c045-480f-9559-67c7c47c47e6(v=TechNet.10))  
-   [Code Red による深刻な問題に対する防護策と対処方法についての説明](https://technet.microsoft.com/ja-jp/library/d0803687-3916-46c2-a9e2-47183f757099(v=TechNet.10))  
-   [Code Red II ワームの既知の影響を排除するツール](https://technet.microsoft.com/ja-jp/library/703ec83e-ddb5-4632-b70c-65557bf014fe(v=TechNet.10))  
-   [Windows 2000 Professional 用 Code Red ワーム対策ガイド](https://technet.microsoft.com/ja-jp/library/965ef673-a989-486b-af44-4dcfe294127d(v=TechNet.10))  
-   [よくある質問と回答](https://technet.microsoft.com/ja-jp/library/1ce261cd-67cb-452a-ad50-83018ed6072b(v=TechNet.10))  
-   [更新履歴](https://technet.microsoft.com/ja-jp/library/d0803687-3916-46c2-a9e2-47183f757099(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
  
**関連サイト**
  
-   [株式会社シマンテック](http://www.symantec.com/ja/jp/security_response/writeup.jsp?docid=2001-071911-5755-99)![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
-   [トレンドマイクロ株式会社](http://www.trendmicro.co.jp/esolution/solutiondetail.asp?solutionid=3057)![](images/Dd362800.leave-ms(ja-jp,TechNet.10).gif)
  
[](#mainsection)[ページのトップへ](#mainsection)
