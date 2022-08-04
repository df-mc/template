# Template
This repository is a GitHub Template which may be used to create [Dragonfly](https://github.com/df-mc/dragonfly) servers.

## Usage
See this [GitHub page](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)
on how to set up a new GitHub repository using this template.

This template also contains a Dockerfile, that can be run with this:
```shell
docker run -p 19132:19132/udp \
  -v "$PWD/world:/opt/app/world" \
  -v "$PWD/resources:/opt/app/resources" \
  dragonfly-image
```

## Contact
[![Chat on Discord](https://img.shields.io/badge/Chat-On%20Discord-738BD7.svg?style=for-the-badge)](https://discord.gg/evzQR4R)