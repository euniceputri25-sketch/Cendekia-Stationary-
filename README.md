# Cendekia-Stationary-
Cendekia Stationary: Sistem POS dan Akuntansi Persediaan Toko ATK

Aplikasi web untuk mencatat pembelian (restock), penjualan kasir, dan pergerakan stok toko alat tulis kantor (ATK), lalu menyusun jurnal dan laporan secara otomatis dari setiap transaksi.

Web App: https://euniceputri25-sketch.github.io/Sistem-Persediaan-ATK-/

Fitur Utama
Master Data Barang: SKU, kategori, harga beli (HPP), harga jual, stok, dan batas stok minimum (ROP).
Pembelian dan Restock: kasir mengajukan, manajer menyetujui sebelum stok bertambah.
Penjualan / POS: pembayaran Tunai, QRIS, atau Transfer Bank dengan validasi stok.
Mutasi Persediaan: pencatatan setiap barang masuk dan keluar.
Kartu Persediaan (FIFO): saldo persediaan per produk, bisa diekspor ke Excel/PDF.
Stock Opname: membandingkan stok sistem dengan stok fisik.
Laporan Pembelian dan Penjualan: jurnal otomatis dan ringkasan performa usaha.
Audit Trail: log aktivitas pengguna.
Akun Demo
Peran	Email	Password
Kasir	kasir@cendekia.com	kasir123
Pemilik / Manajer	owner@cendekia.com	owner123
Teknologi

HTML, CSS, dan JavaScript dalam satu file (index.html), dengan Chart.js (grafik), SheetJS (ekspor Excel), dan Supabase (disiapkan untuk penyimpanan data tahap lanjut).

Catatan
Data prototipe disimpan di memori browser, sehingga hilang jika halaman di-refresh.
Memerlukan koneksi internet untuk memuat pustaka grafik dan ekspor.
Pengembang

[Eunice Putri Shekina] · [12030124140310] · Pengkodean dan Pemrograman, Kelas E
