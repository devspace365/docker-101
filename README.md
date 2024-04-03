# docker-101
## Basic to intermediate docker commands

To check docker version:
```
docker –version 
```
```
docker -v
```

To start service Docker (Engine):
```
service docker start
```

To stop service Docker (Engine):
```
service docker stop 
```

To automatically start Docker with system boot:
```
systemctl enable docker
```

To check and confirm the service is running:
```
service docker status
```

To check all images available locally:
```
docker images
```

To Pull an image from Docker Hub:
```
docker pull <image_name>
```

Create and start container:
```
docker run -it --name container <image_name> /bin/bash 
```

To see a container info:
```
$ cat /etc/os-release
```

To exit a container
```
exit
```

To list the running container ( ps =Process status )
```
docker ps
```

To list the all container ( running and exited containers )
```
docker ps -a
```

To search an image on Docker Hub:
```
docker search <image_name>
```

To start a container:
```
docker start <container_name>
```

To stop a container:
```
docker stop <container_name>
```

To go inside the container:
```
docker attach <container_name>
```

To remove a container:
```
docker rm <container_name>
```

To see the difference between the base image and changes on it:
```
docker diff <container_name>
```
