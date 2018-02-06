# docker-packer
[![Source Code](https://img.shields.io/badge/source-GitHub-blue.svg?style=flat)](https://github.com/BreakingPitt/docker-packer) 
[![Build Status](https://travis-ci.org/BreakingPitt/dockerfiles.svg?branch=master)](https://travis-ci.org/BreakingPitt/docker-packer)
[![](https://images.microbadger.com/badges/image/breakingpitt/docker-packer.svg)](https://microbadger.com/images/breakingpitt/docker-packer "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/breakingpitt/docker-packer.svg)](https://microbadger.com/images/breakingpitt/docker-packer "Get your own version badge on microbadger.com")

Image to run Packer inside Docker container.

To be used with Docker http://www.docker.io

# Documentation of how to build the image.

Build an image is pretty simple:

    cd mtr/alpine
    docker build -t breakingpitt/packer-alpine .

Run the previously created image and attach to it at the same time:

    docker run -i -t breakingpitt/packer-alpine:latest
    
Run the previously created image in the background
  
    docker run -d breakingpitt/packer-alpine:latest

