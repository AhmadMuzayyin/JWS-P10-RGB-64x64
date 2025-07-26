# JWS-P10-RGB-64x64

Repositori ini berisi dua proyek utama untuk papan LED RGB berukuran 64x64 berbasis esp32 wroom 2 / devkit v1:

## 1. RGB_JAM_ISTIWA
File: `RGB_JAM_ISTIWA/RGB_JAM_ISTIWA.bin`

Proyek ini digunakan untuk menampilkan jam istiwa (waktu matahari tepat di atas kepala) pada papan LED RGB. Fitur utama:
- Menampilkan jam istiwa secara akurat.
- Cocok untuk edukasi astronomi atau penunjuk waktu khusus.

## 2. RGB_JADWAL_SHALAT
File: `RGB_JADWAL_SHALAT/RGB_JADWAL_SHALAT.bin`

Proyek ini digunakan untuk menampilkan jadwal shalat harian pada papan LED RGB. Fitur utama:
- Menampilkan waktu shalat (Subuh, Dzuhur, Ashar, Maghrib, Isya) secara digital.
- Dapat digunakan untuk masjid, mushola, atau tempat ibadah lainnya.

---

Setiap file `.bin` merupakan firmware yang dapat diunggah ke papan LED RGB 16x128 x 2. Jadi
instalasi dari panel p10 rgb untuk proyek ini sebenarnya dua rangkaian dijadikan satu, yaitu rangkaian 16x128 disusun ke bawah menjadi susunan 32x64 untuk jam istiwa dan susunan yang sama untuk jadwal shalatnya.
