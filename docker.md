#### To build the docker image

```
docker build -t <image-name>:<version> .
```

#### To list all available images in docker

```
docker images
```

which will give data like this:
```
REPOSITORY     TAG       IMAGE ID       CREATED         SIZE
learn_docker   1.0       8a53f2f0b28a   3 minutes ago   1.28GB
```

#### To remove docker image

```
docker image rm [options] IMAGE <image id>
```

Options:
