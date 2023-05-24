# docker-compose-adguardhome

A docker compose file for my adguardhome environment.

## Usage 

### Starting

```bash
cd ~/adguardhome      # change to the adguardhome directory
docker compose pull   # pulls the latest image
docker compose up -d  # starts container in detached mode

```

### Stopping

```bash
cd ~/adguardhome     # change to the adguardhome directory
docker compose down  # stops the container
```

### Updating

```bash
cd ~/adguardhome        # change to the adguardhome directory
docker compose pull     # pulls the latest image
docker compose up -d    # restarts the containers with the newer images
docker system prune -a  # deletes any unused images
```

### Uninstall

```bash
cd ~/adguardhome        # change to the adguardhome directory
docker compose down -v  # stops the container and deletes the data volumes
docker system prune -a  # deletes any unused container images
```

## License

MIT

## Author Information

This project was created in 2023 by Graham Lillico.
