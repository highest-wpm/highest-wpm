# Terminal 終端機

<img alt="old computer" src="https://i.pinimg.com/originals/3a/65/a5/3a65a5f4ef238fce307d0116af6b23f1.jpg" width="500px">


終端機得名於終端二字，在個人電腦還不流行的時代，一台電腦會連接多個終端控制介面給多個使用者，這個介面就叫做終端機。  
現在的電腦通常是個人電腦，已經不需要使用終端機了，人人都有一台。   
個人電腦中的終端機環境就是終端機模擬器，而運行指令的載體是 Shell Program。 

終端機的常用指令   

1. ls: list，列出當下路徑的所有檔案
2. cd: change directory，變換資料夾
3. pwd: print working directory，當前工作路徑
5. clear: 清空頁面
6. .: 意指當前資料夾位置
7. ..: 意指上層資料夾位置
9. rm: remove，徹底移除檔案



# Shell
Shel 中文翻譯成殼程式，負責將使用者輸入的指令傳遞到作業系統裡面，再將作業系統的 Output 傳到 terminal 上。  <br />
常見的 Shell program 有 bash、zsh、PowerShell，其中 bash 是 linux 預設的 shell。    <br />
上面提到的指令都能在這些 shell program 運行，然而每個 shell program 還是有些差異的。  <br />

bash 與 zsh 都將輸出的內容視為字串。  <br />
<img alt="zsh ls" src="https://miro.medium.com/max/1200/1*6yzG8wMkndJo7XxapE_Bew.png" width="500px"><br />

而 PowerShell 則把每個輸出是為物件。<br />
<img alt="PowerShell ls" src="https://programminghistorian.org/images/intro-to-powershell/intro-to-powershell2.png" width="500px"><br />
