---
TOCTitle: 'マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 C ‐ オプションのファイル システムのアクセス許可'
Title: 'マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 C ‐ オプションのファイル システムのアクセス許可'
ms:assetid: 'af304b67-3190-4a66-b75a-07d8fcd8585d'
ms:contentKeyID: 19869233
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc751225(v=TechNet.10)'
---

マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 C ‐ オプションのファイル システムのアクセス許可
==================================================================================================================

### 付録 C ‐ オプションのファイル システムのアクセス許可

次の表は、システム ボリュームのオプションのファイル システムのアクセス許可を示したものです。この設定は、セキュリティ テンプレート Optional File System ACLs.inf に含まれています。

**表 X.1 オプションのファイル システムの ACL**

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >ファイルおよびフォルダ</th>
<th style="border:1px solid black;" >ACL の設定</th>
<th style="border:1px solid black;" >継承方法</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">C:\config.sys</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">C:\ntbootdd.sys
<strong>注意 :</strong> SCSI が利用可能な場合に使用されます。</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">C:\ntdetect.com</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">C:\ntldr</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%ProgramFiles%</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\appmgmt</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\config</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\dllcache</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\DTCLog</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\GroupPolicy</td>
<td style="border:1px solid black;">Administrators: フル コントロール
Authenticated Users: 読み取り、実行
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\ias</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\Ntbackup.exe</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\NTMSData</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\rcp.exe</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\Regedt32.exe</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\repl</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\repl\export</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
Replicator: 読み取り、実行
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\repl\import</td>
<td style="border:1px solid black;">Administrators: フル コントロール
Replicator: 変更
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\rexec.exe</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\rsh.exe</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\secedit.exe</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDirectory%\Setup</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDirectory%\spool\Printers</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: フォルダのスキャン、属性の読み取り、拡張属性の読み取り、ファイルの作成、フォルダの作成
(フォルダとサブフォルダ)</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%
<strong>注意 :</strong> Windows 2000 オペレーティング システムがインストールされているドライブ。</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings\
Administrator</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings\
All Users</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings\
All Users\Documents\DrWatson
<strong>注意 :</strong> ワトソン博士アプリケーションのエラー ログが格納されているフォルダ。</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: フォルダのスキャン、ファイルの作成、フォルダの作成
(フォルダとサブフォルダ)</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDrive%\Documents and Settings\
All Users\Documents\DrWatson\
drwtsn32.log
<strong>注意 :</strong> ワトソン博士のエラー ログ ファイル。</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
SYSTEM: フル コントロール
Users: 変更</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%\io.sys</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemDrive%\msdos.sys</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemDrive%\Temp</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: フォルダのスキャン、ファイルの作成、フォルダの作成
(フォルダとサブフォルダ)</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\$NtServicePackUninstall$</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%\debug</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: 読み取り、実行</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\debug\UserMode</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: (フォルダのみ) - フォルダのスキャン、フォルダの一覧、ファイルの作成。(ファイルのみ) - ファイルの作成、フォルダの作成</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%\regedit.exe</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\Registration</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール
Users: 読み取り</td>
<td style="border:1px solid black;">継承</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">%SystemRoot%\repair</td>
<td style="border:1px solid black;">Administrators: フル コントロール
SYSTEM: フル コントロール</td>
<td style="border:1px solid black;">上書き</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">%SystemRoot%\ Temp</td>
<td style="border:1px solid black;">Administrators: フル コントロール
CREATOR OWNER: フル コントロール
(サブフォルダとファイル)
SYSTEM: フル コントロール
Users: フォルダのスキャン、ファイルの作成、フォルダの作成
(フォルダとサブフォルダ)</td>
<td style="border:1px solid black;">上書き</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
### 目次
  
-   [概要](https://technet.microsoft.com/ja-jp/library/71a89c24-0bfe-4e21-aeac-89ba6f84b06d(v=TechNet.10))  
-     
-   [第 1 章 ‐ Securing Windows 2000 Server 入門](https://technet.microsoft.com/ja-jp/library/18bbfc43-3d1a-4031-bc06-372064ffff72(v=TechNet.10))  
-     
-   [第 2 章 ‐ セキュリティの概要を定義する](https://technet.microsoft.com/ja-jp/library/52d2d069-16f8-4a1f-8fa8-ec6b77571799(v=TechNet.10))  
-     
-   [第 3 章 ‐ セキュリティ リスク管理の統制について理解する](https://technet.microsoft.com/ja-jp/library/81560275-04b7-4e40-8937-699e4b4defea(v=TechNet.10))  
-     
-   [第 4 章 ‐ セキュリティ リスク管理の統制を適用する](https://technet.microsoft.com/ja-jp/library/07ed8438-6264-4e30-9ca9-2235687e62e7(v=TechNet.10))  
-     
-   [第 5 章 ‐ ドメイン インフラストラクチャをセキュリティで保護する](https://technet.microsoft.com/ja-jp/library/83d7ede4-67ea-43d7-93a9-ccff8e5ca4e6(v=TechNet.10))  
-     
-   [第 6 章 ‐ Base Windows 2000 Server のハードニング](https://technet.microsoft.com/ja-jp/library/265d2c3d-5af6-4f6e-85ea-d674d4c314a7(v=TechNet.10))  
-     
-   [第 7 章 ‐ 特定サーバーの役割のハードニング](https://technet.microsoft.com/ja-jp/library/138bac60-132a-4faf-b979-503828583374(v=TechNet.10))  
-     
-   [第 8 章 ‐ 修正プログラムの管理](https://technet.microsoft.com/ja-jp/library/c474ed12-f438-4d49-acaa-260df90e5e13(v=TechNet.10))  
-     
-   [第 9 章 ‐ 監査と侵入検出](https://technet.microsoft.com/ja-jp/library/f8a8ab2f-f727-459c-aee0-c6a06f7f9fb0(v=TechNet.10))  
-     
-   [第 10 章 ‐ インシデントへの対応](https://technet.microsoft.com/ja-jp/library/4baf189b-f762-4c67-a5bc-f438a1274fec(v=TechNet.10))  
-     
-   [第 11 章 ‐ 結論](https://technet.microsoft.com/ja-jp/library/0deb6d1a-1083-4353-b645-6bdc1cbab83c(v=TechNet.10))  
-     
-   [付録 A ‐ Windows 2000 のサービスの用途](https://technet.microsoft.com/ja-jp/library/13468c13-a3f3-4b75-aadf-fec1c40fe801(v=TechNet.10))  
-     
-   [付録 B ‐ レジストリのアクセス制御の変更](https://technet.microsoft.com/ja-jp/library/132e1a99-29b0-4f66-956c-d009da62a51d(v=TechNet.10))  
-     
-   付録 C ‐ オプションのファイル システムのアクセス許可  
-     
-   [付録 D ‐ 信頼されていないネットワーク内にあるサーバーでの NetBIOS の無効化](https://technet.microsoft.com/ja-jp/library/cac85879-5a6d-419c-bb04-09f0a93fb668(v=TechNet.10))  
-     
-   [付録 E ‐ セキュリティで保護された LDAP および SMTP 複製を行うためのドメイン コントローラでのデジタル証明書の構成](http://www.microsoft.com/japan/technet/security/prodtech/windows2000/secwin2k/a0701.mspx)  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
