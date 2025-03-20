# 使用GitHub Pages發布服務條款和隱私政策

Discord應用在商店發布時需要提供服務條款和隱私政策的公開鏈接。以下是使用GitHub Pages發布這些文件的步驟。

## 步驟1：創建GitHub儲存庫

1. 登入您的GitHub帳戶
2. 點擊右上角的"+"圖標，選擇"New repository"
3. 命名儲存庫，例如：`translation-bot-legal`
4. 勾選"Add a README file"選項
5. 點擊"Create repository"按鈕

## 步驟2：上傳條款和隱私政策文件

1. 在新儲存庫中，點擊"Add file"按鈕，選擇"Upload files"
2. 將以下文件拖拽到上傳區域：
   - 將 `TERMS_AND_PRIVACY.md` 重命名為 `index.md`（或上傳後再重命名）
3. 點擊"Commit changes"按鈕

## 步驟3：設置GitHub Pages

1. 在儲存庫頁面，點擊"Settings"選項卡
2. 在左側菜單中，點擊"Pages"選項
3. 在"Source"部分，選擇"Deploy from a branch"
4. 在"Branch"下拉菜單中，選擇"main"分支和"/(root)"文件夾
5. 點擊"Save"按鈕
6. 等待幾分鐘，GitHub Pages將被啟用

## 步驟4：添加自定義主題（可選但推薦）

1. 在儲存庫的根目錄中，點擊"Add file"按鈕，選擇"Create new file"
2. 將文件命名為"_config.yml"
3. 添加以下內容：
```yaml
remote_theme: pages-themes/cayman@v0.2.0
plugins:
- jekyll-remote-theme
title: 多語言翻譯機器人 - 法律文件
description: 服務條款與隱私政策
```
4. 點擊"Commit new file"按鈕

## 步驟5：分離條款和隱私政策（推薦）

為了更專業的展示，您可以將服務條款和隱私政策分為兩個獨立的頁面：

1. 在儲存庫中，創建兩個新文件：
   - `terms.md`：包含服務條款部分
   - `privacy.md`：包含隱私政策部分
   
2. 在`index.md`中添加鏈接：
```markdown
# 多語言翻譯機器人 - 法律文件

歡迎使用多語言翻譯機器人。請查閱我們的法律文件：

- [服務條款](terms.html)
- [隱私政策](privacy.html)
```

## 步驟6：獲取您的鏈接

1. 一旦GitHub Pages啟用，您將在Settings > Pages頁面看到一個網站URL
2. 您的網址將是 `https://[您的用戶名].github.io/translation-bot-legal/`
3. 服務條款獨立頁面： `https://[您的用戶名].github.io/translation-bot-legal/terms.html`
4. 隱私政策獨立頁面： `https://[您的用戶名].github.io/translation-bot-legal/privacy.html`

## 步驟7：在Discord開發者門戶添加鏈接

1. 登入 [Discord Developer Portal](https://discord.com/developers/applications)
2. 選擇您的機器人應用
3. 在"App Directory"選項卡中：
   - 添加服務條款URL：`https://[您的用戶名].github.io/translation-bot-legal/terms.html`
   - 添加隱私政策URL：`https://[您的用戶名].github.io/translation-bot-legal/privacy.html`
4. 保存更改

## 注意事項

- GitHub Pages可能需要幾分鐘才能生效
- 確保您的文檔符合Discord的要求
- 定期更新您的條款和隱私政策
- 在發布前，檢查鏈接是否正常工作

## 問題排解

如果您的GitHub Pages未正確顯示：
1. 確認您的文件使用正確的Markdown格式
2. 確保儲存庫設置中GitHub Pages已啟用
3. 等待幾分鐘，GitHub Pages生效需要時間
4. 檢查儲存庫中是否存在名為".nojekyll"的文件，如果沒有，可以創建一個空的此文件

完成這些步驟後，您將擁有永久的服務條款和隱私政策鏈接，滿足Discord應用商店的發布要求。