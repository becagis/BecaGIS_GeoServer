# BecaGIS_GeoServer
## Setup
Start docker service

```shell
docker compose up -d
```

Remove docker service

```shell
docker compose down
```

Remove docker service and data

```shell
docker compose down -v
```

View volumes `\\wsl$\docker-desktop-data\data\docker\volumes\`

## Plugins
- [STABLE_EXTENSIONS](https://github.com/kartoza/docker-geoserver/blob/master/build_data/stable_plugins.txt)
- [COMMUNITY_EXTENSIONS](https://github.com/kartoza/docker-geoserver/blob/master/build_data/community_plugins.txt)