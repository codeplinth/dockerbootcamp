https://www.youtube.com/watch?v=wi-MGFhrad0&list=PLhW3qG5bs-L99pQsZ74f-LC-tOEsBp2rK

## Docker commands

**docker verson**
Show docker version , engine information

**drocker -v**

show the version of the docker installed

**docker info**

Show docker system wide information

**docker command --help**

show help for docker coomand

**docker images**

list the docker images

**docker pull image:latest**

pull lastest image from docker hub

**docker pull image:tag**

pull the image with tag

**docker rmi image**

remove docker image

**docker run -it image**

Run image in interactive mode

**docker run --name myimage -it image**

Run image with imagename in interactive mode

**docker stop myimage**

stop running container by name or id

**docker start myimage**

start running container by name or id

**docker top myimage**

list processes running in myimage container

**docker stats**

show resources used by containers

**docker ps**

list running containers

**docker ps -a**

list all containers

**Jenkins on docker**

docker pull jenkins/jenkins:lts

docker run --name myjenkins -u 0 -d -p 8080:8080 -p 50000:50000 -v /home/kali/projects/playground/learn_docker/jenkins_home:/var/jenkins_home jenkins/jenkins

cat jenkins_home/secrets/initialAdminPassword




