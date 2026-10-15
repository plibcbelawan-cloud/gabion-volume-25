# Flipbook Majalah GABION Volume 25

Flipbook Majalah GABION – Garda Budaya Informasi Bea Cukai Belawan, Edisi September 2026.

## Isi folder
- `index.html` – halaman flipbook
- `pages/01.jpg` … `pages/20.jpg` – halaman majalah (untuk animasi flipbook)
- `hd/01.jpg` … `hd/20.jpg` – halaman resolusi tinggi untuk mode Perbesar & Baca
- `js/page-flip.browser.js` – library animasi balik halaman (StPageFlip, lisensi MIT)

## Cara publikasi di GitHub Pages
1. Buat repository baru, misalnya `gabion-flipbook`.
2. Upload semua isi folder ini (index.html, folder pages, folder hd, folder js) ke root repository.
3. Buka **Settings → Pages**, pilih Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1–2 menit. Flipbook bisa dibuka di `https://USERNAME.github.io/gabion-flipbook/`.

## Embed ke website lain
```html
<iframe src="https://USERNAME.github.io/gabion-flipbook/"
        style="width:100%;height:720px;border:0"
        title="Majalah GABION Volume 25" allowfullscreen loading="lazy"></iframe>
```
Ganti `USERNAME` dengan nama akun GitHub Anda.
