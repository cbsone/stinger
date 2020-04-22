---
content_title: Stinger Overview
---

Stinger is the next-generation blockchain platform for creating and deploying smart contracts and distributed applications. Stinger comes with a number of programs. The primary ones included in Stinger are the following:

* [Stnode](01_nodeos/index.md) (node + eos = stnode)  - core service daemon that runs a node for block production, API endpoints, or local development.
* [Cleos](02_cleos/index.md) (cli + eos = cleos) - command line interface to interact with the blockchain (via `stnode`) and manage wallets (via `keosd`).
* [Keosd](03_keosd/index.md) (key + eos = keosd) - component that manages Stinger keys in wallets and provides a secure enclave for digital signing.

The basic relationship between these components is illustrated in the diagram below.

![Stinger components](eosio_components.png)

[[info | What's Next?]]
| [Install the Stinger Software](00_install/index.md) before exploring the sections above.
