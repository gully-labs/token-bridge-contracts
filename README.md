<!-- gully-header:start -->
<a href="https://gullychain.xyz"><img src="https://gullychain.xyz/brand/repos/token-bridge-contracts.svg" alt="GullyChain · Bridge Contracts" width="100%"></a>

<p align="center">
  <a href="https://gullychain.xyz"><img src="https://img.shields.io/badge/gullychain.xyz-01D9FA?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=000000" alt="Website"></a>
  <a href="https://app.gullychain.xyz"><img src="https://img.shields.io/badge/App-0A0F1A?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=01D9FA" alt="App"></a>
  <a href="https://docs.gullychain.xyz"><img src="https://img.shields.io/badge/Docs-0A0F1A?style=for-the-badge&labelColor=000000&logo=readthedocs&logoColor=01D9FA" alt="Docs"></a>
  <a href="https://x.com/Gully_Labs"><img src="https://img.shields.io/badge/@Gully__Labs-0A0F1A?style=for-the-badge&labelColor=000000&logo=x&logoColor=white" alt="X"></a>
  <a href="https://t.me/GullyLabsNews"><img src="https://img.shields.io/badge/Telegram-0A0F1A?style=for-the-badge&labelColor=000000&logo=telegram&logoColor=26A5E4" alt="Telegram"></a>
  <a href="https://github.com/gully-labs"><img src="https://img.shields.io/badge/GitHub-0A0F1A?style=for-the-badge&labelColor=000000&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<p align="center"><b>Bridge Contracts: Token bridge contracts between GullyChain and its parent chain.</b></p>

<p align="center"><sub>Maintained by <a href="https://gullylabs.xyz">Gully Labs</a> as part of <a href="https://gullychain.xyz">GullyChain</a>. Fork of <a href="https://github.com/OffchainLabs/token-bridge-contracts">OffchainLabs/token-bridge-contracts</a>, used under its Apache-2.0 licence. Not affiliated with or endorsed by Offchain Labs.</sub></p>

---
<!-- gully-header:end -->

<p align="center"><img src="docs/assets/arbitrum_horizontal_logo.png" width="600"></p>

# Arbitrum Token Bridge Contracts

The Arbitrum Token Bridge is a decentralized application that uses [Nitro's](https://github.com/OffchainLabs/nitro) arbitrary cross-chain messaging system to implement an ERC20 token bridge between an EVM compatible base-chain and an Arbitrum chain.

All public Arbitrum chains include a [canonical token bridge deployment](https://developer.arbitrum.io/useful-addresses#token-bridge).

The Token Bridge includes "Gateway" contracts — pairs of contracts that implement a particular token-bridging flow — as well as "Gateway Router" contracts, which map tokens to their respective gateways.

See the [developer documentation](https://developer.arbitrum.io/asset-bridging) for more info.

See security audit reports [here](./audits).

This repository is offered under the Apache 2.0 license. See [LICENSE](https://github.com/OffchainLabs/token-bridge-contracts/blob/main/LICENSE) for details.

## Deployment
Check [this doc](./docs/deployment.md) for instructions on deployment and verification of token bridge.

## Contact

Discord: [Arbitrum](https://discord.com/invite/5KE54JwyTs)

Twitter: [Arbitrum](https://twitter.com/arbitrum)

