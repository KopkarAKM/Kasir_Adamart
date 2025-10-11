# AdaMart — Minimal GitHub Pages Package

Langsung **drag & drop** file ke repository GitHub kamu (root), lalu aktifkan **Settings → Pages** (branch: `main`, folder: `/(root)`).

## File
- `index.html` — Halaman login + tes koneksi ke Google Apps Script.

## Konfigurasi
- URL Google Script sudah diisi di dalam `index.html` pada variabel `GOOGLE_SCRIPT_URL`.

## Uji Koneksi
- Isi username & password lalu klik **Login** → akan mencoba `action: get_products`.
- Jika sukses, akan muncul alert **“Koneksi ke Google Sheet berhasil!”**.
