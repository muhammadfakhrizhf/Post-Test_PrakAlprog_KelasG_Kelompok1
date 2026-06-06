# Post-Test Prak Alprog Kelas G Kelompok 1

Repository ini berisi analisis data mengenai **Fixed Call Report** yang bertujuan untuk memahami pola panggilan layanan kesehatan, tren komplain pengguna, hubungan antara volume konsultasi dokter dengan total panggilan, serta distribusi data komplain bulanan secara statistik.

Di sini dilakukan proses pengolahan dan analisis data mulai dari tahap persiapan dataset, eksplorasi data, visualisasi, hingga penyajian hasil analisis dalam bentuk grafik agar informasi lebih mudah dipahami.

## Isi Repository

Repository ini berisi beberapa komponen utama:

* **Dataset** — File CSV data call report (`Kelas_G_Fixed_Call_Report.csv`)
* **Source Code** — Notebook analisis data (`Kelas_G_Analisis_Call_Report.ipynb`)
* **Hasil Visualisasi Grafik** — Output grafik dari 4 kategori analisis

## Kategori Analisis

### Kategori A — Agregasi
Menghitung total keseluruhan jumlah panggilan (*Total Number of Calls*) yang dikelompokkan berdasarkan tahun. Divisualisasikan menggunakan **Bar Chart** untuk membandingkan volume panggilan antar tahun secara langsung.

### Kategori B — Tren / Filter
Menampilkan fluktuasi bulanan jumlah komplain (*Number of Total Complaints*) khusus pada tahun 2024. Divisualisasikan menggunakan **Line Chart** untuk melihat pola naik-turun komplain sepanjang tahun.

### Kategori C — Korelasi
Menganalisis hubungan antara jumlah konsultasi dokter (*Total Number of Doctors Consultancy*) dengan total volume panggilan masuk. Divisualisasikan menggunakan **Scatter Plot** dilengkapi garis regresi linear dan nilai koefisien korelasi (r).

### Kategori D — Distribusi
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
