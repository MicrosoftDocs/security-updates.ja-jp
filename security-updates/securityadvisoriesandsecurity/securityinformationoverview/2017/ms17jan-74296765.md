---
TOCTitle: 'MS17-JAN'
Title: 2017 年 1 月のマイクロソフト セキュリティ情報の概要
ms:assetid: 'ms17-jan'
ms:contentKeyID: 74296765
ms:mtpsurl: 'https://technet.microsoft.com/ja-JP/library/ms17-jan(v=Security.10)'
---

2017 年 1 月のマイクロソフト セキュリティ情報の概要
===================================================

公開日: 2017 年 1 月 11 日 | 最終更新日: 2017 年 1 月 11 日

**バージョン:** 1.1

このセキュリティ情報の概要は 2017 年 1 月公開のセキュリティ情報の一覧です。

マイクロソフト セキュリティ情報の公開時に自動の通知を受け取る方法の詳細については、「[マイクロソフト テクニカル セキュリティ情報通知のご案内](http://go.microsoft.com/fwlink/?linkid=21163)」を参照してください。

また、マイクロソフトはお客様が月例のセキュリティ更新プログラムのリリースと同日に公開されるセキュリティ以外の更新プログラムとともに、月例のセキュリティ更新プログラムの優先順位を決定するときに役立つ情報も提供します。「**関連情報**」の欄を参照してください。

**注:** 2017 年 1 月の定例リリースに関して、Windows 8.1、Windows Server 2012 または Windows Server 2012 R2 のセキュリティ修正や品質改善はありません。よって、今月はこれらのプラットフォーム用のセキュリティのみの品質更新プログラム、またはセキュリティの月例の品質ロールアップは公開されません。

既にお知らせしたように、2017 年 2 月から、セキュリティ更新プログラムの情報は、セキュリティ情報サイトではなく、[セキュリティ更新プログラム ガイド](https://portal.msrc.microsoft.com/ja-jp/security-guidance)で公開されます。詳細については、ブログ記事「[セキュリティ更新プログラムに対するコミットメントの促進について](https://blogs.technet.microsoft.com/jpsecurity/2016/11/09/furthering-our-commitment-to-security-updates/)」を参照してください。

概要
----

<span id="sectionToggle0"></span>
次の表では、今月のセキュリティ情報を深刻度順にまとめています。

影響を受けるソフトウェアの詳細については、次の「**影響を受けるソフトウェア**」のセクションを参照してください。

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><strong>セキュリティ情報タイトルおよび概要</strong></td>
<td style="border:1px solid black;"><strong>最大深刻度<br />
と脆弱性の影響</strong></td>
<td style="border:1px solid black;"><strong>再起動の必要性</strong></td>
<td style="border:1px solid black;"><strong>既知の<br />
問題</strong></td>
<td style="border:1px solid black;"><strong>影響を受けるソフトウェア</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=838331">MS17-001</a></td>
<td style="border:1px solid black;"><strong>Microsoft Edge 用のセキュリティ更新プログラム (3214288)</strong><br />
このセキュリティ更新プログラムは、Microsoft Edge の脆弱性を解決します。この脆弱性が悪用された場合、ユーザーが Microsoft Edge を使用して特別に細工された Web ページを表示すると、特権の昇格が起こる可能性があります。攻撃者はこの脆弱性を悪用して影響を受けるバージョンの Microsoft Edge で特権を昇格する可能性があります。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
特権の昇格</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Microsoft Edge</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=838332">MS17-002</a></td>
<td style="border:1px solid black;"><strong>Microsoft Office 用のセキュリティ更新プログラム (3214291)<br />
</strong>このセキュリティ更新プログラムは、Microsoft Office の脆弱性を解決します。この脆弱性により、ユーザーが特別に細工された Microsoft Office ファイルを開いた場合にリモートでコードが実行される可能性があります。攻撃者がこの脆弱性を悪用した場合、現在のユーザーのコンテキストで任意のコードを実行する可能性があります。システムに対するユーザー権限が低く設定されているアカウントを使用しているユーザーは、管理者ユーザー権限で実行しているユーザーよりも影響が少なくなると考えられます。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">再起動が必要な場合あり</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office、<br />
Microsoft Office Services および Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=838351">MS17-003</a></td>
<td style="border:1px solid black;"><strong>Adobe Flash Player のセキュリティ更新プログラム (3214628)<br />
</strong>このセキュリティ更新プログラムは、すべてのサポートされているエディションの Windows 8.1、Windows Server 2012、Windows Server 2012 R2、Windows RT 8.1、Windows 10、および Windows Server 2016 にインストールすることで Adobe Flash Player の脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">緊急</a> <br />
リモートでコードが実行される</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows、<br />
Adobe Flash Player</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=838352">MS17-004</a></td>
<td style="border:1px solid black;"><strong>ローカル セキュリティ機関サブシステム サービス用のセキュリティ更新プログラム (3216771)<br />
</strong>ローカル セキュリティ機関サブシステム サービス (LSASS) が認証要求を処理する方法に、サービス拒否の脆弱性が存在します。攻撃者がこの脆弱性の悪用に成功した場合、標的のシステムの LSASS でサービス拒否が起こり、システムの自動的な再起動をトリガーする可能性があります。このセキュリティ更新プログラムは、LSASS が特別に細工された認証要求を処理する方法を変更することにより、この脆弱性を解決します。</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">重要</a> <br />
サービス拒否</td>
<td style="border:1px solid black;">要再起動</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Exploitability Index (悪用可能性指標)  
-------------------------------------
  
<span id="sectionToggle1"></span>
次の表は、今月解決した各脆弱性の Exploitability (悪用可能性) を提供します。脆弱性は、セキュリティ情報 ID、CVE 番号の順でリストされています。セキュリティ情報での深刻度評価が緊急または重要である脆弱性のみが含まれています。
  
**この表はどのように使用しますか?**
  
この表を使用して、お客様がインストールする必要のある各セキュリティ更新プログラムについて、セキュリティ情報の公開から 30 日以内にコード実行やサービス拒否などの悪用がなされる可能性を確認してください。今月の更新プログラムを適用する優先順位を決定するために、お客様の特定の構成に従って、下記の各評価を検討してください。これらの評価の意味の詳細については、「[Microsoft Exploitability Index (悪用可能性指標)](http://technet.microsoft.com/ja-jp/security/cc998259)」を参照してください。
  
下の表では、このセキュリティ情報の「影響を受けるソフトウェア」および「影響を受けないソフトウェア」の一覧のように、「最新のソフトウェアのリリース」は該当のソフトウェアを示し、「以前のソフトウェアのリリース」は、旧バージョンのすべてのサポートされている該当のソフトウェアのリリースを示しています。

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE 番号**

</td>
<td style="border:1px solid black;">
**脆弱性のタイトル**

</td>
<td style="border:1px solid black;">
**最新のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**過去のソフトウェア リリースでの  
悪用可能性評価**

</td>
<td style="border:1px solid black;">
**サービス拒否  
悪用可能性評価**

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-001: Microsoft Edge 用のセキュリティ更新プログラム (3214288)**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0002](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0002)

</td>
<td style="border:1px solid black;">
Microsoft Edge の特権の昇格の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-002: Microsoft Office 用のセキュリティ更新プログラム (3214291)**](https://go.microsoft.com/fwlink/?linkid=838332)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0003](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0003)

</td>
<td style="border:1px solid black;">
Microsoft Office のメモリ破損の脆弱性

</td>
<td style="border:1px solid black;">
1 - 悪用される可能性が高い

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-003: Adobe Flash Player のセキュリティ更新プログラム (3214628)**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB17-02](http://helpx.adobe.com/jp/security/products/flash-player/apsb17-02.html)

</td>
<td style="border:1px solid black;">
脆弱性の深刻度と更新プログラムの優先度の評価については、Adobe Security Bulletin [APSB17-02](http://helpx.adobe.com/jp/security/products/flash-player/apsb17-02.html) を参照してください。

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
---------

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS17-004: ローカル セキュリティ機関サブシステム サービス用のセキュリティ更新プログラム (3216771)**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2017-0004](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2017-0004)

</td>
<td style="border:1px solid black;">
ローカル セキュリティ機関サブシステム サービスのサービス拒否の脆弱性

</td>
<td style="border:1px solid black;">
4 - 影響されない

</td>
<td style="border:1px solid black;">
3 - 悪用される可能性は非常に低い

</td>
<td style="border:1px solid black;">
永続的

</td>
</tr>
</table>
 

影響を受けるソフトウェア
------------------------

<span id="sectionToggle2"></span>
次の表は、主要なソフトウェア カテゴリおよび深刻度の順にセキュリティ情報を示しています。

これらの表を使用して、インストールが必要なセキュリティ更新プログラムに関する情報を確認してください。記載されている各ソフトウェア プログラムまたはコンポーネントをご覧いただき、お客様の環境に該当するセキュリティ更新プログラムがあるかどうかを確認してください。ソフトウェア プログラムまたはコンポーネントが記載されている場合、ソフトウェア更新プログラムに関する脆弱性の深刻度も記載されています。

**注**: 1 つの脆弱性のために複数のセキュリティ更新プログラムをインストールする必要がある場合もあります。上記の各セキュリティ情報 ID の表全体をご覧になり、お使いのシステムにインストールしてあるプログラムまたはコンポーネントをもとに、インストールする必要がある更新プログラムを確認してください。

### Windows オペレーティング システムおよびコンポーネント

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista for Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista for Service Pack 2  
(3216775)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3216775)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(3216775)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(3216775)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for Itanium-based Systems Service Pack 2  
(3216775)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x32-bit Systems Service Pack 1  
(3212642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3212646)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x32-bit Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x32-bit Systems Service Pack 1  
(3212642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows 7 for x64-based Systems Service Pack 1  
(3212646)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack  
(3212642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(3212646)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3212642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for Itanium-based Systems Service Pack 1  
(3212646)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for 32-bit Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 for x64-based Systems  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 および Windows Server 2012 R2**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(警告)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT 8.1**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 10**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3210720)  
(緊急)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 for x64-based Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3210720)  
(緊急)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3210721)  
(緊急)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 for x64-based Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3210721)  
(緊急)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for 32-bit Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3211320)  
(緊急)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1607 for x64-based Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3211320)  
(緊急)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
[**緊急**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems

</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3211320)  
(警告)

