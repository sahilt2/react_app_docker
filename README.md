## Docker Practice

This is just a simple practice to use react app in docker.

### Steps

- Create Docker file in root
- run

```shell
docker build --tag react_app-docker .
```

- check th images in docker dashboard or using command :

```shell
docker images
```

- run:

```shell
docker run —publish 3009:3000 react_app_docker

```

- create "docker-compose.yml" file
- build docker image:

```shell
docker-compose build
```

```shell
docker-compose run app
```

- create container:

```shell
docker-compose up
```

### Docker Hub

- login to docker hub

```shell
docker login -u sahilt2
```

- enter docker hub password
- create tag:

```shell
docker image tag react_app_docker sahilt2/react_app_docker:0.1.0
```

- push image

```shell
docker image push sahilt2/react_app_docker:0.1.0
```
