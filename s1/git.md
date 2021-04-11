# Git

# 作者：KuanHui

<img alt="git logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png" width="150px">

# Git 是什麼

以下片段節錄自維基百科    

> 自 2002 年開始，林納斯·托瓦茲決定使用 BitKeeper 作為 Linux 核心主要的版本控制系統用以維護程式碼。因為 BitKeeper 為專有軟體，這個決定在社群中長期遭受質疑。在 Linux 社群中，特別是理察·斯托曼與自由軟體基金會的成員，主張應該使用開放原始碼的軟體來作為 Linux 核心的版本控制系統。Linus Torvalds 曾考慮過採用現成軟體作為版本控制系統（例如 Monotone ），但這些軟體都存在一些問題，特別是效能不佳。現成的方案，如CVS的架構，受到 Linus Torvalds 的批評。    
>    
> 2005 年，安德魯·垂鳩寫了一個簡單程式，可以連接 BitKeeper 的儲存庫，BitKeeper 著作權擁有者拉里·麥沃伊認為安德魯·垂鳩對 BitKeeper 內部使用的協定進行逆向工程，決定收回無償使用 BitKeeper 的授權。Linux 核心開發團隊與 BitMover 公司進行磋商，但無法解決他們之間的歧見。Linus Torvalds 決定自行開發版本控制系統替代 BitKeeper，以十天的時間編寫出 git 第一個版本。     

# 為什麼要學 Git
Git 是版本控制工具。  
若開發者的世界有必須學會的工具，那一定是如何打字、如何使用電腦、如何使用 git。     
學會 git 才有能力與其他開發者一同工作。利用 git 追蹤與紀錄檔案的變化，控制版本，實現多人同時開發同一個檔案。   

# Git 的創作者
Linus Torvalds   
(1969 - 現在，51y) 
<img alt="git logo" src="https://i.pcmag.com/imagery/articles/04YGKmUR4kalhELBkVuuviO-1.fit_scale.size_1028x578.v1569488622.png" width="300px">  
大銘鼎鼎的 Linux 之父，為了管理全世界開發者對 Linux 核心提交的程式碼而以 10 天的時間開發出 git。  

# Github 是什麼

<img alt="git logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/1024px-Octicons-mark-github.svg.png" width="100px">     

GitHub 是透過 Git 進行版本控制的軟體原始碼代管服務平台，2018 年夏天被微軟以 75 億美金收購。    
Github 就像是 code 的社群軟體，它也曾被戲稱是 Gayhub，因為這個平台上的使用者多為男性。    
  
# 常用的 Git 語法
1. `git init`: 將使用者的當下位置進行 git 初始化
2. `git clone https://some.domain.com`: 將位在特定位置的 git repository (repo) 下載到 local。 
3. `git add .`: 追蹤指定檔案被做的更動。   
4. `git commit -m 'message'`: 將被追蹤的檔案更動寫入 git 紀錄中。  
5. `git push origin master`: 將 local 的 git version 推向指定的遠端 repo 的指定分支上。
6. `git remote -v`: 打印出所有遠端的 git repo。
7. `git status`: 打印出現行 git 的所偵測到的狀態。
8. `git log`: 打印出所有 git 紀錄的版本。
9. `git pull`: 將遠端 repo 的變動的項目 merge 到 local repo 上。
10. `git fetch`: 將遠端 repo 的變動項目記載到 local 上。如同將遠端 repo 的變動在 local add 上。  

[Often used git commands](https://github.com/joshnh/Git-Commands)   

# Git 軼聞

* 混蛋   
Git 一詞在有混蛋的意思，Torvalds 解釋喜歡以自身暱稱爲作品命名，而「混蛋」一詞即為他眾多暱稱之一。   

* master branch   
2020 年起美國發生 BLM 系列活動，Github 官方爲避免術語涉及非裔美國人在過往被奴役的歷史，選擇將預設的 branch 名稱「master」改為「main」，如今新創的 repository 預設的 branch 會是 main。   
