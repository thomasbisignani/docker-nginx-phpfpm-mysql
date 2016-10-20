# docker-nginx-phpfpm-mysql
This Docker demo is a simple web stack based on 3 official images.

 - [Nginx][1] (nginx:latest)
 - [PHP-FPM][2] (php:7.0-fpm)
 - [MySQL][3] (mysql:latest)
 - [PhpMyAdmin][4] (phpmyadmin)

This application run 4 separate containers orchestrated by [Docker Compose][5].

## Usage
	docker-compose up -d

## Test your deployment
* Open [localhost:8080](http://localhost:8080) to check the app
* Open [localhost:8181](http://localhost:8181) to check PhpMyAdmin

[1]: https://hub.docker.com/_/nginx/
[2]: https://hub.docker.com/_/php/
[3]: https://hub.docker.com/_/mysql/
[4]: https://hub.docker.com/_/phpmyadmin/
[5]: https://docs.docker.com/compose/
