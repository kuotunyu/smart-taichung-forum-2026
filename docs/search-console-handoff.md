# Search Console：網站發布後的操作

只需使用原先管理此網站的 Google 帳號。不需要重新建立網站、不需要購買網域，也不需要更換驗證碼。

## 1. 選對網站

開啟 [Google Search Console](https://search.google.com/search-console)，在左上角選擇：

`https://kuotunyu.github.io/smart-taichung-forum-2026/`

注意這是 GitHub Pages 網址，不是 github.com 儲存庫網址。

## 2. 審查首頁並要求更新

在最上方的網址審查欄貼上：

`https://kuotunyu.github.io/smart-taichung-forum-2026/`

按 Enter，展開網頁索引資訊，記下：

- 索引狀態（例如「網址在 Google 服務中」）。
- 上次檢索時間。
- Google 選定的標準網址。

網站已部署更新後，按「測試實際網址／測試即時網址」（介面名稱可能略異）。若測試可建立索引，按「要求建立索引」一次，看到已要求／已加入佇列即可。這不等於立即完成抓取，也不必每天重複提交。

若測試顯示錯誤、標準網址不同或按鈕無法使用，保留狀態文字再交給助理排查，先不要刪除資源或更換驗證設定。

## 3. 確認 Sitemap

左側選「Sitemap／網站地圖」。若以下網址已存在且狀態為「成功」，不需刪除或重加：

`https://kuotunyu.github.io/smart-taichung-forum-2026/sitemap.xml`

若尚未提交，新增此網址。如果輸入欄左側已固定顯示完整網站前綴，只填 `sitemap.xml`；否則貼上完整網址。按「提交」，確認成功或等待處理。

## 4. 查看曝光資料

左側「成效／搜尋結果」，日期選最近 7 天或目前可用範圍。查看查詢、曝光次數、點擊次數與平均排名。新網站可能資料很少或尚在處理，這不是提交失敗。

回報給助理時，提供索引狀態、上次檢索時間、Google 選定的標準網址、Sitemap 狀態及曝光次數即可；不要分享密碼、驗證碼或其他帳號機密。

## 本次操作界線

2026-09-06：助理在可用的 Codex 內建瀏覽器開啟 Search Console 時，被導向登入；Google 登入頁回傳 HTTP 400。當時沒有其他已連接的瀏覽器，因此無法讀取你的 Search Console 私有報表或代按要求索引。這是登入通道限制，不能據此判斷網站索引有問題。

官方參考：[要求 Google 重新檢索](https://developers.google.com/search/docs/crawling-indexing/ask-google-to-recrawl)。
