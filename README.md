# docker-getting-started

To create/build a Docker image..

`docker build -t friendlyhello .`

Run the app, mapping your machine’s port 4000 to the container’s published port 80 using -p:

`docker run -p 4000:80 friendlyhello`

## Pull and run the image from my remote repository

`docker run -p 4000:80 gopalsaini/get-started:part2`

---

## List Docker CLI commands

docker
docker container --help

## Display Docker version and info

docker --version
docker version
docker info

## Execute Docker image

docker run hello-world

## List Docker images

docker image ls

## List Docker containers (running, all, all in quiet mode)

docker container ls
docker container ls --all
docker container ls -aq