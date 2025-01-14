---
title: Supported Networks
sidebar_position: 4
---

## Overview
Chains supported by the Router Chain are as follows:

```json
{
    "chains": [
        {
            "chainId": "137",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Polygon",
            "chainRpc": "https://polygon-rpc.com",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "42161",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Arbitrum",
            "chainRpc": "https://arbitrum-one.publicnode.com",
            "blocksToSearch": 1000,
            "blockTime": "3s"
        },
        {
            "chainId": "43114",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Avalanche",
            "chainRpc": "https://avalanche.public-rpc.com",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "10",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Optimism",
            "chainRpc": "https://mainnet.optimism.io",
            "blocksToSearch": 1000,
            "blockTime": "3s"
        },
        {
            "chainId": "56",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "BSC",
            "chainRpc": "https://bsc-dataseed4.bnbchain.org",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "1101",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "polygonZkEvm",
            "chainRpc": "https://zkevm-rpc.com",
            "blocksToSearch": 1000,
            "blockTime": "10s"
        },
        {
            "chainId": "324",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "zkSync",
            "chainRpc": "https://mainnet.era.zksync.io",
            "blocksToSearch": 1000,
            "blockTime": "10s"
        },
        {
            "chainId": "1",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Ethereum",
            "chainRpc": "https://eth-pokt.nodies.app",
            "blocksToSearch": 1000,
            "blockTime": "15s"
        },
        {
            "chainId": "728126428",
            "chainType": "CHAIN_TYPE_TRON",
            "chainName": "tron-mainnet",
            "chainRpc": "https://api.trongrid.io/jsonrpc",
            "chainGRpc": "grpc.trongrid.io:50051",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "8453",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Base",
            "chainRpc": "https://base.publicnode.com",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "534352",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Scroll",
            "chainRpc": "https://rpc.ankr.com/scroll",
            "blocksToSearch": 1000,
            "blockTime": "10s"
        },
        {
            "chainId": "169",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Manta",
            "chainRpc": "https://pacific-rpc.manta.network/http",
            "blocksToSearch": 1000,
            "blockTime": "10s"
        },
        {
            "chainId": "5000",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Mantle",
            "chainRpc": "https://rpc.mantle.xyz",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "34443",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Mode Network",
            "chainRpc": "https://1rpc.io/mode",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "288",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "BOBA Network",
            "chainRpc": "https://mainnet.boba.network",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "1088",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Metis Network",
            "chainRpc": "https://andromeda.metis.io/?owner=1088",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "10242",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Arthera Mainnet",
            "chainRpc": " https://rpc.arthera.net",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "30",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "RootStock",
            "chainRpc": "https://public-node.rsk.co",
            "blocksToSearch": 1000,
            "blockTime": "3s"
        },
        {
            "chainId": "1313161554",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Aurora",
            "chainRpc": "https://mainnet.aurora.dev",
            "blocksToSearch": 1000,
            "blockTime": "3s"
        },
        {
            "chainId": "59144",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Linea",
            "chainRpc": "https://rpc.linea.build",
            "blocksToSearch": 1000,
            "blockTime": "2s"
        },
        {
            "chainId": "81457",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "BlastL2",
            "chainRpc": "https://blast.blockpi.network/v1/rpc/public",
            "blocksToSearch": 1000,
            "blockTime": "2s"
        },
        {
            "chainId": "7225878",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Saakuru Mainnet",
            "chainRpc": "https://rpc-mainnet.saakuru.network/",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "200901",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "bitlayer-mainnet",
            "chainRpc": "https://rpc.bitlayer-rpc.com",
            "blocksToSearch": 1000,
            "blockTime": "5s"
        },
        {
            "chainId": "167000",
            "chainType": "CHAIN_TYPE_EVM",
            "chainName": "Taiko",
            "chainRpc": "https://rpc.taiko.xyz",
            "blocksToSearch": 1000,
            "blockTime": "60s"
        },
        {
            "chainId": "near",
            "chainType": "CHAIN_TYPE_NEAR",
            "chainName": "near-mainnet",
            "chainRpc": "https://rpc.mainnet.near.org",
            "blocksToSearch": 10000,
            "blockTime": "2s",
            "useStreamerApi": true,
            "nearStreamerApi": "http://13.233.000.00:6902/"
        }
    ]
}
```

:::info
1. For better performance, please use premium RPCs or self deployed nodes for the above supported networks.
2. For Near chain, please set up streamer before enabling it for orchestration.  
:::
