---
theme　: "black"
transition　: "default"
customTheme : "my-style"
title : "A hidden trap in DNS"
---
## A hidden trap in DNS
DNSに潜む罠  

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

DNSについてあまり詳しくなったので、ネット上で評判の良かった本を読んでみました。  

---

Here is the book I read.  

その本が、これです。  

<img src="./assets/001.png" style="max-width: 60%; max-height: 500px;">  
https://mochikoastech.booth.pm/items/812516  

---

This was good.  

---

Thanks to this book, I got basic knowledge of DNS.  

この本のおかげで、私はDNSの基礎を理解する事ができました。  

---

But, today I am not going to explain how DNS works.  

しかし、私がこのスライドで取りあげたいのは、DNSの技術についてではありません。  

---

I want to pick up a hidden trap of in this book.  

この本に書かれていた、ある「トラップ」についてです。  

---

We normally name variables and functions randomly such as 'a', 'test', and 'xxx'.  

変数名や関数名に、適当な名前の例として "a", "test", "xxx" といった名称を使う事はよくありますが  

---

But, These names are not allowed in DNS.  

DNS の世界では、それは許されていません。  

---

Bucause, there is high possibility of that your random domain name is already taken.  

なぜなら、そのドメインの所有者が存在する可能性があるからです。  

---

For example, test.co.jp is taken by Kyoikuhyokakenkyujyo.  

例えば、test.co.jp  というドメインは、  
有限会社教育評価研究所という会社のウェブサイトです。  

---

And 'aaa.com' is already taken by the American Automobile Association.  

同様に、aaa.com は、American Automobile Association のウェブサイトです。  

---

If you use domain name that is not yours, it cause some troubles.  

このように「自分の持ち物でないドメイン名」を勝手に使うのはトラブルの元となります。  

---

In fact, there are defined domain names which we can use freely on the internet.  

実はインターネットでは「例示やテストで使って いいドメイン名」というものが定められています。  

---

You can use following domain names for mail address of test user or when you write in form.   

テストユーザのメールアドレスや、 フォームで例として書くメールアドレスには次のドメイン名を使いましょう。  

* example.co.jp
* example.jp
* example.com
* example.net

---

These domains are will not taken by someone.  
You avoid sending email to a unexpected third person unintentionally.  

これらのドメイン名であれば将来的に誰かのものになる可能性もありません。  
予期せぬ第三者へうっかりメールが飛んでいってしまうことも避けられます。  

---

So, here goes the main part.  

そして、ここからが本題です。  

---

The author introduced those domains in the book.  
for example 'aaa.com', 'test.com', 'xxx.com'  

そして、この本では、取得済みのドメインの例として、"aaa.com", "test.co.jp", "xxx.com" が紹介されています。  

---

I became interested in these so I visited those websites.  

興味が湧いたので、それらのサイトを訪問してみました。  

---

But, one of domain had an unexpected hidden trap.  

その中の１つのドメインに、とんでもない罠が隠されていました。  

---

Unbelievably, **“xxx. com” is a hardcore adult web site!**  

何と、**"xxx. com" は、かなりドギツめのアダルトサイトだったのです！**  

---

When I checked the site, I was in the office, so I closed this page quickly.  

そのサイトを見ていたとき、私はオフィスにいたので、超速でブラウザを閉じました。  

---

Maybe, nobody noticed this accident.  
When you visite unknown domains, be careful enough.  

多分、誰にも見られてなかったと思います。  
皆様も、正体不明のドメインを踏む時は、注意してください。  

---

Also, If the domain that you proposed as example in the formal meeting is actual existing adult website, you might feel embarrassed.

また、「例として適当に挙げたドメインが、実在するアダルトサイトだった」となってしまったら、オフィシャルな場面では、笑うに笑えません。  

---

Be careful with domain names.

ドメインの取り扱いには注意しましょう。  

---

So, I tweeted this accident.  

そして、この事件を私は Twitter で呟きました。  

---

Then the auther of the book replied me.  

すると、本の作者からリプライをもらえました。

---

<img src="./assets/002.png" style="max-width: 60%; max-height: 500px;">  

<a href="https://twitter.com/kakisoft_tab/status/1157635487340752898">https://twitter.com/kakisoft_tab/status/1157635487340752898</a>

---

She said "I', sorry about xxx/.com"  

『xxx/.com の件は、なんというかスマン。。』  

---

## COOOOOOL!  
She is a great engineer!  

---

Furthermore, as of December 2020, 
you can't access xxx.com.

You can visite without any problems even if you are in office.

なお、2020年 12月の時点では、xxx.com はアクセスできないようです。  
あなたがオフィスにいる時でも、安心して訪れてみてください。  

---

<small>However, in the moment you visite the website, it might be revived.</small>  

<small>ただし、あなたがアクセスしたその瞬間には、生き返っているかもしれません。</small>

---

fin.
