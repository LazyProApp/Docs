![Lazy PageSpeed](../assets/images/og-image.png)

> 天下網頁，唯快不破

Lazy PageSpeed 是 Google PageSpeed Insights API 的增強工具，批次分析多個網址，產生完整報告供 AI 分析。

## 快速開始

### 線上使用
訪問 [https://pagespeed.lazypro.app](https://pagespeed.lazypro.app)

### 使用流程
1. 點擊右上角 **+ New** 新增網址（免費版最多 3 個）
2. 點擊底部 **Start** 開始分析
3. 完成後點擊 **Analyze** 查看報告
4. 使用 **Download** 下載 Markdown 報告給 AI 分析

## 主要功能

### 批次分析
一次分析多個網址，支援 Mobile 和 Desktop 兩種裝置。

詳見：[快速開始](01-quick-start.md)

### Pro 模式
使用自己的 API Key，無網址數量限制。

詳見：[Pro Mode 切換按鈕](04-pro-mode-toggle.md)

### 報告下載
- **Markdown 報告**：精簡格式，適合貼給 AI 分析
- **JSON 原始檔**：完整資料，可重新匯入

詳見：[下載 Markdown 報告](09-download-report.md)、[Download 下載 JSON](07-download-button.md)

### 報告分享
產生分享連結讓團隊協作（需設定 R2）。

詳見：[Share 分享報告](06-share-button.md)

## 常見問題

### 免費版有限制嗎？
免費版最多分析 3 個網址。需要更多請使用 Pro 模式（需申請 Google API Key）。

### API Key 會被記錄嗎？
不會。Pro 模式直接從瀏覽器呼叫 Google API，中間沒有伺服器。

### 報告分享功能是必須的嗎？
不是。報告分享功能是選用的，需要自己設定 Cloudflare R2。

詳見：[分享功能限制](10-share-limitations.md)

## 報告範例

![PageSpeed 分析報告](../assets/images/2-report.png)
