# 譯者序

在上個世紀70年代，貝爾實驗室的 [Ken Thompson](http://genius.cat-v.org/ken-thompson/) 和 [Dennis M. Ritchie](http://genius.cat-v.org/dennis-ritchie/) 合作發明了 [UNIX](http://doc.cat-v.org/unix/) 操作系統，同時 [Dennis M. Ritchie](http://genius.cat-v.org/dennis-ritchie/) 爲了解決 [UNIX](http://doc.cat-v.org/unix/) 系統的移植性問題而發明了 C 語言，貝爾實驗室的 [UNIX](http://doc.cat-v.org/unix/) 和 C 語言兩大發明奠定了整個現代IT行業最重要的軟件基礎（目前的三大桌面操作系統的中[Linux](http://www.linux.org/)和[Mac OS X](http://www.apple.com/cn/osx/)都是源於 [UNIX](http://doc.cat-v.org/unix/) 系統，兩大移動平臺的操作系統 iOS 和 Android 也都是源於 [UNIX](http://doc.cat-v.org/unix/) 系統。C 系家族的編程語言佔據統治地位達幾十年之久）。在 [UNIX](http://doc.cat-v.org/unix/) 和 C 語言發明40年之後，目前已經在 Google 工作的 [Ken Thompson](http://genius.cat-v.org/ken-thompson/) 和 [Rob Pike](http://genius.cat-v.org/rob-pike/)（他們在貝爾實驗室時就是同事）、還有[Robert Griesemer](http://research.google.com/pubs/author96.html)（設計了 V8 引擎和 HotSpot 虛擬機）一起合作，爲了解決在21世紀多核和網絡化環境下越來越複雜的編程問題而發明了 Go 語言。從 Go 語言庫早期代碼庫日誌可以看出它的演化歷程（ Git 用 `git log --before={2008-03-03} --reverse` 命令查看）：

![](./images/go-log04.png)

從早期提交日誌中也可以看出，Go 語言是從 [Ken Thompson](http://genius.cat-v.org/ken-thompson/) 發明的 B 語言、[Dennis M. Ritchie](http://genius.cat-v.org/dennis-ritchie/) 發明的 C 語言逐步演化過來的，是 C 語言家族的成員，因此很多人將 Go 語言稱爲 21 世紀的 C 語言。縱觀這幾年來的發展趨勢，Go 語言已經成爲雲計算、雲存儲時代最重要的基礎編程語言。

在 C 語言發明之後約5年的時間之後（1978年），[Brian W. Kernighan](http://www.cs.princeton.edu/~bwk/) 和 [Dennis M. Ritchie](http://genius.cat-v.org/dennis-ritchie/) 合作編寫出版了C語言方面的經典教材《[The C Programming Language](http://s3-us-west-2.amazonaws.com/belllabs-microsite-dritchie/cbook/index.html)》，該書被譽爲 C 語言程序員的聖經，作者也被大家親切地稱爲 [K&R](https://en.wikipedia.org/wiki/K%26R)。同樣在 Go 語言正式發佈（2009 年）約 5 年之後（2014 年開始寫作，2015 年出版），由 Go 語言核心團隊成員 [Alan A. A. Donovan](https://github.com/adonovan) 和 [K&R](https://en.wikipedia.org/wiki/K%26R) 中的 [Brian W. Kernighan](http://www.cs.princeton.edu/~bwk/) 合作編寫了Go語言方面的經典教材《[The Go Programming Language](http://gopl.io)》。Go 語言被譽爲 21 世紀的 C 語言，如果說 [K&R](https://en.wikipedia.org/wiki/K%26R) 所著的是聖經的舊約，那麼 D&K 所著的必將成爲聖經的新約。該書介紹了 Go 語言幾乎全部特性，並且隨着語言的深入層層遞進，對每個細節都解讀得非常細緻，每一節內容都精彩不容錯過，是廣大 Gopher 的必讀書目。大部分 Go 語言核心團隊的成員都參與了該書校對工作，因此該書的質量是可以完全放心的。

同時，單憑閱讀和學習其語法結構並不能真正地掌握一門編程語言，必須進行足夠多的編程實踐——親自編寫一些程序並研究學習別人寫的程序。要從利用 Go 語言良好的特性使得程序模塊化，充分利用 Go 的標準函數庫以 Go 語言自己的風格來編寫程序。書中包含了上百個精心挑選的習題，希望大家能先用自己的方式嘗試完成習題，然後再參考官方給出的解決方案。

該書英文版約從 2015 年 10 月開始公開發售，其中日文版本最早參與翻譯和審校（參考致謝部分）。在 2015 年 10 月，我們並不知道中文版是否會及時引進、將由哪家出版社引進、引進將由何人來翻譯、何時能出版，這些信息都成了一個祕密。中國的 Go 語言社區是全球最大的Go語言社區，我們從一開始就始終緊跟着 Go 語言的發展腳步。我們應該也完全有能力以中國 Go 語言社區的力量同步完成 Go 語言聖經中文版的翻譯工作。與此同時，國內有很多 Go 語言愛好者也在積極關注該書（本人也在第一時間購買了紙質版本，[亞馬遜價格314人民幣](http://www.amazon.cn/The-Go-Programming-Language-Donovan-Alan-A-A/dp/0134190440/)。補充：國內也即將出版英文版，[價格79元](http://product.china-pub.com/4912464)）。爲了 Go 語言的學習和交流，大家決定合作免費翻譯該書。

翻譯工作從 2015 年 11 月 20 日前後開始，到 2016 年 1 月底初步完成，前後歷時約 2 個月時間（在其它語言版本中，全球第一個完成翻譯的，基本做到和原版同步）。其中，[chai2010](https://github.com/chai2010) 翻譯了前言、第2 ~ 4章、第10 ~ 13章，[Xargin](https://github.com/cch123) 翻譯了第1章、第6章、第8 ~ 9章，[CrazySssst](https://github.com/CrazySssst) 翻譯了第5章，[foreversmart](https://github.com/foreversmart) 翻譯了第7章，大家共同參與了基本的校驗工作，還有其他一些朋友提供了積極的反饋建議。如果大家還有任何問題或建議，可以直接到中文版項目頁面提交 [Issue](https://github.com/golang-china/gopl-zh/issues)，如果發現英文版原文在[勘誤](http://www.gopl.io/errata.html)中未提到的任何錯誤，可以直接去[英文版項目](https://github.com/adonovan/gopl.io/)提交。

最後，希望這本書能夠幫助大家用Go語言快樂地編程。

2016年 1月 於 武漢
