# 🍳 Kokiku — Cooking Craft Simulator

Game simulasi masak berbasis web (single HTML file, tanpa backend).

## Cara Main
1. Pilih bahan dari hotbar.
2. Bahan masuk ke slot Tungku Masak (maks 6 bahan).
3. Klik **Masak!** dan tunggu prosesnya selesai.
4. Hidangan tersaji otomatis di Meja Saji dan menghasilkan uang tiap detik.
5. Gunakan uang untuk beli bahan di **Toko** 🛒.
6. Naik level untuk membuka bahan baru.
7. Cek resep yang sudah ditemukan di **Ensiklopedia** 📖.

Tombol **ℹ️ Tutorial** di navbar bisa dipakai kapan saja untuk mengulang panduan langkah-langkah di atas.

## Fitur
- Sistem crafting bahan → resep (tier 0–2, kombinasi 1–3 bahan).
- Progres level & XP dengan unlock bahan baru.
- Auto-save ke `localStorage`.
- Tutorial interaktif untuk pemain baru.

## Cara Jalankan
Buka `index.html` langsung di browser — tidak perlu server atau instalasi.

## Struktur
- Semua kode (HTML, CSS, JS) ada dalam satu file `index.html`.
- Data resep & bahan didefinisikan di objek `INGREDIENTS` dan `RECIPES` dalam script.
