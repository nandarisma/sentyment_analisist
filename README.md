## Sentiment Analysis with Caikit and Hugging Face

Dengan menggunakan kerangka kerja runtime Caikit dan model Hugging Face, repositori ini menyediakan layanan analisis sentimen. Server gRPC mengelola permintaan analisis sentimen, yang memungkinkan pengguna untuk memeriksa input teks untuk mengetahui apakah itu positif, negatif, atau netral.

## Resume

Untuk menjalankan model analisis sentimen Hugging Face dalam lingkungan server gRPC, proyek ini menggunakan kerangka kerja modular Caikit. Contoh skrip klien menunjukkan cara mengirimkan input teks ke server dan menerima hasil klasifikasi sentimen.

## Karakteristik

- **gRPC Server**: Mengoperasikan server untuk menangani permintaan analisis sentimen melalui gRPC.
- **Integrasi Kerangka Kerja Caikit**: Menyederhanakan operasi model dengan menggunakan kerangka kerja Waktu Caikit.
- **Hugging Face Models**: Memanfaatkan model klasifikasi sentimen Hugging Face yang sudah terlatih.

## Installation
1. **Salin Repositori**
   Salin repositori ini ke. komputer lokal Anda:
   ```bash
   git clone https://github.com/nandarisma/sentiment_analisist.git.
2. 2. Instalasi Dependensi
Instal semua dependensi yang diperlukan:
   ```bash
   pip install -r requirements.txt
3. Pengaturan Lingkungan
   Pastikan konfigurasi yang dibutuhkan (seperti jalur model atau pengenal) sudah diatur dengan benar dalam lingkungan atau
   file konfigurasi Anda.
