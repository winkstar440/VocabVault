# 多層級雲端單字表 (Google 登入版)

支援「語言大分類 → 子資料夾」兩層結構，並使用 **Google 帳號登入** 的雲端單字學習 App。

## 功能

- **Google 登入**：資料綁定個人 Google 帳號，多裝置同步
- 兩層結構：語言大分類 → 子資料夾
- 可自由新增語言與子資料夾
- 新增 / 刪除單字
- 搜尋單字
- 文字轉語音（TTS）
- Firebase Firestore 雲端儲存

## 技術

- 純 HTML + Tailwind CSS + Vanilla JS
- Firebase Authentication (Google)
- Cloud Firestore

## 部署建議

建議使用 **Firebase Hosting** 部署，倉庫保持 Private。

## 重要設定

在 Firebase Console → Authentication → Sign-in method 中，請確認已啟用 **Google** 登入提供者。
