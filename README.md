# Docker-implementation
Docker is a container management service. The keywords of Docker are develop, ship and run anywhere. The whole idea of Docker is for developers to easily develop applications, ship them into containers which can then be deployed anywhere.<br>
<br>
<b>Advantages of docker:</b><br>
1. Environment standardization.
2. Build once deploy anywhere.
3. Isolation.
4. Portability.
<br>
First we will download the required base image from the docker hub than add all the necessary components (Anaconda python 3.6 environment, Flask, Flasgger, Pickle etc). Once all the required components are added we will encapsulate it together and this is called docker image. Once the docker image is created we dockerize it and take into any othe similar base environment and install there.<br>
<br>
The official site for Docker is https://www.docker.com/ The site has all information and documentation about the Docker software. It also has the download links for various operating systems.<br>
<br>
<b>Commands:</b><br>
<br>
1. FROM - To create base image.<br>
2. COPY- Copy from host to user/root in docker image.<br>
3. EXPOSE - For network interface (Port number).<br>
4. WORKDIR- user/root (path in the base image).<br>
5. RUN - install dependent libraries.<br>
6. CMD - To make the application run.<br>
All the above commands will be used in Dockerfile.<br>
<br>
<b>Docker Hub − </b>Docker Hub is a registry service on the cloud that allows you to download Docker images that are built by other communities. You can also upload your own Docker built images to Docker hub.<br>
<br>
<b>Docker Images - </b>In Docker, everything is based on Images. An image is a combination of a file system and parameters.<br>
<br>
<b>Displaying Docker Images</b><br>
To see the list of Docker images on the system, you can issue the following command:<br>
<b>Syntax:</b><br>
docker images<br>
This command is used to display all the images currently installed on the system.<br>
<br>
<b>Removing Docker Images:</b><br>
The Docker images on the system can be removed via the docker rmi command.<br>
<b>Syntax:</b><br>
docker rmi ImageID<br>
<b>Options:</b><br>
ImageID − This is the ID of the image which needs to be removed.<br>
<br>
<b>Docker Containers - </b>Containers are instances of Docker images that can be run using the Docker run command. The basic purpose of Docker is to run containers.
