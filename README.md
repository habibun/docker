## About The Project
[Docker][docker_website] resources for learning and practicing.


## Learn More
- [The Docker Handbook – Learn Docker for Beginners](https://www.freecodecamp.org/news/the-docker-handbook/#how-to-run-a-container)
- [A PHP development environment generator built with Docker containers.](https://phpdocker.io/)
- [Introduction to Containers](https://container.training/intro-selfpaced.yml.html#1)


## Reference

### Docker CLI reference
`docker ps` => List containers

`docker ps -a` => Show all containers

`docker start container_id/container_name` => Start one or more stopped containers

`docker stop container_id/container_name` => Stop one or more running containers

`docker attach container_id/container_name` => Attach local standard input, output, and error streams to a running container

`docker rm container_id/container_name` => Remove one or more containers

`docker logs container_id/container_name` => Fetch the logs of a container

`docker inspect container_id/container_name` => Return low-level information on Docker objects

`docker restart container_name/container_id` => Restart one or more containers

`docker system prune` => Remove unused data

`docker login` => Log in to a Docker registry

`docker tag mycurl username/repository_name:version`

`docker push username/repository_name:version`

    ######Image

`docker run repository_name:tag/image_id` => Run a command in a new container

`docker rmi repository_name:tag/image_id` => Remove one or more images



### Docker Container CLI reference 

`docker container ls` => List containers

`docker container prune` => Remove all stopped containers

`docker container stop CONTAINER` => Stop one or more running containers



### Docker Image CLI reference 

`docker image ls` => List images

`docker image inspect repository_name:tag/image_id` => Display detailed information on one or more images

`docker image history repository_name:tag/image_id` => Show the history of an image

`docker image pull repository_name:tag/image_id` => Pull an image or a repository from a registry

`docker image rm repository_name:tag/image_id` => Remove one or more images

`docker image prune` => Remove unused images



### docker-compose CLI reference

`docker-compose build`

`docker-compose up`

`docker-compose up container_name/container_id`

`docker-compose up -d`

`docker-compose up --build`

`docker-compose rm`

`docker-compose down`



### Docker Volume CLI reference

`docker volume ls`

`docker volume rm volume_name`

`docker volume create --name volume_name`



### Docker network CLI reference

`docker network ls`

`docker network prune`

`docker inspect container_name/container_id`

`docker network create network_name`

`docker run --rm -d --name web-server --network network_name image_name`



**Random CLI**
* `docker run -it ubuntu /bin/bash`
* `docker run -it -d --rm --name ubuntu ubuntu /bin/bash`
* `docker run --rm -v ${PWD}:/myvol ubuntu /bin/bash -c "ls -lha > /myvol/myfile.txt"`
* `docker run --rm klutchell/rar"`
* `docker run --rm -v ${PWD}:/files klutchell/rar a /files/myrar.rar /files/myfile.txt`
* `docker run --rm -v ${PWD}:/files -w /files klutchell/rar a myrar.rar myfile.txt`
* `docker run -it --rm --name my-running-script php:7.2-cli /bin/bash`
* `docker run -it -v ${PWD}:/myfiles --name my-running-script php:7.2-cli /bin/bash`
* `docker run -d httpd`
* `docker exec -it c7467ffffbb0`
* `docker logs c7467ffffbb0`
* `docker logs -f c7467ffffbb0`
* `docker run -d -p 8080:80 httpd`
* `docker run -d -p 8080:80 -v ${PWD}:/var/www/html php:7.2-apache`
* `docker build -t myphpapp .`
* `docker run -p 8080:80 phpapp:web`


**Argument reference**
* `-d` running in the background
* `--rm` remove container
* `--name` name of the container
* `-v`  mount volume
* `-d`  detach mode
* `-w`  working directory
* `-p`  port binding
* `-t`  tagging


---
## License
Distributed under the MIT License. See **[LICENSE][license]** for more information.


[//]: # (Links)
[docker_website]: https://www.docker.com/
[license]: https://github.com/habibun/docker/blob/main/LICENSE
