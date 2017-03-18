# docker-node-app
Handy Lists of docker commands Raw

##### Pull repo from Docker hub
`docker pull <image>`

##### List Docker images
`docker images`

##### List Docker running containers
`docker ps`

##### List all docker running and non running containers
`docker ps -a`

##### Run a image as container
`docker run -it <image>:<tag> [/bin/bash]` 
* -d for daemon
* --name for name
* -p to expose port  

##### Stop docker container gracefully
`docker stop <container id|name>`

##### Start docker container
`docker start <container id>`

##### kill container immediately
`docker kill <container id>`

##### Output logs from docker container proxying stdout
` docker logs <container id>`

##### exec command on docker container
`docker exec -it /bin/bash`

###### Search images in docker hub
`docker search <search term>`

######  change the name that has been randomly generated for the container
`docker rename <current_container_name> <new_container_name>`

###### take a peek inside our containers
` docker stats <container_name>`

######  list of all running processes inside the container
` docker top <container_name>`

###### Remove container 
`docker rm <container>`
* -v to remove with volume

###### Remove image
` docker rmi <image>`

