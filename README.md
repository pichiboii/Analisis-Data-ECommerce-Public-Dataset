# 🛒 Analisis Data: E-Commerce Public Dataset
Project Analisis Data dengan Python *Coding Camp 2025 by DBS Foundation* oleh Hafizha Aghnia Hasya
Proyek ini bertujuan untuk melakukan analisis menyeluruh terhadap dataset e-commerce publik. Fokus utama dari proyek ini adalah menggali insight bisnis dari data transaksi pelanggan melalui tahapan data wrangling, analisis eksploratif, visualisasi, hingga penyajian dalam bentuk dashboard interaktif menggunakan Streamlit.

## 🔍 Alur Analisis
### 📌 Menentukan Pertanyaan Bisnis
- Bagaimana tren jumlah pesanan pada e-commerce dalam beberapa bulan terakhir (tahun 2018)?
- Bagaimana performa seller berdasarkan jumlah pesanan dan rating pelanggan?
- Bagaimana distribusi geografis seller berdasarkan kode pos dan koordinat?
### 🧹 Data Wrangling
- Gathering data
- Assessing data
- Cleaning data
### 📊 Exploratory Data Analysis (EDA)
- Statistik deskriptif
- Distribusi dan korelasi antar fitur
- Outlier detection
- Feature Engineering untuk Insight Tambahan
### 📈 Visualisasi dan Explanatory Analysis
- Visualisasi tren dan pola pembelian
- Analisis performa seller dengan clustering (manual grouping) dan RFM analysis
- Analisis distribusi geografis seller
### 🖥️ Dashboard Interaktif dengan Streamlit
- Tampilan interaktif insight e-commerce
- Filter data berdasarkan tanggal, jumlah yang ingin ditampilkan
- Visualisasi dinamis dan ringkas

## How to Open Dashboard - Anaconda
Untuk membuka dashboard di lokal dengan Anaconda, lakukan ini pada Windows PowerShell :
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```
Kemudian arahkan path ke folder dashboard, dan ketikkan ini 
```
streamlit run dashboard.py
```
Selamat! Kamu sudah membuka dashboard secara lokal di browser kamu!

## How to Open Dashboard - Online by url
Untuk membuka dashboard secara online dengan url/link, ketikkan link ini di browsermu :
```
https://hafizhaaghniaprojectdashboard.streamlit.app/
```
Atau kamu bisa mengklik [link ini](https://hafizhaaghniaprojectdashboard.streamlit.app/)
