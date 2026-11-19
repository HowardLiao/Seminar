# Howard Liao Ph.D. ｜ 前沿技術論壇與研討會專案矩陣 (Seminar Hub)

> **專案總覽網址**：[https://howardliao.github.io/Seminar/](https://howardliao.github.io/Seminar/)  
> **GitHub 儲存庫**：[https://github.com/HowardLiao/Seminar](https://github.com/HowardLiao/Seminar)  
> **設計體系**：Executive Two-Track Design System (米蘭編排 / 暖琥珀白皮書風格 16:9 出版級)

---

## 目錄架構 (Seminar Series Taxonomy)

本專案庫（`Seminar/`）採獨立子目錄分冊管理各期高階技術論壇、科技峰會與戰略白皮書：

```
Seminar/
├── index.html                                                      # 研討會系列總目錄門戶 (Seminar Series Hub)
├── README.md                                                       # 專案總說明
│
├── 001/                                                            # 【001 專題】AI Agent 新賽局：全球掀五大變革
│   ├── index.html                                                  # 50 頁米蘭風格全靜態響應式簡報播放器
│   ├── manifest.json                                               # PWA 離線設定
│   ├── AI_Agent_全球五大變革_簡立峰博士演講深度解析_米蘭風格_50頁報告.pdf   # 100% 向量銳利度 PDF（米蘭風格）
│   ├── AI_Agent_全球五大變革_簡立峰博士演講深度解析_50頁報告.pdf           # 100% 向量銳利度 PDF（曜石黑風格）
│   ├── AI_Agent_全球五大變革_簡立峰博士演講深度解析_米蘭風格_50頁報告.pptx  # 16:9 出版級 PowerPoint（米蘭風格）
│   ├── AI_Agent_全球五大變革_簡立峰博士演講深度解析_50頁報告.pptx          # 16:9 出版級 PowerPoint（曜石黑風格）
│   └── assets/                                                     # 報告人肖像與圖騰資產
│
├── 004/                                                            # 【004 專題】AI 判斷力 × AI Agent 五大架構性缺陷
│   ├── index.html                                                  # 27 頁線上簡報播放器（僅供線上觀看，不提供下載）
│   ├── slides/                                                     # 投影片影像
│   └── assets/                                                     # 報告人肖像
│
├── 005/                                                            # 【005 專題】MIT 6.S184 Flow Matching and Diffusion Models 課程筆記
│   ├── index.html                                                  # 互動學習導航、前導片時間軸、學習單與 121 條術語手冊
│   └── data/                                                       # 影片縮圖資產 (thumb_01 ~ thumb_04.jpg)
│
├── 006/                                                            # 【006 專題】避開「偽專業陷阱」與默會知識外顯化
│   ├── index.html                                                  # 9 頁線上簡報放映器 ＋ 深度研習講義與對話全貌
│   ├── slides/                                                     # 簡報高解析度影像 (01.jpg ~ 09.jpg) 與縮圖 (t01.jpg ~ t09.jpg)
│   └── assets/                                                     # 報告人肖像資產
│
├── 007/                                                            # 【007 專題】網頁與 APP 需求規格制定 × 網站建置架構方案策略比較
│   ├── index.html                                                  # 4 大成果循序總覽門戶、雙簡報播放器與雙原型內嵌
│   ├── 1.把需求說清楚合作更順暢.pptx                                 # 規格制定溝通指南原始 PPTX (8 頁)
│   ├── 1.把需求說清楚合作更順暢.pdf                                  # 高解析向量印刷版 PDF
│   ├── 1.1interactive-demo.html                                    # S01 登入流程互動示範與實測像素尺寸標註
│   ├── 1.1.1.範例說明.html                                         # 企業級客服工單排查、逐步判定與改版變更標註原型
│   ├── 2.網站建置方案比較.pptx                                      # 一頁式、架站機、前後端分離技術與三年 TCO 分析 (13 頁)
│   ├── 2.網站建置方案比較.pdf                                       # 高解析向量印刷版 PDF
│   ├── slides1/                                                    # 簡報一高解析投影片影像與縮圖
│   ├── slides2/                                                    # 簡報二高解析投影片影像與縮圖
│   └── assets/                                                     # 報告人肖像資產
│
├── 002/ (規劃中)                                                   # 全球算力基礎設施與推論架構大遷徙
└── 003/ (規劃中)                                                   # 企業主權 AI (Sovereign AI) 與數位員工防禦體系
```

---

## 001 專案摘要：AI Agent 新賽局（全球掀五大變革）

- **主講嘉賓**：簡立峰 博士（前 Google 台灣董事總經理 ｜ 中華電信獨立董事）
- **報告人**：Howard Liao Ph.D. (廖倫豪 博士)
- **展示入口**：[https://howardliao.github.io/Seminar/001/](https://howardliao.github.io/Seminar/001/)
- **下載 PDF 報告**：[米蘭風格 50 頁高管報告 PDF](001/AI_Agent_全球五大變革_簡立峰博士演講深度解析_米蘭風格_50頁報告.pdf)
- **核心內容**：涵蓋 5,000 人分水嶺、5 萬 GPU 破解 722 數學難題、80/20 人類極限與 RSI、Long-Horizon 20 天自主任務、軟體 1:1 革命、Moderna 6 天癌症疫苗、B-Coding 研發重構、SaaS 2.0 服務軟體化與台灣小島進太平洋之資本博弈。

---

## 004 專案摘要：當 AI 的答案看起來都對，員工判斷得出錯誤嗎？

- **報告人**：Howard Liao Ph.D.
- **展示入口**：[https://howardliao.github.io/Seminar/004/](https://howardliao.github.io/Seminar/004/)
- **形式**：27 頁線上簡報，僅供線上觀看（不提供 PDF／PPTX 下載）
- **核心內容**：金字塔結構——AI Agent 五大架構性缺陷（長上下文退化、記憶污染、自我修正失效、目標不對齊、交接失真）、Approve／Correct／Escalate 三種決定、4E Framework、十大 AI 風險與風險分級、知識／資料／流程／權責與情境演練。

---

## 005 專案摘要：MIT 6.S184 Flow Matching and Diffusion Models 課程筆記

- **課程來源**：麻省理工學院 MIT Course 6.S184 (IAP 2026: Generative AI with Stochastic Differential Equations)
- **主講學者**：Peter Holderrieth & Ezra Erives 等
- **展示入口**：[https://howardliao.github.io/Seminar/005/](https://howardliao.github.io/Seminar/005/)
- **核心內容**：
  - **7 大單元導航**：01 流與擴散、02 流匹配、03 分數匹配、04 無分類器引導、05 潛在空間與 VAE、06 網路架構與案例 (DiT/U-Net)、07 離散擴散。
  - **原片小節時間軸與學習單**：動手計算練習、觀念自我問答、陷阱提示。
  - **121 條系列術語手冊**：涵蓋「錨定」、「聽過就好」、「聽力詞」三層篩選與中英對照解釋。
  - **原片逐句字幕對照**：Lecture 01 ~ 05 繁中英對照導讀。

---

## 006 專案摘要：避開「偽專業陷阱」與默會知識外顯化

- **主講／報告人**：Howard Liao Ph.D. (廖倫豪 博士)
- **核心來源**：《哈佛商業評論》週三編輯室 EP109 精華（把 AI 本事當自己本領？4步驟避開「偽專業陷阱」）
- **展示入口**：[https://howardliao.github.io/Seminar/006/](https://howardliao.github.io/Seminar/006/)
- **形式**：9 頁高解析線上互動簡報放映 ＋ 企業輔導實戰講義與完整對話全貌
- **核心內容**：
  - **兩極化痛點**：新手「偽專業陷阱」（解釋深度錯覺）vs. 老手「默會知識障礙」（手感難以言傳）。
  - **個人 4 步驟防線**：1. 先想 (Anchor) ➔ 2. 挑戰 (Red Teaming) ➔ 3. 比較 (Delta Analysis) ➔ 4. 交代判斷過程 (Explainability)。
  - **管理顧問實務案例**：新市場競研 80/20 法則（70% 靠 AI，20% 人工專業過濾決定生死）。
  - **主管審查 3 個靈魂拷問**：1. AI 原本給什麼？ 2. 你修改了哪些？ 3. 為什麼這樣修改？
  - **團隊知識管理（KM）閉環**：將老手踩坑經驗逆向工程為組織 Few-Shot、規則邊界與 SOP 規格書。
  - **延伸技術架構**：企業級 Model Routing 智慧調度器選型（MixRoute、OpenRouter、Azure/GCP 原廠）。

---

## 007 專案摘要：網頁與 APP 需求規格制定 × 網站建置架構方案策略比較

- **專案背景**：2026 企業架構與技術戰略研習 · 網頁需求規格標準化資產
- **報告人**：Howard Liao Ph.D. (廖倫豪 博士)
- **展示入口**：[https://howardliao.github.io/Seminar/007/](https://howardliao.github.io/Seminar/007/)
- **交付檔案（依序展示與提供下載）**：
  1. `1.把需求說清楚合作更順暢.pptx` / `1.把需求說清楚合作更順暢.pdf`：8 頁簡報，規格書溝通五大做法、畫面編號規則（S01）、Claude Prompt 範本、跨端 APP 提示與驗收檢核表。
  2. `1.1interactive-demo.html`：單頁獨立互動原型，展示登入流程（S01 登入 ➔ S02 首頁 / S03 找回密碼），右上角支援動態切換像素尺寸與跳轉標註。
  3. `1.1.1.範例說明.html`：完整客服工單改版原型，涵蓋開單前排查、逐步分級判斷決策樹（P1~P4）、四維影響範圍分析、裝置交叉檢查與全欄位改版變更標註卡。
  4. `2.網站建置方案比較.pptx` / `2.網站建置方案比較.pdf`：13 頁策略簡報，一頁式、架站機、前後端分離架構剖析、台灣市場建置與維運行情、三年 TCO 總擁有成本模型與廠商採購避坑四問。
- **實務建置指南**：手遊公司官網準備深度與 Apple 平台審查機制（法定主體、產品揭露、四項必備資訊與鄧白氏編碼互補實務）。


