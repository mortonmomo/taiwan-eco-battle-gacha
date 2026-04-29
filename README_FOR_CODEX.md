# 《臺灣生態戰》Codex 接手檔案包

請先閱讀：

1. `Taiwan_Eco_Battle_Claude_Web_Handoff.md`
2. `Taiwan_Eco_Battle_Art_Requirements_and_Style_Guide.docx`
3. `taiwan_eco_battle_web_gacha_mobile.html`

說明：
- `taiwan_eco_battle_web_gacha_mobile.html` 是目前前導網頁版 HTML，已包含抽卡、圖鑑、生物百科詳情頁、Wikimedia 圖片載入與已套用的視覺素材。
- 目前任務建議是先理解並整理，不要直接重寫整個專案。
- 這是前導網頁抽卡版，不是正式戰鬥版；正式版未來會由 Unity 製作。

建議 Codex 第一階段：
1. 先檢查目前單檔 HTML 的結構。
2. 保留全部既有功能。
3. 將單檔拆成可維護的前端專案：`index.html`、`data/`、`src/`、`styles/`、`assets/`。
4. 不要刪除首發 120 種資料、Wikimedia 載圖、fallback、localStorage、圖鑑詳情頁與已套用美術。
