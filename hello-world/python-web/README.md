# Simple Python Web App
A simple Python Web App (print a Hello World message). This is used to demonstrate how to build a docker image and run Python app as container.

  Below are the steps to follow:
  
  - Make sure docker is installed
  - Build the image
  - Run the app in a container
  - Access the app
    
## 1. Make sure docker is installed
    docker --version
    docker ps
  
## 2. Build the image
    docker build -t hello-world-web-python .

## 3. Run the app in a container
    docker run -p 80:8080 hello-world-web-python  # exposed port 8080 and mapped with 80 at host

## 4. Access the app
    curl http://localhost     ## at docker host
   
