# Review guidelines（onholdlab 網頁遊戲）

- 本頁是點擊加語音操作，只用 CSS 的 `inapp-lock`；不要加攔截 touchstart/touchmove 的程式，會讓輸入框不能用。
- 不可用 `100vh` 排版；用 `100%` 或 `100dvh`。
- 轉址與 `pushState` 的目標必須是實際存在的檔案；不可相對路徑指回自己（曾造成 survive 頁 404）。itch.io 不會自動補 `index.html`，路徑要帶完整檔名。
- `og:image` 必須是絕對網址。
- 只回報會讓玩家玩不了或看錯的問題；不要回報命名、格式、風格。
