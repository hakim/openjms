# Docker file for openjms
This is a dockerfile for building an openjms server used to communited between java developped microservices.
Instructions:
1. Download the project
2. Download JDK package (specified in the dockerfile) and put it in the same project directory 
2. Go to the project directory and build the image using the follwing command: 
  <code> $docker build . -t openjms </code>
# docker image available in dockerhub 
you can pull an already buit docker image from my repo in dockerhub using the follwing 
<code> docker pull abhakim1980/myopenrepo:openjms </code>
