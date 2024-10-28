

# Penghitung Umur

Aplikasi ini adalah program Java yang menghitung umur seseorang berdasarkan tanggal lahir yang dipilih. Selain menghitung umur, aplikasi ini juga menampilkan hari ulang tahun berikutnya dan peristiwa penting yang terjadi pada tanggal ulang tahun tersebut. 

## Fitur

- **Penghitungan Umur:** Menghitung umur secara detail (tahun, bulan, hari) berdasarkan tanggal lahir yang dimasukkan.
- **Hari Ulang Tahun Berikutnya:** Menampilkan hari dan tanggal ulang tahun berikutnya.
- **Peristiwa Penting:** Mengambil dan menampilkan peristiwa penting yang terjadi pada tanggal ulang tahun dari API eksternal.
- **Penerjemahan:** Menerjemahkan deskripsi peristiwa dari bahasa Inggris ke bahasa Indonesia.

## Prasyarat

Sebelum menjalankan aplikasi ini, pastikan Anda memiliki:

- Java Development Kit (JDK) versi 8 atau lebih baru.
- IDE untuk pengembangan Java seperti IntelliJ IDEA, Eclipse, atau NetBeans.
- Koneksi internet aktif (untuk mengambil data peristiwa dari API).

## Struktur Proyek

Proyek ini terdiri dari dua kelas utama:

1. **PenghitungUmurFrame**
   - Kelas ini bertanggung jawab untuk antarmuka pengguna (UI) dan interaksi dengan pengguna.
   - Menggunakan komponen Swing untuk menampilkan tanggal lahir, umur, dan peristiwa penting.
   - Mengelola event ketika tombol dihitung umur dan keluar ditekan.
   
2. **PenghitungUmurHelper**
   - Kelas ini berisi metode untuk menghitung umur, menentukan hari ulang tahun berikutnya, dan mengambil peristiwa penting dari API.
   - Memiliki metode untuk menerjemahkan deskripsi peristiwa ke dalam bahasa Indonesia.

## Cara Menjalankan

1. Clone repositori ini ke dalam komputer Anda atau unduh sebagai ZIP.
2. Buka proyek di IDE pilihan Anda.
3. Pastikan Anda mengatur JDK yang benar di IDE Anda.
4. Jalankan `PenghitungUmurFrame` untuk memulai aplikasi.

## Penggunaan

1. Pilih tanggal lahir menggunakan pemilih tanggal.
2. Klik tombol **Hitung Umur** untuk mendapatkan umur dan hari ulang tahun berikutnya.
3. Aplikasi akan mengambil dan menampilkan peristiwa penting yang terjadi pada tanggal ulang tahun Anda.
4. Untuk keluar dari aplikasi, klik tombol **Keluar**.


## Demo

![App Screenshot](https://github.com/Rijal0321/AplikasiPenghitungUmur/blob/main/img/Latihan%202%20Demo.gif)

## Pembuat
Latihan 2 - Muhammad Rijal Aditya (2210010148) - Kelas 5C Reguler pagi Banjarmasin

