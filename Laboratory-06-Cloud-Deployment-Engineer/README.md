# Laboratory 06: Cloud Deployment Engineer

## Mission Overview
Deploys a two-tier private cloud storage solution using Nextcloud and MariaDB orchestrated through Docker Compose as Infrastructure as Code (IaC).

## Objectives
- Deploy and manage a multi-tier containerized stack.
- Author infrastructure specifications using declarative YAML configuration.
- Leverage Docker Compose for local network DNS and container service discovery.
- Document deployment, architecture, and container teardown workflows.

## Commands Executed
- `mkdir nextcloud-deployment && cd nextcloud-deployment`: Created the deployment workspace.
- `nano docker-compose.yml`: Authored the multi-container configuration blueprint.
- `docker-compose up -d`: Provisioned the database and application containers in detached mode.
- `docker-compose ps`: Verified the running state and published ports of the containers.
- `docker-compose down`: Stopped and cleaned up container instances and internal network resources.

## Skills Learned
- Managing multi-container architectures.
- Infrastructure as Code (IaC) with YAML.
- Service discovery and environment variable configuration.
- Container lifecycle management.

## Verification Evidence
- Deployment Verification: `screenshots/compose-deployment.png`
- Web Interface: `screenshots/nextcloud-web.png`
- Teardown Verification: `screenshots/compose-teardown.png`
