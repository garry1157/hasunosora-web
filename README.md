# 蓮ノ空女學院 活動記錄 — 視覺小說＆角色扮演網頁版 線上部署包

本壓縮包已配置好標準網站入口檔 `index.html` 與完整 `story_main/`（全 395 個原始劇本檔）。

## 方法一：Cloudflare Pages / Netlify Drop（最推薦，免寫程式、30 秒拖曳上線）
1. 將本壓縮包解壓縮為一個資料夾。
2. 前往 [Cloudflare Pages](https://pages.cloudflare.com/)（選擇 **Create application -> Pages -> Upload assets**）或 [Netlify Drop](https://app.netlify.com/drop)。
3. 直接將解壓縮後的整個資料夾拖曳到網頁上傳區，即可自動獲得一個免費的 `https://...` 公開網址！

## 方法二：GitHub Pages（永久免費託管）
1. 在 GitHub 建立一個新的公開儲存庫（Repository）。
2. 上傳本資料夾內的 `index.html` 與 `story_main/` 資料夾。
3. 進入儲存庫的 **Settings -> Pages**，在 **Branch** 選擇 `main` 並按 **Save**，等待約 1 分鐘即可透過 `https://<你的帳號>.github.io/<儲存庫名稱>/` 遊玩。

## 線上版專屬自動連動功能
- 當 `index.html` 與 `story_main/` 放在同一個網站目錄下時，點擊左下角任何一節（`Part 01`～`Part N`），網頁會自動從 `./story_main/story_main_XXXX.txt` 讀取該節全部原始分鏡；若只單獨上傳 `index.html` 一個檔案，也能直接使用內建的全 46 話精華分鏡資料庫運作。
