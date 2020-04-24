# docker-mininet

The Docker image for [Mininet](http://mininet.org/)

## Set up

- download [xquartz](https://www.xquartz.org/)
- open xquartz -> go to preference>security -> click "Allow connections from network"
- log out and log back in
- from your computer terminal run `xhost +`

## Usage

Open xquartz

```bash
docker-compose run --rm mininet
```

inside the container

```bash
mn
xterm h1
```
