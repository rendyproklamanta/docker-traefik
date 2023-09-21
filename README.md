### Deploy Traefik
```
docker network create traefik-network
docker-compose up -d -f traefik/docker-compose.yml
```

### Deploy App
```
docker-compose up -d -f apps/whoami/docker-compose.yml
```