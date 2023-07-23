# Stellar

## Quick Start

    mkdir stellar
    cd stellar
    git clone https://github.com/ayan4m1/stellar-compose.git compose
    git clone https://github.com/ayan4m1/stellar-ui.git ui
    git clone https://github.com/ayan4m1/stellar-api.git api
    cd compose
    mkdir -p volumes/db-data

Now, edit `.env` and `.env.api` and replace all relevant configuration. Refer to UI/API documentation for documentation on the keys and values.

    docker compose build
    docker compose up -d
