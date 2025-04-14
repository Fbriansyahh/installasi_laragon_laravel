Dokumentasi Instalasi Laragon & Laravel


##Instalasi Laragon##
1. Download Laragon di https://laragon.org/download/
2. Install Laragon seperti biasa
3. Jalankan Laragon
4. Pastikan Apache & MySQL aktif
5. Buka Terminal di Laragon


##Instalasi Laravel##
1. Buka Terminal di Laragon
2. Cek Composer:
 composer --version
 (Kalau belum ada, install Composer dari https://getcomposer.org/download/)
3. Install Laravel:
composer create-project --prefer-dist laravel/laravel kelase
4. Masuk ke folder project:
 cd nama_project
5. Jalankan server Laravel:
 php artisan serve
6. Buka browser di http://localhost:8000

   
##Upload ke GitHub##
1. Buat repository baru di GitHub
2. Clone repository ke komputer:
 git clone https://github.com/username/nama-repo.git
3. Lakukan commit & push:
 git add .
 git commit -m "add dokumentasi instalasi laragon & laravel"
 git push origin main


Author
- Nama: [Febriansyah]
- Kelas: [IF23E]
- NIM: [23416255201257]
