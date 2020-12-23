## Create an image with nginx
  - [Default image registry](https://hub.docker.com)

### Useful commands
  - Start a container  
  `docker container run -p <host_port>:<container_port> -d --name <container_name> <base_img>`  
    - **-p|--publish**  - list of published ports
    - **-d|--detach**   - run container in background
    - **--name**        - assign a name to the container
  - Stop the container  
  `docker container stop <container-id>`
  - List containers  
  `docker container ls [-a]`
  - View logs  
  `docker container logs *<container-name>*
  - Remove container  
  `docker container rm -f <container-id1> <container-id2>`
    - **-f|--force  - force remove (if a container is being used)

### Image vs Container
  - An Image is the app we want to run
  - A Container is an instance of that app

