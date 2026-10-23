# 抓寶中醫師｜Google 智慧早報設定精靈

互動式繁體中文設定網頁，協助使用者建立自己的 Google Calendar 每日早報及特定日期提醒設定。

## 公開網站
啟用 GitHub Pages 後，網址是：

https://liaodr-beep.github.io/zaobao-gpt-wizard/

## 網站操作
1. 開啟上述網址。
2. 依序選擇功能、時區與時間、特殊日期規則、郵件收件人、早報內容。
3. 複製產生的設定指令。
4. 點擊「開啟 ChatGPT」並貼上指令。
5. 在 ChatGPT 內自行授權 Google Calendar 和 Gmail，逐步測試並確認自動寄信能力。

## 檔案
- `index.html`：可直接由 GitHub Pages 託管的互動式網站。
- `SKILL.md`：自訂 GPT 對話指引，可用於 ChatGPT GPT Builder 的 Instructions。

## 隱私與限制
這是**靜態網站**，不包含 Google OAuth 或寄信後端，表單值只在使用者自己的瀏覽器產生文字指令。**產生設定指令不等於完成排程或自動寄信。**

如果 ChatGPT 的排程執行環境無法持續呼叫 Gmail，需要另採 Google Apps Script 等實際支援排程的服務。訪客不應在公開網站輸入 Google 密碼、存取權杖或機密。
