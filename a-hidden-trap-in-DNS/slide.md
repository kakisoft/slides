---
theme　: "black"
transition　: "default"
customTheme : "my-style"
title : "A hidden trap in DNS"
---
## A hidden trap in DNS

<br>
<br>
<br>
<br>
kakisoft
<br>
&nbsp;&nbsp;<img src="../assets/kakisoft_log
.png" style="max-width: 10%;">

---

## about me

&nbsp;  |  &nbsp;
-------------|---------------
name       | Satoru Kakinohana &nbsp;&nbsp;&nbsp;<small><a href="https://kakisoft-portfolio-v2.netlify.com/">portfolio</a></small>
job        | Software Engineers<br><small>Specifically Logistics.<br>PHP/JavaScript/AWS etc...</small>  
hobby      | escape room<small>( It is called "リアル脱出ゲーム" in Japan )</small>  
<small>Twitte account</small> | <small>[@kakisoft_tab](https://twitter.com/kakisoft_tab)</small>

<br>

<small>
cf. escape room is really exciting entertainment.  
You use deductive skill and inspiration and team work, then solve challenging puzzles.</small>

---

I wasn't sure about DNS, so I read the book had good reviews on the internet.  
私は、DNSについてあまり詳しくなったので、評判の良かったこの本を読んでみました。  

---

I read book is it  
その本が、これです。  

---

This book is good.  

---

この本のおかげで、私はDNSの基礎を理解する事ができました。  
next, I will explain technical contents of this book.  

---

しかし、私がこのスライドで取りあげたいのは、DNSの技術についてではありません。  
But, My main topic is not DNS  

---

この本に書かれていた、ある「トラップ」についてです。  
But this book has a hidden trap.  

---

We normally name variables and functions randomly such as 'a', 'test', and 'xxx'.  
変数名や関数名に、適当な名前の例として "a", "test", "xxx" といった名称を使う事はよくありますが  

---

But, These names are not allowed in DNS.  
DNS の世界では、それは許されていません。  

---

なぜなら、そのドメインの所有者が存在する可能性があるからです。  

---

例えば、  
http://test.co.jp/  
は、  
有限会社教育評価研究所という会社のウェブサイトです。  

---

同様に、  
aaa.com は、  

'aaa.com' is already taken by the American Automobile Association.  

---

このように「自分の持ち物でないドメイン名」を勝手に使うのはトラブルの元となります。

---

実はインターネットでは「例示やテストで使って いいドメイン名」というものが定められています。  
テストユーザのメールアドレスや、 フォームで例として書くメールアドレスには次のドメイン名を使いましょう。  


* example.co.jp
* example.jp
* example.com
* example.net

これらのドメイン名であれば将来的に誰かのものになる可能性もありませんし、
予期せ ぬ第三者へうっかりメールが飛んでいってしまうことも避けられます。

これらのドメイン名であれば将来的に誰かのものになる可能性もありませんし、  
予期せ ぬ第三者へうっかりメールが飛んでいってしまうことも避けられます。  

---

The book introduce those domains. for example 
'aaa.com', 'test.com', 'xxx.com'

---

There is possibility that those random names are already taken by someone.  

The book introduce already taken domeins, for example  
'aaa.com', 'test.com', 'xxx.com'  

---

私は興味があったので、そのドメインを  
I interested in  
So, I visited these domain  

---

その中の１つのドメインに、とんでもない罠が隠されていました。  

---

何と、"xxx.com" は、かなりドギツめのアダルトサイトだったのです！

---

そのサイトを見ていたとき、私はオフィスにいたので、超速でブラウザを閉じました。

---

多分、誰にも見られてなかったと思います。  
皆様も、正体不明のドメインを踏む時は、注意してください。  

また、「例として適当に挙げたドメインが、アダルトサイトだった」となったら、オフィシャルな場では、笑うに笑えません。  

---

この事を、Twitter に書きました。

---

すると、本の作者からリプライをもらえました。

---

COOOOOOL!  
She is a great engineer!

---

fin.
