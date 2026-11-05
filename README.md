# Arus — Catatan Keuangan

Aplikasi web responsif (PWA) untuk mencatat pemasukan dan pengeluaran di rekening Mandiri dan BCA. Bisa dijalankan di Windows, lalu dibuka dari Safari di iPhone dan ditambahkan ke Home Screen.

## Menjalankan di Windows

1. Pasang Node.js jika belum tersedia.
2. Buka PowerShell di folder project ini.
3. Jalankan `npx serve .` lalu buka alamat lokal yang ditampilkan.

Untuk membuka dari iPhone di jaringan Wi-Fi yang sama, sajikan project dengan alamat jaringan yang dapat dijangkau iPhone. Agar opsi **Add to Home Screen** dan service worker berfungsi, gunakan HTTPS untuk alamat publik atau jaringan lokal yang mendukung secure context.

## Masuk

- Username: `admin`
- Password: `wang123abc`

## Fitur

- Dashboard saldo total dan saldo per rekening.
- Catatan pemasukan transfer dan pengeluaran melalui transfer, QRIS, virtual account, atau tarik tunai.
- Laporan bulanan, ringkasan per bank, dan rincian metode pembayaran.
- Pencarian dan filter transaksi.
- Penyimpanan transaksi di local storage browser dan dukungan PWA.

## Batasan penyimpanan

Ini prototipe lokal tanpa server. Login hanya gerbang sederhana di browser, bukan perlindungan data yang aman; transaksi tersimpan pada browser/perangkat yang digunakan dan tidak tersinkron otomatis. Siapa pun yang memiliki akses ke browser/perangkat dapat mengakses data. Untuk penggunaan serius, backend, autentikasi aman, dan backup terenkripsi perlu ditambahkan.
