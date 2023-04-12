# Base Image

The choice of the base image used is node- alpine version which worked well with the application and is also lighter in terms of size.

## Docker Directives

Used the following FROM sets base images for backend, client and mongo COPY copies files to containers RUN initiates commands to install and build WORKDIR holds files for the current directory EXPOSE opens up ports for apps Network builds the intercontainer network CMD commands to fire up our app LABEL gives decription, names, version to our images.

## Networking

Used a configured network to ensure the containers communicate to each other

## Git Workflow

I forked the repository from the source then cloned and worked on it with the updated changes to the file

## Bugs

There are no known bugs with this project.

## Docker image tag

I tagged the client image as client:v1 and the backend image as backend:v1.

## Prerequisites

Docker-compose up

## Instructions

1. git clone <https://github.com/Barchok-Kiposmet/yolo.git>

2. cd yolo

3. docker-compose up --build

4. Access App on <http://localhost:3000>
