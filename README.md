# Docker Prometheus Monitoring

[Dockprom](https://github.com/stefanprodan/dockprom) inspired prometheus monitoring.

## Additions:
- Loki with promtail
- Caddy with cloudflare dns
- Exposed cAdvisor web interface
- Environment variables based config

## Requirements

- Own wildcard domain set up on cloudflare dns

## Environment Variables

- APP_DIR
- ADMIN_USER
- ADMIN_PASSWORD
- CLOUDFLARE_EMAIL
- CLOUDFLARE_API_TOKEN
- MON_DOMAIN