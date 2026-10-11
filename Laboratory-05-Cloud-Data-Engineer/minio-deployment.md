# MinIO Object Storage Deployment Documentation

## 1. Deployment Command
The MinIO container was deployed using the following Docker run command:

\`\`\`bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
  -e "MINIO_ROOT_USER=cloudadmin" \
  -e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
  minio/minio:latest server /data --console-address ":9001"
\`\`\`

## 2. Web Console Access Port
- **Port 9001** was configured and used to access the MinIO Web Console interface via the KillerCoda Traffic/Ports forwarding mechanism.
- Port 9000 handles S3 API calls, while port 9001 hosts the administrative browser interface.

## 3. Bucket Details
- **Bucket Name:** `client-photos`
- **Initial Object Uploaded:** `container-lifecycle.png` (verified and stored in the root of the bucket)

## 4. Role of the Environment Variables (`-e` flags)
The `-e` flags pass key runtime environment variables into the container environment:
- **`MINIO_ROOT_USER=cloudadmin`**: Sets the root superuser identity (administrative access key) for the MinIO instance.
- **`MINIO_ROOT_PASSWORD=CloudNova2026!`**: Configures the root secret key (password) required for authenticating both the S3 API and the Web Console.
