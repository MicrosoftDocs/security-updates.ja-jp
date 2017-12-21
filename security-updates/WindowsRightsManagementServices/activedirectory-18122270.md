---
TOCTitle: Active Directory サービス検出の無効化
Title: Active Directory サービス検出の無効化
ms:assetid: '9d97e7fb-5b05-4853-ad7b-6cc82b9729f0'
ms:contentKeyID: 18122270
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747614(v=WS.10)'
---

Active Directory サービス検出の無効化
=====================================

RMS サービスとクライアントは、ローカル レジストリからサービスの場所を検索します。レジストリ内の特定のキーに値がない場合、RMS サービスとクライアントは、Active Directory からサービス接続ポイント (SCP) を探索します。つまり、サーバーまたはクライアントのレジストリに特定のキーを入力した場合、既定の Active Directory 探索設定は無視されます。

> [!NOTE]
> SCP が Active Directory に公開されないように RMS ルート クラスタが構成されている場合、これらのキーを使用して、RMS クライアントに正しい場所を指定できます。 

このセクションでは、レジストリ エントリとその作成方法について説明します。

ライセンスのみのクラスタのサブ登録の上書き
------------------------------------------

ライセンスのみのクラスタを準備していて、そのクラスタを、ライセンスのみのクラスタの Active Directory フォレストに展開したルート クラスタとは別のルート クラスタでサブ登録したい場合、サブ登録とアカウント証明サービスの両方の探索を上書きする必要があります。

#### レジストリ エントリの説明

サブ登録およびアカウント証明サービスを上書きするには、次のレジストリ エントリを使用します。

-   **SubEnrollmentURL**。このエントリは、ライセンス サーバーがサーバー ライセンサ証明書を要求するときに使用するルート クラスタへのパスを指定します。
-   **GicURL**。このエントリは、このライセンスのみのクラスタのアカウント証明サービスへのパスを指定します。

#### エントリの詳細

32 ビット バージョンの Windows Server 2003 を実行しているコンピュータの場合、ライセンスのみのクラスタ サブ登録のサービス探索エントリの完全なレジストリ サブキー パスは次のとおりです。

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0**

64 ビット バージョンの Windows Server 2003 を実行しているコンピュータの場合、ライセンスのみのクラスタ サブ登録のサービス探索エントリの完全なレジストリ サブキー パスは次のとおりです。

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0**

次の表は、サービス探索を上書きするときに追加できるエントリの一覧です。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名前</th>
<th style="border:1px solid black;" >型</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">SubEnrollmentURL</td>
<td style="border:1px solid black;">String</td>
<td style="border:1px solid black;">http(または https)://<em>サーバー名</em>/_wmcs/certification/subenrollservice.asmx</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GicURL</td>
<td style="border:1px solid black;">String</td>
<td style="border:1px solid black;">http(または https)://<em>サーバー名</em>/_wmcs/certification/certification.asmx</td>
</tr>
</tbody>
</table>
  
公開用のクライアント側のサービス探索の上書き  
--------------------------------------------
  
ユーザーが自分のコンピュータのコンテンツを公開する場合に、企業で使われているトポロジに応じて公開に使用するサーバーの場所を上書きすることができます。通常、公開に使用するサーバーの場所は、クライアントが Active Directory を使用して探索します。クライアント コンピュータに適切なレジストリ キーを追加することで、クライアントはこれらの方法を無視して、代わりにレジストリ エントリの値に指定された URL を使用するようになります。
  
| ![](images/Cc747614.note(WS.10).gif)注                                                                                                                |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| このセクションに記載されているクライアントの上書き設定は、独立したエントリではなく、キーとして作成する必要があります。キーの値は、各キーの既定のエントリに作成する必要があります。 |
  
#### レジストリ キーの説明
  
次のレジストリ キーは、RMS クラスタの自動探索の上書きに使用できます。
  
-   **Activation**。このレジストリ キーは、コンピュータ ライセンス認証サービスの URL を定義します。Service Pack 1 以降の RMS クライアントを実行している場合、このレジストリ キーはもう使用されません。  
-   **EnterprisePublishing**。このレジストリ キーは、このクライアントがライセンス要求に使用する RMS インストールの URL を定義します。  
-   **CloudPublishing**。このレジストリ キーは、マイクロソフトがホストしているライセンス サービスの URL を定義します。クライアントから RMS インストールへのアクセスは許可されていないが、インターネットにはアクセス可能な場合に使用できます。
  
#### キーの詳細
  
クライアント側の公開用サービス探索エントリの完全なレジストリ サブキー パスは次のとおりです。
  
**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\MSDRM\\ServiceLocation\\**
  
次の表は、RMS クライアント コンピュータに追加してサービス探索を上書きできるレジストリ キーの一覧です。
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名前</th>
<th style="border:1px solid black;" >型</th>
<th style="border:1px solid black;" >値</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Activation</td>
<td style="border:1px solid black;">String</td>
<td style="border:1px solid black;">http(または https)://<em>RMS クラスタ名</em>/_wmcs/Certification (<em>RMS クラスタ名</em>は RMS クラスタの名前)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">EnterprisePublishing</td>
<td style="border:1px solid black;">String</td>
<td style="border:1px solid black;">http(または https)://<em>RMS クラスタ名</em>/_wmcs/Licensing (<em>RMS クラスタ名</em>は RMS クラスタの名前)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CloudPublishing</td>
<td style="border:1px solid black;">String</td>
<td style="border:1px solid black;">http(または https)://<em>FQDN クラスタ名</em>/_wmcs/Licensing (<em>FQDN クラスタ名</em>は RMS クラスタの完全修飾ドメイン名)。</td>
</tr>
</tbody>
</table>
  
これらのレジストリ キーは、組織のすべてのクライアントが確実に正しい公開サーバーを使用するように、Systems Management Server またはグループ ポリシーを使用して実装することをお勧めします。
  
| ![](images/Cc747614.Caution(WS.10).gif)注意                                                                                                     |  
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| レジストリを正しく編集しないと、システムが正常に動作しなくなる場合があります。レジストリを変更する前に、コンピュータ上の重要なデータのバックアップを作成する必要があります。 |
  
サンプル レジストリ ファイル (.reg) は、RMS クラスタの各サーバーの適切なレジストリ キーにインポートするために使用できます。
  
**RMS クラスタの各サーバーに適切なレジストリ キーをインポートするには**  
1.  次のサンプル レジストリ ファイルをメモ帳にコピーします。
  
    `Windows Registry Editor Version 5.00`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation]`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\Activation]`
  
    `@="http://<RMS_cluster_name>/_wmcs/certification"`
  
    `[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDRM\ServiceLocation\EnterprisePublishing]`
  
    `@="http://<RMS_cluster_name>/_wmcs/licensing"`
  
2.  &lt;RMS クラスタ名&gt; を RMS クラスタの名前で置換します。
  
3.  ファイルの拡張子を .reg にして保存します。
  
4.  エクスプローラでファイルの名前をダブルクリックします。
  
5.  \[ユーザー アカウント制御\] ダイアログ ボックスが表示された場合、このボックスに希望する動作が表示されていることを確認し、\[継続\] をクリックします。。情報をレジストリに追加するかどうかを確認するメッセージが表示されたら \[はい\] をクリックします。
