---
id: info
name:Info
---
### **Payment-Channel Network for Ethereum**

Raiden is a technology that leverages off-chain state networks to extend Ethereum with some nice properties for asset transfers:

* **Scalable**: it scales linearly with the number of participants (1,000,000+ transfers per second possible)
* **Fast**: Transfers are confirmed and final within the fraction of a second
* **Confidential**: Single transfers don’t show up in the global shared ledger
* **Interoperable**: Works with any token that follows Ethereum's standardized token API
* **Low Fees**: Transaction fees can be 7 orders of magnitude lower than on the blockchain
* **Micro-payments**: Low transaction fees allow to efficiently transfer tiny values

## Technology

The technology enabling this is similar to the proposed Bitcoin [Lightning Network](https://lightning.network/). 

The basic idea is to switch from a model where all transactions hit the shared ledger on the blockchain (which is the bottleneck) to a model where users can privately exchange messages which sign the transfer of value. 

Raiden uses a network of p2p payment channels and deposits in Ethereum to preserve the guarantees expected from a blockchain system.

Raiden is implemented as an extension to Ethereum. A Raiden nodes runs alongside an Ethereum node and communicates with other Raiden nodes to facilitate transfers and with the Ethereum blockchain to manage deposits. It offers a simple API which makes it easy use Raiden in DApps. 

## Applications

* Micropayments for *content distribution*: Alternative to Paywalls, Ads and  Subscrptions. (Figure a decentralized youtube where the creators of a video are payed for every second watched)
* Decentralized *M2M* markets: especially in *IoT* where tiny chunks of bandwidth, storage, cpu time, energy, sensor data, etc. can be traded.
* Frictionless *Token Systems*: Game Tokens, Reward Tokens, Private Currencies 
* API Access: Accessing and monetizing APIs on a per use basis is at the core of the upcoming Machine-to-Machine economy
* Fast Decentralized Exchanges

## Complementary to Ethereum

Vitalik Buterin: "State channels are an important technology that has the potential to greatly improve the scalability and privacy of many categories of blockchain applications; in conjunction with sharding and other privacy-preserving cryptographic technologies, they are an important ingredient in helping decentralized systems to achieve the properties that mainstream individual and institutional users expect and deserve." 


## Further reading

* [Coindesk feature on Raiden: "Will Ethereum Beat Bitcoin to Mainstream Microtransactions?"](http://www.coindesk.com/ethereum-bitcoin-mainstream-microtransactions/)
* [Robert McCone's blogpost about a lightning style network on Ethereum](http://www.arcturnus.com/ethereum-lightning-network-and-beyond/)

### Development

The technology is currently under development. An alpha version is to be released in Q3/2016. See our [GitHub repository](https://github.com/raiden-network/raiden).

[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg?maxAge=2592000?style=flat-square)](https://gitter.im/raiden-network/raiden)
