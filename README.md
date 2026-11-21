# 殭屍體操間歇計數器

單一靜態網頁版殭屍體操間歇計時與組數累計工具，可直接部署至 GitHub Pages 使用。

## 功能特色

- 預設標準節奏：原地慢跑甩手 60 秒 ＋ 原地踏步放鬆 30 秒，共 3 組（總時數 04:30）
- 支援自訂目標組數、慢跑秒數、踏步秒數與快速預設，並即時計算總時數
- 提供提示音與中文語音切換、跳過此段、結束運動、重設本輪與手動 `+1 組`
- 自動於瀏覽器 `localStorage` 累計今日組數、今日時間、歷史總組數與歷史總運動時間

## 部署到 GitHub Pages

1. 在 GitHub 建立一個新的 Repository（公開或私人皆可）。
2. 將本資料夾內的 `index.html` 與 `README.md` 上傳至 Repository 根目錄。
3. 前往 Repository 的 **Settings → Pages**，在 **Build and deployment** 選擇 **Deploy from a branch**，分支選 `main`（資料夾 `/ (root)`）後儲存。
4. 稍候約 1 分鐘即可透過 GitHub Pages 網址在手機或電腦瀏覽器開啟使用。
