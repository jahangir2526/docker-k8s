# Simple Java SE App om GraalVM
A simple Hello World Java SE app running on GraalVM (print a Hello World message). This is used to demonstrate how to build a docker image and run java app on GraalVM as container.

  Below are the steps to follow:
  
  - Make sure docker is installed
  - Build the image
  - Run the app in a container
    
## 1. Make sure docker is installed
    docker --version
    docker ps
  
## 2. Build the image
    docker build -t hello-world-graalvm-java .

## 3. Run the app in a container
    docker run hello-world-graalvm-java
