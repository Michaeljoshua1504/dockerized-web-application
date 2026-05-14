# Containerized Static Website Deployment with Docker and Nginx

## Project Overview

This project demonstrates how to containerize and deploy a static website using Docker and Nginx.

## Technologies Used

- Docker
- Nginx
- HTML
- CSS

## Project Structure

dockerized-web-application/
├── index.html
├── styles.css
├── Dockerfile
├── .dockerignore
└── README.md

## Build Docker Image

docker build -t mywebsite .

## Run Docker Container

docker run -d -p 8080:80 mywebsite

## Access the Application

http://localhost:8080

## Skills Demonstrated

- Containerization
- Docker Image Creation
- Docker Container Management
- Static Website Deployment
- Nginx Web Server Configuration
- Docker Best Practices

## Run with Docker Compose
docker compose up --build -d

## Stop the Application
docker compose down