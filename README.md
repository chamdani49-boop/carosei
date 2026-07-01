# carosei

Carousel Reel — alat berbasis browser untuk memecah artikel (HTML atau teks biasa) menjadi slide carousel siap unggah ke Instagram/TikTok. Semua proses berjalan di browser, tidak ada data yang dikirim ke server.

## Fitur

- Tempel artikel HTML atau teks biasa, atau unggah file `.html`
- Pecah slide otomatis per sub-judul atau per jumlah karakter
- Pilih rasio slide: 1:1, 4:5, atau 9:16 (story)
- 3 gaya warna: Paper, Ink, Rust
- **Upload logo** (PNG/JPG/SVG) dengan pengaturan posisi (4 sudut), ukuran, dan pilihan tampil di semua slide atau sampul saja
- Unduh per slide sebagai PNG 1080px, atau semua sekaligus dalam `.zip`

## Cara membuka via website (GitHub Pages)

1. Push repo ini ke GitHub.
2. Buka **Settings → Pages** di repositori.
3. Pada **Build and deployment → Source**, pilih **Deploy from a branch**.
4. Pilih branch `main` (atau `master`) dan folder `/ (root)`, lalu **Save**.
5. Tunggu beberapa menit. Situs akan tersedia di:
   `https://<username>.github.io/carosei/`

Karena file utama sudah bernama `index.html`, GitHub Pages otomatis menyajikannya di URL tersebut.

## Menjalankan secara lokal

Cukup buka file `index.html` langsung di browser — tidak perlu server.
