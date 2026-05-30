Tutorial GitHub dari Awal Sampai Akhir (Lengkap untuk Pemula)
![image](/image/metamedia.jpg)
Universitas Metamedia, Padang
Fakutlas Teknologi Sistem Informasi dan Industri Kreatif
Program Studi Sistem Informasi

Tutorial ini ditujukan untuk mahasiswa yang ingin menggunakan GitHub dari nol hingga mampu mengelola proyek secara profesional.

1. Apa itu GitHub?
   GitHub adalah platform berbasis cloud untuk menyimpan, mengelola, dan berkolaborasi pada kode program menggunakan sistem kontrol versi Git.
   GitHub digunakan untuk:
   1.1 Menyimpan source code
   1.2 Backup project
   1.3 Kolaborasi tim
   1.4 Mencatat perubahan program
   1.5 Portofolio programmer
   1.6 Publikasi proyek open source
   Website resmi:
   GitHub

2. Perbedaan Git dan GitHub
   Git GitHub
   Software Version Control Website penyimpanan repository
   Berjalan di komputer lokal Berjalan di internet
   Mengelola histori perubahan Menyimpan repository online
   Singkatnya:
   Git = Mesin
   GitHub = Garasi

---

3. Membuat Akun GitHub
   Langkah 1
   Buka:
   GitHub Sign Up
   Langkah 2
   Isi:
   • Email
   • Password
   • Username
   Contoh:
   Username : amrinlubis
   Email : mamrinlubis@metamedia.ac.id
   Password : **\*\*\*\***
   Langkah 3
   Verifikasi email.
   Langkah 4
   Login ke GitHub.

4. Mengenal Tampilan GitHub
   Menu utama:
   Dashboard
   Berisi:
   • Repository terbaru
   • Aktivitas
   • Notifikasi
   Repositories
   Tempat penyimpanan project.
   Projects
   Manajemen pekerjaan.
   Issues
   Daftar masalah atau tugas.
   Pull Requests
   Permintaan penggabungan kode.
   Actions
   CI/CD otomatis.
   Settings
   Pengaturan akun dan repository.

5. Install Git
   Download Git:
   Git Download
   Cek Instalasi
   Buka CMD:
   git --version
   Contoh hasil:
   git version 2.50.0

6. Konfigurasi Git
   Setelah instalasi:
   git config --global user.name "Muhammad Amrin Lubis"

git config --global user.email "amrin@gmail.com"
Cek konfigurasi:
git config --list

7. Membuat Repository di GitHub
   Klik:
   New Repository
   Isi:
   Repository Name : belajar-github
   Description : Tutorial GitHub
   Pilih:
   Public
   Centang:
   README.md
   Klik:
   Create Repository

8. Clone Repository
   Clone berarti mengambil repository dari GitHub ke komputer.
   Contoh:
   git clone https://github.com/amrinlubis/belajar-github.git
   Masuk folder:
   cd belajar-github

9. Menambahkan File
Misal membuat:
index.php
Isi:
<?php
echo "Hello GitHub";
?>

10. Status Repository
    Lihat status:
    git status
    Contoh:
    Untracked files:
    index.php

11. Menambahkan File ke Staging Area
    git add index.php
    Atau:
    git add .

12. Commit
    Commit adalah menyimpan perubahan.
    git commit -m "Menambah file index.php"

13. Push ke GitHub
    Kirim ke server GitHub:
    git push origin main

14. Pull dari GitHub
    Mengambil update terbaru:
    git pull origin main

15. Alur Kerja GitHub
    Edit File
    ↓
    git add .
    ↓
    git commit
    ↓
    git push
    ↓
    GitHub

16. Membuat Branch
    Branch digunakan untuk pengembangan fitur.
    Buat branch:
    git branch fitur-login
    Pindah branch:
    git checkout fitur-login
    Atau:
    git switch fitur-login

17. Merge Branch
    Kembali ke main:
    git checkout main
    Merge:
    git merge fitur-login

18. Pull Request (PR)
    Pull Request digunakan untuk meminta penggabungan kode.
    Alur:
    Branch Baru
    ↓
    Push
    ↓
    Create Pull Request
    ↓
    Review
    ↓
    Merge

19. Fork Repository
    Fork digunakan untuk menyalin repository orang lain.
    Klik:
    Fork
    Repository akan masuk ke akun Anda.

20. Issue
    Issue digunakan untuk:
    • Bug
    • Permintaan fitur
    • Dokumentasi
    Contoh:
    Judul:
    Login gagal ketika password kosong

21. GitHub Pages
    Digunakan untuk hosting website gratis.
    Masuk:
    Settings
    → Pages
    Pilih:
    Deploy from branch
    Pilih:
    main
    Website akan aktif di:
    https://username.github.io/repository

22. File .gitignore
    Digunakan untuk mengabaikan file tertentu.
    Contoh:
    node_modules/
    vendor/
    .env
    Buat file:
    .gitignore
    Isi:
    .env
    vendor/
    node_modules/

23. README.md
    README adalah dokumentasi proyek.
    Contoh:

# Sistem Informasi Koperasi

Aplikasi berbasis Laravel

## Fitur

- Login
- Simpan Pinjam
- Laporan

24. GitHub Actions
    Digunakan untuk otomatisasi:
    • Testing
    • Build
    • Deploy
    Contoh file:
    .github/workflows/main.yml

---

25. SSH GitHub
    Lebih aman daripada username/password.
    Generate SSH:
    ssh-keygen -t ed25519 -C "email@gmail.com"
    Lihat key:
    cat ~/.ssh/id_ed25519.pub
    Tambahkan ke:
    GitHub SSH Settings

26. Repository Private
    Digunakan untuk:
    • Skripsi
    • Penelitian
    • Proyek perusahaan
    Pilih:
    Private
    Saat membuat repository.

27. Struktur Repository Profesional
    project/
    │
    ├── src/
    ├── docs/
    ├── tests/
    ├── assets/
    ├── README.md
    ├── LICENSE
    └── .gitignore

28. GitHub untuk Dosen
    GitHub dapat digunakan untuk:
    • Menyimpan materi kuliah
    • Menyimpan source code praktikum
    • Kolaborasi penelitian
    • Portofolio akademik
    • Publikasi modul pembelajaran

29. GitHub untuk Mahasiswa
    GitHub dapat digunakan untuk:
    • Tugas kuliah
    • Skripsi
    • Portofolio kerja
    • Belajar Open Source

---

30. Perintah Git yang Paling Sering Digunakan
    git init

git clone

git status

git add .

git commit -m "pesan"

git push

git pull

git branch

git checkout

git switch

git merge

git log

---

Ringkasan Alur GitHub

1. Buat akun GitHub
2. Install Git
3. Konfigurasi Git
4. Buat Repository
5. Clone Repository
6. Edit File
7. git add .
8. git commit
9. git push
10. Kolaborasi menggunakan Branch
11. Pull Request
12. Merge
13. Deploy dengan GitHub Pages
