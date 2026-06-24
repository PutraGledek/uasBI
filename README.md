
# Dashboard BI - Analisis Penjualan Shopee dengan AHP-TOPSIS

Sistem Business Intelligence dan Sistem Pendukung Keputusan (SPK) untuk analisis penjualan retail di Shopee dengan metode AHP-TOPSIS, analisis perilaku konsumen, dan Market Basket Analysis.

## Fitur Utama

### 📊 Dashboard BI
- **4 Chart Visualisasi**: Tren pendapatan, top pelanggan, distribusi wilayah, dan pareto produk
- **KPI Cards**: Total omzet, transaksi, AOV, dan top area
- **Filter Interaktif**: Bulan, rentang waktu, dan lokasi
- **4 Tema Tampilan**: Light, Dark, Brown, Lime

### 🎯 Sistem Pendukung Keputusan (AHP-TOPSIS)
- Peringkat wilayah untuk ekspansi berdasarkan 4 kriteria
- Rekomendasi prioritas wilayah

### 👥 Analisis Perilaku Konsumen
- **Customer Segmentation**: 3 klaster (High, Medium, Low Value)
- **Market Basket Analysis**: Rekomendasi bundling produk

## Struktur Proyek

```
uasBI/
├── index.html                          # Dashboard utama
├── shopee_analysis.json                # Dataset transaksi
├── TECHNICAL_DOCUMENTATION.txt         # Dokumentasi teknis lengkap
└── README.md                           # File ini
```

## Cara Penggunaan

1. **Buka Dashboard**: Klik dua kali `index.html` atau buka di browser
2. **Interaksi**: Gunakan filter untuk melihat data sesuai kebutuhan
3. **Ganti Tema**: Pilih tema dari dropdown di panel kontrol

## Dataset

Dataset berisi 403 transaksi dengan atribut:
- No. Pesanan
- Waktu Pesanan Dibuat
- Nama Produk
- Jumlah
- Total Pembayaran
- Username Pembeli
- Kota/Kabupaten

## Dokumentasi

Lihat **TECHNICAL_DOCUMENTATION.txt** untuk dokumentasi teknis lengkap termasuk:
- Arsitektur sistem
- Implementasi AHP-TOPSIS
- Metode clustering
- Business questions dan analisis
- Panduan penggunaan

## Teknologi

- **HTML5** - Struktur halaman
- **Tailwind CSS 3** - Styling
- **Chart.js 4** - Visualisasi grafik
- **Vanilla JavaScript** - Logika aplikasi
- **JSON** - Format data

## Lisensi

Proyek untuk keperluan akademis.
