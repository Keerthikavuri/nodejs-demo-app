# nodejs-demo-app

A simple Node.js web app with Docker and CI/CD automation using GitHub Actions.

## Features

- Simple Node.js server (`app.js`)
- Dockerized for easy deployment (`Dockerfile`)
- Automated build and push using GitHub Actions workflow

## How to Run

node app.js

## How to Build with Docker

docker build -t <your-dockerhub-saikeerthi03>/nodejs-demo-app:latest .
docker run -p 3000:3000 <your-dockerhub-saikeerthi03>/nodejs-demo-app:latest.


## CI/CD Automation

This repo contains a GitHub Actions workflow in `.github/workflows/main.yml` that builds and pushes the Docker image automatically on every commit to the `main` branch.

