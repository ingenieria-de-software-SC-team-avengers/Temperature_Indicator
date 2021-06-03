
composer install

cp .env.example .env

vi .env

php artisan key:generate

php artisan migrate --seed
