## 請解釋後端與前端的差異。
```前端：是指使用者看的到的部分，像是網頁等等，包含：HTML、CSS、JavaScript。廣義的前端也包含手機的APP。```

```後端：開發者端，包含DNS、伺服器的server和Database等，使用者看不到的部分```


## 假設我今天去 Google 首頁搜尋框打上：JavaScript 並且按下 Enter，請說出從這一刻開始到我看到搜尋結果為止發生在背後的事情。
```當我發一個 request 給 google 網頁的時候，網頁會指使系統，系統指使硬碟，硬碟指使電腦的網卡，發送 request，中間經過 DNS，DNS 告訴我們 google 的 server 在哪個 IP 位置，之後 request 再傳到 google 的 server。google 接收到後 request 後，再傳給 database。database 之後會回傳資料給 server，之後再傳一個 response（ html 檔案 ）給網路卡。網卡給硬碟，再給作業系統，再給瀏覽器，最後呈現給使用者看。```


## 請列舉出 3 個「課程沒有提到」的 command line 指令並且說明功用
1. `whoami` 檢視自己是否為有效的用戶
2. `exxit` 關閉 terminal
3.  `top` 顯示電腦負載狀態，或是各種系統資訊
