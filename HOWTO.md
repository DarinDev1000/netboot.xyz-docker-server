Copy docker-compose.yml.example to docker-compose.yml
Edit as needed
Run `docker compose up -d netbootxyz` to start containers in the background
Run `docker compose logs -f netbootxyz` to view logs


https://netboot.xyz/docs/docker/usage



To update the image using Docker Compose:
```
docker compose pull netbootxyz     # pull the latest image down
docker compose up -d netbootxyz    # start containers in the background
```