# Rancher docker-compose

[Using Rancher Docker Image](https://rancher.com/docs/rancher/v2.x/en/installation/single-node/)

## Installation

Create the `.env` file from [.env.dist](.env.dist) example with the
environment variables from [docker let's encrypt nginx proxy](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion/wiki/Basic-usage)

```bash
docker-compose up -d
```

## Update docker images

```bash
./updateDockerImages.sh
```
