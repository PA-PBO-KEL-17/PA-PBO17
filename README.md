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
`Admin`

<img width="736" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/175a593d-0b35-4d81-89dd-0134ffc85f1f">
<img width="728" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/76d66a3d-eff0-4122-9cae-979e8a90b344">
<img width="625" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/7d52d941-030c-4d93-b1f1-42b3f67e33e3">
<img width="749" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/a4a870e8-356d-4d10-95f0-1e181ad8879a">

`Buah` 

<img width="793" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/f7bab74f-2f34-43c8-bbb9-6269a546a10e">
<img width="524" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/b5b48869-f985-4f0d-9427-96483dea27b8">
<img width="796" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/f6e1f2f4-b5cc-4f24-9bed-2f6bb3c0a1e0">
<img width="793" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/ec349d80-ee10-4f8f-985c-16c33d76ca77">
<img width="793" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/92a1c1aa-de59-45a0-a3ff-27d4f36cf171">
<img width="792" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/a7d708eb-525a-49c5-8cc5-3061a960ffc0">

`Karyawan`

<img width="525" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/3c1646cc-101b-4d0d-9c27-76d2eb8b8ffd">
<img width="788" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/9c717093-69ea-459a-98a5-7253cefeeb56">
<img width="490" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/24efc227-e271-4376-8c79-3f9831a33803">
<img width="778" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/1c5035d4-750a-445a-900f-6a58af584f02">

`Sayuran`

<img width="786" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/ae1048a7-399e-4ef9-a5ab-2d3237822e73">
<img width="587" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/74e93b0d-1d42-4845-a772-cb5aeb48b613">
<img width="789" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/f5d5d8b2-a846-4c37-b4eb-bfdc44312eb4">
<img width="797" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/67ec6eda-de37-4878-b39b-c88906dcc1eb">
<img width="799" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/3525a22c-609f-4248-a281-2a7ce7566ae8">
<img width="794" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/31f9b572-b547-478a-a9c2-d70bfd002fdf">

`Tanaman`

<img width="533" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/d9ec168a-0888-4944-9dd4-bc51cf26897a">
<img width="517" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/8b41ec5e-f26a-4483-aabf-00ca477c6961">
<img width="589" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/86454016-c570-4e8b-8290-8d4a8ef67d7f">
<img width="799" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/7a084eb1-6198-4516-8e2d-74894f077508">
<img width="790" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/34fc734f-0e74-433b-a12d-f355e20d57d8">

`Riwayat Tanam`

<img width="636" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/b0477ff5-f507-4094-842b-16fb772778e5">
<img width="493" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/f2b22c44-2c77-4372-83bc-9752bfec7714">
<img width="773" alt="image" src="https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/4abbbada-ea44-4892-ba81-f725e708b5d0">

## Penjelasan Output
`Menu Login`

Saat memulai aplikasi, user akan diminta untuk login. Disini terdapat 2 role, yaitu admin dan karyawan

![WhatsApp Image 2023-11-04 at 02 30 01_5639ab10](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/638ae90c-5ed2-4606-be0c-421c64bdbdb4)

`Login Admin`

Jika user memilih login sebagai admin, user akan diminta untuk memasukkan name dan password yang telah di tetapkan.

![image](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/21d8821c-72de-4447-89cd-ad83bd03ff6d)

Apabila user berhasil login maka akan muncul notifikasi seperti gambar dibawah ini

![WhatsApp Image 2023-11-04 at 02 32 04_178985e0](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/c4e44640-0fa8-4d61-8b65-6060ea5cb042)

`Menu Admin`

Berikut adalah menu untuk admin

![WhatsApp Image 2023-11-04 at 02 32 19_600bb02b](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/bb87325d-4608-41d9-bee9-88916e8f2724)

`Menu Create`

Apabila user memilih menu create maka user harus menginput seluruh inputan yang tertera.

![WhatsApp Image 2023-11-04 at 02 32 31_042f8e0e](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/28b258fc-42a8-4f4e-8b0d-267ee34aa5c9)

Berikut adalah notifikasi apabila telah berhasil membuat tanaman

![image](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/27cbaebb-1449-4ba4-bc5b-acf93eb53a05)

`Menu Show Data`

Apabila user memilih menu data, maka user dapat memilih 2 menu yang tertera yakni menu data tanaman dan menu riwayat tanam

![WhatsApp Image 2023-11-04 at 02 34 56_8432169b](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/65c6de4d-fbec-4ad3-9172-e84bbabff445)

Apabila user memilih data tanaman maka tampilannya akan seperti di gambar bawah ini

![WhatsApp Image 2023-11-04 at 02 35 06_375a5d8b](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/45429ae8-4d84-46a8-96d2-258e44c95b8b)

Apabila user memilih riwayat tanam maka tampilannya akan seperti di gambar bawah ini

![WhatsApp Image 2023-11-04 at 02 37 10_6dd64b21](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/a57f7dd6-a7e2-403e-be59-e5ad401e0d08)

`Menu Update Data`

Apabila user ingin mengupdate data, user harus menginputkan id tanaman yang ingin di update dan mengisi setiap inputannya

![image](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/ee9189d1-5c99-45fc-a9aa-e05840d4eb32)

`Menu Delete Data`

Apabila user ingin mendelete data, user dapat mengklik baris yang ingin di delete lalu klik tombol delete yang tertera

![image](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/ce10e38e-17d4-4789-a3b9-cc567dff76d0)

`Login Karyawan`

Jika user memilih login sebagai karyawan, user akan diminta untuk memasukkan name dan password yang telah di tetapkan.

![image](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/9b2d1fca-e0d3-4e93-8384-3b80801e23d4)

`Menu Karyawan`

Berikut adalah menu untuk karyawan, yaitu menu show data yang berisi menu data tanaman dan data riwayat tanam

![WhatsApp Image 2023-11-04 at 03 23 23_e651f1fe](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/41cfc210-d5bb-4699-b536-29d8e3f5aa80)

`Menu Data Tanaman`

Apabila user memilih data tanaman maka user dapat mengklik salah satu data yang ingin dipilih. Untuk bisa melihat data tanaman, user dapat mengklik tombol "visit:

![WhatsApp Image 2023-11-04 at 03 24 35_437f37a0](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/9163fddb-00ab-4271-9885-b8e44bd0a927)

Apabila user memilih riwayat tanam maka tampilannya akan seperti digambar ini.

![WhatsApp Image 2023-11-04 at 03 23 57_863259a6](https://github.com/PA-PBO-KEL-17/PA-PBO17/assets/122090377/cb82ec54-86fa-48d0-9f51-5bc6dbc5a1ca)

Apabila user mengklik "logout" maka user akan keluar dari program.

Sekian terima kasih
