# Tedu Exam Project

## Docker command Examples

docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=Admin@123$' -p 1422:1433 -d mcr.microsoft.com/mssql/server:2017-latest

## MongoDB
MACs-MacBook-Pro:~ mac$ docker run -d --name mongodb -e MONGO_INITDB_ROOT_USERNAME=mongoadmin -e MONGO_INITDB_ROOT_PASSWORD=secret -p 127.0.0.1:27017:27017 mongo
