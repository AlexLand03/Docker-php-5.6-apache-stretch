# Docker-php-5.6-apache-stretch

I Created a new container as php:5.6-apache-stretch image, in my root base var/www/html

docker run -p 8080:80 -v "$PWD":/var/www/html --name php-apache-des -d php:5.6-apache-stretch

its working normally with same proyect, but i try to open a dir with php-PDF codes and show me:

Not Found

The requested URL /8080 was not found on this server.
Apache/2.4.18 (Ubuntu) Server at localhost Port 80

