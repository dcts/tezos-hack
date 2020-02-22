# TEZOS Hack / Workshop
This repo was created during the Tezos Workshop 22.02.2020 @ Berlin. Some resources:
- [Meetup-Link](https://www.meetup.com/de-DE/Tezos-Berlin/events/268464836/)
- [Medium Article, Basic Introduction to Tezos](https://medium.com/the-cryptonomic-aperiodical/blockchain-development-with-tezos-698aa930e50f)

### Tools build by cryptonomic
- **[Minimax](https://mininax.cryptonomic.tech/mainnet/blocks/BM8NvYQ3HdBAwqviET7DYap4ZAhcRZ5YebdWt9vbAJrJcvVyLpj)**: retro bock explorer.
- **[Arronax](https://github.com/Cryptonomic/Arronax)**: Data Analytics for Tezos Blockchain.
- **[ConseilJS](https://github.com/Cryptonomic/ConseilJS)**: connect to tezos blockchain through JS client.

### Why Tezos?
- Difference to Ethereum:
  - on chain governance: voting is build into the framework.
  - liquid proof of stake: -> you deligate your funds to a "baker"...

# Notes
### Tezos CLI
```bash
# disable warning if not on MAIN NET
export TEZOS_CLIENT_UNSAFE_DISABLE_DISCLAIMER=yes

# use NPM version v12.14.1 (use NVM to switch environments)
nvm ls-remote # shows all availible node installations
nvm ls        # show all installed node versions
nvm install v12.14.1 # install version 12.14.1 (recommended by Mike, runs stable)
```

