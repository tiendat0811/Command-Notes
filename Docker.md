# DOCKER COMMAND

## DOCKER COMPOSE

1. Build docker-compose
   `docker-compose build name_build`

2. Up docker-compose
   `docker-compose up name`

## DOCKER IMAGE

1. Get all image
   ` docker image ls`

## DOCKER CONTAINER

1. Get all container
   `docker ps -a`

## DOCKER ACCESS

1. Create the `docker` group
   ` sudo groupadd docker`

2. Add user to `docker` group
   `sudo usermod -aG docker $USER`

3. Log out and log back in so that your group membership is re-evaluated
   `newgrp docker`
