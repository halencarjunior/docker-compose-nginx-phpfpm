# Docker Container - Includes nginx and php7-fpm

Nginx default image and php-fpm listening port 9000. Nginx will connect php-fpm port 9000 and proxy to port 80. Next, we configure docker to listen port 3000 on localhost host machine forwarding to port 80 on container.


## Requirements

1. docker - https://docs.docker.com/engine/installation/
2. docker-compose - https://github.com/docker/compose/releases


## Starting container

	docker-compose up

	Open browser in url: http://localhost:3000
