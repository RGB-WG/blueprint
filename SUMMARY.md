# Table of contents

* [Introduction](README.md)

## Design

* [Design goals](design/goals.md)
* [Design approaches](design/approach.md)
* [Protocol overview](design/overview.md)

## Consensus level

* [Data encoding & commitments](consensus-level/data-encoding-and-commitments.md)
* [Anchoring](consensus-level/anchoring/README.md)
  * [Bitcoin consensus](consensus-level/anchoring/bitcoin-consensus.md)
  * [Deterministic bitcoin commitments](consensus-level/anchoring/deterministic-bitcoin-commitments.md)
  * [Single-use-seals](consensus-level/anchoring/single-use-seals.md)
  * [Bundling](consensus-level/anchoring/bundling.md)
* [Schema](consensus-level/schema/README.md)
  * [Data types](consensus-level/schema/data-types.md)
  * [State](consensus-level/schema/state.md)
  * [Operations](consensus-level/schema/operations.md)
  * [Interfaces](consensus-level/schema/interfaces.md)
  * [Schema hierarchy](consensus-level/schema/schema-hierarchy.md)
  * [Scripting](consensus-level/schema/scripting.md)
* [Contract operations](consensus-level/contract-operations/README.md)
  * [Genesis](consensus-level/contract-operations/genesis.md)
  * [State transition](consensus-level/contract-operations/state-transition.md)
  * [State extensions](consensus-level/contract-operations/state-extensions.md)
* [System libraries](consensus-level/system-libraries.md)

## Application level

* [Invoices](application-level/invoices.md)
* [Working with PSBTs](application-level/working-with-psbts.md)
* [RGB containers](application-level/rgb-containers/README.md)
  * [Consignments](application-level/rgb-containers/consignments.md)
  * [Disclosures](application-level/rgb-containers/disclosures.md)
  * [Data attachments](application-level/rgb-containers/data-attachments.md)

## Main schemata

* [RGB20 fungible assets](main-schemata/rgb20-fungible-assets.md)
* [RGB21 NFT collectibles](main-schemata/rgb21-nft-collectibles.md)

## RGB & Lightning

* [Storm for RGB](rgb-and-lightning/storm-for-rgb/README.md)
  * [Ephemeral global state](rgb-and-lightning/storm-for-rgb/ephemeral-global-state.md)
  * [Asset information](rgb-and-lightning/storm-for-rgb/asset-information.md)
  * [Consignment propagation](rgb-and-lightning/storm-for-rgb/consignment-propagation.md)
  * [Attachments](rgb-and-lightning/storm-for-rgb/attachments.md)
* [Bifrost channels](rgb-and-lightning/bifrost-channels/README.md)
  * [State in channels](rgb-and-lightning/bifrost-channels/state-in-channels.md)
  * [Fungible state routing](rgb-and-lightning/bifrost-channels/fungible-state-routing.md)
* [Kaleidoscope: DEX](rgb-and-lightning/kaleidoscope-dex.md)
* [LN nodes running contracts](rgb-and-lightning/ln-nodes-running-contracts.md)

## Developing for RGB <a href="#devs" id="devs"></a>

* [Overview](devs/overview.md)
* [Schema development](devs/schema-development.md)
* [Breaking things](devs/breaking-things.md)
