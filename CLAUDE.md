# CLAUDE.md

此文件為 Claude Code（claude.ai/code）在本專案中工作時的指引。

## 專案目的

本專案是一個教學用工作坊課程庫，內容為一場兩小時的 AI Agent 理論與設計密集工作坊，目標對象為研究所學生（含非技術背景）。內容主要以繁體中文撰寫，技術術語保留英文。

## 內容結構

工作坊分為兩大部分：

**講課（60 分鐘）** — 四個章節，收錄於 `agent_workshop_outline_V2.md`：
- CH.01：LLM 演進（BERT → Claude、Bitter Lesson、Software 3.0）
- CH.02：Agent 基礎 — ReAct 循環、Memory／Planning／Tools／Action 四大支柱、Context Engineering
- CH.03：Agent 產品設計 — 意圖系統設計、信任機制、漸進式授權
- CH.04：人機協作、「Builder」角色轉變

**實作（60 分鐘）** — 兩個 Lab 練習，附於同一大綱檔案末尾：
- Lab 1：設計個人 UX 設計 Agent
- Lab 2：使用該 Agent 執行真實任務

**主要檔案：**
- `agent_workshop_outline_V2.md` — 課程內容的唯一來源（以此為主進行編輯）
- `references.md` — 依章節整理的參考資料連結，使用可折疊區塊格式
- `agent_course_outline.html` — 含互動目錄的 HTML 版本，需與 Markdown 保持同步

## 編輯原則

- 以大綱檔案為唯一來源，任何結構調整須同步反映於 HTML 版本
- 新增參考資料時，請沿用 `references.md` 現有的可折疊區塊格式
- 重新整理內容時，保留時間標註（例如 `（20 分鐘）`）
- 技術術語（ReAct、LLM、Context Engineering 等）在中文段落中刻意保留英文原文
