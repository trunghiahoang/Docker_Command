# Docker Advanced Commands

1. **Docker Networks**:
   - *Create a Custom Network*: `docker network create <network-name>`
   - *Connect Container to a Network*: `docker network connect <network-name> <container-name>`
   - *Inspect a Network*: `docker network inspect <network-name>`

2. **Docker Volumes**:
   - *Create a Volume*: `docker volume create <volume-name>`
   - *Mount a Volume in a Container*: `docker run -v <volume-name>:<container-path> ...`
   - *Inspect a Volume*: `docker volume inspect <volume-name>`

3. **Docker Compose** (for multi-container applications):
   - *Define Services*: Use a `docker-compose.yml` file to define services and their configurations.
   - *Start Compose*: `docker-compose up`
   - *Stop Compose*: `docker-compose down`
   - *Scale Services*: `docker-compose up --scale <service-name>=<num-instances>`

4. **Dockerfile Directives**:
   - *FROM*: Specify the base image.
   - *RUN*: Execute commands during image build.
   - *COPY* and *ADD*: Copy files into the image.
   - *WORKDIR*: Set the working directory.
   - *EXPOSE*: Expose ports.
   - *CMD* and *ENTRYPOINT*: Specify the default command when a container starts.

5. **Docker Registry**:
   - *Push an Image to a Registry*: `docker push <registry>/<image-name>`
   - *Pull an Image from a Registry*: `docker pull <registry>/<image-name>`

6. **Docker Swarm** (for orchestration):
   - *Initialize a Swarm*: `docker swarm init`
   - *Join a Swarm*: `docker swarm join`
   - *Create Services*: Define and manage services in a swarm.
   - *Deploy Stacks*: Use Docker Compose files to deploy multi-service applications in a swarm.

7. **Docker Security**:
   - *Docker Content Trust*: Enable content trust to verify the authenticity of images.
   - *Docker Security Scanning*: Scan images for vulnerabilities.

8. **Docker Machine** (for managing Docker hosts):
   - *Create a Docker Machine*: `docker-machine create <machine-name>`
   - *SSH into a Machine*: `docker-machine ssh <machine-name>`
   - *Manage Machines*: Start, stop, and list Docker machines.

9. **Docker Build Context**:
   - Use `.dockerignore` to exclude files and directories from the build context.
   - Use `-f` to specify a different Dockerfile location.

10. **Docker Executables**:
    - Use `docker cp` to copy files between a container and the local filesystem.
    - Use `docker export` to export a container's filesystem as a tarball.
