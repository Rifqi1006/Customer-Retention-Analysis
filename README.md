# 👥 Customer Retention Analysis
 
Proyek ini melakukan analisis retensi pelanggan menggunakan metode **cohort analysis** pada dataset ritel online. Cohort analysis merupakan teknik analisis yang mengelompokkan pelanggan berdasarkan waktu pertama mereka melakukan transaksi, kemudian memantau perilaku mereka dari waktu ke waktu. Analisis ini berguna untuk mengukur seberapa baik perusahaan mempertahankan pelanggannya serta mengidentifikasi pola perilaku pelanggan.

---

## 🎯 Tujuan  
- Mengukur pola retensi pelanggan dari waktu ke waktu menggunakan pendekatan cohort analysis. 
- Menjadi portfolio yang menunjukkan kemampuan dalam menganalisis data serta menghasilkan actionable insights.  

---

## 📁 Struktur Proyek  
```
Customer-Retention-Analysis/
├── Online Retail - Cohort Analysis.ipynb   # Jupyter notebook dengan analisis lengkap
├── Customer Retention (Dashboard).pbit     # Dashboard Power BI
├── Model View.jpg                          # Skema model data
├── Project Process.jpg                     # Preview dashboard
├── Share.png                               # Ikon dalam dashboard
└── README.md
```
---

## 📋 Dataset  
Dataset bersumber dari Kaggle: *Retail Sales Dataset*  
Data ini merepresentasikan penjualan toko online dari Januari – Desember 2010 

- Ukuran Data: 461.773 baris, 7 kolom  
- Karakteristik Data: berisi transaksi penjualan mencakup informasi pesanan, produk, jumlah, harga, dan pelanggan.  
- Struktur Kolom:
  - Data Transaksi Penjualan (`order_id`, `order_date`)  
  - Informasi Produk (`product_code`, `product_name`, `quantity`, `price`)  
  - Informasi Pelanggan (`customer_id`)  

---

## 📈 Metrik Analisis  
Analisis retensi pelanggan dilakukan menggunakan tiga metrik utama, dengan dua dimensi pengukuran (jumlah dan persentase).  

- **Customer Retention** → Persentase pelanggan yang kembali berbelanja setelah transaksi awal.  
- **Sales Retention** → Nilai penjualan yang berhasil dipertahankan oleh masing-masing cohort.  
- **Average Sales per Customer** → Rata-rata nilai belanja per pelanggan dalam cohort tertentu.  

---

## 🖥️ Dashboard Preview  

Berikut adalah tampilan dashboard interaktif yang dibuat dengan Power BI.  

![Alt Text](https://drive.google.com/uc?export=view&id=13ntBfmNSQqAD79PlcMjtMdugmDPuiTnG)

Dashboard interaktif ini memungkinkan pengguna untuk melacak pola retensi pelanggan dari waktu ke waktu, menganalisis performa setiap cohort berdasarkan metrik retensi pelanggan dan penjualan, mengidentifikasi cohort dengan retensi tertinggi dan terendah, membandingkan performa antar cohort, serta mendapatkan wawasan untuk pengembangan strategi peningkatan loyalitas.

---

## 🔧 Teknologi dan Tools  
Analisis dilakukan menggunakan Python dengan dukungan library utama:  

- Bahasa Pemrograman: `Python`  
- Analisis Data: `Pandas`, `NumPy`  
- Visualisasi Data: `Matplotlib`, `Seaborn`
- Visualisasi Interaktif: `Power BI` 
- Pengolahan Tanggal/Waktu: `datetime`  
- Lingkungan Pengembangan: `Jupyter Notebook`  

---

## 🔍Key Insights  
- 64-83% pelanggan tidak kembali setelah pembelian pertama, sehingga diperlukan strategi engagement pasca-pembelian yang lebih kuat.  
- Cohort 2010-01 unggul dalam retensi jangka panjang dengan nilai penjualan konsisten hingga periode ke-11, sementara cohort lain mengalami penurunan signifikan. 
- Rata-rata nilai belanja meningkat hingga 81% pada pelanggan yang bertahan, membuktikan kesuksesan strategi upselling dan loyalitas.
- Cohort Q1 dengan retention rate 40%, merepresentasikan adanya kelompok pelanggan yang loyal.
- Sebagian besar cohort kesulitan mempertahankan lebih dari 20-30% pelanggannya hingga bulan ke-6.
