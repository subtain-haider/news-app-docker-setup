# News Application

This project consists of a backend API built with Laravel and a frontend application built with React.

## Prerequisites

- Docker
- Docker Compose

## Running the project

1. Clone both the backend and frontend repositories:
    git clone https://github.com/firstnamelastname/backend-laravel-api.git
    git clone https://github.com/firstnamelastname/react-news-app.git

2. Change to the directory containing the `docker-compose.yml` file:
    cd /path/to/docker-compose/directory

3. Run `docker-compose up --build` to build and start both the backend and frontend services:
    docker-compose up --build

4. Access the React news app at `http://localhost` and the Laravel API at `http://localhost:8000`.

5. To stop the services, press `Ctrl+C` or run `docker-compose down` in another terminal.
