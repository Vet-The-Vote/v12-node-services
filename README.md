V11 Node Services
---

* Date: 01/31/2026

This repo contains additional services, which are run on a V12 Compute Node as containerized micro-services.  At the time of this writing only the following additional services are run on a V12 Compute Node:

* `v12_tx_wrapper`: The **`v12_tx_wrapper` service** acts as a bridge between standard Ethereum-style transactions and the underlying V12 EVM contract, packaging, signing, and submitting EVM transactions in a format the blockchain can execute. It allows users and tools to interact with the V12 EVM as if it were a native Ethereum network, while handling all V12-specific transaction and permission details behind the scenes.
