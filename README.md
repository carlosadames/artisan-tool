
# Artisan Tool
## The power of Artisan in Nova

[![Latest Version on Packagist](https://img.shields.io/packagist/v/pragmarx/artisan-tool.svg?style=flat-square)](https://packagist.org/packages/pragmarx/artisan-tool)

### Screenshots

![screenshot1](docs/img/screenshot-1.png)

![screenshot1](docs/img/screenshot-2.png)

![screenshot1](docs/img/screenshot-3.png)

### Installation

You can install the package in to a Laravel app that uses [Nova](https://nova.laravel.com) via composer:

```bash
composer require pragmarx/artisan-tool
```

Next up, you must register the tool with Nova. This is typically done in the `tools` method of the `NovaServiceProvider`.

```php
// in app/Providers/NovaServiceProvider.php

// ...

public function tools()
{
    return [
        // ...
        new \PragmaRX\ArtisanTool\Tool(),
    ];
}
```

### Usage

Click on the "artisan-tool" menu item in your Nova app to see the tool provided by this package.

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

### Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email acr@antoniocarlosribeiro.com instead of using the issue tracker.

### Credits

- [Antonio Carlos Ribeiro](https://github.com/antonioribeiro)

### License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
