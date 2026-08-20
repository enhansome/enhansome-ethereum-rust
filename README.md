# awesome-ethereum-rust with stars

Awesome Ethereum Rust repos

* [Consensus](#consensus)
* [Execution](#execution)
* [Beam Chain](#beam-chain)
* [EVM - Ethereum Virtual Machine](#evm---ethereum-virtual-machine)
* [Core](#core)
* [Light Clients](#light-clients)
* [Scaling](#scaling)
* [PBS - Proposer-Builder Separation](#pbs---proposer-builder-separation)
* [Account Abstraction](#account-abstraction)
* [ZKP and zkEVM](#zkp-and-zkevm)
* [Statelessness](#statelessness)
* [Layer 2](#layer-2)
* [dApp Development](#dapp-development)
* [Smart Contracts](#smart-contracts)
* [Analytics](#analytics)
* [Misc](#misc)

## Consensus

* [libp2p](https://github.com/libp2p/rust-libp2p) ⭐ 5,603 | 🐛 289 | 🌐 Rust | 📅 2026-08-17.
  The Rust implementation of the libp2p networking stack.
* [Lighthouse](https://github.com/sigp/lighthouse) ⭐ 3,468 | 🐛 523 | 🌐 Rust | 📅 2026-08-20.
  Ethereum consensus client.
* [grandine](https://github.com/grandinetech/grandine) ⭐ 275 | 🐛 111 | 🌐 Rust | 📅 2026-08-20.
  High performance Ethereum consensus client.
* [discv5](https://github.com/sigp/discv5) ⭐ 193 | 🐛 10 | 🌐 Rust | 📅 2026-08-03.
  Rust implementation of Discovery v5.
* [ethereum-consensus](https://github.com/ralexstokes/ethereum-consensus) ⭐ 151 | 🐛 49 | 🌐 Rust | 📅 2025-07-18.
  A library for interacting with Ethereum consensus objects.
* [beacon-api-client](https://github.com/ralexstokes/beacon-api-client) ⚠️ Archived.
  A client for the Ethereum beacon node APIs.

## Execution

* [Reth](https://github.com/paradigmxyz/reth) ⭐ 5,742 | 🐛 216 | 🌐 Rust | 📅 2026-08-20.
  Ethereum execution client.
* [ethrex](https://github.com/lambdaclass/ethrex) ⭐ 887 | 🐛 982 | 🌐 Rust | 📅 2026-08-20.
  Lambda Ethereum Rust Execution client.
* [Akula](https://github.com/akula-bft/akula) ⚠️ Archived.
  Ethereum execution client - deprecated.
* [ranger](https://github.com/Rjected/ranger) ⭐ 204 | 🐛 9 | 🌐 Rust | 📅 2023-04-06.
  Ranger is an ethereum p2p client capable of interacting with peers without a full node.

## Beam Chain

* [ream](https://github.com/ReamLabs/ream) ⭐ 145 | 🐛 42 | 🌐 Rust | 📅 2026-08-16.
  ream: an Ethereum Beam client written in Rust.

## EVM - Ethereum Virtual Machine

* [Revm](https://github.com/bluealloy/revm/) ⭐ 2,220 | 🐛 85 | 🌐 Rust | 📅 2026-08-20.
  Rust Ethereum virtual machine (revm) Is EVM written in rust that is focused on speed and simplicity.
* [create2crunch](https://github.com/0age/create2crunch) ⭐ 541 | 🐛 9 | 🌐 Rust | 📅 2024-08-07.
  A Rust program for finding salts that create gas-efficient Ethereum addresses via CREATE2.
* [pevm](https://github.com/risechain/pevm) ⭐ 356 | 🐛 65 | 🌐 Rust | 📅 2026-08-05.
  Blazingly fast Parallel EVM in Rust.
* [revmc](https://github.com/paradigmxyz/revmc) ⭐ 286 | 🐛 3 | 🌐 Rust | 📅 2026-08-10.
  JIT and AOT compiler for the Ethereum Virtual Machine, built on Revm.
* [evm-inspectors](https://github.com/paradigmxyz/evm-inspectors) ⭐ 255 | 🐛 19 | 🌐 Rust | 📅 2026-08-19.
  EVM Execution Hooks for revm.
* [balls](https://github.com/Philogy/balls) ⭐ 196 | 🐛 6 | 🌐 Rust | 📅 2024-11-05.
  A DSL for generating optimal EVM bytecode.
* [jitevm](https://github.com/paradigmxyz/jitevm) ⚠️ Archived.
  Convert evm bytecode to native machine code and go vroom.
* [evm-disassembler](https://github.com/ckoopmann/evm-disassembler) ⭐ 24 | 🐛 4 | 🌐 Rust | 📅 2026-01-11.
  Rust library to disassemble evm bytecode.
* [evm\_mlir](https://github.com/lambdaclass/evm_mlir).
  An EVM written with MLIR.

## Core

* [Reth](https://github.com/paradigmxyz/reth) ⭐ 5,742 | 🐛 216 | 🌐 Rust | 📅 2026-08-20.
  Modular, contributor-friendly and blazing-fast implementation of the Ethereum protocol.
* [ethers-rs](https://github.com/gakonst/ethers-rs/) ⚠️ Archived.
  Complete Ethereum library and wallet implementation.
* [rust-web3](https://github.com/tomusdrw/rust-web3) ⭐ 1,509 | 🐛 105 | 🌐 Rust | 📅 2026-04-27.
  Ethereum JSON-RPC multi-transport client. Rust implementation of web3 library.
* [alloy](https://github.com/alloy-rs/alloy) ⭐ 1,322 | 🐛 130 | 🌐 Rust | 📅 2026-08-19.
  Alloy connects applications to blockchains. Transports, Middleware, and Networks for the Alloy project. Rewrite of ethers-rs.
* [alloy core](https://github.com/alloy-rs/core) ⭐ 963 | 🐛 32 | 🌐 Rust | 📅 2026-08-20.
  High-performance, well-tested & documented core libraries for Ethereum.
* [ethers-reth](https://github.com/SorellaLabs/ethers-reth/) ⭐ 270 | 🐛 2 | 🌐 Rust | 📅 2023-10-18.
  An ether-rs middleware to access reth's db directly, bypassing JSON-RPC.
* [uint](https://github.com/recmo/uint) ⭐ 224 | 🐛 69 | 🌐 Rust | 📅 2026-08-17.
  Rust Uint crate using const-generics.
* [trie](https://github.com/alloy-rs/trie) ⭐ 160 | 🐛 6 | 🌐 Rust | 📅 2026-08-17.
  Fast Merkle-Patricia Trie (MPT) state root calculator and proof generator for prefix-sorted nibbles.
* [rlp](https://github.com/alloy-rs/rlp) ⭐ 113 | 🐛 3 | 🌐 Rust | 📅 2026-08-17.
  Fast implementation of Ethereum RLP serialization.
* [ssz-rs](https://github.com/ralexstokes/ssz-rs) ⭐ 112 | 🐛 17 | 🌐 Rust | 📅 2024-10-04.
  Implementation of Ethereum's ssz.
* [chains](https://github.com/alloy-rs/chains) ⭐ 107 | 🐛 2 | 🌐 Rust | 📅 2026-08-17.
  Canonical type definitions for EIP-155 chains.
* [enr](https://github.com/sigp/enr) ⭐ 65 | 🐛 5 | 🌐 Rust | 📅 2025-09-29.
  This crate contains an implementation of an Ethereum Node Record (ENR) as specified by EIP-778.
* [ethereum\_ssz](https://github.com/sigp/ethereum_ssz) ⭐ 28 | 🐛 10 | 🌐 Rust | 📅 2026-07-20.
  SimpleSerialize (SSZ) implementation optimised for speed and security.
* [milhouse](https://github.com/sigp/milhouse) ⭐ 27 | 🐛 23 | 🌐 Rust | 📅 2026-08-20.
  Persistent binary merkle tree.
* [trie-proofs](https://github.com/HerodotusDev/trie-proofs) ⭐ 12 | 🐛 4 | 🌐 Rust | 📅 2025-10-14.
  A comprehensive transaction MPT proofs handler for Ethereum / Starknet.
* [eth-trie.rs](https://github.com/ethereum/eth-trie.rs) ⭐ 10 | 🐛 2 | 🌐 Rust | 📅 2025-06-29.
  Rust implementation of the Modified Patricia Tree (aka Trie).
* [ssz\_types](https://github.com/sigp/ssz_types) ⭐ 6 | 🐛 8 | 🌐 Rust | 📅 2026-06-29.
  List, vector and bitfield types for SSZ.
* [sszb](https://github.com/rakita/sszb) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2021-12-06.
  SSZ with BigEndian notation.
* [Rust Crypto](https://github.com/RustCrypto).
  Dozens of popular crates which provide pure Rust implementations of cryptographic algorithms.

## Light Clients

* [Helios](https://github.com/a16z/helios) ⭐ 2,174 | 🐛 94 | 🌐 Rust | 📅 2026-06-26.
  A fast, secure, and portable light client for Ethereum.
* [Trin](https://github.com/ethereum/trin) ⭐ 441 | 🐛 63 | 🌐 Rust | 📅 2025-09-23.
  An Ethereum portal client: a json-rpc server with nearly instant sync, and low CPU & storage usage.
* [sp1-helios](https://github.com/succinctlabs/sp1-helios) ⭐ 82 | 🐛 1 | 🌐 Rust | 📅 2026-07-14.
  On-chain Ethereum light client built with SP1.
* [Ethereum zk light client](https://github.com/argumentcomputer/zk-light-clients/tree/dev/ethereum) ⭐ 69 | 🐛 24 | 🌐 Rust | 📅 2024-12-04.
  Ethereum zk light client leveraging Sphinx (fork of SP1).

## Scaling

* [c-kzg-4844](https://github.com/ethereum/c-kzg-4844/blob/main/bindings/rust/README.md) ⭐ 174 | 🐛 7 | 🌐 C | 📅 2026-08-11.
  Minimal 4844 version of c-kzg (bindings for Rust).
* [KZG Ceremony Sequencer](https://github.com/ethereum/kzg-ceremony-sequencer) ⚠️ Archived.
  This implements KZG Ceremony Specification.
* [kzg](https://github.com/ralexstokes/kzg) ⭐ 36 | 🐛 0 | 🌐 Rust | 📅 2022-10-05.
  A library for KZG commitments over BLS12-381 in Rust.
  Proto-Danksharding Cryptography.
* [proto-danksharding-crypto](https://github.com/crate-crypto/proto-danksharding-crypto) ⭐ 12 | 🐛 0 | 🌐 Rust | 📅 2023-03-30.
* [kateth](https://github.com/jacobkaufmann/kateth) ⭐ 4 | 🐛 6 | 🌐 Rust | 📅 2024-04-11.
  Ethereum KZG.

## PBS - Proposer-Builder Separation

* [Artemis](https://github.com/paradigmxyz/artemis) ⭐ 2,961 | 🐛 37 | 🌐 Rust | 📅 2024-03-05.
  A simple, modular, and fast framework for writing MEV bots.
* [Brontes](https://github.com/SorellaLabs/brontes) ⭐ 672 | 🐛 21 | 🌐 Rust | 📅 2025-07-28.
  A blazingly fast general purpose blockchain analytics engine specialized in systematic mev detection.
* [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs) ⚠️ Archived.
  Discover historic Miner Extractable Value (MEV) opportunities.
* [rbuilder](https://github.com/flashbots/rbuilder) ⭐ 563 | 🐛 106 | 🌐 Rust | 📅 2026-07-20.
  rbuilder is a blazingly fast, state of the art Ethereum MEV-Boost block builder written in Rust.
* [mev-rs](https://github.com/ralexstokes/mev-rs/) ⭐ 456 | 🐛 40 | 🌐 Rust | 📅 2024-10-24.
  A gateway to a network of block builders.
* [ethers-flashbots](https://github.com/onbjerg/ethers-flashbots) ⚠️ Archived.
  An Ethers middleware for submitting Flashbots bundles.
* [mev-share-rs](https://github.com/paradigmxyz/mev-share-rs) ⭐ 215 | 🐛 6 | 🌐 Rust | 📅 2025-05-17.
  Rust client library for Flashbots MEV-share.
* [Hindsight](https://github.com/flashbots/hindsight) ⭐ 130 | 🐛 14 | 🌐 Rust | 📅 2024-04-26.
  Retroactively estimate Uniswap-ish MEV on Flashbots MEV-Share by simulating backrun-arbitrages.
* [evangelion](https://github.com/jacobkaufmann/evangelion/) ⭐ 81 | 🐛 9 | 🌐 Rust | 📅 2023-09-16.
  A prototype Ethereum block builder.
* [suave-andromeda-revm](https://github.com/flashbots/suave-andromeda-revm) ⭐ 32 | 🐛 6 | 🌐 Rust | 📅 2024-07-25.
  Andromeda revm execution service - EVM with precompiles used internally by SUAVE for key management and boostrapping kettles.

## Account Abstraction

* [Rundler](https://github.com/alchemyplatform/rundler) ⭐ 391 | 🐛 47 | 🌐 Rust | 📅 2026-08-18.
  An ERC-4337 Bundler in Rust - high-performance, modular implementation of an ERC-4337 bundler.
* [Silius](https://github.com/Vid201/silius/) ⭐ 273 | 🐛 34 | 🌐 Rust | 📅 2025-08-18.
  ERC-4337 (Account Abstraction) - modular and efficient bundler implementation.
* [UoIndexer](https://github.com/zsluedem/UoIndexer) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2023-05-03.
  User operation indexer for ERC-4337.
* [ethers-userop](https://github.com/qi-protocol/ethers-userop/).
  An ether-rs middleware to craft user operations.

## ZKP and zkEVM

* [sp1](https://github.com/succinctlabs/sp1) ⭐ 1,729 | 🐛 124 | 🌐 Rust | 📅 2026-08-18.
  A performant, 100% open-source, contributor-friendly zkVM.
* [noir-lang](https://github.com/noir-lang/noir) ⭐ 1,391 | 🐛 796 | 🌐 Rust | 📅 2026-08-20.
  Noir is a domain specific language for zero knowledge proofs.
* [zkevm-circuits](https://github.com/privacy-scaling-explorations/zkevm-circuits) ⚠️ Archived.
  Circuits for zkEVM.
* [lambdaworks](https://github.com/lambdaclass/lambdaworks) ⭐ 735 | 🐛 111 | 🌐 Rust | 📅 2026-08-14.
  The library for kids who wanna learn how to do SNARKs and learn other cryptographic stuff too.
* [Zeth](https://github.com/risc0/zeth) ⭐ 450 | 🐛 15 | 🌐 Rust | 📅 2026-07-17.
  A "Type 0" zkEVM. Prove validity of Ethereum blocks using RISC Zero's zkVM.
* [OpenVM](https://github.com/openvm-org/openvm) ⭐ 393 | 🐛 17 | 🌐 Rust | 📅 2026-08-20.
  OpenVM is a performant and modular zkVM framework built for customization and extensibility.
* [halo2](https://github.com/privacy-scaling-explorations/halo2) ⚠️ Archived.
  Implementation of halo2 zkSNARK proof system.
* [chiquito](https://github.com/privacy-scaling-explorations/chiquito) ⚠️ Archived.
  DSL for Halo2 circuits.
* [rsp](https://github.com/succinctlabs/rsp) ⭐ 164 | 🐛 3 | 🌐 Rust | 📅 2026-08-13.
  A minimal implementation of ZKPs of Ethereum block execution using Reth.
* [sp1-reth](https://github.com/succinctlabs/sp1-reth).
  A performant, type-1 zkEVM written in Rust & SP1.

## Statelessness

* [ress](https://github.com/paradigmxyz/ress) ⭐ 188 | 🐛 5 | 🌐 Rust | 📅 2025-04-16.
  The implementation of Stateless Ethereum client based on Reth.
* [rust-verkle](https://github.com/crate-crypto/rust-verkle) ⭐ 134 | 🐛 36 | 🌐 Rust | 📅 2024-10-25.
  This is a proof of concept implementation of Verkle Tries.
* [verkle-block-sample](https://github.com/gballet/verkle-block-sample) ⭐ 39 | 🐛 1 | 🌐 Rust | 📅 2022-11-25.
  Example of a block root with a Verkle state root.

## Layer 2

### Arbitrum

* [Stylus](https://github.com/OffchainLabs/stylus-sdk-rs) ⭐ 323 | 🐛 25 | 🌐 Rust | 📅 2026-08-11.
  Rust Smart Contracts on Arbitrum.

### Optimism

* [Magi](https://github.com/a16z/magi) ⭐ 637 | 🐛 24 | 🌐 Rust | 📅 2024-08-16.
  A blazing fast OP Stack rollup client.
* [odyssey](https://github.com/ithacaxyz/odyssey) ⭐ 316 | 🐛 26 | 🌐 Rust | 📅 2025-07-12.
  A testnet open-source Layer 2 from the future, co-designed with the developer tools stack.
* [kona](https://github.com/ethereum-optimism/kona) ⚠️ Archived.
  A suite of `no_std` components for the OP Stack state transition function.
* [op-succinct](https://github.com/succinctlabs/op-succinct) ⭐ 214 | 🐛 33 | 🌐 Rust | 📅 2026-08-17.
  Standalone repo to use Kona & SP1 to verify OP Stack blocks.
* [Reth AlphaNet](https://github.com/paradigmxyz/alphanet) ⚠️ Archived.
  Reth AlphaNet is a testnet OP Stack-compatible rollup aimed at enabling experimentation of bleeding edge Ethereum Research.
* [optimism-rs](https://github.com/refcell/optimism-rs) ⚠️ Archived.
  Scaling Ethereum, but this time in rust.
* [op-alloy](https://github.com/alloy-rs/op-alloy) ⭐ 88 | 🐛 6 | 🌐 Rust | 📅 2026-02-18.
  Optimism alloy types.
* [op-reth](https://github.com/anton-rs/op-reth) ⚠️ Archived.
  Optimism + Reth.
* [cannon-rs](https://github.com/anton-rs/cannon-rs) ⚠️ Archived.
  An alternative implementation of the OP Stack's Cannon, a MIPS emulator for the EVM.
* [op-up](https://github.com/anton-rs/op-up) ⚠️ Archived.
  Composable OP Stack Orchestration.
* [durin](https://github.com/anton-rs/durin) ⚠️ Archived.
  A Rust library for creating solvers in the OP Stack's dispute protocol.
* [op-revm](https://github.com/anton-rs/op-revm) ⚠️ Archived.
  Optimism + Revm.

### Polygon

* [plonky2](https://github.com/0xPolygonZero/plonky2) ⭐ 858 | 🐛 25 | 🌐 Rust | 📅 2025-07-01.
  Plonky2, a SNARK implementation based on techniques from PLONK and FRI.

### Scroll

* [scroll-prover](https://github.com/scroll-tech/scroll-prover) ⚠️ Archived.
  Scroll's zkEVM rust crates.

### Starknet

* [Cairo](https://github.com/starkware-libs/cairo) ⭐ 1,902 | 🐛 209 | 🌐 Rust | 📅 2026-08-20.
  Cairo is the first Turing-complete language for creating provable programs for general computation.
* [Madara](https://github.com/keep-starknet-strange/madara) ⭐ 524 | 🐛 0 | 🌐 Rust | 📅 2026-08-16.
  Madara is a blazing fast Starknet sequencer, based on substrate.
* [Starknet Foundry](https://github.com/foundry-rs/starknet-foundry) ⭐ 393 | 🐛 184 | 🌐 Rust | 📅 2026-08-20.
  Blazing fast toolkit for developing Starknet contracts.
* [Papyrus](https://github.com/starkware-libs/papyrus) ⚠️ Archived.
  Papyrus is a Starknet full node written.
* [starknet-rs](https://github.com/xJonathanLEI/starknet-rs) ⭐ 312 | 🐛 23 | 🌐 Rust | 📅 2025-11-09.
  Complete Starknet library.
* [Stone Prover](https://github.com/starkware-libs/stone-prover) ⭐ 268 | 🐛 12 | 🌐 C++ | 📅 2024-09-16.
  Stone prover - this repository contains a prover and a verifier for STARKs, and in particular for the CPU AIR underlying the CairoZero programming language.
* [starknet\_in\_rust](https://github.com/lambdaclass/starknet_in_rust) ⚠️ Archived.
  A Rust implementation of Starknet execution logic.
* [cairo\_native](https://github.com/lambdaclass/cairo_native) ⭐ 135 | 🐛 77 | 🌐 Rust | 📅 2026-08-20.
  A compiler to convert Cairo's intermediate representation "Sierra" code to MLIR.
* [types-rs](https://github.com/starknet-io/types-rs) ⭐ 78 | 🐛 3 | 🌐 Rust | 📅 2025-12-02.
  Starknet Rust types.
* [cairo-vm](https://github.com/lambdaclass/cairo-vm) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2026-04-09.
  cairo-vm is a Rust implementation of the Cairo VM.

### zkSync

* [zksync-era](https://github.com/matter-labs/zksync-era) ⭐ 3,234 | 🐛 147 | 🌐 Rust | 📅 2026-08-20.
  zkSync era.
* [era-sync\_vm](https://github.com/matter-labs/era-sync_vm) ⚠️ Archived.
  Circuit Implementation of zkVM for zkSync Era.
* [era\_vm](https://github.com/lambdaclass/era_vm) ⭐ 19 | 🐛 14 | 🌐 Rust | 📅 2024-09-05.
  EraVM implementation.

### Taiko

* [raiko](https://github.com/taikoxyz/raiko) ⚠️ Archived.
  Multi-proofs for Taiko. SNARKS, STARKS and Trusted Execution Enclave.

### Fuel

* [Sway](https://github.com/FuelLabs/sway) ⭐ 61,495 | 🐛 932 | 🌐 Rust | 📅 2026-08-14.
  Sway is a language developed for the Fuel blockchain. It is heavily inspired by Rust and aims to bring modern language development and performance to the blockchain ecosystem.
* [fuel-core](https://github.com/FuelLabs/fuel-core) ⭐ 56,898 | 🐛 200 | 🌐 Rust | 📅 2026-08-18.
  Rust full node implementation of the Fuel v2 protocol.
* [fuels-rs](https://github.com/FuelLabs/fuels-rs) ⭐ 43,061 | 🐛 70 | 🌐 Rust | 📅 2026-06-29.
  Rust SDK for Fuel.

### Aztec

* [aztec-nr](https://github.com/AztecProtocol/aztec-nr) ⭐ 149 | 🐛 24 | 🌐 Noir | 📅 2026-08-20.
  Aztec-nr is a Noir framework for smart contracts on Aztec.

### Other

* [zenith-rs](https://github.com/init4tech/zenith-rs) ⚠️ Archived.
  Rust types and services for Zenith (next-gen rollup system).

## dApp Development

* [Foundry](https://github.com/foundry-rs/foundry) ⭐ 10,567 | 🐛 293 | 🌐 Rust | 📅 2026-08-20.
  Foundry is a blazing fast, portable and modular toolkit for Ethereum application development.
* [Rivet](https://github.com/paradigmxyz/rivet) ⭐ 929 | 🐛 21 | 🌐 TypeScript | 📅 2025-03-26.
  Developer Wallet & DevTools for Anvil.
* [solar](https://github.com/paradigmxyz/solar) ⭐ 555 | 🐛 14 | 🌐 Rust | 📅 2026-08-20.
  Blazingly fast, modular and contributor friendly Solidity compiler, written in Rust.

## Smart Contracts

* [Fe](https://github.com/ethereum/fe) ⭐ 1,727 | 🐛 140 | 🌐 Rust | 📅 2026-08-01.
  Emerging smart contract language for the Ethereum blockchain.
* [Heimdall](https://github.com/Jon-Becker/heimdall-rs) ⭐ 1,600 | 🐛 20 | 🌐 Rust | 📅 2026-08-16.
  Heimdall is an advanced EVM smart contract toolkit specializing in bytecode analysis.
* [Pyrometer](https://github.com/nascentxyz/pyrometer) ⭐ 798 | 🐛 15 | 🌐 Rust | 📅 2025-02-14.
  A tool for analyzing the security and parameters of a solidity smart contract.
* [huff-rs](https://github.com/huff-language/huff-rs) ⚠️ Archived.
  A low-level assembly language for the Ethereum Virtual Machine built in blazing-fast pure rust.
* [ethabi](https://github.com/rust-ethereum/ethabi) ⭐ 523 | 🐛 46 | 🌐 Rust | 📅 2023-08-16.
  Encode and decode smart contract invocations.
* [svm-rs](https://github.com/alloy-rs/svm-rs) ⭐ 288 | 🐛 8 | 🌐 Rust | 📅 2026-08-17.
  Solidity-Compiler Version Manager.

## Analytics

* [cryo](https://github.com/paradigmxyz/cryo) ⭐ 1,579 | 🐛 80 | 🌐 Rust | 📅 2025-01-08.
  cryo is the easiest way to extract blockchain data to parquet, csv, json, or python dataframes.
* [Ethshadow](https://github.com/ethereum/ethshadow) ⭐ 59 | 🐛 5 | 🌐 Rust | 📅 2025-03-12.
  Simulate a full Ethereum network using Shadow.

## Misc

* [block-explorers](https://github.com/foundry-rs/block-explorers) ⚠️ Archived.
  Bindings for the etherscan API and other block explorers.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
