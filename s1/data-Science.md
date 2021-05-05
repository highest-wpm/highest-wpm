# Data science
-----
2021/05/04 華柏維

## 名詞
>資料科學、資料探勘、大數據、人工智慧、機器學習...近10年如雨後春筍冒出的名詞，每個看起來都好潮，任何人只要說出這些名詞瞬間就覺得自己專業了起來，但到底它們是什麼?又有什麼不同?
![alt text](https://github.com/kid50901/My-learning/blob/master/img/main-qimg-0434dc91cfe529790780b590da4d4f90.jpg?raw=true)
* Big data : 處理大量資料的技術，數據及需符合 3V 才算大數據(Volume、Velocity、Variety)多量、高頻、多樣。
* Data science : 對資料進行處理，產生有價值的產物。
* Data mining : 對資料進行萃取，產生有價值的產物。
* AI : 能夠表現出類人智能的機器。
* Machine Learning : 以大量已提取屬性的數據建立模型，進行分類。
* Deep Learnig : 以大量未提取屬性的數據建立模型，進行分類。
![alet test](https://github.com/kid50901/My-learning/blob/master/img/1_eh48E1DUcz7uHusyRtIrhQ.png?raw=true)
## 起源
>* 20世紀二戰期間，圖靈製作了一台可以破譯密碼的計算機，協助盟軍擊潰納粹，也開啟了計算機科學的時代。
>* 1969 [ARPANET](https://theconversation.com/how-the-internet-was-born-from-the-arpanet-to-the-internet-68072) 上線 ，1989年Tim Berners-Lee發明了www，1990年[第一個網頁](http://info.cern.ch/hypertext/WWW/TheProject.html)誕生。
>* 2001年 William Cleveland 首次提議設立一個新的學科"data science"，直到今日，data science 已是各項產業爭相發展的領域。
![alt text](https://github.com/kid50901/My-learning/blob/master/img/The_Imitation_Game.jpg?raw=true)
## Position
>Data science 應用比較成熟的產業是網路平台業，如Facebook、Google、Amazon...，我們可以觀察這些巨頭公司對於 Data science 職位的 [job description](https://www.amazon.jobs/en/job_categories/data-science?offset=0&result_limit=10&sort=relevant&distanceType=Mi&radius=24km&latitude=&longitude=&loc_group_id=&loc_query=&base_query=&city=&country=&region=&county=&query_options=&) 來研究，一個成熟的資料科學體系需要什麼樣的組織分工。一般來說 Data science team 會有三種工程師(Data Engineer、Data analyst、Data scientist)，可以用[Monica Rogati](https://www.linkedin.com/in/mrogati)提出的 [data science pyramid](https://hackernoon.com/the-ai-hierarchy-of-needs-18f111fcc007) 來區分。
![alt text](https://github.com/kid50901/My-learning/blob/master/img/1_7IMev5xslc9FLxr9hHhpFw.png?raw=true)
如同馬斯洛需求金字塔的概念，data science pyramid 同樣也是由下往上進行條件滿足，換句話說，滿足下層才能往上層走。。
>* Data Engineer : 主要負責最下面兩層collect、store/move，是資料科學應用在產業的基礎建設所以他非常重要，所需投資的人力也最多。主要工作內容有建立資料庫、建立資料通道、將演算法落地系統並優化效能。技能要求偏向傳統的 computer science，比較接近IT，使用程式python、SQL、JAVA、PHP、HTML...。
 >* Data analyst : 為資料科學家的入門職位，主要負責exlore/transform、aggregate/label層，主要工作為資料清洗與基礎的資料分析(資料聚合、切片、篩選...)，可能也會進行簡單的建模工作(call model)，通常一般碩士統計數學相關科系畢業即可，使用程式python、SQL、R、SAS、EXCEL...。
>* Data scientist : 負責金字塔頂端的工作，負責ML/DL的演算法開發，優化現有模型、建立新演算法，一般由 PHD 擔任此工作，需要極強的數學統計基礎，且需時常study論文，跟上最新的 ML 趨勢，使用程式 python..，有些公司會把Data analyst 、Data scientist 統稱 Data scientist。

 >一個產業若想應用 Data science 且有所成就，須由下往上找尋適合的人才，並從金字塔基底做起，可以沒有ML/DL，但不可以沒有Database、pipline、system，否則演算法再好也沒有對應的資料與落地的場域。以youtube 為例，如果yt沒有效能最好、最友善的 web 介面，即使有超強的推薦演算法，也無法從介面蒐集到資料，更沒有可以放置演算法的殼。data science 可以創造價值，但他必須基於computer science 之上。
## 技能
* 理論知識 : 統計學、純數(最佳化理論)、計算機科學、生物學、教育理論..
* 實現工具 : python、excel、Javascript、R、SAS...
## 應用
* 網路平台的策展(curated)
* 智慧製造
* 風管
* 天氣預測
* 影像辨識
* 自動駕駛
![alt text](https://github.com/kid50901/My-learning/blob/master/img/1efcc879f7b942ab92fd8c7f966c26b2.jpg?raw=true)
## 未來
* 電腦科學界 21 世紀兩項最重要的發展，區塊鏈與 AI 正在醞釀，它們都還在嬰兒期，對人類的影響有限，但隨著摩爾定律硬體條件提升與開發社群的開源文化，許多原本在紙上的理論正在被極快的速度實現，或許是5年、10年人類生活將會有翻天覆地得變化，增加對新事物的認知是我們現在必須做的事，你的人生能擁有多少，取決你對這個世界的認知。