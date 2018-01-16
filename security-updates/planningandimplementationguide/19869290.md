---
TOCTitle: 'セキュリティ リスク管理の統制を、Windows 2000 ドメイン上に Windows 98 および Windows NT が混在する Trey Research シナリオに適用する'
Title: 'セキュリティ リスク管理の統制を、Windows 2000 ドメイン上に Windows 98 および Windows NT が混在する Trey Research シナリオに適用する'
ms:assetid: '0516c71f-2823-40e8-bcd4-ec70d9dcd6be'
ms:contentKeyID: 19869290
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc750827(v=TechNet.10)'
---

Windows NT 4.0 および Windows 98 脅威への対策ガイド
===================================================

### 第 2 章 : セキュリティ リスク管理の統制を Trey Research のシナリオに適用する

公開日: 2004年11月17日

この章では、情報システムのリスク分析を構造的に繰り返し行う手法を適用する方法について、基礎的な部分を説明します。 システムのセキュリティ保護を行う場合、時間と労力をどの程度費やせば最適のセキュリティと投資収益 (ROI) を実現できるかを評価するには、完全なリスク管理プロセスがすべての組織で確立されている必要があります。

ビジネス ネットワーク上に従来からあるアプリケーションおよびクライアントのセキュリティを向上させる最初の手順としては、環境、アプリケーション、ユーザー、およびネットワークに関する脅威とリスクの完全な分析を行います。 マイクロソフトのセキュリティ リスク管理の統制 (SRMD) などの明確に定義されたプロセスを使用して、すべてのネットワークを分析することをお勧めします。 SRMD を利用すると、構造化された繰り返し可能なプロセスによって、組織の保有資産、これらを脅かすリスク、攻撃者による資産の盗難または損傷を可能にする脆弱性、およびリスクの軽減または移管を行うために適用できる対策を評価することができます。

SRMD に関する詳細な説明はこのガイドの対象外であり、ここでは次のことを認知していれば充分です。すなわち、SRMD は、組織が適切でかつ費用対効果の高いセキュリティ活動について正しい判断を行えるように、資産の特定、その価値の定量化、およびそれらの資産が直面する脅威の特定と定量化を行うためのフレームワークを提供するものです。

**注 :** SRMD の詳細については、この章の最後にある「関連情報」の各項目を参照してください。

##### トピック

