# dockerized-docs-postgresql

# What is it? #
Dockerzied PostgreSQL documentation for offline use.

# Image description #
- Base image: `centos/httpd-24-centos7`
- The most current (10.3) postgres source code is downloaded

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-postgresql
```

You can test it by visiting http://container-ip:80
