# Docker configs

- mysql

```bash
docker-compose -d -f mysql/docker-compose.yml up
```

- postgres

```bash
docker-compose -d -f postgres/docker-compose.yml up
```

## create network

```
docker network create --driver=bridge --subnet=172.100.0.0/16 my_network
```
