Giro assestment

heroku couldnt combined my laravel and react app so to check this project

clone this project

<!-- run  -->

composer install

create env
cp .env.example .env

generate key
php artisan key:generate

setup your database setting in the env

run migration
php artisan migrate

run seed
php artisan db:seed

npm install

npm run dev

php artisan serve

route for api

can perform POST, GET PUT and DELETE verb
/api/product
/api/category
