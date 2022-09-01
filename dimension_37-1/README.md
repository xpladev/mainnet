# Dimension_37-1

[xpla@v1.0.0](https://github.com/xpladev/xpla/releases/tag/v1.0.0) should be used to run the dimension_37-1 mainnet.

- The genesis event for dimension_37-1 mainnet will occur **2022-08-19T09:30:00Z**

## Prerequisites
* Go v1.18+ or higher
* Git
* curl
* jq

## How to Setup

```shell
$ git clone https://github.com/xpladev/xpla
$ git checkout v1.0.0
$ make install

$ xplad version
v1.0.0

$ xplad init [moniker] --chain-id dimension_37-1
$ wget https://raw.githubusercontent.com/xpladev/mainnet/main/dimension_37-1/genesis.json
$ cp genesis.json ~/.xpla/config/genesis.json

$ xplad start
```
