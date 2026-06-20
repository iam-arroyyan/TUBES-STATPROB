# Analisis Statistik & Probabilitas: Tren Bencana Alam (2018-2022) 🌋📊

Repositori ini berisi proyek Tugas Besar (TUBES) untuk mata kuliah **Statistik dan Probabilitas**. Proyek ini berfokus pada pengolahan, analisis deskriptif, dan visualisasi data terkait frekuensi jumlah bencana alam yang terjadi selama periode lima tahun (2018 hingga 2022).

Melalui proyek ini, data mentah diekstraksi dan dianalisis untuk menemukan *insight*, tren tahunan, serta distribusi probabilitas dari kejadian bencana.

## 🎯 Tujuan Analisis

* **Statistika Deskriptif:** Menghitung nilai pemusatan data (mean, median, modus) dan penyebaran data (variansi, standar deviasi) dari kejadian bencana alam setiap tahun.
* **Analisis Tren:** Membandingkan fluktuasi jumlah bencana alam dari tahun ke tahun (2018 - 2022) untuk melihat apakah ada peningkatan atau penurunan yang signifikan.
* **Visualisasi Data:** Menyajikan kumpulan data berbentuk teks menjadi grafik visual yang mudah dipahami.
* **Probabilitas:** (Jika ada) Menerapkan konsep probabilitas dan distribusi kejadian berdasarkan data historis.

## 🛠️ Tech Stack & Alat

Proyek ini dibangun sepenuhnya menggunakan ekosistem Data Science Python:

![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-000000?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-000000?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-000000?style=for-the-badge) 

*(Catatan: Digunakan juga library standar seperti NumPy dan Matplotlib/Seaborn untuk visualisasi data).*

## 📂 Struktur Dataset & Repositori

Data historis dipisah per tahun ke dalam file berformat `.txt` dan diolah secara terpusat di dalam Jupyter Notebook.

```text
tubes-statprob/
├── Jumlah Bencana Alam - 2018.txt   # Dataset mentah kejadian bencana tahun 2018
├── Jumlah Bencana Alam - 2019.txt   # Dataset mentah kejadian bencana tahun 2019
├── Jumlah Bencana Alam - 2020.txt   # Dataset mentah kejadian bencana tahun 2020
├── Jumlah Bencana Alam - 2021.txt   # Dataset mentah kejadian bencana tahun 2021
├── Jumlah Bencana Alam - 2022.txt   # Dataset mentah kejadian bencana tahun 2022
└── TUBES.ipynb                      # Source code utama (Jupyter Notebook) berisi analisis
