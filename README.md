# Node.js Sample CI/CD with GitHub Actions

This repo demonstrates a CI/CD pipeline for a Node.js app using:

- GitHub Actions
- DockerHub

## Steps

1. Cloned a sample Node.js app from Heroku.
2. Created a Dockerfile to containerize the application.
3. Set up a GitHub Actions workflow (.yml file) to:
  - Install dependencies
  - Run a placeholder test
  - Build a Docker image
  - Push the image to DockerHub automatically
4. Secured credentials using GitHub Secrets (`DOCKER_USERNAME`, `DOCKER_PASSWORD`).

## 🚀 Result

On every push to the `main` branch, GitHub Actions automatically builds the Docker image and pushes it to my DockerHub repository.

## 📁 Files

- `Dockerfile`: Instructions to build the container.
- `.github/workflows/main.yml`: GitHub Actions workflow.
- `index.js`, `package.json`: Node.js app files.

## DockerHub Image:
➡️ https://hub.docker.com/repository/docker/sonayadav0709/node-js-sample/general
