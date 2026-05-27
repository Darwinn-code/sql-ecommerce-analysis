# SQL Retail Store Analytics Project

## 📌 Project Overview
Proyek ini dibuat untuk mensimulasikan peran seorang Data Analyst di sebuah perusahaan ritel online (*e-commerce*). Tujuan utama dari proyek ini adalah membangun database toko ritel dari nol dan melakukan analisis bisnis tingkat lanjut untuk menemukan produk yang paling menguntungkan menggunakan SQL.

## 🛠️ Tech Stack & Database Name
* **Database Management System:** MySQL / PostgreSQL
* **Database Name:** `retail_store_db`
* **Table Name:** `online_store_products`

---

## Part 1: Database & Table Creation (DDL)
Pada tahap ini, saya merancang arsitektur database dan membuat tabel untuk menampung data produk toko online.

*(Catatan: Kode lengkap pembuatan database dan pengisian data secara detail telah dipisahkan ke dalam file script SQL khusus agar siap dijalankan).*

## Part 2: Populating the Data (DML)
Pada tahap ini, saya memasukkan 200 data produk realistis ke dalam tabel `online_store_products`. Data ini dibagi menjadi 5 kategori utama untuk menyimulasikan data transaksi asli.

<details>
<summary><b>Klik di sini untuk melihat seluruh 200 data produk SQL (INSERT INTO)</b></summary>

```sql
INSERT INTO online_store_products (product_id, product_name, category, cost_price, selling_price)
VALUES 
(1, 'Oversized Black T-Shirt', 'Fashion & Accessories', 45000, 75000),
(2, 'White Casual Sneakers', 'Fashion & Accessories', 120000, 195000),
(3, 'Canvas Tote Bag', 'Fashion & Accessories', 20000, 35000),
(4, 'Leather Minimalist Wallet', 'Fashion & Accessories', 60000, 110000),
(5, 'Bucket Hat Unisex', 'Fashion & Accessories', 15000, 29000),
(6, 'High-waisted Loose Jeans', 'Fashion & Accessories', 85000, 145000),
(7, 'Knitted Cardigan', 'Fashion & Accessories', 70000, 115000),
(8, 'Ankle Socks Pack of 5', 'Fashion & Accessories', 18000, 30000),
(9, 'Waterproof Windbreaker Jacket', 'Fashion & Accessories', 110000, 185000),
(10, 'Premium Chino Pants', 'Fashion & Accessories', 90000, 150000),
(11, 'Corduroy Shoulder Bag', 'Fashion & Accessories', 35000, 59000),
(12, 'Sunglasses Retro Oval', 'Fashion & Accessories', 12000, 25000),
(13, 'Stainless Steel Ring Set', 'Fashion & Accessories', 8000, 19000),
(14, 'Pleated Skirt', 'Fashion & Accessories', 55000, 89000),
(15, 'Silk Hair Scrunchies', 'Fashion & Accessories', 3000, 10000),
(16, 'Bomber Jacket Classic', 'Fashion & Accessories', 130000, 210000),
(17, 'Leather Waist Belt', 'Fashion & Accessories', 25000, 45000),
(18, 'Linen Short Pants', 'Fashion & Accessories', 40000, 69000),
(19, 'Oversized Flannel Shirt', 'Fashion & Accessories', 65000, 105000),
(20, 'Casual Slip-on Sandals', 'Fashion & Accessories', 30000, 55000),
(191, 'To Do List Daily Notebook', 'Stationeries & Hobbies', 12000, 22000),
(192, 'Canvas Tote Bag for Painting', 'Stationeries & Hobbies', 15000, 27000),
(193, 'Wax Seal Stamp Starter Kit', 'Stationeries & Hobbies', 75000, 129000),
(194, 'Geometry Set Metal Compass', 'Stationeries & Hobbies', 18000, 30000),
(195, 'Whiteboard Marker Pens 4pcs', 'Stationeries & Hobbies', 14000, 24000),
(196, 'Self Inking Custom Stamp', 'Stationeries & Hobbies', 30000, 55000),
(197, 'Craft Paper Scissors Wave 6pc', 'Stationeries & Hobbies', 25000, 44000),
(198, 'B6 Pocket Dotted Notebook', 'Stationeries & Hobbies', 14000, 24000),
(199, 'Glitter Glue Pens Set of 10', 'Stationeries & Hobbies', 16000, 28000),
(200, 'Leather Journal Retro Strap', 'Stationeries & Hobbies', 65000, 115000);
