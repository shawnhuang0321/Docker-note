# Docker Note

### Terminology

- __Images__ :
  The blueprints of our application which form the basis of containers.
- __Containers__ :
  Created from Docker images and run the actual application.
  
### Command

`docker run [image name]`

`docker pull [image name]`

`docker images`

`docker run [image name] echo "hello world"`

`docker ps`

`docker ps -a`

`docker run -it [image name] sh`

`docker rm [container ID]`

`docker rm $(docker ps -a -q -f status=exited)`

`docker container prune`

`docker run -p 8888:8000 [image name]`
第一個 port 8888 是本機，第二個 port 8000 是 container 的 port

`docker port [image name]`

`docker stop [image name]`

`docker build . -t [name]`


