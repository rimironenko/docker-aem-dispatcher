## AEM Dispatcher in Docker container (Windows)

A simple configuration to build a Docker Image with Apache 2.4 and AEM Dispatcher module and run it in a Docker container on Windows.

### Prerequisites 

* Installed official Docker for Windows (can be downloaded [here](https://docs.docker.com/docker-for-windows/install/))
* AEM Publish instance is running locally on localhost:4503

### Build and run

```
# From root directory
docker-compose up
```

### How to reach Docker entities

* Docker image created with **aem-dispatcher** name.
* Docker container created from "aem-dispatcher" image with **docker-aem-dispatcher** name.
