# 邊境人生模擬器(iOS 主畫面 App)

PWA 版本,可加入 iPhone / iPad 主畫面,全螢幕執行、可離線遊玩。

## 部署(需 HTTPS)
把 `borderlife/` 資料夾放到任一靜態主機即可,例如:
- GitHub Pages:Settings → Pages → 選此分支,網址為 `https://<帳號>.github.io/<repo>/borderlife/`
- Netlify / Cloudflare Pages / Vercel:直接拖曳資料夾

## 安裝到主畫面
1. 用 **iPhone 的 Safari** 開啟上述網址
2. 點下方「分享」按鈕 → **加入主畫面**
3. 從主畫面圖示開啟,即為獨立全螢幕 App(首次開啟需連網以載入字型,之後可離線)

## 檔案
- `index.html` 遊戲本體
- `manifest.webmanifest` / `sw.js` PWA 設定與離線快取(更新遊戲後請把 `sw.js` 的 `CACHE` 版本號 +1)
- `icons/` App 圖示
