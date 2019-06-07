# Java On Docker Image

This project show how to build a java spring-boot application using the docker´s multi-stage functionality and package it into a docker image and run it on a container.

## Useful Commands

To create the image run this command at the Dockerfile directory:
```bash
docker build -t multi-stage:latest .
```

To run the example run:

```bash
docker run -p 8081:8081 --name=multi-stage --rm multi-stage:latest
```



## References

- [Use multi-stage builds](https://docs.docker.com/develop/develop-images/multistage-build/)
- [Spring-boot-docker](https://spring.io/guides/gs/spring-boot-docker/)

