# Luaran 2022 - Indikator 3: Masa Tunggu Kerja Pertama

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

## Ringkasan data 2022
- File sumber: `data-responden2022.xlsx`
- Total responden non-kosong: **44**
- Distribusi status (`F8`):
  - `1` Bekerja: **16**
  - `2` Belum memungkinkan bekerja: **1**
  - `5` Tidak kerja tetapi sedang mencari kerja: **27**

## Hasil utama (filter: `F8 = 1`)
- Jumlah data masa tunggu valid (`F502`): **16**
- Rata-rata masa tunggu: **17,56 bulan**
- Median masa tunggu: **1,50 bulan**
- Proporsi masa tunggu `<= 6 bulan`: **11/16 (68,75%)**
- Proporsi masa tunggu `> 6 bulan`: **5/16 (31,25%)**

Sebaran kategori:
- `0 bulan`: 5 (31,25%)
- `1-3 bulan`: 5 (31,25%)
- `4-6 bulan`: 1 (6,25%)
- `7-12 bulan`: 1 (6,25%)
- `13-24 bulan`: 0 (0,00%)
- `>24 bulan`: 4 (25,00%)

## Hasil pembanding (opsional, jika bekerja + wirausaha)
Jika memakai `F8 in (1,3)`:
- n = **16**
- Rata-rata = **17,56 bulan**
- Median = **1,50 bulan**
- `<= 6 bulan` = **11/16 (68,75%)**

## Catatan kualitas data (penting untuk narasi borang)
- Ditemukan 4 data `F502 > 24` bulan pada lulusan tahun 2022 (48, 48, 113, 48 bulan), yang berpotensi memengaruhi nilai rata-rata secara signifikan.
- Karena terdapat outlier, untuk borang disarankan menampilkan indikator robust (median dan proporsi `<= 6 bulan`) bersama nilai rata-rata.

Data yang perlu verifikasi:
- NIM `1801650008` - HANNA OCTAVIANY PAMULANINGRUM - 48 bulan
- NIM `1801552056` - ARDANI YANUAR IKHSAN - 48 bulan
- NIM `1801552038` - ABDUL SUKRONI - 113 bulan
- NIM `1801552007` - NICODIMUS BAGUS ADI KUSUMA DAHNI SUALANG - 48 bulan

## Narasi singkat siap pakai (draft borang)
Pada data tracer alumni SI tahun 2022, dari 16 alumni berstatus bekerja, sebesar 68,75% memperoleh pekerjaan dalam waktu paling lama 6 bulan sejak memperoleh nomor ijazah, dengan median masa tunggu 1,5 bulan. Nilai rata-rata masa tunggu relatif tinggi akibat adanya beberapa data ekstrem di atas 24 bulan. Oleh karena itu, interpretasi kinerja penyerapan kerja disarankan menekankan median dan proporsi lulusan dengan masa tunggu cepat.
