#docker compose demo
create a image from  python  base image
add a litte flask  redis demo app 
build the Dockerfile to create a web image 

create a redis image from  the latest stable official image on dockerhub

create a docker-compose.yml  file that uses 2 services : web and redis (web depends on  redis from  storing a page hit counter)

run  : "docker-compose up"  in the directory where lives the : Dockerfile, docker-compose.yml and the code of the demo app

 



