# 多層級雲端單字表 (VocabVault)

支援「語言大分類 → 子資料夾」兩層結構的雲端單字學習 App。

## 功能

- **兩層結構**：先選語言（日文 / 西文 / 英文 / 韓文…），再選子資料夾
- 可自由新增語言大分類與子資料夾
- 新增 / 刪除單字
- 搜尋目前語言下的單字
- 文字轉語音（TTS）
- Firebase 雲端同步（匿名登入）

## 技術

- 純 HTML + Tailwind CSS + Vanilla JS
- Firebase Authentication（匿名）
- Cloud Firestore

## 部署建議

建議使用 **Firebase Hosting** 部署，倉庫保持 Private。
