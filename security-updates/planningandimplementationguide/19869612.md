---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 C ‐ ユーザー権利と特権'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 C ‐ ユーザー権利と特権'
ms:assetid: '9d7407aa-87b7-4564-9659-3e99abe3ac6c'
ms:contentKeyID: 19869612
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277460(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 C ‐ ユーザー権利と特権

最終更新日: 2003年2月18日

下の表に、Windows 2000 システムにおける既定のユーザーの権利の割り当てを列挙し、それらに適用される Windows 2000 のセキュリティ ターゲットへの要件を定義し、セキュリティ ターゲットの目的を満たすために必須の変更と実施するよう推奨する変更を示します。

この表には、スタンドアロンの Windows 2000 Professional と Server の両システムおよび Windows 2000 ドメイン コントローラのユーザーに割り当てられている、既定のユーザー権利を示します。また、ドメイン セキュリティ ポリシーにおける既定のユーザー権利も示します (既定ではすべて 「未定義」)。ドメインのメンバに対しては、ドメイン セキュリティ ポリシーにおける割り当てが、ローカル セキュリティ ポリシーよりも優先します。表の中に「必須」と記されている変更は、ST の要件を満たすために必要です。

ユーザー権利/特権の割り当ては、ローカル セキュリティ ポリシーおよびドメイン セキュリティ ポリシーの以下の場所に収められています。

-   Windows 2000 Professional:

    管理ツールのローカル セキュリティ ポリシーのセキュリティの設定\\ローカル ポリシー\\ユーザー権利の割り当て

-   Windows 2000 Server:

    管理ツールのローカル セキュリティ ポリシーのセキュリティの設定\\ローカル ポリシー\\ユーザー権利の割り当て

-   Windows 2000 Domain ドメイン コントローラ:

    管理ツールのドメイン コントローラ セキュリティ ポリシー ウィンドウの設定\\セキュリティの設定\\ローカル ポリシー\\ユーザー権利の割り当て

    管理ツールのドメイン セキュリティ ポリシー ウィンドウの設定\\セキュリティの設定\\ローカル ポリシー\\ユーザー権利の割り当て

<table style="width:100%;">
<colgroup>
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
<col width="14%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >ユーザー権利/特権</th>
<th style="border:1px solid black;" >説明</th>
<th style="border:1px solid black;" >スタンドアロンの Windows 2000 Professional において権利を割り当てられているグループ</th>
<th style="border:1px solid black;" >スタンドアロンの Windows 2000 Server において権利を割り当てられているグループ</th>
<th style="border:1px solid black;" >Windows 2000 のドメイン セキュリティ ポリシー において権利を割り当てられているグループ (ドメイン コントローラ内に所在)</th>
<th style="border:1px solid black;" >Windows 2000 ドメイン コントローラ において権利を割り当てられているグループ (ドメイン コントローラ セキュリティ ポリシー)</th>
<th style="border:1px solid black;" >適用されるセキュリティ ターゲットの要件 および/または 変更の理由</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ログオン権利</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ネットワーク経由でコンピュータへアクセス
(SeNetwork<br />
LogonRight)</td>
<td style="border:1px solid black;">ネットワークを通じてコンピュータに接続することを許可されるのはだれかを決定します。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
Power Users
Users
Everyone
<strong>必須の変更</strong> :
Administrators
Backup Operators
Power Users
Users
Authenticated Users</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
Power Users
Users
Everyone
<strong>必須の変更</strong> :
Administrators
Backup Operators
Power Users
Users
Authenticated Users</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Authenticated Users
Everyone
<strong>必須の変更</strong> :
Administrators
Authenticated Users</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FIA_UAU.2.1 認証 および FIA_UID.2 アクション前の利用者認証
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.3 Identification and Authentication for network logons
<strong>変更</strong> :
ゲスト/匿名ログオンを許可しないようにします。(何らかの理由でゲストが有効な場合には) 認証されていないアクセスや匿名アクセスを許す潜在的な可能性のあるアカウントを削除/置換します。「Everyone」を「Authenticated Users」で置き換えます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">バッチ ジョブとしてログオン
(SeBatch<br />
LogonRight)</td>
<td style="border:1px solid black;">バッチ ジョブ機能を使用して、ユーザーがログオンできるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ローカル ログオン
(SeInteractive<br />
LogonRight)</td>
<td style="border:1px solid black;">コンピュータのキーボードからユーザーがローカル ログオンできるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
Power Users
Users
<em>コンピュータ名\\</em>Guest
<strong>必須の変更</strong> :
Administrators
Backup Operators
Power Users
Users</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
Power Users
Users
<em>コンピュータ名</em>\\Guest
<em>コンピュータ名\\TsInternetUser</em>
<strong>必須の変更</strong> :
Administrators
Backup Operators
Power Users
Users</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>Required</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Account Operators
Backup Operators
Print Operators
Server Operators
TsInternetUser
<strong>必須の変更</strong> :
Administrators
Account Operators
Backup Operators
Print Operators
Server Operators</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FIA_UAU.2.1 認証 および FIA_UID.2 アクション前の利用者認証
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.3 Identification and Authentication for local logons
<strong>変更</strong> :
ゲスト/匿名ログオンを許可しないようにします。認証されていないアクセスや匿名アクセスを許可するので、ゲスト アカウントを削除します。TsInternetUser アカウントを削除します ・TOE に関してはターミナル サービスを実装しません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">サービスとしてログオン
(SeService<br />
LogonRight)</td>
<td style="border:1px solid black;">セキュリティ プリンシパルがサービスとしてログオンできるようにします。サービスとしてログオンする権利があらかじめ組み込まれている LocalSystem アカウントのもとで実行するように、サービスを構成することができます。他のアカウントのもとで実行するサービスには、権利を割り当てる必要があります。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ネットワーク経由でコンピュータへアクセスを拒否する
(SeDeny<br />
Network<br />
LogonRight)</td>
<td style="border:1px solid black;">ユーザーまたはグループがネットワークを通じてこのコンピュータに接続することを禁止します。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ローカルでログオンを拒否する
(SeDeny<br />
Interactive<br />
LogonRight)</td>
<td style="border:1px solid black;">ユーザーまたはグループがキーボードからローカルにログオンすることを禁止します。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">バッチ ジョブとしてログオンを拒否する
(SeDenyBatch<br />
LogonRight)</td>
<td style="border:1px solid black;">ユーザーまたはグループがバッチ キュー機能を使用してログオンすることを禁止します。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">サービスとしてログオンを拒否する
(SeDeny<br />
Service<br />
LogonRight)</td>
<td style="border:1px solid black;">ユーザーまたはグループがサービスとしてログオンすることを禁止します。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>特権</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">オペレーティング システムの一部として機能
(SeTcb<br />
Privilege)</td>
<td style="border:1px solid black;">プロセスをユーザーとして認証できるようにし、結果としてユーザーと同じリソースにプロセスがアクセスできるようにします。このサービスが必要なのは、低レベルの認証サービスだけのはずです。
既定では、ユーザーに関連するものだけにアクセスが限定されない潜在的な可能性があります。なぜならば、呼び出し元のプロセスにより、任意の追加のアクセスがアクセス トークンに入れられる可能性があるからです。さらに、懸念されることは、呼び出し元のプロセスが匿名のトークンを作成して、ありとあらゆるアクセスを行うことができることです。それに加えて、匿名のトークンからは監査ログ中のイベントを追跡するための身元情報が得られません。
LocalSystem アカウントは既定ではこの特権を使用しています。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">既定の設定により、以下の TOE セキュリティ機能要件をサポートします。
FPT_SEP.1.2, ドメイン分離
この特権を誤って使用すると、FAU_GEN.1 監査データ生成、FAU_GEN.2 ユーザー識別子の関連付け、FIA_USB.1 利用者サブジェクトの結合に違反する可能性があります。
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.5.5 Domain Separation
LocalSystem 以外のアカウントでこの特権を使用すると、責任あるセキュリティ要件を満たさなくなる可能性があります。匿名のトークンが作成される潜在的な可能性があるからです。
<strong>変更</strong> :
ドメイン ポリシーを「なし」に設定して、ドメインに既定の設定を適用し、FPT_SEP.1.2、FAU_GEN.1、FAU_GEN.2、および FIA_USB.1 を確実にサポートするようにします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ドメインにワークステーションを追加
(SeMachine<br />
Account<br />
Privilege)</td>
<td style="border:1px solid black;">ユーザーが特定のドメインにコンピュータを追加できるようにします。この特権を有効にするには、ドメイン内のドメイン コントローラ用のローカル セキュリティ ポリシーの一環として割り当てる必要があります。この特権を持つユーザーは対象のドメインに 10 台までのワークステーションを追加することができます。
Windows 2000 においては、この特権の働きは、組織単位向けのコンピュータ オブジェクトの作成許可および Active Directory 内の既定のコンピュータ コンテナと重複しています。コンピュータ オブジェクトの作成許可を持つユーザーは対象のドメインに無制限の数のコンピュータを追加することができます。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Authenticated Users
<strong>必須の変更</strong> :
Domain Admins</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Security Management Functions。権限のある管理者がドメインにコンピュータを追加したりドメインからコンピュータを削除したりできるようにします。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。認証されているユーザーに、ドメインにコンピュータを追加したりドメインからコンピュータを削除したりする特権を付与するために使用することができます。
<strong>変更</strong> :
ドメイン コントローラ セキュリティ ポリシーの既定値を Authenticated Users から Domain Admins に変更して、ドメイン インフラストラクチャの管理と構成の制御を信頼できるようにします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ファイルとディレクトリのバックアップ
(SeBackup<br />
Privilege)</td>
<td style="border:1px solid black;">システムをバックアップするためのファイルとディレクトリへのアクセス許可をユーザーに与えないようにします。この特権を選択するのは、アプリケーションにおいて NTFS バックアップ アプリケーション インタフェースを通じてアクセスを試みるときだけです。それ以外の場合は、ファイルおよびディレクトリへの通常のアクセス許可を適用します。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
Server Operators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
この特権を誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御に違反します。ユーザーが ACL の制限を回避できるようになるからです。
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにバックアップを行う特権を与えるために使用することができます。
既定のもの以外のアカウントにこの特権を割り当ててはいけません。Administrators、Backup Operators、Server Operators のいずれかのグループに属する権限のある管理者だけにこの権利を与えるようにするためです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">走査チェックのバイパス
(SeChange<br />
Notify<br />
Privilege)</td>
<td style="border:1px solid black;">任意の Microsoft Windows のファイル システムまたはレジストリ内でオブジェクトのパスを移動する間に、アクセスする権限のないフォルダをユーザーが通り抜けて行けるようにします。この権限はユーザーがフォルダの内容をリストすることを許可するものではありません。ユーザーがディレクトリを走査することを許可するだけです。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators Power Users
Users
Everyone
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators Power Users
Users
Everyone
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Authenticated Users
Everyone
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">システム時刻の変更
(SeSystem<br />
TimePrivilege)</td>
<td style="border:1px solid black;">コンピュータ内蔵の時計の時刻をユーザーが設定できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators Power Users
<strong>必須の変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators Power Users
<strong>必須の変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須の変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Server Operators
<strong>必須の変更</strong> :
変更しない</td>
<td style="border:1px solid black;">既定の設定で以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割と、FMT_MTD.1.1(g) TSF データの管理
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles、パラグラフ 6.1.5.6 Time Service。承認されているユーザーにシステム時刻を設定する特権を与えるために使用することができます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">トークン オブジェクトの作成
(SeCreate<br />
Token<br />
Privilege)</td>
<td style="border:1px solid black;">NtCreate<br />
Token() または他のトークン作成 API を呼び出すことにより、プロセスがアクセス トークンを作成できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須の変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須の変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
なし</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">既定の設定では、以下の TOE セキュリティ機能要件をサポートします。
FPT_SEP.1.2 ドメイン分離
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.5.5, Domain Separation
この特権の使用は監査できません。
この特権を誤って使用すると、FIA_USB.1 利用者サブジェクトの結合および FAU_GEN.1 監査データの生成に違反する可能性があります。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを 「なし」に設定して、ドメインに既定の設定を適用し、FPT_SEP.1.2 を確実にサポートするようにします。
プロセスがこの特権を必要とする場合、<em>LocalSystem</em> アカウント (この特権があらかじめ与えられています) を使用するようにします。別のアカウントを作成してこの特権を与えることは避けます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">永続的共有オブジェクトの作成
(SeCreate<br />
Permanent<br />
Privilege)</td>
<td style="border:1px solid black;">Windows 2000 のオブジェクト マネージャ内に、プロセスがディレクトリ オブジェクトを作成できるようにします。この特権は、Windows 2000 のオブジェクト名前空間を拡張する、カーネル モードのコンポーネントにとって役に立ちます。カーネル モードで実行されているコンポーネントには既にこの特権が割り当てられています。したがって、それらのコンポーネントにこの特権を割り当てる必要ありません。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ページ ファイルの作成
(SeCreate<br />
Pagefile<br />
Privilege)</td>
<td style="border:1px solid black;">ユーザーがページ ファイルを作成してサイズを変更できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにページ ファイルの設定を変更する特権を与えるために、使用することができます。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするとともに、不法なシステム修正を防止するようにします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">プログラムのデバッグ
(SeDebug<br />
Privilege)</td>
<td style="border:1px solid black;">ユーザーが任意のプロセスにデバッガを添付できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">この特権を割り当てると、FAU_GEN.1 監査データの生成 および FDP_ACF.1(a) セキュリティ属性によるアクセス制御 TOE セキュリティ機能要件に違反します。
この特権があると、ACL にかかわらず、ユーザーはオブジェクトにアクセスすることができます。この特権の使用状況を監査することはできません。したがって、管理者も含めて、この特権をだれにも割り当ててはいけません。
<strong>変更</strong> :
既定のすべての特権の割り当てを 「なし」に変更して、FAU_GEN.1 および FDP_ACF.1(a) に確実に準拠するようにします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">コンピュータとユーザー アカウントに委任時の信頼を付与
(SeEnable<br />
Delegation<br />
Privilege)</td>
<td style="border:1px solid black;">Active Directory 内のユーザーまたはコンピュータに関して、委任に対する信頼の設定をユーザーが変更できるようにします。この特権を与えられたユーザーまたはコンピュータはオブジェクトのアカウント制御フラグに対する書き込みアクセス許可も有していなければなりません。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須の変更</strong> :
なし</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。Active Directory 内のユーザーまたはコンピュータに関して、委任に対する信頼の設定を承認されたユーザーに許可するために使用することができます。
この特権または委任に対する信頼の設定を間違って使用すると、システムに対するトロイの木馬作戦を用いた巧妙な攻撃に、ネットワークが被害を受けやすくなります。そのような攻撃では、クライアントからの着信を装い、クライアントの資格情報を使用して、ネットワーク リソースにアクセスしようとします。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを 「なし」に設定して、承認されていないアクセスおよび修正を防止するようにします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">リモート コンピュータからの強制シャットダウン
(SeRemote<br />
Shutdown<br />
Privilege)</td>
<td style="border:1px solid black;">ネットワーク上のリモート ロケーションからユーザーがコンピュータをシャットダウンできるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Server Operators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">セキュリティ監査の生成
(SeAudit<br />
Privilege)</td>
<td style="border:1px solid black;">プロセスがセキュリティ ログ中にエントリを記録できるようにします。セキュリティ ログは承認されていないシステム アクセスおよびその他のセキュリティ関連活動を追跡するために使用します。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">LocalSystem アカウントを通じて、以下の TOE セキュリティ機能要件をサポートします。
FAU_GEN.1.1 監査データの生成
この特権をユーザーに与えると、TFS 以外のものによって生成された監査レコードが、監査ログ中に記録されます。この特権の使用状況を監査することはできません。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを 「なし」に設定します。管理者も含めて、この特権をいかなるユーザーにも許可してはいけません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">クォータの増加
(SeIncrease<br />
Quota<br />
Privilege)</td>
<td style="border:1px solid black;">他のプロセスに対するプロパティの書き込み許可を得ているプロセスが、他のプロセスに割り当てられているプロセッサのクォータを増やせるようにします。この特権はシステムをチューニングするのに役立ちます。しかし、サービス拒否攻撃などに、この特権を悪用することが可能です。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須の変更</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能をサポートするために使用することができます。
FMT_SMR.1 セキュリティ役割
しかし、この機能を管理者のみに限定するようには、ST では特に求められてはいません。
以下の TOE セキュリティ機能要件をサポートすることができます。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーに、プロセスに割り当てられたプロセッサのクォータを増やす管理能力を与えるために、使用することができます。
この特権を誤って使用すると、サービス拒否攻撃を招く可能性があります。それはセキュリティ上の深刻な問題です。プロセッサのクォータの管理はパフォーマンスおよび可用性に影響を及ぼすからです。しかし、ST ではサービス拒否攻撃への対処を求めてはいません。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理を実施するようにします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">スケジューリング優先順位の繰り上げ
(SeIncrease<br />
BasePriority<br />
Privilege)</td>
<td style="border:1px solid black;">他のプロセスに対するプロパティの書き込み許可を得ているプロセスが、他のプロセスの実行優先度を上げられるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須の変更</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
しかし、この機能を管理者のみに限定するようには、ST では特に求められてはいません。
以下の TOE セキュリティ機能をサポートするために使用することができます。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーに、プロセスの実行優先度を上げる管理能力を与えるために、使用することができます。
この特権を誤って使用すると、サービス拒否攻撃を招く可能性があります。それはセキュリティ上の深刻な問題です。プロセッサのクオータの管理はパフォーマンスおよび可用性に影響を及ぼすからです。しかし、ST ではサービス拒否攻撃への対処を求めてはいません。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理を実施するようにします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">デバイス ドライバのロードとアンロード
(SeLoad<br />
Driver<br />
Privilege)</td>
<td style="border:1px solid black;">ユーザーがプラグ アンド プレイ方式のデバイス ドライバをインストールおよびアンインストールできるようにします。この特権はプラグ アンド プレイ方式ではないデバイス ドライバには適用されません。プラグ アンド プレイ方式ではないデバイス ドライバをインストールすることができるのは管理者だけです。デバイス ドライバは信頼された (非常に特権的な) プロセスとして実行されることに注意してください。ユーザーがこの特権を乱用することが可能です。たとえば、有害なプログラムをインストールして、リソースを破壊できるアクセス許可を与えるといったことが可能です。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須の変更</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにデバイス ドライバをインストールして構成する管理能力を与えるために使用することができます。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">メモリ内のページのロック
(SeLock<br />
Memory<br />
Privilege)</td>
<td style="border:1px solid black;">プロセスがデータを物理メモリ内に保持できるようにします。それにより、ディスク上の仮想メモリにデータをページングすることが避けられます。この特権を割り当てると、システムのパフォーマンスが相当に低下する可能性があります。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">監査とセキュリティ ログの管理
(SeSecurity<br />
Privilege)</td>
<td style="border:1px solid black;">ファイル、Active Directory オブジェクト、レジストリ キーなどの個々のリソースに関して、オブジェクト アクセスの監査オプションを、ユーザーが指定できるようにします。監査ポリシー内で有効に設定されていないと、オブジェクト アクセスの監査は実際には行われません。この特権を持つユーザーは、イベント ビューアからセキュリティ ログを表示して消去することもできます。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須の変更</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
FMT_SMR.1 セキュリティ役割
FAU_SAR.1.1、 監査レビュー
FAU_SAR.2.1、 限定監査レビュー, FAU_SAR.3, 選択可能監査レビュー, FAU_SEL.1, 選択的監査
FAU_STG.1.1、 FAU_STG.1.2, 監査記録の保証
FMT_MOF.1.1(a)、 監査の管理
FMT_MTD.1.1(a)、 監査記録の管理
FMT_MTD.1.1(b)、 監査イベントの管理
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles およびパラグラフ 6.1.1 Audit Function。承認されたユーザーに監査データを構成して管理する管理能力を与えるために使用することができます。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ファームウェア環境値の修正
(SeSystem<br />
Environment<br />
Privilege)</td>
<td style="border:1px solid black;">システム環境変数を修正できるようにします。修正方法は 2 通りあります。具体的には、API を通じてプロセスに行わせる方法と、システム プロパティ アプレットを通じてユーザーが行う方法があります。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにシステム環境変数を変更する管理能力を与えるために使用することができます。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">単一プロセスのプロファイル
(SeProfile<br />
Single<br />
Process<br />
Privilege)</td>
<td style="border:1px solid black;">ユーザーが Microsoft Windows NT および Windows 2000 のパフォーマンス モニタ ツールを使用して、システム プロセスのパフォーマンスを監視できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Power Users
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Power Users
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートするために使用することができます。
FMT_SMR.1 セキュリティ役割
以下の TOE セキュリティ機能をサポートするために使用することができます。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーに、システム プロセス以外のプロセスのパフォーマンスの診断を行う管理能力を与えるために使用することができます。
しかし、この特権によって得られる能力を活用するようには、ST では特に求められてはいません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">システム パフォーマンスのプロファイル
(SeSystem<br />
Profile<br />
Privilege)</td>
<td style="border:1px solid black;">ユーザーが Microsoft Windows NT および Windows 2000 のパフォーマンス モニタ ツールを使用して、システム プロセス以外のプロセスのパフォーマンスを監視できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須の変更</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
以下の TOE セキュリティ機能をサポートします。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles およびパラグラフ 6.1.5.1 System Integrity。承認されたユーザーに、システム プロセスのパフォーマンスの診断を行う管理能力を与えるために使用することができます。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ドッキング ステーションからコンピュータを削除
(SeUndock<br />
Privilege)</td>
<td style="border:1px solid black;">ポータブル コンピュータのユーザーが [スタート] メニューの [PC の取り外し] をクリックすることにより、コンピュータのロックを解除できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Power Users
Users
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Power Users
Users
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">プロセス レベル トークンの置き換え
(SeAssign<br />
Primary<br />
Token<br />
Privilege)</td>
<td style="border:1px solid black;">親プロセスが子プロセスに関連するアクセス トークンを置換できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">この特権を割り当てることは、以下の TOE セキュリティ機能要件に違反します。
セキュリティ属性によるアクセス制御、FIA_USB.1 利用者サブジェクトの結合、および FAU_GEN.1 監査データの生成
この特権を監査することはできません。
<strong>変更</strong> :
ドメイン セキュリティ ポリシーにおける既定の特権の割り当てを「なし」に変更して、ドメインが確実に FDP_ACF.1(a)、FIA_USB.1、および FAU_GEN.1 に準拠するようにします。
どのユーザーにもこの特権を割り当ててはなりません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ファイルとディレクトリの復元
(SeRestore<br />
Privilege)</td>
<td style="border:1px solid black;">バックアップからファイルを復元するときに、ファイルおよびディレクトリへのアクセス許可をユーザーが回避して、オブジェクトの所有者としての有効なセキュリティ プリンシパルを設定できるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
Server Operators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
この特権を誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御 に違反します。ユーザーが ACL の制限を回避できるようになるからです。
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーにバックアップから復元する特権を与えるために使用することができます。
既定のもの以外のアカウントにこの特権を割り当ててはいけません。Administrators、Backup Operators、Server Operators のいずれかのグループに属する権限のある管理者だけにこの権利を与えるようにするためです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">システムのシャットダウン
(SeShutdown<br />
Privilege)</td>
<td style="border:1px solid black;">ユーザーがローカル コンピュータをシャットダウンできるようにします。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
BACKUP OPERATORS
Power Users
Users
<strong>推奨する変更</strong> :
Administrators
Backup Operators
Power Users
Authenticated Users</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Backup Operators
Power Users
<strong>推奨する変更</strong> :
Administrators
Backup Operators
Power Users
Authenticated Users</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
Account Operators
Backup Operators
Server Operators
Print Operators
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ディレクトリ サービス データの同期化
(SeSyncAgent<br />
Privilege)</td>
<td style="border:1px solid black;">ディレクトリの同期を取るサービスを行えるようにします。この特権はドメイン コントローラ上でのみ該当します。
ドメイン コントローラ上で LDAP ディレクトリ同期サービスを使用するために必要です。この特権の所有者はディレクトリ内のすべてのオブジェクトおよびプロパティを読むことができます。オブジェクトおよびプロパティが保護されていても、妨げられることはありません。既定では、この特権はドメイン コントローラ上の Administrator アカウントおよび LocalSystem アカウントに割り当てられています。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrator
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ファイルとその他のオブジェクトの所有権の取得
(SeTake<br />
Ownership<br />
Privilege)</td>
<td style="border:1px solid black;">システム内のセキュリティで保護可能な任意のオブジェクトの所有権をユーザーが取得できるようにします。その中には、Active Directory オブジェクト、ファイルとフォルダ、プリンタ、レジストリ キー、プロセス、およびスレッドを含みます。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
(未定義)
<strong>必須の変更</strong> :
Administrators</td>
<td style="border:1px solid black;"><strong>既定</strong> :
Administrators
<strong>必須</strong> :
変更しない</td>
<td style="border:1px solid black;">以下の TOE セキュリティ機能要件をサポートします。
FMT_SMR.1 セキュリティ役割
この特権を誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御に違反します。ユーザーが ACL の制限を回避できるようになるからです。
以下の TOE セキュリティ機能を実装します。
「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.4.1 Roles。承認されたユーザーに、システム内のセキュリティで保護可能な任意のオブジェクトを管理する能力を与えるために使用することができます。
<strong>変更</strong> :
この特権に関するドメイン ポリシーを Administrators に設定して、信頼性の高い管理をサポートするようにします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">読み取りを要求されていないデータのターミナル デバイスからの読み取り
(SeUnsolicited<br />
Input<br />
Privilege)</td>
<td style="border:1px solid black;">読み取りを要求されていないデータをターミナル デバイスからの読み取るために必要です。この特権は陳腐化しており、現在は使用されていません。システムに何の影響も及ぼしません。</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"><strong>既定</strong> :
なし
<strong>推奨する変更</strong> :
変更しない</td>
<td style="border:1px solid black;"> </td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 目次
  
-   [第 1 章 ‐ ハードウェアおよびソフトウェアの環境](https://technet.microsoft.com/ja-jp/library/da7603d8-d1d7-400a-9993-3ac61d633e66(v=TechNet.10))  
-   [第 2 章 ‐ オペレーティング システムのインストール](https://technet.microsoft.com/ja-jp/library/ddb614e6-9456-4f76-8dea-4018a51a810d(v=TechNet.10))  
-   [第 3 章 ‐ セキュリティで保護された構成](https://technet.microsoft.com/ja-jp/library/95fe8ebd-7386-4e95-aff8-5fca17435788(v=TechNet.10))  
-   [第 4 章 ‐ Windows 2000 Common Criteria (共通基準) セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/270098dc-f10b-41de-b26a-c2d795bca536(v=TechNet.10))  
-   [参考資料](https://technet.microsoft.com/ja-jp/library/6df170a9-3e6d-42d6-a4c3-0fd3eb71bf77(v=TechNet.10))  
-   [付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定](https://technet.microsoft.com/ja-jp/library/1adc2300-c9de-4ee0-bab7-9f8a797b03bc(v=TechNet.10))  
-   [付録 B ‐ 監査カテゴリとイベント](https://technet.microsoft.com/ja-jp/library/0fc077e8-8bf5-4b4d-a555-a8c26c9792f0(v=TechNet.10))  
-   付録 C ‐ ユーザー権利と特権  
-   [付録 D ‐ ユーザー アカウントとグループ アカウント](https://technet.microsoft.com/ja-jp/library/50b1a83f-d25a-4ffe-b601-3adc677fa632(v=TechNet.10))  
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))  
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
