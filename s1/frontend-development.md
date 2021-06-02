# Web Frontend Development



網頁「前端」就是一個網站中 User 能看見的全部，而看不見的元素基本上被歸為「後端」。前端是構成網頁最基本的元素，一個網站可以不要後端，前端是必不可少的，而只有前端的網站又稱靜態網頁。

一般而言，網頁前端的需要的人力會少於後端，甚至有些公司有出現一人前端的狀況。（但筆者見過的案例沒有包含美術設計）

{{TOC}}

當 user 對 URL 發動 HTTP 請求時，URL 指向的 server 會回覆 HTML 原始碼

## Lets fuck up Google.

既然得到 Google 的原始碼，我們就能對它做任何事情，我們可以編輯原始碼並且把 Google search bar 從這個世界上消失。

搞毀 Google 之後別擔心，這家科技巨頭不會這麼小心眼地寄存證信函給我們，因為我們亂搞的是那一次我們得到的在我們瀏覽器裡的前端原始碼，遠端 Google 機房儲存的程式碼不會被我們更動，而我們頁面重新整理之後依然會得到完好無缺的 Google。

# 網頁前端涉及議題

## 畫面設計美術：畫面如何呈現

顏色在視覺設計領域的重要性不言而喻，選用的色調會影響
一般來說希望顧客久待的地方我們會避免使用鮮豔的紅黃色系，而不希望顧客待太久的店家就會使用比較亮的暖色系，像是追求高翻桌率的速食店就會選用紅色黃色當作主色，例如麥當勞、肯德基、漢堡王，

臺灣新創電商平台 [Pinkoi](https://youtu.be/lYBX9WQDzLI) 重新設計 Logo 的過程。

Bootstrap 的顏色稱呼

| 顏色 | Bootstrap 代號 ||
|----|--------------|-----|
| 藍色 | primary      |主要|
| 綠色 | success      |成功|
| 紅色 | danger       |危險|
| 橘色 | warning      |警告|
| 青色 | info         |資訊|
| 灰色 | secondary    |次要|


## 使用者體驗

> UI 就像笑話，如果還需要解釋就代表做得很失敗。


## 網頁渲染效能：前端如何掌握大資料流

## 異步
## Code splitting

# 網頁前端只有三個元素組成

## 文本標記語言：HTML 

Hyper Text Markup Language 簡稱 HTML，是 Sir Tim Berners-Lee 發明用來撰寫文章的標記語言，所以記住**網頁的本質其實就是文章**，而 HTML 的用途就是標記(tag)文章中每段文本的「語意」，例如我們寫了一段文章裡頭有一個一級標題搭配一個段落。

```
<div>
	<h1>我是一級標題</h1>
	<p>我是文章中完整的段落，所以我適合使用的 HTML tag 是 paragraph tag。</P>
</div>
```

網頁的基底 Document Object Model(DOM)，DOM 本身是樹狀結構，

HTML 由 tag 而成，不同的 tag 有不同的「語意」，

HTML 語意構成的文章



### 搜尋最佳化：讓所有人找到這個網站

善用 HTML 語法讓搜尋引擎認識網站，

## 階層樣式表：CSS

CSS 是筆者遇過最難懂的工具...

CSS 不只是難寫

## 腳本語言：JavaScript

HTML & CSS 只能表現出一個頁面的外在而已，要能活動起來一定要仰賴 JavaScript。

Conjunction

# Http Request GET

Browser 可以檢視原始碼，任何人都可以下載別人的前端原始碼
 - 破壞 Google 原始碼

# Cookie & Session



## 前端第一品牌 JQuery


## 前端三框架

React.js