### How to use? 

Simple, just clone the repo, run `cp .env.example .env` and run `docker compose up`

### How can i access app bash?

Simple too, just run `docker compose exec app bash`, you need to run `composer install` and `php artisan key:generate`.

To migrations run: `php artisan migrate`

### How can i access database?

Simple as well, just run `docker compose exec db mysql -u user -p`
Default password: password

Inside the database run: `use ignitiondb`. And there you go, your are already on the database.