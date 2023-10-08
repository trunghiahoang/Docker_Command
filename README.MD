# Docker Basic Commands

Below are some basic Docker commands for managing containers and images.

1. **Check Docker Version**
   ```sh
   docker --version
   ```

2. **Display Docker Information**
   ```sh
   docker info
   ```

3. **Run a Container**
   ```sh
   docker run <image>
   ```

4. **List Running Containers**
   ```sh
   docker ps
   ```

5. **List All Containers**
   ```sh
   docker ps -a
   ```

6. **List Available Images**
   ```sh
   docker images
   ```

7. **Pull an Image**
   ```sh
   docker pull <image>
   ```

8. **Build an Image**
   ```sh
   docker build -t <tag> <path>
   ```

9. **Stop a Container**
   ```sh
   docker stop <container>
   ```

10. **Start a Container**
    ```sh
    docker start <container>
    ```

11. **Restart a Container**
    ```sh
    docker restart <container>
    ```

12. **Remove a Container**
    ```sh
    docker rm <container>
    ```

13. **Remove an Image**
    ```sh
    docker rmi <image>
    ```

14. **Execute a Command in a Container**
    ```sh
    docker exec -it <container> <command>
    ```

15. **View Container Logs**
    ```sh
    docker logs <container>
    ```

16. **List Docker Networks**
    ```sh
    docker network ls
    ```

17. **List Docker Volumes**
    ```sh
    docker volume ls
    ```

18. **Run Docker Compose**
    ```sh
    docker-compose up
    ```

19. **Stop Docker Compose**
    ```sh
    docker-compose down
    ```

Feel free to copy and paste this content into a Markdown file named "file.md" and save it for your reference. You can use a text editor or a Markdown editor to work with Markdown files.