[](#eeaa)[シナリオの詳細](#eeaa)  
[](#edaa)[セキュリティ リスク管理の統制を適用する](#edaa)  
[](#ecaa)[リスクを評価する](#ecaa)  
[](#ebaa)[リスクを決定する](#ebaa)  
[](#eaaa)[要約](#eaaa)

### シナリオの詳細

Trey Research は、廃水の分析、監視、処理を専門とする企業です。 Trey の本社はシアトルにあり、ジョージア、フロリダ、アリゾナ、ペンシルヴェニアに営業所があります。 Trey の従業員数は 500 人弱で、現場作業員、実験技術者、研究者、および数名の管理職で構成されています。

Trey Research の顧客は、専門評価サービス (地下水の水銀レベルの測定など) を必要とする地方および州政府、建設の前後および建設中に現場検査を行う必要がある建設会社各社、施設の継続的な監視を必要とする製造会社各社、緊急の環境監視または浄化を必要とするその他の企業などです。 Trey が収集したデータおよび分析結果は、財務的または法的に機密である場合がよくあります。 Trey のエンジニアが専門家証人を依頼される場合は、収集データのライフ サイクルに関して一連の証拠としての具体的な要件に適合させる必要があります。

現場作業員は、測定を用紙に記録し、事務所に戻ってから手作業で入力します。 一部のエンジニアは、Microsoft® Windows® 98 が搭載されたモバイル コンピュータを使用して現場で直接データを入力しますが、この分析システムは Trey の一部の大手顧客専用です。

過去 3 年間、Trey は、年間で約 20 パーセントの成長を続けてきました。 この成長率に刺激されて、同社の CEO は、情報システムを刷新する計画を策定および指揮する IT 責任者を雇いました。 IT 責任者は、2003 年末から活動を開始しました。最初の仕事として、会社のコンピュータ資産の価値とそれらが直面している脆弱性を理解するためリスク分析を行いました。 この分析の結果、Trey は、IT 環境に対する多数の変更を迅速に実行しました。 最初の大きな変更は、Microsoft Active Directory® ディレクトリ サービスおよび Microsoft Windows Server™ 2003 にドメイン構造をアップグレードすることでした。 このアップグレードによって、同社はドメイン アカウントのセキュリティを即座に向上させることができ、経営幹部とそのスタッフが使用するような機密性の高いコンピュータにグループ ポリシー制御を追加で適用できるようになりました。 また同社は、新しい分析および収集システム (Windows XP および Windows XP Tablet PC Edition に基づく) の初期展開が計画よりも早く開始されるように、テクノロジ刷新計画を早めました。

ただし、現時点から新システムが完全に展開されるまでの間、データ損失や侵害のリスクを軽減するために、既存システムの強化に投資を行うことも選択しました。 CEO は、IT 責任者が直近の脅威の特定、優先順位設定、軽減を行い、会社の Microsoft Windows NT® 4.0 システムのアップグレード状況を調査する作業に、1 か月という期間を与えました。 これは短い期間ですが、Trey は、関係するセキュリティの脅威を深刻に受け止め、可能な限り自社を保護するために積極的に活動しています。

#### ネットワーク

この文書で説明している推奨事項と設定は、次の図のように構成された Trey のネットワークのシミュレーションでテストされました。

![](images/Cc750827.nt980201(ja-jp,TechNet.10).gif)

**図 2.1 Trey Research ネットワークのサブセットをテストするネットワーク**

[拡大表示する](https://technet.microsoft.com/ja-jp/cc750827.nt980201_big(ja-jp,technet.10).gif)

#### Active Directory 設計

Trey Research では、組織用の単一の Active Directory ドメインが保持されています。 保守が簡単で制御しやすいため、この構成が選択されました。 どの営業所も Trey 本社と専用リース回線で接続されているため、事務所ごとにサブドメインを構築する必要はありません。

#### ビジネス要件

Trey には、会社のシステムおよびネットワークのセキュリティに関して、主要なビジネス要件が 5 つあります。

-   外部の攻撃者による侵害に対して、システムの完全性を保持します。 この要件は、ペネトレーションに対するネットワークの強化、監査とログ記録能力の向上、および、広く知られた悪用に対するシステムの脆弱性の低減を必要とします。

-   すべてのセキュリティ対策が設定されたあとも、正常な業務を保持します。 実行される分析作業はほとんどが一刻を争うものであるため、頻繁に中断が行われる状況、または中断が長く続く状況は許容できるものではありません。

-   必要に応じて情報の機密性を保持します。 Trey が管理する情報の一部は非常に機密性が高く、漏えいによって責任問題が発生する可能性は排除しておく必要があります。

-   ネットワーク上の悪意のあるコードに対する保護を向上させます。 Trey の利用ポリシーはかなり自由で無難なものであり、多数のユーザーが、ソフトウェアを自分でダウンロードしてインストールすることに慣れています。 この状況が原因で、過去にセキュリティとパフォーマンスの問題が発生しました。 強化を行う目的の 1 つに、ダウンロードした*マルウェア* (悪意のあるソフトウェア) に対する会社のシステムの脆弱性を低減させることがあります。

-   監査およびセキュリティ更新プログラムの配布方法を自動化します。

[](#mainsection)[ページのトップへ](#mainsection)

### セキュリティ リスク管理の統制を適用する

SRMD の目標は、リスクを定量化し、組織の制御範囲内にあるリスクを減らして軽減化する方法の提供です。 この目標の実現のために、SRMD では、リスク管理は、次の図のような 4 つの主要な段階に分けられる継続的なプロセスとして定義されています。

1.  リスクを評価します。 組織のリスクを特定して優先順位を設定します。 これらのリスクは、特定の IT システムまたは資産に関連する場合もあれば関連しない場合もあります。

2.  意思決定を支援します。 定義された費用対利益分析プロセスに基づいて、制御ソリューションを特定し選択します。

3.  制御を実装します。 総合的な制御ソリューションを展開および運用して、組織のリスクを低減します。

4.  リスクを判定します。 展開した制御の効果を判定して報告し、リスクを許容できるレベルで管理します。

    ![](images/Cc750827.nt980202(ja-jp,TechNet.10).gif)

    **図 2.2 SRMD サイクル**

「*マイクロソフト セキュリティ リスク管理の統制ガイド*」(2004 年後半に発行予定) に、SRMD の詳細な説明が記載されています。 Trey の IT スタッフは、SRMD 資料を確認して、次のことを実行する計画を策定しました。

1.  リスクを評価します。このプロセスでは、リスク評価の計画策定、リスクおよび組織の脆弱性の実際の程度に関するデータの収集、深刻度とコスト順によるそれらのリスクの優先順位の設定という 3 段階の作業が Trey に要求されます。

2.  リスク評価を使用し、存在するリスクの実際の程度に基づいて、適用する具体的な制御を決定します。

3.  選択した制御を実装します。 このガイドの残りの章で、特定の種類のリスクを軽減するために適用できる制御について説明します。

4.  リスクおよび組織の環境に適用された制御の効果を評価します。

この章では、最初の 2 つの手順に焦点を当て、Trey の IT スタッフが SRMD を同社の環境に適合させ、SRMD 主導のリスク管理プロセスを開始できるようにした経緯を説明します。 残りの章で、3 番目の手順、つまり実際の制御の適用に焦点を当てます。

[](#mainsection)[ページのトップへ](#mainsection)

### リスクを評価する

セキュリティ強化プロセスの開始にあたって Trey が実行する必要のある最初の重要な手順は、会社が実際に直面しているリスクと脅威を評価することです。 このプロセスにおいて、Trey は、複数の異なる手順を連携させる必要がありました。

1.  ネットワーク上の各種コンピュータの役割と機能を特定します。

2.  異なる役割間で行われる通信をマッピングします。 たとえば、アプリケーション サーバーは、ドメイン コントローラおよびユーザー ワークステーションと通信する必要があります。 このマッピングでは、これらの通信に使用されるプロトコル、ポート、およびトラフィック パターンを正確に指定する必要があります。

3.  さまざまな役割のコンピュータが悪用される可能性のある潜在的な脅威を特定します。

4.  特定の脅威が特定の役割に適用される確率または可能性を判断します。

#### 役割を特定する

ほとんどのネットワークの場合、ネットワーク上のコンピュータが果たす役割を特定するプロセスは簡単です。 会社が所有するシステムの物理的なインベントリを調査することで、Trey の IT 部門は、次の表のようなデータを作成することができました。この表では、ネットワーク上で使用される際の主な役割、それらの役割で使用されるオペレーティング システム、およびそれらの役割に一般的な場所とハードウェアの種類が一覧にされています。 この情報はすべて、脅威モデルの作成プロセスに関連します。

**表 2.1: Trey のコンピュータの役割**

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
<th style="border:1px solid black;" >役割</th>
<th style="border:1px solid black;" >役割で使用されるオペレーティング システム</th>
<th style="border:1px solid black;" >場所</th>
<th style="border:1px solid black;" >ハードウェアの種類</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">アプリケーション/Web サーバー</td>
<td style="border:1px solid black;">Windows NT 4.0</td>
<td style="border:1px solid black;">本社</td>
<td style="border:1px solid black;">従来のサーバー</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Dynamic Host Configuration Protocol (DHCP) サーバー</td>
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">本社、営業所</td>
<td style="border:1px solid black;">従来のサーバー</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ドメイン ネーム システム (DNS) サーバー</td>
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">本社</td>
<td style="border:1px solid black;">従来のサーバー</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ドメイン コントローラ</td>
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">本社、営業所</td>
<td style="border:1px solid black;">従来のサーバー</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">経営幹部のモバイル コンピュータ</td>
<td style="border:1px solid black;">Windows 2000、Windows XP</td>
<td style="border:1px solid black;">モバイル</td>
<td style="border:1px solid black;">モバイル コンピュータ</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">経営幹部/特殊用途のワークステーション</td>
<td style="border:1px solid black;">Windows XP</td>
<td style="border:1px solid black;">本社</td>
<td style="border:1px solid black;">従来のデスクトップ</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">現場のエンジニア システム</td>
<td style="border:1px solid black;">Windows 98</td>
<td style="border:1px solid black;">モバイル</td>
<td style="border:1px solid black;">モバイル コンピュータ</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ファイル/プリント サーバー</td>
<td style="border:1px solid black;">Windows NT 4.0</td>
<td style="border:1px solid black;">本社、営業所</td>
<td style="border:1px solid black;">従来のサーバー</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">メッセージング サーバー</td>
<td style="border:1px solid black;">Windows NT 4.0</td>
<td style="border:1px solid black;">本社</td>
<td style="border:1px solid black;">従来のサーバー</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">特殊用途の制御システム</td>
<td style="border:1px solid black;">Windows NT 4.0、一部 Windows 98</td>
<td style="border:1px solid black;">営業所</td>
<td style="border:1px solid black;">従来のサーバーとデスクトップの混在</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ユーザー ワークステーション</td>
<td style="border:1px solid black;">Windows 98、一部</td>
<td style="border:1px solid black;">本社、営業所</td>
<td style="border:1px solid black;">従来のデスクトップ</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Internet Name Service (WINS) サーバー</td>
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;">本社、営業所</td>
<td style="border:1px solid black;">従来のサーバー</td>
</tr>
</tbody>
</table>
  
#### 通信のマッピングを行う
  
コンピュータの役割を特定したら、異なる役割間で行われるネットワーク通信の種類の判別を開始できます。 これを判別しておくと、ネットワーク全体と古いバージョンの Windows オペレーティング システムを実行しているコンピュータが含まれたセグメントとの間で、許可する必要があるトラフックと許可してはいけないトラフィックの種類を指定できます。
  
##### ネットワークのモデルを作成する
  
ネットワークのモデル作成は簡単です。 Trey のエンジニアは、既存のネットワーク概略図を取り出し、それをネットワーク マップの基礎として使用するだけです。 そのようなマップでは、ネットワーク上の各コンピュータの物理的な場所、ネットワーク アドレス、およびオペレーティング システムの種類が示されている必要があります。 ルーターとファイアウォールの場所、およびネットワークのセグメント化方法に関しても視覚的に表示されていると理想的です。
  
##### データ フロー情報を追加する
  
ネットワーク マップが作成できたら、次の手順として、データのフローに関する情報をその上に重ね合わせます。 これは通常、Yourdon-DeMarco データ フロー ダイアグラム (DFD) 手法を使用して行います。DFD では、システムまたはオブジェクト間を流れるデータが有向直線によって示されます。 それぞれの線には、使用されるポート番号またはプロトコルのラベルを付けることができます。 最終的に、各役割セット間の通信の流れを示す図が完成します。 この図を参照することで、指定した種類のトラフィックのみが許可されるように、簡単にファイアウォールおよびポート/パケット フィルタを構成することができます。 また、データ フロー情報は、将来、Windows 2000、Windows XP、Windows Server 2003 が展開された組織のインターネット プロトコル セキュリティ (IPSec) フィルタ ルールの構築にも、簡単に使用できます。
  
#### 脅威を特定してモデルを作成する
  
脅威モデルとは、発生元に関係なく、システムに対するすべての脅威のインベントリを作成することによって、分散システムのセキュリティを強化する試みのことです。 可能な限り多数の脅威を特定することができる場合、存在する脅威の種類がわかれば脅威の軽減または排除が簡単になるという考え方が基盤にあります。 これらの決定は、その脅威の軽減は不可能、軽減は非常に困難または高価、あるいは、軽減するほど重要ではないかまたは発生する可能性がない、ということに基づいて行うことができます。 脅威モデルを作成するときの基本的な考え方は、*すでに保護が適用されることがわかっている脅威も含めて*、現実的な脅威はすべて列挙するということです。 現在防御されている脅威について検討すると、同様の攻撃または接点のある攻撃が明らかになる場合があります。
  
#### 脅威を特定する
  
Trey の IT エンジニアは、ネットワーク上に存在する役割およびさまざまな役割のコンピュータ間で使用される通信方法を示すネットワーク マップの作成を完了すると、具体的な脅威の特定および優先順位の設定を開始する準備ができたことになります。 これらの脅威は、次のような複数のカテゴリに分けることができます。
  
-   物理的なセキュリティまたはコンピュータの完全性に対する脅威。 これらの脅威には、火災、洪水、停電、偶発的または意図的な物理的損傷、不正な物理的アクセスによる侵害などがあります。
  
-   サービス拒否 (DoS) 攻撃。個々のコンピュータ、インフラストラクチャ サービス、またはネットワーク自体に関係します。
  
-   悪意のあるコードの実行。ウイルス、ワーム、トロイの木馬など。
  
-   機密情報の不正な開示。ネットワーク監視、アカウント侵害などの手段で行われます。
  
-   ユーザーまたは特権アカウントの管理喪失による侵害 (脆弱なパスワード、特権アカウントの不適切な管理、セキュリティ手順の失敗、不適切な監査などにより発生)。
  
脅威の各カテゴリには、さまざまな種類の個別の脅威が含まれます。すでに軽減されているものもあれば、Trey の環境では効果的に軽減することが難しいものもあります。 ここからは、特定の種類の脅威、およびそれらを軽減するために Trey が利用できる対策について説明します。 ここに挙げる軽減対策の効果は、多くの場合、部分的なものです。 Windows NT 4.0 または Windows 98 で利用可能な対策についてのみ説明します。Windows の最新リリースでは、さらに効果的な対策を利用できます。
  
##### 物理的なセキュリティの脅威
  
次の表では、Trey が特定した、自社のネットワークに対する物理的なセキュリティの脅威の主なものを示しています。 これらの脅威のほとんどは、会社の制御外の要因から発生したものであり、障害復旧とビジネス継続プロセスを実行するポリシーを設定することによってのみ、効果的に軽減することができます。ただし、これについての説明はこのガイドの対象外です。
  
**注 :** 次の表の "影響/範囲" および "発生の可能性" 列には、指定された各脅威の性質、範囲、発生の可能性についての、Trey の IT 部門による最適な評価が表示されています。 これらの列の具体的な値は、組織によって大きく異なる場合があります。
  
**表 2.2: 物理的なセキュリティの脅威および軽減対策**

<p> </p>
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
<th style="border:1px solid black;" >脅威</th>
<th style="border:1px solid black;" >詳細/攻撃経路</th>
<th style="border:1px solid black;" >影響/範囲</th>
<th style="border:1px solid black;" >発生の可能性</th>
<th style="border:1px solid black;" >使用可能な軽減対策</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">環境的な損害</td>
<td style="border:1px solid black;">火災、洪水、天候などの外部環境要因。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">保険、障害復旧およびビジネス継続計画。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">インフラストラクチャ サービスの一時的な停止</td>
<td style="border:1px solid black;">ワイド エリア ネットワーク (WAN) の停止/インターネット接続、電力、冷却などの重要なインフラストラクチャ サービスが Trey によって提供されない。</td>
<td style="border:1px solid black;">中/ネットワーク全体</td>
<td style="border:1px solid black;">中</td>
<td style="border:1px solid black;">このような停止は、ほとんどの場合短期間で回復します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">主要コンピュータの物理的な損傷</td>
<td style="border:1px solid black;">偶発的または意図的な損傷。</td>
<td style="border:1px solid black;">中/単一マシン</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">バックアップ、機密性の高いコンピュータへの物理的アクセスの制御。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">単一コンピュータの侵害</td>
<td style="border:1px solid black;">攻撃者によるコンピュータへの物理的アクセスおよび侵害。</td>
<td style="border:1px solid black;">高/単一マシン</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">物理的アクセスの制御、ブート強化、ローカル管理アカウントの強固なパスワード、Syskey の使用によるローカルのセキュリティ アカウント マネージャ データベース データの保護。</td>
</tr>
</tbody>
</table>
  
##### サービス拒否 (DoS) の脅威
  
DoS の脅威には、偽のトラフィックを使用してネットワーク機器またはコンピュータを妨害または麻痺させようとする意図的な試みを原因とする、ネットワーク サービスまたはコンピュータへのアクセス不可などがあります。 通常、これらの脅威はネットワーク境界で軽減されます。 次の表では、Trey が重大であると特定した、自社のネットワークに対する DoS の脅威の主なものを示しています。
  
**表 2.3: サービス拒否の脅威および軽減対策**

<p> </p>
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
<th style="border:1px solid black;" >脅威</th>
<th style="border:1px solid black;" >詳細/攻撃経路</th>
<th style="border:1px solid black;" >影響/範囲</th>
<th style="border:1px solid black;" >発生の可能性</th>
<th style="border:1px solid black;" >使用可能な軽減対策</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">ネットワーク トラフィックの改ざんまたはなりすまし</td>
<td style="border:1px solid black;">攻撃者は、不適切または無効なメッセージをホストに送信します。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">ネットワークの入口フィルタリング。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DNS サービスの改ざん</td>
<td style="border:1px solid black;">攻撃者は、DNS トラフィックのなりすまし、汚染、または妨害を行います。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">DNS サービスの品質を監視することにより、サービスの問題を迅速に検出できます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">標的トラフィックの改ざんまたはなりすまし</td>
<td style="border:1px solid black;">攻撃者は、個々のコンピュータまたは資産を標的にします。</td>
<td style="border:1px solid black;">高/単一コンピュータ</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">ポートおよびパケット フィルタリング、ネットワークのセグメンテーション、パーソナル ファイアウォール。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ユーザー アカウントのロックアウト</td>
<td style="border:1px solid black;">攻撃者は、許可されている回数以上にパスワードの入力を試行して、アカウント ロックアウト ポリシーを起動します。</td>
<td style="border:1px solid black;">中/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">ロックアウトされる回数が設定されていないアカウント ロックアウト ポリシーの展開。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">サービス アカウントのロックアウト</td>
<td style="border:1px solid black;">攻撃者は、パスワードの再試行回数を超過することによって、サービス アカウントへのアクセスを拒否させます。</td>
<td style="border:1px solid black;">中/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">ロックアウトされる回数が設定されていないアカウント ロックアウト ポリシーの展開。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">帯域幅消費攻撃</td>
<td style="border:1px solid black;">攻撃者は、ネットワークまたはデバイスを標的として意図的に帯域幅を消費します。</td>
<td style="border:1px solid black;">中/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">境界領域ネットワークの場合、入口フィルタリングおよびインターネット サービス プロバイダ (ISP) の監視。 内部ホストの場合、Transmission Control Protocol/Internet Protocol (TCP/IP) スタックの強化および入口フィルタリング。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">改ざんされた DHCP/WINS サービス</td>
<td style="border:1px solid black;">攻撃者は、クライアントとインフラストラクチャ サーバー間の DHCP または WINS トラフィックのなりすまし、汚染、または妨害を行います。</td>
<td style="border:1px solid black;">低/単一コンピュータ</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">複数の DHCP および WINS サーバーによる範囲の重複の実行。</td>
</tr>
</tbody>
</table>
  
##### 悪意のあるコードの脅威
  
次の表では、Trey が特定した、自社のネットワークに対する物理的なセキュリティの脅威の主なものを示しています。 物理的な脅威と同様に、これらの脅威のほとんどは、会社の制御外の要因から発生したものであり、障害復旧とビジネス継続プロセスを実行するポリシーを設定することによってのみ、効果的に軽減することができます。ただし、これについての説明はこのガイドの対象外です。
  
**表 2.4: 悪意のあるコードの脅威および軽減対策**

<p> </p>
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
<th style="border:1px solid black;" >脅威</th>
<th style="border:1px solid black;" >詳細/攻撃経路</th>
<th style="border:1px solid black;" >影響/範囲</th>
<th style="border:1px solid black;" >発生の可能性</th>
<th style="border:1px solid black;" >使用可能な軽減対策</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">ウイルス感染</td>
<td style="border:1px solid black;">ウイルスは、内部ユーザーによって Trey のネットワークに持ち込まれたあとに拡大します。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">中</td>
<td style="border:1px solid black;">クライアントおよびサーバーへのウイルス対策ソフトウェアの展開、ユーザー教育、パッチ管理、古いコンピュータの隔離。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">悪意のあるコードのユーザーによる実行</td>
<td style="border:1px solid black;">ユーザーが、無害を装った悪意のあるコードをダウンロードして実行します。</td>
<td style="border:1px solid black;">高/単一コンピュータ</td>
<td style="border:1px solid black;">中</td>
<td style="border:1px solid black;">Microsoft Internet Explorer の強化、ユーザー教育。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ワーム感染</td>
<td style="border:1px solid black;">ワームは、インターネットまたは感染した内部コンピュータによって持ち込まれたあとに拡大します。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">悪用対象となる脆弱性を低減するパッチ管理、古いコンピュータの隔離。</td>
</tr>
</tbody>
</table>
  
##### 情報の漏えいの脅威
  
情報の漏えいの脅威には、機密データの偶発的な漏えい、権限のあるユーザーが権限のない者に対して行った意図的な漏えい、データの漏えいを目的とした攻撃などがあります。
  
**表 2.5: 情報の漏えいの脅威および軽減対策**

<p> </p>
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
<th style="border:1px solid black;" >脅威</th>
<th style="border:1px solid black;" >詳細/攻撃経路</th>
<th style="border:1px solid black;" >影響/範囲</th>
<th style="border:1px solid black;" >発生の可能性</th>
<th style="border:1px solid black;" >使用可能な軽減対策</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">ネットワーク スニッフィング</td>
<td style="border:1px solid black;">攻撃者は、パスワードなど機密性の高いデータを取得するために、ネットワーク トラフィックを密かに監視します。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">中</td>
<td style="border:1px solid black;">ネットワークの物理的アクセス制御、Server Message Block (SMB) 署名、NTLM または LM 認証に代わる Windows NT LAN Manager バージョン 2 (NTLMv2) の使用。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">モバイル/ラップトップ コンピュータからのデータの盗難</td>
<td style="border:1px solid black;">攻撃者は、コンピュータを盗み出し、そこからデータを取り出します。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">中</td>
<td style="border:1px solid black;">なし</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">パスワード データの漏えい</td>
<td style="border:1px solid black;">攻撃者は、侵害されたコンピュータまたはネットワークからパスワード ハッシュを盗み出します。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">ドメイン コントローラの物理的アクセス制御、Syskey の使用、NTLMv2。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">意図的な情報の漏えい</td>
<td style="border:1px solid black;">権限のあるユーザーが、権限のない者へ意図的に情報を漏えいします。</td>
<td style="border:1px solid black;">高/単一コンピュータ</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">なし</td>
</tr>
</tbody>
</table>
  
##### アカウント侵害の脅威
  
アカウント侵害の脅威は、大きく 2 つのカテゴリに分けることができます。攻撃者がコンピュータに物理的にアクセスできるために発生する侵害 (したがって、攻撃者はローカル管理者パスワードの削除、キーストローク ロガーのインストールなど、コンピュータの改ざんを行うことができます)、およびネットワークベースの攻撃です。 次の表では、Trey に関係する最も重大なアカウント侵害の脅威を示しています。
  
**表 2.6: アカウント侵害の脅威および軽減対策**

<p> </p>
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
<th style="border:1px solid black;" >脅威</th>
<th style="border:1px solid black;" >詳細/攻撃経路</th>
<th style="border:1px solid black;" >影響/範囲</th>
<th style="border:1px solid black;" >発生の可能性</th>
<th style="border:1px solid black;" >使用可能な軽減対策</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">ドメイン管理者アカウントの侵害</td>
<td style="border:1px solid black;">攻撃者は、ドメイン管理者アカウントのパスワードを取得します。</td>
<td style="border:1px solid black;">高/ネットワーク全体</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">物理的アクセス制御。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">個々のコンピュータのローカル管理者アカウントの侵害</td>
<td style="border:1px solid black;">攻撃者は、パスワード解読などの手段で、ローカル管理者アカウントのパスワードを取得します。</td>
<td style="border:1px solid black;">高/単一コンピュータ</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">物理的なセキュリティ制御、NTLMv2 認証。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">個々のコンピュータのローカル管理者アカウントのパスワードのリセット</td>
<td style="border:1px solid black;">攻撃者は、コンピュータに物理的にアクセスして、ローカル管理者パスワードをリセットします。</td>
<td style="border:1px solid black;">高/単一コンピュータ</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">物理的なセキュリティ制御。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ユーザー アカウントの侵害</td>
<td style="border:1px solid black;">攻撃者は、通常のユーザー アカウントへのアクセスを取得します。</td>
<td style="border:1px solid black;">中/単一コンピュータ</td>
<td style="border:1px solid black;">低</td>
<td style="border:1px solid black;">物理的アクセス制御、SMB 署名、NTLMv2 認証。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### リスクを決定する
  
Trey の IT スタッフは、(上の各表で一覧化され、優先順位付けされているように) 組織が直面した最も重大なリスクを特定すると、個々の脅威の潜在的な影響と発生の可能性に基づき、実行する軽減対策を決定しました。 最も重大な脅威の一部は、Windows 98 および Windows NT 4.0 を実行しているコンピュータ上では効果的に対策*できません*。そのため、Trey は、インフラストラクチャ システムを Windows Server 2003 に移行することを決定しました。 その他のリスクは、オペレーティング システム固有の手順、ネットワーク構成、およびポリシー変更を組み合わせることによって軽減することができます。 潜在的な脅威をそれぞれ調査し、防御に必要なコストを計算して、Trey は、できる限り多数の重大なリスクを軽減する計画を策定しました。 このガイドの残りの章では、Trey が決定した具体的な対策について説明します。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 要約
  
この章では、SRMD を一般的な顧客のシナリオに適用した場合に関連する考慮事項の一部について説明しました。 この例に使用した情報はすべて、実際のデータに基づいています。しかし、ここに示した情報は、組織がセキュリティ リスク分析を全面的に実施するために必要な情報の、ほんの一部にすぎません。 すべてのリスク分析表やセキュリティ リスク ステートメントを含めてしまうと、この章が理解しづらい内容になってしまいます。 そのため、すばやく参照して容易に理解できるように、例の紹介に重点を置きました。
  
この章で示したガイドラインは、リスクの一覧を作成し、それに対処するための解決手順を適用するように構成されています。 一覧が完成したら、システムをセキュリティ保護して一覧に挙げられた脆弱性に対する保護を実行することで、リスクの軽減に必要な手順の特定に進むことができます。 このガイドの残りの章では、このような手順の詳細について検証します。
  
#### 詳細情報
  
SRMD をエンタープライズ環境に適用する方法の詳細については、次のリソースを参照してください。
  
-   Microsoft TechNet [http://technet.microsoft.com/library/cc163143.aspx](https://technet.microsoft.com/ja-jp/library/b3e09f12-b0dc-4a9d-946c-ac092c2994eb(v=TechNet.10))  
    の「セキュリティ リスク管理 : セキュリティ リスク管理の統制について理解する」モジュール
  
-   Microsoft TechNet [http://technet.microsoft.com/library/cc163143.aspx](https://technet.microsoft.com/ja-jp/library/b3e09f12-b0dc-4a9d-946c-ac092c2994eb(v=TechNet.10))  
    の「セキュリティ リスク管理 : セキュリティ リスク管理の統制を適用する」モジュール
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 目次
  
-   [概要](https://technet.microsoft.com/ja-jp/library/f114078a-7e91-4269-88f0-445520350634(v=TechNet.10))  
-   [第 1 章 : Windows NT 4.0 および Windows 98 脅威への対策ガイドの紹介](https://technet.microsoft.com/ja-jp/library/bf8df11a-7fdd-44c6-9dfe-5ff119152225(v=TechNet.10))  
-   第 2 章 : セキュリティ リスク管理の統制を Trey Research のシナリオに適用する  
-   [第 3 章 : ネットワークの強化とセキュリティ](http://technet.microsoft.com/ja-jp/library/cc750828.aspx)  
-   [第 4 章 : Microsoft Windows NT 4.0 の強化](http://technet.microsoft.com/ja-jp/library/cc750829.aspx)  
-   [第 5 章 : Microsoft Windows 98 の強化](http://technet.microsoft.com/ja-jp/library/cc750830.aspx)  
-   [第 6 章 : パッチ管理](http://technet.microsoft.com/ja-jp/library/cc750831.aspx)  
-   [第 7 章 : 対ウイルス保護](http://technet.microsoft.com/ja-jp/library/cc750832.aspx)  
-   [第 8 章 : 結論](https://technet.microsoft.com/ja-jp/library/2a40ad33-7a75-414d-8a5e-611baab28492(v=TechNet.10))  
-   [謝辞](https://technet.microsoft.com/ja-jp/library/2d051a1d-59c1-4fc3-ad04-6e8c7401afe4(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
