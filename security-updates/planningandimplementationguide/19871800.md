---
TOCTitle: IIS Lockdown Wizard ツール
Title: IIS Lockdown Wizard ツール
ms:assetid: 'fcdb991f-db6b-4408-b39c-141415b4d2ec'
ms:contentKeyID: 19871800
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362854(v=TechNet.10)'
---

IIS Lockdown Wizard 2.1 ツール
==============================

マイクロソフトは IIS 4.0 または 5.0 Web サーバーをセキュリティで保護することを簡素化するIIS Lockdown Wizard ツールをバージョンアップしました。このツールは IIS Lockdown Wizard 2.1 ツールと呼ばれ、Web サーバーを迅速かつ容易に正しい設定にすることができます。この正しい設定とは、管理者が提供したいサービスのみをサーバーが提供するということです。お客様はこのツールを使用して、システムを Web サーバーを標的としたセキュリティ上の脅威から保護することができます。

このツールは、サーバーの使用用途や使用しているサーバー製品ごとに適切な設定のテンプレートを用意しています。このテンプレートをお客様の環境に合わせて編集する事で、よりセキュアな状態を作り出す事が可能です。テンプレートが用意されていない場合にも、きめ細かな設定が可能なテンプレートに頼らない方法があります。

**本ツールご使用にあたっての注意**
 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="100%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><ul>
<li>本ツールは、IIS の管理者向けに作成されたものです。IIS 上で必要な機能が何であるかを十分検討された上で使用してください。IIS Lockdown Wizard 2.1 ツールにより必要な機能までも制限してしまった場合、 IIS 上で動作していた アプリケーションが一切動作しなくなる可能性があります。<br />
また、本ツールを日本語環境で使用する場合、問題の発生するテンプレートがあります。</li>
<li>本ツールを使用することで、修正モジュールが自動的に適用されることはございません。よりセキュアなサイトを実現するために、必ず修正モジュールの適用をお願いいたします。</li>
<li>マイクロソフト セキュリティツールキット CD には、IIS Lockdown Wizard 2.0 が含まれております。新しいバージョンの IIS Lockdown Wizard 2.1 は本ページの最後からダウンロード可能になっております。</li>
</ul>
<br />
</td>
</tr>
</tbody>
</table>
 
**本ツールをご使用いただく前に**

本ツールは、 IIS および、NTFS パーティションのアクセス権を多数変更いたします。  
そのため、本ツールをご使用いただく前に、 IIS のメタベースおよび、ディスクのバックアップを取っていただくことを強くお勧めいたします。

**使用方法** **(Lockdown)**

1.  IISLockD.exe を起動します。

2.  "Welcome to the Internet Information Services Lockdown Wizard' の画面が表示されます。

3.  \[次へ &gt;\] をクリックします。使用許諾が表示されますので了承の場合は 'I agree' ラジオボタンをクリックします。

4.  \[次へ &gt;\] をクリックします。 'Select Server Template' が表示され使用する環境にあったテンプレート (template) を選択します。

5.  \[次へ &gt;\] をクリックします。

6.  'URLScan' が表示され URLScan filter のインストールを行うかを選択します。インストールする場合は、チェックボックをチェックします。

7.  \[次へ &gt;\] をクリックします。

8.  'Ready to Apply Setting' が表示され行われる作業内容を確認します。

9.  \[次へ &gt;\] をクリックします。

10. 'Applying Security Settings' が表示され実際に変更作業が開始されます。この処理は数分かかる場合があります。

11. \[次へ &gt;\] をクリックします。

12. 'Competing the Internet Information Services Lockdown Wizard' が表示され作業が完了します。

13. \[完了\] をクリックします。

14. ツールを終了します。

**使用方法** **(UnDo)**

UnDo を行うことで、本ツールにより設定を変更する前の状態に戻すことができます。しかしながら、本ツールにより設定した後に行っていただいた変更作業についても UnDo される場合があります。

1.  IISLockD.exe を起動します。

2.  "This Server Was Already Configured' の画面が表示されます。

3.  \[次へ &gt;\] をクリックします。

4.  以下の内容のダイアログが表示されます。
        
    ```
    "This Process will undo the configuration changes that you made to this server using the internet Information Services Lockdown Wizard. However, it will not restore services that you've uninstalled using Add/Remove Programs. Important Any Configuration chages that have been made since this wizard was run will be lost. Do you want to continue"
    ```

5.  Undo を行う場合は、\[はい\] をクリックします。

6.  'Restore Security Setting' が表示され UnDo 処理が行われます。 この処理は数分かかる場合があります。

7.  \[次へ &gt;\] をクリックします。

8.  'Restore Complete' が表示され作業が完了します。

9.  \[完了\] をクリックします。

10. ツールを終了します。

