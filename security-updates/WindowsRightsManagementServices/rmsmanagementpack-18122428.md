---
TOCTitle: RMS Management Pack をインポートして使用するには
Title: RMS Management Pack をインポートして使用するには
ms:assetid: 'd9a73ef0-2f81-48c2-97cc-deb7bf477389'
ms:contentKeyID: 18122428
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747688(v=WS.10)'
---

RMS Management Pack をインポートして使用するには
================================================

RMS Management Pack のインポートと使用
--------------------------------------

#### RMS Management Pack をインポートして使用するには

1.  RMS Management Pack (RMS\_MOMPack.akm) を %ProgramFiles%\\Windows Rights Management Services\\Tools フォルダから Microsoft Operations Manager (以下 MOM) サーバーにコピーします。

2.  MOM 管理者コンソールを開き、次の操作を行って RMS Management Pack をインポートします。

    1.  MOM 管理者コンソールのコンソール ツリーで、\[ルール\]項目を展開し、\[処理ルール グループ\]項目を右クリックします。
    2.  ショートカット メニューの **\[管理パックのインポート\]** をクリックします。\[管理パックのインポート\]ダイアログ ボックスが表示されます。
    3.  \[参照\]をクリックし、RMS\_MOMPack.akm を選択します。

3.  マージまたは置換オプションを指定します。マージおよび置換オプションの詳細については、マイクロソフトの Web サイト (http://www.microsoft.com/) の「Exporting and Importing Management Packs」を参照してください。

    \[Replace\]をクリックします。このオプションを使用すると、既存の処理規則グループはインポートされた Management Pack で上書きされます。ユーザー コメントは保持されません。この Management Pack を既存の Management Pack にマージする場合は、テスト環境で実行してください。また、実稼動環境に Management Pack を導入する場合は、\[Replace\]オプションを使用します。

4.  \[インポート\]をクリックして Management Pack をインポートします。

5.  **MOM 管理者**コンソールで、**\[構成\]** 項目をクリックし、**Agent Managers** フォルダをクリックします。

6.  RMS Management Pack をインポートしたサーバーの名前を右クリックし、**\[管理されたコンピュータを今すぐスキャン\]** をクリックします。
