# Docker MariaDB
Docker MariaDB is a images and container with mariaDB and phpmyadmin. For startd to create new some app faster.

## Installation
### Create a docker network first ***(Require)
```CMD
docker network create my-network
docker network ls
```

User command below for started
```CMD
git clone https://github.com/anisonglopez/docker_mariadb.git
cd docker_mariadb
docker-compose up --build -d
```

## Check your container is running
```
docker ps
```
Must to check status is up time

## Service
MariaDB is running on port 3307:3306

PhpMyadmin is running on port 8081

DB_HOST=docker_mariadb

server=docker_mariadb

username=root

password=secret
