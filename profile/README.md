# 🎴 Marketplate Labs 

## Introduction

We are currently building 2 projects.
- Marketplate
- 2.54NFT Marketplace

# 🧱 Marketplate

## Boilerplate for in-game marketplaces

Decrease web3 engineering costs. Focus on what you do best: the
game.

### Summary

Marketplate Labs is building a modular boilerplate that allows game devs to easily bootstrap
the skeleton of a NFT marketplace with decentralized off-chain
orderbook. The modular design enables the end-developer to
customize the business logic of the template or to plug their
own modules. Supported modules will include settlement,
liquidity and storage layers.

### Problem

Game devs are forced to reinvent the wheel when implementing
web3 logic. In the context of NFT marketplaces this causes:

1) Lack of standardization of different NFT marketplace models
as every implementation is different (different API schemas
etc.).
2) Lack of standardization causes lack of interoperability and
fragmentation of the NFT market liquidity.
3) Game devs are not blockchain devs. Increases likelihood of
bugs and negatively affects the liquidity.

### Solution

It decreases the engineering effort of bootstrapping an in-game NFT
marketplace, hence enabling game devs to work on their core
product. Furthermore, the adoption of 'marketplace factory' would
help to standardize the different models of NFT marketplaces and
their APIs.

### Getting started

The SDK can be imported as a library which allows easy interface,
and provides a standardized API to query essential on-chain data and
different off-chain orderbooks and storage layers. Alternatively, it can
be used as a CLI or as an open-source template to bootstrap a
fullstack NFT marketplace template.

### FAQs

What chains are supported out-of-the-box?
- The immediate focus is to be EVM-chains compatible. The
longer-term focus would be to make it compatible with the
broader ecosystem of different execution layers.
 
What can you use this NFT marketplace boilerplate for?
- Games of any sizes
- Personal projects
 
What problem does it solve?
- No need to build a marketplace from scratch! Our pre-built
templates allow you to have your tailored in-game
marketplace up and running right away in just a few simple
steps.

Are the contracts secured?
- Contracts are audited.
- Follows best security practice.

How feasible is it to integrate the SDK to my game?
- Connect easily and integrate powerful contracts into your
games with JavaScript, TypeScript, Go,...

### Internal FAQs

How much does it cost to use the boilerplate?
- There is no cost to use the Marketplate Labs at this point
 
How to verify my contracts?
- Prebuilt contracts are automatically verified.

How do we prevent liquidity segregation?
- We use API endpoints and SDKs to aggregate NFT
orders from across the Ethereum ecosystem to make
liquidity available.

How do we decentralize an off-chain orderbook?
- We will use a P2P network of nodes sharing the signed
order

### Product Roadmap

- [ ] Arbitrary chain support

----

# 🦄 2.54NFT Marketplace

## NFT Marketplace powered by the 1inch Limit Order Protocol 

The most innovative and flexible limit order functionality now for NFTs.

### Summary

2.54NFT marketplace utilizes the 1inch Limit Order Protocol (LOP) to give participants an advanced trading experience. On the other hand, our order book is aggregated from marketplaces across many ecosystems, providing traders with a rich and lively NFT marketplace. 

### Problem

1) Current NFT Marketplaces only support Buy, Sell, and Offer features without the more advanced trading strategies.
2) Current NFT marketplaces provide poor support for gas optimizations and off-chain signatures.
3) NFT Marketplaces face a lack of liquidity.

### Solution

- 1inch LOP allows Conditional Orders and P2P trading for flexibility and maximum profit from trading operations.
- The 1inch LOP charges no fees for supported tokens via the support of off-chain signatures (i.e. via NFTs that support ERC4494)
- 2.54NFT is multi-chain with orders coming from a variety of marketplaces across the ecosystem and no-fee P2P trading. Traders can also explore orders in the 1inch LOP.

### FAQs

What chains are currently supported?
- The immediate focus is to be EVM-chains compatible. The longer-term focus would be to make it compatible with the broader ecosystem of different execution layers.

Is 2.54NFT Marketplace open-sourced?
- 2.54NFT Marketplace is built on top of our Marketplate Labs product, which is a boilerplate for NFT marketplace. Now the users can build their own NFT marketplace for their NFT drop, collection, or in-game NFT marketplace with the built-in Limit Order Protocol from 1inch.

Is 2.54NFT Marketplace sustainable?
- 1inch LOP powerful API supports creating sell orders with zero gas and it charges no fee, making it extremely efficient in terms of gas.

How do we solve the NFT liquidity problem?
- 1inch LOP allows P2P orders, which could increase liquidity
- Orders are aggregated from many marketplaces
 
  - OpenSea
  - LooksRare
  - X2Y2
  - Sudoswap

Is the off-chain order book decentralized?
- We use a P2P network of nodes sharing the signed orders via decentralized storage settlement.
 
What is the 2.54NFT Marketplace fee structure?
- 2.54NFT charges no fee to trade at this point.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
