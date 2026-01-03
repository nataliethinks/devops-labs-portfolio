# Verification

## Application access
- URL: http://localhost:8080
- Expected: WordPress installation page loads successfully

## Container status
```bash
docker compose ps

## Commands Log

docker compose up -d
docker compose ps
docker volume ls
docker volume inspect 04-multi-container-app_db_data
docker compose down
docker compose up -d

## Environment
- Docker Desktop (local)
- Docker Compose v2
- macOS

This lab was executed in a local Docker environment to demonstrate container orchestration concepts independent of cloud infrastructure.