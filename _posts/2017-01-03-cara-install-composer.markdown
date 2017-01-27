---
title:  "Cara install composer"
date:   2017-01-03 10:00:00
categories: [developer, composer]
tags: [developer,php,composer]
---

Mumpung ada sela waktu (di saat kerja, hehe), saya akan menulis tentang cara installasi composer.

### Installasi Composer
- Berkunjung ke halaman web Composer -> pilih menu Download
- Siapkan Terminal, copas kode berikut di terminal lalu jalankan.

``` ruby
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('SHA384', 'composer-setup.php') === '55d6ead61b29c7bdee5cccfb50076874187bd9f21f65d8991d46ec5cc90518f447387fb9f76ebae1fbbacf329e583e30') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```

- Agar menjalankannya tidak menggunakan composer.phar baiknya kita buatkan semacam link composer

``` ruby
mv composer.phar /usr/local/bin/composer
```

- Tes apakah sudah berjalan

``` ruby
composer -V
```