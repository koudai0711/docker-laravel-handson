# docker-laravel-handson

アプリケーション立ち上げコマンド
```
[mac] $ git clone git@github.com:ucan-lab/docker-laravel-handson.git
[mac] $ cd docker-laravel-handson
[mac] $ docker compose up -d --build
[mac] $ docker compose exec app bash
[app] $ composer install
[app] $ cp .env.example .env
[app] $ php artisan key:generate
[app] $ php artisan storage:link
[app] $ chmod -R 777 storage bootstrap/cache

```
`http://127.0.0.1:8080`