# Testing docker

### Dev:

- When running for the first time:

```
docker-compose
```

- Then:

```
docker-compose up
```

- If you apply changes to the DockerFile or docker-compose:

```
docker-compose up --build
```

### Prod

```
docker-compose run node yarn build
```
