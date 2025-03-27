# Welcome-to-Docker

This is My-First-Docker-Container with Docker.

You can try it out using the following command.

cmd =>   docker run -d -p 8089:80 --name welcome-to-docker docker/welcome-to-docker

Build and run:
cmd => docker build -t welcome-to-docker-main . 

cmd => docker run -d -p 8089:3000 --name welcome-to-docker-main welcome-to-docker-main

Open url =>  http://localhost:8089 in your browser.
