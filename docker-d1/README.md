# What does Docker mean?

Lets make a basic Ubuntu container with a `Dockerfile` and look!

# Setup

```BASH
# Notice: This echo command doesn't work on PowerShell :'(
echo "FROM ubuntu:latest" >> Dockerfile
docker build -t docker-d1 .
docker run -it docker-d1 /bin/bash
```

# What is going on?

Where:

- `docker build -t docker-d1 .`
    - Creates a image titled “docker-d1” from the Dockerfile located at . (Local directory)
- `docker run -it docker-d1 /bin/bash`
    - Runs a container in “interactive terminal” mode of the image “docker-d1” invoking run on the program /bin/bash (The bash shell)

# Gimi Gimi The Answer

```BASH
# Copy & Rename the completed Dockerfile
cp Dockerfile-Final Dockerfile
# Repeat Setup commands
```
