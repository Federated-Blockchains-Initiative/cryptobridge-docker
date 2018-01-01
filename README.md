# [CryptoBridge](https://cryptobridge.com/) for Docker

Run the [CryptoBridge](https://github.com/cryptobridge/cryptobridge.github.io) exchange UI from a Docker container on your local machine

## Getting started

- Install [Docker](https://docs.docker.com/engine/installation/) for your platform
- Download the [cryptobridge-docker](https://github.com/abbotto/cryptobridge-docker) repository

        git clone https://github.com/abbotto/cryptobridge-docker.git && cd cryptobridge-docker

- Start the container

        npm start

- Visit [localhost:8080](http://localhost:9111) in your web browser

## Connecting a wallet
- After the initial setup is complete, you can connect to the exchange through any of the following methods:
    - Create a wallet for `CryptoBridge` (good)
    - Use the [MetaMask](https://metamask.io/) browser plugin as a wallet (better)
    - Use a hardware wallet such as [Treznor](https://trezor.io/) or [Ledger Nano S](https://www.ledgerwallet.com/products/ledger-nano-s) (best)
