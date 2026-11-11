# SNIPER POKER — 六人連線遊戲 V2

## 更新內容
- 新增「退出房間」，退出者視同棄牌，其他玩家可繼續；房主離開時自動交棒。
- 移除公開行動紀錄（狙擊宣告仍公開）。
- 本局獲勝玩家及贏得籌碼在牌桌中央醒目顯示。
- 加注欄位標示「請輸入加注金額」。
- 每局開始顯示 10 秒狙擊規則，狙擊也會影響自己的牌型。

## 如何更新 GitHub
1. 請在遊戲無人進行中的時候更新；部署可能會中斷正在玩的局。
2. 解壓縮 ZIP，進入 sniper-poker-update-v2 資料夾。
3. 將 `server.js`、`index.html`、`package.json`、`render.yaml`、`README.md` 上傳並覆蓋 GitHub `sienna060111-bit/sniper-poker` 根目錄同名檔案。
4. `public/index.html` 也包含相同畫面，但現有 Render 啟動指令會從根目錄複製 index.html，故根目錄 index.html 是最重要的。
5. Render 已設置自動部署；沿用 https://sniper-poker-online.onrender.com 。

注意：伺服器目前將房間狀態保存在記憶體中，重新部署會清空當下的房間。
