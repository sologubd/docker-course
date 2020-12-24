## Networking
[Networking Overview](https://docs.docker.com/network/)
### Useful commands
- List networks  
`docker networks ls`  
- Inspect network  
`docker network inspect <network-name>`  
- Create a network  
`docker network create --driver <network-name>`
- Connect a container to a network  
`docker network connect <network-name> <container-name>`
- Disconnect a container from a network  
`docker network disconnect <network-name> <container-name>`

