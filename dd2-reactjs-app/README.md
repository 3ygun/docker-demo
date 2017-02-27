# dd2-reactjs-app

Dockerizing [Newpath React App Demo](https://github.com/atareshawty/newpath-react-app-demo) with was the [presented](https://github.com/newpathosu/schedule) at Newpath a few weeks back!

# Execursizes 
## Making from scratch

See the [Dockerfile](newpath-react-app-demo/Dockerfile-Self-Install)

```BASH
# Place into the cloned demo app
# Rename to Dockerfile  : mv Dockerfile-Self-Install Dockerfile 
docker build -t dd2-i
docker run -it -v $pwd`:/app/ -p 3000:3000 dd2-f /bin/bash
```

## Making with Docker Hub content

See the [Dockerfile](newpath-react-app-demo/Dockerfile-Docker-Hub)

```BASH
# Place into the cloned demo app
# Rename to Dockerfile  : mv Dockerfile-Docker-Hub Dockerfile 
docker build -t dd2-dh .
docker run -it -v $pwd`:/app/ -p 3000:3000 dd2-dh /bin/bash
```

## Making with Docker Compose

See the [docker-compose.yml](newpath-react-app-demo/dockerfile-compose.yml)

```BASH
# Rename to docker-compose.yml : cp docker-compose-final.yml docker-compose.yml
# To build and start the server
docker-compose up
```
