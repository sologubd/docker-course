## Testing using Docker
Test `curl` using different linux distro

### Scenarios
- Run centos distro  
`docker container run --rm -it centos:7 bash`  
  Run bash commands:    
  - `yum update curl`
  - `curl --version`
- Run ubuntu distro  
  `docker container run --rm -it ubuntu:14.04 bash`  
  Run bash commands:  
  - `upt-get update && apt-get install -y curl`
  - `curl --version`
- Make sure that containers don't exist  
`docker container ls -a`

### Useful commands
  - Start docker container that is removed automatically  
  `docker container run --rm -it ubuntu:14.04 bash`  
    - **--rm** - Remove the container automatically  

