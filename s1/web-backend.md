# Web Backend Development
---
## 前後端的區別 
* 前端，廣義來說就是使用者看到的部份，負責呈現資訊與收集資訊，前端會直接影響使用者體驗。
* 後端，廣義來說就是使用者看不到的部份(f12 也看不到)，負責 Web 大部分 CRUD 的功能與一些邏輯判斷、資料處裡。

## 網站設計模式(Web Design Pattern )
對 Web 開發中普遍存在（反覆出現）的各種問題，所提出的解決方案。提供一個架構概念不提供程式碼。
* MVC
1.Model（模型）對資料庫的CRUD。
2.View（視圖）處理與展示數據。
3.Controller（控制器）處理使用者交互的部分，例如控制器負責從視圖讀取數據，控制用戶輸入，並向模型發送數據。

![alet test](https://github.com/kid50901/meetup-q/blob/master/s1/img/mvc.png?raw=true)

* MTV
1.Model（模型）對資料庫的CRUD。
2.View（視圖）處理要展示的數據。
3.Template（模板）展示數據。

![alet test](https://github.com/kid50901/meetup-q/blob/master/s1/img/mtv.jpg?raw=true)

* MVC VS MTV

![alet test](https://github.com/kid50901/meetup-q/blob/master/s1/img/mvc_vs_mtv.png?raw=true)
## 網站框架(Web Application Framework)
框架是按照設計模式完成的半成品，在框架的基礎上可以進行二次開發。
## Django
![alet test](https://github.com/kid50901/meetup-q/blob/master/s1/img/django-logo.jpeg?raw=true)
Django 是個用 Python 寫成的且免費開放原始碼的 Web 框架。，名稱來自一位知名的爵士吉他手 Django Reinhardt，從官網可以得知，創始者是因為喜歡這一名吉他手才將它命名為 Django。它採用了MVT設計模式。秉持著DRY(Don't Repeat Yourself)的原則，有許多的程式在 Django 都已完成。大大減低開發 web 的時間。
## 實際演示 Django 製作 Query 功能
Template.html 傳遞請求給 Views.py，Views.py 依據請求從 model.py 撈取對應的資料給 Template.html 進行呈現。
![alet test](https://github.com/kid50901/meetup-q/blob/master/s1/img/djang_query_ex.PNG?raw=true)
## 前端渲染與後端渲染
前端沒興起之前，網頁的展示大都是後端渲染，也就是服務器渲染。隨著前端行業的發展，前端的工作越來越精細。前後端開始分離，前端只關注ui渲染。後端只提供數據和進行邏輯處理。
簡單的解釋，前端寫好html模板，讓後端直接填數據，這就是後端渲染。
前端渲染是，通過 ajax 請求接口返回的數據，將數據渲染出來。後端只寫接口(json API)，分工更明細。

## 小維元件 Web 開發
屬於前端渲染，MQ 規劃的架構為由 python 撈 oracle DB 資料，進行後多邏輯處理後，餵入 oracle DB 的 report table，建立 json API 撈取 report table，前端元件透過 ajax 請求接口返回數據。
![alet test](https://github.com/kid50901/meetup-q/blob/master/s1/img/pre_warroom.PNG?raw=true)
