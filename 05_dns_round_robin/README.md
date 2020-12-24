## DNS Round Robin
Multiple containers respond to the same NDS address

### Scenarios
- Create network  
  `docker network create dude`  
- Run 2 elasticsearch containers  
  `docker container run -d --net dude --net-alias search elasticsearch:2`  
  `docker container run -d --net dude --net-alias search elasticsearch:2`  
- Run curl a few times, it should get response from different containers (take a look at "name" in the response)  
  `docker run container --rm --net dude centos -s curl search:9200`  

