# GitHub + Netlify 部署包

這個專案可直接上傳到 GitHub repository，再由 Netlify 連接部署。

## 內容
- index.html
- netlify/functions/supabase-config.js
- netlify.toml

## Netlify 設定
1. 在 Netlify 選擇 Add new project / Import an existing project。
2. 連接 GitHub repository。
3. 保持根目錄部署，讓 Netlify 讀取 netlify.toml。
4. 在 Netlify Environment variables 新增：
   - SUPABASE_URL
   - SUPABASE_ANON_KEY
   - SUPABASE_BUCKET

## 推薦
把 repository 預設 branch 設為 main，之後每次 push 都會自動重新部署。
