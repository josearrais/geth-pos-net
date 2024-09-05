# Build a private Ethereum network post merge

This guide explains how to set up a private network of multiple Geth nodes. Geth only works in PoS mode and in concert with a consensus client. In order to run multiple nodes locally, each one requires a separate data directory (--datadir). The nodes must also know about each other and be able to exchange information, share an initial state and a common consensus algorithm.

## Prerequisites

Before you start, make sure you have the following:

- [Geth](https://geth.ethereum.org/downloads) client installed
