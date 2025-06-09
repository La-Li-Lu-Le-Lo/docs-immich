
```
name: immich

services:
  immich-server:
    labels:
      net.unraid.docker.icon: "https://raw.githubusercontent.com/imagegenius/templates/main/unraid/img/immich.png"
      net.unraid.docker.webui: http://[IP]:[PORT:2283]
  immich-machine-learning:
    labels:
      net.unraid.docker.icon: "https://raw.githubusercontent.com/imagegenius/templates/main/unraid/img/immich.png"
  redis:
    labels:
      net.unraid.docker.icon: "https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/redis.png"
  database:
    labels:
      net.unraid.docker.icon: "https://raw.githubusercontent.com/bmartino1/unraid-docker-templates/refs/heads/main/images/postgresql-immich-logo.png"
```
