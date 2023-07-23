# Stellar Compose

This is a Docker compose file which ties together the API and UI for Stellar.

## Quick Start

Make sure you have the following installed and working:

* Docker
* Git

The following commands will set up a new development environment using Docker.

    mkdir stellar
    cd stellar
    git clone https://github.com/orphic-inc/stellar-compose compose
    git clone https://github.com/orphic-inc/stellar-ui.git ui
    git clone https://github.com/orphic-inc/stellar-api.git api
    cd compose
    mkdir -p volumes/db-data
    cd ../

Now, edit `.env.api` and replace all relevant configuration. Refer to [API](https://github.com/orphic-inc/stellar-api) documentation on the keys and values.

    docker compose up --build -d

## Docker Images

Tagged Docker images are not yet available. When they are, you will be able to comment/uncomment lines in `docker-compose.yml` to switch between built local images and tagged remote images.
