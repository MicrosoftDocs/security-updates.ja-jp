---
TOCTitle: Web フィルタを使用した RSA SecurID の認証
Title: Web フィルタを使用した RSA SecurID の認証
ms:assetid: '58273446-6a00-4aae-8c69-eead60686e9e'
ms:contentKeyID: 19869680
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc723567(v=TechNet.10)'
---

Web フィルタを使用した RSA SecurID の認証
=========================================

最終更新日: 2003年7月7日

**Microsoft ISA Server 2000 Feature Pack 1 バージョン 1**

RSA SecurID の認証のための Web フィルタでは、RSA SecurID の認証の資格情報に基づいた、ユーザーの認証機能が導入されています。RSA SecurID は、RSA Security, Inc. のテクノロジに基づいています。

このマニュアルでは、ユーザーに RSA SecurID 資格情報を使用した認証を求める Web サーバーの公開に必要な手順を説明します。このマニュアルでは、次のシナリオについて説明します。

-   ISA Server を使用した RSA SecurID の認証

-   二重認証

-   二重配置による認証

-   Microsoft インターネットインフォメーションサービス (IIS) サーバーでの RSA SecurID の認証

-   RSA SecurID の認証を使用した Microsoft Exchange Outlook Web Access の公開


##### トピック

[](#ejaa)[ハードウェア要件](#ejaa)

[](#eiaa)[ソフトウェア要件](#eiaa)

[](#ehaa)[作業を始める前に](#ehaa)

[](#egaa)[シナリオ 1: ISA Server を使用した RSA SecurID の認証](#egaa)

[](#efaa)[シナリオ 2: 二重認証](#efaa)

[](#eeaa)[シナリオ 3: 二重配置による認証](#eeaa)

[](#edaa)[シナリオ 4: IIS サーバーでの RSA SecurID の認証](#edaa)

[](#ecaa)[シナリオ 5: Outlook Web Access での公開](#ecaa)

[](#ebaa)[トラブル シューティング](#ebaa)

[](#eaaa)[その他のヒント](#eaaa)

### ハードウェア要件

ここで説明するシナリオには、2 台のコンピュータとインターネットへの接続が必要です。1 台のコンピュータを Web サーバーとして使用し、社内ネットワーク内に配置して、ISA Server コンピュータで保護します。セットアップをテストするには、ネットワークの外部に配置され、インターネットに接続されているコンピュータが必要です。

ISA Server は、2 つのネットワークアダプタを備えた 3 台目のコンピュータにインストールします。1 つは内部ネットワークに、もう 1 つはインターネットに接続します。

[](#mainsection)[ページのトップへ](#mainsection)

### ソフトウェア要件

ISA Server コンピュータには、以下がインストールされている必要があります。

-   Service Pack 3 が適用された Microsoft Windows 2000 Server、Windows 2000 Advanced Server、または Windows Server 2003


-   Service Pack 1 が適用された ISA Server


-   ISA Server Feature Pack 1


-   RSA SecurID の認証に使用する Web フィルタ



Web サーバーには、Windows 2000 Server、Windows 2000 Advanced Server、または Windows Server 2003 がインストールされている必要があります。Web サイトの公開に使用するインターネットインフォメーションサービス (IIS) は、Windows 2000 Server、Windows 2000 Advanced Server、および Windows Server 2003 に含まれています。

[](#mainsection)[ページのトップへ](#mainsection)

### 作業を始める前に

短時間で構成するために、Web サイトのパブリック名がバブリックインターネット DNS サーバーにより ISA Server の外部 IP アドレスにマップされていることを確認します。

**注意** これらの作業を行うには、管理者特権が必要です。

[](#mainsection)[ページのトップへ](#mainsection)

### シナリオ 1: ISA Server を使用した RSA SecurID の認証

#### 手順

このシナリオを構成するには、これから説明する次の手順を実行します。

1.  ISA Server を RSA ACE/Agent としてセットアップする

2.  RSA ACE/Agent の ISA Server ホストレコードにユーザーを追加する

3.  ACE Server コンピュータを使用して接続をテストする

4.  Web 公開ルールを作成する

5.  クライアントと ISA Server コンピュータ間のセキュリティで保護された接続を構成する

**手順 1. ISA Server を RSA ACE/Agent としてセットアップする**

**ISA Server を RSA ACE/Agent としてセットアップするには**

1.  ACE Server コンピュータで、\[スタート\] ボタンをクリックし、\[プログラム\] をポイントします。次に、\[RSA ACE Server\] をポイントし、\[Database Administration - Host Mode\] をクリックします。

2.  \[Agent Host\] メニューの \[Add Agent Host\] をクリックします。

3.  \[Name\] に ISA Server コンピュータの名前を入力します。

4.  \[Network address\] に ISA Server コンピュータの IP アドレスが表示されていない場合は入力します (この IP アドレスをメモしておきます)。

5.  RSA ACE/Server コンピュータの ACE\\Data フォルダにある Sdconf.rec ファイルを ISA Server コンピュータの %windir%\\system32 フォルダにコピーします。

**手順 2. ACE Server コンピュータの ISA Server ホストレコードにユーザーを追加する**

ACE Server コンピュータで、有効な認証の資格情報を持つユーザーを指定する必要があります。ACE Server コンピュータの ISA Server ホストレコードにユーザーを追加する方法については、ACE Server のマニュアルを参照してください。

**手順 3. ACE Server コンピュータを使用して接続をテストする**

**ACE Server コンピュータを使用して接続をテストするには**

1.  コマンドプロンプトで、「&lt;ISA のインストールディレクトリ&gt;\\sdtest.exe」と入力します。

2.  \[RSA SecurID Authentication Information\] で、\[RSA ACE/Server Test Directly\] をクリックします(英語)。

3.  \[RSA SecurID Authentication\] で \[Enter User Name\] にユーザー名を入力し、\[Enter PASSCODE\] にパスコードを入力します。

4.  認証が成功したことを示すメッセージが表示されたら \[OK\] をクリックします。

    **ヒント** ACE Server コンピュータに接続できない場合は、このマニュアルの「トラブルシューティング」を参照してください。

**手順 4. Web サイトの Web 公開ルールを作成する**

**Web 公開ルールを構成するには**

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\]、目的のアレイ、\[公開\]、\[Web 公開ルール\] の順にクリックします。

2.  詳細ペインで、目的の Web 公開ルールを右クリックし、\[Properties\] をクリックします。

3.  \[SecurID\] タブで、\[Enable authentication\] を選択します。

**手順 5. クライアントと ISA Server コンピュータ間のセキュリティで保護された接続を構成する**

クライアントと ISA Server コンピュータ間のセキュリティで保護された接続を構成するには、次の作業を行う必要があります。

-   RSA SecurID の認証用 Web フィルタの有効化

-   Web 公開ルールの構成

-   適切な着信方向の Web 要求リスナの構成

**RSA SecurID の認証用 Web フィルタを有効にするには**

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\]、目的のアレイ、\[拡張\]、\[Web フィルタ\] の順にクリックします。

2.  詳細ペインで、\[Web Filter for RSA SecurID\] を右クリックし、\[有効化\] をクリックします。

3.  Web Proxy サービスを再起動します。

**Web 公開ルールを構成するには**

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\]、目的のアレイ、\[公開\]、\[Web 公開ルール\] の順にクリックします。

2.  詳細ペインで、目的のルールを右クリックし、\[Properties\] をクリックします。

3.  \[ブリッジ\] タブで、\[公開されたサイト用には保護されたチャネル (SSL) を要求する\] チェックボックスをオンにします。

**着信方向の Web 要求リスナを構成するには**

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\] の順にクリックし、目的のアレイを右クリックします。

3.  \[着信方向の Web 要求\] タブで、目的の着信方向の Web 要求リスナに対して \[SSL リスナを有効にする\] が有効になっていることを確認します。

3.  着信方向の Web 要求リスナに対してサーバー証明書が構成されていることを確認します。

6.  

[](#mainsection)[ページのトップへ](#mainsection)

### シナリオ 2: 二重認証

このシナリオでは、Web サイトへアクセスするのに RSA SecurID と Windows の両方の認証が必要です。Windows 認証は Web サーバーで構成します。RSA SecurID の認証は ISA Server が実行します。

#### 手順

このシナリオを構成するには、まず「シナリオ 1 : ISA Server を使用した RSA SecurID の認証」で説明した手順を実行します。その後、次の手順を実行します。

-   ACE Server コンピュータで、IIS サーバーのホストレコード上で認証アクセス許可を持つすべてのユーザーを ISA Server のホストレコードに追加します。

[](#mainsection)[ページのトップへ](#mainsection)

### シナリオ 3: 二重配置による認証

このシナリオでは、Web サイトへアクセスするのに RSA SecurID と Windows の両方の認証が必要です。Windows および RSA SecurID の認証は、Web サーバーで構成します。RSA SecurID の認証は、ISA Server コンピュータでも構成できます。

このシナリオでは、ISA Server から Web サーバーへの RSA SecurID 資格情報の委任を許可することをお勧めします。

#### 手順

「シナリオ 2 : 二重認証」で説明した手順に加え、次の手順を実行する必要があります。

1.  ISA Server と IIS サーバーの両方で同じ Cookie を使用する

2.  ブラウザの IP アドレスを無視するように ISA Server を構成する

3.  ブラウザの IP アドレスを無視するように IIS サーバーを構成する

**手順 1. ISA Server と IIS サーバーの両方で同じ Cookie を使用する**

まず、ISA Server コンピュータで Cookie を生成します。次に、この Cookie を IIS サーバーコンピュータにインポートします。

**ISA Server と IIS サーバーの両方に同じ Cookie を構成するには**

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\]、目的のアレイ、\[公開\]、\[Web 公開ルール\] の順にクリックします。

2.  Web 公開ルールの詳細ペインで、目的の Web 公開ルールを右クリックし、\[Properties\] をクリックします。

3.  \[RSA SecurID\] タブで、\[このルールに対し、RSA Web Access Authentication Feature Set を有効にする\] チェックボックスをオンにします。

4.  \[Cookie の期限の制御\] で、\[ドメイン構成の管理\] をクリックします。

5.  \[ドメイン Cookie を有効にする\] チェックボックスをオンにします。

6.  \[ドメインシークレットの管理\] をクリックします。

7.  \[Generate New Domain Secret for This Web Publishing Rule\]、\[OK\] の順にクリックします。

8.  ドメインシークレットファイル (domain.sdi など) を保存するフォルダを参照し、\[Save\] をクリックします。

9.  \[パスワード\] および \[確認入力\] に、ドメインシークレットファイルを保護するためのパスワードを入力します。

    パスワードには少なくとも 6 文字を含める必要があります。

10.  IIS サーバーで、ドメインシークレットファイルをインポートします。

**手順 2. ブラウザの IP アドレスを無視するように ISA Server を構成する**

**ブラウザの IP アドレスを無視するように ISA Server を構成するには**

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\]、目的のアレイ、\[公開\]、\[Web 公開ルール\] の順にクリックします。

2.  詳細ペインで、目的の Web 公開ルールを右クリックし、\[Properties\] をクリックします。

3.  \[RSA SecurID\] タブで、\[このルールに対し、RSA Web Access Authentication Feature Set を有効にする\] チェックボックスをオンにします。

4.  \[RSA SecurID\] タブで、\[Cookie の検証時にブラウザの IP アドレスを無視する\] チェックボックスをオンにします。

**手順 3. ブラウザの IP アドレスを無視するように IIS サーバーを構成する**

**ブラウザの IP アドレスを無視するように IIS サーバーを構成するには**

-   \[Web サーバーの公開のプロパティ\] ダイアログボックスの \[RSA SecurID\] タブで、\[Cookie の検証時にブラウザの IP アドレスを無視する\] チェックボックスをオンにします。

    **重要** この場合、Web サーバーのクライアントは、実際には ISA Server コンピュータです。Cookie に隠されている IP アドレスは、ISA Server から Cookie を受け取ったクライアントの IP アドレスです。したがって、Web サーバーのクライアント (ISA Server コンピュータ) の IP アドレスとは一致しません。


[](#mainsection)[ページのトップへ](#mainsection)

### シナリオ 4: IIS サーバーでの RSA SecurID の認証

このシナリオでは、Web サーバーが RSA SecurID を認証し、ISA Server コンピュータは何も認証しません。ISA Server コンピュータには、RSA SecurID を認証するための Web フィルタをインストールしません。ただし、認証情報を渡すことができるように、ISA Server コンピュータでいくつかの設定を行う必要があります。

認証処理の間に、クライアントは /WebID/\* という形で Web サーバーに要求を送信します。この処理を ISA Server を介して行えるようにするには、パスが /WebID/ で始まる Web サーバー上のコンテンツへの匿名アクセスを許可する Web 公開ルールを構成し、パス /WebID/\* をルールに指定される宛先セットに含める必要があります。

たとえば、外部で解決可能な名前が www.microsoft.com である、localfs.microsoft.com という内部名の Web サイト上の仮想ディレクトリ /docs を公開するには、www.microsoft.com およびパス /docs を含む特定の宛先セットを許可する Web 公開ルールを有効にします。

このシナリオを構成するには、これから説明する次の手順を実行します。

1.  宛先セットを作成する

2.  Web 公開ルールを作成する

**手順 1. 宛先セットを作成する**

**宛先セットを作成するには**

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\]、目的のアレイ、\[ポリシーの要素\] の順にクリックし、\[宛先セット\] を右クリックして、\[新規作成\]、\[セット\] の順にクリックします。

2.  \[名前\] に、「MyDocs」と入力します。次に、\[追加\] をクリックします。

3.  \[宛先\] に「www.microsoft.com」と入力します。

4.  \[パス\] に「/WebID/\*」と入力します。

**手順 2. Web 公開ルールを作成する**

**Web 公開ルールを作成するには**

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\]、目的のアレイ、\[公開\] の順にクリックし、\[Web 公開ルール\] を右クリックして、\[新規作成\]、\[ルール\] の順にクリックします。

2.  \[名前\] に、「My Rule」と入力します。次に、\[次へ\] をクリックします。

3.  \[宛先セット\] で、\[指定された宛先セット\] を選択します。

4.  \[名前\] で MyDocs を選択します。次に、\[次へ\] をクリックします。

5.  \[クライアントの種類\] ページで \[すべての要求\] を選択します。次に、\[次へ\] をクリックします。

6.  \[ルールの動作\] ページで \[要求をこの内部 Web サーバーへリダイレクトする (名前または IP アドレス)\] を選択します。テキストボックスに「localfs.microsoft.com」と入力します。

7.  \[次へ\]、\[完了\] の順にクリックします。

さらに、RSA SecurID 資格情報を ISA Server から Web サーバーへ渡せるように、www.microsoft.com およびパス /WebID/\* を含み、すべてのユーザー (または特定のクライアントアドレスセット) に適用される宛先セットに適用される Web 公開ルールを構成する必要があります。

[](#mainsection)[ページのトップへ](#mainsection)

### シナリオ 5: Outlook Web Access での公開

このシナリオは、このマニュアルで説明した他のシナリオと似ています。このシナリオでは、内部ネットワークで ISA Server コンピュータの背後に配置されている Outlook Web Access サーバーに外部ユーザーがアクセスできるようにします。

まず、「シナリオ 1 : ISA Server を使用した RSA SecurID の認証」で説明した手順を実行します。その後、次の手順を実行します。

1.  \[ISA の管理\] コンソールツリーで、\[Internet Security and Acceleration Server\]、\[サーバーとアレイ\]、目的のアレイ、\[公開\] の順にクリックし、\[Web 公開ルール\] を右クリックして、\[新規作成\]、\[Outlook Web Access サーバーの公開\] の順にクリックします。

2.  \[公開されたサーバーの名前\] ページで \[ISA Server から Outlook Web Access サーバーへ SSL 接続を使う\] チェックボックスをオンにします。

3.  \[クライアントからの接続をセキュリティで保護する\] ページで \[SSL を有効にする: クライアントは SSL を使って ISA Server に接続しなくてはなりません\] チェックボックスをオンにします。

4.  ウィザードで作成された Web 公開ルールの RSA SecurID を有効にします。

[](#mainsection)[ページのトップへ](#mainsection)

### トラブル シューティング

ここでは、RSA SecurID の認証を構成するときに発生する可能性があるいくつかの一般的な問題について説明します。

#### Sdtest を実行しても ACE Server コンピュータで認証できない

「Cannot communicate with RSA Ace/Server」というメッセージが表示された場合は、以下を試してください。

-   ACE Server コンピュータで認証サービスが開始されているかどうかを確認します。必要に応じてサービスを開始し、通信が確立されていることを確認します。

-   RSA サーバーが LAT に含まれていない場合は、ISA Server のパケットフィルタにより ACE Server コンピュータへの通信がブロックされている可能性があります。通信を許可するパケットフィルタを作成してください。

-   イベントビューアのアプリケーションログで、マルチホームホストが検出され、予想されるプライマリ IP が x.x.x.x であることを示すイベントを確認します。

    x.x.x.x が、ACE Server コンピュータが ISA Server コンピュータを識別するための IP アドレスでない場合は、REG\_SZ という種類で PrimaryInterfaceIP という名前の値をレジストリキー HKEY\_LOCAL\_MACHINE\\Software\\SDTI\\ACECLIENT に追加します。ACE Server コンピュータと通信する ISA Server コンピュータのインターフェイスの IP アドレスの値を設定します。


#### ノードの検証が失敗する

ACE Server コンピュータのログに「Node Verification Failed」というメッセージが含まれている場合は、以下を試してください。

1.  ISA Server コンピュータで、レジストリから HKEY\_LOCAL\_MACHINE\\SOFTWARE\\SDTI\\ACECLIENT\\NodeSecret キーを削除します。

2.  ACE Server コンピュータで、\[Agent Host\] メニューの \[Edit Agent Host\] をクリックします。

3.  問題が発生している ISA Server コンピュータを選択し、\[Sent Node Secret\] が選択されていないことを確認します。

4.  ISA Server コンピュータで、sdtest を正常に使用できることを確認します。

#### 要求が匿名で渡される

RSA SecurID の認証が有効になっている Web 公開ルールに送信された要求が、RSA 認証フォームを受信せずに、匿名で渡される場合は、以下を試してください。

-   Extensions\\Web Filters のフィルタが有効になっていることを確認し、Web 公開ルールで SecurID の認証が有効になっていることを確認します。

-   Web Proxy サービスを再起動します。

-   sdisa.dll フィルタの読み込みに失敗したことを示すエラーコード 0x7e のイベントをイベントログで確認します。この場合は、フィルタを読み込めない原因を調べてみてください。アンインストールしてから再インストールしてください。

#### OWA サーバーへのアクセス

ユーザーがインターネットブラウザの Netscape Navigator を使用して OWA サーバーにアクセスしようとすると、問題が発生することがあります。この問題を解決するには、ISA Server Feature Pack 1 で導入されたリンク変換機能を使用します。次の手順に従います (OWA サーバーの内部名が internalmail.microsoft.com で、外部名が mail.microsoft.com であると想定しています)。

1.  \[リンク変換 Web\] フィルタを有効にします。

2.  OWA サーバーへのアクセスを許可する公開ルールのリンク変換を有効にします。

3.  OWA Web 公開ルールの \[リンクの変換\] タブに次の辞書項目を追加します。

    -   応答の文字列 : https://mail.myorg.com

    -   置換する文字列 : https://mail.myorg.com:443   

着信方向の Web 要求リスナが 443 以外のセキュリティで保護されたポートでリッスンするよう構成されている場合は、443 を特定のポート番号に置き換えてください。

[](#mainsection)[ページのトップへ](#mainsection)

### その他のヒント

ここには、いくつかの追加情報を記載してあります。

-   SSL の使用。ISA Server、またはその他の RSA ACE/Agent によって作成された Cookie が悪意のあるユーザーに盗まれた場合、権限のないユーザーがセキュリティで保護された Web コンテンツの受信に使用するおそれがあります。そのため、RSA SecurID 資格情報は、SSL チャネル上で送信することを強くお勧めします。SSL 接続では、クライアントに対して ISA Server コンピュータを認証し、通信を暗号化するために、サーバー証明書が使用されます。RSA SecureID を使用すると、クライアント自体を ISA Server に対して認証できます。Cookie をセキュリティで保護された接続で送信すると、悪意のあるユーザーから保護できます。


-   キャッシュの回避。Web 公開ルールの RSA SecurID の \[クライアントで保護されたページをキャッシュしない\] オプションは、ページがクライアントのブラウザにキャッシュされないようにします。ただし、このオプションが有効になっていても、保護されたページは ISA Server にキャッシュされます。

    「シナリオ 4 : IIS サーバーでの RSA SecurID の認証」で説明したようなシナリオでシステムのセキュリティを強化するには、IIS サーバーで RSA SecurID 認証によって保護されている Web コンテンツを ISA Server にキャッシュしないようにすることをお勧めします。そのためには、指定された宛先セットへの応答をキャッシュしないルーティングルールを作成します。詳細については、ISA Server のオンラインヘルプを参照してください。



[](#mainsection)[ページのトップへ](#mainsection)
