# How to use Laravel and Pusher to create web notifications
[![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/neoighodaro?utm_source=github&utm_medium=button&utm_term=neoighodaro&utm_campaign=github)

This is an example of how to create web notifications. You can read the article on Pusher [here](https://pusher.com/tutorials/web-notifications-laravel-pusher-channels)

## Getting Started
- Download or clone the project
- Rename `.env.example` to `.env`
- Run `composer install` to install the dependencies
- Open `resources/views/welcome.blade.php` and update the Pusher keys
- Update the `PUSHER_APP_*` keys in the .env file
- Change the `BROADCAST_DRIVER` to `pusher`
- Run the command: `php artisan serve` to start the app


## Built With
- Laravel framework
- PHP
