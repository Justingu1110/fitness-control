# 🔥 卡路里日記

手機用的熱量記錄小 App:輸入食物自動帶入熱量、輸入運動自動計算消耗,
還有體重情境模擬。所有記錄只存在你手機的瀏覽器裡,不會上傳。

**App 網址:https://justingu1110.github.io/fitness-control/**

## 📲 安裝到手機 (加入主畫面)

| 手機 | 步驟 |
|---|---|
| iPhone (Safari) | 打開上面網址 → 點下方「分享」⬆️ → 「加入主畫面」→ 完成 |
| Android (Chrome) | 打開上面網址 → 右上「⋮」→ 「加到主畫面」(或「安裝應用程式」) → 完成 |

之後桌面上會出現可愛的小火焰圖示,點開就是全螢幕 App。

## ✏️ 想改程式?直接在手機上改

整個 App 就是一個檔案:`index.html`。改完存檔,網站 1~2 分鐘內自動更新。

- **方法一 (最簡單)**:用手機瀏覽器打開這個 repo → 點 `index.html` → 點鉛筆 ✏️ →
  修改 → 按綠色「Commit changes」→ 等 1~2 分鐘重新整理 App 即可。
- **方法二 (請 AI 改)**:在手機上開 Claude Code (claude.ai/code) → 連到
  `justingu1110/fitness-control` → 用說的告訴它要改什麼。

## 檔案說明

| 檔案 | 用途 |
|---|---|
| `index.html` | 整個 App (畫面 + 程式 + 食物/運動資料庫都在裡面) |
| `icon-512.png` / `icon.svg` | 主畫面 App 圖示 |
| `manifest.json` | 讓 Android 能「安裝」這個 App 的設定檔 |
| `.github/workflows/pages.yml` | 自動部署:每次 commit 後自動更新網站 |

## 備註

- 熱量目標用 Mifflin-St Jeor 公式估算 BMR/TDEE;運動消耗用 MET × 體重 × 時間。
- 體重預測採 7700 kcal ≈ 1 kg 的通用估算,僅供參考,不是醫療建議。
