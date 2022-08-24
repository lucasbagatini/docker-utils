# docker-utils

### List all containers
```docker ps -a```

## Persist container data

### Bind mount (filesystem)
```docker run --mount type=bind,source=/home/my_user,target=/app ubuntu:latest```
