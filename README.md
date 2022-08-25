# docker-utils

### List all containers
```docker ps -a```

### Remove all containers
```docker rm $(docker container ps -aq) --force```

### Create and open bash
```docker run -it fedora bash```

## Persist container data

### Bind mount (filesystem)
```docker run -it --mount type=bind,source=/home/my_user,target=/app ubuntu:latest bash```

### Volume
```docker run -it --mount source=my_volume,target=/app ubuntu:latest bash```
