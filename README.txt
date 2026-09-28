# Coach 2 Training — PWA

Folder ini adalah versi Progressive Web App (PWA) dari Coach 2 Training.

## Agar bisa dipasang ke beranda Android
File PWA perlu dibuka dari website HTTPS (contoh: GitHub Pages), bukan langsung dari `file://`.

Cara paling sederhana:
1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ini, terutama `index.html`, `manifest.webmanifest`, `sw.js`, dan folder `icons`.
3. Aktifkan GitHub Pages dari Settings → Pages → Deploy from a branch → pilih branch utama dan folder `/root`.
4. Buka alamat Pages yang diberikan GitHub di Chrome Android.
5. Tekan menu ⋮ → "Tambahkan ke layar utama" / "Install app".

Setelah terpasang, Coach 2 Training akan terbuka seperti aplikasi dan dapat bekerja offline untuk halaman yang sudah tersimpan.
