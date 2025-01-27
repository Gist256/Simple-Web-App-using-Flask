# Simple-Web-App-using-Flask

# Flask Docker App

This is a simple web application built with Flask and Docker.

## Features
- Flask-based web app
- Dockerized for easy deployment
- GitHub Actions CI/CD pipeline

## How to Run Locally
1. Clone the repository:
   https://github.com/Gist256/Simple-Web-App-using-Flask
3. Build the Docker image:
4. docker build -t projectflask1 .
5. Run the container:
   docker run -d -p 5000:5000 projectflask1
6.
## CI/CD Pipeline
The project includes a GitHub Actions workflow to build and push the Docker image to Docker Hub automatically on each push to the `main` branch.

## Kubernetes
You can deploy the app to Kubernetes using the provided `deployment.yml`.

Push your changes:
git add .
git commit -m "Added README and CI/CD pipeline"
git push

