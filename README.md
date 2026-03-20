


# Docker Compose Setup

This repository contains my Docker Compose setup.

## Configuration

Everything that needs to be configured is in `config.env` If there is any program you do not want just take it out of the right docker-compose.yml and the variables for it in config.env keep in mind that jellyseerr depends on Radarr or Sonarr otherwise Jellyseerr it is basically useless

## Usage

To make running the stack easier, add the following alias to your `.bashrc`:

###### Replace "user" with your user

```bash
alias compose="docker compose --env-file /home/user/docker/config.env up -d"
```

## Thanks to


[Watchtower Fork](https://github.com/nicholas-fedor/watchtower/)- Thanks for taking the role of maintainer and continuing development on Watchtower after the original got archived




