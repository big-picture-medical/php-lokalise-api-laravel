# README

This is a Service Provider wrapper for the package [lokalise/php-lokalise-api](https://github.com/lokalise/php-lokalise-api).

Set the environment variable `LOKALISE_API_KEY`.

Add the GIT Repository to your composer file.

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url":  "https://github.com/arg2009/php-lokalise-api-laravel.git"
    }
  ]
}

```

Run with composer

```shell
composer require --dev arg2009/php-lokalise-api-laravel:dev-main
```