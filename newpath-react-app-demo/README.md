# Newpath React App Demo

Dockerizing [Newpath React App Demo](https://github.com/atareshawty/newpath-react-app-demo)!

# Execursizes 
## Making from scratch

See the [Dockerfile](newpath-react-app-demo/Dockerfile-Self-Install)

```BASH
# Place into the cloned demo app
# Rename to Dockerfile  : mv Dockerfile-Self-Install Dockerfile 
docker build -t np-react-f
docker run -it -v $pwd`:/app/ -p 3000:3000 np-react-f /bin/bash
```

## Making with Docker Hub content

See the [Dockerfile](newpath-react-app-demo/Dockerfile-Docker-Hub)

```BASH
# Place into the cloned demo app
# Rename to Dockerfile  : mv Dockerfile-Docker-Hub Dockerfile 
docker build -t np-react-dh
docker run -it -v $pwd`:/app/ -p 3000:3000 np-react-dh /bin/bash
```
