
# Dockerized Node.js App

This is a simple Node.js application containerized using Docker.

## How to run

1. Clone the repo:

git clone https://github.com/danialkhan8284/docker-node-project.git

2. Build Docker image: 

 docker build -t node-devops-app

3. Run container:

docker run -p 3000:3000 node-devops-app


Visit `http://localhost:3000` to see the app running.

## Docker Hub Image
https://hub.docker.com/repository/docker/danialkhan8284/node-devops-app