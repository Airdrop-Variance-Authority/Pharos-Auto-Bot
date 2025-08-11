# Pharos S2 Auto Bot (Safe version)

This is the updated version for Airdrop Variance Authority.

Changes:
- Update Dodo API Key
- Clears guide
- Update packages

## Setup

1. Fill `wallets.txt` with your `send PHRS` addresses. Replace the current one.
2. Add proxies to `proxies.txt`. Replace the current one.
3. Add private keys to `privatekeys.txt`. Replace the current one.
4. You can add your dodokey to `dodokey.txt`. Replace the current one. [Create dodo key here](https://developer.dodoex.io/).
5. Install package

```sh
npm install
```

6. Run the script

```sh
npm run start
```

## Config

Modify `config.json` to increase your transactions:

```json
{
  "swapRepetitions": 1,
  "sendPhrsRepetitions": 1,
  "addLiquidityRepetitions": 1,
  "tipRepetitions": 1,
  "mintRepetitions": 1
}
```

:warning: Don't use proxies if you're using your retroactive or active addresses, only use farm wallets.

**Before redistribute this code, please don't forget to change the data of your dodo key, private key, and proxy files**