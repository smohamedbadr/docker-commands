# docker-commands
#Docker Installation and basis commands
Docker on Windows 10:
https://docs.docker.com/docker-for-windows/install-windows-home/
https://docs.docker.com/docker-for-windows/wsl/
Linex Kernal:
https://docs.microsoft.com/en-us/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package

commands:

docker ps

docker pull postgres

docker images

docker pull redis

docker images

docker run redis

ctrl c

docker ps

docker start "container id"

docker stop "container id"

docker pull redis:5.0

docker images

docker run redis:5.0

docker ps -a

port already in use:

docker run -p9000:6379 redis
docker run -p9000:6379 redis:4.0 (issue port already in use)
docker run -p9001:6379 redis:4.0 runs without any issues


docker logs "container id"


