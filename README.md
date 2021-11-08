# Development Environment

## Create `.env`
- Create or copy `.env` file in the project root.

## Create Database Schema
- Use any client to create a database schema named `laravel-vue-composition-api`.


## Migration
```
composer install
php artisan migrate
```

## (For Dev) To build Vue's js files with every change
```
npm run watch
```


## (For Dev) Hot Module Replacement
```
npm run hot
```
***Note:*** if HMR is used during development, remember to re-build js files by running `npm run development` or `npm run production`