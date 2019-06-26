# Test Nginx+FPM with Docker
Launch container with commands

`docker run  -d -v $PWD:/scripts php:7.2-fpm`

`docker run  -d -p 8080:80 -v $PWD:/usr/share/nginx/html -v $PWD/nginx:/etc/nginx/conf.d nginx`

Start localhost:8080
