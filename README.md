# docker-mininet

The Docker image for [Mininet](http://mininet.org/)

## Set up

- download [xquartz](https://www.xquartz.org/)
- open xquartz -> go to preference>security -> click "Allow connections from network"
- log out and log back in
- from your computer terminal run `xhost +`

## Usage

If you have installed [Docker Compose](https://docs.docker.com/compose/),
you can run container with:

```bash
docker-compose run --rm mininet
```

inside the container

```bash
mn
xterm h1
```
