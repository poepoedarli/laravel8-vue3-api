## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.


## Steps while creating projects

## Migration
// editing .env file here
composer install
php artisan migrate

## Install Breeze
composer require laravel/breeze
php artisan breeze:install
npm install && npm run dev

## Create Model with migration
php artisan make:model Company -m
