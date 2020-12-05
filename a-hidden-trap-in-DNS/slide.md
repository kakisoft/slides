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

私は、DNSについてあまり詳しくなったので、ネット上で評判の良かった本を読んでみました。  

---

This is the book that I read.  
<img src="./assets/001.png" style="max-width: 60%;">  
https://mochikoastech.booth.pm/items/812516  

その本が、これです。  

---

This is good.  

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

The domain names you ramdamly named are already someone has ohther.  

あなたが適当な例として挙げたドメイン名は、既に誰かが所有している可能性があります。  


---

For example, test.co.jp is taken by Kyoikuhyokakenkyujyo.  

例えば、test.co.jp  というドメインは、  
有限会社教育評価研究所という会社のウェブサイトです。  

---

And 'aaa.com' is already taken by the American Automobile Association.  
同様に、aaa.com は、American Automobile Association のウェブサイトです。  

---

If you use domain name that is not yours,it cause some troubles.
このように「自分の持ち物でないドメイン名」を勝手に使うのはトラブルの元となります。  

---

In fact, there are defined domain names which we can use freely on the internet  
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

The book introduce those domains. for example 
'aaa.com', 'test.com', 'xxx/.com'

そして、この本では、取得済みのドメインの例として、"aaa.com", "test.co.jp", "xxx/.com" が紹介されています。  

---

I interested in these domains.  
So, I visited.

興味が湧いたので、それらのサイトを訪問してみました。

---

その中の１つのドメインに、とんでもない罠が隠されていました。  

---

Surprisingly, **“xxx. com” is a hardcore adult web site!**  
何と、**"xxx.com" は、かなりドギツめのアダルトサイトだったのです！**  

---

When I saw the site, I was in the office, so I close this page quickly.  

そのサイトを見ていたとき、私はオフィスにいたので、超速でブラウザを閉じました。  

---

多分、誰にも見られてなかったと思います。  
皆様も、正体不明のドメインを踏む時は、注意してください。  

---

また、「例として適当に挙げたドメインが、実在するアダルトサイトだった」となってしまったら、オフィシャルな場面では、笑うに笑えません。  

ドメインの取り扱いには注意しましょう。  

---

そして、この事件を私は Twitter で呟きました。

---

すると、本の作者からリプライをもらえました。
<img src="./assets/002.png" style="max-width: 60%;">  
https://twitter.com/kakisoft_tab/status/1157635487340752898

---

She said ""
xxx/.com の件は、なんというかスマン。。

---

## COOOOOOL!  
She is a great engineer!

---

また、202X年 XX月 時点では、xxx/.com はアクセスできないようです。  
あなたがオフィスにいる時でも、安心して訪れてみてください。  

---

なお、2020年 12月の時点では、xxx.com はアクセスできないようです。  
公共の場でも、安心して訪れてください。

---

<small>ただし、アクセスした瞬間には生きている</small>

---

fin.