# 電商平台 (E-commerce System)

## 系統介紹：
本專案為模擬線上購物商城的練習專案，採用前後端分離架構：
- 前端：以 React.js + Tailwind CSS 開發，開發使用者操作介面。
- 後端：以 Spring Boot + MySQL 建立 RESTful API，並支援 JWT 驗證與授權。
- 支付串接：支援 Line Pay 與 Stripe，模擬完整線上購物付款流程。

## 功能介紹：
- 會員註冊、登入、登出
- 瀏覽商品、篩選排序商品
- 購物車：商品加入、刪除、修改數量
- 訂單付款結帳、歷史訂單查詢

## 系統展示：
- 前端部署於 Vercel，後端以 Docker 容器化部署於 Render，並使用 MySQL 資料庫。
- Demo網址：平台架設於 [Vercel](https://ecommerce-frontend-ylwz.vercel.app/)
- 可使用以下資料登入網頁，請輸入 **帳號或電郵** 和密碼。  
- 也歡迎註冊新帳密進行登入。

|帳號     |電郵                   |密碼      |
|--------|--------------------- |----------|
| User1  | user1@example.com    |admin123  |
| User2  |user2@example.com    |user123   |

## 使用技術：
- 前端：Vite / React.js / Tailwind.css
- 後端：Java Spring Boot / MySQL

## 前後端完整原始碼：
- 前端：[Front-End Repository](https://github.com/felixven/ecommerce-frontend.git)
- 後端：[Back-End Repository](https://github.com/felixven/ecommerce-backend.git)
