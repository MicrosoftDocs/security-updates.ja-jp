---
TOCTitle: Windows Server 2003 セキュリティ ガイド
Title: Windows Server 2003 セキュリティ ガイド
ms:assetid: '9911b568-c474-465f-998f-4f0fa31bebc6'
ms:contentKeyID: 19869679
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc163140(v=TechNet.10)'
---

Windows Server 2003 セキュリティ ガイド
=======================================

概要
----

最終更新日: 2006年8月14日

**ダウンロード**

[Windows Server 2003 セキュリティ ガイドを入手する (英語情報)](http://download.microsoft.com/download/c/8/6/c86b1b59-0388-4945-8bd9-06f04db13136/windows_server_2003_security_guide_v2.1.zip)

この最新版の*『Windows Server 2003 セキュリティ ガイド』*では、Microsoft® Windows Server™ 2003 Service Pack 1 (SP1) を実行するコンピュータのセキュリティを強化する方法の推奨事項を、3 種類の異なる環境ごとに説明します。この 3 種類の環境はそれぞれ、Windows NT® 4.0 や Windows® 98 などの古いオペレーティング システムをサポートする必要がある環境、使用している Windows オペレーティング システムのうち最も古いものが Windows 2000 である環境、セキュリティが非常に重視され、最高レベルのセキュリティを実現する代わりに、クライアントの機能および管理のしやすさが大幅に低下してもやむを得ないと見なされる環境です。このガイドでは、このそれぞれをレガシ クライアント (LC) 環境、エンタープライズ クライアント (EC) 環境、およびセキュリティ強化 - 機能制限環境と呼びます。

この 3 種類の環境のコンピュータのセキュリティを強化する方法が、サーバーの役割ごとに説明されています。記載される対策と提供されるツールは、各サーバーの役割が単一であることを前提としています。環境において、サーバーの役割を一部組み合わせる必要がある場合は、このガイドのダウンロード バージョンに付属のセキュリティ テンプレートをカスタマイズすることで、サービスとセキュリティ オプションを適宜、組み合わせることができます。このガイドで説明するサーバーの役割は次のとおりです。

-   ドメイン コントローラ (提供サービスに DNS サービスを含む)

-   WINS サービスと DHCP サービスを提供するインフラストラクチャ サーバー

-   ファイル サーバー

-   プリント サーバー

-   Microsoft インターネット インフォメーション サービス (IIS) を実行する Web サーバー

-   インターネット認証サービス (IAS) サーバー

-   証明書サービス サーバー

-   要塞ホスト

このガイドは、読者が自分の組織のコンピュータに適した設定を速やかに検索、および判断できるように、あらゆる努力を払って読みやすく編集されています。このガイドは企業ユーザー向けに作成されていますが、内容の大部分はさまざまな規模の組織に適用できます。

このガイドを最大限に活用するには、すべての内容に目を通す必要があります。また、http://go.microsoft.com/fwlink/?LinkId=15159 の関連ガイド『[脅威とその対策 : Windows Server 2003 と Windows XP のセキュリティ設定](https://technet.microsoft.com/ja-jp/library/75849e66-9f52-4ceb-874e-cace62110b09(v=TechNet.10))』も参照してください。

##### トピック

![](images/Cc163140.arrow_px_down(ja-jp,TechNet.10).gif)[対象読者](#e3c)

![](images/Cc163140.arrow_px_down(ja-jp,TechNet.10).gif)[ガイドの概要](#efd)

![](images/Cc163140.arrow_px_down(ja-jp,TechNet.10).gif)[関連リソース](#ewf)

![](images/Cc163140.arrow_px_down(ja-jp,TechNet.10).gif)[ご意見、ご感想](#ejg)

![](images/Cc163140.arrow_px_down(ja-jp,TechNet.10).gif)[コンサルティングおよびサポート サービス](#ezg)

### 対象読者

このガイドは基本的に、Windows Server 2003 のアプリケーション開発、インフラストラクチャ開発、および展開の計画段階を担当するコンサルタント、セキュリティ専門家、システム設計者、および IT 技術者を対象として作成されています。本ガイドではホーム ユーザーは想定されていません。

セキュリティ専門家や IT 設計者には、このガイドで説明するセキュリティ設定に関する詳細情報が必要になる場合があります。詳細については、http://go.microsoft.com/fwlink/?LinkId=15159 の関連ガイド『[脅威とその対策 : Windows Server 2003 と Windows XP のセキュリティ設定](https://technet.microsoft.com/ja-jp/library/75849e66-9f52-4ceb-874e-cace62110b09(v=TechNet.10))』を参照してください。

[](#mainsection)[ページのトップへ](#mainsection)

### ガイドの概要

#### 第 1 章 :Windows Server 2003 セキュリティ ガイドの概要  
この章では、*『Windows Server 2003 セキュリティ ガイド』*の概要と各章の概略について説明します。この中で、レガシ クライアント、エンタープライズ クライアント、およびセキュリティ強化 - 機能制限の各環境と、そこで実行するコンピュータについて説明します。

#### 第 2 章 :Windows Server 2003 のセキュリティ強化メカニズム  
この章では、このガイドで Windows Server 2003 SP1 のセキュリティ強化に使用する主要メカニズムである、セキュリティの構成ウィザード (SCW) と Active Directory グループ ポリシーの概要を説明します。この中で、さまざまなサーバーの役割を担当する Windows Server 2003 ベースのコンピュータのセキュリティ ポリシーの作成、管理、およびテストを行うために SCW が提供する対話的なフレームワークについて説明します。また、第 1 章で説明している 3 つの環境で使用する場合の SCW の機能を評価します。

この章ではその次に、Active Directory の設計、組織単位 (OU) の設計、グループ ポリシー オブジェクト (GPO)、管理グループの設計、およびドメイン ポリシーの、それぞれの概要について説明します。これらのトピックについて、第 1 章に記載している 3 つの環境でどうなっているかを説明し、セキュリティ保護された環境の理想的な最終形を示します。

最後に、Windows Server2003 SP1 のセキュリティ強化を目的として、SCW と従来の GPO ベースの方法の特長がどう組み合わされているかを詳しく説明します。

#### 第 3 章 :ドメイン ポリシー  
この章では、ドメイン レベルのポリシーで使用するセキュリティ テンプレートの設定と追加対策を、第 1 章で説明している 3 つの環境ごとに説明します。この章では、特定のサーバーの役割には注目せず、最上位レベルのドメイン ポリシーに役立つ個々のポリシーと設定について説明します。

#### 第 4 章 :メンバ サーバー ベースライン ポリシー  
この章では、このガイドの後半で説明するサーバーの役割で使用するメンバ サーバー ベースライン ポリシー (MSBP) の確立方法を中心に説明します。

#### 第 5 章 :ドメイン コントローラ ベースライン ポリシー  
ドメイン コントローラ サーバーの役割は、Windows Server 2003 SP1 を実行しているコンピュータによるすべての Active Directory 環境をセキュリティ保護するために最も重要な役割の 1 つです。ドメイン コントローラになんらかの損失や障害があると、認証、グループ ポリシー、および中央 LDAP (Lightweight Directory Access Protocol) ディレクトリをドメイン コントローラに依存しているクライアント コンピュータ、サーバー、およびアプリケーションが大打撃を受けることが実証されています。このガイドで定義している 3 種類の環境では、ドメイン コントローラは DNS サービスも提供します。

#### 第 6 章 :インフラストラクチャ サーバーの役割  
この章では、インフラストラクチャ サーバーの役割が DHCP サーバーまたは WINS サーバーを提供するものとして定義されています。メンバ サーバー ベースライン ポリシー (MSBP) からセキュリティ設定を適用せずに、環境内の Windows Server 2003 SP1 インフラストラクチャ サーバーをどのように活用できるのかについて詳しく説明します。

#### 第 7 章 :ファイル サーバーの役割  
この章では、ファイル サーバーとして機能するコンピュータをセキュリティ強化する方法と、ファイル サーバーのセキュリティ強化が難しい理由について説明します。ファイル サーバーが提供する最も重要なサービスには、Windows NetBIOS 関連のプロトコル、サーバー メッセージ ブロック (SMB) プロトコル、および共通インターネット ファイル システム (CIFS) プロトコルが必要です。認証済みユーザーのアクセスには、SMB プロトコルと CIFS プロトコルが一般的に使用されますが、セキュリティ保護が適切でないと、それによって未認証ユーザーや攻撃者に大量の情報が漏洩する可能性もあります。こうした脅威を理由に、これらのプロトコルは高セキュリティ環境ではしばしば無効にされます。この章では、MSBP からセキュリティ設定を適用せずに、Windows Server 2003 SP1 を実行するファイル サーバーで、どのようにセキュリティ設定を活用するかについて説明します。

#### 第 8 章 :プリント サーバーの役割  
この章では、プリント サーバーについて説明します。ファイル サーバーと同様、プリント サーバーで最も重要なサービスには、Windows NetBIOS 関連のプロトコル、SMB プロトコル、および CIFS プロトコルが必要です。前述のように、SMB プロトコルと CIFS プロトコルはほとんどの高セキュリティ環境で無効にされます。この章では、Windows Server 2003 SP1 によるプリント サーバーのセキュリティ設定を MSBP が適用されない方法で強化する方法を詳しく説明します。

#### 第 9 章 :Web サーバーの役割  
この章では、Web サイトとアプリケーションを包括的にセキュリティ保護するため、IIS サーバー全体 (その IIS サーバーで実行される各 Web サイトとアプリケーションを含む) をその環境内のクライアント コンピュータから保護する必要があることについて説明します。Web サイトやアプリケーションも、同じ IIS サーバーで実行されている他の Web サイトとアプリケーションから保護される必要があります。この章では、こうした対策を、それぞれの環境において Windows Server 2003 SP1 で実行している IIS サーバーによって実現できることを詳しく説明します。

#### 第 10 章 :IAS サーバーの役割  
インターネット認証サービス (IAS) は、RADIUS (Remote Authentication Dial-In User Services) サービスを提供します。これは標準ベースの認証プロトコルで、リモートでネットワークにアクセスしているクライアントの ID を検証することを目的としています。この章では、Windows Server 2003 SP1 を実行している IAS サーバーのセキュリティ設定が、MSBP から適用されていなくても、メリットを得ることができることについて説明します。

#### 第 11 章 :証明書サービス サーバーの役割  
証明書サービスは、サーバー環境内に公開キー基盤 (PKI) を構築するために必要な、暗号化および証明書管理サービスを提供します。この章では、Windows Server 2003 SP1 を実行している証明書サーバーが、MSBP から適用されていなくても、メリットを得ることができることについて説明します。

#### 第 12 章 :要塞ホストの役割  
要塞ホスト サーバーには、クライアント コンピュータからインターネット経由でアクセスできます。この章では、公開されているシステムが、多数のユーザーから (ユーザーが望めば完全に匿名のまま) 攻撃を受ける可能性があることについて説明します。多くの組織で、ドメイン インフラストラクチャがインターネットにまで拡張されないので、この章では、Windows Server 2003 SP1 を実行し、Active Directory-ベースのドメインに属さないスタンドアロン コンピュータのセキュリティを強化する方法に焦点を当てています。

#### 第 13 章 :結論  
このガイドの最終章では、それまでの各章で説明した内容の重要な点を簡単にまとめます。

#### 付録 A:セキュリティ ツールと形式

*『Windows Server 2003 セキュリティ ガイド』*では、SCW を使用してポリシーを作成し、そのポリシーをセキュリティ テンプレートとグループ ポリシー オブジェクトに変換する方法を中心に説明していますが、数多くの別のツールやデータ形式を使用することで、こうした方法の改善や代用が可能です。この付録では、こうしたツールと形式について簡単に説明します。

#### 付録 B:検討が必要な重要な設定

*『Windows Server 2003 セキュリティ ガイド』*では、数多くのセキュリティ対策やセキュリティ設定について説明していますが、その中でも特に重要な設定が存在します。この付録では、Windows Server 2003 SP1 を実行するコンピュータのセキュリティに大きな影響を与える設定について説明します。

#### 付録 C:セキュリティ テンプレートの設定の概要

この付録では、Microsoft Excel® スプレッドシート「[Windows Server 2003 Security Guide Settings](http://download.microsoft.com/download/c/8/6/c86b1b59-0388-4945-8bd9-06f04db13136/windows_server_2003_security_guide_v2.1.zip)」 (英語情報) を紹介します。このスプレッドシートは、http://download.microsoft.com/download/c/8/6/c86b1b59-0388-4945-8bd9-06f04db13136/Windows\_Server\_2003\_Security\_Guide\_v2.1.zip にある、このガイドの[ダウンロード バージョン](http://download.microsoft.com/download/c/8/6/c86b1b59-0388-4945-8bd9-06f04db13136/windows_server_2003_security_guide_v2.1.zip) (英語情報) のツールとテンプレートに含まれています。このスプレッドシートは、このガイドで定義している 3 種類の環境に関するすべての推奨設定が使いやすい形でコンパクトにまとめられおり、全体のマスタ リファレンスとして使用できます。

#### 付録 D:Windows Server 2003 セキュリティ ガイドのテスト

*『Windows Server 2003 セキュリティ ガイド』*では、Windows Server 2003 SP1 を実行するサーバーのセキュリティを強化する方法について多くの情報を提供していますが、この中で読者に対し、運用環境に設定を実装する前にすべての設定を検証するよう、絶えず警告しています。

この付録では、運用環境に推奨設定を確実に実装させることを目的として、適切なテスト ラボ環境を作成する方法について説明しています。これにより、必要な検証を実行しつつ、そのために必要なリソースを最小限に抑えることができます。

#### ツールおよびテンプレート

このガイドのダウンロード バージョンにはセキュリティ テンプレート、スクリプト、および追加ツールが付属しており、このガイドで推奨されている対策を組織で評価、テスト、および実装することが簡単になっています。セキュリティ テンプレートはテキスト ファイルで、ドメイン ベースのグループ ポリシーにインポートしたり、Microsoft 管理コンソール (MMC) の \[セキュリティの構成と分析\] スナップインを使用してローカルに適用したりできます。これらの手順については、「第 2 章 Windows Server 2003 のセキュリティ強化メカニズム」で詳しく説明しています。このガイドに付属のスクリプトには、グループ ポリシー オブジェクトを作成してリンクするスクリプトや、推奨対策をテストするために使用するスクリプトなどが含まれています。

[](#mainsection)[ページのトップへ](#mainsection)

### 関連リソース

このガイドで規定しているセキュリティ設定の詳細については、http://go.microsoft.com/fwlink/?LinkId=15159 の関連ガイド『[*脅威とその対策 : Windows Server 2003 と Windows XP のセキュリティ設定*](https://technet.microsoft.com/ja-jp/library/75849e66-9f52-4ceb-874e-cace62110b09(v=TechNet.10))』および http://go.microsoft.com/fwlink/?LinkId=14840 の『[*Windows XP セキュリティ ガイド*](http://go.microsoft.com/fwlink/?linkid=14840)』を参照してください。Microsoft Solutions for Security and Compliance (MSSC) チームによるその他のセキュリティ情報については、http://www.microsoft.com/japan/technet/community/columns/sectip/st0805.mspx の「[セキュリティおよび準拠に関するソリューションのガイダンス](http://www.microsoft.com/japan/technet/community/columns/sectip/st0805.mspx)」を参照してください。

[](#mainsection)[ページのトップへ](#mainsection)

### ご意見、ご感想

Microsoft Solutions for Security and Compliance (MSSC) チームは、このガイドおよびその他のソリューションに関するご意見、ご感想をお待ちしております。

ご意見をお寄せいただく場合は、「[Security Solutions Blog for the IT Professional](http://blogs.technet.com/secguide)」(英語情報) にアクセスしてご意見を入力してください。

または、[SecWish@microsoft.com](mailto:secwish@microsoft.com?subject=windows%20server%202003%20security%20guide) 宛て (英語のみ) にご意見を送ってください。この宛先に送っていただいたフィードバックにはできる限り返答させていただいております。

皆様からのご意見、ご感想をお待ちしております。

[](#mainsection)[ページのトップへ](#mainsection)

### コンサルティングおよびサポート サービス

組織のセキュリティ作業をサポートするさまざまなサービスがあります。以下のリンクが、必要なサービスを見つけるのに役立ちます。

マイクロソフト認定ゴールド パートナー、マイクロソフト認定技術教育センター、マイクロソフト認定パートナー、およびマイクロソフト テクノロジを使用したソフトウェア ベンダ (ISV) 製品については、「[Microsoft Solution Finder](https://solutionfinder.microsoft.com/)」で検索してください。

組織のニーズに適したコンサルティングおよびサポート サービスを見つけるには、http://support.microsoft.com/ の「[Microsoft Services](http://support.microsoft.com/)」(英語情報) を参照してください。

[](#mainsection)[ページのトップへ](#mainsection)

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><h5 id="目次">目次</h5>
<ul>
<li>概要</li>
<li><a href="https://technet.microsoft.com/ja-jp/library/8a6cda2e-32c2-4945-897f-0353cd6e908a(v=TechNet.10)">第 1 章 :Windows Server 2003 セキュリティ ガイドの概要</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/7cc50ea6-80d8-4ef6-81de-f47a60ebf8fa(v=TechNet.10)">第 2 章 :Windows Server 2003 のセキュリティ強化メカニズム</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/833fddab-0361-4209-bef6-ee3b14acd18d(v=TechNet.10)">第 3 章 :ドメイン ポリシー</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/d28caa21-4ec2-4556-a92a-5aa8410df6da(v=TechNet.10)">第 4 章 :メンバ サーバー ベースライン ポリシー</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/4247b4ee-4805-4ac4-8962-9f73c91bb80f(v=TechNet.10)">第 5 章 :ドメイン コントローラ ベースライン ポリシー</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/ed0c9484-c1e8-4399-8da1-488342ca6503(v=TechNet.10)">第 6 章 :インフラストラクチャ サーバーの役割</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/e4da3b65-69ce-44a2-8c77-dcd42da508b8(v=TechNet.10)">第 7 章 :ファイル サーバーの役割</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/897b32c2-f09c-4b08-b10c-37f73aa516df(v=TechNet.10)">第 8 章 :プリント サーバーの役割</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/ae41b3f3-b46f-4818-ae75-3aaf23075b56(v=TechNet.10)">第 9 章 :Web サーバーの役割</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/edd5e9dd-fda5-41a5-8b71-80ce960bc394(v=TechNet.10)">第 10 章 :IAS サーバーの役割</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/a4238f44-28fc-4931-b1d5-a37d2a173284(v=TechNet.10)">第 11 章 :証明書サービス サーバーの役割</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/c663fb69-d017-4f65-b812-01882f39a34b(v=TechNet.10)">第 12 章 :要塞ホストの役割</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/90522937-7ccc-49fe-943b-a7b95cdcd8e9(v=TechNet.10)">第 13 章 :結論</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/bb480ff2-c590-4af4-8f5d-b8d09bb272bf(v=TechNet.10)">付録 A:セキュリティ ツールと形式</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/22b7ca9a-8713-4a2a-8255-3666a82da9ee(v=TechNet.10)">付録 B:検討が必要な重要な設定</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/80d2b596-9608-4ae0-8095-81238a707002(v=TechNet.10)">付録 C:セキュリティ テンプレートの設定の概要</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/6aec7740-ad4a-4bbb-916c-16b8da021179(v=TechNet.10)">付録 D:Windows Server 2003 セキュリティ ガイドのテスト</a></li>
<li><a href="https://technet.microsoft.com/ja-jp/library/d43f2ace-bc5d-46b1-92ff-9468ae0c73ac(v=TechNet.10)">謝辞</a></li>
</ul></td>
</tr>
</tbody>
</table>
 

[](#mainsection)[ページのトップへ](#mainsection)
