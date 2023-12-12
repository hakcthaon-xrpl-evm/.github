# XRPL-EVM-Solvency 🚀  

## Overview 🌟  

XRPL-EVM-Solvency is an innovative project that allows users to seamlessly prove their ownership of native XRP and any other tokens and NFTs in the XRPL-EVM sidechain while prioritizing privacy and security. This groundbreaking solution leverages a sophisticated technology stack and our home made (Cypher Lab) ring signatures library (Alice's Ring) for secure ownership proofs, opening the door to a wide range of compelling use cases in the world of decentralized finance and privacy-preserving applications.  

## Repo

- [WebApp](https://github.com/hakcthaon-xrpl-evm/webApp)
- [Smart Contracts](https://github.com/hakcthaon-xrpl-evm/contracts)
- [API](https://github.com/hakcthaon-xrpl-evm/API) without Alice's Ring library (close sourced for now -> waiting for audit, it will be used for future initiatives)

## Table of Contents 📑

- [XRPL-EVM-Solvency 🚀](#xrpl-evm-solvency-)
  - [Overview 🌟](#overview-)
  - [Repo](#repo)
  - [Table of Contents 📑](#table-of-contents-)
  - [Ideas ✨](#ideas-)
  - [Usage 📈](#usage-)
  - [Technical Details 🛠️](#technical-details-️)
  - [Security and Privacy 🔐](#security-and-privacy-)
  - [Use Cases 🌐](#use-cases-)
  - [Useful ressources 📜](#useful-ressources-)
  - [Note](#note)

## Ideas ✨  

- **Collateral for DeFi Loans:** Prove your token holdings for decentralized loans on EVM without compromising security or exposing wallet addresses.  
- **Enhanced Privacy:** Safeguard user privacy by utilizing ring signatures and encryption techniques.   
- **Tokenization:** Mint tokenized versions of BTC,XRP on EVM, such as Wrapped BTC (WBTC) or (WXRP), without intermediaries.  
- **Future:** Explore various applications, including credit scoring, cross-chain financial products, privacy-preserving wealth management, and more.  

## Usage 📈

To use the XRPL-EVM-Solvency, you can directly interact with our [WebApp](http://89.58.41.130:4051/) (TEST -> HTTP):  


## Technical Details 🛠️

The XRPL-EVM-Solvency relies on a comprehensive technology stack:

- **Privacy-Preserving Ownership Proofs:** Ring signatures, based on our homemade solution [Alice's Ring](https://www.cypherlab.fr/alices-ring) enable users to prove XRP and any other token (ERC20/NFTs) ownership without revealing specific wallet addresses, preserving user's privacy.
- **Highly Scalable and Efficient Ring Signature Protocol:** We leverage a highly scalable and efficient ring signature protocol, Alice's Ring, to ensure that users can prove their assets ownership on chain without compromising security.
- **High decentralization:** The XRPL-EVM-Solvency is built on top of the XRPL-EVM sidechain, it only uses decentralized tools. This ensures that the system is not controlled by a single entity and that users can interact with the system in a trustless manner for free.
- **Smart Contracts:** The smart contracts are deployed on the XRPL-EVM sidechain, they are written in Solidity. They are used to verify and store the ownership proofs.

## Security and Privacy 🔐

Security and privacy are paramount in the Cro on Ethereum project:

- **User Data Protection:** All user data, including asset holdings, wallet addresses, and transaction histories, are kept confidential.
- **Privacy-Preserving Techniques:** Ring signatures and encryption ensure that users can prove their assets ownership on chain without exposing their other chain's wallet addresses.

## Use Cases 🌐  

- **Collateral for DeFi Loans:** Users can prove their XRP and token holdings to secure decentralized loans on EVM chains without compromising security.
- **Credit Scoring and Underwriting:** Decentralized credit systems can assess user creditworthiness without revealing identities.
- **Cross-Chain Financial Products:** Users can participate in Ethereum-based financial instruments like staking, yield farming, or liquidity pools.
- **Proof of Reserves for Exchanges:** Cryptocurrency exchanges can transparently prove Bitcoin reserves to Ethereum users.
- **Privacy-Preserving Wealth Management:** Users can manage wealth across blockchains without exposing total holdings or transactions.
- **Atomic Swaps:** Trustless atomic swaps between BTC, XRP and ETH or other Ethereum-based assets are facilitated.
- **Participation in DAOs:** Users can prove XRP and token holdings to participate in DAOs without revealing real-world identities.
- **Tokenized non-EVM assets on Ethereum:** Users can mint tokenized versions of BTC, MATIC, AVAX & XRP on EVM, potentially without intermediaries.
- **Voting Rights in DeFi Protocols:** Proof of XRP and token holdings can allocate voting rights in Ethereum-based DeFi protocols.
- **Enhanced Privacy for BTC and XRP Holders:** BTC/XRP holders can interact with the Ethereum ecosystem without revealing Bitcoin addresses.
- **Cross-Chain Reputation Systems:** Users can build financial reputations on EVM platforms by proving their XRP and token holdings.

## Useful ressources 📜

- **Litepaper:** You can find our litepaper [here](https://github.com/hakcthaon-xrpl-evm/.github/blob/main/XRPL%2BEVM%2BSolvency.pdf)
- [*Alice's Ring, ring signature protocol*](https://www.cypherlab.fr/alices-ring)

## Note

This project was concurrently developed for two hackathons that occurred simultaneously. Here is the tailored version for the XRPL-EVM hackathon and the other is designed for the Chainlink - Constellation hackathon (https://github.com/hack-chainlink).
