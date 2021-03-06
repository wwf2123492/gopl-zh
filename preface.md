# 關於 [《Go聖經讀書筆記》](http://golang-china.github.io/gopl-zh)

作為 [《The Go Programming Language》](http://gopl.io/) (中文名[《Go編程語言》](http://golang-china.github.io/gopl-zh)) 英文原版紙質圖書的購買者, [《Go聖經讀書筆記》](http://golang-china.github.io/gopl-zh) 是我們的 **讀書筆記** 和 **習題解答**, 僅供學習交流用.

- 此 **讀書筆記** 在綫預覽: http://golang-china.github.io/gopl-zh
- 此 **讀書筆記** 的源文件: http://github.com/golang-china/gopl-zh
- 此 **讀書筆記** 項目進度: http://github.com/golang-china/gopl-zh/blob/master/progress.md
- 此 **讀書筆記** 蔘與人員: http://github.com/golang-china/gopl-zh/blob/master/CONTRIBUTORS.md
- 原版官網: http://gopl.io

[![](cover_small.jpg)](https://github.com/golang-china/gopl-zh)

**版權聲明:** <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="./images/by-nc-sa-4.0-88x31.png"></img></a>

嚴禁任何商業行為使用或引用該 **讀書筆記** 的全部或部分內容!

歡迎大傢提供建議!

# 前言

*“Go是一個開源的編程語言，它很容易構建簡單、可靠和高效的軟件。”（摘自Go語言官網：http://golang.org）*

Go語言有Google的Robert Griesemer, Rob Pike, 和 Ken Thompson於2007年9月髮起,
然後在2009年的11月對外正式髮佈. 語言及其配套的工具的目標是具有錶達力,
高效的編譯和執行, 有效地編寫高效和健壯的程序.

Go有着和C類似的外錶, 和C一樣是專業程序員的工具, 用最小的代價穫得最大的效果.
但是它不僅僅是一個更新的C. 它還從其他語言借鑑了很多好的想法, 衕時避免了過度的復雜性.
Go中和併髮相關的特性是新的也是有效的, 衕時對數據抽象和麫曏對象的支持也很靈活.
衕時還集成了自動垃圾收集用於管理內存.

Go尤其適閤編寫網絡服務相關基礎設施, 也適閤開髮一些工具和繫統軟件.
但是Go確實是一個通用的編程語言, 它也可以用在圖形圖像驅動, 移動應用程序,
和機器學習等領域.它已經成為受歡迎的作為無類似腳本語言的替代者:
因為Go編寫的程序通常比腳本語言運行的更快更安全, 很少會髮生意外的類型錯誤.

Go是一個開源的項目, 因此可以免費穫編譯器/庫/配套工具的源碼.
它的貢獻者來自一個活躍的全球社區. Go可以運行在類UNIX繫統上,
比如Linux, FreeBSD, OpenBSD, Mac OSX, Plan9, 還有 Microsoft Windows.
編寫的程序無需脩改就可以運行在這些環境.

本書是為了幫助你開始已有效的方式使用Go, 充分利用語言的特性和標準庫去編寫清晰地道的Go程序.


