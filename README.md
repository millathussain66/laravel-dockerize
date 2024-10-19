## docker container exec -it app-rifive-laravel sh
## docker container exec -it app-rifive-laravel bash

docker container exec -it <container_name> <command>

docker compose up down
docker-compose up --build
docker-compose up --build -d



cd docker-compose/nginx/ssl/
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:2048 -keyout self-signed.key -out self-signed.crt

cd /var/www
php artisan migrate
