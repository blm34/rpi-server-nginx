# Nginx

Docker compose configuration for running Nginx on ubuntu server

## Requirements

* Docker
* Docker compose

## Set Up

Clone this repository

```bash
git clone git@github.com:blm34/rpi-server-nginx.git
```

Copy the file `.env.template` to `.env` and fill in the variables

```bash
cp .env.template .env
```

Start the container with

```bash
docker compose up -d
```
