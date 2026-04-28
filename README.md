# 交易學院 v3 — 部署教學

每日 15 堂課：股票、期貨、選擇權、可轉債、權證 × 初階、中階、困難

## 部署步驟

### 1. 取得 API Key
前往 https://console.anthropic.com → API Keys → Create Key

### 2. 上傳到 GitHub
1. github.com → New repository → 名稱 `trading-academy` → Public → Create
2. uploading an existing file，上傳以下檔案：
   - index.html
   - manifest.json
   - sw.js
   - icons/icon-192.png
   - icons/icon-512.png
3. Commit changes

### 3. Vercel 部署
1. vercel.com → Sign up with GitHub
2. Add New Project → 選 trading-academy → Deploy
3. 取得網址

### 4. 安裝到手機
**iPhone**：Safari 開啟網址 → 分享 → 加入主畫面
**Android**：Chrome 開啟網址 → ⋮ → 安裝應用程式

### 5. 輸入 API Key
首次開啟輸入一次，之後自動記住。

## 費用估算
每個主題生成3堂課約 $0.006 USD
每天15堂課（5個主題）約 $0.03 USD（台幣約1元）
每月約 $0.9 USD（台幣約28元）

## 功能說明
- 5個主題各自點按鈕生成，每次產出初/中/難3堂
- AI自動避免重複已出過的主題
- 每堂課含內文、長條圖解、核心重點、測驗題
- 歷史紀錄：所有學過的課程按日期分組
- 我的最愛：點★收藏任何課程隨時回顧
- 所有資料存在裝置本機
