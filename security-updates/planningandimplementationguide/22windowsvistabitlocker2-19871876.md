---
TOCTitle: 第 22 回 Windows Vista のセキュリティ機能 ～ BitLocker その 2 ～
Title: 第 22 回 Windows Vista のセキュリティ機能 ～ BitLocker その 2 ～
ms:assetid: '13931ae3-30fd-4b8d-b8c8-5b1ef570fe31'
ms:contentKeyID: 19871876
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd362931(v=TechNet.10)'
---

セキュリティ対策の要点解説
==========================

### 第 22 回 Windows Vista のセキュリティ機能 ～ BitLocker その 2 ～

公開日: 2007年10月24日

![](images/Dd362931.SecPoint(ja-jp,TechNet.10).gif)

マイクロソフト株式会社
セキュリティ レスポンス チーム
小野寺 匠 著

[前回](https://technet.microsoft.com/ja-jp/library/aca2eb90-b50c-4630-b73e-fd85f6fa75c7(v=TechNet.10))は、Microsoft BitLocker ドライブ暗号化 (BitLocker) の概要について触れました。今回は、BitLocker を実際に使用する際の条件や設定について触れます。

BitLocker はWindows Vista の機能ではありますが、2 つのエディションでのみ使用することが出来ます。

 
<table style="border:1px solid black;">
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Windows Vistaエディション</th>
<th style="border:1px solid black;" >BitLocker</th>
<th style="border:1px solid black;" >EFS</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Home Basic</td>
<td style="border:1px solid black;">×</td>
<td style="border:1px solid black;">×</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Home Premium</td>
<td style="border:1px solid black;">×</td>
<td style="border:1px solid black;">×</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Business</td>
<td style="border:1px solid black;">×</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Enterprise</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Ultimate</td>
<td style="border:1px solid black;">○</td>
<td style="border:1px solid black;">○</td>
</tr>
</tbody>
</table>
  
×: 使用不可 ○: 使用可
  
使用可能なエディションに加えて、以下のハードウェア等の条件があります。
  
-   TPM 1.2 以上が搭載されていること  
    （TPM が搭載されていない場合は、USB フラッシュ ドライブ等のデバイスでも代用可能）
  
-   ディスク ボリューム （パーティション） が 2 つ以上あること
  
-   BitLocker で使用する 2 つのボリュームが NTFS でフォーマットされていること
  
-   PC 起動中の USB デバイスへのアクセスに対応した BIOS であること
  
すでに、Windows Vista を単一のディスク ボリュームでセットアップしてしまった場合でも、BitLocker ドライブ準備ツールを使い、ディスク ボリューム構成を見直すことで、条件をクリアする事ができます。BitLocker ドライブ準備ツールの詳細は、サポート技術情報 [930063](http://support.microsoft.com/kb/930063) を参照してください。ボリュームは、システム起動用と、OS インストール用に構成します。BitLocker ドライブ準備ツールを使用すると、OS がインストールされている C ドライブを自動的にサイズ調整し、システム起動用の S ドライブが作成されます。
  
では、実際に BitLocker を構成していくには、\[コントロ-ルパネル\] - \[セキュリティ\] - \[BitLocker ドライブ暗号化\] を選択します。BitLocker の使用準備が整っていると、BitLocker が設定可能なドライブの一覧と、\[BitLocker をオンにする\] が表示されます。TPM が搭載されていないコンピューターの場合、ここで警告が表示され、先に進む事ができません。その場合は、グループ ポリシーを変更して、TPM を使用しない BitLocker の使用を有効にする必要があります。\[コンピューターの構成\] - \[管理用テンプレート\] - \[Windows コンポーネント\] - \[BitLocker ドライブ暗号化\] - \[コントロール パネル セットアップ: 詳細なスタートアップ オプションを有効にする\] を有効にする事で、USB キーを TPM の代用に使用することが可能になります。
  
しかし、BitLocker を設定したあとに、USB キーを紛失したりすると、OS が起動できなくなる可能性があります。そのために、回復用のパスワードを必ず安全なところに保存することをお勧めします。間違っても、回復用のパスワードを、USB キーに保存する事が無いようにします。印刷または、USB キーとは別のリムーバブル メディアに保存しておく事をお勧めします。Active Directory がある環境では、回復用のパスワードを、Active Directory で集中管理することができます。特に企業で BitLocker を使用する場合は、回復する手段を最優先に考えて BitLocker の展開を計画しなければなりません。
  
[![](images/Dd362931.btn_reg_today(ja-jp,TechNet.10).jpg)](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))
  
この記事は、マイクロソフト セキュリティ ニュースレターで配信しました。
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 購読無料
  
![](images/Dd362931.subscribe(ja-jp,TechNet.10).gif)
  
[セキュリティ ニュースレター](http://www.microsoft.com/japan/technet/security/secnews/default.mspx) では、セキュリティに関する様々な情報を毎月お届けしています。  
セキュリティ ニュースレターを[購読する](https://technet.microsoft.com/ja-jp/library/d2607610-3137-420b-9bbf-2552bec68922(v=TechNet.10))。
  
**バックナンバー**  
-   [セキュリティ対策の要点解説](https://technet.microsoft.com/ja-jp/library/f301b3b4-fdcc-43f8-846e-135538db4edf(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
