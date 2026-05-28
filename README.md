# Project Kelompok 4-2B-SI

Project akhir Mata Kuliah Algoritma dan Struktur Data dengan studi kasus Sistem Pemesanan Tiket Bioskop

Sistem Pemesanan Tiket Bioskop berbasis Java Console.

## Deskripsi

Project ini merupakan aplikasi pemesanan tiket bioskop berbasis Java yang berjalan melalui terminal/console. Sistem digunakan dari sudut pandang admin atau kasir untuk mengelola film, jadwal tayang, kursi, transaksi, dan riwayat pembelian tiket.

## Struktur File

```text
Project-Kelompok-4-2B-SI/
│
├── Laporan Kelompok 4_2B_Sistem Informasi.pdf
├── SistemBioskop.java
├── films.csv
├── transactions.csv
└── README.md
```
Keterangan:

`Laporan Kelompok 4_2B_Sistem Informasi.pdf` → laporan project

`SistemBioskop.java` → file utama program

`films.csv` → penyimpanan data film

`transactions.csv` → penyimpanan riwayat transaksi

`README.md` → dokumentasi singkat project

---

## Persyaratan

Pastikan perangkat sudah terpasang:

- Java JDK 8 atau lebih baru
- Terminal / Command Prompt
- Git (opsional)

---

## Cara Menjalankan Program

### 1. Jalankan Program
Program dapat dijalankan secara lokal menggunakan IDE Java atau melalui terminal/command prompt.

### 2. Login ke Sistem

Masukkan password sesuai hak akses yang ingin digunakan.

- Password Kasir : 123456

- Password Admin : 654321

### 3. Gunakan Fitur Program

Setelah berhasil login, pengguna dapat mengakses berbagai fitur yang tersedia, seperti:

Mengelola data film
Mengatur jadwal tayang
Melakukan transaksi tiket
Memilih kursi bioskop
Melihat riwayat transaksi
### 4. Keluar Program dengan Benar

Untuk memastikan seluruh data tersimpan dengan aman, keluar program secara bertahap melalui menu Kembali hingga kembali ke halaman login utama, kemudian pilih opsi Keluar.

---

## Penyimpanan Data

Data program disimpan otomatis menggunakan file CSV:

* Film disimpan pada `films.csv`
* Transaksi disimpan pada `transactions.csv`

Perubahan data akan tetap tersimpan setelah program ditutup.

---

## Catatan

* Jangan menghapus file CSV saat program digunakan.
* Pastikan format file CSV tidak diubah secara manual.
* Jika file CSV kosong, sistem akan membuat data baru saat program berjalan.

---
