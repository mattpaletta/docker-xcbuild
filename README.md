[![](https://images.microbadger.com/badges/image/mattpaletta/xcbuild.svg)](https://microbadger.com/images/mattpaletta/xcbuild "Get your own image badge on microbadger.com") | [![Docker Stars](https://img.shields.io/docker/stars/mattpaletta/xcbuild.svg?style=flat-square)](https://hub.docker.com/r/mattpaletta/xcbuild/) | [![Docker Pulls](https://img.shields.io/docker/pulls/mattpaletta/xcbuild.svg?style=flat-square)](https://hub.docker.com/r/mattpaletta/xcbuild/)

# Docker-xcbuild
Using Facebook xcbuild inside docker (https://github.com/facebook/xcbuild)

## Download
`docker pull mattpaletta/xcbuild:latest`

## Usage
`docker run -it mattpaletta/xcbuild bash`
From there, use `xcbuild --executor ninja ...` to build your iOS project.
See official documentation for reference.



