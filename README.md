# Docker Platform Monitor

Demo DevOps/Platform project using Flask, PostgreSQL, Redis and Docker Compose.

## Prerequisites

- Docker Desktop
- Git

## Clone the Repository

```bash
git clone <repository-url>
cd docker-platform-monitor
```

## Start the Project

Build and start all services:

```bash
docker compose up --build
```

Run in background:

```bash
docker compose up -d --build
```

## Access the Application

Open:

http://localhost:5000

## Check Running Containers

```bash
docker compose ps
```

## View Logs

```bash
docker compose logs -f
```

## Stop the Project

```bash
docker compose down
```

## Remove Containers and Volumes

```bash
docker compose down -v
```

## Services

- Flask Web Application
- PostgreSQL Database
- Redis Cache
