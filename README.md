# laravel-githubactions-test


## create laravel project
- docker-compose exec app bash
- composer create-project --prefer-dist "laravel/laravel=10.*" .
- chown www-data storage/ -R   

## db migrate
- php artisan migrate

## build vue
- npm install
- npm install --save-dev vue @vitejs/plugin-vue
