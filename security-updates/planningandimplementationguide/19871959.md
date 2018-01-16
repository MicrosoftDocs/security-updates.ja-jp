---
TOCTitle: '付録 A:Windows XP Service Pack 2 のその他のガイダンス'
Title: '付録 A:Windows XP Service Pack 2 のその他のガイダンス'
ms:assetid: 'fdfcd31f-cacc-4201-b1fc-1c18dab43567'
ms:contentKeyID: 19871959
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd363016(v=TechNet.10)'
---

Windows XP セキュリティ ガイド
==============================

### 付録 A:Windows XP Service Pack 2 のその他のガイダンス

最終更新日: 2006年8月17日

この付録では、Microsoft Windows XP Service Pack 2 (SP2) リリースに基づくセキュリティ ガイダンスの変更点について説明します。

この付録を読むには、*『Windows XP セキュリティ ガイド』*の前の各セクションの内容を理解している必要があります。この付録は、前の各セクションの補足であり、SP2 に固有の構成の変更点についてのみ説明しています。他のセクションから独立した内容ではありません。

##### トピック

[](#efaa)[Windows XP SP2 の概要](#efaa) 
[](#eeaa)[セキュリティ設定の変更点](#eeaa)  
[](#edaa)[管理用テンプレートの変更点](#edaa) 
[](#ecaa)[\[コンピュータの構成\] 設定](#ecaa) 
[](#ebaa)[ユーザーの構成の設定](#ebaa) 
[](#eaaa)[まとめ](#eaaa)

### Windows XP SP2 の概要

Windows XP SP2 には、Windows XP の最新の更新が含まれています。これらの更新では、Windows XP ベースのコンピュータがウイルスやワームなどの悪質な攻撃に耐える機能を強化する一連のセキュリティ技術が導入されており、オペレーティング システムのセキュリティ、信頼性、および互換性を高めることができます。これらの技術には、次のようなものがあります。

-  ネットワーク保護

-  メモリ保護

-  電子メール セキュリティの強化

-  参照の安全性の向上

-  コンピュータのメンテナンスの改善

SP2 には、セキュリティ サービスの管理性に関連する多数の改善点があります。これらの改善点により、管理者は複数のユーザーおよびコンピュータに、より詳細なセキュリティ設定を実装できます。

SP2 の大きな変更点は、既定のセキュリティ設定が強化されたことです。セキュリティに関連するほとんどの変更点は既定で実装され、構成を変更する必要がありません。多くの改善点によって、互換性に関連する課題が生じますが、通常はオペレーティング システムのセキュリティが全体的に向上することで、そのような課題は埋め合わされます。

SP2 で行われた大幅な変更の詳細については、[http://technet.microsoft.com/library/bb457097.aspx](http://www.microsoft.com/technet/prodtechnol/winxppro/ja/maintain/sp2chngs.mspx) の「Microsoft Windows XP Service Pack 2 での機能の変更点」 を参照してください。

[](#mainsection)[ページのトップへ](#mainsection)

### セキュリティ設定の変更点

Windows XP SP2 で行われたポリシーと設定の大幅な変更は、主にグループ ポリシーの管理用テンプレートに集中しています。そのため、この付録では、セキュリティ設定に推奨される変更は示しません。

[](#mainsection)[ページのトップへ](#mainsection)

### 管理用テンプレートの変更点

Windows XP SP 2 の管理用テンプレートは大幅に変更されました。数百種類もの新しい設定を使用することで、ユーザーの操作性およびセキュリティ環境のより詳細な制御を実装できます。この付録の大部分では、管理用テンプレートの新しい設定について詳しく説明します。これらの新しい設定によって、環境のセキュリティを強化できます。

**注 :** このガイドの執筆時点では、この付録で説明する設定は、Windows XP SP2 以外のオペレーティング システムでは効果がありません。この設定は、Windows XP Service Pack 1 以前のバージョンのオペレーティング システムでは無視されます。

#### 新しい管理用テンプレート

その他のセキュリティ設定は、管理用テンプレートという Unicode ベースのファイルにあります。これらのファイルには、Windows XP とそのコンポーネントに影響するレジストリ設定が含まれます。新しい管理用テンプレートは、Windows XP SP2 に付属しています。新しいテンプレートを使用するには、GPO を管理するときに、Windows XP SP2 を実行しているコンピュータを使用する必要があります。

古いバージョンのグループ ポリシー オブジェクト エディタ (Gpedit.exe) では、新しい管理用テンプレートはサポートされません。新しい GPO または既存の GPO に対する変更は、Windows XP SP2 を実行しているコンピュータを使用して行う必要があります。Windows XP SP2 以外のオペレーティング システムを使用して GPO を管理する方法については、<http://support.microsoft.com/?kbid=842933> のマイクロソフト サポート技術情報 842933を参照してください。

新しい管理用テンプレートの設定は、Windows XP SP2 を実行しているコンピュータでのみ効果があります。Windows XP SP1 以前のバージョンのオペレーティング システムでは、新しい設定は無視されます。このアプローチにより、*『Windows XP セキュリティ ガイド』*の第 2 章で説明した OU 構造を使用して GPO を実装して、環境内で Windows XP を実行しているすべてのコンピュータのセキュリティを強化できます。

[](#mainsection)[ページのトップへ](#mainsection)

### \[コンピュータの構成\] 設定

次のセクションでは、グループ ポリシー オブジェクト エディタの \[コンピュータの構成\] で既定される設定について説明します。次の項目について各種設定を構成します。

コンピュータの構成\\管理用テンプレート

環境内のコンピュータ アカウントが含まれる OU にリンクする GPO を介してこれらの設定を適用します。*『Windows XP セキュリティ ガイド』*の第 2 章で説明しているように、GPO のラップトップ設定をラップトップの OU にリンクし、GPO のデスクトップ設定をデスクトップの OU にリンクします。

#### Internet Explorer

グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。

コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer

##### クラッシュの検出を無効にする

**表 A.1:クラッシュ検出の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**クラッシュの検出を無効にする**ポリシー設定を使用すると、Internet Explorer のアドオン管理のクラッシュ検出機能を管理できます。このポリシー設定を有効にすると、Internet Explorer でクラッシュが発生した場合、Windows XP Professional Service Pack 1 以前のバージョンを実行しているコンピュータの場合と同様に、Windows エラー報告が起動します。無効にすると、アドオン管理のクラッシュ検出機能が動作します。
 
Internet Explorer のクラッシュ レポート情報には、コンピュータのメモリに保存されている機密情報が含まれている場合があるので、このポリシーの値を \[有効\] に設定することをお勧めします。ただし、クラッシュが頻繁に発生し、そのトラブルシューティングのために問題を報告する必要がある場合を除きます。そのような場合は、一時的に \[無効\] に設定することもできます。
 
##### ユーザーによるアドオンの有効化および無効化を許可しない
 
**表 A.2:アドオンの有効化または無効化の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**ユーザーによるアドオンの有効化および無効化を許可しない**ポリシー設定を使用すると、ユーザーが \[アドオンの管理\] を使用してアドオンを許可または拒否できるかどうかを管理できます。このポリシー設定の値を \[有効\] に設定すると、ユーザーは \[アドオンの管理\] を使用してアドオンを有効または無効にすることはできません。ただし、ユーザーがアドオンを引き続き管理できるように**アドオンの一覧**ポリシー設定にそのアドオンを入力した場合を除きます。この場合は、ユーザーが \[アドオンの管理\] を使用してそのアドオンを管理できます。このポリシー設定の値を \[無効\] に設定すると、ユーザーはアドオンを有効または無効にすることができます。
 
**注 :** Windows XP SP2 で Internet Explorer のアドオンを管理する方法については、<http://support.microsoft.com/?kbid=883256> のマイクロソフト サポート技術情報 883256「Windows XP Service Pack 2 で Internet Explorer のアドオンを管理する方法」を参照してください。
 
ユーザーは、組織のセキュリティ ポリシーで許可されていないアドオンをインストールすることがよくあります。このようなアドオンは、ネットワークにとってセキュリティ上およびプライバシー上の大きなリスクとなる可能性があります。したがって、このポリシーの値を \[有効\] に設定することをお勧めします。
 
**注 :** Internet Explorer\\セキュリティの機能\\アドオン管理にある GPO 設定を確認し、許可された適切なアドオンを環境内で実行できることを確認する必要があります。
 
##### インターネット コントロール パネル\\セキュリティ ページ
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\インターネット コントロール パネル\\セキュリティ ページ
 
SP2 では、環境全体で Internet Explorer ゾーン構成のセキュリティを保護するための、複数の新しいポリシー設定が導入されています。これらの設定では、セキュリティを強化するように既定値が構成されています。ただし、これらの設定を見直して、環境全体でこれらのポリシーを必須の設定に構成したり、利便性やアプリケーションの互換性を考慮して緩和したりすることもできます。
 
たとえば、SP2 では、Internet Explorer がすべてのインターネット ゾーンのポップアップをブロックするように既定で構成されています。この設定を環境内のすべてのコンピュータで適用することで、迷惑なポップアップ ウィンドウを排除し、インターネット Web サイトから悪質なソフトウェアやスパイウェアがインストールされる可能性を低減できます。反対に、環境内にポップアップ機能を使用する必要のあるアプリケーションが含まれる場合があります。この場合は、イントラネット内の Web サイトではポップアップを許可するようにポリシーを構成することもできます。
 
##### インターネット コントロール パネル\\詳細設定ページ
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\インターネット コントロール パネル\\詳細設定ページ
 
###### 署名が無効であっても、ソフトウェアの実行またはインストールを許可する
 
**表 A.3:ソフトウェア実行許可の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
Microsoft ActiveX コントロールとファイル ダウンロードには、多くの場合、ファイルの整合性およびソフトウェア署名者 (作成者) の ID を保証するデジタル署名が添付されています。署名により、ダウンロードしたソフトウェアが改変されていないことを確認でき、また署名者を特定することで、ソフトウェアを安心して実行できるかどうかを判断できます。
 
**署名が無効であっても、ソフトウェアの実行またはインストールを許可する**ポリシー設定を使用すると、ダウンロードしたソフトウェアの署名が無効であった場合に、ユーザーがそのソフトウェアをインストールまたは実行できるかどうかを管理できます。署名が無効であることは、ファイルが改ざんされている可能性があることを意味します。このポリシー設定を有効にすると、署名が無効な場合に、そのファイルをインストールするか実行するかを確認するメッセージが表示されます。無効にすると、ユーザーは署名が無効なファイルを実行またはインストールできません。
 
ソフトウェアに署名がないとセキュリティ上の脆弱性が生じる可能性があるので、このポリシー設定の値を \[無効\] に設定して、署名のないソフトウェアをブロックすることをお勧めします。
 
**注 :** 合法的なソフトウェアやコントロールの中には、署名が無効であっても問題のないものがあります。そのようなソフトウェアは、隔離された環境で慎重にテストしてから、組織のネットワーク上での使用を許可する必要があります。
 
##### セキュリティの機能\\MK プロトコル セキュリティの制限
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\セキュリティの機能\\MK プロトコル セキュリティの制限
 
###### Internet Explorer のプロセス (MK プロトコル)
 
**表 A.4:MK プロトコルの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**MK プロトコル セキュリティの制限**ポリシー設定は、ほとんど使用されることのない MK プロトコルをブロックすることで、攻撃対象を減らします。一部の古い Web アプリケーションでは、MK プロトコルが使用されて、圧縮ファイルから情報が抽出されます。このポリシーの値を \[有効\] に設定すると、エクスプローラと Internet Explorer で MK プロトコルがブロックされるので、このプロトコルを使用するリソースは正常に動作しなくなります。無効にすると、アプリケーションで MK プロトコル API を使用できます。
 
MK プロトコルは一般的には使用されていないので、不要な場合はブロックする必要があります。環境で必要な場合以外は、このポリシー設定の値を \[有効\] に設定して、MK プロトコルをブロックすることをお勧めします。
 
**注 :** この設定を有効にすると、MK プロトコルを使用するリソースは正常に動作しなくなるので、有効にする場合は、MK プロトコルを使用するアプリケーションがないことを確認してください。
 
##### セキュリティの機能\\整合性のある MIME 処理
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\セキュリティの機能\\整合性のある MIME 処理
 
###### Internet Explorer のプロセス (整合性のある MIME 処理)
 
**表 A.5:整合性のある MIME 処理の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
Internet Explorer は、Multipurpose Internet Mail Extensions (MIME) データを使用して、Web サーバー経由で受信したファイルの処理手順を決定します。**整合性のある MIME 処理\\Internet Explorer のプロセス** ポリシー設定では、Web サーバーから提供されるファイルの種類の情報すべてに整合性があることを Internet Explorer で必要条件にするかどうかを指定します。たとえば、ファイルの MIME の種類が text/plain であるのに、MIME データはファイルが実は実行可能ファイルであることを示す場合は、Internet Explorer によってファイルの拡張子が変更され、実行可能のステータスに反映されます。この機能により、実行可能コードを信頼できる他の種類のデータとして見せかけることができなくなります。
 
このポリシー設定を有効にすると、Internet Explorer ですべての受信ファイルが調べられ、受信ファイルの MIME データに整合性があることが必要条件とされます。このポリシー設定を無効にするか、構成しなかった場合は、Internet Explorer は受信ファイルの MIME データに整合性があることを要求せず、ファイルの MIME データを使用します。
 
MIME ファイル タイプの偽装は、組織にとって脅威となる可能性があります。受信ファイルに整合性があり、適切にラベル付けされていることを確認することで、ネットワークが悪質なファイルのダウンロードに感染することを防止できます。したがって、このガイドに示すすべての環境で、このポリシーの値を \[有効\] に設定することをお勧めします。
 
**注 :** この設定は、**MIME スニッフィングの安全機能**の設定と連動しますが、それに置き換わるものではありません。
 
##### セキュリティの機能\\MIME スニッフィングの安全機能
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\セキュリティの機能\\MIME スニッフィングの安全機能
 
###### Internet Explorer のプロセス (MIME スニッフィング)
 
**表 A.6:MIME スニッフィングの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
MIME スニッフィングとは、MIME ファイルの内容を調べ、それがデータ ファイルであるか、実行可能ファイルであるか、または他の種類のファイルであるかを判別するプロセスです。このポリシー設定では、Internet Explorer の MIME スニッフィング機能を使用して、特定の種類のファイルが危険度の高い別の種類のファイルに変わることを防止するかどうかを指定します。このポリシーの値を \[有効\] に設定すると、特定の種類のファイルが危険度の高い別の種類のファイルに変わることはありません。無効にすると、Internet Explorer のプロセスは、特定の種類のファイルが危険度の高い別の種類のファイルに変わることを許可するように MIME スニッフィングを構成します。たとえば、テキスト ファイルが実行可能ファイルに変更されると、テキスト ファイルの内容がそのままコードとして実行されるので危険です。
 
MIME ファイル タイプの偽装は、組織にとって脅威となる可能性があります。これらのファイルの処理方法に一貫性を持たせることにより、ネットワークが悪質なファイルのダウンロードに感染することを防止できます。したがって、このガイドに示すすべての環境で、このポリシーの値を \[有効\] に設定することをお勧めします。
 
**注 :** この設定は、**整合性のある MIME 処理**の設定と連動しますが、それに置き換わるものではありません。
 
##### セキュリティの機能\\スクリプト化されたウィンドウのセキュリティ制限
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\セキュリティの機能\\スクリプト化されたウィンドウのセキュリティ制限
 
###### Internet Explorer のプロセス (スクリプト化されたウィンドウのセキュリティ制限)
 
**表 A.7:スクリプト化されたウィンドウ制限の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
Internet Explorer では、スクリプトのプログラムを使用してさまざまな種類のウィンドウを開いたり、ウィンドウのサイズや位置を変更したりすることが許可されています。悪質な Web サイトにアクセスすると、ウィンドウのサイズが変更されて、他のウィンドウが隠されたり、悪質なコードを含むウィンドウの操作するように誘導されたりします。
 
**スクリプト化されたウィンドウのセキュリティ制限**セキュリティ機能は、ポップアップ ウィンドウを制限し、タイトル バーやステータス バーがユーザーに表示されないウィンドウ、または他のウィンドウのタイトル バーやステータス バーを隠すウィンドウがスクリプトによって表示されることを禁止します。**スクリプト化されたウィンドウのセキュリティ制限\\Internet Explorer のプロセス** ポリシー設定を有効にすると、ポップアップ ウィンドウの制限や他の制限が、エクスプローラおよび Internet Explorer のプロセスに適用されます。このポリシー設定を無効にするか、構成しなかった場合は、ポップアップ ウィンドウおよび他のウィンドウを隠すウィンドウをスクリプトで作成できます。
 
このポリシー設定の値を \[有効\] に設定して、悪質な Web サイトにアクセスしたときに Internet Explorer のウィンドウが制御されたり、不正なウィンドウをクリックするようにユーザーがだまされたりしないようにすることをお勧めします。
 
##### セキュリティの機能\\ゾーン昇格からの保護
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\セキュリティの機能\\ゾーン昇格からの保護
 
###### Internet Explorer のプロセス (ゾーン昇格からの保護)
 
**表 A.8:ゾーン昇格からの保護の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
Internet Explorer では、Web ページの場所 (インターネット ゾーン、イントラネット ゾーン、ローカル コンピュータ ゾーンなど) によって、その Web ページを開くかどうかの制限が適用されます。ローカル コンピュータにある Web ページはローカル コンピュータ ゾーンに存在し、セキュリティの制限が最小限であるため、このゾーンは悪意のある攻撃者の一番の標的となります。
 
このポリシー設定を有効にすると、すべてのゾーンが Internet Explorer のプロセスによるゾーン昇格から保護されます。このアプローチにより、あるゾーンで実行しているコンテンツは、別のゾーンの昇格された特権を得ることができなくなります。このポリシー設定を無効にすると、ゾーンは Internet Explorer のプロセスに対するそのような保護を受けません。
 
ゾーン昇格攻撃は重大であり、また比較的頻繁に発生するので、すべての環境でこのポリシー設定の値を \[有効\] に設定することをお勧めします。
 
##### セキュリティの機能\\ActiveX のインストールの制限
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\セキュリティの機能\\ActiveX のインストールの制限
 
###### Internet Explorer のプロセス (ActiveX のインストールの制限)
 
**表 A.9:ActiveX のインストール制限の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
</tr>
</tbody>
</table>
 
**ActiveX のインストールの制限\\Internet Explorer のプロセス** ポリシー設定では、Internet Explorer のプロセスで ActiveX コントロールのインストールを確認するダイアログ ボックスが表示されないように制限できます。
 
このポリシー設定を有効にすると、Internet Explorer のプロセスで ActiveX コントロールのインストールを確認するダイアログ ボックスは表示されません。無効にすると、ActiveX コントロールのインストールを確認するダイアログ ボックスは表示されます。
 
ユーザーは、会社のセキュリティ ポリシーで許可されていない ActiveX コントロールなどのソフトウェアをインストールすることがよくあります。このようなソフトウェアは、ネットワークにとってセキュリティ上およびプライバシー上の大きなリスクとなる可能性があります。したがって、このポリシーの値を \[有効\] に設定することをお勧めします。
 
**注 :** この設定を有効にすると、許可された正当な ActiveX コントロールのインストールも制限されるため、Windows Update などの重要なシステム コンポーネントがインストールできなくなります。この設定を有効にするときは、Software Update Services (SUS) またはセキュリティ アップデートを展開する別の方法を採用してください。
 
SUS の詳細については、<http://www.microsoft.com/japan/windowsserversystem/updateservices/evaluation/previous/default.mspx> の「Software Update Services」ページを参照してください。このページには、SUS の後継である Windows Update Services に関する情報も記載されています。
 
##### セキュリティの機能\\ファイル ダウンロードの制限
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\セキュリティの機能\\ファイル ダウンロードの制限
 
###### Internet Explorer のプロセス (ファイル ダウンロードの制限)
 
**表 A.10:ファイル ダウンロード制限の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
特定の状況では、Web サイトは、ユーザーが操作を行わなくても、ファイルのダウンロードを確認するダイアログ ボックスを表示できます。この手法を採用している Web サイトにアクセスした場合には、ユーザーが誤ってボタンをクリックしてダウンロードした場合に、ユーザーのハード ドライブに不正なファイルが保存される可能性があります。
 
**ファイル ダウンロードの制限\\Internet Explorer のプロセス** ポリシー設定の値を \[有効\] に設定すると、ユーザーが開始したのではないファイル ダウンロードを確認するダイアログ ボックスが Internet Explorer のプロセスでブロックされます。\[無効\] に設定すると、ユーザーが開始したのではないファイル ダウンロードを確認するダイアログ ボックスが Internet Explorer のプロセスで表示されます。
 
**注** :このガイドに示すすべての環境では、攻撃者がユーザーのコンピュータに任意のコードを保存することを防止するため、このポリシー設定の値を \[有効\] に設定します。
 
##### セキュリティの機能\\アドオン管理
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Internet Explorer\\セキュリティの機能\\アドオン管理
 
###### アドオンの一覧で許可されたものを除き、アドオンはすべて拒否する
 
**表 A.11:許可されたものを除きすべてのアドオンを拒否する設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
</tr>
</tbody>
</table>
 
このポリシー設定を**アドオンの一覧**ポリシーと共に使用して、Internet Explorer のアドオンを制御できます。**アドオンの一覧**ポリシー設定では、既定で、グループ ポリシーを通じて許可または拒否するアドオンの一覧が定義されています。**アドオンの一覧で許可されたものを除き、アドオンはすべて拒否する**ポリシー設定では、**アドオンの一覧**ポリシー設定に指定されていないアドオンはすべて拒否するものと見なされます。
 
このポリシー設定を有効にすると、Internet Explorer では、**アドオンの一覧**ポリシー設定に指定されている (許可されている) アドインだけが許可されます。無効にすると、ユーザーはアドオン マネージャを使用してアドオンを許可または拒否できます。
 
環境内で使用できるアドオンを制御するには、**アドオンの一覧で許可されたものを除き、アドオンはすべて拒否する**および**アドオンの一覧**の両設定の使用を検討する必要があります。このアプローチにより、許可されたアドオンだけを使用できます。
 
###### アドオンの一覧
 
**表 A.12:アドオンの一覧の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
</tr>
</tbody>
</table>
 
このポリシー設定を**アドオンの一覧で許可されたものを除き、アドオンはすべて拒否する**ポリシーと共に使用して、Internet Explorer のアドオンを制御できます。**アドオンの一覧**ポリシー設定では、既定で、グループ ポリシーを通じて許可または拒否するアドオンの一覧が定義されています。**アドオンの一覧で許可されたものを除き、アドオンはすべて拒否する**ポリシー設定では、**アドオンの一覧**ポリシー設定に指定されていないアドオンはすべて拒否するものと見なされます。
 
このポリシー設定を有効にするには、Internet Explorer で許可または拒否するアドオンの一覧を入力する必要があります。一覧に追加するエントリごとに、次の情報を入力する必要があります。
 
-  **値の名前**。一覧に追加するアドオンの CLSID (クラス識別子)。CLSID は、「{000000000-0000-0000-0000-0000000000000}」のように、波かっこで囲む必要があります。アドオンの CLSID は、アドオンを参照している Web ページの OBJECT タグから取得できます。
 
-  **値**。Internet Explorer がアドオンの読み込みを拒否または許可するかどうかを示す数値です。有効な値を次に示します。
 
  **表 A.13:アドオンの一覧設定の値**

 
  <table style="border:1px solid black;">
  <colgroup>
  <col width="50%" />
  <col width="50%" />
  </colgroup>
  <thead>
  <tr class="header">
  <th style="border:1px solid black;" >値</th>
  <th style="border:1px solid black;" >説明</th>
  </tr>
  </thead>
  <tbody>
  <tr class="odd">
  <td style="border:1px solid black;">0</td>
  <td style="border:1px solid black;">このアドオンを拒否します。</td>
  </tr>
  <tr class="even">
  <td style="border:1px solid black;">1</td>
  <td style="border:1px solid black;">このアドオンを許可します。</td>
  </tr>
  <tr class="odd">
  <td style="border:1px solid black;">2</td>
  <td style="border:1px solid black;">このアドオンを許可し、ユーザーが [アドオンの管理] を使用してこのアドオンを管理することを許可します。</td>
  </tr>
  </tbody>
  </table>
 
このポリシー設定を無効にすると、一覧は削除されます。
 
環境内で使用できるアドオンを制御するには、**アドオンの一覧で許可されたものを除き、アドオンはすべて拒否する**および**アドオンの一覧**の両設定の使用を検討する必要があります。このアプローチにより、許可されたアドオンだけを使用できます。
 
#### ターミナル サービス\\クライアント
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
管理用テンプレート\\Windows コンポーネント\\ターミナル サービス\\クライアント
 
##### パスワードの保存を許可しない
 
**表 A.14:パスワードの保存を許可しない設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**パスワードの保存を許可しない**ポリシー設定は、ターミナル サービス クライアントによってパスワードがコンピュータに保存されることを防止します。この設定を有効にすると、ターミナル サービス クライアントのパスワードを保存するためのチェック ボックスが使用できなくなり、ユーザーはパスワードを保存できなくなります。パスワードを保存することが習慣になるとセキュリティ侵害の可能性が高くなるため、このガイドで定義されている環境では、このポリシー設定の値を \[有効\] に設定します。
 
**注 :** このポリシー設定の値を以前に \[無効\] または \[未構成\] に設定していた場合は、ターミナル サービス クライアントが最初にサーバーから切断されるときに、以前に保存したパスワードがすべて削除されます。
 
#### Windows Update
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
管理用テンプレート\\Windows コンポーネント\\Windows Update
 
##### \[Windows シャットダウン\] ダイアログ ボックスで \[更新をインストールしてシャットダウン\] オプションを表示しない
 
**表 A.15:シャットダウン オプションを表示しない設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
**\[Windows シャットダウン\] ダイアログ ボックスで \[更新をインストールしてシャットダウン\] オプションを表示しない**ポリシー設定を使用すると、\[Windows シャットダウン\] ダイアログ ボックスに \[更新をインストールしてシャットダウン\] オプションを表示するかどうかを管理できます。
 
このポリシー設定を無効にすると、ユーザーが \[スタート\] メニューの \[シャットダウン\] をクリックするか、**Ctrl** + **Alt** + **Del** キーを押すと表示されるウィンドウで \[シャットダウン\] をクリックしたときに更新が存在する場合に、\[Windows シャットダウン\] ダイアログ ボックスに \[更新をインストールしてシャットダウン\] オプションが表示されます。すべてのコンピュータの全体的なセキュリティを維持するために更新をインストールすることは重要なので、このガイドで定義されているすべての環境では、このポリシー設定の値を \[無効\] に設定します。この設定は、次の **\[Windows シャットダウン\] ダイアログ ボックスの既定のオプションを \[更新をインストールしてシャットダウン\] に調整しない**ポリシー設定と連動します。
 
##### \[Windows シャットダウン\] ダイアログ ボックスの既定のオプションを \[更新をインストールしてシャットダウン\] に調整しない
 
**表 A.16:既定のシャットダウン オプションを調整しない設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
この **\[Windows シャットダウン\] ダイアログ ボックスの既定のオプションを \[更新をインストールしてシャットダウン\] に調整しない**ポリシー設定を使用すると、\[更新をインストールしてシャットダウン\] を \[Windows シャットダウン\] ダイアログ ボックスの既定のオプションにするかどうかを管理できます。このポリシー設定を無効にすると、ユーザーが \[スタート\] メニューの \[シャットダウン\] をクリックしたときに更新が存在する場合に、\[更新をインストールしてシャットダウン\] が \[Windows シャットダウン\] ダイアログ ボックスの既定のオプションになります。
 
すべてのコンピュータの全体的なセキュリティを維持するために更新をインストールすることは重要なので、このガイドで定義されているすべての環境では、このポリシー設定の値を \[無効\] に設定します。
 
**注 :コンピュータの構成\\管理用テンプレート\\Windows コンポーネント\\Windows Update** の \[Windows シャットダウン\] ダイアログ ボックスで **\[更新をインストールしてシャットダウン\] オプションを表示しない**ポリシー設定が有効になっている場合、このポリシー設定は効果がありません。
 
#### システム
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
コンピュータの構成\\管理用テンプレート\\システム
 
##### Windows Update でのデバイス ドライバ検索についての確認をしない
 
**表 A.17:Windows Update でのデバイス ドライバ検索確認の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**Windows Update でのデバイス ドライバ検索についての確認をしない**ポリシー設定では、管理者がインターネットを使用して Windows Update でのデバイス ドライバ検索を行うかどうかを確認するダイアログを表示するかどうかを指定します。この設定を有効にすると、Windows Update でのドライバ検索を確認するダイアログ ボックスは管理者に表示されません。この設定を無効または未構成にし、**Windows Update でのデバイス ドライバの検索をオフにする**ポリシー設定を無効または未構成にした場合は、Windows Update でのデバイス ドライバ検索を確認するダイアログ ボックスが管理者に表示されます。
 
インターネットからデバイス ドライバをダウンロードすることにはリスクが伴うので、このポリシー設定の値は、高セキュリティ環境では \[有効\] に設定し、エンタープライズ環境では \[無効\] に設定することをお勧めします。この設定を推奨する理由は、ドライバのダウンロードを悪用する可能性のある種類の攻撃は、通常は適切なエンタープライズ リソース管理によって軽減されるからです。
 
**注 :** この設定は、**管理用テンプレート\\システム\\インターネット通信の管理\\インターネット通信の設定**の**Windows Update でのデバイス ドライバの検索をオフにする**ポリシー設定が無効または未構成の場合にのみ効果があります。
 
##### システム\\エラーの報告
 
*『Windows XP セキュリティ ガイド』*の第 4 章では、エラー報告を構成するいくつかの設定を既定しています。これらの設定は Windows XP SP2 を実行しているコンピュータの設定と同じですが、1 つの設定の名前が変更されています。表 4.42 に示す \[エラーを報告する\] 設定は、最新版では、\[エラー報告を構成する\] と表示されます。既定の設定は、第 4 章に示すものと同じです。
 
##### システム\\リモート プロシージャ コール
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
管理用テンプレート\\システム\\リモート プロシージャ コール
 
###### 認証されていない RPC クライアントの制限
 
**表 A.18:認証されていない RPC クライアントの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**認証されていない RPC クライアントの制限**ポリシー設定を有効にすると、コンピュータで実行されている RPC サーバーに対する、認証されていない RPC クライアントの接続が制限されるように、RPC サーバーの RPC ランタイムが構成されます。クライアントは、名前付きパイプを使用してサーバーと通信するか、RPC セキュリティを使用している場合に、認証済みと見なされます。このポリシーで選択する値によっては、認証されていないクライアントがアクセスできるよう明示的に要求した RPC インターフェイスは、この制限から除外される場合もあります。この設定を有効にすると、次の値が使用可能になります。
 
-  **なし**。この値は、このポリシーが適用されているコンピュータで実行している RPC サーバーにすべての RPC クライアントが接続することを許可します。
 
-  **認証済み**。この値は、このポリシーが適用されているコンピュータで実行している RPC サーバーに、認証済みの RPC クライアントだけが接続することを許可します。この制限から除外されるよう要求したインターフェイスは、除外されます。
 
-  **認証済み (例外なし)**。この値は、このポリシーが適用されているコンピュータで実行している RPC サーバーに、認証済みの RPC クライアントだけが接続することを許可します。例外は許可されません。
 
認証されていない RPC 通信によってセキュリティ上の脆弱性が生じる可能性があるので、このガイドで定義されているすべての環境で、このポリシー設定の値を \[有効\] に設定し、\[適用する RPC ランタイム未認証クライアント制限\] の値を \[認証済み\] に設定することをお勧めします。
 
**注 :** この設定を適用すると、不要な受信接続要求を認証しない RPC アプリケーションが正常に動作しなくなる場合があります。この設定を広く展開する前に、必ずアプリケーションをテストしてください。この設定の \[認証済み\] の値が完全に安全というわけではありませんが、環境内でのアプリケーションの互換性の確保に役立つ場合があります。
 
###### RPC エンド ポイント マッパー クライアント認証
 
**表 A.19:クライアント認証の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**RPC エンド ポイント マッパー クライアント認証**ポリシー設定を有効にすると、このコンピュータと通信するクライアントは、RPC 通信を確立する前に、認証情報を提供することが強制されます。
 
##### システム\\インターネット通信の管理\\インターネット通信の設定
 
インターネット通信の設定グループには、複数の設定があります。コンピュータ システムに保存されているデータの機密性を高めることを主な目的として、これらの設定の多くを制限することを推奨します。これらの設定を制限しないと、情報が攻撃者に傍受され、使用される可能性があります。今日、このような攻撃が実際に発生するケースはまれですが、これらの設定を適切に構成することで、将来の攻撃から環境を保護できます。
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
管理用テンプレート\\システム\\インターネット通信の管理\\インターネット通信の設定
 
###### ファイルとフォルダのタスクから \[Web に公開する\] を削除する
 
**表 A.20:\[Web に公開する\] タスク削除の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
このポリシー設定では、Windows フォルダのファイルとフォルダのタスクで \[このファイルを Web に公開する\]、\[このフォルダを Web に公開する\]、および \[選択した項目を Web に発行する\] の各タスクを使用可能にするかどうかを指定します。Web 発行ウィザードを使用して、プロバイダの一覧をダウンロードし、コンテンツを Web に公開できます。この設定の値を \[有効\] に設定すると、これらのオプションは Windows フォルダのファイルとフォルダのタスクから削除されます。
 
###### Web 発行およびオンライン注文ウィザードのインターネット ダウンロードをオフにする
 
**表 A.21:インターネット ダウンロード オフの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**Web 発行およびオンライン注文ウィザードのインターネット ダウンロードをオフにする**ポリシー設定では、Web 発行およびオンライン注文ウィザードで、プロバイダの一覧をダウンロードするかどうかを指定します。この設定を有効にすると、プロバイダの一覧はダウンロードされず、ローカル レジストリにキャッシュされたサービス プロバイダのみが表示されます。
 
###### Windows Messenger カスタマ エクスペリエンス向上プログラムをオフにする
 
**表 A.22:Windows Messenger カスタマ プログラム オフの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**Windows Messenger カスタマ エクスペリエンス向上プログラムをオフにする**ポリシー設定では、Windows Messenger ソフトウェアおよびサービスがどのように使用されているかについて、匿名の情報を収集するかどうかを指定します。このポリシー設定の値を \[有効\] に設定すると、Windows Messenger による使用情報の収集は実行されず、使用情報の収集を有効にするユーザー設定は表示されません。
 
###### 検索コンパニオンのコンテンツ ファイルの更新をオフにする
 
**表 A.23:検索コンパニオン更新オフの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**検索コンパニオンのコンテンツ ファイルの更新をオフにする**ポリシー設定では、ローカル検索およびインターネット検索時に、検索コンパニオンがコンテンツの更新を自動的にダウンロードするかどうかを指定します。このポリシー設定の値を \[有効\] に設定すると、検索中にコンテンツの更新はダウンロードされません。
 
**注 :** インターネット検索時には、検索文字列と検索情報が、Microsoft および選択した検索プロバイダに送信されます。クラシック検索を選択すると、検索コンパニオンの機能は完全にオフになります。クラシック検索を選択するには、\[スタート\] をクリックし、\[検索\] をクリックします。次に、\[設定を変更する\] をクリックし、\[インターネット検索の動作を変更する\] をクリックします。
 
###### HTTP 経由の印刷をオフにする
 
**表 A.24:HTTP 経由の印刷オフの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
この設定を使用すると、このクライアントからの HTTP 経由の印刷を無効にすることができます。HTTP 経由の印刷では、クライアントはイントラネットおよびインターネット上のプリンタで印刷できます。この設定を有効にすると、クライアントは HTTP を経由してインターネット プリンタで印刷できません。
 
印刷時に HTTP 経由で送信される情報は保護されないので、悪意のあるユーザーによって傍受される可能性があります。そのため、HTTP 経由の印刷は通常はエンタープライズ環境や高セキュリティ環境では使用しません。この機能をオフにすると、誤って使用されることがなくなります。誤って使用されると、安全ではない印刷ジョブによってセキュリティが侵害される可能性があります。
 
**注 :** この設定は、インターネット印刷のクライアント側のみに影響します。コンピュータがインターネット プリント サーバーとして機能し、共有プリンタを HTTP 経由で使用可能にすることを防ぐことはできません。
 
###### プリンタ ドライバの HTTP 経由でのダウンロードをオフにする
 
**表 A.25:プリンタ ドライバの HTTP 経由でのダウンロード オフの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**プリンタ ドライバの HTTP 経由でのダウンロードをオフにする**ポリシー設定では、コンピュータが HTTP 経由でプリンタ ドライバ パッケージをダウンロードできるかどうかを指定します。HTTP 経由の印刷をセットアップするために、場合によっては、オペレーティング システムの標準インストールには付属していないドライバを HTTP 経由でダウンロードする必要があります。プリンタ ドライバが HTTP 経由でダウンロードされないように、このポリシー設定の値を \[有効\] に設定することをお勧めします。
 
**注 :** この設定では、クライアントが HTTP を経由してイントラネットやインターネット上のプリンタで印刷することは防止できません。この設定で禁止される対象は、まだローカルでインストールされていないドライバのダウンロードのみです。
 
###### Windows Update でのデバイス ドライバの検索をオフにする
 
**表 A.26:Windows Update でのデバイス ドライバ検索オフの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**Windows Update でのデバイス ドライバの検索をオフにする**ポリシー設定では、デバイス ドライバがローカルにない場合に、Windows Update でデバイス ドライバを検索するかどうかを指定します。
 
インターネットからデバイス ドライバをダウンロードすることにはリスクが伴うので、このポリシー設定の値は、高セキュリティ環境では \[有効\] に設定し、エンタープライズ環境では \[無効\] に設定することをお勧めします。この設定を推奨する理由は、ドライバのダウンロードを悪用する可能性のある種類の攻撃は、通常は適切なエンタープライズ リソースおよび構成管理によって軽減されるからです。
 
**注 :管理用テンプレート\\システム**の**Windows Update でのデバイス ドライバ検索についての確認をしない**ポリシー設定も参照してください。このポリシー設定では、デバイスがローカルにない場合、Windows Update でデバイス ドライバを検索する前に管理者に確認するダイアログ ボックスを表示するかどうかを指定します。
 
#### Windows ファイアウォール\\ドメイン プロファイル
 
このセクションの設定では、Windows ファイアウォールのドメイン プロファイルを構成します。Windows ファイアウォールは、コンピュータがドメイン環境にあるかどうかを動的に判断し、その判断に基づいて環境に合ったファイアウォール構成を適用します。この機能により、コンピュータの場所によって異なるファイアウォール設定を展開できます。
 
ドメイン環境が検出されると、常にドメイン プロファイルが使用されます。多くの場合、ドメイン環境には他の保護手段があるので、ドメイン プロファイルは標準プロファイルよりも制限を少なくすることができます。標準プロファイルの構成については、後で説明します。
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
管理用テンプレート\\ネットワーク\\ネットワーク接続\\Windows ファイアウォール\\ドメイン プロファイル
 
##### Windows ファイアウォール: ネットワーク接続をすべて保護する (ドメイン プロファイル)
 
**表 A.27:ネットワーク接続をすべて保護 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: ネットワーク接続をすべて保護する**ポリシー設定では、Windows XP SP2 を実行しているすべてのコンピュータで Widows ファイアウォール (インターネット接続ファイアウォール) を有効にします。すべての環境にあるコンピュータのすべてのネットワーク接続を保護するため、この設定の値を \[有効\] に設定することをお勧めします。
 
\[無効\] に設定すると、Windows ファイアウォールは無効になり、Windows ファイアウォールの他のすべての設定が無視されます。
 
**注 :** このポリシー設定を有効にすると、Windows ファイアウォールが実行され、**コンピュータの構成\\管理用テンプレート\\ネットワーク\\ネットワーク接続\\DNS ドメイン ネットワーク上でのインターネット接続ファイアウォールの使用を禁止する**ポリシー設定は無視されます。
 
##### Windows ファイアウォール: 例外を許可しない (ドメイン プロファイル)
 
**表 A.28:例外を許可しない (ドメイン プロファイル) 設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: 例外を許可しない**ポリシー設定では、Windows ファイアウォールですべての不要な着信メッセージをブロックすることを指定します。このポリシー設定は、不要な着信メッセージを許可する他のすべての Windows ファイアウォールのポリシー設定に優先します。コントロール パネルの Windows ファイアウォールのコンポーネントで、このポリシー設定を有効にすると、\[例外を許可しない\] チェック ボックスがオンになり、管理者がオフにすることはできなくなります。
 
多くの環境には、不要な受信通信を通常運用の一環として許可する必要のあるアプリケーションやサービスが含まれます。このような場合は、アプリケーションやサービスが正常に実行されるように、このポリシーの値を \[無効\] に設定することを検討する必要があります。このポリシーを変更するときは、事前に環境をテストして、何を許可し、何を許可しないかを決定する必要があります。
 
**注** :この設定は外部攻撃者に対する強力な防御になります。新しいネットワーク ワームの発生など、外部からの攻撃に対する完全な保護が必要な場合は、\[有効\] に設定する必要があります。このポリシーの値を \[無効\] に設定すると、Windows ファイアウォールで、不要な着信メッセージを許可する他のポリシー設定が適用できるようになります。
 
##### Windows ファイアウォール: プログラムの例外を定義する (ドメイン プロファイル)
 
**表 A.29:プログラム例外定義 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
</tr>
</tbody>
</table>
 
一部のアプリケーションでは、通常は Windows ファイアウォールで許可されないネットワーク ポートを開いて使用する必要があります。**Windows ファイアウォール: プログラムの例外を定義する**ポリシー設定を使用すると、グループ ポリシーで定義されたプログラムの例外一覧を表示および変更できます。
 
このポリシーの値を \[有効\] に設定すると、プログラムの例外一覧を表示および変更できます。この一覧にプログラムを追加し、その状態を \[有効\] に設定すると、そのプログラムは、Windows ファイアウォールに開くように要求するすべてのポートで不要な着信メッセージを受信します。これは、そのポートが別のポリシー設定でブロックされている場合も同じです。
 
このポリシー設定の値を \[無効\] に設定すると、グループ ポリシーで定義されたプログラムの例外一覧は削除されます。
 
**注 :** 無効な定義文字列を入力しても、エラーはチェックされずに、その文字列が一覧に追加されます。入力内容がチェックされないため、まだインストールしていないプログラムを追加できます。また、スコープまたは状態の値が異なる同じプログラムの例外を誤って複数作成する可能性もあります。
 
##### Windows ファイアウォール: ローカル プログラムの例外を許可する (ドメイン プロファイル)
 
**表 A.30:ローカル プログラム例外許可 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: ローカル プログラムの例外を許可する**ポリシー設定を使用すると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用してローカル プログラムの例外一覧を定義できます。このポリシー設定を無効にすると、管理者はローカル プログラムの例外一覧を定義できないので、プログラムの例外はグループ ポリシーだけで決定します。\[有効\] に設定すると、ローカル管理者はコントロール パネルを使用してプログラムの例外をローカルで定義できます。
 
エンタープライズ クライアント コンピュータの場合、クライアントがローカル プログラムの例外を定義できるようにした方がいい場合があります。たとえば、組織のファイアウォール ポリシーの作成時に分析されなかったアプリケーション、または非標準のポート構成を必要とする新しいアプリケーションがこれに該当します。このような場合は、そのコンピュータが攻撃対象になる可能性が高くなることを認識したうえで、この設定を有効にすることもできます。
 
##### Windows ファイアウォール: リモート管理の例外を許可する (ドメイン プロファイル)
 
**表 A.31:リモート管理例外許可 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
多くの組織では、日常の運用でリモート コンピュータ管理を利用します。しかし、リモート管理プログラムに通常使用されるポートが一部の攻撃で悪用されています。Windows ファイアウォールでは、これらのポートをブロックできます。リモート管理を柔軟に行うことができるように、**Windows ファイアウォール: リモート管理の例外を許可する**ポリシー設定が用意されています。
 
このポリシー設定の値を \[有効\] に設定すると、リモート管理に関連付けられた不要な着信メッセージをコンピュータの TCP ポート 135 および 445 で受信できます。また、このポリシー設定によって、SVCHOST.EXE および LSASS.EXE で不要な着信メッセージを受信でき、またホストされるサービスで動的に割り当てられる追加ポートを開くことができます。追加ポートは通常は 1024 ～ 1034 の範囲内ですが、1024 ～ 65535 の任意のポートを使用可能です。この設定を有効にするときは、着信メッセージを許可する IP アドレスまたはサブネットを指定する必要もあります。
 
このポリシー設定の値を \[無効\] に設定すると、これらの例外は許可されません。
 
このポリシー設定は、エンタープライズ コンピュータでは必要に応じて有効にし、高セキュリティ コンピュータでは常に無効にすることをお勧めします。環境内のコンピュータでは、できる限り少ない数のコンピュータからリモート管理要求を受け入れるようにする必要があります。Windows ファイアウォールによる保護を最大限に高めるには、リモート管理に使用するコンピュータの IP アドレスとサブネットだけを指定してください。
 
**注** :任意のポリシー設定が TCP ポート 445 を開いているときには、**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定でブロックするように設定した場合でも、着信 ICMP エコー要求メッセージ (Ping ユーティリティから送信されるメッセージなど) は許可されます。TCP ポート 445 を開くことが可能なポリシー設定には、**Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する**、**Windows ファイアウォール: リモート管理の例外を許可する**、**Windows ファイアウォール: ポートの例外を定義する**などがあります。
 
##### Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する (ドメイン プロファイル)
 
**表 A.32:ファイルとプリンタの共有例外許可 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
このポリシー設定を使用すると、Windows ファイアウォールで UDP ポート 137 および 138 と TCP ポート 139 および 445 を開くように構成して、ファイルとプリンタを共有できます。このポリシー設定を有効にすると、Windows ファイアウォールはこれらのポートを開き、コンピュータが印刷ジョブ、および共有ファイルへのアクセス要求を受信できるようになります。この設定を有効にするときは、着信メッセージを許可する IP アドレスまたはサブネットを指定する必要があります。
 
このポリシー設定を無効にすると、これらのポートはブロックされ、コンピュータでファイルとプリンタの共有ができなくなります。
 
通常は、環境内の Windows XP を実行しているコンピュータでファイルやプリンタを共有することはないので、すべての環境でこのポリシーの値を \[無効\] に設定することをお勧めします。
 
**注 :**任意のポリシー設定が TCP ポート 445 を開いているときには、**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定でブロックするように設定した場合でも、着信 ICMP エコー要求メッセージ (Ping ユーティリティから送信されるメッセージなど) は許可されます。TCP ポート 445 を開くことが可能なポリシー設定には、**Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する**、**Windows ファイアウォール: リモート管理の例外を許可する**、**Windows ファイアウォール: ポートの例外を定義する**などがあります。
 
##### Windows ファイアウォール: ICMP の例外を許可する (ドメイン プロファイル)
 
**表 A.33:ICMP 例外許可 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定では、Windows ファイアウォールで許可する Internet Control Message Protocol (ICMP) メッセージの種類を定義します。ユーティリティでは、ICMP メッセージを使用して他のコンピュータの状態を判断できます。たとえば、Ping ではエコー要求メッセージが使用されます。
 
このポリシー設定の値を \[有効\] に設定する場合は、コンピュータの送受信を許可する ICMP メッセージの種類を指定する必要があります。\[無効\] に設定すると、すべての不要な着信 ICMP メッセージおよび一覧内の発信 ICMP メッセージがブロックされます。その結果、ブロックされた ICMP メッセージを使用するユーティリティは、コンピュータでこれらのメッセージの送受信ができなくなります。
 
数多くの攻撃ツールは ICMP メッセージを受け入れるコンピュータを利用し、これらのメッセージを使用してさまざまな攻撃を仕掛けます。ただし、アプリケーションの中には、正常に動作するために ICMP メッセージが必要なものもあります。そのため、このポリシー設定の値は、できる限り \[無効\] に設定することをお勧めします。環境内で特定の ICMP メッセージが Windows ファイアウォールを通過するようにする必要がある場合は、該当するメッセージの種類を指定します。
 
**注 :**任意のポリシー設定が TCP ポート 445 を開いているときには、**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定でブロックするように設定した場合でも、着信 ICMP エコー要求メッセージ (Ping ユーティリティから送信されるメッセージなど) は許可されます。TCP ポート 445 を開くことが可能なポリシー設定には、**Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する**、**Windows ファイアウォール: リモート管理の例外を許可する**、**Windows ファイアウォール: ポートの例外を定義する**などがあります。
 
##### Windows ファイアウォール: リモート デスクトップの例外を許可する (ドメイン プロファイル)
 
**表 A.34:リモート デスクトップ例外許可 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
</tr>
</tbody>
</table>
 
多くの組織では、通常のトラブルシューティングの手順または操作でリモート デスクトップ接続を使用します。しかし、リモート デスクトップに通常使用されるポートを悪用する攻撃が存在します。リモート管理を柔軟に行うことができるように、**Windows ファイアウォール: リモート デスクトップの例外を許可する**ポリシー設定が用意されています。
 
このポリシー設定を有効にすると、Windows ファイアウォールが受信接続用に TCP ポート 3389 を開くように構成されます。また、このポリシー設定を有効にするときは、着信メッセージを許可する IP アドレスまたはサブネットを指定する必要があります。
 
このポリシー設定を無効にすると、このポートはブロックされ、コンピュータはリモート デスクトップ要求を受信できなくなります。管理者がローカル ポートの例外一覧にポートを追加することでポートを開こうとしても、Windows ファイアウォールはポートを開きません。
 
一部の攻撃で、開いているポート 3389 が悪用される可能性があります。リモート デスクトップが提供する強化された管理機能を維持するには、このポリシー設定の値を \[有効\] に設定し、リモート管理に使用するコンピュータの IP アドレスまたはサブネットを指定する必要があります。環境内のコンピュータでは、できる限り少ない数のコンピュータからリモート デスクトップ要求を受け入れるようにする必要があります。
 
##### Windows ファイアウォール: UPnP フレームワークの例外を許可する (ドメイン プロファイル)
 
**表 A.35:UPnP フレームワーク例外許可 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: UPnP フレームワークの例外を許可する**ポリシー設定は、ファイアウォールが組み込まれたルーターなどのネットワーク デバイスから送信された、不要なプラグ アンド プレイ メッセージをコンピュータが受信することを許可します。これらのメッセージを受信するため、Windows ファイアウォールは TCP ポート 2869 および UDP ポート 1900 を開きます。
 
このポリシー設定を有効にすると、Windows ファイアウォールはこれらのポートを開き、コンピュータはプラグ アンド プレイ メッセージを受信します。この設定を有効にするときは、着信メッセージを許可する IP アドレスまたはサブネットを指定する必要があります。このポリシー設定を無効にすると、Windows ファイアウォールはこれらのポートをブロックし、コンピュータはプラグ アンド プレイ メッセージを受信しなくなります。
 
UPnP ネットワーク トラフィックをブロックすると、環境内でコンピュータの攻撃対象が実質的に減少します。ネットワークで UPnP デバイスを使用する場合を除いて、このポリシー設定の値を \[無効\] に設定することをお勧めします。
 
##### Windows ファイアウォール: 通知を禁止する (ドメイン プロファイル)
 
**表 A.36:通知禁止 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
</tr>
</tbody>
</table>
 
Windows ファイアウォールは、プログラムの例外一覧にプログラムを追加する要求を受け取ったときに、ユーザーに対して通知を表示できます。ユーザーに対する通知は、プログラムがポートを開こうとしたときに、Windows ファイアウォールの現在のルールによって開くことができない場合に表示されます。**Windows ファイアウォール: 通知を禁止する**ポリシー設定では、これらの設定をユーザーに対して表示するかどうかを指定します。
 
このポリシーの値を \[有効\] に設定すると、通知は表示されません。\[無効\] に設定すると、通知が表示されます。
 
エンタープライズ セキュリティ環境または高セキュリティ環境では、通常はユーザーがこれらのメッセージへの応答としてアプリケーションやポートを追加することが許可されません。このような場合では、メッセージによってユーザーに権限がないことが通知されます。ユーザーが権限を持っていない場合は、このポリシーの値を \[有効\] に設定する必要があります。例外を許可するようにユーザーを構成している環境では、このポリシーの値を \[無効\] に設定する必要があります。
 
##### Windows ファイアウォール: マルチキャストまたはブロードキャスト要求に対するユニキャスト応答を禁止する (ドメイン プロファイル)
 
**表 A.37:ユニキャスト応答禁止 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: マルチキャストまたはブロードキャスト要求に対するユニキャスト応答を禁止する**ポリシー設定は、コンピュータからのマルチキャスト メッセージおよびブロードキャスト メッセージに対するユニキャスト応答の受信を禁止します。このポリシー設定を有効にすると、コンピュータから他のコンピュータにマルチキャスト メッセージまたはブロードキャスト メッセージが送信されたときに、Windows ファイアウォールは、送信先のコンピュータから送信されるユニキャスト応答をブロックします。このポリシー設定を無効にすると、コンピュータから他のコンピュータにマルチキャスト メッセージまたはブロードキャスト メッセージが送信されたときに、Windows ファイアウォールは、送信先のコンピュータからのユニキャスト応答を最大で 3 秒間待ってから、その後の応答をすべてブロックします。
 
通常は、マルチキャスト メッセージまたはブロードキャスト メッセージに対するユニキャスト応答は受信しません。ユニキャスト応答が発生している場合には、サービス拒否 (DoS) 攻撃が行われるか、または攻撃者によって既知の稼動中のコンピュータが調査される可能性があります。このような攻撃を防止するため、このポリシー設定の値を \[有効\] に設定することをお勧めします。
 
**注 :** ユニキャスト メッセージが、コンピュータから送信された 動的ホスト構成プロトコル (DHCP) ブロードキャスト メッセージに対する応答である場合は、このポリシー設定には効力はありません。Windows ファイアウォールは、DHCP ユニキャスト応答を常に許可します。ただし、このポリシー設定は、名前の競合を検出する NetBIOS メッセージを妨げる可能性があります。
 
##### Windows ファイアウォール: ポートの例外を定義する (ドメイン プロファイル)
 
**表 A.38:ポート例外定義 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
</tr>
</tbody>
</table>
 
Windows ファイアウォールのポートの例外一覧はグループ ポリシーで定義する必要があります。それにより、ポートの例外を一元的に管理および展開し、ローカル管理者が強度の低いセキュリティ設定を行わないようにできます。**Windows ファイアウォール: ポートの例外を定義する**ポリシー設定を使用すると、これらの設定を一元管理できます。
 
このポリシー設定を有効にすると、グループ ポリシーで定義されたポートの例外一覧を表示および変更できます。ポートの例外一覧を表示して変更するには、このポリシー設定の値を \[有効\] に設定し、\[表示\] をクリックします。無効な定義文字列を入力すると、エラーはチェックされずにその文字列が一覧に追加されます。このため、スコープや状態の値が異なる同じポートのエントリを誤って複数作成する可能性があります。
 
このポリシー設定を無効にすると、グループ ポリシーで定義されたポートの例外一覧は削除されますが、他のポリシー設定で引き続きポートを開いたりブロックしたりすることができます。また、ローカル ポートの例外一覧が存在する場合でも、**Windows ファイアウォール: ローカル ポートの例外を許可する**ポリシー設定を有効にしない限り、一覧は無視されます。
 
特定のポートを開く必要のある非標準アプリケーションがある環境では、プログラムの例外を展開することを検討する必要があります。プログラムの例外を定義できない場合に限り、このポリシー設定を有効にし、ポートの例外一覧を指定することをお勧めします。プログラムの例外を指定すると、指定したプログラムの実行中にのみ不要なネットワーク トラフィックを受け付けることができます。ポートの例外を指定すると、指定したポートが常に開いた状態になります。
 
**注 :**任意のポリシー設定が TCP ポート 445 を開いているときには、**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定でブロックするように設定した場合でも、着信 ICMP エコー要求メッセージ (Ping ユーティリティから送信されるメッセージなど) は許可されます。TCP ポート 445 を開くことが可能なポリシー設定には、**Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する**、**Windows ファイアウォール: リモート管理の例外を許可する**、**Windows ファイアウォール: ポートの例外を定義する**などがあります。
 
##### Windows ファイアウォール: ローカル ポートの例外を許可する (ドメイン プロファイル)
 
**表 A.39:ローカル ポート例外許可 (ドメイン プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: ローカル ポートの例外を許可する**ポリシー設定を使用すると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用してローカル ポートの例外一覧を定義できます。Windows ファイアウォールではポートの例外一覧を 2 つ使用できます。もう 1 つは **Windows ファイアウォール: ポートの例外を定義する**ポリシー設定で定義します。
 
このポリシー設定を有効にすると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用して、ローカル ポートの例外一覧を定義できます。無効にすると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用した例外一覧の作成ができなくなります。
 
エンタープライズ セキュリティ環境または高セキュリティ環境では、組織全体のポリシーに優先する独自のポート例外一覧を作成する権限は、通常、ローカル管理者にはありません。そのため、このポリシーの値を \[無効\] に設定することをお勧めします。
 
#### Windows ファイアウォール\\標準プロファイル
 
このセクションのポリシー設定では、Windows ファイアウォールの標準プロファイルを構成します。Windows ファイアウォールは、コンピュータがドメイン環境にあるかどうかを動的に判断し、その判断に基づいて環境に合ったファイアウォール構成を適用します。この機能により、コンピュータの場所によって異なるファイアウォール設定を展開できます。
 
非ドメイン環境が検出されると、標準プロファイルが使用されます。多くの場合、標準プロファイルはドメイン プロファイルよりも制限が多くなります。これは、ドメイン環境では基本レベルのセキュリティが提供されると見なされるからです。標準プロファイルは、コンピュータが、ホテルのネットワークや公共のワイヤレス アクセス ポイントなど、信頼されていないネットワークに接続されているときに使用することを目的としています。このような環境には未知の脅威があるので、セキュリティ保護対策を強化する必要があります。
 
Windows XP が Network Location Awareness (NLA) を使用して接続先のネットワークの種類を判別するしくみについては、<http://www.microsoft.com/japan/technet/community/columns/cableguy/cg0504.mspx> の「ネットワーク関連のグループ ポリシー設定におけるネットワークの決定動作」を参照してください。
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
管理用テンプレート\\ネットワーク\\ネットワーク接続\\Windows ファイアウォール\\標準プロファイル
 
##### Windows ファイアウォール: ネットワーク接続をすべて保護する (標準プロファイル)
 
**表 A.40:ネットワーク接続をすべて保護 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: ネットワーク接続をすべて保護する**ポリシー設定では、Windows XP SP2 を実行しているすべてのコンピュータで Widows ファイアウォール (インターネット接続ファイアウォール) を有効にします。すべての環境で、すべてのネットワーク接続をファイアウォールで保護する必要があるため、このポリシー設定の値を \[有効\] に設定します。
 
\[無効\] に設定すると、Windows ファイアウォールは無効になり、Windows ファイアウォールの他のすべての設定が無視されます。
 
**注 :** このポリシー設定を有効にすると、Windows ファイアウォールが実行され、**コンピュータの構成\\管理用テンプレート\\ネットワーク\\ネットワーク接続\\DNS ドメイン ネットワーク上でのインターネット接続ファイアウォールの使用を禁止する**ポリシー設定は無視されます。
 
##### Windows ファイアウォール: 例外を許可しない (標準プロファイル)
 
**表 A.41:例外を許可しない (標準プロファイル) 設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: 例外を許可しない**ポリシー設定では、Windows ファイアウォールですべての不要な着信メッセージをブロックすることを指定します。このポリシー設定は、不要な着信メッセージを許可する他のすべての Windows ファイアウォールのポリシー設定に優先します。コントロール パネルの Windows ファイアウォールのコンポーネントで、このポリシー設定を有効にすると、\[例外を許可しない\] チェック ボックスがオンになり、管理者がオフにすることはできなくなります。
 
**注 :**この設定は外部の攻撃者に対する強力な防御になります。他のポリシー設定で例外を指定する場合を除いて、このポリシーは \[有効\] に設定する必要があります。このポリシーの値を \[無効\] に設定すると、不要な着信メッセージを許可する他のポリシー設定を Windows ファイアウォール で適用できるようになります。
 
##### Windows ファイアウォール: プログラムの例外を定義する (標準プロファイル)
 
**表 A.42:プログラム例外定義 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
<td style="border:1px solid black;">推奨</td>
</tr>
</tbody>
</table>
 
一部のアプリケーションでは、通常は Windows ファイアウォールで許可されないネットワーク ポートを開いて使用する必要があります。**Windows ファイアウォール: プログラムの例外を定義する**ポリシー設定を使用すると、グループ ポリシーで定義されたプログラムの例外一覧を表示および変更できます。
 
このポリシーの値を \[有効\] に設定すると、プログラムの例外一覧を表示および変更できます。この一覧にプログラムを追加し、その状態を \[有効\] に設定すると、そのプログラムは、Windows ファイアウォールに開くように要求するすべてのポートで不要な着信メッセージを受信します。これは、そのポートが別のポリシー設定でブロックされている場合も同じです。
 
このポリシー設定の値を \[無効\] に設定すると、グループ ポリシーで定義されたプログラムの例外一覧は削除されます。
 
**注 :** 無効な定義文字列を入力しても、エラーはチェックされずに、その文字列が一覧に追加されます。この機能を使用すると、まだインストールしていないプログラムを追加できますが、スコープや状態の値が異なる同じプログラムのエントリを誤って複数作成する可能性があります。
 
##### Windows ファイアウォール: ローカル プログラムの例外を許可する (標準プロファイル)
 
**表 A.43:ローカル プログラム例外許可 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: ローカル プログラムの例外を許可する**ポリシー設定を使用すると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用してローカル プログラムの例外一覧を定義できます。このポリシー設定を無効にすると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用して例外一覧を定義できなくなり、プログラムの例外はグループ ポリシーだけで決定されるようになります。このポリシー設定を有効に設定すると、ローカル管理者はコントロール パネルを使用してプログラムの例外をローカルで定義できるようになります。
 
##### Windows ファイアウォール: リモート管理の例外を許可する (標準プロファイル)
 
**表 A.44:リモート管理例外許可 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
多くの組織では、日常の運用でリモート コンピュータ管理を利用します。しかし、リモート管理プログラムに通常使用されるポートが一部の攻撃で悪用されています。この問題に対処するために、Windows ファイアウォールでこれらのポートをブロックできます。リモート管理を柔軟に行うことができるように、**Windows ファイアウォール: リモート管理の例外を許可する**ポリシー設定が用意されています。
 
このポリシー設定の値を \[有効\] に設定すると、リモート管理に関連付けられた不要な着信メッセージをコンピュータの TCP ポート 135 および 445 で受信できます。また、このポリシー設定によって、SVCHOST.EXE および LSASS.EXE で不要な着信メッセージを受信でき、またホストされるサービスで動的に割り当てられる追加ポートを開くことができます。追加ポートは通常は 1024 ～ 1034 の範囲内ですが、1024 ～ 65535 の任意のポートを使用可能です。この設定を有効にするときは、着信メッセージを許可する IP アドレスまたはサブネットを指定する必要もあります。
 
このポリシー設定の値を \[無効\] に設定すると、これらの例外は許可されません。
 
TCP ポート 135 および 445 を悪用する既知の攻撃を回避するため、標準プロファイルのすべてのコンピュータに対して、この設定を無効にすることをお勧めします。
 
**注 :**任意のポリシー設定が TCP ポート 445 を開いているときには、**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定でブロックするように設定した場合でも、着信 ICMP エコー要求メッセージ (Ping ユーティリティから送信されるメッセージなど) は許可されます。TCP ポート 445 を開くことが可能なポリシー設定には、**Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する**、**Windows ファイアウォール: リモート管理の例外を許可する**、**Windows ファイアウォール: ポートの例外を定義する**などがあります。
 
##### Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する (標準プロファイル)
 
**表 A.45:ファイルとプリンタの共有例外許可 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
このポリシー設定を使用すると、Windows ファイアウォールで UDP ポート 137 および 138 と TCP ポート 139 および 445 を開くように構成して、ファイルとプリンタを共有できます。このポリシー設定を有効にすると、Windows ファイアウォールはこれらのポートを開き、コンピュータが印刷ジョブ、および共有ファイルへのアクセス要求を受信できまるようになります。この設定を有効にするときは、着信メッセージを許可する IP アドレスまたはサブネットを指定する必要があります。
 
このポリシー設定を無効にすると、これらのポートはブロックされ、コンピュータでファイルとプリンタの共有ができなくなります。
 
通常は、環境内の Windows XP を実行しているコンピュータでファイルやプリンタを共有することはないので、すべての環境でこのポリシーの値を \[無効\] に設定することをお勧めします。
 
**注 :**任意のポリシー設定が TCP ポート 445 を開いているときには、**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定でブロックするように設定した場合でも、着信 ICMP エコー要求メッセージ (Ping ユーティリティから送信されるメッセージなど) は許可されます。TCP ポート 445 を開くことが可能なポリシー設定には、**Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する**、**Windows ファイアウォール: リモート管理の例外を許可する**、**Windows ファイアウォール: ポートの例外を定義する**などがあります。
 
##### Windows ファイアウォール: ICMP の例外を許可する (標準プロファイル)
 
**表 A.46:ICMP 例外許可 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定では、Windows ファイアウォールで許可する Internet Control Message Protocol (ICMP) メッセージの種類を定義します。ユーティリティでは、ICMP メッセージを使用して他のコンピュータの状態を判断できます。たとえば、Ping ユーティリティではエコー要求メッセージが使用されます。
 
このポリシー設定の値を \[有効\] に設定する場合は、コンピュータの送受信を許可する ICMP メッセージの種類を指定する必要があります。\[無効\] に設定すると、すべての不要な着信 ICMP メッセージおよび一覧内の発信 ICMP メッセージがブロックされます。その結果、ブロックされた ICMP メッセージを使用するユーティリティは、コンピュータでこれらのメッセージの送受信ができなくなります。
 
数多くの攻撃ツールは ICMP メッセージを受け入れるコンピュータを利用し、これらのメッセージを使用してさまざまな攻撃を仕掛けます。ただし、アプリケーションの中には、正常に動作するために ICMP メッセージが必要なものもあります。そのため、このポリシー設定の値は、できる限り \[無効\] に設定することをお勧めします。信頼されていないネットワークにコンピュータが接続されている場合は、\[無効\] に設定する必要があります。
 
**注 :**任意のポリシー設定が TCP ポート 445 を開いているときには、**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定でブロックするように設定した場合でも、着信 ICMP エコー要求メッセージ (Ping ユーティリティから送信されるメッセージなど) は許可されます。TCP ポート 445 を開くことが可能なポリシー設定には、**Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する**、**Windows ファイアウォール: リモート管理の例外を許可する**、**Windows ファイアウォール: ポートの例外を定義する**などがあります。
 
##### Windows ファイアウォール: リモート デスクトップの例外を許可する (標準プロファイル)
 
**表 A.47:リモート デスクトップ例外許可 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
多くの組織では、通常のトラブルシューティングの手順または操作でリモート デスクトップ接続を使用します。しかし、リモート デスクトップに通常使用されるポートを悪用する攻撃が存在します。リモート管理を柔軟に行うことができるように、**Windows ファイアウォール: リモート デスクトップの例外を許可する**ポリシー設定が用意されています。
 
このポリシー設定を有効にすると、Windows ファイアウォールが受信接続用に TCP ポート 3389 を開くように構成されます。また、このポリシー設定を有効にするときは、着信メッセージを許可する IP アドレスまたはサブネットを指定する必要があります。
 
このポリシー設定を無効にすると、このポートはブロックされ、コンピュータはリモート デスクトップ要求を受信できなくなります。管理者がローカル ポートの例外一覧にポートを追加することでポートを開こうとしても、Windows ファイアウォールはポートを開きません。
 
一部の攻撃で、開いているポート 3389 が悪用される可能性があります。リモート デスクトップが提供する強化された管理機能を維持するには、このポリシー設定の値を \[有効\] に設定し、リモート管理に使用するコンピュータの IP アドレスまたはサブネットを指定する必要があります。環境内のコンピュータでは、できる限り少ない数のコンピュータからリモート デスクトップ要求を受け入れるようにする必要があります。
 
##### Windows ファイアウォール: UPnP フレームワークの例外を許可する (標準プロファイル)
 
**表 A.48:UPnP フレームワーク例外許可 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: UPnP フレームワークの例外を許可する**ポリシー設定は、ファイアウォールが組み込まれたルーターなどのネットワーク デバイスから送信された、不要なプラグ アンド プレイ メッセージをコンピュータが受信することを許可します。これらのメッセージを受信するため、Windows ファイアウォールは TCP ポート 2869 および UDP ポート 1900 を開きます。
 
このポリシー設定を有効にすると、Windows ファイアウォールはこれらのポートを開き、コンピュータはプラグ アンド プレイ メッセージを受信します。この設定を有効にするときは、着信メッセージを許可する IP アドレスまたはサブネットを指定する必要があります。このポリシー設定を無効にすると、Windows ファイアウォールはこれらのポートをブロックし、コンピュータはプラグ アンド プレイ メッセージを受信しなくなります。
 
UPnP ネットワーク トラフィックをブロックすると、コンピュータの攻撃対象が実質的に減少します。信頼されていないネットワークでは、このポリシー設定を常に \[無効\] に設定する必要があります。
 
##### Windows ファイアウォール: 通知を禁止する (標準プロファイル)
 
**表 A.49:通知禁止 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
</tr>
</tbody>
</table>
 
Windows ファイアウォールは、プログラムの例外一覧にプログラムを追加する要求を受け取ったときに、ユーザーに対して通知を表示できます。ユーザーに対する通知は、プログラムがポートを開こうとしたときに、Windows ファイアウォールの現在のルールによって開くことができない場合に表示されます。**Windows ファイアウォール: 通知を禁止する**ポリシー設定では、これらの設定をユーザーに対して表示するかどうかを指定します。
 
このポリシーの値を \[有効\] に設定すると、通知は表示されません。\[無効\] に設定すると、通知が表示されます。
 
エンタープライズ セキュリティ環境または高セキュリティ環境では、通常はユーザーがこれらのメッセージへの応答としてアプリケーションやポートを追加することが許可されません。このような場合では、メッセージによってユーザーに権限がないことが通知されます。ユーザーが権限を持っていない場合は、このポリシーの値を \[有効\] に設定する必要があります。例外を許可するようにユーザーを構成している環境では、このポリシーの値を \[無効\] に設定する必要があります。
 
##### Windows ファイアウォール: マルチキャストまたはブロードキャスト要求に対するユニキャスト応答を禁止する (標準プロファイル)
 
**表 A.50:ユニキャスト応答禁止 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: マルチキャストまたはブロードキャスト要求に対するユニキャスト応答を禁止する**ポリシー設定は、コンピュータからのマルチキャスト メッセージおよびブロードキャスト メッセージに対するユニキャスト応答の受信を禁止します。このポリシー設定を有効にすると、コンピュータから他のコンピュータにマルチキャスト メッセージまたはブロードキャスト メッセージが送信されたときに、Windows ファイアウォールは、送信先のコンピュータから送信されるユニキャスト応答をブロックします。このポリシー設定を無効にすると、コンピュータから他のコンピュータにマルチキャスト メッセージまたはブロードキャスト メッセージが送信されたときに、Windows ファイアウォールは、送信先のコンピュータからのユニキャスト応答を最大で 3 秒間待ってから、その後の応答をすべてブロックします。
 
通常は、マルチキャスト メッセージまたはブロードキャスト メッセージに対するユニキャスト応答は受信しません。ユニキャスト応答が発生している場合には、サービス拒否 (DoS) 攻撃が行われるか、または攻撃者によって既知の稼動中のコンピュータが調査される可能性があります。このような攻撃を防止するため、このポリシー設定の値を \[有効\] に設定することをお勧めします。
 
**注 :** ユニキャスト メッセージが、コンピュータから送信された 動的ホスト構成プロトコル (DHCP) ブロードキャスト メッセージに対する応答である場合は、このポリシー設定には効力はありません。Windows ファイアウォールは、DHCP ユニキャスト応答を常に許可します。ただし、このポリシー設定は、名前の競合を検出する NetBIOS メッセージを妨げる可能性があります。
 
##### Windows ファイアウォール: ポートの例外を定義する (標準プロファイル)
 
**表 A.51:ポート例外定義 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
<td style="border:1px solid black;">推奨しない</td>
</tr>
</tbody>
</table>
 
Windows ファイアウォールのポートの例外一覧はグループ ポリシーで定義する必要があります。それにより、ポートの例外を一元的に管理および展開し、ローカル管理者が強度の低いセキュリティ設定を行わないようにできます。**Windows ファイアウォール: ポートの例外を定義する**ポリシー設定を使用すると、これらの設定を一元管理できます。
 
このポリシー設定を有効にすると、グループ ポリシーで定義されたポートの例外一覧を表示および変更できます。ポートの例外一覧を表示して変更するには、このポリシー設定の値を \[有効\] に設定し、\[表示\] をクリックします。無効な定義文字列を入力すると、エラーはチェックされずにその文字列が一覧に追加されます。このため、スコープや状態の値が異なる同じポートのエントリを誤って複数作成する可能性があります。
 
このポリシー設定を無効にすると、グループ ポリシーで定義されたポートの例外一覧は削除されますが、他のポリシー設定で引き続きポートを開いたりブロックしたりすることができます。また、ローカル ポートの例外一覧が存在する場合でも、**Windows ファイアウォール: ローカル ポートの例外を許可する**ポリシー設定を有効にしない限り、一覧は無視されます。
 
特定のポートを開く必要のある非標準アプリケーションがある環境では、プログラムの例外を展開することを検討する必要があります。プログラムの例外を定義できない場合に限り、このポリシー設定を有効にし、ポートの例外一覧を指定することをお勧めします。プログラムの例外を指定すると、指定したプログラムの実行中にのみ不要なネットワーク トラフィックを受け付けることができます。ポートの例外を指定すると、指定したポートが常に開いた状態になります。
 
**注 :** 任意のポリシー設定が TCP ポート 445 を開いているときには、**Windows ファイアウォール: ICMP の例外を許可する**ポリシー設定でブロックするように設定した場合でも、着信 ICMP エコー要求メッセージ (Ping ユーティリティから送信されるメッセージなど) は許可されます。TCP ポート 445 を開くことが可能なポリシー設定には、**Windows ファイアウォール: ファイルとプリンタの共有の例外を許可する**、**Windows ファイアウォール: リモート管理の例外を許可する**、**Windows ファイアウォール: ポートの例外を定義する**などがあります。
 
##### Windows ファイアウォール: ローカル ポートの例外を許可する (標準プロファイル)
 
**表 A.52:ローカル ポート例外許可 (標準プロファイル) の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (デスクトップ)</th>
<th style="border:1px solid black;" >エンタープライズ クライアント環境 (ラップトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (デスクトップ)</th>
<th style="border:1px solid black;" >高セキュリティ環境 (ラップトップ)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
**Windows ファイアウォール: ローカル ポートの例外を許可する**ポリシー設定を使用すると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用してローカル ポートの例外一覧を定義できます。Windows ファイアウォールではポートの例外一覧を 2 つ使用できます。もう 1 つは **Windows ファイアウォール: ポートの例外を定義する**ポリシー設定で定義します。
 
このポリシー設定を有効にすると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用して、ローカル ポートの例外一覧を定義できます。無効にすると、管理者はコントロール パネルの Windows ファイアウォール コンポーネントを使用した例外一覧の作成ができなくなります。
 
エンタープライズ セキュリティ環境または高セキュリティ環境では、組織全体のポリシーに優先する独自のポート例外一覧を作成する権限は、通常、ローカル管理者にはありません。そのため、このポリシーの値を \[無効\] に設定することをお勧めします。
 
[](#mainsection)[ページのトップへ](#mainsection)
 
### ユーザーの構成の設定
 
この付録の残りのセクションでは、ユーザー構成の設定について説明します。ユーザーのアカウントが含まれる OU にリンクする GPO を介してこれらの設定を適用します。
 
**注 :** ユーザー構成の設定は、Microsoft Active Directory ディレクトリ サービス ドメインでユーザーがログオンするすべてのクライアントに適用されますコンピュータ構成の設定は、クライアントにログオンするユーザーに関係なく、Active Directory の GPO で管理しているすべてのクライアントに適用されます。これらの理由から、このセクションの表は、このガイドで定義するエンタープライズ クライアントおよび高セキュリティ環境で推奨される設定のみを示しています。これらの設定には、デスクトップごとおよびラップトップごとの既定はありません。
 
#### 添付ファイル マネージャ
 
グループ ポリシー オブジェクト エディタを使用して、適切な管理用テンプレートを構成します。既定の設定は、次の場所にあります。
 
ユーザーの構成\\管理用テンプレート\\Windows コンポーネント\\添付ファイル マネージャ
 
##### ゾーン情報を添付ファイルに保存しない
 
**表 A.53:ゾーン情報を保存しない設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境</th>
<th style="border:1px solid black;" >高セキュリティ環境</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">無効</td>
</tr>
</tbody>
</table>
 
**ゾーン情報を添付ファイルに保存しない**ポリシー設定を使用すると、Internet Explorer または Outlook Express の添付ファイルに元のゾーン情報 (制限付き、インターネット、イントラネット、ローカルなど) をマークするかどうかを管理できます。この設定が正しく機能するには、ファイルが NTFS ディスク パーティションにダウンロードされる必要があります。ゾーン情報を保存しない場合、Windows は添付ファイルの送信元ゾーンに基づく適切なリスク評価ができなくなります。
 
このポリシーの値を \[有効\] に設定すると、添付ファイルにはゾーン情報がマークされません。\[無効\] に設定すると、添付ファイルとそのゾーン情報が保存されます。危険な添付ファイルは、インターネット ゾーンなどの信頼されていない Internet Explorer ゾーンからダウンロードされることが多いので、各ファイルと共にできるだけ多くのセキュリティ情報が保存されるように、このポリシーを \[無効\] に設定することをお勧めします。
 
##### ゾーン情報を削除する方法を非表示にする
 
**表 A.54:ゾーン情報の削除方法の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境</th>
<th style="border:1px solid black;" >高セキュリティ環境</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
**ゾーン情報を削除する方法を非表示にする**ポリシー設定を使用すると、ユーザーがファイルのプロパティ シートの \[ブロックの解除\] をクリックするか、\[セキュリティの警告\] ダイアログ ボックスのチェック ボックスをオンにすることで、保存された添付ファイルからゾーン情報を手動で削除できるかどうかを管理できます。ゾーン情報を削除すると、ユーザーは、Windows が開くことを禁止した、危険な可能性のある添付ファイルを開くことができます。
 
このポリシー設定の値を \[有効\] に設定すると、このチェック ボックスと \[ブロックの解除\] ボタンは表示されません。\[無効\] に設定すると、このチェック ボックスと \[ブロックの解除\] ボタンが表示されます。危険な添付ファイルは、インターネット ゾーンなどの信頼されていない Internet Explorer ゾーンからダウンロードされることが多いので、各ファイルと共にできるだけ多くのセキュリティ情報が保存されるように、このポリシーを \[有効\] に設定することをお勧めします。
 
**注 :** ファイルと共にゾーン情報を保存するかどうかを構成するには、前述した**ゾーン情報を添付ファイルに保存しない**ポリシー設定を参照してください。
 
##### 添付ファイルを開くとき、ウイルス対策プログラムに通知する
 
**表 A.55:ウイルス対策プログラムへの通知の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >エンタープライズ クライアント環境</th>
<th style="border:1px solid black;" >高セキュリティ環境</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">有効</td>
</tr>
</tbody>
</table>
 
ウイルス対策プログラムは、ほとんどの環境で使用が義務付けられてきており、最新の攻撃に対する強力な防御になっています。**添付ファイルを開くとき、ウイルス対策プログラムに通知する**ポリシー設定を使用すると、登録されたウイルス対策プログラムに通知する動作を管理できます。
 
このポリシー設定の値を \[有効\] に設定すると、ユーザーが添付ファイルを開くときに、登録されたウイルス対策プログラムが呼び出され、そのプログラムによってファイルがスキャンされます。ウイルス対策プログラムによるスキャンが失敗した場合は、添付ファイルを開くことができません。\[無効\] に設定すると、ユーザーが添付ファイルを開くとき、登録されたウイルス対策プログラムは呼び出されません。
 
すべてのファイルを開く前にウイルス対策プログラムによって調べられるように、すべての環境でこのポリシーの値を \[有効\] に設定することをお勧めします。
 
**注 :** この機能が正常に動作するには、最新のウイルス対策プログラムをインストールする必要があります。最新のウイルス対策プログラムの多くでは、SP2 の新しい API が使用されます。
 
[](#mainsection)[ページのトップへ](#mainsection)
 
### まとめ
 
Windows XP SP2 でのセキュリティ サービスの管理性に関連する数多くの改善点により、管理者は複数のユーザーおよびコンピュータに、より詳細なセキュリティ設定を実装できます。この付録では、SP2 環境でセキュリティを強化するために使用する必要のある最も重要な設定について説明してきました。使用できるすべての設定については説明していませんが、この付録で説明した設定は、環境に直接、大きな影響があるものです。
 
SP2 は Window の旧バージョンから大幅に変更されているので、環境内でアプリケーションの互換性の問題が発生する可能性があります。すべての推奨設定は、実装する前に慎重にテストする必要があります。これらの設定は、指定された環境では十分にテストされ機能することが確認されていますが、実際の環境でテストしたときに必ずしも正常に機能するかは保証されません。
 
[](#mainsection)[ページのトップへ](#mainsection)
