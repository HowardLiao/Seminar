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
