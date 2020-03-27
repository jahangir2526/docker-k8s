# Simple Python App

This is is simple Hello World python app. This is used to demonstrate how to build a docker image and run python app.

  Below are the steps to follow:
    - Make sure docker is installed
    - Build the image
    - Run the app in a container
    
## Make sure docker is installed
  docker version
  
## Build the image
  docker build -t hello-world-python:v1 .

## Run the app in a container
  docker run hello-world-python:v1
  
  
