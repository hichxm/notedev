# [README.MD](../README.md)

## Construire une image depuis [Dockerfile](DOCKERFILE.md):
```docker
docker build -t name/repo .
```

## Lancé une image depuis un build:
```docker
docker run -rmt image
```
ou
```docker
docker run -rmt name/repo
```

## Lancé un [docker-compose](DOCKERCOMPOSE.md):
```docker
docker-compose up
```

## Supprimer une image:
```docker
docker rmi image -f
```

## Supprimer toute les images:
```docker
docker rmi $(docker images -q) -f
```

### Link

[hub.docker.com](https://hub.docker.com/)

[docs.docker.com](https://docs.docker.com/)