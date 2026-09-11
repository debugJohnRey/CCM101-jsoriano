# Checkpoint 6 - Technical Documentation

## Mission Overview
This lab explores the shift from Virtual Machines to containers. We deployed an Nginx web server using Docker. We learned how containers save memory and start fast.

## Objectives
* Compare Virtual Machines and containers.
* Access a Docker environment using KillerCoda.
* Run basic Docker commands.
* Manage an Nginx container.
* Write technical documentation in Markdown.

## Docker Commands Executed
| Command | Description |
| :--- | :--- |
| `docker --version` | Checks the Docker version. |
| `docker info` | Shows the Docker environment status. |
| `docker pull nginx` | Downloads the Nginx image. |
| `docker run -d -p 8080:80 nginx` | Runs the server and maps the port. |
| `curl http://localhost:8080` | Tests the local web server. |
| `docker ps` | Lists active containers. |
| `docker stop <container_id>` | Stops the running container. |
| `docker ps -a` | Shows all containers. |
| `docker rm <container_id>` | Deletes the stopped container. |

## Skills Learned
* I learned how to start and stop containers.
* I learned how to map network ports.
* I practiced writing Markdown files.

## Challenges Encountered
* Understanding port mapping took time.
* Remembering exact Docker commands required practice.