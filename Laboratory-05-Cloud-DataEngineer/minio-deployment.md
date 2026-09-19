## Checkpoint 5 - Technical Documentation 

# MinIO server command:

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
pgsty/minio:latest server /data --console-address ":9001"
```

# Web Console Access
Port 9001 accesses the web console.

# Bucket Name
The bucket name is client-photos

# Environment Variables Explanation
The -e flags pass environment variables to the container. They configure the root username and password. This secures the MinIO server and enables administrator login.