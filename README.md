# 📊 Customer Segmentation RFM Analysis
## 📌 Latar Belakang
Dalam dunia bisnis modern, memahami perilaku pelanggan menjadi kunci untuk meningkatkan loyalitas dan profitabilitas. Salah satu pendekatan yang efektif untuk segmentasi pelanggan adalah RFM Analysis (Recency, Frequency, Monetary). RFM memungkinkan bisnis untuk mengidentifikasi kelompok pelanggan berdasarkan seberapa baru mereka bertransaksi (Recency), seberapa sering mereka bertransaksi (Frequency), dan seberapa banyak uang yang mereka belanjakan (Monetary). Dengan segmentasi ini, perusahaan dapat menyusun strategi pemasaran yang lebih tertarget dan personal.

## 🎯 Tujuan Proyek
Tujuan dari proyek ini adalah untuk melakukan segmentasi pelanggan berdasarkan nilai RFM guna:
- Mengetahui kelompok pelanggan loyal, potensial, atau yang berisiko churn.
- Memberikan wawasan kepada tim pemasaran untuk kampanye yang lebih efektif.
- Membantu pengambilan keputusan bisnis berdasarkan perilaku pelanggan.

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

## ▶️ Cara Menjalankan
Clone repositori ini:

```bash
git clone https://github.com/IsmaDDamara/Customer-Segmentation-RFM-Analysis.git
cd notebook
```

Jalankan analisis:
```bash
jupyter notebook RFM_Segmentation.ipynb
```
