# education-docker-basics #

__Link to official DockerHub repo for php:__

https://hub.docker.com/_/php/

__Build an image from a Dockerfile__

`docker build -t hello-world .`

__Docker runs processes in isolated containers. A container is a process which runs on a host. The host may be local or remote.__

`docker run -p 80:80 hello-world`

__Create a bind mount - Volume (shared filesystems)__

`docker run -p 80:80 -v /Users/Muttalip/GitHub/education-docker-basics:/var/www/html/ hello-world`

__List of Docker commands__

`docker runz – Runs a command in a new container.

`docker start` – Starts one or more stopped containers

`docker stop` – Stops one or more running containers

`docker build` – Builds an image form a Docker file

`docker pull` – Pulls an image or a repository from a registry

`docker push` – Pushes an image or a repository to a registry

`docker export` – Exports a container’s filesystem as a tar archive

`docker exec` – Runs a command in a run-time container

`docker search` – Searches the Docker Hub for images

`docker attach` – Attaches to a running container

`docker commit` – Creates a new image from a container’s changes
