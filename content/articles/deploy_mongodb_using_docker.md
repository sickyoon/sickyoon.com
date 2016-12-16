+++
title = "Deploy MongoDB using Docker"
date = "2016-12-11T23:27:09+09:00"
+++

# Test Environment

Setting up MongoDB using docker to behave as your native installation, we just have to ensure corresponding volumes and ports are mapped correctly.

```bash
docker pull mongo
docker run --name mongo -p 27017:27017 -v /data/db:/data/db -d mongo:latest
```
