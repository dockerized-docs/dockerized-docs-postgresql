# dockerized-docs-postgresql

# What is it?#
Dockerzied PostgreSQL documentation for offline use.

# Image description #
Base image: `httpd:latest`.
The most current (9.6.1) postgres source code is downloaded.
PostgreSQL documentation directory (`/postgresql-9.6.1/doc/src/sgml/html`) is linked to httpd `DocumentRoot` (`/usr/local/apache2/htdocs`).

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-postgresql
```

You can test it by visiting http://container-ip:80
