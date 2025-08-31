# Buy & Hold Strategy: Apple vs S&P 500

Mini quant project untuk membandingkan strategi **Buy and Hold** pada saham Apple (`AAPL`) dengan indeks pasar S&P 500 (proxy ETF: `SPY`).  

## 📌 Project Description
Tujuan project ini adalah untuk melihat bagaimana performa investasi jangka panjang jika sejak tahun 2015 kita hanya membeli **AAPL** lalu menahannya (buy & hold), dibandingkan dengan jika kita berinvestasi di pasar luas (S&P 500).

Data harga saham diambil otomatis dari **Yahoo Finance** menggunakan library `yfinance`.

## ⚙️ Requirements
Pastikan sudah install Python 3.10+ dan library berikut:
```bash
pip install yfinance pandas matplotlib notebook

▶️ How to Run

Clone repo ini

git clone https://github.com/username/repo-name.git
cd repo-name


Jalankan Jupyter Notebook

jupyter notebook


Buka file buy_and_hold.ipynb

Run semua cell untuk generate grafik & hasil analisis.

📊 Output

Grafik perkembangan nilai investasi dari 2015–sekarang

Total return (%) masing-masing aset (AAPL vs SPY)

File hasil:

equity_curve.png → grafik Buy & Hold

returns_summary.csv → ringkasan return

Contoh grafik:
(contoh gambar bisa kamu upload manual ke repo, misalnya screenshot dari notebook)

🚀 Next Steps

Tambahkan saham lain untuk perbandingan (misalnya TSLA, MSFT, AMZN)

Coba strategi lain selain Buy & Hold (contoh: moving average crossover)

Lanjut belajar backtesting dengan library seperti backtrader atau zipline

✨ Notes

Project ini adalah latihan pertama untuk pemula yang ingin belajar quantitative finance menggunakan Python.
