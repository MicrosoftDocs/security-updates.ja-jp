---
TOCTitle: 'Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) をインストールして RMS のデータベース サポートを利用できるようにするには'
Title: 'Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) をインストールして RMS のデータベース サポートを利用できるようにするには'
ms:assetid: 'c9b9cd08-98c4-424f-b3fc-d685f57c002e'
ms:contentKeyID: 18122325
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747667(v=WS.10)'
---

Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) をインストールして RMS のデータベース サポートを利用できるようにするには
=============================================================================================================================

Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) のインストールによる RMS のデータベース サポートの利用
-----------------------------------------------------------------------------------------------------------

#### Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) をインストールして RMS のデータベース サポートを利用できるようにするには

1.  Microsoft SQL Server 2000 Desktop Engine (以下 MSDE 2000) をインストールするサーバー上で、ローカルの Administrators グループのメンバとなっているドメイン アカウントを使用してログオンします。

2.  [マイクロソフトの Web サイト](http://www.microsoft.com/) (http://www.microsoft.com/) から MSDE 2000 をダウンロードして自分のコンピュータに保存します。

3.  MSDE2000A.exe ファイルを実行して MSDE 2000 セットアップ パッケージをフォルダに抽出します。既定では、このフォルダの名前は MSDERelA ですが、別の名前も指定できます。

4.  コマンド プロンプトを開き、MSDE 2000 インストールを保存した場所に移動します。

5.  次のコマンドを入力して、RMS で動作させるのに適切な構成を持つ Microsoft SQL Server 2000 Desktop Engine アプリケーションをインストールします。ここで、"*パスワード*"には、強力なパスワードを設定してください。

    **Setup.exe /i setup\\sqlrun10.msi INSTANCENAME=RMS DISABLEAGENTSTARTUP=1 SAPWD**=*パスワード*

    | ![](images/Cc747667.Important(WS.10).gif)重要                                                                                                                                                                     |
    |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
    | MSDE サービスは、インストールしてから起動してください。サービスは \[コントロール パネル\]の \[サービス\]から起動できます。RMS の動作中に MSDE データベースを常に使用できるように、サービスが自動的に起動するように構成することをお勧めします。 |

RMS 構成データベースをサポートするためのデータベースをインストールするまでは、RMS をサーバーに提供しないでください。

Microsoft SQL Server Desktop Engine には企業規模のデータベースを完全に操作およびサポートするために必要なツールが含まれていないため、Microsoft SQL Server Desktop Engine はテスト環境で RMS データベースをサポートする場合にのみ使用することをお勧めします。さらに MSDE はリモート ネットワークをサポートしていないため、RMS と同じサーバー上にインストールする必要があります。また、RMS サーバーを RMS クラスタに追加することはできません。Microsoft SQL Server Desktop Engine の使用条件には、SQL Server クライアント ツールを使用して Microsoft SQL Server Desktop Engine データベースを操作することはできないと定められています。この制限により、RMS 構成データベースのバックアップおよび復元、ログ情報の表示、または構成データベースに格納されているデータの直接変更を実行することはできません。
