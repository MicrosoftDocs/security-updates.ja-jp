---
TOCTitle: 第 11 回 危険度には個人差があります ～ Security Risk Management ～ システムと脆弱性の関係
Title: 第 11 回 危険度には個人差があります ～ Security Risk Management ～ システムと脆弱性の関係
ms:assetid: '27eb4541-52f8-4b5c-849c-d18f6b5d7901'
ms:contentKeyID: 19871865
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362920(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 11 回 危険度には個人差があります ～ Security Risk Management ～ システムと脆弱性の関係

公開日: 2006年11月22日

![](images/Dd362920.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社  
セキュリティ レスポンス チーム  
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/fc0c06dd-be94-4620-a7f6-38b3971f0627(v=TechNet.10))は、脆弱性の危険度を判断する基本的な方法についてお話しました。

さて、今回はシステム全体を見た場合に脆弱性の危険度がどのように変化するのかについて考えてみます。脆弱性は、システムを構成する各部分々々に存在します。その脆弱性のある部分を含めてシステム全体で評価した場合に悪用される可能性がある場合は、システムの脆弱性ともいうことができますが、システムの他の機能や制限により悪用される可能性がない場合は、システムとして考えた場合に脆弱性はないと評価します。

このように、部分としての脆弱性を、システムとしての脆弱性ではなくしてしまう機能や要素がセキュリティ情報やセキュリティ アドバイザリにある「緩和される要素」です。

たとえば、サーバー サービスの特にファイル共有に関るような脆弱性が発見されたと仮定します。その場合、ファイル サーバーにとっては、一般に緩和する余地のない危険度の高い脆弱性となります。クライアント PC にとっては、必ずしもファイル共有の提供側になる必要があるわけではありません。最小限のサービスで動作しており、サーバー サービスが無効化されているような環境では、危険はないこととなります。もし、無効化されていない場合でも、一時的に無効化することで、対策が完了するまでのリスクを低く抑えることが可能です。

この様な機能の取捨選択や制限により危険度を評価することが可能ですが、システムとしてみた場合には、もうひとつの観点があります。

それは、システムまたは、脆弱性のある部分が、何を扱っており何のためのシステム・機能なのかという観点です。たとえば、ショッピング サイトのシステムに脆弱性があれば、社内のファイル サーバーよりは、危険度が高くなります。また、情報漏えいの脆弱性が、顧客管理システムにあれば危険度は非常に高いものとなりますが、他のシステムでは、それほど危険度は高くならない場合もあります。

この判断を、適切に行うことは、脆弱性が発見された場合でもシステムへの影響や停止時間を最小限に抑えることができます。しかしそのためには、事前にシステムに対する脅威モデルを把握しておくことが重要になります。

脅威モデルの詳細については、関連資料を見ていただくとして、簡易的に脅威モデルを作る方法として、各機能単位や外部から操作できる部分 (エントリーポイント) 毎に、STRIDE モデルに従った脅威の可能性を割り当てていきます。

 <p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >脅威</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">なりすまし<br />
(Spoofing identity)</td>
<td style="border:1px solid black;">不正にアクセス権を取得して、別のユーザーの認証情報 （ユーザー名とパスワードなど） を使用すること。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">データの改ざん<br />
(Tampering with data)</td>
<td style="border:1px solid black;">データに悪意のある変更を行うこと。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">否認<br />
(Repudiation)</td>
<td style="border:1px solid black;">ユーザーがある操作を実行することを拒否されることで、そのことを他人に証明する手段がない状態のこと。&quot;否認防止&quot; は、否認の脅威に対抗するシステムの能力を指します (小包を受け取ったときに署名するようなことで、小包の受け取り手はこれを証拠として使用できます)。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">情報漏洩<br />
(Information disclosure)</td>
<td style="border:1px solid black;">情報へのアクセス権を持たない個人に情報が公開されること。たとえば、適切な権利なしにファイルにアクセスすること。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">サービス拒否<br />
(Denial of service)</td>
<td style="border:1px solid black;">正当なユーザーがサービスやシステムを使用できないようにする、意図的な試み。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">特権の昇格<br />
(Elevation of privilege)</td>
<td style="border:1px solid black;">特権を持たないユーザーがアクセス権を獲得すること。特権の不正取得の一例には、特権のないユーザーを Administrators グループに追加する手段を考案することなどがあります。</td>
</tr>
</tbody>
</table>
  
そして、各脅威が発生した場合に、取りうる対処方法や事故対応の方法をまとめることで、脆弱性が発見され、脅威が顕在化してから慌てる必要はなくなります。さらに、脅威モデルを突き詰めて情報単位で脅威の分析が行われる情報資産の管理まで行えれば理想的です。
  
**関連サイト：**
  
-   [更新プログラム管理](https://technet.microsoft.com/ja-jp/library/4cd8ee12-7d73-4b1e-a11d-ec34e80515ec(v=TechNet.10))
  
-   [セキュリティ情報検索](http://www.microsoft.com/japan/technet/security/current.aspx)
  
-   [Microsoft セキュリティ修正プログラム管理ガイド (第 1 部)](http://www.microsoft.com/japan/technet/archive/security/topics/patch/p1ch1.mspx)
  
-   [セキュリティ上の脅威の評価](http://msdn.microsoft.com/library/ms172104.aspx)
  
-   [脅威モデルを作成する](https://technet.microsoft.com/ja-jp/library/bff621a7-5afe-42fa-98c0-20a750241f76(v=TechNet.10))
  
[![](images/Dd362920.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))
  
この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### バックナンバー
  
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
