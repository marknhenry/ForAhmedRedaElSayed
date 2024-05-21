# DotNetStarter

[![Mark Henry](https://img.shields.io/static/v1?label=Author&message=Mark%20Henry&color=success)](https://www.linkedin.com/in/marknhenry/) 
[![License](https://img.shields.io/static/v1?label=License&message=MIT&color=blue)](https://www.linkedin.com/in/marknhenry/)

## To Setup A New Project
# First time Setup of Container:
```
docker stop my_instance # stop container
docker rm my_instance # remove container
docker build -t "starter_kit:v1" . # Build the image from Dockerfile
docker run -it -p 8888:8888 -d --name llmbase "starter_kit:v1" # Run container
docker exec -it starter_kit /bin/bash # Log into container
```
# Cloning the repo locally in container:
```
gh auth login
git config --global user.email "xx@xx"
git config --global user.name "Your Name"
gh repo clone xxx\xxx
```
