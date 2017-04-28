[![Docker Build Status](https://img.shields.io/docker/build/herzog31/locust.svg)](https://hub.docker.com/r/herzog31/locust/)

# Docker Container for Locust.io

## Usage
```bash
docker run -it -p 8089:8089 -v $(pwd):/locust herzog31/locust --host=http://localhost
```