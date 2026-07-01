# carosei

Carousel Reel — alat berbasis browser untuk memecah artikel (HTML atau teks biasa) menjadi slide carousel siap unggah ke Instagram/TikTok. Semua proses berjalan di browser, tidak ada data yang dikirim ke server.

## Fitur

- Tempel artikel HTML atau teks biasa, atau unggah file `.html`
- **Dua mode hasil:**
  - **Teks jadi slide** — mengambil teks artikel dan menatanya ulang pakai template + tema bawaan
  - **Desain asli** — merender HTML apa adanya (warna, gambar, layout dipertahankan) lalu memotongnya otomatis sesuai rasio slide
- Pecah slide otomatis per sub-judul atau per jumlah karakter (mode teks)
- Pilih rasio slide: 1:1, 4:5, atau 9:16 (story)
- 6 gaya warna: Paper, Ink, Rust, **Nebula** (gradient ungu-navy dengan aksen hijau), **Grid** (hitam-teal gelap dengan pola grid halus & bingkai kartu, aksen hijau), dan **Alert** (near-black dengan pola grid, aksen merah/coral untuk sinyal overvalued)
- **Upload logo** (PNG/JPG/SVG) dengan pengaturan posisi (4 sudut), ukuran, dan pilihan tampil di semua slide atau sampul saja — bekerja di kedua mode
- Unduh per slide sebagai PNG 1080px, atau semua sekaligus dalam `.zip`

### Catatan mode "Desain asli"

- File HTML sebaiknya **self-contained**: CSS ditulis inline/di dalam `<style>`, gambar berupa URL online atau ter-embed base64. Gambar yang mengandalkan file lokal terpisah tidak akan muncul.
- Pemotongan slide dilakukan otomatis dengan tinggi sama rata sesuai rasio, sehingga kadang bisa memotong di tengah elemen. Sesuaikan tinggi konten HTML bila perlu potongan yang lebih presisi.

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
