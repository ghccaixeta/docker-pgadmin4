# docker-pgadmin4

Docker container for execute pgadmin4 WEB and share folder to restore and import dump files



## Setup .env

Rename the .env.example to .env
```
  bash
  cp -av .env{.example,}
```

> You need replace @ by _ on PGADMIN_STORAGE

## Deploy

```bash
  docker compose up -d
```


## Access

http://localhost:8081