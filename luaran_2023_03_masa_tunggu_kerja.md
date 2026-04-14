# Luaran 2023 - Indikator 3: Masa Tunggu Kerja Pertama

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

## Ringkasan data 2023
- File sumber: `data-responden2023.xlsx`
- Total responden non-kosong: **80**
- Distribusi status (`F8`):
  - `1` Bekerja: **80**

## Hasil utama (filter: `F8 = 1`)
- Jumlah data masa tunggu valid (`F502`): **80**
- Rata-rata masa tunggu: **3,01 bulan**
- Median masa tunggu: **0 bulan**
- Proporsi masa tunggu `<= 6 bulan`: **73/80 (91,25%)**
- Proporsi masa tunggu `> 6 bulan`: **7/80 (8,75%)**

Sebaran kategori:
- `0 bulan`: 67 (83,75%)
- `1-3 bulan`: 4 (5,00%)
- `4-6 bulan`: 2 (2,50%)
- `7-12 bulan`: 2 (2,50%)
- `13-24 bulan`: 1 (1,25%)
- `>24 bulan`: 4 (5,00%)

## Hasil pembanding (opsional, jika bekerja + wirausaha)
Jika memakai `F8 in (1,3)`:
- n = **80**
- Rata-rata = **3,01 bulan**
- Median = **0 bulan**
- `<= 6 bulan` = **73/80 (91,25%)**

## Catatan kualitas data (penting untuk narasi borang)
- Ditemukan 4 data `F502 > 24` bulan pada lulusan tahun 2023 (48, 35, 48, 48 bulan).
- Outlier ini tidak mengubah median, tetapi dapat menaikkan rata-rata; karenanya disarankan menyajikan median dan proporsi `<= 6 bulan` sebagai indikator utama.

Data yang perlu verifikasi:
- NIM `1801552043` - ANGELICA YULIANY PRASETYO - 48 bulan
- NIM `1801552040` - LAILATUL IRVANA - 35 bulan
- NIM `1701550098` - REYHAN ALTAIR PRADANA - 48 bulan
- NIM `1901550078` - HARRIS SURYA ARDIANSYAH - 48 bulan

## Narasi singkat siap pakai (draft borang)
Pada data tracer alumni SI tahun 2023, 91,25% alumni berstatus bekerja memperoleh pekerjaan dalam waktu paling lama 6 bulan sejak memperoleh nomor ijazah, dengan median masa tunggu 0 bulan. Temuan ini menunjukkan penyerapan lulusan ke dunia kerja tergolong cepat. Meskipun terdapat beberapa data ekstrem di atas 24 bulan, indikator robust (median dan proporsi `<= 6 bulan`) tetap menunjukkan kinerja luaran yang baik.
