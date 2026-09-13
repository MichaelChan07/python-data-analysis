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

## Dataset
Sample Superstore Dataset (Kaggle) — sama dengan yang digunakan di 
[excel-data-analysis](https://github.com/MichaelChan07/excel-data-analysis), 
untuk memastikan hasil analisis konsisten lintas tool (Excel vs Python).

## Tools
Python, pandas, matplotlib, seaborn, Kaggle Notebook
