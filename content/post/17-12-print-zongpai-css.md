---
author: 黃樵志
blackfriday:
  hrefTargetBlank: true
comments: false
date: 2017-12-11
description: 嘗試打造數位先行的縱排小說出版流程，結果雖不理想，卻看得出未來的潛力。
draft: false
isCJKLanguage: true
menu: ""
share: true
slug: 17-12-print-zongpai-css
tags:
- technology
- publishing
- 科技
- 出版
- CSS
- Markdown
- HTML
title: 縱排印刷CSS・第一次嘗試
---

繼上次寫了[〈數位先行的CSS出版流程〉](https://eternallogger.com/post/17-10-digital-first-publishing-with-css/)之後，覺得手癢，非得自己試試看是不是真的可行。我的野心不大，只打算做出文字小說或內含少量圖片的旅遊札記而已。我本來就用Markdown寫作，所以若是能把完稿集結後直接轉成EPUB和PDF印刷檔，同時自動生成扉頁、目錄、頁眉或頁腳、頁碼，就算成功。

在腦中盤算時，總覺得不會太難，尤其西方已經有許多嘗試，甚至中文的教程也找得到，尤其知道O'Reilly早已用類似方法出版大多數教材之後，心裡更加踏實。「O'Reilly顯然更為複雜的教材排版都辦得到，我豈有辦不到的道理？」

結果真的辦不到，一個原因是我企圖挑戰縱排／竪排／直書。

由於這套出版模式基於網頁顯示技術，所以瀏覽器對縱排的支援十分關鍵，但瀏覽器的支援程度實在有限。其實我早該想到這個問題，看現在網路上有多少網頁敢用縱排就可見一斑。較高級的排版功能──標點擠壓、懸吊、中英字距等──固然不知從何下手，但有些明明應該要支援的功能卻會出錯，像是我就遇到文字縱排了、但標點卻維持橫排的狀況。

除此之外，文繞圖、腳註也遇到了各種問題。我固然才能有限，幾乎整個嘗試都是基於別人開發的服務，包括Pandoc和Vivliostyle，也因此必須仰賴它們的支援。不過，許多技術都正在發展階段，現在做不到的事、沒修完的臭蟲，可能不久之後就都不是問題了。

至於現階段，就把暫時弄好的東西先丟上GitHub，且看未來的發展吧。

[☞ 點此前往PrintZongpai.css的GitHub頁面](https://github.com/mgeorgetw/PrintZongpai.css)  
[☞ 點此查看自動生成的PDF範例（42MB）](https://github.com/mgeorgetw/PrintZongpai.css/blob/master/MyBook/travel_book_sample.pdf)  
[☞ 點此下載自動生成的EPUB範例（9.34MB）](https://github.com/mgeorgetw/PrintZongpai.css/blob/master/MyBook/travel_book_sample.epub)

#### 【延伸閱讀】

* [〈數位先行的CSS出版流程〉](https://eternallogger.com/post/17-10-digital-first-publishing-with-css/)