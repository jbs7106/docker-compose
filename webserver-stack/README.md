# Webserver Stack
- NGINX Proxy Manager
- Cloudflared
- Apache-PHP
- MariaDB
- phpMyAdmin
- DDNS Updater
  
#### Install Portainer (optional) 
- https://docs.portainer.io/start/install-ce

#### Create Network
```
docker network create -d bridge nginx-proxy
```
#### Deploy Stack
```
docker compose up -d
```
