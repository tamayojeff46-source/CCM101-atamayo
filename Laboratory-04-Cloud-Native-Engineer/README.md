# Laboratory Activity 4: Cloud-Native Engineer - Docker Deployment & Container Lifecycle

## Mission Overview
This laboratory activity focuses on core cloud-native engineering principles, specifically setting up a Docker environment, deploying web servers, and managing the complete container lifecycle.

## Objectives
* Verify Docker installation and environment configuration.
* Pull, deploy, and test an Nginx web server inside a container.
* Execute and document container lifecycle commands (`docker ps`, `stop`, `rm`).

## Docker Commands Executed
* `docker --version`
* `docker info`
* `docker pull nginx`
* `docker run -d -p 8080:80 --name my-web-server nginx`
* `curl http://localhost:8080`
* `docker ps`
* `docker stop my-web-server`
* `docker ps -a`
* `docker rm my-web-server`

## Skills Learned
* Managing container states, networking ports, and lifecycle operations using the Docker CLI.
* Documenting technical configurations and commands inside Markdown files for reproducibility.

## Challenges Encountered
* Ensuring proper formatting and syntax for Markdown documentation and verifying terminal output states during container lifecycle execution.
