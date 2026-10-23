# 多層級雲端單字表 (帳號密碼版)

支援「語言大分類 → 子資料夾」兩層結構，使用 **Email + 密碼** 登入的雲端單字學習 App。

## 功能

- **Email / 密碼登入與註冊**：資料綁定個人帳號，多裝置同步
- 兩層結構：語言大分類 → 子資料夾
- 可自由新增語言與子資料夾
- 新增 / 刪除單字
- 搜尋單字
- 文字轉語音（TTS）
- Firebase Firestore 雲端儲存

## 技術

- 純 HTML + Tailwind CSS + Vanilla JS
- Firebase Authentication (Email/Password)
- Cloud Firestore

## 部署建議

建議使用 **Firebase Hosting** 部署，倉庫保持 Private。

## 重要設定

在 Firebase Console → Authentication → Sign-in method 中，請確認已啟用 **Email/Password** 登入提供者。
