# Website Global Tama Solusi (GitHub Pages)

Isi folder ini:
- `index.html` : seluruh halaman website (Home, Tentang Kami, Layanan, Our Projects, Dokumentasi, Kontak)
- `img/`       : logo dan foto

## Pengaturan penting
Buka `index.html`, cari baris `var API_URL = '...'` di dekat bagian `<script>`.
Isinya adalah alamat web app Apps Script (berakhiran `/exec`). Ganti bila alamatnya berubah.

## Memasang di GitHub Pages
1. Buat repository publik baru di GitHub.
2. Unggah `index.html`, folder `img`, dan `README.md` ke repository (Add file > Upload files).
3. Buka Settings > Pages > Build and deployment > Source: "Deploy from a branch".
4. Pilih branch `main` dan folder `/ (root)`, lalu Save.
5. Tunggu 1-2 menit. Alamat situs: https://NAMA-GITHUB.github.io/NAMA-REPOSITORY/
