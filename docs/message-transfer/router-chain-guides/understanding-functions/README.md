---
title: Functions on Router chain's middleware contract
sidebar_position: 4
---

import {
HomepageCard as Card,
HomepageSection as Section,
} from '../../../../src/components/HomepageComponents';

import {
IDEIcon,
Tscodegen,
} from '../../../../src/icons';

In the cosmwasm smart contact, `router-wasm-bindings` needs to be added to support the cross-chain functionality.

### router-wasm-bindings as dependency

The router-wasm-bindings crate dependency can be added as shown in the following code snippet.

```jsx
[dependencies]
# add the following line in the cargo.toml [dependencies] section
router-wasm-bindings = "0.2.4"
```

To implement cross-chain interoperability, the contract needs to implement the following functionality

- **SudoMsg**
  - to handle incoming requests from the other chains
- **RouterMsg**
  - to send a request to the other chains

The contract can write the intermediate business logic in-between the incoming request and outbound request. While writing the intermediate business logic, the developer can convert single or multiple incoming requests into single or multiple outbound requests.
Also, while creating requests to other chains, the contract can be developed in such a way that multiple requests can be generated for different chains.
You can find examples of different scenarios in the [_cw-bridge-contracts_](https://github.com/router-protocol/cw-bridge-contracts.git) repository.

<Section>
  <Card
    title="SudoMsg"
    description="Enum type for handling the incoming requests on Router chain's contracts"
    to="/message-transfer/router-chain-guides/understanding-functions/sudomsg"
    icon={<IDEIcon />}
  />
    <Card
    title="RouterMsg"
    description="Enum type for creating outbound requests for destination chain contracts"
    to="/message-transfer/router-chain-guides/understanding-functions/routermsg"
    icon={<Tscodegen />}
  /> 
</Section>