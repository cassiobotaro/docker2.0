# docker2.0
Repositório para colocar os desafios do curso Docker 2.0 

Desafio 1 - Postgres
docker container run -d -p 5432:5432 -e POSTGRES_DB="curso_docker" -e POSTGRES_USER="docker_usr" -e POSTGRES_PASSWORD="docker_pwd"  postgres

Desafio 2 - MySQL
docker container run -d -p 3306:3306 -e MYSQL_DATABASE="docker_db" -e MYSQL_USER="docker_usr" -e MYSQL_PASSWORD="docker_pwd" -e MYSQL_RANDOM_ROOT_PASSWORD="yes" mysql

Desafio 3 - Mongo
docker container run -d -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME="mongo_usr" -e MONGO_INITDB_ROOT_PASSWORD="mongo_pwd" mongo
