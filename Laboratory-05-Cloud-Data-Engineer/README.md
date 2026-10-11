# Laboratory 05: Cloud Data Engineer - MinIO Object Storage Deployment

## Mission Overview
Deploy an enterprise-ready, S3-compatible private cloud storage engine using MinIO inside a Docker container. This laboratory simulates configuring on-premise object storage infrastructure, securing access credentials, managing networking ports, and performing bucket administrative tasks using the web console.

## Objectives
- Deploy a standalone MinIO object storage container using Docker with port mappings and root credentials.
- Verify container runtime health and inspect exposed ports.
- Access the MinIO Web Console on port 9001 through port forwarding.
- Administer storage buckets by creating `client-photos` and uploading unstructured binary objects.
- Produce technical system documentation and maintain verified deployment screenshots.

## Tools Used
- **Docker Engine & Docker CLI**: Container lifecycle management, port mapping, and container virtualization.
- **MinIO Object Store**: High-performance, S3-compatible cloud-native object storage service.
- **MinIO Web Console**: Web-based graphical interface for bucket and identity administration.
- **Linux Terminal (KillerCoda)**: Remote cloud sandbox execution environment.
- **Git & GitHub**: Version control and artifact submission repository.

## Skills Learned
- Configuring dual container port forwarding (`9000` for S3 API, `9001` for Console UI).
- Injecting administrative access variables securely using Docker `-e` environment flags.
- Navigating and resolving Docker image registry compatibility and open-source binaries.
- Managing object lifecycles and bucket directories in modern S3-compatible cloud systems.
- Preparing structured Markdown technical documentation and submission assets.
