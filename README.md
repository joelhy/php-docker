# dockerized web environment
> Dockerized web environemnt using NGINX, PHP 7, MySQL, Memcache, and Redis.

[![Author](https://img.shields.io/badge/author-joelhy-blue.svg?style=flat-square)](https://github.com/iwyg)
[![Source Code](https://img.shields.io/badge/source-joelhy/php__docker-blue.svg?style=flat-square)](https://github.com/joelhy/php-docker/tree/master)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://github.com/joelhy/php-docker/blob/master/LICENSE.md)

[![Build Status](https://img.shields.io/travis/joelhy/php-docker/master.svg?style=flat-square)](https://travis-ci.org/joelhy/php-docker)

This repository uses the official [php docker container](https://hub.docker.com/_/php/).

## Contents
- [NGINX](http://nginx.org/)
- [Postres](http://www.postgresql.org)
- [PHP-FPM](http://php-fpm.org/)
- [Redis](http://redis.io/)
- [Memcached](http://memcached.org/)

Additional PHP extensions are:
- curl
- gd
- iconv
- intl
- mbstring
- mcrypt
- memcached
- mysqli
- pdo_mysql
- redis

## Requirements
- [Docker Engine](https://docs.docker.com/installation/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Docker Machine](https://docs.docker.com/machine/) (OS X and Windows)

## Containers
- [Nginx](https://hub.docker.com/_/nginx/)
- [php-fpm](https://hub.docker.com/_/php/)
- [Redis](https://hub.docker.com/_/redis/)
- [Memcached](https://hub.docker.com/_/memcached/)
- [MySQL](https://hub.docker.com/_/mysql/)

## Usage

Assuming you have a running docker machine:

```bash
$ docker-compose up
```

## Credits
Based on work of [Thomas Appel](https://github.com/iwyg/php-docker).
