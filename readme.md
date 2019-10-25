## How To Use

`php composer.phar install`

`cp .env.example .env`

Update the db credentials to point to the database for which to generate the migrations

`php artisan migrate:generate`

The migration files will be placed in database/migrations

## Generate Models

To generate models from the current database, use the following command

`php artisan generate:modelfromtable --all --folder=app/Models`

This will place them in the app/Models directory, (warning) the namespace is still App.