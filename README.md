Nama: rafi RIzkullah  
NPM: 2210010288  
Kelas: 5A REG BJB  

![image](https://github.com/user-attachments/assets/6ab1b197-fb61-448a-8288-b0ba539579c3)

![image](https://github.com/user-attachments/assets/65117162-22a6-444a-a60e-519a0855b4c4)

# Penghitung Umur (Age Calculator) - README

Aplikasi ini adalah sebuah program Java sederhana yang digunakan untuk menghitung umur seseorang dan menentukan hari apa ulang tahun berikutnya. Selain itu, aplikasi ini juga mengambil dan menampilkan peristiwa-peristiwa penting yang terjadi pada hari ulang tahun berikutnya.

### Fitur:
- **Perhitungan Umur**: Menghitung umur secara tepat berdasarkan tanggal lahir yang dimasukkan.
- **Ulang Tahun Berikutnya**: Menampilkan tanggal dan hari ulang tahun berikutnya.
- **Peristiwa Penting**: Mengambil dan menampilkan peristiwa-peristiwa penting yang terjadi pada tanggal ulang tahun berikutnya.

---

### Prasyarat:
- **Java Development Kit (JDK)**: Aplikasi ini dibangun menggunakan Java. Pastikan Anda sudah menginstal Java versi 8 atau lebih baru di mesin Anda.
- **Library Eksternal**:
  - **JDateChooser**: Komponen untuk memilih tanggal dari kalender.
  - **JSON.org**: Untuk parsing dan menampilkan peristiwa penting (Anda mungkin perlu menambahkan ini sebagai dependensi).

---

### Cara Menjalankan:
1. **Kompilasi File Java**:
   Gunakan IDE atau editor teks untuk mengompilasi file `.java` yang ada dalam proyek ini.
   
2. **Jalankan Program**:
   Setelah kompilasi selesai, jalankan program untuk membuka antarmuka pengguna grafis (GUI), di mana Anda dapat memasukkan tanggal lahir dan menghitung umur serta detail ulang tahun berikutnya.

---

### Cara Menggunakan:
- **Pilih Tanggal Lahir**: Gunakan komponen kalender untuk memilih tanggal lahir Anda.
- **Hitung Umur**: Klik tombol "Hitung Umur" untuk menghitung umur Anda.
- **Lihat Hari Ulang Tahun Berikutnya**: Setelah menghitung umur, aplikasi akan menampilkan hari ulang tahun berikutnya.
- **Lihat Peristiwa Penting**: Aplikasi ini akan mengambil dan menampilkan peristiwa penting yang terkait dengan tanggal ulang tahun berikutnya. Peristiwa ini diambil secara asinkron dan dapat dilihat di area teks.

---

### Penjelasan Komponen:
1. **PenghitungUmurFrame**: Kelas utama yang berisi antarmuka pengguna dan logika aplikasi.
   - Tombol `Hitung Umur` digunakan untuk memicu perhitungan umur dan pengambilan peristiwa penting.
   - Tombol `Keluar` digunakan untuk menutup aplikasi.
   - Pemilih tanggal memungkinkan pengguna memilih tanggal lahir.
   - Dua field teks menampilkan umur dan detail ulang tahun berikutnya.
   - Area teks menampilkan peristiwa-peristiwa yang diambil terkait dengan tanggal ulang tahun berikutnya.

2. **PenghitungUmurHelper**: Kelas pembantu yang menyediakan fungsi-fungsi untuk:
   - Menghitung umur dari tanggal lahir.
   - Menentukan hari ulang tahun berikutnya.
   - Mengambil peristiwa penting berdasarkan tanggal ulang tahun berikutnya.

---

### Lisensi:
Proyek ini dilisensikan di bawah Lisensi MIT.

---

### Pemecahan Masalah:
- **Tidak ada peristiwa yang ditampilkan**: Pastikan koneksi internet aktif karena aplikasi ini mengambil data secara online.
- **Tanggal tidak valid**: Jika Anda mengalami masalah dengan pemilih tanggal, pastikan lingkungan Java Anda sudah dikonfigurasi dengan benar.

---

### Kontribusi:
Silakan fork repository ini, buka isu, dan ajukan pull request untuk perbaikan!
