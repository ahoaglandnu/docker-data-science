# Docker for Data Science Projects

This configuration sets up a Jupyter Notebook environment with different databases using Docker containers orchestrated by Docker Compose.

## Getting Started

### Initial Start

To start all services in the foreground, run:

`docker-compose up`

### Running in Background

To start all services in the background (detached mode), use:

`docker-compose up -d`

### Stopping Services

To stop the services without removing them, execute:

`docker-compose stop`

### Viewing Container Status

Check the status of the containers with:

`docker-compose ps`

### Starting Stopped Services

To start services that have been previously stopped, run:

`docker-compose start`

### Stopping and Removing Services

To stop all services and remove them along with the default network, use:

`docker-compose down`

### Additional Commands

Explore more Docker Compose commands:

`docker-compose --help`
