# 餐廳清單
這是一個用 Node.js 和 Express 打造的餐廳清單。此清單列出餐廳的基本資訊，點餐廳的圖片即能夠看到詳細的介紹，同時也能透過關鍵字搜尋你想找的餐廳。

## Features 產品功能
- 列出所有餐廳
- 可以透過關鍵字搜尋相關的餐廳
- 點擊你想查看的餐廳就能夠看到詳細的介紹，例如地址、電話、簡介等。

## Install 安裝以及執行步驟
1. Clone此專案至本機
```
git colne https://github.com/ezcomenezgo/Restaurant-List.git
```
2. 進入專案的資料夾
```
cd restaurant_list
```
3. 安裝npm套件
```
npm install
```
4. 安裝nodemon
```
npm i -g nodemon
```
5. 啟動伺服器，執行app.js
```
nodemon app.js
```
6. 此時終端機如果出現以下字樣表示伺服器與資料庫已啟動並成功連結
```
Restaurant List is running on localhost:3000
```
7. 在瀏覽器輸入http://localhost:3000 即可開始瀏覽