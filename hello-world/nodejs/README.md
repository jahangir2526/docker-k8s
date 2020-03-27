# Simple NodeJS Web App
A simple NodeJS Web App (print a Hello World message). This is used to demonstrate how to build a docker image and run NodeJS app as container.

  Below are the steps to follow:
  
  - Make sure docker is installed
  - Build the image
  - Run the app in a container
    
## 1. Make sure docker is installed
    docker --version
    docker ps
  
## 2. Build the image
    docker build -t hello-world-web-nodejs .

## 3. Run the app in a container
    docker run hello-world-web-nodejs
