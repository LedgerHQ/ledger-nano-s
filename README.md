# Ledger Nano S for developers

The Ledger Nano S is a personal lightweight mobile device architectured around a ST31 secure element with USB connectivity.

It is based on [BOLOS](https://medium.com/@Ledger/introducing-bolos-blockchain-open-ledger-operating-system-b9893d09f333) (Blockchain Open Ledger Operating System), where apps can run securely in full isolation and leverage the main secrets (BIP39 seed) through allocated derivations. The functional architecture and project goals are described in the following Medium post : https://medium.com/@Ledger/secure-hardware-and-open-source-ecd26579d839 

The Nano S can be purchased from [Ledger shop](https://www.ledgerwallet.com/products/12-ledger-nano-s) and resellers.

This repository provides pointers to the development environment and applications available for developers

# Getting started 

Developers need to clone the following repositories and follow the building instructions 

* Development environment : contains the compiler (specific LLVM patch), available at https://github.com/LedgerHQ/blue-devenv/

* Ledger Nano S SDK : contains the development libraries, available at https://github.com/LedgerHQ/nanos-secure-sdk - use the tagged version matching the firmware flashed on your device

* Python tools : contains host tools to load applications on Nano S, available at https://github.com/LedgerHQ/blue-loader-python

# Production applications

* Bitcoin wallet : https://github.com/LedgerHQ/blue-app-btc

* Ethereum wallet : https://github.com/LedgerHQ/blue-app-eth

* FIDO U2F token : https://github.com/LedgerHQ/blue-app-u2f

# Applications under development 

* PGP/SSH agent : https://github.com/LedgerHQ/blue-app-ssh-agent, to be tested with https://github.com/romanz/trezor-agent on the ledger branch

# Sample applications 

To be added

# Documentation

To be added

