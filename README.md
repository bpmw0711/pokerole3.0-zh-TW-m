# Pokerole 3.0 繁中規則站 — Android APK

用 Capacitor 把網站包成離線 App。網站內容來自 `bpmw0711/pokerole3.0-zh-TW`，每次 workflow 都會抓最新版。

## 取得 APK
1. 把這個資料夾推到 GitHub 新儲存庫（例如 `pokerole-apk`）。
2. 到 Actions → Build APK → Run workflow（push 到 main 也會自動跑）。
3. 完成後在該次執行頁面底部 Artifacts 下載 `pokerole-apk`，解壓得到 `app-debug.apk`。
4. 傳到手機，允許「安裝未知應用程式」後安裝。

## 更新內容
網站更新並 push 後，重跑 workflow 即可產生新版 APK。
