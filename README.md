# n8n-docker-caddy-postgres
This will help setup n8n with Caddy and Postgres 14

## Quick Setup
### Create volumes
```
docker volume create n8n_data
docker volume create caddy_data
docker volume create db_data
```

### Edit files
- [ ] .env  
- [ ] caddy_config/Caddyfile  

### Start Containers
```
docker compose up -d
```
