# Docker Compose Technical Guide

## Role of the `services:` Block
The `services:` block defines the distinct containerized components that make up the multi-tier application stack. In this deployment, it outlines the configuration for two coordinated containers: `database` (MariaDB) and `app` (Nextcloud), specifying their base images, networking rules, port mappings, and runtime variables.

## Service Discovery (`MYSQL_HOST=database`)
Docker Compose establishes a default bridge network connecting all declared containers. Under this internal network, Compose provides automatic DNS service discovery where container hostnames match their service definitions. By assigning `MYSQL_HOST=database`, the Nextcloud container can resolve and query the MariaDB instance directly by name without relying on static internal IP addresses.

## `docker run` vs. `docker-compose up -d`
* **`docker run`**: Spins up a single container directly from the command line. Managing multiple connected containers requires executing individual commands with extensive manual flags for port bindings, volumes, and shared networks.
* **`docker-compose up -d`**: Uses Infrastructure as Code (IaC) principles to read a single declarative YAML file. It provisions, links, and runs the entire multi-tier stack in detached mode with a single command.
