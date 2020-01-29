# Docker Compose For LEMP Stack
this repository brings LEMP stack with docker compose version 3 

for database test, first you must install pdo driver into php:fpm container, for this you can run below command :
```
docker container -exec <containerID> docker-php-ext-install pdo pdo_mysql
```
and after that restart containers : 
```
 docker-compose restart 
 ```

* note this you've to create a database before run the test-database.php file and you can change database name into that file.


Good Luck !!
