+++

date = "2017-06-19"
draft = false
title = "如何管理電子書？"
slug = "17-06-how-to-manage-ebooks"
tags = ["lifestyle","閱讀","生活","technology", "prosumer tips"]
comments = false # set false to hide Disqus
share = true # set false to hide share buttons
menu= ""  # set "main" to add this content to the main menu
author = "黃樵志"
isCJKLanguage = true

[blackfriday]

hrefTargetBlank = true 
smartypants = true

+++

這是電子書管理系列文章的第二篇。還沒看過第一篇雖然也沒關係，但如果想從頭了解，請先閱讀[〈都2017年了，電子書究竟該去哪裡買？〉](https://eternallogger.com/post/17-06-where-to-buy-ebooks/)。

<!--more-->

[上一篇](https://eternallogger.com/post/17-06-where-to-buy-ebooks/)我建議買電子書前先考慮能否取得檔案，這篇接著探討入手電子書後該如何管理。一旦取得電子書檔案，管理方式便可憑個人喜好，只要記得檔案存在哪，要找的時候找得到就好了。最陽春的方法是開個資料夾，把所有的書都丟在裡面。可是這種方法雖然簡單可靠，但放久了恐怕會忘記自己究竟有哪些書，甚至根本不會想到要去找。

這時候就可以使用電子書管理程式來協助管理。選擇的關鍵是：這個軟體也必須以檔案管理為基礎。如此一來，就算有一天這軟體不能用了，還是能保留電子書的檔案。

我最後選擇了[Calibre](http://calibre-ebook.com)作為主要的管理程式。Calibre是一個免費且跨平台的[開源軟體](https://en.wikipedia.org/wiki/Open-source_software)，能自動把匯入的電子書以「作者」→「書名」的架構存檔。不過，就像大多數的跨平台開源軟體，Calibre的介面算不上美觀，甚至顯得有些複雜，例如點開「加入書籍」會看到長得嚇人的選項，不禁想要碎嘴一番：「我只是要匯入呀！不能給我一個選項就好了嗎？」

{{< img src="/images/2017/17-06-calibre-files-structure.png" caption="圖說：Calibre自動建立的書庫資料架構" >}}

實際使用卻沒問題。儘管選單複雜得嚇人，但通常只要用滑鼠把檔案拉進Calibre就完成匯入了。匯入的電子書會統一另存在Calibre自己的書庫資料夾中，檔名也會改成Calibre的標準格式。我把[書庫資料夾改設](https://manual.calibre-ebook.com/gui.html#library)在Dropbox裡，等於直接在雲端備份了書庫，也方便從手機、平板取得電子書。看起來似乎足夠好了，但最終讓我決定採用Calibre的原因，是另外兩個殺手級的功能。

首先是「電子書轉檔」。今天市面上買得到的電子書並不限於一種檔案格式，現實是[電子書的格式種類](https://en.wikipedia.org/wiki/Comparison_of_e-book_formats)多得讓人不知該選哪種才好。亞馬遜Kindle和蘋果iBooks兩大敵對平台（自然）互不支援，所以如果想在iBooks看Kindle買的書，或是想上傳自己的書籍到Kindle閱讀器，Calibre就大為有用。

轉檔程序不算複雜，只要點[「轉換書籍」](https://manual.calibre-ebook.com/gui.html#convert-books)，在彈出的視窗右上角選擇「輸出格式」（要上傳Kindle我會選MOBI，否則就選EPUB），然後當作其他選項都不存在，點右下角的「確定」開始轉檔。這時右下角的圓圈會旋轉，也會顯示有幾個轉檔「工作」正在進行。轉檔完成後，右鍵點擊剛剛轉的書，再點「開啟包含的資料夾」，就能找到轉好的檔案。

Calibre的第二個殺手級功能是一個[外掛，能去除主流電子書的DRM](https://apprenticealf.wordpress.com)，包括亞馬遜的Kindle和樂天的Kobo。破解方法我就不細述，基本上只要安裝外掛，匯入書籍時就會自動去除DRM。我在購買電子書之後會留一份DRM-free的檔案，理由我已經在[前文](https://eternallogger.com/post/17-06-where-to-buy-ebooks/)說明了；如今有了這個Calibre的外掛，省了好多麻煩，反倒讓我成為Kindle和Kobo的忠實客戶。

寫到這裡，還得強調：我反對盜版。著作權保護作者，終究是為了鼓勵創作、鼓勵人們表達思想；不過鼓勵創作當然有更積極的方式，也就是給作者錢，也給願意出書的人錢。能夠花錢買到的電子書，就花錢買。去除DRM的電子書，請自行保存，不要外流。

按照以上方法使用Calibre，你將能夠：

1. 去除Kindle和Kobo電子書的DRM；
2. 集中管理電子書的檔案；
3. 主導自己購買的書。

{{< img src="/images/2017/17-06-calibre.png" caption="圖說：Calibre介面一覽" >}}

這裡想多說幾句。我不是要主張消費者權益，也不認為「我都花錢買了，要怎麼用是我的事」。只是身為一個熱衷閱讀又愛搞東搞西的人，我無法不試圖尋找數位閱讀的最佳實踐方式，即使在過程中可能必須把書拆爛。這，與其說是伸張消費者的權利，不如說是負起身為讀者的責任吧。

下一篇，閱讀軟體。（總算）

> 結論：先取得檔案，再用Calibre去除DRM，就能主導自己的閱讀習慣。

#### 【延伸閱讀】  
- [〈都2017年了，電子書究竟該去哪裡買？〉](https://eternallogger.com/post/17-06-where-to-buy-ebooks/)
- [〈電子書閱讀軟體評比：一個挑剔鬼的告白〉](https://eternallogger.com/post/17-06-the-one-ebook-reader/)