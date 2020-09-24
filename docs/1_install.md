Generating project
composer create-project --prefer-dist laravel/laravel test-project "5.8.*"

Show laravel version
php artisan --version

Generating laravel files
php artisan make:auth

Making models and migrations 
php artisan make:model Models/Test -m
php artisan migrate

Making controllers
php artisan make:controller Shop/Admin/AboutController --resource
php artisan make:controller Shop/Site/TestController

Making seeds
php artisan make:seeder TestSeeder

Запуск сидов
php artisan db:seed
php artisan db:seed --class=TestSeeder
php artisan migrate:refresh --seed

Making Factories
php artisan make:factory TestFactory

Making Request
php artisan make:request TestUpdateRequest

Commands for routes
1.  php artisan route:list
2.  php artisan route:list > routes.txt
