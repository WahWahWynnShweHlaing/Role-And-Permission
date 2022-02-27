# Laravel Role And Permission
A simple implementation of laravel 8 spatie user roles and permissions.

## Set up
To set up this project, first clone the repositiory
```bash
$ git clone https://github.com/WahWahWynnShweHlaing/Role-And-Permission.git
```

Change your working directory into the project directory
```bash
$ cd permission
```

Then install dependencies using [Composer](https://getcomposer.org/doc/00-intro.md)
```bash
$ composer install
```

Copy `.env.example` to `.env`
```bash
$ cp .env.example .env
```
Create database and configure in .env file
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=auth
DB_USERNAME=root
DB_PASSWORD=
```

Run database migrations:
```bash
php artisan migrate
```

## Installation Package

```bash
composer require spatie/laravel-permission
```
```bash
php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"
```
```bash
php artisan migrate:fresh
```
```bash
npm install
npm run dev
```

Add Laravel's basic auth
```bash
composer require laravel/ui --dev
php artisan ui bootstrap --auth
```

## Run
Run the application with the following command
```bash
$ php artisan serve
```

