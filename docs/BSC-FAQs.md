---
sidebar_label: BSC General FAQs
sidebar_position: 2
---
# BNB Smart Chain 

## What is BNB Smart Chain ?

BNB Smart Chain  brings EVM-compatible programmability and native cross-chain communication with BNB Beacon Chain  using an innovative consensus of Proof of Staked Authority(PoSA).

## Why is BNB Smart Chain  designed as a separate chain from BNB Beacon Chain ?

The execution of a Smart Contract may slow down the exchange function and add non-deterministic factors to trading. Even if that compromise could be tolerated, it might be a straightforward idea to introduce a new Virtual Machine specification based on Tendermint, based on the current underlying consensus protocol and major RPC implementation of BNB Beacon Chain . But all these will increase the learning requirements for all existing dApp communities, and will not be very welcomed.

## Where will the published whitepaper be found?

BNB Smart Chain Whitepaper can be found at <https://github.com/bnb-chain/whitepaper>, where feedback is more than welcome.

## Where can I take a look at BNB Smart Chain  code? Is there a GitHub repository?

The codebase of BSC is open-sourced here:

* <https://github.com/bnb-chain/bsc>
* <https://github.com/bnb-chain/bsc-relayer>
* <https://github.com/bnb-chain/bsc-relayer-config>
* <https://github.com/bnb-chain/bsc-genesis-contract>
* <https://github.com/bnb-chain/bsc-double-sign-sdk>
* <https://github.com/bnb-chain/oracle-relayer>

## Where can I find some support?

* Technical talk and support running our software: 
  * Telegram: <http://t.me/bnbchain> or <https://t.me/BNBchaincommunity>
  * Discord: <https://discord.com/invite/bnbchain>
* Bugs or technical contributions on [GitHub](https://github.com/bnb-chain)
* General discussion regarding our blockchain on [Telegram](https://t.me/BNBChainDevs) or <https://t.me/BNBchaincommunity>

## Which are BNB Smart Chain's official channels for communication and information?

* Binance DEX announcements: <https://t.me/Binance_DEX_Announcement>
* Twitter: <https://twitter.com/bnbchain>
* BNB Chain Forum: <https://forum.bnbchain.org/>


## Wallet support for BNB Smart Chain 

  - [Binance Extension Wallet ](wallet/bnb-chain-wallet.md)
  - [MetaMask](wallet/metamask.md)
  - [Math Wallet](wallet/math.md)
  - [Arkane](wallet/arkane.md)
  - [Ledger](wallet/ledger.md)
  - [MEW](wallet/myetherwallet.md)
  - [Trust Wallet](wallet/trustwallet.md)
  - [SafePal](https://blog.safepal.io/pre-announcement-trade-on-dex-with-safepal/)
  - [TokenPocket](https://tokenpocket-gm.medium.com/defi-with-tokenpocket-how-to-use-binance-smart-chain-swap-with-tokenpocket-e76d6cd7986)


##  How to recover if you choose the wrong network type?

Please read this [guide](./wallet/withdraw-en.md)

清阅读以下[说明](./wallet/withdraw-cn.md)

## How does BNB Smart Chain  work? What is the architecture and consensus used?

BNB Smart Chain relies on a system of 50 validators with Proof of Staked Authority (PoSA) consensus that can support short block time and lower fees.

There will be fewer validators on BNB Smart Chain  testnet.

## Can you tell more about Proof of Staked Authority(PoSA)? What is it?

PoSA is a combination of PoA and PoS. Blocks are produced by a limited set of validators, they are elected in and out based on a staking based governance. Validators take turns to produce blocks in a PoA manner

## What are the benefits for developers to build on BNB Smart Chain ?

* **EVM-compatible:** BNB Smart Chain  supports all the existing Ethereum tooling

* **Fast Finality:** Fast block time

* **Cheaper Cost**

* **Native cross-chain transfer & communication:** Binance DEX remains a liquid venue of exchange of assets on BNB Beacon Chain and BNB Smart Chain

## What are the benefits for developers to build on BNB Chain ?

BNB Chain opens the gate for users to take advantage of the fast transferring and trading

## How many assets are issued on BNB Chain ?

There are already [140 assets](https://explorer.bnbchain.org/assets/bep2) on BNB Chain.

The introduction of [BEP8](https://github.com/bnb-chain/BEPs/blob/master/BEPs/BEP8.md) is an innovative way for tokenization of properties.

## What make BNB Smart Chain  different?

Key Innovations:

* Proof-of-staked-authority Consensus

* Native Cross-Chain Communication

* Expand the use cases of BNB token

## BNB Smart Chain  is EVM-compatible. What does that mean?

EVM means Ethereum Virtual Machine. Any smart-contract written to run in EVM can be easily ported to BNB Smart Chain .

## Can developers make hybrid Dapps using both BNB Beacon Chain  and BNB Smart Chain  in one single Dapp?

Yes, with the help of native cross-chain functions

## How to query the current system parameters

```
bnbcli  params side-params  --side-chain-id=bsc   --node  http://dataseed4.bnbchain.org:80   --chain-id=Binance-Chain-Tigris --trust-node --output=json
```

* Minimum self-delegated amount: **2000BNB**

* Minimum delegate amount: **1BNB**

* Unbonding time: **7 days**

* Offline Unjail fee:  **1BNB**

* Offline jail time: **2 day**

* Offline slashing amount: **50BNB**

* Double-sign slashing amount: **10000BNB**

* Cross-chain relay fee: **0.004BNB**

## Which dApps are deployed on BSC?
Refer to [here](https://bnbproject.org/) to learn about the different projects deployed on BSC.

