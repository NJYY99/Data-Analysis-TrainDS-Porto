# Analisis Penjualan Superstore & Dasbor Interaktif

## 📝 Ringkasan Proyek
Proyek ini merupakan studi kasus analisis data *end-to-end* pada dataset Global Superstore. Analisis ini bertujuan untuk mengeksplorasi data penjualan secara mendalam, mengidentifikasi faktor-faktor kunci yang mendorong pendapatan dan profitabilitas, serta menyajikan temuan dalam sebuah dasbor eksekutif yang interaktif untuk mendukung pengambilan keputusan strategis.

Proses analisis dimulai dengan mengikuti metode CRISP-DM. dimuali dari pembersihan dan persiapan data menggunakan Python, dilanjutkan dengan analisis data eksplorasi (EDA) untuk menemukan pola, dan diakhiri dengan pembuatan dasbor di Tableau.

##  dashboards Dasbor Eksekutif Interaktif
### [➡️ Klik di sini untuk melihat Dasbor Interaktif di Tableau Public](https://public.tableau.com/app/profile/panji.adhi7559/viz/DashboardTableau_17588856859990/Dashboard1?publish=yes)

Dasbor ini memungkinkan pemangku kepentingan untuk menjelajahi data penjualan secara mandiri, memfilter berdasarkan wilayah, kategori produk, dan periode waktu untuk mendapatkan wawasan yang lebih dalam.

## 🎯 Tujuan Analisis
Berdasarkan laporan yang dianalisis, tujuan utama proyek ini adalah:
1.  Mengidentifikasi tren penjualan utama dari waktu ke waktu untuk memahami pola musiman.
2.  Menganalisis kinerja penjualan di berbagai segmen pelanggan dan kategori produk.
3.  Menentukan wilayah geografis dengan kontribusi penjualan dan laba tertinggi.
4.  Memberikan rekomendasi bisnis yang didasarkan pada data untuk meningkatkan efisiensi dan profitabilitas.

---

## 🛠️ Teknologi & Metode
- **Pembersihan & Manipulasi Data:** Python, Pandas
- **Analisis Data Eksplorasi (EDA):** Python, Matplotlib, Seaborn
- **Visualisasi & Dasbor Interaktif:** Tableau

---

## 🔑 Temuan Kunci
Analisis mendalam dari data mengungkapkan beberapa wawasan penting:
- **Kontributor Pendapatan Teratas:** Kategori **'Technology'** secara konsisten menjadi penyumbang pendapatan terbesar, diikuti oleh **'Furniture'**.
- **Isu Profitabilitas:** Meskipun menjadi kontributor pendapatan kedua terbesar, kategori **'Furniture'** menunjukkan margin keuntungan yang sangat rendah, bahkan negatif di beberapa sub-kategori.
- **Pola Musiman:** Penjualan menunjukkan tren peningkatan yang signifikan pada kuartal terakhir setiap tahun, terutama di bulan **November dan Desember**.
- **Segmen Pelanggan Paling Berharga:** Segmen **'Consumer'** menghasilkan volume penjualan tertinggi, namun segmen **'Corporate'** memiliki nilai rata-rata per transaksi yang lebih tinggi.

---

## 💡 Rekomendasi Bisnis
Berdasarkan temuan di atas, berikut adalah beberapa rekomendasi strategis:
1.  **Optimalkan Kategori Furniture:** Lakukan evaluasi ulang strategi penetapan harga dan manajemen biaya untuk sub-kategori 'Tables' dan 'Bookcases' guna meningkatkan profitabilitas.
2.  **Fokus pada Pelanggan Korporat:** Kembangkan program loyalitas atau penawaran bundel yang ditargetkan untuk segmen 'Corporate' untuk meningkatkan volume transaksi dari pelanggan bernilai tinggi ini.
3.  **Maksimalkan Puncak Penjualan Akhir Tahun:** Luncurkan kampanye pemasaran dan promosi yang agresif dimulai dari bulan Oktober untuk memanfaatkan momentum puncak penjualan musiman.

---

## 📂 Struktur Repositori
- `main.pdf`: Laporan teknis yang berisi proses pembersihan dan analisis data menggunakan Python.
- `Project Report.pdf`: Laporan bisnis formal yang merangkum temuan dan rekomendasi.
- `data_bersih.csv`: Dataset yang telah dibersihkan dan siap untuk divisualisasikan.
