# Discord應用驗證清單

使用此清單確保您的Discord翻譯機器人符合Discord商店驗證的所有要求。

## 基本要求

- [ ] 申請已加入團隊（必須）
  - 按照 `TEAM_SETUP_GUIDE.md` 的步驟設置團隊
  - 確認Developer Portal顯示「Owned by: [您的團隊名稱]」

- [ ] 應用名稱及描述內容適當（已符合）
  - 確認不含有不當、冒犯或違規內容

- [ ] 添加服務條款連結（必須）
  - 按照 `GITHUB_PAGES_SETUP.md` 的步驟部署GitHub Pages
  - 在Developer Portal的「App Directory」中添加Terms of Service URL
  - 例如：`https://[您的用戶名].github.io/translation-bot-legal/terms.html`

- [ ] 添加隱私政策連結（必須）
  - 使用GitHub Pages部署的隱私政策
  - 在Developer Portal的「App Directory」中添加Privacy Policy URL
  - 例如：`https://[您的用戶名].github.io/translation-bot-legal/privacy.html`

- [ ] 具有安裝連結（已符合）
  - 確認OAuth2 URL設置正確
  - 確認已選擇正確的Bot權限

- [ ] 開發團隊成員已驗證郵件及啟用2FA（已符合）
  - 確認所有團隊成員都已啟用雙重認證

## 應用信息設置

- [ ] 應用圖標
  - 上傳512x512像素的PNG或JPG格式圖標
  - 確保圖標清晰可辨識

- [ ] 應用描述
  - 簡短描述（190字符以內）
  - 詳細描述（包含主要功能和使用指南）

- [ ] 應用標籤（至少1個，最多5個）
  - 選擇符合機器人功能的標籤（如翻譯、工具、多語言等）

- [ ] 商店圖片
  - 至少3張展示圖片（1280x720像素）
  - 確保圖片清晰展示機器人功能

## 付費訂閱設置（如有）

- [ ] 啟用付費功能
  - 在「Monetization」選項卡中啟用
  - 設置月度和年度訂閱價格

- [ ] SKU詳細信息
  - 填寫訂閱計劃名稱和描述
  - 定義退款政策

- [ ] 訂閱權限
  - 明確定義付費功能與免費功能的區別

## 文檔與品質

- [ ] 提供完整使用說明
  - 包括基本命令列表和用法
  - 添加示例說明

- [ ] 確保機器人功能正常
  - 測試所有主要功能
  - 確認錯誤處理機制

## 最終提交前檢查

- [ ] 開發者信息完整
  - 填寫準確的開發者聯繫信息

- [ ] 支持渠道可用
  - 確認支持伺服器邀請鏈接有效
  - 提供有效的聯繫電子郵件

- [ ] 所有必要的URL都使用HTTPS
  - 服務條款URL
  - 隱私政策URL
  - 支持URL

- [ ] 測試模式正確設置
  - 在提交前先使用測試模式測試付費功能

## 提交過程

1. 在「App Directory」選項卡底部點擊「Submit for Review」
2. 確認所有必要資訊已填寫完整
3. 等待審核結果（通常需要3-7個工作日）

## 注意事項

- 審核期間不能修改提交內容
- 如被拒絕，仔細閱讀拒絕原因後修正
- 審核通過後會自動發布到Discord應用商店

最後更新：2024年6月1日