# Docker Commands
<p align="center">
<img src="https://user-images.githubusercontent.com/75911392/210276325-68a1f015-9777-4e12-a894-95cb4a68ddff.png" class="center"/>
</p>


| Commands                                    | Description                                       | Example                                               |                                                                                         
| --------------------------------------------| --------------------------------------------------|-------------------------------------------------------|
| `docker version`                            | Show the Docker version information
| `docker pull <image_name>`                  | Pull an image or a repository from a registry     | `docker pull ubuntu`  
| `docker run <image_name>`                   | Run a command in a new container                  | `docker run ubuntu`
| `docker ps` or `docker container ls`        | List only shows running containers by default
| `docker ps -a`, `docker ps --all` or `docker container ls -a`| List all running or not running containers
| `docker images`                             | List the most recently created images
| `docker rmi <image_name>` or `docker rmi <image_id>`| Remove the docker image                    | `docker rmi ubuntu`
| `docker run -it <image_name>`               | Run docker image and enter docker image's container| `docker run -it ubuntu`
| `docker run --name <create_container_name> -it <image_name`| Run a container named using the docker image | 
| `exit`                                      | Exit docker container                              |

