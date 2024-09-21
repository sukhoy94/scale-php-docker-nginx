# Scale PHP Docker Nginx

## Description

This repository contains a Docker configuration for a PHP application using Nginx as a reverse proxy. The application is scalable, meaning you can run multiple instances of the PHP backend.

## Technologies

- PHP
- Nginx
- Docker
- Docker Compose

## Requirements

- Docker
- Docker Compose

## How to Run

1. Clone this repository:

   ```bash
   git clone git@github.com:sukhoy94/scale-php-docker-nginx.git
   cd scale-php-docker-nginx

2. Start the containers using Docker Compose:

```bash
docker-compose up --build
```

3. Visit 0.0.0.0:8080 to see results