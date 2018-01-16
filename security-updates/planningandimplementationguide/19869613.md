---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 D ‐ ユーザー アカウントとグループ アカウント'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 D ‐ ユーザー アカウントとグループ アカウント'
ms:assetid: '50b1a83f-d25a-4ffe-b601-3adc677fa632'
ms:contentKeyID: 19869613
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277461(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 D ‐ ユーザー アカウントとグループ アカウント

最終更新日: 2003年2月18日

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
<th style="border:1px solid black;" >Windows 2000 にあらかじめ組み込まれているユーザーとグループ</th>
<th style="border:1px solid black;" >説明</th>
<th style="border:1px solid black;" >スタンドアロンの Professional</th>
<th style="border:1px solid black;" >スタンドアロンの Server</th>
<th style="border:1px solid black;" >ドメイン コントローラ</th>
<th style="border:1px solid black;" >既定のメンバ</th>
<th style="border:1px solid black;" >適用されるセキュリティ ターゲットの要件 および/または 変更の理由</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ローカル ユーザー アカウント</strong></td>
<td style="border:1px solid black;"><strong>既定のローカル ユーザー アカウント</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Administrator</td>
<td style="border:1px solid black;">コンピュータ/ドメインを管理するためにあらかじめ組み込まれているアカウント</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">2 人以上の管理者がこのアカウントを使用することは、FAU_GEN.2 利用者識別情報の関連付けに違反する可能性があります。このユーザー識別アソシエーションには、監査可能な各イベントはイベントを引き起こしたユーザーの識別情報と関連づけられなければならない、と記述されています。
<strong>要件:</strong>
権限を与えられた管理者のユーザー アカウントを管理者の責任のレベルに見合った管理グループに含めることにより、管理者に役割を割り当てます。それにより、すべての管理措置を監査ログ内で追跡して、特定のユーザー アカウントに辿り着けることが保証されます。Administrator アカウントの名前を変更して、非常時にのみ使用するようにパスワードの安全を図ります。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Guest</td>
<td style="border:1px solid black;">コンピュータ/ドメインへのゲスト アクセスのためにあらかじめ組み込まれているアカウント</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">このアカウントを誤って使用すると、FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前の利用者識別 に違反する可能性があります。
既定ではこのアカウントはすべてのシステムにおいて無効にされています。
<strong>要件:</strong>
このアカウントは無効のままにしておかなければなりません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">TsInternetUser</td>
<td style="border:1px solid black;">ターミナル サービスによって使用されるユーザー アカウントです。このアカウントはターミナル サービスのインターネット コネクタ ライセンスによって使用されます。インターネット コネクタ ライセンスが有効にされると、Windows 2000 ベースのサーバーは匿名の接続のみを 200 件受け付けます。ターミナル サービスのクライアントにログオン ダイアログ ボックスは提示されません。ターミナル サービスのクライアントは TsInternetUser アカウントを用いて自動的にログオンされます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">2 人以上のユーザーがこのアカウントを使用することは、FAU_GEN.2 利用者識別情報の関連付けに違反する可能性があります。
<strong>要件:</strong>
ターミナル サービスは TOE の目的ではありません。匿名アクセスをサポートするアカウントを許可すべきではありません。したがって、このアカウントを無効にします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">krbtgt</td>
<td style="border:1px solid black;">キー配布センター サービス アカウント。Windows 2000 の Kerberos 認証はチケットを使用して行われます。このチケットは対称キーを使用して暗号化されます。対称キーは要求されたアクセス先のサーバーまたはサービスのパスワードから導出されます。そのようなセッション チケットを要求するために、チケット許可チケット (TGT) という特殊なチケットを Kerberos サービス自体に提示しなければなりません。TGT は krbtgt アカウントのパスワードから導出されたキーを用いて暗号化されます。このキーを知っているのは Kerberos サービスだけです。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">2 人以上のユーザーがこのアカウントを使用することは、FAU_GEN.2 利用者識別情報の関連付けに違反する可能性があります。
既定ではこのアカウントはドメイン コントローラ上で無効にされています。
<strong>要件:</strong>
他のユーザー アカウントとは異なり、krbtgt アカウントはドメインにログオンするために使用することはできず、実際に有効にすることはできません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">グローバル グループ</td>
<td style="border:1px solid black;">ドメインが作成されたときに、Windows 2000 は Active Directory ストア内に、以下のグローバル グループをあらかじめ作成します。このグローバル グループを使用して、ドメイン全体で、共通なタイプのユーザー アカウントをグループ化します。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">グローバル グループを使用することにより、権限を与えられた管理者の役割および権限を与えられたユーザーの役割にユーザーを割り当てることができます。それらの役割には、ユーザーが割り当てられた先のグローバル グループに基づいて、ドメインレベルの固有のアクセス制限が課されています。グローバル グループは TOE セキュリティ機能要件 の FMT_SMR.1 セキュリティ役割をサポートします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Cert Publishers</td>
<td style="border:1px solid black;">エンタプライズの証明書発行と書き換えエージェントです。エンタプライズ証明機関を稼働させているすべてのコンピュータを含みます。Cert Publishers は Active Directory 内のユーザー オブジェクトに関する証明書を発行する権限を与えられています。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">評価された構成には Windows 2000 Cert Server は含まれていません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DnsUpdateProxy</td>
<td style="border:1px solid black;">他のクライアント (たとえば DHCP サーバー) の代りに動的な更新を行うことを許可された DNS クライアントです。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">TOE は FQDN をサポートするので、このグループのメンバになる必要はありません。
<strong>要件:</strong>
このグループにアカウントを追加してはいけません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Domain Admins</td>
<td style="border:1px solid black;">このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。このメンバはドメイン全体を管理する特権を与えられます。既定では、ドメイン コントローラ上のローカル Administrator アカウントがこのグループのメンバになっています。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Administrator</td>
<td style="border:1px solid black;">特定のドメイン内の管理と制御の役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウント (ユーザー) を追加してはいけません。&#42;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Domain Computers</td>
<td style="border:1px solid black;">ドメインのメンバであるすべてのサーバーおよびワークステーションです。ドメイン コントローラは含まれません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">ドメイン コンピュータに固有のリソースにアクセスできるようにする、ユーザーの役割の割り当てをサポートします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Domain Controllers</td>
<td style="border:1px solid black;">ドメイン内のすべてのドメイン コントローラ用のグループ アカウントです。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">DC_Name</td>
<td style="border:1px solid black;">ドメイン コントローラに固有のリソースにアクセスできるようようにする、ユーザーの役割の割り当てをサポートします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Domain Guests</td>
<td style="border:1px solid black;">このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。このグループのメンバはネットワークを通じてのみシステムにアクセスすることを許され、既定では非常に限られた特権しか与えられません。このグループには当初はドメインの Guest ユーザー アカウントだけが含まれます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Guest</td>
<td style="border:1px solid black;">Guest/匿名アカウントは FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別に違反する可能性があります。
<strong>要件:</strong>
このグループを使用してはいけません。このグループから、Guest も含めて、すべてのアカウントを削除します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Domain Users</td>
<td style="border:1px solid black;">このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。ドメイン環境においては、Administrator アカウントおよびすべての新しいユーザー アカウントが自動的にこのグループのメンバに入れられます。このグループはドメインおよびドメイン内のすべての Windows コンピュータの Users ローカル グループのメンバでもあります。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Administrator
Guest
Krbtgt
TsInternetUser
(既定では、すべての新しいユーザーが追加されます。)</td>
<td style="border:1px solid black;">ドメインのリソースにアクセスできるようにする、ユーザーの役割の割り当てをサポートします。
Guest/匿名アカウントは 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別に違反する可能性があります。
<strong>要件:</strong>
Guest アカウントおよび TsInternetUser アカウントを削除します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Enterprise Admins</td>
<td style="border:1px solid black;">ネットワーク全体にわたって管理と制御を行えるようにします。既定では、ドメイン コントローラの Administrator アカウントがメンバです。このグループは Active Directory 内のフォレスト全体にわたって変更を行う権限を与えられています。その例として、子ドメインの追加が挙げられます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Administrator (ドメイン コントローラ)</td>
<td style="border:1px solid black;">ネットワーク全体にわたる管理と制御の役割の割り当てをサポートします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Group Policy Creator Owner</td>
<td style="border:1px solid black;">このグループのメンバはドメインのグループ ポリシーを修正することができます。このグループは Active Directory 内に新しいグループ ポリシー オブジェクトを作成する権限を与えられています。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Administrator</td>
<td style="border:1px solid black;">ドメイン レベルのグループ ポリシーを維持するように指定された、管理的役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Schema Admins</td>
<td style="border:1px solid black;">Active Directory スキーマの管理者です。このグループは Active Directory 内のスキーマを変更する権限を与えられています。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Administrator</td>
<td style="border:1px solid black;">Active Directory スキーマを管理するように指定された、管理的役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ドメイン ローカル グループ</td>
<td style="border:1px solid black;">このグループは、特にドメイン コントローラ上および Active Directory ストア内でタスクを行うための、特権およびアクセス許可をユーザーに与えます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">このグループは、権限を与えられた管理者の役割および権限を与えられたユーザーの役割に、ユーザーを割り当てられるようにします。その際、ユーザーが割り当てられているドメイン ローカル グループに基づいて、ドメイン コントローラへの固有のアクセス制限が課されます。 このグループは TOE セキュリティ機能要件の FMT_SMR.1 セキュリティ役割をサポートします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Account Operators</td>
<td style="border:1px solid black;">このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。このグループはシステムおよびドメインに関するユーザー アカウントおよびグループ アカウントを、メンバが管理できるようにします。既定では、このグループは、Active Directory のすべてのコンテナおよび組織単位 (OU) 内のユーザー、グループ、およびコンピュータに関するアカウントを、作成、修正、および削除するアクセス許可を有しています。ただし、Builtin コンテナとドメイン コントローラ OU は対象外です。このグループは Administrators グループおよび Domain Admins グループを修正するアクセス許可は有していません。また、それらのグループのメンバのアカウントを修正するアクセス許可も有していません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">ドメイン内のユーザー アカウントを管理するように指定された、管理的な役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">このグループのメンバはすべてのドメイン コントローラおよびドメイン自体の上で、すべての管理的なタスクを実行することができます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Administrator
Domain Admins
Enterprise Admins</td>
<td style="border:1px solid black;">ドメイン内のすべてのドメイン コントローラおよびリソースに対する全面的な管理的アクセス権利を有する、管理的な役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Backup Operators</td>
<td style="border:1px solid black;">このグループのメンバはすべてのドメイン コントローラ上で Windows Backup を使用して、ファイルのバックアップと復元を行うことができます。その際、それらのファイルを保護するアクセス許可の制約を受けません。このグループのメンバはコンピュータにログオンすることもコンピュータをシャットダウンすることもできます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このアカウントを誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御に違反する可能性があります。
このグループのメンバは、通常は自分がアクセスしないファイルおよびディレクトリを抽出することができます。このグループに属しているユーザーは、バックアップの目的で、任意のファイルを開くことができ、読み取り用に開いた後で、任意の場所にファイルをリダイレクトすることができます。
既定では、Backup Operators グループに属していなくても、ユーザーは適切なファイルおよびディレクトリへのアクセス許可を有しているファイルを、バックアップおよび復元することができます。
Administrator アカウントは最初からバックアップ権利を全面的に有しています。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DnsAdmins</td>
<td style="border:1px solid black;">DNS 管理グループです。このグループは DNS サーバーおよびそのゾーンを全面的に管理する権限を有しています。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">DNS の管理を担当する管理的な役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Guests</td>
<td style="border:1px solid black;">このグループはシステム上のリソースに限定的にアクセスできるようにします。このグループのメンバはデスクトップ環境に永続的な変更を加えることはできません。サービスの中には、インストールされると、ユーザーを自動的にこのグループに加えるものがあります。たとえば、IIS は匿名ユーザー アカウントをこのグループに追加します。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Guest (ローカル)
Domain Guests
TsInternetUser</td>
<td style="border:1px solid black;">Guest/匿名アカウントは FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別 に違反する可能性があります。
<strong>要件:</strong>
このグループを使用してはいけません。このグループから、Guest も含めて、すべてのアカウントを削除します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Pre-Windows 2000 Compatible Access</td>
<td style="border:1px solid black;">ドメイン内のすべてのユーザーおよびグループに関して読み取りアクセスを許可する、下位互換性グループです。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><strong>要件:</strong>
Windows 2000 以前のシステムとの下位互換性を持つことは、TOE の目的ではありません。したがって、このグループにユーザーを追加してはいけません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Print Operators</td>
<td style="border:1px solid black;">ドメイン コントローラだけに組み込まれているグループです。このグループのメンバはドメイン コントローラ上のネットワーク プリンタをセットアップおよび管理することができます。このグループのメンバは、ドメイン内のプリンタ共有リソースを、作成、変更、および削除する権利を与えられます。また、このグループのメンバは、システムにローカルにログオンすることも、システムをシャットダウンすることもできます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">ドメイン内の印刷サービスの管理を担当する管理的な役割の割り当てをサポートします。
<strong>推奨:</strong>
これは管理的機能です。したがって、権限を与えられた管理者だけをこのグループに追加すべきです。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Replicator</td>
<td style="border:1px solid black;">ドメイン コントローラ上でのファイルの複製をサポートします。このグループはドメイン コントローラ上のファイル複製サービスによって使用されます。このグループのメンバはファイル複製サービスを構成することができます。ユーザー ログオン スクリプトのようなファイルを Windows 2000 ベースのコンピュータ間で自動的にコピーするために、ディレクトリ レプリケータ サービスが使用されます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.5.3 TFS Data Replication Consistency に示されている要件をサポートするために使用することができます。ドメイン内のディレクトリ複製サービスの管理を担当する管理的な役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RAS and IAS Servers</td>
<td style="border:1px solid black;">このグループ内のサーバーはユーザーのリモート アクセス プロパティにアクセスすることができます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Server Operators</td>
<td style="border:1px solid black;">このグループはドメイン コントローラの役割を果たしている Windows 2000 のサーバー上でのみ利用することができます。このグループのメンバはサーバー管理タスクを遂行することができます。その例として、共有プリンタ、共有ディレクトリ、およびファイルの作成、変更、および削除が挙げられます。このグループのメンバはファイルのバックアップと復元を行うこと、サーバーのコンソールをロックすること、システムをシャットダウンすることもできます。このグループのメンバはシステムのポリシーを変更することやサービスを起動および停止することはできません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">サーバーの保守を担当する管理的な役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Users</td>
<td style="border:1px solid black;">このグループはエンド ユーザーとしてコンピュータを動かすのに必要な権利をユーザーに提供します。その例として、アプリケーションの実行およびファイルの管理が挙げられます。既定では、新しいすべてのローカル ユーザーがこのグループに追加されます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Authenticated Users
Domain Users
INTERACTIVE
(既定では、新しいすべてのローカル ユーザーがこのグループに追加されます。)</td>
<td style="border:1px solid black;">ドメイン コントローラ上のリソースにアクセスする、ユーザーの役割の割り当てをサポートします。
<strong>要件:</strong>
認証を受けずにアクセスする潜在的な危険があるアカウント (たとえば、Guest) をこのグループに追加してはいけません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ローカル グループ</td>
<td style="border:1px solid black;">すべてのスタンドアロンの Windows 2000 Server、メンバ サーバー、および Professional ワークステーションにこのグループがあらかじめ組み込まれています。このグループのメンバはグループが属するコンピュータ上でタスクを遂行することができます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">このグループでは、権限を与えられた管理者の役割および権限を与えられたユーザーの役割に、ユーザーを割り当てることができます。それらの役割には、ユーザーが割り当てられた先のローカル グループに基づいて、ローカルに固有のアクセス制限が課されています。このグループは TOE セキュリティ機能要件の FMT_SMR.1 セキュリティ役割をサポートします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">このグループのメンバはコンピュータ全体を完全に制御することができます。Windows 2000 が稼働しているメンバ サーバーまたはコンピュータがドメインに加えられると、ローカル Administrators グループに Domain Admins グループが追加されます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><strong>スタンドアロン:</strong>
Administrator
<strong>ドメイン メンバ:</strong>
Administrator
Domain Admins</td>
<td style="border:1px solid black;">コンピュータ上のすべてのローカル リソースに対する全面的な管理アクセス権限を持つ、管理的な役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Backup Operators</td>
<td style="border:1px solid black;">このグループのメンバは Windows Backup を使用して、いつでもコンピュータのバックアップと復元を行うことができます。ファイル システムのセキュリティに制約されることはありません。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">このアカウントを誤って使用すると、FDP_ACF.1(a) セキュリティ属性によるアクセス制御に違反する可能性があります。
このグループのメンバは、通常は自分がアクセスしないファイルおよびディレクトリを抽出することができます。このグループに属しているユーザーは、バックアップの目的で、任意のファイルを開くことができ、読み取り用に開いた後で、任意の場所にファイルをリダイレクトすることができます。
既定では、Backup Operators グループに属していなくても、ユーザーは適切なファイルおよびデ ィレクトリへのアクセス許可を有しているファイルを、バックアップおよび復元することができます。
Administrator アカウントは最初からバックアップ権利を全面的に有しています。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Guests</td>
<td style="border:1px solid black;">このグループはシステム上のリソースに限定的にアクセスできるようにします。このグループのメンバはデスクトップ環境に永続的な変更を加えることはできません。
既定では、コンピュータの Guest ユーザー アカウントはこのグループのメンバです。このアカウントは既定では無効にされています。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><strong>スタンドアロン Professional:</strong>
Guest
<strong>スタンドアロン Server:</strong>
Guest
TsInternetUser
<strong>ドメイン メンバ:</strong>
Add Domain Guests</td>
<td style="border:1px solid black;">Guest/匿名アカウントは FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別に違反する可能性があります。
<strong>要件:</strong>
このグループを使用してはいけません。このグループから、Guest も含めて、すべてのアカウントを削除します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Power Users</td>
<td style="border:1px solid black;">このグループのメンバであるユーザーはコンピュータ上でローカル ユーザー アカウントを作成して修正し、リソースを共有することができます。ただし、コンピュータを完全に制御する権利は与えられません。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">特定のコンピュータ上で権利を多く与えられた、ユーザーの役割の割り当てをサポートします。
このグループでは、ローカル ユーザー アカウントの管理およびローカル リソースの管理のような、管理者レベルの特権が与えられます。権限を与えられている管理者ではないユーザーをこのグループのメンバに入れることは、通常は権限のある管理者に与えられる特権をユーザーが持つことになる分だけ、FMT_MTD.1(c) ユーザー属性の管理、FMT_MTD.1(d)、認証データの管理 (ユーザーが作成したアカウント関して)、FMT_MTD.1(e) ロックアウト期間の管理 (ユーザーが作成したアカウント関して)、最小パスワード文字数の管理 (ユーザーが作成したアカウント関して)、および FMT_SMR.1 セキュリティ役割に違反する可能性があります。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Replicator</td>
<td style="border:1px solid black;">このグループのメンバはファイル複製サービスを構成することができます。ユーザー ログオン スクリプトのようなファイルを Windows 2000 ベースのコンピュータ間で自動的にコピーするために、ディレクトリ レプリケータ サービスが使用されます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;">「<a href="http://download.microsoft.com/download/win2000srv/ccsectar/2.0/nt5/en-us/w2kccst.pdf">Windows 2000 Security Target</a>」 パラグラフ 6.1.5.3 TFS Data Replication Consistency に明示されている要件をサポートするために使用することができます。コンピュータ内でディレクトリ複製サービスの管理を担当する管理的な役割の割り当てをサポートします。
<strong>要件:</strong>
このグループに非管理的アカウントを追加してはいけません。&#42;</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Users</td>
<td style="border:1px solid black;">このグループはエンド ユーザーとしてコンピュータを動かすのに必要な権利をユーザーに提供します。その例として、アプリケーションの実行およびファイルの管理が挙げられます。既定では、新しいすべてのローカル ユーザーがこのグループに追加されます。Windows 2000 が稼働しているメンバ サーバーまたはコンピュータがドメインに加えられると、ローカル User グループに Domain Users グローバル グループ、Authenticated Users 特殊グループ、および INTERACTIVE 特殊グループが追加されます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><strong>スタンドアロン:</strong>
Authenticated Users
INTERACTIVE
(既定では、新しいすべてのローカル ユーザーが追加されます。)
<strong>ドメイン メンバ:</strong>
Authenticated Users
Domain Users
INTERACTIVE
(既定では、新しいすべてのローカル ユーザーが追加されます。)</td>
<td style="border:1px solid black;">コンピュータ上のローカル リソースにアクセス可能なユーザーの役割の割り当てをサポートします。
<strong>要件:</strong>
認証を受けずにアクセスする潜在的な危険があるアカウント (たとえば、Guest) をこのグループに追加してはいけません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">システム グループ</td>
<td style="border:1px solid black;">システム グループではメンバの所属を修正することはできません。各グループは特定のユーザー クラスまたはオペレーティング システム自体を表します。これらのグループは Windows 2000 システムによって自動的に作成されますが、グループ管理 GUI に表示はされません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Anonymous Logon</td>
<td style="border:1px solid black;">Windows 2000 によって認証されていないユーザー アカウントがこのグループに含まれます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">認証されていないすべてのユーザー</td>
<td style="border:1px solid black;">このアカウントを誤って使用すると、FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別に違反する可能性があります。
<strong>要件:</strong>
このアカウントにはリソースへのアクセス許可またはユーザーの権利を与えてはいけません。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Authenticated Users</td>
<td style="border:1px solid black;">コンピュータ上または Active Directory サービス内に有効なユーザー アカウントを持つすべてのユーザーがこのグループに含まれます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">認証されているすべてのユーザー</td>
<td style="border:1px solid black;">FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前の利用者識別をサポートします。
<strong>推奨:</strong>
リソースへの匿名アクセスを防止するために、Everyone グループの代わりに Authenticated Users グループを使用します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">BATCH</td>
<td style="border:1px solid black;">バッチ キュー機能を通じてログオンしたすべてのユーザーがこのグループに含まれます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATOR OWNER</td>
<td style="border:1px solid black;">リソースを作成または所有しているユーザーのユーザー アカウントがこのグループに含まれます。Administrators グループのメンバがリソースを作成した場合は、Administrators グループがそのリソースの所有者となります。このグループは Windows 2000 Server または Professional 上の共有可能なリソースごとに作成されます。継承可能なアクセス制御エントリ (ACE) 内のプレースホルダです。ACE が継承されるとき、この SID がオブジェクトの作成者の SID で置き換えられます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">このグループのメンバはリソースを作成または所有しているユーザーです。</td>
<td style="border:1px solid black;">オブジェクトの所有者の属性の割り当てを通じて、FDP_ACF.1(a) セキュリティ属性によるアクセス制御をサポートします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CREATOR GROUP</td>
<td style="border:1px solid black;">継承可能な ACE 内のプレースホルダです。ACE が継承されるとき、この SID がオブジェクトの作成者のプライマリ グループの SID で置き換えられます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DIALUP</td>
<td style="border:1px solid black;">現在ダイアルアップ接続しているユーザーがこのグループに含まれます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">すべてのダイアルイン ユーザー</td>
<td style="border:1px solid black;"><strong>要件:</strong>
ダイアルアップ サービスは TOE の目的ではありません。したがって、このアカウントにリソースへのアクセス許可またはユーザーの権利を与えてはいけません。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ENTERPRISE DOMAIN CONTROLLER</td>
<td style="border:1px solid black;">Active Directory サービスを利用するフォレスト内のすべてのドメイン コントローラを含むグループです。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Everyone</td>
<td style="border:1px solid black;">コンピュータにアクセスするすべてのユーザーがこのグループに含まれます。Windows 2000 では、有効なユーザー アカウントを持たないユーザーは Guest として認証されます。ユーザーは Everyone グループに割り当てられているすべての権利とアクセス許可を自動的に取得します。
匿名ユーザーおよびゲストをはじめ、すべてのユーザーを含むグループです。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">このグループのメンバには、Windows 2000 Server または Professional にアクセスするすべてのユーザーが含まれます。ローカルにアクセスするか、ネットワークを通じてアクセスするか、RAS を通じてアクセスするかを問いません。認証されているユーザーも認証されていないユーザーも含まれます。基本的には、システムにアクセスするあらゆるユーザーが Everyone グループのメンバになります。</td>
<td style="border:1px solid black;">このアカウントを誤って使用すると、FAU_GEN.2 利用者識別情報の関連付け、FIA_UAU.2 認証、および FIA_UID.2 アクション前のユーザー識別 に違反する可能性があります。
<strong>要件:</strong>
このアカウントにリソースへのアクセス許可またはユーザーの権利を割り当ててはなりません。必要に応じて、Authenticated Users または個々のユーザー アカウントまたはグループを使用します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">INTERACTIVE</td>
<td style="border:1px solid black;">コンピュータにローカルにログオンしたユーザーのユーザー アカウントがこのグループに属します。Interactive グループのメンバは自分達が実際に所在する場所にあるコンピュータ上のリソースにアクセスすることができます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">Windows 2000 Server または Professional にローカルにログインしたユーザーがこのグループに含まれます。ネットワークを通じて接続されているユーザーはこのグループのメンバになれません。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">NETWORK</td>
<td style="border:1px solid black;">ネットワーク上の他のコンピュータからコンピュータ上の共有リソースに現在接続しているユーザーがこのグループに含まれます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">このグループに属するのは、ネットワークを介してリソースに接続したユーザーです。対話型でローカル ログインしたユーザーは含まれません。</td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROXY</td>
<td style="border:1px solid black;">この SID は Windows 2000 では使用されていません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">RESTRICTED</td>
<td style="border:1px solid black;">この SID は Windows 2000 では使用されていません。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SELF</td>
<td style="border:1px solid black;">Active Directory 内のアカウント オブジェクトまたはグループ オブジェクト上の継承可能な ACE 内のプレースホルダです。ACE が継承されるとき、この SID がアカウントを保持するセキュリティ プリンシパルの SID で置き換えられます。</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SERVICE</td>
<td style="border:1px solid black;">サービスとしてログオンしたすべてのセキュリティ プリンシパルを含むグループです。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SYSTEM</td>
<td style="border:1px solid black;">サービス、ユーティリティ、およびデバイス ドライバを実行するために、オペレーティング システムによって使用されるアカウントです。このアカウントは無制限の能力を持ち、レジストリの SAM のように Administrator でさえも拒否されるリソースにもアクセスすることができます。</td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">このアカウントは、権限のある管理者の管轄外にある TSF 保護機能のようなセキュリティ サービスを実行するために、Windows 2000 によって使用されます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">TERMINAL SERVER USER</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><img src="images/Dd277461.check(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><strong>要件:</strong>
ターミナル サービスのサポートは TOE の目的ではありません。したがって、このアカウントにリソースへのアクセス許可またはユーザーの権利を与えてはいけません。</td>
</tr>
</tbody>
</table>
 

\* 要件が満たされている限り、セキュリティで保護されたオブジェクトの DACL から対応するグループを削除する必要はありません。

[](#mainsection)[ページのトップへ](#mainsection)

##### 目次

-   [第 1 章 ‐ ハードウェアおよびソフトウェアの環境](https://technet.microsoft.com/ja-jp/library/da7603d8-d1d7-400a-9993-3ac61d633e66(v=TechNet.10))
-   [第 2 章 ‐ オペレーティング システムのインストール](https://technet.microsoft.com/ja-jp/library/ddb614e6-9456-4f76-8dea-4018a51a810d(v=TechNet.10))
-   [第 3 章 ‐ セキュリティで保護された構成](https://technet.microsoft.com/ja-jp/library/95fe8ebd-7386-4e95-aff8-5fca17435788(v=TechNet.10))
-   [第 4 章 ‐ Windows 2000 Common Criteria (共通基準) セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/270098dc-f10b-41de-b26a-c2d795bca536(v=TechNet.10))
-   [参考資料](https://technet.microsoft.com/ja-jp/library/6df170a9-3e6d-42d6-a4c3-0fd3eb71bf77(v=TechNet.10))
-   [付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定](https://technet.microsoft.com/ja-jp/library/1adc2300-c9de-4ee0-bab7-9f8a797b03bc(v=TechNet.10))
-   [付録 B ‐ 監査カテゴリとイベント](https://technet.microsoft.com/ja-jp/library/0fc077e8-8bf5-4b4d-a555-a8c26c9792f0(v=TechNet.10))
-   [付録 C ‐ ユーザー権利と特権](https://technet.microsoft.com/ja-jp/library/9d7407aa-87b7-4564-9659-3e99abe3ac6c(v=TechNet.10))
-   付録 D ‐ ユーザー アカウントとグループ アカウント
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
