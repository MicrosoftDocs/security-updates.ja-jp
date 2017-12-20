---
TOCTitle: セキュリティ対策の要点解説 第 3 回 そもそもアレの動作を禁止したい ～ Software Restriction Policy ～
Title: セキュリティ対策の要点解説 第 3 回 そもそもアレの動作を禁止したい ～ Software Restriction Policy ～
ms:assetid: '1ceda3fe-8f9b-434d-8f43-f690211e38c8'
ms:contentKeyID: 19871857
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362912(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 3 回 そもそもアレの動作を禁止したい ～ Software Restriction Policy ～

公開日: 2006年3月22日

![](images/Dd362912.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/09bbd2c9-79d5-429e-bb82-3e78e7726a75(v=TechNet.10))は、暗号化を取り上げましたが実際に実施した人はいますか？ 大切な情報だと思うのならば、自分自身でも守る努力をすることが肝要です。今回は、情報流出の経路として取り上げられることが多くなった P2P ソフトウェアの実行を制御する方法ということで、「ソフトウェア制限ポリシー (Software Restriction Policy)」についてご紹介します。

この機能は、SRP と WinSafer の略称で呼ばれていますが、聞いたことがある方はそれほど多くないと思います。これにより、管理者の意思で、アプリケーションの実行を禁止することができます。ですから、個人所有のユーザーが自分自身で望んで P2P を導入する場合には、あまり意味をなさず、組織内や、ある程度管理可能な PC で有効な方法です。

では、色々説明する前に、実際に SRP の設定を行っていきます。設定を行うには、\[コントロールパネル\] - \[管理ツール\] - \[ローカル セキュリティ ポリシー\] または、gpedit.msc を使います。

\[ローカル セキュリティ ポリシー\] を開くと、図 1 の様な画面が表示され、左側のペインに \[ソフトウェア制限のポリシー\] が見つかると思います。

![](images/Dd362912.secpoint0003_01(ja-jp,TechNet.10).gif)

[図 1 全画面表示](https://technet.microsoft.com/ja-jp/dd362912.secpoint0003_01_big(ja-jp,technet.10).gif)

通常は、ポリシーの定義が行われていないため、新たにポリシーを作成する必要があります。

以下の手順で、テスト用に、メモ帳 (notepad.exe) を禁止するポリシーを作成します。

1.  \[ソフトウェア制限のポリシー\] を右クリックすると表示されるメニューから \[新しいポリシーの作成\] をクリックします。

2.  左側のペインから \[追加の規則\] を選択します。

3.  右側のペインで右クリックすると表示されるメニューから、\[新しいハッシュの規則\] をクリックします。

4.  \[参照\] ボタンをクリックし、%windir%\\notepad.exe を指定します。

5.  自動的に、ハッシュやファイル情報が入力されますので、\[セキュリティレベル\] が "許可しない" になっていることを確認します。

6.  \[OK\] ボタンをクリックし、ダイアログを閉じます。右側のペインに新しい規則が追加されたことを確認します。

以上の手順で、すでに メモ帳 の動作は禁止されており、実際に実行してみると図 ２ のエラーが表示されるはずです。

![](images/Dd362912.secpoint0003_02(ja-jp,TechNet.10).gif)

**図** **2**

この操作と同様に、禁止したい実行ファイルのハッシュ値を追加することで、P2P ソフトウェアを含め既知のアプリケーションの実行を制御することができます。

#### ハッシュ以外の制限方法

ファイルをハッシュで制限する方法が、最も手軽さと確実性のバランスが取れた方法ですが、ファイルが大量にある、またはバージョンアップが頻繁などの場合には、向かない場合もあります。そのため、SRP にはいくつかの制限方法が用意されています。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >優先順位</th>
<th style="border:1px solid black;" >方法</th>
<th style="border:1px solid black;" >概要</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">1 (高)</td>
<td style="border:1px solid black;">ハッシュ</td>
<td style="border:1px solid black;">実行ファイルのハッシュ値を元に、制限または許可を行います。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">2</td>
<td style="border:1px solid black;">証明書</td>
<td style="border:1px solid black;">実行ファイルに施されている証明書による署名を元に、制限または許可を行います。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">3</td>
<td style="border:1px solid black;">パス</td>
<td style="border:1px solid black;">実行ファイルが置かれている場所 (パス) を元に、制限または許可を行います。ワイルドカードを使うこともできます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">4 (低)</td>
<td style="border:1px solid black;">インターネットゾーン</td>
<td style="border:1px solid black;">Internet Explorer で指定できる、各ゾーン毎に、制限または許可を行います。</td>
</tr>
</tbody>
</table>
  
これらを、上手く組み合わせることで自由に制限を行うことができますが、優先順位の低い規則は、広範囲に制限が行われる傾向があります。そのため、間違った規則を設定すると、トラブルの元になりますので、十分に注意する必要があります。例えば、パス規則で、%windir% を制限するとどうなるかは、容易に想像できると思います。
  
#### 制限されたアプリケーションの監視
  
制限を行った以上、正しく制限されているか、誰が実行しようとしているのかを知りたいのが管理者の性だと思います。制限されたアプリケーションを実行しようとすると、以下のイベントがアプリケーションログに警告として残ります。

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >イベントID</th>
<th style="border:1px solid black;" >内容</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">865</td>
<td style="border:1px solid black;">規定の制限規則により実行が制限された場合</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">866</td>
<td style="border:1px solid black;">パス規則により実行が制限された場合</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">867</td>
<td style="border:1px solid black;">証明書規則により実行が制限された場合</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">878</td>
<td style="border:1px solid black;">インターネットゾーン規則または、ハッシュ規則により実行が制限された場合</td>
</tr>
</tbody>
</table>
  
![](images/Dd362912.secpoint0003_03(ja-jp,TechNet.10).gif)
  
**図** **3**
  
規則をすり抜けて、実行されたことを確認したい場合は、通常の監査設定として、プロセスの監査を行う必要がありますが、大量の監査ログが記録されるため使用には十分な検討が必要です。
  
#### ポリシーの展開
  
ここまで、クライアント上で設定する方法を説明してきましたが、グループポリシーとして展開する場合は、\[ローカル セキュリティ ポリシー\] の代わりに、通常のグループポリシエディタを使用して設定します。グループポリシーの場合、\[Windowsの設定\] - \[セキュリティの設定\] - \[ソフトウェア制限ポリシー\] に設定が存在しますので、通常のポリシー設定と同様に適用先を指定して展開することが可能です。
  
今回は、ソフトウェアの実行を制限をする方法を紹介しましたが、理想的には、SRP のセキュリティレベルを、「許可しない」に設定し、各ルールで必要なソフトウェアだけを許可することです。しかし、この方法は厳密な管理と計画が必要となりますので、SRP で一部のアプリケーションのみを制限するのも応急処置としては良いでしょう。 また、SRP は、万能ではなく技術的に回避する方法が無いわけではありません。 多層防御の原則に基づいて、 SRP だけで対処しようとせず、アクセス権の設定、ユーザーが使う権限の最小化 (Administrator を使わない) 等を組合せて、不要なソフトウェアのインストール自体をさせない環境を作っていくことが大切です。さて、次回は、うっかりと怪しいファイルを実行しないようにする方法について触れてみたいと思います。
  
**関連サイト：**
  
-   [Windows XP セキュリティ ガイド - 第 6 章 ‐ Windows XP クライアントのソフトウェア制限ポリシー](https://technet.microsoft.com/ja-jp/library/e588520d-eda1-4d74-87d9-5c6634e70453(v=TechNet.10))
  
[![](images/Dd362912.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))  
この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### バックナンバー
  
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
