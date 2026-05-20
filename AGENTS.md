# AGENTS.md

這個 repo 是 Jay & Tilly 的婚禮電子喜帖靜態頁面。

## 專案目標
- 維持「極簡白金婚禮感」與手機優先體驗。
- 保持單頁式電子喜帖，資訊清楚、載入簡單。
- 後續照片、Google 表單連結與細節資訊應容易替換。

## 主要檔案
- `index.html`：主頁面與全部樣式。
- `assets/photos/cover.svg`：首頁主視覺預留圖。
- `assets/photos/gallery-1.svg`：照片區主圖預留圖。
- `assets/photos/gallery-2.svg`：照片區輔助圖 1。
- `assets/photos/gallery-3.svg`：照片區輔助圖 2。
- `README.md`：專案說明與替換指南。

## 編修規則
1. 優先顧手機版，桌機版其次。
2. 首屏避免資訊過密，保留留白與照片主導感。
3. 新增內容前先確認不會破壞既有的 LINE、Google Maps、婚宴資訊。
4. Google 表單目前尚未接入，保留 CTA 區塊，後續只替換連結與按鈕文字。
5. 真實婚紗照上線時，優先替換 `assets/photos/` 內圖片並視需要調整 `object-fit` / 裁切位置。
6. 若改動圖片檔名，需同步更新 `index.html` 與 `README.md`。

## 驗收清單
- 手機寬度下首屏不擁擠。
- Jay & Tilly、2027/05/01、11:30、萬豪 36F 寰宇廳可清楚辨識。
- Google Maps 與 LINE 連結可正常點擊。
- 圖片 placeholder 顯示正常。

## 給 coding agent 的工作方式
- 先讀 `README.md` 與 `index.html` 再修改。
- 每次修改盡量維持小範圍、可回顧。
- 若需求涉及視覺大改版，先保留既有版本再迭代。
