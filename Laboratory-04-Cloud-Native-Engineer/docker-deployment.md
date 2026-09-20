# Docker Deployment and Container Lifecycle Documentation

## Checkpoint 3: Docker Environment Verification
* `docker --version`
* `docker info`

## Checkpoint 4: Deploying Nginx Web Server
1. `docker pull nginx`
2. `docker run -d -p 8080:80 --name my-web-server nginx`
3. `curl http://localhost:8080`

## Checkpoint 5: Container Lifecycle Management
* `docker ps`
* `docker stop my-web-server`
* `docker ps -a`
* `docker rm my-web-server`
