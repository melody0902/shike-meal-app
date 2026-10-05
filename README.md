# 食刻

依個人飲食條件推薦這餐吃什麼。繁體中文，支援手機與桌面。

## 本機開啟

在本目錄執行：

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory dist
```

在瀏覽器開啟 http://127.0.0.1:4173 。不需安裝 Node 套件或設定 API 金鑰。

## 檔案

- `SPEC.md`：已確認的 MVP 規格與完成範圍。
- `dist/index.html`：網頁入口。
- `dist/style.css`：手機與桌面樣式。
- `dist/data.js`：60 道餐點、材料、條件標記、簡要做法。
- `dist/app.js`：篩選、排序、畫面、設定與本機儲存。
- `QA.md`：驗證紀錄與目前限制。

## 資料說明

僅將資料存於此瀏覽器，無帳號、無跨裝置同步，沒有第三方分析工具。價格與時間為估算，外食是點餐構想而非店家成分保證。示範食譜仍需依實際包裝及店家確認成分。

## 圖片

首頁蔬菜碗照片：Cup of Couple / Pexels。
來源：https://www.pexels.com/photo/rice-bowl-on-top-of-a-table-7660431/
授權：https://www.pexels.com/license/
圖片僅為飲食情境示意，不代表每一道推薦餐點。
