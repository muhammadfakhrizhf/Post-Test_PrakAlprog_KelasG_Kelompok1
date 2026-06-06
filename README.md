# Post-Test Prak Alprog Kelas G Kelompok 1

Repository ini berisi hasil analisis data **Fixed Call Report** milik layanan kesehatan berbasis panggilan telepon, mencakup rekaman bulanan dari tahun 2016 hingga 2025 dengan total 107 entri. Dataset terdiri dari 8 kolom, yaitu tahun (*Year*), bulan (*Month*), serta enam kategori jenis panggilan: total seluruh panggilan, konsultasi dokter, informasi kesehatan, informasi ambulans, laporan komplain, dan panggilan mengenai layanan.

Analisis yang dilakukan dalam repository ini mencakup empat pendekatan, yaitu agregasi total panggilan per tahun, pemantauan tren komplain bulanan pada tahun 2024, eksplorasi korelasi antara konsultasi dokter dengan volume panggilan masuk, serta identifikasi bulan-bulan pencilan (*outlier*) berdasarkan jumlah komplain. Seluruh proses dikerjakan menggunakan Python dengan library **pandas**, **matplotlib**, dan **seaborn**, dan disajikan dalam format Jupyter Notebook.

## Isi Repository

* **Dataset** — File CSV data call report (`Kelas_G_Fixed_Call_Report.csv`)
* **Source Code** — Notebook analisis data (`Analisis_Fixed_Call_Report_KelasG_Kelompok1.ipynb`)
* **Hasil Visualisasi Grafik** — (`Infografis_KelasG_Kelompok1.jpeg`)

## Kategori Analisis

### Kategori A (Agregasi)
Menghitung total keseluruhan jumlah panggilan (*Total Number of Calls*) yang dikelompokkan berdasarkan tahun. Divisualisasikan menggunakan **Bar Chart** untuk membandingkan volume panggilan antar tahun secara langsung.

### Kategori B (Tren / Filter)
Menampilkan fluktuasi bulanan jumlah komplain (*Number of Total Complaints*) khusus pada tahun 2024. Divisualisasikan menggunakan **Line Chart** untuk melihat pola naik-turun komplain sepanjang tahun.

### Kategori C (Korelasi)
Menganalisis hubungan antara jumlah konsultasi dokter (*Total Number of Doctors Consultancy*) dengan total volume panggilan masuk. Divisualisasikan menggunakan **Scatter Plot** dilengkapi garis regresi linear dan nilai koefisien korelasi (r).

### Kategori D (Distribusi)
Mengidentifikasi keberadaan bulan-bulan pencilan (*outlier* atas) dalam jumlah komplain bulanan menggunakan metode IQR. Divisualisasikan menggunakan **Boxplot** dengan penanda upper fence.

## Library yang Digunakan

```python
pandas
matplotlib
seaborn
numpy
```

## Pembagian Tugas

| No | Nama | NIM | Tugas |
|----|------|-----|-------|
| 1 | Callista Aviana Randabunga | 21060125140173 | Membantu pengodean kategori A dan analisis kategori A |
| 2 | Ahmad Hafizuddin Saragih | 21060125140162 | Membantu pengodean kategori B dan analisis kategori B |
| 3 | Kahfi Hanzah | 21060125140202 | Membantu pengodean kategori C dan analisis kategori C |
| 4 | Muhammad Fakhri Zhafran | 21060125140205 | Membuat pengodean gabungan seluruh kategori dan analisis kategori D |
| 5 | Adhyaksa Setia Negara | 21060125140182 | Pendesain utama infografis dari Post-Test |
