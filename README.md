# What's this 

This repository is to make c/c++ environment with docker.

# Usage

- move into working dir
- build image and create container

```{shell}
$ docker-compose up -d
```

- get into the container

```{shell}
$ docker container exec -it cenv_simple /bin/sh
```