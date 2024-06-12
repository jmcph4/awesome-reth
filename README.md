# awesome-reth #

**A list of awesome Reth-related resources**.

 - [Repository](https://github.com/paradigmxyz/reth)
 - [User Book](https://reth.rs)

[Follow me](https://twitter.com/secjack_) for live updates as I usually retweet whatever I find. Alternatively, feel free to contribute to this list by opening a PR!

## Audits ##

 - [Sigma Prime](https://x.com/gakonst/status/1726711059715920250)

## Development Tools ##

 - [Reth Alphanet](https://github.com/paradigmxyz/alphanet), OP-Stack compatible testnet rollup explicitly designed for Ethereum R&D ([blog post](https://www.paradigm.xyz/2024/04/reth-alphanet), [Tweet](https://x.com/gakonst/status/1779892069169008709))
 - [ethers-reth](https://github.com/SorellaLabs/ethers-reth), an [Ethers-rs](https://ethers.rs)-aware middleware by [Sorella Labs](https://github.com/SorellaLabs) for accessing Reth state directly ([Tweet](https://x.com/0xvanbeethoven/status/1668434735281090560))

## Execution Extensions (ExExes) ##

An [Execution Extension (Exex)](https://www.paradigm.xyz/2024/05/reth-exex) is code that runs in-process with Reth that has access to *reorg-aware* chain state.

 - [shadow-reth](https://github.com/shadow-hq/shadow-reth), an implementation of the [Shadow RPC](https://docs.shadow.xyz/product-guide/shadow-rpc) as an Exex ([blog post](https://blog.shadow.xyz/shadow-reth))
 - [flare](https://github.com/rauljordan/flare), an Exex that indexes [Arbitrum](https://arbitrum.io) sequencer batches ([Tweet](https://mobile.x.com/rauljordaneth/status/1787252292250485231))
 - [hyperlane-exex](https://github.com/aroralanuk/hyperlane-exex), a PoC [Hyperlane](https://www.hyperlane.xyz) validator built as an ExEx ([Tweet](https://x.com/aroralanuk/status/1787203558955233562))
 - [wvm-reth](https://github.com/weaveVM/wvm-reth), a BigQuery ExEx ([blog post](https://docs.wvm.dev/about-weavevm/weavevm-testnet-v0))

## Crawlers ##

A crawler (in the Ethereum context) is a program that indexes and gathers various metrics on different nodes within a P2P network (either at the execution or consensus layer).

 - [reth-crawler](https://github.com/Keep-Reth-Strange/reth-crawler), a crawler for EL nodes ([Tweet](https://x.com/alemaz98/status/1731961719583396119))
 - [reconnaissance](https://github.com/Will-Smith11/reconnaissance), a proxy EL node using Reth

## Indexers ##

An indexer (in the Ethereum context) takes data directly from the blockchain and produces alternative database schemas (typically relational) to allow enhanced and performant querying.

 - [reth-indexer](https://github.com/joshstevens19/reth-indexer), an indexer that accesses Reth's database directly and indexes into various backends

## Research ##

Publications using or mentioning Reth.

 - [Decentralization of Ethereum’s Builder Market](https://arxiv.org/pdf/2405.01329), a paper due to Yang, et. al. that details the auction dynamics of [MEV-Boost](https://github.com/flashbots/mev-boost) auctions and the subsequent structure current PBS pipeline ([Tweet 1](https://x.com/gakonst/status/1787802487753154862), [Tweet 2](https://x.com/kartik1507/status/1791485547589857753))

## Layer 2 ##

 - [sp1-reth](https://github.com/succinctlabs/sp1-reth), a zkEVM PoC by [Succint Labs](https://succinct.xyz) demonstrating transaction costs to the order of $0.01 USD atop Reth
 - [scroll-reth](https://x.com/gakonst/status/1788548434393210938), a port of Scroll to Reth
 - [pevm](https://github.com/risechain/pevm), a massively-parallelised EVM implementation that is explicitly compatible with Reth ([blog post](https://medium.com/@rise_chain/rise-pevm-parallel-evm-bdfc4bc9f38e), [Tweet](https://x.com/gakonst/status/1798165192460976195))

## Tutorials ##

 - [reth-custom-api-example](https://github.com/libevm/reth-custom-api-example), an example demonstrating RPC extension using Reth due to [libevm](https://libevm.com) ([blog post](https://www.libevm.com/2023/09/01/reth-custom-api))
    - This also became a talk during the hackathon at [ETHGlobal Sydney 2024](https://ethglobal.com/events/sydney)

## Miscellaneous ##

 - [reth-payload-validator](https://github.com/ultrasoundmoney/reth-payload-validator), a RPC extension of Reth by the [Ultra Sound Money relay](https://ultrasound.money) that implements rapid block validation of builder submissions

