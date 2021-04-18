# Python
#programming #python #introduction

資料科學是 Python 最廣為人知的應用領域，故不少人聽到 Python 就與之聯想在一起，然而不只於此，網頁開發、作業系統、自動化測試等等工作 Python 都能勝任，Python 的多才多藝反映的是背後相當活躍的開發者社群，根據[Github 統計](https://madnight.github.io/githut/#/pull_requests/2021/1)，2021 年 Q1 最受歡迎的程式語言第二名就是 Python，選擇 Python 就等於擁抱背後巨大的社群，這樣的好處是遇到任何問題都能相當輕易地在網路上得到解答。

這篇文章主要介紹 Python 是什麼，及如何開始使用它。

# Interpreter（直譯器）
Python 使用 Interpreter，Interpreter 是逐行將程式碼直譯為 Binary Code 讓電腦讀取，所以還未有讀取的錯誤程式不會被 Interpreter 發現，這有助於加速開發速度，Developer 可以一邊寫程式一邊觀察執行結果，一步一步地確認程式往對的方向成型。

# Compiler（編譯器）
Compiler 是將所有程式碼一次轉譯為 Binary Code，整個程式只要有一個錯誤就會轉譯失敗，這樣有益於程式的品質，因為錯誤在編譯的時候就被發現了，而不是程式執行時才被發現。

# Python 2 and Python 3
Python 2 與 Python 3 的語法並沒有多大的差別，只要學會 3 會看得懂 2。

# 終身仁慈的獨裁者 Guido van Rossum

Guido van Rossum 原為荷蘭國家數學和電腦科學研究中心的員工，在 1980 年代能使用的程式語言具有相當局限性，van Rossum 就是在當時認為想著現有的程式語言都不好用，於是在 1989 年的聖誕假期為了打發時間而著手創造 Python，這個語言得名於 Rossum 最喜歡的劇團「 Monty Python 」。因為網路效應，Python 傳播到全世界並深受喜愛，所以作為 Python 之父的 van Rossum 做的每個規劃與決定都將造成巨大的影響，van Rossum 也因此獲得了「終身仁慈的獨裁者」的稱號。

## Python 的哲學：Zen of Python

在 Python REPL 環境輸入 `import this` 就會出現 Python 彩蛋「 Zen of Python 」，這是一個講述 Python 哲學的詩篇，而所謂 「 Pythonic 」 的程式碼必定得符合。

原文：
> The Zen of Python, by Tim Peters
> Beautiful is better than ugly.
> Explicit is better than implicit.
> Simple is better than complex.
> Complex is better than complicated.
> Flat is better than nested.
> Sparse is better than dense.
> Readability counts.
> Special cases aren't special enough to break the rules.
> Although practicality beats purity.
> Errors should never pass silently.
> Unless explicitly silenced.
> In the face of ambiguity, refuse the temptation to guess.
> There should be one-- and preferably only one --obvious way to do it.
> Although that way may not be obvious at first unless you're Dutch.
> Now is better than never.
> Although never is often better than *right* now.
> If the implementation is hard to explain, it's a bad idea.
> If the implementation is easy to explain, it may be a good idea.
> Namespaces are one honking great idea -- let's do more of those!

<br />
中文翻譯：

> Python 禪，Tim Peters
> 美麗的勝於醜陋的
> 顯性的勝於隱性的
> 簡單的勝於複雜的
> 複雜的勝於雜亂的
> 扁平的勝於巢狀的
> 稀疏的勝於密集的
> 可讀性非常重要
> 特例並不會特別到可以破壞規則
> 雖然務實的好過純粹的
> 錯誤絕對不可以不出聲地出現
> 除非明確需要如此
> 在面對令人混淆且不確定的問題千萬不妄自猜測
> 且應該有唯一個完美解決問題的方法
> 雖然這個方法可能只有荷蘭人才能在第一眼發現（註：Python 之父是荷蘭人）
> 現在行動永遠好過永不作為
> 雖然永不作為時常比魯莽做事要好得多
> 不好解釋的方法必然是不好的方法
> 好解釋的方法通常是不錯的解方
> 有命名原則永遠是好的事情應該多多推廣！


# REPL 環境
REPL 的全名是 Read-Evaluate-Print-Loop，REPL 環境讓使用者可以馬上看到指令的輸出結果，這個工具對於初學者來說相當方便，初學者可以透過 REPL 環境與 Python 做互動進而熟悉它。

# Jupyter Notebook - Python 工作室

Jupyter Notebook 是非常強大的 Web based 的 Python IDE，支援魔術指令，可以及時輸出部分程式碼的執行結果，Notebook 檔案的副檔名是 `.ipynb`。


下載方式

``` 
pip install jupyter
```

# Anaconda

## conda 與 pip 的不同

# Python 基礎語法


# Django - 網頁框架
# Pandas - 你新的 Excel 
# Numpy & Scipy - 數學好幫手
# Matplotlib - 視覺化精靈
# Python Community - welcome to the nightbor
## 其他常用套件
### selenium - 變身蜘蛛人
selenium 是一個自動化測試套件，因為操作特性被當作爬蟲工具來使用。
### scikit-learn - Machine Learning
scikit-learn 是開源的機器學習套件，被很多學術單位及公司使用。
### tensorflow, pytorch - Deep Learning
tensorflow 是 Google.inc 發表的深度學習框架，

# 第一個 side project
學習程式語言跟自然語言都是一樣的，唯有時常使用才能熟練，我推薦在知名影音平台上學習例如 Youtube、udemy，並且在 w3school、stackoverflow 解決自己的疑問，在自學的過程中學會如何 google。在學習完基礎語法之後，動手做第一個 side project，透過實作一整個專案的過程，了解程式語言本身的特性。