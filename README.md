# 📊 Optimizing Customer Strategy with RFM Analysis

## 📌 Background

<<<<<<< HEAD
In today’s business landscape, understanding customer behavior is essential for enhancing loyalty and profitability. One effective method for customer segmentation is **RFM Analysis**—which stands for **Recency**, **Frequency**, and **Monetary**. RFM allows businesses to categorize customers based on how recently they made a purchase (Recency), how often they purchase (Frequency), and how much they spend (Monetary). With this segmentation, companies can tailor marketing strategies to be more targeted and personalized.

## 🎯 Project Objectives

The objectives of this project are to perform customer segmentation based on RFM values in order to:

* Identify groups of loyal, potential, or at-risk customers.
* Provide insights to the marketing team for more effective campaign targeting.
* Support data-driven business decisions based on customer behavior.

## 🧭 Analysis Steps

1. **Data Collection**

   * Transaction dataset including customer ID, transaction dates, and purchase amounts.
=======
## 🧭 Langkah-langkah Analisis
1. **Pengumpulan Data**
- Dataset transaksi pelanggan yang mencakup ID pelanggan, tanggal transaksi, dan nilai pembelian.

2. **Pembersihan Data**
- Menangani nilai yang hilang dan duplikat
- Konversi format tanggal
- Menyaring data yang tidak relevan

3. **Perhitungan Nilai RFM**
- Recency: Berapa hari sejak transaksi terakhir hingga tanggal referensi.
- Frequency: Jumlah transaksi yang dilakukan pelanggan.
- Monetary: Total nilai uang yang dibelanjakan.

4. **Skoring RFM**
- Memberi skor 1–5 untuk masing-masing komponen RFM berdasarkan kuantil.
- Menggabungkan skor menjadi segmentasi pelanggan.

5. **Segmentasi Pelanggan**
- Mengelompokkan pelanggan ke dalam segmen seperti:
Champions, Loyal Customers, Potential Loyalist, At Risk, Lost Customers.

6. **Visualisasi dan Dashboard Interaktif**
- Menampilkan distribusi segmen, statistik masing-masing segmen, dan insights lainnya.
>>>>>>> 248d199256d95f87de07905ab2682c10b631f64d

2. **Data Cleaning**

   * Handle missing values and duplicates
   * Convert date formats
   * Filter out irrelevant or test data

3. **RFM Calculation**

   * **Recency**: Days since the last transaction from a reference date
   * **Frequency**: Number of transactions per customer
   * **Monetary**: Total amount spent by each customer

4. **RFM Scoring**

   * Assign scores from 1–5 for each RFM component based on quantiles
   * Combine scores to create RFM segments

5. **Customer Segmentation**

   * Group customers into segments such as:
     **Champions**, **Loyal Customers**, **Potential Loyalists**, **At Risk**, **Lost Customers**

6. **Visualization & Interactive Dashboard**

   * Display segment distributions, segment-level statistics, and other actionable insights

## ▶️ How to Run

Clone this repository:

```bash
git clone https://github.com/IsmaDDamara/Customer-Segmentation-RFM-Analysis.git
cd notebook
```

Run the analysis notebook:

```bash
jupyter notebook RFM_Segmentation.ipynb
```
