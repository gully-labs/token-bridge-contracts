<!-- gully-header:start -->
<p align="center">
  <a href="https://gullychain.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/gullychain-badge-dark.png">
      <img alt="Powered by GullyChain" src=".github/assets/gullychain-badge-light.png" width="360" height="96">
    </picture>
  </a>
</p>

<p align="center"><b>The social chain where your profile is your wallet. Arbitrum Orbit L3, testnet chain 485590.</b></p>

<p align="center">Token bridge contracts between Gully Chain and its parent chain.</p>

<p align="center">
  <a href="https://gullychain.xyz"><img src="https://img.shields.io/badge/gullychain.xyz-01D9FA?style=for-the-badge&labelColor=000000&logo=googlechrome&logoColor=000000" alt="Website"></a>
  <a href="https://docs.gullychain.xyz"><img src="https://img.shields.io/badge/Docs-0A0F1A?style=for-the-badge&labelColor=000000&logo=readthedocs&logoColor=01D9FA" alt="Docs"></a>
  <a href="https://t.me/GullyChain"><img src="https://img.shields.io/badge/Telegram-0A0F1A?style=for-the-badge&labelColor=000000&logo=telegram&logoColor=26A5E4" alt="Telegram"></a>
  <a href="https://discord.com/invite/tY2ErsNNBp"><img src="https://img.shields.io/badge/Discord-0A0F1A?style=for-the-badge&labelColor=000000&logo=discord&logoColor=5865F2" alt="Discord"></a>
  <a href="https://x.com/Gully_Labs"><img src="https://img.shields.io/badge/@Gully__Labs-0A0F1A?style=for-the-badge&labelColor=000000&logo=x&logoColor=white" alt="X"></a>
</p>

<p align="center"><sub>A Gully Chain fork of <a href="https://github.com/OffchainLabs/token-bridge-contracts">OffchainLabs/token-bridge-contracts</a>, maintained by <a href="https://gullylabs.xyz">Gully Labs</a>. It is used under its Apache-2.0 licence; the upstream LICENSE, copyright and attribution notices are kept unchanged. The upstream README follows below as published. Not affiliated with or endorsed by OffchainLabs.</sub></p>

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


<!-- gully-footer:start -->
---

<p align="center">
  <a href="https://gullylabs.xyz">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset=".github/assets/powered-by-gully-labs-dark-2x.png">
      <img alt="Powered by Gully Labs" src=".github/assets/powered-by-gully-labs-light-2x.png" width="254" height="64">
    </picture>
  </a>
</p>
<!-- gully-footer:end -->
