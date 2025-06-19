# 📊Analisis Profitabilitas dan Kinerja Penjualan Produk SaaS AWS
---
Proyek ini bertujuan untuk menganalisis performa penjualan produk SaaS milik Amazon Web Services (AWS), dengan fokus khusus pada produk Marketing Suite yang menunjukkan profit negatif pada sejumlah transaksi. Analisis ini membantu perusahaan mengidentifikasi penyebab kerugian dan memberikan rekomendasi berbasis data untuk perbaikan strategi penjualan dan diskon.
## 🎯 Tujuan Analisis
1. Mengidentifikasi pola transaksi dengan profit negatif.

2. Mengevaluasi pengaruh diskon terhadap penurunan margin.

3. Menelusuri kontribusi dari produk Marketing Suite terhadap kerugian.

4. Memberikan insight untuk perbaikan strategi pricing dan promosi.
---
## 🗃️ Dataset
Dataset berisi data transaksi penjualan SaaS AWS, dataset dapat diakses melalui link berikut:
https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales?select=SaaS-Sales.csv

#### Data bersifat simulasi untuk keperluan pembelajaran
---
## 🔍 Proses Analisis
1. Notebook ini mencakup tahapan berikut:

   - Data Understanding

   - Distribusi jumlah transaksi dan nilai profit.

2. Identifikasi jumlah transaksi dengan nilai profit negatif.

   - Exploratory Data Analysis (EDA)

   - Analisis distribusi diskon dan keterkaitannya dengan profit negatif.

   - Fokus khusus pada produk Marketing Suite, karena memiliki frekuensi tertinggi kasus rugi.

   - Visualisasi:

      - Boxplot untuk outlier pada Sales, Discount, dan Profit

      -  Bar chart dan pie chart untuk persebaran produk, region, dan segmen pelanggan
3. Analisis Profit Negatif
   - Agregasi total rugi berdasarkan produk,wilayah, dan segmen pelanggan
---              
## 📌 Insight Utama
- Produk Marketing Suite menyumbang proporsi tertinggi dari total transaksi rugi.
- Transaksi dengan diskon tinggi sering kali menghasilkan profit negatif
- Beberapa region dan segmen pelanggan tertentu cenderung menunjukkan nilai profit negatif secara konsisten

## 💡 Rekomendasi
Analisis ini menunjukkan bahwa sejumlah besar transaksi mengalami **profit negatif**, terutama pada produk **Marketing Suite**. Penyebab utama kerugian berasal dari **diskon yang terlalu tinggi**, dan **segmen pelanggan tertentu**. Untuk mengatasi hal ini, berikut beberapa rekomendasi yang bisa dipertimbangkan:

### 1. 🎯 Pendekatan Personal terhadap Pelanggan Bernilai Tinggi
Kenali pola transaksi pelanggan yang sering melakukan pembelian dan tetap memberikan keuntungan. Gunakan pemahaman ini untuk merancang strategi komunikasi, dukungan, dan retensi yang lebih sesuai dengan kebutuhan mereka.

### 2. 🛑 Strategi Penanganan Transaksi Merugi
Identifikasi area atau segmen pelanggan yang sering menyebabkan kerugian. Pertimbangkan evaluasi ulang atas penawaran, layanan, atau bahkan kelayakan kerja sama jika pola kerugian terus berulang.

### 3. 💵 Evaluasi Harga dan Persepsi Produk
Tinjau kembali struktur harga dan nilai yang dirasakan oleh pelanggan terhadap **Marketing Suite**. Pastikan bahwa harga produk sebanding dengan manfaat yang diberikan, agar tetap kompetitif di pasar.

### 4. 📉 Optimasi Kebijakan Diskon
Kembangkan sistem diskon yang lebih **fleksibel dan selektif**, seperti diskon bertingkat berdasarkan volume pembelian atau loyalitas pelanggan. Hindari pemberian diskon besar-besaran tanpa perhitungan dampak terhadap margin keuntungan.

### 5. 🚀 Inisiatif Penjualan Tanpa Diskon
Dorong peningkatan penjualan melalui cara lain, seperti:
- Penambahan fitur produk yang lebih relevan
- Integrasi dengan layanan lain
- Kampanye pemasaran berbasis manfaat produk (bukan harga murah)

---

Dengan strategi ini, perusahaan dapat **meminimalkan kerugian tanpa mengorbankan volume penjualan**, serta membangun hubungan jangka panjang yang lebih sehat dengan pelanggan. Pendekatan berbasis data seperti ini penting untuk menjaga keberlanjutan dan profitabilitas bisnis ke depan.
    
