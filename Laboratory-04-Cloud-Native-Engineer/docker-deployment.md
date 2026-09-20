# Docker Deployment and Container Lifecycle Documentation

## Checkpoint 3: Docker Environment Verification
* `docker --version`
* `docker info`

## Checkpoint 4: Deploying Nginx Web Server
1. `docker pull nginx`
2. `docker run -d -p 8080:80 --name my-web-server nginx`
3. `curl http://localhost:8080`

## Checkpoint 5: The Container Lifecycle
1. `docker ps` - This command lists all currently running containers to check their active status and assigned ports.
2. `docker stop my-web-server` - This command gracefully stops the running Nginx container by sending a SIGTERM signal.
3. `docker ps -a` - This command displays all containers (both running and stopped) to verify that the container has successfully stopped.
4. `docker rm my-web-server` - This command completely removes and deletes the stopped container from the system to free up resources.
