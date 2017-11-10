# docker-nightwatch

Dockerfile for running Nightwatch tests on xvfb and chrome.

## Example setup

To run the container, mount your working directory that contains the Nightwatch tests to the `/tests` directory in the container. For example:

```
docker pull alisonmi/docker-nightwatch:latest
docker run --net=host -v $(pwd):/tests alisonmi/docker-nightwatch:latest
```
