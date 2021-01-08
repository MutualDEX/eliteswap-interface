# Big Swap Interface

[![Lint](https://github.com/MutualDEX/bigswap-interface/workflows/Lint/badge.svg)](https://github.com/MutualDEX/bigswap-interface/actions?query=workflow%3ALint)
[![Tests](https://github.com/MutualDEX/bigswap-interface/workflows/Tests/badge.svg)](https://github.com/MutualDEX/bigswap-interface/actions?query=workflow%3ATests)
[![Styled With Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)

An open source interface for Big Swap -- a protocol for decentralized exchange of Ethereum tokens.

- Interface: [bigswap.app](https://bigswap.app)
- Discord: [MutualDEX](https://discord.gg/yFsjhuQ7Kj)
- Telegram: [MutualDEX](https://telegram.org/@MutualDEX)
- Twitter: [@Bigswap1](https://twitter.com/Bigswap1)
- Whitepaper: [Link](https://uniswap.org/whitepaper.pdf)

## Accessing Big Swap Interface

[latest release](https://github.com/EthereumEliteswap/eliteswap-interface/releases/latest), 
visit [https://bigswap.app](https://bigswap.app).

## Listing a token

Please see the
[@bigswap/default-token-list](https://github.com/EthereumEliteswap/default-token-list) 
repository.

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"` 


## Contributions

**Please open all pull requests against the `master` branch.** 
CI checks will run against all PRs.

