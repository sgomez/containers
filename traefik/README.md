# Traefik container

## Installation

1. Create a web network:

    docker network create web

1. Copy traefik.toml.dist to traefik.toml

1. Install certificates in certs directory

1. Run

All containers managed by traefik must be attached to web network too.
