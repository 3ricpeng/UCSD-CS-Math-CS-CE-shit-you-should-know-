# UCSD CS/Math-CS/CE shit you should know

- Table of Contents:

# | CS Major Requirements

This is what my degree looked like if i remembered it correctly: (CS26 - BS Computer Science Major) 

 **Lower Div 必修 (Lower Div Requirements) ⚠️**

CSE8A+8B or CSE11 ❌

CSE12+15L **⚠️**

CSE20+21 ✅

CSE30 **⚠️**

Probability/Stats Req: Math183/Math181A/Econ120/ECE109/CSE103 `//這個越早上越好` ✅

**Calc*3(Math20ABC)** + **Linear Algebra(Math18)** + **Science*2(any random class on that list)**

 **Upper Div 必修 (CSE Core)** 

**CSE100** Data Structure ✅

**CSE101** Algo ✅

**CSE105** Theory of Computability (fuck Turing) ✅

**CSE110** SWE ✅

**CSE120/123/124** Systems Req **⚠️**

**CSE130/132A** this makes no sense to me personally **⚠️**

**CSE15X/167** Learning Req **⚠️**

**CSE107/127** security req **⚠️**

**CSE140+140L** Digital Logic Design & Labs ✅

**CSE141 Series** or **CSE142 Series** ✅

→ Total: 8 Courses 

 **Upper Div 選修** ✅

Elective * 5 

Tech Elective * 2

→ Total: 7 Course 

<aside>
💡 ✅ 是我有寫心得/推薦教授之類的課
**⚠️** 是上過了但還沒有時間寫內容的，之後會逐漸補上
❌ 沒上過/太久/忘了/懶得寫了，想問教授或是內容的話自己私訊我吧，或歡迎勇者補充

</aside>

# | Classes to Take

下面列出幾點針對大二以上declair完Major的人選課的事, 還有要怎麼挑教授之類的，都是我自己的經驗啦所以超subjective的

- **CSE20** → **CSE21** → **CSE101** & **CSE105** 彼此為pre req, 內容也滿相近 (風格很像, 都是algorithm, 用 $\LaTeX$ 寫proof之類的) 這幾堂數學感很重, you either love it or hate it but its low-key really important to build up foundations for leet-coding :)))
    - **CSE20 + CSE21:** Mile Jones跟Mia Minnes固定輪流教這幾堂,Mia偏簡單,兩個都算中規中矩不太難,網路上也有podcast可以看,裡面最重要的應該就是big O和一些sorting和一些proof methods,反正declare major需要這兩堂所以認真點好好讀吧🙂
    - **CSE101:** 中規中矩的Algo課,延續20&21的感覺有很多proofs/要寫,上之前建議複習21的一些東西,基本上只寫psudo code而已
        - 如果有Miles Jones 或 Mia Minnes 選他們吧。
        - Kane是個哈佛來的天才據說他教的版本都會有解不出來的題目,但想挑戰自我的話不錯。
        - Dasgupta自己寫了本書我覺得還不錯, 其他教授都用Algo 4th或是CLR來教, Dasgupta我沒上過但他書寫的還不錯 [link](http://algorithmics.lsi.upc.edu/docs/Dasgupta-Papadimitriou-Vazirani.pdf)
        - 其他就偶而會有數學系教授來教吧，暑課也幾乎都是，怕踩雷建議看CAPE再決定
        - 不錯的資源: Coursera 上 Stanford的Algo課大推,`geeksforgeeks`,`StackExchange` 喜歡看書的話讀課本吧:)))
    - **CSE105**: 這堂也是20+21的延續,很有數學課的既是感,中文叫正規語言/自動機 theory of computation
        - 如果有Miles Jones or Mia Minnes選他們吧。
        - 會有一些數學系教授跑來教，怕踩雷建議看CAPE再決定，這堂沒啥pre req但會需要一定的mathematical matruity不然看到一堆符號會反胃。
        - 不錯的資源:超推薦Michael Spicer教授寫的書,MIT OCW也有他本人的授課的版本但我覺得教的偏無聊,這堂課讀出心得的話恭喜你可以簽博班,grad 200系列可以繼續讓你走火入魔上下去,但我自己覺得滿沒用的啦可能我慧根不足吧。
        
