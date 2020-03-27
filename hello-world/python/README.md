# Simple Python App
A simple Hello World python app (print a Hello World message). This is used to demonstrate how to build a docker image and run python app as container.

  Below are the steps to follow:
  
  - Make sure docker is installed
  - Build the image
  - Run the app in a container
    
## 1. Make sure docker is installed
    docker version
  
## 2. Build the image
    docker build -t hello-world-python:v1 .

## 3. Run the app in a container
    docker run hello-world-python:v1
  
  
