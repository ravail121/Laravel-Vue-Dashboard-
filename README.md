Laravel Dashboard Vue ReadMe
Welcome to the Laravel Dashboard Vue project! This ReadMe file provides step-by-step instructions on how to set up and run your Laravel project, which combines the power of Laravel for the backend with Vue.js for the frontend.

composer install

cp .env.example .env

php artisan key:generate

php artisan migrate --seed

php artisan passport:install

php artisan storage:link

npm install

npm run dev
php artisan serve
This command will start a local development server, and you can access your project in a web browser at http://localhost:8000.