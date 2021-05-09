私は、ソフトウェアアンジニアで、特に物流のシステムについて、数多く関わってきました。
I'm software engineer. Especially, I created many logistic systems.

在庫管理のシステムであれば、立ち上げから運用保守まで、一通りの経験があります。
I have experiences in launch and stabilization of warehouse management systems.

なので、私は、ソフトウェアエンジニアであるけでなく、物流のプロでもあります。
So, I'm a software engineer and also logistics specialist.

このプレゼンは、それらの知見を元にした資料となっております。
This presentation is based on my expertise in logistics.

________________________________________________________________________________
（没）

エンジニアとしてだけではなく、物流の仕事をする人間として、長年携わってきました。  
I have been working not only as an engineer but also as a logistic worker.   

________________________________________________________________________________
ただ、ここで話す内容は、あくまでスライド主が  
経験した範囲のもので、物流業界全体が  
そうだという事を保証するものではありません。  


First of all, this presentation doesn't explain all logistics field.
It's case by case.



まず、物流の基本である、６大機能について説明します。
First, I will explain 6 main categories	in logistics.



このスライドで話をするのは、このうちの、この２つです。
This presentation explains two out of all categories.


two out of -> 〜の中の
two out of all categories.　カテゴリの中の２つ


I will talk about warehouse management system.



Warehouse management system has these functions.
as follows:



入荷


入荷とは、仕入先から商品を倉庫に入れるプロセスの事です。


Arrival is the process of putting goods from a supplier into a warehouse.


Inbound is the process of storing items to the warehouse from supplier.



Most case of system is not so complex.

It is not became so complex.


複雑化する事は、あまり多くない。  
It doesn't become so complex in many cases.


And if the system launch and run suitable, 
this function 


You almost don't have to change and add functions 



初級または中級のエンジニアをアサインしても

You can assign junior and middle level engineers to  the tasks.



high
intermediate
low



resources that is required

割くリソース：中
resources required : intermediate

---------------------------------------------
【 出荷 】


Shipment is the process of bring out some items from warehouses to customers.



It tends to be complex.


また、外的要因により、システムの改修が必要となる事も多い。
（余儀なく、システムを変えなければならないケースも多い）

And, sometimes we have to adjust the system because of the clients' circumstances.



Even if you launch the system, it is common you have to modify the system's' function.


（あなたがマネージャーなら）
エースはこの機能を担当させるべきです
You should assign the ace to this function
assign O to O2
the ace

resources required : high

---------------------------------------------
【 棚卸 】

Stock taking is the process of chekiang number of items in warehouses.

Actually, 

You can go well   without create own(専用の) functions
the process


きっちりシステム化せずとも、  
何とかなるケースも多い。  

(あなたは、その機能を時間をかけて作り込まなくとも、
現場が運用できるパターンは多い。)
You can manage the work at the warehouse even if you don't spend time to create the function.

"even if"
"spend time" がメインの動詞

通常、棚卸しには、ハンディーターミナルを使用します。
Normally, You use handy terminal when you do Stock taking.

しかし、扱う商品によっては、ハンディターミナルで在庫を１つ１つ読み込ませる作業が現実的でないケースがあります。


But, there are cases when it is not realistic to read barcode of each item in a warehouse.


X each items -> ○ each item



その場合は、帳票を見ながら、目視で確認します。
In that case, you check the inventory with your eyes.


In that case, you visually check the inventory by looking while look some statement.


In that case, you visually check the inventory while you look at some lists.



by  〜によって




システム的な作業は、  
事務所内だけで完結させる事も多い。  

-- Normally, You use handy terminal when you do Stock taking.

In many cases, you can finish only office work.

In many cases, you can finish only office work.

「倉庫内で機器を使った作業」無しで、完結させる事も多い


In many cases, you can finish the work without working with devices in a warehouse.
In many cases, you can finish the work without working on site.

on site



resources required : low


---------------------------------------------
 * 入荷
 * 出荷
 * 棚卸
 * データ交換
 * 請求・支払



入荷データ・出荷データ・棚卸データ  
といった電子データを、ベンダーやサードパーティと  
やり取りする業務。
Data exchange is the process which exchanges electronic data with other companies.
For example ASN data, shipping instruction data, and stock taking data.


重要なのは、交渉力と政治力。  
このプロセスにおいて、最も重要なのは、交渉力と政治力です。
The most important in this process are negotiation skill and political skill.
The most important thing/point in this process are negotiation skill and political power.
The most important point in this process are negotiation skill and political skill.


The most important points in this process are negotiation skill and political skill.



相手が一方的に有利な条件を呑んでしまうと、自社の仕事が極端に増えてしまう事があります。

If you accept client offer directly, your company's work will xxx increase.


accept A without questioning  -> 鵜呑みにする

↓
If you accept clients' offer without question, your company's work will drastically increase.


そうならないために、マネージャーには確かな交渉力が求められます。

outcome  -> 仕事の成果

If you want to avoid these outcome, project manager is required negotiation skill.

↓正解
If you want to avoid these outcome, project manager is required to have negotiation skill.



