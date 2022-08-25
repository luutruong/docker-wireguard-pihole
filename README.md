# Setup Wireguard and Docker

This includes:

- Wireguard
- Pihole (latest)
- Caddy (to supports ssl access to pihole manager)

## Installation

```bash
docker-compose -f docker-compose.yml up -d
```

## Config

You will need update `Caddyfile` to your domain; it uses localhost as default.
