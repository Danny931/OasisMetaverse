# Oasiswap Interface

[![Tests](https://github.com/Uniswap/Uniswap-interface/workflows/Tests/badge.svg)](https://github.com/Oasiswap/Oasiswap-interface/actions?query=workflow%3ATests)
[![Styled With Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)

An open source interface for OASISwap -- a protocol for decentralized exchange of BinanceSmartChain tokens.

- Website: [oasiswap.finance](https://oasiswap.finance/)
- Interface: [app.oasiswap.finance](https://app.oasiswap.finance)
- Docs: [docs.oasiswap.finance](https://docs.oasiswap.finance/)
- Twitter: [@Oasis_Meta_BSC](https://twitter.com/Oasis_Meta_BSC)
- Email: [contact@oasiswap.finance](mailto:contact@oasiswap.finance)

## Accessing the Oasiswap Interface

To access the Oasiswap Interface, use an IPFS gateway link from the
[latest release](https://github.com/Oasiswap/Oasiswap-interface/releases/latest), 
or visit [app.oasiswap.finance](https://app.oasiswap.finance).

## Listing a token

Please see the
[Oasiswap-Hosted-Tokenlist](https://github.com/Danny931/Oasiswap-Hosted-Tokenlist) 
repository or send email to [contact@oasiswap.finance](mailto:contact@oasiswap.finance)

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

Note that the interface only works on testnets where both 
[Oasiswap V2](https://oasiswap.finance/docs/v2/smart-contracts/factory/) and 
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Contributions

**Please open all pull requests against the `master` branch.** 
CI checks will run against all PRs.

## Accessing Oasiswap Interface V1

The Oasiswap Interface supports swapping against, and migrating or removing liquidity from Oasiswap V1. However,
if you would like to use Oasiswap V1, the Oasiswap V1 interface for mainnet and testnets is accessible via IPFS gateways 
linked from the [v1.0.0 release](https://github.com/Oasiswap/Oasiswap-interface/releases/tag/v1.0.0).
