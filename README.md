# TA-03 Pemodelan dan Simulasi – Monte Carlo Risiko Harga Saham
Muhammad Fadillah Ramadhan · NIM 301240051 · Topik (digit NIM 1): Forecasting Harga Saham

## Isi
- `TA03_ModSim.ipynb` – notebook (load data Kaggle → cleaning → μ, σ → simulasi ≥5.000 jalur → analisis risiko)
- `index.html` – aplikasi web (upload CSV Kaggle, simulasi berjalan di browser)
- `vercel.json` – konfigurasi Vercel
- `data/` – taruh CSV Kaggle di sini (mis. `TSLA.csv`)

## Menjalankan notebook
1. Unduh dataset saham (Apple / Tesla / BCA) dari Kaggle, simpan ke `data/`.
2. Ubah `CSV_PATH` di sel konfigurasi, lalu Run All.

## Deploy ke Vercel
**Lewat GitHub (disarankan):** push folder ini ke repo → vercel.com → *Add New Project* → import repo → Framework Preset: *Other* → Deploy.
**Lewat CLI:** `npm i -g vercel` lalu `vercel --prod` di folder ini.
Tidak perlu build command maupun output directory (situs statis).
