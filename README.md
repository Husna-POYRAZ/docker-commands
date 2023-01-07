# Docker Commands
<p align="center">
<img src="https://user-images.githubusercontent.com/75911392/210276325-68a1f015-9777-4e12-a894-95cb4a68ddff.png" class="center"/>
</p>


| Commands                                    | Description                                       | Example                                               |                                                                                         
| --------------------------------------------| --------------------------------------------------|-------------------------------------------------------|
| `docker version`                            | Show the Docker version information
| `docker pull <image_name>`                  | Pull an image or a repository from a registry     | `docker pull ubuntu`  
| `docker run <image_name>`                   | Run a command in a new container                  | `docker run ubuntu`
| `docker run <image_name>:<image_version>`   | Run a command in a new container with the specified version | `docker run ubuntu:20.04`
| `docker run --detach <image_name>` or `docker run -d <image_name>`| Run container in background and print container ID | `docker run -d redis`
| `docker --attach <container_id>` or `docker -a <container_id>` | Attach to STDIN, STDOUT or STDERR    | `docker --attach 9cd`
| `docker container logs <container_id>`      | Fetch the logs of a container                     | `docker container logs 9cd`
| `docker run <image_name> sleep <wait_time>` | Run a command in a new container until the wait time | `docker run ubuntu sleep 10`
| `docker run -it <image_name>`               | Run command in a new container and get inside that container| `docker run -it ubuntu`
| `docker run --name <create_container_name> -it <image_name`| Assign the container name using the image, run and get inside that container| `docker run --name bash_ubuntu -it ubuntu`
| `docker start <container_name>`             | Start one or more stopped containers with container name | `docker start bash_ubuntu`
| `docker stop <container_name>` or `docker stop <container_id>`             | Stop one or more stopped containers with container name/id  | `docker stop bash_ubuntu`
| `docker rm <container_name>`or `docker rm <container_id>`                  | Remove one or more containers with container name/id | `docker rm bash_ubuntu`
| `docker container rm $(docker container ls -aq)`                           | Remove all running or not running containers 
| `docker ps` or `docker container ls`        | List only shows running containers by default
| `docker ps -a`, `docker ps --all` or `docker container ls -a`| List all running or not running containers
| `docker images`                             | List the most recently created images
| `docker rmi <image_name>` or `docker rmi <image_id>`| Remove the docker image                    | `docker rmi ubuntu`
| `docker image tag <image_name> <create_tag_name>`   | Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE | `docker image tag ubuntu my-ubuntu`
| `exit`                                      | Exit docker container                              |

