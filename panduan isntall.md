Cara Penggunaan :

*----------------------------------------------------------------------------------------------------------------------------*

**❇️Persyaratan :**

⚫ Composer.

⚫ PHP 8.1+ dan MySQL atau XAMPP, Laragon versi 8.1+ dengan mengaktifkan extension -intl dan -gd.

⚫ (Opsional) Kamera/webcam untuk menjalankan qr scanner. Bisa juga menggunakan kamera HP dengan bantuan software DroidCam.



❇️Instalasi :
⚫ Unduh dan impor kode proyek ini ke dalam direktori proyek anda (htdocs).

⚫ Penting ⚠️. Jika belum memiliki file .env, salin/rename file .env.example menjadi .env

⚫ (Opsional) Konfigurasi file .env untuk mengatur parameter seperti koneksi database dan pengaturan lainnya sesuai dengan lingkungan pengembangan Anda.

⚫ Penting ⚠️. Install dependencies yang diperlukan dengan cara menjalankan perintah berikut di terminal:



*composer install*

⚫ Buat database db\_book\_library di phpMyAdmin / mysql

⚫ Penting ⚠️. Jalankan migrasi database untuk membuat struktur tabel yang diperlukan. Ketikkan perintah berikut di terminal:



*php spark migrate --all*

Penting ⚠️. Karena belum memiliki akun admin, untuk mengakses halaman admin, anda memerlukan user/akun dengan level superadmin. Jalankan perintah berikut untuk membuat akun superadmin:

*php spark db:seed SuperAdminSeeder*

💡(Opsional) Isi database dengan data dummy / seeder.
⚫ *php spark db:seed Seeder # semua seeder*

⚫ *php spark db:seed BookSeeder # buku*

⚫ *php spark db:seed MemberSeeder # anggota*

⚫ *php spark db:seed LoanSeeder # peminjaman, pengembalian \& denda*

⚫ Jalankan website
Buka http://localhost:8080

Login dengan kredensial superadmin berikut:

*username : superadmin*

*email    : superadmin@admin.com*

*password : superadmin*

*----------------------------------------------------------------------------------------------------------------------------*

*👇👇👇
link file Sistem-Informasih-Perpustakaan-Unmus-Merauke-dengan-fitur-QR : 

https://drive.google.com/drive/folders/1Ou5y14lMzK9F1ssj7uETC39FsKDq1tIX?usp=sharing

-----------------------------------------------------------------------------------------------------------------------------*









