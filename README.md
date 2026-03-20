# Docker Compose Setup

This repository contains my Docker Compose setup.

## Usage

To make running the stack easier, add the following alias to your `.bashrc`:

###### Replace "user" with your user

```bash
alias compose="docker compose --env-file /home/user/docker/config.env up -d"