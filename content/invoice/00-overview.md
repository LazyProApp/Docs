# Lazy Invoice

> 輕鬆自在開發票

Lazy Invoice 是統一介面的電子發票開立工具，支援台灣五大加值中心，透過 AI 協助將訂單資料轉換為 JSON 格式，批次開立發票。

## 快速開始

### 線上使用
訪問 [https://invoice.lazypro.app](https://invoice.lazypro.app)

### 使用流程
1. 準備訂單資料（Excel、CSV、文字等）
2. 使用 AI 工具轉換為 JSON 格式（參考 [AI 轉換指南](02-ai-convert.md)）
3. 點擊上傳按鈕，選擇 JSON 檔案
4. 系統自動偵測平台，點擊 **Start** 開始批次開立
5. 查看開立結果（成功/失敗狀態即時顯示）

## 主要功能

### 五大平台支援
支援台灣五大電子發票加值中心：ECPay、ezPay、O'Pay、SmilePay、Amego。

上傳 JSON 後系統會自動偵測平台並切換，無需手動選擇。

### AI 輔助轉換
使用 AI 工具（如 Claude、ChatGPT）將訂單資料轉換為標準 JSON 格式。

詳見：[使用 AI 轉換訂單資料](02-ai-convert.md)

### 批次開立
一次上傳多筆發票資料，系統自動批次開立，節省重複操作時間。

詳見：[JSON 檔案格式](03-json-format.md)

### 雙模式切換
- **測試模式**：使用測試環境，不會實際開立發票
- **正式模式**：實際開立發票（需在 JSON 中設定 `production: true`）

## 常見問題

### 支援哪些加值中心？
目前支援：ECPay、ezPay、O'Pay、SmilePay、Amego 五家。

### API 金鑰會被記錄嗎？
不會。所有 API 金鑰都在你的 JSON 檔案中，系統不會儲存。

### 測試模式有限制嗎？
測試模式使用加值中心的測試環境，各平台有不同限制。

詳見：[測試環境限制](04-test-limitations.md)

### 離線使用可以嗎？
可以。若對線上版有隱私疑慮，可下載專案在本機 PHP 環境執行。
