# Your First OmniChain dApp
In this section, we'll provide a step-by-step guide for how users can deploy their first cross-chain dApp that leverages the middleware infra enabled by the Router Chain.

Before diving into the guide, it's important to understand Router's <a href="../develop/message-transfer-via-crosstalk/key-concepts/high-level-architecture" target="_blank">high-level architecture</a>. Once you have gained a basic understanding of how a cross-chain application works on the Router Chain, you can read through this guide that will cover the following sections:

-   Setting up Router's EVM Devnet to deploy and test sample cross-chain applications
-   Deploying a sample application contract (Solidity) on Router's EVM Devnet
-   Deploying a sample bridge contract (CosmWasm) on Router's Alpha Devnet
-   Testing the end-to-end workflow
    <!-- 1. Sending a random cross-chain message to Router's Gateway contract on the source chain
    2. Verifying the state change of the bridge contract following the delivery of the inbound request to the Router Chain
    3. Verifying the state change of the application contract following the delivery of the outbound request to the destination chain
    4. Verifying the state change of the bridge contract following the delivery of the outbound acknowledgment to the Router Chain -->

At the end of the guide, we'll have two working contracts:
1. An application contract on Router's EVM Devnet acting as both the source and destination contract
2. A bridge contract on the Router Chain