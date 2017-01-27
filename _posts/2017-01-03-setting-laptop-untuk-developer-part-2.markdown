---
title:  "Setting laptop untuk developer (part 2)"
date:   2017-01-03 06:00:00
categories: [developer, series]
tags: [developer,setting, laptop]
---

Hari ini sudah masuk hari kerja, sebelum kerja, nulis dulu biar kece, haha.
Pagi ini saya akan menulis tentang lanjutan dari postingan hari kemarin, memposisikan diri jikalau saya ini adalah web developer.

Sebenarnya, untuk install PHP, DB, dan Web Server nya bisa menggunakan aplikasi bundle seperti WAMP dan XAMPP di Windows, Linux menggunakan LAMP, dan untuk Mac bisa menggunakan [MAMP/MAMP PRO](https://www.mamp.info/en/).

Sebelumnya, pastikan teman2 sudah install [Homebrew](http://brew.sh/)

``` ruby
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Copas kode di atas ke dalam Terminal. 

### Install PHP
``` ruby
brew install php70
```

### Install Mariadb
``` ruby
brew install mariadb
```

### Install Apache
``` ruby
brew install apache
```

Setelah semua terinstall, cek menggunakan Terminal,

``` ruby
php -v
mysql -v
apachectl -v
```

