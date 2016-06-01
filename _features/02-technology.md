---
id: technology
name: Technology
heading: Technology
image: "http://placehold.it/300x300"
---


### Technology

Raiden transactions happen outside of the Ethereum blockchain. A network of [payment channels](http://altheamesh.com/blog/universal-payment-channels) and hashlocks are leveraged to enable secure [multi hop payments](ladida) between participants that don’t have a direct payment channel. Every participant in a transfer can charge a small transaction fee. Deposits in smart contracts on the Ethereum chain secure that signed off-chain balances can be settled on-chain.

###### Payment Channels:

To start transferring assets off-chain, they have to be deposited as a security on the blockchain.
There, a smart contract holds the assets of the payment channel's two participants.
Assets can then be exchanged off-chain by exchanging cryptographically enforceable promises to update each others balance.
If one party decides to close the payment channel and claim it's assets on the blockchain, the smart-contract will handle any potential dispute and it will payout the assets according to the latest valid off-chain transaction.

###### Multi-hop payments
The Raiden-Network provides an infrastructure to link single payment-channels and create a network where transactions can be mediated to parties not connected via a direct payment-channel. To encourage other participants to mediate this *multi-hop payments*, they are allowed to charge a small amount of fees to compensate for the provision of liquidity.