- **CSE100 Data Structure**: 沒意外這幾年都會是Niema Moshiri或他的學生上, 中規中矩用C++寫data structure的課,11+12活過來的話會覺得100的PA都不難。課本應該固定是下面連結的Stepik線上課本,閒著沒事大概一個月可以自學完,裡面不知道為啥有一些比較冷門(面試/刷題少見)的String/Lexicon。其實這堂課的核心就是掌握C++ STL實踐一些樹啊 圖啊 哈希啊 隨便啦。這堂一上完**CSE30+CSE21**務必趕快開始，因為他是後面所有upper div的課程pre req
    
    沒寫過或很怕C/C++的話上之前可以稍微惡補一下,尤其從Java過來的人一開始會超崩潰(像我)
    
    [Data Structures](https://stepik.org/course/579/syllabus)
    

- **CSE110 Software Engineering**: Loading滿重的一堂project課,看你的程度/組員的智商/教授是誰決定你的GPA,基本上你有過internship或是自幹過任何project、知道怎麼用github、弄過pipeline、怎麼寫test這堂課就是一個看猴子耍把戲的狀態。但以上這些都沒經驗的話恭喜你這堂課會超花時間der。
    - 不要沒事挑戰自我去搞些有的沒的框架，一直重複告訴自己 組員都是智障 組員都是智障 能用Vanilla JavaScript寫出來的東西拜託不要自找麻煩，因為組員都是智障他們絕對不知道怎麼維護code
    - 如果你發現你不會維護code那你一定就是組上的那隻猴子，這堂課的Lab走很快，基本上是一週教一個前/後端技術然後六週之內要你生出一個網站/APP的狀態，反正結論就是多花一點額外的時間學，然後不要走火入魔，凡事學的點到為止能用就好
    - 以上這些都很有餘韻的話再專心去聽教授上課講什麼吧😊 通常都會講一些design pattern/業界小故事/good practice之類的，還會強迫用一些slack/asana/figma/miro/codacy之類的工具,總之他們很認真在simulate SWE工作現場但10週真的太短了，最後就會覺得一直在白忙然後開很多廢會(跟工作倒是滿像的啦)
        - Griswold/Powell 輪流教的樣子, 下學期Politz第一次上110說不定他會改良這堂課，良心教授怎麼能不選呢。
        - Powell會限制只能做網頁。
        - Griswold Scope比較廣可以做phone app但我也不確定，參考reddit吧。
    - 不錯的資源: 基本上你要是沒intern過這堂課一定所有東西都はじめまして，YouTube上的印度人是你好夥伴, `W3School`, `codecademy` 都很推，最後就是`stackoverflow`
    
- **CSE140+140L Digital Logic Design**: 中文叫啥數位邏輯設計之類的，是CS必修裡最偏底層最硬體的課(除非你想不開去上System CSE14X or CSE176E or 任何ECE的課)
    - Rosing 教的不錯的女教授，比較嚴格考試也略難，但整體而言學得到東西也比較coheisive
    - Orailoglu 自己去查reddit我不想破壞教授名聲:)
    - CK Cheng 很有台灣味的男人，他是ㄍ瑰寶:)
    - 不錯的資源: YouTube上隨便搜尋都有，交大王俊堯的數位邏輯設計教很好，System Verilog Crash Course 對140L 很有幫助
    - 延伸的資源: Coursera的 `from nand to tetris` 但用的HDL不一樣可能會造成你的誤解。
    
