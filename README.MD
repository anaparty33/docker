Here we have two containers running created by docker-compose

- redis
- node js app

These two containers are automatically connected by docker compose

- DockerFile - is configuration for node app container
- docker-compose.yml uses the Dockerfile to build node app container and redis base image for redis container
