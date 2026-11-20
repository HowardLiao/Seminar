# Howard Liao Ph.D. ｜ 前沿技術論壇與研討會專案矩陣 (Seminar Hub)

> **專案總覽網址**：[https://howardliao.github.io/Seminar/](https://howardliao.github.io/Seminar/)  
> **GitHub 儲存庫**：[https://github.com/HowardLiao/Seminar](https://github.com/HowardLiao/Seminar)  
> **設計體系**：Executive Two-Track Design System (米蘭編排 / 暖琥珀白皮書風格 16:9 出版級)

---

## 目錄架構 (Seminar Series Taxonomy)

本專案庫（`Seminar/`）採獨立子目錄分冊管理各期高階技術論壇、科技峰會與戰略白皮書：

```text
Seminar/
├── index.html                                                      # 研討會系列總目錄門戶 (Seminar Series Hub)
├── README.md                                                       # 專案總說明
│
├── 001/                                                            # 【001 專題】AI Agent 新賽局：全球掀五大變革
│   ├── index.html                                                  # 50 頁米蘭風格全靜態響應式簡報播放器（線上專屬）
│   ├── manifest.json                                               # PWA 離線設定
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
│   ├── index.html                                                  # 4 大成果循序總覽門戶、雙簡報播放器與雙原型內嵌（線上展示）
│   ├── 1.1interactive-demo.html                                    # S01 登入流程互動示範與實測像素尺寸標註
│   ├── 1.1.1.範例說明.html                                         # 企業級客服工單排查、逐步判定與改版變更標註原型
│   ├── slides1/                                                    # 簡報一高解析投影片影像與縮圖
│   └── slides2/                                                    # 簡報二高解析投影片影像與縮圖
│
├── 008/                                                            # 【008 專題】AI 核心架構全景解析：Skill、Project、Agent、MCP
│   ├── index.html                                                  # 向量 SVG 拓撲圖、四象限解析卡、四大支柱與企業決策樹
│   └── assets/                                                     # 報告人肖像資產
│
├── 010/                                                            # 【010 專題】Gartner 2027 十大策略技術趨勢深度解析
│   ├── index.html                                                  # 掌握機器行為的新邊界全景深度戰略門戶（三大主軸 × 十大趨勢 × RACI 矩陣，僅供線上瀏覽）
│   └── assets/                                                     # 原廠高解析架構圖解、時程地圖與報告人肖像
│
├── 011/                                                            # 【011 專題】Palo Alto Networks 2026 Security by Design 高階白皮書
│   ├── index.html                                                  # 全情境 AI 治理、自主端點、機器特權與 PQC 密碼敏捷（僅供線上瀏覽）
│   └── assets/                                                     # 6 幅米蘭風格向量架構圖與報告人肖像
│
├── 012/                                                            # 【012 專題】Howard AI Governance (HAG) 企業 AI 治理產品架構白皮書
│   └── index.html                                                  # 單檔自包含高管互動門戶（3D 架構圖 + 8 幅實機介面 + 6 大主題，僅供線上瀏覽）
│
├── 002/ (規劃中)                                                   # 全球算力基礎設施與推論架構大遷徙
└── 003/ (規劃中)                                                   # 企業主權 AI (Sovereign AI) 與數位員工防禦體系
```

---

## 001 專案摘要：AI Agent 新賽局（全球掀五大變革）

- **主講嘉賓**：簡立峰 博士（前 Google 台灣董事總經理 ｜ 中華電信獨立董事）
- **報告人**：Howard Liao Ph.D. (廖倫豪 博士)
- **展示入口**：[https://howardliao.github.io/Seminar/001/](https://howardliao.github.io/Seminar/001/)
- **形式**：50 頁米蘭風格全靜態響應式簡報，僅供線上互動觀看（全站不提供檔案下載）
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
- **形式**：線上互動原型 ＋ 雙簡報放映門戶，僅供線上展示（不提供檔案下載）
- **交付成果（線上循序展示）**：
  1. `1. 把需求說清楚，讓合作更順暢`：8 頁線上簡報，規格書溝通五大做法、畫面編號規則（S01）、Claude Prompt 範本、跨端 APP 提示與驗收檢核表。
  2. `1.1 互動示範：S01 登入畫面`：單頁獨立互動原型，展示登入流程（S01 登入 ➔ S02 首頁 / S03 找回密碼），右上角支援動態切換像素尺寸與跳轉標註。
  3. `1.1.1 範例說明：客服問題回報修改版`：完整客服工單改版原型，涵蓋開單前排查、逐步分級判斷決策樹（P1~P4）、四維影響範圍分析、裝置交叉檢查與全欄位改版變更標註卡。
  4. `2. 網站建置方案比較`：13 頁策略簡報，一頁式、架站機、前後端分離架構剖析、台灣市場建置與維運行情、三年 TCO 總擁有成本模型與廠商採購避坑四問。
- **實務建置指南**：手遊公司官網準備深度與 Apple 平台審查機制（法定主體、產品揭露、四項必備資訊與鄧白氏編碼互補實務）。

---

## 010 專案摘要：Gartner 2027 十大策略技術趨勢：掌握機器行為的新邊界 (Mastering Machine Behavior)

- **專案背景**：2027 策略技術趨勢峰會 · Gartner 官方白皮書深度戰略轉譯與 C-Level 落地指引
- **報告人**：Howard Liao Ph.D. (廖倫豪 博士)
- **展示入口**：[https://howardliao.github.io/Seminar/010/](https://howardliao.github.io/Seminar/010/)
- **形式**：全靜態響應式高管戰略門戶，僅供線上互動瀏覽（全站不提供檔案下載）
- **三大營運戰略主軸**：
  1. **開拓非文字 AI 前沿 (Leverage the nontextual AI frontier)**：模型會計算、聆聽與模擬，提供確定性精度與感官深度。
  2. **治理自主代理平台 (Govern the autonomous agent platform)**：系統級控制平面，確保數位勞動力的自主性值得信賴。
  3. **建構長效敏捷性 (Architect durable agility)**：轉向主權、拋棄式與生物運算環境，防範供應商鎖定與能源極限。
- **十大核心技術趨勢深入解析**：
  1. **大型量化模型 (LQMs)**：突破 LLM 機率猜測缺陷，2030 年取代 25% 預測與營運建模任務。
  2. **語音推理模型 (Speech Reasoning)**：端到端音訊推理，2030 年承接 70% 企業語音對話。
  3. **世界模型 (World Models)**：物理優先與空間模擬，2030 年導入 40% 機器人應用。
  4. **AI 上下文平台 (AI Context Platforms)**：建立企業真理層，精準度提升 80%、成本降 60%。
  5. **AI 編碼代理安全框架 (AI Coding Agent Harness)**：閉環 SDLC 門禁與防回壓，應對 2026 年底 AI 產出 20% 公開 Commits。
  6. **AI 代理身分識別 (AI Agent Identity)**：複合身分模型與動態零信任，化解 2028 年 25% Agent 權限濫用危機。
  7. **自主曝險修復 (Autonomous Exposure Remediation)**：機器速度防禦，將漏洞暴露窗口自數週壓縮至 48 小時內。
  8. **主權科技 (SovereignTech)**：技術與法律雙退出機制，2030 年 75% 非美企業採納數位主權防斷供。
  9. **拋棄式應用 (Disposable Applications)**：預設壽命、隨用隨丟，2030 年 80% 新應用為拋棄式以破除 SaaS 綁架。
  10. **生物運算即服務 (Wetware as a Service)**：活體神經元有機處理器突破矽晶片能耗牆，2030 年 25% 低功耗 AI 企業部署。
- **C-Level 跨部門權責矩陣**：CIO 領導治理、IT 架構防護與業務主管價值創造之端到端對照表。


## 008 專案摘要：AI 核心架構全景解析：Skill、Project、Agent、MCP

- **主講／報告人**：Howard Liao Ph.D.
- **展示入口**：[https://howardliao.github.io/Seminar/008/](https://howardliao.github.io/Seminar/008/)
- **形式**：出版級架構互動解析門戶、向量 SVG 拓撲視覺化、四象限決策矩陣與企業落地評估表
- **核心內容**：
  - **米其林廚房總覽比喻**：Skill（食譜）、Project（廚房配置）、Agent（廚師群）、MCP（冷鏈倉庫）。
  - **Skill 四大支柱**：Prompt Template（提示詞模板）、Golden Samples（Few-shot 範例）、Output Schema（格式規格）、Code Execution（程式調用）。避免長上下文衰退與 Token 浪費。
  - **Project 專案邊界與 Token 經濟學**：高 Context 負擔、全域文件常駐風險與知識混淆隔離矩陣。「能用 Skill 模組化解決，絕不濫開 Project」。
  - **Agent 具判斷力的主從階層分工**：管家 Agent（任務路由與 Token 守門員）、主 Agent（深度推理與唯一對外把關窗口）、Sub-Agent（機械子任務與粗活執行隔離）。
  - **MCP 開放標準外掛協議**：打破 API 孤島、避免重複造輪子、企業私有數據與安全沙盒對接。
  - **企業架構選型決策樹**：針對不同業務特質（固定步驟、長期脈絡、多步探索、跨系統介接）的標準決策矩陣。

---

## 011 專案摘要：Palo Alto Networks 2026 Security by Design：從全情境 AI 治理、自主端點防禦、產線機器特權身分到後量子密碼學的實務落地綱領

- **專案背景**：Palo Alto Networks 2026 年度實體技術研討會（台灣 ‧ 台中）
- **報告人**：Howard Liao Ph.D. (廖倫豪 博士)
- **展示入口**：[https://howardliao.github.io/Seminar/011/](https://howardliao.github.io/Seminar/011/)
- **形式**：全靜態響應式高階戰略門戶，米蘭暖琥珀風格，含 6 幅全客製向量示意圖、10 組決策表格與 C-Level 4 大指標（全站僅供線上專業研習瀏覽，不提供實體檔案下載）
- **五大核心戰略支柱**：
  1. **全情境 AI 應用治理與防禦中樞 (Prisma AIRS & AI Gateway)**：部署前掃描未宣告能力（如 `panos-ngfw-Skill` 惡意讀檔），運行時以 Portkey 整合反向代理實施 Prompt Injection/Jailbreak 即時語意過濾、全域 Trace 追蹤、動態 PII 遮罩與資料庫試探阻斷。
  2. **自主式時代端點防禦重構 (Cortex AES & AIDR)**：針對 Claude Code、Cursor 等本機自主代理提權風險，發表以 **KOI 安全閘道為第 1 階核心**的五階防線（KOI 閘道 ➔ AIDR 執行階段 ➔ 憑證管道 ➔ 版本冷卻 ➔ 持續補救），徹底阻斷 **Shai-Hulud** 開源供應鏈投毒。
  3. **人機雙軌工作力量與安全企業瀏覽器 (Prisma Access Browser)**：「One Company, Two Types of Employees」共存治理模型，以瀏覽器政策引擎動態區隔真人與 AI 代理，實施 DOM 級敏感資料遮罩、背景未授權下載攔截、Step-up MFA 中斷審批與全量提示詞稽核。
  4. **製造業產線防線與機器特權身分治理 (Idira™ Identity Governance)**：直擊智慧工廠機器身分與人類比率高達 **109 : 1** 的失控危機；落實 Idira 身分治理三部曲（盤點 Inventory、零常駐特權 ZSP、委任代理 OBO），推動企業由 Level 1 躍升至 Level 4/5 密碼學通用工作負載身分。
  5. **後量子密碼學敏捷性與密碼技術清冊 (Crypto Agility & CBOM)**：應對 Google 47 天憑證縮短危機與「先擷取、後解密」(Harvest Now, Decrypt Later) 國安級威脅；自動探勘建立 CBOM 密碼資產清冊，並引進 **PQC 密碼轉換中繼閘道**，實現機齡 10~15 年之 OT 舊機台 **100% 零停機抗量子升級**。
- **企業落地三階段藍圖**：盤點止血（1~3月）➔ 控管自動化（3~6月）➔ 敏捷韌性（6~12月）三階段推進，全面平衡創新效能與邊界安全。

---

## 012 專案摘要：Howard AI Governance (HAG) 企業 AI 治理產品架構白皮書

- **專案定位**：L.L.H Enterprise Edition — 企業級 AI Agent 集中治理與可信賴底座
- **報告人**：Howard Liao Ph.D. (廖倫豪 博士)
- **展示入口**：[https://howardliao.github.io/Seminar/012/](https://howardliao.github.io/Seminar/012/)
- **形式**：單檔自包含響應式高管互動門戶，支援 6 大高管設計主題切換、互動四層架構檢視、3D 全局架構圖與 8 幅實機控制台截圖（附分類篩選與全螢幕 Lightbox；全站僅供線上瀏覽，不提供檔案下載）
- **核心治理架構**：
  1. **四層解耦架構**：User Portal 統一入口 ➔ L.L.H AI Studio / BYOA 應用層 ➔ HAG 集中治理層 ➔ 跨雲／地端多模型基礎設施層。
  2. **四大治理支柱（SEE / GOVERN / SECURE / CONTROL）**：全組織 AI 資產清冊與全鏈路稽核、Enterprise RBAC 與 BYOA API Key 納管、OWASP LLM 動態護欄（PII 遮罩 / Prompt Injection 阻斷 / Sandbox 驗證）、以及團隊與使用者 Token／USD 預算上限控管。
