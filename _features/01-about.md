---
id: info
name:Info
---

A payment-channel implementation for the Ethereum network.

Raiden is a technology that leverages off-chain state networks to extend Ethereum with some nice properties for asset transfers:


* **Scalable**: it scales linearly with the number of participants (1,000,000+ transfers per second possible)
* **Fast**: Transfers are confirmed and final within the fraction of a second
* **Confidential**: Single transfers don’t show up in the global shared ledger
* **Interoperable**: Works with any token that follows Ethereum's standardized token API
* **Low Fees**: Transaction fees can be 5-7 orders of magnitude lower than on the blockchain
* **Micro-payments**: Low transaction fees allow to efficiently transfer tiny values

------

The technology enabling this is similar to the proposed Bitcoin [Lightning Network](https://lightning.network/) Network. 

The basic idea is to switch from a model where all transactions hit the shared ledger on the blockchain (which is the bottleneck) to a model where users can privately exchange messages which sign the transfer of value. 

Raiden uses a network of p2p payment channels and deposits in Ethereum to preserve the guarantees expected from a blockchain system.

Raiden is implemented as an extension to Ethereum which can easily be integrated in DApps. 

Areas of application are:
* Micropayments for *content distribution* (e.g. a decentralized youtube where one pays the creators of a video for every second watched.)
* Decentralized *M2M* markets especially in *IoT* where tiny chunks of bandwidth, storage, cpu time, energy, sensor data, etc. can be traded. 

Further reads:

* [Robert McCone's blogpost about a lightning network on Ethereuem](http://www.arcturnus.com/ethereum-lightning-network-and-beyond/)
* [Jehan Tremback's blogpost about payment channels](http://altheamesh.com/blog/universal-payment-channels)
* [ryepdx's StackExchange answer](http://ethereum.stackexchange.com/a/1648)



The technology is currently under development. See our [GitHub repository](https://github.com/raiden-network/raiden).

[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg?maxAge=2592000?style=flat-square)](https://gitter.im/raiden-network/raiden)
