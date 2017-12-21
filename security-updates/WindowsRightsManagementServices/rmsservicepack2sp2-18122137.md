---
TOCTitle: 'RMS Service Pack 2 (SP2) による展開の更新'
Title: 'RMS Service Pack 2 (SP2) による展開の更新'
ms:assetid: '27ee06a1-f467-4a6c-b662-45ddb5f8c13e'
ms:contentKeyID: 18122137
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc720225(v=WS.10)'
---

RMS Service Pack 2 (SP2) による展開の更新
=========================================

このセクションでは、既存の RMS が展開されている組織で Microsoft® Windows® Rights Management サービス (RMS) Service Pack 2 (SP2) をインストールするために役立つ情報を提供します。RMS SP2 で展開を更新する必要があるのは、既に RMS を展開済みの組織のみです。組織で RMS を初めて導入する場合は、このドキュメント コレクションの「RMS の展開計画」([http://go.microsoft.com/fwlink/?LinkId=74999](http://go.microsoft.com/fwlink/?linkid=74999)) および「RMS システムの展開」([http://go.microsoft.com/fwlink/?LinkID=75000](http://go.microsoft.com/fwlink/?linkid=75000)) のガイドラインに従って RMS SP2 を展開できます。

既存の RMS SP1 のインストールを削除せずに RMS SP2 をインストールできます。RMS SP2 のセットアップ プログラムは、RMS SP1 がインストールされていることを検出し、追加機能と設定を必要に応じて追加します。

> [!NOTE]
> サービス パックの適用されていない RMS サーバーから RMS SP2 へのアップグレードはサポートされていません。サービス パックの適用されていない RMS を使用している場合、RMS SP2 にアップグレードする前に、RMS SP1 にアップグレードする必要があります。RMS クライアントは、任意の前バージョンの RMS クライアントからアップグレードできます。 

**この項目の内容**

-   [RMS SP2 更新プログラムの準備](#bkmk_preparingforsp2update)
-   [RMS SP2 更新プログラムの実行](#bkmk_performingsp2update)
-   [クラスタの更新](#bkmk_updateclusters)
-   [RMS クライアントの更新](#bkmk_updateclients)
-   [RMS Version 1.0 との相互運用性](#bkmk_interop)
-   [RMS SP2 の削除](#bkmk_removingrms)

<span id="bkmk_PreparingForSP2Update"></span>
RMS SP2 更新プログラムの準備
----------------------------

RMS SP2 更新プログラムは、RMS の実行を中断せずに実行できます。ただし、RMS クラスタを更新する前に、次の作業を実行することをお勧めします。

-   構成データベースと RMS 秘密キーのバックアップ。詳細については、このドキュメント コレクションの RMS のシステム バックアップに関するページ ([http://go.microsoft.com/fwlink/?LinkId=75001](http://go.microsoft.com/fwlink/?linkid=75001)) を参照してください。
-   ソフトウェアベースの秘密キーを使用している場合は、RMS 秘密キー パスワードがあることを確認します。
-   以前に記録されたログ データベースを保持したい場合は、ログ データベースをバックアップします。
-   オペレーティング システムの最新の重要な更新プログラムおよびセキュリティ更新プログラムがクライアントおよびサーバーにインストール済みであることを確認します。重要な更新プログラムとセキュリティ更新プログラムがすべてインストールされていることを確認するには、\[スタート\] ボタンをクリックし、\[Windows Update\] をクリックして、画面に表示される指示に従います。

<span id="bkmk_PerformingSP2Update"></span>
RMS SP2 更新プログラムの実行
----------------------------

Windows Rights Management サービス Service Pack 2 セットアップ ウィザードが RMS インストールを検出した場合、現在の RMS SP1 インストールに対して、新しいファイルの追加と RMS SP2 で変更が必要なファイルの置換のみを実行します。既に RMS を正常に実行している場合、RMS SP2 のインストール後に再構成や構成の変更を実行しなくとも引き続き RMS を実行できます。

<span id="bkmk_UpdateClusters"></span>
クラスタの更新
--------------

クラスタ構成で RMS をインストールしている場合、インストールに対する更新プログラムの影響を最小限に留めるため、クラスタの更新の計画を立てる必要があります。組織で RMS SP2 をどのように実装するのが最適かを判断する際は、次の推奨事項を参考にしてください。

-   定石としては、クラスタのアップグレードの予測可能性を高め、アップグレード中にサービスのパフォーマンスが低下する機会を低減するように、RMS SP2 をクラスタ部分に一度にインストールします。
-   複数の RMS クラスタがある場合は、ルート証明クラスタを最初にアップグレードしてから、サブ登録したライセンス クラスタをアップグレードします。
-   複数のフォレストにまたがるグループの拡張を使用している場合、グループ メンバシップを複数のフォレストに拡張する RMS の機能に影響を与えずに、フォレスト内のクラスタを個別にアップグレードすることができます。
-   RMS SP2、RMS SP1、および RMS Version 1.0 サーバーは、それぞれが異なる Active Directory フォレストにあれば、共存と相互運用が可能です。同一のクラスタに異なるバージョンの RMS サーバーを共存させることはお勧めしません。
-   RMS SP2 セットアップ パッケージは、RMS SP2 をサーバーに新規インストールする際にも使用できます。この場合、RMS SP1 がインストールされている必要はありません。

<span id="bkmk_UpdateClients"></span>
RMS クライアントの更新
----------------------

新しい RMS SP2 クライアントは、Windows Update または Microsoft ダウンロード センターから入手できます。RMS SP2 クライアント セットアップ パッケージは、新バージョンの RMS SP2 クライアントをコンピュータにインストールする際にも使用できます。この場合、RMS Version 1.0 クライアントがインストールされている必要はありません。RMS SP2 クライアントには、下位互換機能が含まれており、RMS Version 1.0 を必要とする RMS 対応アプリケーションに対しても使用できます。

RMS クライアントの更新とインストールの詳細については、「RMS クライアントの配布」([http://go.microsoft.com/fwlink/?LinkId=75070](http://go.microsoft.com/fwlink/?linkid=75070)) を参照してください。

<span id="bkmk_InterOp"></span>
RMS Version 1.0 との相互運用性
------------------------------

RMS SP2 では多数の改善とパフォーマンスの強化が図られているため、インストールは次回のアップグレード サイクルに行う必要があります。RMS SP2 を実行している RMS サーバーとクライアントは、RMS SP2 を実行していない RMS サーバーおよびクライアントと完全に相互運用可能です。混在環境における動作については次の差異に注意してください。

-   オフライン登録を実行できるのは RMS SP1 以降を実行しているサーバーのみです。
-   セルフライセンス認証を実行できるのは RMS SP1 以降を実行しているクライアントのみです。
-   次の表は、混在環境でサポートされている機能の一覧です。

###  

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >RMS サーバーのバージョン</th>
<th style="border:1px solid black;" >バージョン 1 クライアントでサポートされている機能</th>
<th style="border:1px solid black;" >SP2 クライアントでサポートされている機能</th>
<th style="border:1px solid black;" >混在クライアント環境でサポートされている機能</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">1.0</td>
<td style="border:1px solid black;">以前のバージョンの機能すべて
サーバーのオフライン登録機能は使用できません。サーバーはインターネット経由で登録する必要があります。

クライアントのセルフライセンス認証機能は使用できません。</td>
<td style="border:1px solid black;">以前のバージョンの機能すべて
サーバーのオフライン登録機能は使用できません。

クライアントのセルフライセンス認証。</td>
<td style="border:1px solid black;">以前のバージョンの機能すべて
SP2 クライアントの場合、クライアントはセルフライセンス認証を実行できます。

Version 1 クライアントの場合、クライアントはインターネット経由でライセンス認証を実行する必要があります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SP2</td>
<td style="border:1px solid black;">以前のバージョンの機能すべて
サーバーのオフライン登録。

クライアントのセルフライセンス認証機能は使用できません。</td>
<td style="border:1px solid black;">すべての SP1 機能。

サーバーのオフライン登録。

クライアントのセルフライセンス認証。

サーバー ロックボックス。

Microsoft SQL Server™ 2005 は製品そのままの状態でサポートされています。</td>
<td style="border:1px solid black;">以前のバージョンのすべての機能と SP2 の機能。

サーバーのオフライン登録。

SP2 クライアントの場合、クライアントはセルフライセンス認証を実行できます。

Version 1 クライアントの場合、クライアントはインターネット経由でライセンス認証を実行する必要があります。</td>
</tr>
</tbody>
</table>
 

<span id="bkmk_RemovingRMS"></span>
RMS SP2 の削除
--------------

RMS SP2 のインストール後に RMS サーバーを以前の構成に戻したい場合は、コントロール パネルの \[プログラムの追加と削除\] を使用して、RMS SP2 を削除します。
