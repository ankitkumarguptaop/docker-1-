Why we use docker?
To package and run applications in lightweight, isolated environments called containers, simplifying deployment, scaling, and management of software across different environments, leading to faster development cycles and consistent operation.

Docker image vs container 
Images like operating system
Container helps to run image 


Run image on container 
docker run -it ubuntu  {it id for opening the environment}
Find docker running containers 
docker container ls
Find docker all containers 
docker container ls -a
Start any container 
docker start <container name> /id
Stop any container 
docker stop <container name> /id
Execute any command inside the container ( and gets disconnects)
PS C:\Users\info> docker exec <container_name> <container_insider_command>
Execute any command inside the container ( and gets  not disconnects)
PS C:\Users\info> docker exec  -it <container_name> <container_insider_command>



in docker 
docker pull rabbitmq:management (image)


docker run -it --name rabbitmq -p 5672:5672 -p 15672:15672 sha256:31e292362ff145b383b308fe904778bf6cd9c7475813b5ed76ade67314a69885
