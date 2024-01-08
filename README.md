# Laradock's Workspace Base Image

[Contribution Guide](http://laradock.io/contributing/#edit-base-image).

[Workspace Docker Hub Repository](https://hub.docker.com/r/laradock/workspace/)

[Laradock Github Repository](https://github.com/Laradock/laradock).

# How to
```
docker build -t ssglopes/workspace:latest-8.3 -f Dockerfile .
docker login -u "ssglopes" -p "password" docker.io
docker push ssglopes/workspace:latest-8.3
```