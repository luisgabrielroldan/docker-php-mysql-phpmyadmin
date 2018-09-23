# Docker: Apache+MySQL+phpMyAdmin

## How to use

Power ON

```
docker-compose up -d
```

Power OFF

```
docker-compose down
```

Power OFF deleting volumes

```
docker-compose down --volumes
```

## Populate database

Add an SQL script in to `./initdb.d'

