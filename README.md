# docker
- There are three parts to represent :
  - client
    1. docker run
    2. docker build
    3. docker pull
       
  - docker host
    1. docker daemon
    2. docker images
    3. docker containers
       
  - registry / docker hub
    1. docker image
    2. we can create image and pull to docker hub
       
   

# Commonly used Docker commands include:

1. docker run - Starts a new container from a specified image.
2. docker build - Builds an image from a Dockerfile.
3. docker pull - Pulls an image from a registry.
4. docker push - Pushes an image to a registry.
5. docker images - Lists all locally stored images.
6. docker ps - Lists running containers (include -a to list all containers).
7. docker stop - Stops a running container.
8. docker start - Starts a stopped container.
9. docker restart - Restarts a container.
10. docker rm - Removes one or more containers.
11. docker rmi - Removes one or more images.
12. docker exec - Executes a command in a running container.
13. docker logs - Fetches the logs of a container.
14. docker inspect - Returns detailed information on containers or images.
15. docker network - Manages networks (with subcommands like create, ls, rm).
16. docker volume - Manages volumes (with subcommands like create, ls, rm).

# docker
- There are three parts to represent :
  - client
    1. docker run
    2. docker build
    3. docker pull
       
  - docker host
    1. docker daemon
    2. docker images
    3. docker containers
       
  - registry / docker hub
    1. docker image
    2. we can create image and pull to docker hub

# Commonly used Docker commands include:

1. docker run - Starts a new container from a specified image.
2. docker build - Builds an image from a Dockerfile.
3. docker pull - Pulls an image from a registry.
4. docker push - Pushes an image to a registry.
5. docker images - Lists all locally stored images.
6. docker ps - Lists running containers (include -a to list all containers).
7. docker stop - Stops a running container.
8. docker start - Starts a stopped container.
9. docker restart - Restarts a container.
10. docker rm - Removes one or more containers.
11. docker rmi - Removes one or more images.
12. docker exec - Executes a command in a running container.
13. docker logs - Fetches the logs of a container.
14. docker inspect - Returns detailed information on containers or images.
15. docker network - Manages networks (with subcommands like create, ls, rm).
16. docker volume - Manages volumes (with subcommands like create, ls, rm).

# docker run springboot project :
  1. package the springboot project to jar
  2. create docker file for jar
  3. run cmd " docker build -t test:1 . -f Dockerfile " to create docker image
  4. run cmd " docker run -d -p 8080:8080 [image id] " to create container and binding the port 8080.

# docker run springboot project with postgre :
TBC


