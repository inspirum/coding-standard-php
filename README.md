# Coding standard

**Created as part of [inspishop][link-inspishop] e-commerce platform by [inspirum][link-inspirum] team.**

[![Latest Stable Version][ico-packagist-stable]][link-packagist-stable]
[![Total Downloads][ico-packagist-download]][link-packagist-download]
[![Software License][ico-license]][link-licence]


## System requirements

* [PHP 7.4+](http://php.net/releases/7_4_0.php), [PHP 8.0+](http://php.net/releases/8_0_0.php)


## Installation

Run composer require command:
```
composer require --dev inspirum/coding-standard
```

Create `phpcs.xml.dist` file with:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<ruleset>
    <rule ref="InspirumCodingStandard"/>
</ruleset>
```


## Security

If you discover any security related issues, please email tomas.novotny@inspirum.cz instead of using the issue tracker.


## Credits

- [Tomáš Novotný](https://github.com/tomas-novotny)
- [All Contributors][link-contributors]


## License

The MIT License (MIT). Please see [License File][link-licence] for more information.


[ico-license]:              https://img.shields.io/github/license/inspirum/coding-standard-php.svg?style=flat-square&colorB=blue
[ico-workflow]:             https://img.shields.io/github/workflow/status/inspirum/coding-standard-php/Test/master?style=flat-square
[ico-packagist-stable]:     https://img.shields.io/packagist/v/inspirum/coding-standard.svg?style=flat-square&colorB=blue
[ico-packagist-download]:   https://img.shields.io/packagist/dt/inspirum/coding-standard.svg?style=flat-square&colorB=blue

[link-author]:              https://github.com/inspirum
[link-contributors]:        https://github.com/inspirum/coding-standard-php/contributors
[link-licence]:             ./LICENSE.md
[link-changelog]:           ./CHANGELOG.md
[link-inspishop]:           https://www.inspishop.cz/
[link-inspirum]:            https://www.inspirum.cz/
[link-packagist-stable]:    https://packagist.org/packages/inspirum/coding-standard
[link-packagist-download]:  https://packagist.org/packages/inspirum/coding-standard
