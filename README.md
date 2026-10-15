# QC Paperless

Aplikasi QC paperless (Inline & Final QC, measurement, dashboard) — satu file `index.html`, tanpa build.

## Pakai di GitHub Pages
1. Upload `index.html` (dan `README.md`) ke root repository.
2. Settings → Pages → Source: *Deploy from a branch* → Branch `main` / folder `/ (root)` → Save.
3. Buka `https://<username>.github.io/<nama-repo>/`.

## Catatan
- Di GitHub Pages data tersimpan di browser masing-masing perangkat (tidak terhubung antar user).
  Untuk data terintegrasi antar user (real-time), jalankan paket `lan_server` di jaringan pabrik.
- Pindah data antar perangkat: Master data → Export semua data (JSON) → Import data (JSON).
