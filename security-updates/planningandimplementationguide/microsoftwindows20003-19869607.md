---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 第 3 章 ‐ セキュリティで保護された構成'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 第 3 章 ‐ セキュリティで保護された構成'
ms:assetid: '95fe8ebd-7386-4e95-aff8-5fca17435788'
ms:contentKeyID: 19869607
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277455(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 第 3 章 ‐ セキュリティで保護された構成

最終更新日: 2003年2月18日

この章では、評価された構成をサポートする Windows 2000 の標準のインストール ベースにおけるセキュリティ構成に変更を加える手順について、詳しく説明します。セキュリティ上の目的およびその目的を満たすために必要な構成上の措置を表にして示します。それらの措置は、 Windows 2000 Professional (スタンドアロンおよびドメイン メンバ)、Server (スタンドアロンおよびドメイン メンバ)、およびドメイン コントローラの構成ごとに列を分けて記述します。

ドメイン セキュリティ ポリシーをドメイン内のすべてのコンピュータに適用する場合、Windows 2000 Professional および Server 用に定義されている設定を、必要に応じてドメイン セキュリティ ポリシーの要件に適用します。このドキュメントに定義されているドメイン コントローラの設定はドメイン コントローラ セキュリティ ポリシーに対してのみ適用されます。

このドキュメントの第 4 章では、あらかじめ定義されているセキュリティ構成のテンプレートを適用することにより、この章に定義されているセキュリティの設定の大部分を自動化する手順を説明します。ユーザーに便利なように、このドキュメントの付録 E に Windows 2000 セキュリティ構成チェック リストを提示します。

##### トピック

[](#epaa)[Windows 2000 のセキュリティ ポリシー](#epaa)
[](#eoaa)[その他のセキュリティ構成インターフェイス](#eoaa)
[](#enaa)[アカウント ポリシー](#enaa)
[](#emaa)[ローカル ポリシー](#emaa)
[](#elaa)[監査ログの管理](#elaa)
[](#ekaa)[既定のグループ アカウント](#ekaa)
[](#ejaa)[既定のユーザー アカウント](#ejaa)
[](#eiaa)[システム サービス](#eiaa)
[](#ehaa)[ファイル システムのセキュリティ保護](#ehaa)
[](#egaa)[共有フォルダへのアクセス許可](#egaa)
[](#efaa)[レジストリのセキュリティ保護](#efaa)
[](#eeaa)[IPSec ポリシー](#eeaa)
[](#edaa)[ファイル システムの暗号化](#edaa)
[](#ecaa)[自動的なスクリーン ロックによる保護の有効化](#ecaa)
[](#ebaa)[システム修復ディスクの更新](#ebaa)
[](#eaaa)[セキュリティで保護された構成上でのアプリケーションのインストール手順](#eaaa)

### Windows 2000 のセキュリティ ポリシー

ここでは、さまざまなセキュリティ ポリシー ツールおよびセキュリティ ポリシーを適用する際の優先順位について説明します。既定では、グループ ポリシーは累積的に継承され、Active Directory コンテナ内のすべてのコンピュータに適用されます。グループ ポリシーはグループ ポリシー オブジェクト (GPO) を通じて管理します。GPO とは、サイト、ドメインまたは組織単位 (OU) のような、特定の Active Directory オブジェクトに特殊な階層構造で添付されているデータ構造です。

いったん作成された GPO は LSDOU という標準的な順序で適用されます。この記号は、(1) ローカル、(2) サイト、(3) ドメイン、(4) 組織単位を意味します。順序が後のポリシーほど、前に適用されたポリシーよりも優先度が高くなります。ローカル グループ ポリシー オプションが最初に処理され、次にドメイン ポリシーが処理される順序です。あるコンピュータがドメインに属し、 ドメインのコンピュータ ポリシーとローカルのコンピュータ ポリシーの間に競合がある場合には、ドメインのポリシーが優先します。しかし、コンピュータがドメインに属さない場合には、ローカル グループ ポリシー オブジェクトが適用されます。

Active Directory およびグループ ポリシーが取り入れられているドメインにコンピュータが組み込まれたときに、ローカル グループ ポリシー オブジェクト (LGPO) が処理されます。ポリシーを継承しないオプションが指定されている場合でも、LGPO ポリシーは処理されることに注意してください。

ドメイン全体に関するアカウント ポリシー (パスワード、ロックアウト、Kerberos) はドメインの既定のグループ ポリシー オブジェクト (GPO) 内に定義されます。ドメイン コントローラ (DC) に関するローカル ポリシー (監査、ユーザー権利、およびセキュリティ オプション) はドメイン コントローラ の既定の GPO 内に定義されます。DC の場合、既定の DC GPO に定義されている設定は既定のドメイン GPO に定義されている設定よりも優先します。したがって、既定のドメイン GPO にユーザーの特権 (たとえば、ドメインにワークステーションを追加) を定義しても、そのドメイン内の DC には影響しません。

特定のグループ ポリシー オブジェクト内のグループ ポリシーを必ず適用し、そのポリシーが下位の Active Directory コンテナ内の GPO によって上書きされることを防止するオプションが存在します。たとえば、ドメインのレベルにある GPO が定義されており、その GPO を必ず適用するように指定されていれば、その GPOに含まれるポリシーはそのドメインに属するすべての OU に適用されます。つまり、下位レベルのコンテナ (OU) からそのドメインのグループ ポリシーを上書きすることはできません。

**注意** : アカウント ポリシー セキュリティ領域は、ドメイン内のコンピュータへの適用のされ方について、特別な扱いを受けます。ドメイン内の DC はすべて、**DC 用のコンピュータ オブジェクトがどこに存在しても**、ドメイン ノードにおいて構成された GPO からアカウント ポリシーを受け取ります。それにより、すべてのドメイン アカウントにアカウント ポリシーが一貫して適用されることが保証されます。ドメイン内の DC 以外のコンピュータはすべて、通常の GPO 階層に従って、それらのコンピュータに関するローカル アカウント用のポリシーを受け取ります。既定では、ローカル アカウント用にドメイン GPO 内で構成されているポリシーの設定が、メンバのワークステーションおよびサーバーに適用されます。しかし、下位レベルに別の GPO があって、それが既定の設定とは異なる場合、下位の設定が有効になります。

#### ローカル セキュリティ ポリシー

ローカル セキュリティ ポリシーは、ローカルコンピュータのセキュリティ用件の設定に使用されます。主に、スタンドアロン コンピュータ用または、ドメイン メンバのセキュリティに特化した設定の適用に使用されます。ネットワークで管理される Active Directory 内のローカル セキュリティ ポリシーの設定は、最も低い優先順位になります。

**ローカル セキュリティ ポリシーを開くには**

1.  管理者権限を持っているアカウントを使用して、コンピュータにログオンします。

2.  Windows 2000 Professional コンピュータにおいては、既定では **\[管理ツール\]** は \[スタート\] メニューのオプションとして表示されません。Windows 2000 Professional において **\[管理ツール\]** メニュー オプションを表示するには、**\[スタート\]** をクリックし、**\[設定\]** をポイントし、**\[タスクバーと \[スタート\] メニュー\]** を選択します。**\[タスクバーとスタート メニューのプロパティ\]** ウィンドウ内で、**\[詳細\]** タブをクリックします。**\[\[スタート\] メニュー のカスタマイズ\]** ダイアログ ボックス内で **\[管理ツールを表示する\]** チェック ボックスをオンにします。**\[OK\]** ボタンをクリックして、設定を終了します。

3.  **\[スタート\]** をクリックし、**\[プログラム\]** をポイントし、さらに **\[管理ツール\]** をポイントし、それから **\[ローカル セキュリティ ポリシー\]** をクリックします。すると、\[ローカル セキュリティ設定\] コンソールが開かれます。

    ![](images/Dd277455.w2ksc301s(ja-jp,TechNet.10).gif)
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc301(ja-jp,technet.10).gif)

    **注意** : ローカル セキュリティ ポリシーには、コンピュータのローカル設定、およびドメイン レベルのセキュリティ ポリシーの設定を追加した結果の有効な設定が表示されます。ドメイン レベルのセキュリティ ポリシーの設定は、下に示すように、いかなるローカル設定よりも優先します。

    ![](images/Dd277455.w2ksc302s(ja-jp,TechNet.10).gif)
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc302(ja-jp,technet.10).gif)

#### ドメイン セキュリティ ポリシー

ドメイン セキュリティ ポリシーはドメイン内のすべてのコンピュータに関するセキュリティ要件を設定して継承するために使用します。ドメイン セキュリティ ポリシーはドメイン内のすべてのコンピュータに対するローカル セキュリティ ポリシーに優先します。

**ドメイン セキュリティ ポリシーを開くには**

1.  管理者権限を持っているアカウントを使用して、ドメイン コントローラにログオンします。

2.  **\[スタート\]** をクリックし、**\[プログラム\]** をポイントし、**\[管理ツール\]** をポイントしてから、**\[ドメイン セキュリティ ポリシー\]** を選択します。すると、\[ドメイン セキュリティ ポリシー\] コンソールが開かれます。

    ![](images/Dd277455.w2ksc303s(ja-jp,TechNet.10).gif)
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc303(ja-jp,technet.10).gif)

#### ドメイン コントローラ セキュリティ ポリシー

ドメイン コントローラ セキュリティ ポリシーはドメイン コントローラに関するセキュリティ要件を設定して適用するために使用します。ドメイン コントローラ セキュリティ ポリシーは対象のドメイン内のすべてのドメイン コントローラに厳格に適用され、ドメイン セキュリティ ポリシーによって上書きされることはありません。

**ドメイン コントローラ セキュリティ ポリシーを開くには**

1.  管理者権限を持っているアカウントを使用して、ドメイン コントローラにログオンします。

2.  **\[スタート\]** をクリックし、**\[プログラム\]** をポイントし、**\[管理ツール\]** をポイントしてから、**\[ドメイン コントローラ セキュリティ ポリシー\]** を選択します。すると、\[ドメイン コントローラ セキュリティ ポリシー\] コンソールが開かれます。

    ![](images/Dd277455.w2ksc304s(ja-jp,TechNet.10).gif)
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc304(ja-jp,technet.10).gif)

#### 組織単位グループ ポリシー オブジェクト

このドキュメントでは組織単位グループ ポリシー オブジェクト (OU GPO) の実装については取り上げません。しかし、前に説明したポリシー インターフェイスによって実装されたセキュリティ ポリシー設定を OU GPO が上書きする可能性があることに注意する必要があります。たとえば、ドメイン用に設定されているポリシーが子 OU 用に構成された同じポリシーと矛盾する場合、そのドメイン ポリシー設定は子 OU に継承されません。代わって、子 OU 内の設定が適用されます。OU GPO を作成する際に **\[上書きなし\]** オプションを選択すると、それを避けることができます。**\[上書きなし\]** オプションは、親のポリシーが子のポリシーと矛盾し、かつ、子に **\[ポリシーを継承しない\]** が設定されている場合でも、すべての子コンテナに親のポリシーを強制的に継承させる働きをします。GPO の **\[プロパティ\]** ダイアログ ボックスの **\[オプション\]** ボタンをクリックすることにより、**\[上書きなし\]** チェック ボックスを表示させることができます。

[](#mainsection)[ページのトップへ](#mainsection)

### その他のセキュリティ構成インターフェイス

説明と実装を容易にするために、このドキュメントでは上で説明したインターフェイスである Windows 2000 セキュリティ ポリシーを通じてセキュリティの設定を管理することに焦点を当てます。しかし、他にも利用可能なツールがあります。スタンドアロンのポリシー インターフェイスを通じては対処できないセキュリティ管理オプションがあった場合には、それらのツールを取り上げることがあります。それらのツールには、標準 Windows 2000 管理インターフェイスもあれば、セキュリティ構成ツール セットもあります。後者の場合、特定のセキュリティの設定を適用するために使用できるだけではなく、確立されたポリシー要件にオペレーティング システムが適合しているかをテストするためにも使用することができます。それらの各インターフェイスの使い方の詳細については、『Windows 2000 評価された構成 管理者ガイド』を参照してください。

#### Windows エクスプローラ

特定のファイルおよびフォルダに関するアクセス許可および監査の設定を行うために、**Windows エクスプローラ**を使用することができます。共有リソースおよび共有アクセス許可も、**Windows エクスプローラ** インターフェイスを通じて設定することができます。そのようすを下に図示します。

![](images/Dd277455.w2ksc305s(ja-jp,TechNet.10).gif)
[拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc305(ja-jp,technet.10).gif)

#### レジストリ エディタ

Windows 2000 で利用可能なレジストリ エディタは 2 つあります。**Regedit.exe** と **Regedt32.exe** です。その 2 つのうちで、レジストリ キー オブジェクトに関するアクセス許可および監査の設定をサポートしているのは **Regedt32.exe** だけです。評価された構成においては、 Regedt32.exe のみを使用すべきです。

![](images/Dd277455.w2ksc306(ja-jp,TechNet.10).gif)

**警告** : レジストリ エディタの使い方を誤ると、システム全体に及ぶ深刻な問題が生じ、それを修正するためには Windows 2000 を再インストールしなければならないことがあります。レジストリ エディタの不適切な使用によって生じた問題の解決に関して、マイクロソフトは一切保証を負いません。

#### コンピュータ管理インターフェイス

**\[コンピュータの管理\]** インターフェイスはすべての Windows 2000 オペレーティング システムで利用可能です。このインターフェイスを使用すると、監査ログ、共有リソース割り当てとアクセス許可、システム サービス、さらにはユーザー アカウントおよびグループ アカウントを管理することができます。ドメイン コントローラ上においては、**\[コンピュータの管理\]** インターフェイスではなく、**\[Active Directory ユーザーとコンピュータ\]** インターフェイスを使用して、ユーザー アカウントおよびグループ アカウントを管理します。

![](images/Dd277455.w2ksc307(ja-jp,TechNet.10).gif)

#### Active Directory ユーザーとコンピュータ

**\[Active Directory ユーザーとコンピュータ\]** インターフェイスは、ドメインのユーザーおよびコンピュータをはじめとする Active Directory オブジェクトを作成して管理するために使用します。このインターフェイスはドメイン コントローラ上でのみ利用可能です。

![](images/Dd277455.w2ksc308s(ja-jp,TechNet.10).gif)
[拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc308(ja-jp,technet.10).gif)

#### Microsoft セキュリティ構成ツール セット

Microsoft セキュリティ構成ツール セットは Microsoft 管理コンソール (MMC) の一連のスナップインから構成されており、Windows 2000 オペレーティング システムのセキュリティを構成し分析できるように設計されています。セキュリティ構成ツール セットを使用すると、管理者は Windows 2000 オペレーティング システムのセキュリティを構成し、それから定期的にシステムの分析を実施して、構成の現状を維持したり、時間の経過にともなって必要となる構成の変更を実施したりすることができます。

Microsoft セキュリティ構成ツール セットの使い方に関する詳しい情報が記載されているドキュメントを次のサイトからダウンロードすることができます。<http://www.microsoft.com/japan/windows2000/remove404.mspx>.

[](#mainsection)[ページのトップへ](#mainsection)

### アカウント ポリシー

アカウント ポリシーは主要な 3 つのアカウント認証機能を制御するルールです。具体的には、パスワードの構成、アカウントのロックアウト、および Kerberos 認証を対象にします。

-   **パスワード ポリシー** : ローカル ユーザー アカウントに関して、適用や有効期間のようなパスワードの設定を決める働きをします。

-   **アカウント ロックアウト ポリシー** : ローカル ユーザー アカウントに関して、いつだれのためにアカウントをシステムからロックアウトするかを決める働きをします。

-   **Kerberos ポリシー** : Kerberos 認証は Active Directory ドメインにおいて使用される主要な認証機構です。

アカウント ポリシーはドメイン内のユーザー、組織単位、ツリーなどに適用することができます。これらのポリシーは階層構造をしています。

-   ドメイン ポリシーは Active Directory オブジェクト ポリシーに優先します。

-   組織単位ポリシーはドメイン ポリシーに優先します。

-   ルート ドメイン ポリシーはすべてのポリシーに優先します。

アカウント ポリシーの設定に関する詳細については、『Windows 2000 評価された構成 管理者ガイド』を参照してください。

#### パスワード ポリシーの設定

現在のパスワード ポリシーを表示して編集するには、以下の手順で操作を行います。

1.  対象のセキュリティ ポリシーを開きます。

2.  \[セキュリティの設定\] を展開します。

3.  \[セキュリティの設定\] の下の \[アカウント ポリシー\] を展開して、\[パスワードのポリシー\]、\[アカウント ロックアウトのポリシー\]、\[Kerberos ポリシー\] を表示させます。

4.  **\[パスワードのポリシー\]** オブジェクトをクリックします。すると、右側の詳細ペインに、構成可能な \[パスワードのポリシー\] の設定が表示されます。

    ![](images/Dd277455.w2ksc309(ja-jp,TechNet.10).gif)

5.  表 3.1 に示されている「推奨」または「必須」の指示に応じて、パスワード ポリシーを設定します。

**表 3.1 パスワード ポリシーの設定**

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >パスワード ポリシー</th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>パスワード履歴要件を設定する</em></strong>
<strong>セキュリティの目的</strong>: パスワード再利用の頻度の制限を設定します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>パスワードの有効期間を設定する</em></strong>
<strong>セキュリティの目的</strong>: ユーザーがパスワードを変更せずに使い続けられる期間を設定します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>パスワードの変更禁止期間を設定する</em></strong>
<strong>セキュリティの目的</strong>: ユーザーがパスワードを変更せずに使い続けなければならない期間を設定します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>パスワードの長さを設定する</em></strong>
<strong>セキュリティの目的:</strong> ユーザーのパスワードに必要な長さを設定します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>パスワードの複雑性要件を設定する</em></strong>
<strong>セキュリティの目的:</strong> 複雑 (強力) なパスワードを使用することを求めます。このポリシーを設定した場合、パスワード内で英数字、特殊文字、大文字、小文字を組み合わせて使用しなければなりません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>元に戻せるパスワードの暗号化を有効にしない</em></strong>
<strong>セキュリティの目的:</strong> 推奨しません。
<strong>手順:</strong> 既定の設定が無効になっていることを確認します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" />
<br />
</td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
#### アカウント ロックアウト ポリシーの設定
  
現在のアカウント ロックアウト ポリシーの設定を表示し、以下の手順に従って編集します。
  
1.  対象のセキュリティ ポリシーを開きます。
  
2.  \[セキュリティの設定\] を展開します。
  
3.  \[セキュリティの設定\] の下の \[アカウント ポリシー\] を展開して、\[パスワードのポリシー\]、\[アカウント ロックアウトのポリシー\]、\[Kerberos ポリシー\] を表示させます。
  
4.  **\[アカウント ロックアウトのポリシー\]** オブジェクトをクリックします。すると、右側の詳細ペインに、構成可能な \[アカウント ロックアウトのポリシー\] の設定が表示されます。
  
    ![](images/Dd277455.w2ksc310(ja-jp,TechNet.10).gif)
  
5.  表 3.2 に示されている「推奨」または「必須」の指示に応じて、アカウント ロックアウトのポリシーを設定します。
  
**表 3.2 アカウント ロックアウトのポリシーの設定**
  
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >アカウント ロックアウトのポリシー</th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ロックアウト期間の設定</em></strong>
<strong>セキュリティの目的:</strong> 無効なパスワードの使用が試みられたためにいったんアカウントがロックされると、この指定期間が経過 (または管理者がアカウントのロックを解除) してからでないと、リセットすることはできません。
<strong>手順:</strong>
<ol>
<li>右側の詳細ペイン内の <strong>[ロックアウト期間]</strong> ポリシー オブジェクトをダブルクリックして、対応する [セキュリティ ポリシーの設定] ダイアログ ウィンドウを開きます。</li>
<li>ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。</li>
<li><strong>[分]</strong> フィールドの数値をゼロ (0) に変更して、該当のアカウントを無期限にロックするように、このポリシーを設定することを推奨します。そうした場合、管理者がアカウントのロックを解除する必要があります。</li>
</ol>
<strong>注意</strong> : ST ではロックアウトの期間を設定する必要があります。この機能を発揮させるためには、1 以上の値を設定する必要があります。値を 0 に設定することもできます。その場合は、管理者がアカウントのロックを解除する必要があります。
ロックアウト期間ポリシーは [ロックアウト カウントのリセット] ポリシーとリンクしています。ロックアウト期間ポリシーに 0 を設定した場合は、[ロックアウト カウントのリセット] ポリシーには任意の値を指定することができます。ロックアウト期間ポリシーに 0 以外の値を設定した場合は、既定では [ロックアウト カウントのリセット] ポリシーに同じ値が自動的に設定されます。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>アカウントのロックアウトのしきい値を設定する</em></strong>
<strong>セキュリティの目的:</strong> 無効なログインの試みが何回行われたら、アカウントをロックするかを設定します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>アカウントのロックアウト リセット カウンタを設定する</em></strong>
<strong>セキュリティの目的:</strong> ログオンの試みが失敗するたびに、不正なログオンの回数を記録するしきい値が繰り上げられます。このポリシーはロックアウトしきい値を何分間維持した後にリセットするかを決定します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
#### Kerberos ポリシーの設定
  
現在の Kerberos ポリシーの設定を表示し、以下の手順に従って編集します。
  
1.  必要に応じて、ドメイン セキュリティ ポリシーまたはドメイン コントローラ セキュリティ ポリシーを開きます。
  
    **注意** : Kerberos ポリシーの設定はローカル セキュリティ ポリシー ツールを用いて行うことはできません。ドメインのメンバはドメイン セキュリティ ポリシーからこのポリシーを継承することができます。
  
2.  \[セキュリティの設定\] を展開します。
  
3.  \[セキュリティの設定\] の下の \[アカウント ポリシー\] を展開して、\[パスワードのポリシー\]、\[アカウント ロックアウトのポリシー\]、\[Kerberos ポリシー\] を表示させます。
  
4.  **\[Kerberos ポリシー\]** オブジェクトをクリックします。すると、右側の詳細ペインに、構成可能な \[Kerberos ポリシー\] の設定が表示されます。
  
    ![](images/Dd277455.w2ksc311(ja-jp,TechNet.10).gif)
  
5.  表 3.3 に示されている「推奨」または「必須」の指示に応じて、Kerberos ポリシーを設定します。
  
**表 3.3 Kerberos ポリシーの設定**
  
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Kerberos ポリシー</th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ユーザー ログオンの制限を強制する</em></strong>
<strong>セキュリティの目的:</strong> すべてのログオン要求をユーザー権利のポリシーに照らしてチェックし、ユーザーがローカルにログオンまたはネットワークを通じてコンピュータにアクセスする許可を有しているかどうか判定します。
<strong>手順:</strong> 既定の設定が適切です。設定が「有効」であることを確認します。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>サービス チケットの最長有効期間を設定する</em></strong>
<strong>セキュリティの目的:</strong> サービス チケットが有効な最長の期間を設定します。
<strong>手順:</strong> 既定の設定が適切です。サービス チケットの有効期限が「600 分」に設定されていることを確認します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>チケットの最長有効期間を設定する</em></strong>
<strong>セキュリティの目的:</strong> ユーザー チケットが有効な最長の期間を設定します。
<strong>手順:</strong> 既定の設定が適切です。ユーザー チケットの有効期限が「10 時間」に設定されていることを確認します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ユーザー チケットを更新できる最長有効期間を設定する</em></strong>
<strong>セキュリティの目的:</strong> 有効期限が切れたユーザー チケットを更新できる期間を設定します。
<strong>手順:</strong> 既定の設定が適切です。ユーザー チケットを更新できる期間が「7 日」であることを確認します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>コンピュータの時計の同期の最長トレランスを設定する</em></strong>
<strong>セキュリティの目的:</strong> ドメイン内のコンピュータ間の同期の最長のトレランスを設定します。
<strong>手順:</strong> 既定の設定が適切です。最長トレランスが「5 分」に設定されていることを確認します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### ローカル ポリシー
  
ローカル ポリシーはユーザー アカウントまたはサービス アカウントのセキュリティ オプションを決定するものです。ローカル ポリシーはユーザーがログインしたコンピュータおよびユーザーがそのコンピュータに関して有している権利に基づいています。ローカル ポリシーを用いて、以下の事項を構成することができます。
  
-   **監査ポリシー** : どのセキュリティ イベント (成功、失敗、またはその両方) をコンピュータ上のセキュリティ ログに記録するかを決定します。セキュリティ ログはイベント ビューアの一部です。
  
-   **ユーザー権利の割り当て** : どのユーザーまたはグループにコンピュータにログオンまたはコンピュータ上でタスクを行う特権を持たせるかを決定します。
  
-   **セキュリティ オプション** : データへのデジタル署名、Administrator アカウントおよび Guest アカウントの名前、フロッピー ディスクおよび CD-ROM へのアクセス、ドライバのインストール、ログオン プロンプトなどの、コンピュータに関するセキュリティの設定を有効または無効にします。
  
    **注意** : ローカル ポリシーは定義上 1 台のコンピュータにのみ適用されます。しかし、ローカル ポリシーの設定を Active Directory 内のグループ ポリシー オブジェクトにインポートすると、そのグループ ポリシー オブジェクトが適用される任意のコンピュータ アカウントのローカル セキュリティの設定に影響が及びます。したがって、セキュリティ ポリシーの優先順位に注意することが重要です。グループ ポリシー (組織単位) に関連するセキュリティ ポリシーはローカル レベルで設定されたポリシーに優先します。ドメイン用のポリシーはローカルに定義されたポリシーに優先します。どちらの場合も、ユーザー アカウントの権利を上書きするローカル ポリシーが設定されていると、それらの権利は効力を発揮しません。このことは重要です。その理由は、Microsoft Windows 2000 の動作には Microsoft Windows NT の動作とは大きく異なる点があるからです。たとえば、(既定どおりに) ドメインのグループ ポリシーとして構成されたパスワード ポリシーがあると、それはそのドメイン内のすべてのコンピュータに影響を及ぼします。そのドメイン内の (個々のワークステーション上の) ローカル アカウント データベースのパスワード ポリシーはドメイン自体のパスワード ポリシーと同じになります。
  
#### イベント監査の設定
  
セキュリティに関連するイベントを監査できるようにします。
  
1.  対象のセキュリティ ポリシーを開きます。
  
2.  \[セキュリティの設定\] を展開します。
  
3.  \[セキュリティの設定\] の下の \[ローカル ポリシー\] を展開して、\[監査ポリシー\]、\[ユーザー権利の割り当て\]、\[セキュリティ オプション\] を表示させます。
  
4.  **\[監査ポリシー\]** オブジェクトをクリックします。すると、右側の詳細ペインに、構成可能な \[監査ポリシー\] の設定が表示されます。
  
    ![](images/Dd277455.w2ksc312s(ja-jp,TechNet.10).gif)  
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc312(ja-jp,technet.10).gif)
  
5.  セキュリティ イベントの監査を設定するには、右側の詳細ペイン内の対象の監査ポリシーをダブルクリックして、\[セキュリティ ポリシーの設定\] ダイアログ ウィンドウを開きます。
  
6.  ドメインレベルのポリシーに関して、**\[このポリシーの設定を定義する\]** チェック ボックスをオンにします。また、イベントの \[成功\] と \[失敗\] のチェック ボックスをオンにします。そのようすを下に図示します。
  
    ![](images/Dd277455.w2ksc313(ja-jp,TechNet.10).gif)
  
7.  監査イベントのカテゴリを表 3.4 に定義するように設定するには、これらの手順に従います。
  
**表 3.4 監査ポリシーの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >監査ポリシー</th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
<th style="border:1px solid black;" > </th>
<th style="border:1px solid black;" > </th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">監査イベントのカテゴリ</td>
<td style="border:1px solid black;">成功</td>
<td style="border:1px solid black;">失敗</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>アカウント ログオン イベントの監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>アカウント管理の監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ディレクトリ サービスのアクセスの監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ログオン イベントの監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>オブジェクト アクセスの監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ポリシーの変更の監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>特権使用の監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>プロセス追跡の監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>システム イベントの監査</em></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
</tbody>
</table>
 

**注意** :

1.  評価された構成には特定の監査情報を提供する機能が含まれなければなりません。しかし、監査情報が生成される必要はありません。

2.  **\[オブジェクト アクセスの監査\]** ポリシーを設定すると、オブジェクトを監査することが可能になるだけです。オブジェクト アクセス監査イベントを収集するためには、アクセスの試みをログに記録する対象の個々のオブジェクトに関して、監査 SACL を設定する必要があります。**\[ディレクトリ サービスのアクセスの監査\]** ポリシーを設定する場合も同様です。

3.  付録B 「監査カテゴリとイベント」に、Windows 2000 の監査イベント、適用される ST 要件、および推奨する監査の設定のマトリックスを提示します。

4.  「アカウント ログオン イベント」は、ドメインのように、アカウントが置かれている場所で生成されます。「ログオン イベント」はログオンの試みがなされた場所で生成されます。

#### ログオン権利およびログオン特権の修正

ユーザー アカウントおよびサービスに関するログオン権利およびログオン特権を修正します。

1.  対象のセキュリティ ポリシーを開きます。

2.  \[セキュリティの設定\] を展開します。

3.  \[セキュリティの設定\] の下の \[ローカル ポリシー\] を展開して、\[監査ポリシー\]、\[ユーザー権利の割り当て\]、\[セキュリティ オプション\] を表示させます。

4.  **\[ユーザー権利の割り当て\]** オブジェクトをクリックします。すると、右側の詳細ペインに、構成可能なユーザー権利ポリシーの設定が表示されます。

    ![](images/Dd277455.w2ksc314s(ja-jp,TechNet.10).gif)
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc314(ja-jp,technet.10).gif)

5.  ログオン権利およびログオン特権を設定するには、右側の詳細ペイン内の対象のポリシーをダブルクリックします。すると、\[セキュリティ ポリシーの設定\] ダイアログ ウィンドウが開かれます。

6.  ドメインレベルのポリシーに関して、**\[このポリシーの設定を定義する\]** チェック ボックスをオンにします。

7.  アカウントのログオン権利またはログオン特権を削除するには、アカウント名をクリックしてハイライトさせ、それから **\[削除\]** ボタンをクリックします。

8.  アカウントにログオン権利またはログオン特権を追加するには、**\[追加\]** ボタンをクリックし、それから対象のアカウントの適切なアカウント ディレクトリを参照します。

9.  評価された構成を維持するためには、ユーザーの権利と特権の既定の割り当ての中で、管理者が変更しなければならないものがいくつかあります (表 3.5 の「推奨」および「必須」の列を参照)。

**注意** : ドメイン コントローラには Power Users アカウントは存在しません。したがって、Power Users グループのユーザー権利と特権に影響を与える修正をドメイン コントローラから手作業で実施することはできません。また、ドメイン コントローラには Power Users グループは存在しないにもかかわらず、ドメイン コントローラのローカル ポリシーには Power Users グループへの参照が依然として残っている可能性があることにも注意してください。コンピュータをサーバーからドメイン コントローラに変更した後でも、この参照は残ります。

**表 3.5 ユーザー権利と特権**

 
<table style="border:1px solid black;">
<colgroup>
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >ユーザー権利と特権の割り当て</th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
<th style="border:1px solid black;" > </th>
<th style="border:1px solid black;" > </th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">ログオン権利</td>
<td style="border:1px solid black;">既定値</td>
<td style="border:1px solid black;">修正後</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ネットワーク経由でコンピュータへアクセス</em></strong>
<strong><em>(Professional/Server)</em></strong></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users</td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ネットワーク経由でコンピュータへアクセス</em></strong>
<strong><em>(ドメイン コントローラ)</em></strong></td>
<td style="border:1px solid black;">Administrators
Authenticated Users</td>
<td style="border:1px solid black;">AdministratorsAuthenticated Users</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ローカル ログオン</em></strong>
<strong><em>(Professional)</em></strong></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users
コンピュータ名\Guest</td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ローカル ログオン</em></strong>
<strong><em>(Server)</em></strong></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users
コンピュータ名\Guest
コンピュータ名\TsInternetUser</td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ローカル ログオン</em></strong>
<strong><em>(ドメイン コントローラ)</em></strong></td>
<td style="border:1px solid black;">Administrators
Account Operators
Backup Operators
Print Operators
Server Operators</td>
<td style="border:1px solid black;">Administrators
Account Operators
Backup Operators
Print Operators
Server Operators</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">特権</td>
<td style="border:1px solid black;">既定値</td>
<td style="border:1px solid black;">修正後</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ドメインにワークステーションを追加</em></strong>
<strong><em>(ドメイン コントローラ)</em></strong></td>
<td style="border:1px solid black;">　</td>
<td style="border:1px solid black;">Authenticated Users のアカウントを削除します。この特権を他のユーザーに与えてはなりません。
<strong>注意</strong> Domain Administrators は既定でこの特権を保持しています。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>クォータの増加</em></strong>
<strong><em>(ドメイン コントローラ – ドメイン セキュリティ ポリシー内)</em></strong></td>
<td style="border:1px solid black;">(未定義)</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>スケジューリング優先順位の繰り上げ</em></strong>
<strong><em>(ドメイン コントローラ – ドメイン セキュリティ ポリシー内)</em></strong></td>
<td style="border:1px solid black;">(未定義)</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>デバイス ドライバのロードとアンロード</em></strong>
<strong><em>(ドメイン コントローラ – ドメイン セキュリティ ポリシー内)</em></strong></td>
<td style="border:1px solid black;">(未定義)</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>監査とセキュリティ ログの管理</em></strong>
<strong><em>(ドメイン コントローラ – ドメイン セキュリティ ポリシー内)</em></strong></td>
<td style="border:1px solid black;">(未定義)</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ファームウェア環境値の修正</em></strong>
<strong><em>(ドメイン コントローラ – ドメイン セキュリティ ポリシー内)</em></strong></td>
<td style="border:1px solid black;">(未定義)</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>システム パフォーマンスのプロファイル</em></strong>
<strong><em>(ドメイン コントローラ – ドメイン セキュリティ ポリシー内)</em></strong></td>
<td style="border:1px solid black;">(未定義)</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>システムのシャットダウン</em></strong>
<strong><em>(Professional)</em></strong></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users</td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ファイルとその他のオブジェクトの所有権の取得</em></strong>
<strong><em>(ドメイン コントローラ – ドメイン セキュリティ ポリシー内)</em></strong></td>
<td style="border:1px solid black;">(未定義)</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
**注意** : 付録 C 「ユーザー権利と特権」に、Windows 2000 のユーザー権利と特権、適用される ST 要件、および推奨/必須の修正のマトリックスを提示します。
  
#### セキュリティ オプションの修正
  
あらかじめ定義されているセキュリティ関連のレジストリの設定を修正します。
  
1.  対象のセキュリティ ポリシーを開きます。
  
2.  \[セキュリティの設定\] を展開します。
  
3.  \[セキュリティの設定\] の下の \[ローカル ポリシー\] を展開して、\[監査ポリシー\]、\[ユーザー権利の割り当て\]、\[セキュリティ オプション\] を表示させます。
  
4.  **\[セキュリティ オプション\]** オブジェクトをクリックします。すると、右側の詳細ペインに、構成可能な \[セキュリティ オプション\] が表示されます。
  
    ![](images/Dd277455.w2ksc315s(ja-jp,TechNet.10).gif)  
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc315(ja-jp,technet.10).gif)
  
5.  セキュリティ オプションを設定するには、右側の詳細ペイン内の対象のポリシーをダブルクリックます。すると、\[セキュリティ ポリシーの設定\] ダイアログ ウィンドウが開かれます。
  
6.  ドメインレベルのポリシーに関して、**\[このポリシーの設定を定義する\]** チェック ボックスをオンにします。
  
7.  選択したセキュリティ オプションに関する **\[セキュリティ ポリシーの設定\]** ダイアログ ボックスへの入力方法は、対象のオブジェクトの構成要件に応じて異なります。たとえば、ドロップダウン メニューから選択する必要があるセキュリティ オプションもあれば、テキストを入力する必要があるセキュリティ オプションもあります。そのようすを下に図示します。
  
    ![](images/Dd277455.w2ksc316(ja-jp,TechNet.10).gif)
  
    ![](images/Dd277455.w2ksc317(ja-jp,TechNet.10).gif)
  
8.  表 3.6 に示すように、セキュリティ オプションを修正します。
  
**表 3.6 セキュリティ オプションの設定**
  
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティ オプション</th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>匿名接続の追加を制限する</em></strong>
<strong>セキュリティの目的:</strong> 匿名ユーザーが SAM アカウントおよび共有を列挙できないようにします。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>サーバー オペレータがタスクのスケジュールを割り当てるのを許可する (ドメイン コントローラのみ)</em></strong>
<strong>セキュリティの目的:</strong> Server Operators が AT スケジュール機能を用いてジョブを作成することを許すかどうかを決定します。既定では、AT スケジュール機能を用いてジョブを作成することができるのは、管理者だけです。このセキュリティ ポリシーの設定を有効にすると、Administrators としてのアクセス許可を与えずに、Server Operators グループのメンバが AT スケジュール機能を用いてドメイン コントローラ上のジョブを作成できるようになります。
<strong>手順:</strong> この機能を有効にしてはいけません。AT スケジュール機能は評価された構成の一部ではありません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ログオン抜きのシャットダウンを無効にする</em></strong>
<strong>セキュリティの目的:</strong> 先にシステムの認証を受けないでコンピュータをシャットダウンできないようにします。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>リムーバブル NTFS メディアの取り出しを制限する</em></strong>
<strong>セキュリティの目的:</strong> 権限のある管理者にのみ、コンピュータからメディアを取り出すことを許可することにより、リムーバブル メディアに収められているデータに関する ACL 設定の整合性を保証します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>セッションを切断する前に、ある一定のアイドル時間を必要とする</em></strong>
<strong>セキュリティの目的:</strong> サーバー メッセージ ブロック (SMB) セッションにおいて、アイドル状態が何分間続いたらセッションを切断するかを決定します。管理者はこのポリシーを使用して、非アクティブな SMB セッションをいつ切断するかを制御することができます。クライアントのアクティビティが再開された場合には、セッションは自動的に再確立されます。ローカル コンピュータ ポリシーには、サーバーに関するこのポリシーの既定値は 15 分と定義されています。ワークステーションにはこのポリシーは定義されていません。このポリシーの値が 0 に設定されている場合、アイドルなセッションを、合理的に可能な限り、早急に切断することを意味します。
<strong>手順:</strong> 既定の設定のままにしておきます。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>グローバル システム オブジェクトへのアクセスを監査する</em></strong>
<strong>セキュリティの目的:</strong> グローバル システム オブジェクトへのアクセスを監査できるようにします。このポリシーを有効にすると、ミューテックス、イベント、セマフォ、および DOS デバイスのようなシステム オブジェクトが既定のシステム アクセス制御リスト (SACL) と共に作成されます。オブジェクト アクセスの監査に関する監査ポリシーも有効に設定されていると、これらのシステム オブジェクトへのアクセスが監査されます。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>バックアップと復元の特権の使用を監査する</em>セキュリティの目的: [ファイルとディレクトリのバックアップ]</strong>または <strong>[ファイルとディレクトリの復元]</strong> の特権が使用されるたびに、監査イベントを記録できるようにします。既定では、バックアップと復元の特権の使用は監査の対象外です。<strong>[特権使用の監査]</strong>に関する監査ポリシーが有効であり、このセキュリティ オプションも設定されている場合に、バックアップと復元の特権の使用が監査されます。<strong>手順:</strong>
<ol>
<li>右側の詳細ペイン内の <strong>[バックアップと復元の特権の使用を監査する]</strong> をダブルクリックします。</li>
<li>ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。</li>
<li><strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。</li>
</ol>
<strong>注意</strong> : 評価された構成においては、これらのオブジェクトは監査可能でなければなりません。しかし、監査を実施することを強制はされません。これらのオブジェクトを監査するためには、管理者がこのオプションを設定する必要があります。この設定を行うと、大量の監査情報が生成されます。したがって、監査ログを定期的にレビュー、アーカイブ、およびクリアする厳格な監査管理プロセスが用意されている場合にのみ、このオプションを有効にすべきです。ログに記録するイベント数の増大に備えて、最大ログ サイズも編集すべきです。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ログオン時間を経過した場合は自動的にユーザーをログオフする</em></strong>
<strong>セキュリティの目的:</strong> ユーザーが許可されている時間以上にログオンしたままでいるときに、そのユーザーをネットワークから強制的にログオフさせます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ログオン時間が時間切れになった場合、自動的にユーザーをログオフする (ローカル)</em></strong>
<strong>セキュリティの目的:</strong> ユーザーが許されている時間以上にログオンしたままでいるときに、そのユーザーをローカル コンピュータから強制的にログオフさせます。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[</strong><em>ログオン時間が時間切れになった場合、自動的にユーザーをログオフする (ローカル)</em>] をダブルクリックします。
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
<strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>システムのシャットダウン時に仮想メモリのページ ファイルをクリアする</em></strong>
<strong>セキュリティの目的:</strong> システムがシャットダウンされたときに、仮想メモリのページ ファイルを削除します。ユーザーが次回にログインするときに、ページファイルは再初期化されます。この目的は、ページファイル内に残っている情報が、次のユーザーがコンピュータにログオンしたときに利用できないようにすることです。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>常にクライアント側の通信にデジタル署名を行う</em></strong>
<strong>セキュリティの目的:</strong> クライアント側の通信に常にデジタル署名を行うかどうかを決定します。Windows 2000 のサーバー メッセージ ブロック (SMB) 認証プロトコルでは、相互認証およびメッセージ認証をサポートしています。前者は「man-in-the-middle」攻撃を排除し、後者はアクティブ メッセージ攻撃を防止する働きをします。各 SMB にデジタル署名を付し、それをクライアントとサーバーの両方で検証することにより、この認証が行われます。
このオプションを有効にすると、Windows 2000 SMB クライアントは SMB パケットに署名する必要があります。このオプションを無効にした場合は、SMB クライアントがパケットに署名する必要はありません。このポリシーは既定では無効にされています。評価された構成に関しては、このポリシー オプションを無効にし、次のセキュリティ オプションの <strong>[可能な場合、クライアントの通信にデジタル署名を行う]</strong> を有効にすることができます。評価された構成の運用環境は同じ要件に合わせてすべてのコンピュータが構成されている閉じたネットワークです。したがって、通信には SMB 署名が用いられます (下の注意を参照してください)。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>可能な場合、クライアントの通信にデジタル署名を行う</em></strong>
<strong>セキュリティの目的:</strong> このポリシーを有効にすると、SMB パケット署名を行うことが有効または必要となっている SMB サーバーと通信するときに、Windows 2000 のサーバー メッセージ ブロック (SMB) クライアントは SMB パケット署名を行います。詳細については、「常にクライアント側の通信にデジタル署名を行う」を参照してください。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>常にサーバーの通信にデジタル署名を行う</em></strong>
<strong>セキュリティの目的:</strong> このポリシーを有効にすると、Windows 2000 のサーバー メッセージ ブロック (SMB) サーバーは SMB パケットに署名する必要があります。このポリシーは既定では無効にされています。詳細については、「常にクライアント側の通信にデジタル署名を行う」を参照してください。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>可能な場合、サーバーの通信にデジタル署名を行う</em></strong>
<strong>セキュリティの目的:</strong> このポリシーを有効にすると、Windows 2000 のサーバー メッセージ ブロック (SMB) サーバーは SMB パケットに署名する必要があります。ローカル コンピュータ ポリシーにおいては、ワークステーションおよびサーバー プラットフォームに関しては、このポリシーは既定では無効にされています。ドメイン コントローラに関しては、このポリシーは既定では有効にされています。詳細については、「常にクライアント側の通信にデジタル署名を行う」を参照してください。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ログオンに Ctrl+Alt+Del を必要としない</em></strong>
<strong>セキュリティの目的: このオプションを有効にしてはいけません。</strong>このオプションを有効にすると、信頼されたパスの仕組みが無効になります。信頼されたパスの仕組みの目的は、ユーザーのログイン セッションがスプーフィングされることを防止することにあります。Windows 2000 コンピュータ上ではこのオプションは既定では無効に設定されています。ただし、ポリシー ツールの中には未定義と表示するもがあります。
<strong>手順:</strong> 右側の詳細ペイン内の <strong>[ログオンに Ctrl+Alt+Del を必要としない]</strong>オプションが<strong>未定義または無効に設定</strong>されていることを確認します。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ログオン画面に最後のユーザー名を表示しない</em></strong>
<strong>セキュリティの目的:</strong> 既定では、コンピュータに前回ログオンしたユーザーのユーザー ID が Windows 2000 のログイン インターフェイス画面に表示されます。このオプションを有効にすると、ログイン セッションにおいて、前回ログインしたユーザーの名前が削除されます。その結果、ローカルでコンピュータに入りこもうとする侵入者は、パスワードだけではなく正しいユーザー ID も推測しなければならなくなります。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>LAN Manager 認証レベル</em></strong>
<strong>セキュリティの目的:</strong> このセキュリティ オプションはWindows のチャレンジ/レスポンス認証レベルを設定するために使用します。このセキュリティ オプションにより、ネットワーク ログオンに使用するチャレンジ/レスポンス認証プロトコルが決まります。この選択により、クライアントによって使用される認証プロトコルのレベル、ネゴシエートされるセッションのセキュリティのレベル、および以下の各選択オプションで受け入れられる認証のレベルが影響を受けます。
<ul>
<li><strong>LM NTLM 応答の送信</strong>: クライアントは LM および NTLM 認証を使用します。NTLMv2 セッション セキュリティを使用することはありません。DC は LM、NTLM、および NTLMv2 認証を受け付けます。</li>
<li><strong>ネゴシエートされた場合 LM NTLM を送信 - NTLMv2 セッション セキュリティを使用する</strong>: クライアントは LM および NTLM 認証を使用し、サーバーでサポートされている場合に NTLMv2 セッション セキュリティを使用します。DC は LM、NTLM、および NTLMv2 認証を受け付けます。</li>
<li><strong>NTLM 応答のみ送信する</strong>: クライアントは NTLM 認証のみを使用し、サーバーでサポートされている場合に NTLMv2 セッション セキュリティを使用します。DC は LM、NTLM、および NTLMv2 認証を受け付けます。</li>
<li><strong>NTLMv2 応答のみ送信する</strong>: クライアントは NTLMv2 認証のみを使用し、サーバーでサポートされている場合に NTLMv2 セッション セキュリティを使用します。DC は LM、NTLM、および NTLMv2 認証を受け付けます。</li>
<li><strong>NTLMv2 応答のみ送信\\LM を拒否する</strong>: クライアントは NTLMv2 認証のみを使用し、サーバーでサポートされている場合に NTLMv2 セッション セキュリティを使用します。DC は LM を拒否します (NTLM および NTLMv2 認証のみを受け付けます)。</li>
<li><strong>NTLMv2 応答のみ送信\\LM と NTLM を拒否する</strong>: クライアントは NTLMv2 認証のみを使用し、サーバーでサポートされている場合に NTLMv2 セッション セキュリティを使用します。DC は LM および NTLM を拒否します (NTLMv2 認証のみを受け付けます)。</li>
</ul>
サーバーの既定の設定は <strong>LM NTLM 応答の送信</strong>です。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>ログオン画面に警告を表示する</em></strong>
<strong>セキュリティの目的:</strong> タイトルと警告の付いたログオン見出しを表示するように、対話型のログオン画面を構成します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ログオン情報をキャッシュ化しない</em></strong>
<strong>セキュリティの目的:</strong> Windows 2000 にはログオン情報をキャッシュ化する機能が備わっています。ログオン時にドメイン コントローラが見つからず、ユーザーが過去にシステムにログオンしたことがある場合、それらの資格情報を使用してログオンすることができます。CachedLogonsCount レジストリ値は、Windows 2000 によって何件のユーザー アカウント エントリがローカル コンピュータのログオン キャッシュに保存されるかを示します。このエントリの値が 0 である場合、ユーザー アカウントに関するデータはログオン キャッシュに保存されません。その場合、ドメイン コントローラが利用できず、ユーザーのアカウント情報が保存されていないコンピュータにユーザーがログオンしようとすると、次のメッセージが表示されます。
<strong>ログオンできません。ログオン先ドメイン ＜ドメイン名＞ は利用できません。</strong>
Administrator がユーザーのドメイン アカウントを無効にしても、ネット ケーブルを外すことにより、ユーザーは依然としてキャッシュを使用してログオンすることができます。これを防止するために、管理者はログオン情報のキャッシュ化を無効にすべきです。そうすると、ログオンにかかる時間が少し長くなりますが、ハッカーがキャッシュ メモリからログオン情報を盗用することを防止することができます。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>コンピュータ アカウント パスワードのシステム保守をしない</em></strong>
<strong>セキュリティの目的:</strong> コンピュータ アカウント パスワードを毎週リセットするか否かを決定します。Windows 2000 のセキュリティの一環として、<strong><em>コンピュータ アカウント</em></strong> パスワードは 7 日ごとに自動的に変更されます。このポリシーを有効にすると、パスワードが毎週変更されることはなくなります。このポリシーを無効にすると、コンピュータ アカウントの新しいパスワードが毎週生成されます。既定ではこのポリシーは無効に設定されています。
<strong>手順:</strong> このポリシーを有効にしてはなりません。ローカルポリシーは<strong>無効</strong>、ドメイン ポリシーは<strong>無効</strong>に設定されているかまたは<strong>未定義</strong>であることを確認します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>ユーザーがプリンタ ドライバをインストールできないようにする</em></strong>
<strong>セキュリティの目的:</strong> Users グループのメンバがプリンタ ドライバをインストールできないようにするどうかを決定します。このポリシーを有効にすると、ユーザーがローカル コンピュータにプリンタ ドライバをインストールすることはできなくなります。したがって、ローカル コンピュータ上にデバイス ドライバが存在しないときに、ユーザーが「プリンタを追加」することはできません。このポリシーを無効にすると、Users グループのメンバがコンピュータ上にプリンタ ドライバをインストールすることができます。既定では、この設定はサーバー上では有効に、ワークステーション上では無効になっています。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>パスワードが無効になる前にユーザーに変更を促す</em></strong>
<strong>セキュリティの目的:</strong> ユーザーのパスワードの有効期限が切れる何日前にユーザーに警告するかを決定します。ユーザーに予告することにより、ユーザーは余裕を持って十分強力なパスワードを考案することができます。既定では、この値は 14 日に設定されています。
<strong>手順:</strong> なし。既定の設定は適切です。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>回復コンソール:</em></strong> <strong><em>自動管理ログオンを許可する</em></strong>
<strong>セキュリティの目的:</strong> 回復コンソールの既定の設定では、システムにアクセスするためには、Administrator アカウントのパスワードを入力する必要があります。このオプションを有効にすると、回復コンソールはパスワードを必要とせずに、自動的にシステムにログオンします。既定では、このオプションは無効に設定されています。ただし、ポリシー ツールの中にはこのオプションを未定義と表示するもがあります。
<strong>手順:</strong> このオプションを有効にしてはいけません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>回復コンソール:</em></strong> <strong><em>すべてのドライブとフォルダに、フロッピーのコピーとアクセスを許可する</em></strong>
<strong>セキュリティの目的:</strong> このオプションを有効にすると、回復コンソールの SET コマンドを使用できるようになります。すると、回復コンソールの以下の環境変数を設定することが可能になります。
<ul>
<li><strong>AllowWildCards</strong> - 一部のコマンド (たとえば、DEL コマンド) にワイルドカードを使用できるようになります。</li>
<li><strong>AllowAllPaths</strong> - コンピュータ上のすべてのファイルおよびフォルダにアクセスできるようになります。</li>
<li><strong>AllowRemovableMedia</strong> - フロッピー ディスクのようなリムーバブル メディアにファイルをコピーできるようになります。</li>
<li><strong>NoCopyPrompt</strong> - 既存のファイルに上書きするときに、確認のメッセージが表示されなくなります。</li>
</ul>
既定の設定では SET コマンドは無効であり、上記の環境変数はすべて無効になっています。ただし、ポリシー ツールの中にはこのオプションを未定義と表示するもがあります。
<strong>手順:</strong> このオプションを有効にしてはいけません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Administrator アカウント名の変更</em></strong>
<strong>セキュリティの目的:</strong> Administrator アカウントのセキュリティ識別子 (SID) に関連する名前を変更するために使用します。この変更を行うと、ハッカーにパスワードだけではなく Administrator アカウントに関連したユーザー ID も推測させることになり、 Administrator アカウントが盗用される機会を減らすことができます。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[Administrator アカウント名の変更]</strong> をダブルクリックします。
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
テキスト ボックスに Administrator アカウントの新しい名前を入力し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Guest アカウント名の変更</em></strong>
<strong>セキュリティの目的:</strong> Guest アカウントのセキュリティ識別子 (SID) に関連する名前を変更するために使用します。この変更を行うと、ハッカーにパスワードだけではなく Guest アカウントに関連したユーザー ID も推測させることになり、匿名で Guest アカウントが盗用される機会を減らすことができます。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[Guest アカウント名の変更]</strong> をダブルクリックします。
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
テキスト ボックスに Guest アカウントの新しい名前を入力し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する</em></strong>
<strong>セキュリティの目的:</strong> ローカル ユーザーとリモート ユーザーの両方に同時に CD-ROM へのアクセスを許可するかどうかを決定します。このポリシーを有効にすると、対話型でログオンしたユーザーだけがリムーバブル CD-ROM メディアにアクセスできるようになります。このポリシーを無効にすると、ローカル ユーザーとリモート ユーザーが同時に CD-ROM にアクセスできるようになります。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する]</strong> をダブルクリックします
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします
<strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>フロッピーへのアクセスを、ローカル ログオン ユーザーだけに制限する</em></strong>
<strong>セキュリティの目的:</strong> ローカル ユーザーとリモート ユーザーの両方に同時にリムーバブル フロッピー メディアへのアクセスを許すかどうかを決定します。このオプションを有効にすると、対話型でログオンしたユーザーだけがリムーバブル フロッピー メディアにアクセスできるようになります。対話型でログオンしたユーザーがだれもいない場合は、ネットワークを通じてフロッピー メディアを共有することができます。このオプションを無効にすると、ローカル ユーザーとリモート ユーザーが同時にフロッピー メディアにアクセスできるようになります。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[フロッピーへのアクセスを、ローカル ログオン ユーザーだけに制限する]</strong> をダブルクリックします
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
<strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>セキュリティで保護されたチャネル: 常にセキュリティ チャネルのデータをデジタル的に暗号化または署名する</em></strong>
<strong>セキュリティの目的:</strong> セキュリティで保護されたチャネル データを常にデジタル的に暗号化または署名するかどうかを決定します。Windows 2000 システムをドメインに加えたときに、コンピュータ アカウントが作成されます。その後で、Windows 2000 システムを起動すると、コンピュータ アカウントのパスワードを使用して、属するドメインのドメイン コントローラとの間にセキュリティで保護されたチャネルが作成されます。セキュリティで保護されたチャネルを通じて送られる要求は認証され、パスワードのような機密情報は暗号化されます。しかし、チャネルの整合性はチェックされず、すべての情報が暗号化されるとは限りません。このポリシーを有効にすると、セキュリティで保護されたチャネルを通じ発信されるすべてのトラフィックは署名または暗号化されなければなりません。このポリシーを無効にすると、署名および暗号化についてドメイン コントローラとネゴシエートされます。既定では、このポリシーは無効に設定されています。
<strong>手順:</strong> 既定の設定を変更してはいけません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>セキュリティで保護されたチャネル: 可能な場合、セキュリティ チャネルのデータをデジタル的に暗号化または署名する</em></strong>
<strong>セキュリティの目的:</strong> セキュリティで保護されたチャネル データを常にデジタル的に暗号化または署名するかどうかを決定します。Windows 2000 システムをドメインに加えたときに、コンピュータ アカウントが作成されます。その後で、Windows 2000 システムを起動すると、コンピュータ アカウントのパスワードを使用して、属するドメインのドメイン コントローラとの間にセキュリティで保護されたチャネルが作成されます。セキュリティで保護されたチャネルを通じて送られる要求は認証され、パスワードのような機密情報は暗号化されます。しかし、チャネルの整合性はチェックされず、すべての情報が暗号化されるとは限りません。このポリシーを有効にすると、セキュリティで保護されたチャネルを通じて発信されるすべてのトラフィックは暗号化されなければなりません。このポリシーを無効にすると、セキュリティで保護されたチャネルを通じて発信されるトラフィックは暗号化されません。既定では、このオプションは有効に設定されています。
<strong>手順:</strong> 既定の設定を変更してはいけません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>セキュリティで保護されたチャネル: 可能な場合、セキュリティ チャネルのデータをデジタル的に署名する</em></strong>
<strong>セキュリティの目的:</strong> セキュリティで保護されたチャネル データを常にデジタル的に暗号化または署名するかどうかを決定します。Windows 2000 システムをドメインに加えたときに、コンピュータ アカウントが作成されます。その後で、Windows 2000 システムを起動すると、コンピュータ アカウントのパスワードを使用して、属するドメインのドメイン コントローラとの間にセキュリティで保護されたチャネルが作成されます。セキュリティで保護されたチャネルを通じて送られる要求は認証され、パスワードのような機密情報は暗号化されます。しかし、チャネルの整合性はチェックされず、すべての情報が暗号化されるとは限りません。このポリシーを有効にすると、セキュリティで保護されたチャネルを通じて発信されるすべてのトラフィックは署名されなければなりません。このポリシーを無効にすると、セキュリティで保護されたチャネルを通じて発信されるトラフィックは署名されません。既定では、このオプションは有効に設定されています。
<strong>手順:</strong> 既定の設定を変更してはいけません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>セキュリティで保護されたチャネル: 強力な (Windows 2000 かそれ以降のバージョン) セッション キーを必要とする</em></strong>
<strong>セキュリティの目的:</strong> このポリシーを有効にすると、セキュリティで保護されたチャネルを通じて発信されるすべてのトラフィックは強力な (Windows 2000 かそれ以降のバージョン) 暗号化キーを必要とします。このポリシーを無効にすると、キーの強度についてドメイン コントローラとネゴシエートされます。このオプションを有効にするのは、信頼される側のすべてのドメイン内のすべてのドメイン コントローラで強力なキーがサポートされている場合のみとすべきです。既定では、このポリシーは無効に設定されています。
<strong>手順:</strong> 既定の設定を変更してはいけません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>サード パーティ製の SMB サーバーへ接続するためのパスワードを、暗号化しないで送信する</em></strong>
<strong>セキュリティの目的:</strong> このポリシーを有効にすると、サーバー メッセージ ブロック (SMB) リダイレクタは、認証中にパスワードを暗号化することがサポートされていない非マイクロソフト SMB サーバーにクリアテキストのパスワードを送信できるようになります。既定では、このポリシーは無効に設定されています。
<strong>手順:</strong> 既定の設定を変更してはいけません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>セキュリティ監査のログを記録できない場合は直ちにシステムをシャットダウンする</em></strong>
<strong>セキュリティの目的:</strong> セキュリティ イベントのログを記録できない場合に、システムを直ちにシャットダウンするかどうかを決定します。このポリシーを有効にすると、何らかの理由でセキュリティ監査のログを記録できない場合、システムは停止されます。通常、イベントのログを記録できないのは、セキュリティ監査ログがいっぱいになり、指定されているセキュリティ ログの保存方法が <strong>[イベントを上書きしない]</strong> または <strong>[指定した日数を過ぎたら上書きする]</strong> のどちらかである場合です。セキュリティ ログがいっぱいになり、既存のエントリを上書きすることができず、このセキュリティ オプションが有効であると、次のブルー スクリーンのエラーが表示されます。
<strong>STOP: C0000244 {Audit Failed}</strong>
<strong>An attempt to generate a security audit failed.</strong>
回復するためには、管理者がログオンし、必要があればログのアーカイブを取り、ログをクリアし、このオプションを適切にリセットする必要があります。既定では、このポリシーは無効に設定されています。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[セキュリティ監査のログを記録できない場合は直ちにシステムをシャットダウンする]</strong> をダブルクリックします。
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
<strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>スマート カード取り出し時の動作</em></strong>
<strong>セキュリティの目的:</strong> ログオンしたユーザーのスマート カードがスマート カード読み取り装置から取り出されたときの措置を決定します。以下のオプションがあります。
<ul>
<li>何もしない</li>
<li>ワークステーションをロックする</li>
<li>ログオフを強制する</li>
</ul>
既定では、<strong>[何もしない]</strong> が指定されています。<strong>[ワークステーションをロックする]</strong> を指定した場合、スマート カードを取り外すと、ワークステーションがロックされます。それにより、ユーザーはスマート カードを持って席を離れながら、保護状態でセッションを続行することができます。[ログオフを強制する] を指定した場合、スマート カードを取り外すと、ユーザーは自動的にログオフされます。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[スマート カード取り出し時の動作]</strong>をダブルクリックします。
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
ドロップダウン メニューから <strong>[ワークステーションをロックする]</strong> を選択し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>グローバル システム オブジェクトの既定のアクセス許可を強化する (例: シンボリック リンク)</em></strong>
<strong>セキュリティの目的:</strong> オブジェクトに関する既定の随意アクセス制御リスト (DACL) の強度を決定します。Windows 2000 は、DOS デバイス名、ミューテックス、およびセマフォのような共有システム リソースのグローバル リストを保持しています。それにより、プロセスの間でオブジェクトの所在を突き止めて共有することができます。作成される各オブジェクト タイプには既定の DACL が付けられます。その中に、オブジェクトに対してだれがどのようなアクセス許可を有しているかが指定されています。このポリシーを有効にすると、既定の DACL が強化されます。それにより、管理者でないユーザーが共有オブジェクトを読むことができるようになりますが、自分が作成したのではない共有オブジェクトを修正することはできません。既定では、Windows 2000 Professional と Server 上でこのオプションはローカルに有効に設定されていますが、ドメイン セキュリティ ポリシーには定義されていません。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[グローバル システム オブジェクトの既定のアクセス許可を強化する (例: シンボリック リンク)]</strong> をダブルクリックします。
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
<strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。
スタンドアロン コンピュータ/ドメイン メンバに関して、ローカル ポリシー内でこのセキュリティ オプションが有効に設定されていることを確認します。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>署名されていないドライバのインストール時の動作</em></strong>
<strong>セキュリティの目的:</strong> Windows ハードウェア品質研究所 (WHQL) によって検証されていないデバイス ドライバを (Windows 2000 デバイス インストーラを用いて) インストールする試みがなされたときに、どのように対処するかを決定します。以下のオプションがあります。
<ul>
<li><strong>警告なしで許可する</strong></li>
<li><strong>警告するがインストールは許可する</strong></li>
<li><strong>インストールを許可しない</strong></li>
</ul>
既定の設定は <strong>[警告するがインストールは許可する]</strong> です。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[署名されていないドライバのインストール時の動作]</strong> をダブルクリックします。
ローカル ポリシーに関しては、<strong>[警告するがインストールは許可する]</strong>に設定されていることを確認します。
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
ドロップダウン メニューから <strong>[警告するがインストールは許可する]</strong> を選択し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>署名されていないドライバ以外のインストール時の動作</em></strong>
<strong>セキュリティの目的:</strong> デバイス ドライバ以外の未検証のソフトウェアをインストールする試みがなされたときに、どのように対処するかを決定します。以下のオプションがあります。
<ul>
<li><strong>警告なしで許可する</strong></li>
<li><strong>警告するがインストールは許可する</strong></li>
<li><strong>インストールを許可しない</strong></li>
</ul>
既定の設定は <strong>[警告なしで許可する]</strong> です。
<strong>手順:</strong>
右側の詳細ペイン内の <strong>[署名されていないドライバ以外のインストール時の動作]</strong> をダブルクリックします
ローカル ポリシーに関しては、<strong>[警告するがインストールは許可する]</strong>に設定されていることを確認します。
ドメインレベルのポリシーに関して、<strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。
ドロップダウン メニューから <strong>[警告するがインストールは許可する]</strong> を選択し、それから <strong>[OK]</strong> ボタンをクリックします。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
</tbody>
</table>
  
#### その他のセキュリティの設定
  
ここに記述するその他のセキュリティの設定はセキュリティ ポリシー GUI を通じて操作することはできません。したがって、レジストリ エディタを通じて構成する必要があります。レジストリ エディタの使い方については、『Windows 2000 評価された構成 管理者ガイド』を参照してください。
  
レジストリの編集方法に関する情報は **Regedit.exe** の **\[ヘルプ\]** ツールを通じて得ることもできます。たとえば、レジストリにキーを追加する方法を知るには、以下の手順で操作を行います。
  
1.  **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** を選択します。
  
2.  **\[ファイル名を指定して実行\]** ダイアログ ボックス内のテキスト ボックスに **regedt32** と入力し、**\[OK\]** ボタンをクリックします。レジストリ エディタ (Regedt32.exe) が開かれます。
  
3.  レジストリ エディタの **\[ヘルプ\]** メニューから **\[目次\]** を選択します。
  
4.  レジストリ エディタのヘルプ ツールの右側のペイン内で、**\[レジストリ情報の追加と削除\]** ハイパーリンクをクリックします。
  
5.  レジストリ情報の追加および削除に関するヘルプ トピックの一覧がペインに表示されます。そこで、**\[レジストリにキーを追加する\]** ハイパーリンクをクリックします。すると、詳細な手順の説明が表示されます。
  
**警告** : レジストリ エディタの使い方を誤ると、システム全体に及ぶ深刻な問題が生じ、それを修正するためには Windows 2000 を再インストールしなければならないことがあります。レジストリ エディタの不適切な使用によって生じた問題の解決に関して、マイクロソフトは一切保証を負いません。
  
#### 必要なレジストリの設定
  
ここに記述するレジストリの設定は、評価された構成の要件を満たすために必要です。数値はすべて 10 進数で示します。ただし、例外があります。その場合は別途注記します。
  
#### DirectDraw を無効にする
  
DirectDraw 機能はパフォーマンスの高いマルチメディア アプリケーションを可能とするために存在します。そのために、システム上の 2-D グラフィックス ハードウェアへの可能な限り最も直接的なパスがアプリケーションに提供されます。DirectDraw 機能は評価された構成の一部ではありません。したがって、この機能は無効にすべきです。
  
DirectDraw 機能は無効にするには、レジストリを編集して、Timeout 値を下に示すように 0 に変更します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Control\GraphicsDrivers</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> DCI   <strong>値の名前:</strong> Timeout</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">0</td>
</tr>
</tbody>
</table>
  
#### OS/2 および POSIX サブシステムを削除する
  
サブシステムの OS/2 と POSIX は評価された構成には含まれていません。したがって、削除すべきです。Windows 2000 から OS/2 および POSIX のサポートを削除するには、レジストリを編集して、下に示すように値を削除します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Control\Session Manager</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> SubSystems   <strong>値の名前:</strong> 任意</td>
<td style="border:1px solid black;">REG_MULTI_SZ</td>
<td style="border:1px solid black;">値を削除</td>
</tr>
</tbody>
</table>
  
#### 不必要なデバイスを無効にする
  
評価された構成では、下に列挙するすべてのデバイスを無効にする必要があります。そのためには、レジストリを編集して、下に示すように **Start** の値を 4 に変更します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Services</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> audstub   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> mnmdd   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> ndistap   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> ndiswan   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> ndproxy   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> parvdm   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> pptpminiport   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> ptilink   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> rasacd   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> rasl2tp   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> raspti   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> wanarp   <strong>値の名前:</strong> Start</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">4</td>
</tr>
</tbody>
</table>
  
#### カーネル オブジェクトの属性を保護する
  
呼び出し元の前のモードがカーネル モードであった場合に限って、オブジェクト マネージャが現在のプロセス用のオブジェクト表内のカーネル オブジェクトの属性を変更できることを保証するために、このステップが必要です。この機能を有効にするには、レジストリを編集して、下に示すようにレジストリ エントリを作成して値を設定します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Control</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Session Manager   <strong>値の名前:</strong> EnhancedSecurityLevel</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">1</td>
</tr>
</tbody>
</table>
  
#### ヌル セッション アクセスを制限する
  
ヌル セッションはコンピュータ上のさまざまな共有リソースを通じて利用される可能性のある弱点です。コンピュータ上の共有リソースへのヌル セッション アクセスを修正するには、レジストリ値の **RestrictNullSessAccess** を追加します。このレジストリ値はヌル セッションのさまざまな共有リソースをオンまたはオフに切り替えて、ユーザー名およびパスワードの認証を受けずにシステム アカウントにログオンしたユーザーへのアクセスを Server サービスに制限させるかどうかを決定します。この値を 1 に設定すると、認証されていないユーザーに対してヌル セッション アクセスをすべてのサーバー パイプおよび共有リソースだけに制限することになります。ただし、**NullSessionPipes** エントリおよび **NullSessionShares** エントリに列挙されているものは除きます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\ CurrentControlSet\Services\LanmanServer</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> parameters   <strong>値の名前:</strong> RestrictNullSessAccess</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">1</td>
</tr>
</tbody>
</table>
  
#### 名前付きパイプ上でヌル セッション アクセスを制限する
  
そのようなアクセスを制限すると、ネットワーク上で許可されていないアクセスを防止する役に立ちます。名前付きパイプおよび共有ディレクトリ上でのヌル セッション アクセスを制限するには、レジストリを編集して、下に示すように値を削除します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Services\LanmanServer</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> parameters   <strong>値の名前:</strong> NullSessionPipes
NullSessionShares</td>
<td style="border:1px solid black;">REG_MULTI_SZ</td>
<td style="border:1px solid black;">すべての値を削除</td>
</tr>
</tbody>
</table>
  
#### Service Pack 3 のレジストリのエントリ
  
Service Pack 3 には、オペレーティング システムに組み込まれているセキュリティ機能を強化するように構成可能な、新しいレジストリ エントリがいくつも追加されています。
  
#### アプリケーションで生成された入力からのセッション ロックの干渉を防止する
  
Service Pack 3 には、アプリケーションで生成されたキーボード/マウス入力メッセージによってセッション ロックが干渉されることを防止するために使用可能な、レジストリ キー値が追加されています。キーの名前は BlockSendInputResets です。大部分のポリシーの設定においては、このキーは次のディレクトリのもとに置かれています。
  
HKCU\\Software\\Policies\\Microsoft\\Windows\\Control Panel\\Desktop (ポリシー) および
  
HKCU\\Control Panel\\Desktop (ユーザー)
  
ユーザーによって適用される設定よりも、ポリシーの方が優先します。他の関連するキーと整合性を持たせるためには、キーのフォーマットは REG\_SZ とします。このキーの値がゼロ以外である場合、ブーリアン値であると解釈され、キーが設定されて機能が働いていることを意味します。このキーの値がゼロであるかまたはキーが存在しない場合、現在の機能が維持されます。
  
このキーを設定すると、「実際の」 (マウスまたはキーボードからの) 入力によってのみ、スクリーンセーバー タイマがリセットされます。現在のところ、「挿入」により時間がリセットされるケースには以下の 3 通りがあります。
  
-   SendInput を通じて入力を挿入・これは、app において入力が意図的にシミュレートされているものであり、ブロックされます。
  
-   Window のアクティブ化 – 新しいウィンドウがアクティブになると、カウンタがリセットされます。スクリーンセーバーが既にアクティブでない限り、これはブロックされます。
  
-   SPI\_SETSCREENSAVETIMEOUT、SPI\_SETSCREENSAVEACTIVE、SPI\_SETLOWPOWERTIMEOUT、SPI\_SETLOWPOWERACTIVE、SPI\_SETPOWEROFFTIMEOUT、SPI\_SETPOWEROFFACTIVE を設定する SystemParametersInfo() の呼び出し。BlockSendInputResets が設定されている場合、これらの呼び出しによってタイマはリセットされません。このことはユーザーによる操作に影響を与えないはずです。これらの値を設定するユーザーはマウスを動かしたりキーボードを叩いたりして「実際に」入力を行うからです。
  
この機能を有効にするには、下の表に示すように、レジストリ キーの値を編集します。**HKCU\\Software\\Policies\\Microsoft** キーの下に、必要な値と共に、キーのパスを作成する必要があります。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKCU\Software\Policies\Microsoft\Windows\Control Panel</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Desktop   <strong>値の名前:</strong> BlockSendInputResets</td>
<td style="border:1px solid black;">REG_SZ</td>
<td style="border:1px solid black;">1</td>
</tr>
</tbody>
</table>
  
**注意** : この機能を有効に働かせるためには、このキーと共にスクリーン セーバーを適切に設定することが重要です。以下の設定を行う必要があります。
  
-   スクリーン セーバーの選択
  
-   パスワードによる保護
  
-   スクリーン セーバーのタイムアウト期間
  
スクリーンセーバーが適切に構成されていないと、この機能はコンピュータ全体のセキュリティに関して基本的に効果を発揮しません。スクリーン セーバーをパスワードで保護する手順については、「自動画面ロック保護の有効化」に後述します。
  
#### 監査ログがいっぱいのしきい値のパーセントに達したら監査イベントを生成する
  
Service Pack 3 には、セキュリティ ログが構成可能なしきい値に達したときに、セキュリティ イベント ログのセキュリティ監査を生成する機能があります。この機能を有効にするには、下の表に示すようにキー値を作成し、セキュリティ ログにイベントを記録する引き金となる、パーセント値を指定します。下の表に示した値は推奨値です。ローカルの運用上のニーズに応じて、適切な値に設定することができます。たとえば、下の表に示したように設定した場合、セキュリティ ログのサイズが指定値 (90) に達すると、セキュリティ ログにイベント ID 523 のイベント エントリが 1 件記録されます。そのテキストは「The security event log is 90 percent full.」となっています。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Services\Eventlog</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Security   <strong>値の名前:</strong> WarningLevel</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">90</td>
</tr>
</tbody>
</table>
  
#### 推奨するレジストリの設定
  
ここでは、セキュリティ保護を強化したオペレーティング システムの構成を確立するために推奨する、レジストリの設定について説明します。
  
#### サービス拒否攻撃に対して TCP/IP スタックを強化する
  
サービス拒否攻撃は、コンピュータまたはコンピュータ上の特定のサービスをネットワーク ユーザーが使えないようにすることを狙ったネットワーク攻撃です。サービス拒否ネットワーク攻撃に対して Windows 2000 内の Windows 2000 TCP/IP スタックの抵抗力を高めるためには、TCP/IP 関連の以下のレジストリ値が役に立ちます。下に列挙したキーの中には、指定のレジストリ キーを追加する必要があるものがあります。詳細については、マイクロソフトのサポート技術情報 (KB) の記事 [315669](http://support.microsoft.com/kb/315669) 「\[HOW TO\] Windows 2000 でサービス拒否攻撃に対する TCP/IP スタックを強化する方法」を参照してください。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Services\Tcpip</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> DisableIPSourceRouting</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> EnableDeadGWDetect</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">0</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> EnableICMPRedirect</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">0</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> EnablePMTUDiscovery</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">0</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> EnableSecurityFilters</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">1</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> KeepAliveTime</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">300,000</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> NoNameReleaseOnDemand</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">1</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> PerformRouterDiscovery</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">0</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> SynAttackProtect</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">2</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> TcpMaxConnectResponseRetransmissions</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">2</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> TcpMaxConnectRetransmissions</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">3</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> TCPMaxPortsExhausted</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">5</td>
</tr>
</tbody>
</table>
  
#### スクリーンセーバーのパスワードを使用して直ちに保護する
  
スクリーンセーバーがロックされるまでにユーザーが動作を行える猶予時間は既定の 5 秒に設定されているものとみなされます。レジストリにエントリを追加することにより、この長さを調整することができます。パスワードによって直ちに保護させるために、このエントリの値を 0 に設定するよう推奨します。そのためには、下に表に示すようにレジストリ キーを編集して、ScreenSaverGracePeriod という名前の値を作成し、その値を 0 に設定します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\Software\Microsoft\Windows NT\CurrentVersion</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Winlogon   <strong>値の名前:</strong> ScreenSaverGracePeriod</td>
<td style="border:1px solid black;">REG_SZ</td>
<td style="border:1px solid black;">0</td>
</tr>
</tbody>
</table>
  
#### タイム サービス認証をレビューする
  
下の表に示したキーをレビューして、"type" の値が NT5DS に設定されていることを確認します。それにより、評価された構成に認証済みのタイム サービスが適用されることが保証されます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Services\W32Time</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> type</td>
<td style="border:1px solid black;">REG_SZ</td>
<td style="border:1px solid black;">Nt5DS</td>
</tr>
</tbody>
</table>
  
#### LMHash の作成を無効にする
  
Windows 2000 ベースのサーバーは以前のすべての Windows バージョンを稼働させているコンピュータを認証することができます。しかし、以前のバージョンの Windows では認証に Kerberos が使用されていません。そのために、Windows 2000 では LAN Manager (LM)、Windows NT (NTLM)、および NTLM バージョン 2 (NTLMv2) をサポートしています。LM ハッシュは NTLM ハッシュと比べて弱いので、強引な攻撃に早く屈しやすいです。評価された構成には LM の認証は必要ありません。したがって、それを無効にして、セキュリティを高めることができます。Windows 2000 のService Pack 2 以降には、LM ハッシュの格納を無効にするレジストリの設定が用意されています。詳細については、マイクロソフトのサポート技術情報 (KB) の記事 [299656](http://support.microsoft.com/kb/299656) 「New Registry Key to Remove LM Hashes from Active Directory and Security Account Manager」を参照してください。この値を設定するには、下に表に示すようにレジストリ キーを編集して、NoLMHash という名前のキーを作成します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Control\Lsa</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> NoLMHash   <strong>値の名前:</strong> 値の名前は不要</td>
<td style="border:1px solid black;">指定不要</td>
<td style="border:1px solid black;">指定不要</td>
</tr>
</tbody>
</table>
  
#### 自動実行を無効にする
  
自動実行機能が有効であると、メディアをドライブに挿入すると、直ちにその読み取りが開始されます。したがって、プログラムのセットアップ ファイルやオーディオ メディアのサウンドがすぐに実行開始されます。メディアを挿入したとたんに悪意のあるプログラムが実行される可能性をなくすために、以下のレジストリ値を作成して、すべてのドライブでの自動実行を無効にします。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Explorer   <strong>値の名前:</strong> NoDriveTypeAutoRun</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">255</td>
</tr>
</tbody>
</table>
  
#### Service Pack 3 のレジストリ エントリをレビューする
  
Service Pack 3 には、オペレーティング システムのセキュリティ機能を強化するために構成可能な、新しいレジストリ エントリがいくつも組み込まれています。
  
#### LDAP BIND コマンド要求の設定
  
この値は LDAP サーバー (ldapagnt.lib) における LDAP バインド コマンド要求の取り扱いを決めるために使用します。具体的には以下のとおりです。
  
1.  (既定) または未定義: SASL 認証機構を指定する LDAP バインド コマンド要求を処理するとき、LDAP トラフィックへの署名を求める LDAP クライアント要求を、AD の LDAP エージェントは常にサポートします。
  
2.  着信する要求が既に TLS/SSL によって保護されていない限り、AD の LDAP エージェントは LDAP バインド コマンド要求中の SASL のみをサポートします。他のタイプの認証が使用されている場合、AD の LDAP エージェントは LDAP バインド コマンド要求を拒否します。LDAP バインド コマンド要求が TLS/SSL を通じて着信したのではない場合、AD の LDAP エージェントはクライアント セキュリティ コンテキストにおいて LDAP トラフィック署名オプションを必要とします。
  
この値を設定するには、下に表に示すようにレジストリ キーを編集して、LdapServerIntegrity という名前の値を作成し、その値に 2 を設定します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\System\CurrentControlSet\Services\NTDS</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> LdapServerIntegrity</td>
<td style="border:1px solid black;">REG_DWORD</td>
<td style="border:1px solid black;">2</td>
</tr>
</tbody>
</table>
  
#### 監査ログがいっぱいになったときに、管理上の警告を発する
  
Windows 2000 ベースのコンピュータに関するAlerter サービスの受信者を追加するには、(Regedt32.exe を使用して) 下の表に示すようにレジストリを編集します。値のエントリは管理上の警告の宛先の各受信者名 (ユーザー名またはコンピュータ名) です。各受信者を **\[データ\]** ダイアログ ボックス内で別々の行に指定します。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >キーのパス : HKLM\SYSTEM\CurrentControlSet\Services\Alerter</th>
<th style="border:1px solid black;" >フォーマット</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>キー:</strong> Parameters   <strong>値の名前:</strong> AlertNames</td>
<td style="border:1px solid black;">REG_MULTI_SZ</td>
<td style="border:1px solid black;">上に説明</td>
</tr>
</tbody>
</table>
  
**注意** : 管理上の警告はAlerter サービスとメッセンジャ サービスの両方に依存しています。送信元のコンピュータ上でAlerter サービスが、受信側のコンピュータ上でメッセンジャ サービスが、それぞれ実行されていることを確認してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 監査ログの管理
  
ドメイン内のすべてのコンピュータに関して、セキュリティ ログを含むイベント ログの管理オプションを構成することができます。そのためには、ドメイン セキュリティ ポリシー内のイベント ログ フォルダを使用します。または、ドメイン、組織単位、およびサイト (ドメイン) に関連する、特定のグループ ポリシー オブジェクトを使用します。ローカル セキュリティ ポリシー オブジェクト内にはイベント ログ フォルダは置かれていません。
  
ドメイン メンバに関しては、イベント ビューアのスナップインを使用して、ローカル監査に関する管理オプションを構成することができます。イベント ビューアから該当するプロパティ インターフェイスを選択し、セキュリティ ログのような特定のログの管理オプションを設定します。
  
それらのインターフェイスを使用して、イベント ログを表示、ソート、フィルタリング、検索することができます。さらに、最大ログ サイズを設定したり、ログをクリアしたりすることもできます。イベント ログを正しく表示するためには、ユーザーはイベント ログ ファイルへのアクセス権限を有している必要があります。セキュリティ ログの内容を見るためには、ユーザーは Administrator グループのメンバとしてログオンしていなければなりません。イベント ビューア自体を使用するのには、特権は何も必要ありません。ログおよびレジストリの設定には ACL によりセキュリティがかけられています。
  
#### イベント ログの設定にアクセスする
  
イベント ログの現在の設定を表示して、編集できるようにします。
  
**ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順:**
  
1.  必要に応じて、ドメイン セキュリティ ポリシーまたはドメイン コントローラ セキュリティ ポリシーを開きます。
  
2.  \[セキュリティの設定\] を展開します。
  
3.  \[セキュリティの設定\] の下の \[イベント ログ\] を展開して、\[イベント ログの設定\] ポリシーを表示させます。
  
4.  **\[イベント ログの設定\]** オブジェクトをクリックします。すると、右側の詳細ペインに構成可能な監査ログ管理の設定が表示されます。
  
    ![](images/Dd277455.w2ksc318s(ja-jp,TechNet.10).gif)  
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc318(ja-jp,technet.10).gif)
  
スタンドアロンのワークステーションおよび Server の場合の手順:
  
1.  イベント ビューアを開きます。**\[スタート\]** をクリックし、**\[プログラム\]** をポイントし、**\[管理ツール\]** をポイントしてから、**\[イベント ビューア\]** をクリックします。
  
2.  **\[セキュリティ ログ\]** オブジェクトを右クリックし、それから **\[プロパティ\]** を選択します。すると、**\[セキュリティ ログのプロパティ\]** ウィンドウが表示され、その中に構成可能な監査ログ管理の設定が示されます。
  
    ![](images/Dd277455.w2ksc319(ja-jp,TechNet.10).gif)
  
表 3.8 に示されている「必須」または「推奨」の指示に応じて、監査ポリシーを設定します。
  
**表 3.8 監査ポリシーの設定**
  
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >監査ポリシーと構成</th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>アプリケーション ログの最大サイズを設定する</em></strong>
<strong>セキュリティの目的:</strong> アプリケーション イベント ログの最大サイズを指定します。既定値は 512 KB であり、最大サイズは 4 GB (4,194,240 KB) です。アプリケーション ログ サイズの要件は、プラットフォームの機能およびアプリケーション関連のイベントの履歴レコードの必要性に応じて異なります。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順:</strong>
<ol>
<li><strong>[アプリケーション ログのプロパティ]</strong> ウィンドウの <strong>[全般]</strong> タブの下の <strong>[最大ログ サイズ]</strong> テキスト ボックスに希望するアプリケーション ログ サイズの値を入力します。ほとんどの環境では、既定の設定が適切です。しかし、ログ保存方法にイベントを上書きしないように設定した場合は、ログ サイズを大きく設定する必要があります。その際、予想される処理量、ログを手作業でレビュー、アーカイブ、クリアする頻度、利用可能なディスク スペースなどを考慮に入れます。</li>
<li><strong>[OK]</strong> ボタンをクリックします。</li>
</ol></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>セキュリティ ログの最大サイズを設定する</em></strong>
<strong>セキュリティの目的:</strong> セキュリティ イベント ログの最大サイズを指定します。既定値は 512 KB であり、最大サイズは 4 GB です。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順:</strong>
<ol>
<li><strong>[セキュリティ ログのプロパティ]</strong> ウィンドウの <strong>[全般]</strong> タブの下の <strong>[最大ログ サイズ]</strong> テキスト ボックスに希望するセキュリティ ログ サイズの値を入力します。セキュリティ ログのログ保存方法にはイベントを上書きしないように設定すべきです。したがって、ログ サイズを大きく設定する必要があります。その際、予想される処理量、ログを手作業でレビュー、アーカイブ、クリアする頻度、利用可能なディスク スペースなどを考慮に入れます。</li>
<li><strong>[OK]</strong> ボタンをクリックします。</li>
</ol></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>システム ログの最大サイズを設定する</em></strong>
<strong>セキュリティの目的:</strong> システム イベント ログの最大サイズを指定します。既定値は 512 KB であり、最大サイズは 4 GB です。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順:</strong>
<ol>
<li><strong>[システム ログのプロパティ]</strong> ウィンドウの <strong>[全般]</strong> タブの下の <strong>[最大ログ サイズ]</strong> テキスト ボックスに希望するシステム ログ サイズの値を入力します。ほとんどの環境では、既定の設定が適切です。しかし、ログ保存方法にイベントを上書きしないように設定した場合は、ログ サイズを大きく設定する必要があります。その際、予想される処理量、ログを手作業でレビュー、アーカイブ、クリアする頻度、利用可能なディスク スペースなどを考慮に入れます。</li>
<li><strong>[OK]</strong> ボタンをクリックします。</li>
</ol></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>アプリケーション ログのゲスト アクセスの制限</em></strong>
<strong>セキュリティの目的</strong>: アプリケーション イベント ログへの匿名アクセスを防止します。このポリシーを有効にすると、ゲストはアプリケーション イベント ログにアクセスできなくなります。既定では、すべての Windows 2000 オペレーティング システムにおいて、このポリシーはローカルで無効に設定されています。
<strong>ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順</strong>:
<ol>
<li>右側の詳細ペイン内の <strong>[アプリケーション ログのゲスト アクセスの制限]</strong> をダブルクリックます。</li>
<li><strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。</li>
<li><strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。</li>
</ol>
<strong>スタンドアロンのワークステーションおよび Server の場合の手順:</strong> スタンドアロンのワークステーションと Server ではこの機能は利用できません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>セキュリティ ログのゲスト アクセスの制限</em></strong>
<strong>セキュリティの目的:</strong> セキュリティ イベント ログへの匿名アクセスを防止します。このポリシーを有効にすると、ゲストはセキュリティ イベント ログにアクセスできなくなります。既定では、すべての Windows 2000 オペレーティング システムにおいてこのポリシーはローカルで無効に設定されています。セキュリティ ログにアクセスするためには、ユーザーは <strong>[監査とセキュリティ ログの管理]</strong> のユーザー権利を有している必要があります。
<strong>ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順:</strong>
<ol>
<li>右側の詳細ペイン内の <strong>[セキュリティ ログのゲスト アクセスの制限]</strong> をダブルクリックします。</li>
<li><strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。</li>
<li><strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。</li>
</ol>
<strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順:</strong> スタンドアロンのワークステーションと Server ではこの機能は利用できません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>システム ログへのゲスト アクセスを制限する</em></strong>
<strong>セキュリティの目的:</strong> システム イベント ログへの匿名アクセスを防止します。このポリシーを有効にすると、ゲストはシステム イベント ログにアクセスできなくなります。既定では、すべての Windows 2000 オペレーティング システムにおいてこのポリシーはローカルで無効に設定されています。
<strong>ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順:</strong>
<ol>
<li>右側の詳細ペイン内の <strong>[システム ログのゲスト アクセスの制限]</strong> をダブルクリックします。</li>
<li><strong>[このポリシーの設定を定義する]</strong> チェック ボックスをオンにします。</li>
<li><strong>[有効]</strong> ラジオ ボタンを選択し、それから <strong>[OK]</strong> ボタンをクリックします。</li>
</ol>
<strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順:</strong> スタンドアロンのワークステーションと Server ではこの機能は利用できません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>アプリケーション ログの保存</em></strong>
<strong>セキュリティの目的:</strong> アプリケーション ログを保存すべき日数を決定します。この指定が必要なのは、ドメイン ポリシー内でアプリケーション ログの保存方法を <strong>[指定した日数を過ぎたら上書きする]</strong> に設定した場合、またはスタンドアロンのワークステーションまたは Server の <strong>[アプリケーション ログのプロパティ]</strong> ウィンドウ内で <strong>[イベントを上書きする]</strong> オプションを選択した場合です。スケジュールに従って定期的にアプリケーション ログをアーカイブしている<strong>場合にのみ</strong>、この値を設定します。また、アーカイブの間隔に対応して、アプリケーション ログの最大サイズを十分大きく取るようにします。
<strong>ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順:「未定義」</strong>となっている既定の設定を変更してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順: [アプリケーション ログのプロパティ]</strong> ウィンドウの <strong>[イベントを上書きする]</strong> オプションに設定されている既定の日数 (7) を変更してはなりません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>セキュリティ ログを保存する</em></strong>
<strong>セキュリティの目的:</strong> セキュリティ ログを保存すべき日数を決定します。この指定が必要なのは、ドメイン ポリシー内でセキュリティ ログの保存方法を <strong>[指定した日数を過ぎたら上書きする]</strong> に設定した場合、またはスタンドアロンのワークステーションまたは Server の<strong>[セキュリティ ログのプロパティ]</strong> ウィンドウ内で <strong>[イベントを上書きする]</strong> オプションを選択した場合です。スケジュールに従って定期的にセキュリティ ログをアーカイブしている<strong>場合にのみ</strong>、この値を設定します。また、アーカイブの間隔に対応して、セキュリティ ログの最大サイズを十分大きく取るようにします。
<strong>ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順:「未定義」</strong>となっている既定の設定を変更してはなりません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順: [セキュリティ ログのプロパティ]</strong> ウィンドウの <strong>[イベントを上書きする]</strong> オプションに設定されている既定の日数 (7) を変更してはなりません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>システム ログを保存する</em></strong>
<strong>セキュリティの目的:</strong> システム ログを保存すべき日数を決定します。この指定が必要なのは、ドメイン ポリシー内でシステム ログの保存方法を <strong>[指定した日数を過ぎたら上書きする]</strong> に設定した場合、またはスタンドアロンのワークステーションまたは Server の <strong>[システム ログのプロパティ]</strong> ウィンドウ内で <strong>[イベントを上書きする]</strong> オプションを選択した場合です。スケジュールに従って定期的にシステム ログをアーカイブしている<strong>場合にのみ</strong>、この値を設定します。また、アーカイブの間隔に対応して、システム ログの最大サイズを十分大きく取るようにします。
<strong>ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順:「未定義」</strong>となっている既定の設定を変更してはなりません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順: [システム ログのプロパティ]</strong>ウィンドウの <strong>[イベントを上書きする]</strong> オプションに設定されている既定の日数 (7) を変更してはなりません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>アプリケーション ログの保存方法</em></strong>
<strong>セキュリティの目的:</strong> アプリケーション ログが最大サイズに達したときの措置を決定します。
<strong>ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順:「未定義」</strong>となっている既定の設定を変更してはなりません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順: [アプリケーション ログのプロパティ]</strong> ウィンドウの <strong>[イベントを上書きする]</strong> オプションに設定されている既定の日数 (7) を変更してはなりません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>セキュリティ ログの保存方法</em></strong>
<strong>セキュリティの目的:</strong> セキュリティ ログが最大サイズに達したときの措置を決定します。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順:</strong>
<ol>
<li><strong>[セキュリティ ログのプロパティ]</strong> ウィンドウの <strong>[全般]</strong> タブの下の <strong>[イベントを上書きしない (手動でログを消去)]</strong> ラジオ ボタンを選択します。</li>
<li><strong>[OK]</strong> ボタンをクリックします。</li>
</ol></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>システム ログの保存方法</em></strong>
<strong>セキュリティの目的:</strong> システム ログが最大サイズに達したときの措置を決定します。
<strong>ドメイン ポリシーおよびドメイン コントローラ ポリシーの場合の手順:「未定義」</strong>となっている既定の設定を変更してはなりません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>スタンドアロンの Windows 2000 Professional および Server の場合の手順: [システム ログのプロパティ]</strong>ウィンドウの <strong>[イベントを上書きする]</strong> オプションに設定されている既定の日数 (7) を変更してはなりません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>セキュリティの監査ログがいっぱいになったら、コンピュータをシャットダウンする</em></strong>
<strong>セキュリティの目的:</strong> セキュリティ イベントをログに記録できないときに、システムをシャットダウンするかどうかを決定します。このポリシーが有効であると、何らかの理由でセキュリティ監査のログを取れない場合、システムは停止されます。通常、イベントをログに記録できなくなるのは、セキュリティ監査ログがいっぱいになったときに、セキュリティ ログの保存方法に <strong>[イベントを上書きしない]</strong> または <strong>[指定した日数を過ぎたら上書きする]</strong> のどちらかが指定されている場合です。
<strong>手順</strong>: 上記のポリシーの設定に代えて、[セキュリティ監査のログを記録できない場合は直ちにシステムをシャットダウンする] を使用します。このポリシーの設定はスタンドアロンのワークステーションおよび Server で利用することはできません。</td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">  <img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 既定のグループ アカウント
  
ここでは、既定の Windows 2000 オペレーティング システム環境に組み込まれているグループの既定のグループ メンバシップに対して、必須の変更および推奨する変更を説明します。組み込みのグループには、グループのメンバの他に、ユーザーの一連の権利および特権があらかじめ定義されています。組み込みのグループには以下の 4 つがあります。
  
-   **グローバル グループ** : Windows 2000 のドメインを確立するときに、Active Directory ストアのもとに組み込みのグローバル グループが作成されます。グローバル グループはドメイン全体に使用する共通のタイプのユーザーおよびグループ アカウントをグループ化するために使用します。
  
-   **ドメイン ローカル グループ** : ドメイン ローカル グループは、特にドメイン コントローラ上の Active Directory ストアのもとで、タスクを遂行する特権およびアクセス許可をユーザーに与える働きをします。
  
-   **ローカル グループ** : スタンドアロンの Windows 2000 Server、メンバ サーバー、Professional ワークステーションにはローカル グループが組み込まれています。それらのローカル グループはグループが属する特定のコンピュータ上でのみタスクを遂行する能力をメンバに与える働きをします。
  
-   **システム グループ** : システム グループには修正可能なメンバシップはありません。システム グループは特定のクラスのユーザーまたはオペレーティング システム自体を表すために使用されます。これらのグループは Windows 2000 オペレーティング システム内で自動的に作成されますが、グループ管理 GUI には表示されません。
  
**注意** : 付録 D 「ユーザー アカウントとグループ アカウント」では、評価された構成中に維持される既定のグループ アカウントの設定を網羅して説明します。その中には、追加の詳細、適用される ST 要件、および推奨する変更を含みます。
  
#### ドメインのグループ アカウントのメンバシップをレビュー/修正する
  
1.  ドメイン内のグループ アカウントにアクセスするには、ドメイン コントローラの管理者アカウントを用いてログインします。
  
2.  \[スタート\] をクリックし、\[管理ツール\] をポイントし、それから \[Active Directory ユーザーとコンピュータ\] をクリックします。
  
3.  コンソール ツリー内で \[ドメイン ノード\] をダブルクリックします。
  
4.  グループ アカウントは **\[ビルトイン\]** コンテナおよび **\[ユーザー\]** コンテナに収められています。
  
    ![](images/Dd277455.w2ksc320(ja-jp,TechNet.10).gif)
  
#### スタンドアロンのグループ アカウントのメンバシップをレビュー/修正する
  
1.  スタンドアロンまたは個々のドメイン メンバ コンピュータ内のグループ アカウントにアクセスするには、Administrator アカウントを用いてログインします。
  
2.  \[スタート\] をクリックし、\[管理ツール\] をポイントし、それから \[コンピュータの管理\] をクリックします。
  
3.  コンソール ツリー内で **\[ローカル ユーザーとグループ\]** をダブルクリックします。
  
4.  グループ アカウントは **\[グループ\]** コンテナに収められています。
  
    ![](images/Dd277455.w2ksc321(ja-jp,TechNet.10).gif)
  
**注意** : 表 3.9 に示されている「必須」または「推奨」の指示に応じて、グループ メンバシップを設定します。
  
#### アカウントのプライマリ グループ メンバシップを変更する
  
下の表に示す必須のグループ メンバシップの変更の中には、該当のグループからアカウントを削除する必要があるものがあります。ドメイン内では、アカウントにはプライマリ グループを割り当てられなければなりません。したがって、コンピュータがドメインに加えられたときに既定値として設定されたアカウントのプライマリ グループ メンバシップを最初に変更する必要がある可能性があります。プライマリ グループからアカウントを削除しようとすると、その操作が拒否されて、次のメッセージが表示されます。
  
![](images/Dd277455.w2ksc322(ja-jp,TechNet.10).gif)
  
アカウントのプライマリ グループを変更するには、以下の手順で操作を行います。
  
1.  管理者アカウントを用いてドメイン コントローラにログインします。
  
2.  \[スタート\] をクリックし、\[管理ツール\] をポイントし、それから \[Active Directory ユーザーとコンピュータ\] をクリックします。
  
3.  コンソール ツリー内で \[ドメイン ノード\] をダブルクリックします。
  
4.  ユーザー アカウントは \[ユーザー\] コンテナに収められています。
  
5.  \[アカウント名\] を右クリックし、表示されるメニューから **\[プロパティ\]** を選択します。アカウントの **\[プロパティ\]** GUI が表示されます。
  
6.  **\[所属するグループ\]** タブをクリックします。すると、アカウントが所属するグループのリストが表示されます。**\[所属するグループ\]** ウィンドウ内のどれかのグループをクリックしたときに、**\[プライマリ グループの設定\]** ボタンがアクティブになったり非アクティブになったりすることに注目してください。**\[プライマリ グループの設定\]** ボタンがアクティブになるのは、選択したグループをプライマリ グループとして設定可能な場合です。**\[プライマリ グループの設定\]** ボタンが非アクティブになるのは、選択したグループをプライマリ グループとして設定できないか、または既にプライマリ グループに設定されている場合です。
  
    ![](images/Dd277455.w2ksc323(ja-jp,TechNet.10).gif)
  
7.  アカウントのプライマリ グループを変更するには、新たにプライマリ グループとするグループを選択し、それから **\[プライマリ グループの設定\]** ボタンをクリックします ( **\[プライマリ グループの設定\]** ボタンがアクティブになっている必要があります)。**\[プライマリ グループの設定\]** ボタンの上に **\[プライマリ グループ\]** として示されているグループが新たに選択されたものに変わることに注目してください。
  
8.  **\[適用\]** をクリックし、それから **\[OK\]** をクリックします。
  
**注意** : **\[プロパティ\]** GUI の **\[所属するグループ\]** タブを通じて、グループからアカウントを削除することもできます。そのためには、アカウントを削除するグループを選択して、**\[削除\]** ボタンをクリックします。
  
**表 3.9 グループ メンバシップ**

 
<table style="border:1px solid black;">
<colgroup>
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >グループ アカウントの修正</th>
<th style="border:1px solid black;" > </th>
<th style="border:1px solid black;" > </th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>グローバル グループ</strong></td>
<td style="border:1px solid black;"><strong>既定のメンバ</strong></td>
<td style="border:1px solid black;"><strong>修正 / 検証</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>DnsUpdateProxy</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループにアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Domain Admins</em></strong></td>
<td style="border:1px solid black;">Administrator</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Domain Guests</em></strong></td>
<td style="border:1px solid black;">Guest</td>
<td style="border:1px solid black;">このグループにアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Domain Users</em></strong></td>
<td style="border:1px solid black;">Administrator
Guest
Krbtgt
TsInternetUser
(既定ではすべての新しいユーザーが追加されます)</td>
<td style="border:1px solid black;">Guest アカウントを削除し、TsInternetUser アカウントが無効になっていることを確認します。
<strong>注意</strong> : Guest アカウントを削除する前に、そのアカウントのプライマリ グループを Domain Guests に変更します。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Enterprise Admins</em></strong></td>
<td style="border:1px solid black;">Administrator (ドメイン コントローラの Administrator)</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Group Policy Creator Owner</em></strong></td>
<td style="border:1px solid black;">Administrator</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Schema Admins</em></strong></td>
<td style="border:1px solid black;">Administrator</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>ドメイン ローカル グループ</strong></td>
<td style="border:1px solid black;"><strong>既定のメンバ</strong></td>
<td style="border:1px solid black;"><strong>修正 / 検証</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Account Operators</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Administrators</em></strong></td>
<td style="border:1px solid black;">Administrator
Domain Admins</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Backup Operators</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>DnsAdmins</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Guests</em></strong></td>
<td style="border:1px solid black;">Guest (ローカル)
Domain Guests
TsInternetUser</td>
<td style="border:1px solid black;">このグループは使用しません。Guest も含めて、すべてのアカウントをこのグループから削除します。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Pre-Windows 2000 Compatible Access</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">Windows 2000 よりも前のオペレーティング システムとの下位互換性を持たせるためのものです。TOE の目的を満たさないので、このグループを使用しないでください。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Print Operators</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Replicator</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Server Operators</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Users</em></strong></td>
<td style="border:1px solid black;">Authenticated Users
Domain Users
INTERACTIVE
(既定ではすべての新しいユーザーが追加されます)</td>
<td style="border:1px solid black;">認証を受けずにアクセスする潜在的な可能性のあるアカウント (Guest など) をこのグループに追加してはいけません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>ローカル グループ</strong></td>
<td style="border:1px solid black;"><strong>既定のメンバ</strong></td>
<td style="border:1px solid black;"><strong>修正 / 検証</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Administrators</em></strong></td>
<td style="border:1px solid black;">スタンドアロン:
Administrator
ドメイン メンバ:
Administrator</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Backup Operators</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Guests</em></strong></td>
<td style="border:1px solid black;">スタンドアロン Professional:
Guest
スタンドアロン Server:
Guest
TsInternetUser
ドメイン メンバ:
上記に Domain Guests を追加します。</td>
<td style="border:1px solid black;">このグループは使用しません。Guest も含めて、すべてのアカウントをこのグループから削除します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Power Users</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Replicator</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このグループに管理者以外のアカウントを追加してはいけません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Users</em></strong></td>
<td style="border:1px solid black;">スタンドアロン:
Authenticated Users
INTERACTIVE
(既定ではすべての新しいユーザーが追加されます)
ドメインメンバ:
Authenticated Users
Domain Users
INTERACTIVE
(既定ではすべての新しいユーザーが追加されます)</td>
<td style="border:1px solid black;">認証を受けずにアクセスする潜在的な可能性のあるアカウント (Guest など) をこのグループに追加してはいけません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>システム グループ</strong></td>
<td style="border:1px solid black;"><strong>既定のメンバ</strong></td>
<td style="border:1px solid black;"><strong>修正 / 検証</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Anonymous Logon</em></strong></td>
<td style="border:1px solid black;">認証されていないすべてのユーザー</td>
<td style="border:1px solid black;">このグループは使用しません。このグループにはリソースへのアクセス許可またはユーザー権限を与えてはいけません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Authenticated Users</em></strong></td>
<td style="border:1px solid black;">認証されているすべてのユーザー</td>
<td style="border:1px solid black;">リソースへの潜在的な匿名アクセスを防止するために、Everyone の代りに、Authenticated Users グループを使用します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>DIALUP</em></strong></td>
<td style="border:1px solid black;">すべてのダイアルイン ユーザー</td>
<td style="border:1px solid black;">ダイアルアップ サービスをサポートすることは TOE の目的ではありません。したがって、このグループにはリソースへのアクセス許可またはユーザー権限を与えてはいけません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong><em>Everyone</em></strong></td>
<td style="border:1px solid black;">ローカル、ネットワークまたは RAS を通じてコンピュータにアクセスする、すべてのユーザー。その中には、認証されているユーザーも認証されていないユーザーも、すべて含まれます。</td>
<td style="border:1px solid black;">このグループにはリソースへのアクセス許可またはユーザー権限を与えてはいけません。必要に応じて、Authenticated Users または特定のユーザー アカウントおよびユーザー グループを使用します。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>TERMINAL SERVER USER</em></strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">Terminal Service をサポートすることは TOE の目的ではありません。したがって、このアカウントにはリソースへのアクセス許可またはユーザー権限を与えてはいけません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 既定のユーザー アカウント
  
ここでは、既定の Windows 2000 オペレーティング システム環境に組み込まれているユーザー アカウントに対して、必須の変更および推奨する変更を説明します。組み込みのユーザー アカウントには Administrator、Guest、および TsInternetUser があります。
  
**注意** : 付録 D 「ユーザー アカウントとグループ アカウント」では、評価された構成中に維持される既定のグループ アカウントの設定を網羅して説明します。その中には、追加の詳細、適用される ST 要件、および推奨する変更を含みます。
  
#### ドメインの既定のユーザー アカウントをレビュー/修正する
  
ユーザー アカウントをレビューまたは修正して、ST の要件を満たすようにします。
  
1.  ドメイン内のユーザー アカウントにアクセスするには、管理者アカウントを用いてドメイン コントローラにログインします。
  
2.  \[スタート\] をクリックし、\[管理ツール\] をポイントし、それから \[Active Directory ユーザーとコンピュータ\] をクリックします。
  
3.  コンソール ツリー内で \[ドメイン ノード\] を展開します。
  
4.  ユーザー アカウントは **\[ユーザー\]** コンテナに収められています。
  
    ![](images/Dd277455.w2ksc324(ja-jp,TechNet.10).gif)
  
#### 既定のユーザー アカウントをローカルにレビュー/修正する
  
スタンドアロンまたは個々のドメイン メンバ コンピュータ内のユーザー アカウントをレビューまたは修正して、ST の要件を満たすようにします。
  
1.  \[スタート\] をクリックし、\[管理ツール\] をポイントし、それから \[コンピュータの管理\] を選択します。
  
2.  コンソール ツリー内で **\[ローカル ユーザーとグループ\]** を展開します。
  
3.  ユーザー アカウントは **\[ユーザー\]** コンテナに収められています。
  
    ![](images/Dd277455.w2ksc325(ja-jp,TechNet.10).gif)
  
表 3.10 に示されている「必須」または「推奨」の指示に応じて、ユーザー アカウントを修正します。
  
**表 3.10 既定のユーザー アカウント**

 
<table style="border:1px solid black;">
<colgroup>
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
<col width="12%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >ユーザー アカウントの修正</th>
<th style="border:1px solid black;" > </th>
<th style="border:1px solid black;" > </th>
<th style="border:1px solid black;" >Professional</th>
<th style="border:1px solid black;" >Server</th>
<th style="border:1px solid black;" >DC</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ローカル ユーザー アカウント</strong></td>
<td style="border:1px solid black;"><strong>説明</strong></td>
<td style="border:1px solid black;"><strong>修正 / 検証</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong><em>Administrator</em></strong></td>
<td style="border:1px solid black;">コンピュータ/ドメインを管理するために組み込まれているアカウントです。</td>
<td style="border:1px solid black;">日常の管理にはこのアカウントを使用しません。権限を与えられた管理者のユーザー アカウントを責任のレベルに適する管理グループに含めることにより、その管理者に役割を割り当てます。Administrator アカウントの名前を変更し、パスワードで保護して、緊急時にのみ使用するようにします。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Guest</strong></td>
<td style="border:1px solid black;">コンピュータ/ドメインへのゲスト アクセス用に組み込まれているアカウントです。</td>
<td style="border:1px solid black;">このアカウントは無効にしておかなければなりません。</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>TsInternetUser</strong></td>
<td style="border:1px solid black;">Terminal Service によって使用されるユーザー アカウントです。Windows 2000 Server 上で Terminal Service のインターネット コネクタ ライセンスによって使用されます。インターネット コネクタ ライセンスが有効に設定されていると、Windows 2000 ベースのサーバーは匿名の接続を 200 件だけ受け付けます。Terminal Service のクライアントにログオン ダイアログ ボックスが提示されることはありません。Terminal Service のクライアントは TsInternetUser アカウントを用いて自動的にログオンされます。</td>
<td style="border:1px solid black;">Terminal Service は評価された構成の目的ではありません。また、匿名アクセスをサポートするアカウントは許可されるべきではありません。したがって、このアカウントを無効にします。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### システム サービス
  
評価された構成において有効にすることのできる、システム サービスを表 3.11 に一覧にして示します。表 3.11 に掲げたすべてのシステム サービスまたはそのサブセットを有効にして稼働させても、評価された構成は保たれます。
  
ドメイン内のすべて、またはあるグループの Windows 2000 プラットフォーム上でサービスを有効または無効にするために、ドメイン セキュリティ ポリシーを設定します。ドメイン コントローラ上で設定を行うには、ドメイン コントローラ セキュリティ ポリシー インターフェイスを使用します。個々の Windows 2000 プラットフォーム上では、\[コンピュータの管理\] インターフェイスを使用してローカルに設定を行うことができます。
  
**注意** : 下の表に有効であると明示されていない新しいサービスを有効にしたりインストールしたりすることは、Common Criteria (共通基準) 評価された構成の範囲から外れます。Common Criteria (共通基準) 評価された構成には、管理者がサービスをインストール、有効化、または無効化することを監査する機能が備わっていません。したがって、サービスの管理は評価された構成の範囲外で行うしかありません。ただし、その後で評価された構成を再確立する可能性があります。
  
#### ドメイン コンピュータ上の不要なシステム サービスを無効にする
  
ドメイン内の不要なサービスを無効にするように、ポリシーを設定します。ドメイン コントローラ用の不要なサービスも無効にするポリシーを設定します。
  
1.  必要に応じて、ドメイン セキュリティ ポリシーまたはドメイン コントローラ セキュリティ ポリシーを開きます。
  
2.  \[セキュリティの設定\] を展開して、\[システム サービス\] をクリックします。
  
3.  右側の詳細ペインから、無効にする対象のサービスを選択します。選択したサービスを右クリックし、それから **\[セキュリティ\]** を選択します。
  
4.  **\[セキュリティ ポリシーの設定\]** ダイアログ ウィンドウ内で、**\[このポリシーの設定を定義する\]** チェック ボックスをオンにし、それから **\[無効\]** ラジオ ボタンを選択します。
  
    ![](images/Dd277455.w2ksc326(ja-jp,TechNet.10).gif)
  
5.  **\[OK\]** ボタンをクリックします。
  
#### 不要なシステム サービスをローカルで無効にする
  
Windows 2000 Server または Professional オペレーティング システムのもとで、不要なサービスをローカルで無効にします。
  
1.  **\[コンピュータの管理\]** インターフェイスを開きます。
  
2.  コンソール ツリー内の **\[サービスとアプリケーション\]** を展開し、**\[サービス\]** を選択します。
  
3.  右側の詳細ペインから、無効にする対象のサービスを選択します。選択したサービスを右クリックし、それから **\[プロパティ\]** を選択します。
  
4.  すると、選択したサービスに関する **\[プロパティ\]** ダイアログ ボックスが表示されます。**\[スタートアップの種類\]** ドロップダウン メニューから **\[無効\]** を選択します。
  
    ![](images/Dd277455.w2ksc327(ja-jp,TechNet.10).gif)
  
5.  **\[サービスの状態\]** の下にある **\[停止\]** ボタンをクリックします。
  
6.  **\[OK\]** ボタンをクリックします。
  
#### 評価された構成のシステム サービス
  
評価された構成において有効にすることのできるシステム サービスを表 3.11 に一覧にして示します。評価された構成を保つためには、表 3.11 に記述されたすべてのシステム サービスまたはそのサブセットを有効にして稼働させても構いませんが、他のサービスはすべて無効にしなければなりません。
  
**表 3.11 評価された構成に受け入れられるサービス**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >評価されたサービスの一覧</th>
<th style="border:1px solid black;" ></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Alerter サービス
COM+ イベント システム
コンピュータ ブラウザ
DHCP クライアント
DHCP サーバー
分散ファイル システム (DFS)
DNS クライアント
DNS サーバー
イベント ログ
ファイル複製サービス
サイト間メッセージング
IPSec ポリシー エージェント
Kerberos キー配布センター
論理ディスク マネージャ
論理ディスク マネージャ管理サービス
メッセンジャ
ネット ログオン</td>
<td style="border:1px solid black;">ネットワーク接続
NTLM セキュリティ サポート プロバイダ
プラグ アンド プレイ
印刷スプーラ
保護された記憶域
リモート プロシージャ コール (RPC)
リモート プロシージャ コール (RPC) ロケータ
リモート レジストリ サービス
セキュリティ アカウント マネージャ
サーバー
システム イベント通知
TCP/IP NetBIOS ヘルパ サービス
Windows インターネット ネーム サービス (WINS)
Windows Management Instrumentation
Windows Management Instrumentation のドライバ拡張
Windows Time
ワークステーション</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[ページのトップへ](#mainsection)

### ファイル システムのセキュリティ保護

保護すべきファイルおよびディレクトリの中に、Windows 2000 オペレーティング システム自体の構成要素があります。ファイルおよびディレクトリへのアクセス許可に関する一連の既定の設定により、ソフトウェアのインストールおよび運用環境のカスタマイズを、使用性を損なわずに容易に行えるようにする、最小レベルのセキュリティがかけられています。オペレーティング システムをインストールする際に適用される既定のファイルおよびディレクトリへのアクセス許可は "setup security.inf" セキュリティ テンプレート ファイルに収められています。この一連の既定のセキュリティの設定は製品の梱包を解いて直ちに使用することができます。

さらにセキュリティを高めるために、オペレーティング システムをインストールした直後に、このサブセクションに示す推奨に従って、ファイル、ディレクトリ、およびサブディレクトリへのアクセス許可を修正することを考慮してください。アクセス許可はサブディレクトリに適用する前に、親ディレクトリに適用するようにします。下に推奨するアクセス許可の変更は、すべての Windows 2000 オペレーティング システムに当てはまります。ドメイン内のすべて、またはあるグループの Windows 2000 プラットフォームにアクセス許可を適用するには、ドメイン セキュリティ ポリシーを設定します。ドメイン コントローラ上で設定を行うには、ドメイン コントローラ セキュリティ ポリシー インターフェイスを使用します。個々の Windows 2000 プラットフォーム上でローカルなアクセス許可を設定するには Windows エクスプローラ インターフェイスを使用します。

Windows エクスプローラ インターフェイスを使用して個別にアクセス許可を設定する方法の詳細については、『Windows 2000 評価された構成 管理者ガイド』の「データ保護」を参照してください。

#### ドメイン ポリシーを通じてアクセス許可を設定する

ドメイン用のファイルおよびフォルダへのアクセス許可ポリシーを設定します。ドメイン コントローラ用のファイルおよびフォルダへのアクセス許可ポリシーを設定します。

1.  必要に応じて、ドメイン セキュリティ ポリシーまたはドメイン コントローラ セキュリティ ポリシーを開きます。

2.  \[セキュリティの設定\] を展開します。

3.  \[セキュリティの設定\] の下の \[ファイル システム\] を右クリックします。

4.  **\[ファイルの追加\]** を選択します。

5.  **\[ファイルまたはフォルダを追加します\]** ウィンドウから対象のファイルまたはフォルダに位置付けて選択します。

    ![](images/Dd277455.w2ksc328(ja-jp,TechNet.10).gif)

6.  \[OK\] ボタンをクリックします。すると、\[データベース セキュリティ - *path\\filename* プロパティ\] ウィンドウが表示されます。

    ![](images/Dd277455.w2ksc329(ja-jp,TechNet.10).gif)

7.  必要に応じてアクセス許可を設定します。具体的な方法については、『Windows 2000 評価された構成 管理者ガイド』の「データ保護」を参照してください。ファイルおよびフォルダへのアクセス許可として推奨する設定を表 3.12 に示します。

#### Windows エクスプローラを通じてアクセス許可をローカルに設定する

Windows 2000 Server または Professional オペレーティング システムのもとで、ファイルおよびフォルダへのアクセス許可をローカルに設定します。

1.  Windows エクスプローラを起動します。

2.  対象のファイルまたはフォルダに位置付けて選択します。

3.  ファイルまたはフォルダ上で右クリックし、**\[プロパティ\]** をクリックします。

4.  プロパティ ウィンドウ内の **\[セキュリティ\]** タブを選択します。さらに詳細なアクセス許可の設定を行うために、**\[詳細\]** をクリックします。

    ![](images/Dd277455.w2ksc330(ja-jp,TechNet.10).gif)

5.  必要に応じてアクセス許可を設定します。具体的な方法については、『Windows 2000 評価された構成 管理者ガイド』 の 「データ保護」を参照してください。ファイルおよびフォルダへのアクセス許可として推奨する設定を表 3.12 に示します。

**注意** : \[詳細\] タブを通じて現在のフォルダ、サブフォルダ、およびファイルに適用することにより、アクセス許可は継承されます。現在のフォルダおよびファイルまたは現在のファイル オブジェクトのみに適用することにより、アクセス許可はローカルで上書きされます。

**表 3.12 ファイルおよびフォルダへのアクセス許可の設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >ファイルおよびフォルダ</th>
<th style="border:1px solid black;" >ACL の設定</th>
<th style="border:1px solid black;" >継承メソッド (セキュリティ ポリシー ツールを通じて使用)</th>
<th style="border:1px solid black;" >必須</th>
<th style="border:1px solid black;" >推奨</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">C:\autoexec.bat</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">C:\boot.ini</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">C:\config.sys</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">C:\ntbootdd.sys
<strong>注意</strong> : SCSI が利用可能なときに使用します。</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">C:\ntdetect.com</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">C:\ntldr</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%ProgramFiles%</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\appmgmt</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\config</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\dllcache</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\DTCLog</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\GroupPolicy</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>Authenticated Users:</strong> 読み取り、実行
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\ias</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\Ntbackup.exe</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\NTMSData</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\rcp.exe</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\Regedt32.exe</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\repl</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\repl\export</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
<strong>Replicator:</strong> 読み取り、実行
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\repl\import</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>Replicator:</strong> Modify
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\rexec.exe</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\rsh.exe</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\secedit.exe</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\Setup</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\spool\Printers</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> フォルダのスキャン、属性の読み取り、拡張属性の読み取り、ファイルの作成、フォルダの作成
(フォルダおよびサブフォルダ)</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%
<strong>注意</strong> : Windows 2000 オペレーティング システムがインストールされているドライブ</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings\
Administrator</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings\
All Users</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings\
All Users\Documents\DrWatson</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> フォルダのスキャン、ファイルの作成、フォルダの作成
(フォルダおよびサブフォルダ)</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings\
All Users\Documents\DrWatson\
drwtsn32.log</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 修正</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%\io.sys</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDrive%\msdos.sys</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%\Temp</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> フォルダのスキャン、ファイルの作成、フォルダの作成
(フォルダおよびサブフォルダ)</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\$NtServicePackUninstall$</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%\debug</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\debug\UserMode</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> (フォルダのみ) - フォルダのスキャン、フォルダの一覧、ファイルの作成。 (ファイルのみ) – ファイルの作成、フォルダの作成</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%\regedit.exe</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\Registration</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り</td>
<td style="border:1px solid black;">継承</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%\repair</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\ Temp</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール
(サブフォルダおよびファイル)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> フォルダのスキャン、ファイルの作成、フォルダの作成
(フォルダおよびサブフォルダ)</td>
<td style="border:1px solid black;">上書き</td>
<td style="border:1px solid black;"> 
<img src="images/Dd277455.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 共有フォルダへのアクセス許可
  
ネイティブな Windows 2000 ファイル共有サービスは SMB ベースのサーバーおよびリダイレクタ サービスを使用して提供されます。共有リソースを作成できるのは管理者だけですが、共有リソースに設定された既定のセキュリティに基づいて、Everyone グループは全面的にアクセスすることができます。それらのアクセス許可により、ネットワーク上で可視的な共有リソースにアクセスすることができます。共有リソースを通じて表示されるファイルおよびサブフォルダへのアクセスは、共有リソースにマッピングされる根底にあるフォルダに設定された NTFS アクセス許可によって制御されます。したがって、共有リソースにマッピングされる任意のファイルおよびフォルダに対する NTFS アクセス許可を通じて、適切なセキュリティを適用するように推奨します。共有リソースへのアクセス許可を設定する詳細な手順については、『Windows 2000 評価された構成 管理者ガイド』を参照してください。しかし、評価された構成には、インストール中に既定で設定された管理的な共有リソース以外には、共有リソースが含まれていてはなりません。管理的な共有リソースの詳細については、『Windows 2000 評価された構成 管理者ガイド』を参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### レジストリのセキュリティ保護
  
このドキュメントに記載されている標準的なセキュリティに関する考慮事項に加えて、セキュリティ管理者は Windows 2000 レジストリ内の一部のキーに関する保護を強化したいかもしれません。既定では、レジストリのさまざまなコンポーネントに保護がかけられており、標準レベルのセキュリティを実現しながら、作業を遂行できるようになっています。オペレーティング システムをインストールする際に適用される既定のレジストリ キーへのアクセス許可は "setup security.inf" セキュリティ テンプレート ファイルに収められています。この一連の既定のセキュリティの設定は製品の梱包を解いて直ちに使用することができます。
  
Windows NT 4.0 に関して指摘された既定のレジストリ ACL の設定に関するセキュリティ上の問題に対処するために、マイクロソフトは Windows 2000 のレジストリ ACL に関する既定の設定を改善しました。管理者以外がレジストリにアクセスするのを制限するための評価された構成の要件を確実に遵守するために、既定の設定を変更しないことが重要です。ただし、表 3.13 に定義されている必要な ACL の変更は例外とします。変更は慎重に行うべきです。なぜなら、アプリケーションにアクセスするためにユーザーが必要とするプログラムはユーザーに代わって何らかのレジストリ キーにアクセスする必要がよくあるからです。必要なアクセス許可の変更はすべての Windows 2000 オペレーティング システムに当てはまります。
  
ドメイン内のすべてまたはあるグループの Windows 2000 プラットフォームにアクセス許可を適用するには、ドメイン セキュリティ ポリシーを設定します。ドメイン コントローラ上で設定を行うには、ドメイン コントローラ セキュリティ ポリシー インターフェイスを使用します。個々の Windows 2000 プラットフォーム上でローカルなアクセス許可を設定するには Regedt32.exe インターフェイスを使用します。レジストリ キーを変更するためには、ユーザーは TakeOwnership 特権を有しているか、またはキーの所有者である必要があります。
  
#### ドメイン ポリシーを通じてレジストリへのアクセス許可を設定する
  
ドメイン用およびドメイン コントローラ用のレジストリへのアクセス許可ポリシーを設定します。
  
1.  必要に応じて、**ドメイン セキュリティ ポリシー**またはドメイン コントローラ セキュリティ ポリシーを開きます。
  
2.  **\[セキュリティの設定\]** を展開します。
  
3.  **\[セキュリティの設定\]** の下の **\[レジストリ\]** を右クリックします。
  
4.  **\[キーの追加\]** を選択します。
  
5.  **\[レジストリ キーの選択\]** ウィンドウから対象のキーに位置付けて選択します。
  
    ![](images/Dd277455.w2ksc331(ja-jp,TechNet.10).gif)
  
6.  **\[OK\]** ボタンをクリックします。すると、**\[データベース セキュリティ -** ***path*** **プロパティ\]** ウィンドウが表示されます。
  
    ![](images/Dd277455.w2ksc332(ja-jp,TechNet.10).gif)
  
7.  必要に応じてアクセス許可を設定します。必要な ACL の変更を表 3.13 に示します。
  
#### Regedt32.exe を通じてレジストリへのアクセス許可を設定する
  
Windows 2000 Server または Professional オペレーティング システムのもとでファイルおよびフォルダへのアクセス許可をローカルに設定します。
  
1.  **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** を選択します。
  
2.  **\[ファイル名を指定して実行\]** ダイアログ ボックス内のテキスト ボックスに **regedt32** と入力して、**\[OK\]** ボタンをクリックします。すると、**レジストリ エディタ** (Regedt32.exe) が起動されます。
  
3.  対象のレジストリ キーに位置付けて選択します。
  
    ![](images/Dd277455.w2ksc333(ja-jp,TechNet.10).gif)
  
4.  **\[セキュリティ\]** メニューから **\[アクセス許可\]** を選択します。すると、**\[アクセス許可\]** ダイアログ ウィンドウが表示されます。さらに詳細なアクセス許可を設定するために、**\[詳細\]** をクリックします。
  
    ![](images/Dd277455.w2ksc334(ja-jp,TechNet.10).gif)
  
5.  必要に応じてアクセス許可を設定します。必須の ACL の変更を表 3.13 に示します。
  
**注意**
  
-   \[詳細\] タブを通じて現在のキーおよびサブキーに適用することにより、アクセス許可は継承されます。現在のキーのみに適用することにより、アクセス許可は上書きされます。
  
-   Regedt32.exe における「読み取り制御」はセキュリティ ポリシー ツールにおいては「読み取りアクセス許可」と呼ばれています。
  
-   下の表に示すPower Users グループはドメイン コントローラ上では利用できず、したがってドメイン コントローラから手作業で設定することはできません。
  
**表 3.13 レジストリへのアクセス許可に関して必須の変更**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >レジストリ キー</th>
<th style="border:1px solid black;" >サブキー ACL の設定     特殊 (読み取り、書き込み、削除) = 値の照会、値の設定、サブキーの作成、サブキーの列挙、通知、削除、読み取り制御     読み取り = 値の照会、サブキーの列挙、通知、読み取り制御     別に注記しない限り、[このキーとサブキー] に適用します。</th>
<th style="border:1px solid black;" >継承メソッド (セキュリティ ポリシー ツールを通じて使用)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKEY_LOCAL_MACHINE</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">\SOFTWARE</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)
<strong>Power Users</strong>: 特殊 (読み取り、書き込み、削除)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">\SOFTWARE\classes</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>Authenticated Users:</strong> 読み取り
<strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)
<strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">\SOFTWARE\classes\.hlp</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>Authenticated Users:</strong> 読み取り
<strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)
<strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">\SOFTWARE\classes\helpfile</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>Authenticated Users:</strong> 読み取り
<strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)
<strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">\SOFTWARE\Microsoft\OS/2 Subsystem for NT</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)
<strong>SYSTEM:</strong> フル コントロール</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">\SOFTWARE\Microsoft\Windows NT\CurrentVersion</td>
<td style="border:1px solid black;"><strong>Authenticated Users:</strong> 読み取り
<strong>注意</strong> : Everyone を Authenticated Users で置き換えます。継承した ACL はすべて残ります。</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">\SYSTEM\CurrentControlSet\ Control\ComputerName</td>
<td style="border:1px solid black;"><strong>Authenticated Users:</strong> 読み取り
<strong>注意</strong> Everyone を Authenticated Users で置き換えます。継承した ACL はすべて残ります。</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">\SYSTEM\currentcontrolset\control \ContentIndex</td>
<td style="border:1px solid black;"><strong>Authenticated Users:</strong> 読み取り
<strong>注意</strong> : Everyone を Authenticated Users で置き換えます。継承した ACL はすべて残ります。</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">\SYSTEM\CurrentControlSet\ Control\Keyboard Layout</td>
<td style="border:1px solid black;"><strong>Authenticated Users:</strong> 読み取り
<strong>注意</strong> : Everyone を Authenticated Users で置き換えます。継承した ACL はすべて残ります。</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">\SYSTEM\CurrentControlSet\ Control\Keyboard Layouts</td>
<td style="border:1px solid black;"><strong>Authenticated Users:</strong> 読み取り
<strong>注意</strong> : Everyone を Authenticated Users で置き換えます。継承した ACL はすべて残ります。</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">\SYSTEM\CurrentControlSet\ Control\Print\Printers</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>Authenticated Users:</strong> 読み取り
<strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)
<strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">\SYSTEM\CurrentControlSet\ Control\ProductOptions</td>
<td style="border:1px solid black;"><strong>Authenticated Users:</strong> 読み取り
<strong>注意</strong> : Everyone を Authenticated Users で置き換えます。継承した ACL はすべて残ります。</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">\SYSTEM\CurrentControlSet\ Services\Eventlog</td>
<td style="border:1px solid black;"><strong>Authenticated Users:</strong> 読み取り
<strong>注意</strong> : Everyone を Authenticated Users で置き換えます。継承した ACL はすべて残ります。</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">\SYSTEM\CurrentControlSet\ Services\Tcpip</td>
<td style="border:1px solid black;"><strong>Authenticated Users:</strong> 読み取り
<strong>注意</strong> : Everyone を Authenticated Users で置き換えます。継承した ACL はすべて残ります。</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKEY_CLASSES_ROOT</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">\HKEY_CLASSES_ROOT
<strong>注意</strong> : このキーは HKEY_LOCAL_MACHINE \SOFTWARE\Classes のエイリアスです。</td>
<td style="border:1px solid black;"><strong>Administrators:</strong> フル コントロール
<strong>Authenticated Users:</strong> 読み取り
<strong>CREATOR OWNER:</strong> フル コントロール (サブキーのみ)
<strong>Power Users:</strong> 特殊 (読み取り、書き込み、削除)
<strong>SYSTEM:</strong> フル コントロール
<strong>Users:</strong> 読み取り</td>
<td style="border:1px solid black;">継承</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### IPSec ポリシー
  
IPSec セキュリティ サービスを構成するには、アプリケーション プログラミング インターフェイス (API) よりもむしろ、IPSec ポリシーを使用します。IPSec ポリシーを使用すると、既存のほとんどのネットワークにおける大部分のトラフィック タイプを、さまざまなレベルで保護することができます。ユーザー、グループ、アプリケーション、ドメイン、サイト、またはグローバル エンタプライズのセキュリティ要件を満たすために、IPSec ポリシーを構成することができます。Microsoft Windows 2000 には IPSec ポリシーの管理と呼ばれる管理インターフェイスが用意されています。このインターフェイスを通じて、任意のドメイン メンバの Active Directory レベルにあるコンピュータ、またはドメインに属さないローカル コンピュータ上で、IPSec ポリシーを定義することができます。
  
Active Directory のもとに作成されたコンピュータ、サイト、ドメイン、または任意の組織単位に IPSec ポリシーを適用することができます。IPSec ポリシーは安全に運用を行うための組織のガイドラインに基づいたものでなければなりません。**ルール**と呼ばれるセキュリティ上の手段を使用して、1 つのポリシーを異質な複数のコンピュータのセキュリティ グループまたは組織単位に適用することができます。
  
IPSec ポリシーを記憶しておく場所には以下の 2 通りがあります。
  
-   Active Directory
  
-   スタンドアロン コンピュータおよびドメインに属さないコンピュータのローカル レジストリ。コンピュータが Microsoft Windows 2000 の信頼される側のドメインから一時的に外されるとき、ポリシー情報はキャッシュ化してローカル レジストリ中に保持されます。
  
各ポリシーは組織の確立されたセキュリティ計画において考慮されたシナリオに対して適用すべきです。DHCP サーバー、ドメイン ネーム システム (DNS)、Windows インターネット ネーム サービス (WINS)、簡易ネットワーク管理プロトコル (SNMP)、またはリモート アクセス サーバーにポリシーを割り当てる場合、特殊な構成の設定が適用されることがあります。
  
IPSec ポリシーを作成する手順の詳細については、『Windows 2000 評価された構成 管理者ガイド』を参照してください。評価された構成に関しては、特別な IPSec 設定要件はありません。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### ファイル システムの暗号化
  
Windows 2000 オペレーティング システムには、NTFS ボリューム上のファイルおよびフォルダを暗号化ファイル システム (EFS) を使用して暗号化する機能がもともと備わっています。EFS では、ネットワーク上にデータを暗号化して格納するために、秘密キー暗号化機構を使用します。EFS はサービスとして稼働して、秘密キー暗号化および公開キー暗号化の両方の方式を使用しています。
  
ST では、NTFS ボリューム上で EFS を有効化、無効化、および制御することができる必要があります。しかし、評価された構成に関して、特定の EFS 構成要件はありません。EFS を有効化して使用し、管理する手順の詳細、さらには暗号化キーを格納し検索する手順の詳細については、『Windows 2000 評価された構成 管理者ガイド』を参照してください。
  
オペレーティング システムを最初にインストールした後で、Administrator の暗号化証明書および秘密キーのバックアップを取るよう推奨します。その手順は以下のとおりです。
  
1.  **\[スタート\]** をクリックし、**\[ファイル名を指定して実行\]** をクリックし、**\[開く\]** ボックスに **mmc** と入力して、**\[OK\]** をクリックします。
  
2.  **\[コンソール\]** メニューの **\[スナップインの追加と削除\]** をクリックし、**\[追加\]** をクリックします。
  
3.  **証明書**スナップインに位置付け、**\[追加\]** をクリックします。
  
    ![](images/Dd277455.w2ksc335(ja-jp,TechNet.10).gif)
  
4.  **\[ユーザー アカウント\]** を選択し、**\[完了\]** をクリックします。**\[閉じる\]** をクリックします。**\[OK\]** をクリックします。
  
    ![](images/Dd277455.w2ksc336(ja-jp,TechNet.10).gif)
  
5.  個人証明書ストア内で**暗号化ファイル システム**証明書に位置付けます。**\[証明書 - 現在のユーザー\]** の横にある + 記号をクリックします。**\[個人\]** フォルダを展開します。**\[証明書\]** を選択します。
  
    ![](images/Dd277455.w2ksc337s(ja-jp,TechNet.10).gif)  
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc337(ja-jp,technet.10).gif)
  
6.  Administrator の証明書を右クリックし、表示されるメニューから **\[すべてのタスク\]** を選択し、**\[エクスポート\]** をクリックします。
  
    ![](images/Dd277455.w2ksc338s(ja-jp,TechNet.10).gif)  
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc338(ja-jp,technet.10).gif)
  
7.  8.  すると、**\[証明書マネージャ エクスポート\]** ウィザードが起動されます。**\[次へ\]** をクリックします。
  
    ![](images/Dd277455.w2ksc339(ja-jp,TechNet.10).gif)
  
9.  **\[はい、秘密キーをエクスポートします\]** ラジオ ボタンを選択し、**\[次へ\]** をクリックします。
  
    ![](images/Dd277455.w2ksc340(ja-jp,TechNet.10).gif)
  
10. 利用可能なエクスポート フォーマットは **Personal Information Exchange-PKCS\#12** または .pfx - personal exchange format です。**\[次へ\]** をクリックします。
  
    ![](images/Dd277455.w2ksc341(ja-jp,TechNet.10).gif)
  
11. .pfx データを保護するためのパスワードを指定します。**\[次へ\]** をクリックします。
  
12. .pfx データを格納する先のパスとファイル名を指定します。たとえば、**c:\\mykey** と入力します。**\[次へ\]** をクリックします。
  
    ![](images/Dd277455.w2ksc342(ja-jp,TechNet.10).gif)
  
13. エクスポート対象の証明書とキーの一覧が表示されます。確認のため **\[完了\]** をクリックします。
  
14. **\[OK\]** をクリックして、ウィザードを閉じます。スナップインを閉じます。
  
これで暗号化証明書と秘密キーが .pfx ファイルにエクスポートされます。その結果を安全にバックアップしておきます。
  
暗号化証明書と秘密キーを別のシステムに復元するには、以下の手順で操作を行います。
  
1.  .pfx ファイルをフロッピー ディスクにコピーし、そのフロッピー ディスクを暗号化証明書と秘密キーをインポートする先のコンピュータに挿入します。
  
2.  **\[スタート\]** をクリックし、**\[ファイル名を指定して実行\]** をクリックし、**mmc** と入力して、**証明書**スナップインを起動します。
  
3.  **\[コンソール\]** メニューの **\[スナップインの追加と削除\]** をクリックし、**\[追加\]** をクリックします。
  
4.  **\[証明書\]** をクリックし、**\[追加\]** をクリックします。**\[ユーザー アカウント\]** を選択し、**\[完了\]** をクリックします。**\[閉じる\]** をクリックします。**\[OK\]** をクリックします。
  
5.  **\[個人\]** ストアを右クリックし、**\[すべてのタスク\]** をクリックし、**\[インポート\]** をクリックすると、.pfx ファイルがインポートされます。
  
    ![](images/Dd277455.w2ksc343s(ja-jp,TechNet.10).gif)  
    [拡大表示する](https://technet.microsoft.com/ja-jp/dd277455.w2ksc343(ja-jp,technet.10).gif)
  
6.  これにより **\[証明書マネージャ インポート\]** ウィザードが起動されます。このウィザードの案内に従って、証明書と秘密キーを正しくインポートします。
  
    ![](images/Dd277455.w2ksc344(ja-jp,TechNet.10).gif)
  
7.  .pfx ファイルのパスを指定します。
  
8.  .pfx データを取り出すためのパスワードを入力します。
  
9.  **\[証明書をすべて次のストアに配置する\]** をクリックして、個人証明書ストアを受け入れます。**\[次へ\]** をクリックします。
  
    ![](images/Dd277455.w2ksc345(ja-jp,TechNet.10).gif)
  
10. **\[完了\]** をクリックし、**\[OK\]** をクリックすると、インポート処理が開始されます。インポートが完了したら、**\[OK\]** をクリックして、ウィザードを閉じます。
  
    ![](images/Dd277455.w2ksc346(ja-jp,TechNet.10).gif)
  
同じキーが利用可能になると、別のコンピュータにバックアップした暗号化ファイルを元の暗号化ファイルと同じように使用できるようになります。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 自動的なスクリーン ロックによる保護の有効化
  
パスワードで保護されたスクリーンセーバーを評価された構成に適用できるようにします。所定の時間にわたって操作が何も行われないとスクリーンセーバーが自動的に起動されて画面がロックされるので、ユーザーのデスクトップのセキュリティが高まります。コンピュータの画面がいったんロックされると、現在ログオンしているアカウントの持ち主のユーザーまたは権限のある管理者しかそのコンピュータにアクセスできなくなります。
  
スクリーンセーバーを用いて画面を自動的にロックするように設定するには、以下の手順で操作を行います。
  
1.  デスクトップ上で右クリックし、**\[プロパティ\]** を選択します。すると、**\[画面のプロパティ\]** ウィンドウが表示されます。
  
2.  **\[スクリーン セーバー\]** タブをクリックします。
  
3.  **\[スクリーン セーバー\]** ドロップダウン メニューからスクリーン セーバーを選択します。
  
4.  無操作の状態が何分間続いたらスクリーン セーバーを起動するかを表す数値を **\[待ち時間\]** ダイアログ ボックスに入力します (既定値の 15 分を推奨します)。
  
5.  **\[パスワードによる保護\]** チェック ボックスをオンにします。
  
    ![](images/Dd277455.w2ksc347(ja-jp,TechNet.10).gif)
  
6.  **\[OK\]** をクリックします。これでスクリーン セーバーがパスワードで保護されました。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### システム修復ディスクの更新
  
行ったすべての変更を反映するために、システム修復ディスクを更新します。具体的な方法については、「Service Pack または修正プログラムをインストールする前に推奨する措置」を参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### セキュリティで保護された構成上でのアプリケーションのインストール手順
  
Windows インストーラ ベースのパッケージの要件に準拠したアプリケーションを、評価された構成の Windows 2000 オペレーティング システムを稼働させているコンピュータに、CD-ROM からインストールすることには困難な点があります。その理由は、Windows インストーラ サービスは評価されたサービスではないので、Windows 2000 の評価された構成においては無効に設定されているからです。それに加えて、評価された構成において設定されている AllocateCDRoms レジストリ値ではWindows インストーラが CD-ROM から .Cap ファイルを直接開くことが許可されていません。したがって、Windows インストーラ ベースのパッケージの要件に準拠したアプリケーションをインストールするためには、Windows インストーラ サービスを一時的に有効にし、かつ "MACHINE\\Software\\Microsoft\\Windows NT\\CurrentVersion\\Winlogon\\AllocateCDRoms" レジストリ値を一時的に 0 に設定する必要があります (この処理はローカル セキュリティ ポリシー インターフェイスを通じて行うことができます)。
  
**注意** : Windows インストーラ ベースのパッケージの要件に準拠したアプリケーションをアンインストールするためにも、Windows インストーラ サービスを一時的に有効にする必要があります。アプリケーションをアンインストールした後で、Windows インストーラ サービスを無効にして、評価された構成に戻さなければなりません。アプリケーションをアンインストールするためには、"AllocateCDRoms" レジストリ値を修正する必要はありません。評価された構成に設定されているとおりに、有効なままにしておきます。
  
以下の手順で操作を行います。
  
1.  Windows インストーラ サービスを起動します。
  
    1.  管理者の権利を用いて、コンピュータにログオンします。
  
    2.  **\[スタート\]** をクリックし、**\[プログラム\]** をポイントし、**\[管理ツール\]** をポイントし、**\[サービス\]** クリックします。 すると、ローカル システムの **\[サービス\]** インターフェイスが開かれます。
  
    3.  右側のペイン内の **\[Windows Installer\]** を右クリックし、**\[プロパティ\]** を選択します。すると、**\[Windows Installer のプロパティ\]** インターフェイスが表示されます。
  
    4.  **\[全般\]** タブ内で、ドロップダウン メニューを使用して、**\[スタートアップの種類\]** を **\[無効\]** から **\[手動\]** に変更します。
  
    5.  **\[適用\]** ボタンをクリックします。すると、**\[サービスの状態\]** の下にある **\[開始\]** ボタンがアクティブになります。
  
    6.  **\[開始\]** ボタンをクリックして、**Windows Installer** サービスを起動します。
  
    7.  **\[OK\]** ボタンをクリックして、**\[Windows Installer のプロパティ\]** インターフェイスを閉じます。
  
    8.  **\[サービス\]** インターフェイスを閉じます。
  
2.  ローカル セキュリティ ポリシーのセキュリティ オプションにおける \[CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する\] の設定を変更します。
  
    1.  管理者としてログオンし、**\[スタート\]** をクリックし、**\[プログラム\]** をポイントし、**\[管理ツール\]** をポイントし、**\[ローカル セキュリティ ポリシー\]** クリックします。 すると、ローカル システムの **\[ローカル セキュリティ ポリシー\]** インターフェイスが開かれます。
  
    2.  \[セキュリティの設定\] を展開します。
  
    3.  \[セキュリティの設定\] の下の **\[ローカル ポリシー\]** を展開して、\[監査ポリシー\]、\[ユーザー権利の割り当て\] 、\[セキュリティ オプション\] を表示させます。
  
    4.  **\[セキュリティ オプション\]** オブジェクトをクリックします。すると、右側の詳細ペインに、構成可能な \[セキュリティ オプション\] の設定が表示されます。
  
    5.  右側の詳細ペイン内の **\[CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する\]** をダブルクリックします。
  
    6.  **\[無効\]** ラジオ ボタンを選択し、**\[OK\]** ボタンをクリックします。
  
    7.  **\[ローカル セキュリティ ポリシー\]** インターフェイスを閉じ、それからコンピュータを再起動します。
  
3.  ソフトウェア アプリケーションを CD-ROM からインストールします。
  
    1.  コンピュータが再起動されたら、管理者の権利を用いてログオンします。
  
    2.  アプリケーションのインストール用の CD-ROM を CD-ROM ドライブに挿入し、インストール手順に従って操作を進めます。
  
アプリケーションのインストールを終えたら、コンピュータ上の評価された構成の設定を元に戻す必要があります。具体的には、**Windows Installer** サービスを無効にし、**\[CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する\]** ポリシーの設定を **\[有効\]** にします。
  
1.  評価された構成を設定し直す手順は以下のとおりです。
  
    1.  上記の手順の **ステップ 1** に従って、\[サービス\] インターフェイスを開き、**Windows Installer** サービスにアクセスします。
  
    2.  ドロップダウン メニューを使用して、**\[スタートアップの種類\]** を **\[手動\]** から **\[無効\]** に変更します。
  
    3.  **\[停止\]** ボタンをクリックして、**Windows Installer** サービスを停止します。
  
    4.  **\[OK\]** ボタンをクリックして、**\[Windows Installer のプロパティ\]** インターフェイスを閉じます。
  
    5.  **\[サービス\]** インターフェイスを閉じます。
  
    6.  次に、上記の**ステップ 2** の手順に従って、**\[ローカル セキュリティ ポリシー\]** 内の **\[セキュリティ オプション\]** ポリシーを開きます。
  
    7.  右側の詳細ペイン内の \[CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する\] をダブルクリックします。
  
    8.  **\[有効\]** ラジオ ボタンを選択し、**\[OK\]** ボタンをクリックします。
  
    9.  **\[ローカル セキュリティ ポリシー\]** インターフェイスを閉じて、コンピュータを再起動します。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 目次
  
-   [第 1 章 ‐ ハードウェアおよびソフトウェアの環境](https://technet.microsoft.com/ja-jp/library/da7603d8-d1d7-400a-9993-3ac61d633e66(v=TechNet.10))  
-   [第 2 章 ‐ オペレーティング システムのインストール](https://technet.microsoft.com/ja-jp/library/ddb614e6-9456-4f76-8dea-4018a51a810d(v=TechNet.10))  
-   第 3 章 ‐ セキュリティで保護された構成  
-   [第 4 章 ‐ Windows 2000 Common Criteria (共通基準) セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/270098dc-f10b-41de-b26a-c2d795bca536(v=TechNet.10))  
-   [参考資料](https://technet.microsoft.com/ja-jp/library/6df170a9-3e6d-42d6-a4c3-0fd3eb71bf77(v=TechNet.10))  
-   [付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定](https://technet.microsoft.com/ja-jp/library/1adc2300-c9de-4ee0-bab7-9f8a797b03bc(v=TechNet.10))  
-   [付録 B ‐ 監査カテゴリとイベント](https://technet.microsoft.com/ja-jp/library/0fc077e8-8bf5-4b4d-a555-a8c26c9792f0(v=TechNet.10))  
-   [付録 C ‐ ユーザー権利と特権](https://technet.microsoft.com/ja-jp/library/9d7407aa-87b7-4564-9659-3e99abe3ac6c(v=TechNet.10))  
-   [付録 D ‐ ユーザー アカウントとグループ アカウント](https://technet.microsoft.com/ja-jp/library/50b1a83f-d25a-4ffe-b601-3adc677fa632(v=TechNet.10))  
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))  
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
