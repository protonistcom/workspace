# Laradock's Workspace Base Image

[Contribution Guide](http://laradock.io/contributing/#edit-base-image).  
[Workspace Docker Hub Repository](https://hub.docker.com/r/laradock/workspace/)  
[Laradock Github Repository](https://github.com/Laradock/laradock).

# Preface
This is a fork of the laradock workspace project. 
The reason is to support the newer version of Ubuntu 22.04 whereas the official 
version to date is still based on Ubuntu 20.04.

# How to
Rename any Dockerfile-x.x to Dockerfile and build the image with the below commands
and push them to docker repository.
```
docker build --platform="linux/amd64" -t ssglopes/workspace:latest-8.3 -f Dockerfile .
docker login -u "ssglopes" -p "password" docker.io
docker push ssglopes/workspace:latest-8.3
```