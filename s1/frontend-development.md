# Web Frontend Development

網頁「前端」就是一個網站中 User 能看見的全部，而看不見的元素基本上被歸為「後端」。前端是構成網頁最基本的元素，一個網站可以不要後端，前端是必不可少的，而只有前端的網站又稱靜態網頁。

一般而言，網頁前端的需要的人力會少於後端，甚至有些公司有出現一人前端的狀況。（但筆者見過的案例沒有包含美術設計）

<!-- TOC -->

- [Lets fuck up Google.](#lets-fuck-up-google)
- [UI/UX](#uiux)
    - [顏色](#顏色)
- [網頁前端三元素](#網頁前端三元素)
    - [文本標記語言：HTML](#文本標記語言html)
    - [階層樣式表：Cascading Style Sheet](#階層樣式表cascading-style-sheet)
    - [腳本語言：JavaScript](#腳本語言javascript)
- [前端效能](#前端效能)
    - [async](#async)

<!-- /TOC -->

# Lets fuck up Google.

既然得到 Google 的原始碼，我們就能對它做任何事情，我們可以編輯原始碼並且把 Google search bar 從這個世界上消失。

搞毀 Google 之後別擔心，這家科技巨頭不會這麼小心眼地寄存證信函給我們，因為我們亂搞的是那一次我們得到的在我們瀏覽器裡的前端原始碼，遠端 Google 機房儲存的程式碼不會被我們更動，而我們頁面重新整理之後依然會得到完好無缺的 Google。

# UI/UX

> UI 就像笑話，如果還需要解釋就代表做得很失敗。

## 顏色

顏色在視覺設計領域的重要性不言而喻，選用的色調會影響
一般來說希望顧客久待的地方我們會使用讓人感到沉靜的深色系，例如星巴克的室內設計調用許多黑色；而不希望顧客待太久的店家則相反，像是追求高翻桌率的速食店就會選用紅色黃色當作主色，例如麥當勞、肯德基、漢堡王。

臺灣多數的連鎖早餐店都是小店面的店家，既是小店面就必須增加人流來換取金流，鮮紅的招牌與黃色的餐桌就常常在這些品牌出現，例如美而美、美芝城、鄉村漢堡、拉亞漢堡；而麥味登的策略就相反，提供舒適且寬敞的空間留住顧客，讓客人在店內長時間用餐營造熱鬧的景象，就不見高亮的暖色系。

![麥味登店面](https://rememberdelicious.files.wordpress.com/2012/12/image54_thumb.jpg?w=500&h=500)

- 影片：[臺灣新創電商平台 Pinkoi 重新設計 Logo 的過程](https://youtu.be/lYBX9WQDzLI)。

- Bootstrap 的顏色定義

| 顏色 | Bootstrap 代號 ||
|----|--------------|-----|
| 藍色 | primary      |主要|
| 綠色 | success      |成功|
| 紅色 | danger       |危險|
| 橘色 | warning      |警告|
| 青色 | info         |資訊|
| 灰色 | secondary    |次要|



# 網頁前端三元素

## 文本標記語言：HTML 

Hyper Text Markup Language 簡稱 HTML，是 Sir Tim Berners-Lee 發明用來撰寫文章的標記語言，所以記住**網頁的本質其實就是文章**，而 HTML 的用途就是標記(tag)文章中每段文本的「語意」，例如我們寫了一段文章裡頭有一個一級標題搭配一個段落。

```html
<html>
  <head>
    <title>Meetup-Q page</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <header>
	  <h1>這是網頁的標題，一級標題</h1>
	  <div>這是一的 division </div>
    <header>
    <section>
	  <h2>我是二級標題</h2>
	  <p>我是文章中完整的段落，所以我適合使用的 HTML tag 是 paragraph tag。</P>
    </section>
    <footer>
      <ul>
	    <li>GitHub</li>
	    <li>GitLab</li>
	    <li>Gitea</li>
      </ul>
    </footer>
    <script src="myscripts.js"></script>
  <body>
</html>


```

網頁的基底 Document Object Model(DOM)，DOM 本身是樹狀結構，

HTML 由 tag 而成，不同的 tag 有不同的「語意」，

HTML 語意構成的文章



## 階層樣式表：Cascading Style Sheet

要想快速上手 CSS 語言必須先了解 box-model，網頁的所有元素都是 box-model，由 margin、border、padding、content 組成，前端設計或前端工程的工作就是把這所有 box-model 乖乖的排列到對的位置。

![Box Model](http://intensivstation.ch/assets/Uploads/box.png)

```css
.component-box {
  width: 500px;
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
}

#meetup-q {
  frontend: 😎;
  backend: 💪;
  machine-learning: 🤖;
  data-science: 📈;
  hacking: 💻;
}
```


## 腳本語言：JavaScript

HTML & CSS 只能表現出一個頁面的外在而已，要能活動起來一定要仰賴 JavaScript。

```javascript
Const fetchData = () => {
  axios({
    method: 'post',
    url: '/login',
    data: {
      orgnization: 'meetup-q',
      platform: 'GitHub'
    }
  })
}
```



# 前端效能

## async

因為 javascript 本身是 「synchronous」 的語言，一個步驟完成之後才會往下一個步驟前進。

若有一段程式需要比較多的工作時間，接續的程式就必須等待，若一份 javascript code 有 10 個 function 需要執行，每個 function 的執行時間都是 10 秒鐘，那就需要 10 * 10 = 100 秒直譯完這份檔案。而 user 不可能忍受每次載入網頁都需要花這麼長的時間。

asynchronous 技術就在解決這個問題，它實現多核心處理程序，當一個程式需要一段時間執行時，將它指派給其他執行 thread，程式繼續往下執行。