システム的に重要なのは、スピードよりも正確性。  

この機能を開発する時、重要なのは、開発速度よりも、正確性です。
↓正解
When you create this function, Accuracy is more important than development speed.


「粗いが早い」エンジニアより、  
「じっくり作ってバグが少ない」エンジニアの方が  
この工程に向いてます。  

あなたは、「素早く作れるが荒が目立つ」タイプのエンジニアでなく、
「じっくり作り、バグが少ない」タイプのエンジニアを、この工程にアサインするべきです。

You should assign the engineer that 



A is more suitable for this process than B

An engineer who makes it carefully and has few bugs is more suitable for this process than An engineer who can make it quickly but has a noticeable roughness.

An engineer who makes it carefully and has few bugs is more suitable for this process than a careless engineer who can make it quickly.

↓丸
A careful engineer who has few bugs is more suitable for this process than a careless engineer who can make it quickly.



unreliable



resources required : intermediate to high

---------------------------------------------
【 請求・支払 】

requirement and payment
bill and payment
request and payment



単純化できないなら、
システムでカバーしない方がいい。

↓正解
If you can't simplify it, you shouldn't add this function.
incorporate

↓正解
In many cases, you have to create really complex calculation program.


時には、会計の知識が必要になります。
In some cases, you are required to have knowledge of accounting.

In some cases, knowledge of accounting is required.



時には、妙なローカルルールに盛大に振り回されりする事もあります。
In some cases, you are swayed by strange local rules.



重症化すると、物流のシステム作ってるのか会計のシステム作ってるのか、分からなくなるレベルに達します。

そのルールが複雑すぎると、あなたは物流のシステムを作っていると言うよりも、会計のシステムを作っているかのように思えてしまいます。

If this rule is too complex, you feel you are creating account system, rather than logistic system.


加えて、計算ルールがベンダーごとに違っていたり、
ルールがコロコロ変わる事も珍しくありません。


ベンダーは、それぞれの計算ルールを持っている事も珍しくありません。


In addition, Some customer have own calculation rules.
そして、そのルールは、時々変わることがあります。
And, sometimes these customer change the rules.


それらのルール変更に追従していくのは、とても大変です。
It is hard task 

あなたが、そのルールに追従していくには、とても大変な労力を必要とするでしょう。
If you catch up the rules, you are required heavy effort.
 -> ボツ


It is hard to catch up with the rules.

時には、大幅にシステムを変えなければならない場面が出てきます。
Some cases, you have to change the calculation logic drastically.



また、  
『割高になるけど   
計算がシンプルで事務作業が軽減される』
という計算方法より、  
『計算が複雑怪奇でも、  
安くできる（可能性がある）』
計算の方が好まるケースもあります。




『計算が複雑でも、安くできる（可能性がある）』計算方法の方が、
『割高になるけど、計算がシンプルで事務作業が軽減される』計算方法よりも、
好まれるケースがあります。



""
complex calculation method


"complex and may be cheep calculation method with more office work"
"complex calculation method with more office work"




"complex calculation method with more office work which may be cheap depending on patten"
"simple and relatively expensive calculation method with less office work"


depend on 動詞
depending on 名詞（depending on ）
https://ameblo.jp/english-teacher-yohei/entry-12435763186.html


In some cases, 
"complex calculation method with more office work which may be cheap depending on patten"
is prefered to
"simple and relatively expensive calculation method with less office work"




そういった場合、
「請求と支払の計算に必要な帳票は出せるように  
　しているから、計算はそっちでやってね♪」  
という方向に持っていくのが理想です。  
In this case, you should lead the customers to calculate on their own.


ただし、様々な事情があり、そうでけいないケースは多いかと思います。
But, It often doesn't work well according to your ideal.


そんな感じで、発生した課題に対し、  
技術のみで解決しない方法が、  
ベターな選択となる事も多いです。

あなたは、顧客の課題の解決に、技術のみを使うべきではない場面があります。


As discussed, 
for some cases you shouldn't use only techlogy when you solove the customers problem.



最後に、システムを導入するときについて、話をしたいと思います。
lastly, I want to speak about when you launch WMS system.

There are many varieties of sites in logistic industory.



自前で保有しているシステムが、  
「現場の運用にマッチしない」  
といった事は多々あります。

So, If you have own systems,
it is not suitable in warehouses in some cases.



そんな時、あなたが取る選択肢は、次の２つのうち、どちらかです。
If you encount such sutiation, you have to choise these options.

あたたは、この２つのうちの、どちらかを選択する事になるでしょう。
If you encounter such sutiation, you will choose one of these options.




 1. 業務に合わせてシステムを変える
Change the systems to suit the work style.


 2. システムに合わせて現場の運用を変えてもらう
Change work style to suit the systems.



-  1. 業務に合わせてシステムを変える

導入がスムーズに行きやすい。  
こっちで進めてほしいと言われる事が多い。  

It is easier than another case.
Many customers request this style.



ただ、システムが１点ものになったり、  
一部の機能が、完全に特定のユーザ向けに  
なる事が多い。  

