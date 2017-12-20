---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 B ‐ 監査カテゴリとイベント'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 B ‐ 監査カテゴリとイベント'
ms:assetid: '0fc077e8-8bf5-4b4d-a555-a8c26c9792f0'
ms:contentKeyID: 19869611
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277459(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 B ‐ 監査カテゴリとイベント

最終更新日: 2003年2月18日

**監査のためのセキュリティ ターゲットの遵守マトリックス**

 
<table style="border:1px solid black;">
<tr>
<th style="border:1px solid black;" >
コンポーネント

</th>
<th style="border:1px solid black;" >
イベント

</th>
<th style="border:1px solid black;" >
監査イベント

</th>
<th style="border:1px solid black;" >
必要な設定

</th>
<th style="border:1px solid black;" >
 

</th>
</tr>
<tr>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
S

</td>
<td style="border:1px solid black;">
F

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_GEN.1

</td>
<td style="border:1px solid black;">
監査機能のスタートアップとシャットダウン

</td>
<td style="border:1px solid black;">
**カテゴリ: ポリシーの変更**
  
612 – 監査ポリシーの変更
  
(任意の監査カテゴリに関して監査が有効または無効にされたときに、このイベントが生成されます。監査の変更の一覧がイベント ログに表示されます。)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_GEN.2

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_SAR.1

</td>
<td style="border:1px solid black;">
監査レコードからの情報の読み取り

</td>
<td style="border:1px solid black;">
**カテゴリ: 特権の使用**
  
578 – 特権オブジェクト操作
  
(セキュリティ イベント ログへのアクセス。SeSecurityPrivilege は正常終了するはずです。)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_SAR.2

</td>
<td style="border:1px solid black;">
監査レコードからの情報の読み取りの試みが不成功

</td>
<td style="border:1px solid black;">
**カテゴリ: 特権の使用**
  
578 – 特権オブジェクト操作
  
(SeSecurityPrivilege は異常終了するはずです。)

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_SAR.3

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_SEL.1

</td>
<td style="border:1px solid black;">
監査コレクション機能が働いている間に発生した、監査構成に対するすべての修正

</td>
<td style="border:1px solid black;">
**カテゴリ: ポリシーの変更**
  
612 – 監査ポリシーの変更
  
(監査の変更の一覧がイベント ログに表示されます。)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_STG.1

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_STG.3

</td>
<td style="border:1px solid black;">
しきい値を超過したために取られた措置

</td>
<td style="border:1px solid black;">
**カテゴリ: システム**
  
516 – 監査メッセージをキューに登録するために割り当てられた内部リソースをすべて使用したため、一部の監査が失われました。
  
517 – 監査ログが消去されました。
  
(あらかじめ定義されている監査のしきい値をシステムが超過したために、権限のある管理者によって取られたイベント ログの消去措置をレビューします。)
  
523 – 監査ログ ファイルが "x" % に達しました。
  
**注意:** 上記のイベントは SP3 の場合にのみ生成されます。 (監査レコードを減らしても良いと管理者が判断するパーセントに値を設定します。） (HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet \\Services\\Eventlog\\Security\\WarningLevel)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FAU\_STG.4

</td>
<td style="border:1px solid black;">
監査記憶域に障害が発生したために取られた措置

</td>
<td style="border:1px solid black;">
517 – 監査ログが消去されました。
  
(あらかじめ定義されている監査のしきい値をシステムが超過したために、権限のある管理者によって取られたイベント ログの消去措置をレビューします。)

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FDP\_ACC.1(a)

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FDP\_ACF.1(a)

</td>
<td style="border:1px solid black;">
SFP の対象となっているオブジェクトを操作しようとするすべての要求

</td>
<td style="border:1px solid black;">
**カテゴリ: オブジェクト アクセス**
  
563 – 削除のために開かれているオブジェクト
  
564 – 削除されたオブジェクト
  
565 – オブジェクトのオープン
  
566 – オブジェクトの操作
  
**カテゴリ: プロセスの追跡**
  
594 – オブジェクトへのハンドルの複製
  
595 – オブジェクトへの間接アクセスの取得

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FDP\_RIP.2

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FDP\_RIP.2.
  
Note 1

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FIA\_ATD.1

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FIA\_SOS.1

</td>
<td style="border:1px solid black;">
テスト済みの任意の TSF による拒否または受け入れ

</td>
<td style="border:1px solid black;">
**カテゴリ: ログオン**
  
528 – ログオンの成功
  
529 – ログオン失敗: ユーザー名を認識できないか、またはパスワードが間違っています。
  
535 – ログオン失敗: 指定されたアカウント パスワードの有効期間が切れています。
  
540 – ネットワーク ログオンの成功
  
545 – IPSec ピアの認証に失敗しました。
  
**カテゴリ: アカウント ログオン**
  
680 – ログオンに使用されたアカウント
  
681 – ワークステーション &lt;ワークステーション&gt; からの &lt;ソース&gt; によるアカウント &lt;クライアント名&gt; のログオンに失敗しました。エラー コードは &lt;エラー&gt; です。

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FIA\_UAU.7

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FIA\_USB.1

</td>
<td style="border:1px solid black;">
ユーザーのセキュリティ属性をサブジェクトにバインドするのに成功または失敗 (例: サブジェクトの作成に成功または失敗)

</td>
<td style="border:1px solid black;">
**カテゴリ: プロセスの追跡**
  
592 – 新しいプロセスの作成

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_MSA.1(a)

</td>
<td style="border:1px solid black;">
オブジェクトのセキュリティ属性の値に関するすべての修正

</td>
<td style="border:1px solid black;">
**カテゴリ: オブジェクト アクセス**
  
560 – オブジェクトのオープン
  
(「説明: アクセス」の下に AppendData、ReadAttributes、WriteAttributes の3 つのエントリが必要です。)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_MSA.3(a)

</td>
<td style="border:1px solid black;">
許容的規則または制限的規則の既定の設定の修正。セキュリティ属性の初期値のすべての修正。

</td>
<td style="border:1px solid black;">
**カテゴリ: オブジェクト アクセス**
  
560 – オブジェクトのオープン

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_MTD.1(a)
  
CAPP – 5.4.3

</td>
<td style="border:1px solid black;">
TSF データの値に対するすべての修正 (監査ログの作成、削除、およびクリア)

</td>
<td style="border:1px solid black;">
**カテゴリ: システム**
  
517 – 監査ログが消去されました。
  
**カテゴリ: オブジェクト アクセス**
  
(セキュリティ ログ ファイルに監査が設定されている場合、これらのイベントにより、セキュリティ ログ ファイルの直接削除をログに記録することができます。)
  
563 – 削除のために開かれているオブジェクト
  
564 – 削除されたオブジェクト
  
**カテゴリ: 特権の使用**
  
578 – 特権オブジェクト操作
  
(SeSecurityPrivilege を使用したものとして示され、実際の変更はイベント 612 に注記されます。)
  
**カテゴリ: ポリシーの変更**
  
612 – 監査ポリシーの変更

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_MTD.1(b)
  
CAPP – 5.4.4

</td>
<td style="border:1px solid black;">
TSF データの値に対するすべての修正 (監査ログの修正 - TSF データの新しい値を含みます)

</td>
<td style="border:1px solid black;">
**カテゴリ: ポリシーの変更**
  
612 – 監査ポリシーの変更

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_MTD.1(c)
  
CAPP – 5.4.5

</td>
<td style="border:1px solid black;">
TSF データの値に対するすべての修正 (ユーザーのセキュリティ属性 - TSF データの新しい値を含みます)

</td>
<td style="border:1px solid black;">
**カテゴリ: ポリシーの変更**
  
608 – ユーザー権利の割り当て
  
609 – ユーザー権利の削除
  
**カテゴリ: アカウント管理**
  
624 – ユーザー アカウントの作成
  
625 – ユーザー アカウントの種類の変更
  
626 – ユーザー アカウントの有効化
  
629 – ユーザー アカウントの無効化
  
630 – ユーザー アカウントの削除
  
631 – セキュリティが有効なグローバル グループの作成
  
632 – セキュリティが有効なグローバル グループ メンバが追加されました。
  
633 – セキュリティが有効なグローバル グループ メンバが削除されました。
  
634 – セキュリティが有効なグローバル グループが削除されました。
  
635 – セキュリティが有効なローカル グループの作成
  
636 – セキュリティが有効なローカル グループ メンバが追加されました。
  
637 – セキュリティが有効なローカル グループ メンバが削除されました。
  
638 – セキュリティが有効なローカル グループが削除されました。
  
639 – セキュリティが有効なローカル グループが変更されました。
  
641 – セキュリティが有効なグローバル グループが変更されました。
  
642 – ユーザー アカウントの変更
  
644 – ユーザー アカウントのロック
  
648 – セキュリティが無効なローカル グループが作成されました。
  
649 – セキュリティが無効なローカル グループが変更されました。
  
650 – セキュリティが無効なローカル グループ メンバが追加されました。
  
651 – セキュリティが無効なローカル グループ メンバが削除されました。
  
652 – セキュリティが無効なローカル グループが削除されました。
  
653 – セキュリティが無効なグローバル グループの作成
  
654 – セキュリティが無効なグローバル グループが変更されました。
  
655 – セキュリティが無効なグローバル グループ メンバが追加されました。
  
656 – セキュリティが無効なグローバル グループ メンバが削除されました。
  
657 – セキュリティが無効なグローバル グループが削除されました。
  
658 – セキュリティが有効なユニバーサル グループの作成
  
659 – セキュリティが有効なユニバーサル グループが変更されました。
  
660 – セキュリティが有効なユニバーサル グループ メンバが追加されました。
  
661 – セキュリティが有効なユニバーサル グループ メンバが削除されました。
  
662 – セキュリティが有効なユニバーサル グループが削除されました。
  
663 – セキュリティが無効なユニバーサル グループの作成
  
664 – セキュリティが無効なユニバーサル グループが変更されました。
  
665 – セキュリティが無効なユニバーサル グループ メンバが追加されました。
  
666 – セキュリティが無効なユニバーサル グループ メンバが削除されました。
  
667 – セキュリティが無効なユニバーサル グループが削除されました。
  
668 – グループの種類が変更されました。

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_MTD.1(d)
  
CAPP- 5.4.6

</td>
<td style="border:1px solid black;">
TSF データ (認証データ) の値に対するすべての修正

</td>
<td style="border:1px solid black;">
**カテゴリ: アカウント管理**
  
627 – パスワード変更の試行
  
628 – ユーザー アカウント パスワードの設定

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_REV.1(a)
  
CAPP – 5.4.7

</td>
<td style="border:1px solid black;">
セキュリティ属性 (ユーザー属性) を失効させるすべての試み

</td>
<td style="border:1px solid black;">
**カテゴリ: ポリシーの変更**
  
609 – ユーザー権利の削除
  
**カテゴリ: アカウント管理**
  
629 – ユーザー アカウントの無効化
  
644 – ユーザー アカウントのロック

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_REV.1(b)
  
CAPP – 5.4.8

</td>
<td style="border:1px solid black;">
TSF データ (オブジェクト属性) の値に対するすべての修正

</td>
<td style="border:1px solid black;">
(See FMT\_MSA.1a)

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_SMR.1

</td>
<td style="border:1px solid black;">
役割の一部を担うユーザーのグループに対する修正
  
役割の権利のすべての行使 (追加/ 詳細)

</td>
<td style="border:1px solid black;">
**カテゴリ: 特権の使用**
  
578 – 特権オブジェクト操作
  
**カテゴリ: アカウント管理**
  
632 – セキュリティが有効なグローバル グループ メンバが追加されました。
  
633 – セキュリティが有効なグローバル グループ メンバが削除されました。
  
634 – セキュリティが有効なグローバル グループが削除されました。
  
636 – セキュリティが有効なローカル グループ メンバが追加されました。
  
637 – セキュリティが有効なローカル グループ メンバが削除されました。
  
638 – セキュリティが有効なローカル グループが削除されました。
  
639 – セキュリティが有効なローカル グループが変更されました。
  
640 – 全般アカウント データベースの変更
  
641 – セキュリティが有効なグローバル グループが変更されました。
  
648 – セキュリティが無効なローカル グループが作成されました。
  
649 – セキュリティが無効なローカル グループが変更されました
  
650 – セキュリティが無効なローカル グループ メンバが追加されました。
  
652 – セキュリティが無効なローカル グループが削除されました。
  
654 – セキュリティが無効なグローバル グループが変更されました。
  
655 – セキュリティが無効なグローバル グループ メンバが追加されました。
  
656 – セキュリティが無効なグローバル グループ メンバが削除されました。
  
657 – セキュリティが無効なグローバル グループが削除されました。
  
659 – セキュリティが有効なユニバーサル グループが変更されました。
  
660 – セキュリティが有効なユニバーサル グループ メンバが追加されました。
  
661 – セキュリティが有効なユニバーサル グループ メンバが削除されました。
  
662 – セキュリティが有効なユニバーサル グループが削除されました。
  
664 – セキュリティが無効なユニバーサル グループが変更されました。
  
665 – セキュリティが無効なユニバーサル グループ メンバが追加されました。
  
666 – セキュリティが無効なユニバーサル グループ メンバが削除されました。
  
668 – グループの種類が変更されました。

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FPT\_AMT.1

</td>
<td style="border:1px solid black;">
基礎となっているコンピュータのテストの実行とその結果

</td>
<td style="border:1px solid black;">
利用不可

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FPT\_RVM.1

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FPT\_SEP.1

</td>
<td style="border:1px solid black;">
なし

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
FPT\_STM.1

</td>
<td style="border:1px solid black;">
時刻の変更

</td>
<td style="border:1px solid black;">
**カテゴリ: 特権の使用**
  
577 – 特権サービスの呼び出し
  
(SeSystemTimePrivilege の使用として示されます。)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FIA\_AFL.1

</td>
<td style="border:1px solid black;">
ログオン失敗
  
(あらかじめ定義されているしきい値に合致したため、アカウントを無効化)

</td>
<td style="border:1px solid black;">
**カテゴリ: ログオン**
  
529 – ログオン失敗: ユーザー名を認識できないか、またはパスワードが間違っています。
  
(ロックアウトにつながります。)
  
**カテゴリ: アカウント管理**
  
642 – ユーザー アカウントの変更 – アカウントはロックされました。
  
644 – ユーザー アカウントのロック

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FIA\_UAU.2

</td>
<td style="border:1px solid black;">
認証機構の使用

</td>
<td style="border:1px solid black;">
**カテゴリ: ログオン**
  
528 – ログオンの成功
  
529 – ログオン失敗: ユーザー名を認識できないか、またはパスワードが間違っています。
  
540 – ネットワーク ログオンの成功
  
**カテゴリ: アカウント ログオン**
  
680 – ログオンに使用されたアカウント
  
681 – ワークステーション &lt;ワークステーション&gt; からの &lt;ソース&gt; によるアカウント &lt;クライアント名&gt; のログオンに失敗しました。エラー コードは &lt;エラー&gt; です。

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FIA\_UID.2

</td>
<td style="border:1px solid black;">
ユーザー認証機構のすべての使用 (成功したときに提示された識別情報を含みます)

</td>
<td style="border:1px solid black;">
**カテゴリ: ログオン**
  
528 – ログオンの成功
  
529 – ログオン失敗: ユーザー名を認識できないか、またはパスワードが間違っています。
  
535 – ログオン失敗: 指定されたアカウント パスワードの有効期間が切れています。
  
540 – ネットワーク ログオンの成功
  
545 – IPSec ピアの認証に失敗しました。
  
**カテゴリ: アカウント ログオン**
  
625 – 事前認証の失敗
  
681 – ワークステーション &lt;ワークステーション&gt; からの &lt;ソース&gt; によるアカウント &lt;クライアント名&gt; のログオンに失敗しました。エラー コードは &lt;エラー&gt; です。

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_MOF.1(a)

</td>
<td style="border:1px solid black;">
監査ポリシーの変更

</td>
<td style="border:1px solid black;">
**カテゴリ: 特権の使用**
  
578 – 特権オブジェクト操作
  
(SeSecurityPrivilege の使用として示されます。)
  
**カテゴリ: ポリシーの変更**
  
612 – 監査ポリシーの変更

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FMT\_MTD.1(g)

</td>
<td style="border:1px solid black;">
TSF 時刻を変更するための権限のある管理者特権の使用の試み

</td>
<td style="border:1px solid black;">
**カテゴリ: 特権の使用**
  
577 – 特権サービスの呼び出し (SeSystemTimePrivilege の使用として示されます。)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
 

</td>
</tr>
<tr>
<td style="border:1px solid black;">
TRANSFER\_PROT\_EX

</td>
<td style="border:1px solid black;">
IPSEC 関連のイベント

</td>
<td style="border:1px solid black;">
**カテゴリ: ログオン**
  
541 – IPSec セキュリティ アソシエーションが確立されました。
  
542 – IPSec セキュリティ アソシエーションが終了しました。モード: データ保護 (クイック モード)
  
543 – IPSec セキュリティ アソシエーションが終了しました。モード: キー交換 (メイン モード)
  
544 – ピアが認証されなかったため、IPSec セキュリティ アソシエーションの確立に失敗しました。
  
545 – IPSec ピアの認証に失敗しました。
  
546 – ピアが無効な提案を送信したため、IPSec セキュリティ アソシエーションの確立に失敗しました。
  
547 – IPSec セキュリティ アソシエーションのネゴシエーションに失敗しました。
  
**カテゴリ: ポリシーの変更**
  
613 – IPSec ポリシー エージェントを開始しました。
  
614 – IPSec ポリシーが変更されました。
  
615 – IPSec ポリシー エージェントで、重大である可能性のある障害がありました。
  
616 – IPSec ポリシー エージェントで、重大である可能性のある障害がありました。

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)  
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FTA\_SSL1

</td>
<td style="border:1px solid black;">
ロックを解除する試み

</td>
<td style="border:1px solid black;">
**カテゴリ: ログオン**
  
528 – ログオンの成功 (エントリ 6 のロックを解除)
  
529 – ログオン失敗 (エントリ 6 のロックを解除)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FTA\_SSL.2

</td>
<td style="border:1px solid black;">
ロックを解除する試み

</td>
<td style="border:1px solid black;">
**カテゴリ: ログオン**
  
528 – ログオンの成功 (エントリ 6 のロックを解除)
  
529 – ログオン失敗 (エントリ 6 のロックを解除)

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
FTA\_TSE.1

</td>
<td style="border:1px solid black;">
ログオン失敗

</td>
<td style="border:1px solid black;">
**カテゴリ: ログオン**
  
535 – ログオン失敗: 指定されたアカウント パスワードの有効期間が切れています。

</td>
<td style="border:1px solid black;">
 

</td>
<td style="border:1px solid black;">
![](images/Dd277459.check(ja-jp,TechNet.10).gif)
</td>
</tr>
</table>
 
[](#mainsection)[ページのトップへ](#mainsection)

##### 目次

-   [第 1 章 ‐ ハードウェアおよびソフトウェアの環境](https://technet.microsoft.com/ja-jp/library/da7603d8-d1d7-400a-9993-3ac61d633e66(v=TechNet.10))
-   [第 2 章 ‐ オペレーティング システムのインストール](https://technet.microsoft.com/ja-jp/library/ddb614e6-9456-4f76-8dea-4018a51a810d(v=TechNet.10))
-   [第 3 章 ‐ セキュリティで保護された構成](https://technet.microsoft.com/ja-jp/library/95fe8ebd-7386-4e95-aff8-5fca17435788(v=TechNet.10))
-   [第 4 章 ‐ Windows 2000 Common Criteria (共通基準) セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/270098dc-f10b-41de-b26a-c2d795bca536(v=TechNet.10))
-   [参考資料](https://technet.microsoft.com/ja-jp/library/6df170a9-3e6d-42d6-a4c3-0fd3eb71bf77(v=TechNet.10))
-   [付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定](https://technet.microsoft.com/ja-jp/library/1adc2300-c9de-4ee0-bab7-9f8a797b03bc(v=TechNet.10))
-   付録 B ‐ 監査カテゴリとイベント
-   [付録 C ‐ ユーザー権利と特権](https://technet.microsoft.com/ja-jp/library/9d7407aa-87b7-4564-9659-3e99abe3ac6c(v=TechNet.10))
-   [付録 D ‐ ユーザー アカウントとグループ アカウント](https://technet.microsoft.com/ja-jp/library/50b1a83f-d25a-4ffe-b601-3adc677fa632(v=TechNet.10))
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))

[](#mainsection)[ページのトップへ](#mainsection)
