# Go Docker App

A simple Go web application dockerized using Docker.

## Description

This app is a basic HTTP server that responds with:
Hello, Docker! This is a Go web app.



It runs on port `8080`.

## Docker Image

The Docker image is available on Docker Hub:

[https://hub.docker.com/r/esraamedhat/go-docker-app](https://hub.docker.com/r/esraamedhat/go-docker-app)

## How to Run

1. Pull the Docker image:

```bash
docker pull esraamedhat/go-docker-app:latest

2. Run the Docker container:
docker run -p 8080:8080 esraamedhat/go-docker-app

3.Open your browser at http://localhost:8080
 to see the message.



