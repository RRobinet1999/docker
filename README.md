# 

# test


# latest = dernière 
FROM ubuntu:lastest

LABEL Author="Teck" Email="remy.teck@toto.com"


RUN apt update


PS Z:\MEGA\Ecole\ISITECH\RPI\GIT> docker build -t ubuntu .


PS Z:\MEGA\Ecole\ISITECH\RPI\GIT> docker login
Login with your Docker ID to push and pull images from Docker Hub. If you don't have a Docker ID, head over to https://hub.docker.com to create one.
Username: teck1254
Password: 
Login Succeeded



FROM ubuntu:latest

LABEL Author="Teck" Email="remy.teck@toto.com"

RUN apt update


docker build -t ubuntu1 .

PS C:\Users\remy> docker stop 0ce
0ce
PS C:\Users\remy> docker start 0ce
0ce
PS C:\Users\remy> docker exec -it admiring_beaver /bin/sh
# exitdocker exec -it 0ce  /bin/sh
PS C:\Users\remy> 
# exit
PS C:\Users\remy> docker  run --name test -ti ubuntu /bin/bash
root@ce858227ca98:/#

# docker
# docker
# docker
# docker
# docker
# docker
# docker
# docker
# docker
