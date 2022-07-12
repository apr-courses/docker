# Docker

## Install [Docker Desktop](https://www.docker.com/get-started/) based on your OS.

## Run docker getting-started image
```bash
docker run -d -p 80:80 docker/getting-started
```

Open [localhost:80](http://localhost:80) in your browser.

## Change the docker port
```bash
docker run -d -p 8080:80 docker/getting-started
```

Open [localhost:8080](http://localhost:8080) in your browser.

## Stop and remove the container
```bash
docker ps  // (see the list of containers and their ID)
docker stop containerID // (check the website in browser)
docker kill container ID
docker ps // (the container should be removed)
```
