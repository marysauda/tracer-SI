# Luaran 2024 - Indikator 3: Masa Tunggu Kerja Pertama

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

## Ringkasan data 2024
- File sumber: `data-responden2024.xlsx`
- Total responden non-kosong: **45**
- Distribusi status (`F8`):
  - `1` Bekerja: **32**
  - `2` Belum memungkinkan bekerja: **1**
  - `3` Wiraswasta: **2**
  - `5` Tidak kerja tetapi sedang mencari kerja: **10**

## Hasil utama (filter: `F8 = 1`)
- Jumlah data masa tunggu valid (`F502`): **32**
- Rata-rata masa tunggu: **6,34 bulan**
- Median masa tunggu: **0 bulan**
- Proporsi masa tunggu `<= 6 bulan`: **26/32 (81,25%)**
- Proporsi masa tunggu `> 6 bulan`: **6/32 (18,75%)**

Sebaran kategori:
- `0 bulan`: 21 (65,62%)
- `1-3 bulan`: 3 (9,38%)
- `4-6 bulan`: 2 (6,25%)
- `7-12 bulan`: 2 (6,25%)
- `13-24 bulan`: 1 (3,12%)
- `>24 bulan`: 3 (9,38%)

## Hasil pembanding (opsional, jika bekerja + wirausaha)
Jika memakai `F8 in (1,3)`:
- n = **34**
- Rata-rata = **6,21 bulan**
- Median = **0 bulan**
- `<= 6 bulan` = **28/34 (82,35%)**

## Catatan kualitas data (penting untuk narasi borang)
- Ditemukan 3 data `F502 > 24` bulan pada lulusan tahun 2024 (35, 48, 60 bulan), yang berpotensi perlu verifikasi entri.
- Data outlier tersebut dapat menaikkan nilai rata-rata; karena itu, untuk borang disarankan menampilkan juga indikator robust:
  - median
  - proporsi `<= 6 bulan`

Data yang perlu verifikasi:
- NIM `2001550038` - EMA TITANIA KHARISMA - 35 bulan
- NIM `2001550018` - ERVIANA SETIANI - 48 bulan
- NIM `2001550006` - JIMMY PRATAMA SETIADI - 60 bulan

## Narasi singkat siap pakai (draft borang)
Pada data tracer alumni SI tahun 2024, dari 32 alumni berstatus bekerja, mayoritas memperoleh pekerjaan dalam waktu relatif cepat. Sebanyak 81,25% alumni mendapatkan pekerjaan dalam waktu paling lama 6 bulan sejak memperoleh nomor ijazah, dengan median masa tunggu 0 bulan. Temuan ini menunjukkan transisi lulusan ke dunia kerja tergolong baik. Terdapat sejumlah kecil data outlier masa tunggu di atas 24 bulan yang perlu verifikasi administratif agar interpretasi rerata lebih presisi.
