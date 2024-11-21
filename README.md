## Apa itu E-Sekolah?
Dalam dunia pendidikan kehadiran akan situs website akan sangat membantu diantarnya sebagai sarana untuk promosi, penyampaian informasi, instansi akan lebih professional serta masih banyak lagi manfaat yang dapat diperoleh bagi instansi pendidikan ketika menggunakan website. Dalam rangka digitalisasi untuk pendidikan E-Sekolah hadir untuk menjawab permasalahan tersebut. 

## Fitur E-Sekolah?
Berikut beberapa fitur yang ada di dalam E-Sekolah 
- Manajemen Artikel Sekolah
- Manajemen Fasilitas Sekolah
- Manajemen Jurusan Sekolah
- Manajemen Agenda Sekolah
- Manajemen Tentang Sekolah
- Dan masih banyak lagi 

Oleh karena itu source code website ini sangat cocok digunakan untuk instansi pendidikan mulai dari tingkat SD, SMP, SMA / SMK

## Requirements
- Sudah terinstall composer
- Sudah terinstall XAMPP

## Cara Menggunakan E-Sekolah
- Langkah pertama silahkan clone repository ini, kemudian jangan lupa di beri star
- Selanjutnya memasang semua dependensi project menggunakan perintah 
```dark
composer install
```
- Jika Mengalami kegagalan coba untuk melakukan update
```
composer update
```
- Langkah selanjutnya adalah mengenerate file env example / atau simplenya meng copy file env example menggunakan perintah
```
cp .env.example .env
```
Maka Anda akan mendapati file .env seperti berikut<br>

- Kemudian lakukan generate key, menggunakan perintah
```
php artisan key:generate
```
- Kemudian set up database terlebih dahulu di phpmyadmin Anda

- Kemudian lakukan migrate database menggunakan perintah
```
php artisan migrate
```
- Terakhir lakukan seed database menggunakan perintah
```
php artisan db:seed
```
## URL LOGIN
- tinggal tambah /login
- email : admin@sekolah.com
- passoword : admin123

Apabila Anda menemukan code error silahkan lakukan PR (Pull Request) saja. Sekian dan semoga bermanfaat
## Salam Open Source!
