# Bash Alpine Docker image

This image is based on Alpine image and contains Bash.

## Usage

Build the image and run a container

```
$ docker build docker-alpine-bash .
$ docker run -it docker-alpine-bash bash
```

Or execute a command and automatically remove the container when it exits.

```
$ docker run --rm docker-alpine-bash bash -c 'echo "Hello World"'
```
