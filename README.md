## Create Docker with Apache/PHP 8.2 and mysqlx-xdevapi

* Edit **.env** file with your settings

* Run 
```
docker-compose build && docker-compose up -d
```

* **/www** folder will be created

* Put your php files in **/www** folder. Change permissions from root to your user

### Login to container

```
docker exec -it php-xdevapi-docker-apache-server-1 /bin/bash
```