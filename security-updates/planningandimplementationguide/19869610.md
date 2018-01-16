---
TOCTitle: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定'
Title: 'Microsoft Windows 2000 セキュリティ構成ガイド : 付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定'
ms:assetid: '1adc2300-c9de-4ee0-bab7-9f8a797b03bc'
ms:contentKeyID: 19869610
ms:mtpsurl: 'https://technet.microsoft.com/ja-jp/library/Dd277458(v=TechNet.10)'
---

Microsoft Windows 2000 セキュリティ構成ガイド
=============================================

### 付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定

最終更新日: 2003年2月18日

**Windows 20000 既定のセキュリティ ポリシーの設定**

 
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >セキュリティの設定</th>
<th style="border:1px solid black;" >ローカル セキュリティ ポリシー (Professional および Server/Adv. Server)</th>
<th style="border:1px solid black;" >ドメイン コントローラ セキュリティ ポリシー</th>
<th style="border:1px solid black;" >ドメイン セキュリティ ポリシー</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">アカウント ポリシー</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>パスワード ポリシー</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>パスワードの履歴を記録する</em></td>
<td style="border:1px solid black;">パスワードを記憶しない</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">パスワードを 1 つ記憶する</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>パスワードの有効期間</em></td>
<td style="border:1px solid black;">42 日</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">42 日</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>パスワードの変更禁止期間</em></td>
<td style="border:1px solid black;">0 日</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">0 日</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>パスワードの長さ</em></td>
<td style="border:1px solid black;">0 文字</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">0 文字</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>パスワードは要求する複雑さを満たす</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">無効</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>暗号化を元に戻せる状態でドメインのすべてのユーザーのパスワードを保存する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">無効</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>アカウント ロックアウト ポリシー</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ロックアウト期間</em></td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>アカウントのロックアウトのしきい値</em></td>
<td style="border:1px solid black;">無効なログインの試みなし</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">無効なログインの試みなし</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ロックアウト カウントのリセット</em></td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Kerberos ポリシー</strong></td>
<td style="border:1px solid black;"><strong>(ポリシー利用不可)</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ユーザー ログオンの制限を強制する</em></td>
<td style="border:1px solid black;">(利用不可)
(ローカル既定値は有効)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">有効</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>サービス チケットの最長有効期間</em></td>
<td style="border:1px solid black;">(利用不可)
(ローカル既定値は 60 分)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">600 分</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>チケットの最長有効期間</em></td>
<td style="border:1px solid black;">(利用不可)
(ローカル既定値は 7 時間)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">10 時間</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ユーザー チケットを更新できる最長有効期間</em></td>
<td style="border:1px solid black;">(利用不可)
(ローカル既定値は 10 日)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">7 日</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>コンピュータの時計の同期の最長トレランス</em></td>
<td style="border:1px solid black;">(利用不可)
(ローカル既定値は 60 分)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">5 分</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">ローカル ポリシー</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>監査ポリシー</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>アカウント ログオン イベントの監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>アカウント管理の監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ディレクトリ サービスのアクセスの監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ログオン イベントの監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>オブジェクト アクセスの監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ポリシーの変更の監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>特権使用の監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>プロセス追跡の監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>システム イベントの監査</em></td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">監査しない</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>ユーザー権利の割り当て</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ネットワーク経由でコンピュータへアクセス</em></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users
Everyone</td>
<td style="border:1px solid black;">Administrators
Authenticated Users
Everyone
IUSR_W2K-<em>コンピュータ名</em>
IWAM_W2K-<em>コンピュータ名</em></td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ペレーティング システムの一部として機能</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ドメインにワークステーションを追加</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">Authenticated Users</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ファイルとディレクトリのバックアップ</em></td>
<td style="border:1px solid black;">Administrators
Backup Operators</td>
<td style="border:1px solid black;">Administrators
Backup Operators
Server Operators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>走査チェックのバイパス</em></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users
Everyone</td>
<td style="border:1px solid black;">Administrators
Authenticated Users
Everyone</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>システム時刻の変更</em></td>
<td style="border:1px solid black;">Administrators
Power Users</td>
<td style="border:1px solid black;">Administrators
Server Operators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ページ ファイルの作成</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>トークン オブジェクトの作成</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>永続的共有オブジェクトの作成</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>プログラムのデバッグ</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ネットワーク経由でコンピュータへアクセスを拒否する</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>バッチ ジョブとしてログオンを拒否する</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>サービスとしてログオンを拒否する</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ローカルでログオンを拒否する</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>コンピュータとユーザー アカウントに委任時の信頼を付与</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>リモートコンピュータからの強制シャットダウン</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators
Server Operators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>セキュリティ監査の生成</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>クォータの増加</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>スケジューリング優先順位の繰り上げ</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>デバイス ドライバのロードとアンロード</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>メモリ内のページのロック</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>バッチ ジョブとしてログオン</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">IUSR_W2K-<em>コンピュータ名</em>
IWAM_W2K-<em>コンピュータ名</em></td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>サービスとしてログオン</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ローカル ログオン</em></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users
<em>コンピュータ名</em>/Guest
<em>コンピュータ名</em>/TsInternetUser (Server/Adv. Server のみ)</td>
<td style="border:1px solid black;">Administrators
Authenticated Users
Backup Operators
IUSR_W2K-<em>コンピュータ名</em>
Print Operators
Server Operators
TsInternetUser</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>監査とセキュリティ ログの管理</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ファームウェア環境値の修正</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>単一プロセスのプロファイル</em></td>
<td style="border:1px solid black;">Administrators
Backup Operators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>システム パフォーマンスのプロファイル</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ドッキング ステーションからコンピュータを削除</em></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Users</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>プロセス レベル トークンの置き換え</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ファイルとディレクトリの復元</em></td>
<td style="border:1px solid black;">Administrators
Backup Operators</td>
<td style="border:1px solid black;">Administrators
Backup Operators
Server Operators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>システムのシャットダウン</em></td>
<td style="border:1px solid black;">Administrators
Backup Operators
Power Users
Users (Professional のみ)</td>
<td style="border:1px solid black;">Account Operators
Administrators
Backup Operators
Print Operators
Server Operators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ディレクトリ サービス データの同期化</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ファイルとその他のオブジェクトの所有権の取得</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">セキュリティ オプション</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>匿名接続の追加を制限する</em></td>
<td style="border:1px solid black;">なし。既定のアクセス許可に依存。</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>サーバー オペレータがタスクのスケジュールを割り当てるのを許可する (ドメイン コントローラのみ)</em></td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>システムをシャットダウンするのにログオンを必要としない</em></td>
<td style="border:1px solid black;">有効 (Professional のみ)
無効 (Server/Adv. Server のみ)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>リムーバブル NTFS メディアを取り出すのを許可する</em></td>
<td style="border:1px solid black;">Administrators</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>セッションを切断する前に、ある一定のアイドル時間を必要とする</em></td>
<td style="border:1px solid black;">15 分</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>グローバル システム オブジェクトへのアクセスを監査する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>バックアップと復元の特権の使用を監査する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ログオン時間を経過した場合は自動的にユーザーをログオフする</em></td>
<td style="border:1px solid black;">(スタンドアロンの Professional、Server、または Advanced Server ではこのオプションは利用不可)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">無効</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ログオン時間が時間切れになった場合、自動的にユーザーをログオフする (ローカル)</em></td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>システムのシャットダウン時に仮想メモリのページ ファイルをクリアする</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>常にクライアント側の通信にデジタル署名を行う</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>可能な場合、クライアントの通信にデジタル署名を行う</em></td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>常にサーバーの通信にデジタル署名を行う</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>可能な場合、サーバーの通信にデジタル署名を行う</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ログオンに Ctrl+Alt+Del を必要としない</em></td>
<td style="border:1px solid black;">未定義 (Professional のみ)
無効 (Server/Adv. Server のみ)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ログオン画面に最後のユーザー名を表示しない</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>LAN Manager 認証レベル</em></td>
<td style="border:1px solid black;">LM &amp; NTLM 応答の送信</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ログオン時のユーザーへのメッセージのテキスト</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>ログオン時のユーザーへのメッセージのタイトル</em></td>
<td style="border:1px solid black;">(空)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ドメイン コントローラが利用できない場合に使用する、前回ログオンのキャッシュ数</em></td>
<td style="border:1px solid black;">10 ログオン</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>コンピュータ アカウント パスワードのシステム保守をしない</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>ユーザーがプリンタ ドライバをインストールできないようにする</em></td>
<td style="border:1px solid black;">無効 (Professional のみ)
有効 (Server/Adv. Server のみ)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>パスワードが無効になる前にユーザーに変更を促す</em></td>
<td style="border:1px solid black;">14 日</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>回復コンソール: 自動管理ログオンを許可する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>回復コンソール: すべてのドライブとフォルダに、フロッピーのコピーとアクセスを許可する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>Administrator アカウント名の変更</em></td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>Guest アカウント名の変更</em></td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>CD-ROM へのアクセスを、ローカル ログオン ユーザーだけに制限する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>フロッピーへのアクセスを、ローカル ログオン ユーザーだけに制限する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>セキュリティで保護されたチャネル: 常にセキュリティ チャネルのデータをデジタル的に暗号化または署名する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>セキュリティで保護されたチャネル: 可能な場合、セキュリティ チャネルのデータをデジタル的に暗号化または署名する</em></td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>セキュリティで保護されたチャネル: 可能な場合、セキュリティ チャネルのデータをデジタル的に署名する</em></td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>セキュリティで保護されたチャネル: 強力な (Windows 2000 かそれ以降のバージョン) セッション キーを必要とする</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>システム パーティションの保護 (RISC プラットフォームのみ)</em></td>
<td style="border:1px solid black;">(スタンドアロンの Professional、Server、または Advanced Server ではこのオプションは利用不可)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>サード パーティ製の SMB サーバーへ接続するためのパスワードを、暗号化しないで送信する</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>セキュリティ監査のログを記録できない場合は直ちにシステムをシャットダウンする</em></td>
<td style="border:1px solid black;">無効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>スマート カード取り出し時の動作</em></td>
<td style="border:1px solid black;">無動作</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>グローバル システム オブジェクトの既定のアクセス許可を強化する (例: シンボリック リンク)</em></td>
<td style="border:1px solid black;">有効</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>署名されていないドライバのインストール時の動作</em></td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>署名されていないドライバ以外のインストール時の動作</em></td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">イベント ログ</td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>イベント ログの設定</strong></td>
<td style="border:1px solid black;"><strong>イベント ビューアにおけるログ プロパティの設定</strong></td>
<td style="border:1px solid black;"> </td>
<td style="border:1px solid black;"> </td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>アプリケーション ログの最大サイズ</em></td>
<td style="border:1px solid black;">512 Kb</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>セキュリティ ログの最大サイズ</em></td>
<td style="border:1px solid black;">512 Kb</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>システム ログの最大サイズ</em></td>
<td style="border:1px solid black;">512 Kb</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>アプリケーション ログのゲスト アクセスの制限</em></td>
<td style="border:1px solid black;">(利用不可)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>セキュリティ ログのゲスト アクセスの制限</em></td>
<td style="border:1px solid black;">(利用不可)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>システム ログのゲスト アクセスの制限</em></td>
<td style="border:1px solid black;">(利用不可)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>アプリケーション ログの保存日数</em></td>
<td style="border:1px solid black;">7 日を超えたイベントを上書きする</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>セキュリティ ログの保存日数</em></td>
<td style="border:1px solid black;">7 日を超えたイベントを上書きする</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>システム ログの保存日数</em></td>
<td style="border:1px solid black;">7 日を超えたイベントを上書きする</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>アプリケーション ログの保存方法</em></td>
<td style="border:1px solid black;">7 日を超えたイベントを上書きする</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>セキュリティ ログの保存方法</em></td>
<td style="border:1px solid black;">7 日を超えたイベントを上書きする</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><em>システム ログの保存方法</em></td>
<td style="border:1px solid black;">7 日を超えたイベントを上書きする</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><em>セキュリティの監査ログがいっぱいになったら、コンピュータをシャットダウンする</em></td>
<td style="border:1px solid black;">(利用不可)</td>
<td style="border:1px solid black;">未定義</td>
<td style="border:1px solid black;">未定義</td>
</tr>
</tbody>
</table>
  
