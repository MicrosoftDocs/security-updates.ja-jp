---
TOCTitle: 'マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 B ‐ レジストリのアクセス制御の変更'
Title: 'マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 B ‐ レジストリのアクセス制御の変更'
ms:assetid: '132e1a99-29b0-4f66-956c-d009da62a51d'
ms:contentKeyID: 19869232
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc751224(v=TechNet.10)'
---

マイクロソフトの Securing Windows 2000 Server ソリューション: 付録 B ‐ レジストリのアクセス制御の変更
=====================================================================================================

### 付録 B ‐ レジストリのアクセス制御の変更

Microsoft Windows 2000 Server のレジストリに適用される既定のアクセス許可 (アクセス制御リスト (ACL) とも呼ばれる) は、Microsoft Windows NT Version 4.0 のものよりも大幅に安全になっています。このアクセス許可を、アプリケーションの互換性の問題が発生するリスクを増大させることなく、さらに厳格にすることができます。Member Server Baseline Policy (MSBP) は、hisecws.inf で定義されているレジストリの ACL を変更しません。この ACL では、認証されていないユーザー、Users、Power Users がレジストリに対して持つアクセス許可のレベルを制限しています。次のような変更によって、管理者権限よりも低いアクセス許可を持つ攻撃者がレジストリに対して望ましくない変更を加えることが非常に難しくなります。

**重要** : 既存の ACL を変更する前に、環境内で十分なテストを行う必要があります。

hisecws.inf で定義されている ACL は、主に、Windows NT 4.0 ベースの環境との下位互換性を維持するために既定で作成される Power Users グループを変更します。このテンプレートは、Power Users グループが Windows 2000 の Users グループと同じアクセス許可を持つようにします。

**注** : Power Users グループは、ドメイン コントローラでは定義されません。

**表 1 レジストリのアクセス制御の変更**

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティで保護されるキー</th>
<th style="border:1px solid black;" >適用されるアクセス許可</th>
<th style="border:1px solid black;" >継承し構成</th>
<th style="border:1px solid black;" >上書きで構成</th>
<th style="border:1px solid black;" >上書きしない</th>
<th style="border:1px solid black;" >継承</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\Software</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\Software\Classes</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>NetDDE</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
System: フル コントロール</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Protected Storage System Provider</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Secure</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>SystemCertificates</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Accessibility</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>AEDebug</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>AsrCommands</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り<br />
Backup Operators: 特殊なアクセス許可 (読み取りと書き込み)</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Classes</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Drivers32</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>EFS</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Font Drivers</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>FontMapper</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Image File Execution Options</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>IniFileMapping</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Perflib</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Interactive: 読み取り<br />
System: フル コントロール</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Perflib\009</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>ProfileList</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>SecEdit</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Setup\RecoveryConsole</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Svchost</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Time Zones</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Windows</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows NT\CurrentVersion\</strong><br />
<strong>Winlogon</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows\CurrentVersion\</strong><br />
<strong>Group Policy</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows\CurrentVersion\</strong><br />
<strong>Installer</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SOFTWARE\Microsoft\</strong><br />
<strong>Windows\CurrentVersion\</strong><br />
<strong>Policies</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\System</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\Clone</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet001</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet002</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet003</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet004</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet005</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet006</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet007</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet008</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet009</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\ControlSet010</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Control\Computername</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Control\ContentIndex</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Control\Keyboard Layout</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Control\Keyboard Layouts</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Control\Print\Printers</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Control\ProductOptions</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Control\SecurePipeServers\winreg</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Backup Operators: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Control\WMI\Security</strong></td>
<td style="border:1px solid black;">Administrators: 読み取り<br />
Creator Owner: フル コントロール<br />
System: フル コントロール</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Enum</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Hardware Profiles</strong></td>
<td style="border:1px solid black;">なし</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Services\EventLog</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>HKLM\SYSTEM\CurrentControlSet\</strong><br />
<strong>Services\Tcpip</strong></td>
<td style="border:1px solid black;">Everyone: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>USERS\. DEFAULT</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
Power Users: 読み取り<br />
System: フル コントロール<br />
Users: 読み取り</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>USERS\. DEFAULT\Software\</strong><br />
<strong>Microsoft\NetDDE</strong></td>
<td style="border:1px solid black;">Administrators: フル コントロール<br />
Creator/Owner: フル コントロール<br />
System: フル コントロール</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>USERS\. DEFAULT\SOFTWARE\</strong><br />
<strong>Microsoft\Protected Storage System Provider</strong></td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;"><br />
</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
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
-   付録 B ‐ レジストリのアクセス制御の変更  
-     
-   [付録 C ‐ オプションのファイル システムのアクセス許可](https://technet.microsoft.com/ja-jp/library/af304b67-3190-4a66-b75a-07d8fcd8585d(v=TechNet.10))  
-     
-   [付録 D ‐ 信頼されていないネットワーク内にあるサーバーでの NetBIOS の無効化](https://technet.microsoft.com/ja-jp/library/cac85879-5a6d-419c-bb04-09f0a93fb668(v=TechNet.10))  
-     
-   [付録 E ‐ セキュリティで保護された LDAP および SMTP 複製を行うためのドメイン コントローラでのデジタル証明書の構成](http://www.microsoft.com/japan/technet/security/prodtech/windows2000/secwin2k/a0701.mspx)  
-   
  
[](#mainsection)[ページのトップへ](#mainsection)
