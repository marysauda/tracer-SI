# Luaran 2021 - Indikator 3: Masa Tunggu Kerja Pertama

## Rekomendasi ekstensi file
Ekstensi yang paling sesuai untuk kebutuhan ini adalah **`.md`** karena:
- Bisa memuat **angka + analisis naratif** dalam satu file.
- Mudah dikonversi ke `.docx`/PDF saat penyusunan borang.
- Tetap ringan dan mudah dilacak revisinya.

## Definisi indikator yang dipakai
- `F8` = status alumni saat ini.
  - `1`: Bekerja (full time/part time)
  - `3`: Wiraswasta
- `F502` = jumlah bulan sampai mendapatkan pekerjaan (0 bulan = sebelum lulus).

Untuk indikator **masa tunggu kerja pertama**, perhitungan utama menggunakan alumni dengan `F8 = 1` (bekerja).

## Ringkasan data 2021
- File sumber: `data-responden2021.xlsx`
- Total responden non-kosong: **85**
- Distribusi status (`F8`) pada data:
  - Kode `0` (non-standar): **44**
  - `1` Bekerja: **24**
  - `2` Belum memungkinkan bekerja: **17**

## Hasil utama (filter: `F8 = 1`)
- Jumlah data masa tunggu valid (`F502`): **24**
- Rata-rata masa tunggu: **1,62 bulan**
- Median masa tunggu: **0 bulan**
- Proporsi masa tunggu `<= 6 bulan`: **24/24 (100,00%)**
- Proporsi masa tunggu `> 6 bulan`: **0/24 (0,00%)**

Sebaran kategori:
- `0 bulan`: 13 (54,17%)
- `1-3 bulan`: 6 (25,00%)
- `4-6 bulan`: 5 (20,83%)
- `7-12 bulan`: 0 (0,00%)
- `13-24 bulan`: 0 (0,00%)
- `>24 bulan`: 0 (0,00%)

## Hasil pembanding (opsional, jika bekerja + wirausaha)
Jika memakai `F8 in (1,3)`:
- n = **24**
- Rata-rata = **1,62 bulan**
- Median = **0 bulan**
- `<= 6 bulan` = **24/24 (100,00%)**

## Catatan kualitas data (penting untuk narasi borang)
- Tidak ditemukan outlier `F502 > 24` bulan pada kelompok bekerja (`F8 = 1`).
- Ditemukan kode status `F8 = 0` pada 44 responden (tidak sesuai skema standar 1-5), sehingga perlu klarifikasi definisi kode saat menyusun narasi final.

## Narasi singkat siap pakai (draft borang)
Pada data tracer alumni SI tahun 2021, dari 24 alumni berstatus bekerja, seluruhnya memperoleh pekerjaan dalam waktu paling lama 6 bulan sejak memperoleh nomor ijazah, dengan median masa tunggu 0 bulan. Hasil ini menunjukkan transisi lulusan ke dunia kerja pada kelompok bekerja tergolong sangat baik. Pada saat penyusunan laporan akhir, perlu diberikan catatan metodologis terkait keberadaan kode status non-standar (`F8 = 0`) agar interpretasi distribusi status alumni tetap akurat.
