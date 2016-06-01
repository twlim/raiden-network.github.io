---
id: info
name:Info
---

A payment-channel implementation for the Ethereum network.

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/brainbot-com/raiden?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)




Raiden is a technology that leverages off-chain state networks to extend Ethereum with [some nice] properties for asset transfers:


* **Scalable**: it scales linearly with the number of participants (1,000,000+ transfers per second)
* **Fast**: Transfers are confirmed and final within the fraction of a second
* **Confidential**: Single transfers don’t show up in the global shared ledger
* **Interoperable**: Works with any token that follows Ethereum's standardized fungible API
* **Low Fees**: Transaction fees can be 5-7 orders of magnitude lower than on the blockchain
* **Micro/Nano/Pico-payments**: Low transaction fees allow to efficiently transfer tiny values

------



**All this is possible because participants are exchanging payment-promises off-chain, which are backed by locked security deposits on the blockchain. If there is a dispute, a smart contract pays out the locked funds according to the latest off-chain payment.**

This keeps Ethereum's transaction volume low and shifts transactions to a network that doesn't require a replicated database and consensus-securities. 

The Raiden technology will enable the Ethereum blockchain to become a payment solution that scales very well and therefore allowing  real world transaction volume and micropayments:

* *Imagine* a decentralized youtube where one pays the creators of a video for every second watched.

* *Imagine* decentralized trading of resources like energy, bandwidth or computational power.

* *Imagine* an instant payment system for the entire world - avoiding the centralization and high fees of current solutions.


Raiden is influenced by the proposed [Lightning Network](https://lightning.network/) for Bitcoin, but has some major differences:

* more flexibilty and shorter settlement times
* can be implemented on the current Ethereum protocol
* interoperable with any standardized token on the Ethereum blockchain
* **will be available in 2016**
