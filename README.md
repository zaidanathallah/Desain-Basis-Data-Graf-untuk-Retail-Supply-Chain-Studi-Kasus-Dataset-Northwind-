# 📊 Visualisasi Northwind Graph — Retail & Supply Chain

Proyek ini merupakan visualisasi database Northwind menggunakan **Neo4j Graph Database** sebagai studi kasus dalam domain retail / supply chain.  
Data ditransformasikan menjadi node & relasi agar pola koneksi antar entitas dapat dianalisis secara interaktif dan intuitif.

---

## 📝 Deskripsi Proyek

Northwind adalah dataset klasik di dunia retail yang mencakup entitas seperti **Customer**, **Order**, **Product**, **Supplier**, **Employee**, **Shipper**, **Category**, **Region**, dan **Territory**.

Dalam proyek ini, dataset tersebut:
- Diimpor ke Neo4j
- Diubah menjadi node & relasi melalui Cypher Query
- Divisualisasikan sebagai graph untuk berbagai analisis seperti:
  - Supplier dengan produk terbanyak  
  - Shipper paling aktif  
  - Kinerja per Sales / Employee  
  - Distribusi pelanggan per produk populer  

---

## 🛠️ Teknologi Digunakan

- 🧠 **Neo4j (Desktop / AuraDB)**  
- 📝 **Cypher Query Language (CQL)**  
- 🌐 **GitHub** sebagai repositori dan dokumentasi proyek  
- 🗃️ **Dataset Northwind** sebagai sumber data utama dari repositori resmi Neo4j

---

## 💡 Insight Utama

- Graph Database sangat cocok untuk retail & supply chain karena memungkinkan pemodelan hubungan langsung antar entitas.  
- Node dengan banyak relasi (high degree) menunjukkan peran strategis, seperti produk best-seller, shipper utama, dan customer utama.  
- Visualisasi *hub-and-spoke* memudahkan identifikasi entitas pusat (hub) seperti produk paling banyak dipesan atau shipper paling aktif.  
- Analisis semacam ini sulit dicapai dengan database relasional biasa atau SQL murni.

---

## 🚀 Cara Menjalankan Proyek

1. Clone repositori ini:
   ```bash
   git clone https://github.com/zaidanathallah/Desain-Basis-Data-Graf-untuk-Retail-Supply-Chain-Studi-Kasus-Dataset-Northwind-.git
Buka Neo4j Desktop atau AuraDB.

Buat project / instance baru.

Import dataset CSV ke folder import/ pada instance database.

Jalankan query DDL (constraint) → lalu DML (LOAD CSV & relasi).

Gunakan Graph View di Neo4j Browser / Bloom untuk visualisasi.

📚 Sumber Data
Dataset Northwind yang digunakan bersumber dari repositori resmi Neo4j:
👉 Neo4j Northwind Graph Examples

📝 Kesimpulan
Graph Database mempermudah pemahaman hubungan kompleks antar entitas dalam domain retail dan supply chain.
Dengan visualisasi graf, kita bisa mendapatkan insight langsung mengenai produk populer, koneksi supplier, pengiriman, hingga pelanggan utama — hal-hal yang sulit dilihat dari tabel relasional.

👤 Penulis
Nama: Zaidan Athallah

Bidang: Data Science

Proyek: Visualisasi Northwind Graph dengan Neo4j

Tahun: 2025

🪪 Lisensi
Dataset Northwind bersifat publik dan dapat digunakan untuk pendidikan.
Harap proyek ini digunakan untuk keperluan pembelajaran dan penelitian.