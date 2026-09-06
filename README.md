# TemanCipta — HRIS

Website demo Human Resource Information System dengan identitas TemanCipta dan tema biru–hijau. Dibuat menggunakan HTML, CSS, dan JavaScript tanpa framework atau proses build.

## Fitur

- Dashboard ringkasan karyawan dan kehadiran.
- Direktori karyawan dengan pencarian, filter departemen, dan form tambah karyawan.
- Absensi dan unduhan laporan CSV.
- Simulasi persetujuan atau penolakan cuti.
- Ringkasan payroll bruto.
- Logo TemanCipta, kartu dan ikon berefek 3D, animasi transisi, serta tata letak responsif.
- Mendukung preferensi reduced motion pada perangkat pengguna.

## Menjalankan

Buka folder proyek menggunakan VS Code, lalu buka `index.html` melalui ekstensi Live Server. Website ini juga dapat dibuka langsung dari `index.html`.

Jika Python tersedia, jalankan dari folder proyek:

```sh
python -m http.server 8000
```

Lalu buka http://localhost:8000 pada browser. Tidak perlu `npm install` atau database.

## File utama

| File | Keterangan |
| --- | --- |
| `index.html` | Struktur halaman dan form karyawan |
| `style.css` | Tema, tata letak responsif, dan efek visual |
| `app.js` | Navigasi, data demo, interaksi, dan animasi |
| `assets/temancipta-logo.png` | Logo yang diberikan pemilik proyek |

## Batasan demo

Data karyawan, absensi, cuti, dan payroll adalah contoh. Data hanya disimpan di memori halaman dan kembali ke kondisi awal ketika halaman dimuat ulang. Persetujuan cuti tidak mengubah saldo cuti. Payroll belum menghitung pajak, BPJS, potongan, atau pembayaran. Belum ada backend, autentikasi aplikasi, atau database.

Font dimuat dari Google Fonts ketika koneksi internet tersedia, dengan font sans-serif bawaan sebagai fallback.

## GitHub Pages (opsional)

Setelah file ada di repository, buka **Settings → Pages**, pilih **Deploy from a branch**, kemudian pilih branch `main` dan folder `/ (root)`. Penyimpanan source code di GitHub tidak otomatis mengaktifkan publikasi website.
