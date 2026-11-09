# Playbook BAE Accurate Online Tangerang 2 — PWA

Versi ini disiapkan agar bisa di-install di HP sales sebagai aplikasi web (PWA).

## Fitur
- Bisa dipasang dari Chrome Android atau Safari iPhone melalui Add to Home Screen.
- Terbuka dalam tampilan standalone seperti aplikasi.
- App shell disimpan oleh service worker agar halaman utama dapat dibuka kembali saat offline setelah kunjungan online pertama.
- Checklist tetap menggunakan penyimpanan lokal browser (`localStorage`). Tidak ada login, sinkronisasi, atau database bersama.

## Deploy ke GitHub Pages
1. Buat repository GitHub, misalnya `playbook-bae-tangerang-2`.
2. Upload seluruh isi folder ini ke root repository (pastikan `index.html`, `manifest.webmanifest`, dan `service-worker.js` berada di root).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu **Save**.
6. Buka URL GitHub Pages yang diberikan GitHub. PWA membutuhkan HTTPS; GitHub Pages sudah menyediakan HTTPS.

## Cara instal oleh sales
- **Android:** buka URL melalui Chrome → menu titik tiga → Install app / Add to Home Screen.
- **iPhone:** buka URL melalui Safari → Share → Add to Home Screen → Add.

## Catatan penyimpanan
Checklist disimpan hanya di browser/perangkat sales masing-masing. Data tidak terlihat oleh ABM dan tidak otomatis berpindah ke HP lain. Hindari membersihkan data situs/browser jika ingin mempertahankan checklist.
