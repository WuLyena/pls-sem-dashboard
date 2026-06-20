Analisis Pengaruh Makroekonomi Terhadap Kinerja Pasar Modal dengan Aktivitas Pasar Sebagai Variabel Mediasi (Periode 2020–2023)

Repository ini berisi source code dan data untuk Dashboard Interaktif Tugas Akhir / Skripsi yang menyajikan visualisasi real-time dan hasil pengujian model struktural berbasis Variance-based Structural Equation Modeling (PLS-SEM).


📊 Akses Dashboard Utama
Web dashboard hasil analisis telah di-deploy dan dapat diakses secara publik melalui tautan berikut:
👉 [KLIK DI SINI UNTUK MEMBUKA DASHBOARD WEBSITE LU](https://WuLyena.github.io/pls-sem-dashboard/)

---

📑 Profil Peneliti
- Nama: Muhammad Nuril Syifa Elmar
- Fakultas: Ekonomi
- Institusi: Universitas MH. Thamrin
- Program Studi: S1 Manajemen (Konsentrasi Analisis Pasar Modal)
- Sertifikasi Profesi: Wakil Perantara Pedagang Efek (WPPE)

---

🔍 Ringkasan Model Penelitian
Penelitian ini menguji hubungan kausalitas antara kondisi makroekonomi global dan domestik terhadap indikator kinerja pasar saham di Bursa Efek Indonesia (BEI), dengan melibatkan dinamika aktivitas transaksi investor sebagai variabel pemediasi.

- Variabel Eksogen (X) - Kondisi Makroekonomi: Inflasi YoY (%), BI 7-Day Reverse Repo Rate (BI7DRR), Nilai Tukar Rupiah (Kurs IDR).
- Variabel Mediasi (Z) - Aktivitas Pasar: Volume Transaksi (Juta Lembar), Frekuensi Perdagangan (Ribu Transaksi), Jumlah Investor (Single Investor Identification / SID).
- Variabel Endogen (Y) - Kinerja Pasar Modal: Indeks Harga Saham Gabungan (IHSG), Kapitalisasi Pasar (Triliun IDR).

---

📉 Ringkasan Hasil Pengujian (SmartPLS 4)
Model ini dievaluasi menggunakan data deret waktu (time-series) bulanan selama 48 bulan (Januari 2020 – Desember 2023). Hasil algoritma PLS menunjukkan:
1. R-Square Kinerja Pasar (Y): 0.863 (86.3%), menunjukkan kemampuan prediktif model struktural yang sangat kuat dalam menjelaskan variasi IHSG dan Kapitalisasi Pasar.
2. Efek Mediasi (X ke Z ke Y): Signifikan dengan nilai P-Value 0.000 dan T-Statistic 5.342, membuktikan peran Aktivitas Pasar sebagai Complementary Partial Mediation.
3. Validitas dan Reliabilitas: Seluruh konstruk memenuhi syarat Convergent Validity (AVE > 0.50) dan Construct Reliability (Composite Reliability > 0.70).

---

🛠️ Teknologi yang Digunakan
- Analisis Statistik: SmartPLS 4 (PLS-SEM Algorithm dan Bootstrapping)
- Frontend Dashboard: HTML5, CSS3 (Custom Academic Typography dan Print Layout), JavaScript (ES6)
- Library Grafik: Chart.js 4.4.1 (Real-time Dual Y-Axis Rendering)

---
Dokumen digital ini dibuat sebagai transparansi metodologi ilmiah dan portofolio data analitik finansial.
