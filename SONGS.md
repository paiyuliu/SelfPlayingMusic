# 歌曲庫

## 簡譜來源指南

### 格式說明

本專案使用 [jianpu.space](https://jianpu.space/zh-tw/songList/16) 的文字簡譜格式，與 `je.js` 完全相容。
語法速查見 `jianpu.space/miss_you.txt` 底部。

---

### 來源 1：jianpu.space 直接取用（最相容）

`je.js` 本身來自 jianpu.space，格式零轉換成本。

- 前往 https://jianpu.space/zh-tw/songList/16 瀏覽曲目
- 直接複製文字內容貼入本專案
- 缺點：曲目有限，以華語流行為主

---

### 來源 2：AI 輔助轉譯（最實用）

#### 流程

1. 找到歌曲的旋律來源（YouTube 說明、網路簡譜圖片、或直接給歌名）
2. 準備 prompt：
   - 附上 `jianpu.space/miss_you.txt` 底部的語法說明
   - 附上 `miss_you.txt` 或本檔案已有歌曲作為格式範例
3. 請 AI（Claude / Gemini / Copilot 均可）輸出符合格式的簡譜文字
4. 貼入程式播放測試，人工校對音準與節拍

#### 注意事項

- AI 初稿準確度約 70–80%，需要播放後比對原曲微調
- 升降音（`#` / `b`）與附點（`.`）最容易出錯，重點檢查
- 每次使用 AI 時，建議直接附上語法說明作為 prompt 的一部分

---

### 來源 3：其他中文簡譜網站（需手動轉格式）

網路上的簡譜通常是圖片或非標準文字，需對照語法說明手動轉換。
常見差異只有升降號寫法與時值符號，工作量不大。

---

## 歌曲清單

| 歌曲 | 歌手 | 調性 | BPM | 檔案 | 狀態 |
|------|------|------|-----|------|------|
| 好想你 | 四葉草 | F 大調 | 97 | `jianpu.space/miss_you.txt` | 完成 |
| 生日快樂 | — | C 大調 | 120 | `jianpu.space/birthday.txt` | 完成 |
| 叮叮噹 (Jingle Bells) | — | C 大調 | 120 | `jianpu.space/jingle_bells.txt` | 完成 |
| 一閃一閃亮晶晶 (Twinkle Star) | — | C 大調 | 97 | `jianpu.space/twinkle_star.txt` | 完成 |
