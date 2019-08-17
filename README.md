# laravel Base Api

I created this as a starting point for laravel api projects

It comes with a basic User table migration and Model and some basic Signin, Signout, and registration controllers

It uses a simple token based auth.

## Init

1. Pull repo
2. Run `composer install`
3. Run `cp .env.example .env`
4. Edit all database related env variables appropriately
5. Create database
6. Run `php artisan migrate`
7. Run `php artisan serve`

## Testing

`phpunit` runs tests if you have phpunit installed globally with composer.

Otherwise run `./vendor/bin/phpunit`
