# AI × Web3 School — 個人學習儲存庫

> **Learning Agent 協助建立 · 由學習者手動審查確認**

[![Handbook](https://img.shields.io/badge/📖_Handbook-aiweb3.school-blue)](https://aiweb3.school/zh/handbook/)
[![WCB Course](https://img.shields.io/badge/🎓_WCB_Course-aiweb3.school-purple)](https://aiweb3.school)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## 🏫 關於 AI × Web3 School

**AI × Web3 School** 是一所專注於 AI 與 Web3 交叉領域的學習社群。課程涵蓋：

- 去中心化應用（dApp）開發
- 智慧合約（Smart Contract）設計與安全
- 大型語言模型（LLM）與 AI Agent 實作
- DeFi、NFT、DAO 等 Web3 核心協議
- AI × Web3 融合應用場景

| 資源 | 連結 |
|------|------|
| 學生手冊（Handbook） | [https://aiweb3.school/zh/handbook/](https://aiweb3.school/zh/handbook/) |
| WCB 課程主頁 | [https://aiweb3.school](https://aiweb3.school) |
| Learning Agent 引導文件 | [https://aiweb3.school/learning-agent.zh.txt](https://aiweb3.school/learning-agent.zh.txt) |

---

## ⚠️ 安全與隱私警告

> **[!IMPORTANT] 嚴格禁止提交以下任何內容至本儲存庫：**
>
> - 🔑 私鑰（Private Keys）或助記詞（Seed Phrases / Mnemonic）
> - 🔐 API Keys、Access Tokens、Bearer Tokens
> - 📄 `.env` 檔案或任何含有敏感環境變數的設定檔
> - 🔗 未公開的會議連結（Zoom / Meet / Discord 私人邀請連結）
> - 💰 錢包地址私鑰、交易所帳號密碼
>
> **請在提交前確認 `.gitignore` 已正確設定，永遠不要在公開 Repo 中暴露任何憑證。**

---

## 📁 目錄結構說明

```
web3xai/
├── README.md              # 本說明文件
├── profile.md             # 個人學習簡介與背景
├── learning-plan.md       # 個人 AI × Web3 學習計畫與里程碑
│
├── daily/                 # 每日學習筆記與打卡記錄
│   └── YYYY-MM-DD.md      # 按日期命名的每日筆記
│
├── tasks/                 # 課程任務與 Proof of Tasks（PoT）
│   └── task-XXX.md        # 每個任務的完成記錄與證明
│
├── experiments/           # 程式碼實驗、合約測試、AI 實作記錄
│   └── exp-XXX/           # 每個實驗的獨立資料夾
│
├── handbook-feedback/     # 學生手冊閱讀心得與章節反饋
│   └── chapter-XX.md      # 對應手冊章節的筆記與問題
│
├── hackathon/             # Hackathon 籌備基地
│   ├── ideas.md           # 想法發想與概念草稿
│   └── project/           # Hackathon 專案程式碼
│
├── submissions/           # 正式提交的作業與成果
│   └── week-XX/           # 依週次整理的提交內容
│
└── templates/             # 標準化筆記範本
    ├── daily-note.md      # 每日筆記範本
    └── task-note.md       # 任務證明範本
```

### 各資料夾用途詳解

| 資料夾 | 用途說明 |
|--------|----------|
| `daily/` | 每日學習打卡，記錄當天學了什麼、實作了什麼、遇到什麼問題 |
| `tasks/` | 課程指定任務的完成記錄，含截圖、程式碼、交易 Hash 等 PoT |
| `experiments/` | 自主實驗空間，可包含 Solidity 合約、Python AI 腳本、測試記錄 |
| `handbook-feedback/` | 閱讀手冊各章節後的心得、疑問、建議，可作為與社群互動的素材 |
| `hackathon/` | Hackathon 準備區，從想法發想到最終提交的完整過程 |
| `submissions/` | 正式提交物，需完整、有據可查、符合提交格式要求 |
| `templates/` | 統一格式的範本，確保筆記品質一致並易於回顧 |

---

## 🎯 第一週學習目標（Week 1 Learning Goals）

### 主題：AI × Web3 基礎建立

**Week 1 核心目標**

- [ ] 完成環境建置：Node.js、Hardhat / Foundry、MetaMask 錢包設定
- [ ] 閱讀並理解 Handbook 前兩章，完成 `handbook-feedback/chapter-01.md`
- [ ] 理解區塊鏈基礎概念：區塊、交易、共識機制、Gas
- [ ] 部署第一個 Solidity Hello World 合約至測試網（Sepolia / Mumbai）
- [ ] 理解 LLM 基礎：Prompt Engineering、Temperature、Context Window
- [ ] 嘗試使用 AI API（Claude / GPT）發送第一個 API 請求
- [ ] 完成每日打卡 ×7（`daily/` 資料夾，每天一份）
- [ ] 完成 `profile.md` 個人簡介並 Push 至 GitHub

**每日打卡節奏**

```
早上：設定今日學習目標 → 下午：實作與記錄 → 晚上：反思與 Commit
```

**里程碑驗證**
> Week 1 結束時，`daily/` 中應有 7 份筆記，`tasks/` 中應有至少 1 份 PoT，且 `experiments/` 中有第一個合約部署記錄。

---

## 🤖 Learning Agent 分工說明

本儲存庫由 **Claude Code（claude-sonnet-4-6）** 擔任 **Learning Agent** 協助建立初始架構與生成範本內容。

### 分工模式

| 角色 | 負責事項 |
|------|----------|
| **Claude Code（Learning Agent）** | 目錄結構規劃、範本生成、學習計畫草擬、內容建議 |
| **學習者（你）** | 內容審查、個人化修改、手動 Commit、Push 確認 |

### 重要原則

> **所有的檔案寫入、Commit、Push 動作皆由學習者在 VS Code 中手動審查並確認（Manual Confirmation）。**
> Claude Code 作為 Learning Agent 僅負責內容生成與建議，不自動執行任何 Git 推送操作，確保學習者對儲存庫內容擁有完整的知情權與控制權。

---

## 📅 更新紀錄

| 日期 | 事件 |
|------|------|
| 2026-05-19 | 由 Learning Agent 初始化儲存庫結構與核心文件 |
