# Scraping Data dan Dashboard

Proyek ini bertujuan untuk melakukan *web scraping* data kendaraan bekas dari situs web [[carsome](https://www.carsome.id/beli-mobil-bekas?carTypes=1)] dan membuat dashboard interaktif untuk menganalisis data.

## Langkah-langkah

1. **Scraping Data**
   - Menggunakan Python dengan library requests dan BeautifulSoup untuk melakukan scraping data.
   - Data yang diambil meliputi informasi tentang kendaraan seperti Year, Brand, Model, Other Info
   - Data kemudian disimpan dalam format CSV untuk analisis lebih lanjut.

2. **Dashboard**
   - Menggunakan Power BI untuk membuat dashboard interaktif.
   - Dashboard akan menampilkan visualisasi data seperti grafik, tabel, dan filter untuk memudahkan analisis.

## Instalasi dan Penggunaan

1. **Scraping Data**
   - Pastikan Python telah terinstal di komputer Anda.
   - Install library requests dan BeautifulSoup menggunakan pip:

     ```bash
     pip install requests beautifulsoup4
     ```

   - Jalankan script scraping untuk mengumpulkan data:

     ```bash
     python scrape_data.py
     ```

2. **Dashboard**
   - Pastikan Power BI telah terinstal di komputer Anda.
   - Impor file CSV yang telah dihasilkan dari scraping data ke dalam Power BI.
   - Buat visualisasi dan dashboard dengan menampilkan informasi seperti sales by segment, orders by month, total category growth by year, total segment growth by year, total budget 2023, perbandingan growth 2022 vs 2023, YTD sales 2022 dan 2023.
