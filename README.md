# SpringBoot 技術面試

這是一個單頁版 Spring Boot 技術面試評分工具，適合面試官在面試過程中逐題記錄候選人的回答狀態、技術深度與備註。

線上頁面：

https://sobadrush.github.io/springboot-interview-questions/

## 功能

- 依面試流程編排 Spring Boot、Java、測試、設計模式與架構題
- 每題可標記候選人程度：`L`、`M`、`H`
- 每題提供觀察重點、參考解答與備註欄
- 每題顯示分類，例如：Spring 核心、Web API、架構、設計模式、開發技術
- 第 12 題提供 Java Stream 例題資料 popup
- 可匯出已填妥狀態的 HTML 面試紀錄，方便留存或分享

## 評分層級

- `L`：理論派，實務經驗不足
- `M`：具備基礎，需要磨練
- `H`：有工程判斷力，值得加分

## 使用方式

1. 開啟 GitHub Pages 網址
2. 填寫候選人、面試官與整體備註
3. 依序詢問題目，並點選每題的 `L`、`M` 或 `H`
4. 視需要點擊「看解答」或「例題」
5. 面試結束後點擊「匯出結果」，下載 HTML 紀錄

## 專案內容

此 repository 僅包含靜態頁面：

- `index.html`：互動式面試評分工具
- `README.md`：專案說明

不需要後端服務或額外建置流程，GitHub Pages 會直接發布 `main` branch 根目錄的 `index.html`。
