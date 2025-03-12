## Key Concepts

1. **Containers**: A container is like a lightweight virtual machine. It contains everything an application needs (e.g., code, libraries, and environment settings). Containers are isolated but share the host OS kernel, which makes them more efficient than VMs.

2. **Docker Images**: An image is a blueprint for creating containers. It contains the application and everything it needs to run. Images are read-only and can be reused across containers.

3. **Dockerfile**: A file that contains instructions for building a Docker image. It defines the environment for the application, like which base image to use, what files to copy, and which commands to run.

4. **Docker Hub**: A public registry where Docker images are stored. You can pull images from Docker Hub and push your custom images there for sharing.

5. **Docker Compose**: A tool to define and run multi-container applications. You can specify services, networks, and volumes for your application in a YAML file, which Docker Compose uses to set up everything.

6. **Docker Engine**: The software that runs and manages containers on a host machine. It includes the Docker daemon, the Docker CLI, and the Docker API.
