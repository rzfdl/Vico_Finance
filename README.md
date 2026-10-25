Vico Finance - Aplikasi Manajemen Pembiayaan & Pelacakan Jatuh Tempo Mikro

> Aplikasi mobile berbasis Android untuk pengelolaan kas, pelacakan tanggal jatuh tempo, perhitungan bunga/denda otomatis, dan analisis kesehatan kredit nasabah pada usaha pembiayaan mikro konvensional.

---

## 📌 Tentang Proyek
**Vico Finance** adalah proyek pengembangan perangkat lunak yang dirancang untuk menyelesaikan permasalahan operasional pada usaha pembiayaan mikro konvensional perorangan. Selama ini, pencatatan kas masuk/keluar, pelacakan cicilan, dan rekapitulasi laba dilakukan secara manual. 

Aplikasi ini dibangun untuk *single user* (**Owner**) agar dapat mencatat transaksi secara cepat di lapangan (mendukung 2 titik posko layanan), menghitung otomatis denda keterlambatan harian, serta menyinkronkan data secara *real-time* ke *cloud database* sehingga laporan laba kotor dan bersih tersaji otomatis tanpa rekap manual di rumah.

Proyek ini dipersiapkan sebagai studi kasus **Tugas Akhir / Skripsi** di Program Studi Teknik Informatika, Universitas Indraprasta PGRI (UNINDRA).

---

## 🚀 Fitur Utama
* **Manajemen Nasabah & Foto Profil:** Penyimpanan data nasabah lengkap dengan foto visual untuk menghindari kesalahan identifikasi nama yang sama.
* **Indikator Lampu Status Nasabah:** Penanda visual instan (🟢 Hijau: Lancar, 🟡 Kuning: Sering Menunggak, 🔴 Merah: Macet/Tidak Aktif).
* **Multi-Pinjaman Aktif:** Satu nasabah dapat memiliki beberapa pinjaman aktif sekaligus (pilihan tenor bulanan & mingguan).
* **Perhitungan Otomatis:** Otomatisasi perhitungan bunga *flat* 10% per bulan dan akumulasi denda harian berdasarkan tanggal bayar riil.
* **Dashboard Analitik & Grafik:** Ringkasan keuangan harian, peringatan jatuh tempo hari ini, *Donut Chart* rasio kesehatan pinjaman, arus kas harian, dan tren keuntungan bulanan.
* **Arsitektur Cloud-Based:** Terhubung ke *Cloud Database* untuk sinkronisasi data *real-time*, dengan rancangan yang skalabel untuk pengembangan versi *Desktop* di masa depan.

---

## 🛠️ Tech Stack & Arsitektur
* **Frontend Mobile:** Flutter / Dart (atau Native Android / React Native)
* **Backend / Database:** Cloud Database (Firebase Firestore / Supabase)
* **Version Control:** Git & GitHub
* **Desain UI/UX:** Figma
* **Metodologi Pengembangan:** *Prototyping / Agile*

---

## 📂 Struktur Repositori
```text
vico-finance/
├── docs/               # Dokumentasi SRS dan diagram UML
├── designs/            # Mockup UI/UX & Wireframe (Figma asset)
├── src/                # Kode sumber aplikasi mobile
└── README.md           # Dokumentasi proyek
