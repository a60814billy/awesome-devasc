# All command you should known about docker in DEVASC exam

1. list local images
- `docker images`
- `docker image ls`

2. list containers (including running and stopped)
- `docker ps`
- `docker ps -a`

3. container control command (stop and remove)
- `docker stop container_id`
- `docker rm container_id`

4. run a container (include common uses flags)
- `docker run -t -i -p 8080:80 image:tag command`
- `docker run -d -ti -P image:tag`

5. build an image
- `docker build -t name:tag ./`

6. image management (remove local image)
- `docker image rm name:tag`
- `docker rmi name:tag`
