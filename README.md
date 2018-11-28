# FVyper
[![CircleCI](https://circleci.com/gh/LayerXcom/verified-vyper-contracts.svg?style=svg)](https://circleci.com/gh/LayerXcom/verified-vyper-contracts)  
Formally Verified Vyper Contracts  

## About FVyper
FVyper is a collection of formally verified, useful Vyper programs.  
See [roadmap](https://github.com/LayerXcom/verified-vyper-contracts/issues/5).

## Structure of this project
The `/contracts` directory contains vyper contracts we use in formal verification (`/k` directory) and unit testing ( `/tests` directory).

The `/k` directory contains formal verification specs using [K Framework](https://github.com/kframework/k).

The `/tests` directory contains unit tests.

## References
This project is based on K Framework and Runtime Verification's works. See [their resources](https://github.com/runtimeverification/verified-smart-contracts/blob/master/README.md#resources) for the details of KEVM and background knowledge.