# Docker Prometheus Monitoring

[Dockprom](https://github.com/stefanprodan/dockprom) and [Loki Syslog AIO](https://github.com/lux4rd0/grafana-loki-syslog-aio) inspired prometheus monitoring.

## Additions:
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