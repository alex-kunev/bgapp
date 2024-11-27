# Docker BGApp Project
This is a simple Docker project that has a Dockerfile for a building the resources of web server, and a Dockerfile for building a MySQL database. 

## Docker Compose
The Docker-compose YAML file takes the Dockerfiles and builds the infrastructure, while performing configurations:
- it opens up ports 8080:80 for the web app
- it sets out the password for the MySQL database from the .env file.

## Application
Once setup finished, the web server displays a list of Bulgarian cities from the database, on top of a map of Bulgaria.  
