---
TOCTitle: RMS の Active Directory サポート
Title: RMS の Active Directory サポート
ms:assetid: '9589127d-19b3-44f1-b7a1-01992e78218a'
ms:contentKeyID: 18122255
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747604(v=WS.10)'
---

RMS の Active Directory サポート
================================

RMS は、次の目的で Active Directory を使用します。

-   **ユーザー認証機能を実装する。**RMS では、Active Directory が提供するディレクトリ サービスを使用して、ユーザーを認証します。認証と RMS の詳細については、この項目の「[RMS セキュリティ モデル](https://technet.microsoft.com/665db831-366d-4dca-9bb3-cc2912481fe1)」を参照してください。
-   **グループ メンバシップおよび個人のユーザー アカウント ID を解決する。**発行ライセンスの権利が個々のユーザー アカウントではなく、グループに対して付与される場合、Active Directory は、RMS が RMS で保護されたコンテンツの使用ライセンスを付与する際に用いるグループ メンバシップに関する情報を提供します。RMS では、Active Directory に対して発行される LDAP クエリの回数を減らすため、ローカル キャッシュや一元管理されたディレクトリ サービス データベースに情報がキャッシュされます。詳細については、この項目の「[RMS Active Directory キャッシュ](https://technet.microsoft.com/c721a2eb-2fe9-4346-b426-3cc169b97265)」および「[RMS ディレクトリ サービス データベース](https://technet.microsoft.com/6f6b8586-5d17-4a40-94a3-4dc738195301)」を参照してください。
-   **RMS サービス検出ロケーションを格納する。**サービス要求 (使用ライセンス、発行ライセンス、ライセンス サーバーのサブ登録など) は、その要求を許可する Web サービスの、実行モジュールの URL に送信されます。すべてのサービス要求は、サーバー Web サービス (Server.asmx) の URL を要求する Active Directory クエリによって開始されます。 これにより、サービス要求に対応する適切な URL を得ることができます。詳細については、この項目の「[RMS サービスの発行と検出](https://technet.microsoft.com/336c0d55-fd7f-4aa9-b3e6-bfd6565b1086)」を参照してください。
