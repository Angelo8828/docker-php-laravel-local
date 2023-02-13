## Docker scripts for PHP / Laravel local development

### Stack

 - PHP 8.0
 - Nginx
 - MySQL 5.7
 - PHPMyAdmin
 - Redis

### Installation notes

1. Place the `docker` folder and the `docker-compose.yml` to your Laravel project directory

2. Replace the DB configuration values on your project `.env` with the values indicated on `.env.example` file from this repository

3. Run `docker-compose up -d`

### Local URLs and Credentials

App URL: http://localhost:8001

PHPMyAdmin URL: http://localhost:8081

Redis Port: 6380

DB Credentials:
```
UN: root
PW: p@ssw0rd

UN: user1
PW: p@ssw0rd
```
