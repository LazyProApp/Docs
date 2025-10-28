![Lazy PageSpeed](../assets/images/og-image.png)

> 天下網頁，唯快不破

Lazy PageSpeed 是 Google PageSpeed Insights API 的增強工具，僅花費極少的時間就能整理好大量網址的分析報告，再交由 AI 整理分析，取代手動操作與整理，用最短的時間取得全面性的完整分析報告。

## 功能特色

- **批次分析**: 可以快速分析多個網址
- **完整報告下載**: JSON 原始資料 + Markdown 精簡格式
- **AI 友善**: 報告格式優化，可直接貼給 AI 分析
- **雙模式**: 免費版（3 個網址）/ Pro 模式（無限制）
- **報告分享**: 產生分享連結讓團隊協作
- **零信任架構**: API Key 和報告資料都在你自己掌控中

## 分析流程說明

**PSI 分析流程**：
```
網址 → PageSpeed Insights 網頁 → 看結果 → 截圖/手動複製 → 難給 AI 分析
       (每次一個)                   (無法下載)      (片段資訊)
```

**Lazy PageSpeed 分析流程**：
```
多個網址 → Lazy PageSpeed → PageSpeed API → 完整報告下載
          (批次處理)         (自動呼叫)      (JSON + Markdown)
                                                    ↓
                                        ┌───────────┴───────────┐
                                        ↓                       ↓
                                  逐一給 AI               資料夾 + 提示
                                   單頁分析                  系統性總結
```

## 報告範例

![PageSpeed 分析報告](../assets/images/2-report.png)

## 快速開始

請參閱 [快速開始](content/01-quick-start.md) 章節。
