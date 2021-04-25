# JavaScript

![JavaScript](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/javascript.png)
首先，JavaScript 與 Java 完全沒有關係，前者既不是後者的縮寫也不是一種腳本的類型，千萬不要搞混，這是相當不專業的錯誤！

過去 JavaScript 只是在網頁前端控制網頁元素（Document Object Model）的程式語言，有它我們才能看見有豐富動態的網頁

現在的 JavaScript 被應用到各種平台上包括 Web、iOS app、Android app、Desktop app，並且也被應用到伺服器上，強大的 JavaScript 讓開發者可以在前端後端都使用它。
 
 ![Github Language Stat](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/github-language-stat.png)


# JavaScript 與網頁前端
網頁前端是由靜態的 Document Object Model（DOM）組成，我們使用 JavaScript 寫成的腳本來告訴 Browser 該怎麼讓使用者與 DOM 互動。簡單一點比喻 HTML 是前端的骨幹，CSS 是前端的皮膚，JavaScript 就是前端的大腦。

# ECMAScript
![](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/ecmascript-logo.png)
ECMAScript 指的是語言的規格，而 JavaScript 則是實作出的語言。不同瀏覽器之間有不同的JavaScript 的直譯器，這些直譯器需要符合 ECMAScript 的內容，所以 JavaScript 在每個瀏覽器才會呈現一致的結果。有時候開發者會直接認為 ECMAScript 等價於 JavaScript，它們之間還是有點差異，但大致上兩者都要實現同樣的結果，完成同樣的工作。

# TypeScript
![typescript](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/typescript.png)
程式語言允許資料型別的變化可以簡單分類成強弱兩種，強型別的語言會禁止資料型別任意轉換，例如變數在定義時就宣告為字串（string）就不能在隨意地賦予一個非字串的值，而 JavaScript 是屬於弱型別的語言，變數可以隨意賦值。

通常強型別的語言需要在宣告變數的時候一同宣告資料型態，而弱型別的語言則不用。需要預先宣告資料型別的壞處是在敲鍵盤之前需要規劃的更完全，這對初學者來說並不容易，好處是在程式碼增長之後能確保程式不因資料型態錯置而造成錯誤。

下方是 TypeScript，宣告 name 變數的時候要同時宣告資料型別為字串。
```typescript
let name:string = "Harry"; 
```

下方是 JavaScript，在宣告 name 變數時不需要宣告資料型別，並且可以賦予不同資料型態的值。
```javascript
let name = "Harry"
name = 1234 
```

# Frontend framework

最受歡迎的前端框架有 React、Angular 和 Vue。React 是 Facebook, Inc. 開發的，現在的 Facebook 頁面就是使用 React，React 的設計將程式碼模組化，大大的提升程式碼再利用的效率，使得程式碼更 DRY（Don't Repeat Yourself）；Angular 是 Google, Inc. 推出的，Angular 的設計確保了前端團隊的每個人都遵從同一個規範，這個特性反映出 Google 在管理多人協作程式的專長；Vue 是中國裔開發者 Evan You 尤雨溪自主開發的，天賦極高的 Evan 在學生時代創作的作品就被 Google 相中，並邀請他加入 Google 的前端實驗室。開發 Vue 的動機是 Evan 認為當時能用的前端工具不夠靈活，且多是以管理者或以工程的角度開發，不符合開發者對前端「藝術」的需求。

軼聞：Evan 在訪問影片提到在 Google 前端團隊常常要思考超前世代的前端應用會是什麼，例如一面牆如果是一個巨大的螢幕要怎麼呈現上面的應用程式。這樣的需求促使他需求更靈活的前端工具，遂行創作出 Vue。

軼聞：Vue 得名於 MVC 框架中的 View，但他覺得 View 太直白且容易混淆，所以在 Google translate 上尋找 View 在其他語言的翻譯，最後選擇了法語 Vue。
![React](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/react-js-logo.png)
![Angular](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/angular-js-logo.png)
![Vue](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/vue-js-logo.png)
![Evan You](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/evan-you.jpg)
# Node
![Node](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/node-js-logo.png)
Node 的設計者是 Ryan Dahl，Node 是 JavaScript 的 runtime 環境，我們將 Node 安裝在 server 上就可以把 JavaScript 當作後端語言了。Node 也使用 V8 engine 執行 JavaScript。我們要很清楚，前端的 JavaScript 與 Node 是完全不一樣的東西。

![Ryan Dahl](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/ryan-dahl.jpg)

軼聞：常有 HR 不慎把 Node 寫成 Nude（裸體）刊登在徵才資訊上，遭到開發者的嘲笑，所以要非常小心自動選字造成的錯誤。

# Deno
![Deno](https://raw.githubusercontent.com/meetup-q/meetup-q/master/s1/img/deno-logo.png)
Deno 也是 Ryan Dahl 開發的，Deno 的原生語言不只有 JavaScript，TypeScript 也被 Dahl 考慮進來。Deno 是值得關注的新星，自從 2018 年推出以來就被認為會一統各平台應用程式開發，也許 2021 年就會看到它爆炸性的成長。現在投資時間在 Deno 與 TypeScript 絕對是明智的選擇。

# 最後
再提醒一次，JavaScript 不是 Java，兩語言的關係就像太陽餅與太陽一樣，完全沒有關係，請不要搞混！