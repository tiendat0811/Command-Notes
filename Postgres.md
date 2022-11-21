# Some Postgres notes

## CREATE

1. Create a Postgres
   `docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres`
2. Get all container
   `sudo docker ps -a`
3.

## RUN

1. Run a container
   `docker start name-container`
2. Open bash
   ` docker exec -it name-postgres bash`

## REMOVE

1. Remove a container
   `docker rm name-container`

## BASH COMMAND

1. Run psql
   `psql -h localhost -p 5432 -U postgres`

## POSTGRES COMMAND

1. List Database
   `\l`
2. Create Database
   `create database name_database;`
3. Connect Database
   `\c name_database`

## DATABASE COMMAND

1. List Relations
   `\dt`

## QUIT COMMAND

1. Exit
   `exit`
