## About website-redant-api

website-redant-api is an API project and web application. We believe development must be exciting and a great experience to be truly fulfilling.

## Project Installation

```
git clone https://github.com/turbotechlabs/website-redant-api.git
```
```
composer install && composer update
```
```
php artisan key:generate
```
```
php artisan serve
```

## Laravel Modules (Optional)

```
composer require nwidart/laravel-modules
```
```
php artisan vendor:publish --provider="Nwidart\Modules\LaravelModulesServiceProvider"
```
```
{
  "autoload": {
    "psr-4": {
      "App\\": "app/",
      "Modules\\": "Modules/"
    }
  }
}
```
```
composer dump-autoload
```

## Contributing

Thank you for considering contributing to the project!
