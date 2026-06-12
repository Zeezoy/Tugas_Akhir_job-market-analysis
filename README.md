# Job Market Analysis

## Deskripsi Proyek

Proyek ini bertujuan untuk melakukan analisis data lowongan pekerjaan (Job Market Analysis) menggunakan Python dan teknik Exploratory Data Analysis (EDA).

Analisis dilakukan untuk mengetahui:

- Distribusi lowongan pekerjaan berdasarkan lokasi
- Ketersediaan informasi gaji pada lowongan
- Rata-rata gaji maksimum pada tiap lokasi
- Tren jumlah posting lowongan pekerjaan berdasarkan tanggal publikasi

---

## Dataset

Dataset yang digunakan:

- JOB_RAW.csv (data mentah)
- jobs_clean_1.csv (data hasil pembersihan)

---

## Tools dan Library

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Tahapan Pengolahan Data

1. Import dataset
2. Data Cleaning
   - Menghapus data kosong
   - Menyesuaikan format data
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Visualisasi Data
6. Interpretasi Hasil

---

## Hasil Analisis

### 1. Distribusi Lowongan Berdasarkan Lokasi

Hasil menunjukkan bahwa Jakarta Selatan memiliki jumlah lowongan terbanyak dibandingkan lokasi lainnya.

Temuan:
- Jakarta Selatan: 13 lowongan
- Jakarta Timur: 2 lowongan
- Denpasar, Jakarta Pusat, Surabaya, Bandung, dan Prov. DKI Jakarta masing-masing 1 lowongan

Kesimpulan:
Pasar kerja pada dataset didominasi oleh wilayah Jakarta Selatan.

---

### 2. Ketersediaan Informasi Gaji

Hasil analisis menunjukkan:

- 35% lowongan menyediakan informasi gaji
- 65% lowongan tidak menyediakan informasi gaji

Kesimpulan:
Sebagian besar perusahaan tidak mencantumkan informasi gaji pada iklan lowongan pekerjaan.

---

### 3. Rata-rata Gaji Maksimum per Lokasi

Lokasi dengan rata-rata gaji maksimum tertinggi:

| Lokasi | Rata-rata Gaji Maksimum |
|---------|---------|
| Jakarta Pusat | Rp12.500.000 |
| Prov. DKI Jakarta | Rp7.500.000 |
| Surabaya | Rp6.500.000 |
| Jakarta Selatan | Rp5.700.000 |
| Jakarta Timur | Rp5.000.000 |
| Denpasar | Rp4.100.000 |
| Bandung | Rp2.000.000 |

Kesimpulan:
Jakarta Pusat menawarkan rata-rata gaji maksimum tertinggi pada dataset yang dianalisis.

---

### 4. Tren Posting Lowongan

Jumlah lowongan yang diposting:

- 03 Maret 2026 : 6 lowongan
- 04 Maret 2026 : 14 lowongan

Kesimpulan:
Terjadi peningkatan jumlah lowongan yang dipublikasikan pada periode pengamatan.

---

## Visualisasi

- chart_distribusi_lokasi.png
- chart_ketersediaan_gaji.png
- chart_rata_rata_gaji.png
- chart_tren_posting.png

---

## Struktur Repository

```
Tugas_Akhir_job-market-analysis/
│
├── JOB_RAW.csv
├── jobs_clean_1.csv
├── TUGAS_AKHIR_FEVOURA_AGNESIA_TATONTOS.ipynb
├── chart_distribusi_lokasi.png
├── chart_ketersediaan_gaji.png
├── chart_rata_rata_gaji.png
├── chart_tren_posting.png
└── README.md
```

---

## Kesimpulan Umum

Berdasarkan analisis yang dilakukan:

1. Jakarta Selatan merupakan lokasi dengan jumlah lowongan terbanyak.
2. Mayoritas lowongan tidak mencantumkan informasi gaji.
3. Jakarta Pusat memiliki rata-rata gaji maksimum tertinggi.
4. Terdapat peningkatan jumlah posting lowongan pada periode pengamatan.

Hasil ini menunjukkan bahwa distribusi lowongan kerja dan informasi kompensasi masih terkonsentrasi pada wilayah tertentu serta tidak seluruh perusahaan memberikan transparansi informasi gaji.
