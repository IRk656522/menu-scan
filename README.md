# 點單掃描・銅板麵店

拍紙本點單 → Gemini 辨識手寫數量（數字／正字、「大」）→ 算金額結帳 → 手機本機統整業績。

- 網址：https://irk656522.github.io/menu-scan/
- API Key 與點單資料只存在使用者的手機瀏覽器（localStorage / IndexedDB），不會上傳到這個 repo。
- 設定頁可匯出 CSV、備份／還原 JSON、修改菜單價格。

## 多家店
- 銅板麵店：`/menu-scan/`、客人點餐 `/menu-scan/order.html`（菜單在 `menu.js`）
- 食方客：`/menu-scan/?shop=shifangke`、客人點餐 `/menu-scan/order.html?shop=shifangke`（菜單在 `shops/shifangke.js`）
- 每家店的點單、業績、設定分開存。新增店家＝在 `shops/` 加一個菜單檔。
