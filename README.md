# 多層級雲端單字表 (VocabVault)
https://winkstar440.github.io/VocabVault/

## 目前檔案說明

| 檔案 | 說明 | 建議 |
|------|------|------|
| **`index.html`** | **最新版**：Firebase 雲端同步 + Email/密碼登入 + 編輯 + 記住狀態 + 備份 | **主要使用這個** |
| `index-local.html` | 舊的 Local Storage 本地版（保留備份） | 僅供參考 |

## 最新版功能（index.html）

- Email + 密碼登入 / 註冊
- 資料存在 Firebase 雲端，多裝置同步
- 兩層結構：語言大分類 → 子資料夾
- 新增 / 編輯 / 刪除單字
- 搜尋、發音（TTS）
- 記住上次開啟的語言與子資料夾
- 一鍵備份（複製到剪貼簿）

## 重要設定

在 Firebase Console → Authentication → Sign-in method 中，請確認已啟用 **Email/Password**。

## 部署建議

建議使用 **Firebase Hosting** 部署，倉庫保持 Private。
