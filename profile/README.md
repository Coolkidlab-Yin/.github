# Coolkid AI Lab

把實際做過的 AI Workflow 整理成可安裝、可驗證，也適合拿來學習的開源 Skills。

Skill 提供決策框架、安全邊界與完成判準；實作細節由執行 Agent 依使用者的 repo、
環境與當下官方文件補完，不把單一範例假裝成唯一解法。

[完整 Skill 工具庫](https://github.com/Coolkidlab-Yin/Coolkidlab) ·
[實作紀錄](https://www.coolkidlab.com/) ·
[關於我](https://www.coolkidlab.com/about.html)

## SEO／GEO

- [article-overlap-checker](https://github.com/Coolkidlab-Yin/article-overlap-checker)：找出內容撞題、關鍵字互相競爭與孤兒頁面。
- [competitor-content-map](https://github.com/Coolkidlab-Yin/competitor-content-map)：從網站 sitemap 整理競品主題版圖與內容缺口。
- [ga4-chatgpt-referral](https://github.com/Coolkidlab-Yin/ga4-chatgpt-referral)：用 GA4 免費資料倒推 ChatGPT 引用與 AI 流量來源。

## 品牌與內容

- [brand-profile-lockdown](https://github.com/Coolkidlab-Yin/brand-profile-lockdown)：透過顧問式訪談釐清定位，建立可長期沿用的品牌 Profile。
- [voice-profile-extraction](https://github.com/Coolkidlab-Yin/voice-profile-extraction)：從真實寫作樣本萃取語氣指紋，讓 Agent 保留作者風格。

## Agent 工作流

- [claude-code-checkpoint-system](https://github.com/Coolkidlab-Yin/claude-code-checkpoint-system)：用 checkpoint 與 hooks 建立可跨對話接續的專案狀態系統。

## 社群自動化 Builder

- [threads-bot-builder](https://github.com/Coolkidlab-Yin/threads-bot-builder)：引導 Agent 建立有人類審核、安全重試與狀態追蹤的 Threads 發文流程。
- [ig-bot-builder](https://github.com/Coolkidlab-Yin/ig-bot-builder)：引導 Agent 建立圖片、輪播與排程所需的 Instagram 發文流程。
- [line-bot-builder](https://github.com/Coolkidlab-Yin/line-bot-builder)：引導 Agent 建立 LINE 推播、收訊息、預約或提醒流程。

## 職場工具

- [shiftdeck](https://github.com/Coolkidlab-Yin/shiftdeck)：AI 生成簡報後仍保留控制權，版面從頁型庫挑選、動畫逐元素設定、單頁重生成不必等全份重跑。輸出為原生可編輯的 .pptx，底層使用 [ppt-master](https://github.com/hugohe3/ppt-master) 編譯引擎。

shiftdeck 是獨立專案而非 Skill，以 `git clone` 取得後執行 `python scripts/setup.py` 安裝，
詳見該 repo 的 README。

## 有趣小工具

- [windows-desktop-pet-builder](https://github.com/Coolkidlab-Yin/windows-desktop-pet-builder)：用自己寵物的照片做一隻會拖曳、會看滑鼠、會撿球的 Windows 桌面小精靈。完整繁中教學、可貼給 Agent 的主提示詞與環境檢查腳本都在 repo 裡。

適合當第一個「跟 AI Agent 協作」的題目：不必會寫程式，素材全留在本機，
做壞了重來也沒有代價。

## 安裝完整工具庫

在 Claude Code 執行：

```text
/plugin marketplace add Coolkidlab-Yin/Coolkidlab
```

各 Skill 的適用情境、限制與驗證方式都記錄在
[Coolkidlab README](https://github.com/Coolkidlab-Yin/Coolkidlab#readme)。
