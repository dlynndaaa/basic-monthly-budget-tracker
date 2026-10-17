# 💰 Monthly Budget Tracker

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-Terminal-4D4D4D?style=for-the-badge&logo=windows-terminal&logoColor=white)

Sebuah program CLI (Command Line Interface) sederhana berbasis C++ untuk melacak dan mengelola keuangan bulanan. Program ini membantu mencatat detail pemasukan, pengeluaran, alokasi tabungan, serta mengkalkulasi ringkasan akhir untuk mengetahui sisa dana (saldo) di akhir bulan.

## 📸 Screenshot Output
<img width="1920" height="3015" alt="outputBasicMonthlyBudgetTracker" src="https://github.com/user-attachments/assets/1f73620e-2292-4fd1-a74a-226e57739e67" />


## 🚀 Fitur Utama
- **Pencatatan Pemasukan (Income):** Mendata berbagai sumber pemasukan beserta nominalnya.
- **Pencatatan Pengeluaran (Expenses):** Melacak rincian pengeluaran bulanan (transportasi, makan, kebutuhan pribadi, dll).
- **Pencatatan Tabungan (Savings):** Mengalokasikan dana ke berbagai pos tabungan.
- **Ringkasan (Summary):** Menghitung secara otomatis kalkulasi `Total Income`, `Total Expenses`, `Total Tabungan`, dan `Total Left` (sisa uang).
- **Sistem Evaluasi (Notes):** Memberikan pesan otomatis di akhir program berdasarkan status sisa uang (apakah surplus atau defisit).

## 🛠️ Konsep Pemrograman yang Digunakan
Program ini dibangun menggunakan beberapa konsep dasar struktur data dan kontrol alur pada C++:
- **Struct:** Digunakan untuk mengelompokkan entitas data (nomor, tanggal, deskripsi, jumlah) pada tabel pemasukan, pengeluaran, dan tabungan.
- **Array:** Digunakan untuk menyimpan sekumpulan *string* seperti *header* tabel dan judul ringkasan.
- **Function / Modularitas:** Pemisahan UI/tampilan seperti `beranda()`, `headTable()`, dan `judulSummary()` agar kode lebih bersih dan mudah dibaca.
- **Control Flow:** Menggunakan perulangan `do-while` untuk mengulang program sesuai keinginan pengguna, dan `if-else` untuk logika validasi akhir.
- **I/O Manipulation:** Menggunakan `iomanip` (`setw`) untuk merapikan spasi agar output tabel presisi di console.

## 💻 Cara Menjalankan Program (via CMD Windows)

1. Pastikan compiler C++ (MinGW/MSYS2) sudah terinstal dan terdaftar di sistem.
2. *Clone* repositori ini ke lokal:
   ```bash
   git clone https://github.com/dlynndaaa/proyek-uas-s1.git
   
## 🚀 Fitur Utama
- **Pencatatan Pemasukan (Income):** Mendata berbagai sumber pemasukan beserta nominalnya.
- **Pencatatan Pengeluaran (Expenses):** Melacak rincian pengeluaran bulanan (transportasi, makan, kebutuhan pribadi, dll).
- **Pencatatan Tabungan (Savings):** Mengalokasikan dana ke berbagai pos tabungan.
- **Ringkasan (Summary):** Menghitung secara otomatis kalkulasi `Total Income`, `Total Expenses`, `Total Tabungan`, dan `Total Left` (sisa uang).
- **Sistem Evaluasi (Notes):** Memberikan pesan otomatis di akhir program berdasarkan status sisa uang (apakah surplus atau defisit).

## 🛠️ Konsep Pemrograman yang Digunakan
Program ini dibangun menggunakan beberapa konsep dasar struktur data dan kontrol alur pada C++:
- **Struct:** Digunakan untuk mengelompokkan entitas data (nomor, tanggal, deskripsi, jumlah) pada tabel pemasukan, pengeluaran, dan tabungan.
- **Array:** Digunakan untuk menyimpan sekumpulan *string* seperti *header* tabel dan judul ringkasan.
- **Function / Modularitas:** Pemisahan UI/tampilan seperti `beranda()`, `headTable()`, dan `judulSummary()` agar kode lebih bersih dan mudah dibaca.
- **Control Flow:** Menggunakan perulangan `do-while` untuk mengulang program sesuai keinginan pengguna, dan `if-else` untuk logika validasi akhir.
- **I/O Manipulation:** Menggunakan `iomanip` (`setw`) untuk merapikan spasi agar output tabel presisi di console.

## 💻 Cara Menjalankan Program (via CMD Windows)

1. Pastikan compiler C++ (MinGW/MSYS2) sudah terinstal dan terdaftar di sistem.
2. *Clone* repositori ini ke lokal:
   ```bash
   git clone https://github.com/dlynndaaa/proyek-uas-s1.git
3. Buka folder repositori tersebut, lalu buka terminal/CMD.
4. Compile file C++:
   ```bash
   g++ MonthlyBudgetTracker-ProyekUAS-DelindaMegaPutri-TI-1A.cpp -o budget
5. Jalankan program hasil *compile*:
   ```bash
   budget

## 👤 Author
**Delinda Mega Putri**
- 🎓 Teknik Informatika, Universitas Muhammadiyah Sukabumi
- 💼 [LinkedIn](https://www.linkedin.com/in/dlnmgp)
- 📧 Email: delindamegaputri123@gmail.com
