---
TOCTitle: セキュリティ対策の要点解説 第 1 回 セキュリティ対策の土台 ～ Defense In Depth ～
Title: セキュリティ対策の要点解説 第 1 回 セキュリティ対策の土台 ～ Defense In Depth ～
ms:assetid: 'ce17755a-1971-4f61-852c-7baf2bae36f1'
ms:contentKeyID: 19871855
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362910(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 1 回 セキュリティ対策の土台 ～ Defense In Depth ～

公開日: 2006年1月25日

![](images/Dd362910.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

今月より、新コーナーとして、「セキュリティの要点設定」をネタが尽きるまでお届けします。今回は、具体的なセキュリティ設定ではなく、セキュリティを考える上で重要な、マイクロソフト製品の基本的な考え方にもなっている ”多層防御 (Defense In Depth)” についてです。”多層防御” (またの名を 「縦深防御」)とは、攻撃に対して防御を直列に並べて階層的に対処することで、機密情報 (守るべきもの) への被害を最小にするというアプローチです。

1 つの方法 (層) のみで最高のセキュリティを目指す道もあるのですが、100% の安全性を確保することは現実的に考えて不可能と言えます。また、1 つの方法では、突破された場合に即手遅れとなります。そこで、複数の方法を重ね合わせて多層化することで、1 つが突破されても別の方法で防御しようというのが多層防御です。

また、多層防御の別の側面として運用への効果もあります。たとえば、1 つの方法で攻撃を検出しようとすると、センサーの感度調整が難しくなる傾向があります。誤検出 (False-Positive) を嫌ってセンサーの感度を緩めれば見逃し (False-Negative) が増えてセンサーの意味がなくなり、誤検出が増えすぎれば本当の攻撃を検出したときに、誤検出に埋もれたりする危険も増えます。多層的であれば、最外層のセンサーの感度はバランスを重視し、2 層目のセンサーの感度を敏感にすることも可能です。

さて、マイクロソフトでは、多層防御に関して、7 つの層を組み合わせる事を推奨しています。
では、各層を外側から紹介します。

 <p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >各層</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">1. ポリシーと手順</td>
<td style="border:1px solid black;">セキュリティ対策を行う上でポリシーはとても大切です。ポリシーというと、ISMS や ISO-127001 を想像する人も多いと思いますが、多層防御では特定の認定の取得を推奨しているわけではありません。ISMS/ISO を取得できるポリシーの策定はある種の理想形ですが、たとえ簡易的にでも「何を」「どのように」保護するかを決めたルールを定める事が大切です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">2. 物理防御</td>
<td style="border:1px solid black;">他の層をどれほど完璧に対策しても、サーバー自体が誰もが操作できる場所に置かれていたのでは意味がありません。たとえログオンできなくても、HDD を抜き出せばセキュリティ設定を無視してデータを読み出すのは容易です。入退室管理や盗難防止ワイヤーなどがこの層です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">3. 境界防御</td>
<td style="border:1px solid black;">境界は、インターネットとイントラネット (LAN) の境目とよく言われますが、厳密には違います。この境界は、自分の管理するネットワークと他者が管理するネットワークの境界 (責任境界) と、要求されるセキュリティレベルが変化する境界 (セキュリティ境界) の両方を指します。いわゆる境界ファイアウォール/ルータはこの層です。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">4. ネットワーク</td>
<td style="border:1px solid black;">境界防御のところで説明した、自分が管理する組織内部のネットワークです。商用 Web サイトでは当たり前に使用されている SSL や、IPSec や 802.1x 認証接続等はこの層です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">5. アプリケーション</td>
<td style="border:1px solid black;">PC やサーバーの上で動作するアプリケーションやサーバー ソフトウェアです。この層は他の層と違い管理的ではなく、開発時に行われるべきものです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">6. ホスト</td>
<td style="border:1px solid black;">PC やサーバー自体のセキュリティ更新プログラムの管理や、要塞化（ハーデニング）、ウイルス対策ソフトウェアの導入はこの層です。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">7. データ防御</td>
<td style="border:1px solid black;">ホストに納められているデータです。この対策がしっかりしていると、データを持出されても利用・悪用を防止できます。暗号化されていれば、HDD を持ち去られても内容を読み取られる可能性を下げることが可能です。</td>
</tr>
</tbody>
</table>
  
勿論、ここで紹介した各層は論理的なものですので、実際の製品や機能を当てはめると、複数の層にまたがることがあるのは、OSI 参照モデル等と同じです。しかし、皆さんが普段行っているセキュリティ対策に当てはめることで、より安全性を担保できる所、運用を楽にできる層が見えてくれば幸いです。
  
以下、関連するサイトです。次回は、多層防御を頭の片隅に残しつつ、もう少し具体的にいきたいと思います。
  
**関連サイト** **:**  
[セキュリティ コンテンツの概要](http://www.microsoft.com/japan/technet/security/)
  
[![](images/Dd362910.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))  
この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### バックナンバー
  
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
