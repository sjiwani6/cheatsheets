# Docker Cheatsheet

## Overview

Docker allows you to run applications in a container rather than trying to run it on your own machine. When running, a Docker image can be used to create a single environment for the software to run on. More information [here](https://docs.docker.com/get-started/overview/).

## Keywords
**Container** - a running image  
**Image** - template that specifies instructions and settings for the Docker container that will be created  

## Useful Commands
<code>docker search [image-name]</code> -> Search for Docker images with corresponding name.  
<code>docker run [-d] [image-name]</code> -> Runs a Docker image to create a container. The -d flag says the command will be ran in the background. Additionally, by default, the latest Docker image will be ran. To change the version, add <code>:version_no</code> to the end of the image name.  
<code>docker ps</code> -> Lists all running containers. 

## References
1. [Docker docs](https://docs.docker.com/get-started/overview/)
2. [Docker Tutorials from O'Reilly](https://www.katacoda.com/courses/docker)