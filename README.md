# 2026 Smart Taichung 智慧台中論壇 · 個人整理

2026 年 8 月 26 日「2026 Smart Taichung 智慧台中論壇」八個場次的重點整理、摘要與逐場筆記，非官方個人整理與再詮釋。
主軸是 Physical AI 與臺中智慧城市（台中智慧城市）的落地條件：無人載具、機器人產業鏈、5G SA 與城市驗證場域。

亦作：智慧臺中論壇、智慧台中、智慧臺中、Smart Taichung、Smart Taichung Forum。

An unofficial, independent compilation of all eight sessions of the 2026 Smart Taichung Forum
(Taichung, Taiwan, 26 August 2026): Physical AI, smart-city platforms, uncrewed vehicles and the robotics supply chain.

本頁網址：<https://kuotunyu.github.io/smart-taichung-forum-2026/>

原活動官網：<https://www.smarttaichung2026.com/>（主辦單位，非本專案）

## 內容架構

| 章節 | 錨點 | 內容 |
|---|---|---|
| 核心結論 | `#quick-review` | 五項跨場結論與全日論述 |
| 場次總覽 | `#session-matrix` | 八場用同一組問題並排比較 |
| 延伸分析 | `#archive-analysis` | 城市系統、從願景到可營運、技術解析 |
| 完整資料 | `#archive-program` | 八場逐場筆記、論證地圖、時程表；全文搜尋與篩選 |
| 研究工具 | `#archive-research` | 論壇沒有回答的問題、名詞速查、常見問題、方法與來源 |

## 檔案說明

| 檔案 | 用途 |
|---|---|
| `index.html` | 網站本體。單檔、零外部資源，理由見下節 |
| `llms.txt` | 給 AI 搜尋讀的結構化摘要與常見問答 |
| `sitemap.xml` | 提交給搜尋引擎的網址清單 |
| `53ad7fa7….txt` | IndexNow 金鑰，供 Bing／Yandex 等在內容更新時即時重新抓取。檔名必須等於金鑰內容、必須是十六進位、且必須放在站台根目錄才能授權整站，三者皆無法更動 |
| `assets/og-card.png` | 社群分享卡 |
| `.nojekyll` | 讓 GitHub Pages 跳過 Jekyll 處理 |

## 技術取捨

整站是一個 HTML 檔，CSS 與 JS 內嵌，不載入任何外部資源，字型也走系統字型堆疊。這是刻意的：單一請求載完、首次渲染不被任何東西阻塞、離線可完整閱讀。
中英文以 `<i18n-zh>` / `<i18n-en>` 並存於同一份 DOM，切換語言不重新載入；全文搜尋、章節導覽與深淺色也都在這一份檔案內完成。

## 來源分層

- 講者主張：論壇中提出的說法，不自動等同已驗證事實。
- 整理者判讀：跨場統整與工程／治理觀點，非講者原話，也非主辦單位立場。
- 未能另行查證的數字，標示為「講者案例數據」或「外部報導」。

## 授權

整理者自己的著作部分（重點整理、摘要、逐場筆記、圖解與跨場分析，以及承載它們的 HTML／CSS／JS）
以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 授權：可自由重製、散布、改作與商業使用，**條件是標示出處**。

建議的標示方式：

> 資料來源：kuotunyu，《2026 Smart Taichung 智慧台中論壇：八場次重點整理、摘要與逐場筆記》
> （非官方個人整理），<https://kuotunyu.github.io/smart-taichung-forum-2026/>，CC BY 4.0

**不在授權範圍內**：講者主張的原始內容、企業與機構名稱及商標、外部報導與其連結資料。
這些權利屬各自權利人，本授權不及於此。

## 內容界線

本頁不是主辦單位網站、活動新聞稿，也不是逐字紀錄；官方議程與講者資訊請以原活動官網 <https://www.smarttaichung2026.com/> 為準。講者主張、企業與機構名稱屬各自權利人；圖解與跨場分析為整理者的個人再詮釋。
引用時請標示「非官方個人整理」並附上網址；收到可核對的更正資料，會保留更正日期、來源與理由。
