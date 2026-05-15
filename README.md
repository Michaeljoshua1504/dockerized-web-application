# Containerized Static Website Deployment with Docker, Nginx, and CI/CD

## Project Overview

This project demonstrates how to containerize and deploy a static website using Docker and Nginx. It also includes Docker Compose for simplified container management and GitHub Actions workflows for Continuous Integration (CI) and Continuous Deployment (CD) to GitHub Pages.

## Live Demo

https://michaeljoshua1504.github.io/dockerized-web-application/


## Technologies Used

- HTML
- CSS
- Docker
- Nginx
- Docker Compose
- GitHub Actions
- GitHub Pages

## Project Structure

```text
dockerized-web-application/
├── index.html
├── styles.css
├── Dockerfile
├── docker-compose.yml
├── .dockerignore
├── README.md
└── .github/
    └── workflows/
        ├── main.yml
        └── deploy.yml
```

## Build Docker Image

docker build -t mywebsite .

## Run Docker Container

docker run -d -p 8080:80 mywebsite

## Run with Docker Compose

docker compose up --build -d

## Stop the Application

docker compose down

## Access the Application Locally

http://localhost:8080

## CI/CD Workflow

### Continuous Integration (CI)

Whenever code is pushed to the main branch, GitHub Actions automatically builds the Docker image to verify that the application can be successfully containerized.

### Continuous Deployment (CD)

After a successful build, GitHub Actions automatically deploys the website to GitHub Pages, making the latest version available through the live demo URL.

## Skills Demonstrated

- Containerization
- Docker Image Creation
- Docker Container Management
- Static Website Deployment
- Nginx Web Server Configuration
- Docker Compose
- CI/CD Automation
- GitHub Actions Workflow Configuration
- GitHub Pages Deployment
- Docker Best Practices
- Technical Documentation

## Learning Outcomes

Through this project, I gained practical experience in:

- Packaging applications using Docker
- Serving static content with Nginx
- Automating builds with GitHub Actions
- Deploying applications automatically using GitHub Pages
- Managing containers with Docker Compose
- Following industry-standard DevOps practices

## Author

Padamuthum Michael Joshua
