Metapackage for PHP development with Heroku
===========================================

Meant to provide contraints regarding PHP extentions. Follows [Heroko's documentation](https://devcenter.heroku.com/articles/php-support#extensions) and default extentions for `php:8.0-fpm`.

## Usage

```shell
composer require --dev brnc/php-heroku-meta
```

## Development
```shell
composer update --lock --ignore-platform-req ext-ds && composer normalize
```
