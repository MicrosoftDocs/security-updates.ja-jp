---
TOCTitle: Microsoft Operations Manager を使用した監視
Title: Microsoft Operations Manager を使用した監視
ms:assetid: 'ce372598-7421-4f1f-b8eb-f62da26e85d1'
ms:contentKeyID: 18122363
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747758(v=WS.10)'
---

Microsoft Operations Manager を使用した監視
===========================================

RMS には Microsoft® Operations Manager (以下 MOM) と共に使用できる Management Pack が含まれています。MOM を使用すると、組織内にあるサーバーの動作を次のような方法で管理できます。

-   RMS によってアプリケーション イベント ログに記録されたイベントを監視する。
-   サービス停止の可能性や構成上の問題を示すイベントを強調表示して、対策や予防措置をすばやく取れるようにする。
-   サーバー ライセンサ証明書の有効期限切れや Web サービスの失敗など、警告やエラーについて注意を促す。

RMS Management Pack (RMS\_MOMPack.akm) は、RMS と共に %programfiles%\\Windows Rights Management Services\\Tools フォルダにインストールされます。

この Management Pack には、RMS 管理者が RMS サーバーを導入するときに役立つ以下のルール セットが含まれています。

**RMS MOM Management Pack のルール**

1.  PMC Measure - Activation Proxy total failures
2.  PMC Measure - Activation Proxy Total time
3.  PMC Measure - Activation Total Processing Time
4.  PMC Measure - Activation Total Reqs
5.  PMC Measure - ActivationProxy total reqs
6.  PMC Measure - AD cache (DB cache) hits
7.  PMC Measure - AD cache (DB cache) misses
8.  PMC Measure - Average License Processing time
9.  Event - Configuration Info corruption
10. PMC Measure - Dead GC connections
11. PMC Measure - Enroll failures
12. Event - General Error
13. Event - Init Failure
14. Event - Licensor Cert has expired
15. Event - Licensor Cert Request Failure
16. Event - Logging service failure
17. PMC Measure - Max GC connections available
18. Event - Missing License Acq Point generation plugin
19. PMC Measure - MSMQ Queue length on all RM servers
20. Event - No GCs available
21. Event - Plugin Init Failure
22. Event - PrivateKey protection password changed
23. Event - RM Server Shut Down
24. Event - RM Server ShutDown Failure
25. Event - Server Startup Failure
26. PMC Measure - SubEnroll failures
27. Event - SuperUser privileged override power was invoked
28. PMC Threshold - Too Many GetLicensorCert failures
29. Event - Upcoming Licensor Cert Expiry - 1 Month
30. Event - Upcoming Licensor Cert expiry - 1 Week

組織で MOM Management Pack を展開する方法の詳細については、[マイクロソフトの Web サイト](http://www.microsoft.com/) (http://www.microsoft.com/) を参照してください。
