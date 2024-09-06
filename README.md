# Setup Wireguard and Docker

This includes:

- [Wireguard](https://github.com/linuxserver/docker-wireguard)
- Pihole (latest)
- Caddy (to supports ssl access to pihole manager)

## Installation

You need install `wireguard` in your server first then run the docker command after.

```bash
docker-compose -f docker-compose.yml up -d
```

## Config

You will need update `Caddyfile` to your domain; it uses localhost as default.

## Show peer

```bash
docker exec -it wireguard /app/show-peer <id or name>
```
