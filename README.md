

# Build the image, then list images

```
docker build -t docker-jenkins .
docker images
```

# Create a container, then list containers

```
docker run --name jenkins -i -t docker-jenkins
docker ps -a
docker inspect jenkins
```

# Get container IP

```
docker inspect jenkins | grep IP
```

# Quit a container

```
CTRL + P
CTRL + Q
```
