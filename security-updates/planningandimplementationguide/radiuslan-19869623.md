---
TOCTitle: '運用ガイド - RADIUS およびワイヤレス LAN のセキュリティ インフラストラクチャを管理する'
Title: '運用ガイド - RADIUS およびワイヤレス LAN のセキュリティ インフラストラクチャを管理する'
ms:assetid: '56beab30-3f67-4633-9074-f5f85241b1ab'
ms:contentKeyID: 19869623
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc527047(v=TechNet.10)'
---

証明書サービスを使用してワイヤレス LAN のセキュリティを保護する
===============================================================

### 第 12 章 : RADIUS およびワイヤレス LAN のセキュリティ インフラストラクチャを管理する

最終更新日: 2005年5月24日

##### トピック

[](#ejaa)[はじめに](#ejaa)
[](#eiaa)[基本的な保守タスク](#eiaa)
[](#ehaa)[運用ガイドで使用されているテクノロジ](#ehaa)
[](#egaa)[RADIUS と WLAN セキュリティ管理の役割](#egaa)
[](#efaa)[運用作業領域のタスク](#efaa)
[](#eeaa)[サポート作業領域のタスク](#eeaa)
[](#edaa)[最適化作業領域のタスク](#edaa)
[](#ecaa)[変更作業領域のタスク](#ecaa)
[](#ebaa)[構成表](#ebaa)
[](#eaaa)[関連情報](#eaaa)

### はじめに

*ワイヤレス LAN のセキュリティ強化*ガイダンスの一部としてリモート認証ダイヤルイン ユーザー サービス (RADIUS) インフラストラクチャおよびワイヤレス LAN (WLAN) セキュリティが実装されますが、この章では、これらを管理するために必要な運用手順について説明します。 この章の構成は、Microsoft Operations Framework (MOF) のカテゴリおよび「第 10 章 : 運用ガイドの紹介」で説明している概念に基づいています。

この章を理解することで、システムの監視と保守を開始するためのあらゆるセットアップ タスクを実施し、RADIUS インフラストラクチャと WLAN セキュリティに対応した完全な管理システムを実装できるようになります。 また、インフラストラクチャを正常に保つために定期的に実施するタスクや、サポート インシデントの管理、環境の変更への対処、およびシステム パフォーマンスを最適化する手順についても説明します。

この章は大きく 2 つの部分に分かれています。 前半は、「基本的な保守タスク」と「RADIUS と WLAN セキュリティ管理の役割」の 2 つのセクションで構成されています。簡単な説明で構成されているので、全体を読み通してください。システム用に正しく管理された環境をセットアップするための基本的な情報を確認できます。 章の後半は主に参照用です。 参照セクションには、システムを展開するときに実装する必要のあるいくつかのタスクが記載されていますが、これらのタスクについては、「基本的な保守タスク」で具体的に説明されています。

参照セクションの内容はすべて理解しておく必要はありませんが、セクション全体に目を通しておくことで、必要になったときに該当する項目をすばやく見つけることできます。

#### 章の前提条件

「第 10 章 : 運用ガイドの紹介」で説明している MOF の概念についてひと通り理解しておく必要があります。MOF の詳細な知識は必要ありません。

RADIUS と Microsoft® インターネット認証サービス (IAS) の概念、および 802.11、802.1X、EAP-TLS の概念についても、特に理解しておく必要があります。 これらの技術的なトピックの詳細については、計画ガイドの各章の説明を参照してください。

Microsoft Windows® 2000 Server (またはそれ以降) についても、次の分野に関する知識が必要になります。

-   Microsoft Windows Server™ 2003 の基本的な運用および保守 (イベント ビューア、コンピュータの管理、NTBackup などのツールの使い方など)。

-   Active Directory® ディレクトリ サービスの概念とタスク。 Active Directory の構造とツール、ユーザー、グループ、その他の Active Directory オブジェクトの操作、グループ ポリシーの使い方など。

-   ユーザー、グループ、監査、アクセス制御リストなどの Windows システムのセキュリティの概念、セキュリティ テンプレートの使用、グループ ポリシーまたはコマンド ライン ツールを使用したセキュリティ テンプレートの適用。

-   インターネット認証サービスの管理。

-   Windows スクリプト ホスト (WSH) と Microsoft Visual Basic® Scripting Edition (VBScript) 言語。 バッチ プログラミング構文に関する知識があると、提供されているスクリプトを有効に活用できますが、これは必須ではありません。

さらに、この章を読む前に、計画ガイドと構築ガイドの各章に目を通し、ソリューションのアーキテクチャと設計について一通り理解しておく必要があります。

#### 章の概要

次の一覧は、この章の主なセクションをまとめたものです。

-   **基本的な保守タスク**。 管理システムをセットアップするために必要なタスクの一覧と、システムを維持するために定期的に実施する必要のあるタスクの一覧で構成されます。

-   **管理役割**。 ソリューションで使用される管理役割、各役割の機能、およびこれらの役割の MOF 役割クラスタとソリューション用に定義された管理セキュリティ グループへの対応付け方法について説明します。

-   **運用作業領域のタスク**。 RADIUS インフラストラクチャと WLAN セキュリティの通常の保守に関連するすべてのタスクについて説明します。 監視、バックアップ、ディレクトリおよびセキュリティの運用などのタスクがあります。

-   **サポート作業領域のタスク**。 システムの問題からの復旧に関連するすべての手順について説明します。 バックアップからの復元、障害のある IAS サーバーの処理に関する操作などがあります。

-   **最適化作業領域のタスク**。 いくつかの容量管理計画手順について説明します。

-   **変更作業領域のタスク**。 IAS サーバー構成に変更を加え、その変更内容を制御された方法で運用環境にリリースする共通のタスクについて説明します。 IAS サーバーに関する重要な構成情報を収集して保守する手順についても説明します。

-   **トラブルシューティング**。 RADIUS インフラストラクチャと WLAN セキュリティで発生する共通の問題を解決する手順について説明します。 また、各種コンポーネントのログを有効にする手順と便利なトラブルシューティング ツールについても説明します。

-   **構成表**。 構築ガイドの各章で使用される構成パラメータのサブセットについて説明します。 これらの値は、各手順で例として使用されます。

-   **関連情報**。 本文で参照した関連情報ソースがまとめて記載してあります。

[](#mainsection)[ページのトップへ](#mainsection)

### 基本的な保守タスク

ここでは、RADIUS インフラストラクチャおよび WLAN セキュリティを正しく運用するために実行する必要のある主要なタスクについて説明します。 これらのタスクは、最初に行うセットアップ タスクと、継続して行う運用タスクの 2 つの表に分けて記載されています。 表に記載されたタスク名についてはこのドキュメントの後半で詳しく説明します。 タスクは MOF の作業領域ごとにグループ化されています。必要なタスクを簡単に探すことができるように、タスクが属している MOF サービス管理機能 (SMF) をタスクの横に記述しています。

また、ここでは、この章の手順で使用されるツールやテクノロジの一覧も記載しています。

#### 最初に行うセットアップ タスク

次の表は、RADIUS インフラストラクチャと WLAN セキュリティを運用状態にするために実行する必要があるタスクを示しています。 運用基準や業務内容によってはこれらのタスクをすべて実行する必要はありませんが、 タスクの詳細を確認して、実行すべきタスクかどうかを判断する必要があります。 また、タスクの中には、再度実行しなければならないものもあります。 たとえば、新しい IAS サーバーをインストールした場合には、IAS のバックアップ ジョブと監視ジョブを構成する必要があります。

**表 12.1: 最初に行うセットアップ タスク**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >タスク名</th>
<th style="border:1px solid black;" >サービス管理機能</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>運用作業領域</strong></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS に RADIUS クライアントを追加する</td>
<td style="border:1px solid black;">ネットワーク管理</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">コンピュータのワイヤレス設定を有効にする</td>
<td style="border:1px solid black;">ディレクトリ サービス管理</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">リモート アクセス ポリシー グループにコンピュータとユーザーを追加する</td>
<td style="border:1px solid black;">ディレクトリ サービス管理</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">監視の警告を分類する</td>
<td style="border:1px solid black;">サービスの監視と管理</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS の容量制約を監視する</td>
<td style="border:1px solid black;">サービスの監視と管理</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS 構成エクスポートを構成する</td>
<td style="border:1px solid black;">記憶域管理</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RADIUS クライアント構成をエクスポートする</td>
<td style="border:1px solid black;">記憶域管理</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS データ ディレクトリのバックアップを構成する</td>
<td style="border:1px solid black;">記憶域管理</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS バックアップをテストする</td>
<td style="border:1px solid black;">記憶域管理</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>最適化作業領域</strong></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS サーバーの最大負荷を判定する</td>
<td style="border:1px solid black;">容量管理</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS サーバーの記憶域要件およびバックアップ要件を判定する</td>
<td style="border:1px solid black;">容量管理</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>変更作業領域</strong></td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">オペレーティング システムの更新を管理する</td>
<td style="border:1px solid black;">変更管理<br />
リリース管理</td>
</tr>
</tbody>
</table>
 

#### 保守タスク

次の表は、RADIUS インフラストラクチャと WLAN セキュリティを正常に維持し続けるために定期的に実行する必要があるタスクを示します。 この表は、必要なリソースやシステム管理の運用スケジュールを計画する際に役立ちます。

実行する必要のないタスクもありますが、各タスクの詳細を確認し、実行する必要があるかどうかを判断する必要があります。 また、タスクの中には、必要に応じて実行するものと、定期的に実行するものもあります。 たとえば、RADIUS クライアントを IAS サーバーに追加する場合は、スケジュール設定されていなくても、サーバー構成のエクスポートやバックアップを実行する必要があります。 こうしたタスクは \[実行頻度\] 欄に注記しています。 また、このような必要事項は、個々のタスクの説明でも注記しています。

**表 12.2: 継続保守タスク**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >タスク名</th>
<th style="border:1px solid black;" >実行頻度</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">IAS に RADIUS クライアントを追加する</td>
<td style="border:1px solid black;">ワイヤレス AP がネットワークに追加された時点</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS サーバーから RADIUS クライアントを削除する</td>
<td style="border:1px solid black;">ワイヤレス AP がネットワークから削除された時点</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">コンピュータのワイヤレス設定を有効にする</td>
<td style="border:1px solid black;">コンピュータがネットワークに追加された時点</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">リモート アクセス ポリシー グループにコンピュータとユーザーを追加する</td>
<td style="border:1px solid black;">従業員が WLAN へのアクセスを許可された時点</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RADIUS クライアント構成をエクスポートする</td>
<td style="border:1px solid black;">ワイヤレス AP がネットワークに追加された時点</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS バックアップをテストする</td>
<td style="border:1px solid black;">毎月</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS RADIUS 要求ログへアクセスする</td>
<td style="border:1px solid black;">毎日または毎週<br />
(セキュリティ要件による)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS RADIUS 認証イベント ログ エントリを確認する</td>
<td style="border:1px solid black;">毎日または毎週<br />
(セキュリティ要件による)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS RADIUS ログ エントリをアーカイブおよび削除する</td>
<td style="border:1px solid black;">毎月</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">オペレーティング システムの更新を管理する</td>
<td style="border:1px solid black;">毎日</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 運用ガイドで使用されているテクノロジ
  
次の表は、この章で説明されている手順で使用されているツールとテクノロジの一覧です。
  
**表 12.3: 必要なテクノロジ**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >項目</th>
<th style="border:1px solid black;" >ソース</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">[Active Directory ユーザーとコンピュータ] MMC スナップイン</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MSS スクリプト</td>
<td style="border:1px solid black;">このソリューション</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">テキスト エディタ</td>
<td style="border:1px solid black;">Windows Server 2003 のメモ帳</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows タスク スケジューラ サービス</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SchTasks.exe</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows バックアップ</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">イベント ビューア</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">パフォーマンス モニタ</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Net.exe</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">運用警告コンソール</td>
<td style="border:1px solid black;">Microsoft Operations Manager (MOM)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">外部保管用のリムーバブル メディア</td>
<td style="border:1px solid black;">フロッピー ディスク、CD-RW、またはテープ</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IAS サーバー バックアップ</td>
<td style="border:1px solid black;">ネットワーク バックアップ サービス<br />
または<br />
ローカル バックアップ デバイス</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">グループ ポリシー管理コンソール</td>
<td style="border:1px solid black;">Microsoft.com からの Web ダウンロード</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">IASParse</td>
<td style="border:1px solid black;">Windows Server 2003 サポート ツール</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Access 2002</td>
<td style="border:1px solid black;">Microsoft Office XP</td>
</tr>
</tbody>
</table>
  
**表 12.4: 推奨テクノロジ**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >項目</th>
<th style="border:1px solid black;" >ソース</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">運用警告コンソール</td>
<td style="border:1px solid black;">Microsoft Operations Manager またはその他のサービス監視システム</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">運用警告用の電子メール インフラストラクチャ (MOM の代替)</td>
<td style="border:1px solid black;">SMTP/POP3/IMAP サーバーとクライアント (Microsoft Exchange Server および Microsoft Outlook® など)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Eventquery.vbs</td>
<td style="border:1px solid black;">Windows Server 2003</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">容量計画ツール</td>
<td style="border:1px solid black;">Microsoft Operations Manager またはその他の容量計画ツール</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">セキュリティ更新配布システム</td>
<td style="border:1px solid black;">Microsoft Systems Management Server<br />
または<br />
Microsoft Software Update Services</td>
</tr>
</tbody>
</table>
 

[](#mainsection)[ページのトップへ](#mainsection)

### RADIUS と WLAN セキュリティ管理の役割

RADIUS インフラストラクチャと WLAN セキュリティの管理には多数の役割が関与しています。 ここでは、中心的な役割とサポート的な役割に分けて説明します。

#### RADIUS と WLAN の中心的な役割

RADIUS インフラストラクチャと WLAN セキュリティの管理にとって中心的な役割を次の表に示します。

**表 12.5: RADIUS と WLAN セキュリティの中心的な役割**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >役割名</th>
<th style="border:1px solid black;" >範囲</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">インターネット認証サービス管理者 (Internet Authentication Service Administrator)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">企業の IAS の全体的な管理と構成を担当</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">インターネット認証サービス監査人 (Internet Authentication Service Auditor)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">IAS サーバー コンピュータに格納されている RADIUS ログの確認、アーカイブ、および削除を担当</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">インターネット認証サービス バックアップ オペレータ (Internet Authentication Service Backup Operators)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">IAS 構成状態データと履歴データのバックアップと復元を担当</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">WLAN ヘルプデスク スタッフ (WLAN Helpdesk Staff)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">WLAN の問題のトラブルシューティングを担当する上級ヘルプデスク スタッフ</td>
</tr>
</tbody>
</table>
  
#### RADIUS と WLAN セキュリティをサポートする役割
  
次の表に示す役割は、RADIUS インフラストラクチャと WLAN セキュリティを管理するうえで中心となる役割ではなく、中心となる役割をサポートする運用上の役割です。
  
**表 12.6: RADIUS と WLAN セキュリティをサポートする役割**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >役割名</th>
<th style="border:1px solid black;" >範囲</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">監視オペレータ (Monitor Operator)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">イベントの監視を担当</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">容量計画立案者 (Capacity Planner)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">将来的な容量要件を予測するためのパフォーマンスと負荷の分析を担当</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Active Directory 管理者 (Active Directory Administrator)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">Active Directory インフラストラクチャの構成とサポートを担当</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Active Directory 運用 (Active Directory Operations)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">セキュリティ グループの保守、アカウントの作成など、ディレクトリの日常的な保守業務を担当</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">デスクトップ管理者 (Desktop Administrator)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">デスクトップ コンピュータの構成とサポートを担当</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">変更承認委員会 (Change Approvals Board)</td>
<td style="border:1px solid black;">エンタープライズ環境</td>
<td style="border:1px solid black;">インフラストラクチャの変更の承認に必要な業務および技術部門の代表者</td>
</tr>
</tbody>
</table>
  
#### 役割をセキュリティ グループに対応付ける
  
次の表は、このソリューションで定義されているセキュリティ グループ、およびその機能とアクセス許可について簡単に説明したものです。
  
IAS サーバーの場合は、ドメイン セキュリティ グループを使って、各役割にアクセス許可が適用されます。 ドメイン アカウントによって役割グループが指定されます。 組織のセキュリティおよび IT ポリシーをサポートしていれば、1 つのアカウントが複数の役割グループのメンバになることができます。
  
**表 12.7: RADIUS および WLAN セキュリティ役割のセキュリティ グループへの対応付け**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >役割名</th>
<th style="border:1px solid black;" >ドメイン セキュリティ グループ</th>
<th style="border:1px solid black;" >ローカル セキュリティ グループ</th>
<th style="border:1px solid black;" >機能</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">インターネット認証サービス管理者 (Internet Authentication Service Administrator)</td>
<td style="border:1px solid black;">IAS Admins</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">IAS サービスの開始と終了、およびその構成変更も含む、IAS サーバーのすべての管理機能</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">インターネット認証サービス監査人 (Internet Authentication Service Auditor)</td>
<td style="border:1px solid black;">IAS Security Auditors</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">ログ ボリュームの RADIUS 要求ログ ファイルの読み取りや削除を行う機能</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">IAS バックアップ オペレータ (IAS Backup Operators)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">Backup Operators</td>
<td style="border:1px solid black;">オペレーティング システムの状態データおよび IAS 構成データの完全バックアップと復元機能</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">WLAN ヘルプデスク スタッフ (WLAN Helpdesk Staff)</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">IAS の認証に関する問題を解決するための IAS 管理者との連携 (場合によっては IAS セキュリティ監査人と同じリソースの読み取りアクセス許可が付与される可能性がある)</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 運用作業領域のタスク
  
運用作業領域には、事前に設定されたパラメータの範囲内のサービス レベルを実現し、維持するために定期的にサービス ソリューションに適用する IT 運用基準、プロセス、および手順が含まれます。 運用作業領域の目的は、手動と自動にかかわらず、毎日どのようなタスクを行うかをできるだけ事前に明確にすることです。
  
ここでは、次の SMF に関連する情報について説明します。
  
-   ネットワーク管理
  
-   ディレクトリ サービス管理
  
-   セキュリティ管理
  
-   記憶域管理
  
-   サービスの監視と管理
  
-   ジョブ スケジュール
  
次の SMF に属するタスクはありません。
  
-   システム管理
  
-   ネットワーク管理
  
-   印刷管理と出力管理
  
    **注 :** 各タスクの説明には、セキュリティ要件、実行頻度、技術要件などの要約情報を記載します。
  
#### ネットワーク管理
  
ネットワーク管理の役割は、サーバー、ルーター、スイッチ、ファイアウォールなど、組織のネットワークを構成する物理コンポーネントの設計と保守を担当します。 ワイヤレス ネットワークの場合は、ネットワークをサポートするワイヤレス アクセス ポイント (AP) や RADIUS サーバーなどのコンポーネントが該当します。
  
##### IAS に RADIUS クライアントを追加する
  
ワイヤレス AP は IAS サーバーを使って認証やアカウンティングを行えるように許可されている必要があります。 新しいワイヤレス AP を RADIUS クライアントとして有効にする手順は、運用環境の IAS サーバー上で導入後に行う必要のある変更作業の 1 つです。 このタスクでは、ワイヤレス AP を承認し、IAS サーバーを使用して RADIUS の認証処理およびアカウンティング処理を実行できるようにします。 このタスクは、新しいワイヤレス AP が導入され、ネットワーク認証に参加できるように構成されるたびに実行します。
  
###### 要約情報
  
-   **セキュリティ要件** : IAS Admins セキュリティ グループのメンバ
  
-   **実行頻度** : 新たなワイヤレス AP がネットワークに追加された時点
  
-   **技術要件** :
  
    -   \[インターネット認証サーバー\] MMC スナップイン
  
    -   MSS スクリプト (GenPwd スクリプト コマンド用)
  
    -   フロッピー ディスク ドライブまたは他の書き込み可能なリムーバブル メディア ドライブ
  
    -   フロッピー ディスクまたは他の書き込み可能なリムーバブル メディア
  
###### タスクの詳細
  
AP を各 IAS サーバーに追加するときは、ワイヤレス AP ごとに固有のランダム パスワード (シークレット) を使用します。 複数のワイヤレス AP で同じ RADIUS シークレットを使用すると、共有シークレットを長期間維持することができないため、リスクが発生します。
  
Windows Server 2003 Enterprise Edition では、管理者はワイヤレス AP を IAS サーバーに一括で追加できます。具体的には、RADIUS クライアント専用のサブネットを追加し、そのサブネット上のすべての AP で共有シークレットを使用します。 この方法を使用すると、シークレットの管理は容易になりますが、各ワイヤレス AP に固有のシークレットを使用する場合よりセキュリティは低くなります。
  
このソリューションでは、暗号化されたランダム シークレットを実装します。このシークレットは、このモジュールに付属している GenPwd スクリプトによって生成されます。
  
**IAS に RADIUS クライアントを個別に追加するには**
  
1.  \[インターネット認証サービス\] MMC スナップインで **\[RADIUS クライアント\]** フォルダを右クリックし、**\[新しい RADIUS クライアント\]** をクリックします。
  
2.  ワイヤレス AP の **\[フレンドリ名\]** と **\[クライアントのアドレス (IP または DNS)\]** を入力します。 DNS 名ではなく IP アドレスを使用してください。DNS 名を指定すると、サーバー起動時に IAS によって各 RADIUS クライアントの名前解決が実行されます。 ワイヤレス AP が多数存在する大規模な環境では、DNS 名でクライアントの名前解決を実行すると、起動時間が長くなってしまいます。 **\[次へ\]** をクリックします。
  
3.  クライアント製造元の属性で **\[RADIUS の標準\]** を選択し、このワイヤレス AP 用の共有シークレットを入力します。
  
    **注 :** 以降の手順では、フロッピー ディスクなどの書き込み可能なリムーバブル メディアを使用します。 フォーマット済みのメディアを用意し、"*&lt;サーバー名&gt;* のRADIUS クライアント" と書いたラベルを貼ります。
  
4.  このガイドに記載されている GenPwd スクリプトを使用することで、RADIUS クライアントとして構成された各 WAP で個々に使用する強力なランダム シークレットを生成できます。 GenPwd スクリプトを実行するとシークレットが生成され、Clients.txt ファイルに各 RADIUS クライアントのフレンドリ名と共に保存されます。 フレンドリ名とシークレットは、現在のディレクトリにある Clients.txt の末尾に、コンマ区切り形式で自動的に追加されます。 ただし、強力な RADIUS シークレットを生成するための手段を独自に用意している場合は、以降の手順で GenPwd の代わりに使用することもできます。
  
    **注 :** GenPwd は、CryptoAPI 機能を使用して Base64 でエンコードされた暗号化ランダム文字列を生成します。 VBScript 乱数機能は使用しません。
  
5.  コマンド プロンプトを開き、A:\\ を現在のディレクトリにします。 現在のディレクトリ内の Clients.txt ファイルに新しい情報が自動で追加されるため、ファイル システムのディレクトリの場所は重要です。 Clients.txt が存在しない場合は、新規に作成されます。
  
6.  次のコマンドを実行します。 &lt;*client name*&gt; の部分はワイヤレス アクセス ポイントのフレンドリ名に置き換えてください。 クライアント名には、DNS 名や IP アドレスなどの文字列を指定することもできます。
  
    cscript //job:GenPwd C:\\MSSScripts\\wl\_tools.wsf /client:client\_name
  
    作成されたコンマ区切り形式ファイルは、参照や編集用としてスプレッドシートやデータベース アプリケーションに簡単にインポートできます。
  
    **重要 :** 各 IAS サーバーおよびワイヤレス AP のRADIUS シークレットは、定期的に変更することをお勧めします。 GenPwd またはその他のユーティリティを使用して強力なシークレットを生成し、変更後のパスワードとワイヤレス AP 名を Clients.txt ファイルに保存してください。 clients.txt ファイルには、機密性の非常に高いデータが格納されています。 このファイルはサーバーにコピーせず、金庫などの安全な場所に保管してください。
  
7.  \[インターネット認証サービス\] MMC スナップインで、RADIUS 共有シークレットを **\[共有シークレット\]** と **\[共有シークレットの確認入力\]** フィールドにそれぞれ入力します。 **\[要求はメッセージ認証属性を含んでいる必要がある\]** 属性を選択し、**\[完了\]** をクリックします。
  
    **注 :** 一部の RADIUS クライアントは、ベンダ固有の属性 (VSA) を構成しないと正しく動作しません。 VSA の要件については、ベンダが提供しているドキュメントを参照してください。
  
##### IAS サーバーから RADIUS クライアントを削除する
  
RADIUS クライアントとして使用している不要なワイヤレス AP を削除する手順は、運用環境の IAS サーバー上で導入後に行う必要のある変更作業の 1 つです。 この作業では、ワイヤレス AP を削除し、IAS サーバーを使用した RADIUS の認証処理およびアカウンティング処理の実行を無効にします。 ワイヤレス AP を廃止するたびにこのタスクを実行し、それらの AP で RADIUS 認証とアカウンティング サービスを使用できないようにしてください。
  
###### 要約情報
  
-   **セキュリティ要件** : IAS Administrators グループのメンバ
  
-   **実行頻度 :** ワイヤレス AP がネットワークから削除された時点
  
-   **技術要件** :
  
    -   \[インターネット認証サーバー\] MMC スナップイン
  
    -   Notepad.exe またはその他のテキスト ファイル エディタ
  
###### タスクの詳細
  
IAS から各ワイヤレス アクセス ポイントを個別に削除します。 また、安全な場所に保管してある RADIUS クライアントのフロッピー ディスクに格納された Clients.txt ファイルから、対応するエントリを削除する必要もあります。 Clients.txt ファイルは、「IAS に RADIUS クライアントを追加する」タスクの手順で作成されるファイルです。
  
**IAS サーバーから RADIUS クライアントを削除するには**
  
1.  \[インターネット認証サーバー\] MMC スナップインで、\[RADIUS クライアント\] フォルダを選択します。
  
2.  右側のペインで、削除対象の RADIUS クライアントを表すエントリを選択し、**\[削除\]** をクリックします。
  
3.  削除の確認を求められたら、**\[はい\]** をクリックします。
  
    **注 :** 以降の手順では、前のセクションで作成したフロッピー ディスクなどの書き込み可能なリムーバブル メディアを使用します ("*&lt;サーバー名&gt;* の RADIUS クライアント" というラベルが貼られています)。 データの消失を防ぐため、サーバーに対応した適切なディスクを使用してください。
  
4.  このサーバー用の RADIUS クライアント フロッピー ディスクを用意し、メモ帳で A:\\Clients.txt ファイルを開きます。
  
5.  不要になった RADIUS クライアントのエントリを探して削除します。
  
#### ディレクトリ サービス管理
  
ディレクトリ サービスによって、ユーザーやアプリケーションは、ユーザー、サーバー、アプリケーション、ツール、サービス、その他のネットワーク上の情報などネットワーク リソースを見つけることができます。 ディレクトリ サービス管理では、エンタープライズ ディレクトリで毎日実行する操作、保守、およびサポートを管理します。 ディレクトリ サービス管理では、承認を受けた要求者が、ネットワーク経由で情報を体系化された簡単な方法で確実に利用できるようにします。
  
##### ユーザーとコンピュータの WLAN アクセスを有効にする
  
WLAN へのアクセスを有効にするには、3 つの独立したタスクを実行する必要があります。 これらのタスクはすべてセキュリティ グループ メンバシップによって制御されるので、VBScript、Jscript、コマンド (バッチ) ファイル スクリプトなどを使って簡単に自動化できます。 多くの組織では、これらのタスクを WLAN ロールアウトの異なる段階で実行するので、タスクは個別に文書化されています。
  
**重要 :** このソリューションでは、カスタム セキュリティ グループを使用して、WLAN 証明書とポリシー設定を受け取るユーザーとコンピュータ、および IAS で WLAN にアクセスするユーザーとコンピュータを制御します。 このため、証明書、ポリシー設定、および WLAN アクセスを段階的に導入できるように、これらの 3 つの項目に対して個別のグループを使用します。 このような緻密な制御を必要としない場合は、これらの項目のいずれかまたはすべてに対して、すべてのユーザーとコンピュータを有効にできます。 すべてのユーザーとコンピュータを簡単に有効にするには、該当する証明書登録グループ、WLAN グループ ポリシー グループ (コンピュータのみ)、および WLAN アクセス グループにドメイン ユーザーまたはドメイン コンピュータを追加します。
  
**コンピュータの WLAN アクセスを有効にするには**
  
1.  第 11 章の「ユーザーまたはコンピュータが証明書の種類を登録 (または自動登録) できるようにする」の手順に従って、コンピュータ アカウントを証明書登録グループ **AutoEnroll Client Authentication – Computer Certificate** に追加します。
  
2.  このセクションで後述する「コンピュータのワイヤレス設定を有効にする」の手順に従って、コンピュータに適切なネットワーク設定を行います。 コンピュータ アカウントをポリシー グループ **Wireless Network Policy – Computer** に追加します。
  
3.  このセクションで後述する「リモート アクセス ポリシー グループにコンピュータとユーザーを追加する」の手順に従って、コンピュータの WLAN への接続を承認します。 コンピュータ アカウントをリモート アクセス セキュリティ グループ **Remote Access Policy – Wireless Computers** に追加します。
  
    **重要 :** これらの手順の実行順序は任意です。 大規模な展開の場合は、WLAN ハードウェアを有効にする前に、これらの手順をすべて実施しておきます。 これらの各手順で割り当てられたグループ メンバシップを受け取るために、コンピュータを少なくとも 1 回は*再起動する必要があります*。 ある程度時間が経過するとコンピュータのログオン トークンがタイムアウトになり、グループ メンバシップが更新されますが、このプロセスには最大 1 週間かかります。  
    初回証明書と初回ワイヤレス設定を受け取るには、コンピュータをワイヤード ネットワークに*接続する必要があります*。 その後の証明書の更新とワイヤレス設定の変更は、WLAN 経由で受け取ることができます。
  
**ユーザーの WLAN アクセスを有効にするには**
  
1.  第 11 章の「ユーザーまたはコンピュータが証明書の種類を登録 (または自動登録) できるようにする」の手順に従って、ユーザー アカウントを証明書登録グループ **AutoEnroll Client Authentication – User Certificate** に追加します。
  
2.  承認を受けた構成済みの WLAN コンピュータを使用してユーザーがログオンしていることを確認してください (前の手順を参照)。 特に、コンピュータは適切な WLAN ポリシー設定を使用して構成されている必要があります。
  
3.  このセクションで後述する「リモート アクセス ポリシー グループにコンピュータとユーザーを追加する」の手順に従って、コンピュータの WLAN への接続を承認します。 ユーザー アカウントをリモート アクセス セキュリティ グループ **Remote Access Policy – Wireless Users** に追加します。
  
    **重要 :** これらの手順の実行順序は任意です。WLAN ハードウェアを実際に展開して有効にする前に、これらの手順を実行することもできます。 これらの各手順で割り当てられたグループ メンバシップを受け取るために、ユーザーは少なくとも 1 回は*ログオフしてログオンし直す必要があります*。 ある程度時間が経過するとユーザーのログオン トークンがタイムアウトになり、グループ メンバシップが更新されますが、このプロセスには最大 1 週間かかります。  
    ユーザーが初回証明書を受け取るには、コンピュータをワイヤード ネットワークに*接続する必要があります*。 その後の証明書の更新は、WLAN 経由で受け取ることができます。
  
##### コンピュータのワイヤレス設定を有効にする
  
クライアント コンピュータのワイヤレス ネットワーク設定 (802.11 や 802.1X の設定など) の構成は、Active Directory グループ ポリシーで自動化されます。 任意のコンピュータをセキュリティ グループに追加することで、ワイヤレス ネットワーク設定を受け取るコンピュータを制御します。 セキュリティ グループを使用すると、グループのメンバのみがポリシー設定を受け取るようにグループ ポリシー オブジェクト (GPO) をフィルタリングできます。 このタスクは、ワイヤレス ネットワークを使用するコンピュータを新しく導入するたびに実行する必要があります。
  
###### 要約情報
  
-   **セキュリティ要件** : Domain Admins のメンバシップ、または Active Directory の Wireless Network Policy – Computer セキュリティ グループにユーザーを追加する権限
  
-   **実行頻度** : モバイル コンピュータがネットワークに追加された時点
  
-   **技術要件** : \[Active Directory ユーザーとコンピュータ\] MMC スナップイン
  
###### タスクの詳細
  
ワイヤレス ネットワーク ポリシーを構成し、動作可能な状態にしたら、ポリシーのアプリケーションを制御するセキュリティ グループにコンピュータを追加するのが一般的かつ直接的な方法です。
  
**ワイヤレス ネットワーク グループ ポリシーのセキュリティ グループにコンピュータを追加するには**
  
1.  \[Active Directory ユーザーとコンピュータ\] MMC スナップインで、適用するワイヤレス ネットワーク ポリシーに対応した Wireless Network Policy – Computer セキュリティ グループを探します。 このグループのメンバシップを変更するアクセス許可を持つユーザーとしてログオンする必要があります。
  
2.  選択したセキュリティ グループにコンピュータを追加します。
  
    **注 :** この新しいグループ メンバシップを反映してワイヤレス ポリシーを適用するには、コンピュータを再起動する必要があります。 ワイヤレス ポリシーを初めて適用するときは、ワイヤレス設定を受け取るためにコンピュータをワイヤード ネットワークに*接続する必要があります*。 その後の変更は、WLAN 経由で適用することができます。
  
##### リモート アクセス ポリシー グループにコンピュータとユーザーを追加する
  
コンピュータとユーザーを Remote Access Policy セキュリティ グループに追加すると、WLAN にアクセスできるようになります。 IAS は、Remote Access Policy 内にあるこのグループのメンバシップをアクセス許可の優先順位を判断する条件として使用します。 WLAN に対する確実な認証を有効にするには、コンピュータとユーザーを Remote Access Policy グループに追加する必要があります。
  
###### 要約情報
  
-   **セキュリティ要件 :** Domain Admins、または Active Directory の Remote Access Policy - Wireless Users および Remote Access Policy - Wireless Computers セキュリティ グループのメンバを変更するアクセス許可
  
-   **実行頻度 :** ユーザーが WLAN へのアクセスを許可された時点
  
-   **技術要件** : \[Active Directory ユーザーとコンピュータ\] MMC スナップイン
  
###### タスクの詳細
  
Remote Access Policy セキュリティ グループを構成して動作可能な状態にしたら、WLAN アクセスを制御するセキュリティ グループにその他のコンピュータとユーザーを追加するのが一般的で直接的な方法です。
  
**リモート アクセス ポリシーのセキュリティ グループにユーザーを追加するには**
  
1.  Domain Admins のメンバ、または Remote Access Policy - Wireless Users セキュリティ グループのメンバを更新できるセキュリティ権限を持つアカウントで管理コンピュータにログオンします。
  
2.  \[Active Directory ユーザーとコンピュータ\] MMC スナップインで、ワイヤレス LAN アクセスを制御するリモート アクセス ポリシーに対応した Remote Access Policy - Wireless Users セキュリティ グループを探します。
  
3.  選択したセキュリティ グループにユーザーを追加します。
  
    **注 :** 新しいグループ メンバシップを受け取って WLAN にアクセスするために、ユーザーはいったんログオフしてログオンし直す必要があります。
  
**リモート アクセス ポリシー セキュリティ グループにコンピュータを追加するには**
  
1.  Domain Admins のメンバ、または Remote Access Policy - Wireless Computers セキュリティ グループのメンバを更新できるセキュリティ権限を持つアカウントで管理コンピュータにログオンします。
  
2.  \[Active Directory ユーザーとコンピュータ\] MMC スナップインで、ワイヤレス LAN アクセスを制御するリモート アクセス ポリシーに対応した Remote Access Policy - Wireless Computers セキュリティ グループを探します。
  
3.  選択したセキュリティ グループにコンピュータを追加します。
  
    **注 :** この新しいグループ メンバシップを受け取って WLAN にアクセスするには、コンピュータを再起動する必要があります。
  
#### サービスの監視と管理
  
サービス監視により、運用スタッフが、リアルタイムで IT サービスの健全性を監視できます。
  
ここで Microsoft Operations Manager (MOM) について述べている場合は、「MOM Operations Guide」(英語) のガイドラインに従って MOM がインストールされていることを前提としています。 ただし、MOM は必須ではありません。単に例として使用されています。 「MOM Operations Guide」の詳細については、この章の最後にある「関連情報」を参照してください。
  
##### 監視の警告を分類する
  
監視システムでは、運用スタッフに最も重要な警告だけを発する必要があります。 比較的重要でないエラーがすべてエスカレートされて障害警告が生成されると、運用スタッフは混乱し、どれが緊急で、どれが緊急でないかを直ちに判断できなくなります。
  
###### 要約情報
  
-   **セキュリティ要件** : なし
  
-   **実行頻度** : セットアップ タスク
  
-   **技術要件** : 操作警告コンソール (MOM など)
  
###### タスクの詳細
  
このドキュメントでは、次の警告カテゴリが使用されます。 カテゴリの上位 3 つ (サービスは利用できない、セキュリティ違反、および致命的なエラー) だけをオペレータ コンソールに警告表示して、速やかに注意を喚起する必要があります。 エラーと警告は緊急ではないため、RADIUS および WLAN 運用サポート スタッフで解決します。 これらのイベント カテゴリは MOM が使用する既定値です。このセクションの次のタスクの説明で参照しています。
  
**表 12.8: 警告カテゴリ**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >警告カテゴリ</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">サービスは利用できない</td>
<td style="border:1px solid black;">アプリケーションまたはコンポーネントが完全に利用できない場合。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">セキュリティ違反</td>
<td style="border:1px solid black;">アプリケーションがハッキングされている場合またはセキュリティを侵害された場合。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">致命的なエラー</td>
<td style="border:1px solid black;">アプリケーションで、早急な (ただし即時とは限らない) 管理措置の必要な重大なエラーが検出された場合。 アプリケーションまたはコンポーネントは、標準以下のレベルのパフォーマンスで動作していますが、それでもほとんどの重要な操作を実行できます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">エラー</td>
<td style="border:1px solid black;">アプリケーションで、即時の管理措置や解決を必要としない一時的な問題が検出された場合。 アプリケーションまたはコンポーネントは、許容レベルのパフォーマンスで動作していますが、それでもほとんどの重要な操作を実行できます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">警告</td>
<td style="border:1px solid black;">アプリケーションで、即時の管理措置や解決を必要としない警告メッセージが生成された場合。 アプリケーションまたはコンポーネントは、許容レベルのパフォーマンスで動作していますが、それでもほとんどの重要な操作を実行できます。 ただし、問題が続く場合は、この状況が &quot;エラー&quot;、&quot;致命的なエラー&quot;、または &quot;サービスは利用できない&quot; に変化する可能性があります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">情報</td>
<td style="border:1px solid black;">アプリケーションが情報イベントを生成した場合。 アプリケーションまたはコンポーネントは、許容レベルのパフォーマンスで動作しており、重要な操作や重要でない操作を実行しています。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">成功</td>
<td style="border:1px solid black;">アプリケーションが成功イベントを生成した場合。 アプリケーションまたはコンポーネントは、許容レベルのパフォーマンスで動作しており、重要な操作や重要でない操作を実行しています。</td>
</tr>
</tbody>
</table>
  
##### IAS の容量制約を監視する
  
潜在的な容量制約を検出することは、サービスを最適レベルに維持するために欠かせません。 サブシステムが動作容量の限界に近くなると、パフォーマンスは急速に (通常は非直線的に) 低下します。 したがって、容量の利用傾向を監視し、今後の制約の傾向を早期に特定して対処することが重要です。
  
###### 要約情報
  
-   **セキュリティ要件** : 監視ソリューションで指示された必要なアクセス許可
  
-   **実行頻度** : セットアップ タスク
  
-   **技術要件** :
  
    -   パフォーマンス モニタ
  
    -   パフォーマンス カウンタ コンソリデータ (MOM など)
  
    -   操作警告コンソール (MOM など)
  
    -   容量計画ツール
  
###### タスクの詳細
  
次に示すパフォーマンス カウンタは、IAS の容量制約を特定するうえで最も役立ちます。 プロセッサとディスクは、IAS で最も集中的に使用される 2 つのリソースなので、ネットワークやメモリより早い段階で制約が示される可能性があります。
  
**表 12.9: IAS 容量制約パフォーマンス オブジェクトの監視項目**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >パフォーマンス オブジェクト</th>
<th style="border:1px solid black;" >パフォーマンス カウンタ</th>
<th style="border:1px solid black;" >インスタンス</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Processor</td>
<td style="border:1px solid black;">% Processor Time</td>
<td style="border:1px solid black;">_Total</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Physical Disk</td>
<td style="border:1px solid black;">% Disk Time</td>
<td style="border:1px solid black;">_Total</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Physical Disk</td>
<td style="border:1px solid black;">Avg. Disk Read Queue Length</td>
<td style="border:1px solid black;">_Total</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Physical Disk</td>
<td style="border:1px solid black;">Avg. Disk Write Queue Length</td>
<td style="border:1px solid black;">D: (IAS–DATA)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Network Interface</td>
<td style="border:1px solid black;">Bytes Total/sec</td>
<td style="border:1px solid black;">NW adapter</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Memory</td>
<td style="border:1px solid black;">% Committed Bytes in use</td>
<td style="border:1px solid black;">---</td>
</tr>
</tbody>
</table>
  
容量制約全般の情報および関連パフォーマンス カウンタの詳細については、この章の最後にある「関連情報」の参照情報を参照してください。
  
また、サポートするインフラストラクチャの容量インジケータを監視することも重要です。 主な項目は、次のとおりです。
  
-   **Active Directory と IAS の通信**。 IAS では、認証および一部の認証サービスに幅広く Active Directory を使用しています。
  
-   **ワイヤレス AP などの RADIUS クライアント**。 これらのクライアントは、拡張認証プロトコル (EAP) と RADIUS プロトコルを使用してクライアントと IAS の両方と通信します。
  
-   **Active Directory とのクライアント関連の通信**。 ワイヤレス LAN クライアントでは、グループ ポリシーとネイティブなドメイン認証に Active Directory ドメイン コントローラを利用します。
  
#### 記憶域管理
  
記憶域管理は、データの復元と履歴のアーカイブにおけるオンサイトとオフサイトのデータ記憶域に対応します。 記憶域管理チームは、バックアップとアーカイブの物理的なセキュリティを確保する必要があります。 記憶域管理では、IT 運用環境におけるデータやデータ リソースの定義、追跡、および保守を行います。
  
##### IAS 構成エクスポートを構成する
  
このタスクでは、致命的なイベントが発生した後にシステムの復元を簡単に行えるように、毎晩 IAS 構成状態を部分的にエクスポートするタスクをスケジュール設定します。 完全な IAS 構成状態には、セキュリティに関係する情報である RADIUS クライアント構成が含まれています。 したがって、構成状態の RADIUS クライアント部分をエクスポートする手順については、別途詳しく説明します。 完全な運用サービスに対して各 IAS サーバーを完全に復元するには、両方の種類のバックアップが必要です。
  
IAS サーバーの完全なバックアップには、IAS サーバーが依存するオペレーティング システム構成や他の状態情報が含まれます。 このタスクは、サーバーの再インストール、オプションの IAS コンポーネントの再インストール、および構成状態の復元を実行できるように開発されています。 IAS 構成エクスポートを構成すると、既知の構成状態でなくなった (信頼できない) サーバー、またはセキュリティを侵害されたサーバーのサービスを容易に復元できます。
  
###### 要約情報
  
-   **セキュリティ要件** : ローカルの Administrators セキュリティ グループのメンバ
  
-   **実行頻度** : セットアップ タスク
  
-   **技術要件** :
  
    -   MSS スクリプト
  
    -   Windows タスク スケジューラ サービス
  
    -   SchTasks.exe
  
###### タスクの詳細
  
このタスクでは、IAS サーバーの構成状態を夜間にバックアップするようにスケジュールされたタスクを構成します。 IAS バックアップは、組織にエンタープライズ サーバー バックアップ システムが配備されていることを前提にしています。つまり、この手順で作成されるバックアップ ファイルは、組織のバックアップ システムでのバックアップに使用できます。 主なバックアップ システムには、ネットワーク バックアップ、ストレージ エリア ネットワーク (SAN) バックアップ、ローカル デバイス バックアップなどがあります。 このソリューションでは、サーバー バックアップ システムが夜間稼動して IAS サーバーのディスクをバックアップすることも想定しています。
  
**IAS 構成のバックアップを構成するには**
  
1.  次のコマンドを実行して、バックアップ ジョブを夜間実行するようにスケジュールします。 このコマンドでは、毎晩午前 2 時にジョブを実行するように設定しています。
  
    SCHTASKS /Create /RU system /SC Daily /TN "IAS Backup" /TR \\"C:\\MSSScripts\\IASExport.bat\\" /ST 02:00
  
    (このコマンドは表示の都合上複数行で示していますが、実際には 1 行で入力してください)
  
    **注 :** スクリプト名 C:\\MSSScripts\\IASExport.bat の前後にある円記号とそれに続く引用符 (\\") は、ファイル名またはパス名にスペースが含まれる場合にのみ必要です。 円記号はスクリプト名を囲む引用符の "エスケープ" 文字になり、スクリプト名が schtasks ジョブ コマンド ラインの一部として保存されるようにします。 パス名にスペースが含まれない場合、これらの記号は省略可能です。
  
2.  一時バックアップ フォルダ (C:\\CABackup) の内容を夜間リムーバブル メディアにバックアップするようにサーバー バックアップ システムを構成します。 可能であれば、条件スクリプトを設定します。この条件スクリプトは、IASExport.bat スクリプトによって生成された IAS 構成ファイルのタイムスタンプが 24 時間以内であるかどうかを検査するものです。 IAS 構成ファイルのタイムスタンプが 24 時間以上前である場合、前回のバックアップ処理が失敗したか、まだ実行中であることを意味します。
  
    **注 :** IASExport.bat スクリプトをこのタスクの開始点として使用できます。 この IASExport.bat スクリプトのロジックを変更することができます。具体的には、このスクリプト内で使用されている **netsh** ツールを実行した結果エラー状態が発生したときに、運用スタッフが認識できるイベントや通知が生成されるように変更します。
  
D:\\IASConfig ディレクトリの Windows ファイルの監査を有効にすることや、サーバー セキュリティ監査人に指示して異常なアクティビティ (アクセスの失敗など) について定期的に監査データを確認させることを検討する必要があります。 攻撃者が、D:\\IASConfig ディレクトリにある情報でネットワーク アクセス管理を脆弱にする方法を手に入れる可能性があます。
  
##### RADIUS クライアント構成をエクスポートする
  
サーバーに致命的な障害が発生した場合に構成情報を確実に復元できるように、IAS サーバーから RADIUS クライアント構成をエクスポートする必要があります。 RADIUS クライアント情報がセキュリティに関係するのは、各サーバーとワイヤレス AP の間で使用される RADIUS シークレットが含まれているためです。 したがって、RADIUS クライアント データはリムーバブル メディアにエクスポートし、このメディアを安全な場所に保管する必要があります。 エクスポートされた RADIUS クライアント構成データは、通常、IAS サーバーごとに固有の内容になります。
  
IAS サーバー構成を完全に復元するには、このタスクで作成した RADIUS クライアント構成データと前の手順の IASExport.bat スクリプトで作成した IAS システム構成データを復元する必要があります。
  
###### 要約情報
  
-   **セキュリティ要件** : IAS Admins セキュリティ グループのメンバ
  
-   **実行頻度** : セットアップ タスク
  
-   **技術要件** :
  
    -   MSS スクリプト
  
    -   フロッピー ディスクまたは他の書き込み可能なリムーバブル メディア
  
###### タスクの詳細
  
RADIUS クライアント構成情報をエクスポートするには、**netsh** コマンドを使用します。 このガイドではバッチ ファイルを使用します。このバッチ ファイルは、RADIUS クライアント情報をフロッピー ディスクなどのリムーバブル メディアにエクスポートするものです。
  
**RADIUS クライアント構成をエクスポートするには**
  
1.  RADIUS クライアント データの保存元となる IAS サーバーにログオンし、コマンド プロンプトで次のコマンドを実行します。
  
    C:\\MSSScripts\\IASClientExport.bat
  
2.  エラーや警告が表示されていないかどうかを調べ、表示されている場合は問題点を修正します。 修正が完了したら、スクリプトを再度実行します。
  
3.  バックアップ メディアを適切に保管します。 このバックアップ データには、社内の WLAN にアクセスする際に使用される RADIUS シークレットが含まれているので、特に慎重に扱う必要があります。 このデータは、IAS サーバー自体と同等のセキュリティ レベルで取り扱ってください。 バックアップ データは、IAS サーバー自体とは物理的に異なるサイトに保管してください。別のサイトに保管することで、IAS のサイトのコンピュータ設備がすべて破壊されたり、設備にアクセスできなくなった場合でも、IAS サーバーを回復することができます。
  
##### IAS データ ディレクトリのバックアップを構成する
  
このタスクの目的は、致命的なサーバー イベントが発生した後に IAS 構成状態と RADIUS ログ データの完全なシステム復旧が確実にできるように、IAS サーバーのバックアップが必要なディレクトリに関するガイダンスを提供することです。 IAS サーバーの完全なバックアップには、IAS サーバーが依存するオペレーティング システム構成や他のシステム状態情報が含まれます。
  
###### 要約情報
  
-   **セキュリティ要件** : ローカルの Backup Operators セキュリティ グループのメンバ
  
-   **実行頻度** : セットアップ タスク
  
-   **技術要件** :
  
    -   Windows バックアップまたはエンタープライズ バックアップ システム
  
    -   Windows タスク スケジューラ サービス
  
    -   SchTasks.exe
  
###### タスクの詳細
  
このタスクでは、IAS 構成状態とログ ファイル データを完全に復元できるように、バックアップする必要のあるディレクトリの一覧を示します。 このタスクは、エンタープライズ サーバー バックアップ システムが配備されていることを前提にしています。 配備されているシステムとしては、ネットワーク バックアップ、SAN バックアップ、ローカル デバイス バックアップなどが考えられます。 このソリューションでは、エンタープライズ サーバー バックアップ システムが夜間 (02:00) 稼動して IAS サーバーのディスクをバックアップすることも想定しています。
  
**IAS データ ディレクトリ バックアップを構成するには**
  
1.  IAS 構成状態バックアップが正しくスケジュール設定され、正常に実行していることを確認します。 IAS 構成状態スケジュール タスクは、IAS 構成状態をハード ディスクのファイルに出力します。
  
2.  メモ帳を使用して、D:\\IASLogs ディレクトリに backuptest.txt というファイルを作成します。 このファイルに、「**バックアップと復元の検証用**」と入力します。 ファイルを保存してメモ帳を閉じます。 このファイルは、後ほど復元の検証手順に使用します。
  
    次のディレクトリの完全バックアップ、増分バックアップ、または差分バックアップを実行するようにエンタープライズ サーバー バックアップ システムを構成します。
  
    -   D:\\IASConfig
  
    -   D:\\IASLogs
  
3.  サーバー バックアップ システムのログ ファイルを表示してエラーまたは警告が発生していないことを確認します。 エラーまたは警告が検出された場合は、IAS 構成エクスポート スクリプトを手動で実行し、両方のディレクトリの完全バックアップを別に実行することを検討してください。
  
4.  バックアップ メディアを適切に保管します。 このバックアップ データには、組織の WLAN にアクセスする際に使用される RADIUS シークレットが含まれているので、特に慎重に扱う必要があります。 このデータは、IAS サーバー自体と同等のセキュリティ レベルで取り扱ってください。 バックアップ データは、IAS サーバー自体とは物理的に異なるサイトに保管してください。別のサイトに保管することで、IAS のサイトのコンピュータ設備がすべて破壊されたり、設備にアクセスできなくなった場合でも、IAS サーバーを回復することができます。
  
##### IAS バックアップをテストする
  
このタスクの目的は、テスト復元を実行することによってバックアップ プロセスとバックアップ テクノロジが正しく実行されることを確認することです。 予備のサーバー ハードウェアでバックアップを完全に復元できれば、バックアップ手順が正しく機能していることを確認できます。 ただし、この手順は、予備のサーバー ハードウェアを使用できないユーザーが、ある程度のリスクを認識した上で運用ハードウェアで復元手順をテストできるように作成されています。 運用サーバーで復元手順をテストすると、部分的な復元ではサーバーが使用できない状態のままになるというリスクが生じます。
  
バックアップのテストを行うことで、致命的なイベントが発生したときの復元手順に習熟し、処理を完了する障害になる操作上または技術上のエラーを無くせます。
  
IAS サーバー復元データは、次のデータで構成されます。
  
-   **IAS 構成状態エクスポート データ**。 D:\\IASConfig ディレクトリに格納されています。 テープから復元する場合、この情報を使用して IAS サーバーに構成をインポートします。この章の「IAS 構成エクスポートを構成する」タスクの手順に従って作成されます。
  
-   **RADIUS クライアント エクスポート データ**。 "*&lt;サーバー名&gt;* の RADIUS クライアント" というラベルのフロッピー ディスクまたは他の書き込み可能なリムーバブル メディアに格納されています。この情報は、RADIUS クライアント構成を IAS サーバーに復元するために使用されます。この章の「RADIUS クライアント構成をエクスポートする」タスクの手順に従って作成されます。
  
-   **RADIUS 要求ログ データ**。 D:\\IASLogs ディレクトリに格納されています。 テープから復元する場合、この情報には IAS セキュリティ監査人が使用する履歴データが含まれています。 このデータは、IAS サービスが RADIUS 情報のログをディスクに記録するときに作成されます。
  
テスト復元を実行する前に、IAS 構成エクスポート データと RADIUS クライアント エクスポート データを手動でエクスポートする必要があります。 その後、スケジュール設定されていないバックアップを実行し、サーバー データを専用のテープにバックアップします。このデータは別途保管しておき、テスト復元中に問題が発生した場合のみ使用します。 このアプローチにより、正常なバックアップ中に見過ごされる恐れのある不正なテープやエラーが運用サーバーに部分的に復元されてしまうというリスクが軽減されます。
  
###### 要約情報
  
-   **セキュリティ要件** : テスト コンピュータのローカルの Administrators または Backup Operators
  
-   **実行頻度** :
  
    -   IAS サーバーが運用状態になる前
  
    -   毎月
  
    -   バックアップのテクノロジまたはプロセスが変更された場合に再テスト
  
-   **技術要件** :
  
    -   Windows バックアップまたはエンタープライズ バックアップ システム
  
    -   MSS スクリプト
  
###### タスクの詳細
  
このタスクでは、IAS データの復元と検証について詳しく説明します。 3 種類のデータすべてが復元され、特別な手順で復元が検証されます。 正常に完了した最新の (前夜の) 完全バックアップを必ず使用してください。 また、テストを開始する前に、最後のバックアップ以後にターゲット サーバーで管理作業 (何らかの構成変更など) が行われていないことを確認してください。
  
新しくインストールされた Windows Server 2003 のコピーを復元する場合は、「第 8 章 : RADIUS インフラストラクチャを実装する」の必須のサーバー構築手順を実行して、IAS のサーバー ハードウェアとソフトウェアを正しく構成する必要があります。
  
**注 :** 復元された WLAN リモート アクセス ポリシー内の新たにインストールされた RAS と IAS サーバー認証証明書の再選択を必要とする可能性があります。
  
**IAS バックアップをテストするには**
  
**注 :** この手順の最初の段階は省略可能であり、非運用サーバー ハードウェアのテスト環境で実行されます。 また、サーバーを不安定な状態やセキュリティ侵害された状態から復旧できるようにするうえで役立ちます。
  
1.  ハードウェアまたはソフトウェアに回復不能な障害が発生したサーバー、またはセキュリティを侵害されたサーバー (ウイルス感染など) を復元するには、「第 8 章 : RADIUS インフラストラクチャを実装する」の手順に従って Windows Server 2003 を再インストールします。MSS スクリプトを配布メディアからサーバーの C:\\MSSScripts ディレクトリに必ずコピーしてください。
  
2.  D:\\IASLogs ディレクトリに移動して、backuptest.txt ファイルを探します。 このファイルが存在しない場合は、次の手順に進みます。 backuptest.txt ファイルが見つかった場合は、それを削除します。 backuptest.txt ファイルは、「IAS データ ディレクトリのバックアップを構成する」の手順で作成されます。 このファイルは IAS RADIUS 要求ログとともにバックアップされます。このファイルを使用すると、RADIUS ログを復元せずにデータをバックアップから復元できるかどうかを確認できます。 場合によっては、代わりに D:\\IASLogs から実際の RADIUS 要求ログ データを復元してもかまいません。 ただし、ログ ファイル データに上書きすると、復元が失敗した場合にデータが失われる可能性があります。
  
3.  \[インターネット認証サービス\] MMC スナップインを開いて、**\[インターネット認証サービス (ローカル)\]** オブジェクトのプロパティを選択し、**\[全般\]** タブを調べます。 **\[説明\]** フィールドに「**(復元テスト)**」というテキストを追加します。 **\[OK\]** をクリックし、\[プロパティ\] ダイアログ ボックスを閉じます。 サーバーの説明文字列を変更すると、前にバックアップした IAS 構成の設定が復元されているかどうかを確認できます。 前の IAS 構成の設定を復元すると、**説明**文字列が以前の値で上書きされ、"**(復元テスト)**" というテキストが表示されなくなります。
  
4.  **\[インターネット認証サービス\]** MMC スナップインで、**\[RADIUS クライアント\]** フォルダを右クリックし、**\[新しい RADIUS クライアント\]** をクリックします。 **\[フレンドリ名\]** に「**復元テスト**」と入力し、**\[クライアントのアドレス (IP または DNS)\]** に「**127.0.0.1**」と入力します。 この RADIUS クライアントの **\[共有シークレット\]** と **\[共有シークレットの確認入力\]** のフィールドにパスワードを入力し、**\[完了\]** をクリックします。 復元が成功すると、RADIUS クライアント情報が上書きされ、この新しい RADIUS が表示されなくなります。
  
5.  テストするバックアップ メディア (スケジュールで実行された前夜のバックアップなど) を用意し、それを使用してサーバーのハード ディスクに次のデータを復元します。
  
    -   D:\\IASConfig\\\*.\*
  
    -   D:\\IASLogs\\BACKUPTEST.TXT
  
6.  以前にテキスト ファイルとして保存した IAS 構成を IAS データベースに復元するには、コマンド プロンプトで次のコマンドを実行します。 スクリプトの実行中に表示されたエラーや警告は必ず調査してください。
  
    C:\\MSSScripts\\IASImport.bat
  
    **注 :** 以降の手順では、フロッピー ディスクなどの書き込み可能なリムーバブル メディアを使用します ("*&lt;サーバー名&gt;* の RADIUS クライアント" というラベルが貼られています)。データの損失を防ぐために、サーバーに対応した正しいディスクを使用してください。
  
7.  このサーバーの RADIUS クライアント構成フロッピー ディスクまたは他の書き込み可能なリムーバブル メディアを探して、それをサーバーのドライブに挿入します。 コマンド プロンプトで次のコマンドを実行します。 スクリプトの実行中に表示されたエラーや警告は必ず調査してください。
  
    C:\\MSSScripts\\IASClientImport.bat
  
8.  **\[インターネット認証サービス\]** MMC スナップインを閉じてから再度開き、**\[インターネット認証サービス (ローカル)\]** オブジェクトのプロパティを選択し、**\[全般\]** タブを調べて "**(復元テスト)**" というテキストが **\[説明\]** フィールドに表示されなくなったことを確認します。 **\[OK\]** をクリックし、**\[IAS のプロパティ\]** ダイアログ ボックスを閉じます。
  
9.  \[RADIUS クライアント\] フォルダを選択し、**\[復元テスト\]** RADIUS クライアントが右側のクライアント リストに表示されなくなったことを確認します。
  
10. **\[インターネット認証サービス\]** MMC スナップイン内の他のすべての構成では、復元テストより前の設定が表示されるはずです。
  
11. D:\\IASLogs ディレクトリに移動して、backuptest.txt ファイルが存在することを確認します。 この手順を使用して運用サーバーを復元した場合は、ログ ファイルが少なくともバックアップ時点と同じで最新の状態であることを確認するために、IAS セキュリティ監査人にログ ファイルを検査してもらいます。
  
12. バックアップ メディアやフロッピー ディスクを安全な保管場所に戻す必要があります。
  
#### セキュリティ管理
  
セキュリティ管理は、安全なコンピューティング環境を実現します。 セキュリティは、エンタープライズ IT インフラストラクチャで重要な部分を占めます。 セキュリティ インフラストラクチャの脆弱な情報システムは、最終的にセキュリティが侵害されることになります。
  
##### IAS RADIUS 要求ログへアクセスする
  
IAS では、必要に応じてワイヤレス AP の RADIUS 要求から生じる各種イベントを、サーバーのハード ディスクに格納されている RADIUS 要求ログに記録できます。 RADIUS ログは、システム上の潜在的な攻撃や組織のネットワークへの許可されていないアクセスを特定するなど、数多くの理由から有用です。 このタスクでは、RADIUS 要求ログの検査方法について説明します。ただし、RADIUS 要求ログの分析の詳細については、このガイドでは説明しません。
  
RADIUS 要求ログは、IAS 形式またはデータベース インポート形式のテキストとして格納されるので、さまざまな方法で分析できます。 コンマ区切りのテキスト ファイルを読み込めるアプリケーションにインポートすることが比較的容易に実行できることから、このソリューションでは、ログ ファイルにデータベース インポート形式を採用しています。 IAS RADIUS 要求ログは次のような方法で確認できます。
  
-   **IASPARSE ユーティリティを使用してログ ファイルを直接参照する**。 このツールは Windows Server 2003 サポート ツール から利用可能です。パフォーマンスを確保するために、通常、このツールは IAS サーバー自体にインストールされて実行されます。 このため、リモート デスクトップ接続 (またはその他のリモート実行方法による) セッションが必要です。 既定では、このソリューションは、このユーティリティを使用してログ ファイルを表示するように構成されていません。
  
-   **リモート管理コンピュータから Microsoft Access 2002 にログ ファイルをインポートする**。 この方法により、管理者は、緊急のクエリ用、または構造化されたレポートおよびアーカイブの方式の一部として、ログを Microsoft Access テーブルにインポートできます。 わかりやすさと柔軟性のバランスが取れているため、このソリューションでは、ログ ファイルの表示にこの方法を採用しています。 エンタープライズ ユーザーの場合は、後述の Microsoft SQL Server™ 2000 ベースのログ記録方法も考慮する必要があります。
  
-   **中央 SQL Server 2000 クラスタ経由でログ情報にアクセスする**。このログ情報のデータは、各 IAS サーバーの MSDE 2000 によって複製されます。 各 IAS サーバーは、MSDE のローカル インスタンスにログを記録します。 この方法のセットアップは複雑ですが、マイクロソフトでは、このプロセスの実施を支援するためにホワイト ペーパーとコードを作成しています。 この SQL ログ記録のセットアップの支援を受ける場合は、マイクロソフトのパートナーに相談するか、マイクロソフトの営業担当に連絡して適切なパートナーまたは Microsoft Consulting Services の専門家について問い合わせてください。
  
###### 要約情報
  
-   **セキュリティ要件** : IAS Security Auditors セキュリティ グループのメンバ
  
-   **実行頻度** : 毎日または毎週 (セキュリティ要件による)
  
-   **技術要件** :
  
    -   IASPARSE
  
    -   Microsoft Access
  
    -   Microsoft Excel
  
###### タスクの詳細
  
RADIUS 要求ログは、このソリューションの各サーバーで生成され、専用のディスク ボリュームに格納されます。 このログ ファイルにアクセスする手順には、各 IAS サーバーへのネットワーク接続の確立、ログ ファイルの確認、およびログ ファイルが不要になった場合の削除方法が含まれます。 このソリューションの IAS サーバーは、毎月新しい RADIUS 要求ログ ファイルを作成するように構成されますが、作成頻度は各自のニーズに合わせて変更できます。
  
Access で作成するテーブルは、各フィールドに含まれているデータの種類に従って書式設定されます。 この例では新しいテーブルの作成方法を示していますが、既存のテーブルにログをインポートすることもできます。
  
**RADIUS 要求ログ ファイルを Microsoft Access にインポートするには**
  
1.  Active Directory の IAS Security Auditors セキュリティ グループのメンバとして管理ワークステーションにログオンし、ログを確認する IAS サーバーのドライブをネットワーク ドライブに割り当てます。 コマンド プロンプトに次のコマンドを入力します。Q-IAS-01 は IAS サーバーの実際の名前に置き換えてください。
  
    NET USE X: \\\\HQ-IAS-01\\IASLogs
  
2.  表示する月のログ ファイルを探します。 ログ ファイル名には、ファイルが作成された日付が含まれています。 ログ ファイルのコピーを作成し、コピーしたファイルの拡張子を .txt に変更します。
  
3.  コピーしたログ ファイルの先頭に、テキスト ファイル C:\\MSSScripts\\IASAccessPrep.txt に記載されている 2 行をそのまま追加します。 最初の行にはログの各フィールドの属性名が含まれており、Access ではこの属性名がテーブルのフィールド名になります。 テーブルで属性名を使用することで、ログ エントリを解釈しやすくなります。 2 行目は、Access がテーブルの各列に適切なデータ型をセットアップするために使用されます。 これらのエントリは、ログ ファイルをインポートした後に Access のテーブルから削除する必要があります。
  
4.  Access 2002 で、**\[空のデータベース\]** をクリックします。 **\[新しいデータベース\]** でファイル名を指定し、**\[データを入力してテーブルを作成する\]** をクリックします。 **\[ファイル\]**、**\[外部データの取り込み\]**、**\[インポート\]** の順にクリックします。
  
5.  **\[インポート\]**、**\[ファイルの種類\]**、**\[テキスト ファイル\]** の順にクリックします。次に、IAS ログ ファイルを探し、それを選択して、**\[インポート\]** をクリックします。 **テキスト インポート ウィザード**で、**\[詳細\]** をクリックします。
  
6.  **\[インポート定義\]** をクリックします。
  
7.  **\[ファイル形式\]** で、**\[区切り記号付き\]** をクリックします。
  
8.  **\[フィールド区切り記号\]** で、**\[,\]** (コンマ) を選択します。
  
9.  **\[文字列の引用符\]** で、\["\] (引用符) を選択します。
  
10. **\[日付、時刻、数値\]** で、**\[西暦を 4 桁で表示\]** と **\[日付に 0 を表示\]** を選択し、**\[日付順\]** (\[月日年\] など)、**\[日付区切り記号\]** (\[**/**\]など)、**\[時刻区切り記号\]** (\[**:**\] など)、および **\[小数点記号\]** (\[.\] など) を入力します。
  
11. **\[テキスト インポート ウィザード\]** ダイアログ ボックスで、**\[次へ\]** をクリックし、**\[先頭行をフィールド名として使う\]** を選択して、**\[次へ\]** をクリックします。 **\[新規テーブルに保存する\]** を選択し、**\[次へ\]** をクリックします。
  
12. **\[フィールドのオプション\]** を既定値のままにして、**\[次へ\]** をクリックします。 **\[主キーを自動的に設定する\]** を選択して、**\[次へ\]** をクリックします。 **\[インポート先のテーブル\]** に、新しいテーブルの名前を入力します。 **\[完了\]** をクリックします。
  
13. **\[ファイル名 : データベース\]** ダイアログ ボックスで、データベースの名前を入力し、**\[開く\]** をクリックしてテーブルを表示します。
  
##### IAS RADIUS 認証イベント ログ エントリを確認する
  
セキュリティ監査人は、このタスクを定期的に実行することにより、ワイヤレス ネットワークへの不正アクセスの試みがあるかどうかを調べることができます。 イベント ログ内の RADIUS 認証関連のイベントを定期的に確認して認証を受けようとする試みや証明書の資格情報の盗用を検出する必要があることが、内部向けのセキュリティ方針に規定されている場合もあります。 MOM などの管理ツールを使用して、疑わしいイベントがログされたときに警告を表示することもできます。
  
このタスクはオプションですが、前述の IAS RADIUS ログの代わりに使用することもできます。 このタスクを実行するには、IAS Admins グループまたはサーバーのローカル Administrators グループのメンバである必要があります。
  
###### 要約情報
  
-   **セキュリティ要件** : IAS Admins グループまたはローカルのビルトイン Administrators グループのメンバ
  
-   **実行頻度** : 毎日または毎週 (セキュリティ要件による)
  
-   **技術要件** :
  
    -   イベント ビューア
  
    -   必要に応じて Windows Server 2003 リソース キットの EventCombMT または EventFilter
  
###### タスクの詳細
  
このタスクは、IAS のセキュリティ監査人と IAS のシステム管理者を同じ人が兼務している IT 環境に適しています。 これに対し、RADIUS ログは、サーバーのローカル管理者ではないオペレータが見ることができます。 このソリューションでは、ローカルの Administrator 権限をセキュリティ監査人に与えません。 このため、このタスクを実行する前に、監査人を Active Directory の IAS Admins セキュリティ グループに追加する必要があります。
  
**イベント ビューアでイベント ログを調べて認証失敗の有無を確認するには**
  
1.  いずれかの IAS サーバーに、IAS Admins セキュリティ グループのメンバとしてログオンします。
  
2.  イベント ビューアを開きます (**\[スタート\]** ボタン、**\[すべてのプログラム\]**、**\[管理ツール\]**、\[イベント ビューア\] の順にクリックします)。
  
3.  **システム イベント**を示すログをクリックします。
  
4.  **\[表示\]** メニューの **\[フィルタ\]** をクリックします。
  
5.  **\[イベント ソース\]** ボックスの一覧の **\[IAS\]** をクリックし、**\[イベント ID\]** ボックスに「**2**」と入力します。
  
6.  何度も発生している認証失敗や他の不審なエントリを調べます。
  
    **注 :** IAS イベントは、Eventquery ツール (Windows XP および Windows Server 2003) と Windows Server 2003 リソース キットの EventFilter または EventCombMT ツールを使用して表示することもできます。
  
##### IAS RADIUS ログ ファイルをアーカイブおよび削除する
  
IAS には、ログ ディスクが最大サイズに達したときに古い IAS RADIUS ログ ファイルを削除する機能があります。 この自動機能を使用しない場合は、IAS のディスク容量が不足しないように、IAS RADIUS 要求ログの保存と削除を手動で行う必要があります。 ディスク容量が不足すると、ワイヤレス AP からの認証およびアカウンティング要求に対して IAS が応答できなくなります。 スクリプトまたは SQL Server 2000 による自動レプリケーションを使用してログ アーカイブを自動化することもできます (「この章で前述した「IAS RADIUS 要求ログへアクセスする」タスクを参照)。
  
**注 :** このソリューションでは、IAS 機能を使用して、ディスクが最大サイズに達したときに古いログ ファイルを自動的に削除しています。
  
###### 要約情報
  
-   **セキュリティ要件** : Active Directory の IAS Security Auditors セキュリティ グループのメンバ
  
-   **実行頻度** : 毎月
  
-   **技術要件** : Windows のネイティブ コマンド
  
###### タスクの詳細
  
RADIUS 認証とアカウンティング要求ログは、さまざまな方法でアーカイブおよび削除できます。 たとえば、サーバーベースのバックアップ スクリプトを使用する場合、IAS のセキュリティ監査人は、ログ ファイルのバックアップが正常に完了したことを電子メールによる通知で知ることができます。 その後、セキュリティ監査人は、IAS サーバーに接続して、ログ ファイルを古いものから順に削除することができます。 また、IAS のセキュリティ監査人は、管理コンピュータに接続したテープ デバイスや CD–RW デバイスに RADIUS ログ ファイルをバックアップし、その後 IAS サーバーに接続して不要になった古いログ ファイルを削除することもできます。
  
このソリューションでは、IAS は毎月新しいログ ファイルを作成するように構成されています。
  
十分な量のデータをオンラインに保存し、さまざまなシナリオに合わせてネットワーク アクセス情報を再構築できるように戦略を立てる必要があります。 たとえば、3 か月分のデータがオンラインで 3 つの異なるログ ファイルに保持されており、セキュリティ イベントの追跡のために、新しいものから順に 2 つのログ ファイルのみを使用してネットワーク アクセス情報を再現する必要があるとします。 この場合、3 つのログ ファイルのうち最も古いものはアーカイブして削除できます。それよりも新しい 2 つのファイルは残しておきます。
  
RADIUS 要求ログとその他の IAS データのバックアップについては、この章の「IAS データ ディレクトリのバックアップを構成する」のタスクで詳しく説明しています。 このタスクは、管理ステーションから RADIUS ログのアーカイブと削除を行う場合のためのガイダンスを提供します。
  
**RADIUS 要求ログ ファイルをアーカイブおよび削除するには**
  
1.  管理用ワークステーションに、IAS Security Auditors セキュリティ グループのメンバとしてログオンします。
  
2.  次のコマンドを使用して、ログ ファイルをアーカイブする IAS サーバーにドライブを対応付けます。HQ-IAS-01 は対象の IAS サーバーの名前に置き換えてください。
  
    NET USE X: \\\\HQ-IAS-01\\IASLogs
  
3.  IAS サーバーで、アーカイブしてサーバーから削除する古いログ ファイルを特定します。 NTBACKUP、**copy** コマンド、またはその他のユーティリティを使用して、選択したログ ファイルをオンライン共有から二次メディアにアーカイブします。
  
4.  オンライン共有から不要なログ ファイルを削除します。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### サポート作業領域のタスク
  
サポート作業領域の SMF には、必要なサービス レベルを維持するために、事後対応型のタスクと事前対応型のタスクの両方が含まれています。 事後対応型の機能は、組織が障害や問題への対応とこれらの解決を迅速に行うためにどのような能力を備えているかに左右されます。 望ましいのは、事前対応型の機能によって、サービス レベルが影響を受ける前に問題を特定して解決し、サービスの中断を回避することです。 これらの機能では、事前に定めたしきい値に照らしてサービス ソリューションを適切に監視し、潜在的な問題がサービスの中断という形で現われないうちに運用スタッフにその問題に対処する十分な時間を与えることができます。 サポート作業領域は、運用作業領域で説明しているサービス制御および SMF の監視に密接に関連しています。 サービス制御と監視は、運用スタッフとサポート スタッフが問題を検出するために必要不可欠な情報を提供します。 ここで説明する手順は、最も一般的なインシデントに対処し、そのインシデントから回復することを目的としています。
  
ここでは、次の SMF に関連する情報について説明します。
  
-   インシデント管理
  
次の SMF に属するタスクはありません。
  
-   問題管理
  
-   サービス デスク
  
    **注 :** 各タスクの説明には、セキュリティ要件、実行頻度、技術要件などの要約情報を記載します。
  
#### インシデント管理
  
インシデント管理は、顧客や IT パートナーから報告された、IT サービスを使用中または実装中に発生した障害や中断を、管理および制御するプロセスです。 インシデント管理では、正常なサービス運用への復旧をできる限り迅速に行い、業務に及ぼす悪影響を最小限に抑えることにより、サービス レベルの質と提供状況を最良の状態に保つことが目標になります。 正常なサービス運用とは、ここでは、サービス品質保証制度 (SLA) の限度内でのサービス運用のことです。
  
**注 :** Windows XP ワイヤレス クライアントに関する問題の一般的なトラブルシューティングについては、この章の最後にある「関連情報」を参照してください。
  
##### クライアントのネットワーク接続フォルダの状態を確認する
  
ネットワーク接続フォルダおよび Windows XP の通知アイコンは、WLAN 認証の状態に関する情報を示します。 エンド ユーザーやヘルプデスクのスタッフ メンバは、このタスクを実行することで、クライアント コンピュータのワイヤレス接続の状態を確認できます。 認証時にユーザーからの追加情報が必要になると (複数のユーザー証明書から 1 つを選択する必要がある場合など)、ユーザーにそのことを通知する吹き出しが表示されます。 このタスクはトラブルシューティングの際に使用されます。
  
###### 要約情報
  
-   **セキュリティ要件** : ローカル Administrators セキュリティ グループのメンバ (WLAN の設定を変更する場合)
  
-   **実行頻度** : ユーザーの問題をトラブルシューティングするとき
  
-   **技術要件** : Windows XP Professional
  
###### タスクの詳細
  
ネットワーク接続フォルダでは、ワイヤレス ネットワーク アダプタに対応する接続の名前の下に、認証の状態を示すテキストが表示されます。
  
接続の状態を確認するには、その接続のアイコンをダブルクリックします。**\[全般\]** タブでシグナルの強さを、**\[サポート\]** タブで IP アドレスの構成を確認できます。 プライベート IP アドレスの自動割り当て (APIPA) 機能によりワイヤレス アダプタにアドレス (169.254.0.0/16) が割り当てられている場合や、アダプタの Transmission Control Protocol/Internet Protocol (TCP/IP) のプロパティで代替 IP アドレスが設定されている場合には、認証が失敗しますが、この場合も Windows XP ワイヤレス クライアントとワイヤレス アクセス ポイントの関連付けは継続します。 認証が失敗しても、関連付けが継続していれば、Windows によりワイヤレス アダプタは有効とされ、TCP/IP の通常の構成プロセスが実行されます。 この例では、クライアントが WLAN に対して正常に認証されなかったため、Dynamic Host Configuration Protocol (DHCP) サーバーを検出できず、TCP/IP が自動的に APIPA または代替アドレスで構成されます。 この場合、IAS サーバーで WLAN 認証が失敗した原因を確認するか、クライアント コンピュータのトレースを有効にして結果を確認することをお勧めします。
  
**ネットワーク接続フォルダの状態を確認するには**
  
-   **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**ncpa.cpl**」と入力して **\[OK\]** をクリックします。
  
##### クライアント コンピュータでトレースを有効または無効にする
  
Windows では、詳細なトレース情報を取得できます。このトレース情報は、ヘルプデスクのスタッフや開発者がソフトウェア コンポーネントに関する問題を解決する際に役立ちます。 トレース処理を有効にすれば、イベント ログよりも詳しい情報を取得できます。また、その情報をテキスト形式のログ ファイルに保存することもできます。
  
拡張認証プロトコル (EAP) の認証プロセスに関する詳細情報を取得するには、EAP over LAN (EAPOL) コンポーネントおよび Remote Access Service-Transport Layer Security (RASTLS) コンポーネントに対するトレース処理を有効にする必要があります。
  
###### 要約情報
  
-   **セキュリティ要件** : ローカル Administrators セキュリティ グループのメンバ
  
-   **実行頻度** : クライアントの WLAN に関する問題をトラブルシューティングするときに必要に応じて
  
-   **技術要件** :
  
    -   Windows XP Professional
  
    -   Notepad.exe
  
###### タスクの詳細
  
次のコマンドを実行した後、認証プロセスを再度試行し、%systemroot%\\Tracing フォルダにある Eapol.log ファイルおよび Rastls.log ファイルの内容を確認してください。
  
**クライアント コンピュータのトレース処理を有効にするには**
  
-   次のコマンドを実行します。
  
    -   **netsh ras set tracing eapol enabled**
  
    -   **netsh ras set tracing rastls enabled**
  
**クライアント コンピュータのトレース処理を無効にするには**
  
-   次のコマンドを実行します。
  
    -   **netsh ras set tracing eapol disabled**
  
    -   **netsh ras set tracing rastls disabled**
  
    **注 :** トレース処理を有効にすると、システム リソースが消費され、また、生成されるログ ファイルのサイズが急激に大きくなります。 トラブルシューティングが完了したら、トレース処理を無効にしてください。
  
##### クライアント コンピュータでドメイン名文字列を確認する
  
次のタスクは、クライアント コンピュータで証明書ドメイン名のチェックを有効にしている場合に役立ちます。 この設定は、ユーザーを混乱させる WLAN ダイアログ ボックスが表示される可能性があるため、このソリューションでは有効にされていません。 Windows XP Professional SP1 でも、この設定は既定で無効になっています。
  
クライアント コンピュータは、EAP-TLS 相互認証の途中で証明書の失効を確認することができません。これは、通常、証明書失効リスト (CRL) がある場所は WLAN へのアクセスが許可される前に利用することができないためです。 ただし、Windows クライアントは、IAS サーバーから提示された証明書に含まれるサーバー名の全部または一部を検証することができます。 この機能は、ワイヤレス クライアント の GPO にあるワイヤレス ネットワーク ポリシー設定で構成されます (この設定のユーザー インターフェイスは、クライアント コンピュータのワイヤレス ネットワーク アダプタのプロパティで設定するワイヤレス ネットワークのプロパティとほとんど同じです)。
  
ワイヤレス クライアントでサーバー証明書の検証を行う場合、**\[サーバー名が次で終わる場合のみ接続する\]** フィールドに入力されている IAS サーバーのドメインが間違っていると、認証が失敗します。 このタスクは、**\[次のサーバーに接続する\]** チェック ボックスをオンにしている状況でクライアント認証に関する問題をトラブルシューティングするときに実行します。
  
###### 要約情報
  
-   **セキュリティ要件** : ローカル Administrators セキュリティ グループのメンバ
  
-   **実行頻度** : セットアップ時、またはユーザーの WLAN に関する問題をトラブルシューティングするとき
  
-   **技術要件** : Windows XP Professional
  
###### タスクの詳細
  
このタスクを実行すると、クライアントまたはワイヤレス ネットワーク ポリシー GPO の WLAN ネットワーク アダプタ ネットワーク接続の **\[プロパティ\]** ダイアログ ボックスのドメイン名文字列が正しいかどうかを確認できます。
  
**クライアント コンピュータでドメイン名文字列を確認するには**
  
1.  **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**ncpa.cpl**」と入力して **\[OK\]** をクリックします。
  
2.  ワイヤレス ネットワーク接続のプロパティを表示します。
  
3.  **\[ワイヤレス ネットワーク\]** タブの \[優先するネットワーク\] ボックスの一覧で適切なネットワークのサービス セット識別子 (SSID) をクリックし、そのネットワークのプロパティを表示します。
  
4.  **\[認証\]** タブのプロパティで、**\[サーバー名が次で終わる場合のみ接続する\]** ボックスの文字列が IAS サーバーのドメイン名と一致していることを確認します。
  
##### イベント ログ内の IAS 関連の認証イベントを確認する
  
クライアント認証の成功と失敗のイベントは、IAS サーバーのシステム イベント ログに記録されます。これはトラブルシューティングに役立てることができます。 \[インターネット認証サービス\] MMC スナップインで確認できる IAS サーバーのプロパティの **\[サービス\]** タブでは、どの種類の IAS イベント (拒否、破棄、および成功の各認証イベント) についてもイベント ログへの記録が既定で有効になっています。
  
IAS の管理者がこのタスクを実行して IAS サーバーのイベント ログに含まれている認証イベントを確認すると、ヘルプデスクのスタッフがコンピュータ認証やユーザー認証に関する問題をトラブルシューティングする際に役立ちます。
  
IT ヘルプデスクのスタッフが IAS 関連のシステム イベント ログに含まれているワイヤレス クライアントの認証情報にアクセスする必要がある場合には、次のオプションを検討することになります。
  
-   IAS Admins セキュリティ グループのメンバであり、IAS のシステム イベント ログにアクセス可能な IAS 管理者に協力を求める。 このタスクでは、このオプションを使用します。
  
-   MOM などのエンタープライズ向けイベント ログ管理システムを使用して、ヘルプデスクのスタッフがログを参照できる場所にログをエクスポートする。
  
-   IASLogs 共有とそのベースになっている NTFS ディレクトリ D:\\IASLogs の両方で、ヘルプデスクのスタッフに読み取りアクセス許可を付与する。 次に、これらのスタッフに、IASPARSE などのツールを使用してログ ファイルを参照する方法を説明します (この章の「IAS RADIUS 要求ログへアクセスする」タスクを参照)。 ほとんどのユーザーはこのオプションの採用を検討します。このオプションでは、最小限のインフラストラクチャしか求められず、またセキュリティ上のリスクが極端に増加することがないからです。
  
IAS システム イベント ログへの管理者アクセス許可を持たないユーザーに権利を付与すると、セキュリティ上のリスクが発生する可能性があります。 このことは、IAS サーバーの役割とドメイン コントローラ サーバーの役割を同じサーバーが果たしている場合に特に問題になります。
  
###### 要約情報
  
-   **セキュリティ要件** : ローカル IAS Administrators セキュリティ グループ、またはシステム イベント ログへの読み取り/保存アクセス許可を与えられているグループのメンバ
  
-   **実行頻度** : クライアント認証に関する問題をトラブルシューティングするとき
  
-   **技術要件** : \[イベント ビューア\] MMC スナップイン、または Windows Server 2003 リソース キットの EventCombMT
  
###### タスクの詳細
  
システム イベント ログ内の認証関連の記録を確認すれば、IAS で拒否された認証をトラブルシューティングするうえで役立ちます。 複数のリモート アクセス ポリシーが構成されている場合には、ログを使用して、接続を受理または拒否したリモート アクセス ポリシーの名前を特定することができます (イベントの説明に含まれるポリシー名を調べてください)。 また、認証イベント (ソースは IAS、イベント ID は受理の場合 1 で拒否の場合 2) には、理由コードが示されます。このコードには対応する説明があります。理由コードについての解説は、Windows Server 2003 のヘルプとサポートにあります。
  
IAS のイベントがログに記録されるようにし、さらにシステム イベント ログ内の IAS 関連の認証イベントを確認することは、失敗した IAS 認証のトラブルシューティングに最も役立つ手法です。
  
**システム イベント ログ内の認証イベントを確認するには**
  
1.  **\[スタート\]** ボタンをクリックし、**\[ファイル名を指定して実行\]** をクリックします。次に、「**Eventvwr**」と入力して **\[OK\]** をクリックします。
  
2.  **システム イベント**を示すログをクリックします。
  
3.  **\[表示\]** メニューの **\[フィルタ\]** をクリックし、**\[イベント ソース\]** ボックスの一覧の **\[IAS\]** をクリックしてから **\[OK\]** をクリックします。
  
##### IAS サーバーでトレースを有効または無効にする
  
Windows では、詳細なトレース情報を取得できます。このトレース情報は、ヘルプデスクのスタッフや開発者がソフトウェア コンポーネントに関する問題を解決する際に役立ちます。 トレース処理を有効にすれば、イベント ログよりも詳しい情報を取得できます。また、その情報をテキスト形式のログ ファイルに保存することもできます。
  
Microsoft Windows Server 2003 には強力なトレース機能が用意されています。この機能は、特定のコンポーネントの複雑な問題のトラブルシューティングに使用できます。 Windows Server 2003 のコンポーネントでトレース情報をファイルに記録できるようにするには、**netsh** コマンドを使用します。
  
###### 要約情報
  
-   **セキュリティ要件** : IAS サーバー上のローカル Administrators セキュリティ グループのメンバ
  
-   **実行頻度** : クライアントの WLAN 接続に関する問題をトラブルシューティングするときに必要に応じて
  
-   **技術要件** :
  
    -   Netsh
  
    -   メモ帳
  
    -   Regedit
  
###### タスクの詳細
  
**netsh** コマンドを使用することにより、特定のコンポーネントまたはすべてのコンポーネントに対するトレース処理を有効または無効にすることができます。 EAP-TLS を使用した 802.1x 認証に関する問題をトレースするうえで、特に有用なコンポーネントは次のとおりです。
  
-   **IASSAM** **(%*systemroot%*\\tracing フォルダにある Iassam.log ファイル)**。 このログは、IAS に関する問題を調べる際に最もよく使われるトレース ファイルです。このファイルには、ユーザー名のクラッキング、DC へのバインド、証明書の妥当性検査などに関する処理が記録されています。 このファイルは、IAS トレース ファイル群の中心的な存在であり、通常、認証に関する問題解決の際に必要となります。
  
-   **RASTLS (%*systemroot%*\\tracing フォルダにある Rastls.log ファイル)**。 EAP および PEAP を使用した認証プロセスで問題が発生した場合、その問題の解決に不可欠な情報の大半がこのログ ファイルに記録されます。 ただし、このログ ファイルに記録された情報の解析には手間がかかります。 マイクロソフトでは、このログ ファイルの内容を簡単に解析するための資料を作成中です。
  
IAS に関する次のトレース情報は、EAP-TLS を使用した 802.1x 認証プロセスのトラブルシューティングには通常必要ありません。しかし、その他の処理のトラブルシューティングには役に立つことがあります。
  
-   **IASRAD (*%systemroot%*\\tracing フォルダにある Iasrad.log ファイル)**。 このログ ファイルには、RADIUS プロトコルに関するすべての動作が記録されます。 たとえば、サーバーが監視しているポートなどが記録されます。このログ ファイルは、IAS サーバーに関する問題を解決する際、ごくまれに使用されます。
  
-   **IASSDO (*%systemroot%*\\tracing フォルダにある Iassdo.log ファイル)**。 このログ ファイルには、UI からサーバーの構成と辞書が保存されている MDB ファイルへのトランザクションが記録されます。 このログ ファイルは、サービスやユーザー インターフェイスに関する問題を解決する目的で使用されます。
  
**IAS サーバーのトレース処理を有効にするには**
  
-   必要なトレース情報に対応する **netsh** コマンドを実行します。 EAP-TLS を使用した 802.1x 認証プロセスに関する問題をトラブルシューティングする場合、IASSAM ログおよび RASTLS ログの参照をお勧めします。
  
    各トレース情報に対応する **netsh** コマンドは次のとおりです。
  
    -   **netsh ras set tracing iassam enabled**
  
    -   **netsh ras set tracing rastls enabled**
  
    -   **netsh ras set tracing iasrad enabled**
  
    -   **netsh ras set tracing iassdo enabled**
  
**IAS サーバーのトレース処理を無効にするには**
  
-   無効にするトレース情報に対応する **netsh** コマンドを実行します。
  
    各トレース情報に対応する **netsh** コマンドは次のとおりです。
  
    -   **netsh ras set tracing iassam disabled**
  
    -   **netsh ras set tracing rastls disabled**
  
    -   **netsh ras set tracing iasrad disabled**
  
    -   **netsh ras set tracing iassdo disabled**
  
        **注 :** トレースはシステム リソースを消費するので、ネットワークの問題を特定するための補助として使用を控えめにする必要があります。 トレース情報の取得が終了したら、または問題が特定されたら、直ちにトレースを無効にしてください。
  
IASSAM トレース ログは既定では 1 MB の容量しか確保されていないため、負荷が大きい場合は、ログ ファイルの貴重な情報が上書きされる可能性があります。 IASSAM トレース ログの容量を 15 MB に設定するには、次の手順を実行します。 ログのサイズが 15 MB に達すると、ファイル名が IASSAM.old に変更され、新しい IASSAM.log が作成されます。 この手順により、サーバー上で 30 MB のデータを確保することができます。
  
**IASSAM トレース ログ ファイルの容量を 15 MB に設定するには**
  
1.  Regedit.exe を起動します。
  
2.  レジストリ キー **\\HKLM\\Software\\Microsoft\\Tracing\\** に移動します。
  
3.  **IASSAM** キーを更新し、**MaxFileSize** の値を作成します。タイプは **REG\_DWORD** で、データ値は **0xF00000** に設定します。
  
##### IAS サーバーで SChannel のログの記録を有効にする
  
セキュリティで保護されたチャネル SChannel は、SSL (Secure Sockets Layer) や TLS (Transport Level Security) などの複数のインターネット セキュリティ プロトコルをサポートするセキュリティ サポート プロバイダ (SSP) です。
  
###### 要約情報
  
-   **セキュリティ要件** : ローカル Administrators セキュリティ グループのメンバ
  
-   **実行頻度 :** IAS サーバーでクライアントの接続に関する問題をトラブルシューティングするときに必要に応じて
  
-   **技術要件** :
  
    -   Regedit
  
    -   メモ帳
  
###### タスクの詳細
  
クライアント証明書の検証失敗をログに記録することは、セキュリティで保護されたチャネルのイベントです。IAS サーバーでは既定で無効にされています。
  
**IAS サーバーで SChannel のログの記録を有効にするには**
  
セキュリティで保護されたチャネルのイベントが追加で記録されるようにするには、次のレジストリ キーの値を **1** (種類は **REG\_DWORD**、データは **0x00000001**) から **3** (種類は **REG\_DWORD**、データは **0x00000003**) に変更します。
  
**HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\SecurityProviders**  
**\\SCHANNEL\\EventLogging**
  
**警告** : レジストリの編集を誤ると、システムに深刻な損害を与えるおそれがあります。 レジストリに変更を加える前に、コンピュータ上の重要なデータをバックアップすることをお勧めします。
  
SChannel のログ記録はシステム リソースを消費し、イベント ログが不要なエントリであふれてしまう可能性があるため、トラブルシューティング中は SChannel のログ記録を無効にしてください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 最適化作業領域のタスク
  
最適化作業領域には、サービス レベルの維持または向上とコスト管理を同時に行うための SMF が含まれます。 この作業領域には、サービスの停止や障害の見直し、コスト構造の調査、スタッフの査定、可用性分析、パフォーマンス分析、およびキャパシティ予測が含まれています。
  
ここでは、次の SMF に関連する情報について説明します。
  
-   容量管理
  
次の SMF に属するタスクはありません。
  
-   サービス レベル管理
  
-   財務管理
  
-   可用性管理
  
-   IT サービス継続性管理
  
-   人員管理
  
    **注 :** 各タスクの説明には、セキュリティ要件、実行頻度、技術要件などの要約情報を記載します。
  
#### 容量管理
  
容量管理は、ユーザーの要求を満たすことができるように、SLA に定められているパフォーマンス レベルの範囲内でサービス ソリューションの容量計画、サイズ変更、および制御を行うプロセスです。 この処理には、定められているパフォーマンス要件のほかに、サービス ソリューションを使用する状況、使用パターン、およびピーク時の負荷の特性についての情報が必要です。
  
##### IAS サーバーの最大負荷を判定する
  
ここでは、IAS サーバーの最大負荷の予測に関係する情報について説明します。
  
サイズ設定と構成が適切に行われている IAS RADIUS サーバーでは、パフォーマンスが問題となることはほとんどありません。 IAS RADIUS サーバーの負荷が最も高まるのは、多数のユーザーが一斉にログオンする朝の時間帯などのピーク負荷時、ネットワークの大規模な停止の直後、または RADIUS サーバーに障害が発生してワイヤレス AP がバックアップ サーバーにフェールオーバーしたときです。
  
###### 要約情報
  
-   **セキュリティ要件** : なし
  
-   **実行頻度** : セットアップ タスク
  
-   **技術要件** : なし
  
###### タスクの詳細
  
マイクロソフトでの内部テストの結果によると、IAS は、中程度のハードウェアでもピーク負荷に対応できます。これはほとんどのユーザーのニーズを満たす結果です。 IAS で対応できる認証数の概算値を表わす方法としては、1 秒あたりの認証数が最適です。 IAS は、Windows Server 2003 を実行している Intel Pentium 4 2 GHz 搭載サーバーでは、次のパフォーマンスを達成しています (Active Directory は別の Intel Pentium 4 2 GHz 搭載サーバーで実行)。
  
**表 12.10: IAS サーバーの負荷の判断**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >認証の種類</th>
<th style="border:1px solid black;" >1 秒あたりの認証数</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">新しい EAP-TLS 認証</td>
<td style="border:1px solid black;">36</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">オフロード カード サポートを使用する新しい EAP-TLS 認証</td>
<td style="border:1px solid black;">50</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">高速再接続による認証</td>
<td style="border:1px solid black;">166</td>
</tr>
</tbody>
</table>
  
**注 :** この情報の正確さは保証されていません。この情報は、容量計画用のガイドラインとしてのみ使用し、パフォーマンスの比較には使用しないでください。
  
IAS は、さまざまな量の RADIUS 要求情報を含めたディスクベースのテキスト ログを生成するように構成できます。 RADIUS サーバー上での RADIUS ログ記録のオーバーヘッドを考慮して、RADIUS ログの保存にはパフォーマンスの高いディスクの使用を計画してください。 ディスク サブシステムの処理能力が低いと、IAS RADIUS によるワイヤレス AP への応答が遅くなり、プロトコル タイムアウトやセカンダリ RADIUS サーバーに対するワイヤレス AP の不必要なフェールオーバーが発生する可能性があります。 RADIUS ログ オプションの詳細については、「第 5 章 : ワイヤレス LAN のセキュリティに対応した RADIUS インフラストラクチャを設計する」を参照してください。
  
また、Windows 2003 Server ソフトウェア トレース機能を有効にすると (前述の「IAS サーバーでトレースを有効または無効にする」を参照)、IAS サーバーにさらなる負荷がかかります。 ただし、この機能はネットワーク アクセスに関する問題を解決する際に必要になる場合があります。 IASサーバーについては、トレース機能を一定期間有効にした状態でも運用上の負荷を処理できるだけの容量を確保しておく必要があります。
  
##### IAS サーバーの記憶域要件およびバックアップ要件を判定する
  
ここでは、IAS の記憶域に求められるキャパシティについて詳しく説明します。 この情報は、オンライン ディスクとオフラインのバックアップ記憶域に将来求められる記憶域関連の条件を、容量計画の担当者が検討する際に役立ちます。
  
###### 要約情報
  
-   **セキュリティ要件** : なし
  
-   **実行頻度** : 必要に応じて
  
-   **技術要件** : なし
  
###### タスクの詳細
  
IAS RADIUS のログ ファイルは、IAS サーバー上にある、記憶域の計画が必要な単一コンポーネントです。 このガイドで取り扱うソリューションの場合、RADIUS 要求のログは、毎月新しいログ ファイルを作成するように構成されます。このソリューションを開発するときにテストしたハードウェアには、ログ ファイル専用の 18 GB のディスク ボリュームが用意されていました。
  
実際の環境での IAS サーバーの負荷を見積もり、ログ記録のオプションを選択してから、ラボ環境でテストを行い、実際の環境における IAS でのワイヤレス クライアントの認証とこれに伴うログ データの生成をシミュレートする必要があります。 見積もりには、次のようなロジックを使用できます。
  
ワイヤレス AP ごとの平均ユーザー数は 25 です (ユーザーまたはコンピュータ)。 各ユーザーまたはコンピュータは初回認証を行い、その後 10 ～ 60 分 ごと (セキュリティ要件により異なります) に再認証を実行します。 認証が行われるたびに 1 KB のログ情報がディスク上に生成されます。認証要求と監査要求はログに記録されますが、中間要求は記録されません (ファイル サイズはログ記録のオプションによって異なります)。 各ワイヤレス AP が 25 ユーザーをサポートしている場合にディスク上に生成されるログ領域の 1 時間あたりの量を見積もる必要があります。 その後で、プライマリ IAS サーバーがネットワークの負荷が高いときやサーバー フェールオーバーが発生したときにもサポートできるワイヤレス AP の数 (最大数) を見積もります。
  
IAS RADIUS 要求のログは、圧縮性の高いデータです。 通常の使用ではお勧めできませんが、必要な場合には RADIUS 要求のログ ファイルのフォルダで圧縮を有効にすることができます。 データを圧縮する場合、IAS サーバーの負荷が増加するので、対応を検討する必要があります。
  
###### IAS RADIUS のログ ファイルのバックアップ期間
  
バックアップ サーバーへのネットワーク バックアップが、専用の 100 Mbps (メガビット/秒) スイッチ上で理想的な状態で実行されることを前提とした場合、3 GB のデータベースおよび 500 MB のシステム状態は約 15 ～ 20 分でバックアップできます。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 変更作業領域のタスク
  
変更作業領域には、管理下にある IT 環境での変更の特定、確認、承認、および組み込みに必要なプロセスと手順が含まれます。 変更には、ハード資産やソフト資産の変更のほかに、特定のプロセスや手順の変更などがあります。
  
変更プロセスの目的は、新しいテクノロジ、システム、アプリケーション、ハードウェア、ツール、およびプロセスのほか、役割や責任の変更を、迅速に、そしてサービスの中断を最小限に抑えながら IT 環境に導入することです。
  
#### 変更管理
  
変更管理 SMF は、IT 環境での変更を管理する役割を果たします。 変更管理プロセスの主要な目標は、ある変更によって影響を受ける関係者が、そのような面倒な変更の影響を認識し理解できるようにすることです。 ほとんどのシステムは相互に密接に関連しているので、システムの一部を変更すると、別のシステムが深刻な影響を受けることがあります。 変更管理では、変更が展開される前に、影響を受けるシステムとプロセスのすべてを特定して、悪影響を緩和または排除するよう試みます。 一般に、"ターゲット環境" つまり管理対象の環境とは運用環境のことですが、これにはキーの統合環境、テスト環境、およびステージング環境も含まれます。
  
RADIUS のインフラストラクチャや WLAN のセキュリティの変更は、いずれも次に示す MOF の標準的な変更管理プロセスに従って行う必要があります。
  
1.  **変更の要求**。 変更の要求 (RFC) を発行して変更を正式に開始します。
  
2.  **変更の分類**。 緊急度、およびインフラストラクチャまたはユーザーに対する影響を基準に、変更の優先度およびカテゴリを割り当てます。 この割り当ては、実装のスピードとルートに影響します。
  
3.  **変更の承認**。 変更マネージャおよび変更承認委員会 (CAB) が変更を検討し、承認/非承認を決定します。CAB には IT および運営の担当者が参加します。
  
4.  **変更の開発**。 変更を計画および開発します。このプロセスはそれぞれの目的によって大きく異なります。主な中間マイルストーンでのレビューも含まれます。
  
5.  **変更のリリース**。 変更を運用環境にリリースおよび実装します。
  
6.  **変更のレビュー**。 変更の実装後、当初の目的を達成したか、変更を有効にするかどうかを決定するプロセスです。
  
ここで説明する手順は、実際の環境で日常的に必要になり得る主要な変更の一部について、変更開発手順の概要を示すものです。 変更開発手順には、それぞれに応じた変更リリース手順があります。変更リリース手順は、変更をどのような方法で運用環境に展開する必要があるかを示します。
  
##### オペレーティング システムの更新を管理する
  
RADIUS および WLAN ソフトウェア コンポーネントに対するセキュリティ更新の管理は、一般的な Windows 更新プログラムの管理の一部です。 この管理については、マイクロソフトが提供している 2 つのソリューション ガイドを参照してください。これらのガイドでは、Microsoft Systems Management Server (SMS) または Microsoft Software Update Services (SUS) のいずれかを使用した Windows オペレーティング システムの更新について説明しています。 このガイドの入手方法については、この章の最後にある「関連情報」を参照してください。
  
更新プログラムの管理には、リリース管理コンポーネントや構成管理コンポーネントだけでなく、変更管理コンポーネントも関係しています。 ただし、この 3 つの SMF については、上記のドキュメントを参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 構成表
  
次の表に、この章の手順で使用されているサイト固有およびソリューション固有の構成情報の値を示します。 次の表は、「第 8 章 : RADIUS インフラストラクチャを実装する」と「第 9 章 : ワイヤレス LAN のセキュリティに対応したインフラストラクチャを実装する」の構成計画表から参照用に抜粋したものです。
  
#### サイト単位の構成パラメータ
  
**表 12.11: ユーザー定義の構成項目**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >構成項目</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Active Directory フォレスト ルート ドメインの DNS 名</td>
<td style="border:1px solid black;">woodgrovebank.com</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ドメインのネットワーク基本入出力システム (NetBIOS) 名</td>
<td style="border:1px solid black;">WOODGROVEBANK</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">プライマリ IAS サーバーのサーバー名</td>
<td style="border:1px solid black;">HQ-IAS-01</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">セカンダリ IAS サーバーのサーバー名</td>
<td style="border:1px solid black;">HQ-IAS-02</td>
</tr>
</tbody>
</table>
  
#### ソリューションの構成パラメータ
  
**表 12.12: ソリューションで規定されている構成項目**

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >構成項目</th>
<th style="border:1px solid black;" >設定</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">[アカウント] IAS の構成を制御する管理グループの完全な名前</td>
<td style="border:1px solid black;">IAS Admins</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[アカウント] IAS の構成を管理する管理グループの Windows 2000 以前の名前</td>
<td style="border:1px solid black;">IAS Admins</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[アカウント] セキュリティ目的で IAS 認証とアカウンティング要求のログを確認するグループの完全な名前</td>
<td style="border:1px solid black;">IAS Security Auditors</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[アカウント] セキュリティ目的で IAS 認証とアカウンティング要求のログを確認するグループの Windows 2000 以前の名前</td>
<td style="border:1px solid black;">IAS Security Auditors</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[アカウント] 802.1x 認証の証明書を必要とするユーザーを含む Active Directory グローバル グループ</td>
<td style="border:1px solid black;">AutoEnroll Client Authentication – User Certificate</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[アカウント] 802.1x 認証の証明書を必要とするコンピュータを含む Active Directory グローバル グループ</td>
<td style="border:1px solid black;">AutoEnroll Client Authentication – Computer Certificate</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[アカウント] 802.1x 認証の証明書を必要とする IAS サーバーを含む Microsoft Active Directory グローバル グループ</td>
<td style="border:1px solid black;">AutoEnroll RAS and IAS Server Authentication Certificate</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[アカウント] 802.1x 認証の証明書を必要とする IAS サーバーを含む Microsoft Active Directory グローバル グループの Windows 2000 以前の名前</td>
<td style="border:1px solid black;">AutoEnroll RAS and IAS Server Authentication Certificate</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[アカウント] ワイヤレス ネットワークへのアクセスを許可されているユーザーを含む Active Directory グローバル グループ</td>
<td style="border:1px solid black;">Remote Access Policy – Wireless Users</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[アカウント] ワイヤレス ネットワークへのアクセスを許可されているコンピュータを含む Active Directory グローバル グループ</td>
<td style="border:1px solid black;">Remote Access Policy – Wireless Computers</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[アカウント] Wireless Users グループと Wireless Computers グループの両方を含む Active Directory ユニバーサル グループ</td>
<td style="border:1px solid black;">Remote Access Policy – Wireless Access</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[アカウント] Active Directory のグループ ポリシーを使用してワイヤレス ネットワーク関連のプロパティを構成する必要があるコンピュータが属する Active Directory グローバル グループ</td>
<td style="border:1px solid black;">Wireless Network Policy – Computers</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[証明書] ユーザー クライアント認証用の証明書を生成するために使用される証明書テンプレート</td>
<td style="border:1px solid black;">Client Authentication – User</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[証明書] コンピュータ クライアント認証用の証明書を生成するために使用される証明書テンプレート</td>
<td style="border:1px solid black;">Client Authentication – Computer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[証明書] IAS で使用されるサーバー認証証明書を生成するために使用される証明書テンプレート</td>
<td style="border:1px solid black;">RAS and IAS Server Authentication</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[スクリプト] インストール スクリプトのパス</td>
<td style="border:1px solid black;">C:\MSSScripts</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[スクリプト] IAS 構成のエクスポート バッチ ファイル</td>
<td style="border:1px solid black;">IASExport.bat</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[スクリプト] IAS 構成のインポート バッチ ファイル</td>
<td style="border:1px solid black;">IASImport.bat</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[スクリプト] IAS RADIUS クライアント構成のエクスポート バッチ ファイル</td>
<td style="border:1px solid black;">IASClientExport.bat</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[スクリプト] IAS RADIUS クライアント構成のインポート バッチ ファイル</td>
<td style="border:1px solid black;">IASClientImport.bat</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[構成] 構成バックアップ ファイルのパス</td>
<td style="border:1px solid black;">D:\IASConfig</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[要求ログ] IAS 認証および監査要求ログの場所</td>
<td style="border:1px solid black;">D:\IASLogs</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[要求ログ] RADIUS 要求ログの共有名</td>
<td style="border:1px solid black;">IASLogs</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[リモート アクセス ポリシー] ポリシー名</td>
<td style="border:1px solid black;">Allow Wireless Access</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">[グループ ポリシー] Microsoft Active Directory グループ ポリシー オブジェクト (GPO) 名</td>
<td style="border:1px solid black;">Wireless Network Policy</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">[グループ ポリシー] GPO 内のワイヤレス ネットワーク ポリシー</td>
<td style="border:1px solid black;">Client Computer Wireless Configuration</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 関連情報
  
-   MOF プロセス モデルとチーム モデルの詳細については、「[Microsoft Operations Framework](http://www.microsoft.com/japan/technet/itsolutions/techguide/mof/default.mspx)」www.microsoft.com/japan/technet/itsolutions/techguide/mof/default.mspx を参照してください。
  
-   容量制約全般の情報および関連パフォーマンス カウンタの詳細については、マイクロソフト サポート技術情報 Q146005「[パフォーマンスのための Windows NT の最適化](http://support.microsoft.com/default.aspx?kbid=146005)」http://support.microsoft.com/default.aspx?scid=146005 を参照してください。
  
-   ワイヤレス ネットワークに関する問題のトラブルシューティングの詳細については、次の情報を参照してください。
  
    -   マイクロソフト サポート技術情報 Q313242「[Windows XP におけるワイヤレス ネットワーク接続のトラブルシューティング](http://support.microsoft.com/?kbid=313242)」http://support.microsoft.com/?scid=313242
  
    -   ホワイトペーパー「[Troubleshooting Windows XP IEEE 802.11 Wireless Access](http://www.microsoft.com/windowsxp/pro/techinfo/administration/networking/troubleshooting.asp)」www.microsoft.com/windowsxp/pro/techinfo/administration/  
        networking/troubleshooting.asp (英語)
  
-   MOM の展開の詳細については、 「[*MOM 2000 SP1 Operations Guide*](http://www.microsoft.com/resources/documentation/mom/2000sp1/all/opsguide/en-us/1_in781g.mspx)」 www.microsoft.com/resources/documentation/mom/2000sp1/all/opsguide/en-us/1\_in781g.mspx (英語) を参照してください。
  
-   Microsoft SMS 2003 での更新プログラムの管理については、「[Patch Management Using Systems Management Server 2003](http://technet.microsoft.com/ja-jp/solutionaccelerators/default.aspx)」www.microsoft.com/technet/itsolutions/cits/mo/swdist/pmsms/2003/pmsms031.mspx (英語) を参照してください。
  
-   Microsoft SMS 2.0 を使った更新プログラムの管理については、「[Patch Management Using Microsoft Systems Management Server 2.0](http://www.microsoft.com/technet/itsolutions/cits/mo/swdist/pmsms/20/pmsmsin.mspx)」www.microsoft.com/technet/itsolutions/cits/mo/swdist/pmsms/20/pmsmsin.mspx (英語) を参照してください。
  
-   Microsoft Software Update サービスを使った更新プログラムの管理については、「[Patch Management Using Microsoft Software Update Services](http://www.microsoft.com/technet/itsolutions/cits/mo/swdist/pmsus/pmsus251.mspx)」www.microsoft.com/technet/itsolutions/cits/mo/swdist/pmsus/pmsus251.mspx (英語) を参照してください。
  
-   Microsoft プラットフォームでのセキュリティ更新プログラムの管理については、「[Improve Platform Manageability](http://go.microsoft.com/fwlink/?linkid=16284)」http://go.microsoft.com/fwlink/?LinkId=16284 (英語) を参照してください。
  
-   グループ ポリシー管理コンソール (GPMC) の取得方法と使用方法については、「[グループ ポリシー管理コンソールによる企業システムの管理](http://www.microsoft.com/japan/windowsserver2003/gpmc/default.mspx)」www.microsoft.com/japan/windowsserver2003/gpmc/default.mspx を参照してください。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 目次
  
-   [概要](https://technet.microsoft.com/ja-jp/library/30f90d1c-7faa-432f-b6c8-d4927fe36229(v=TechNet.10))  
-   [ソリューションの概要](https://technet.microsoft.com/ja-jp/library/30b42da7-6df7-4c17-8f81-e3129a989221(v=TechNet.10))  
-   [第 1 章 : ソリューションの概要](https://technet.microsoft.com/ja-jp/library/178db46c-9580-45ec-8ca8-565f7eec6521(v=TechNet.10))  
-   [設計ガイドの概要](https://technet.microsoft.com/ja-jp/library/e6114a19-d2e2-4f4f-9354-9a973b9e3221(v=TechNet.10))  
-   [第 2 章 : セキュリティで保護されたワイヤレス LAN ネットワークの構築方針を決定する](https://technet.microsoft.com/ja-jp/library/798406d6-d739-4d18-879b-9ae061fa320a(v=TechNet.10))  
-   [第 3 章 : セキュリティ保護されたワイヤレス LAN ソリューション アーキテクチャ](https://technet.microsoft.com/ja-jp/library/40ad9fbf-71fc-4ade-af08-905a35ae95e8(v=TechNet.10))  
-   [第 4 章 : 公開キー基盤を設計する](https://technet.microsoft.com/ja-jp/library/26fc5cef-602a-4340-9552-f48b4d7d674e(v=TechNet.10))  
-   [第 5 章 : ワイヤレス LAN のセキュリティに対応した RADIUS インフラストラクチャを設計する](https://technet.microsoft.com/ja-jp/library/e3e593bb-1c1d-40ad-97fc-3798b6869f18(v=TechNet.10))  
-   [第 6 章 : 802.1X を使用してワイヤレス LAN のセキュリティを設計する](https://technet.microsoft.com/ja-jp/library/75fadbd9-af34-4322-96ad-c609aaaa5907(v=TechNet.10))  
-   [構築ガイドの概要](https://technet.microsoft.com/ja-jp/library/2b673333-12a3-4bac-affe-207d148e68a0(v=TechNet.10))  
-   [第 7 章 : 公開キー基盤を実装する](https://technet.microsoft.com/ja-jp/library/70a59275-e4e0-4849-af0e-1af643e7b8fe(v=TechNet.10))  
-   [第 8 章 : RADIUS インフラストラクチャを実装する](https://technet.microsoft.com/ja-jp/library/83bbb839-cc8d-4724-affb-a6ae08237f29(v=TechNet.10))  
-   [運用ガイドの概要](https://technet.microsoft.com/ja-jp/library/9519ea6d-b101-4981-b836-1168f32c7f1f(v=TechNet.10))  
-   [第 9 章 : ワイヤレス LAN のセキュリティに対応したインフラストラクチャを実装する](http://technet.microsoft.com/ja-jp/library/cc527040.aspx)  
-   [第 10 章 : 運用ガイドの紹介](https://technet.microsoft.com/ja-jp/library/75d535e0-e9ed-454c-98ec-2ed53ce54d52(v=TechNet.10))  
-   [第 11 章 : 公開キー基盤を管理する](https://technet.microsoft.com/ja-jp/library/9437df75-a375-40f2-9577-17755eec9545(v=TechNet.10))  
-   第 12 章 : RADIUS およびワイヤレス LAN のセキュリティ インフラストラクチャを管理する  
-   [テスト ガイドの概要](https://technet.microsoft.com/ja-jp/library/7e4b9c88-3b35-41f8-b81d-9546743da068(v=TechNet.10))  
-   [第 13 章 : テスト ガイド](https://technet.microsoft.com/ja-jp/library/4d249b34-b07e-46af-b8c7-e2ab85f0c26e(v=TechNet.10))  
-   [付録](https://technet.microsoft.com/ja-jp/library/c60be0d8-d416-41bd-b173-23bdcf56bcf0(v=TechNet.10))  
-   [付録 A: Windows のバージョン サポート表](https://technet.microsoft.com/ja-jp/library/d55ba82b-f689-4e8a-bddd-37ab55d9f4f1(v=TechNet.10))  
-   [付録 B: スクリプトとサポート ファイル](https://technet.microsoft.com/ja-jp/library/ecfc00f9-d0a2-44b0-b92e-73d714462bbe(v=TechNet.10))  
-   [付録 C: 配信ガイド](https://technet.microsoft.com/ja-jp/library/7fdf9700-34db-4b0f-92d1-f6a6d8dbe5e1(v=TechNet.10))  
-   [付録 D: WPA のサポート](http://technet.microsoft.com/ja-jp/library/cc527037.aspx)
  
[](#mainsection)[ページのトップへ](#mainsection)
