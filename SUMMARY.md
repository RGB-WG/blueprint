# Table of contents

* [Introduction](README.md)

## Design

* [Design goals](design/goals.md)
* [Design approaches](design/approach.md)
* [Protocol overview](design/overview.md)

## Consensus level

* [Data encoding & commitments](consensus/encoding.md)
* [Anchoring](consensus/anchoring.md)
  * [Bitcoin consensus](consensus/pow.md)
  * [Deterministic bitcoin commitments](consensus/dbc.md)
  * [Single-use-seals](consensus/seals.md)
  * [Bundling](consensus/bundles.md)
* [Schema](consensus/schema.md)
  * [Data types](consensus/schema-data.md)
  * [State](consensus/schema-state.md)
  * [Operations](consensus/schema-operations.md)
  * [Interfaces](consensus/schema-interfaces.md)
  * [Schema hierarchy](consensus/subschema.md)
  * [Scripting](consensus/scripting.md)
* [Contract operations](consensus/operations.md)
  * [Genesis](consensus/genesis.md)
  * [State transition](consensus/transitions.md)
  * [State extensions](consensus/extensions.md)

## Application level

* [Invoices](wallet/invoices.md)
* [Working with PSBTs](wallet/psbt.md)
* [RGB containers](wallet/containers.md)
  * [Consignments](wallet/consignments.md)
  * [Disclosures](wallet/disclosures.md)
  * [Data attachments](wallet/attachments.md)

## Main schemata

* [RGB20 fungible assets](schemata/rgb20.md)
* [RGB21 NFT collectibles](schemata/rgb21.md)

## RGB & Lightning

* [Storm for RGB](lightning/storm.md)
  * [Ephemeral global state](lightning/storm-state.md)
  * [Asset information](lightning/storm-assets.md)
  * [Consignment propagation](lightning/storm-consignments.md)
  * [Attachments](lightning/storm-attachments.md)
* [Bifrost channels](lightning/bifrost.md)
  * [State in channels](lightning/bifrost-state.md)
  * [Fungible state routing](lightning/bifrost-routing.md)
* [Kaleidoscope: DEX](lightning/dex.md)
* [LN nodes running contracts](lightning/node-contracts.md)

## Toolchain

* [Overview](toolchain/overview.md)
