#### To build the docker image

```
docker build -t [image-name]:[version] .
```
---

#### To list all available images in docker

```
docker images
```

which will give data like this:
```
REPOSITORY     TAG       IMAGE ID       CREATED         SIZE
learn_docker   1.0       8a53f2f0b28a   3 minutes ago   1.28GB
```
---

#### To remove docker image

```
docker image rm [Options] IMAGE [image id]
```

Options:

| Option  | Short | Description |
| ------------- | ------------- | ------------- |
| `--force` | `-f` | Force removal of the image  |
| `--no-prune` |  | Do not delete untagged parents  |

---

#### To run docker image

```
docker run [image id]
```

Run docker image with custom ports:
```
docker run -p [NEW PORT]:[APP PORT] [image id]
```

Run multiple docker images:
```
docker run -p [NEW PORT]:[OLD PORT] -d [image id]
```

To stop docker container:
```
docker container stop [container_id]
```
