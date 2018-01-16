---
TOCTitle: '[HOWTO] Active Directory 環境で Windows XP SP2 のネットワーク保護技術を構成する方法'
Title: '[HOWTO] Active Directory 環境で Windows XP SP2 のネットワーク保護技術を構成する方法'
ms:assetid: 'b95d0f4a-e3a6-450b-b6b8-58514a8969eb'
ms:contentKeyID: 19869243
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc700817(v=TechNet.10)'
---

\[HOWTO\] Active Directory 環境で Windows XP SP2 のネットワーク保護技術を構成する方法
=====================================================================================

公開日: 2005年3月28日

##### トピック

[](#ekaa)[はじめに](#ekaa)  
[](#ejaa)[開始する前に](#ejaa)  
[](#eiaa)[管理ワークステーションと Windows Small Business Server 2003 に修正プログラムを追加する](#eiaa)  
[](#ehaa)[既存のグループ ポリシー オブジェクトを更新する](#ehaa)  
[](#egaa)[セキュリティ センターの設定を構成する](#egaa)    
[](#efaa)[Windows ファイアウォールの設定を構成する](#efaa)  
[](#eeaa)[Internet Explorer のセキュリティ設定を構成する](#eeaa)  
[](#edaa)[インターネット通信の管理の設定を構成する](#edaa)  
[](#ecaa)[DCOM アクセス設定を構成する](#ecaa)  
[](#ebaa)[RPC の設定を構成する](#ebaa)  
[](#eaaa)[関連情報](#eaaa)  

### はじめに

グループ ポリシー設定は、組織の Microsoft Active Directory の実装に基づいて適用されます。この設定により、ユーザーとコンピュータ全体にわたって標準構成のコンピュータ環境を保護できます。 Microsoft Windows XP Service Pack 2 (以下 SP2) の新しいグループ ポリシー ネットワーク保護設定には、次の機能が含まれます。

-   **Windows ファイアウォール**。 このポリシー設定を構成すると、ファイアウォールの有効/無効の切り替え、プログラムとポートの例外管理、特定のシナリオ (対象コンピュータのリモート管理を可能にする場合など) の例外の定義を行うことができます。

-   **Internet Explorer**。 この新しいポリシー設定を利用すると、Microsoft Internet Explorer のセキュリティ設定を構成できます。 さらに、さまざまなプロセスに対して Internet Explorer のセキュリティ機能を有効または無効にすることができます。

-   **インターネット通信管理**。 この設定を構成すると、組織内のコンピュータとインターネット間の情報交換に関連するタスクのために、Windows XP SP2 のさまざまなコンポーネントがインターネット経由で通信を行う方法を制御できます。

-   **DCOM セキュリティ**。 この設定を構成すると、分散コンポーネント オブジェクト モデル (DCOM) のセキュリティ設定を制御できます。 DCOM インフラストラクチャにはアクセス制御の新たな制限があるため、ネットワーク攻撃によって発生するセキュリティ リスクを最小限に抑えることができます。

-   **セキュリティ センター**。 この設定を構成すると、Windows セキュリティ センターを一元管理できます。 セキュリティ センターは、Windows XP SP2 の新しい機能です。これを利用すると、組織内のコンピュータを監視して、コンピュータが最新のセキュリティ アップデートに準拠していることを確認したり、コンピュータにセキュリティ上の問題がある場合にユーザーに通知したりすることができます。

-   **Remote Procedure Call(RPC)**。 RPC のポリシー設定を構成すると、システムの RPC インターフェイスへのリモートによる匿名アクセスをブロックしたり、RPC エンド ポイント マッパー インターフェイスへの匿名アクセスを防ぐことができます。

この文書では、ネットワーク保護のグループ ポリシー設定を導入して、Windows XP SP2 クライアント コンピュータのセキュリティを強化する方法について説明します。

推奨する設定の詳細なリストについては、次のサイトを参照してください。

-   Microsoft TechNet Web サイトの「[Windows XP セキュリティ ガイド 付録 A : Windows XP Service Pack 2 に関する追加ガイダンス (Windows XP Security Guide Appendix A: Additional Guidance for Windows XP Service Pack 2](http://www.microsoft.com/japan/technet/security/prodtech/windowsxp/secwinxp/xpsgapa.mspx))」http://www.microsoft.com/japan/technet/security/prodtech/windowsxp/secwinxp/xpsgapa.mspx

グループ ポリシー オブジェクト (GPO) に関するタスクは、Active Directory ドメイン内で実行します。 このタスクの一部はドメイン コントローラから実行できますが、通常は、Active Directory 管理ツールがインストールされている Windows XP SP2 クライアント コンピュータで実行します。

**注意 :** GPO を導入する方法の詳細については、次のサイトを参照してください。

-   Microsoft Windows Server System Web サイトの「[管理環境の設計 : グループ ポリシー導入の準備 (Designing a Managed Environment: Staging Group Policy Deployments)](http://technet2.microsoft.com/windowsserver/en/library/3ddb5bec-a454-4e9b-a6e7-397ee7c4ea3a1033.mspx?mfr=true)」 (英語)

Active Directory 環境でネットワーク保護を構成するには、次のタスクを実行します。

-   管理ワークステーションに修正プログラムを追加する

-   既存の GPO を更新する

-   セキュリティ センターの設定を構成する

-   Windows ファイアウォールの設定を構成する

-   Internet Explorer の設定を構成する

-   インターネット通信管理の設定を構成する

-   DCOM セキュリティの設定を構成する

-   RPC の設定を構成する

**重要 :** この文書に記載されている手順は、オペレーティング システムをインストールしたときの既定の設定で表示される \[スタート\] メニューを使用することを前提に作成されています。 したがって、\[スタート\] メニューの設定を変更している場合には、この手順と異なる可能性があります。

セキュリティ関連用語の定義については、次のサイトを参照してください。

-   マイクロソフト Web サイトの「[Microsoft セキュリティ用語集](http://www.microsoft.com/japan/security/glossary.mspx)」http://www.microsoft.com/japan/security/glossary.mspx

[](#mainsection)[ページのトップへ](#mainsection)

### 開始する前に

Windows XP SP2 を Active Directory ドメイン内の Windows ドメイン クライアントとして使用するには、次のいずれかのエディションの OS を実行するドメイン コントローラを使用します。

-   Microsoft Windows Server 2003

-   Microsoft Windows Small Business Server 2003

-   Microsoft Windows 2000 Server SP3 以降    

修正プログラムをインストールする前に、レジストリのバックアップなど、コンピュータのバックアップを必ず作成してください。

レジストリのバックアップを作成する方法の詳細については、次のサイトを参照してください。

-   [マイクロソフト サポート技術情報 322756「Windows XP および Windows Server 2003 でレジストリをバックアップ、編集、および復元する方法」](http://go.microsoft.com/fwlink/?linkid=36365)http://go.microsoft.com/fwlink/?linkid=36365

[](#mainsection)[ページのトップへ](#mainsection)

### 管理ワークステーションと Windows Small Business Server 2003 に修正プログラムを追加する

以前のバージョンのオペレーティング システムまたはサービス パック (Windows XP SP1 または Windows Server 2003 など) を実行しているコンピュータでグループ ポリシー オブジェクト設定を管理する場合は、修正プログラム (KB842933) をインストールして、ポリシー設定がグループ ポリシー オブジェクト エディタに正しく表示されるようにする必要があります。

Small Business Server 2003 (以下 SBS 2003) を使用している場合は、別の修正プログラム (KB872769) もインストールする必要があります。これは、SBS 2203 では既定で Windows ファイアウォールが無効にされているためで、 この修正プログラムの適用によってこの問題は解決されます。

**注意 :** ここで挙げた修正プログラムは、Windows Update には含まれていません。それぞれ個別にインストールする必要があります。 また、影響を受けるすべてのシステムに個別に適用する必要があります。

KB842933 は次のシステムに適用されます。

-   Microsoft Windows Server 2003, Web Edition

-   Microsoft Windows Server 2003, Standard Edition

-   Microsoft Windows Server 2003, Enterprise Edition

-   Microsoft Windows Server 2003, 64-Bit Enterprise Edition

-   Microsoft Windows XP Professional SP1

-   Microsoft Windows Small Business Server 2003, Premium Edition

-   Microsoft Windows Small Business Server 2003, Standard Edition

-   Microsoft Windows 2000 Advanced Server

-   Microsoft Windows 2000 Server

-   Microsoft Windows 2000 Professional

KB872769 は次のシステムに適用されます。

-   Microsoft Windows Small Business Server 2003, Standard Edition

-   Microsoft Windows Small Business Server 2003, Premium Edition

    **注意 :** これらの修正プログラムの入手方法と詳細については、次のサイトを参照してください。

    -   [マイクロソフト サポート技術情報 842933「Windows Server 2003、Windows XP Professional または Windows 2000 で GPO を編集または参照すると、エラー メッセージ "\[strings\] セクションの次のエントリが長すぎるため切り詰められました" が表示される」](http://go.microsoft.com/fwlink/?linkid=35474)http://go.microsoft.com/fwlink/?linkid=35474

    -   [マイクロソフト サポート技術情報 872769「Windows Small Business Server 2003 ベースのネットワーク内にある Windows XP Service Pack 2 ベースのクライアント コンピュータで Windows ファイアウォールまたはセキュリティ センターの設定を構成できない」](http://go.microsoft.com/fwlink/?linkid=35477)http://go.microsoft.com/fwlink/?linkid=35477

#### このタスクを実行するための要件

-   資格情報 : Domain Administrators セキュリティ グループまたは Local Administrators セキュリティ グループのメンバとして、クライアント コンピュータにログオンする必要があります。

-   ツール : マイクロソフト サポート技術情報の文書 842933 および 872769 の説明どおりにダウンロードした、使用しているオペレーティング システムに対応した修正プログラム。

##### 修正プログラム 842933 を、Windows Small Business Server 2003、Windows 2000 Server SP3 以降、Windows XP SP1、または Windows Server 2003 に追加する

**修正プログラムを追加するには**

1.  Windows デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、ダウンロードした修正プログラムのパスとファイル名を入力して、**\[OK\]** をクリックします。

2.  **\[KB842933 セットアップ ウィザードへようこそ\]** ページで **\[次へ\]** をクリックします。

3.  **\[使用許諾契約書\]** ページで **\[同意します\]** をクリックして、**\[次へ\]** をクリックします。

4.  **\[KB842933 セットアップ ウィザードの完了\]** ページで、修正プログラムのインストールを完了してコンピュータを再起動するために、**\[完了\]** をクリックします。

5.  修正プログラムを適用するすべてのシステム (サーバーおよび管理ワークステーション) について、上記の手順を繰り返します。

##### 修正プログラム 872769 を、Windows Small Business Server 2003 に追加する

**修正プログラムを追加するには**

1.  Windows デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、ダウンロードした修正プログラム 872769 のパスとファイル名を入力して、**\[OK\]** をクリックします。

2.  **\[KB872769 セットアップ ウィザードへようこそ\]** ページで **\[次へ\]** をクリックします。

3.  **\[使用許諾契約書\]** ページで **\[同意します\]** をクリックして、**\[次へ\]** をクリックします。

4.  **\[KB872769 セットアップ ウィザードの完了\]** ページで、修正プログラムのインストールを完了してコンピュータを再起動するために、**\[完了\]** をクリックします。

[](#mainsection)[ページのトップへ](#mainsection)

### 既存のグループ ポリシー オブジェクトを更新する

Windows XP SP2 では、追加の設定は管理用テンプレートで追加されます。 この新しい設定を構成するには、Windows XP SP2 の新しい管理用テンプレートを使用して、各 GPO を更新する必要があります。 グループ ポリシー オブジェクトを更新しない限り、Windows ファイアウォールに関連する設定は使用できません。

GPO を更新するには、Windows XP SP2 がインストールされているコンピュータ上の、グループ ポリシー オブジェクト エディタ スナップインがインストールされている Microsoft 管理コンソール (MMC) を使用します。

GPO の更新が完了すると、Windows XP SP2 を実行しているコンピュータに適したネットワーク保護設定を構成できます。

#### このタスクを実行するための要件

-   資格情報 : Domain Admins または Group Policy Creator/Owner セキュリティ グループのメンバとして、Active Directory ドメイン クライアントである Windows XP SP2 コンピュータにログオンする必要があります。

-   ツール : グループ ポリシー オブジェクト エディタ スナップインがインストールされている Microsoft 管理コンソール (MMC)。

##### グループ ポリシー オブジェクトを更新する

**グループ ポリシー オブジェクトを更新するには**

1.  Windows XP SP2 デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**mmc**」と入力して、**\[OK\]** をクリックします。

2.  **\[ファイル\]** メニューの **\[スナップインの追加と削除\]** をクリックします。

3.  **\[スタンドアロン\]** タブで **\[追加\]** をクリックします。

4.  **\[利用できるスタンドアロン スナップイン\]** ボックスに表示されるリストの中から **\[グループ ポリシー オブジェクト エディタ\]** をクリックし、**\[追加\]** をクリックします。

5.  **\[グループ ポリシー オブジェクトの選択\]** ダイアログ ボックスで **\[参照\]** をクリックします。

    ![](images/Cc700817.adprte01(ja-jp,TechNet.10).gif)

    **図 1   \[グループ ポリシー オブジェクトの参照\]**

6.  **\[グループ ポリシー オブジェクトの参照\]** ダイアログ ボックスで、新しい Windows ファイアウォールの設定で更新するグループ ポリシー オブジェクトを選択します。

7.  **\[OK\]** をクリックし、次に **\[完了\]** をクリックしてグループ ポリシー ウィザードを閉じます。

    新しい管理用テンプレートが、選択した GPO に適用されます。

8.  **\[スタンドアロン スナップインの追加\]** ダイアログ ボックスで **\[閉じる\]** をクリックします。

9.  **\[スナップインの追加と削除\]** ダイアログ ボックスで **\[OK\]** をクリックします。

10. MMC を閉じます。**\[ファイル\]** をクリックして \[終了\] をクリックすると、コンソールの設定に対する変更は保存されません。

    **注意 :** 上記の手順を実行するとコンソールの変更は保存されませんが、新しい管理用テンプレートが Windows XP SP2 から GPO にインポートされます。 テンプレートは、定義された各 GPO にインポートする必要があります。

11. Windows XP SP2 がインストールされているコンピュータにグループ ポリシーを適用する際に使用するすべての GPO について、上記の手順を繰り返します。

    **注意 :** Active Directory と Windows XP SP1 を使用しているネットワーク環境の GPO を更新する場合は、グループ ポリシー管理コンソールを使用することをお勧めします。このコンソールは無償でダウンロードできます。 詳細については、次のサイトを参照してください。

    -   Microsoft Windows Server System Web サイトの「[グループ ポリシー管理コンソールによる企業システムの管理](http://www.microsoft.com/japan/windowsserver2003/gpmc/default.mspx)」http://www.microsoft.com/japan/windowsserver2003/gpmc/default.mspx\#LearnMore

[](#mainsection)[ページのトップへ](#mainsection)

### セキュリティ センターの設定を構成する

セキュリティ センターは、Windows XP SP2 の新しいサービスです。これを利用することで、セキュリティ設定の変更、セキュリティに関する詳細の確認、ユーザーのコンピュータがマイクロソフト推奨の基本的なセキュリティ設定によって最新の状態に保たれていることの確認などの作業を一元的に行うことができます。

Windows ドメイン環境では、グループ ポリシーを使用してセキュリティ センターを有効にすることで、ユーザーのコンピュータを監視できるようになります。これにより、最新のセキュリティ アップデートが適用されていることを確認したり、コンピュータが危険にさらされる可能性がある場合にはユーザーに通知したりすることができます。

セキュリティ センターのサービスはバックグラウンド プロセスとして動作し、ユーザーのコンピュータの次のコンポーネントの状態を確認します。

-   **ファイアウォール**。 セキュリティ センターは、Windows ファイアウォールの有効/無効を確認し、その他のソフトウェア ファイアウォールの有無についても確認します。 その他のファイアウォールの有無を確認するため、セキュリティ センターは、関係するベンダが利用可能にしている特定の Windows Management Instrumentation (WMI) プロバイダについてクエリを行います。

-   **ウイルス対策機能**。 セキュリティ センターは、ウイルス対策ソフトウェアの有無を確認します。 ウイルス対策ソフトウェアの有無を確認するため、セキュリティ センターは、関係するベンダが利用可能にしている特定の WMI プロバイダについてクエリを行います。 情報を入手できる場合は、ソフトウェアが最新の状態であるかどうか、リアルタイム スキャンが有効であるかどうかについても確認します。

-   **自動更新機能**。 セキュリティ センターは、自動更新機能が推奨設定に設定されていることを確認します。この機能が設定されている場合、重要な更新がユーザーのコンピュータに自動的にダウンロードされてインストールされます。 自動更新機能が無効になっている場合や推奨設定に設定されていない場合は、セキュリティ センターによって適切な推奨案が提供されます。

セキュリティ ポリシーに準拠していないコンポーネントが検出された場合、セキュリティ センターは、タスク バーの通知領域に赤いアイコンを表示するとともにログオン時に警告メッセージを表示して、ユーザーに警告します。 表示されるメッセージには、セキュリティ センターのユーザー インターフェイスを開くリンクがあります。このリンクをクリックすると、問題に関する情報と問題解決のための推奨案が表示されます。

セキュリティ センターによって検出されないファイアウォールまたはウイルス対策ソフトウェアを実行している場合は、そのコンポーネントに対する警告が表示されないようにセキュリティ センターを設定できます。

グループ ポリシー設定を使用すると、Windows ドメイン内のコンピュータを対象にしたセキュリティ センター機能を一元的に管理できます。

\[セキュリティ センターを有効にする (ドメイン上のコンピュータのみ)\] ポリシー設定を有効にすると、セキュリティ センターは、基本的なセキュリティ設定 (ファイアウォール、ウイルス対策ソフトウェア、自動更新) を監視し、コンピュータが危険にさらされる可能性がある場合にユーザーに通知します。 既定では、\[セキュリティ センターを有効にする (ドメイン上のコンピュータのみ)\] ポリシー設定は有効にされていません。セキュリティ センターを無効にした場合はこのポリシー設定も無効になり、通知が行われることもセキュリティ センターのステータス セクションが表示されることもありません。

#### このタスクを実行するための要件

-   資格情報 : Domain Admins セキュリティ グループのメンバとして Active Directory ドメイン クライアントである Windows XP SP2 コンピュータにログオンし、**グループ ポリシー オブジェクト**を開く必要があります。

-   ツール : グループ ポリシー オブジェクト エディタ スナップインがインストールされている Microsoft 管理コンソール (MMC)。

##### セキュリティ センターの設定を構成する

この設定を使用すると、Windows XP SP2 を実行しているコンピュータのユーザーは、セキュリティ センターを利用してファイアウォール、ウイルス対策ソフトウェア、および自動更新に関する警告を受け取ることができます。

**セキュリティ センターの設定を構成するには**

1.  Windows XP SP2 デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**mmc**」と入力して、**\[OK\]** をクリックします。

2.  **\[ファイル\]** メニューの **\[スナップインの追加と削除\]** をクリックします。

3.  **\[スタンドアロン\]** タブで **\[追加\]** をクリックします。

4.  **\[利用できるスタンドアロン スナップイン\]** ボックスに表示されるリストの中から **\[グループ ポリシー オブジェクト エディタ\]** を検索してクリックし、**\[追加\]** をクリックします。

5.  **\[グループ ポリシー オブジェクトの選択\]** ダイアログ ボックスで **\[参照\]** をクリックします。

6.  構成するグループ ポリシー オブジェクトをリストから選択します。 **\[OK\]** をクリックし、次に **\[完了\]** をクリックしてグループ ポリシー ウィザードを閉じます。

7.  **\[閉じる\]** をクリックして **\[スタンドアロン スナップインの追加\]** ダイアログ ボックスを終了します。次に、**\[OK\]** をクリックして **\[スナップインの追加と削除\]** ダイアログ ボックスを終了し、管理コンソールに戻ります。

8.  コンソール ツリーで、**\[コンピュータの構成\]**、**\[管理用テンプレート\]**、**\[Windows コンポーネント\]** の順に展開し、**\[セキュリティ センター\]** をクリックします。

    [![](images/Cc700817.adprte02(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte02_big(ja-jp,technet.10).gif)

    **図 2   セキュリティ センターの設定**

    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte02_big(ja-jp,technet.10).gif)

9.  **\[セキュリティ センターを有効にする (ドメイン上のコンピュータのみ)\]** をダブルクリックして、**\[有効\]** をクリックします。次に **\[OK\]** をクリックします。

#### GPUpdate を使用して構成を適用する

GPUpdate ユーティリティを使用すると、セキュリティ設定など Active Directory ベースのグループ ポリシー設定を更新できます。 グループ ポリシーの構成が完了したら、設定のクライアント コンピュータへの適用は、標準の更新サイクルによって行われます。 既定の更新サイクルは 90 分ごとですが、プラスマイナス 30 分まで任意に数値を補正できます。

標準サイクルの合間にグループ ポリシーを更新するには、GPUpdate ユーティリティを使用します。

##### GPUpdate を実行する

**GPUpdate を実行するには**

1.  Windows XP デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。

2.  **\[名前\]** ボックスに「**cmd**」と入力して、**\[OK\]** をクリックします。

    **注意 :** GPUpdate を使用する場合に利用できるオプションの詳細については、次のサイトを参照してください。

    -   [マイクロソフト サポート技術情報 298444「グループ ポリシー更新ユーティリティの説明」](http://go.microsoft.com/fwlink/?linkid=35504)http://go.microsoft.com/fwlink/?linkid=35504

3.  コマンド プロンプトで「**GPUpdate**」と入力し、ENTER キーを押します。

    [![](images/Cc700817.adprte03(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte03_big(ja-jp,technet.10).gif)

    **図 3   コマンド ラインの「GPUpdate」**
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte03_big(ja-jp,technet.10).gif)

4.  コマンド プロンプトを閉じるには、「**Exit**」と入力して ENTER キーを押します。

#### セキュリティ センターの設定が適用されていることを確認する

**セキュリティ センターの設定が適用されていることを確認するには**

1.  Windows XP デスクトップの **\[スタート\]** ボタンをクリックし、**\[コントロール パネル\]** をクリックします。

2.  **\[作業する分野を選びます\]** の **\[セキュリティ センター\]** をクリックします。

3.  セキュリティ センターが起動することを確認します。

    **注意 :** 設定が適用されていない場合は、グループ ポリシーの適用に関してトラブルシューティングを行う必要があります。 グループ ポリシーの適用に関するトラブルシューティングについては、次のサイトを参照してください。

    -   Microsoft Download Center Web サイトの「[Windows Server 2003 のグループ ポリシーのトラブルシューティング (Troubleshooting Group Policy in Windows Server 2003)](http://go.microsoft.com/fwlink/?linkid=35481)」http://go.microsoft.com/fwlink/?linkid=35481 (英語)

[](#mainsection)[ページのトップへ](#mainsection)

### Windows ファイアウォールの設定を構成する

Windows ファイアウォールの設定には、次の 3 種類があります。

-   **\[認証された IPSec のバイパスを許可する\]**。 組織がインターネット プロトコル セキュリティ (IPSec) を使用してトラフィックを保護し、Windows ファイアウォールを有効にしている場合は、この設定が表示されます。

-   **\[ドメイン プロファイル\]**。 コンピュータが、所属しているドメインのドメイン コントローラを含むネットワークに接続されている場合は、この設定が表示されます。

-   **\[標準プロファイル\]**。 コンピュータがネットワークに接続されていない場合 (ラップトップ コンピュータを携帯して移動する場合など) は、この設定が表示されます。

標準プロファイルの設定を行わないと、既定値は変更されません。 ドメイン プロファイルと標準プロファイルの両方を設定し、両方のプロファイルに対して Windows ファイアウォールを有効にすることをお勧めします。 ただし、既にサードパーティ製のホスト ファイアウォール製品を使用している場合は例外です。

サードパーティ製のホスト ファイアウォール製品を使用している場合は、Windows ファイアウォールを無効にすることをお勧めします。

Windows XP SP2、Windows XP SP1、およびサービス パックがインストールされていない Windows XP を実行している各コンピュータが混在する組織のネットワーク全体で、Windows ファイアウォールを無効にする場合は、次のようにグループ ポリシー設定を構成する必要があります。

-   **\[DNS ドメイン ネットワーク上でのインターネット接続ファイアウォールの使用を禁止する\]** を **\[有効\]** に設定します。

-   **\[ドメイン プロファイル\] - \[Windows ファイアウォール: ネットワーク接続をすべて保護する\]** を **\[無効\]** に設定します。

-   **\[標準プロファイル\] - \[Windows ファイアウォール: ネットワーク接続をすべて保護する\]** を **\[無効\]** に設定します。

    **注意 :** 標準プロファイルをこの設定にすると、コンピュータが組織のネットワークに接続されているかどうかに関係なく、Windows ファイアウォールは使用されません。 組織のネットワークでは使用しないが、コンピュータが組織のネットワークに接続されていないときには Windows ファイアウォールを使用するという場合は、この設定を **\[有効\]** に変更してください。

標準プロファイルの設定は、通常、ドメイン プロファイルの設定よりも制限されています。これは、管理対象のドメイン環境でのみ使用されるアプリケーションやサービスが、標準プロファイルの設定に含まれないためです。

GPO では、ドメイン プロファイルと標準プロファイルの両方に Windows ファイアウォール設定の同じ組み合わせが含まれます。 Windows XP SP2 では、ネットワークの決定により適切なプロファイルが適用されます。

**注意 :** ネットワークの決定の詳細については、次のサイトを参照してください。

-   Microsoft TechNet Web サイトの「[ネットワーク関連のグループ ポリシー設定におけるネットワークの決定動作](http://www.microsoft.com/japan/technet/community/columns/cableguy/cg0504.mspx)」http://www.microsoft.com/japan/technet/community/columns/cableguy/cg0504.mspx

ここでは、GPO で可能な Windows ファイアウォールの設定と、エンタープライズ環境の場合の推奨設定について説明します。また、4 種類の設定を有効にする方法についても説明します。

#### このタスクを実行するための要件

-   資格情報 : Domain Admins セキュリティ グループのメンバとして Active Directory ドメイン クライアントである Windows XP SP2 コンピュータにログオンし、既に説明したタスクで変更した**グループ ポリシー オブジェクト**を開く必要があります。

-   ツール : グループ ポリシー オブジェクト エディタ スナップインがインストールされている Microsoft 管理コンソール (MMC)。

    **注意 :** GPO を開くには、グループ ポリシー オブジェクト エディタ スナップインがインストールされている MMC、または \[Active Directory ユーザーとコンピュータ\] コンソールのいずれかを使用します。 Windows XP クライアント コンピュータで \[Active Directory ユーザーとコンピュータ\] コンソールを使用するには、Windows Server 2003 CD から adminpak.msi を実行する必要があります。

##### グループ ポリシーを使用して Windows ファイアウォールの設定を構成する

適切な GPO で Windows ファイアウォールの設定を変更するには、グループ ポリシー オブジェクト エディタ スナップインまたは \[Active Directory ユーザーとコンピュータ\] を使用します。

Windows ファイアウォールの設定の構成が完了したら、次に \[コンピュータの構成\] グループ ポリシーを更新すると Windows ファイアウォールの新しい設定がダウンロードされ、Windows XP SP2 を実行しているコンピュータに適用されます。

**Windows ファイアウォールの設定を構成するには**

1.  Windows XP SP2 デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**mmc**」と入力して、**\[OK\]** をクリックします。

2.  **\[ファイル\]** メニューの **\[スナップインの追加と削除\]** をクリックします。

3.  **\[スタンドアロン\]** タブで **\[追加\]** をクリックします。

4.  **\[利用できるスタンドアロン スナップイン\]** ボックスに表示されるリストの中から **\[グループ ポリシー オブジェクト エディタ\]** を検索してクリックし、**\[追加\]** をクリックします。

5.  **\[グループ ポリシー オブジェクトの選択\]** ダイアログ ボックスで **\[参照\]** をクリックします。

6.  構成するグループ ポリシー オブジェクトを選択して **\[OK\]** をクリックします。次に **\[完了\]** をクリックして、グループポリシー ウィザードを終了します。

7.  **\[閉じる\]** をクリックして **\[スタンドアロン スナップインの追加\]** ダイアログ ボックスを終了します。次に、\[OK\] をクリックして \[スナップインの追加と削除\] ダイアログ ボックスを終了し、管理コンソールに戻ります。

8.  コンソール ツリーで、**\[コンピュータの構成\]**、**\[管理用テンプレート\]**、**\[ネットワーク\]**、**\[ネットワーク接続\]** の順に展開し、**\[Windows ファイアウォール\]** をクリックします。

    [![](images/Cc700817.adprte04(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte04_big(ja-jp,technet.10).gif)

    **図 4   グループ ポリシーの \[Windows ファイアウォール\] のオプション**

    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte04_big(ja-jp,technet.10).gif)

9.  **\[Windows ファイアウォール: 認証された IPSec のバイパスを許可する\]** をダブルクリックします。

    ![](images/Cc700817.adprte05(ja-jp,TechNet.10).gif)

    **図 5   \[認証された IPSec のバイパスを許可する\]**

    表 1 に、\[認証された IPSec のバイパスを許可する\] のオプションを示します。

    **表 1   エンタープライズ環境で使用する \[認証された IPSec のバイパスを許可する\] の設定**
    <p> </p>
    <table style="border:1px solid black;">
    <colgroup>
    <col width="33%" />
    <col width="33%" />
    <col width="33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th style="border:1px solid black;" >設定</th>
    <th style="border:1px solid black;" >説明</th>
    <th style="border:1px solid black;" >注</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>未構成</strong></td>
    <td style="border:1px solid black;">この GPO は、Windows ファイアウォールの現在の構成を変更しません。</td>
    <td style="border:1px solid black;"> </td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>有効</strong></td>
    <td style="border:1px solid black;">ポリシーに記載されているユーザーまたはグループから送信されたもの以外、Windows ファイアウォールは IPSec でセキュリティ保護されたトラフィックを処理しません。</td>
    <td style="border:1px solid black;">ユーザーおよびグループを記載する構文は、SDDL 標準を使用します。 詳細については、次のサイトを参照してください。
    MSDN Web サイトの「<a href="http://go.microsoft.com/fwlink/?linkid=35503">セキュリティ記述子定義言語 (Security Descriptor Definition Language)</a>」http://go.microsoft.com/fwlink/?linkid=35503 (英語)</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>無効</strong></td>
    <td style="border:1px solid black;">Windows ファイアウォールは、IPSec でセキュリティ保護されたトラフィックを処理します。</td>
    <td style="border:1px solid black;"> </td>
    </tr>
    </tbody>
    </table>
  
10. 表 1 を参考にして、**\[有効\]** または **\[無効\]** のいずれかをクリックします。
  
    **注意 :** \[有効\] をクリックした場合は、IPSec でセキュリティ保護されたトラフィックをコンピュータに送信することを許可されているユーザーまたはグループのリストを作成できます。
  
11. **\[OK\]** をクリックします。    
  
12. **\[ドメイン プロファイル\]** または **\[標準プロファイル\]** のいずれかをクリックします。
  
    [![](images/Cc700817.adprte06(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte06_big(ja-jp,technet.10).gif)
  
    **図 6   グループ ポリシーの \[Windows ファイアウォール\] の設定**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte06_big(ja-jp,technet.10).gif)
  
    表 2 に、ドメイン プロファイルおよび標準プロファイルそれぞれの、\[Windows ファイアウォール\] グループ ポリシーの推奨設定を示します。
  
    **表 2   エンタープライズ環境で使用する \[Windows ファイアウォール\] の推奨設定**

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
    <th style="border:1px solid black;" >設定</th>
    <th style="border:1px solid black;" >説明</th>
    <th style="border:1px solid black;" >ドメイン プロファイル</th>
    <th style="border:1px solid black;" >標準プロファイル</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>ネットワーク接続をすべて保護する</strong></td>
    <td style="border:1px solid black;">すべてのネットワーク接続で Windows ファイアウォールを有効にするかどうかを指定します。</td>
    <td style="border:1px solid black;">有効</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>例外を許可しない</strong></td>
    <td style="border:1px solid black;">例外のトラフィックなど、要求していない着信トラフィックをすべてドロップするかどうかを指定します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">有効。ただし、プログラムの例外を構成する必要がある場合を除きます。</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>プログラムの例外を定義する</strong></td>
    <td style="border:1px solid black;">例外のトラフィックを、プログラムのファイル名に基づいて定義します。</td>
    <td style="border:1px solid black;">有効。この定義は、ネットワークで Windows XP SP2 を実行しているコンピュータによって使用されているプログラム (アプリケーションおよびサービス) で構成します。</td>
    <td style="border:1px solid black;">有効。この定義は、ネットワークで Windows XP SP2 を実行しているコンピュータによって使用されているプログラム (アプリケーションおよびサービス) で構成します。</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>ローカル プログラムの例外を許可する</strong></td>
    <td style="border:1px solid black;">プログラムの例外のローカルの構成を許可します。</td>
    <td style="border:1px solid black;">無効。ただし、ローカル管理者がプログラムの例外をローカルで構成できるようにする場合を除きます。</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>リモート管理の例外を許可する</strong></td>
    <td style="border:1px solid black;">ツールを使用したリモート構成を許可します。</td>
    <td style="border:1px solid black;">無効。ただし、MMC スナップインを使用してコンピュータをリモート管理できるようにする場合を除きます。</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>ファイルとプリンタの共有の例外を許可する</strong></td>
    <td style="border:1px solid black;">ファイルとプリンタの共有トラフィックを許可するかどうかを指定します。</td>
    <td style="border:1px solid black;">無効。ただし、Windows XP SP2 を実行しているコンピュータでローカル リソースが共有される場合を除きます。</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>ICMP の例外を許可する</strong></td>
    <td style="border:1px solid black;">許可する ICMP メッセージのタイプを指定します。</td>
    <td style="border:1px solid black;">無効。ただし、ping コマンドを使用してトラブルシューティングを行う場合を除きます。</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>リモート デスクトップの例外を許可する</strong></td>
    <td style="border:1px solid black;">コンピュータでリモート デスクトップ ベースの接続要求を受信できるようにするかどうかを指定します。</td>
    <td style="border:1px solid black;">有効</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>UPnP フレームワークの例外を許可する</strong></td>
    <td style="border:1px solid black;">コンピュータで要求していない UPnP メッセージを受信できるようにするかどうかを指定します。</td>
    <td style="border:1px solid black;">無効</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>通知を禁止する</strong></td>
    <td style="border:1px solid black;">通知を無効にします。</td>
    <td style="border:1px solid black;">無効</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>ログの記録を許可する</strong></td>
    <td style="border:1px solid black;">トラフィックのログの記録とログ ファイル設定の構成を許可します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">未構成</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>マルチキャストまたはブロードキャスト要求に対するユニキャスト応答を禁止する</strong></td>
    <td style="border:1px solid black;">マルチキャストまたはブロードキャスト要求メッセージに対して受信したユニキャスト パケットを破棄します。</td>
    <td style="border:1px solid black;">有効</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>ポートの例外を定義する</strong></td>
    <td style="border:1px solid black;">例外のトラフィックを TCP および UDP に基づいて指定します。</td>
    <td style="border:1px solid black;">無効</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>ローカル ポートの例外を許可する</strong></td>
    <td style="border:1px solid black;">ポートの例外のローカルの構成を許可します。</td>
    <td style="border:1px solid black;">無効</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    </tbody>
    </table>
  
##### ポートの例外を有効にする
  
**ポートの例外を有効にするには**
  
1.  **\[ドメイン プロファイル\]** または **\[標準プロファイル\]** 設定領域のいずれかで、**\[Windows ファイアウォール: ポートの例外を定義する\]** をダブルクリックします。
  
    ![](images/Cc700817.adprte07(ja-jp,TechNet.10).gif)
  
    **図 7   \[Windows ファイアウォール: ポートの例外を定義するのプロパティ\]**
  
2.  **\[有効\]** をクリックして、次に **\[表示\]** をクリックします。    
  
    [![](images/Cc700817.adprte08(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte08_big(ja-jp,technet.10).gif)
  
    **図 8   \[表示するコンテンツ\]**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte08_big(ja-jp,technet.10).gif)
  
3.  **\[追加\]** をクリックします。
  
    ![](images/Cc700817.adprte09(ja-jp,TechNet.10).gif)
  
    **図 9   \[項目の追加\]**
  
4.  ブロックまたは有効にするポート情報を、次の構文を使用して入力します。
  
    **port:transport:scope:status:name**
  
    port はポート番号、transport は TCP または UDP、scope は \* (すべてのシステム) またはこのポートへのアクセスを許可するコンピュータのリスト、status は enabled (有効) または disabled (無効)、name はこのエントリのラベルとして使用するテキスト文字列です。
  
    scope を使用すると、ホスト名、Domain Name System (DNS) の名前、または DNS のサフィックスはサポートされません。 IPv4 アドレスの場合は、ドット付き 10 進数形式のサブネット マスクまたはプレフィックス長を使用して範囲を指定できます。 ドット付き 10 進数形式のサブネット マスクを使用する場合は、IPv4 ネットワーク ID として範囲を指定するか (例 : 10.47.81.0/255.255.255.0)、範囲内の IPv4 アドレスを使用して範囲を指定することができます (例 : 10.47.81.231/255.255.255.0)。 ネットワーク プレフィックス長を使用する場合は、IPv4 ネットワーク ID として範囲を指定するか (例 : 10.47.81.0/24)、範囲内の IPv4 アドレスを使用して範囲を指定することができます (例 : 10.47.81.231/24)。
  
    TCP/IP アドレスの割り当てとサブネット化の詳細については、次のサイトを参照してください。
  
    -   [マイクロソフト サポート技術情報 164015「TCP/IP アドレスの割り当てとサブネット化に関する基礎知識」](http://go.microsoft.com/fwlink/?linkid=36370)http://go.microsoft.com/fwlink/?linkid=36370
  
    **注意 :** ソースのリストの各エントリの間にスペースやその他の無効な文字を指定すると、scope の指定は無視され、無効に設定した場合と同様に機能します。 変更内容を保存する前に、scope 構文を再確認してください。
  
    この例では、ポートの例外として WebTest という名前を使用し、TCP ポート 80 をすべての接続に対して有効にします。
  
5.  **\[OK\]** をクリックして **\[項目の追加\]** を閉じます。
  
    [![](images/Cc700817.adprte10(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte10_big(ja-jp,technet.10).gif)
  
    **図 10   \[表示するコンテンツ\]**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte10_big(ja-jp,technet.10).gif)
  
6.  **\[OK\]** をクリックして **\[表示するコンテンツ\]** を閉じます。
  
7.  **\[閉じる\]** をクリックして、**\[Windows ファイアウォール: ポートの例外を定義するのプロパティ\]** を閉じます。
  
    **注意 :\[例外を許可しない\]** を選択すると、すべてのポートの例外が無視されます。
  
##### プログラムの例外を有効にする
  
**プログラムの例外を有効にするには**
  
1.  **\[ドメイン プロファイル\]** または **\[標準プロファイル\]** 設定領域のいずれかで、**\[Windows ファイアウォール: プログラムの例外を定義する\]** をダブルクリックします。
  
    ![](images/Cc700817.adprte11(ja-jp,TechNet.10).gif)
  
    **図 11   \[Windows ファイアウォール: プログラムの例外を定義するのプロパティ\]**
  
2.  **\[有効\]** をクリックして、次に **\[表示\]** をクリックします。
  
    [![](images/Cc700817.adprte12(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte12_big(ja-jp,technet.10).gif)
  
    **図 12   \[表示するコンテンツ\]**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte12_big(ja-jp,technet.10).gif)
  
3.  **\[追加\]** をクリックします。
  
    ![](images/Cc700817.adprte13(ja-jp,TechNet.10).gif)
  
    **図 13   \[項目の追加\]**
  
4.  ブロックまたは有効にするプログラム情報を、次の構文を使用して入力します。
  
    **path:scope:status:name**
  
    path はプログラムのパスとファイル名、scope は \* (すべてのシステム) またはこのプログラムへのアクセスが許可されているコンピュータのリスト、status は enabled (有効) または disabled (無効)、name はこのエントリのラベルとして使用するテキスト文字列です。
  
    この例では、Windows Messenger をすべての接続に対して有効にします。
  
    TCP/IP アドレスの割り当てとサブネット化の詳細については、次のサイトを参照してください。
  
    -   [マイクロソフト サポート技術情報 164015「TCP/IP アドレスの割り当てとサブネット化に関する基礎知識」](http://go.microsoft.com/fwlink/?linkid=36370)http://go.microsoft.com/fwlink/?linkid=36370
  
5.  **\[OK\]** をクリックして **\[項目の追加\]** を閉じます。
  
    [![](images/Cc700817.adprte14(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte14_big(ja-jp,technet.10).gif)
  
    **図 14   \[表示するコンテンツ\]**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte14_big(ja-jp,technet.10).gif)
  
6.  **\[OK\]** をクリックして **\[表示するコンテンツ\]** を閉じます。
  
7.  **\[閉じる\]** をクリックして、**\[Windows ファイアウォール: プログラムの例外を定義するのプロパティ\]** を閉じます。
  
##### 基本的な ICMP のオプションを構成する
  
ICMP の詳細については、次のサイトを参照してください。
  
-   「[Internet Control Message Protocol (ICMP)](http://support.microsoft.com/kb/170292/ja)」 (英語)
  
**基本的な ICMP のオプションを構成するには**
  
1.  **\[ドメイン プロファイル\]** または **\[標準プロファイル\]** 設定領域のいずれかで、**\[Windows ファイアウォール: ICMP の例外を許可する\]** をダブルクリックします。
  
2.  **\[有効\]** をクリックします。
  
    ![](images/Cc700817.adprte15(ja-jp,TechNet.10).gif)
  
    **図 15   \[Windows ファイアウォール: ICMP の例外を許可するのプロパティ\]**
  
3.  有効にする ICMP の例外 (複数可) のチェック ボックスをオンにします。 この例では、\[エコー要求の着信を許可する\] チェック ボックスをオンにしています。
  
4.  **\[OK\]** をクリックして、**\[Windows ファイアウォール: ICMP の例外を許可するのプロパティ\]** を閉じます。
  
##### ドロップされたパケットと成功した接続のログを記録する
  
**ドロップされたパケットと成功した接続のログを記録するには**
  
1.  **\[ドメイン プロファイル\]** または **\[標準プロファイル\]** 設定領域のいずれかで、**\[Windows ファイアウォール: ログの記録を許可する\]** をダブルクリックします。
  
    ![](images/Cc700817.adprte16(ja-jp,TechNet.10).gif)
  
    **図 16   \[Windows ファイアウォール: ログの記録を許可するのプロパティ\]**
  
2.  **\[有効\]** をクリックして、**\[ドロップされたパケットのログをとる\]** チェック ボックスと **\[成功した接続のログをとる\]** チェック ボックスをオンにします。次にログ ファイルのパスと名前を入力し、**\[OK\]** をクリックします。
  
    **注意 :** ログ ファイルの保存先はセキュリティ保護して、ログが削除されたり改ざんされたりしないようにしてください。
  
3.  グループ ポリシー オブジェクト エディタを閉じます。
  
4.  コンソールの設定を保存するかどうかを確認するメッセージが表示されたら、**\[いいえ\]** をクリックします。
  
#### GPUpdate を使用して構成を適用する
  
GPUpdate ユーティリティを使用すると、セキュリティ設定など Active Directory ベースのグループ ポリシー設定を更新できます。 グループ ポリシーの構成が完了したら、設定のクライアント コンピュータへの適用は、標準の更新サイクルによって行われます。 既定の更新サイクルは 90 分ごとですが、プラスマイナス 30 分まで任意に数値を補正できます。
  
標準サイクルの合間にグループ ポリシーを更新するには、GPUpdate ユーティリティを使用します。
  
##### GPUpdate を実行する
  
**GPUpdate を実行するには**
  
1.  Windows XP デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。
  
2.  **\[名前\]** ボックスに「**cmd**」と入力して、**\[OK\]** をクリックします。
  
    **注意 :** GPUpdate を使用する場合に利用できるオプションの詳細については、次のサイトを参照してください。
  
    -   [マイクロソフト サポート技術情報 298444「グループ ポリシー更新ユーティリティの説明」](http://go.microsoft.com/fwlink/?linkid=35504)http://go.microsoft.com/fwlink/?linkid=35504
  
3.  コマンド プロンプトで「**GPUpdate**」と入力し、ENTER キーを押します。
  
    [![](images/Cc700817.adprte17(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte17_big(ja-jp,technet.10).gif)
  
    **図 17   コマンド ラインの「GPUpdate」**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte17_big(ja-jp,technet.10).gif)
  
4.  コマンド プロンプトを閉じるには、「Exit」と入力して **ENTER** キーを押します。
  
#### Windows ファイアウォールの設定が適用されていることを確認する
  
**注意 :** グループ ポリシーを使用して Windows ファイアウォールを構成した場合、設定によっては、ローカル管理者が構成の一部を変更できないことがあります。 \[Windows ファイアウォール\] ダイアログ ボックスの一部のタブとオプションは、ユーザーのローカル コンピュータでは使用できません。
  
**Windows ファイアウォールの設定が適用されていることを確認するには**
  
1.  **\[セキュリティ センター\]** をクリックし、**\[セキュリティの設定の管理\]** の **\[Windows ファイアウォール\]** をクリックします。
  
2.  **\[全般\]**、**\[例外\]**、**\[詳細設定\]** の各タブをクリックして、コンピュータの Windows ファイアウォールに必要な構成が適用されていることを確認します。次に **\[OK\]** をクリックして、\[Windows ファイアウォール\] を閉じます。
  
    **注意 :** 設定が適用されていない場合は、グループ ポリシーの適用に関してトラブルシューティングを行う必要があります。 グループ ポリシーの適用に関するトラブルシューティングについては、次のサイトを参照してください。
  
    -   Microsoft Download Center Web サイトの「[Windows Server 2003 のグループ ポリシーのトラブルシューティング (Troubleshooting Group Policy in Windows Server 2003)](http://go.microsoft.com/fwlink/?linkid=35481)」http://go.microsoft.com/fwlink/?linkid=35481 (英語)
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### Internet Explorer のセキュリティ設定を構成する
  
Windows XP SP2 では、新しいグループ ポリシー設定を使用して、コンピュータとユーザーの両方の構成について Internet Explorer のすべてのセキュリティ設定を管理できます。
  
Windows XP SP2 では、主要なポリシー設定領域として次の 2 つを使用できます。
  
-   セキュリティの機能
  
-   URL 動作
  
\[セキュリティの機能\] ポリシー設定を使用すると、Internet Explorer のセキュリティに影響を与える可能性がある特定のシナリオを管理できます。 ほとんどの場合、特定の動作の防止が必要となるため、セキュリティの機能は必ず有効にする必要があります。 たとえば、インターネット ゾーンではなくローカル コンピュータ ゾーンで実行された悪意のあるコードが、自身のアクセス許可の昇格を試みる可能性があります。 このような攻撃を防ぐには、\[ゾーン昇格からの保護\] ポリシー設定を使用します。
  
それぞれの \[セキュリティの機能\] ポリシー設定に対して、セキュリティの機能の動作を制御するポリシー設定を次の手段によって指定できます。
  
-   Internet Explorer のプロセス
  
-   定義されたプロセスのリスト
  
-   すべてのプロセス (プロセスの開始場所に無関係)
  
Uniform Resource Locator (URL) 動作は、Java アプレットや ActiveX コントロールの実行など、ローカル コンピュータにセキュリティ上の問題が発生する場合がある、ブラウザの可能な動作を参照します。 URL 動作は、URL が存在するセキュリティ ゾーン内の機能に対して実行するアクションを特定する、レジストリ内のセキュリティ設定に対応します。 URL 動作の設定には、有効、無効、プロンプト、および必要に応じてその他の設定があります。
  
Internet Explorer で URL 動作のセキュリティ管理を行うには、**\[インターネット コントロール パネル\]** の下位にある新しい \[セキュリティ ページ\] グループ ポリシー設定を使用します。 グループ ポリシーを使用して URL 動作のセキュリティを制御することで、組織内のすべてのユーザーとコンピュータを対象にした Internet Explorer の標準の構成を作成できます。
  
セキュリティを提供する場合は、セキュリティ ゾーンのテンプレートのポリシー設定を使用して、すべての URL ゾーンのポリシーを有効にできます。 それぞれの URL 動作のテンプレートのポリシー設定に対して、次に挙げるセキュリティ レベルのいずれかを指定できます。
  
-   **\[低\]**。 このセキュリティ レベルは通常、ユーザーが完全に信頼している Web サイトを含む URL セキュリティ ゾーンに使用されます。 信頼済みサイト ゾーンの既定のセキュリティ レベルです。
  
-   **\[中低\]**。 このセキュリティ レベルは、ユーザーのコンピュータやデータに損害を与えることはほとんどない Web サイトを含む URL セキュリティ ゾーンに使用されます。 イントラネット ゾーンの既定のセキュリティ レベルです。
  
-   **\[中\]**。 このセキュリティ レベルは、信頼済みの Web サイトでも信頼されていない Web サイトでもない Web サイトを含む URL セキュリティ ゾーンに使用されます。 インターネット ゾーンの既定のセキュリティ レベルです。
  
-   **\[高\]**。 このセキュリティ レベルは、ユーザーのコンピュータやデータに損害を与える可能性が大きい Web サイトを含む URL セキュリティ ゾーンに使用されます。 制限付きサイト ゾーンの既定のセキュリティ レベルです。
  
セキュリティの機能の制御の詳細については、次のサイトを参照してください。
  
-   Microsoft TechNet Web サイトの「[Microsoft Windows XP Service Pack 2 での機能の変更点](http://www.microsoft.com/downloads/details.aspx?familyid=77b9c4e0-9812-42ee-a973-de5b8f23951c&displaylang=ja)」http://www.microsoft.com/downloads/details.aspx?FamilyID=77b9c4e0-9812-42ee-a973-de5b8f23951c&displaylang=ja
  
#### このタスクを実行するための要件
  
-   資格情報 : Domain Admins セキュリティ グループのメンバとして Active Directory ドメイン クライアントである Windows XP SP2 コンピュータにログオンし、**グループ ポリシー オブジェクト**を開く必要があります。
  
-   ツール : グループ ポリシー オブジェクト エディタ スナップインがインストールされている Microsoft 管理コンソール (MMC)。
  
##### Internet Explorer のセキュリティ設定を構成する
  
**Internet Explorer の設定を構成するには**
  
1.  Windows XP SP2 デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**mmc**」と入力して、**\[OK\]** をクリックします。
  
2.  **\[ファイル\]** メニューの **\[スナップインの追加と削除\]** をクリックします。
  
3.  **\[スタンドアロン\]** タブで **\[追加\]** をクリックします。
  
4.  **\[利用できるスタンドアロン スナップイン\]** ボックスに表示されるリストの中から **\[グループ ポリシー オブジェクト エディタ\]** を検索してクリックし、**\[追加\]** をクリックします。
  
5.  **\[グループ ポリシー オブジェクトの選択\]** ダイアログ ボックスで **\[参照\]** をクリックします。
  
6.  構成するグループ ポリシー オブジェクトを選択して **\[OK\]** をクリックします。次に **\[完了\]** をクリックして、グループポリシー ウィザードを終了します。
  
7.  **\[閉じる\]** をクリックして **\[スタンドアロン スナップインの追加\]** ダイアログ ボックスを終了します。次に、\[OK\] をクリックして \[スナップインの追加と削除\] ダイアログ ボックスを終了し、管理コンソールに戻ります。
  
8.  コンソール ツリーで、**\[コンピュータの構成\]**、**\[管理用テンプレート\]**、**\[Windows コンポーネント\]**、**\[Internet Explorer\]** の順に展開し、**\[セキュリティの機能\]** をクリックします。
  
    [![](images/Cc700817.adprte18(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte18_big(ja-jp,technet.10).gif)
  
    **図 18   \[Internet Explorer\] グループ ポリシーのセキュリティ設定**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte18_big(ja-jp,technet.10).gif)
  
9.  表 3 を参考にして、Internet Explorer のセキュリティ設定を構成します。
  
    **表 3   Internet Explorer の \[セキュリティの機能\] の設定**
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
    <th style="border:1px solid black;" >設定</th>
    <th style="border:1px solid black;" >説明</th>
    <th style="border:1px solid black;" >既定の構成</th>
    <th style="border:1px solid black;" >エンタープライズ環境で使用する場合の推奨構成</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>バイナリ ビヘイビアのセキュリティの制限</strong></td>
    <td style="border:1px solid black;">[バイナリ ビヘイビアのセキュリティの制限] 設定を禁止するか許可するかを制御します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">組織の許可されたビヘイビアを [管理者によって許可されたビヘイビア] リストに追加します。その際には、#package#behavior と表記します。</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>MK プロトコル セキュリティの制限</strong></td>
    <td style="border:1px solid black;">MK プロトコルを使用不可にすることで危険を回避します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>ローカル コンピュータ ゾーンのロックダウン セキュリティ</strong></td>
    <td style="border:1px solid black;">ローカル コンピュータ ゾーンを使用して悪意のある HTML コードを読み込む攻撃のリスクを軽減します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>整合性のある MIME 処理</strong></td>
    <td style="border:1px solid black;">Web サーバーから送信されるすべてのファイル タイプの情報に一貫性があることを Internet Explorer が要求するかどうかを決定します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>MIME スニッフィングの安全機能</strong></td>
    <td style="border:1px solid black;">Internet Explorer MIME スニッフィングにより、特定のタイプのファイルがより危険性の高いタイプのファイルに昇格しないようにするかどうかを決定します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>オブジェクト キャッシュ保護</strong></td>
    <td style="border:1px solid black;">ユーザーが同じドメイン内で移動した場合や新しいドメインに移動した場合に、オブジェクトへの参照をアクセス可能にするかどうかを定義します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>スクリプト化されたウィンドウのセキュリティ制限</strong></td>
    <td style="border:1px solid black;">ポップアップ ウィンドウを制限し、タイトル バーやステータス バーが表示されない、またはその他のタイトル バーやステータス バーがわかりにくいウィンドウをスクリプトで表示できなくします。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>ゾーン昇格からの保護</strong></td>
    <td style="border:1px solid black;">ローカル コンピュータのセキュリティ ゾーンを保護できます。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>情報バー</strong></td>
    <td style="border:1px solid black;">ファイルやコードのインストールが制限されている場合に、Internet Explorer のプロセスを示す情報バーを表示するかどうかを管理します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>ActiveX のインストールの制限</strong></td>
    <td style="border:1px solid black;">Internet Explorer のプロセスを示す ActiveX® コントロールのインストールのプロンプトをブロックできます。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>ファイル ダウンロードの制限</strong></td>
    <td style="border:1px solid black;">ユーザーが開始したものではないファイル ダウンロード プロンプトをブロックできます。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">すべてのプロセスに対して有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>アドオン管理</strong></td>
    <td style="border:1px solid black;">[アドオンの一覧] ポリシー設定に表示されていない Internet Explorer アドオンを拒否することができます。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">[アドオンの一覧] で明確に許可されていない限り、すべてのアドオンに対して有効です。</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>ネットワーク プロトコルのロックダウン</strong></td>
    <td style="border:1px solid black;">インターネット、イントラネット、信頼済みサイト、制限付きサイト、およびローカル コンピュータのセキュリティ ゾーンに対して、制限付きプロトコルのリストを指定します。</td>
    <td style="border:1px solid black;">未構成</td>
    <td style="border:1px solid black;">各セキュリティ ゾーンごとに、特定のプロトコルを有効にします。</td>
    </tr>
    </tbody>
    </table>
  
10. **\[インターネット コントロール パネル\]** を展開します。
  
    [![](images/Cc700817.adprte19(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte19_big(ja-jp,technet.10).gif)
  
    **図 19   \[インターネット コントロール パネル\] の設定**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte19_big(ja-jp,technet.10).gif)
  
11. 各設定を有効にして、一覧表示されている Internet Explorer の構成ページにユーザーがアクセスできないようにします。 それには、各設定をダブルクリックして、**\[有効\]**、**\[OK\]** の順にクリックします。
  
12. **\[セキュリティ ページ\]** を展開します。
  
    [![](images/Cc700817.adprte20(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte20_big(ja-jp,technet.10).gif)
  
    **図 20   \[インターネット コントロール パネル\] の \[セキュリティ ページ\] の設定**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte20_big(ja-jp,technet.10).gif)
  
13. セキュリティ ゾーンを構成するには 2 とおりの方法があります。テンプレートを使用するか、ゾーンごとに各設定を選択します。  
    次のいずれかの手順を実行します。
  
    -   表 4 を参考にしてゾーンのテンプレートを使用し、各セキュリティ ゾーンを構成します。 各テンプレート オプションをダブルクリックして、**\[有効\]** をクリックします。
  
        または
  
    -   表 5 を参考にして各セキュリティ ゾーンを個別に構成します。  <br/><br/>
          **表 4   \[インターネット コントロール パネル\] のセキュリティ ゾーン別設定**
        <p> </p>
        <table style="border:1px solid black;">
        <colgroup>
        <col width="33%" />
        <col width="33%" />
        <col width="33%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" >設定</th>
        <th style="border:1px solid black;" >推奨構成</th>
        <th style="border:1px solid black;" >推奨レベル</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>インターネット ゾーンのテンプレート</strong></td>
        <td style="border:1px solid black;">有効</td>
        <td style="border:1px solid black;">中</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>イントラネット ゾーンのテンプレート</strong></td>
        <td style="border:1px solid black;">有効</td>
        <td style="border:1px solid black;">中低</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>信頼済みサイトのテンプレート</strong></td>
        <td style="border:1px solid black;">有効</td>
        <td style="border:1px solid black;">低</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>制限付きサイト ゾーンのテンプレート</strong></td>
        <td style="border:1px solid black;">有効</td>
        <td style="border:1px solid black;">高</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>ローカル コンピュータ ゾーンのテンプレート</strong></td>
        <td style="border:1px solid black;">有効</td>
        <td style="border:1px solid black;">低</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>ロックダウンされたローカル コンピュータ ゾーンのテンプレート</strong></td>
        <td style="border:1px solid black;">有効</td>
        <td style="border:1px solid black;">高</td>
        </tr>
        </tbody>
        </table>

        **表 5   \[インターネット コントロール パネル\] のセキュリティ ゾーン別設定**
        <p> </p>
        <table style="border:1px solid black;">
        <colgroup>
        <col width="33%" />
        <col width="33%" />
        <col width="33%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th style="border:1px solid black;" >設定</th>
        <th style="border:1px solid black;" >説明</th>
        <th style="border:1px solid black;" >既定の構成</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>署名済み ActiveX コントロールのダウンロード</strong></td>
        <td style="border:1px solid black;">HTML ページに署名済み ActiveX コントロールが含まれている場合、その HTML ページの URL ゾーンからの ActiveX コントロールのダウンロードを管理します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>未署名の ActiveX コントロールのダウンロード</strong></td>
        <td style="border:1px solid black;">HTML ページに未署名の ActiveX コントロールが含まれている場合、その HTML ページの URL ゾーンからの ActiveX コントロールのダウンロードを管理します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>スクリプトを実行しても安全だとマークされていない ActiveX コントロールの初期化とスクリプトの実行</strong></td>
        <td style="border:1px solid black;">ゾーン内の HTML ページからの ActiveX コントロールとプラグインの実行を管理します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>ActiveX コントロールとプラグインの実行</strong></td>
        <td style="border:1px solid black;">URL セキュリティ ゾーン内のページに対する、ActiveX コントロール オブジェクトの安全性を無視するか、強制するかを決定します。 オブジェクトの安全性を無視できるのは、ゾーン内のページで連携する可能性があるすべての ActiveX コントロールとスクリプトが信頼でき、セキュリティに違反しない場合のみです。 これは、URLACTION_ACTIVEX_OVERRIDE_DATA_SAFETY と URLACTION_ACTIVEX_OVERRIDE_SCRIPT_SAFETY を集約したものです。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>アクティブ スクリプトの許可</strong></td>
        <td style="border:1px solid black;">URL セキュリティ ゾーン内のページ上のスクリプト コードを実行するかどうかを決定します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>Java アプレットのスクリプト</strong></td>
        <td style="border:1px solid black;">Java アプレットのプロパティ、メソッド、およびイベントがスクリプトに公開されている場合、URL セキュリティ ゾーン内の HTML ページ上のスクリプト コードで Java アプレットを使用できるようにするかどうかを決定します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>スクリプトを実行しても安全だとマークされている ActiveX コントロールのスクリプトの実行</strong></td>
        <td style="border:1px solid black;">安全な ActiveX コントロールのスクリプトを使用できるかどうかを決定します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>ドメイン間でのデータ ソースのアクセス</strong></td>
        <td style="border:1px solid black;">リソースからドメインのデータ ソースにアクセスできるようにするかどうかを決定します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>スクリプトによる貼り付け処理の許可</strong></td>
        <td style="border:1px solid black;">スクリプトで貼り付け処理をできるようにするかどうかを決定します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>暗号化されていないフォーム データの送信</strong></td>
        <td style="border:1px solid black;">URL セキュリティ ゾーン内のページ上の HTML フォーム、またはゾーン内のサーバーに送信された HTML フォームを許可するかどうかを決定します。 これは、URLACTION_HTML_SUBMIT_FORMS_FROM フラグと URLACTION_HTML_SUBMIT_FORMS_TO フラグを集約したものです。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>フォントのダウンロードの許可</strong></td>
        <td style="border:1px solid black;">HTML フォントのダウンロードを許可するかどうかを決定します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="even">
        <td style="border:1px solid black;"><strong>UserData の常設</strong></td>
        <td style="border:1px solid black;">ユーザー データの常設を有効にするかどうかを決定します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        <tr class="odd">
        <td style="border:1px solid black;"><strong>異なるドメイン間のサブフレームの移動</strong></td>
        <td style="border:1px solid black;">サブフレームの異なるドメイン間での移動を許可するかどうかを決定します。</td>
        <td style="border:1px solid black;">未構成</td>
        </tr>
        </tbody>
        </table>
  
#### GPUpdate を使用して構成を適用する
  
GPUpdate ユーティリティを使用すると、セキュリティ設定など Active Directory ベースのグループ ポリシー設定を更新できます。 グループ ポリシーの構成が完了したら、設定のクライアント コンピュータへの適用は、標準の更新サイクルによって行われます。 既定の更新サイクルは 90 分ごとですが、プラスマイナス 30 分まで任意に数値を補正できます。
  
標準サイクルの合間にグループ ポリシーを更新するには、GPUpdate ユーティリティを使用します。
  
##### GPUpdate を実行する
  
**GPUpdate を実行するには**
  
1.  Windows XP デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。
  
2.  **\[名前\]** ボックスに「**cmd**」と入力して、**\[OK\]** をクリックします。
  
    **注意 :** GPUpdate を使用する場合に利用できるオプションの詳細については、次のサイトを参照してください。
  
    -   [マイクロソフト サポート技術情報 298444「グループ ポリシー更新ユーティリティの説明」](http://go.microsoft.com/fwlink/?linkid=35504)http://go.microsoft.com/fwlink/?linkid=35504
  
3.  コマンド プロンプトで「**GPUpdate**」と入力し、ENTER キーを押します。
  
    [![](images/Cc700817.adprte21(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte21_big(ja-jp,technet.10).gif)
  
    **図 21   コマンド ラインの「GPUpdate」**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte21_big(ja-jp,technet.10).gif)
  
4.  コマンド プロンプトを閉じるには、「Exit」と入力して **ENTER** キーを押します。
  
#### Internet Explorer のセキュリティ設定が適用されていることを確認する
  
**注意 :** グループ ポリシーを使用して Internet Explorer を構成した場合、設定によっては、ローカル管理者が構成の一部を変更できないことがあります。 ダイアログ ボックスの一部のタブとオプションは、ユーザーのローカル コンピュータでは使用できません。
  
##### Internet Explorer のセキュリティ設定が適用されていることを確認する
  
**Internet Explorer の設定が適用されていることを確認するには**
  
1.  **\[セキュリティ センター\]** をクリックし、**\[セキュリティの設定の管理\]** の **\[インターネット オプション\]** をクリックします。
  
2.  **\[セキュリティ\]**、**\[プライバシー\]**、**\[詳細設定\]** の各タブをクリックして、コンピュータの Internet Explorer に必要な構成が適用されていることを確認します。次に **\[OK\]** をクリックして、\[インターネットのプロパティ\] を閉じます。
  
    **注意 :** 設定が適用されていない場合は、グループ ポリシーの適用に関してトラブルシューティングを行う必要があります。 グループ ポリシーの適用に関するトラブルシューティングについては、次のサイトを参照してください。
  
    -   Microsoft Download Center Web サイトの「[Windows Server 2003 のグループ ポリシーのトラブルシューティング (Troubleshooting Group Policy in Windows Server 2003)](http://go.microsoft.com/fwlink/?linkid=35481)」http://go.microsoft.com/fwlink/?linkid=35481 (英語)
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### インターネット通信の管理の設定を構成する
  
Windows XP SP2 には、Windows XP SP2 のコンポーネントがインターネットと通信を行う方法を制御することを主な目的とした、新しいグループ ポリシー設定が用意されています。 このグループ ポリシー設定を使用すると、次の操作の使用可/不可の設定を管理できます。
  
-   オンラインでのプリントの注文
  
-   オンライン記憶域の使用
  
-   Web への公開
  
Windows XP SP2 では、オンラインでのプリントの注文 (**オンラインでのプリントの注文ウィザード**)、オンライン記憶域を提供するサービスへのサインアップ (**ネットワーク プレースの追加ウィザード**)、またはブラウザで表示可能なファイルの公開 (**Web 発行ウィザード**) といった作業についても、その他のタスクと同様、エクスプローラでタスクをクリックして実行することができます。 タスクまたはウィザードでは、このような作業を実施するサービス プロバイダの名前と URL を、ローカルに保存されているリスト (レジストリ内) およびマイクロソフト Web サイトに保存されているリストから取得します。 既定では、レジストリ内のリストに記載されているプロバイダにマイクロソフト Web サイトのリストに記載されているプロバイダが追加されて表示されます。
  
次のグループ ポリシー設定を使用すると、これらのウィザードとタスクの動作を制御し、これらのコンポーネントがインターネットと通信を行う方法を制御することができます。
  
-   **\[ファイルとフォルダのタスクから \[Web に公開する\] を削除する\]**。 このポリシー設定では、Web に項目を公開する場合に必要なタスクを、Windows フォルダの \[ファイルとフォルダのタスク\] から実行できるかどうかを指定します。 タスクには、\[このファイルを Web に公開する\]、\[このフォルダを Web に公開する\]、および \[選択した項目を Web に発行する\] があります。
  
-   **\[Web 発行およびオンライン注文ウィザードのインターネット ダウンロードをオフにする\]**。 このポリシー設定では、**Web 発行ウィザード**、**ネットワーク プレースの追加ウィザード**、および**オンラインでのプリントの注文ウィザード**で使用されるプロバイダのリストをダウンロードする必要があるかどうかを指定します。 既定では、レジストリ内のリストに指定されているプロバイダに、Windows Web サイトからダウンロードされたプロバイダが追加されて表示されます。
  
-   **\[画像のタスクから \[オンラインでプリントを注文する\] を削除する\]**。 このポリシー設定では、\[オンラインでプリントを注文する\] タスクを、Windows フォルダの \[画像のタスク\] から実行できるかどうかを指定します。 この設定を有効にすると、オンラインでのプリントの注文ウィザードが無効になります。
  
上記のポリシー設定は、\[ユーザーの構成\] と \[コンピュータの構成\] の両方で使用できます。
  
ネットワーク プレースの追加ウィザードと Web 発行ウィザードの使用方法については、次のサイトを参照してください。
  
-   Microsoft TechNet Web サイトの「[管理環境での Windows XP Professional Service Pack 2 の使用: インターネットとの通信の制御 (Using Windows XP Professional with Service Pack 2 in a Managed Environment: Controlling Communication with the Internet)](http://go.microsoft.com/fwlink/?linkid=35489)」http://go.microsoft.com/fwlink/?LinkId=35489 (英語)
  
#### このタスクを実行するための要件
  
-   資格情報 : Domain Admins セキュリティ グループのメンバとして Active Directory ドメイン クライアントである Windows XP SP2 コンピュータにログオンし、**グループ ポリシー オブジェクト**を開く必要があります。
  
-   ツール : グループ ポリシー オブジェクト エディタ スナップインがインストールされている Microsoft 管理コンソール (MMC)。
  
##### インターネット通信の管理の設定を構成する
  
**インターネット通信の管理の設定を構成するには**
  
1.  Windows XP SP2 デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**mmc**」と入力して、**\[OK\]** をクリックします。
  
2.  **\[ファイル\]** メニューの **\[スナップインの追加と削除\]** をクリックします。
  
3.  **\[スタンドアロン\]** タブで **\[追加\]** をクリックします。
  
4.  **\[利用できるスタンドアロン スナップイン\]** ボックスに表示されるリストの中から **\[グループ ポリシー オブジェクト エディタ\]** を検索してクリックし、**\[追加\]** をクリックします。
  
5.  **\[グループ ポリシー オブジェクトの選択\]** ダイアログ ボックスで **\[参照\]** をクリックします。
  
6.  構成するグループ ポリシー オブジェクトを選択して **\[OK\]** をクリックします。次に **\[完了\]** をクリックして、グループポリシー ウィザードを終了します。
  
7.  **\[閉じる\]** をクリックして **\[スタンドアロン スナップインの追加\]** ダイアログ ボックスを終了します。次に、\[OK\] をクリックして \[スナップインの追加と削除\] ダイアログ ボックスを終了し、管理コンソールに戻ります。
  
8.  コンソール ツリーで、**\[コンピュータの構成\]**、**\[管理用テンプレート\]**、**\[システム\]** の順に展開し、**\[インターネット通信の管理\]** をクリックします。
  
    [![](images/Cc700817.adprte22(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte22_big(ja-jp,technet.10).gif)
  
    **図 22   \[インターネット通信の管理\] の設定**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte22_big(ja-jp,technet.10).gif)
  
9.  **\[インターネット通信を制限する\]** 設定を **\[無効\]** に構成して \[インターネット通信の設定\] の下位のすべての設定を無効するか、**\[有効\]** に構成して \[インターネット通信の設定\] の下位のすべての設定を有効にします。
  
10. 各設定を個別に構成するには、**\[インターネット通信の設定\]** を展開し、表 6 を参考にして設定を構成します。
  
    **表 6   \[インターネット通信の設定\] の推奨設定**
    <p> </p>
    <table style="border:1px solid black;">
    <colgroup>
    <col width="33%" />
    <col width="33%" />
    <col width="33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th style="border:1px solid black;" >設定</th>
    <th style="border:1px solid black;" >説明</th>
    <th style="border:1px solid black;" >推奨設定</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>ファイルとフォルダのタスクから [Web に公開する] を削除する</strong></td>
    <td style="border:1px solid black;">[このファイルを Web に公開する]、[このフォルダを Web に公開する]、および [選択した項目を Web に発行する] の各タスクを、Windows フォルダの [ファイルとフォルダのタスク] から実行できるかどうかを指定します。</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>Web 発行およびオンライン注文ウィザードのインターネット ダウンロードをオフにする</strong></td>
    <td style="border:1px solid black;">Web 発行ウィザードおよびオンラインでの注文ウィザードで、プロバイダのリストのダウンロードが実行されるかどうかを制御します。</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>Windows Messenger カスタマ エクスペリエンス向上プログラムをオフにする</strong>
    </td>
    <td style="border:1px solid black;">Windows Messenger ソフトウェアおよびサービスの使用方法に関する匿名情報を収集するかどうかを指定します。</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>検索コンパニオンのコンテンツ ファイルの更新をオフにする</strong></td>
    <td style="border:1px solid black;">ローカル検索およびインターネット検索時に、検索コンパニオンのコンテンツのアップデートを自動的にダウンロードするかどうかを指定します。</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>HTTP 経由の印刷をオフにする</strong></td>
    <td style="border:1px solid black;">このクライアントの HTTP 経由の印刷を無効にすることができます。</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="even">
    <td style="border:1px solid black;"><strong>プリンタ ドライバの HTTP 経由でのダウンロードをオフにする</strong></td>
    <td style="border:1px solid black;">HTTP 経由でプリンタ ドライバ パッケージがダウンロードされるようにするかどうかを制御します。</td>
    <td style="border:1px solid black;">有効</td>
    </tr>
    <tr class="odd">
    <td style="border:1px solid black;"><strong>Windows Update でのデバイス ドライバの検索をオフにする</strong></td>
    <td style="border:1px solid black;">ローカルのデバイス ドライバが存在しない場合に、Windows Update でデバイス ドライバを検索するかどうかを指定します。</td>
    <td style="border:1px solid black;">無効</td>
    </tr>
    </tbody>
    </table>
  
    **注意 :** 表 6 には、インターネット通信の推奨設定がすべて記載されています。
  
#### GPUpdate を使用して構成を適用する
  
GPUpdate ユーティリティを使用すると、セキュリティ設定など Active Directory ベースのグループ ポリシー設定を更新できます。 グループ ポリシーの構成が完了したら、設定のクライアント コンピュータへの適用は、標準の更新サイクルによって行われます。 既定の更新サイクルは 90 分ごとですが、プラスマイナス 30 分まで任意に数値を補正できます。
  
標準サイクルの合間にグループ ポリシーを更新するには、GPUpdate ユーティリティを使用します。
  
##### GPUpdate を実行する
  
**GPUpdate を実行するには**
  
1.  Windows XP デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。
  
2.  **\[名前\]** ボックスに「**cmd**」と入力して、**\[OK\]** をクリックします。
  
    **注意 :** GPUpdate を使用する場合に利用できるオプションの詳細については、次のサイトを参照してください。
  
    -   [マイクロソフト サポート技術情報 298444「グループ ポリシー更新ユーティリティの説明」](http://go.microsoft.com/fwlink/?linkid=35504)http://go.microsoft.com/fwlink/?linkid=35504
  
3.  コマンド プロンプトで「**GPUpdate**」と入力し、ENTER キーを押します。
  
    [![](images/Cc700817.adprte23(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte23_big(ja-jp,technet.10).gif)
  
    **図 23   コマンド ラインの「GPUpdate」**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte23_big(ja-jp,technet.10).gif)
  
4.  コマンド プロンプトを閉じるには、「Exit」と入力して **ENTER** キーを押します。
  
#### インターネット通信の管理の設定が適用されていることを確認する
  
**インターネット通信の管理の設定が適用されていることを確認するには**
  
1.  **\[スタート\]** ボタンをクリックし、**\[マイ ピクチャ\]** をクリックします。
  
2.  **\[画像のタスク\]** の下に **\[オンラインでプリントを注文する\]** が表示されていないことを確認します。
  
3.  **\[ファイルとフォルダのタスク\]** の下に **\[このフォルダを Web に公開する\]** が表示されていないことを確認します。
  
4.  **\[マイ ピクチャ\]** を閉じます。
  
    **注意 :** 設定が適用されていない場合は、グループ ポリシーの適用に関してトラブルシューティングを行う必要があります。 グループ ポリシーの適用に関するトラブルシューティングについては、次のサイトを参照してください。
  
    -   Microsoft Download Center Web サイトの「[Windows Server 2003 のグループ ポリシーのトラブルシューティング (Troubleshooting Group Policy in Windows Server 2003)](http://go.microsoft.com/fwlink/?linkid=35481)」http://go.microsoft.com/fwlink/?linkid=35481 (英語)
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### DCOM アクセス設定を構成する
  
Microsoft コンポーネント オブジェクト モデル (COM) は、対話可能なソフトウェア アプリケーションを作成するためのシステムです。 DCOM を使用すると、作成したアプリケーションをロケーション間で分散することができます。 DCOM ワイヤ プロトコルは、COM コンポーネント間の通信を透過的にサポートします。
  
**注意 :** DCOM セキュリティの詳細については、次のサイトを参照してください。
  
-   Microsoft TechNet Web サイトの「[RPC および DCOM の脆弱性を軽減する最善の方法 (Best Practices for Mitigating RPC and DCOM Vulnerabilities)](http://www.microsoft.com/technet/security/alerts/info/bpdcom.mspx)」
  
多くの COM アプリケーションにはセキュリティ固有のコードが含まれていますが、脆弱な設定が使用されているため、コンポーネント間で認証されていないアクセスが許可されることがよくあります。 Windows XP SP2 では COM に変更が加えられているため、コンピュータ上のすべての呼び出し要求、アクティブ化要求、または起動要求へのアクセスを管理する、コンピュータ全体のアクセス制御を実行できます。 Windows XP SP2 では最低限の承認が標準化されており、コンピュータ上の COM サーバーにアクセスするには、それを満たす必要があります。
  
**注意 :** Windows XP SP2 の COM の修正プログラムの詳細については、次のサイトを参照してください。
  
-   Microsoft サポート オンライン Web サイトの「[Windows XP Service Pack 2 での COM+ 関連の修正一覧](http://support.microsoft.com/kb/838211/ja)」http://support.microsoft.com/kb/838211/ja
  
DCOM 要求があるたびに、コンピュータ全体のアクセス制御リスト (ACL) がチェックされます。 チェックが失敗した場合、要求は拒否されます。 コンピュータ全体の ACL の対象には、次のものがあります。
  
-   **起動とアクティブ化のアクセス許可**。 この許可は、COM サーバーがまだ実行されていない場合、COM のアクティブ化処理中に COM サーバーの起動の承認を制御します。次の 4 種類のアクセス権を所有しています。
  
    -   ローカルの起動
  
    -   リモートの起動
  
    -   ローカルのアクティブ化
  
    -   リモートのアクティブ化
  
-   **アクセス許可**。 この許可は、実行中の COM サーバーの呼び出しの承認を制御します。次の 2 種類のアクセス権を所有しています。
  
    -   ローカルの呼び出し
  
    -   リモートの呼び出し
  
        **注意 :** ローカルの COM メッセージはローカル呼び出し経由で着信し、リモートの COM メッセージはリモート呼び出し経由で着信します。
  
許可は、コンポーネント サービスの Microsoft 管理コンソール (MMC) を使用して構成できます。これにより、特定の COM サーバー アプリケーションの設定とは無関係に、必要な最低限のセキュリティ標準が提供されます。
  
**注意 :** 既定では、Windows XP SP2 を実行しているコンピュータ上のこの MMC スナップインは、Windows ファイアウォールによってブロックされます。この結果に対してセキュリティの警告が表示された場合は、**\[ブロックを解除する\]** をクリックする必要があります。
  
表 7 に、Windows XP SP2 コンピュータの既定の制限設定を示します。
  
**表 7   既定の DCOM アクセス制御の制限**

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
<th style="border:1px solid black;" >許可</th>
<th style="border:1px solid black;" >Administrator</th>
<th style="border:1px solid black;" >Everyone</th>
<th style="border:1px solid black;" >Anonymous</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">起動とアクティブ化</td>
<td style="border:1px solid black;">ローカルの起動
ローカルのアクティブ化
リモートの起動
リモートのアクティブ化</td>
<td style="border:1px solid black;">ローカルの起動
ローカルのアクティブ化</td>
<td style="border:1px solid black;">許可は未設定</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">アクセス</td>
<td style="border:1px solid black;">許可は未設定</td>
<td style="border:1px solid black;">ローカルの呼び出し
リモートの呼び出し</td>
<td style="border:1px solid black;">ローカルの呼び出し</td>
</tr>
</tbody>
</table>
  
既定の設定により、ローカルのシナリオはすべて、ソフトウェアまたはオペレーティング システムを変更しなくても有効です。 また、ほとんどの COM クライアントのシナリオも有効ですが、管理者以外のユーザーがインストール済みの COM サーバーに対して行うリモートでのアクティブ化は無効です。
  
COM サーバーを実装した場合、管理 COM クライアント以外のクライアントによるリモートでのアクティブ化または非認証のリモート呼び出しをサポートするには、この機能の既定の構成を変更する必要があります。
  
**注意 :** 既定の設定の変更方法はこの文書に記載されていますが、変更すると攻撃に対するコンピュータの脆弱性を増加させる場合があります。
  
#### このタスクを実行するための要件
  
-   資格情報 : Domain Admins セキュリティ グループのメンバとして Active Directory ドメイン クライアントである Windows XP SP2 コンピュータにログオンし、**グループ ポリシー オブジェクト**を開く必要があります。
  
-   ツール : グループ ポリシー オブジェクト エディタ スナップインがインストールされている Microsoft 管理コンソール (MMC)。
  
##### DCOM の設定を構成する
  
**DCOM の設定を構成するには**
  
1.  Windows XP SP2 デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**mmc**」と入力して、**\[OK\]** をクリックします。
  
2.  **\[ファイル\]** メニューの **\[スナップインの追加と削除\]** をクリックします。
  
3.  **\[スタンドアロン\]** タブで **\[追加\]** をクリックします。
  
4.  **\[利用できるスタンドアロン スナップイン\]** ボックスに表示されるリストの中から **\[グループ ポリシー オブジェクト エディタ\]** を検索してクリックし、**\[追加\]** をクリックします。
  
5.  **\[グループ ポリシー オブジェクトの選択\]** ダイアログ ボックスで **\[参照\]** をクリックします。
  
6.  構成するグループ ポリシー オブジェクトを選択して **\[OK\]** をクリックします。次に **\[完了\]** をクリックして、グループポリシー ウィザードを終了します。
  
7.  **\[閉じる\]** をクリックして **\[スタンドアロン スナップインの追加\]** ダイアログ ボックスを終了します。次に、\[OK\] をクリックして \[スナップインの追加と削除\] ダイアログ ボックスを終了し、管理コンソールに戻ります。
  
8.  コンソール ツリーで、**\[コンピュータの構成\]**、**\[Windows の設定\]、\[セキュリティの設定\]**、**\[ローカル ポリシー\]**、**\[セキュリティ オプション\]** の順に展開します。
  
    [![](images/Cc700817.adprte24(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte24_big(ja-jp,technet.10).gif)
  
    **図 24   \[セキュリティ オプション\]**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte24_big(ja-jp,technet.10).gif)
  
9.  **\[DCOM: セキュリティ記述子定義言語 (SDDL) でのコンピュータ アクセス制限\]** をダブルクリックします。
  
    **注意 :** SDDL の詳細については、次のサイトを参照してください。
  
    -   MSDN Web サイトの「[セキュリティ記述子定義言語 (Security Descriptor Definition Language)](http://go.microsoft.com/fwlink/?linkid=35503)」http://go.microsoft.com/fwlink/?linkid=35503 (英語)
  
    ![](images/Cc700817.adprte25(ja-jp,TechNet.10).gif)
  
    **図 25   \[DCOM: コンピュータ アクセス制限\]**
  
10. **\[セキュリティの編集\]** をクリックします。
  
    ![](images/Cc700817.adprte26(ja-jp,TechNet.10).gif)
  
    **図 26   \[アクセス許可\]**
  
11. 企業内の DCOM アプリケーションの特定のユーザーにすべてのコンピュータへのアクセス権を付与する場合は、**\[追加\]** をクリックします。
  
    ![](images/Cc700817.adprte27(ja-jp,TechNet.10).gif)
  
    **図 27   \[ユーザー、コンピュータ、またはグループの選択\]**
  
12. ユーザー名を入力して **\[OK\]** をクリックします。
  
13. **\[OK\]** をクリックして **\[アクセス許可\]** ダイアログ ボックスを閉じます。次に、**\[OK\]** をクリックして、**\[DCOM: セキュリティ記述子定義言語 (SDDL) でのコンピュータ アクセス制限\]** ダイアログ ボックスを閉じます。
  
14. **\[DCOM: セキュリティ記述子定義言語 (SDDL) でのコンピュータ起動制限\]** をダブルクリックして、**\[セキュリティの編集\]** をクリックします。 企業内の DCOM アプリケーションの特定のユーザーに、すべてのコンピュータの起動またはアクティブ化のアクセス許可を付与する場合は、**\[追加\]** をクリックします。
  
15. ユーザー名を入力して **\[OK\]** をクリックします。
  
16. **\[OK\]** をクリックして **\[アクセス許可\]** ダイアログ ボックスを閉じます。次に、**\[OK\]** をクリックして、**\[DCOM: セキュリティ記述子定義言語 (SDDL) でのコンピュータ起動制限\]** ダイアログ ボックスを閉じます。
  
17. コンソールを閉じます。
  
#### GPUpdate を使用して構成を適用する
  
GPUpdate ユーティリティを使用すると、セキュリティ設定など Active Directory ベースのグループ ポリシー設定を更新できます。 グループ ポリシーの構成が完了したら、設定のクライアント コンピュータへの適用は、標準の更新サイクルによって行われます。 既定の更新サイクルは 90 分ごとですが、プラスマイナス 30 分まで任意に数値を補正できます。
  
標準サイクルの合間にグループ ポリシーを更新するには、GPUpdate ユーティリティを使用します。
  
##### GPUpdate を実行する
  
**GPUpdate を実行するには**
  
1.  Windows XP デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。
  
2.  **\[名前\]** ボックスに「**cmd**」と入力して、**\[OK\]** をクリックします。
  
    **注意 :** GPUpdate を使用する場合に利用できるオプションの詳細については、次のサイトを参照してください。
  
    -   [マイクロソフト サポート技術情報 298444「グループ ポリシー更新ユーティリティの説明」](http://go.microsoft.com/fwlink/?linkid=35504)http://go.microsoft.com/fwlink/?linkid=35504
  
3.  コマンド プロンプトで「**GPUpdate**」と入力し、ENTER キーを押します。
  
    [![](images/Cc700817.adprte28(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte28_big(ja-jp,technet.10).gif)
  
    **図 28   コマンド ラインの「GPUpdate」**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte28_big(ja-jp,technet.10).gif)
  
4.  コマンド プロンプトを閉じるには、「Exit」と入力して **ENTER** キーを押します。
  
#### DCOM のセキュリティ設定が適用されていることを確認する
  
**DCOM のセキュリティ設定が適用されていることを確認するには**
  
1.  **\[スタート\]** ボタンをクリックして、**\[コントロール パネル\]** をクリックします。
  
2.  **\[パフォーマンスとメンテナンス\]** をクリックします。
  
3.  **\[コントロール パネルを選んで実行します\]** の下にある **\[管理ツール\]** をクリックします。  
  
4.  **\[管理ツール\]** の **\[コンポーネント サービス\]** をダブルクリックします。
  
5.  **\[コンポーネント サービス\]** コンソールで、**\[コンポーネント サービス\]**、**\[コンピュータ\]** の順にダブルクリックします。**\[マイ コンピュータ\]** を右クリックして、**\[プロパティ\]** をクリックします。  
  
6.  **\[COM セキュリティ\]** タブをクリックし、**\[既定値の編集\]** ボタンを 2 つともクリックして、DCOM の必要な構成が適用されていることを確認します。次に、**\[OK\]** をクリックして \[COM セキュリティ\] を閉じます。
  
7.  \[コンポーネント サービス\] を閉じ、\[管理ツール\] を閉じます。
  
8.  \[コントロール パネル\] を閉じます。
  
    **注意 :** 設定が適用されていない場合は、グループ ポリシーの適用に関してトラブルシューティングを行う必要があります。 グループ ポリシーの適用に関するトラブルシューティングについては、次のサイトを参照してください。
  
    -   Microsoft Download Center Web サイトの「[Windows Server 2003 のグループ ポリシーのトラブルシューティング (Troubleshooting Group Policy in Windows Server 2003)](http://go.microsoft.com/fwlink/?linkid=35481)」http://go.microsoft.com/fwlink/?linkid=35481 (英語)
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### RPC の設定を構成する
  
Windows XP SP2 では、RPC サービスに変更が加えられ、RPC インターフェイスが既定でセキュリティ保護されて Windows XP の危険を回避できるようになっています。 新規に追加されたポリシー設定は次の 2 つです。
  
-   **\[認証されていない RPC クライアントの制限\]**。 このポリシー設定では、システム上のすべての RPC インターフェイスの動作を変更できます。既定では、システム上の RPC インターフェイスへのリモートでの匿名アクセスは排除されますが、一部例外があります。
  
-   **\[RPC エンド ポイント マッパー クライアント認証\]**。 このポリシー設定では、エンド ポイント マッパー サービスと通信する必要がある RPC クライアントに認証を実行させることができます。ただし、エンドポイントを解決する必要がある RPC 呼び出しに認証情報が含まれている場合に限ります。  
  
低レベルの認証であっても、RPC 呼び出しに認証の実行を要求すると、インターフェイスを攻撃から保護することができます。 この機能は特に、匿名接続を使用してリモートで呼び出し可能なバッファ オーバーランを攻撃に悪用するワームに対して効果的です。
  
RPC セキュリティの詳細については、次のサイトを参照してください。
  
-   Microsoft TechNet Web サイトの「[RPC および DCOM の脆弱性を軽減する最善の方法 (Best Practices for Mitigating RPC and DCOM Vulnerabilities)](http://www.microsoft.com/technet/security/alerts/info/bpdcom.mspx)」 (英語)
  
#### このタスクを実行するための要件
  
-   資格情報 : Domain Admins セキュリティ グループのメンバとして Active Directory ドメイン クライアントである Windows XP SP2 コンピュータにログオンし、**グループ ポリシー オブジェクト**を開く必要があります。
  
-   ツール : グループ ポリシー オブジェクト エディタ スナップインがインストールされている Microsoft 管理コンソール (MMC)。
  
##### RPC の設定を構成する
  
\[認証されていない RPC クライアントの制限\] ポリシー設定を有効にすると、次のいずれかのオプションを使用して \[適用する RPC ランタイム未認証クライアント制限\] を構成できます。
  
-   **\[認証済み\]** (既定)。 このオプションを使用すると、認証済みの RPCクライアントのみが、ポリシー設定を適用するコンピュータ上で稼働する RPC サーバーへの接続を許可されます。 ただし、この制限からの解除を要求したインターフェイスは、この制限から除外されます。 このオプションは、RPC\_RESTRICT\_REMOTE\_CLIENT\_DEFAULT (1) 値に相当します。
  
-   **\[認証済み (例外なし)\]**。 このオプションを使用すると、認証済みの RPCクライアントのみが、ポリシー設定を適用するコンピュータ上で稼働する RPCサーバーへの接続を許可され、例外は適用されません。 このオプションを指定した場合、RPCを使用するリモートの匿名呼び出しをシステムでは受信できなくなるため、最高レベルのセキュリティが実現します。 このオプションは、RPC\_RESTRICT\_REMOTE\_CLIENT\_HIGH (2) 値に相当します。
  
-   **\[なし\]**。 このオプションを使用すると、すべての RPC クライアントが、ポリシー設定を適用するコンピュータ上で稼働する RPC サーバーへの接続を許可されます。 このオプションを指定した場合、新しい RPC インターフェイスの制限はシステムによってバイパスされます。 このオプションは、以前のバージョンの Windows の RPC の動作と同等です。 このオプションは、RPC\_RESTRICT\_REMOTE\_CLIENT\_NONE (0) 値に相当します。
  
\[RPC エンドポイント マッパー クライアント認証\] ポリシー設定を有効にすると、エンド ポイント マッパー サービスと通信する必要がある RPC クライアントに認証を実行させることができます。ただし、エンドポイントを解決する必要がある RPC 呼び出しに認証情報が含まれている場合に限ります。
  
\[RPC エンド ポイント マッパー クライアント認証\] ポリシー設定を無効にすると、エンドポイント マッパー サービスと通信する必要がある RPCクライアントは認証を行いません。 Microsoft Windows NT® 4.0 オペレーティング システムを実行しているコンピュータ上のエンド ポイント マッパー サービスでは、このような方法で提供された認証情報は処理できません。 クライアント コンピュータ上でこの設定を有効にすると、そのクライアントは、エンドポイントの解決が必要な場合に RPC を使用する Windows NT 4.0 サーバーと通信できなくなります。
  
**RPC の設定を構成するには**
  
1.  Windows XP SP2 デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**mmc**」と入力して、**\[OK\]** をクリックします。
  
2.  **\[ファイル\]** メニューの **\[スナップインの追加と削除\]** をクリックします。
  
3.  **\[スタンドアロン\]** タブで **\[追加\]** をクリックします。
  
4.  **\[利用できるスタンドアロン スナップイン\]** ボックスに表示されるリストの中から **\[グループ ポリシー オブジェクト エディタ\]** を検索してクリックし、**\[追加\]** をクリックします。
  
5.  **\[グループ ポリシー オブジェクトの選択\]** ダイアログ ボックスで **\[参照\]** をクリックします。
  
6.  構成するグループ ポリシー オブジェクトをリストから選択します。 **\[OK\]** をクリックし、次に **\[完了\]** をクリックしてグループ ポリシー ウィザードを閉じます。
  
7.  **\[閉じる\]** をクリックして **\[スタンドアロン スナップインの追加\]** ダイアログ ボックスを終了します。次に、**\[OK\]** をクリックして **\[スナップインの追加と削除\]** ダイアログ ボックスを終了し、管理コンソールに戻ります。
  
8.  コンソール ツリーで、**\[コンピュータの構成\]**、**\[管理用テンプレート\]**、**\[システム\]** の順に展開し、**\[リモート プロシージャ コール\]** をクリックします。
  
    [![](images/Cc700817.adprte29(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte29_big(ja-jp,technet.10).gif)
  
    **図 29   RPC の設定**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte29_big(ja-jp,technet.10).gif)
  
9.  既に説明した構成に関する情報を参照して、**\[認証されていない RPC クライアントの制限\]** をダブルクリックし、**\[有効\]** をクリックします。次に、**\[認証済み (例外なし)\]** をクリックして、**\[OK\]** をクリックします。
  
10. 既に説明した構成に関する情報を参照して、**\[RPC エンド ポイント マッパー クライアント認証\]** をダブルクリックし、**\[有効\]** をクリックします。次に **\[OK\]** をクリックします。
  
11. グループ ポリシー オブジェクトを閉じます。
  
#### GPUpdate を使用して構成を適用する
  
GPUpdate ユーティリティを使用すると、セキュリティ設定など Active Directory ベースのグループ ポリシー設定を更新できます。 グループ ポリシーの構成が完了したら、設定のクライアント コンピュータへの適用は、標準の更新サイクルによって行われます。 既定の更新サイクルは 90 分ごとですが、プラスマイナス 30 分まで任意に数値を補正できます。
  
標準サイクルの合間にグループ ポリシーを更新するには、GPUpdate ユーティリティを使用します。
  
##### GPUpdate を実行する
  
**GPUpdate を実行するには**
  
1.  Windows XP デスクトップの **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。
  
2.  **\[名前\]** ボックスに「**cmd**」と入力して、**\[OK\]** をクリックします。
  
    **注意 :** GPUpdate を使用する場合に利用できるオプションの詳細については、次のサイトを参照してください。
  
    -   [マイクロソフト サポート技術情報 298444「グループ ポリシー更新ユーティリティの説明」](http://go.microsoft.com/fwlink/?linkid=35504)http://go.microsoft.com/fwlink/?linkid=35504
  
3.  コマンド プロンプトで「**GPUpdate**」と入力し、ENTER キーを押します。
  
    [![](images/Cc700817.adprte30(ja-jp,TechNet.10).gif)](https://technet.microsoft.com/ja-jp/cc700817.adprte30_big(ja-jp,technet.10).gif)
  
    **図 30   コマンド ラインの「GPUpdate」**
  
    [拡大表示する](https://technet.microsoft.com/ja-jp/cc700817.adprte30_big(ja-jp,technet.10).gif)
  
4.  コマンド プロンプトを閉じるには、「Exit」と入力して **ENTER** キーを押します。
  
#### RPC の設定が適用されていることを確認する
  
ここで説明する手順には、レジストリの編集作業が含まれています。 編集前にレジストリのバックアップを作成して、問題が発生した場合にレジストリを復元できることを確認してください。 レジストリのバックアップの作成、復元、および編集方法については、次のサイトを参照してください。
  
-   [マイクロソフト サポート技術情報 256986「Windows XP および Windows Server 2003 でレジストリをバックアップ、編集、および復元する方法」](http://go.microsoft.com/fwlink/?linkid=35500)http://go.microsoft.com/fwlink/?linkid=35500
  
##### RPC の設定が適用されていることを確認する
  
**RPC のセキュリティ設定が適用されていることを確認するには**
  
1.  **\[スタート\]** ボタンをクリックして、**\[ファイル名を指定して実行\]** をクリックします。
  
2.  「**Regedit**」と入力して **\[OK\]** をクリックします。
  
3.  レジストリ エディタで、**\[HKEY\_LOCAL\_MACHINE\]** をダブルクリックします。次に、**\[SOFTWARE\]**\\**\[Policies\]**\\**\[Microsoft\]**\\**\[Windows NT\]**\\**\[Rpc\]** をダブルクリックします。  
  
4.  レジストリに次のエントリがあることを確認します。
  
    **EnableAuthEPResolution REG\_DWORD 0x000000001**
  
    **RestrictRemoteClientsIn REG\_DWORD 0x000000002**
  
5.  レジストリ エディタを閉じます。
  
    **注意 :** 設定が適用されていない場合は、グループ ポリシーの適用に関してトラブルシューティングを行う必要があります。 グループ ポリシーの適用に関するトラブルシューティングについては、次のサイトを参照してください。
  
    -   Microsoft Download Center Web サイトの「[Windows Server 2003 のグループ ポリシーのトラブルシューティング (Troubleshooting Group Policy in Windows Server 2003)](http://go.microsoft.com/fwlink/?linkid=35481)」http://go.microsoft.com/fwlink/?linkid=35481 (英語)
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 関連情報
  
Windows XP SP2 のネットワーク保護の詳細については、次のサイトを参照してください。
  
-   Microsoft TechNet Web サイトの「[Microsoft Windows XP Service Pack 2 での機能の変更点 第 2 部: ネットワーク保護技術](http://technet.microsoft.com/library/bb457156.aspx)」http://technet.microsoft.com/library/bb457156.aspx
  
-   Microsoft TechNet Web サイトの「[グループ ポリシーを使用した Windows XP Service Pack 2 の機能の管理](http://www.microsoft.com/japan/technet/prodtechnol/winxppro/maintain/mangxpsp2/mngintro.mspx)」http://www.microsoft.com/japan/technet/prodtechnol/winxppro/maintain/mangxpsp2/mngintro.mspx
  
-   Microsoft TechNet Web サイトの「[グループ ポリシー管理用テンプレート (.adm) ファイルの管理に関する推奨事項](http://go.microsoft.com/fwlink/?linkid=35502)」http://go.microsoft.com/fwlink/?linkid=35502
  
Windows XP SP2 のセキュリティの詳細については、次のサイトを参照してください。
  
-   Microsoft ダウンロード センター Web サイトの「[Service Pack 2 用にアップデートされた Windows XP セキュリティ ガイド v2 (Windows XP Security Guide v2 updated for Service Pack 2](http://go.microsoft.com/fwlink/?linkid=35309))」http://go.microsoft.com/fwlink/?linkid=35309 (英語)
  
-   Microsoft TechNet Web サイト http://www.microsoft.com/japan/technet/security/prodtech/windowsxp/secwinxp/xpsgapa.mspx の「[Windows XP セキュリティ ガイド 付録 A: Windows XP Service Pack 2 のその他のガイダンス (Windows XP Security Guide Appendix A: Additional Guidance for Windows XP Service Pack 2)](http://www.microsoft.com/japan/technet/security/prodtech/windowsxp/secwinxp/xpsgapa.mspx)」
  
-   Microsoft TechNet Web サイトの「[グループ ポリシーを使用した Windows XP Service Pack 2 (SP2) の展開 (Using Group Policy to Deploy Windows XP Service Pack 2 (SP2))](http://technet.microsoft.com/library/bb457070.aspx)」http://technet.microsoft.com/library/bb457070.aspx (英語)
  
セキュリティ関連の用語の定義については、次の資料を参照してください。
  
-   マイクロソフト Web サイトの「[Microsoft セキュリティ用語集](http://www.microsoft.com/japan/security/glossary.mspx)」http://www.microsoft.com/japan/security/glossary.mspx
  
[](#mainsection)[ページのトップへ](#mainsection)