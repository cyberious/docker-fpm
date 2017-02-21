# FPM

centos:7 base image for building RPMs

#example usage https://github.com/cyberious/hashicorp_rpm_builder


Given a system that has a Makefile in the root directory you could run a build with something similar to below code

```shell
docker run -v `pwd`:/fpm -w /fpm -ti cyberious/fpm make
```
