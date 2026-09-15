# Praktikum-STA2561-M0501261075

Repositori ini berisi mengenai **Data Wrangling dan Data Visualization**

## Struktur Repositori

| File | Deskripsi |
|---|---|
| `Kelompok6.qmd` | Dokumen Quarto (sumber) berisi seluruh kode R dan narasi analisis |
| `Kelompok6.html` | Hasil render laporan dalam format HTML |
| `nilai_bersih.csv` | Data nilai mahasiswa hasil pembersihan (missing value, imputasi, duplikat) |
| `penjualan_long.csv` | Data penjualan hasil reshaping ke format long |
| `profil_filter.csv` | Data profil hasil subset dan sorting multikriteria |
| `co2_uptake_visualisasi.png` | Visualisasi hasil eksplorasi data CO2 uptake |

## Ringkasan Isi Laporan

1. **Data Wrangling Pembersihan Data Mahasiswa**
   - Identifikasi dan transformasi nilai hilang (termasuk simbol tanda hubung `-` menjadi `NA`)
   - Imputasi nilai `NA` menggunakan nilai mean
   - Kategorisasi kolom umur
   - Penghapusan data duplikat
   - Penyimpanan data bersih ke `nilai_bersih.csv`

2. **Subset dan Sort Multicriteria**
   - Subset data berdasarkan kriteria tertentu
   - Pengurutan data berdasarkan beberapa kolom (gender descending, kolom lain ascending)
   - Penyimpanan hasil ke `profil_filter.csv`

3. **Penggabungan dan Reshaping Data**
   - Merge antar dataframe
   - Reshaping data ke format long
   - Penyimpanan hasil ke `penjualan_long.csv`

4. **Eksplorasi Visual**
   - Scatterplot hubungan CO2 dengan variabel lain
   - Visualisasi dalam layout canvas 2x2
   - Perbandingan `qplot()` dan `ggplot2`
   - Pengembangan visualisasi dengan `ggplot2`
   - Penyimpanan gambar ke `co2_uptake_visualisasi.png`

