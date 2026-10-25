STUDIO PICO - PROTOTYPE MULTI-HALAMAN

Cara menjalankan:
1. Ekstrak folder roblox-reservasi-prototype.
2. Buka index.html menggunakan browser.
3. Navigasi ke detail produk, cart, checkout, dan riwayat pesanan menggunakan link di halaman.

File halaman:
- index.html: landing page/katalog
- detail.html?id=1: detail produk (ID mengikuti mock data)
- cart.html: keranjang multi-produk
- checkout.html: form checkout dan simulasi login Gmail
- orders.html: riwayat pesanan dan simulasi pembayaran
- assets/site.css: stylesheet bersama
- assets/shared.js: mock data mengikuti Data Dictionary
- assets/pages.js: interaksi untuk halaman terpisah

PENTING: login Google, penyimpanan, pembayaran, upload bukti, dan pesanan di sini masih simulasi localStorage. Tidak ada autentikasi Google/OAuth nyata, server, atau pembayaran aktif. Nomor antrean tidak diterbitkan dalam prototype; sesuai aturan, hanya admin backend yang menerbitkannya setelah verifikasi pembayaran.