</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3214628)  
(緊急)

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core インストール オプション**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-001**](https://go.microsoft.com/fwlink/?linkid=838331)

</td>
<td style="border:1px solid black;">
[**MS17-003**](https://go.microsoft.com/fwlink/?linkid=838351)

</td>
<td style="border:1px solid black;">
[**MS17-004**](https://go.microsoft.com/fwlink/?linkid=838352)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**警告**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
<td style="border:1px solid black;">
**なし**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for 32-bit Systems Service Pack 2 (Server Core インストール)  
(3216775)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 for x64-based Systems Service Pack 2 (Server Core インストール)  
(3216775)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack (Server Core インストール)  
(3212642)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 for x64-based Systems Service Pack 1 (Server Core インストール)  
(3212646)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
N対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
セキュリティのみ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core インストール)  
月例のロールアップ

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2016 for x64-based Systems  
(Server Core インストール)

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
<td style="border:1px solid black;">
対象外

</td>
</tr>
</table>
 
### Microsoft Office スイートおよびソフトウェア

 
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office 2016**

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**セキュリティ情報 ID**

</td>
<td style="border:1px solid black;">
[**MS17-002**](https://go.microsoft.com/fwlink/?linkid=838332)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
**総合的な深刻度**

</td>
<td style="border:1px solid black;">
[**重要**](http://go.microsoft.com/fwlink/?linkid=21140)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (32 ビット版)  
(3128057)  
(重要)

</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64 ビット版)

</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (64 ビット版)  
(3128057)  
(重要)

</td>
</tr>
</table>
 
### Microsoft Office Services および Web Apps

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Microsoft Office Services および Web Apps</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Office Services および Web Apps</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>セキュリティ情報 ID</strong></td>
<td style="border:1px solid black;"><a href="https://go.microsoft.com/fwlink/?linkid=838332"><strong>MS17-002</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>総合的な深刻度</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft SharePoint Enterprise Server 2016 64 ビット版</td>
<td style="border:1px solid black;">Microsoft SharePoint Foundation 2016 64 ビット版<br />
(3141486)<br />
(重要)</td>
</tr>
</tbody>
</table>
 

検出および展開ツールとガイダンス
--------------------------------

<span id="sectionToggle3"></span>
管理者がセキュリティ更新プログラムを展開するときに役立つリソースがいくつかあります。

Microsoft Baseline Security Analyzer (MBSA) を使用して、管理者はローカル システムとリモート システムの不足しているセキュリティ更新プログラムと一般的な誤ったセキュリティ構成をスキャンできます。

Windows Server Update Services (WSUS)、Systems Management Server (SMS)、および System Center Configuration Manager は、管理者がセキュリティ更新プログラムを配布するときに役に立ちます。

Application Compatibility Toolkit に含まれている Update Compatibility Evaluator コンポーネントは、インストールされているアプリケーションに対する Windows の更新プログラムのテストおよび検証を効率化する手助けをします。

利用可能なこれらのツールと他のツールの詳細については、「[IT 管理者向けセキュリティ ツール](http://technet.microsoft.com/ja-jp/security/cc297183)」を参照してください。

謝辞
----

<span id="sectionToggle4"></span>
マイクロソフトでは、マイクロソフトが責任を負う脆弱性の公開によるお客様の保護に際して、セキュリティ コミュニティの方々からいただいたご助力に感謝いたします。詳細については、[謝辞](https://technet.microsoft.com/ja-jp/library/security/mt745121.aspx)を参照してください。

関連情報
--------

<span id="sectionToggle5"></span>
### Microsoft Windows 悪意のあるソフトウェアの削除ツール

毎月第 2 火曜日 (米国時間) に公開されるセキュリティ情報で、マイクロソフトは Windows Update、Microsoft Update、Windows Server Update Services およびダウンロード センターで Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンをリリースしています。Microsoft Windows 悪意のあるソフトウェアの削除ツールの更新バージョンは、定例外のセキュリティ情報では提供されません。

### MU、WU、および WSUS でのセキュリティ以外の更新プログラム

Windows Update および Microsoft Update でのセキュリティ以外の更新プログラムについては、次を参照してください。

-   [マイクロソフト サポート技術情報 894199](https://support.microsoft.com/ja-jp/kb/894199): Software Update Services および Windows Server Update Services におけるコンテンツの変更について。すべての Windows コンテンツが含まれます。
-   [Updates from Past Months for Windows Server Update Services](http://technet.microsoft.com/ja-jp/wsus/bb456965) (英語情報)。Windows 以外の Microsoft 製品についてのすべての新着、更新および再リリースした更新プログラムを表示します。

### Microsoft Active Protections Program (MAPP)

お客様のセキュリティ保護をより向上させるために、マイクロソフトは、月例のセキュリティ更新プログラムの公開に先立ち、脆弱性情報を主要なセキュリティ ソフトウェア プロバイダーに提供しています。セキュリティ ソフトウェア プロバイダーは、この脆弱性の情報を使用し、ウイルス対策、ネットワーク ベースの侵入検出システムまたはホスト ベースの侵入防止システムを介して、お客様に最新の保護環境を提供します。このような保護環境を提供するセキュリティ ソフトウェア ベンダーの情報については、[Microsoft Active Protections Program (MAPP) パートナー](http://go.microsoft.com/fwlink/?linkid=215201)に記載されている各社の Web サイトを参照してください。

### セキュリティの計画とコミュニティ

**更新プログラムの管理の計画**

[Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) (英語情報) では、セキュリティ更新プログラムの適用についてのマイクロソフトの推奨策に関する情報を提供しています。

**他のセキュリティ更新プログラムの入手先:**

他のセキュリティ問題を解決する更新プログラムは以下のサイトから入手できます。

-   セキュリティ更新プログラムは、[Microsoft ダウンロード センター](http://go.microsoft.com/fwlink/?linkid=21129)からダウンロードできます。「security update」のキーワード検索によって容易に見つけることができます。
-   コンシューマー プラットフォーム用の更新プログラムは、[Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) からダウンロードできます。
-   今月の Windows Update で提供されているセキュリティ更新プログラム、セキュリティおよび緊急のリリースの ISO CD イメージを Microsoft ダウンロード センターから入手することができます。詳細については、[マイクロソフト サポート技術情報 913086](https://support.microsoft.com/ja-jp/kb/913086) を参照してください。

**IT プロフェッショナル セキュリティ コミュニティ**

セキュリティの強化および IT インフラストラクチャの最適化について学び、セキュリティ関連のトピックについて他の IT プロフェッショナルとの情報交換を行うには、[IT プロフェッショナル セキュリティ コミュニティ](http://go.microsoft.com/fwlink/?linkid=21164)にアクセスしてください。

### サポート

ここに記載されているソフトウェアをテストし、影響を受けるバージョンを確認しました。その他のバージョンについてはサポート ライフサイクルが終了しています。ご使用中のソフトウェアのバージョンのサポート ライフサイクルを確認するには、[Microsoft サポート ライフサイクル](http://go.microsoft.com/fwlink/?linkid=21742)の Web サイトを参照してください。

IT プロフェッショナル向けのセキュリティ ソリューション: [TechNet セキュリティに関するトラブルシューティングとサポート](http://technet.microsoft.com/ja-jp/security/bb980617)

Windows を実行しているコンピューターのウイルスおよびマルウェアからの保護のヘルプ: [ウイルスとセキュリティ サポート ページ](http://support.microsoft.com/ja-jp/contactus/cu_sc_virsec_master)

国ごとのローカル サポート: [インターナショナル サポート](http://support.microsoft.com/ja-jp/common/international.aspx)

### 免責

マイクロソフト サポート技術情報に含まれている情報は、いかなる保証もない現状ベースで提供されるものです。Microsoft Corporation およびその関連会社は、市場性および特定の目的への適合性を含めて、明示的にも黙示的にも、一切の保証をいたしません。Microsoft Corporation、その関連会社およびこれらの者の供給者は、直接的、間接的、偶発的、結果的損害、逸失利益、懲罰的損害、または特別損害を含むすべての損害に対して、状況のいかんを問わず一切責任を負いません。結果的損害または偶発的損害に対する責任の免除または制限を認めていない地域においては、上記制限が適用されない場合があります。

### 更新履歴

-   V1.0 (2017/01/11): このセキュリティ情報の概要ページを公開しました。
-   V1.1 (2017/01/11): このセキュリティ情報の概要を更新し、CVE-2017-0003 の深刻度を重要に変更しました。これは情報のみの変更です。

*Page generated 2017-02-06 10:33-08:00.*
