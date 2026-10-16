# PWA 打包神器（pwa-packer）

把單檔 HTML 打包成可安裝的 PWA（manifest、Service Worker、圖示、離線頁、README），並一鍵上傳到 GitHub。

**線上使用**：https://kftseng2oo1.github.io/PWA-PACKER/

## 說明
這是 [autopack](https://github.com/kftseng2oo1/autopack) 的另一份，`index.html` 功能幾乎相同（差 67 bytes）。完整功能說明請見 autopack 的 README。

## 主要功能
- 上傳 HTML，自動產生 `manifest.json`、`sw.js`、`offline.html`、圖示、`README.md`
- 打包驗證：script 數量、`</body>` 完整性、檔案大小是否異常
- 沙箱預覽對比、全部下載、透過 GitHub API 一鍵上傳

## 備註
- 建議只保留 autopack 或這個 repo 其中之一，避免兩邊改到不同版本。
