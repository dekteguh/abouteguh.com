---
title:  "Cara install laravel framework"
date:   2017-01-03 11:45:00
categories: [developer, series, laravel]
tags: [developer,php,framework,laravel]
---

Mumpung waktu instirahat (sambil menjelang Sholat Dzuhur), saya mencoba membuat web app dengan bahasa pemrograman PHP menggunakan framework [laravel](https://laravel.com/).

Perlu diketahui bahwa sebelum menggunakan [laravel](https://laravel.com/), ada baiknya kita cek dulu spesifikasi minimal dari framework tersebut.

- PHP >= 5.6.4
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension

Setelah itu, cara menginstall laravel juga ada banyak macam, yaitu via Laravel Installer, dan Composer.

### Install Laravel via Laravel Installer
Pertama kali, download laravel installer dengan menggunakan [Composer](https://getcomposer.org/):

``` ruby
composer global require "laravel/installer"
```

Kedua, pastikan PATH nya sudah benar. Jika belum dilakukan pengaturan, masukkan `$HOME/.composer/vendor/bin` ke PATH

Setelah itu, jalankan laravel installer dengan perintah berikut.

``` ruby
laravel new contoh-laravel
```

Setelah installasi selesai, baru jalankan perintah berikut dan cek di browser.

``` ruby
cd contoh-laravel
php artisan serve
``` 

### Install Laravel via [Composer](https://getcomposer.org/)
Cara lain dengan menggunakan composer `create-project`.
Buka terminal, kemudian jalankan perintah berikut.

``` ruby
composer create-project --prefer-dist laravel/laravel contoh-laravel
```

Setelah terinstall, jalankan perintah berikut dan cek di browser.

``` ruby
cd contoh-laravel
php artisan serve
``` 

Selamat mencoba.
Tetap semangat!