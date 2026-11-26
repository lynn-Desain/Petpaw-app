# Petpaw — Petshop & Professional Pet Care

## Menjalankan demo
1. Ekstrak `Petpaw_App.zip`.
2. Buka folder `petpaw_app`.
3. Klik dua kali `index.html` atau buka melalui browser modern.
4. Semua data demo disimpan di `localStorage` browser yang digunakan.

## Login demo
- Admin: `admin@petpaw.id`
- Password: `Petpaw123`
- Pelanggan: pilih peran Pelanggan, isi nama dan password apa saja untuk simulasi.

## Fitur prototipe
- Katalog 23 entri produk dari PDF, pencarian, kategori, urut harga, detail produk.
- Upload foto produk melalui menu Admin > Inventaris. Foto disimpan lokal di browser.
- Booking grooming dan penitipan, tiket antrean, daftar booking admin, perubahan status.
- Opsi layanan antar jemput, alamat penjemputan/pengantaran, kecamatan Samarinda, peta pratinjau pelanggan, dan tautan Google Maps/rute pada dashboard admin.
- Pencatatan stok masuk/keluar, data penyedia layanan, transaksi masuk/keluar.
- Ekspor CSV produk, booking, penyedia layanan, transaksi.
- Rekap bulanan dan cetak / Save as PDF.
- Tombol WhatsApp mengarah ke tautan Petpaw yang diberikan.
- Mode gelap dan tampilan responsif.

## Penting — integrasi produksi
Ini adalah prototipe frontend, bukan sistem produksi multi-pengguna. Login admin demo bukan autentikasi aman. Data tersimpan lokal di browser, tidak tersinkron antar perangkat. Payment gateway, WhatsApp Business Cloud API, push notification, chat real-time, cloud backup, database, enkripsi end-to-end, serta kontrol akses server memerlukan backend dan kredensial resmi. Jangan gunakan data pelanggan nyata sebelum backend dan keamanan produksi diterapkan.

## Katalog dan foto
PDF sumber berisi nama, merek, varian, harga dan keterangan, namun tidak memuat foto produk individual. Karena itu kartu produk memakai ilustrasi kategori sampai foto produk asli diunggah melalui panel admin. File `products.csv` dapat dipakai sebagai data awal. Harga mengikuti PDF dan merupakan estimasi katalog awal, bukan harga real-time. Obat hewan tidak ditambahkan sebagai rekomendasi produk tertentu, sesuai catatan PDF.
