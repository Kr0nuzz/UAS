# KeuanganHarian

## Deskripsi
**KeuanganHarian** adalah aplikasi sederhana berbasis C++ yang dirancang untuk membantu pengguna mencatat dan menghitung pengeluaran harian. Aplikasi ini memungkinkan pengguna untuk mengelola saldo awal, menambahkan pengeluaran, melihat total pengeluaran, serta mengecek sisa saldo.

## Fitur Utama
1. **Tambah Pengeluaran**
   - Pengguna dapat menambahkan pengeluaran dengan kategori dan jumlah tertentu.
   - Saldo akan berkurang sesuai dengan jumlah pengeluaran yang dimasukkan.

2. **Tampilkan Total Pengeluaran**
   - Aplikasi menampilkan total semua pengeluaran yang telah dicatat sejauh ini.

3. **Tampilkan Sisa Saldo**
   - Pengguna dapat mengecek sisa saldo setelah semua pengeluaran yang tercatat.

4. **Keluar dari Aplikasi**
   - Menghentikan aplikasi dengan pesan perpisahan.

## Spesifikasi Teknis
- **Bahasa Pemrograman**: C++
- **Metode Input**: Menggunakan `cin` dan `getline` untuk menerima input dari pengguna.
- **Pengolahan Data**: Penggunaan vektor (`vector`) untuk menyimpan daftar pengeluaran.
- **Pengulangan**: Menggunakan `do-while` untuk menampilkan menu berulang kali hingga pengguna memilih keluar.
- **Pemilihan**: Menggunakan `switch-case` untuk menangani berbagai pilihan menu.

## Cara Menggunakan Aplikasi
1. Jalankan program.
2. Masukkan saldo awal sesuai dengan keinginan.
3. Pilih opsi dari menu yang ditampilkan:
   - **1**: Tambah pengeluaran (masukkan kategori dan jumlah pengeluaran).
   - **2**: Lihat total pengeluaran sejauh ini.
   - **3**: Lihat sisa saldo saat ini.
   - **4**: Keluar dari aplikasi.
4. Ulangi proses hingga selesai.

## Contoh Tampilan Menu
```
Menu Utama:
1. Tambah Pengeluaran
2. Tampilkan Total Pengeluaran
3. Tampilkan Sisa Saldo
4. Keluar dari Aplikasi
Pilih menu (1-4):
```

## Struktur Kode
- **main()**: Fungsi utama yang menjalankan program dan menampilkan menu utama.
- **tambahPengeluaran()**: Meminta input kategori dan jumlah pengeluaran, lalu memperbarui saldo.
- **tampilkanTotalPengeluaran()**: Menampilkan jumlah total pengeluaran.
- **tampilkanSisaSaldo()**: Menampilkan sisa saldo setelah pengeluaran.

## Catatan
- Pastikan untuk memasukkan saldo awal yang cukup sebelum menambahkan pengeluaran.
- Aplikasi ini hanya menyimpan data selama sesi berlangsung. Data akan hilang setelah program ditutup.


# Program Pengelolaan Data Mahasiswa

## Deskripsi Program
Program ini adalah aplikasi C++ yang dirancang untuk membantu mengelola data mahasiswa, termasuk NIM, Nama, dan Nilai Akhir. Program menyediakan berbagai fitur seperti pencarian, pengurutan, dan akses berkas untuk menyimpan serta membaca data mahasiswa.

## Fitur Utama
1. **Tambah Data Mahasiswa**
   - Pengguna dapat menambahkan data mahasiswa dengan memasukkan NIM, Nama, dan Nilai Akhir.

2. **Tampilkan Semua Data**
   - Menampilkan semua data mahasiswa yang telah dimasukkan.

3. **Cari Data Mahasiswa**
   - Melakukan pencarian mahasiswa berdasarkan NIM menggunakan algoritma pencarian linear.

4. **Urutkan Data Mahasiswa**
   - Mengurutkan data mahasiswa berdasarkan Nilai Akhir dalam urutan menurun (descending) menggunakan algoritma Bubble Sort.

5. **Simpan Data ke Berkas**
   - Menyimpan data mahasiswa ke dalam file teks dengan format:
     ```
     NIM, Nama, Nilai Akhir
     ```
     Contoh:
     ```
     12345, Budi, 85.0
     67890, Ani, 90.5
     ```

6. **Baca Data dari Berkas**
   - Membaca data mahasiswa dari file teks dan memuatnya kembali ke dalam program.

7. **Keluar dari Program**
   - Menghentikan eksekusi program dan keluar dari menu utama.

## Cara Menggunakan Program
1. Jalankan program menggunakan compiler C++.
2. Pada menu utama, pilih opsi sesuai kebutuhan:
   - `1` untuk menambahkan data mahasiswa.
   - `2` untuk menampilkan semua data mahasiswa.
   - `3` untuk mencari mahasiswa berdasarkan NIM.
   - `4` untuk mengurutkan data mahasiswa.
   - `5` untuk menyimpan data ke dalam file.
   - `6` untuk membaca data dari file.
   - `7` untuk keluar dari program.

## Teknologi yang Digunakan
- **Bahasa Pemrograman:** C++
- **Algoritma Pencarian:** Linear Search
- **Algoritma Pengurutan:** Bubble Sort
- **Akses Berkas:** ifstream, ofstream

## Struktur File
- **File utama:** `main.cpp` (Berisi seluruh logika program)
- **File data:** `data_mahasiswa.txt` (Menyimpan data mahasiswa dalam format teks)

## Contoh Eksekusi
```
Menu Utama:
1. Tambah Data Mahasiswa
2. Tampilkan Semua Data
3. Cari Data Mahasiswa
4. Urutkan Data
5. Simpan Data ke Berkas
6. Baca Data dari Berkas
7. Keluar
Pilih menu (1-7):
```

## Catatan Tambahan
- Pastikan file `data_mahasiswa.txt` berada di direktori yang sama dengan program saat melakukan pembacaan dari berkas.
- Program ini mendukung penambahan data mahasiswa secara bertahap dan akan menimpa file lama saat menyimpan data baru.



