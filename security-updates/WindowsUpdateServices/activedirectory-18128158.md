---
TOCTitle: Active Directory 以外の環境で自動更新を構成する
Title: Active Directory 以外の環境で自動更新を構成する
ms:assetid: '75ee9da8-0ffd-400c-b722-aeafdb68ceb3'
ms:contentKeyID: 18128158
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc708449(v=WS.10)'
---

Active Directory 以外の環境で自動更新を構成する
===============================================

Active Directory 以外の環境では、次のいずれかの方法で自動更新を構成できます。

-   グループ ポリシー オブジェクト エディタを使用して、ローカル グループ ポリシー オブジェクトを編集する

-   レジストリ エディタ (Regedit.exe) を使用して、レジストリを直接編集する

-   Windows NT 4.0 形式のシステム ポリシーを使用して、これらのレジストリ エントリを中央から展開する

### WSUS 環境のオプション

WSUS 環境のオプションのレジストリ エントリは、次のサブキーに格納されます。

**HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate**

次の表に、キーと値の範囲を示します。

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Windows Update エージェント環境のオプションのレジストリ キー
</th>
</tr>
<tr>
<th style="border:1px solid black;" >
エントリ名

</th>
<th style="border:1px solid black;" >
値

</th>
<th style="border:1px solid black;" >
データ型

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**ElevateNonAdmins**

</td>
<td style="border:1px solid black;">
範囲 = 1 または 0
  
1 = Users セキュリティ グループのユーザーが更新プログラムを承認するかどうか決定できます。
  
0 = Administrators ユーザー グループのユーザーのみが更新プログラムを承認するかどうか決定できます。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**TargetGroup**

</td>
<td style="border:1px solid black;">
クライアント側のターゲットに使用される、コンピュータが属しているコンピュータ グループの名前 ("TestServers" など)。このポリシーは、**TargetGroupEnabled** と互いにペアで使用されます。

</td>
<td style="border:1px solid black;">
Reg\_String

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**TargetGroupEnabled**

</td>
<td style="border:1px solid black;">
範囲 = 1 または 0
  
1 = クライアント側のターゲットを使用します。
  
0 = クライアント側のターゲットを使用しません。このポリシーは、**TargetGroup** とペアで使用されます。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**WUServer   **

</td>
<td style="border:1px solid black;">
自動更新および既定の API 呼び出し元によって使用される WSUS サーバーの HTTP URL。このポリシーは、**WUStatusServer** とペアで使用されます。有効にするには、両方を同じ値に設定する必要があります。

</td>
<td style="border:1px solid black;">
Reg\_String

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**WUStatusServer**

</td>
<td style="border:1px solid black;">
**WUServer** キーで構成された WSUS サーバーを使用するクライアント コンピュータに関して、レポート情報が送信されるサーバーの HTTP URL。このポリシーは、**WUServer** とペアで使用されます。有効にするには、両方を同じ値に設定する必要があります。

</td>
<td style="border:1px solid black;">
Reg\_String

</td>
</tr>
</table>
 
![](images/Cc708449.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)

### 自動更新の構成オプション

自動更新の構成オプションのレジストリ エントリは、次のサブキーに格納されます。

**HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate\\AU**

次の表に、キーと値の範囲を示します。

 
<table style="border:1px solid black;">
<tr>
<th colspan="3">
自動更新の構成のレジストリ キー
</th>
</tr>
<tr>
<th style="border:1px solid black;" >
エントリ名

</th>
<th style="border:1px solid black;" >
値の範囲と意味

</th>
<th style="border:1px solid black;" >
データ型

</th>
</tr>
<tr>
<td style="border:1px solid black;">
**AUOptions**

</td>
<td style="border:1px solid black;">
範囲 = 2、3、4、または 5
  
2 = ダウンロードの前に通知を行います。
  
3 = 自動的にダウンロードとインストールの通知を行います。
  
4 = 自動的にダウンロードとスケジュールされたインストールを実行します。**ScheduledInstallDay** と **ScheduledInstallTime** の値が存在する場合のみ有効です。
  
