# Testing docker

- Node: 16.13
- npm: 8.1.2
- Task runner: Parcel (for demonstration purposes)

### Development:

- When running for the first time:

```
docker-compose build
docker-compose up
```

- If you apply changes to the DockerFile or docker-compose:

```
docker-compose up --build
```

### Production:

```
docker-compose run node yarn build
```
