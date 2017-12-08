---
TOCTitle: 'Microsoft 仮想プライベート ネットワークでの検疫サービスの実装計画ガイド - 付録 B'
Title: 'Microsoft 仮想プライベート ネットワークでの検疫サービスの実装計画ガイド - 付録 B'
ms:assetid: '5f5b92bf-e8dc-4f83-9322-f7eaa27e306a'
ms:contentKeyID: 19869592
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc163101(v=TechNet.10)'
---

Microsoft 仮想プライベート ネットワークでの検疫サービスの実装計画ガイド
=======================================================================

### 付録 B - リモート アクセス検疫サービス パラメータ

最終更新日: 2006年7月18日

##### ダウンロード

[![](images/Cc163101.icon_exe(ja-jp,TechNet.10).gif)Microsoft 仮想プライベート ネットワークでの検疫サービスの実装計画ガイド (英語情報)](http://go.microsoft.com/fwlink/?linkid=41308)

リモート アクセス検疫サービスをインストールすると、レジストリ内に複数のエントリが作成され、以下の項目を変更できます。   

**注 :** レジストリ エディタを不適切に使用すると、深刻な問題が生じ、オペレーティング システムの再インストールが必要となる場合があります。マイクロソフトは、レジストリ エディタの不正な使用による問題の解決を保証することはできません。レジストリ エディタは、お客様各自の責任において使用して下さい。

レジストリ パラメータを設定するための完全なパスは、以下のとおりです。

HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Services\\rqs

設定可能なパラメータを以下に示します。

-   **AllowedSet**。AllowedSet パラメータにより、リモート アクセス VPN 検疫サーバーで使用可能なスクリプトのバージョンを設定します。
        ```

検疫を削除するためにサービスが受け付ける文字列リストは以下のとおりです。

-   **Port (REG\_DWORD)**.Port パラメータは、RQS サービスがリッスンする TCP ポートを指定します。ポートを指定しない場合、7250 が使用されます。

-   **Authenticator (REG\_SZ)**。検疫を削除するために呼び出すモジュールを指定します。デフォルトは、mprapi.dll です。

    検疫フィルタ機能の削除を実装するカスタム DLL を作成する場合、次の機能を公開する必要があります。
        ```

<!-- -->

-   **Validator (REG\_SZ)**。RQC によって送信された署名文字列が受け付けられるかどうかを確認するモジュールを指定します。デフォルトで、RQS.exe は AllowedSet 文字列を比較します。カスタム認証 dll は、次の関数を公開する必要があります。
        ```

    lpwsString には認証文字列が含まれています。

[](#mainsection)[ページのトップへ](#mainsection)

##### 目次

-   [概要](https://technet.microsoft.com/ja-jp/library/40028620-c153-4851-bf15-d79d55d056bd(v=TechNet.10))
-   [第 1 章 - はじめに](https://technet.microsoft.com/ja-jp/library/b0912680-7a6d-43ac-92d0-cea6dcc8a063(v=TechNet.10))
-   [第 2 章 - 仮想プライベート ネットワーク検疫へのアプローチ](https://technet.microsoft.com/ja-jp/library/3ea09caf-8833-439b-be0c-039e639659b2(v=TechNet.10))
-   [第 3 章 - 問題点と要件](https://technet.microsoft.com/ja-jp/library/c43cc580-e002-49f5-bbd0-4e27a3de16cf(v=TechNet.10))
-   [第 4 章 - ソリューションの設計](https://technet.microsoft.com/ja-jp/library/7e20ac7b-c15a-4cab-9ca2-91f155b818ab(v=TechNet.10))
-   [付録 A - 検疫スクリプトのサンプル](https://technet.microsoft.com/ja-jp/library/a487808c-e193-4190-af9a-37f4ab5cd4c4(v=TechNet.10))
-   付録 B - リモート アクセス検疫サービス パラメータ
-   [付録 C - 関連リンク](https://technet.microsoft.com/ja-jp/library/d59eca38-6dd3-4576-9ba9-70cca609bcae(v=TechNet.10))
-   [謝辞](https://technet.microsoft.com/ja-jp/library/00b4b7ee-825b-4b0d-bda3-b6f040115c24(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
