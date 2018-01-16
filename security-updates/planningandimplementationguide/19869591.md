---
TOCTitle: 'Microsoft 仮想プライベート ネットワークでの検疫サービスの実装計画ガイド - 付録 A'
Title: 'Microsoft 仮想プライベート ネットワークでの検疫サービスの実装計画ガイド - 付録 A'
ms:assetid: 'a487808c-e193-4190-af9a-37f4ab5cd4c4'
ms:contentKeyID: 19869591
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc163099(v=TechNet.10)'
---

Microsoft 仮想プライベート ネットワークでの検疫サービスの実装計画ガイド
=======================================================================

### 付録 A - 検疫スクリプトのサンプル

最終更新日: 2006年7月18日

##### ダウンロード

[![](images/Cc163099.icon_exe(ja-jp,TechNet.10).gif)Microsoft 仮想プライベート ネットワークでの検疫サービスの実装計画ガイド (英語情報)](http://go.microsoft.com/fwlink/?linkid=41308)

##### トピック

[](#ecaa)[検疫スクリプトのサンプル](#ecaa)  
[](#ebaa)[リモート アクセス コンポーネント](#ebaa)  
[](#eaaa)[Windows Update スクリプトの起動](#eaaa)

### 検疫スクリプトのサンプル

次のセクションでは、Microsoft の Web サイトからダウンロードできるサンプル スクリプトについて説明します。VPN Quarantine Sample Scripts.exe という名前の自己解凍型の実行可能ファイルに、スクリプトが含まれています。このファイルには、readme.txt ファイルと、各スクリプトの追加ドキュメントが含まれています。

仮想プライベート ネットワーク (VPN) 検疫スクリプトの詳細については、[VPN Quarantine Sample Scripts for Verifying Client Health Configurations](http://www.microsoft.com/downloads/details.aspx?familyid=a290f2ee-0b55-491e-bc4c-8161671b2462&displaylang=en) www.microsoft.com/downloads/details.aspx?FamilyID=a290f2ee-0b55-491e-bc4c-8161671b2462&displaylang=en (英語情報) を参照してください。

これらのスクリプトはサンプルのため、ご使用の環境に適用する際に、必要に応じてスクリプトを変更してください。次の表に、スクリプトとスクリプトの目的を説明します。

**表 A.1:検疫スクリプトのサンプル**

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >スクリプト名</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Qsamples.cmd</td>
<td style="border:1px solid black;">これは、接続マネージャ プロファイルから接続後のアクションとして呼び出され、他のスクリプトを起動する上位レベルのファイルです。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">AV.Bat</td>
<td style="border:1px solid black;">クライアントのウイルス対策ソフトウェアが最新バージョンであるか、さらにそのウイルス対策ソフトウェアに最新のウイルス シグネチャ ファイルが含まれているかを確認します。このスクリプトは、eTrust ウイルス対策ソフトウェアのみの検証を実行します。他のウイルス対策ソフトウェア パッケージ用に類似スクリプトを作成する場合は、ベンダまでお問い合わせください。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CheckHotFixes.vbs</td>
<td style="border:1px solid black;">クライアント コンピュータ上の重要な更新プログラムをチェックします。管理者は、必須の更新リストを提供する必要があります。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ICS.vbs</td>
<td style="border:1px solid black;">インターネット接続共有を確認し、必要に応じて無効にします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Passwd.vbs</td>
<td style="border:1px solid black;">企業ポリシーに対するパスワードを確認します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ScrSaver.vbs</td>
<td style="border:1px solid black;">現在のユーザーのスクリーン セーバー設定を確認し、設定が有効で、パスワード保護されていることを保証します。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WF.vbs</td>
<td style="border:1px solid black;">すべてのネットワーク インターフェイス上の Windows のファイアウォールを確認し、必要に応じて有効にします。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### リモート アクセス コンポーネント
  
次のセクションでは、2 つのリモート アクセス検疫コンポーネントの構文について説明します。
  
#### リモート アクセス検疫エージェント サービス (RQS) の構文
  
リモート アクセス検疫エージェント サービスを開始するには、コマンドラインで、次のように入力します。

 ```  
    Net start rqs  
 ```


リモート アクセス検疫エージェント サービスを停止するには、コマンドラインで、次のように入力します。
  
 ```
   Net stop rqs  
 ```

#### リモート アクセス検疫クライアント エージェント (RQC) の構文
  
RQC の構文は次のとおりです。

 ```  
   rqc ConnName TunnelConnName Port Domain UserName String  
 ```

次の表に、リモート アクセス検疫クライアント エージェント パラメータとその意味を説明します。



**表 A.2: RQC エージェント パラメータ**

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >パラメータ</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>ConnName</strong></td>
<td style="border:1px solid black;">ホスト上のリモート アクセス サーバー接続の名前を指定します。このパラメータの値は、接続マネージャ プロファイルの変数 %DialRasEntry% から継承できます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>TunnelConnName</strong></td>
<td style="border:1px solid black;">ホスト上のリモート アクセス サーバー トンネル接続の名前を指定します。このパラメータの値は、接続マネージャ プロファイルの変数 %TunnelRasEntry% から継承できます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>ポート</strong></td>
<td style="border:1px solid black;">検疫文字列の送信先ポートを指定します。リモート アクセス サーバー上のリモート エージェント検疫エージェント (RQS) が使用するデフォルト ポートは、TCP ポート 7250 です。RQS が別のポート番号を使用している場合は、RQC に別のポート番号を指定します。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>ドメイン</strong></td>
<td style="border:1px solid black;">接続ユーザーのドメインを指定します。このパラメータの値は、接続マネージャ プロファイルの変数 %Domain% から継承できます。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>UserName</strong></td>
<td style="border:1px solid black;">接続ユーザーのユーザー名を指定します。このパラメータの値は、接続マネージャ プロファイルの変数 %UserName% から継承できます。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>String</strong></td>
<td style="border:1px solid black;">管理者が作成したスクリプトのバージョンを含むテキスト文字列を指定します。/0 文字シーケンスを除く、すべての文字が使用可能です。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### Windows Update スクリプトの起動
  
ユーザーを Microsoft® Windows® Update サイトに導くために CheckHotFixes.vbs スクリプトと共に次のコードを使用します。このサイトでは、最新のセキュリティ アップデートをインストールできます。

  ```
    Prog = """C:\Program Files\Internet Explorer\iexplore.exe""" 
    WUSite= " http://windowsupdate.microsoft.com" 
    Set WshShell = CreateObject("Wscript.Shell") 
    WshShell.Run(prog & WUsite),1,TRUE
  ```

[](#mainsection)[ページのトップへ](#mainsection)
  
##### 目次
  
-   [概要](https://technet.microsoft.com/ja-jp/library/40028620-c153-4851-bf15-d79d55d056bd(v=TechNet.10))  
-   [第 1 章 - はじめに](https://technet.microsoft.com/ja-jp/library/b0912680-7a6d-43ac-92d0-cea6dcc8a063(v=TechNet.10))  
-   [第 2 章 - 仮想プライベート ネットワーク検疫へのアプローチ](https://technet.microsoft.com/ja-jp/library/3ea09caf-8833-439b-be0c-039e639659b2(v=TechNet.10))  
-   [第 3 章 - 問題点と要件](https://technet.microsoft.com/ja-jp/library/c43cc580-e002-49f5-bbd0-4e27a3de16cf(v=TechNet.10))  
-   [第 4 章 - ソリューションの設計](https://technet.microsoft.com/ja-jp/library/7e20ac7b-c15a-4cab-9ca2-91f155b818ab(v=TechNet.10))  
-   付録 A - 検疫スクリプトのサンプル  
-   [付録 B - リモート アクセス検疫サービス パラメータ](https://technet.microsoft.com/ja-jp/library/5f5b92bf-e8dc-4f83-9322-f7eaa27e306a(v=TechNet.10))  
-   [付録 C - 関連リンク](https://technet.microsoft.com/ja-jp/library/d59eca38-6dd3-4576-9ba9-70cca609bcae(v=TechNet.10))  
-   [謝辞](https://technet.microsoft.com/ja-jp/library/00b4b7ee-825b-4b0d-bda3-b6f040115c24(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
