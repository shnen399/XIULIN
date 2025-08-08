✅ PIXNET 自動發文系統使用說明：

1. 修改 pixnet_accounts.txt 加入帳密（格式：帳號:密碼）
2. 如需 LINE Notify，請至 .env 填入 LINE_TOKEN
3. Render 上部署請使用 render.yaml
4. 預設每 180 秒輪替帳號自動發文，可調整 .env 中 CRON_INTERVAL
5. 可手動進入 /dashboard 控制發文與查看狀態
