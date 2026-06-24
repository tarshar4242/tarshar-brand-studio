# Tarshar Brand Studio

「小塔品牌導演」與「小D靈感雷達」組成的品牌視覺作業系統，把課程、文章與教學想法轉成一致的封面、知識圖卡和銷售頁規格。

## 線上使用

<https://tarshar4242.github.io/tarshar-brand-studio/>

## 核心功能

- 小塔品牌導演：輸入主題、受眾、輸出形式與原始內容，產生可直接交給 AI 或設計師的品牌任務單。
- 小D靈感雷達：10 種風格 × 10 種版型，提供 100 組可搜尋的設計方向。
- 靈感收藏：把常用方向保存在瀏覽器中。
- 提示詞複製：每組靈感都附有 Learn AI with Tarshar 專用生成提示詞。
- Brand DNA：保存品牌使命、受眾、教學語氣、色彩與固定署名規範。
- Codex Skill：可透過 `$tarshar-brand-director` 重複執行品牌工作流。

## 使用方式

1. 開啟線上網站。
2. 在「小塔品牌導演」填入主題與原始內容。
3. 產生並複製品牌任務單。
4. 到「小D靈感雷達」篩選風格與版型。
5. 收藏合適方向，複製提示詞進行後續製作。

所有資料只保存在目前瀏覽器的 `localStorage`，不會上傳到伺服器。

## 專案結構

```text
tarshar-brand-studio/
├── index.html
├── README.md
└── skills/
    └── tarshar-brand-director/
        ├── SKILL.md
        ├── agents/openai.yaml
        └── references/
            ├── brand-dna.md
            ├── inspiration-system.md
            └── output-specs.md
```

## 本機使用

下載專案後，直接以瀏覽器開啟根目錄的 `index.html`，不需要安裝套件或執行建置指令。

## 品牌規則

知識圖卡固定使用以下署名：

`🍀Learn AI with Tarshar ｜2026`

目前 Brand DNA 為 v0.1。正式商業使用前，請以最終 Logo、授權字體和品牌色票校準。

---

🍀Learn AI with Tarshar ｜2026
