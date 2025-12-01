# **RFM Analysis: Insights into E-Commerce Customer Behavior & Sales Analysis**

## **Table of Content**

1. Introduction
2. Data Understanding
3. Data Cleaning
4. Correlation Analysis
5. Sales Analysis
6. Customer Analysis 
7. Simpulan
8. Rekomendasi

## **Overview**
- Latar Belakang
Dalam industri e-commerce, memahami perilaku pelanggan menjadi tantangan penting karena setiap pelanggan memiliki pola pembelian yang berbeda.

- Pernyataan Masalah
Perusahaan e-commerce sering menghadapi kesulitan dalam memahami perbedaan perilaku pelanggan. Bagaimana e-commerce dapat mengelompokkan pelanggan secara efektif berdasarkan perilaku pembelian mereka untuk meningkatkan retensi dan mengoptimalkan strategi pemasaran?

Stakeholders: Marketing Department of E-Commerce Company in Turkey

## **Project Structure**
```
RFM-Portfolio-Modul-2/
├── RFM_Analysis.ipynb                                                                      # Main program entry point
├── ecommerce_customer_behavior_dataset_v2.csv                                              # Raw Dataset
├── E-Commerce_Customer_Behavior_Analysis_Cleaned.xlsx                                      # Cleaned Dataset
├── E-Commerce_Customer_Behavior_Analysis.xlsx                                              # Dataset Analysis
├── RFM Analysis: Insights into E-Commerce Customer Behavior & Sales Analysis.pdf           # Powerpoint Slides
├── RFM_Analysis_Tableau.twbx                                                               # Tableau Dashboard
└── README.md                                                                               # This file
```

##  **Deskripsi Dataset**
Dataset ini berisi 17.049 baris dan 18 kolom yang merepresentasikan transaksi pada sebuah platform e-commerce. Dataset telah melalui pemeriksaan kualitas data dan dinyatakan:

- Tidak terdapat data duplikat
- Tidak terdapat missing values
- Seluruh kolom memiliki tipe data yang konsisten

### Data Dictionary:

| # | Fitur | Deskripsi
| --- | --- | ---
| 1 | Order_ID | Unique identifier for each order
| 2 | Customer_ID | Unique identifier for each customer
| 3 | Date | Date of the transaction
| 4 | Age | Customer’s age
| 5 | Gender | Customer gender
| 6 | City | Customer’s city
| 7 | Product_Category | Category of product purchased
| 8 | Unit_Price | Price per unit of the product
| 9 | Quantity | Number of units purchased
| 10 | Discount_Amount | Discount applied to the order
| 11 | Total_Amount | Final amount paid
| 12 | Payment_Method | Payment method used
| 13 | Device_Type | Device used during the purchase
| 14 | Session_Duration_Minutes | Duration of browsing session
| 15 | Pages_Viewed | Number of pages viewed
| 16 | Is_Returning_Customer | Indicates whether the customer is returning
| 17 | Delivery_Time_Days | Delivery duration
| 18 | Customer_Rating | Customer satisfaction rating

### Data Types
- Numerik: Age, Unit_Price, Quantity, Discount_Amount, Total_Amount, Session_Duration_Minutes, Pages_Viewed, Delivery_Time_Days, Customer_Rating
- Kategorikal: Order_ID, Customer_ID, Gender, City, Product_Category, Payment_Method, Device_Type
- Boolean: Is_Returning_Customer
- Datetime: Date

## **Sales Analysis**
- **Best Selling** by Product Category
- **RFM Analysis untuk Segmentasi Pelanggan**
  - Platinum: Pelanggan paling bernilai yang sangat sering berbelanja, bernilai tinggi, dan sangat loyal.
  - Gold: Pelanggan bernilai tinggi dengan pola belanja kuat dan potensi besar untuk ditingkatkan.
  - Silver: Pelanggan dengan aktivitas moderat yang masih dapat ditingkatkan melalui promosi ringan.
  - Bronze: Pelanggan beraktivitas rendah dengan nilai transaksi kecil dan keterlibatan minimal.
  - At Risk: Pelanggan yang sebelumnya aktif tetapi sudah lama tidak berbelanja dan berisiko churn.

## **Project Objectives**
- Melakukan scoring RFM untuk mengidentifikasi segmen nilai pelanggan.
- Menganalisis tren penjualan, kategori produk terpopuler, dan demografi pelanggan.
- Menghasilkan insight untuk meningkatkan retensi pelanggan, loyalitas, dan efisiensi pemasaran.

- Memberikan rekomendasi strategis untuk setiap segmen pelanggan.

## **Publication**
[Tableau Public](https://public.tableau.com/views/RFM_Analysis_Tableau/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)



