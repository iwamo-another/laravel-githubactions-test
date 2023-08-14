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

## install adminlte
- composer require jeroennoten/laravel-adminlte
- php artisan adminlte:install
- php artisan adminlte:status
- php artisan adminlte:install --only=auth_views

※参考
https://qiita.com/zaburo/items/b9e769c7c4a87614b3f9


## memo api.
https://kinsta.com/jp/blog/laravel-api/

