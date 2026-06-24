<div align="center">

<img src="assets/readme-banner.svg" alt="TARA 品牌設計助理：說一句想法，直接取得第一版" width="100%">

# Tarshar Brand Studio

### TARA 品牌設計助理

把課程、文章與教學想法，轉成可持續使用的品牌視覺系統。

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-2F8F62?style=for-the-badge&logo=github)](https://tarshar4242.github.io/tarshar-brand-studio/)
![Static HTML](https://img.shields.io/badge/Static-HTML%20%2B%20CSS%20%2B%20JS-4C9ED9?style=for-the-badge)
![Brand DNA](https://img.shields.io/badge/Brand%20DNA-v0.1-F29A4A?style=for-the-badge)

**[立即開啟線上版](https://tarshar4242.github.io/tarshar-brand-studio/)** · **[查看 TARA Skill](skills/tarshar-brand-director/SKILL.md)**

</div>

---

## 專案定位

Tarshar Brand Studio 是為 **Learn AI with Tarshar** 建立的初學者品牌設計工具。使用者只要說一句想法，TARA 就先完成一個最佳判斷版本；不滿意時才出現少量修改按鈕。

它把品牌製作拆成兩個合作角色：

| 角色 | 定位 | 主要任務 | 產出 |
|---|---|---|---|
| **TARA 品牌設計助理** | 使用者唯一需要面對的入口 | 理解一句自然語言，自動完成輸出、風格與版型判斷 | 一個可直接採用的第一版 |
| **小D Design DNA** | TARA 的幕後靈感系統 | 從 100 組設計方向中自動選擇，不要求初學者操作 | 第一版的風格與修改依據 |

### 核心承諾

> 選項是 TARA 的工作，不是初學者的作業。

---

## 為什麼需要這套系統

傳統外包通常只能取得一次成果；Brand Studio 保存的是可持續累積的品牌決策。

| 常見問題 | Brand Studio 的處理方式 |
|---|---|
| 每次作品風格不同，看不出是同一個品牌 | 使用固定 Brand DNA、色彩、語氣、版面與署名規則 |
| 收藏很多圖片，實際製作時仍不知道怎麼選 | 小D 在幕後自動比對「風格 × 版型 × 使用情境」 |
| AI 圖片漂亮，但與課程訊息沒有關係 | TARA 先理解一句原始想法，再直接完成第一版 |
| 一張圖塞太多內容，手機閱讀困難 | 一張只傳達一個主要訊息，內容過多時先拆卡 |
| 每次重新撰寫生成提示詞 | 每組靈感都提供可直接複製的品牌提示詞 |

---

## 系統架構

```mermaid
flowchart LR
    A[使用者說一句想法] --> B[TARA 自動理解]
    B --> C[Brand DNA]
    B --> D[小D 幕後靈感矩陣]
    C --> E[TARA 直接完成第一版]
    D --> E
    E --> F{使用者滿意嗎}
    F -->|滿意| G[複製設計指令並使用]
    F -->|不滿意| H[更溫暖／更專業／更簡單／換一版]
    H --> E
```

### 完整工作流程

```mermaid
flowchart TD
    S1[1. 像聊天一樣說出想法] --> S2[2. TARA 自動判斷]
    S2 --> S3[3. 直接顯示第一版]
    S3 --> S4{4. 滿意嗎}
    S4 -->|是| S5[複製使用]
    S4 -->|否| S6[按一個修改方向]
    S6 --> S3
```

---

## 核心功能

### 1. TARA：只有一個輸入框

使用者不必理解設計術語，也不用先選設定，只需要輸入一句自然語言：

> 幫我的零基礎 AI 課程做一張封面，讓大家覺得 AI 沒有那麼可怕。

TARA 會自動推斷輸出類型、視覺方向、目標受眾、主標、副標與生成指令，直接顯示第一版。

### 2. 小D：留在幕後的靈感雷達

靈感庫仍採用 **10 種風格 × 10 種版型**，形成 100 組設計方向，但不再全部展示給初學者。TARA 會自動選出一組，只有修改時才切換。

#### 十種風格

| 風格 | 情緒 | 適合情境 |
|---|---|---|
| 溫暖教學 | 安心、清楚 | 零基礎課程與教學圖卡 |
| 日系手帳 | 親切、生活感 | 學習筆記與反思內容 |
| 自然療癒 | 沉靜、陪伴 | 成長、情緒與生活主題 |
| 清新雜誌 | 俐落、有品味 | 專題封面與品牌文章 |
| 親和扁平 | 好懂、活潑 | 工具教學與步驟說明 |
| 紙感拼貼 | 創意、有溫度 | 故事、回顧與個人品牌 |
| 柔和科技 | 新穎、不冰冷 | AI、數位工具與科技課程 |
| 極簡專業 | 可靠、聚焦 | 顧問內容與專業簡報 |
| 故事插畫 | 有共鳴、好記 | 案例、人物與情境敘事 |
| 明亮行動 | 積極、有動力 | 招生、活動與 CTA |

#### 十種版型

`主視覺` · `單句觀念` · `三步驟` · `前後對比` · `九宮摘要` · `重點清單` · `流程圖` · `人物故事` · `課程模組` · `行動召喚`

### 3. 先交付，再修改

- 第一次只顯示一個最佳判斷版本。
- 不滿意時才出現「更溫暖」「更專業」「更簡單」「換一版」。
- 一鍵複製包含品牌色、受眾、手機可讀與安全限制的設計指令。
- 「查看 TARA 這次怎麼判斷」收在可展開區，不干擾第一次操作。

---

## 快速開始

### 線上使用

不需要安裝任何軟體，直接開啟：

> <https://tarshar4242.github.io/tarshar-brand-studio/>

1. 用一句話告訴 TARA 想做什麼。
2. 按下「直接幫我做第一版」。
3. 滿意就複製；不滿意再按一個修改方向。

### 本機使用

```bash
git clone https://github.com/tarshar4242/tarshar-brand-studio.git
cd tarshar-brand-studio
open index.html
```

這是單檔靜態網站，不需要安裝套件，也沒有建置步驟。

---

## 使用 Codex Skill

專案同時包含可重複使用的 `tarshar-brand-director` Skill。

### 呼叫範例

```text
使用 $tarshar-brand-director，將這份課程內容規劃成一張封面與十張系列知識圖卡。
```

```text
使用 $tarshar-brand-director，根據這段內容直接完成一個最佳版本，不要先讓我選風格。
```

Skill 會依序讀取：

```mermaid
flowchart LR
    A[SKILL.md 工作流程] --> B[brand-dna.md]
    B --> C[inspiration-system.md]
    C --> D[output-specs.md]
    D --> E[結構化品牌產出]
```

---

## 專案結構

```text
tarshar-brand-studio/
├── .nojekyll                          # GitHub Pages 靜態網站設定
├── README.md                          # 專案完整說明
├── index.html                         # 單檔互動網站
├── assets/
│   └── readme-banner.svg              # README 品牌封面
└── skills/
    └── tarshar-brand-director/
        ├── SKILL.md                    # Agent 核心工作流程
        ├── agents/
        │   └── openai.yaml             # Codex 顯示名稱與預設提示
        └── references/
            ├── brand-dna.md            # 品牌定位、語氣與視覺規則
            ├── inspiration-system.md   # 小D靈感分類與推薦規則
            └── output-specs.md         # 封面、圖卡與銷售頁規格
```

---

## 技術設計

| 項目 | 使用方式 | 原因 |
|---|---|---|
| 前端 | HTML、CSS、原生 JavaScript | 不需安裝與建置，容易攜帶與教學 |
| 資料 | JavaScript 幕後判斷規則與 Design DNA | 自動選擇第一版，避免把複雜設定交給初學者 |
| 個人設定 | `localStorage` | 不需要伺服器，保留收藏與最近任務單 |
| 部署 | GitHub Pages | 免費、穩定、可直接分享網址 |
| Agent | Codex Skill | 將品牌流程、規格與參考資料模組化 |

### 資料與隱私

- 網站沒有帳號系統。
- 不會把使用者輸入傳送到伺服器。
- 任務單與收藏只保存在目前瀏覽器的 `localStorage`。
- 清除瀏覽器網站資料後，本機收藏也會消失。
- 網站不包含第三方分析追蹤程式。

---

## Tarshar Brand DNA v0.1

| 品牌元素 | 規格 |
|---|---|
| 品牌使命 | 把複雜 AI 講到完全沒基礎的人也能理解並立刻使用 |
| 核心受眾 | 台灣零基礎成人學習者、手機優先使用者 |
| 品牌個性 | 溫暖、清楚、務實、陪伴感、可信任 |
| 主色 | 幸運草綠 `#2F8F62` |
| 輔色 | 天空藍 `#4C9ED9` |
| 暖底 | 奶油白 `#FFF9EE` |
| 強調色 | 暖橘 `#F29A4A` |
| 文字色 | 深墨綠 `#173C32` |
| 教學順序 | 生活比喻 → 白話解釋 → 正式定義 → 操作步驟 → 檢查點 |
| 固定署名 | `🍀Learn AI with Tarshar ｜2026` |

### 品牌品管清單

- [ ] 零基礎讀者能在三秒內看懂主題。
- [ ] 一張圖只保留一個主要訊息。
- [ ] 專有名詞先白話、後正式名稱。
- [ ] 手機尺寸下文字仍然清楚可讀。
- [ ] 系列作品使用一致色彩、字體層級、插畫筆觸與邊距。
- [ ] 知識圖卡包含精確品牌署名。
- [ ] 沒有複製其他品牌、創作者或參考作品的獨特元素。

---

## 輸出規格

| 輸出 | 預設尺寸 | 內容原則 |
|---|---|---|
| 網站課程封面 | 1600 × 900 | 縮圖下仍能辨識主題，主標 12–20 字 |
| 社群分享圖片 | 1200 × 630 | 適合連結預覽與橫式社群貼文 |
| Instagram 直式圖卡 | 1080 × 1350 | 手機閱讀優先，保留固定署名區 |
| 方形圖卡 | 1080 × 1080 | 適合摘要、九宮與單句觀念 |
| 銷售頁 | 響應式 | 先做手機版閱讀任務，再擴充桌面版 |

---

## 部署與更新

網站由 GitHub Pages 直接發布 `main` 分支根目錄。

```mermaid
flowchart LR
    A[修改本機檔案] --> B[驗證 HTML／Skill]
    B --> C[Git Commit]
    C --> D[Push 到 main]
    D --> E[GitHub Pages 自動建置]
    E --> F[公開網站更新]
```

| 設定 | 目前值 |
|---|---|
| Repository | `tarshar4242/tarshar-brand-studio` |
| Default branch | `main` |
| Pages source | `main` / `/` |
| HTTPS | 強制啟用 |
| 網站 | <https://tarshar4242.github.io/tarshar-brand-studio/> |

---

## 已知限制

- 第一版尚未串接圖片生成 API；目前輸出品牌任務單與提示詞。
- 收藏與任務單只存在單一瀏覽器，尚未提供跨裝置同步。
- Brand DNA 是 v0.1，仍需以最終 Logo、授權字體與正式色票校準。
- 100 組 Design DNA 是 TARA 幕後的設計決策矩陣，不是要求使用者瀏覽的圖庫。
- 專案目前未附開源授權檔；未經許可請勿將品牌內容用於其他品牌。

---

## 發展路線

- [x] 品牌任務單產生器
- [x] 10 種風格 × 10 種版型
- [x] 一句話直接產生第一版設計方向
- [x] 不滿意時才顯示四個修改方向
- [x] Tarshar Brand DNA 與 Codex Skill
- [x] GitHub Pages 公開部署
- [ ] 加入實際作品預覽與案例頁
- [ ] 支援品牌專案匯出／匯入
- [ ] 加入封面、圖卡與銷售頁模板
- [ ] 串接圖片生成與品牌一致性檢查
- [ ] 建立可擴充的設計參考資料庫

---

## 常見問題

<details>
<summary><strong>這個網站會把我輸入的內容上傳嗎？</strong></summary>

不會。網站是純前端工具，內容只保存在目前瀏覽器。

</details>

<details>
<summary><strong>100 組靈感是否等於 100 張參考圖片？</strong></summary>

不是。它是 TARA 在幕後使用的設計決策矩陣。初學者不需要逐一瀏覽或選擇，也不是複製現有作品。

</details>

<details>
<summary><strong>可以直接用它產生圖片嗎？</strong></summary>

目前版本產生品牌任務單與提示詞；將提示詞交給支援圖片生成的工具即可繼續製作。

</details>

<details>
<summary><strong>如何保持一整套圖卡風格一致？</strong></summary>

先鎖定同一組 Brand DNA、風格、版型規則、人物設定、色彩與署名，再批次製作；不要逐張重新決定風格。

</details>

---

<div align="center">

### 讓品牌視覺成為可以累積的能力

**[開啟 Tarshar Brand Studio](https://tarshar4242.github.io/tarshar-brand-studio/)**

🍀Learn AI with Tarshar ｜2026

</div>
