# SMP-Pintar (Simpanan Mandiri Pelajar Pintar)

[![Versi](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/Int3_/SimPel_Bank) 
[![Platform](https://img.shields.io/badge/platform-Android-green.svg)](https://appinventor.mit.edu/)

**SMP-Pintar** adalah aplikasi manajemen keuangan digital yang dirancang untuk siswa SMPN 2 Depok. Proyek ini dikembangkan untuk kompetisi **Codefest 2026**, yang berfokus pada pendidikan keuangan dan keamanan data lokal.

---

## Fitur Utama
- **Sistem Akun Mandiri:** Pengguna dapat mendaftar dengan nama pengguna dan kata sandi yang unik.

- **Validasi Data:** Terdapat perlindungan terhadap input kosong dan nama pengguna duplikat.

- **Basis Data Lokal:** Data disimpan dengan aman menggunakan TinyDB, memastikan data tetap ada bahkan setelah aplikasi ditutup.

- **Syarat & Ketentuan:** Aplikasi ini memberikan informasi yang jelas tentang penggunaan dan privasi data.

- **Antarmuka Pengguna Pro:** Aplikasi ini memiliki desain yang bersih dengan fitur *Tampilkan/Sembunyikan Kata Sandi* dan bantuan cepat.

## Teknologi yang Digunakan
- **Alat Pengembangan:** MIT App Inventor
- **Penyimpanan:** TinyDB (Penyimpanan Lokal)
- **Komunikasi:** Activity Starter (untuk tautan eksternal)

## Struktur Data (TinyDB)
Aplikasi menyimpan data dalam format Daftar untuk efisiensi:

- **Tag:** `username`
- **Nilai:** `[nomor_telepon, password]`

## Cara Instalasi
1. Unduh file `.apk` dari folder `bin/` (jika tersedia).

2. Izinkan instalasi dari sumber yang tidak dikenal di perangkat Android Anda.

3. Buka aplikasi dan buat akun di menu **Daftar**.

## Syarat & Ketentuan
Proyek ini mencakup [Syarat & Ketentuan](TERMS.md) yang mengatur privasi data dan batasan tanggung jawab pengembang.

---

## Profil Pengembang
**R. Prabu Panji Nusantara** -Kelas 7 SMP-

**Meikel Clinton Hiroki Simanjuntak** -Kelas 7 SMP-

---
Dibuat dengan memperhatikan masa depan keuangan siswa Indonesia.
