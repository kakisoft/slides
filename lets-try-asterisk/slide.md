---
theme : "serif"
transition: "slide"
slideNumber: false
customTheme : "my-style"
title: "【倉庫内無線LAN環境】アンドロイド端末で無料通話をしてみよう"
---
### 【倉庫内無線LAN環境】<br>アンドロイド端末で無料通話をしてみよう

<br>
<br>
<br>
<br>
kakisoft
<br>

&nbsp;&nbsp;<img src="../assets/kakisoft_logo
.png" style="max-width: 10%;">

---

### about me

&nbsp;  |  &nbsp;
-------------|---------------
名前       | 垣花　暁 &nbsp;&nbsp;&nbsp;<small>
仕事        | 物流系エンジニア<br><small>Laravel/React/AWS etc...</small>  
趣味      | リアル脱出ゲーム
ポートフォリオ | [kakisoft-portfolio](https://kakisoft-portfolio-v2.netlify.com)
Twitte | [@kakisoft_tab](https://twitter.com/kakisoft_tab)

---

某日、福岡と広島に、Androidタブレットを使った、  
ピッキング（出荷）と棚卸のシステムを  
導入しました。

---

しばらくして、こんな要望が。

---

現場「これ（Android端末）使って、  
通話もできない？」

---

(｀・ω・´)

---

調べてみた。

---

できそうな気がする。

---

### IP PBX
**（Intenet Protocol Private Branch eXchange）**
<br>

TCP/IP上で音声通話（VoIP）を利用する際、  
IP電話機の回線交換を行う機器やソフト。  
IP回線交換装置とも。

---

### PBXには２種類ある

 * ハードウェアタイプ  
   　⇒ 専用の機器を使用する

 * ソフトウェアタイプ  
   　⇒ サーバにインストールして使用する

<br><br>
**→今回必要なのは、ソフトウェアタイプ。**

---

**Asterisk（アスタリスク）** というオープンソースのツールを使用。  
内線電話を実現できるそうな。  

http://www.asterisk.org/  
<img src="./assets/Asterisk_overview.png"/>  
サーバにて使用します。Cent OSを使用しました。  

---

クライアント（今回は Android）には、「SIPクライアントツール」が必要となります。  
（「ソフトフォン」とも言います。）  
<br>

以下の３つを試しました。
 * Zoiper IAX SIP VOIP Softphone
 * CSipSimple
 * MizuDroid SIP Softphone

<br>
<br>
手軽にサクッと使う分には、MizuDroidが良さげです。

---

やり方

---

基本、Qiitaの記事を参考にし、うまく行かなかった部分は公式マニュアルを参考にする方法でOKでした。  
<br> 

この記事は特に参考になりました。  
【AWS上にAsteriskサーバ構築して内線電話環境つくってみよう】  
https://qiita.com/ganezasan/items/05b16a2254f066f6bbdc

---

Android端末同士の通話OK！  
(｀・ω・´)b

---

PC⇔PC  
でも、問題なく行けると思います。

---

使う場面は限定的かと思われますが、  
こういうのがある、という事を頭の片隅に置いてみてはどうでしょう。

---

本番環境への導入の予定は・・・

---

諸事情により、特にありません。  
(｀・ω・´)b

---

おわり
