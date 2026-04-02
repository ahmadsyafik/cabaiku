step set up



- cd cabaiku

- composer install

- cp .env.example .env

- create database cabaiku on mysql (only name database, we no need make manual tables)

- php artisan key:generate (automatic generate key on env)







- php artisan migrate --seed

- php artisan storage:link

- php artisan serve
