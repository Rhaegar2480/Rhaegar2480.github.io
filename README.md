# Rhaegar2480.github.io

Google Play 上架用應用程式靜態頁面與政策文件庫（GitHub Pages）。

## HTML 頁面規範

1. **獨立資料夾結構**：每個 App 於根目錄下建立對應小寫資料夾（例如 `streakping/`、`finditongm/`、`findmycar/`），並包含 `privacy-policy.html` 與 `terms-of-service.html`。
2. **雙語切換與預設語系**：
   - 所有條款與政策 HTML 頁面**必須提供「English / 繁體中文」切換按鈕**（置於頁面右上角）。
   - **預設顯示語言為英文（English）**，確保 Google Play 審查人員與全球使用者開啟時皆能直接閱讀；切換後即時顯示完整對應語系內容。
3. **AdMob `app-ads.txt`**：根目錄維護 `app-ads.txt` 以供 AdMob 驗證。
