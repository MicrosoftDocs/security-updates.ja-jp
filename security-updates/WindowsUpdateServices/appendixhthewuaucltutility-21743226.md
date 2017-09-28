---
TOCTitle: 'Appendix H: The wuauclt Utility'
Title: 'Appendix H: The wuauclt Utility'
ms:assetid: '7cc1c5f9-5678-4bb4-a7a6-18939dcc120c'
ms:contentKeyID: 21743226
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd939851(v=WS.10)'
---

Appendix H: The wuauclt Utility
===============================

The wuauclt utility allows you some control over the functioning of the Windows Update Agent. It is updated as part of Windows Update.

Command line switches for wuauclt
---------------------------------

The following are the command line for wuauclt.

###  

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Option</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>/a /ResetAuthorization</p></td>
<td style="border:1px solid black;"><p>Initiates an asynchronous background search for applicable updates. If Automatic Updates is disabled, this option has no effect.</p></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><p>/r /ReportNow</p></td>
<td style="border:1px solid black;"><p>Sends all queued reporting events to the server asynchronously.</p></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><p>/? /h /help</p></td>
<td style="border:1px solid black;"><p>Shows this help information.</p></td>
</tr>
</tbody>
</table>
