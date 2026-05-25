

```sql
-- ===================================================
-- PART 1: DATABASE & TABLE CREATION (DDL)
-- ===================================================

CREATE DATABASE retail_store_db;
USE retail_store_db;

CREATE TABLE Online_Product_Store (
    product_id INT PRIMARY KEY,
    product_name VARCHAR(100),
    category VARCHAR(50),
    cost_price INT,
    selling_price INT
);
