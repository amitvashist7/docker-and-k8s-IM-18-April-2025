    1  docker version 
    2  docker images 
    3  docker rm $(docker ps -qa) 
    4  docker rmi $(docker images -q) 
    5  docker images 
    6  docker ps 
    7  docker run ubuntu echo "Welcome to the world of Docker" 
    8  docker ps 
    9  docker ps -a 
   10  docker images 
   11  docker run ubuntu cat /etc/os-release 
   12  cat /etc/os-release 
   13  docker run ubuntu:20.04 cat /etc/os-release 
   14  docker images 
   15  docker run ubuntu:focal cat /etc/os-release 
   16  docker images 
   17  ls
   18  cd docker-and-k8s-IM-18-April-2025/
   19  ls
   20  history 
   21  mkdir Day1/01-Docker-Introduction
   22  mkdir Day1/01-Docker-Introduction -p 
   23  history > Day1/01-Docker-Introduction/README.md 
