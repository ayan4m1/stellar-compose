# Stellar Compose

This is a Docker compose file which ties together the API and UI for Stellar.

## Quick Start

    mkdir stellar
    cd stellar
    git clone https://github.com/orphic-inc/stellar-compose compose
    git clone https://github.com/orphic-inc/stellar-ui.git ui
    git clone https://github.com/orphic-inc/stellar-api.git api
    cd compose
    mkdir -p volumes/db-data
    cd ../

Now, edit `.env` and `.env.api` and replace all relevant configuration. Refer to UI/API documentation for documentation on the keys and values.

    docker compose build
    docker compose up -d

## Docker Images

Tagged Docker images are not yet available.
