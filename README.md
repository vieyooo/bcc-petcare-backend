# BCC Pet Care - Backend API

Repositori ini berisi kode sumber untuk *Backend REST API* dari aplikasi mobile BCC Pet Care. API ini dirancang untuk mengintegrasikan pengelolaan layanan grooming, dokter hewan, serta penjualan produk petshop.

## 🚀 Teknologi yang Digunakan
- **Framework:** Laravel 11
- **Database:** MySQL
- **Autentikasi:** Laravel Sanctum (Token-based API)
- **Bahasa:** PHP 8.x

## ⚙️ Cara Menjalankan Project (Local Development)
1. Clone repositori ini: `git clone https://github.com/USERNAME/bcc-petcare-backend.git`
2. Masuk ke folder: `cd bcc-petcare-backend`
3. Install dependensi: `composer install`
4. Copy file environment: `cp .env.example .env`
5. Sesuaikan konfigurasi database di file `.env` (DB_DATABASE, DB_USERNAME, DB_PASSWORD).
6. Generate key aplikasi: `php artisan key:generate`
7. Jalankan migrasi database: `php artisan migrate --seed`
8. Jalankan server lokal: `php artisan serve` (Akses di http://127.0.0.1:8000)

## 📌 Endpoint Utama
- `POST /api/login` (Autentikasi & Generate Token)
- `GET /api/pets` (Mendapatkan daftar hewan peliharaan)
- `POST /api/bookings` (Membuat pesanan layanan)
- `GET /api/products` (Katalog produk petshop)
