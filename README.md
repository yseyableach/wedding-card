# wedding-card

Jay & Tilly 的婚禮電子喜帖，採 **極簡白金婚禮感**、**手機優先** 的單頁式設計。

## 已完成內容

- 新人：Jay & Tilly
- 婚宴日期：2027/05/01
- 開桌時間：11:30
- 地點：台北萬豪酒店 36F 寰宇廳
- Google 地圖導航按鈕
- LINE 聯絡按鈕
- Google 表單 RSVP 區塊預留
- 照片資料夾與 placeholder 圖片預留

## 專案結構

```text
.
├── index.html
├── README.md
├── AGENTS.md
└── assets/
    └── photos/
        ├── cover.svg
        ├── gallery-1.svg
        ├── gallery-2.svg
        └── gallery-3.svg
```

## 後續換成正式照片

未來婚紗照拍好後，優先替換：

- `assets/photos/cover.svg`：首頁主視覺，建議用直式婚紗照或半身合照
- `assets/photos/gallery-1.svg`：照片區主圖，建議用橫式氛圍照
- `assets/photos/gallery-2.svg`：照片區輔助圖
- `assets/photos/gallery-3.svg`：照片區輔助圖

若改成 `.jpg` 或 `.png`，請同步更新 `index.html` 裡的圖片路徑。

## 後續待補

- Google 表單正式連結
- 最後回覆期限
- 是否補停車資訊或更完整交通說明
- 正式婚紗照裁切與照片順序調整

## AI / Codex 維護說明

此 repo 另提供 `AGENTS.md`，作為 coding agent 的維護指南。  
若後續使用 Codex、Claude Code 或其他 AI coding agent 迭代，先讀 `README.md` 與 `AGENTS.md` 再改版，可降低把版面改壞的機率。
