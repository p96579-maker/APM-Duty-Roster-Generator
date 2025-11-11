# APM Duty Roster Generator (v9)

修正：
- 修正 JavaScript 語法錯誤（重複宣告 `const roles`），導致網頁完全唔 load / 冇反應。
- 功能同 v8 一樣：
  - MF / WH / EH：Day 第一日揀中 3 個人，用喺 4 日 DAY 入面輪流當值，同一人喺同一個崗位唔會連續超過 2 日。
  - 4 日 DAY → 2 日 OFF → 4 日 NIGHT。
  - BCR / DRIVER / CONTROLLER：依有當值日計，連續 2 日。
  - PM_LEADER：4 個 DAY 同一人。
  - 可用人手 (Availability) + 下方表格 cell 可點擊，用只顯示當日未用過嘅人作選擇。

用法：
1. 把本資料夾內容上載到 GitHub repo。
2. 在 repo Settings → Pages 開啟 GitHub Pages（branch: main / master，folder: root）。
3. 用 GitHub Pages 網址開啟 `index.html` 介面即可使用。
