# HKTicketing Helper Runtime Rules

本儲存庫託管 [HKTicketing Helper](https://github.com/nikkedotdev/hkticketing-api) 擴充功能之公開宣告式業務規則（Runtime Configuration）。

依據 [ADR-0004](https://github.com/nikkedotdev/hkticketing-api/blob/main/docs/adr/0004-unlisted-web-store-distribution-with-runtime-configuration-sync.md)，本儲存庫僅包含純宣告式 JSON 配置（模組特徵、端點路徑、超時參數），絕不包含任何敏感憑證、API 密鑰或動態可執行代碼，完全符合 Chrome Web Store 及 Manifest V3 規範。

## 規則存取網址

```http
GET https://raw.githubusercontent.com/nikkedotdev/hkticketing-rules/main/rules.json
```
