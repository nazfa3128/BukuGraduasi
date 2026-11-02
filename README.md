# Buku Program Majlis Graduasi Murid Tahun 6 · 2026

Flip book interaktif (index.html) untuk buku program majlis graduasi.

## Cara muat naik ke GitHub Pages
1. Cipta repository baharu di GitHub (contoh: `buku-program-graduasi`), tetapkan sebagai **Public**.
2. Klik **Add file → Upload files**, seret SEMUA kandungan folder ini (`index.html`, `page-flip.browser.js`, folder `pages/`), kemudian **Commit changes**.
3. Pergi ke **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → **Save**.
4. Selepas 1–2 minit, flip book boleh dibuka di `https://NAMA-ANDA.github.io/buku-program-graduasi/`

## Thumbnail pautan (WhatsApp / Facebook)
Ikon sekolah akan keluar di sebelah URL (tab pelayar) secara automatik.
Untuk gambar pratonton semasa pautan dikongsi, buka `index.html` di GitHub (ikon pensel ✏️),
cari `SITE_URL` (3 tempat) dan gantikan dengan alamat penuh laman anda, contohnya
`https://nama-anda.github.io/buku-program-graduasi/` (mesti berakhir dengan `/`), kemudian Commit.

## Muzik latar
Fail `music.mp3` (Warisan Gamelan Melayu – Perang Besar) dimainkan apabila butang
"Buka Buku Program" ditekan. Butang equaliser pada bar kawalan untuk hidup/matikan muzik.

## Kawalan
- Tarik bucu halaman / klik / leret (telefon) untuk menyelak
- Kekunci ← → untuk navigasi, Home/End untuk halaman pertama/terakhir
- Butang: zum, semua halaman, main automatik, bunyi, skrin penuh

## Tukar halaman
Gantikan fail `pages/page1.jpg` … `pages/page8.jpg`. Jika bilangan halaman berubah, ubah `const TOTAL = 8;` dalam index.html.
