# PSUSphere - Docker Assignment

## Description

PSUSphere is a Django web application containerized using Docker.

## Requirements

- Docker Desktop
- Docker Compose
- A Docker Hub account (for publishing the image)

## Run Locally with Docker

1. Clone or download this repository.
2. Open a terminal in the project root.
3. Build the image:

   docker compose build

4. Start the application:

   docker compose up

5. Open http://localhost:8001

## Run Using Docker Hub

1. Open the for_client folder.
2. Make sure the Docker Hub image name in docker-compose.yml is correct.
3. Start the application:

   docker compose up -d

4. Open http://localhost:8001

## Useful Commands

Stop the application:

    docker compose down

View logs:

    docker compose logs -f web

Check running containers:

    docker compose ps

Create a Django superuser:

    docker compose exec web python manage.py createsuperuser

## Docker Hub

Image: traumerei09/django-app:latest
