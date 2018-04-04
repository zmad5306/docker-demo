# docker-demo
Very basic docker demo

## Build with Docker

`docker build . -t docker-demo:latest`

## Run with Docker

`docker run -dit --name docker-demo -p 8080:80 docker-demo:latest`

## Check its Running

`docker ps`