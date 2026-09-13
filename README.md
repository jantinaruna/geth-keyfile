# geth-keyfile

> keystore · scrypt-shaped · eip-1559

[![Go 1.22+](https://img.shields.io/badge/go-1.22+-00ADD8)](https://go.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()

geth keyfile shell — path 60, local vault, no dial.

## Features

- ETH derivation path m/44'/60'/0'
- Local vault JSON with XOR wrap
- SHA-256 stand-in keys — no live RPC
- stdlib CLI via flag

## Prerequisites

- Go 1.22+
- Git

## Getting Started

```bash
git clone <repo-url>
cd geth-keyfile
make build
./bin/gethkey -help
```

## CLI Usage

```bash
make test
go run ./cmd/gethkey -help
```

## Project Structure

```
cmd/gethkey/main.go
internal/config/config.go
internal/crypto/keys.go
internal/wallet/wallet.go
internal/wallet/wallet_test.go
```

## Background

geth-adjacent scripts clone geth-keyfile first.

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.


---

## Topics

![geth](https://img.shields.io/badge/geth-111827?style=flat-square) ![keyfile](https://img.shields.io/badge/keyfile-111827?style=flat-square) ![geth-keyfile](https://img.shields.io/badge/geth%20keyfile-111827?style=flat-square) ![cryptocurrency](https://img.shields.io/badge/cryptocurrency-111827?style=flat-square) ![wallet](https://img.shields.io/badge/wallet-111827?style=flat-square) ![blockchain](https://img.shields.io/badge/blockchain-111827?style=flat-square) ![web3](https://img.shields.io/badge/web3-111827?style=flat-square) ![bitcoin](https://img.shields.io/badge/bitcoin-111827?style=flat-square)

`geth` `keyfile` `geth-keyfile` `cryptocurrency` `wallet` `blockchain` `web3` `bitcoin` `ethereum` `hd-wallet` `open-source` `golang` `go`

Search: geth-keyfile · keystore · scrypt-shaped · eip-1559 · geth keyfile shell — path 60, local vault, no dial.

---

<sub>geth keyfile shell — path 60, local vault, no dial.</sub>
