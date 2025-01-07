##Laporan Minggu Ketiga

#Deskripsi Proyek
Web administrasi sekolah yang dirancang oleh tim kami digunakan untuk mengelola suatu data sekolah baik terdiri dari data siswa, data guru, data pembayaran SPP maupun jadwal pelajaran guru atau siswa. Sistem ini ditujukan untuk mempermudan pihak sekolah dalam mengelola data administrasi sekolah serta meningkatkan efektivitas dan efesiensi data yang ada. Pada sistem ini  juga memungkinkan sekolah untuk meminimalisir kesalahan data yang ada dikarenakan terdapat fitur CRUD dan fitur interaktif lainnya yang mudah dan membantu mengolah data dengan baik dan benar.Web ini juga disajikan dalam tampilan yang menarik serta responsif untuk berbagai perangkat yang digunakan 

##Cara Instalasi dan penggunaan

A. Cara Instalasi
  1. Salin link Github berikut di browser :
  2. Jika sudah masuk pada laman Github yang dituju klik menu <> Code lalu pilih HTTPS dan download Zip tunggu hingga folder administrasi sekolah terunduh jika sudah ekstrak folder tersebut.
  3. Step selanjutnya cari folder xampp lalu pilih folder htdocs kemudian pindahkan folder administrasi sekolah yang sudah di ekstrak ke dalam folder htdocs
  4. Buka aplikasi xampp nyalakan atau start apache dan mysql lalu klik admin mysql
  5. Jika sudah buat database baru dengan judul sekolah database kemudian pilih menu import pada bagian choose file klik lalu buka folder xampp -> folder htdocs -> administrasi sekolah kemudian pilih folder database dan klik sekolah database.sql (File sekolah_database.sql inilah yang akan diimport dan digunakan) lalu import file tersebut secara otomatis input database akan muncul di sistem.
  6. Next buka web browser lalu ketika localhost/administrasi_sekolah/ jika tautan tersebut menuju pada website maka web sepenuhnya dapat digunakan
B. Cara Penggunaan
   1. Apabila instalasi yang dilakukan sudah selesai buka web browser lalu ketikkan localhost/administrasi_sekolah/ maka akan muncul tampilan dari web administrasi yang sudah dirancang
   2. Pada menu login masukkan username dan password yang sudah diatur berikut username dan passworrd yang sudah diinputkan :             Username : Cap Kaki 3                                                                                                              Password : 1234                                                                                                                 Selanjutnya akan muncul tampilan beranda yang memiliki berbagai menu seperti :  Menu Utama yang berisi data siswa data guru, pembayaran spp, dan jadwal pelajaran list admin : Tempat untuk mengatur username dan password (Tanda panah -> (logout) : untuk keluar dari web
   3. Next step pilih menu utama dan pilih menu yang dibutuhkan pada setiap fitur menu terdapat fitur berikut :                           Tambah data : Untuk menambahkan atau menginputkan data baru                                                                           Edit data : Untuk mengubah atau mengedit data yang sudah ada apabila terjadi kesalahan atau perubahan data                                Delete : Fitur ini berfungsi untuk menghapus data yang salah dan tidak diperlukan                                                         Cetak : Fitur ini diperuntukkan ketika admin ingin mencetak data dari sistem baik data siswa guru atau yang lainnya
   4. Jika sudah selesai klik tanda panah yang di ujung kanan atas untuk logout dari sitem web

## STRUKTUR FILE PROYEK

Pada file project Web Administrasi yang kami bangun menggunakan SQL dengan struktur folder sebagai berikut :

  1. Pada folder administrasi sekolah terdapat 3 folder yaitu asset, database, dan script
  2. Folder asset dalam folder ini terdapat 2 file yaitu css dan img
  3. Folder Database terdapat file dengan nama sekolah_database.sql
  4. Folder Script dalam folder ini terdapat File Login, Data Siswa, Data Guru, Pembayaran SPP, dan Jadwal Pelajaran
      

    

      
  
     
