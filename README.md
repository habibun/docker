## About The Project
[Docker][docker_website] resources for learning and practicing.


## CLI Reference
<details>
<summary>Docker</summary>

### Docker CLI reference


```bash
# List running containers
docker ps
``` 


```bash
# List all containers
docker ps -a
```

```bash
# Start stopped containers
docker start container_id/container_name
```

```bash
# Stop one or more running containers
docker stop container_id/container_name
```

```bash
# Attach local standard input, output, and error streams to a running container
docker attach container_id/container_name
```

```bash
# Remove one or more containers
docker rm container_id/container_name
```

```bash
# Fetch the logs of a container
docker logs container_id/container_name
```

```bash
# Return low-level information on Docker objects
docker inspect container_id/container_name
```

```bash
# Restart one or more containers
docker restart container_name/container_id
```

```bash
# Remove unused data
docker system prune 
```

```bash
# Log in to a Docker registry
docker login
```

```bash
# Tag an image
docker tag mycurl username/repository_name:version
```

```bash
# Upload an image to a registry
docker push username/repository_name:version
```

##
</details>


<details>
<summary>Docker Container</summary>

### Docker Container CLI reference

```bash
# List containers
docker container ls 
```

```bash
# Remove all stopped containers
docker container prune
```

```bash
# Stop one or more running containers
docker container stop CONTAINER
```

##
</details>


<details>
<summary>Docker Image</summary>

### Docker Image CLI reference
```bash
# List images
docker image ls
```

```bash
# Display detailed information on one or more images
docker image inspect repository_name:tag/image_id
```


```bash
# Show the history of an image
docker image history repository_name:tag/image_id
```


```bash
# Pull an image or a repository from a registry
docker image pull repository_name:tag/image_id
```


```bash
# Remove one or more images
docker image rm repository_name:tag/image_id 
```


```bash
# Remove unused images
docker image prune
```

##
</details>


<details>

<summary>Docker Compose</summary>

### docker-compose CLI reference

```bash
# Check version
docker compose version
```

```bash
# Logs from each of the services interleaved into a single stream
docker compose logs -f
```
```bash
# Logs from specific services
docker compose logs -f app
```


```bash
# Build or rebuild services
docker compose build
```


```bash
# Create and start containers
docker compose up

# Options
docker compose up -d
docker compose up --build
docker compose up container_name/container_id
```

```bash
# Stop services
docker compose stop

```


```bash
# Removes stopped service containers
docker compose rm
```


```bash
# Stop and remove containers, networks
docker compose down
```
##

</details>


<details>

<summary>Docker Volume</summary>

### Docker Volume CLI reference

```bash
# List volumes
docker volume ls
```

```bash
# Remove one or more volumes
docker volume rm volume_name
```

```bash
# Create a volume
docker volume create --name volume_name
```

##

</details>



<details>

<summary>Docker network</summary>

### Docker network CLI reference

```bash 
# List networks
docker network ls
```

```bash 
# Remove all unused networks
docker network prune
```

```bash 
# Display detailed information on one or more networks
docker inspect container_name/container_id
```

```bash 
# Create a network
docker network create network_name
```

##
</details>


## Learn More
- [Getting Started](https://docs.docker.com/get-started/)
- [What next](https://docs.docker.com/get-started/11_what_next/)
- [The Docker Handbook – Learn Docker for Beginners](https://www.freecodecamp.org/news/the-docker-handbook/)
- [Reference documentation](https://docs.docker.com/reference/)
- [The Docker Handbook – Learn Docker for Beginners](https://www.freecodecamp.org/news/the-docker-handbook/#how-to-run-a-container)
- [A PHP development environment generator built with Docker containers.](https://phpdocker.io/)
- [Introduction to Containers](https://container.training/intro-selfpaced.yml.html#1)


## License
Distributed under the MIT License. See **[LICENSE][license]** for more information.


[//]: # (Links)
[docker_website]: https://www.docker.com/
[license]: https://github.com/habibun/docker/blob/main/LICENSE
