# 2026 西葡之旅 PWA

`trip-data.json` 是主要行程資料來源。旅途中修改行程時，優先修改這個檔案，不要重寫 `index.html`。

- `index.html`：App UI
- `trip-data.json`：每日行程與航班資料
- `manifest.json`：PWA
- `sw.js`：離線快取
- `.github/workflows/pages.yml`：GitHub Pages 自動發布
