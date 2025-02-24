Business Intelligence Analysis - PT Sejahtera Bersama

📌 Deskripsi Singkat Proyek

Repository ini berisi dataset dan skrip untuk analisis Business Intelligence (BI) terkait penjualan di PT Sejahtera Bersama. Tujuan utama proyek ini adalah untuk membangun tabel master yang dapat digunakan dalam analisis lebih lanjut, termasuk pembuatan dashboard dan laporan insight bisnis.

Data yang dikumpulkan mencakup informasi pelanggan, produk, kategori produk, pesanan, dan penjualan. Dengan menggunakan data ini, kita dapat memahami tren penjualan, preferensi pelanggan, serta mengoptimalkan strategi bisnis berdasarkan analisis yang dilakukan.

📂 Struktur Data

Repository ini berisi beberapa file penting:

Customers.xlsx - Berisi data pelanggan, termasuk email dan kota asal pelanggan.

Orders.xlsx - Berisi data pesanan pelanggan, termasuk tanggal pesanan dan jumlah produk yang dipesan.

Products.xlsx - Berisi daftar produk yang dijual, termasuk nama produk dan harga.

ProductCategory.xlsx - Berisi kategori produk.

Master_Table.csv - Tabel master yang sudah digabung dari berbagai sumber data untuk memudahkan analisis.

Rakamin.ipynb - Notebook Jupyter yang berisi skrip Python untuk mengolah dan menganalisis data menggunakan pandas dan numpy.

🚀 Instruksi Penggunaan

1. Persiapan Data

Download semua file dalam repository ini.

Pastikan semua dataset dalam format yang sesuai (CSV/XLSX).

2. Eksekusi Skrip Python

Jalankan Rakamin.ipynb untuk:

Menggabungkan beberapa dataset menjadi satu tabel master.

Melakukan pembersihan data (handling missing values, format adjustment, dsb.).

Menghasilkan dataset final untuk analisis lebih lanjut.

3. Query SQL (Jika Menggunakan BigQuery)

Jika menggunakan BigQuery, dataset bisa di-load ke dalamnya dan diolah menggunakan SQL. Contoh query:

SELECT category_name, SUM(total_sales) AS total_revenue
FROM Master_Table
GROUP BY category_name
ORDER BY total_revenue DESC;

4. Visualisasi Data

Gunakan tools BI seperti Looker Studio, Power BI, atau Tableau untuk membuat dashboard interaktif berdasarkan dataset yang telah diproses.

🛠 Teknologi yang Digunakan

Python: pandas, numpy, matplotlib untuk analisis data.

BigQuery: Untuk pengolahan dan analisis data dalam skala besar.

Looker Studio / Power BI / Tableau: Untuk visualisasi data dan pembuatan dashboard.

🎯 Hasil yang Diharapkan

Dashboard yang memberikan insight mengenai total penjualan, jumlah pesanan per kategori, serta distribusi pelanggan berdasarkan kota.

Laporan analisis tren penjualan dan rekomendasi strategi bisnis berdasarkan data yang tersedia.

Query SQL yang dapat digunakan untuk eksplorasi data lebih lanjut.

📢 Kontribusi: Jika ingin menambahkan atau memperbaiki dataset, silakan buat pull request atau ajukan issue di repository ini!

✨ Happy Analyzing! 🚀
