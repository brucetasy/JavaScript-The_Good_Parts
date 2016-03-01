##### 從 Github 上看到的嗎? 我們有更好的瀏覽體驗! **[ JavaScript:優良部分 讀書會紀錄 →](http://miniaspreading.github.io/JavaScript-The_Good_Parts/)**
<!-- {h5: style='display:none'} -->

----
<!-- {hr: style='display:none'} -->

# JavaScript:優良部分

<!-- {h1:.massive-header.-with-tagline} -->

> JavaScript：The_Good_Parts <br>




i. 前言
------------

大多數程式語言都包含好與不好的兩類成分，但 JavaScript 的後者似乎佔了不少比例，因為它是個開發與發表都很匆促、沒有時間精雕細琢的語言。這本權威書籍刮除了 JavaScript 中最可怕的功能，為大家呈現較為可靠、較可讀解、也較可維護的部分 JavaScript －－ 我們能用這部分功能建立真正具擴充性、又有效率的原始碼。
<br>

本書作者 Douglas Crockford，一位獲程式開發社群中許多人公認的 JavaScript 專家，分辨出了讓 JavaScript 成為傑出物件導向程式設計語言的優良部分。但很可惜，這些優良的部分（例如函式、寬鬆型別、動態物件、富表達性的物件實字註記）都與糟糕到家的想法混在一起（例如以全域變數為基礎的程式設計模型）。
<br>

一本《JavaScript：優良部分》在手，你將發現一個美麗、優雅、輕量，且高度表達性的語言，可建立有效率的程式碼；無論你在管理物件函式庫，或只是想讓 Ajax 跑得更快。如果你為全球資訊網開發網站或應用程式，一定要閱讀本書。
<br>

Douglas Crockford 是 Yahoo! 的資深 JavaScript 架構師，因為他對 JSON（JavaScript Object Notation）格式的引進與維護而相當知名。經常於 JavaScript 深度研討會上演講，也是 ECMAScript 委員會的成員。
<br>
<!--
ii. 閱讀對象
------------

本書避免大量使用術語或為網路程式設計初學者解釋基礎概念。而是嘗試對所有人溝通，但假設你已經具有一定的基礎知識。若你剛開始學習網路開發，這不應該是你的第一本書。<br>
因此閱讀本書之前需要先具備以下的基本知識：

- **HTML**
  * 知道 HTML 的功能，並能分辨 HTML 文件上的結構與一些標籤。

- **JavaScript**
  * 知道 JavaScript 的功能並知道 `<script>` 標籤的功能與變化形式。初學者也沒問題，筆者會保持範例程式的簡單。

- **程式設計概念**
  * 筆者會提供一些簡單的概念解釋給新手，像是物件與陣列等。但若你沒有任何的程式設計經驗，則這本書並不適合你。


iii. 學習 JSON
------------

這些年來筆者經常在有時間壓力的專案中需要學習新技術。因此買了厚重的參考書，做練習題，嘗試吸收資訊。在閱讀數百頁的內容時，筆者會尋找著三個基本問題的答案：

- 它是什麼？
- 我如何使用？
- 壞人會怎麼使用？

筆者在撰寫此書時思考著如何直指這些問題，讓你不用讀一大堆內容才找到答案。<br>

在**第一章至第四章**中，筆者從低階開始探索 JSON ，先回答終極的問題：“它是什麼？”，然後檢視語法、語法驗證、資料型別、以及結構驗證。<br>

**第五章**會討論安全性的重要主題，這一章主要包括本書內容中的用戶端與伺服器端的重要概念，這一部份回答“壞人會怎麼使用”的問題。<br>

這些章節包括了許多 JSON 的範例以及與 JSON 互動的技術。 <br>

**第六章至第九章**的重要內容包括：

- **技術**
像是 jQuery、AngularJS 與 CouchDB 等概念，這些主題都大到要以（且已經）用一整本書來討論。筆者刻意省略這些技術的安裝指引與深入討論，重點是在於顯示這些技術如何運用 JSON。<br>

若要常識實驗使用這些技術的範例，你必須做一些繁瑣的工作以設置環境，然而範例本身卻很簡單。若你能夠設置好基本環境，則應該能夠進行實驗。<br>


- **範例程式**
書中有許多範例程式，有些程式設計語言你可能沒接觸過，這些語言的語法不會做解釋，但無須對看不懂的語法感到緊張，其目的只是要讓你“知道”程式在做什麼，所以會對程式碼的作用做出說明。

本書的範例程式可從 [Github 取得](https://github.com/lindsaybassett/json)。我們也會整理並提供在讀書會的過程中有使用到的範例。

第六至第九章的終極目的是，顯示出其他人如今如何使用 JSON ，讓你對自己的專案產生一些想法。若你從未見過以 JSON 作為資料儲存文件格式，怎麼會將它用在專案中？知悉是實作過程的一半。

每一章內容會平成重點概述與足夠的資訊以讓你不會遺漏重點，本書的架構是要讓你快速上手而不會犧牲對 JSON 與其用途更深入的理解。


-->
讓我們開始吧!
[進入第一章 →](docs/1-Good-Parts.md)<br>


<!-- {p:.pull-box} -->

----
<!-- {hr: style='display:none'} -->
書籍資訊：<br>
**JavaScript:優良部分** © 2015+, [Lindsay Bassett](https://github.com/lindsaybassett). <br>

<!-- {p: style='display:none'} -->

----
作者：[Douglas Crockford](https://github.com/lindsaybassett)，翻譯：莊惠淳。<br>
網頁樣板：[docpress](https://github.com/docpress/docpress) ，讀書會紀錄：[多奇數位](http://www.miniasp.com) <br>有任何建議歡迎提出，感謝!

<!-- {blockquote: style='display:none'} -->

[MIT]: http://mit-license.org/