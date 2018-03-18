# [README.MD](../README.md)
# [DOCKER](DOCKER.md)

## Exemple:
```yaml
version: '3'
services:
  web:
    build: ./
    ports:
      - "5000:5000"
  redis:
    image: "redis:alpine"
    environment:
      DEBUG: 'true
```