# Overview

RGB is a complex system composed of multiple layers and multiple protocols on each of the levels. It is based on bitcoin and lightning network technologies, enhanced with client-side-validation (LNP/BP) - and adds a lot of stuff on top of them.

To reduce the level of complexity and mitigate the risks of cross-dependencies RGB developers took a layered approach, building the technology in modular way, where the modules are abstracted into a different strata - such that the strata below do not know anything about the strata above.

Overall, the development around RGB can be classified into the following fields, layered on top of each other:

* **Core protocol**, or **consensus-level development**. You may think of it as of something which means for RGB the same thing as "Bitcoin Core" means for Bitcoin.
* **Toolchain development**, which includes compilers, linkers, programming languagues and other tools. You may think of it as of Consensys company in Ethereum ecosystem.
* Schemata development
* Smart contracts issuance
* Wallet, exchange and other software integration

| Field of development                | Overseen by                                                   | Developers                                                                             | Main languagues                                              |
| ----------------------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| Core protocol                       | Decentralized ASAP                                            | RGB core maintainers, but eventually ossified (i.e. no development activity)           | Rust                                                         |
| Toolchain                           | LNP/BP Standards Association                                  | Association & member companies                                                         | Rust                                                         |
| Schemata                            | LNP/BP Standards Association                                  | Independent companies & developers                                                     | Contractum (alternatively, Rust)                             |
| Smart contracts                     | nobody                                                        | Issuers: independent companies, teams, DAOs, issuing assets & creating smart contracts | JSON & any languagues working with Web                       |
| Integration (wallets, exchange etc) | Integration standards proposed by LNP/BP Standards Asociation | Applied software companies: exchanges, wallet devs, outsourcers etc                    | JavaScript, TypeScript, Python, C, Java, Kotlin, Swift, Rust |

Core protocol devs, upon final RGB/1 v1.0 release will perform just the bugfixing.

Toolchain development, managed and sponsored through LNP/BP Standards Association, will continue to produce and improve tools for other developer categories.&#x20;

Schemata development consists of two main tasks:

* Defining standards for API used in most common use cases.
* Develop specific schemata, which may be seen as "RGB smart contract templates created by domain professionals".

The first case is covered by LNP/BP standards. Anybody can propose a new standard for a Schema (these standards are called "Schema (API) standards"). The standards are reviewed by the same process as any other LNP/BP standard, and are overseen by LNP/BP Standards Association quite similar to how IETF oversees Internet standards (RFCs).

Development of a schema confirming to some, multiple - or even none - or Schema Standards can be performed by anybody, independently from LNP/BP Standards Association or any other body. The only requirement - to unserstand how to develop Schema and ability to write them using Contractum languague.&#x20;

LNP/BP Standards Association maintains [registry of the schemata](https://github.com/RGB-WG/schemata), however any other body may create an independent registry, so multiple registries may co-exist. The process of adding an implementation to the LNP/BP registry is very simple: just submit a PR request providing all necessary information about your schemata.

Using schemata, the development of actual smart contracts require no coders and conding: it comes down to the selection of a schema (or multiple schemata) which the contract must confirm to - and filling in the data specific to that schemata in pretty much the same way as filling in paper forms. This is done with some data-oriented languagues, like JSON, YAML, XML - or using some user interface tools supplied by LNP/BP Association or independent companies for existing schemata types (like fungible asstets, NFTs, identity etc).

