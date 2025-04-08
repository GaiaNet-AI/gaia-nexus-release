# GaiaNexus

## Installation

```bash
# Install GaiaNode
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/raw/refs/heads/feat-integrate-nexus/install.sh' | bash

# Download the wasm file
curl -LO https://github.com/GaiaNet-AI/gaia-nexus-release/releases/download/0.1.0/llama-api-server.wasm

# Move the wasm file to the GaiaNode directory
mv llama-api-server.wasm $HOME/gaianet/
```

## Usage

```bash
# initialize the node
gaianet init

# start the node
gaianet start

# stop the node
gaianet stop
```