- **CSE141&L** or **CSE142&L Computer Architecture**: 計算機結構，這堂課可以想成CSE30的延伸，兩堂課擇一上就好，基本上會吃一點C語言的能力跟pointer，assembly language之類的30教的東西，如果30上得很痛苦的話這堂課風格很像。
    - 142是Leo Porter跟Steve Swanson改良141出來的版本，單純看課綱我覺得跟CMU的15213有點像，但實際的project難度低滿多的，只要不怕C都不太難
    - 參考書籍: CS:APP, [https://diveintosystems.org](https://diveintosystems.org/) 還有那本很常見的Organization 封面是個算盤的那本都不錯.
    - 延伸的資源: CMU 15213就不多說了自己研究,CSE30,**Neso Academy這個頻道CS Major的人都該知道**, 柏克萊的cs61C有一個公開版,
    

- **Math183** 一上完微積分就趕快拿，Statistics解鎖之後能夠開啟一大片AI/ML/NLP/RL的課，(CSE150AB/151AB/156/158系列全部...)
    - Quartfoot 教很好但作業極多(2 hw per week)，很喜歡數學的人歡迎挑戰，他的課都有上podcast所以如果選其他比較簡單的教授可以拿他的podcast來看+slides都在他官網上
    - 其他數學系教授輪著教，這堂網路上一堆資源，全世界任何一堂統計課都差不多，算是偏簡單的課
    - 183基本上就是一堂入門的prob/stats課，可能會寫一些R/Matlab之類的，總之這堂建議早點拿(甚至大一大二心態正確就可以先上了) 如果你嚮往人工智慧的任何東西的話他的core就是線代跟統計所以Math18+Math183學好能解鎖一堆東西
    - 理論上Econ120A CSE103 ECE 109 xxx 都可以拿來抵掉183 (見右表)
    - **Math180A+Math181A**是另一條math nerds可以走的路，我當初是這樣走過來的，想知道內容歡迎私訊。
    

![Screen Shot 2022-02-05 at 12.57.28 AM.png](UCSD%20CS%20Math-CS%20CE%20shit%20you%20should%20know%202b23121564b54cfebdc972d0f6882f87/Screen_Shot_2022-02-05_at_12.57.28_AM.png)

### CSE Electives/Technical

> 很多是聽上過的朋友描述,水課不水本人不服任何責任
> 
- cogs108 intro data science project class
- cogs12X/18X 不排斥project class/CSE110上完不討厭都可以去看看
- CSE194同時滿足DEI但很難搶要first pass
- 可以多看看CSE190的offer，常常出現很酷的課可以上，而且通常都很小班，可以跟教授打好關係，不耍智障的話分數應該也不會打太低
- CSE197/199可以組合達成同樣的效果，有part time internship可以拿來抵學分，但我永遠都不知道怎麼用，請洽VAC
- EDS124AR EDS124BR  [https://sites.google.com/ucsd.edu/eds124ar/home](https://sites.google.com/ucsd.edu/eds124ar/home)
- ENG100D
- LIGN那兩堂
- MGT103 MGT的課應該都算
- DSGN100
- GE上過ECON的話ECON109
- Music Programming MUS的課我看我室友拿到快崩潰哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈智障白人哈哈哈哈哈哈哈哈哈哈哈哈哈快笑死
- 另外不排斥數學的話我覺得數學課還不錯,Math102/170A可以拿來複習線代、Math154/158/184/187都有重疊到CS Core的東西

# | Useful Links - CS people only

CSE Catalog `//look for course descriptions here` 

[Computer Science and Engineering](https://catalog.ucsd.edu/curric/CSE-ug.html)

CSE Degree Programs 

[Undergraduate Degree Programs](https://cse.ucsd.edu/index.php/undergraduate/undergraduate-degree-programs)

CS26 Requirements and Sample Plan `//if youre a transfer student, don’t trust this` 

[B.S. Computer Science](https://cse.ucsd.edu/undergraduate/bs-computer-science)

CSE Course Pre Req Check `//this is the most updated one, newer than catalog` 

[Prerequisites for CSE Undergraduate Classes](https://cse.ucsd.edu/undergraduate/courses/prerequisites-cse-undergraduate-classes)

CSE Course Offering Page //lowkey the page 

[CSE Tentative Undergraduate Course Offerings](https://cse.ucsd.edu/undergraduate/tentative-course-offerings)

CSE List of Electives 

[2021-2022 CSE ELECTIVES AND TECHNICAL ELECTIVES](https://cse.ucsd.edu/undergraduate/2021-2022-cse-electives-and-technical-electives)

# | Q&A I’ll put ppl’s questions and responds here

Q: how many classes should i take per quarter 

A: i’d say get to know the material first, general rule of thumb is have maybe two major classes + two GEs or three major class + one GE, but it kind of depends on the materials, if you’re more familiar with a certain language used in one class then you may probably find it easier or if you happen to have experience in a field then it’ll be a lot easier to pick up something 

Q: chance me. will i get in the major 

A: no idea man 

Q: What Classes should i first pass? 

A: All the CSE Core Classes (CSE101/105/120/132A/15X...) are very popular, also idk why but everyone’s trying to learn AI now so 151A,15X fills up very fast, first pass those, and make space for 

another tip is to ditch the lab class first cuz they’ll save up space for ppl who enroll in a series (don’t take my word for it tho)

<aside>
💡 if you’d like to ask a question → Comment on Top Right Corner
if you’d like to add something or report a bug on this page → go [here](https://github.com/3ricpeng/UCSD-CS-Math-CS-CE-shit-you-should-know-/issues) and raise an issue 
if you’d like to reach me → **@3ricpeng** thats me everywhere IG/FB/Twitter/Line like literally anywhere

</aside>