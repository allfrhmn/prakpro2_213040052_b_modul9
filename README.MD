# Tugas Modul 9 - Studi Kasus 2

- Nama : Allfiandi Rahman
- NPM : 213040052
- Kelas : B
- Mata Kuliah : Praktikum Pemrograman 2

## Penjelasan Mengenai Studi Kasus Kedua

Aplikasi ini adalah sebuah program Java yang dibuat untuk mencatat dan mengelola biodata seseorang. Biodata yang dicatat meliputi nama, jenis kelamin, nomor hp, dan alamat. Aplikasi ini menyediakan fitur dasar seperti menyimpan, mengubah, menghapus, dan memperbarui biodata. Selain itu, aplikasi juga mendukung penyimpanan data ke dalam file teks (txt).

## Alat Yang Digunakan

- Bahasa Pemrograman: _**Java**_
- Versi : _**JDK 21**_
- Aplikasi : _**Laragon dan Apache Netbeans IDE 19**_
- Database: _**MySQL**_
- Library: _**JDBC**_

## Fitur Biodata di Java

1. **Input Data Biodata:** Aplikasi ini memungkinkan pengguna untuk memasukkan biodata, termasuk nama, jenis kelamin, nomor hp, dan alamat.

2. **Validasi Input:** Data yang dimasukkan harus terisi semua. Jika ada kolom yang kosong atau belum diisi, aplikasi akan menampilkan peringatan untuk mengisi inputan yang kosong tersebut.

3. **Konfirmasi Sebelum Menyimpan:** Sebelum data disimpan, aplikasi akan meminta konfirmasi dari pengguna untuk memastikan bahwa mereka benar-benar ingin menyimpan data tersebut.

4. **Penyimpanan Data dalam JTable:** Data biodata yang dimasukkan akan ditampilkan dalam JTable sehingga pengguna dapat dengan mudah melihat dan mengelola data yang telah dimasukkan.

5. **Edit Data:** Pengguna memiliki kemampuan untuk mengedit data yang telah disimpan di tabel.

6. **Hapus Data:** Pengguna juga dapat menghapus data yang telah disimpan di tabel.

7. **Simpan File:** Pengguna juga bisa menyimpan data melalui format apapun.

8. **Konfirmasi Sebelum Keluar:** Aplikasi ini memberikan konfirmasi kepada pengguna sebelum keluar dari aplikasi, baik melalui tombol "X" di jendela aplikasi maupun melalui opsi keluar.

## Panduan Menggunakan Aplikasi Biodata di Java 

Untuk menggunakan aplikasi ini, Anda dapat mengikuti langkah-langkah berikut:

1. Buatlah basis data yang sesuai namanya dengan basis data ini di MySQL Anda.
2. Import basis data dan pastikan port Anda di MySQL harus disesuaikan seperti di kelas ```MySqlConnection.java``` lewat package-nya ```db```
3. Jalankan aplikasi biodata.
4. Masukkan biodata lengkap, termasuk nama, jenis kelamin, nomor hp, dan alamat.
5. Pastikan semua kolom telah diisi dengan benar.
6. Klik tombol **"Simpan"** untuk menyimpan data biodata. Anda akan diminta konfirmasi sebelum data disimpan.
7. Data biodata akan ditampilkan dalam JTable.
8. Jika Anda ingin mengubah data, pilih baris yang ingin diubah, lalu klik tombol **"Ubah"** dan jangan lupa tekan tombol **"Update"** jika anda benar-benar mengubahnya dengan baik.
9. Jika Anda ingin menghapus data, pilih baris yang ingin dihapus, lalu klik tombol **"Hapus"**.
10. Untuk menyimpan data ke dalam file teks, klik tombol **"Simpan Ke TXT"**.
11. Ketika Anda ingin keluar dari aplikasi, Anda akan diminta konfirmasi sebelum keluar.