5 = 自動更新は必須ですが、エンド ユーザーが構成できます。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**AutoInstallMinorUpdates**

</td>
<td style="border:1px solid black;">
範囲 = 0 または 1
  
0 = 優先度の低い更新プログラムを他の更新プログラムと同様に扱います。
  
1 = 優先度の低い更新プログラムをサイレント インストールします。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**DetectionFrequency**

</td>
<td style="border:1px solid black;">
範囲 = n。n = 時間 (1 ～ 22)。
  
検出サイクルの間隔。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**DetectionFrequencyEnabled**

</td>
<td style="border:1px solid black;">
範囲 = 0 または 1
  
1 = DetectionFrequency を有効にします。
  
0 = カスタムの DetectionFrequency を無効にして、既定値の 22 時間を使用します。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**NoAutoRebootWithLoggedOnUsers**

</td>
<td style="border:1px solid black;">
範囲 = 0 または 1
  
1 = ログオン中のユーザーが、コンピュータを再起動するかどうかを選択できます。
  
0 = 自動更新によって、5 分以内にコンピュータが再起動されることがユーザーに通知されます。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**NoAutoUpdate**

</td>
<td style="border:1px solid black;">
範囲 = 0 または 1
  
0 = 自動更新を有効にします。
  
1 = 自動更新を無効にします。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**RebootRelaunchTimeout**

</td>
<td style="border:1px solid black;">
範囲 = n。n = 分 (1 ～ 1440)。
  
スケジュールされた再起動の再確認間隔。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**RebootRelaunchTimeoutEnabled**

</td>
<td style="border:1px solid black;">
範囲 = 0 または 1
  
1 = **RebootRelaunchTimeout** を有効にします。
  
0 = カスタムの **RebootRelaunchTimeout** を無効にして、既定値の 10 分を使用します。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**RebootWarningTimeout**

</td>
<td style="border:1px solid black;">
範囲 = n。n = 分 (1 ～ 30)。
  
期日のある更新プログラム、またはスケジュールされた更新プログラムをインストールした後、再起動までの時間を警告としてカウントダウンする長さ (分)。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**RebootWarningTimeoutEnabled**

</td>
<td style="border:1px solid black;">
範囲 = 0 または 1
  
1 = **RebootWarningTimeout** を有効にします。
  
0 = カスタムの **RebootWarningTimeout** を無効にして、既定値の 5 分を使用します。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**RescheduleWaitTime**

</td>
<td style="border:1px solid black;">
範囲 = n。n = 分 (1 ～ 60)。
  
実行されなかったスケジュール済みのインストール時刻以降、自動更新がシステム起動後に更新プログラムを適用するまで待機する時間 (分)。
  
このポリシーは、スケジュールされたインストールにのみ適用され、期日のあるインストールには適用されません。期日が切れた更新プログラムは、常に直ちにインストールされます。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**RescheduleWaitTimeEnabled**

</td>
<td style="border:1px solid black;">
範囲 = 0 または 1
  
1 = **RescheduleWaitTime** を有効にします。
  
0 = **RescheduleWaitTime** を無効にして、実行されなかったインストールを次にスケジュールされているインストール時刻に試行します。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**ScheduledInstallDay**

</td>
<td style="border:1px solid black;">
範囲 = 0、1、2、3、4、5、6、または 7
  
0 = 毎日。
  
1 ～ 7 = 日曜 (1) ～ 土曜 (7) の該当日。
  
**AUOptions** が 4 の場合のみ有効です。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**ScheduledInstallTime**

</td>
<td style="border:1px solid black;">
範囲 = n。n = 24 時間形式の時刻 (0 ～ 23)。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**UseWUServer**

</td>
<td style="border:1px solid black;">
このキーが設定されていない限り、**WUServer** の値は考慮されません。

</td>
<td style="border:1px solid black;">
Reg\_DWORD

</td>
</tr>
</table>
 
![](images/Cc708449.arrow_px_up(ja-jp,WS.10).gif) [ページのトップへ](#ctl00_rs1_eb1_panel1)
