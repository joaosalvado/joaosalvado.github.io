---
title: 'Docker container of CMake project with dependency on OpenCV'
date: 2022-05-31
permalink: /posts/2022/06/docker-cmake-opencv
tags:
  - CMake
  - Docker
  - OpenCV
---
# Table of Contents

1.  [Integrating Docker + CMake + OpenCV](#org9d6c309)
    1.  [Docker References](#orgfb32bf0)
    2.  [CMake Project](#org0459380)
    3.  [Project with Docker container](#orgeeab9f7)



<a id="org9d6c309"></a>

# Integrating Docker + CMake + OpenCV

Step by step on how to create a  docker container for CMake project with an OpenCV dependency.

To install Docker Engine on Ubuntu follow instructions in [link](https://docs.docker.com/engine/install/ubuntu/).


<a id="orgfb32bf0"></a>

## Docker References

Next you can find a set of references that I consulted to understand how to create a docker container on a CMake project.

-   [X] [2:00:00/2:46] Overview tutorial video on what is Docker and why use it [link](https://www.youtube.com/watch?v=3c-iBn73dDE)
-   [X] [ full ](https://levelup.gitconnected.com/how-to-combine-c-cmake-googletest-circleci-docker-and-why-e02d76c060a3) the entire story, cmake, git, tests, docker &#x2026;
-   [X] [easy article](https://blog.totalcross.com/docker-basics-cross-compiling-a-cmake-project-642001240b6f) dockfile and simple c++ project
-   Official cmake c++ docker image [link](https://hub.docker.com/r/rikorose/gcc-cmake/dockerfile)


<a id="org0459380"></a>

## CMake Project

We will be using the CMake project available at the [repo](https://github.com/joaosalvado/mr_env).


<a id="orgeeab9f7"></a>

## Project with Docker container

I have already created an example repository where docker container is implemented for the CMake Project.
However, you can create your own repo and follow the next steps.

[This post is in progress]

