
# Stinger - The Most Powerful Infrastructure for Decentralized Applications

[![Build status](https://badge.buildkite.com/370fe5c79410f7d695e4e34c500b4e86e3ac021c6b1f739e20.svg?branch=master)](https://buildkite.com/cbsone/cbsone)

Welcome to the Stinger source code repository! This software enables businesses to rapidly build and deploy high-performance and high-security blockchain-based applications.

Some of the groundbreaking features of Stinger include:

1. Free Rate Limited Transactions
1. Low Latency Block confirmation (0.5 seconds)
1. Low-overhead Byzantine Fault Tolerant Finality
1. Designed for optional high-overhead, low-latency BFT finality
1. Smart contract platform powered by WebAssembly
1. Designed for Sparse Header Light Client Validation
1. Scheduled Recurring Transactions
1. Time Delay Security
1. Hierarchical Role Based Permissions
1. Support for Biometric Hardware Secured Keys (e.g. Apple Secure Enclave)
1. Designed for Parallel Execution of Context Free Validation Logic
1. Designed for Inter Blockchain Communication

## Disclaimer

CBS One is neither launching nor operating any initial public blockchains based upon the Stinger software. This release refers only to version 1.0 of our open source software. We caution those who wish to use blockchains built on Stinger to carefully vet the companies and organizations launching blockchains based on Stinger before disclosing any private keys to their derivative software.

## Supported Operating Systems

Stinger currently supports the following operating systems:  

1. Amazon Linux 2
2. CentOS 7
3. Ubuntu 16.04
4. Ubuntu 18.04
5. MacOS 10.14 (Mojave)

---

**Note: It may be possible to install Stinger on other Unix-based operating systems. This is not officially supported, though.**

---

## Software Installation

If you are new to Stinger, it is recommended that you install the [Stinger Prebuilt Binaries](#prebuilt-binaries), then proceed to the [Getting Started](#getting-started) walkthrough. If you are an advanced developer, a block producer, or no binaries are available for your platform, you may need to [Build Stinger from source](#paste-link-here).

---

**Note: If you used our scripts to build/install Stinger, please run the [Uninstall Script](#uninstall-script) before using our prebuilt binary packages.**

---

## Prebuilt Binaries

Prebuilt Stinger software packages are available for the operating systems below. Find and follow the instructions for your OS:

### Mac OS X:

#### Mac OS X Brew Install
```sh
$ brew tap cbsone/stinger
$ brew install stinger
```
#### Mac OS X Brew Uninstall
```sh
$ brew remove stinger
```

### Ubuntu Linux:

#### Ubuntu 18.04 Package Install
```sh
$ wget https://github.com/cbsone/stinger/releases/download/v2.0.4/Stinger_2.0.4-1-ubuntu-18.04_amd64.deb
$ sudo apt install ./Stinger_2.0.4-1-ubuntu-18.04_amd64.deb
```
#### Ubuntu 16.04 Package Install
```sh
$ wget https://github.com/cbsone/stinger/releases/download/v2.0.4/Stinger_2.0.4-1-ubuntu-16.04_amd64.deb
$ sudo apt install ./Stinger_2.0.4-1-ubuntu-16.04_amd64.deb
```
#### Ubuntu Package Uninstall
```sh
$ sudo apt remove cbsone
```

### RPM-based (CentOS, Amazon Linux, etc.):

#### RPM Package Install
```sh
$ wget https://github.com/cbsone/stinger/releases/download/v2.0.4/stinger-2.0.4-1.el7.x86_64.rpm
$ sudo yum install ./stinger-2.0.4-1.el7.x86_64.rpm
```
#### RPM Package Uninstall
```sh
$ sudo yum remove cbsone
```

## Uninstall Script
To uninstall the Stinger built/installed binaries and dependencies, run:
```sh
./scripts/Stinger_uninstall.sh
```

## Documentation
1. [cbsnode](http://github.io/cbsnode/stinger/docs)
    - [Usage](http://github.io/cbsnode/stinger/docs/usage/index)
    - [Replays](http://github.io/cbsnode/stinger/docs/replays/index)
    - [Chain API Reference](http://github.io/cbsnode/stinger/docs/plugins/chain_api_plugin/api-reference/index)
    - [Troubleshooting](http://github.io/cbsnode/stinger/docs/troubleshooting/index)
1. [cbs-cli](http://github.io/cbsnode/stinger/docs/cbs-cli/)
1. [cbs-keys](http://github.io/cbsnode/stinger/docs/cbs-keys/)

## Resources
1. [Website](https://cbs.one)
1. [Blog](https://medium.com/cbsone)
1. [Developer Portal](#paste-link-here)
1. [Community Telegram Group](https://t.me/EOSProject)
1. [Developer Telegram Group](https://t.me/joinchat/EaEnSUPktgfoI-XPfMYtcQ)
1. [White Paper](https://github.com/cbsone/Documentation/blob/master/TechnicalWhitePaper.md)
1. [Roadmap](https://github.com/cbsone/Documentation/blob/master/Roadmap.md)

<a name="gettingstarted"></a>
## Getting Started
Instructions detailing the process of getting the software, building it, running a simple test network that produces blocks, account creation and uploading a sample contract to the blockchain can be found in the [Getting Started](#getting-started) walkthrough.

## Contributing

[Contributing Guide](./CONTRIBUTING.md)

[Code of Conduct](./CONTRIBUTING.md#conduct)

## License

Stinger is released under the open source [MIT](./LICENSE) license and is offered “AS IS” without warranty of any kind, express or implied. Any security provided by the Stinger software depends in part on how it is used, configured, and deployed. Stinger is built upon many third-party libraries such as WABT (Apache License) and WAVM (BSD 3-clause) which are also provided “AS IS” without warranty of any kind. Without limiting the generality of the foregoing, CBS One makes no representation or guarantee that Stinger or any third-party libraries will perform as intended or will be free of errors, bugs or faulty code. Both may fail in large or small ways that could completely or partially limit functionality or compromise computer systems. If you use or implement Stinger, you do so at your own risk. In no event will CBS One be liable to any party for any damages whatsoever, even if it had been advised of the possibility of damage.  

## Important

See [LICENSE](./LICENSE) for copyright and license terms.

All repositories and other materials are provided subject to the terms of this [IMPORTANT](./IMPORTANT.md) notice and you must familiarize yourself with its terms.  The notice contains important information, limitations and restrictions relating to our software, publications, trademarks, third-party resources, and forward-looking statements.  By accessing any of our repositories and other materials, you accept and agree to the terms of the notice.
