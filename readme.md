## How To Use

`php composer.phar install`
`cp .env.example .env`

Update the db credentials to point to the database for which to generate the migrations

`php artisan migrate:generate`

The migration files will be placed in database/migrations
