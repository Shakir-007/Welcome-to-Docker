# Welcome-to-Docker
My-First-Docker-Container

This is My-First-Docker-Container with Docker.

You can try it out using the following command.

docker run -d -p 8088:80 --name welcome-to-docker docker/welcome-to-docker

And open http://localhost:8089 in your browser.

Build and run:
docker build -t welcome-to-docker-main . 
docker run -d -p 8089:3000 --name welcome-to-docker-main welcome-to-docker-main

Open http://localhost:8089 in your browser.
