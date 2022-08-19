# Dimension_37-1

[xpla@v0.1.0](https://github.com/xpladev/xpla/releases/tag/v0.1.0) should be used to run the dimension_37-1 mainnet.

- The genesis event for dimension_37-1 mainnet will occur **TO BE DETERMINED**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/xpladev/xpla
$ git checkout v0.1.0
$ make install

$ xplad version
v0.1.0

$ xplad init [moniker] --chain-id dimension_37-1
$ wget https://raw.githubusercontent.com/xpladev/mainnet/main/dimension_37-1/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```
