## About this project

This project is about a Homework management website for 3 types of users, which are teacher, student and administrator.

## Requirements

- OS: Ubuntu 20.04. [Install Ubuntu](https://phoenixnap.com/kb/install-ubuntu-20-04)
- PHP :
  v7.4.29. [Install PHP](https://www.digitalocean.com/community/tutorials/how-to-install-php-7-4-and-set-up-a-local-development-environment-on-ubuntu-20-04)
- MySQL : v7.4. [Install MySQL](https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-20-04)
- Composer :
  v2.3.7.[Install Composer](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-composer-on-ubuntu-20-04)
- Nginx :
  v1.18.0. [Install Nginx](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-20-04)

## Usage

```ssh
$ php artisan serve
```

## To Use Docker

To build:

```ssh
$ docker compose up -d --build
```

To down:

```ssh
$ docker compose down
```

To list containers:

```ssh
$ docker ps
```

To execute a container:

```ssh
$ docker exec -it homeworkmanagement-nginx-1 bash
$ docker exec -it <container> <command>
```