[](#mainsection)[ページのトップへ](#mainsection)

**日本語環境で問題が確認されているテンプレート**

-   **Commerce Server 2000**

    Commerce Server ビジネス デスクから、完成済みの静的レポートを表示すると 404 エラーが発生する場合があります。これは、レポートを表示する際の URI の中に 日本語コードが含まれており、 Commerce Server 2000 のテンプレートでは、日本語を許可していないために発生いたします。

    *解決策*  
    %WINNT%\\system32\\inetsrv\\urlscan\\urlscan.ini ファイルを開き、以下の 2 点の変更を行い IIS を再起動させてください。

    -   AllowHighBitCharacters の値を 1 に書き換えてください。

        *変更前:*  
        AllowHighBitCharacters=0

        *変更後:*  
        AllowHighBitCharacters=1

    -   \[DenyUrlSequences\] 内の \\ の前に ; を挿入してコメントアウトしてください。

        *変更前:*  
        \[DenyUrlSequences\]
        \\ ; Don't allow backslashes in URL

        *変更後:*  
        \[DenyUrlSequences\]
        ;\\ ; Don't allow backslashes in URL

-   **BizTalk Server 2000**

    **BizTalk Server** 仕様ファイルやマップファイルに日本語名のフォルダや日本語のファイル名を使用している場合、表示する際に以下のようなエラーが発生する場合があります。

    ファイル http://&lt;server\_name&gt;/&lt;directory&gt;/日本語.xml を WebDAV から取得できません。この時点でサーバーを利用できない可能性があります。後で WebDAV から取得してください。

    これは、仕様ファイルやマップファイルを表示する際の URI の中に 日本語コードが含まれており、 BizTalk Server 2000 のテンプレートでは、日本語を許可していないために発生いたします。

    *解決策*
    %WINNT%\\system32\\inetsrv\\urlscan\\urlscan.ini ファイルを開き、以下の 2 点 の変更を行い IIS を再起動させてください。

    -   AllowHighBitCharacters の値を 1 に書き換えてください。

        *変更前:*  
        AllowHighBitCharacters=0

        *変更後:*  
        AllowHighBitCharacters=1

    -   \[DenyUrlSequences\] 内の \\ の前に ; を挿入してコメントアウトしてください。

        *変更前:*  
        \[DenyUrlSequences\]
        \\ ; Don't allow backslashes in URL

        *変更後:*  
        \[DenyUrlSequences\]
        ;\\ ; Don't allow backslashes in URL

-   **Exchange 2000 (OWA, PF Management, IM, SMTP, NNTP)**  
    Exchange System Manager から Public Folder の管理ができなくなるなどのいくつかの問題が確認されております。以下の技術情報を参照し、URLScan.ini の内容を適切に編集してください。

    [309508 : \[XCCC\] Exchange 環境での IIS Lockdown と URLscan の設定](http://support.microsoft.com/kb/309508)

-   
-   **Exchange 5.5 (Outlook Web Access)**  
    いくつかの問題が確認されております。    
    以下の技術情報を参照し、URLScan.ini の内容を適切に編集してください。

    [309508 : \[XCCC\] Exchange 環境での IIS Lockdown と URLscan の設定](http://support.microsoft.com/kb/309508)

-   
-   **SharePoint Portal Server**  
    SharePoint Portal Server の管理コンソールでワークスペースが 「×」 と表示され、ワークスペースのプロパティが開かない場合があります。

    *解決策*  
    %WINNT%\\system32\\inetsrv\\urlscan\\urlscan.ini ファイルを開き、以下の変更を行い IIS を再起動させてください。

    -   \[DenyUrlSequences\] 内の \\ と % の前に ; を挿入してコメントアウトしてください。

        *変更前:*  
        \[DenyUrlSequences\]  
        \\ ; Don't allow backslashes in URL  
        % ; Don't allow escaping after normalization

        *変更後:*  
        \[DenyUrlSequences\]  
        ;\\ ; Don't allow backslashes in URL  
        ;% ; Don't allow escaping after normalization

-   **SharePoint Team Services**  
    日本語を含んだファイルやサブ Web を取り扱う際に問題となることがあります。

    *解決策*  
    %WINNT%\\system32\\inetsrv\\urlscan\\urlscan.ini ファイルを開き、以下の 2 点の変更を行い IIS を再起動させてください。

    -   AllowHighBitCharacters の値を 1 に書き換えてください。

        *変更前:*  
        AllowHighBitCharacters=0 

        *変更後:*  
        \[DenyUrlSequences\]  
        AllowHighBitCharacters=1

    -   \[DenyUrlSequences\] 内の \\ の前に ; を挿入してコメントアウトしてください。

        *変更前:*  
        \[DenyUrlSequences\]  
        \\ ; Don't allow backslashes in URL

        *変更後:*  
        \[DenyUrlSequences\]  
        ;\\ ; Don't allow backslashes in URL

**その他、問題が確認されている製品**

-   **Site Server / Site Server Commerce Edition / MCIS**  
    Site Server , Site Server Commerce Edition および Site Server 上で動作する MCIS 環境では、 IIS Lock Down Wizard を使用しないでください。Site Server は、多種多様な機能を持ち、IIS の機能の大半を利用します。そのため、 IIS Lock Down Wizard を有効に利用する事ができません。

-   **Project Central**  
    ガントチャートを使用できなくなります。
    現在、原因調査・回避策を準備中ですので、 Project Central 環境への 本ツールの適用はしばらくお待ちください。

-   **CGI / ISAPI Extension** **を利用する製品**  
    CGI/ISAPI Extension を利用している場合 IIS Lock Down Wizard 2.1 の設定によっては、 \*.exe, \*.dll へのアクセスを拒否する設定になっているため、一切使用できなくなる場合があります。その際は、 URLScan の設定を調整する必要があります。

**NTFS** **のアクセス権の変更に伴う問題**  

本ツールは、不特定ユーザーからのディスクへの書き込みを防止するために、IIS で使用される匿名ユーザーアカウントからの書き込みが出来ないようアクセス権を変更します。  
これにより、CGI や ASP を利用してディスク上に情報を記録している場合、正常に動作しない場合があります。
その際は、必要なアクセス権をツールの使用後に再度与える必要があります。

**IIS Lockdown Wizard 2.1 ツールのダウンロード**  

IIS Lockdown Wizard 2.1 ツールをダウンロードするには [ここをクリック](http://www.microsoft.com/japan/technet/security/tools/tools/locktldl.htm) してください。

[](#mainsection)[ページのトップへ](#mainsection)
