# [CryptoBridge](https://cryptobridge.com/) for Docker

Run the [CryptoBridge](https://github.com/cryptobridge/cryptobridge.github.io) exchange UI from a Docker container on your local machine

## Getting started

- Install [Docker](https://docs.docker.com/engine/installation/) for your platform
- Download the [cryptobridge-docker](https://github.com/abbotto/cryptobridge-docker) repository

        git clone https://github.com/abbotto/cryptobridge-docker.git && cd cryptobridge-docker

- Start the container

        npm start

- Visit [localhost:9111](http://localhost:9111) in your web browser

## Connecting a wallet
- When creating an account, a local wallet is generated and stored in your browser
- The local wallet is encrypted with your password, and will contain your private keys
- It is important that you backup your local wallet once it has been created
- It is a good idea to store your cryptocurrency in a hardware wallet such as:
    - [Treznor](https://trezor.io/)
    - [Ledger Nano S](https://www.ledgerwallet.com/products/ledger-nano-s)
