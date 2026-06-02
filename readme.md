Tutorial GitHub dari Awal Sampai Akhir (Lengkap untuk Pemula)
![image](/image/metamedia.jpg)
<br>
Universitas Metamedia, Padang
Fakutlas Teknologi Sistem Informasi dan Industri Kreatif
Program Studi Sistem Informasi
<br>
Tutorial ini ditujukan untuk mahasiswa yang ingin menggunakan GitHub dari nol hingga mampu mengelola proyek secara profesional.
<br>

1. Apa itu GitHub?
   GitHub adalah platform berbasis cloud untuk menyimpan, mengelola, dan berkolaborasi pada kode program menggunakan sistem kontrol versi Git.
   GitHub digunakan untuk: <br>
   1.1 Menyimpan source code <br>
   1.2 Backup project <br>
   1.3 Kolaborasi tim <br>
   1.4 Mencatat perubahan program <br>
   1.5 Portofolio programmer <br>
   1.6 Publikasi proyek open source <br>
   Website resmi: <br>
   GitHub
   <br>
2. Perbedaan Git dan GitHub
   Git GitHub
   Software Version Control Website penyimpanan repository
   Berjalan di komputer lokal Berjalan di internet
   Mengelola histori perubahan Menyimpan repository online
   Singkatnya:
   Git = Mesin
   GitHub = Garasi

3. Membuat Akun GitHub <br>
   Langkah 1
   Buka:
   GitHub Sign Up <br>
   Langkah 2
   Isi:
   • Email
   • Password
   • Username
   Contoh:
   Username : amrinlubis
   Email : mamrinlubis@metamedia.ac.id
   Password : **\*\*\*\*** <br>
   Langkah 3
   Verifikasi email. <br>
   Langkah 4
   Login ke GitHub.

4. Mengenal Tampilan GitHub <br>
   Menu utama: <br>
   4.1 Dashboard <br>
   Berisi:
   • Repository terbaru
   • Aktivitas
   • Notifikasi<br>
   4.2 Repositories <br>
   Tempat penyimpanan project. <br>
   4.3 Projects <br>
   Manajemen pekerjaan. <br>
   4.4 Issues <br>
   Daftar masalah atau tugas.
   4.5 Pull Requests <br>
   Permintaan penggabungan kode. <br>
   4.6 Actions <br>
   CI/CD otomatis. <br>
   4.7 Settings <br>
   Pengaturan akun dan repository.
   <br>
5. Install Git <br>
   Download Git:
   Git Download
   Cek Instalasi
   Buka CMD:
   git --version
   Contoh hasil:
   git version 2.50.0
   <br>
6. Konfigurasi Git <br>
   Setelah instalasi:
   git config --global user.name "Muhammad Amrin Lubis"

git config --global user.email "mamrinlubis@metamedia.ac.id"
Cek konfigurasi:
git config --list
<br> 7. Membuat Repository di GitHub <br>
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
<br> 8. Clone Repository <br>
Clone berarti mengambil repository dari GitHub ke komputer.
Contoh:
git clone https://github.com/amrinlubis/belajar-github.git
Masuk folder:
cd belajar-github
<br> 9. Menambahkan File <br>
Misal membuat:
index.php
Isi:

<?php
echo "Hello GitHub";
?>
<br>
10. Status Repository<br>
    Lihat status:
    git status
    Contoh:
    Untracked files:
    index.php
<br>
11. Menambahkan File ke Staging Area<br>
    git add index.php
    Atau:
    git add .
<br>
12. Commit <br>
    Commit adalah menyimpan perubahan.
    git commit -m "Menambah file index.php"
<br>
13. Push ke GitHub<br>
    Kirim ke server GitHub:
    git push origin main
<br>
14. Pull dari GitHub<br>
    Mengambil update terbaru:
    git pull origin main

15. Alur Kerja GitHub<br>
    <br>
    Edit File
    ↓
    git add .
    ↓
    git commit
    ↓
    git push
    ↓
    GitHub
    <br>
16. Membuat Branch <br>
    Branch digunakan untuk pengembangan fitur.
    Buat branch:
    git branch fitur-login
    Pindah branch:
    git checkout fitur-login
    Atau:
    git switch fitur-login
    <br>
17. Merge Branch<br>
    Kembali ke main:
    git checkout main
    Merge:
    git merge fitur-login
    <br>
18. Pull Request (PR)<br>
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
    <br>
19. Fork Repository<br>
    Fork digunakan untuk menyalin repository orang lain.
    Klik:
    Fork
    Repository akan masuk ke akun Anda.
    <br>
20. Issue<br>
    Issue digunakan untuk:
    • Bug
    • Permintaan fitur
    • Dokumentasi
    Contoh:
    Judul:
    Login gagal ketika password kosong
    <br>
21. GitHub Pages <br>
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
    <br>
22. File .gitignore<br>
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
    <br>
23. README.md<br>
    README adalah dokumentasi proyek.
    Contoh:

# Sistem Informasi Koperasi

Aplikasi berbasis Laravel

## Fitur

- Login
- Simpan Pinjam
- Laporan
  <br>

24. GitHub Actions<br>
    Digunakan untuk otomatisasi:
    • Testing
    • Build
    • Deploy
    Contoh file:
    .github/workflows/main.yml
    <br>
25. SSH GitHub<br>
    Lebih aman daripada username/password.
    Generate SSH:
    ssh-keygen -t ed25519 -C "email@gmail.com"
    Lihat key:
    cat ~/.ssh/id_ed25519.pub
    Tambahkan ke:
    GitHub SSH Settings
    <br>
26. Repository Private<br>
    Digunakan untuk:
    • Skripsi
    • Penelitian
    • Proyek perusahaan
    Pilih:
    Private
    Saat membuat repository.
    <br>
27. Struktur Repository Profesional
    <br>
    project/<br>
    │<br>
    ├── src/<br>
    ├── docs/<br>
    ├── tests/<br>
    ├── assets/<br>
    ├── README.md<br>
    ├── LICENSE<br>
    └── .gitignore<br>
    <br>
28. GitHub untuk Dosen<br>
    GitHub dapat digunakan untuk:
    • Menyimpan materi kuliah
    • Menyimpan source code praktikum
    • Kolaborasi penelitian
    • Portofolio akademik
    • Publikasi modul pembelajaran
    <br>
29. GitHub untuk Mahasiswa<br>
    GitHub dapat digunakan untuk:
    • Tugas kuliah
    • Skripsi
    • Portofolio kerja
    • Belajar Open Source

<br>

30. Perintah Git yang Paling Sering Digunakan<br>
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
<br>
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
