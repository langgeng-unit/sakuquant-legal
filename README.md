# SakuQuant — Situs Informasi dan Legal

Situs statis berbahasa Indonesia dengan ringkasan bahasa Inggris untuk aplikasi Android SakuQuant. Halaman ini **tidak** mengandung rahasia, kunci API, token, atau SDK Google.

## Berkas
- `index.html` — halaman beranda.
- `privacy.html` — kebijakan privasi Google Drive dan data pasar.
- `terms.html` — ketentuan penggunaan.
- `styles.css` — gaya responsif.
- `.nojekyll` — publikasikan berkas apa adanya.

## GitHub Pages
1. Buat repository **public** bernama `sakuquant-legal` di organisasi `langgeng-unit`.
2. Unggah semua berkas ini ke root cabang `main`, satu commit. Jangan unggah ke repository privat aplikasi Android.
3. Buka Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/(root)` → Save.
4. Tunggu dan verifikasi melalui browser:
   - `https://langgeng-unit.github.io/sakuquant-legal/`
   - `https://langgeng-unit.github.io/sakuquant-legal/privacy.html`
   - `https://langgeng-unit.github.io/sakuquant-legal/terms.html`

## Penting untuk Google OAuth Production
- GitHub Pages adalah hosting gratis, **tetapi bukan bukti kepemilikan domain** `github.io`.
- Google mensyaratkan beranda produksi pada domain yang dapat diverifikasi sebagai domain yang Anda miliki. `github.io` adalah shared hosting domain; bisa ditolak pada brand verification. Jangan menyatakan lolos sebelum Google mengonfirmasi.
- Bila Google menolak, pertahankan situs/kode ini dan hubungkan domain pribadi ke GitHub Pages nanti. Tidak perlu mengubah APK Android.
- Jangan mengisi alamat OAuth pada Google Cloud sebelum halaman publik aktif dan syarat verifikasi diperiksa.

## Pemeliharaan
Perbarui kebijakan jika pemrosesan Google Drive atau fitur aplikasi berubah. Hindari menaruh informasi pribadi di issue publik.