結果、システムが煩雑になりやすい。



ただし、そうしてしまうと、
システムが、ある顧客に特化した機能を持つ事になります。
But, if you accept the request, 
the system will have the specific function for indivisual customer.

その結果、システムが煩雑になります。
As a result, the system will be complex.


-- ２．システムに合わせて現場の運用を変えてもらう
だいたい嫌がられる。  
調整に時間を要する事も多い。  

Many customers are not willing to accept your suggestion.
You can spend long time to persuade them.


また、政治的に優位な立ち位置でなければ、  
この方法が実践できないケースも多い。
And also, if your company don't have political power, you often can't do this method.


ただ、ビジネス的に大きな成功を  
おさめるなら、こっちだと思います。  
But, if you want to get a big success in business, you should do this method.


ただし、その道のりは、とても険しいものになると思います。
But, if you choose this way, you have to work hard.


どちらが正解というものはありません。
There is no wrong answer.

経営者もしくは責任者が、自身の判断で  
舵を切って行くしかないと思います。
CEO or manager have to decide which way to go, on their judgement.


現場は生き物で、状況も刻々と変わって行ってます。  
物流の現場は様々です。
There are many varieties of methods depending on logistic site.
Situations change day by day.


限られたリソースの中で、何が提案できるのか、という事は重要です。
It is important to suggest what you can do with limited resources.



色々な技術が出てきているとはいえ、  
レガシーな仕組みで泥臭くやっている  
現場が多いのが実情です。
But, many logistic sites are working on old systems and mechanism.



未来を見据えた、華やかで革新的なテクノロジーが世の中を変えていく、という考えも大事ですが、
今現在、泥臭く動いている現場や、日々の業務に追われている方々に目を向けて、そこから改善のアプローチをしていく。

という考えも重要ではないかと思います。


未来を見据えた、華やかで革新的なテクノロジーが世の中を変えていく、という考えも大事ですが、
The idea that innovative technologies change the world is important.


The xxxxxx is important too.

xxxxxx

今現在、泥臭く動いている現場や、日々の業務に追われている方々に目を向けて、そこから改善のアプローチをしていく。

という考えも重要ではないかと思います。
But, it is important to fucus on current chaotic environment and the workers who are busy with their daily task.

そして、そこから改善のアプローチをしていく、という考えが重要ではないかと思います。



It is important to fucus on current chaotic environment and the workers who are busy with their daily task, and to explore more efficient method.




---------------------------------------------



うん、アレだ。
「技術文書は読んでてもそれほどツラくない」と感じていた理由が分かってクラっと来た。

単に「部分的に単語拾って、言っている事を何となく予測する（分からない部分は試しにコード書くなり実際に動かしてみるなりして試す）」







It is important to have accuracy rather than development speed.
It is important accuracy rather than development speed.



to have は基本、先頭にこないので、It を主語にして受ける

It を主語にして受けるには、それなりの理由が必要。（長さ、to 不定詞）


----------

オリンピックの報道とかされてる？
Is the Olympics reported about in your country?








この方法が有効ではないかと思います。
I guess the method is effective.



where you can go


====================================================================================
====================================================================================
====================================================================================


I’m software engineer. Especially, I created many logistic systems.
I’m a software engineer. Especially, I created many logistic systems.


I have experiences in launch and stabilization of warehouse management systems.
I have experiences in launching and stabilization of warehouse management systems.


So, I’m a software engineer and also logistics specialist.
So, I’m a software engineer and also a logistics specialist.



First, I will explain 6 main categories in logistics
To start with, I will explain 6 main categories in logistics.


They are
Transport and delivery
Storage
Packaging
Cargo handling
Distribution processing
and Data processing



This presentation explains two out of all categories
This presentation explains two of them



as follows:
They are as follows:



resources required
Resources required


intermediate
Intermediate


Shipment is the process of bring out some
Shipment is the process of bringing out some


the system’s’ 


chekiang
checking



In that case, you check the inventory by looking while look some statement.


In that case, you check the inventory by eye while looking some statement.


while の後は動名詞が多い



The most important points in this process are negotiation skill and political skill
The most important points in this process are negotiation skill and political skill


If you want to avoid these outcome
If you want to avoid these outcomes

When you create this function, Accuracy 
When you create this function, acuracy 

intermediate to high
Intermediate to high


In some cases, you are required to have knowledge of accounting.
You are often swayed by strange local rules.


If this rule is too complex, you feel you are creating account system
accounting system



In addition, Some customer
In addition, Some customers



Some cases, you have to change 
In some cases, you have to change 


In some cases,
“complex calculation method with more office work which may be cheap depending on patten”
-> sometimes, at times



As discussed, for some cases you shouldn’t use only techlogy

solove



WMS
Warehouse Management System



But, if you accept the request, the system will have the specific function for indivisual 



And also, if your company don’t
And also, if your company doesn't


But, if you choose this way, you have to work hard.
When you choose this way, you have to work hard.



It is important to fucus on current chaotic environment and the workers who are busy with their daily task, and to explore more efficient method
focus
