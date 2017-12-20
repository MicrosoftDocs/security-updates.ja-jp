---
TOCTitle: '第 10 回 危険度には個人差があります ～ Security Risk Management ～ 脆弱性の何が危ない？'
Title: '第 10 回 危険度には個人差があります ～ Security Risk Management ～ 脆弱性の何が危ない？'
ms:assetid: 'fc0c06dd-be94-4620-a7f6-38b3971f0627'
ms:contentKeyID: 19871864
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362919(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 10 回 危険度には個人差があります ～ Security Risk Management ～ 脆弱性の何が危ない？

最終更新日: 10月 25, 2006

![](images/Dd362919.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/145cdb1b-04e9-4d7e-8c65-78aa590a87ca(v=TechNet.10))は、セキュリティ更新の適用に際して適用先のシステムの重要度別に適用のタイミングを考える基本的な考え方についてお話しました。この中で重要度 3 のシステムについて、テストなしで適用するのは無謀ではないかという指摘を、管理者である読書の方からいただきました。この指摘は、管理者として正常な判断だと思いますし、可能であるならば最小限度のテストを行うに越したことはありません。テストなしの配布は、問題発生時の対処とリカバリーが十分に行える体制において、実環境を用いてテストを行う方法であるとも言えますので、適応可能な組織は多くはないのが現実だとおもいます。

さて、今回はシステムではなく脆弱性自体の危険度を、マイクロソフトのセキュリティ情報からどの様に読み解くかを考えて見ます。脆弱性はシステムと組み合わせて評価した場合にのみ危険度を正しく見積もることが可能になりますが、今回はシステムとの組み合わせを考慮せずに、一般論として考えていきます。

まず、脆弱性が悪用された場合にどのような結果をもたらすものかを考えます。それを知るには、セキュリティ情報の \[要点\] - \[深刻度および脆弱性識別番号\] の表を参照し、各脆弱性の \[脆弱性の影響\] を確認します。この影響が、悪用された結果として何が起こるのかを分類しており、以下の様になります。

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >危険度</th>
<th style="border:1px solid black;" >脆弱性の影響</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">(高)
(低)</td>
<td style="border:1px solid black;"><ul>
<li>リモートでコードが実行される</li>
<li>(ローカルで) コードが実行される</li>
<li>特権の昇格</li>
<li>情報漏えい</li>
<li>サービス妨害 (DoS)</li>
</ul></td>
</tr>
</tbody>
</table>
 

あえて、危険度に差をつけていますが、システムによっては危険度が変化することを頭の片隅に残しておく必要があります。たとえば、個人情報や医療情報を扱うようなシステムの場合、情報漏えいは、コードの実行以上に危険と判断される可能性もあります。一般論としては、攻撃の自由度が高いという意味でコード実行の危険度が高くなります。

次に、どのような経路で脆弱性が悪用され攻撃が成立するのかを考えます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >危険度</th>
<th style="border:1px solid black;" >経路</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">(高)
(低)</td>
<td style="border:1px solid black;"><ul>
<li>インターネット</li>
<li>LAN 等のネットワーク</li>
<li>ローカル コンソール</li>
<li>メール等の添付として</li>
<li>物理メディアによる持ち込み</li>
</ul></td>
</tr>
</tbody>
</table>
 

これに関して、おのおの見解が分かれるところかもしれませんが、今回はこの順序で考えます。このリストは各組織やシステムに合わせてカスタマイズしてみてください。

基本的な考え方として、攻撃経路が対象となる PC やサーバーに対してネットワーク等を通じて遠隔から操作できる場合ほど危険度が高くなります。物理メディアによる脆弱性の悪用には、そのシステムの前まで赴き、その上で実行する必要があり、危険度は緩和されます。

最後に誰が悪用する (攻撃する) のかを考えます。実際に攻撃を行う個人や団体を特定するのではなく、不特定多数 (匿名ユーザー)、認証ユーザーなどが攻撃可能かを考えます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >危険度</th>
<th style="border:1px solid black;" >誰が？どのような人が？</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">(高)
(低)</td>
<td style="border:1px solid black;"><ul>
<li>匿名で・・・</li>
<li>特定の権限を持った・・・</li>
<li>認証された・・・</li>
<li>コンソールにログオンした・・・</li>
</ul></td>
</tr>
</tbody>
</table>
 

ここでは、匿名などの「だれでも」悪用できる状況をもっとも危険度 \[高\] にしています。この情報は、セキュリティ情報の \[脆弱性の詳細\] – \[(各脆弱性の) よく寄せられる質問\] の中から、「どのように攻撃者はこの脆弱性を悪用する可能性がありますか?」に注目することで確認可能です。

これらの項目を組み合わせると、「インターネットから/匿名ユーザーが/リモートでコードが実行される」脆弱性がもっとも危険度が高く、過去の大きなセキュリティ インシデントの原因にもなっています。現実には、インターネットや LAN からの直接攻撃は、ホストベースでのファイアウォールの普及により大きくその危険度を下げているとも考えられ、技術で防御することが困難なメールの添付等を悪用した、詐欺的 (ソーシャル エンジニアリング) な攻撃がより危険度を増しています。

現状や組織内の状況を鑑みつつ、脆弱性の危険度を評価するためのパターンを確立することが理想的です。

次回は、脆弱性とシステムを組み合わせたときの危険度の変化について触れます。

**関連サイト：**

-   [更新プログラム管理](http://technet.microsoft.com/ja-jp/updatemanagement/default.aspx)

-   [セキュリティ情報検索](http://www.microsoft.com/japan/technet/security/current.aspx)

[![](images/Dd362919.btn_reg_today(ja-jp,TechNet.10).jpg) この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)

##### バックナンバー

-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
