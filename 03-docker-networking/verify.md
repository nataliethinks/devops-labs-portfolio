# Verification

## Access web container
- Open browser: http://localhost:8080
- Expected result: Nginx welcome page

## Verify container-to-container networking
```bash
docker exec -it alpine-container ping web-container
