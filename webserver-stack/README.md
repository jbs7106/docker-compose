# Webserver Stack
- [Nginx Proxy Manager](https://nginxproxymanager.com)
- [Cloudflared](https://developers.cloudflare.com/cloudflare-one/networks/connectors/cloudflare-tunnel/)
- [Apache-PHP](https://github.com/thecodingmachine/docker-images-php)
- [MariaDB](https://mariadb.org)
- [phpMyAdmin](https://www.phpmyadmin.net)
- [DDNS Updater](https://github.com/qdm12/ddns-updater)
  
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
