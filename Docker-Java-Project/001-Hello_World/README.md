
# Docker Java-Hello-World

This Project consist of a simple java hello world application with a docker file.
  
  This project is really about building an image using Dockerfile.




## Requirements to run this project

The only thing needed to run this project is you have Docker installed on yur machine  
For installation steps for installing docker in your machine can be different.  
Actually it depend on your machine if it is Windows or MAC or Linux the installation process differ.
  

**You can follow official Docker Hub documentation for installation of docker in your machine**  - [Link for Official Documentation to Install Docker](https://docs.docker.com/engine/install/)
  

    


## Command to build Docker Image from file
Go to your Terminal and navigate to the place where docker file is present   
**(Navigating to the place where dockerfile is present is not necessary  it is just easy to build docker images from there.)**
  


**Syntax**
  
   ```
   docker build -t imagename:tag .

   ```

**Command :-**
```
docker build -t java-hello:1.0 .
```

The . (dot) here represents the current directory where Dockerfile is present this is why i recommend to navigate to the folder/directory where Dockerfile is present
## Run the image in a container
for running the image in a container the command is very easy

```
docker run java-hello:1.0
```

After the java hello world project run in container the container will automatically stops.

so we don't have to stop the container explicitly.


## This Image-Repository

The image created from this Dockerfile is present inside my Docker Hub repository by the name   
**gautamjha3112002
/
java-hello-world**

You can check it out on my DockerHub accout :- - [My Dockerhub account](https://hub.docker.com/u/gautamjha3112002)
