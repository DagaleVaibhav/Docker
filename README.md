# Docker
Experimenting about adding a custom database using Mysql as a base image
README

  1. Dockerfile and test.sql are being used to build image and create a container.
	
  2. Use following commands:

    i. For building image using Dockerfile:
  	$ sudo docker build -t testsql .

   ii. For Creating a Container using Image:
  
      	$ docker run -d -it -p 3306:3306 --name=testsql testsql 


