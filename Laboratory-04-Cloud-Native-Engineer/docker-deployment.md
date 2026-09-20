# Docker Deployment and Container Lifecycle Documentation

## Checkpoint 3: Docker Environment Verification
Commands used to verify Docker status in KillerCoda:
* `docker --version`
* `docker info`

*(Save your terminal screenshot as `screenshots/docker-version.png`)*

## Checkpoint 4: Deploying Nginx Web Server
1. Pull the official Nginx image:
   ```bash
   docker pull nginx
2. Run the Nginx container in detached mode and map port 8080:
 ```bash
docker run -d -p 8080:80 --name my-web-server nginx
3. Verify using curl:
 ```bash
curl http://localhost:8080
