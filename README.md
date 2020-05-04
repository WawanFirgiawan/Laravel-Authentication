# 📚 Install Laravel Authentication

<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel adalah sebuah framework PHP yang dirilis dibawah lisensi MIT, dibangun dengan konsep MVC (model view controller). Laravel adalah pengembangan website berbasis MVP yang ditulis dalam PHP yang dirancang untuk meningkatkan kualitas perangkat lunak dengan mengurangi biaya pengembangan awal dan biaya pemeliharaan, dan untuk meningkatkan pengalaman bekerja dengan aplikasi dengan menyediakan sintaks yang ekspresif, jelas dan dapat menghemat waktu.

## Table Of Contents

- [Cara Install Laravel Authentication]
  - [Table Of Content](#table-of-content)
  - [Install Laravel](#install-laravel)
  - [RUN Laravel](#run-laravel)
  - [Kebutuhan](#kebutuhan)


## Install Laravel

1. Install Composer
- Download dan Install Composer melalui link : `https://getcomposer.org/Composer-Setup.exe`

2. Install Laravel
- Buka CMD lalu masuk ke `htdocs` XAMPP
- Buat project laravel dalam folder htdocs dengan memasukkan kode di cmd : `composer create-project laravel/laravel laravel – prefer-dist`
- Tunggu Sampai Proses Selesai.
- Setelah Proses selesai Jalankan XAMPP di browser : `http://localhost/laravel/public`

<p align="center">
  <a href="https://laravel.com/">
    <img title="LARAVEL" height='200' src="https://miro.medium.com/max/2730/1*gsGG1VLh7JSD8hUSNU69EQ.png">
  </a>
</p>

3. Ketikkan di CMD `php artisan serve` untuk menjalankan pada server:8000.

4. Kemudian Buka di browser : `http://127.0.0.1:8000/` maka akan tampil halaman Default Framework Laravel. # (Jika Tidak Eror)

5. Melakukan Konfigurasi Untuk membuat Laravel Authentication (Ketik perintah dibawah pada CMD anda secara bergantian)

```bash
$ composer require laravel/ui
$ php artisan ui vue --auth
```

6. Masuk ke File Laravel pada XAMPP/HTDOCS  cari file `.env` (Kemudian Sesuaikan Dengan Database yang kita buat -  Disini saya membuat Database dengan nama `wfh`)

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=wfh
DB_USERNAME=root
DB_PASSWORD=
```

7. Lalu Ketik pada CMD
```bash
$ php artisan migrate
```

8. Jika tidak terjadi error, maka pada web anda akan bertambah dengan 2 menu yaitu LOGIN dan REGISTER yang terdapat pada pojok kanan atas website anda.

## RUN Laravel
Untuk Menjalankan Laravel pada Server anda bisa menggunakan perintah CMD : `php artisan serve` setalah itu masukkan  pada browsure anda perintah :

```bash
`http://127.0.0.1:8000/`
```

atau ketik

```bash
`http://localhost/laravel/public`
```

## Kebutuhan

- Composer
- MySQL
- Laravel File


---

Copyright © 2020 by Wawan Firgiawan
