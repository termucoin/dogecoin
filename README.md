<h1 align="center">
<img src="https://raw.githubusercontent.com/noncecash/noncecash/master/share/pixmaps/noncecash256.svg" alt="NonceCash" width="256"/>
<br/><br/>
NonceCash Core [NNCC, Ð]  
</h1>

**IMPORTANT: Starting August 2024, the `master` branch has become the primary
integration branch and has become unstable. Please check out a tagged version
before compiling production binaries.**

For internationalized documentation, see the index at [doc/intl](doc/intl/README.md).

NonceCash is a community-driven cryptocurrency that was inspired by a Shiba Inu meme. The NonceCash Core software allows anyone to operate a node in the NonceCash blockchain networks and uses the Scrypt hashing method for Proof of Work. It is adapted from Bitcoin Core and other cryptocurrencies.

For information about the default fees used on the NonceCash network, please
refer to the [fee recommendation](doc/fee-recommendation.md).

## Usage 💻

To start your journey with NonceCash Core, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by NonceCash Core is self-documenting and can be browsed with `noncecash-cli help`, while detailed information for each command can be viewed with `noncecash-cli help <command>`.

### Such ports

NonceCash Core by default uses port `9883` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `9882` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   9883 |   44556 |   18444 |
| RPC      |   9882 |   44555 |   18332 |

## Ongoing development - Moon plan 🌒

NonceCash Core is an open source and community driven software. The development
process is open and publicly visible; anyone can see, discuss and work on the
software.

Main development resources:

* [GitHub Projects](https://github.com/noncecash/noncecash/projects) is used to
  follow planned and in-progress work for upcoming releases.
* [GitHub Discussions](https://github.com/noncecash/noncecash/discussions) is used
  to discuss features, planned and unplanned, related to both the development of
  the NonceCash Core software, the underlying protocols and the NNCC asset.

### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

### Branches
There are 4 types of branches in this repository:

- **master:** Unstable, contains the latest code under development.
- **maintenance:** Stable, contains the latest version of previous releases,
  which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for upcoming releases. Format: ```<version>-dev```
- **archive:** Stable, immutable branches for old versions that no longer change
  because they are no longer maintained.

***Submit your pull requests against `master`***

*Maintenance branches are exclusively mutable by release. When a release is*
*planned, a development branch will be created and commits from master will*
*be cherry-picked into these by maintainers.*

## Contributing 🤝

If you find a bug or experience issues with this software, please report it
using the [issue system](https://github.com/noncecash/noncecash/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Please see [the contribution guide](CONTRIBUTING.md) to see how you can
participate in the development of NonceCash Core. There are often
[topics seeking help](https://github.com/noncecash/noncecash/labels/help%20wanted)
where your contributions will have high impact and get very appreciation. wow.

## Very Much Frequently Asked Questions ❓

Do you have a question regarding NonceCash? An answer is perhaps already in the
[FAQ](doc/FAQ.md) or the
[Q&A section](https://github.com/noncecash/noncecash/discussions/categories/q-a)
of the discussion board!

## License - Much license ⚖️
NonceCash Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information.
