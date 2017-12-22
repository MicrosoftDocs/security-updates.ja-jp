---
TOCTitle: Active Directory キャッシュ設定の変更
Title: Active Directory キャッシュ設定の変更
ms:assetid: '8789a7a5-2065-4fae-9104-e0a70f1f2fb6'
ms:contentKeyID: 18122240
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Cc747586(v=WS.10)'
---

Active Directory キャッシュ設定の変更
=====================================

レジストリ内の設定で、Active Directory キャッシュに格納されるエントリの数が指定されています。クライアント要求に対する応答時間を向上するために、この設定を変更できます。詳細については、この項目の「ディレクトリ サービス パフォーマンスの最適化」を参照してください。また、キャッシュに格納される情報の有効期間を指定することもできます。

32 ビット バージョンの Windows Server 2003 が動作しているコンピュータの場合、次のレジストリ キーは、キャッシュ エントリの完全なサブキー パスです。

**HKEY\_LOCAL\_MACHINE\\Software\\Microsoft\\DRMS\\1.0\\DirectoryServices**

64 ビット バージョンの Windows Server 2003 が動作しているコンピュータの場合、次のレジストリ キーは、キャッシュ エントリの完全なサブキー パスです。

**HKEY\_LOCAL\_MACHINE\\SoftwareWOW6432Node\\Microsoft\\DRMS\\1.0\\DirectoryServices**

メモリ内キャッシュの動作を制御するエントリの一覧を次の表に示します。

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >名前</th>
<th style="border:1px solid black;" >型</th>
<th style="border:1px solid black;" >既定値</th>
<th style="border:1px solid black;" >説明</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">PrincipalCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">キャッシュに格納できるプリンシパルとその電子メール アドレスおよび SID の最大数</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PrincipalCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">プリンシパルについてキャッシュに格納される情報の有効期間</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupIDCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">キャッシュに格納できるグループとその電子メール アドレスおよび SID の最大数</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupIDCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">グループ メンバシップ用にキャッシュされた情報の有効期間</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">GroupMembershipCacheMax</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">1,000</td>
<td style="border:1px solid black;">キャッシュに格納できるグループ メンバの連絡先の最大数</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">GroupMembershipCacheExpireMinutes</td>
<td style="border:1px solid black;">DWORD</td>
<td style="border:1px solid black;">12</td>
<td style="border:1px solid black;">グループ メンバの連絡先用にキャッシュされた情報の有効期間</td>
</tr>
</tbody>
</table>

> [!Caution] 
> レジストリに不適切な編集を行うと、システムに大きな損害を与える可能性があります。レジストリに変更を加える前に、コンピュータ上の重要なデータをバックアップしてください。
  
> [!NOTE] 
> **PrincipalCacheExpireMinutes**、**GroupIDCacheExpireMinutes**、**GroupMembershipCacheExpireMinutes**、および**ContactMembersofGroupCacheExpireMinutes** レジストリ エントリは、データベース サーバーのディレクトリ サービス データベースに格納されているローカルの Active Directory キャッシュの有効期限も制御します。
