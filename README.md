# docker-alpine-java-beagleboneblack
Docker image using alpine linux supporting Oracle Java JRE 8

Built for use with resin.io -- I found that the OpenJDK versions were way too slow.

This is jre only -- to get full jdk, edit the Dockerfile to extract the full tarball in /opt, rather than extracting in /tmp and moving the jre to /opt.

You can find the Docker image at docker.io/dpsmyth/beaglebone-black-alpine-java
