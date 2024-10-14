<p align="center"><img src="https://i.imgur.com/2v6AyjS.png" width="200"></p>

## UANGKAS - EASY TRACKING YOUR MONEY

UANGKAS adalah aplikasi yang dikembangkan untuk mencatat problem keuangan, seperti keuangan masuk / debit dan keuangan keluar / credit. Beberapa fitur diantaranya:

- Daftar (Development)
- Masuk / Login
- Lupa Password (Development)
- Dashboard
- Kategori Uang Masuk
- Uang Masuk
- Kategori Uang keluar
- Uang keluar

UANGKAS juga akan dibuat versi native android, yang rencana akan di kembangkan dengan android studi / java.
Untuk versi webnya menggunakan Framework Laravel

**NOTE**: template admin menggunakan stisla, untuk lebih lengkapnya bisa kunjungi situs resminya di: https://getstisla.com/

## Screenshot

- Login
<img src="https://i.imgur.com/3lfDm0L.png" style="width:100%">

- Register
<img src="https://i.imgur.com/vLeOxNn.png" style="width:100%">

- Dashboard
<img src="https://github.com/rahmathdyat/uangkas-laravel/blob/master/Screenshot/Dashboard.png" style="width:100%">

- Uang Masuk
<img src="https://github.com/rahmathdyat/uangkas-laravel/blob/master/Screenshot/Uangmasuk.png" style="width:100%">

- Uang Keluar
<img src="https://github.com/rahmathdyat/uangkas-laravel/blob/master/Screenshot/uangkeluar.png" style="width:100%">

- Laporan Uang Masuk
<img src="https://github.com/rahmathdyat/uangkas-laravel/blob/master/Screenshot/Laporanuangmasuk.png" style="width:100%">

## Cara Install

`$ > git clone https://github.com/rahmathdyat/uangkas-laravel`

`$ > cd uangku-laravel`

`$ > composer install`

`$ > cp env.example .env`

silahkan konfigurasi pengaturan database, seperti host, user, password dan nama database

`$ > composer dump-autoload`

`$ > php artisan migrate`

`$ > php artisan db:seed`


USERNAME : admin

PASSWORD : admin

## Cara Menjalankan

`$ > cd uangku-laravel`

`$ > php artisan serve`

Silahkan buka browser dan ketikkan : http://localhost:8000

## License

UANGKAS is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
