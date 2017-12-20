---
TOCTitle: 'Blaster に関する情報 : Blaster ワームへの対策 ‐ 亜種によりネットワークが遅くなる'
Title: 'Blaster に関する情報 : Blaster ワームへの対策 ‐ 亜種によりネットワークが遅くなる'
ms:assetid: '161628b4-88ac-4b5a-92cb-77f2a565f0ac'
ms:contentKeyID: 19871733
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362787(v=TechNet.10)'
---

Blaster に関する情報
====================

### Blaster ワームへの対策 ‐ 亜種によりネットワークが遅くなる

公開日: 2003年8月20日 | 最終更新日: 2003年8月20日

### Blaster ワームの亜種に感染した場合のネットワークの復旧方法

2003 年 8 月 12 日に被害を与え始めた [Blaster ワーム](https://technet.microsoft.com/ja-jp/library/4c748477-4337-4f1a-89c5-000801bad760(v=TechNet.10)) によりコンピュータが異常終了してしまったり、Office が正しく動作しなくなるなどの問題が発生しています。また、8 月 18 日には、Blaster ワームの非常に危険な亜種 (W32.Blaster.D.Worm、W32.Nachi.Worm、W32.Welchia.Worm などと呼ばれています) が確認されました。この新種の Blaster ワームに感染した場合、インターネットに接続できなくなったり、ネットワークが非常に遅くなる場合があります。

このワームによって作成された 2 つのサービスを停止することで、この問題を緩和することができます。この資料では、このワームが作成するサービスの停止方法について説明しています。

-   サービスの停止方法

Blaster ワームおよびその亜種の対策については、ネットワークの復旧後に次の資料をご覧ください。

-   [Blaster ワームへの対策 - Windows XP 編](https://technet.microsoft.com/ja-jp/library/221c39e2-01bf-42ea-a857-a27633f5c53b(v=TechNet.10))

-   [Blaster ワームへの対策 - Windows 2000/Windows NT 4.0 編](https://technet.microsoft.com/ja-jp/library/df816f36-1e9e-4775-8526-c1d94fd61e6c(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)

### サービスの停止方法

サービスの停止方法は、次のとおりです。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362787.start_xp(ja-jp,TechNet.10).jpg" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362787.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">[スタート] メニューから [ファイル名を指定して実行] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362787.dbox_rpcpatch(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362787.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><strong>net stop rpcpatch</strong> と入力し、[OK] ボタンをクリックします。</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"> 
<img src="images/Dd362787.start_xp(ja-jp,TechNet.10).jpg" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362787.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;">再び、[スタート] メニューから [ファイル名を指定して実行] をクリックします。</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"> 
<img src="images/Dd362787.dbox_rpctftpd(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"> 
<img src="images/Dd362787.green_arrow_sml(ja-jp,TechNet.10).gif" /></td>
<td style="border:1px solid black;"><strong>net stop rpctftpd</strong> と入力し、[OK] ボタンをクリックします。</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
