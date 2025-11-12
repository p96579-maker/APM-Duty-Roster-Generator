# APM Duty Roster Generator (v23)

修正「Cannot access 'groupType' before initialization」錯誤：
- 先讀取 groupType，再進行任何 DOM 操作；頁面只保留一個結果區。
- 頁面標題會顯示版本號：**v23**。

功能與 v22 一樣：
- 一次只出 4 日（DAY 或 NIGHT）；
- DAY 的 PM_LEADER 4 日內不會落其他崗位；
- NIGHT 的 DAILY_LEADER 遵從名單且可手動調整；
- 下載時只匯出目前顯示的一組。
