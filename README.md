# mysql-docker


The docker-compose.yml file is responsible for creating the docker for mysql.
Database name and user credentials are stored in .env file which is read by docker-compose andacts accordingly while creating the container.
create-tables.sql then creates the table in database. This file isrun during container build.
