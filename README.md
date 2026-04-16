# GitHub + Netlify 精準補齊修正版

## 已修正重點
- 補齊 `setSelectMode()`
- 補齊 `carouselPhotos()`
- 補齊 `getSlideshowItems()`
- 補齊 `filteredPhotos()`
- 補齊 `toggleSelection()`
- 補齊 `updateSelectionUI()`
- 補齊 `openPreview()`
- 保留單檔 `index.html`，避免外部 assets 404

## 部署
1. 將整包推到 GitHub repository 根目錄。
2. 使用 Netlify 連接 GitHub repo。
3. 設定 `SUPABASE_URL`、`SUPABASE_ANON_KEY`、必要時設定 `SUPABASE_BUCKET`。
4. 在 Supabase Auth 設定正式網址 redirect URL。
