# Toko Dapur Manis

Halaman toko online satu berkas. Pembeli memilih produk dari HP, lalu ordernya
dikirim ke WhatsApp penjual sebagai pesan yang sudah terformat rapi.

- `index.html` — seluruh toko: katalog, keranjang, checkout, dan panel penjual.
- Tidak butuh server, database, atau proses build. Cukup dihosting sebagai berkas statis.
- Panel penjual: buka tautan "Kelola toko" di bagian bawah katalog, lalu masukkan PIN.
- Data toko (produk, harga, nomor WhatsApp) tersimpan di dalam `index.html`,
  pada blok `<script id="shop-data" type="application/json">` di bagian atas berkas.
