# docker-pbc

Dockerfiles for PBC, the Pairing-Based Cryptography library (https://crypto.stanford.edu/pbc/).



# docker-pypbc

基于 docker-pbc 搭建 pypbc环境，同时也有GMSSL的环境。

## buildpack-deps

[docker: buildpack-deps](https://hub.docker.com/_/buildpack-deps/)

buildpack-deps 是docker hub 官方提供的一个构建类似heroku stack 镜像的工具包，提供了很多内置依赖库，可以简化我们的镜像部署
