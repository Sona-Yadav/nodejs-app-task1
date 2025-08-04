# Node.js Sample CI/CD with GitHub Actions

This repo demonstrates a CI/CD pipeline for a Node.js app using:

- GitHub Actions
- DockerHub

## Steps:
- On push to `main`, pipeline:
  - Installs dependencies
  - Builds Docker image
  - Pushes image to DockerHub

## DockerHub Image:
➡️ https://hub.docker.com/repository/docker/YOUR_USERNAME/node-js-sample
