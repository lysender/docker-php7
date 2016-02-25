# PHP 7 Docker Container

Base image is using Ubuntu Xenial (16.04) with PHP 7.

## Build

~~~
cd /path/to/docker-file
docker build --rm -t lysender/php7 .
~~~

## Test

~~~
docker run --rm lysender/php7 php -i
docker run --rm lysender/php7 php -m
~~~
