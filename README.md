This is a repo for labs in Kafka Essentials course

Requirements:

- Docker. You need to have docker. You can install it from (https://www.docker.com/products/docker-desktop)
- Http client like Postman, curl, etc

Clone this repository or download it as a zip file.

Module1 - use file docker-compose.yaml

Inside the directory run

`docker compose up`


Module2, Module3, Module4 use file docker-compose-all.yaml

`docker compose -f docker-compose-all.yaml up`


Some useful commands:

1. Remove all the processes on docker 

`docker rm -f $(docker ps -a -q)`


2. See logs of the container

`docker logs container_name`


3. Run command inside the container

`docker exec -ti container_name command_name`

