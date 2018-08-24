# jigg-dockers

Build only a container of external software. JIGG is not built in this container.

[Docker Hub Repository](https://hub.docker.com/r/jigg/jigg-dockers/)

## Build container

```
docker build -t {image name}:{tag} -f dockers/knp/Dockerfile
```

## Pull image

```
docker pull jigg/jigg-dockers:knp
```