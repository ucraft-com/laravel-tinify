# laravel-tinify

This package provides integration with the Tinify a.k.a TinyPNG API.

The package simply provides a Tinify facade that acts as a wrapper to the [tinify/tinfiy-php](https://github.com/tinify/tinify-php)

## Installation

Install via composer by adding the following to your composer.json:

```json
    ...
    "require": {
        "ucraft-com/laravel-tinify": "~1.0"
    }
    ...
```

Add service provider to ```config/app.php```:

```php
    ...
    UcraftCom\LaravelTinify\LaravelTinifyServiceProvider::class
    ...
```

Add alias to ```config/app.php```:

```php
    ...
    'Tinify' => UcraftCom\LaravelTinify\Facades\Tinify::class
    ...
```

## Configuration
Set a env variable "TINIFY_APIKEY" with your issued apikey

This package is available under the [MIT license](http://opensource.org/licenses/MIT).