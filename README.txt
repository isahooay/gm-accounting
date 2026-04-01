GM工作室｜極速記帳 PWA 整包

檔案：
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

上線前要改：
1. index.html 內的 APP_SHARE_URL
   預設是 https://example.com
   請改成你的正式網址

2. 第 5 頁分享 QR 會跟著 APP_SHARE_URL 一起更新

部署：
- 上傳整包到 GitHub Pages
- 或任何可提供 HTTPS 的靜態網站空間

PWA 安裝：
- iPhone：Safari → 分享 → 加入主畫面
- Android：Chrome → 安裝 App
