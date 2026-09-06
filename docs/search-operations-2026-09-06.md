# 搜尋可讀性改善與發布紀錄

日期：2026-09-06（Asia/Taipei）

## 已完成

- 原網址與 canonical 維持 `https://kuotunyu.github.io/smart-taichung-forum-2026/`。
- 五個章節改為連續閱讀；九段主要詳細筆記及四組來源預設展開，保留收合控制。
- 標題、總結開頭與中英文說明一致；發布日期仍為 2026-09-02，修改日期為 2026-09-06。
- 移除 meta keywords、sitemap priority/changefreq 與 llms.txt 的重複關鍵詞清單；修正 IndexNow 和 llms.txt 效果的說明。
- 已準備 [Search Console 操作指南](search-console-handoff.md) 與 [分享貼文草稿](search-sharing-draft.md)。尚未發社群貼文或聯絡他人。

## 驗證

- 修改前：只有一章顯示，九段筆記與四組來源全數收合。
- 修改後：五章顯示、九段筆記展開、四組來源展開；保留八場次及全部原有錨點。
- 靜態檢查：147 個 ID 無重複、52 個內部錨點連結有效、JSON-LD 可解析、兩個 JavaScript 區塊通過語法檢查，canonical 與 sitemap 相符。
- 瀏覽器檢查：筆記收合／展開、搜尋 5G 只顯示 session-06、清除篩選恢復八場、中英文切換、主題切換與 session-06 深連結通過。
- 1280px 與 390px 版面未發現整頁橫向溢出；瀏覽器未記錄 JavaScript error。
- 獨立程式碼審查沒有未解決的問題；英文摘要同步建議已修正。

## 發布及通知證據

- 網站內容發布提交：`fd8fe26c9543f32a0de449c72e49bb69ee2a6b4e`。
- GitHub Pages build 狀態為 built，沒有錯誤。
- 正式首頁回傳 HTTP 200；正規化換行後，HTML 與本機驗證版本完全一致。
- 正式瀏覽器再次確認五章、九段筆記及四組來源的初始顯示狀態。
- 2026-09-06 21:50（UTC+08:00）向 IndexNow 提交首頁，明確傳入本專案的 keyLocation；驗證檔回傳 200，IndexNow 回傳 200。
- IndexNow 的 200 僅表示通知已收到，不代表已索引，更不代表 Google 排名已提升。

## 必須由擁有者接手

Search Console 登入在目前可用瀏覽器回傳 Google HTTP 400，沒有其他連接的瀏覽器。未能查看私有索引／成效報表，也未代按 Google 要求建立索引或提交 sitemap。請依操作指南完成並回報結果。

2026-09-06 的 Google site 查詢已看到本站；一般「智慧台中論壇 筆記」查詢的當次第一頁未看到本站。後續應以 Search Console 曝光與查詢資料觀察，不能將技術驗證結果當作排名成效。
