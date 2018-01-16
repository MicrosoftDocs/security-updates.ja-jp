---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート'
ms:assetid: '8842dd66-853c-4c8f-bb69-ae750f139356'
ms:contentKeyID: 19869615
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277463(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド  
=============================================  
  
### 付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート  
  
最終更新日: 2003年2月18日  
  
##### トピック  
  
[](#ehaa)[G-1. ベースライン Windows 2000 Server セキュリティ構成テンプレート](#ehaa)  
[](#egaa)[G-2. ベースライン Windows 2000 Professional セキュリティのテンプレート](#egaa)  
[](#efaa)[G-3. ベースライン Windows 2000 ドメイン セキュリティ ポリシーのテンプレート](#efaa)  
[](#eeaa)[G-4. ベースライン Windows 2000 ドメイン コントローラ セキュリティ ポリシーのテンプレート](#eeaa)  
[](#edaa)[G-5. 高セキュリティ Windows 2000 Server セキュリティのテンプレート](#edaa)  
[](#ecaa)[G-6. 高セキュリティ Windows 2000 Professional セキュリティのテンプレート](#ecaa)  
[](#ebaa)[G-7. 高セキュリティ Windows 2000 ドメイン セキュリティ ポリシーのテンプレート](#ebaa)  
[](#eaaa)[G-8. 高セキュリティ Windows 2000 ドメイン コントローラ セキュリティ ポリシーのテンプレート](#eaaa)  
  
### G-1. ベースライン Windows 2000 Server セキュリティ構成テンプレート
<p> </p>
<table style="border:1px; solid black;">  
<tr>  
<td>  
; ; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:    CC_Baseline_W2K_Server.inf  
; テンプレート バージョン:   1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - パスワード ポリシー  
;--------------------------------------------------------------------------------  
MinimumPasswordLength = 8  
RequireLogonToChangePassword = 0  
ClearTextPassword = 0  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - ロックアウト ポリシー  
;--------------------------------------------------------------------------------  
LockoutBadCount = 5  
ResetLockoutCount = 30  
LockoutDuration = -1  
;注意 : アカウントをロックアウトしないとき、下記の構成は行いません。  
;ResetLockoutCount = 30  
;LockoutDuration = -1  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - Kerberos ポリシー  
;--------------------------------------------------------------------------------  
[Kerberos Policy]  
TicketValidateClient = 1  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - 監査ポリシー  
;--------------------------------------------------------------------------------  
;注意 : ベースライン ポリシーには監査ポリシーの設定は指定されていません。  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-545,*S-1-5-32-547,*S-1-5-32-551,*S-1-5-11,*S-1-5-32-544  
SeInteractiveLogonRight = *S-1-5-32-545,*S-1-5-32-547,*S-1-5-32-551,*S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\CachedLogonsCount=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateFloppies=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateCDRoms=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SecurityLevel=4,0  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DisableCAD=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Control\Session Manager\ProtectionMode=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\Memory Management\ClearPageFileAtShutdown=4,1  
MACHINE\System\CurrentControlSet\Control\Print\Providers\LanMan Print Services\Servers\AddPrinterDrivers=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\RestrictAnonymous=4,1  
;=========================================================================  
;評価された構成に必須のセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は Common Criteria (共通基準) に基づく評価された構成に必須です。  
;これらの設定はセキュリティ ポリシーのインターフェイスには表示されません。  
=========================================================================  
;--------------------------------------------------------------------------------  
;DirectDraw を無効にする。ここでは、アプリケーションからグラフィックス  
;ハードウェアに直接アクセスされることを防止するために、DirectDraw を  
;無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\GraphicsDrivers\DCI\Timeout=4,0  
;--------------------------------------------------------------------------------  
;不要なサービスを無効にする。これらのサービスはサービス インターフェイスに  
;表示されません。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\audstub\Start=4,4  
MACHINE\System\CurrentControlSet\Services\mnmdd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisTapi\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisWan\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NDProxy\Start=4,4  
MACHINE\System\CurrentControlSet\Services\ParVdm\Start=4,4  
MACHINE\System\CurrentControlSet\Services\PptpMiniport\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Ptilink\Start=4,4  
MACHINE\System\CurrentControlSet\Services\RasAcd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Rasl2tp\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Raspti\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Wanarp\Start=4,4  
;--------------------------------------------------------------------------------  
;OS/2 および POSIX サブシステムを削除する。ここでは、OS/2 および POSIX の  
;既定値を削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\SubSystems\Optional=7,""  
;--------------------------------------------------------------------------------  
;カーネル オブジェクト属性を保護する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\EnhancedSecurityLevel=4,1  
;--------------------------------------------------------------------------------  
;ヌル セッション アクセスを制限する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\RestrictNullSessAccess=4,1  
;--------------------------------------------------------------------------------  
;名前つきパイプを通じた ヌル セッション アクセスを制限する。ここでは、既定値を  
;削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionPipes=7,""  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionShares=7,""  
;--------------------------------------------------------------------------------  
;SP3 を編集する。監査ログがいっぱいのしきい値のパーセントに達したときに、  
;監査イベントを生成します。ここでは、セキュリティ イベント ログが 90  
;パーセントにまで達したときに、監査イベントを生成するように設定します。  
;この値がローカルの状況に合わない場合には、管理者はローカルの要件に基づいて、  
;このキーのパーセント値を調整することができます。  
;--------------------------------------------------------------------------------  
MACHINE\SYSTEM\CurrentControlSet\Services\Eventlog\Security\WarningLevel=4,90  
;--------------------------------------------------------------------------------  
;イベント ログ - ログの設定  
;--------------------------------------------------------------------------------  
;監査ログの保存日数  
;0 = 必要に応じてイベントを上書きする  
;1 = 保存日数に指定した日数を過ぎたら上書きする  
;2 = イベントを上書きしない (手作業でログをクリア)  
;注意 : ベースライン ポリシーにはイベント ログの設定は指定されていません。  
;--------------------------------------------------------------------------------  
;システム サービス - Common Criteria (共通基準) に基づく評価された構成に含まれていない  
;サービスを無効にします。  
;--------------------------------------------------------------------------------  
[Service General Setting]  
TrkWks,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
seclogon,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
Schedule,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
ClipSrv,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
NetDDEdsdm,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
AppMgmt,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;OICI;CCLCSWRPLO;;;BU)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
MSDTC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;RP;;;WD)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
LicenseService,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
SMTPSVC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
TrkSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;RPWPDTRC;;;SY)"  
Fax,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
wuauserv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
BITS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;DCRPWPDTRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
cisvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSFTPSVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
IISADMIN,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SharedAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
mnmsrvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
NetDDE,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)"  
SysmonLog,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RSVP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
RasAuto,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RasMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
NtmsSvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RemoteAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SCardSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)"  
SCardDrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMPTRAP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TapiSrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWRPWPDTLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCLCSWRPWPDTLOCRRC;;;BU)"  
TlntSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UPS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TermService,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UtilMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSIServer,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
W3SVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Microsoft\OS/2 Subsystem for NT",0,"D:PAR(A;CI;KA;;;BA)  
(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\EventLog",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)  
(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ProductOptions",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ContentIndex",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Computername",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\Software\Microsoft\Windows NT\CurrentVersion",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)  
(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
;--------------------------------------------------------------------------------  
;ファイルおよびフォルダへのアクセス許可  
;--------------------------------------------------------------------------------  
[File Security]  
"%SystemDrive%\config.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\autoexec.bat",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\boot.ini",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson\drwtsn32.log",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
;--------------------------------------------------------------------------------  
;グループの既定のメンバを編集する。  
;--------------------------------------------------------------------------------  
[Group Membership]  
;--------------------------------------------------------------------------------  
;Guests グループからアカウントを削除する。これらの設定はセキュリティ ポリシー  
;インターフェイスに表示されません。  
;--------------------------------------------------------------------------------  
%SceInfGuests%__Members =  
[Strings]  
SceInfAdministrator = Administrator  
SceInfAdmins = Administrators  
SceInfAcountOp = Account Operators  
SceInfAuthUsers = Authenticated Users  
SceInfBackupOp = Backup Operators  
SceInfDomainAdmins = Domain Admins  
SceInfDomainGuests = Domain Guests  
SceInfDomainUsers = Domain Users  
SceInfEveryone = Everyone  
SceInfGuests = Guests  
SceInfGuest = Guest  
SceInfPowerUsers = Power Users  
SceInfPrintOp = Print Operators  
SceInfReplicator = Replicator  
SceInfServerOp = Server Operators  
SceInfUsers = Users  
[Profile Description]  
Description=Evaluated Configuration minimum required security policy settings for Windows 2000 Servers.  
</td>  
</tr>  
</table>   
<p> </p>  
  
[](#mainsection)[ページのトップへ](#mainsection)  
  
### G-2. ベースライン Windows 2000 Professional セキュリティのテンプレート
<p></p>
<table style="border:1px; solid black;">  
<tr>  
<td>  
; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:    CC_Baseline_W2K_Professional.inf  
; テンプレート バージョン:   1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - パスワード ポリシー  
;--------------------------------------------------------------------------------  
MinimumPasswordLength = 8  
RequireLogonToChangePassword = 0  
ClearTextPassword = 0  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - ロックアウト ポリシー  
;--------------------------------------------------------------------------------  
LockoutBadCount = 5  
ResetLockoutCount = 30  
LockoutDuration = -1  
;注意 : アカウントをロックアウトしないとき、下記の構成は行いません。  
;ResetLockoutCount = 30  
;LockoutDuration = -1  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - Kerberos ポリシー  
;--------------------------------------------------------------------------------  
[Kerberos Policy]  
TicketValidateClient = 1  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - 監査ポリシー  
;--------------------------------------------------------------------------------  
;注意 : ベースライン ポリシーには監査ポリシーの設定は指定されていません。  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-544,*S-1-5-11,*S-1-5-32-551,*S-1-5-32-547,*S-1-5-32-545  
SeInteractiveLogonRight = *S-1-5-32-544,*S-1-5-32-551,*S-1-5-32-547,*S-1-5-32-545  
SeShutdownPrivilege = *S-1-5-32-547,*S-1-5-32-551,*S-1-5-11,*S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\CachedLogonsCount=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateFloppies=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateCDRoms=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SecurityLevel=4,0  
;--------------------------------------------------------------------------------  
;ここでは、ユーザーは Windows 2000 Professional コンピュータにログオン  
;してからでないとシャットダウンを行えないように、レジストリ値が設定  
;されています。サーバーではこれが既定です。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\ShutdownWithoutLogon=4,0  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DisableCAD=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Control\Session Manager\ProtectionMode=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\Memory Management\ClearPageFileAtShutdown=4,1  
MACHINE\System\CurrentControlSet\Control\Print\Providers\LanMan Print Services\Servers\AddPrinterDrivers=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\RestrictAnonymous=4,1  
;=========================================================================  
;評価された構成に必須のセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は Common Criteria (共通基準) に基づく評価された構成に必須です。  
;これらの設定はセキュリティ ポリシーのインターフェイスには表示されません。  
 =========================================================================  
;--------------------------------------------------------------------------------  
;DirectDraw を無効にする。ここでは、アプリケーションからグラフィックス  
;ハードウェアに直接アクセスされることを防止するために、DirectDraw を  
;無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\GraphicsDrivers\DCI\Timeout=4,0  
;--------------------------------------------------------------------------------  
;不要なサービスを無効にする。これらのサービスはサービス インターフェイスに  
;表示されません。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\audstub\Start=4,4  
MACHINE\System\CurrentControlSet\Services\mnmdd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisTapi\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisWan\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NDProxy\Start=4,4  
MACHINE\System\CurrentControlSet\Services\ParVdm\Start=4,4  
MACHINE\System\CurrentControlSet\Services\PptpMiniport\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Ptilink\Start=4,4  
MACHINE\System\CurrentControlSet\Services\RasAcd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Rasl2tp\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Raspti\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Wanarp\Start=4,4  
;--------------------------------------------------------------------------------  
;OS/2 および POSIX サブシステムを削除する。ここでは、OS/2 および POSIX の  
;既定値を削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\SubSystems\Optional=7,""  
;--------------------------------------------------------------------------------  
;カーネル オブジェクト属性を保護する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\EnhancedSecurityLevel=4,1  
;--------------------------------------------------------------------------------  
;ヌル セッション アクセスを制限する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\RestrictNullSessAccess=4,1  
;--------------------------------------------------------------------------------  
;名前つきパイプを通じた ヌル セッション アクセスを制限する。ここでは、既定値を  
;削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionPipes=7,""  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionShares=7,""  
;--------------------------------------------------------------------------------  
;SP3 を編集する。監査ログがいっぱいのしきい値のパーセントに達したときに、  
;監査イベントを生成します。ここでは、セキュリティ イベント ログが 90  
;パーセントにまで達したときに、監査イベントを生成するように設定します。  
;この値がローカルの状況に合わない場合には、管理者はローカルの要件に基づいて、  
;このキーのパーセント値を調整することができます。  
;--------------------------------------------------------------------------------  
MACHINE\SYSTEM\CurrentControlSet\Services\Eventlog\Security\WarningLevel=4,90  
;--------------------------------------------------------------------------------  
;イベント ログ - ログの設定  
;--------------------------------------------------------------------------------  
;監査ログの保存日数  
;0 = 必要に応じてイベントを上書きする  
;1 = 保存日数に指定した日数を過ぎたら上書きする  
;2 = イベントを上書きしない (手作業でログをクリア)  
;注意 : ベースライン ポリシーにはイベント ログの設定は指定されていません。  
;--------------------------------------------------------------------------------  
;システム サービス - Common Criteria (共通基準) に基づく評価された構成に含まれていない  
;サービスを無効にします。  
;--------------------------------------------------------------------------------  
[Service General Setting]  
TrkWks,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
seclogon,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
Schedule,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
ClipSrv,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
NetDDEdsdm,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
AppMgmt,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;OICI;CCLCSWRPLO;;;BU)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
MSDTC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;RP;;;WD)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
LicenseService,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
SMTPSVC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
TrkSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;RPWPDTRC;;;SY)"  
Fax,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
wuauserv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
BITS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;DCRPWPDTRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
cisvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSFTPSVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
IISADMIN,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SharedAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
mnmsrvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
NetDDE,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)"  
SysmonLog,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RSVP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
RasAuto,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RasMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
NtmsSvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RemoteAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SCardSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)"  
SCardDrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMPTRAP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TapiSrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWRPWPDTLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;BU)"  
TlntSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UPS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TermService,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UtilMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSIServer,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
W3SVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Microsoft\OS/2 Subsystem for NT",0,"D:PAR(A;CI;KA;;;BA)  
(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\EventLog",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)  
(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ProductOptions",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ContentIndex",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Computername",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\Software\Microsoft\Windows NT\CurrentVersion",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)  
(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)  
(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
;--------------------------------------------------------------------------------  
;ファイルおよびフォルダへのアクセス許可  
;--------------------------------------------------------------------------------  
[File Security]  
"%SystemDrive%\config.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\autoexec.bat",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\boot.ini",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson\drwtsn32.log",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
;--------------------------------------------------------------------------------  
;グループの既定のメンバを編集する。  
;--------------------------------------------------------------------------------  
[Group Membership]  
;--------------------------------------------------------------------------------  
;Guests グループからアカウントを削除する。これらの設定はセキュリティ ポリシー  
;インターフェイスに表示されません。  
;--------------------------------------------------------------------------------  
%SceInfGuests%__Members =  
[Strings]  
SceInfAdministrator = Administrator  
SceInfAdmins = Administrators  
SceInfAcountOp = Account Operators  
SceInfAuthUsers = Authenticated Users  
SceInfBackupOp = Backup Operators  
SceInfDomainAdmins = Domain Admins  
SceInfDomainGuests = Domain Guests  
SceInfDomainUsers = Domain Users  
SceInfEveryone = Everyone  
SceInfGuests = Guests  
SceInfGuest = Guest  
SceInfPowerUsers = Power Users  
SceInfPrintOp = Print Operators  
SceInfReplicator = Replicator  
SceInfServerOp = Server Operators  
SceInfUsers = Users  
[Profile Description]  
Description=Evaluated Configuration minimum required security policy settings for   
Windows 2000 Professional computers.  
</td>  
</tr>  
</table>   
<p> </p>
[](#mainsection)[ページのトップへ](#mainsection)  
  
### G-3. ベースライン Windows 2000 ドメイン セキュリティ ポリシーのテンプレート
<p> </p>
<table style="border:1px; solid black;">
<tr>
<td>  
; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:        CC_Baseline_W2K_Domain.inf  
; テンプレート バージョン:     1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[Version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - パスワード ポリシー  
;--------------------------------------------------------------------------------  
MinimumPasswordLength = 8  
RequireLogonToChangePassword = 0  
ClearTextPassword = 0  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - ロックアウト ポリシー  
;--------------------------------------------------------------------------------  
LockoutBadCount = 5  
ResetLockoutCount = 30  
LockoutDuration = -1  
;注意 : アカウントをロックアウトしないとき、下記の構成は行いません。  
;ResetLockoutCount = 30  
;LockoutDuration = -1  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - Kerberos ポリシー  
;--------------------------------------------------------------------------------  
[Kerberos Policy]  
MaxClockSkew = 5  
TicketValidateClient = 1  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - 監査ポリシー  
;--------------------------------------------------------------------------------  
;注意 : ベースライン ポリシーには監査ポリシーの設定は指定されていません。  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
;注意 : このポリシーでは、ある特権に関する管理者の既定の権利をドメイン全体に  
;わたって強制的に適用して、それが変更されることのないようにしています。  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-544,*S-1-5-11,*S-1-5-32-551,*S-1-5-32-547,*S-1-5-32-545  
SeInteractiveLogonRight = *S-1-5-32-544,*S-1-5-32-551,*S-1-5-32-547,*S-1-5-32-545  
SeShutdownPrivilege = *S-1-5-32-547,*S-1-5-32-551,*S-1-5-11,*S-1-5-32-544  
SeIncreaseQuotaPrivilege = *S-1-5-32-544  
SeIncreaseBasePriorityPrivilege = *S-1-5-32-544  
SeLoadDriverPrivilege = *S-1-5-32-544  
SeSecurityPrivilege = *S-1-5-32-544  
SeSystemEnvironmentPrivilege = *S-1-5-32-544  
SeSystemProfilePrivilege = *S-1-5-32-544  
SeTakeOwnershipPrivilege = *S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\CachedLogonsCount=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateFloppies=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateCDRoms=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SecurityLevel=4,0  
;--------------------------------------------------------------------------------  
;ここでは、ユーザーは Windows 2000 Professional コンピュータにログオン  
;してからでないとをシャットダウンを行えないように、レジストリ値が設定  
;されています。サーバーではこれが既定です。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\ShutdownWithoutLogon=4,0  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DisableCAD=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Control\Session Manager\ProtectionMode=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\Memory Management\ClearPageFileAtShutdown=4,1  
MACHINE\System\CurrentControlSet\Control\Print\Providers\LanMan Print Services\Servers\AddPrinterDrivers=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\RestrictAnonymous=4,1  
;=========================================================================  
;評価された構成に必須のセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は Common Criteria (共通基準) に基づく評価された構成に必須です。  
;これらの設定はセキュリティ ポリシーのインターフェイスには表示されません。  
 =========================================================================  
;--------------------------------------------------------------------------------  
;DirectDraw を無効にする。ここでは、アプリケーションからグラフィックス  
;ハードウェアに直接アクセスされることを防止するために、DirectDraw を  
;無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\GraphicsDrivers\DCI\Timeout=4,0  
;--------------------------------------------------------------------------------  
;不要なサービスを無効にする。これらのサービスはサービス インターフェイスに  
;表示されません。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\audstub\Start=4,4  
MACHINE\System\CurrentControlSet\Services\mnmdd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisTapi\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisWan\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NDProxy\Start=4,4  
MACHINE\System\CurrentControlSet\Services\ParVdm\Start=4,4  
MACHINE\System\CurrentControlSet\Services\PptpMiniport\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Ptilink\Start=4,4  
MACHINE\System\CurrentControlSet\Services\RasAcd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Rasl2tp\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Raspti\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Wanarp\Start=4,4  
;--------------------------------------------------------------------------------  
;OS/2 および POSIX サブシステムを削除する。ここでは、OS/2 および POSIX の  
;既定値を削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\SubSystems\Optional=7,""  
;--------------------------------------------------------------------------------  
;カーネル オブジェクト属性を保護する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\EnhancedSecurityLevel=4,1  
;--------------------------------------------------------------------------------  
;ヌル セッション アクセスを制限する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\RestrictNullSessAccess=4,1  
;--------------------------------------------------------------------------------  
;名前つきパイプを通じた ヌル セッション アクセスを制限する。ここでは、既定値を  
;削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionPipes=7,""  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionShares=7,""  
;--------------------------------------------------------------------------------  
;SP3 を編集する。監査ログがいっぱいのしきい値のパーセントに達したときに、  
;監査イベントを生成します。ここでは、セキュリティ イベント ログが 90  
;パーセントにまで達したときに、監査イベントを生成するように設定します。  
;この値がローカルの状況に合わない場合には、管理者はローカルの要件に基づいて、  
;このキーのパーセント値を調整することができます。  
;--------------------------------------------------------------------------------  
MACHINE\SYSTEM\CurrentControlSet\Services\Eventlog\Security\WarningLevel=4,90  
;--------------------------------------------------------------------------------  
;イベント ログ - ログの設定  
;--------------------------------------------------------------------------------  
;監査ログの保存日数  
;0 = 必要に応じてイベントを上書きする  
;1 = 保存日数に指定した日数を過ぎたら上書きする  
;2 = イベントを上書きしない (手作業でログをクリア)  
;注意 : ベースライン ポリシーにはイベント ログの設定は指定されていません。  
;--------------------------------------------------------------------------------  
;システム サービス - Common Criteria (共通基準) に基づく評価された構成に含まれていない  
;サービスを無効にします。  
;--------------------------------------------------------------------------------  
[Service General Setting]  
TrkWks,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
seclogon,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
Schedule,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
ClipSrv,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
NetDDEdsdm,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
AppMgmt,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;OICI;CCLCSWRPLO;;;BU)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
MSDTC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;RP;;;WD)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
LicenseService,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
SMTPSVC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
TrkSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;RPWPDTRC;;;SY)"  
Fax,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
wuauserv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
BITS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;DCRPWPDTRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
cisvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSFTPSVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
IISADMIN,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SharedAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
mnmsrvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
NetDDE,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)"  
SysmonLog,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RSVP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
RasAuto,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RasMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
NtmsSvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RemoteAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SCardSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)"  
SCardDrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMPTRAP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TapiSrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWRPWPDTLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCLCSWRPWPDTLOCRRC;;;BU)"  
TlntSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UPS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TermService,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UtilMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSIServer,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
W3SVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Microsoft\OS/2 Subsystem for NT",0,"D:PAR(A;CI;KA;;;BA)  
(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\EventLog",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)  
(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ProductOptions",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ContentIndex",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Computername",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\Software\Microsoft\Windows NT\CurrentVersion",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
;--------------------------------------------------------------------------------  
;ファイルおよびフォルダへのアクセス許可  
;--------------------------------------------------------------------------------  
[File Security]  
"%SystemDrive%\config.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\autoexec.bat",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\boot.ini",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson\drwtsn32.log",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
;--------------------------------------------------------------------------------  
;グループの既定のメンバを編集する。  
;--------------------------------------------------------------------------------  
[Group Membership]  
;--------------------------------------------------------------------------------  
;Guests グループからアカウントを削除する。これらの設定はドメイン セキュリティ  
;ポリシー MMC 内の制限されたグループ ポリシーに表示されます。  
;--------------------------------------------------------------------------------  
%SceInfGuests%__Members =  
[Strings]  
SceInfAdministrator = Administrator  
SceInfAdmins = Administrators  
SceInfAcountOp = Account Operators  
SceInfAuthUsers = Authenticated Users  
SceInfBackupOp = Backup Operators  
SceInfDomainAdmins = Domain Admins  
SceInfDomainGuests = Domain Guests  
SceInfDomainUsers = Domain Users  
SceInfEveryone = Everyone  
SceInfGuests = Guests  
SceInfGuest = Guest  
SceInfPowerUsers = Power Users  
SceInfPrintOp = Print Operators  
SceInfReplicator = Replicator  
SceInfServerOp = Server Operators  
SceInfUsers = Users  
[Profile Description]  
Description=Evaluated Configuration minimum required security policy settings for Windows 2000 Domains.  
</td>  
</tr>  
</table>   
<p> </p>  
[](#mainsection)[ページのトップへ](#mainsection)  
  
### G-4. ベースライン Windows 2000 ドメイン コントローラ セキュリティ ポリシーのテンプレート
<p> </p>
<table style="border:1px; solid black;">
<tr>  
<td>  
; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:        CC_Baseline_W2K_DC.inf  
; テンプレート バージョン:     1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
RequireLogonToChangePassword = 0  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-544,*S-1-5-11  
SeInteractiveLogonRight = *S-1-5-32-548,*S-1-5-32-544,*S-1-5-32-551,*S-1-5-32-550,*S-1-5-32-549  
SeMachineAccountPrivilege =  
SeBackupPrivilege = *S-1-5-32-549,*S-1-5-32-551,*S-1-5-32-544  
SeChangeNotifyPrivilege = *S-1-1-0,*S-1-5-11,*S-1-5-32-544  
SeSystemtimePrivilege = *S-1-5-32-549,*S-1-5-32-544  
SeCreatePagefilePrivilege = *S-1-5-32-544  
SeDebugPrivilege = *S-1-5-32-544  
SeEnableDelegationPrivilege = *S-1-5-32-544  
SeRemoteShutdownPrivilege = *S-1-5-32-549,*S-1-5-32-544  
SeIncreaseQuotaPrivilege = *S-1-5-32-544  
SeIncreaseBasePriorityPrivilege = *S-1-5-32-544  
SeLoadDriverPrivilege = *S-1-5-32-544  
SeBatchLogonRight =  
SeSecurityPrivilege = *S-1-5-32-544  
SeSystemEnvironmentPrivilege = *S-1-5-32-544  
SeProfileSingleProcessPrivilege = *S-1-5-32-544  
SeSystemProfilePrivilege = *S-1-5-32-544  
SeUndockPrivilege = *S-1-5-32-544  
SeCreateTokenPrivilege =  
SeCreatePermanentPrivilege =  
SeDenyNetworkLogonRight =  
SeDenyBatchLogonRight =  
SeDenyServiceLogonRight =  
SeDenyInteractiveLogonRight =  
SeAuditPrivilege =  
SeTcbPrivilege =  
SeLockMemoryPrivilege =  
SeServiceLogonRight =  
SeAssignPrimaryTokenPrivilege =  
SeRestorePrivilege = *S-1-5-32-549,*S-1-5-32-551,*S-1-5-32-544  
SeShutdownPrivilege = *S-1-5-32-549,*S-1-5-32-550,*S-1-5-32-551,*S-1-5-32-544,*S-1-5-32-548  
SeSyncAgentPrivilege =  
SeTakeOwnershipPrivilege = *S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\System\CurrentControlSet\Control\Lsa\SubmitControl=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,1  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可。評価された構成に基づくドメイン  
;セキュリティ ポリシーによって挿入された、ドメイン コントローラからの  
;パワー ユーザーの参照をなくします。  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)  
(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)  
(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
[Profile Description]  
Description=Evaluated Configuration required security policy (delta) settings for   
Windows 2000 Domain Controllers.  
</td>  
</tr>  
</table>   
<p> </p>  
  
[](#mainsection)[ページのトップへ](#mainsection)  
  
### G-5. 高セキュリティ Windows 2000 Server セキュリティのテンプレート  
  
<table style="border:1px; solid black;">  
<tr>  
<td>  
; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:    CC_HiSec_W2K_Server.inf  
; テンプレート バージョン:   1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - パスワード ポリシー  
;--------------------------------------------------------------------------------  
MinimumPasswordAge = 2  
MaximumPasswordAge = 42  
MinimumPasswordLength = 8  
PasswordComplexity = 1  
PasswordHistorySize = 24  
RequireLogonToChangePassword = 0  
ClearTextPassword = 0  
;--------------------------------------------------------------------------------  
;評価された構成において推奨するセキュリティの設定。Administrator アカウント  
;および Guest アカウントの名前を変更します。このポリシーの設定は実際には  
;ポリシー インターフェイスのセキュリティ オプション カテゴリに表示されます。  
;このテンプレートを通じてこのポリシーを設定するには、下の該当の行のコメント  
;記号を外し、サンプルとして示されている名前の代りに適切な名前を設定します。  
;または、適切なセキュリティ ポリシー インターフェイスを使用して、このポリシーを  
;編集します。下に示した名前をそのまま使用しないでください。これらは置き換える  
;対象を示したものです。  
;--------------------------------------------------------------------------------  
;NewAdministratorName = "NewAdminName"  
;NewGuestName = "NewGuestName"  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - ロックアウト ポリシー  
;--------------------------------------------------------------------------------  
LockoutBadCount = 5  
ResetLockoutCount = 30  
LockoutDuration = -1  
;注意 : アカウントをロックアウトしないとき、下記の構成は行いません。  
;ResetLockoutCount = 30  
;LockoutDuration = -1  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - Kerberos ポリシー  
;--------------------------------------------------------------------------------  
[Kerberos Policy]  
TicketValidateClient = 1  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - 監査ポリシー  
;--------------------------------------------------------------------------------  
[Event Audit]  
AuditSystemEvents = 1  
AuditLogonEvents = 3  
AuditObjectAccess = 3  
AuditPrivilegeUse = 3  
AuditPolicyChange = 1  
AuditAccountManage = 3  
AuditProcessTracking = 3  
AuditDSAccess = 3  
AuditAccountLogon = 3  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-545,*S-1-5-32-547,*S-1-5-32-551,*S-1-5-11,*S-1-5-32-544  
SeInteractiveLogonRight = *S-1-5-32-545,*S-1-5-32-547,*S-1-5-32-551,*S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\ScRemoveOption=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\PasswordExpiryWarning=4,14  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\CachedLogonsCount=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateFloppies=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateDASD=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateCDRoms=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SetCommand=4,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SecurityLevel=4,0  
;--------------------------------------------------------------------------------  
;注意 :  下に示した警告バナーのタイトルとメッセージは、位置を示している  
;だけです。ローカルの組織ポリシーおよび法的要件に適合するように、それらを  
;編集してください。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\LegalNoticeText=1,This message is   
a placeholder!  The local system administrator and security manager must define the appropriate   
login warning message, in accordance with local organizational policies, that will appear here when   
a user attempts to log in.  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\LegalNoticeCaption=1,  
Placeholder for warning banner title.  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DontDisplayLastUserName=4,1  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DisableCAD=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\RequireStrongKey=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\RequireSignOrSeal=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\SealSecureChannel=4,1  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\SignSecureChannel=4,1  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\DisablePasswordChange=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnablePlainTextPassword=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableForcedLogOff=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\ProtectionMode=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\Memory Management\ClearPageFileAtShutdown=4,1  
MACHINE\System\CurrentControlSet\Control\Print\Providers\LanMan Print Services\Servers\AddPrinterDrivers=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\RestrictAnonymous=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\LmCompatibilityLevel=4,5  
MACHINE\Software\Microsoft\Non-Driver Signing\Policy=3,1  
MACHINE\Software\Microsoft\Driver Signing\Policy=3,1  
;--------------------------------------------------------------------------------  
;下のレジストリ値の設定により、セキュリティ監査のログを記録できないときは、  
;システムが直ちにシャットダウンされます。これは推奨する設定ですが、  
;監査ログを定期的にレビュー、アーカイブ、およびクリアする厳格な監査管理  
;プロセスが用意されている場合にのみ、このオプションを有効にすべきです。  
;--------------------------------------------------------------------------------  
;MACHINE\System\CurrentControlSet\Control\Lsa\CrashOnAuditFail=4,1  
;--------------------------------------------------------------------------------  
;グローバル システム オブジェクトおよびバックアップと復元の特権に関する  
;下のレジストリ値の設定により、大量の監査イベントが生成さます。これは  
;推奨する設定ですが、監査ログを定期的にレビュー、アーカイブ、およびクリア  
;する厳格な監査管理プロセスが用意されている場合にのみ、このオプションを  
;有効にすべきです。また、ログを取る対象のイベントの増大に対応するために、  
;ログの最大サイズも大きく変更すべきです。  
;--------------------------------------------------------------------------------  
;MACHINE\System\CurrentControlSet\Control\Lsa\AuditBaseObjects=4,1  
;MACHINE\System\CurrentControlSet\Control\Lsa\FullPrivilegeAuditing=3,1  
;=========================================================================  
;評価された構成に必須のセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は Common Criteria (共通基準) に基づく評価された構成に必須です。  
;これらの設定はセキュリティ ポリシーのインターフェイスには表示されません。  
 =========================================================================  
;--------------------------------------------------------------------------------  
;DirectDraw を無効にする。ここでは、アプリケーションからグラフィックス  
;ハードウェアに直接アクセスされることを防止するために、DirectDraw を  
;無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\GraphicsDrivers\DCI\Timeout=4,0  
;--------------------------------------------------------------------------------  
;不要なサービスを無効にする。これらのサービスはサービス インターフェイスに  
;表示されません。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\audstub\Start=4,4  
MACHINE\System\CurrentControlSet\Services\mnmdd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisTapi\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisWan\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NDProxy\Start=4,4  
MACHINE\System\CurrentControlSet\Services\ParVdm\Start=4,4  
MACHINE\System\CurrentControlSet\Services\PptpMiniport\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Ptilink\Start=4,4  
MACHINE\System\CurrentControlSet\Services\RasAcd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Rasl2tp\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Raspti\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Wanarp\Start=4,4  
;--------------------------------------------------------------------------------  
;OS/2 および POSIX サブシステムを削除する。ここでは、OS/2 および POSIX の  
;既定値を削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\SubSystems\Optional=7,""  
;--------------------------------------------------------------------------------  
;カーネル オブジェクト属性を保護する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\EnhancedSecurityLevel=4,1  
;--------------------------------------------------------------------------------  
;ヌル セッション アクセスを制限する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\RestrictNullSessAccess=4,1  
;--------------------------------------------------------------------------------  
;名前つきパイプを通じた ヌル セッション アクセスを制限する。ここでは、既定値を  
;削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionPipes=7,""  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionShares=7,""  
;--------------------------------------------------------------------------------  
;SP3 を編集する。監査ログがいっぱいのしきい値のパーセントに達したときに、  
;監査イベントを生成します。ここでは、セキュリティ イベント ログが 90  
;パーセントにまで達したときに、監査イベントを生成するように設定します。  
;この値がローカルの状況に合わない場合には、管理者はローカルの要件に基づいて、  
;このキーのパーセント値を調整することができます。  
;--------------------------------------------------------------------------------  
MACHINE\SYSTEM\CurrentControlSet\Services\Eventlog\Security\WarningLevel=4,90  
;=========================================================================  
;評価された構成において推奨するセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は、Common Criteria (共通基準) に基づく評価された構成のセキュリティを  
;高めるために推奨するものですこれらの設定はセキュリティ ポリシーの  
;インターフェイスには表示されません。  
;=========================================================================  
;--------------------------------------------------------------------------------  
;サービス拒否攻撃に対する TCP/IP スタックを強化する。TCP/IP 関連の以下の  
;レジストリ値は、サービス拒否ネットワーク攻撃に対する Windows 2000 における  
;TCP/IP スタックの抵抗力を高める役に立ちます。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\DisableIPSourceRouting=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableDeadGWDetect=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableICMPRedirect=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnablePMTUDiscovery=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableSecurityFilters=4,1  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\KeepAliveTime=4,300000  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\NoNameReleaseOnDemand=4,1  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\PerformRouterDiscovery=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\SynAttackProtect=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TcpMaxConnectResponseRetransmissions=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TcpMaxConnectRetransmissions=4,3  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TCPMaxPortsExhausted=4,5  
;--------------------------------------------------------------------------------  
;パスワードによるスクリーンセーバーの保護を直ちに発効させる。パスワードによる  
;保護を直ちに発効させるために、このキー エントリの値を 0 に設定します。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\ScreenSaverGracePeriod=1,0  
;--------------------------------------------------------------------------------  
;LMHash の作成を無効にする。LM ハッシュは NTLM ハッシュと比べて弱いので、  
;強引な攻撃に早く屈しやすいです。評価された構成には LM の認証は必要あり  
;ません。したがって、それを無効にして、セキュリティを高めることができます。  
;文字列 "bar" はキー "NoLMHash" を自動的に生成するための、ダミーの値名です。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Lsa\NoLMHash\bar=4,0  
;--------------------------------------------------------------------------------  
;自動実行を無効にする。すべてのドライブ上で、自動実行を無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer\NoDriveTypeAutoRun=4,255  
;--------------------------------------------------------------------------------  
;監査ログがいっぱいになったときに、管理上の警告を発する。このキーを必要に  
;応じて編集して、権限のある適切な管理的アカウントに管理上の警告が送られる  
;ようにします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\Alerter\Parameters\AlertNames=7,Administrators  
;--------------------------------------------------------------------------------  
;イベント ログ - ログの設定  
;--------------------------------------------------------------------------------  
;監査ログの保存日数  
;0 = 必要に応じてイベントを上書きする  
;1 = 保存日数に指定した日数を過ぎたらイベントを上書きする  
;2 = イベントを上書きしない (手作業でログをクリアする)  
[System Log]  
RestrictGuestAccess = 1  
[Security Log]  
MaximumLogSize = 10240  
AuditLogRetentionPeriod = 2  
RestrictGuestAccess = 1  
[Application Log]  
RestrictGuestAccess = 1  
;--------------------------------------------------------------------------------  
;システム サービス - Common Criteria (共通基準) に基づく評価された構成に含まれていない  
;サービスを無効にします。  
;--------------------------------------------------------------------------------  
[Service General Setting]  
TrkWks,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
seclogon,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
Schedule,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
ClipSrv,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
NetDDEdsdm,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
AppMgmt,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;OICI;CCLCSWRPLO;;;BU)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
MSDTC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;RP;;;WD)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
LicenseService,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
SMTPSVC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
TrkSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;RPWPDTRC;;;SY)"  
Fax,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
wuauserv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
BITS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;DCRPWPDTRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
cisvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSFTPSVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
IISADMIN,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SharedAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
mnmsrvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
NetDDE,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)"  
SysmonLog,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RSVP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
RasAuto,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RasMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
NtmsSvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RemoteAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SCardSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)"  
SCardDrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMPTRAP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TapiSrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWRPWPDTLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;BU)"  
TlntSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UPS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TermService,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UtilMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSIServer,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
W3SVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Microsoft\OS/2 Subsystem for NT",0,"D:PAR(A;CI;KA;;;BA)  
(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\EventLog",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)  
(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ProductOptions",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ContentIndex",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Computername",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\Software\Microsoft\Windows NT\CurrentVersion",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
;--------------------------------------------------------------------------------  
;ファイルおよびフォルダへのアクセス許可  
;--------------------------------------------------------------------------------  
[File Security]  
"%SystemDrive%\config.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\autoexec.bat",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\ntbootdd.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\ntldr",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\ntdetect.com",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\boot.ini",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\MSDOS.SYS",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\IO.SYS",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)  
(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\Administrator",2,"D:PAR(A;OICI;FA;;;LA)(A;OICI;FA;;;SY)"  
"%SystemDrive%\Documents and Settings",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson\drwtsn32.log",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\$NtServicePackUninstall$",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemRoot%\Debug",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%Systemdirectory%\secedit.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\rsh.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\rexec.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\regedt32.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemroot%\regedit.exe",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%Systemdirectory%\rcp.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\ntbackup.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\ias",2,"D:P(A;OICI;GA;;;BA)(A;OICI;GA;;;SY)(A;OICI;GA;;;CO)"  
"%SystemDirectory%\dllcache",2,"D:P(A;OICI;GA;;;BA)(A;OICI;GA;;;SY)(A;OICI;GA;;;CO)"  
"%SystemDirectory%\config",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\spool\printers",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)  
(A;CI;0x1000ae;;;BU)"  
"%SystemDirectory%\repl\export",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICIIO;FA;;;CO)  
(A;OICI;0x1300a9;;;RE)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\repl\import",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;0x1301bf;;;RE)(A;OICI;FA;;;SY)  
(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\repl",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\Setup",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\NTMSData",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\GroupPolicy",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;0x1200a9;;;AU)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\DTCLog",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICIIO;FA;;;CO)  
(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\appmgmt",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1201a9;;;BU)"  
"%SystemDirectory%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\Debug\UserMode",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OIIO;0x100006;;;BU)(A;;0x100023;;;BU)"  
"%SystemRoot%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemRoot%\repair",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemRoot%\Registration",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;FR;;;BU)"  
"%SystemRoot%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%ProgramFiles%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
;--------------------------------------------------------------------------------  
;グループの既定のメンバを編集する。  
;--------------------------------------------------------------------------------  
[Group Membership]  
;--------------------------------------------------------------------------------  
;Guests グループからアカウントを削除する。これらの設定はセキュリティ  
;ポリシー インターフェイスに表示されません。  
;--------------------------------------------------------------------------------  
%SceInfGuests%__Members =  
[Strings]  
SceInfAdministrator = Administrator  
SceInfAdmins = Administrators  
SceInfAcountOp = Account Operators  
SceInfAuthUsers = Authenticated Users  
SceInfBackupOp = Backup Operators  
SceInfDomainAdmins = Domain Admins  
SceInfDomainGuests = Domain Guests  
SceInfDomainUsers = Domain Users  
SceInfEveryone = Everyone  
SceInfGuests = Guests  
SceInfGuest = Guest  
SceInfPowerUsers = Power Users  
SceInfPrintOp = Print Operators  
SceInfReplicator = Replicator  
SceInfServerOp = Server Operators  
SceInfUsers = Users  
[Profile Description]  
Description=Evaluated Configuration high security policy settings for Windows 2000 Servers.  
</td>  
</tr>  
</table>
<p> </p>  
[](#mainsection)[ページのトップへ](#mainsection)
  
### G-6. 高セキュリティ Windows 2000 Professional セキュリティのテンプレート
<p> </p>
<table style="border:1px; solid black;">
<tr>  
<td>  
; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:    CC_HiSec_W2K_Professional.inf  
; テンプレート バージョン:   1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - パスワード ポリシー  
;--------------------------------------------------------------------------------  
MinimumPasswordAge = 2  
MaximumPasswordAge = 42  
MinimumPasswordLength = 8  
PasswordComplexity = 1  
PasswordHistorySize = 24  
RequireLogonToChangePassword = 0  
ClearTextPassword = 0  
;--------------------------------------------------------------------------------  
;評価された構成において推奨するセキュリティの設定。Administrator アカウント  
;および Guest アカウントの名前を変更します。このポリシーの設定は実際には  
;ポリシー インターフェイスのセキュリティ オプション カテゴリに表示されます。  
;このテンプレートを通じてこのポリシーを設定するには、下の該当の行のコメント  
;記号を外し、サンプルとして示されている名前の代りに適切な名前を設定します。  
;または、適切なセキュリティ ポリシー インターフェイスを使用して、このポリシーを  
;編集します。下に示した名前をそのまま使用しないでください。これらは置き換える  
;対象を示したものです。  
;--------------------------------------------------------------------------------  
;NewAdministratorName = "NewAdminName"  
;NewGuestName = "NewGuestName"  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - ロックアウト ポリシー  
;--------------------------------------------------------------------------------  
LockoutBadCount = 5  
ResetLockoutCount = 30  
LockoutDuration = -1  
;注意 : アカウントをロックアウトしないとき、下記の構成は行いません。  
;ResetLockoutCount = 30  
;LockoutDuration = -1  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - Kerberos ポリシー  
;--------------------------------------------------------------------------------  
[Kerberos Policy]  
TicketValidateClient = 1  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - 監査ポリシー  
;--------------------------------------------------------------------------------  
[Event Audit]  
AuditSystemEvents = 1  
AuditLogonEvents = 3  
AuditObjectAccess = 3  
AuditPrivilegeUse = 3  
AuditPolicyChange = 1  
AuditAccountManage = 3  
AuditProcessTracking = 3  
AuditDSAccess = 3  
AuditAccountLogon = 3  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-545,*S-1-5-32-547,*S-1-5-32-551,*S-1-5-11,*S-1-5-32-544  
SeInteractiveLogonRight = *S-1-5-32-545,*S-1-5-32-547,*S-1-5-32-551,*S-1-5-32-544  
SeShutdownPrivilege = *S-1-5-32-547,*S-1-5-32-551,*S-1-5-11,*S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\ScRemoveOption=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\PasswordExpiryWarning=4,14  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\CachedLogonsCount=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateFloppies=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateDASD=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateCDRoms=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SetCommand=4,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SecurityLevel=4,0  
;--------------------------------------------------------------------------------  
;ここでは、ユーザーは Windows 2000 Professional コンピュータにログオン  
;してからでないとシャットダウンを行えないように、レジストリ値が設定  
;されています。サーバーではこれが既定です。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\ShutdownWithoutLogon=4,0  
;--------------------------------------------------------------------------------  
;注意 :  下に示した警告バナーのタイトルとメッセージは、位置を示している  
;だけです。ローカルの組織ポリシーおよび法的要件に適合するように、それらを  
;編集してください。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\LegalNoticeText=1,This message is   
a placeholder!  The local system administrator and security manager must define the appropriate   
login warning message, in accordance with local organizational policies, that will appear here when   
a user attempts to log in.  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\LegalNoticeCaption=1,  
Placeholder for warning banner title.  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DontDisplayLastUserName=4,1  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DisableCAD=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\RequireStrongKey=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\RequireSignOrSeal=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\SealSecureChannel=4,1  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\SignSecureChannel=4,1  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\DisablePasswordChange=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnablePlainTextPassword=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableForcedLogOff=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\ProtectionMode=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\Memory Management\ClearPageFileAtShutdown=4,1  
MACHINE\System\CurrentControlSet\Control\Print\Providers\LanMan Print Services\Servers\AddPrinterDrivers=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\RestrictAnonymous=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\LmCompatibilityLevel=4,5  
MACHINE\Software\Microsoft\Non-Driver Signing\Policy=3,1  
MACHINE\Software\Microsoft\Driver Signing\Policy=3,1  
;--------------------------------------------------------------------------------  
;下のレジストリ値の設定により、セキュリティ監査のログを記録できないときは、  
;システムが直ちにシャットダウンされます。これは推奨する設定ですが、  
;監査ログを定期的にレビュー、アーカイブ、およびクリアする厳格な監査管理  
;プロセスが用意されている場合にのみ、このオプションを有効にすべきです。  
;--------------------------------------------------------------------------------  
;MACHINE\System\CurrentControlSet\Control\Lsa\CrashOnAuditFail=4,1  
;--------------------------------------------------------------------------------  
;グローバル システム オブジェクトおよびバックアップと復元の特権に関する  
;下のレジストリ値の設定により、大量の監査イベントが生成さます。これは  
;推奨する設定ですが、監査ログを定期的にレビュー、アーカイブ、およびクリア  
;する厳格な監査管理プロセスが用意されている場合にのみ、このオプションを  
;有効にすべきです。また、ログを取る対象のイベントの増大に対応するために、  
;ログの最大サイズも大きく変更すべきです。  
;--------------------------------------------------------------------------------  
;MACHINE\System\CurrentControlSet\Control\Lsa\AuditBaseObjects=4,1  
;MACHINE\System\CurrentControlSet\Control\Lsa\FullPrivilegeAuditing=3,1  
;=========================================================================  
;評価された構成に必須のセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は Common Criteria (共通基準) に基づく評価された構成に必須です。  
;これらの設定はセキュリティ ポリシーのインターフェイスには表示されません。  
 =========================================================================  
;--------------------------------------------------------------------------------  
;DirectDraw を無効にする。ここでは、アプリケーションからグラフィックス  
;ハードウェアに直接アクセスされることを防止するために、DirectDraw を  
;無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\GraphicsDrivers\DCI\Timeout=4,0  
;--------------------------------------------------------------------------------  
;不要なサービスを無効にする。これらのサービスはサービス インターフェイスに  
;表示されません。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\audstub\Start=4,4  
MACHINE\System\CurrentControlSet\Services\mnmdd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisTapi\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisWan\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NDProxy\Start=4,4  
MACHINE\System\CurrentControlSet\Services\ParVdm\Start=4,4  
MACHINE\System\CurrentControlSet\Services\PptpMiniport\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Ptilink\Start=4,4  
MACHINE\System\CurrentControlSet\Services\RasAcd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Rasl2tp\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Raspti\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Wanarp\Start=4,4  
;--------------------------------------------------------------------------------  
;OS/2 および POSIX サブシステムを削除する。ここでは、OS/2 および POSIX の  
;既定値を削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\SubSystems\Optional=7,""  
;--------------------------------------------------------------------------------  
;カーネル オブジェクト属性を保護する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\EnhancedSecurityLevel=4,1  
;--------------------------------------------------------------------------------  
;ヌル セッション アクセスを制限する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\RestrictNullSessAccess=4,1  
;--------------------------------------------------------------------------------  
;名前つきパイプを通じた ヌル セッション アクセスを制限する。ここでは、既定値を  
;削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionPipes=7,""  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionShares=7,""  
;--------------------------------------------------------------------------------  
;SP3 を編集する。監査ログがいっぱいのしきい値のパーセントに達したときに、  
;監査イベントを生成します。ここでは、セキュリティ イベント ログが 90  
;パーセントにまで達したときに、監査イベントを生成するように設定します。  
;この値がローカルの状況に合わない場合には、管理者はローカルの要件に基づいて、  
;このキーのパーセント値を調整することができます。  
;--------------------------------------------------------------------------------  
MACHINE\SYSTEM\CurrentControlSet\Services\Eventlog\Security\WarningLevel=4,90  
;=========================================================================  
;評価された構成において推奨するセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は、Common Criteria (共通基準) に基づく評価された構成のセキュリティを  
;高めるために推奨するものですこれらの設定はセキュリティ ポリシーの  
;インターフェイスには表示されません。  
;=========================================================================  
;--------------------------------------------------------------------------------  
;サービス拒否攻撃に対する TCP/IP スタックを強化する。TCP/IP 関連の以下の  
;レジストリ値は、サービス拒否ネットワーク攻撃に対する Windows 2000 における  
;TCP/IP スタックの抵抗力を高める役に立ちます。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\DisableIPSourceRouting=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableDeadGWDetect=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableICMPRedirect=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnablePMTUDiscovery=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableSecurityFilters=4,1  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\KeepAliveTime=4,300000  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\NoNameReleaseOnDemand=4,1  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\PerformRouterDiscovery=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\SynAttackProtect=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TcpMaxConnectResponseRetransmissions=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TcpMaxConnectRetransmissions=4,3  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TCPMaxPortsExhausted=4,5  
;--------------------------------------------------------------------------------  
;パスワードによるスクリーンセーバーの保護を直ちに発効させる。パスワードによる  
;保護を直ちに発効させるために、このキー エントリの値を 0 に設定します。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\ScreenSaverGracePeriod=1,0  
;--------------------------------------------------------------------------------  
;LMHash の作成を無効にする。LM ハッシュは NTLM ハッシュと比べて弱いので、  
;強引な攻撃に早く屈しやすいです。評価された構成には LM の認証は必要あり  
;ません。したがって、それを無効にして、セキュリティを高めることができます。  
;文字列 "bar" はキー "NoLMHash" を自動的に生成するための、ダミーの値名です。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Lsa\NoLMHash\bar=4,0  
;--------------------------------------------------------------------------------  
;自動実行を無効にする。すべてのドライブ上で、自動実行を無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer\NoDriveTypeAutoRun=4,255  
;--------------------------------------------------------------------------------  
;監査ログがいっぱいになったときに、管理上の警告を発する。このキーを必要に  
;応じて編集して、権限のある適切な管理的アカウントに管理上の警告が送られる  
;ようにします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\Alerter\Parameters\AlertNames=7,Administrators  
;--------------------------------------------------------------------------------  
;イベント ログ - ログの設定  
;--------------------------------------------------------------------------------  
;監査ログの保存日数  
;0 = 必要に応じてイベントを上書きする  
;1 = 保存日数に指定した日数を過ぎたらイベントを上書きする  
;2 = イベントを上書きしない (手作業でログをクリアする)  
[System Log]  
RestrictGuestAccess = 1  
[Security Log]  
MaximumLogSize = 10240  
AuditLogRetentionPeriod = 2  
RestrictGuestAccess = 1  
[Application Log]  
RestrictGuestAccess = 1  
;--------------------------------------------------------------------------------  
;システム サービス - Common Criteria (共通基準) に基づく評価された構成に含まれていない  
;サービスを無効にします。  
;--------------------------------------------------------------------------------  
[Service General Setting]  
TrkWks,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
seclogon,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
Schedule,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
ClipSrv,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
NetDDEdsdm,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
AppMgmt,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;OICI;CCLCSWRPLO;;;BU)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
MSDTC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;RP;;;WD)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
LicenseService,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
SMTPSVC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
TrkSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;RPWPDTRC;;;SY)"  
Fax,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
wuauserv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
BITS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;DCRPWPDTRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
cisvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSFTPSVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
IISADMIN,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SharedAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
mnmsrvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
NetDDE,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)"  
SysmonLog,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RSVP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
RasAuto,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RasMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
NtmsSvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RemoteAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SCardSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)"  
SCardDrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMPTRAP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TapiSrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWRPWPDTLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCLCSWRPWPDTLOCRRC;;;BU)"  
TlntSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UPS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TermService,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UtilMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSIServer,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
W3SVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Microsoft\OS/2 Subsystem for NT",0,"D:PAR(A;CI;KA;;;BA)  
(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\EventLog",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)  
(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ProductOptions",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ContentIndex",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Computername",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\Software\Microsoft\Windows NT\CurrentVersion",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
;--------------------------------------------------------------------------------  
;ファイルおよびフォルダへのアクセス許可  
;--------------------------------------------------------------------------------  
[File Security]  
"%SystemDrive%\config.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\autoexec.bat",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\ntbootdd.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\ntldr",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\ntdetect.com",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\boot.ini",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\MSDOS.SYS",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\IO.SYS",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)  
(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\Administrator",2,"D:PAR(A;OICI;FA;;;LA)(A;OICI;FA;;;SY)"  
"%SystemDrive%\Documents and Settings",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson\drwtsn32.log",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\$NtServicePackUninstall$",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemRoot%\Debug",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%Systemdirectory%\secedit.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\rsh.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\rexec.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\regedt32.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemroot%\regedit.exe",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%Systemdirectory%\rcp.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\ntbackup.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\ias",2,"D:P(A;OICI;GA;;;BA)(A;OICI;GA;;;SY)(A;OICI;GA;;;CO)"  
"%SystemDirectory%\dllcache",2,"D:P(A;OICI;GA;;;BA)(A;OICI;GA;;;SY)(A;OICI;GA;;;CO)"  
"%SystemDirectory%\config",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\spool\printers",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)  
(A;CI;0x1000ae;;;BU)"  
"%SystemDirectory%\repl\export",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICIIO;FA;;;CO)  
(A;OICI;0x1300a9;;;RE)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\repl\import",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;0x1301bf;;;RE)(A;OICI;FA;;;SY)  
(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\repl",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\Setup",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\NTMSData",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\GroupPolicy",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;0x1200a9;;;AU)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\DTCLog",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICIIO;FA;;;CO)  
(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\appmgmt",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1201a9;;;BU)"  
"%SystemDirectory%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\Debug\UserMode",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OIIO;0x100006;;;BU)  
(A;;0x100023;;;BU)"  
"%SystemRoot%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemRoot%\repair",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemRoot%\Registration",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;FR;;;BU)"  
"%SystemRoot%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%ProgramFiles%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
;--------------------------------------------------------------------------------  
;グループの既定のメンバを編集する。  
;--------------------------------------------------------------------------------  
[Group Membership]  
;--------------------------------------------------------------------------------  
;Guests グループからアカウントを削除する。これらの設定はセキュリティ  
;ポリシー インターフェイスに表示されません。  
;--------------------------------------------------------------------------------  
%SceInfGuests%__Members =  
[Strings]  
SceInfAdministrator = Administrator  
SceInfAdmins = Administrators  
SceInfAcountOp = Account Operators  
SceInfAuthUsers = Authenticated Users  
SceInfBackupOp = Backup Operators  
SceInfDomainAdmins = Domain Admins  
SceInfDomainGuests = Domain Guests  
SceInfDomainUsers = Domain Users  
SceInfEveryone = Everyone  
SceInfGuests = Guests  
SceInfGuest = Guest  
SceInfPowerUsers = Power Users  
SceInfPrintOp = Print Operators  
SceInfReplicator = Replicator  
SceInfServerOp = Server Operators  
SceInfUsers = Users  
[Profile Description]  
Description=Evaluated Configuration high security policy settings for Windows 2000 Professional computers.  
</td>  
</tr>  
</table>
<p> </p>
 
[](#mainsection)[ページのトップへ](#mainsection)  
  
### G-7. 高セキュリティ Windows 2000 ドメイン セキュリティ ポリシーのテンプレート
<p> </p>
<table style="border:1px; solid black;">
<tr>  
<td>  
; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:        CC_HiSec_W2K_Domain.inf  
; テンプレート バージョン:     1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[Version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - パスワード ポリシー  
;--------------------------------------------------------------------------------  
MinimumPasswordAge = 2  
MaximumPasswordAge = 42  
MinimumPasswordLength = 8  
PasswordComplexity = 1  
PasswordHistorySize = 24  
RequireLogonToChangePassword = 0  
ClearTextPassword = 0  
;--------------------------------------------------------------------------------  
;評価された構成において推奨するセキュリティの設定。Administrator アカウント  
;および Guest アカウントの名前を変更します。このポリシーの設定は実際には  
;ポリシー インターフェイスのセキュリティ オプション カテゴリに表示されます。  
;このテンプレートを通じてこのポリシーを設定するには、下の該当の行のコメント  
;記号を外し、サンプルとして示されている名前の代りに適切な名前を設定します。  
;または、適切なセキュリティ ポリシー インターフェイスを使用して、このポリシーを  
;編集します。下に示した名前をそのまま使用しないでください。これらは置き換える  
;対象を示したものです。  
;--------------------------------------------------------------------------------  
;NewAdministratorName = "NewAdminName"  
;NewGuestName = "NewGuestName"  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - ロックアウト ポリシー  
;--------------------------------------------------------------------------------  
LockoutBadCount = 5  
ResetLockoutCount = 30  
LockoutDuration = -1  
;注意 : アカウントをロックアウトしないとき、下記の構成は行いません。  
;ResetLockoutCount = 30  
;LockoutDuration = -1  
;--------------------------------------------------------------------------------  
;アカウント ポリシー - Kerberos ポリシー  
;--------------------------------------------------------------------------------  
[Kerberos Policy]  
MaxClockSkew = 5  
TicketValidateClient = 1  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - 監査ポリシー  
;--------------------------------------------------------------------------------  
[Event Audit]  
AuditSystemEvents = 1  
AuditLogonEvents = 3  
AuditObjectAccess = 3  
AuditPrivilegeUse = 3  
AuditPolicyChange = 1  
AuditAccountManage = 3  
AuditProcessTracking = 3  
AuditDSAccess = 3  
AuditAccountLogon = 3  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
;注意 : このポリシーでは、ある特権に関する管理者の既定の権利をドメイン全体に  
;わたって強制的に適用して、それが変更されることのないようにしています。  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-544,*S-1-5-11,*S-1-5-32-551,*S-1-5-32-547,*S-1-5-32-545  
SeInteractiveLogonRight = *S-1-5-32-544,*S-1-5-32-551,*S-1-5-32-547,*S-1-5-32-545  
SeShutdownPrivilege = *S-1-5-32-547,*S-1-5-32-551,*S-1-5-11,*S-1-5-32-544  
SeIncreaseQuotaPrivilege = *S-1-5-32-544  
SeIncreaseBasePriorityPrivilege = *S-1-5-32-544  
SeLoadDriverPrivilege = *S-1-5-32-544  
SeSecurityPrivilege = *S-1-5-32-544  
SeSystemEnvironmentPrivilege = *S-1-5-32-544  
SeSystemProfilePrivilege = *S-1-5-32-544  
SeTakeOwnershipPrivilege = *S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\Software\Microsoft\Driver Signing\Policy=3,1  
MACHINE\Software\Microsoft\Non-Driver Signing\Policy=3,1  
;--------------------------------------------------------------------------------  
;下のレジストリ値の設定により、セキュリティ監査のログを記録できないときは、  
;システムが直ちにシャットダウンされます。これは推奨する設定ですが、  
;監査ログを定期的にレビュー、アーカイブ、およびクリアする厳格な監査管理  
;プロセスが用意されている場合にのみ、このオプションを有効にすべきです。  
;--------------------------------------------------------------------------------  
;MACHINE\System\CurrentControlSet\Control\Lsa\CrashOnAuditFail=4,1  
MACHINE\System\CurrentControlSet\Control\Lsa\LmCompatibilityLevel=4,5  
MACHINE\System\CurrentControlSet\Control\Lsa\RestrictAnonymous=4,1  
MACHINE\System\CurrentControlSet\Control\Print\Providers\LanMan Print Services\Servers\AddPrinterDrivers=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\Memory Management\ClearPageFileAtShutdown=4,1  
MACHINE\System\CurrentControlSet\Control\Session Manager\ProtectionMode=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableForcedLogOff=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnablePlainTextPassword=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\DisablePasswordChange=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\SignSecureChannel=4,1  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\SealSecureChannel=4,1  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\RequireSignOrSeal=4,0  
MACHINE\System\CurrentControlSet\Services\Netlogon\Parameters\RequireStrongKey=4,0  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DisableCAD=4,0  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\DontDisplayLastUserName=4,1  
;--------------------------------------------------------------------------------  
;注意 :  下に示した警告バナーのタイトルとメッセージは、位置を示している  
;だけです。ローカルの組織ポリシーおよび法的要件に適合するように、それらを  
;編集してください。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\LegalNoticeCaption=1,  
Placeholder for warning banner title.  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\LegalNoticeText=1,This message is   
a placeholder!  The local system administrator and security manager must define the appropriate   
login warning message, in accordance with local organizational policies, that will appear here when   
a user attempts to log in.  
;--------------------------------------------------------------------------------  
;ここでは、ドメイン ユーザーはコンピュータにログオンしてからでないと  
;シャットダウンを行えないように、レジストリ値が設定されています。  
;サーバーではこれが既定です。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System\ShutdownWithoutLogon=4,0  
;--------------------------------------------------------------------------------  
;グローバル システム オブジェクトおよびバックアップと復元の特権に関する  
;下のレジストリ値の設定により、大量の監査イベントが生成さます。これは  
;推奨する設定ですが、監査ログを定期的にレビュー、アーカイブ、およびクリア  
;する厳格な監査管理プロセスが用意されている場合にのみ、このオプションを  
;有効にすべきです。また、ログを取る対象のイベントの増大に対応するために、  
;ログの最大サイズも大きく変更すべきです。  
;--------------------------------------------------------------------------------  
;MACHINE\System\CurrentControlSet\Control\Lsa\AuditBaseObjects=4,1  
;MACHINE\System\CurrentControlSet\Control\Lsa\FullPrivilegeAuditing=3,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SecurityLevel=4,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Setup\RecoveryConsole\SetCommand=4,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateCDRoms=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateDASD=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\AllocateFloppies=1,1  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\CachedLogonsCount=1,0  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\PasswordExpiryWarning=4,14  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\ScRemoveOption=1,1  
;=========================================================================  
;評価された構成に必須のセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は Common Criteria (共通基準) に基づく評価された構成に必須です。  
;これらの設定はセキュリティ ポリシーのインターフェイスには表示されません。  
 =========================================================================  
;--------------------------------------------------------------------------------  
;DirectDraw を無効にする。ここでは、アプリケーションからグラフィックス  
;ハードウェアに直接アクセスされることを防止するために、DirectDraw を  
;無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\GraphicsDrivers\DCI\Timeout=4,0  
;--------------------------------------------------------------------------------  
;不要なサービスを無効にする。これらのサービスはサービス インターフェイスに  
;表示されません。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\audstub\Start=4,4  
MACHINE\System\CurrentControlSet\Services\mnmdd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisTapi\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NdisWan\Start=4,4  
MACHINE\System\CurrentControlSet\Services\NDProxy\Start=4,4  
MACHINE\System\CurrentControlSet\Services\ParVdm\Start=4,4  
MACHINE\System\CurrentControlSet\Services\PptpMiniport\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Ptilink\Start=4,4  
MACHINE\System\CurrentControlSet\Services\RasAcd\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Rasl2tp\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Raspti\Start=4,4  
MACHINE\System\CurrentControlSet\Services\Wanarp\Start=4,4  
;--------------------------------------------------------------------------------  
;OS/2 および POSIX サブシステムを削除する。ここでは、OS/2 および POSIX の  
;既定値を削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\SubSystems\Optional=7,""  
;--------------------------------------------------------------------------------  
;カーネル オブジェクト属性を保護する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Session Manager\EnhancedSecurityLevel=4,1  
;--------------------------------------------------------------------------------  
;ヌル セッション アクセスを制限する。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\RestrictNullSessAccess=4,1  
;--------------------------------------------------------------------------------  
;名前つきパイプを通じた ヌル セッション アクセスを制限する。ここでは、既定値を  
;削除します。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionPipes=7,""  
MACHINE\System\CurrentControlSet\Services\lanmanserver\parameters\NullSessionShares=7,""  
;--------------------------------------------------------------------------------  
;SP3 を編集する。監査ログがいっぱいのしきい値のパーセントに達したときに、  
;監査イベントを生成します。ここでは、セキュリティ イベント ログが 90  
;パーセントにまで達したときに、監査イベントを生成するように設定します。  
;この値がローカルの状況に合わない場合には、管理者はローカルの要件に基づいて、  
;このキーのパーセント値を調整することができます。  
;--------------------------------------------------------------------------------  
MACHINE\SYSTEM\CurrentControlSet\Services\Eventlog\Security\WarningLevel=4,90  
;=========================================================================  
;評価された構成において推奨するセキュリティの設定。下に列挙するその他の  
;レジストリ値の設定は、Common Criteria (共通基準) に基づく評価された構成のセキュリティを  
;高めるために推奨するものですこれらの設定はセキュリティ ポリシーの  
;インターフェイスには表示されません。  
;=========================================================================  
;--------------------------------------------------------------------------------  
;サービス拒否攻撃に対する TCP/IP スタックを強化する。TCP/IP 関連の以下の  
;Tレジストリ値は、サービス拒否ネットワーク攻撃に対する Windows 2000 における  
;TCP/IP スタックの抵抗力を高める役に立ちます。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\DisableIPSourceRouting=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableDeadGWDetect=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableICMPRedirect=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnablePMTUDiscovery=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\EnableSecurityFilters=4,1  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\KeepAliveTime=4,300000  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\NoNameReleaseOnDemand=4,1  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\PerformRouterDiscovery=4,0  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\SynAttackProtect=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TcpMaxConnectResponseRetransmissions=4,2  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TcpMaxConnectRetransmissions=4,3  
MACHINE\System\CurrentControlSet\Services\Tcpip\parameters\TCPMaxPortsExhausted=4,5  
;--------------------------------------------------------------------------------  
;パスワードによるスクリーンセーバーの保護を直ちに発効させる。パスワードによる  
;保護を直ちに発効させるために、このキー エントリの値を 0 に設定します。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\ScreenSaverGracePeriod=1,0  
;--------------------------------------------------------------------------------  
;LMHash の作成を無効にする。LM ハッシュは NTLM ハッシュと比べて弱いので、  
;強引な攻撃に早く屈しやすいです。評価された構成には LM の認証は必要あり  
;ません。したがって、それを無効にして、セキュリティを高めることができます。  
;文字列 "bar" はキー "NoLMHash" を自動的に生成するための、ダミーの値名です。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Control\Lsa\NoLMHash\bar=4,0  
;--------------------------------------------------------------------------------  
;自動実行を無効にする。すべてのドライブ上で、自動実行を無効にします。  
;--------------------------------------------------------------------------------  
MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer\NoDriveTypeAutoRun=4,255  
;--------------------------------------------------------------------------------  
;監査ログがいっぱいになったときに、管理上の警告を発する。このキーを必要に  
;応じて編集して、権限のある適切な管理的アカウントに管理上の警告が送られる  
;ようにします。  
;--------------------------------------------------------------------------------  
MACHINE\System\CurrentControlSet\Services\Alerter\Parameters\AlertNames=7,Administrators  
;--------------------------------------------------------------------------------  
;イベント ログ - ログの設定  
;--------------------------------------------------------------------------------  
;0 = 必要に応じてイベントを上書きする  
;1 = 保存日数に指定した日数を過ぎたらイベントを上書きする  
;2 = イベントを上書きしない (手作業でログをクリアする)  
[System Log]  
RestrictGuestAccess = 1  
[Security Log]  
MaximumLogSize = 10240  
AuditLogRetentionPeriod = 2  
RestrictGuestAccess = 1  
[Application Log]  
RestrictGuestAccess = 1  
;--------------------------------------------------------------------------------  
;システム サービス - Common Criteria (共通基準) に基づく評価された構成に含まれていない  
;サービスを無効にします。  
;--------------------------------------------------------------------------------  
[Service General Setting]  
TrkWks,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
seclogon,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
Schedule,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
ClipSrv,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
NetDDEdsdm,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
AppMgmt,4,"D:(A;OICI;CCLCSWLORC;;;WD)(A;OICI;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)  
(A;OICI;CCLCSWLORC;;;PU)(A;OICI;CCLCSWRPLO;;;IU)(A;OICI;CCLCSWRPLO;;;BU)  
S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
MSDTC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;RP;;;WD)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
LicenseService,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
SMTPSVC,4,"D:(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)S:(AU;FA;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;WD)"  
TrkSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;RPWPDTRC;;;SY)"  
Fax,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
wuauserv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
BITS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;DCRPWPDTRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
cisvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSFTPSVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
IISADMIN,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SharedAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
mnmsrvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
NetDDE,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)"  
SysmonLog,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RSVP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
RasAuto,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RasMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)"  
NtmsSvc,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
RemoteAccess,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SCardSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)"  
SCardDrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
SNMPTRAP,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TapiSrv,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWRPWPDTLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;IU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;BU)"  
TlntSvr,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UPS,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
TermService,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
UtilMan,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;SO)  
(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
MSIServer,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
W3SVC,4,"D:AR(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)  
(A;;CCLCSWRPWPDTLOCRRC;;;PU)(A;;CCLCSWRPWPDTLOCRRC;;;SY)"  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Microsoft\OS/2 Subsystem for NT",0,"D:PAR(A;CI;KA;;;BA)  
(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Services\EventLog",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)  
(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ProductOptions",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\ContentIndex",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Computername",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layout",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\Software\Microsoft\Windows NT\CurrentVersion",0,"D:AR(A;CI;KR;;;AU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)  
(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;CCDCLCSWRPSDRC;;;PU)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)(A;CI;CCDCLCSWRPSDRC;;;PU)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
;--------------------------------------------------------------------------------  
;ファイルおよびフォルダへのアクセス許可  
;--------------------------------------------------------------------------------  
[File Security]  
"%SystemDrive%\config.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\autoexec.bat",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)(A;;0x1200a9;;;BU)"  
"%SystemDrive%\ntbootdd.sys",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\ntldr",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\ntdetect.com",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\boot.ini",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%SystemDrive%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\MSDOS.SYS",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\IO.SYS",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)  
(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\Administrator",2,"D:PAR(A;OICI;FA;;;LA)(A;OICI;FA;;;SY)"  
"%SystemDrive%\Documents and Settings",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\Documents and Settings\All Users\Documents\DrWatson\drwtsn32.log",2,"D:PAR(A;OICI;FA;;;BA)  
(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDrive%\",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\$NtServicePackUninstall$",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemRoot%\Debug",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%Systemdirectory%\secedit.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\rsh.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\rexec.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\regedt32.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemroot%\regedit.exe",2,"D:PAR(A;;FA;;;BA)(A;;FA;;;SY)"  
"%Systemdirectory%\rcp.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%Systemdirectory%\ntbackup.exe",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\ias",2,"D:P(A;OICI;GA;;;BA)(A;OICI;GA;;;SY)(A;OICI;GA;;;CO)"  
"%SystemDirectory%\dllcache",2,"D:P(A;OICI;GA;;;BA)(A;OICI;GA;;;SY)(A;OICI;GA;;;CO)"  
"%SystemDirectory%\config",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\spool\printers",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)  
(A;CI;0x1000ae;;;BU)"  
"%SystemDirectory%\repl\export",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICIIO;FA;;;CO)  
(A;OICI;0x1300a9;;;RE)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\repl\import",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;0x1301bf;;;RE)(A;OICI;FA;;;SY)  
(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\repl",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\Setup",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\NTMSData",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\GroupPolicy",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;0x1200a9;;;AU)(A;OICI;FA;;;SY)"  
"%SystemDirectory%\DTCLog",0,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICIIO;FA;;;CO)  
(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemDirectory%\appmgmt",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;0x1201a9;;;BU)"  
"%SystemDirectory%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%SystemRoot%\Debug\UserMode",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)  
(A;OIIO;0x100006;;;BU)(A;;0x100023;;;BU)"  
"%SystemRoot%\Temp",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;CI;0x100026;;;BU)"  
"%SystemRoot%\repair",2,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)"  
"%SystemRoot%\Registration",0,"D:PAR(A;OICI;FA;;;BA)(A;OICI;FA;;;SY)(A;OICI;FR;;;BU)"  
"%SystemRoot%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
"%ProgramFiles%",2,"D:PAR(A;OICI;FA;;;BA)(A;OICIIO;FA;;;CO)(A;OICI;FA;;;SY)(A;OICI;0x1200a9;;;BU)"  
;--------------------------------------------------------------------------------  
;グループの既定のメンバを編集する。  
;--------------------------------------------------------------------------------  
[Group Membership]  
;--------------------------------------------------------------------------------  
;Guests グループからアカウントを削除する。これらの設定はセキュリティ  
;ポリシー インターフェイスには表示されません。  
;--------------------------------------------------------------------------------  
%SceInfGuests%__Members =  
[Strings]  
SceInfAdministrator = Administrator  
SceInfAdmins = Administrators  
SceInfAcountOp = Account Operators  
SceInfAuthUsers = Authenticated Users  
SceInfBackupOp = Backup Operators  
SceInfDomainAdmins = Domain Admins  
SceInfDomainGuests = Domain Guests  
SceInfDomainUsers = Domain Users  
SceInfEveryone = Everyone  
SceInfGuests = Guests  
SceInfGuest = Guest  
SceInfPowerUsers = Power Users  
SceInfPrintOp = Print Operators  
SceInfReplicator = Replicator  
SceInfServerOp = Server Operators  
SceInfUsers = Users  
[Profile Description]  
Description=Evaluated Configuration high security policy settings for Windows 2000 Domains.  
</td>  
</tr>  
</table>
<p> </p>
 
