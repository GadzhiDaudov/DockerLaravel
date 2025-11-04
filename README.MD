## Start
- Docker container for work with Laravel 12: nginx, php8.3-fpm, MySQL, PHPMyAdmin
- Docker compose up -d --build
## For Linux: 
- sudo chmod 777 -R ./
### For empty projects:
- docker-compose exec -it app bash
- mkdir /tmp/temp_docker

- mv /var/www/* /tmp/temp_docker/
- mv /var/www/.* /tmp/temp_docker/

- composer create-project laravel/laravel .

- mv /tmp/temp_docker/* /var/www/
- mv /tmp/temp_docker/.* /var/www/

- rmdir /tmp/temp_docker

- exit
