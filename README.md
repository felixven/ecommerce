# 電商平台 (E-commerce System)

## 系統介紹：
本專案為 Spring Boot + React.js 開發的電商系統，模擬線上購物商城流程，實作了會員管理、商品瀏覽、購物結帳與支付金流等功能。

## 前後端完整原始碼：
- 前端：[E-commerce Frontend](https://github.com/felixven/ecommerce-frontend.git)
- 後端：[E-commerce Backend](https://github.com/felixven/ecommerce-backend.git)

## 系統展示：
- Demo網址：https://ecommerce-frontend-ylwz.vercel.app/
- **此 Demo 使用 Render Free Tier，閒置超過 15 分鐘會休眠，首次運行需等待伺服器喚醒。**
- 可使用以下資料登入網頁，請輸入 **帳號或電郵** 和密碼。  
- 也歡迎註冊新帳密進行登入。

|帳號      |電郵                   |密碼        |
|-------- |--------------------- |------------|
| user1   |user1@example.com     |password1   |
| guest1  |guest1@gmail.com      |guest1      |
- 此專案使用 Line Pay Sandbox 模擬付款流程，無實際金流。
- Stripe付款：
   - 卡號：4242 4242 4242 4242
   - 卡片到期日需晚於當前日期（例如 12/34），驗證碼可輸入任意 3 碼

## 使用技術：
- 前端：Vite / React.js / Tailwind.css
- 後端：Java Spring Boot / MySQL
- 支付：Line Pay / Stripe
- 前端部署於 Vercel，後端以 Docker 容器化部署於 Render，並使用 MySQL 資料庫。

## 畫面展示
![系統畫面展示](https://github.com/felixven/ecommerce-frontend/blob/main/docs/shopping-addcart-flow.gif?raw=true)


