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

如果你下載了 Anaconda，Jupyter 也會連帶一起下載，所以不用再下載一次。

``` 
# using pip
pip install jupyter

# using conda
conda install jupyter

# activate jupyter notebook
jupyter notebook

# activate jupyter lab
jupyter lab
```


# conda 與 pip 的不同

`pip` 是 Python 專用的套件管理器，而 `conda` 是以 Python 撰寫的跨語言的套件管理器，所以也可以透過 `pip` 下載。

```
pip install conda
``` 

Anaconda 在資料科學領域的表現相當出色，因為它有特別針對資料科學的套件做效能優化，做資料科學不用多想就直接使用 `conda` 吧。

# 第一個 side project

程式語言本身是沒有用處的，就像自然語言如普通話或英文一樣，只有被使用的時候才有意義，要想精進寫程式的能力沒有他法，就是要一直寫一直寫一直寫，但是程式語言不能寫日記，必須要有題目有目標才能開始使用。 所謂的 side project 就是與日常生活無關的計畫，可以是修復一台經典老車（例如 1990 年的 BMW E30！😎）、可以是打造自己的私人空間（把空閑的工作陽台改造成舒適的空中花園）、也可以是做自己的第一個網站或是機器學習模型！

如果讀者對網站有興趣，可以從待辦事項清單 to do list 開始；如果對資料科學有興趣，不仿先從 IMDb 文本分類開始。

# 後記

## pandas 能不能在辦公室取代 excel ？
如果可以使用 pandas 取代辦公室之王 excel ，就不用支付微軟授權費用了！可惜的是 excel 在辦公室的地位還是難以撼動，理由有以下幾點。首先，操作 pandas 需要撰寫具備撰寫 python 語法的能力， python 的語法還沒有簡單到看一眼就學會，而在 2021 年的人們上手 excel 幾乎不需要時間。第二，多數時間我們需要對資料做不同的工作， pandas 寫成的腳本就沒有持續使用的機會，而 excel 的可視介面與簡單操作就可以快速地把工作搞定。第三，不考慮搭配 access 的情況下， excel 的短板之一是在處理大量資料速度較慢，相對地 pandas 搭配平行運算技術或其他加速工具下甚至可以處理 PB 級的數據量。然而辦公室內曾幾何時需要操作大量數據呢？呈報給主管的數據多是寥寥數行而已，使用 excel 就能完成日常工作了。pandas 與 excel 不是彼此的替代品，應該審視使用背景選擇最適用的工具。
