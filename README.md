# education-docker-basics #

__Link to official DockerHub repo for php:__

https://hub.docker.com/_/php/

__Build an image from a Dockerfile__

`docker build -t hello-world .`

__Docker runs processes in isolated containers. A container is a process which runs on a host. The host may be local or remote.__

`docker run -p 80:80 hello-world`

__Create a bind mount - Volume (shared filesystems)__

`docker run -p 80:80 -v /Users/Muttalip/GitHub/education-docker-basics:/var/www/html/ hello-world`
