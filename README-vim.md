How to Setup Vim Development Environment
===

## Requires

- neovim
- composer
- vim plugin: coc.nvim
- coc plugin: coc-phpls
- php extensions: php-curl php-xml php-bcmath php-gd php-zip

## Setup

- `composer require --dev barryvdh/laravel-ide-helper`
- `php artisan ide-helper:generate`
- `php artisan ide-helper:models`
- `php artisan ide-helper:meta`

## Reference

- https://github.com/barryvdh/laravel-ide-helper

