# alafia-bento

## Description

Alafia-specific deployment of [Bento](https://github.com/migueravila/Bento) based on [the official Docker image](https://registry.hub.docker.com/r/lewisdoesstuff/bento). This app runs in the user's browser but can be launched from the application menu. It provides links to other in-browser Alafia apps.

## Usage

Meant to be used as a submodule in [alafia-apps](https://github.com/Alafia-Ai/alafia-apps).

`Makefile` can be manually invoked with the following options:

- `make` or `make build`: Locally build the Docker image
- `make install`: Install the files in the `deploy/` directory, and if relevant, install systemd service files and modify `/etc/hosts/`
- `make uninstall`: Removes all installed files, and if relevant, removes systemd services and resets `/etc/hosts/` 
