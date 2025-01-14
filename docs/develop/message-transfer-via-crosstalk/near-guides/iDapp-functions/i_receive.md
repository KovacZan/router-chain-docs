---
title: i_receive
sidebar_position: 3
---

# `i_receive` Function

The cross-chain request initiated from the source chain will deliver the payload to the destination contract address specified in the `contractCalls` parameter. On the destination contract, a function needs to be implemented to handle this payload:

```javascript
fn i_receive(&self, request_sender: String, packet: Vec<u8>, src_chain_id: String) -> Vec<u8>;
```

In this function, you will get the address of the contract that initiated the request from the source chain, the payload that was created on the source chain and the source chain ID. After receiving this information, you can process your payload and complete your cross-chain transaction.

:::caution
It is mandatory to include this function in your contract on the destination chain; otherwise, the request will fail.
:::
