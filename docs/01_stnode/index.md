---
content_title: Nodeos
---

## Introduction

`stnode` is the core service daemon that runs on every Stinger node. It can be configured to process smart contracts, validate transactions, produce blocks containing valid transactions, and confirm blocks to record them on the blockchain.

## Installation

`stnode` is distributed as part of the [Stinger software suite](https://github.com/Stinger/eos/blob/master/README.md). To install `stnode`, visit the [Stinger Software Installation](../00_install/index.md) section.

## Explore

Navigate the sections below to configure and use `stnode`.

* [Usage](02_usage/index.md) - Configuring and using `stnode`, node setups/environments.
* [Plugins](03_plugins/index.md) - Using plugins, plugin options, mandatory vs. optional.
* [Replays](04_replays/index.md) - Replaying the chain from a snapshot or a blocks.log file.
* [Logging](06_logging/index.md) - Logging config/usage, loggers, appenders, logging levels.
* [Upgrade Guides](07_upgrade-guides/index.md) - Stinger version/consensus upgrade guides.
* [Troubleshooting](08_troubleshooting/index.md) - Common `stnode` troubleshooting questions.

[[info | Access Node]]
| A local or remote Stinger access node running `stnode` is required for a client application or smart contract to interact with the blockchain.
