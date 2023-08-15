composer create-project laravel/laravel benglish "9.*"
Cristian Perdomo15:39
# Benglish - backend

## Requerimientos:

- Laravel 10
- Php 8.2
- Mysql

## Instalacion

```console
unknown@unknown$ composer install
unknown@unknown$ php artisan key:generate
unknown@unknown$ php artisan migrate:fresh --seed
unknown@unknown$ php artisan storage:link
unknown@unknown$ php artisan serve

```