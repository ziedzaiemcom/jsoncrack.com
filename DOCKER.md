# JSON Crack (jsoncrack.com)

Fork of https://github.com/AykutSarac/jsoncrack.com

This project adds Docker integration to run on own infrastructure or in isolated environments.

- Github : https://github.com/ziedzaiemcom/jsoncrack.com
- Docker Hub : https://hub.docker.com/r/ziedzaiemcom/jsoncrack.com

You can use [Dive](https://github.com/wagoodman/dive) to inspect Docker image contents.

## Run

```
docker compose build
docker compose up -d
```

## Push to Docker Hub

```
docker login -u ziedzaiemcom
docker tag jsoncrackcom-jsoncrack:latest ziedzaiemcom/jsoncrack.com:0.0.2
docker push ziedzaiemcom/jsoncrack.com:0.0.2
```

### Pull From Docker Hub

```
docker pull ziedzaiemcom/jsoncrack.com:0.0.2

```

Exposed Ports  :
- 8080