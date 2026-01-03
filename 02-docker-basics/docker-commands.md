# Docker Commands Log

## Verify Docker installation
```bash
docker version
docker info

## Run a container
docker run hello-world

## Run Nginx container with port mapping
docker run -d -p 8080:80 --name nginx-demo nginx

## Inspect running containers
docker ps
docker inspect nginx-demo

## Stop and remove container
docker stop nginx-demo
docker rm nginx-demo
