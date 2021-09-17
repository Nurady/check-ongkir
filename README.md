<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Check Ongkir 
- Laravel 8
- Raja ongkir Starter Package

## Penggunaan
1. Clone Project
2. composer install/composer install --ignore-platform-reqs
3. Jika cara nomor 2 tidak bisa lakukan: composer update/composer update --ignore-platform-reqs
4. copy file .env.example, rename menjadi .env
5. php artisan key:generate
6. buat database
7. ganti database name di file .env
8. php artisan migrate
9. Tambahkan di file .env   
    RAJAONGKIR_API_KEY='kode api key'
    RAJAONGKIR_PACKAGE=starter
10. php artisan db:seed
11. php artisan serve