[](#mainsection)[ページのトップへ](#mainsection)
  
##### 目次
  
-   [第 1 章 ‐ ハードウェアおよびソフトウェアの環境](https://technet.microsoft.com/ja-jp/library/da7603d8-d1d7-400a-9993-3ac61d633e66(v=TechNet.10))  
-   [第 2 章 ‐ オペレーティング システムのインストール](https://technet.microsoft.com/ja-jp/library/ddb614e6-9456-4f76-8dea-4018a51a810d(v=TechNet.10))  
-   [第 3 章 ‐ セキュリティで保護された構成](https://technet.microsoft.com/ja-jp/library/95fe8ebd-7386-4e95-aff8-5fca17435788(v=TechNet.10))  
-   [第 4 章 ‐ Windows 2000 Common Criteria (共通基準) セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/270098dc-f10b-41de-b26a-c2d795bca536(v=TechNet.10))  
-   [参考資料](https://technet.microsoft.com/ja-jp/library/6df170a9-3e6d-42d6-a4c3-0fd3eb71bf77(v=TechNet.10))  
-   付録 A ‐ Windows 2000 既定のセキュリティ ポリシーの設定  
-   [付録 B ‐ 監査カテゴリとイベント](https://technet.microsoft.com/ja-jp/library/0fc077e8-8bf5-4b4d-a555-a8c26c9792f0(v=TechNet.10))  
-   [付録 C ‐ ユーザー権利と特権](https://technet.microsoft.com/ja-jp/library/9d7407aa-87b7-4564-9659-3e99abe3ac6c(v=TechNet.10))  
-   [付録 D ‐ ユーザー アカウントとグループ アカウント](https://technet.microsoft.com/ja-jp/library/50b1a83f-d25a-4ffe-b601-3adc677fa632(v=TechNet.10))  
-   [付録 E ‐ 評価された構成のための Windows 2000 セキュリティ構成チェック リスト](https://technet.microsoft.com/ja-jp/library/b1327283-7a58-409a-9554-59e4bbc01374(v=TechNet.10))  
-   [付録 F ‐ 評価された構成のための Windows 2000 セキュリティ構成テンプレート](https://technet.microsoft.com/ja-jp/library/8842dd66-853c-4c8f-bb69-ae750f139356(v=TechNet.10))
  
[](#mainsection)[ページのトップへ](#mainsection)
