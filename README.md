# Aplikasi Pengelolaan Data Perkebunan

Anggota Kelompok :
1. Alisya Nisrina Sativa (2209116005)
2. Chandra Perdana Phang (2209116025)

## Deskripsi Project
Aplikasi Pengelolaan Data Perkebunan yang telah kami buat ini merupakan sebuah aplikasi yang bertujuan untuk membantu suatu instansi dalam mengelola data tanaman yang terkait dengan admin, tanaman, riwayat tanam, dan karyawan. Aplikasi ini memiliki dua package utama, yaitu `Database` dan `GUI`.

## Flowchart
![FLOWCHART-fc fix drawio](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/49a1ac0e-def7-4f04-9e54-a55d9594ab10)

## ERD Logical
ERD atau Entity Relationship Diagram merupakan suatu bentuk diagram yang menjelaskan hubungan antar objek-objek data yang mempunyai hubungan antar relasi. ERD digunakan untuk merancang, menggambarkan, dan memvisualisasikan struktur data yang akan digunakan untuk membangun suatu sistem atau aplikasi.
![Logical](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/a32d54ec-4d57-4369-b040-4bdbdc6620be)

## ERD Relational
ERD Relational merupakan turunan ERD logical yang telah dibuat. Melalui visualisasi ini, terlihat dengan jelas informasi mengenai tipe data masing-masing entitas, panjang dari setiap tipe data, serta identifikasi kunci utama (Primary Key) dan kunci asing (Foreign Key) yang menghubungkan tiap entitas.
![Relational_1](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/5ce64d6a-42be-4817-89d3-3032af77ee8f)

## Hierarki Kelas
![FLOWCHART-hirarki drawio](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/bc2bd195-017a-40d5-a9d7-618729f61e17)

## Struktur Project
<img width="204" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/38f08684-5d4f-4c0d-a4ae-42c0b5973aff">

- Packages `GUI ` merupakan packages yang berisi interface dari aplikasi pengelolaan data perkebunan
- Packages `Database` merupakan packages inti dari aplikasi ini. Didalam packages Database berisi 7 entitas utama. Berikut adalah penjelasan singkat dari setiap kelas:
  
    a. `Admin`: Kelas ini berfungsi untuk menyimpan data admin yang bertugas untuk mengelola data-data tanaman yang ada.

  b. `Buah` : Kelas ini merupakan kelas turunan dari kelas tanaman. Kelas ini berfungsi untuk mengelola data pada entitas buah.

  c. `Database` : Kelas ini berfungsi untuk mengelola koneksi ke database dan operasi dasar seperti mengambil data.

  d. `Karyawan` : Kelas ini berfungsi untuk menyimpan dan mengelola data dan informasi mengenai karyawan yang bekerja pada instansi perkebunan ini.

  e. `Sayuran` : Kelas ini merupakan kelas turunan dari kelas tanaman. Kelas ini berfungsi untuk mengelola data pada entitas tanaman.

  f. `Tanaman` : Kelas ini merupakan kelas utama dari entitas sayuran dan buah. Kelas ini berfungsi untuk menyimpan dan mengelola data tanaman pada instansi perkebunan ini.

  g. `Riwayat` : Kelas ini berfungsi untuk menyimpan data riwayat tanam yang telah dilakukan di instansi perkebunan ini.

  ## Penjelasan SourceCode
