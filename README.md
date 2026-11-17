# CompanyAI Releases

CompanyAI 的公開安裝包下載區，支援 Windows 11 x64。

[下載最新版安裝包](https://github.com/you1230783-sys/CompanyAI-Releases/releases/latest/download/LM_AI_Setup.exe) · [所有版本](https://github.com/you1230783-sys/CompanyAI-Releases/releases)

請先從系統托盤離開程式，再執行安裝包。安裝位置固定為 `C:\largan\LM_AI`；Microsoft WebView2 Runtime 需另外安裝。

每版 Release 提供 `LM_AI_Setup.exe` 與對應的 `update-manifest.json`，檔案大小與 SHA-256 列於該版說明。

## 0.9.42 更新內容

- 進階功能新增「影像對照」：A／B／C 欄位可放資料夾或單張標準品，依檔名配對後同步縮放、平移並以按鍵標記。
- 標記存成 review_marks.csv，優先放影像資料夾；再次載入時會詢問是否讀入上一次的標記。
- 16 位元影像可勾選「將亮度調整相同」，方便比較各欄明暗。
- 「我的工作區」移到專案視窗，按「快速建立我的工作區」即可建立；同名時自動改為「我的工作區(1)」等。

## 0.9.41 更新內容

- 安全性更新。

## 0.9.40 更新內容

- 新增標準卡片、極簡卡片及氣泡通知，可從設定立即測試。
- 可調整透明度、文字大小與顯示時間；預設 3 秒，0 秒持續顯示直到手動關閉。
- 多則通知可展開查看，並在重疊時避開桌寵；未讀紅點可依位置分別開關。
- 版本停止支援時立即提示更新，先下載並驗證，經使用者同意後才安裝。

此儲存庫僅供發布應用程式安裝包與公開下載說明。
