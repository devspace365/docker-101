# docker-101
## Basic to intermediate docker commands

To check docker version:

docker –version 

To Start/stop service Docker (Engine):

service docker start/stop 

To check images available locally:

docker images

To Pull Image from Docker hub:

docker pull

Create and Start container:

docker run
***
docker run -it --name container <image name>:1.1 /bin/bash )

To List the Running Container ( ps =Process status )

docker ps

To list the all container ( running and exited containers )

docker ps -a

To Find out the image in Docker Hub:

docker search

To start/stop container:

docker start/stop

To go inside the container:

docker attach

To remove a container

docker rm
