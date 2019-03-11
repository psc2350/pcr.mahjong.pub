# 利用大鳳林輔助舉辦雀魂團體賽
 管理员培训修订版
 作者：蘭子KKSK
## 目的
 
     進行一個32人8組每組4人的雀魂團體賽。
     分兩組，第1組和第2組。打兩輪。起始點數為100000。每人進行兩次半莊。
     第1輪
     第1組打完第1輪，決定1，2，3，4名。
     第2組打完第1輪，決定1，2，3，4名。
     第2輪
     第1組1，2名對局第2組1，2名。
     第1組3，4名對局第2組3，4名。
     （注意這裡的＂組＂＂輪＂等量詞）
## 添加書籤
 
 ![Image of Bookmark](https://i.imgur.com/i4ZUAhh.png)  

 以Chrome 為例子添加書籤    

     chrome://bookmarks/  
    
![Image of Bookmark2](https://i.imgur.com/2U2nztM.png)

 添加URL  

     javascript:void((function(){var e = document.createElement('script');e.setAttribute('src', 'https://lietxia.github.io/maj/dhs.js');document.body.appendChild(e);})());  
## 添加队员

方法1：後台添加  

     其他管理 → 查看全部組別信息 → 点击队伍名  
方法2：登入添加  

     http://000.mk/?cid=賽事ID  
登入，輸入創建隊伍時的密碼  
## 大鳳林javascript 輔助腳本介紹

開啟新標籤頁  
打開之前創的書籤  
點擊OK 後，會看到下圖：  

![Image of Logo](https://i.imgur.com/pfm98dp.png)  

在這個畫面再次開啟之前創的書籤，會跳轉至雀魂賽事後台。  
下面有大鳳林javascript 輔助腳本。  

![Image of Dashboard](https://i.imgur.com/NVgU7IK.png)  

登入自己的雀魂帳號  
在下方的大鳳林javascript 輔助腳本輸入  
賽事ID，回合，日期，賽事密碼，並且點擊右邊的重載數據。  

![Image of script](https://i.imgur.com/tUFJzOJ.png)  

## 讀取牌普

上一步驟腳本所能自動填寫的技城分數來源於這一步驟所讀取的牌普。  
讀取的數據會上傳至大鳳林作者小模的服務器，並顯示在大鳳林網站上。  

![Image of loadrecord](https://i.imgur.com/QQcBSZi.png)  

點擊腳本的『讀取牌普』即可。  
待腳本將牌普讀取完畢，右邊會出現牌普信息，點擊發送後，會出現發送完畢的消息。  

![Image of sentrecord](https://i.imgur.com/Ofj4SD8.png)  

## 開始對局
參賽選手全準備好之後  
點擊開始某個組  

![Image of startgame](https://i.imgur.com/iHWxkuh.png)  

選擇所要開始對局的組，將會顯示要開始對局的選手，以及所繼承的分數。  

![Image of groupselection](https://i.imgur.com/Wnb4oWi.png)  

點擊開始之後  
腳本會替操盤手自動添加選手，並且自動填寫繼承的分數。  
代腳本結束動作，操盤手只需要填寫標籤，並點擊雀魂後台的『對局開始』即可。  