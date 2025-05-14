# Proyek Pertama: Menganalisis minat pasar hp masyarakat

## Business Understanding

Sebuah penjual ritel hp mengalamai permasalahan pada penjualan hp dimana banyak produk belum kunjung laku, sehingga mengakibatkan cashflow dalam bisnis tidak berjalan dengan baik.

### Permasalahan Bisnis

Banyaknya produk yang belum laku disebabkan oleh manajemen stok produk yang kurang baik, dimana banyak produk yang kurang relevan dengan minat hp masyarakat. Untuk menyelesaikan masalah tersebut kita akan menggunakan pendekatan Stimulus - Response.
- Stimulus : Gadget.in, video bertemakan "Rekomendasi hp untuk lebaran/tahun baru"
- Response : Komentar netizen terhadap video tersebut

Mengapa menggunakan stimulus tersebut ?
Karena Gadget.in merupakan makro influncer yang dimana banyak masyarakat mencari rekomendasi hp melalui videonya.
Video bertemakan "Rekomendasi HP" sering menjadi rujukan masyarakat sebelum membeli HP

### Cakupan Proyek

- Scraping data komentar youtube Gadget.in
- Membersihkan data
- Memberi label pada data
- Membuat visualisasi data
- Rekomendasi insight
- Saran

### Persiapan

Sumber scraping data:
- https://www.youtube.com/watch?v=1Q7sbuPvLic
- https://www.youtube.com/watch?v=a3KriqTgaQE

Gabungkan kedua data tersebut menjadi satu dalam format csv.

Setup environment:

```
# 1. Buat virtual environment
python -m venv env

# 2. Install library yang dibutuhkan
requirements.txt

# 3. Jalankan Jupyter Notebook
jupyter notebook

```

## Melabeli Data

Memberi komentar label dengan asosiasi merek hp

## Visualisasi Data

Menggambarkan data dengan dengan urutan tren hp yang paling diminati

## Kesimpulan

- Setelah kedua data bergabung, menghasilkan 12.337 komentar
- Label komentar terdiri dari ['infinix' 'xiaomi' 'itel' 'samsung' 'realme' 'vivo' 'iqoo' 'oppo' 'tecno' 'asus']
- Data melakukan penyesuaian dengan label, menghasilkan 4.543 komentar
- Visualisasi data menunjukan peringkat tren sesuai merek hp


### Saran

- Bandingkan analisis data pertahun untuk mengetahui trend tiap tahunnya,
    membandingkat analisis data tahun 2021,2022,2023,dst
- Tambahkan analisis sentimen untuk setiap komentar