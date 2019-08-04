# Freja - proxy server for testing

## Introduction

TBD

## Usage

TBD

### Build and deploy Freja on local machine

```bash
# Move to the directory which contains `docker-compose.yml`
$ cd freja
# Start services with daemon mode
$ docker-compose up -d
# Building frontend
# Step 1/9 : FROM node:11.9.0-alpine as builder
# ...
```

### Stop and remove Freja on local machine

```bash
# Move to the directory which contains `docker-compose.yml`
$ cd freja
# Stop and remove containers, networks, images, and volumes
$ docker-compose down
```
