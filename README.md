# node-docker
Dockerfiles for node.js

## Building and pushing a new version

Assuming version 5.1.1

    docker login
    docker build -t node .
    docker tag node artsy/node:5.1.1
    docker push artsy/node:5.1.1
