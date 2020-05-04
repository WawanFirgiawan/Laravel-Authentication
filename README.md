<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Table Of Contents

- [Cara Install Laravel Authentication]
  - [Table Of Content](#table-of-content)
  - [Install Laravel](#install-laravel)
  - [Stacks](#stacks)
  - [Dependencies](#dependencies)
  - [Aplication Structure](#aplication-Structure)


## Install Laravel

1. Install Composer
- Download dan Install Composer melalui link : `https://getcomposer.org/Composer-Setup.exe`

2. Install Laravel
- Buka CMD lalu masuk ke `htdocs` XAMPP
- Buat project laravel dalam folder htdocs dengan memasukkan kode di cmd : `composer create-project laravel/laravel laravel – prefer-dist`
- Tunggu Sampai Proses Selesai.
- Setelah Proses selesai Jalankan XAMPP di browser : `http://localhost/laravel/public`

<p align="center">
  <a href="http://localhost/laravel/public/">
    <img title="Laravel Default View" height='200' src="https://laravelarticle.com/filemanager/uploads/laravel-7.png">
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

7. Jika tidak terjadi error, maka pada web anda akan bertambah dengan 2 menu yaitu LOGIN dan REGISTER yang terdapat pada pojok kanan atas website anda.

## Aplication Structure
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
