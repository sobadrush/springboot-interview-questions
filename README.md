# SpringBoot 面試題庫

多頁面 Spring Boot 面試評分工具，提供進階技術問答（面試題 A）與基礎能力 Checklist（面試題 B），適合面試官依候選人層級選擇使用。

線上頁面：

https://sobadrush.github.io/springboot-interview-questions/

## 頁面結構

| 頁面 | 說明 |
|------|------|
| `index.html` | 統一入口，選擇面試題 A 或 B |
| `interview-a.html` | 面試題 A：進階技術問答 |
| `interview-b.html` | 面試題 B：基礎問題 Checklist |

## 面試題 A — SpringBoot 技術面試

適合中高階 Java 工程師。

- 14 道 Spring Boot 進階技術問答，依面試流程排列
- 涵蓋 DI/AOP、Spring Data JPA、Transaction、REST 設計、OKHttp3、錯誤處理、Mock 測試、Java Stream、Design Pattern 與大流量架構
- 每題可標記候選人程度：`L`、`M`、`H`
- 每題提供觀察重點、參考解答與備註欄
- 第 12 題提供 Java Stream 例題資料 popup
- 可匯出已填妥狀態的 HTML 面試紀錄

### 評分層級

| 等級 | 說明 |
|------|------|
| `L` | 理論派，實務經驗不足 |
| `M` | 具備基礎，需要磨練 |
| `H` | 有工程判斷力，值得加分 |

## 面試題 B — 基礎問題 Checklist

適合初階 Java 工程師。

- 6 大類別、26 道基礎能力確認項目，100 分制
- 涵蓋：專案經驗、Java 基礎、Spring Boot 基礎、API 基礎、資料庫基礎、Git / 協作
- 每類別即時顯示得分，總分進度條同步更新
- 面試結論三選一：建議錄取 / 可錄取需帶領 / 不建議錄取
- 可匯出已填妥狀態的 HTML 面試紀錄

## 使用方式

1. 開啟 GitHub Pages 網址，在首頁選擇面試題 A 或 B
2. 填寫候選人、面試官、面試時間與整體備註
3. 依序進行面試並記錄結果
4. 面試結束後點擊「匯出結果」，下載 HTML 紀錄

## 專案內容

靜態頁面，不需要後端服務或額外建置流程：

- `index.html`：入口選擇頁
- `interview-a.html`：進階技術面試評分工具
- `interview-b.html`：基礎問題 Checklist
- `README.md`：專案說明
