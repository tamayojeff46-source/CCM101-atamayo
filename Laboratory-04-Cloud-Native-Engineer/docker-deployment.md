# Docker Deployment and Container Lifecycle Documentation

## Checkpoint 3: Docker Environment Verification
Commands used to verify Docker status in KillerCoda[cite: 1]:
* `docker --version`
* `docker info`

*(Save your terminal screenshot as `screenshots/docker-version.png`)*[cite: 1]

## Checkpoint 4: Deploying Nginx Web Server
1. Pull the official Nginx image[cite: 1]:

2. Run the Nginx container in detached mode and map port 8080[cite: 1]:

3. Verify using curl[cite: 1]:


*(Save your successful curl output screenshot as `screenshots/nginx-running.png`)*[cite: 1]

## Checkpoint 5: Container Lifecycle Management
* **List running containers:** `docker ps` (Displays all currently active containers.)[cite: 1]
* **Stop the running container:** `docker stop my-web-server` (Gracefully stops the running Nginx container.)[cite: 1]
* **Verify it is stopped:** `docker ps -a` (Shows all containers to confirm the service has stopped.)[cite: 1]
* **Remove the container completely:** `docker rm my-web-server` (Completely removes and deletes the container from the system to free up space.)[cite: 1]

*(Save your lifecycle execution screenshot as `screenshots/container-lifecycle.png`)*[cite: 1]
