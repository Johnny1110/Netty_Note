# Netty 筆記

<br>

-----------------------

<br>


## 簡介

這裡是我練習 netty 的筆記，記錄一些實作例子。

<br>

## 單元

<br>

*   ### 實作練習
    
    1.  [FatCat](./fatcat)

	    FatCat 是一些最基本的 Netty 網路應用實作集合專案，最初從實作一對 Echo Server Client 到
	    後面實作更進階項目。也是我開啟練習的第一個 Netty 項目。
	    
	    後面逐漸新添加了一些好玩的實作，例如線上聊天室、UPD 廣播等。
	
	<br>
	
*   ### Netty 組件
	
    1.  [ByteBuf 使用](./nettynote-bytebuf)

        ByteBuf 是 Netty 的資料傳輸容器。這邊透過實際操作 ByteBuf API 來學習。
        
    2.  [Channel 相關](./nettynote-channel)
    
        Channel 是 Netty 的連線。其衍伸出來的相關組件，則是處理連線傳輸資訊的業務邏輯。這邊簡單介紹一下一些基本組件的使用方法。