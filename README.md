# 重返戰場 — 魔獸地圖修復工坊

部署於 GitHub Pages 的純靜態 SPA，無建置依賴。地圖檔案保留在 Google Drive。

## 功能

- 地圖搜尋、分類、驗證狀態篩選及排序。
- 每張地圖的修復內容、版本紀錄、測試限制及下載資料夾入口。
- 修復進度總覽、遊玩指南、瀏覽器本機收藏。
- GitHub Issues 問題回報入口，需要 GitHub 帳號。
- Hash 路由，支援 GitHub Pages 子路徑與重新整理。

## 維護

修改 `data.js` 更新地圖內容與 Drive 連結。資料為人工整理，不會自動同步 Google Drive。首頁及進度摘要數字依資料自動計算。驗證狀態應分別記錄程式檢查與遊戲實測，不得混用。

`npm run dev` 在 http://127.0.0.1:5173 啟動。`npm run check` 檢查 JavaScript 語法。

GitHub 儲存庫 Settings → Pages → Source 選 GitHub Actions。推送 main 會部署網站。

收藏只存在目前瀏覽器，沒有會員登入、跨裝置同步或內建留言。完整留言服務可另外整合。

## 設計

深色橄欖灰、暖金、細邊框與漢字幾何封面。無 Emoji，無虛構流量、評分或留言。封面是原創字體與幾何構圖，不代表遊戲實際截圖。

資訊結構參考 [HIVE](https://www.hiveworkshop.com/repositories/maps.564/) 與 [Epic War](https://www.epicwar.com/maps/)。地圖權利歸原權利人所有。
