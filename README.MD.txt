# Docker CMD
docker --version: Check the Docker version.
docker info: Display detailed information about Docker.
docker run <image>: Run a container from a specific image.
docker ps: List running containers.
docker ps -a: List all containers, including stopped ones.
docker images: List available images on your system.
docker pull <image>: Download an image from Docker Hub or another registry.
docker build -t <tag> <path>: Build an image from a Dockerfile.
docker stop <container>: Stop a running container.
docker start <container>: Start a stopped container.
docker restart <container>: Restart a running container.
docker rm <container>: Remove a stopped container.
docker rmi <image>: Remove an image.
docker exec -it <container> <command>: Run a command inside a running container.
docker logs <container>: View the logs of a container.
docker network ls: List available Docker networks.
docker volume ls: List available Docker volumes.
docker-compose up: Run a multi-container application using Docker Compose.
docker-compose down: Stop and remove containers managed by Docker Compose.