# 標案雷達

用關鍵字追蹤政府電子採購網最近的招標與決標公告。研究用途。

- 兩組關鍵字（預設 PHAGE、waste-check），可在「關鍵字設定」自己改，一行一個。
- 只看最近 3／7／14 天；自動排除財物變賣、拍賣、出租等公告。
- 依組別、公告類型（招標、決標、無法決標、更正）和文字篩選。
- 「看預算與決標」會載入單一標案的預算金額、決標金額和廠商名稱。
- 可加到手機桌面。

網址：https://p19691221-web.github.io/tender-radar/

## 資料來源與授權

資料來自 g0v 社群的 [pcc-api.openfun.app](https://pcc-api.openfun.app/)，原始資料收集自[政府電子採購網](https://web.pcc.gov.tw/)。依其說明，限個人非營利、研究、評論等用途，引用時請註明出處。**商業用途請改用政府採購網在政府資料開放平台提供的資料集。**

資料可能有延遲或缺漏，投標前請以採購網公告為準。

## 上架（手機 GitHub 網頁版）

1. 建立公開 repo `tender-radar`。
2. Add file → Upload files，一次上傳 8 個檔案：`index.html`、`manifest.webmanifest`、`sw.js`、`icon-192.png`、`icon-512.png`、`icon-maskable.png`、`apple-touch-icon.png`、`README.md`。確認檔名沒被改成 `index-1.html`。
3. Settings → Pages → `main` / `(root)` → Save，等 1–2 分鐘。

## 限制

- 關鍵字只比對標案名稱，不比對內文。
- 每個關鍵字最多翻 3 頁結果；熱門關鍵字在 14 天內可能有漏。
- 設定存在這台裝置的瀏覽器裡。
