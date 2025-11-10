# Movie Ticket Booking System

## 介紹
Movie Ticket Booking System 是一個電影票務預訂系統的資料庫專案，旨在提供一個有效的方式來管理電影票的預訂、查詢和管理。

## 功能
- **資料庫表格建立與管理**：使用 SQL 腳本創建必要的資料表。
- **資料初始化與插入**：預設資料的插入腳本以便於測試和使用。
- **資料查詢與測試**：提供查詢腳本以測試資料的正確性。
- **預存程序定義**：定義業務邏輯的預存程序。
- **資料庫觸發器設定**：設置觸發器以自動處理特定事件。
- **資料庫視圖建立**：創建視圖以便於查詢。
- **角色與權限管理**：管理使用者的角色和權限。
- **索引優化**：提高查詢效率的索引設置。

## 技術堆棧
- SQL 資料庫（如 MySQL、SQL Server 或 PostgreSQL）
- 關聯式資料庫管理系統（RDBMS）

## 安裝
1. 克隆此存儲庫：
   ```bash
   git clone https://github.com/pineappletaco/Movie-Ticket-Booking-System.git
   ```
2. 使用 SQL 客戶端工具執行 `CreateTable.sql` 來建立資料表。
3. 執行 `Insert.sql` 以插入初始資料。

## 使用
- 使用 SQL 查詢腳本 `SelectTest.sql` 測試資料的有效性。
- 根據需要調整預存程序和觸發器。

