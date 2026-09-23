# Python Data Analysis

Proyek portofolio Data Analyst — analisis data menggunakan Python (pandas), 
lanjutan dari proyek Excel Data Analysis untuk dataset yang sama (Superstore).

## Isi

### Minggu 6 — Python & Pandas Dasar
- Fondasi Python (variable, function, loop, list, dictionary)
- Pandas dasar: membaca data, indexing, filtering, summary functions
- **Validasi silang dengan Excel**: replikasi 3 Pivot Table (Sales by Region, 
  Profit by Category, Count by Segment) menggunakan `groupby()` — hasil dicocokkan 
  dengan Pivot Table di `excel-data-analysis` untuk memastikan konsistensi logika

### Minggu 7 — Pandas Lanjutan
- `pd.merge()` — menggabungkan data berdasarkan kolom kunci
- `pd.concat()` — menggabungkan beberapa DataFrame
- `pd.pivot_table()` — Pivot Table multi-dimensi (setara Excel Pivot Table)
- Penanganan missing values (`isna()`, `fillna()`)
- Groupby multi-kolom & multi-agregasi (`.agg()`)

### Minggu 8 — Data Visualization (Matplotlib & Seaborn)
- Subplot grid 2x2: Sales by Category per Region
- Boxplot: deteksi outlier Profit by Category
- Correlation heatmap: verifikasi statistik hubungan Discount-Profit
  (hasil: korelasi lemah -0,22 — mengoreksi asumsi di laporan Excel 
  yang awalnya menyiratkan hubungan kuat)
- Dashboard statis multi-chart

### Minggu 9 — EDA End-to-End (Online Retail Dataset)
Studi kasus analisis mandiri (bukan instruksi step-by-step) pada dataset baru 
(Online Retail Dataset, UK-based e-commerce, ~540rb baris) untuk menguji skill 
EDA di luar dataset Superstore yang sudah familiar.

**Rumusan masalah:**
1. Apa 5 negara yang melakukan transaksi dengan nominal terbesar?
2. Kapan waktu terjadinya transaksi paling ramai?
3. Apa saja barang/produk yang paling banyak dibeli (TOP 10)?
4. Apa saja barang/produk yang paling bayan direfund (TOP 5)?

**Proses:**
- Data Cleaning: pemisahan transaksi cancelled/refund (InvoiceNo berawalan "C") 
  dari transaksi sukses
- EDA Univariate: distribusi Quantity & UnitPrice, top negara, top produk, pola 
  transaksi per bulan & hari
- EDA Bivariate: revenue per negara, tren waktu vs nominal transaksi
- Artikel non-teknis merangkum temuan untuk audiens umum

**Insight tambahan (di luar rumusan masalah awal):** ditemukan pola transaksi 
cancelled/refund yang ditandai kode "C" pada InvoiceNo — dianalisis terpisah 
sebagai temuan bonus.

## Dataset
Sample Superstore Dataset (Kaggle) — sama dengan yang digunakan di 
[excel-data-analysis](https://github.com/MichaelChan07/excel-data-analysis), 
untuk memastikan hasil analisis konsisten lintas tool (Excel vs Python).

## Tools
Python, pandas, matplotlib, seaborn, Kaggle Notebook
