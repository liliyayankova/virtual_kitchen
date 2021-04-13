Install Docker:
https://www.docker.com/products/docker-desktop

Have Docker running - either open the application or in terminal (docker start)

docker ps -> check running containers
docker ps -a -> check all containers

Go into the main folder of this project
Execute - docker-compose up -d --build (This calls the docker-compose.yaml file and starts the containers.
The build option is for the Dockerfile - it enables the mysqli extension for the database);

To check if the containers are running - docker ps

Visit -> http://localhost:8000

To stop the containers - docker-compose down
