# **Blockchain & Crypto**

## Introduction

Blockchain is a distributed ledger technology that records transactions between two parties. The ledger is shared among all the nodes in the network. To simplify this defination, let's break it down into these questions;

1. What is a distributed ledger?-
   A distributed ledger is a shared database that records transactions between two parties.
2. What is a node?-
   A node is a computer that is part of the network.

The purpose of a blockchain is to have a network of computers agree upon a common state of data. As easy as that.

#### Why is Blockchain needed for Cryptocurrency?

A cryptocurrency is a digital currency which serves as a medium of exchange through a computer network without a reliance on central authorities like banks or governments.
Trust has been the major issue with cryptocurrencies. The reason is that the majority of the cryptocurrencies are not backed by any government or bank.
In 2008, a system was been imagined by Satoshi Nakamoto, thereby releasing a bitcoin whitepaper(https://bitcoin.org/bitcoin.pdf). In this paper they described a system that would create a peer-to-peer network for exchanging value. This system would combine years of cryptographic research and game theoretical financial incentives to create a secure, scalable network. The paper describes a chain of blocks tied together cryptographically. This would later be coined the blockchain. Blockchain was invented to solve for **trust**.

## Cryptographic Hashes

A hash function is a function which takes an input of any size and turns it into a fixed size output. It takes an input of any size and returns a fixed 32 byte output. There are many different algorithms for hash functions which could take these inputs and create outputs of fixed sizes but we will focus on cryptographic hash functions. These hash functions need five specific properties:

- Deterministic - One specific input always maps to the same specific output
- Pseudorandom - It is not possible to guess the output based on the output of similar inputs
- One-way - If someone gives you a new output, you could not determine an input without guessing
- Fast to Compute - It must be a quick calculation for a computer
- Collision-resistant - The chance of a collision should be infinitesimally small

### Challenge

Use this tool at https://emn178.github.io/online-tools/sha256.html to generate the hash of any text you want. What do you observe?

With a secure cryptographic hash function you can create a unique, fixed-size representation of an input regardless of its size. For blockchains this feature is critically important for saving space.

## Digital Signatures(Cryptography)

## Mining & Proof of Work(Consensus Mechanism)

Consensus means coming to a general agreement. Blockchain consensus typically means at least 51% of nodes are in agreement over the current global state of the network. Consensus mechanisms end up simply being rules that a distributed + decentralized blockchain network follows in order to stay in agreement over what is considered valid.
Bitcoin being a blockchain network, use a consensus mechanism called proof-of-work. Ethereum was previously using proof of work but has since moved to proof-of-stake.

#### Mining
