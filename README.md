<h1 align="center">
<img src="https://i.imgur.com/DDkfI9i.png" alt="Bonkcoin" width="300"/>
<br/><br/>
Bonkcoin Core [BONC, Ᵽ]
</h1>

Select language: EN | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | [FR](./README_fr_FR.md) | [JA](./README_ja_JP.md) | [DE](./README_de_DE.md)

Bonkcoin is a community focused cryptocurrency created by one of the original Dogecoin shibes from 2013. It was created for one purpose, to create a new and fun community just like the original Dogecoin community.

Unlike all iterations before it, Bonkcoin is a layer 1 coin. This means there are no liquidity pools to drain, no blacklisting wallets, and no confusing smart contracts. Bonkcoin is a simple blockchain.

The Bonkcoin Core software allows anyone to operate a node in the Bonkcoin blockchain networks and uses the Scrypt hashing method for Proof of Work. It is adapted from Dogecoin Core, Bitcoin Core, and other cryptocurrencies.

For information about the default fees used on the Bonkcoin network, please
refer to the [fee recommendation](doc/fee-recommendation.md).

**Website:** [bonkcoin.org](https://bonkcoin.org)

## Dogecoin Differences

Bonkcoin is a fork of Dogecoin. For the sake of familiarity, we will attempt to keep Bonkcoin similar to Dogecoin.

Changes:

* Addresses start with `P` instead of `D`
* BIPS features will start block 1000
* AuxPow starts at block 42,000 (Chain ID: 63)
* GUI themed for Bonkcoin

## Usage 💻

To start your journey with Bonkcoin Core, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by Bonkcoin Core is self-documenting and can be browsed with `bonkcoin-cli help`, while detailed information for each command can be viewed with `bonkcoin-cli help <command>`. Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

### Ports

Bonkcoin Core by default uses port `33874` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `33873` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   33874 |   44874 |   18444 |
| RPC      |   33873 |   44873 |   18332 |

## Ongoing development 💻

Bonkcoin Core is an open source and community driven software. The development
process is open and publicly visible; anyone can see, discuss and work on the
software.

Main development resources:

* [GitHub Projects](https://github.com/bonkcoinppc/bonkcoin/projects) is used to
  follow planned and in-progress work for upcoming releases.
* [GitHub Discussion](https://github.com/bonkcoinppc/bonkcoin/discussions) is used
  to discuss features, planned and unplanned, related to both the development of
  the Bonkcoin Core software, the underlying protocols and the BONC asset.
* [BonkcoinDev subreddit](https://www.reddit.com/r/bonkcoindev/)

### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

### Branches
There are 3 types of branches in this repository:

- **master:** Stable, contains the latest version of the latest *major.minor* release.
- **maintenance:** Stable, contains the latest version of previous releases, which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for planned releases. Format: ```<version>-dev```

*Master and maintenance branches are exclusively mutable by release. Planned*
*releases will always have a development branch and pull requests should be*
*submitted against those. Maintenance branches are there for **bug fixes only,***
*please submit new features against the development branch with the highest version.*

## Contributing 🤝

If you find a bug or experience issues with this software, please report it
using the [issue system](https://github.com/bonkcoinppc/bonkcoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Please see [the contribution guide](CONTRIBUTING.md) to see how you can
participate in the development of Bonkcoin Core. There are often
[topics seeking help](https://github.com/bonkcoinppc/bonkcoin/labels/help%20wanted)
where your contributions will have high impact and get very appreciation.

## Communities 🐸

You can join the communities on different social media.
To see what's going on, meet people & discuss, find the latest meme, learn
about Bonkcoin, give or ask for help, to share your project.

Here are some places to visit:

* [r/Bonkcoin](https://www.reddit.com/r/bonkcoin/)
* [Discord](https://bonkcoin.org/discord)
* [Telegram](https://t.me/BonkcoinGroup)
* [Twitter/X](https://twitter.com/BonkcoinNetwork)

## Frequently Asked Questions ❓

Do you have a question regarding Bonkcoin? An answer is perhaps already in the [FAQ](doc/FAQ.md) or the [Q&A section](https://github.com/bonkcoinppc/bonkcoin/discussions/categories/q-a) of the discussion board!

## License ⚖️
Bonkcoin Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)
