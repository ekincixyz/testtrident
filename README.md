<p align="left">
  <img height="100" width="100" src="https://abchprod.wpengine.com/wp-content/uploads/2024/05/Trident-Color.png" alt="Trident"/>
</p>

# Trident Tests for (X)
This repository serves as an example of tests written with the Solana Fuzzing Framework [Trident](https://github.com/Ackee-Blockchain/trident).


## Setup

1. Clone this repository
2. `git submodule update --init --recursive` if not cloned with `--recursive`
3. `cd source && npm install && cd ..` to install dependencies
4. `wake up pytypes` to generate pytypes
5. `wake test` to run tests

Tested with `trident` version `0.X.0` and `anchor` version `0.X.0 (53b15e6 2023-12-14T00:16:31.655140883Z)`. Some of the tests expect a local full node at http://localhost:8545 with the Ethereum mainnet at block 18414333 running.