[](#mainsection)[ページのトップへ](#mainsection)  
  
### G-8. 高セキュリティ Windows 2000 ドメイン コントローラ セキュリティ ポリシーのテンプレート
<p> </p>
<table style="border:1px; solid black;">
<tr>  
<td>  
; (c) Microsoft Corporation 1997-2000  
;  
; セキュリティ構成エディタ用のセキュリティ構成のテンプレート  
;  
; テンプレート名:        CC_HiSec_W2K_DC.inf  
; テンプレート バージョン:     1.0  
;  
;このセキュリティ構成のテンプレートでは、情報テクノロジ セキュリティ評価のための共通基準 (CC)   
;のもとで、Windows 2000 の評価された構成をサポートするための設定を示します。  
;  
; 改訂履歴  
; 0000   -   作成   2002 年 9 月 17 日  
[version]  
signature="$CHICAGO$"  
Revision=1  
[System Access]  
RequireLogonToChangePassword = 0  
ForceLogoffWhenHourExpire = 1  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - ユーザー権利の割り当て  
;--------------------------------------------------------------------------------  
[Privilege Rights]  
SeNetworkLogonRight = *S-1-5-32-544,*S-1-5-11  
SeInteractiveLogonRight = *S-1-5-32-548,*S-1-5-32-544,*S-1-5-32-551,*S-1-5-32-550,*S-1-5-32-549  
SeMachineAccountPrivilege =  
SeBackupPrivilege = *S-1-5-32-549,*S-1-5-32-551,*S-1-5-32-544  
SeChangeNotifyPrivilege = *S-1-1-0,*S-1-5-11,*S-1-5-32-544  
SeSystemtimePrivilege = *S-1-5-32-549,*S-1-5-32-544  
SeCreatePagefilePrivilege = *S-1-5-32-544  
SeDebugPrivilege = *S-1-5-32-544  
SeEnableDelegationPrivilege = *S-1-5-32-544  
SeRemoteShutdownPrivilege = *S-1-5-32-549,*S-1-5-32-544  
SeIncreaseQuotaPrivilege = *S-1-5-32-544  
SeIncreaseBasePriorityPrivilege = *S-1-5-32-544  
SeLoadDriverPrivilege = *S-1-5-32-544  
SeBatchLogonRight =  
SeSecurityPrivilege = *S-1-5-32-544  
SeSystemEnvironmentPrivilege = *S-1-5-32-544  
SeProfileSingleProcessPrivilege = *S-1-5-32-544  
SeSystemProfilePrivilege = *S-1-5-32-544  
SeUndockPrivilege = *S-1-5-32-544  
SeCreateTokenPrivilege =  
SeCreatePermanentPrivilege =  
SeDenyNetworkLogonRight =  
SeDenyBatchLogonRight =  
SeDenyServiceLogonRight =  
SeDenyInteractiveLogonRight =  
SeAuditPrivilege =  
SeTcbPrivilege =  
SeLockMemoryPrivilege =  
SeServiceLogonRight =  
SeAssignPrimaryTokenPrivilege =  
SeRestorePrivilege = *S-1-5-32-549,*S-1-5-32-551,*S-1-5-32-544  
SeShutdownPrivilege = *S-1-5-32-549,*S-1-5-32-550,*S-1-5-32-551,*S-1-5-32-544,*S-1-5-32-548  
SeSyncAgentPrivilege =  
SeTakeOwnershipPrivilege = *S-1-5-32-544  
;--------------------------------------------------------------------------------  
;ローカル ポリシー - セキュリティ オプション  
;--------------------------------------------------------------------------------  
;--------------------------------------------------------------------------------  
;レジストリ値  
;--------------------------------------------------------------------------------  
; 完全なパスで表したレジストリ値の名前 = 種類、値  
; REG_SZ                      ( 1 )  
; REG_EXPAND_SZ               ( 2 )  // 拡張する環境変数と共に  
; REG_BINARY                  ( 3 )  
; REG_DWORD                   ( 4 )  
; REG_MULTI_SZ                ( 7 )  
[Registry Values]  
MACHINE\System\CurrentControlSet\Services\NTDS\Parameters\LdapServerIntegrity=4,2  
MACHINE\System\CurrentControlSet\Control\Lsa\SubmitControl=4,0  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanManServer\Parameters\RequireSecuritySignature=4,0  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\EnableSecuritySignature=4,1  
MACHINE\System\CurrentControlSet\Services\LanmanWorkstation\Parameters\RequireSecuritySignature=4,0  
;--------------------------------------------------------------------------------  
;レジストリ キーへのアクセス許可。評価された構成に基づくドメイン  
;セキュリティ ポリシーによって挿入された、ドメイン コントローラからの  
;パワー ユーザーの参照をなくします。  
;--------------------------------------------------------------------------------  
[Registry Keys]  
"CLASSES_ROOT",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SYSTEM\CurrentControlSet\Control\Print\Printers",2,"D:PAR(A;CI;KA;;;BA)  
(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\.hlp",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\SOFTWARE\Classes\helpfile",0,"D:PAR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)  
(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
"MACHINE\Software\Classes",0,"D:AR(A;CI;KA;;;BA)(A;CI;KR;;;AU)(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)  
(A;CI;KR;;;BU)"  
"MACHINE\Software",0,"D:PAR(A;CI;KA;;;BA)(A;CIIO;KA;;;CO)(A;CI;KA;;;SY)(A;CI;KR;;;BU)"  
[Profile Description]  
Description=Evaluated Configuration high security policy (delta) settings for   
Windows 2000 Domain Controllers.  
</td>  
</tr>  
</table>   
<p> </p>  
  
[](#mainsection)[ページのトップへ](#mainsection)  
  
##### 目次  
  
-   [第 1 章 ‐ ハードウェアおよびソフトウェアの環境](https://technet.microsoft.com/ja-jp/library/da7603d8-d1d7-400a-9993-3ac61d633e66(v=TechNet.10))  
-   [第 2 章 ‐ オペレーティング システムのインストール](https://technet.microsoft.com/ja-jp/library/ddb614e6-9456-4f76-8dea-4018a51a810d(v=TechNet.10))  
-   [第 3 章 ‐ セキュリティで保護された構成](https://technet.microsoft.com/ja-jp/library/95fe8ebd-7386-4e95-aff8-5fca17435788(v=TechNet.10))  
-   [第 4 章 ‐ Windows 2000 Common Criteria (共通基準) セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/270098dc-f10b-41de-b26a-c2d795bca536(v=TechNet.10))  
-   [参考資料](https://technet.microsoft.com/ja-jp/library/6df170a9-3e6d-42d6-a4c3-0fd3eb71bf77(v=TechNet.10))  
-   [付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定](https://technet.microsoft.com/ja-jp/library/1adc2300-c9de-4ee0-bab7-9f8a797b03bc(v=TechNet.10))  
-   [付録 B ‐ 監査カテゴリとイベント](https://technet.microsoft.com/ja-jp/library/0fc077e8-8bf5-4b4d-a555-a8c26c9792f0(v=TechNet.10))  
-   [付録 C ‐ ユーザー権利と特権](https://technet.microsoft.com/ja-jp/library/9d7407aa-87b7-4564-9659-3e99abe3ac6c(v=TechNet.10))  
-   [付録 D ‐ ユーザー アカウントとグループ アカウント](https://technet.microsoft.com/ja-jp/library/50b1a83f-d25a-4ffe-b601-3adc677fa632(v=TechNet.10))  
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))  
-   付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート  
  
[](#mainsection)[ページのトップへ](#mainsection)
