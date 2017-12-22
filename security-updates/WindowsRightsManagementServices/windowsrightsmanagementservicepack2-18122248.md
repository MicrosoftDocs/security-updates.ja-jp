---
TOCTitle: Windows Rights Management サービス Service Pack 2 リリース ノート
Title: Windows Rights Management サービス Service Pack 2 リリース ノート
ms:assetid: '78067886-681f-49a6-b43d-bfd08a369b69'
ms:contentKeyID: 18122248
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747637(v=WS.10)'
---

Windows Rights Management サービス Service Pack 2 リリース ノート
=================================================================

*リリース日 :2006 年 12 月*

はじめに
--------

Microsoft® Windows® Rights Management サービス (RMS) Service Pack 2 (SP2) をインストールする前に、以下の情報をよくお読みください。このリリース ノートの情報は、RMS SP2 に該当するものであり、RMS クライアントには該当しません。RMS クライアントについては、「Rights Management サービス」([http://go.microsoft.com/fwlink/?LinkId=68637](http://go.microsoft.com/fwlink/?linkid=68637)) を参照してください。

#### システム要件

次の表では、RMS SP2 を実行するためのハードウェア要件について説明します。

###  

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >要件</th>
<th style="border:1px solid black;" >推奨要件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">1 つの Pentium III プロセッサ (800 MHz 以上) を搭載したコンピュータ</td>
<td style="border:1px solid black;">2 つの Pentium 4 プロセッサ (1500 MHz 以上) を搭載したコンピュータ</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">256 MB の RAM</td>
<td style="border:1px solid black;">512 MB の RAM</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">20 GB のハード ディスク空き領域</td>
<td style="border:1px solid black;">40 GB のハード ディスク空き領域</td>
</tr>
</tbody>
</table>
  

> [!NOTE]
> RMS SP2 は 32 ビット コンピュータ用に設計されています。64 ビット コンピュータにインストールすると、エミュレーション モードで動作します。 

  
次の表では、RMS SP2 を実行するためのソフトウェア要件について説明します。

  
###  

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >コンポーネント</th>
<th style="border:1px solid black;" >要件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">オペレーティング システム</td>
<td style="border:1px solid black;">RMS SP2 用の Microsoft Windows Server® 2003 (Web Edition を除く)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Rights Management サービス SP2</td>
<td style="border:1px solid black;">RMS SP2 にアップグレードする前に、RMS Service Pack 1 (SP1) がインストールされている必要があります。RMS SP2 クライアントには、この要件はありません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ファイル システム</td>
<td style="border:1px solid black;">NTFS ファイル システムを推奨します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">必要なコンポーネント</td>
<td style="border:1px solid black;"><ul>
<li>Active Directory® のディレクトリ サービス統合を有効にしたメッセージ キュー (MSMQ)<br />
<br />
</li>
<li>ASP.NET を有効にしたインターネットインフォメーション サービス (IIS)<br />
<br />
</li>
<li>Microsoft .NET Framework 1.1<br />
<br />
</li>
</ul></td>
</tr>
</tbody>
</table>
 

> [!NOTE]
> リモート管理を許可するように RMS SP2 を設定した場合、RMS SP2 管理サービスに接続するコンピュータでは Internet Explorer 6.0 以降を使用する必要があります。 

次の表では、RMS SP2 を実行するためのインフラストラクチャ要件について説明します。

###  

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >コンポーネント</th>
<th style="border:1px solid black;" >要件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">ディレクトリ サービス</td>
<td style="border:1px solid black;">RMS がインストールされているドメインと同じドメインに存在する Windows Server 2000 (SP3 以降を適用) のドメイン コントローラ上で、Active Directory が動作している必要があります。RMS を使用してライセンスの取得やコンテンツの発行を行うすべてのユーザーおよびグループは、Active Directory に電子メール アドレスが設定されている必要があります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">データベース サーバー</td>
<td style="border:1px solid black;">RMS SP2 では、操作を実行するためにデータベースおよびストアド プロシージャが必要です。Microsoft SQL Server™ 2000 (SP3a 以降を適用)、または Microsoft SQL Server 2005が必要です。テストなど 1 台のコンピュータでの導入の場合には Microsoft SQL Server Desktop Engine (MSDE 2000) Release A または Microsoft SQL Server 2005 Express Edition が必要です。</td>
</tr>
</tbody>
</table>
  
RMS は Microsoft SQL Server 2000 および Microsoft SQL Server 2005 が動作するデータベース サーバー向けに設計およびテストされています。他のデータベース サーバーで RMS を実行するには、そのサーバーが次の条件を満たしている必要があります。

  
-   Microsoft .NET Framework 1.1 によって提供される ADO.NET インターフェイスに対応している。  
-   Transact-SQL (Microsoft SQL Server が使用する構造化されたクエリ言語) に準拠している。これは、RMS 初期化スクリプトおよび RMS ストアド プロシージャで Transact-SQL を使用するためです。  
-   すべての Microsoft SQL Server 固有の拡張子に対応している。  
-   .NET Framework の System.Data.SqlClient 名前空間のメソッド呼び出しに応答する。  
-   System.Data.SqlClient 名前空間に対応する機能を提供する。  
-   Windows 認証モードを使用している。

  
データベース サーバーがこれらの条件を満たしているかどうかを知るには、関連するデータベースのベンダにお問い合わせください。

  
次の表は、RMS で各種の操作を行うために必要な、ユーザーの権利およびアクセス許可の一覧です。

  
###  

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >操作</th>
<th style="border:1px solid black;" >アカウントの要件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">RMS のインストール</td>
<td style="border:1px solid black;">ローカル コンピュータの管理者の資格情報を持つドメイン ユーザー</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RMS ルート クラスタの提供</td>
<td style="border:1px solid black;">ローカル コンピュータの管理者の資格情報および Active Directory の参照と書き込み権限を持つドメイン ユーザー</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">RMS のライセンスのみのクラスタの提供</td>
<td style="border:1px solid black;">ローカル コンピュータの管理者の資格情報と Active Directory の参照権限を持つドメイン ユーザー</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">新しい構成データベースの使用中の提供</td>
<td style="border:1px solid black;">ローカル コンピュータの管理者の資格情報と、SQL Server を実行しているコンピュータ上での読み取り、書き込みおよび作成権限を持つドメイン ユーザー</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">既存の構成データベースの使用中の提供</td>
<td style="border:1px solid black;">ローカル コンピュータの管理者の資格情報と、データベース サーバーを実行しているコンピュータ上での読み取りおよび書き込み権限を持つドメイン ユーザー</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RMS の管理</td>
<td style="border:1px solid black;">ローカル コンピュータの管理者の資格情報を持つドメイン ユーザー</td>
</tr>
</tbody>
</table>
  

> [!NOTE]
> Windows Server の構成、Active Directory、メッセージ キュー、IIS およびファイル システムの詳細については、Windows Server 2003 TechCenter ([http://go.microsoft.com/fwlink/?LinkId=78135](http://go.microsoft.com/fwlink/?linkid=78135)) を参照してください。 

  
RMS をクラスタ導入で使用する場合は、次の表に示された点を確認してください。

  
###  

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >状況</th>
<th style="border:1px solid black;" >推奨要件</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">多数のデスクトップで RMS を使用する</td>
<td style="border:1px solid black;">Systems Management Server (SMS) またはグループ ポリシーを使用して、RMS SP2 クライアントをインストールします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">多数のクライアント要求が発生する</td>
<td style="border:1px solid black;">負荷分散サーバー、Windows Server オペレーティング システムのネットワーク負荷分散サービス、またはハードウェア負荷分散を使用して、要求をクラスタ内で分散します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">仮想 IP アドレスを使用して 2 つのネットワーク アダプタでエクストラネットとイントラネットの要求を処理している</td>
<td style="border:1px solid black;">エクストラネットに仮想 IP アドレスを公開するドメイン ネーム システム (DNS) 登録が、イントラネットにもアドレスを公開することを確認してください。</td>
</tr>
</tbody>
</table>


> [!IMPORTANT]
> イントラネットに対して DNS 登録が行われていない場合、内部のクライアント ライセンス要求が失敗します。DNS 設定を変更できない場合は、クラスタ内の各サーバーのホスト テーブルを変更して、クラスタ URL をクラスタの仮想 IP アドレスにマッピングできます。DNS 登録は、RMS の提供前に実行する必要があります。既にサービスを提供している場合は、サーバーから RMS を削除してから、提供処理を再実行してください。 


#### このリリースでサポートされるクライアント
  
サービス パックを適用していない RMS クライアント、RMS クライアント SP1、または RMS クライアント SP2 は、Windows 2000、Windows XP および Windows Server 2003 を実行しているすべてのコンピュータにインストールできます。それ以前の Windows オペレーティング システムは、このリリースではサポートされていません。


> [!CAUTION]
> サービス パックを適用していない RMS クライアントを使用している場合、クライアントは SP1 以降の RMS サーバーに対してオンライン発行を使用することはできません。 
  
  
機能の変更  
----------
  
RMS SP2 には、次のような新機能があります。

  
-   [フォレストにまたがるグループの拡張の強化](#bkmk_cif1)  
-   [データベースのログの変更](#bkmk_cif2)  
-   [サーバーのバッチ サイズの拡大](#bkmk_cif3)  
-   [Microsoft SQL Server 2005 との互換性](#bkmk_cif4)
  
<span id="BKMK_CIF1"></span>
#### フォレストにまたがるグループの拡張の強化
  
#### 機能の説明
  
RMS では、フォレストにまたがるグループの拡張により、グループ メンバシップが 2 つのフォレスト間でレプリケートされない別のフォレスト内にある Active Directory ユニバーサル グループ メンバシップを拡張する RMS の機能の操作が簡単になります。一方のフォレストにいるユーザーが別のフォレストのユーザーに権利で保護されたコンテンツを送信すると、RMS は検出を実行して、そのユーザーがコンテンツへのアクセス権を持っていることを検証します。この検証プロセスは、一方のフォレストからもう一方のフォレストへ LDAP クエリを使用して、リモート フォレストの RMS サービス接続ポイント (SCP) を検出することによって行います。リモート フォレストの SCP が検出されると、RMS サービス アカウントからグループ拡張パイプラインに要求が送信されます。この要求では、ユーザーがグループのメンバであるかどうかをリモート フォレストに問い合わせます。

  
#### この機能に該当するユーザー
  
この新機能は、フォレスト間でユニバーサル グループ メンバシップがレプリケートされない複数のフォレストの Active Directory 環境にいる RMS ユーザーに関係します。

  
#### この変更が重要である理由
  
今回の新しいフォレストの信頼の拡張プロトコルによって、複数のフォレストの Active Directory 環境を展開しているユーザーに対する信頼性が向上します。

  
#### 旧バージョンとの相違点
  
RMS SP2 より前のバージョンでは、フォレストにまたがるグループの拡張は.NET リモート呼び出しを使用して行っていました。今回のリリースでは、フォレストにまたがるグループの拡張プロトコルが、フォレストの信頼のグループ拡張パイプラインへの SOAP/HTTP 要求を使用する ASP.NET Web サービスに変更されています。

> [!NOTE]
> 後方互換性のため、RMS SP2 でも引き続き .NET リモート呼び出しはサポートされています。ただし、新機能であるフォレストにまたがるグループ拡張プロトコルが本来の性能を発揮するには、すべての RMS クラスタで最低でも RMS SP2 が動作している必要があります。 

  
#### RMS SP2 で追加または変更された設定
  
RMS SP2 では、新しい RMS グループ拡張パイプラインは既定でもっとも安全な設定になっており、ローカルの RMS サービス グループおよび管理者グループのみがアクセスできます。アカウントにアクセス権を与えるには、wwwroot\\\_wmcs\\GroupExpansion\\GroupExpansion.asmx にあるグループ拡張パイプラインでアクセス制御リストを変更する必要があります。

> [!IMPORTANT]
> それぞれの Active Directory フォレストの RMS サービス アカウントが、クラスタ内の各 RMS サーバー上のグループ拡張パイプラインへのアクセス権を持っていることを確認します。アカウントにアクセス権がない場合は、グループ拡張が失敗します。別の方法としては、各フォレストに同じアカウントを作成し、各アカウントに同じパスワードを割り当てることもできます。この場合、グループ拡張パイプラインに 1 つのアカウントを追加するだけで済みます。 
  
メッセージ キュー サービスで通知されない問題のメッセージを通知するため、RMS SP2 には新しいイベントが追加されています。新しいイベント ログには、メッセージにデジタル署名できない場合や、メッセージを検証できない場合にユーザーにそのことを通知するイベントが含まれます。検証の問題には、メッセージの形式が誤っている、ハッシュか署名が欠けている、ハッシュや署名が誤っているなどの例があります。

  
<span id="BKMK_CIF2"></span>
#### データベースのログの変更
  
#### 機能の説明
  
RMS ではログ リスナ サービスを使用して、メッセージ キューによってログ データベースにすべての RMS 通信を送信します。RMS クラスタはメッセージ キュー サービスにメッセージを送信し、ログ リスナ サービスではメッセージ キューのキューからそのメッセージを取得してログ データベースに書き込みます。

  
#### この機能に該当するユーザー
  
この機能は、RMS ログ リスナ サービスを使用している既存の RMS ユーザーと、RMS ログ リスナ サービスの使用を考えている新しい RMS SP2 ユーザーに該当します。

  
#### この変更が重要である理由
  
旧リリースの RMS では、RMS ログ キューはアクセス制御リストを使用して保護されていましたが、認証は無効になっていました。認証がないため、悪意のあるユーザーが MRS ログ キューに誤ったメッセージを書き込む可能性がありました。

  
#### 旧バージョンとの相違点
  
RMS SP2 では、RMS クラスタから転送されたメッセージに対し、メッセージ キューを使用して追加認証を行います。メッセージ キューへの不正アクセスを防止するアクセス制御リスト以外に、メッセージ認証確認メカニズムを使用してメッセージ キューのキューを保護することもできます。メッセージ キュー サービスにメッセージを送信すると、RMS パイプラインではそのメッセージのハッシュが生成され、RMS クラスタの秘密キーによってそのメッセージがデジタル署名されます。ログ リスナ サービスではまずメッセージのハッシュを計算し、メッセージに付属しているハッシュと比較します。ハッシュが一致すると、ログ リスナ サービスではクラスタの公開キーとメッセージ内のハッシュを使用して署名を確認します。ハッシュが一致して署名が確認されると、メッセージはログ データベースに送信されます。この検証段階で失敗すると、メッセージはメッセージ キューのキューから永久に削除され、イベント ビューアのアプリケーション ログにイベント警告が書き込まれます。

  
#### RMS SP2 で追加または変更された設定
  
RMS SP2 には、メッセージ キューのキューで問題のメッセージが通知されなかった場合にそのことを通知するために作られた新しいイベントが追加されています。新しいイベントはアプリケーション ログに書き込まれます。ログにはデジタル署名できなかったメッセージや、メッセージのデジタル署名を検証できなかったことが記入されます。検証の問題には、メッセージの形式が誤っている、ハッシュか署名が欠けている、ハッシュや署名が誤っているなどの例があります。

  
<span id="BKMK_CIF3"></span>
#### サーバーのバッチ サイズの拡大
  
#### 機能の説明
  
RMS でバッチ処理を行うと、各ライセンスに対して個別に要求を行う代わりに複数のライセンス要求を 1 つの要求として RMS クラスタに送信できるため、パフォーマンスが向上します。

  
#### この機能に該当するユーザー
  
サーバーのバッチ サイズの拡大のサポートは、権利で保護されたコンテンツへの複数のライセンスを一度に取得する必要がある RMS 対応アプリケーションに関連します。

  
#### この変更が重要である理由
  
RMS のバッチ処理では、AcquireLicense RMS パイプラインに要求を 1 つだけ発行して、1 つまたは複数の発行ライセンスに対する複数の RM アカウント証明書 (RAC) の使用ライセンスを取得することができます。バッチ サイズが 1 以下の場合、RMS 対応アプリケーションでは各ユーザーの使用ライセンスを個別に要求する必要があります。

  
#### 旧バージョンとの相違点
  
RMS SP2 より前のバージョンの RMS では、RMS クラスタでサポートされていた最大バッチ サイズは 1 でした。最大サイズを 1 より大きく設定すると、クラスタではその設定が無視されました。RMS SP2 では、最大バッチ サイズを最大 100 まで設定できます。


> [!NOTE]
> 要求のバッチ処理がサポートされるのは、AcquireLicense RMS パイプラインのみです。 
  
  
RMS SP2 では、要求のバッチ処理を考慮してエラー報告機能が強化されています。たとえば、10 件の要求のバッチを送信して 2 つ目と 3 つ目の要求が失敗した場合、イベント ログにはそれぞれの失敗についてイベントが書き込まれます。

  
<span id="BKMK_CIF4"></span>
#### Microsoft SQL Server 2005 との互換性
  
#### 機能の説明
  
RMS SP2 では、データベース サーバーとして Microsoft SQL Server 2005 を使用することによって、追加の構成を行わなくても RMS 構成とログ データベースに対応することができます。

  
#### この機能に該当するユーザー
  
Microsoft SQL Server 2005 と RMS SP2 の併用のサポートは、RMS データベースとして Microsoft SQL Server 2005 を使用したいと考える RMS ユーザーに関連します。

  
#### この変更が重要である理由
  
旧バージョンの RMS では、sysmessages テーブルで使用される一部のパラメータのデータ型と、Microsoft SQL Server 2005 形式の仕様との間に互換性がありませんでした。詳細については、Microsoft サポート技術情報 913372 ([http://go.microsoft.com/fwlink/?LinkId=68638](http://go.microsoft.com/fwlink/?linkid=68638)) を参照してください。

  
#### 旧バージョンとの相違点
  
RMS SP2 より前のバージョンの RMS では、エラーの発生を RMS ユーザーに通知する際に SQL RAISERROR ステートメントが使用されていました。RAISERROR ステートメントは sysmessages テーブルに対してクエリを実行し、このテーブルに格納されている RMS エラー メッセージを取得します。RMS SP2 では異なる技術を使用して SQL エラーを伝達するため、sysmessages テーブルに依存する必要がなくなります。


> [!NOTE]
> RMS SP1 から RMS SP2 にアップグレードすると、sysmessages テーブルに対してエラー メッセージのクエリは実行されなくなりますが、エラー メッセージそのものは sysmessages テーブル内に残ります。RMS SP2 をクリーン インストールすると、sysmessages テーブルに新しいエントリは追加されません。 
  
  
既知の問題  
----------
  
このリリースの RMS に関する既知の問題について次に示します。

  
#### ヘルプ ファイルが RMS SP1 を参照する
  
RMS SP2 のインストールに含まれているヘルプ ファイルでは、引き続き RMS SP1 を参照しています。RMS SP2 については、「Rights Management サービス」([http://go.microsoft.com/fwlink/?LinkId=68637](http://go.microsoft.com/fwlink/?linkid=68637)) を参照してください。

  
#### Windows Update で、x64 ベースまたは Itanium ベースのバージョンのコンピュータに RMS SP2 クライアントをインストールできない
  
x64 ベースのコンピュータに RMS クライアントまたは RMS SP1 クライアントをインストールし、そのクライアントを Windows Update で RMS SP2 クライアント (x64) にアップグレードしようとすると、インストールが失敗します。旧バージョンの RMS クライアントは 32 ビット システム用に作成されています。64 ベースのコンピュータ上でも動作しますが、RMS SP2 (x64) にアップグレードすることはできません。まず古い RMS クライアントをアンインストールしてから、再度アップデートを開始する必要があります。Windows Update がオペレーティング システムを検出し、適切な RMS SP2 クライアントを提示します。このことは、Itanium ベースのコンピュータにも該当します。

  
#### 提供の解除を行うと必ずログ リスナ サービスの開始に失敗する
  
クラスタの提供を解除すると、ログ リスナ サービスではサービスを停止状態のままにしておくことができません。サービスを完全に停止するには、コンピュータを再起動する必要があります。

  
#### ソフトウェア ベースでない信頼された発行ドメインを削除できない
  
ソフトウェア ベースでない秘密キーを実装した信頼された発行ドメインをインポートすると、そのドメインを削除できなくなります。ソフトウェア ベースでない秘密キーのインポートは、Windows Rights Management サービス管理コンソールから実行しないでください。秘密キーのエクスポートおよびインポート方法については、適切なハードウェア プロバイダにお問い合わせください。

  
#### RMS サーバーに Microsoft .NET Framework 2.0 をインストールすると IIS 仮想ルートが変更される
  
RMS SP2 は、.NET Framework Version 1.1 に含まれている ASP.NET のスクリプト マッピングを使用します。これ以降のバージョンで提供されるマッピングは RMS SP2 と互換性がありません。ただし、どちらのバージョンも、他の依存アプリケーションと干渉することなく共存できます。サーバーに .NET Framework 1.1 と .NET Framework 2.0 以降のバージョンがインストールされている場合、RMS SP2 のインストールおよび提供が正常に完了したように見えても、RMS クラスタが正しく動作しないことがあります。これは、RMS の仮想ルートを、バージョン 2.0 ではなく 1.1 の ASP.NET のスクリプト マップに登録する必要があるためです。RMS の仮想ルートを ASP.NET スクリプト マップ のバージョン 1.1 に登録するには、コマンド プロンプトで次のコマンドを実行します。

  
**%windir%\\Microsoft.NET\\Framework\\v1.1.4322&gt;aspnet\_regiis.exe -s W3SVC/1/ROOT/\_wmcs**
  
このコマンドを実行することで、RMS の仮想ルートが正しく登録され、サーバー上で RMS SP2 が正しく動作できるようになります。

  
#### Active Directory で Windows 2000 ネイティブの機能レベルを使用するとグループ メンバシップが見つからないことがある
  
Active Directory のインフラストラクチャ レベルが Windows 2000 ネイティブの機能レベルまで引き上げられている環境に RMS を展開した場合、非表示になっている配布リストのグループ メンバシップを拡張しようとすると、Active Directory オブジェクトの memberOf 属性を RMS で読み取れなくなる場合があります。RMS で memberOf 属性を読み取れるようにするには、RMS サース アカウントで使用するドメイン アカウントが、Pre-Windows 2000 Compatible Access グループのメンバである必要があります。詳細については、Microsoft サポート技術情報 812841 ([http://go.microsoft.com/fwlink/?LinkId=78152](http://go.microsoft.com/fwlink/?linkid=78152)) を参照してください。

  
#### データベースにアクセスできない場合にログ リスナ サービスから配信不能キューへメッセージ キューのメッセージが送信される
  
場合により (データベースが落ちている場合やネットワーク接続の問題など)、ログ リスナ サービスがデータベースに到達できないことがあります。この場合、配信不能キューへメッセージが送信されます。このようなメッセージを回復する (すなわちログ データベースにメッセージを送信する) 唯一の方法は、RMS 管理ツールキットに付属の RMS Queue Recovery ツールを使用することです。RMS 管理ツールキットのダウンロード方法は、[http://go.microsoft.com/fwlink/?LinkId=33841](http://go.microsoft.com/fwlink/?linkid=33841) を参照してください。


> [!NOTE]
> Recover と RecoverandPurge が LogRecoveryCmd から削除されています。これにより、すべてのメッセージがメッセージ キューを通じて返され、認証されてから、ログ データベースに送信されるようになります。 

  
#### Microsoft SQL Server 2005 へアップグレードする前に RMS SP2 にアップグレードする必要がある
  
RMS を SP2 にアップグレードし、Microsoft SQL Server 2000 から Microsoft SQL Server 2005 にアップグレードする際は、必ず RMS を先にアップグレードしてください。これにより、Microsoft SQL Server のアップグレードとの互換性の問題を回避することができます。

  
#### 名前にアポストロフィ (') が含まれる Web サイト上で RMS SP2 の提供が失敗する
  
名前にアポストロフィ (') が含まれる Web サイト上で RMS SP2 を提供しようとすると、提供処理が失敗し、**パラメータが無効です**というエラー メッセージが表示されます。Web サイト上で RMS SP2 を提供するには、Web サイトの名前からアポストロフィを削除してください。

  
#### 64 ビット バージョンの Windows Server 2003 が動作するサーバー上での ASP.NET Version 1.1 の有効化
  
RMS のヘルプの「システム要件」では、インターネット インフォメーション サービス (IIS) をインストールした後に .NET Framework 1.1 をインストールし、ASP.NET 1.1 を有効化する方法について説明されています。ただし、IIS をインストールする前に .NET Framework 1.1 をインストールする場合、ASP.NET 1.1 が Web サービス拡張の一覧に表示されないため、説明されている手順を実行できません。.NET Framework 1.1 をインストールしてから IIS をインストールした場合は、コマンド プロンプトで次のコマンドを実行して ASP.NET を有効にします。

  
**%SystemRoot%\\Microsoft.NET\\Framework\\v1.1.4322\\aspnet\_regiis.exe -i –enable**
  
.NET Framework 1.1 よりも新しいバージョンを使用する場合は、このコマンド内の **-i** を **-ir** に置き換えて、既存の IIS スクリプト マップがリセットされないようにします。

  
#### リモート フォレストの RMS サービス アカウントをローカルの groupexpansion パイプラインに追加する必要がある
  
groupexpansion パイプライン上の ACL から BUILTIN\\users が削除されるセキュリティ上の問題は修正されています。この問題が発生すると、フォレスト間でのグループ拡張のシナリオが壊れることがあります。この問題を解決するには、次の手順を実行します。

  
**リモート フォレストに RMS サービス アカウントを追加します。**  
1.  Forest1 (最初のフォレスト内のRMS ルート クラスタ) で、inetpub\\wwwroot\\\_wmcs を開きます。
  
2.  \[GroupExpansion\] フォルダを右クリックし、\[プロパティ\] を選択します。
  
3.  \[GroupExpansion のプロパティ\] ウィンドウで \[セキュリティ\] タブをクリックし、*Forest2\\RmsServiceAccount* のエントリ (rmil31\\rmsvc など) を入力します。このとき、Forest2 は2 つ目のフォレストの RMS ルート クラスタです。
  
4.  \[OK\] をクリックします。
  
5.  \[実行\] をクリックし、**iisreset**と入力して、\[OK\] をクリックします。

  
#### .NET Framework をアップグレードするとデータが失われる場合がある
  
RMS をインストールおよび提供した後に .NET Framework (CLR) Version 1.1 をアップグレードすると、vroots が .NET Framework Version 2.0 を使用するように設定されます。この問題が発生すると、ログ データベースに情報が記録されません。その結果としてデータが失われます。これに対処するには次のいずれかの操作を行います。

  
-   RMS をインストールおよび提供する前に .NET Framework をアップグレードする  
-   .NET Framework をアップグレードしてから、1.1 を使用するように vroots をリセットする
  
本リリースでのドキュメントの変更内容  
------------------------------------
  
本リリースで変更されたトピックの一覧を次に示します。

  
-   Passport による RM アカウント証明書を信頼するには ([http://go.microsoft.com/fwlink/?LinkId=70369](http://go.microsoft.com/fwlink/?linkid=70369))  
-   RMS のソフトウェア要件 ([http://go.microsoft.com/fwlink/?LinkId=70371](http://go.microsoft.com/fwlink/?linkid=70371))  
-   RMS クライアントの展開方法 ([http://go.microsoft.com/fwlink/?LinkId=70373](http://go.microsoft.com/fwlink/?linkid=70373))  
-   コマンド プロンプトによる RMS のインストール ([http://go.microsoft.com/fwlink/?LinkId=70374](http://go.microsoft.com/fwlink/?linkid=70374))  
-   RMS の主要な構成データベース テーブル ([http://go.microsoft.com/fwlink/?LinkId=70375](http://go.microsoft.com/fwlink/?linkid=70375))  
-   RMS の構成データベース証明書テーブル ([http://go.microsoft.com/fwlink/?LinkId=70376](http://go.microsoft.com/fwlink/?linkid=70376))  
-   RMS のログ データベース テーブル ([http://go.microsoft.com/fwlink/?LinkId=70377](http://go.microsoft.com/fwlink/?linkid=70377))  
-   スケール要件の評価 ([http://go.microsoft.com/fwlink/?LinkId=70378](http://go.microsoft.com/fwlink/?linkid=70378))  
-   RMS 展開のセキュリティ保護 ([http://go.microsoft.com/fwlink/?LinkId=70379](http://go.microsoft.com/fwlink/?linkid=70379))  
-   使用停止サービスの有効化 ([http://go.microsoft.com/fwlink/?LinkId=70380](http://go.microsoft.com/fwlink/?linkid=70380))  
-   外部 RMS ユーザーの計画 ([http://go.microsoft.com/fwlink/?LinkId=70381](http://go.microsoft.com/fwlink/?linkid=70381))  
-   モバイル デバイスおよびサーバー サービスでの RMS サーバー サポートの有効化 ([http://go.microsoft.com/fwlink/?LinkId=70382](http://go.microsoft.com/fwlink/?linkid=70382))
  
#### 著作権
  
*このドキュメントに記載されている情報は、このドキュメントの発行時点におけるマイクロソフトの見解を反映したものです。変化する市場状況に対応する必要があるため、このドキュメントは、記載された内容の実現に関するマイクロソフトの確約とはみなされないものとします。また、発行以降に発表される情報の正確性に関して、マイクロソフトはいかなる保証もいたしません。*
  
*このドキュメントに記載された内容は情報提供のみを目的としており、明示または黙示に関わらず、これらの情報についてマイクロソフトはいかなる責任も負わないものとします。*
  
*お客様ご自身の責任において、適用されるすべての著作権関連法規に従ったご使用を願います。このドキュメントのいかなる部分も、米国 Microsoft Corporation の書面による許諾を受けることなく、その目的を問わず、どのような形態であっても、複製または譲渡することは禁じられています。ここでいう形態とは、複写や記録など、電子的な、または物理的なすべての手段を含みます。ただしこれは、著作権法上のお客様の権利を制限するものではありません。*
  
*マイクロソフトは、このドキュメントに記載されている内容に関し、特許、特許申請、商標、著作権、またはその他の無体財産権を有する場合があります。別途マイクロソフトのライセンス契約上に明示の規定のない限り、このドキュメントはこれらの特許、商標、著作権、またはその他の無体財産権に関する権利をお客様に許諾するものではありません。*
  
*別途記載されていない場合、このソフトウェアおよび関連するドキュメントで使用している会社、組織、製品、人物、出来事などの名称は架空のものです。実在する会社名、組織名、商品名、個人名などとは一切関係ありません。*
  
*© 2007 Microsoft Corporation.All rights reserved.*
  
*Active Directory、Microsoft、MS-DOS、Visual Studio、Windows、Windows Server、SQL Server、および Windows NT は、米国 Microsoft Corporation の米国およびその他の国における登録商標または商標です。*
  
*記載されている会社名、製品名には、各社の商標のものもあります。*
